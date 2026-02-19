# Quiz 03 - Introdução ao Kotlin 💜

--8<-- "assets/quiz.html"

<div class="quiz-container">
  <div class="quiz-question">1. Qual palavra-chave declara uma variável imutável (constante) em Kotlin?</div>
  <div class="quiz-option" data-correct="true" data-feedback="✅ Correto! Value.">val</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Variable (mutável).">var</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Java/C#.">const</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Swift.">let</div>
  <div class="quiz-feedback"></div>
</div>

<div class="quiz-container">
  <div class="quiz-question">2. O que acontece se tentar: `val x = null`?</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto.">Compila normal</div>
  <div class="quiz-option" data-correct="true" data-feedback="✅ Correto! Kotlin exige tipagem explícita para null ou inferência de valor concreto.">Erro de compilação (Tipo não inferido corretamente)</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto.">x vira String</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto.">x vira 0</div>
  <div class="quiz-feedback"></div>
</div>

<div class="quiz-container">
  <div class="quiz-question">3. Qual símbolo define que um tipo **pode** ser nulo?</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto.">!</div>
  <div class="quiz-option" data-correct="true" data-feedback="✅ Correto! Ex: String?">?</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto.">*</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto.">&</div>
  <div class="quiz-feedback"></div>
</div>

<div class="quiz-container">
  <div class="quiz-question">4. O que faz o operador Elvis `?:`?</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto.">Cria uma classe</div>
  <div class="quiz-option" data-correct="true" data-feedback="✅ Correto! Se for null, usa o valor da direita.">Retorna um valor padrão se a expressão à esquerda for nula</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto.">Força o erro</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto.">Compara strings</div>
  <div class="quiz-feedback"></div>
</div>

<div class="quiz-container">
  <div class="quiz-question">5. Para criar classes que apenas guardam dados (POJOs), usamos:</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto.">class</div>
  <div class="quiz-option" data-correct="true" data-feedback="✅ Correto! Gera equals, hashCode, toString... em 1 linha.">data class</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto.">struct</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto.">object</div>
  <div class="quiz-feedback"></div>
</div>

<div class="quiz-container">
  <div class="quiz-question">6. Como se imprime no console em Kotlin?</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. (Java)">System.out.println()</div>
  <div class="quiz-option" data-correct="true" data-feedback="✅ Correto! Conciso.">println()</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto.">console.log()</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto.">echo</div>
  <div class="quiz-feedback"></div>
</div>

<div class="quiz-container">
  <div class="quiz-question">7. Kotlin é 100% interoperável com Java?</div>
  <div class="quiz-option" data-correct="true" data-feedback="✅ Correto! Pode chamar código Java no Kotlin e vice-versa.">Sim, totalmente</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto.">Não, só com Swift</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto.">Apenas em versões antigas</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto.">Sim, mas requer conversão manual de tudo</div>
  <div class="quiz-feedback"></div>
</div>

<div class="quiz-container">
  <div class="quiz-question">8. Qual a visibilidade padrão em Kotlin?</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto.">private</div>
  <div class="quiz-option" data-correct="true" data-feedback="✅ Correto! Diferente do Java (package-private).">public</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto.">internal</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto.">protected</div>
  <div class="quiz-feedback"></div>
</div>

<div class="quiz-container">
  <div class="quiz-question">9. O que significa `fun somar(a: Int, b: Int) = a + b`?</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto.">Função anônima</div>
  <div class="quiz-option" data-correct="true" data-feedback="✅ Correto! Clean code.">Single-Expression Function</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto.">Erro de sintaxe</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto.">Função recursiva</div>
  <div class="quiz-feedback"></div>
</div>

<div class="quiz-container">
  <div class="quiz-question">10. Para converter uma String "10" para Inteiro, usamos:</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto.">Integer.parseInt()</div>
  <div class="quiz-option" data-correct="true" data-feedback="✅ Correto! Função de extensão.">.toInt()</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto.">ParseInt()</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto.">Convert.ToInt32()</div>
  <div class="quiz-feedback"></div>
</div>
