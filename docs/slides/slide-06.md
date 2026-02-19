# Aula 06 - Navegação e Intents 🗺️

---

## 🚀 O que é uma Intent?
- O "mensageiro" do Android.
- Solicita uma ação de outro componente.
- **Explícita**: Abre uma Activity específica.
- **Implícita**: Pede ao sistema (abrir link, câmera).

---

## 📩 Passando Dados
- Usamos `putExtra(chave, valor)`.
- Na outra tela, recuperamos com `intent.get...Extra("chave")`.
- **Dica**: Use nomes de chaves constantes.

---

## 🥞 A Pilha de Telas (Back Stack)
- Funciona como uma pilha (LIFO).
- Nova Activity = Push.
- Botão Voltar = Pop.
- `finish()`: Fecha a tela atual.

---

## 🏁 Ciclo de Vida na Navegação
- `onPause()` -> `onStop()` (quando a tela sai de vista).
- `onRestart()` -> `onStart()` -> `onResume()` (ao voltar).

---

## 🍎 Segues e Coordinators (iOS)
- No iOS, a navegação é feita via `Segues` ou `UINavigationController`.
- O conceito de pilha é idêntico.