# Exercícios 03 - Introdução ao Kotlin 💜

## 🟢 Fáceis

1.  **Conversão**: Converta o código Java abaixo para Kotlin.
    ```java
    final String fruta = "Maçã";
    int quantidade = 10;
    ```
2.  **Inferência**: O que acontece se eu tentar fazer isso em Kotlin? Por que?
    ```kotlin
    var nota = 10
    nota = "Dez"
    ```

## 🟡 Médios

3.  **Null Safety**:
    Você tem uma variável `var nome: String? = null`.
    Escreva um código que imprime o tamanho do nome SE ele não for nulo, e imprime "0" se for nulo, usando o operador **Elvis** (`?:`).
4.  **Funções**:
    Reescreva a função abaixo usando a sintaxe _Single-Expression_ (linha única).
    ```kotlin
    fun quadrado(x: Int): Int {
        return x * x
    }
    ```

## 🔴 Desafio

5.  **Data Classes e Cópia**:
    *   Crie uma `data class Celular(val marca: String, val modelo: String, val preco: Double)`.
    *   Instancie um "iPhone 14" de 5000 reais.
    *   Use o método `.copy()` para criar um novo celular igualzinho, mas mudando apenas o `modelo` para "iPhone 15" e o `preco` para 6000.
    *   Imprima os dois objetos.
