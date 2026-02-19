# Aula 11 - Threads e Coroutines 🧵

---

## 🛑 O Bloqueio da UI
- Main Thread: Responsável pelo desenho (60fps).
- Nunca faça rede ou banco nela!
- **ANR**: O erro fatal que ninguém quer.

---

## ⚡ Kotlin Coroutines
- Programação assíncrona que parece síncrona.
- Ultra leves (economizam memória).
- `suspend fun`: Funções que podem pausar.

---

## 🚚 Dispatchers
- `Main`: Para UI.
- `IO`: Para Rede e Banco.
- `Default`: Para cálculos pesados.

---

## 🎯 Escopos e Vida
- `viewModelScope`: Morre junto com a tela.
- Cancelamento automático de tarefas.
- Segurança contra Memory Leaks.

---

## 🍎 Async / Await (iOS)
- iOS agora tem o `async / await` igual ao Kotlin.
- `Task` (Swift) == `launch` (Kotlin).
- Adeus ao inferno dos callbacks!