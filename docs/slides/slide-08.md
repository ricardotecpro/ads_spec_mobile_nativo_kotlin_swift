# Aula 08 - Persistência de Dados 💾

---

## 📂 Opções de Armazenamento
1.  **SharedPreferences**: Chaves e valores simples (Configurações).
2.  **Room (SQLite)**: Banco de dados estruturado.
3.  **Arquivos**: Fotos, textos longos.

---

## 🏢 Room Database
- Abstração poderosa sobre o SQLite.
- **Entity**: Tabela.
- **DAO**: Métodos de acesso (SQL).
- **Database**: O ponto de conexão.

---

## 🧵 Threads e Banco de Dados
- **PROIBIDO** acessar banco na Main Thread!
- Use Coroutines ou threads separadas.
- O Room obriga isso por padrão.

---

## 🛠️ Migrations
- O que fazer quando o banco muda?
- Controle de versão do esquema.
- Evite o crash na atualização.

---

## 🍎 Core Data e SwiftData (iOS)
- iOS usa `Core Data` (equivalente ao Room).
- Recentemente lançou o `SwiftData` (mais simples e moderno).
- Ambos focam em persistir objetos locais.