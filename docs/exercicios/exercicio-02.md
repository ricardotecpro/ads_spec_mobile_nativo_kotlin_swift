# Exercícios 02 - Fundamentos Java ☕

## 🟢 Fáceis

1.  **Classe Simples**: Crie uma classe `Livro` com atributos `titulo` e `autor`. Adicione um construtor.
2.  **Tipos**: Qual a diferença entre `int` e `Integer`? Dê um exemplo de quando usar cada um.

## 🟡 Médios

3.  **Herança**:
    *   Crie uma classe `Animal` com método `emitirSom()`.
    *   Crie classes filhas `Cachorro` e `Gato` que sobrescrevem (`override`) esse método.
4.  **Correção de Código**:
    O código abaixo dá erro. Por que? Corrija.
    ```java
    public class Teste {
        public void main(String[] args) {
            System.out.println("Oi");
        }
    }
    ```
    *(Dica: Faltou uma palavra mágica no método).*

## 🔴 Desafio

5.  **Polimorfismo e Listas**:
    *   Crie uma `ArrayList<Animal>` (da questão 3).
    *   Adicione um cachorro e um gato na lista.
    *   Use um `for` para percorrer a lista e chamar `emitirSom()` de cada um.
    *   Explique por que o Java sabe qual som emitir em tempo de execução.
