# Aula 04 - Estrutura de um App Android 🧱

---

## 📂 Anatomia do Projeto
- **manifests/**: `AndroidManifest.xml`.
- **java/** (ou kotlin/): Código fonte.
- **res/**: Recursos (Layouts, Imagens, Strings).

---

## 📝 O Manifesto
- O "RG" do aplicativo.
- Declara Permissões.
- Declara Telas (Activities).
- Define o ícone e tema.

---

## 🖼️ Recursos (Resources)
- `layout/`: Arquivos XML de interface.
- `drawable/`: Imagens e vetores.
- `values/`: Strings, Cores, Dimensões.
- **Dica**: Nunca use texto fixo no XML, use `strings.xml`.

---

## 🐘 Gradle: O Motor de Busca
- Gerenciador de dependências.
- Configura o SDK e versões.
- `build.gradle` (Project vs Module).

---

## 🏗️ Activities
- Uma tela = Uma `Activity`.
- Ciclo de Vida: `onCreate`, `onStart`, `onResume`...
- Conexão código-interface (ViewBinding).