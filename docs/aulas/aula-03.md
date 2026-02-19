# Aula 03 - Introdução ao Kotlin 💜

!!! tip "Objetivo"
    **Objetivo**: Aprender Kotlin, a linguagem oficial do Android, e perceber como ela resolve os problemas do Java e se assemelha incrivelmente ao Swift.

---

## 1. Por que Kotlin? 🚀

Em 2017, o Google tornou o Kotlin oficial. Por quê?
*   **Conciso**: Menos código para fazer a mesma coisa.
*   **Seguro**: Null Safety integrado.
*   **Interoperável**: Funciona 100% com código Java existente.

> "Kotlin é o que o Java seria se tivesse sido criado hoje."

---

## 2. Sintaxe Básica: `var` vs `val` 📦

Esqueça o `String nome = ...`. O Kotlin infere os tipos!

*   **`var`**: Variável (pode mudar).
*   **`val`**: Valor (imutável - constante). **Use sempre que possível!**

```kotlin
var idade = 25
idade = 26 // OK

val nome = "Ricardo"
// nome = "João" // ERRO! Val cannot be reassigned
```

### 🆚 Comparação com Swift (iOS)

É idêntico! 😱

| Recurso | 💜 Kotlin | 🐦 Swift |
| :--- | :--- | :--- |
| Variável | `var x = 10` | `var x = 10` |
| Constante | `val y = 20` | `let y = 20` |
| Função | `fun somar() {}` | `func somar() {}` |
| Print | `println("Oi")` | `print("Oi")` |

---

## 3. Null Safety: Adeus NullPointerException 👋

No Kotlin, você precisa dizer explicitamente se uma variável aceita nulo.

```kotlin
var texto: String = "Não pode ser nulo"
// texto = null // Erro de compilação!

var textoNulo: String? = "Pode ser nulo"
textoNulo = null // OK
```

### Operadores Seguros

1.  **Safe Call (`?.`)**: Só chama se não for nulo.
    ```kotlin
    println(textoNulo?.length) // Imprime tamanho ou null, não quebra!
    ```

2.  **Elvis Operator (`?:`)**: Valor padrão se for nulo.
    ```kotlin
    val tamanho = textoNulo?.length ?: 0
    ```

---

## 4. Funções e Expressões 𝑓(𝑥)

```kotlin
// Forma tradicional
fun somar(a: Int, b: Int): Int {
    return a + b
}

// Single-Expression (One-liner)
fun somarCurto(a: Int, b: Int) = a + b
```

Use e abuse de _Single-Expression functions_ para deixar o código limpo.

---

## 5. Classes de Dados (Data Classes) 💾

Lembra da classe `Pessoa` da aula passada? Em Kotlin é uma linha:

```kotlin
data class Pessoa(val nome: String, val idade: Int)
```

O `data class` já gera automaticamente: `toString()`, `equals()`, `hashCode()` e `copy()`.

### 🆚 Comparação: Structs (Swift)

No iOS, usamos `struct` para dados leves, que é muito similar ao `data class`, mas passado por valor.

---

## 6. Exercício Interativo (Termynal) 💻

Vamos testar o REPL do Kotlin (ambiente de teste rápido). Imagine digitando isso no terminal:

```termynal
$ kotlinc
Welcome to Kotlin version 1.9.0 (JRE 17.0.8)
>>> val lista = listOf("Android", "iOS", "Web")
>>> lista.filter { it.length > 3 }
[Android, Web]
>>> quit
```

---

## 7. Extensions: O Poder do Kotlin 💪

Você pode adicionar funções a classes que você não criou (como `String` ou `Int`).

```kotlin
fun String.darOi() {
    println("Oi, $this!")
}

"Ricardo".darOi() // Imprime: Oi, Ricardo!
```

No **Swift**, isso se chama `extension` e funciona exatamente igual.

---

## 8. Desafio: Tradutor Java -> Kotlin 🔄

**Converta este código Java mentalmente:**

```java
String texto = null;
if (texto != null) {
    System.out.println(texto.toUpperCase());
} else {
    System.out.println("Vazio");
}
```

??? success "Resposta em Kotlin"
    ```kotlin
    val texto: String? = null
    println(texto?.uppercase() ?: "Vazio")
    ```

---

**Próxima Aula**: Agora que sabemos a linguagem, vamos entender o **Android**! [Estrutura de um App Android](./aula-04.md) 📱