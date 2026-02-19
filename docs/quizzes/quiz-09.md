# Quiz 09 - RecyclerView 📋

--8<-- "assets/quiz.html"

<div class="quiz-container">
  <div class="quiz-question">1. Qual o principal benefício do RecyclerView sobre a ListView?</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto.">É mais fácil de implementar</div>
  <div class="quiz-option" data-correct="true" data-feedback="✅ Correto! Reaproveita views.">Performance (Reciclagem de Views)</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto.">Tem animações automáticas 3D</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto.">Usa menos código</div>
  <div class="quiz-feedback"></div>
</div>

<div class="quiz-container">
  <div class="quiz-question">2. Qual componente define a organização dos itens (Lista vs Grade)?</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto.">Adapter</div>
  <div class="quiz-option" data-correct="true" data-feedback="✅ Correto!">LayoutManager</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto.">ViewHolder</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto.">ItemDecoration</div>
  <div class="quiz-feedback"></div>
</div>

<div class="quiz-container">
  <div class="quiz-question">3. O que faz o método `onBindViewHolder`?</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto.">Cria o layout XML</div>
  <div class="quiz-option" data-correct="true" data-feedback="✅ Correto! Liga o dado à View.">Preenche os dados do item na View (Binding)</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto.">Conta quantos itens tem</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto.">Destrói a view</div>
  <div class="quiz-feedback"></div>
</div>

<div class="quiz-container">
  <div class="quiz-question">4. Qual classe guarda as referências dos componentes da view (cache de `findViewById`)?</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto.">Context</div>
  <div class="quiz-option" data-correct="true" data-feedback="✅ Correto!">ViewHolder</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto.">Activity</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto.">Fragment</div>
  <div class="quiz-feedback"></div>
</div>

<div class="quiz-container">
  <div class="quiz-question">5. Para atualizar a lista inteira (método menos eficiente), usamos:</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto.">updateAll()</div>
  <div class="quiz-option" data-correct="true" data-feedback="✅ Correto!">notifyDataSetChanged()</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto.">refresh()</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto.">redraw()</div>
  <div class="quiz-feedback"></div>
</div>

<div class="quiz-container">
  <div class="quiz-question">6. Qual ferramenta calcula a diferença mínima entre duas listas para animar a atualização?</div>
  <div class="quiz-option" data-correct="true" data-feedback="✅ Correto!">DiffUtil</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto.">ListUtils</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto.">CompareTo</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto.">AnimatorSet</div>
  <div class="quiz-feedback"></div>
</div>

<div class="quiz-container">
  <div class="quiz-question">7. O `GridLayoutManager` organiza os itens em:</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto.">Lista vertical</div>
  <div class="quiz-option" data-correct="true" data-feedback="✅ Correto!">Grade (Colunas/Linhas)</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto.">Carrossel</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto.">Aleatório</div>
  <div class="quiz-feedback"></div>
</div>

<div class="quiz-container">
  <div class="quiz-question">8. É correto inflar o layout (XML) dentro do `onBindViewHolder`?</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto.">Sim, sempre</div>
  <div class="quiz-option" data-correct="true" data-feedback="✅ Correto! Deve ser no onCreateViewHolder.">Não, isso mata a performance e a reciclagem</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto.">Depende do tamanho da lista</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto.">Sim, se for Grid</div>
  <div class="quiz-feedback"></div>
</div>

<div class="quiz-container">
  <div class="quiz-question">9. Qual o equivalente ao RecyclerView no iOS (UIKit)?</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto.">ScrollView</div>
  <div class="quiz-option" data-correct="true" data-feedback="✅ Correto!">UITableView / UICollectionView</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto.">ListStruct</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto.">RecycleController</div>
  <div class="quiz-feedback"></div>
</div>

<div class="quiz-container">
  <div class="quiz-question">10. Quantos ViewHolders o RecyclerView mantém na memória?</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto.">Todos (tamanho da lista)</div>
  <div class="quiz-option" data-correct="true" data-feedback="✅ Correto! Os visíveis + um buffer pequeno.">Apenas o suficiente para preencher a tela + buffer</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto.">Apenas 1</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto.">Sempre 10</div>
  <div class="quiz-feedback"></div>
</div>
