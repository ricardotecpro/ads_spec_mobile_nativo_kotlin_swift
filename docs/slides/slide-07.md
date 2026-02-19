# Aula 07 - Arquitetura Moderna (MVVM) 🏗️

---

## 😵 O problema da "God Activity"
- Activities que fazem tudo (UI + Lógica + Banco).
- Difícil de testar.
- Difícil de manter.

---

## 🏗️ O Padrão MVVM
1.  **Model**: Dados e Lógica de Negócios.
2.  **View**: Activity/Fragment (Apenas mostra as coisas).
3.  **ViewModel**: O cérebro. Guarda o estado e se comunica com o Model.

---

## 🧠 ViewModel: A Vida Longa
- Sobrevive à rotação da tela!
- Não deve ter referências à View (evita Memory Leak).

---

## 📡 LiveData
- O dado "vivo".
- A View "observa" o LiveData.
- Quando o dado muda no ViewModel, a View atualiza sozinha.
- Respeita o Ciclo de Vida.

---

## 🍎 MVVM no Swift
- iOS usa muito MVVM com `Combine` ou `SwiftUI`.
- `State` e `ObservableObject` no SwiftUI são os primos do LiveData.