# Quiz 07 - Arquitetura MVVM 🏗️

--8<-- "assets/quiz.html"

<div class="quiz-container">
  <div class="quiz-question">1. O que significa a sigla MVVM?</div>
  <div class="quiz-option" data-correct="true" data-feedback="✅ Correto!">Model - View - ViewModel</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto.">Model - View - ViewMap</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto.">Mobile - View - VirtualMachine</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto.">Main - View - VisualModel</div>
  <div class="quiz-feedback"></div>
</div>

<div class="quiz-container">
  <div class="quiz-question">2. No MVVM, quem deve conter a lógica de negócios e estado da tela?</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. A View é "burra".">A View (Activity)</div>
  <div class="quiz-option" data-correct="true" data-feedback="✅ Correto! É o cérebro.">O ViewModel</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto.">O XML</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto.">O Adapter</div>
  <div class="quiz-feedback"></div>
</div>

<div class="quiz-container">
  <div class="quiz-question">3. Qual o principal benefício do ViewModel em relação à rotação de tela?</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. ViewModel não desenha.">Ele rotaciona junto com a tela automaticamente</div>
  <div class="quiz-option" data-correct="true" data-feedback="✅ Correto! Ele sobrevive à destruição da Activity.">Ele não é destruído quando a Activity é recriada</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto.">Ele impede a rotação da tela</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto.">Ele formata o layout</div>
  <div class="quiz-feedback"></div>
</div>

<div class="quiz-container">
  <div class="quiz-question">4. O que é `LiveData`?</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto.">Um banco de dados em tempo real</div>
  <div class="quiz-option" data-correct="true" data-feedback="✅ Correto! Observável e ciente do ciclo de vida.">Um container de dados observável que respeita o ciclo de vida</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto.">Uma thread separada</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto.">Um plugin de vídeo</div>
  <div class="quiz-feedback"></div>
</div>

<div class="quiz-container">
  <div class="quiz-question">5. A View (Activity) deve ter uma referência direta ao Model (Banco/API)?</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Isso viola a separação.">Sim, para ser mais rápido</div>
  <div class="quiz-option" data-correct="true" data-feedback="✅ Correto! Quem fala com o Model é o ViewModel.">Não, ela deve falar apenas com o ViewModel</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto.">Depende do tamanho do app</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto.">Sim, mas só para leitura</div>
  <div class="quiz-feedback"></div>
</div>

<div class="quiz-container">
  <div class="quiz-question">6. Qual o problema da "God Activity" (Activity Deus)?</div>
  <div class="quiz-option" data-correct="true" data-feedback="✅ Correto! Difícil de manter e testar.">Classe gigante que faz tudo (UI, Lógica, Banco)</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto.">Ter muitas Activities no projeto</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto.">Usar nomes religiosos no código</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto.">Uma Activity que não fecha</div>
  <div class="quiz-feedback"></div>
</div>

<div class="quiz-container">
  <div class="quiz-question">7. Como a Activity recebe atualizações do ViewModel?</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto.">Polling (perguntando toda hora)</div>
  <div class="quiz-option" data-correct="true" data-feedback="✅ Correto! Padrão Observer.">Observando (observing) o LiveData</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto.">Recebendo um callback via Interface Java</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto.">Via BroadcastReceiver</div>
  <div class="quiz-feedback"></div>
</div>

<div class="quiz-container">
  <div class="quiz-question">8. É uma boa prática passar Contexto (Activity) para o ViewModel?</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Isso causa Memory Leak! Ja que o ViewModel vive mais que a Activity.">Sim, sem problemas</div>
  <div class="quiz-option" data-correct="true" data-feedback="✅ Correto! ViewModel não deve referenciar View/Context.">Não, pois pode causar vazamento de memória (Memory Leak)</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto.">Sim, se for SoftReference</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto.">Depende da versão do Android</div>
  <div class="quiz-feedback"></div>
</div>

<div class="quiz-container">
  <div class="quiz-question">9. Qual a camada responsável por fornecer dados (Repository)?</div>
  <div class="quiz-option" data-correct="true" data-feedback="✅ Correto!">Model</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto.">View</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto.">ViewModel</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto.">Controller</div>
  <div class="quiz-feedback"></div>
</div>

<div class="quiz-container">
  <div class="quiz-question">10. O `MutableLiveData` tem qual diferença para o `LiveData`?</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto.">É mais rápido</div>
  <div class="quiz-option" data-correct="true" data-feedback="✅ Correto!">Permite alterar o valor (.value ou .postValue)</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto.">É thread-safe por padrão</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto.">Suporta apenas Strings</div>
  <div class="quiz-feedback"></div>
</div>
