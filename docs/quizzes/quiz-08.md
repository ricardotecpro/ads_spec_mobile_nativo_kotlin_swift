# Quiz 08 - Persistência de Dados 💾

--8<-- "assets/quiz.html"

<div class="quiz-container">
  <div class="quiz-question">1. Qual a melhor opção para salvar configurações simples (ex: Modo Noturno)?</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Muito complexo para isso.">Room Database</div>
  <div class="quiz-option" data-correct="true" data-feedback="✅ Correto! Chave-Valor.">SharedPreferences</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto.">Arquivo de texto</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto.">Firebase</div>
  <div class="quiz-feedback"></div>
</div>

<div class="quiz-container">
  <div class="quiz-question">2. O que é o Room?</div>
  <div class="quiz-option" data-correct="true" data-feedback="✅ Correto! Parte do Android Jetpack.">Uma biblioteca de abstração sobre o SQLite</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto.">Um banco de dados NoSQL</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto.">Um serviço de nuvem</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto.">Um sistema de arquivos</div>
  <div class="quiz-feedback"></div>
</div>

<div class="quiz-container">
  <div class="quiz-question">3. No Room, o que representa uma `@Entity`?</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto.">Uma Query SQL</div>
  <div class="quiz-option" data-correct="true" data-feedback="✅ Correto! Mapeia para uma tabela.">Uma Tabela do banco de dados</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto.">Uma conexão</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto.">Uma migração</div>
  <div class="quiz-feedback"></div>
</div>

<div class="quiz-container">
  <div class="quiz-question">4. O que significa DAO?</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto.">Data Android Object</div>
  <div class="quiz-option" data-correct="true" data-feedback="✅ Correto!">Data Access Object (Objeto de Acesso a Dados)</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto.">Direct Access Order</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto.">Disk Array Operation</div>
  <div class="quiz-feedback"></div>
</div>

<div class="quiz-container">
  <div class="quiz-question">5. Por que operações de banco de dados devem ser feitas fora da Main Thread?</div>
  <div class="quiz-option" data-correct="true" data-feedback="✅ Correto! IO é lento.">Para não travar a interface do usuário (ANR)</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto.">Por segurança de dados</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto.">Porque o banco não suporta</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto.">Para economizar bateria</div>
  <div class="quiz-feedback"></div>
</div>

<div class="quiz-container">
  <div class="quiz-question">6. Qual anotação define a chave primária da tabela?</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto.">@Id</div>
  <div class="quiz-option" data-correct="true" data-feedback="✅ Correto!">@PrimaryKey</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto.">@Key</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto.">@Main</div>
  <div class="quiz-feedback"></div>
</div>

<div class="quiz-container">
  <div class="quiz-question">7. Qual o equivalente ao SharedPreferences no iOS?</div>
  <div class="quiz-option" data-correct="true" data-feedback="✅ Correto!">UserDefaults</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto.">CoreData</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto.">Plist</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto.">KeyChain</div>
  <div class="quiz-feedback"></div>
</div>

<div class="quiz-container">
  <div class="quiz-question">8. Para observar mudanças no banco em tempo real com Room, podemos retornar:</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto.">List&lt;User&gt;</div>
  <div class="quiz-option" data-correct="true" data-feedback="✅ Correto! A UI atualiza sozinha.">LiveData&lt;List&lt;User&gt;&gt;</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto.">ArrayList&lt;User&gt;</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto.">Cursor</div>
  <div class="quiz-feedback"></div>
</div>

<div class="quiz-container">
  <div class="quiz-question">9. Se alterarmos a estrutura da tabela (ex: adicionar coluna) sem Migration, o que ocorre?</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto.">O app ajusta sozinho</div>
  <div class="quiz-option" data-correct="true" data-feedback="✅ Correto! Crash se não tratar.">O App trava (Crash) ao abrir o banco</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto.">A coluna é ignorada</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto.">Nada</div>
  <div class="quiz-feedback"></div>
</div>

<div class="quiz-container">
  <div class="quiz-question">10. Qual a Query correta para pegar todos os usuários?</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto.">@Query("GET ALL")</div>
  <div class="quiz-option" data-correct="true" data-feedback="✅ Correto!">@Query("SELECT * FROM usuario")</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto.">@Get("usuario")</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto.">@SelectAll</div>
  <div class="quiz-feedback"></div>
</div>
