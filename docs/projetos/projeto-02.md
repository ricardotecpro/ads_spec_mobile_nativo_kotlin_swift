# Projeto 02 - Calculadora de IMC (Java) ☕

**Objetivo**: Praticar lógica de programação e tipos de dados usando Java no Android.

## O Desafio
1.  Crie um layout simples com dois `EditText` (Peso e Altura) e um `Button` (Calcular).
2.  No código Java, recupere os valores digitados.
3.  Calcule o IMC (Peso / Altura²).
4.  Exiba o resultado em um `TextView` e use um `Toast` para mostrar a classificação (Ex: "Peso Ideal", "Sobrepeso").

## Dica
Lembre-se de converter o texto do `EditText` para `Double` antes de calcular!
`double peso = Double.parseDouble(editPeso.getText().toString());`