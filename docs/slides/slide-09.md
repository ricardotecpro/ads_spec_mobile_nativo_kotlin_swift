# Aula 09 - Listas Eficientes 📋

---

## 🐢 O Problema da ListView
- Carrega todos os itens de uma vez.
- Trava a UI em listas longas.
- Consumo alto de RAM.

---

## ♻️ RecyclerView (O Reciclador)
- Reaproveita as Views que saem da tela.
- Cria apenas o necessário para preencher a visão.
- Fluidez máxima.

---

## 🛠️ O Trio de Ferro
1.  **LayoutManager**: Como organizar os itens? (Linear, Grid).
2.  **Adapter**: Quem coloca o dado na View?
3.  **ViewHolder**: Quem guarda as referências da View?

---

## 🚀 ListAdapter e DiffUtil
- Identifica o que mudou na lista.
- Atualiza apenas o item específico.
- Animações automáticas e performance de ponta.

---

## 🍎 UITableView (iOS)
- No iOS, usamos `UITableView` ou `UICollectionView`.
- O padrão de "Cells" recicladas é o mesmo.
- `onBindViewHolder` (Android) == `cellForRowAt` (iOS).