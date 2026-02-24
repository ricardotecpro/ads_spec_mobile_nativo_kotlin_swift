# Aula: Java e JDK ☕
## O Coração do Ecossistema Android

O Java Development Kit (JDK) é o kit essencial para compilar e rodar aplicativos Java e a base para o desenvolvimento Kotlin.

---

## 1. JDK (Java Development Kit) 🏗️

O JDK fornece as ferramentas e bibliotecas necessárias para transformar seu código fonte em bytecode.

### Fluxo de Desenvolvimento 📊

```mermaid
graph LR
    A[Código .java] --> B[Compilador javac]
    B --> C[Bytecode .class]
    C --> D[JVM - Qualquer OS]
```

1.  Baixe o **JDK 17 LTS (ou 21 LTS)** no site da Oracle ou Adoptium.
2.  Instale e configure a variável de ambiente `JAVA_HOME`.

!!! concept "Conceito: Write Once, Run Anywhere"
    A grande vantagem do Java é a Máquina Virtual (JVM). Você escreve o código uma vez e ele roda em qualquer hardware que tenha uma JVM instalada.

---

## 2. Na Prática: Verificando o Ambiente 💻

<div class="termy" data-termynal>
    <span data-ty="input">java -version</span>
    <span data-ty="output">openjdk version "17.0.x" 202x-xx-xx</span>
    <span data-ty="input">javac -version</span>
    <span data-ty="output">javac 17.0.x</span>
    <span data-ty="output">🚀 Java configurado com sucesso!</span>
</div>

---

## 3. IDEs: IntelliJ vs. VS Code 💻

*   **IntelliJ IDEA:** A melhor experiência para Java/Kotlin (versão Community é gratuita).
*   **VS Code:** Leve e rápido, excelente para acadêmicos e projetos menores.

!!! tip "Dica: JAVA_HOME"
    Muitas ferramentas (como o Android Studio) precisam que o `JAVA_HOME` esteja apontando para a pasta raiz do seu JDK instalado.

---

## 📝 Exercícios Progressivos

1.  **Nível 1:** Qual a diferença entre o **JRE** (Java Runtime Environment) e o **JDK**?
2.  **Nível 2:** Por que é importante configurar a variável de ambiente `JAVA_HOME`?
3.  **Nível 3:** Explique como o conceito de **Bytecode** ajuda na portabilidade de aplicativos entre diferentes sistemas operacionais.

---

## 🚀 Mini-Projeto: OlaMundo Mobile

**Objetivo:** Compilar e rodar seu primeiro programa Java via terminal.

*   **Tarefa 1:** Criar um arquivo `OlaMundo.java`.
*   **Tarefa 2:** Compilar usando `javac OlaMundo.java`.
*   **Tarefa 3:** Rodar usando `java OlaMundo` e observar a saída.

---

[Ir para próxima aula: Do Silício ao Software :octicons-arrow-right-24:](setup-05.md)