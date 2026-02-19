# Aula 11 - Threads e Assincronismo (Coroutines) 🧵

!!! tip "Objetivo"
    **Objetivo**: Entender o conceito de Main Thread vs Background Thread, o erro ANR, e como programar de forma assíncrona simples e poderosa usando Kotlin Coroutines.

---

## 1. O Bloqueio da UI (ANR) 🛑

O Android desenha a tela a cada 16ms (60fps). Tudo isso acontece na **Main Thread** (Thread Principal).
Se você colocar um código que demora 5 segundos na Main Thread (ex: baixar imagem, ler banco pesado):
1.  A tela congela.
2.  O usuário clica e nada acontece.
3.  O Android exibe o **ANR** (Application Not Responding) e fecha seu app.

> **Regra Suprema**: Operações pesadas (IO, Rede, Banco) **SEMPRE** em Background.

---

## 2. O Passado: Callbacks Hell e Asynctask 🕸️

Antigamente, usávamos `AsyncTask` ou Callbacks aninhados.
```java
// Código Java antigo (Pesadelo)
api.getUser(new Callback() {
    onSuccess(user) {
        api.getPosts(user.id, new Callback() {
            onSuccess(posts) {
                // ... pirâmide de chaves ...
            }
        })
    }
})
```

---

## 3. O Futuro: Kotlin Coroutines ⚡

Coroutines permitem escrever código assíncrono como se fosse sequencial. É mágica pura.

*   **suspend fun**: Uma função que pode ser "pausada" e retomada depois, sem bloquear a thread.
*   **Scope**: O escopo de vida da coroutine (ex: morreu a tela, cancela o download).
*   **Dispatcher**: Define em qual thread vai rodar.

### Dispatchers (Os entregadores)
*   `Dispatchers.Main`: Thread Principal (Atualizar UI).
*   `Dispatchers.IO`: Input/Output (Rede, Banco, Arquivos).
*   `Dispatchers.Default`: Processamento pesado de CPU (Cálculos, Listas gigantes).

---

## 4. Na Prática 👩‍💻

```kotlin
// ViewModelScope: Já vem pronto no ViewModel
fun realizarLogin() {
    viewModelScope.launch { // Inicia a coroutine na Main Thread
        
        exibirLoading(true) // UI: Main
        
        // withContext: Troca para thread de IO e PAUSA a execução aqui (sem travar)
        val resultado = withContext(Dispatchers.IO) {
            api.fazerLoginDemorado() // Roda em background
        }
        
        // Quando voltar, já estamos na Main de novo automaticamente!
        exibirLoading(false)
        tratarResultado(resultado)
    }
}
```

Olhe como a leitura é linear! Não tem `onSuccess`, não tem callback.

### 🆚 Comparação: Swift Concurrency (Async/Await)
O iOS adotou recentemente o `async / await`, que é **muito** parecido com Coroutines.
*   Kotlin: `suspend fun` / `viewModelScope.launch`
*   Swift: `async func` / `Task { await ... }`

---

## 5. Jobs e Cancelamento 🚫

Uma das maiores vantagens. Se o usuário sair da tela no meio do download:
1.  O `ViewModel` morre (`onCleared`).
2.  O `viewModelScope` é cancelado automaticamente.
3.  A requisição de rede é abortada.
4.  Nenhum crash acontece por tentar atualizar uma tela que não existe mais.

---

## 6. Desafio: Simulador de Corrida 🏎️

Crie uma função `suspend fun corrida()` que:
1.  Imprima "Preparar..."
2.  Espere 1 segundo (`delay(1000)` - nota: `delay` não trava a thread, `Thread.sleep` trava!).
3.  Imprima "Apontar..."
4.  Espere 1 segundo.
5.  Imprima "JÁ!"
6.  Chame essa função a partir de um botão e veja se a UI continua responsiva (se o botão clica) durante a contagem.

---

**Próxima Aula**: Agora que o app funciona, vamos deixá-lo incrível? [UX, Material Design e Animações](./aula-12.md) 🎨