# Quiz 11 - Threads e Async 🧵

--8<-- "assets/quiz.html"

<div class="quiz-container">
  <div class="quiz-question">1. O que é ANR?</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto.">Android New Release</div>
  <div class="quiz-option" data-correct="true" data-feedback="✅ Correto! O app travou.">Application Not Responding (Aplicativo Não Respondendo)</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto.">Animation Render</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto.">Async Network Request</div>
  <div class="quiz-feedback"></div>
</div>

<div class="quiz-container">
  <div class="quiz-question">2. A Main Thread também é conhecida como:</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto.">Background Thread</div>
  <div class="quiz-option" data-correct="true" data-feedback="✅ Correto!">UI Thread (Thread de Interface)</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto.">Worker Thread</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto.">Network Thread</div>
  <div class="quiz-feedback"></div>
</div>

<div class="quiz-container">
  <div class="quiz-question">3. O que é uma Coroutine em Kotlin?</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto.">Uma Thread pesada</div>
  <div class="quiz-option" data-correct="true" data-feedback="✅ Correto! Threads leves.">Um mecanismo de concorrência leve (Light-weight Threads)</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto.">Uma função recursiva</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto.">Um tipo de variável</div>
  <div class="quiz-feedback"></div>
</div>

<div class="quiz-container">
  <div class="quiz-question">4. Qual Dispatcher é ideal para fazer cálculos matemáticos pesados ou processar listas gigantes?</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Leitura de disco/rede.">Dispatchers.IO</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Apenas UI.">Dispatchers.Main</div>
  <div class="quiz-option" data-correct="true" data-feedback="✅ Correto! CPU intensive.">Dispatchers.Default</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto.">Dispatchers.Unconfined</div>
  <div class="quiz-feedback"></div>
</div>

<div class="quiz-container">
  <div class="quiz-question">5. A palavra-chave `suspend` indica que:</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto.">A função vai travar a thread</div>
  <div class="quiz-option" data-correct="true" data-feedback="✅ Correto! Sem bloquear a thread.">A função pode ser pausada e retomada posteriormente</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto.">A função foi cancelada</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto.">A função é deprecated</div>
  <div class="quiz-feedback"></div>
</div>

<div class="quiz-container">
  <div class="quiz-question">6. O que acontece se chamarmos `Thread.sleep(5000)` na Main Thread?</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto.">O app espera e depois continua normal</div>
  <div class="quiz-option" data-correct="true" data-feedback="✅ Correto! Congelamento total.">A tela congela por 5s e pode dar ANR</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto.">Nada, o Android gerencia</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto.">Roda em background</div>
  <div class="quiz-feedback"></div>
</div>

<div class="quiz-container">
  <div class="quiz-question">7. Qual o escopo de Coroutine atrelado ao ciclo de vida do ViewModel?</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto.">GlobalScope</div>
  <div class="quiz-option" data-correct="true" data-feedback="✅ Correto!">viewModelScope</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto.">LifecycleScope</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto.">MainScope</div>
  <div class="quiz-feedback"></div>
</div>

<div class="quiz-container">
  <div class="quiz-question">8. Qual a alternativa moderna no Swift (iOS) que se assemelha às Coroutines?</div>
  <div class="quiz-option" data-correct="true" data-feedback="✅ Correto!">Async / Await</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto.">GCD (Grand Central Dispatch)</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto.">Threads manuais</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto.">PerformSelector</div>
  <div class="quiz-feedback"></div>
</div>

<div class="quiz-container">
  <div class="quiz-question">9. Qual função usamos para trocar de thread dentro de uma Coroutine (ex: ir para IO e voltar)?</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto.">changeThread()</div>
  <div class="quiz-option" data-correct="true" data-feedback="✅ Correto!">withContext()</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto.">runOnUi()</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto.">switch()</div>
  <div class="quiz-feedback"></div>
</div>

<div class="quiz-container">
  <div class="quiz-question">10. Uma função `suspend` pode ser chamada de:</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto.">Qualquer lugar (função Java comum)</div>
  <div class="quiz-option" data-correct="true" data-feedback="✅ Correto!">Apenas de outra função suspend ou de um Scopo de Coroutine</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto.">Apenas do XML</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto.">Apenas do Construtor</div>
  <div class="quiz-feedback"></div>
</div>
