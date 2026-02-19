# Quiz 04 - Estrutura App Android 🏗️

--8<-- "assets/quiz.html"

<div class="quiz-container">
  <div class="quiz-question">1. Onde ficam as imagens e ícones do projeto?</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto.">assets</div>
  <div class="quiz-option" data-correct="true" data-feedback="✅ Correto! Drawable (desenhável).">res/drawable</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto.">res/layout</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto.">java</div>
  <div class="quiz-feedback"></div>
</div>

<div class="quiz-container">
  <div class="quiz-question">2. O método `onCreate()` da Activity é equivalente a qual no iOS?</div>
  <div class="quiz-option" data-correct="true" data-feedback="✅ Correto! Quando a tela carrega a memória.">viewDidLoad</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto.">viewDidAppear</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto.">viewWillAppear</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto.">init</div>
  <div class="quiz-feedback"></div>
</div>

<div class="quiz-container">
  <div class="quiz-question">3. O que deve ser registrado no `AndroidManifest.xml` para que uma tela funcione?</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto.">O layout XML</div>
  <div class="quiz-option" data-correct="true" data-feedback="✅ Correto! Se não declarar, o app crasha ao abrir a tela.">A tag &lt;activity&gt;</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto.">A classe Java</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto.">As cores</div>
  <div class="quiz-feedback"></div>
</div>

<div class="quiz-container">
  <div class="quiz-question">4. Qual pasta armazena os layouts de tela?</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto.">res/values</div>
  <div class="quiz-option" data-correct="true" data-feedback="✅ Correto!">res/layout</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto.">res/draw</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto.">src/main</div>
  <div class="quiz-feedback"></div>
</div>

<div class="quiz-container">
  <div class="quiz-question">5. Para evitar `findViewById`, a solução moderna recomendada é:</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Obsoleto.">ButterKnife</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. É uma biblioteca.">Retrofit</div>
  <div class="quiz-option" data-correct="true" data-feedback="✅ Correto! Gera classes de ligação seguras.">ViewBinding</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto.">Kotlin Extensions (Deprecated)</div>
  <div class="quiz-feedback"></div>
</div>

<div class="quiz-container">
  <div class="quiz-question">6. Qual recurso usamos para textos visando internacionalização (tradução)?</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Hardcoded.">String fixa no código</div>
  <div class="quiz-option" data-correct="true" data-feedback="✅ Correto! strings.xml">@string/meu_texto</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto.">txt/meu_texto</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto.">i18n.json</div>
  <div class="quiz-feedback"></div>
</div>

<div class="quiz-container">
  <div class="quiz-question">7. Quando o usuário sai do app pressionando Home, qual método é chamado por último antes da Activity ficar "parada"?</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto.">onDestroy</div>
  <div class="quiz-option" data-correct="true" data-feedback="✅ Correto! Ela para, mas não morre necessariamente.">onStop</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto.">onPause</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto.">onStart</div>
  <div class="quiz-feedback"></div>
</div>

<div class="quiz-container">
  <div class="quiz-question">8. Qual arquivo define a versão mínima do Android que seu app suporta?</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto.">AndroidManifest.xml</div>
  <div class="quiz-option" data-correct="true" data-feedback="✅ Correto! (Module level).">build.gradle (Module: app)</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto.">settings.gradle</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto.">gradle.properties</div>
  <div class="quiz-feedback"></div>
</div>

<div class="quiz-container">
  <div class="quiz-question">9. Se eu girar a tela (rotação), o que acontece por padrão com a Activity?</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto.">Nada</div>
  <div class="quiz-option" data-correct="true" data-feedback="✅ Correto! Ela é destruída e recriada.">Ela é destruída e recriada (onDestroy -> onCreate)</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto.">Ela apenas pausa</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto.">Apenas o layout se ajusta</div>
  <div class="quiz-feedback"></div>
</div>

<div class="quiz-container">
  <div class="quiz-question">10. Qual a classe mãe de todas as telas modernas no Android?</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. (Antiga)">Activity</div>
  <div class="quiz-option" data-correct="true" data-feedback="✅ Correto! Garante compatibilidade.">AppCompatActivity</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto.">Fragment</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto.">View</div>
  <div class="quiz-feedback"></div>
</div>
