# Quiz 06 - Navegação 🗺️

--8<-- "assets/quiz.html"

<div class="quiz-container">
  <div class="quiz-question">1. O que é uma `Intent` no Android?</div>
  <div class="quiz-option" data-correct="true" data-feedback="✅ Correto! Uma mensagem de intenção.">Um objeto mensageiro que solicita uma ação de outro componente</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto.">Uma classe de banco de dados</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto.">Um layout XML</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto.">Um tipo de variável</div>
  <div class="quiz-feedback"></div>
</div>

<div class="quiz-container">
  <div class="quiz-question">2. Para navegar explicitamente da `TelaA` para `TelaB`, usamos:</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto.">goto(TelaB)</div>
  <div class="quiz-option" data-correct="true" data-feedback="✅ Correto!">Intent(this, TelaB::class.java)</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto.">System.open(TelaB)</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto.">Navigate.to(TelaB)</div>
  <div class="quiz-feedback"></div>
</div>

<div class="quiz-container">
  <div class="quiz-question">3. O que acontece com a Activity atual se chamarmos o método `finish()`?</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto.">Ela reinicia</div>
  <div class="quiz-option" data-correct="true" data-feedback="✅ Correto! Sai da pilha.">Ela é destruída e removida da pilha (Back Stack)</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto.">Ela fica em pausa para sempre</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto.">O app fecha totalmente</div>
  <div class="quiz-feedback"></div>
</div>

<div class="quiz-container">
  <div class="quiz-question">4. Qual tipo de Intent usamos para abrir o navegador web ou discador?</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto.">Explícita</div>
  <div class="quiz-option" data-correct="true" data-feedback="✅ Correto! O sistema resolve quem abre.">Implícita</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto.">Direta</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto.">Externa</div>
  <div class="quiz-feedback"></div>
</div>

<div class="quiz-container">
  <div class="quiz-question">5. "Extras" em uma Intent servem para:</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto.">Deixar o app mais bonito</div>
  <div class="quiz-option" data-correct="true" data-feedback="✅ Correto! Parâmetros.">Passar dados (chave-valor) entre Activities</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto.">Salvar dados no banco</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto.">Criar animações</div>
  <div class="quiz-feedback"></div>
</div>

<div class="quiz-container">
  <div class="quiz-question">6. No iOS, o conceito equivalente a Intent para navegação é:</div>
  <div class="quiz-option" data-correct="true" data-feedback="✅ Correto! E NavigationController.">Segue</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto.">Intent (igual)</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto.">Link</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto.">Mapper</div>
  <div class="quiz-feedback"></div>
</div>

<div class="quiz-container">
  <div class="quiz-question">7. O que é a "Back Stack"?</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto.">Uma biblioteca de Backend</div>
  <div class="quiz-option" data-correct="true" data-feedback="✅ Correto! Pilha LIFO.">A pilha de telas (Activities) abertas pelo usuário</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto.">Um erro de memória</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto.">O botão de voltar físico</div>
  <div class="quiz-feedback"></div>
</div>

<div class="quiz-container">
  <div class="quiz-question">8. Qual método usamos para recuperar um texto enviado via Intent?</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto.">getText()</div>
  <div class="quiz-option" data-correct="true" data-feedback="✅ Correto!">intent.getStringExtra("CHAVE")</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto.">intent.getObject("CHAVE")</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto.">getParams()</div>
  <div class="quiz-feedback"></div>
</div>

<div class="quiz-container">
  <div class="quiz-question">9. Se eu quiser limpar todo o histórico e iniciar uma nova tarefa, uso:</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto.">finishAll()</div>
  <div class="quiz-option" data-correct="true" data-feedback="✅ Correto! Flags poderosas.">Flags: FLAG_ACTIVITY_CLEAR_TASK | NEW_TASK</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto.">system.exit(0)</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto.">clearStack()</div>
  <div class="quiz-feedback"></div>
</div>

<div class="quiz-container">
  <div class="quiz-question">10. Qual a alternativa moderna (Jetpack) para Intents manuais?</div>
  <div class="quiz-option" data-correct="true" data-feedback="✅ Correto!">Navigation Component</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto.">Router Flux</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto.">Fragment Manager Legacy</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto.">Maps API</div>
  <div class="quiz-feedback"></div>
</div>
