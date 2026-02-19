# Quiz 13 - Sensores e Hardware 📸

--8<-- "assets/quiz.html"

<div class="quiz-container">
  <div class="quiz-question">1. Qual permissão requer autorização do usuário em tempo de execução?</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto. Permissão normal.">INTERNET</div>
  <div class="quiz-option" data-correct="true" data-feedback="✅ Correto! Permissão perigosa.">CAMERA</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto.">ACCESS_NETWORK_STATE</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto.">SET_ALARM</div>
  <div class="quiz-feedback"></div>
</div>

<div class="quiz-container">
  <div class="quiz-question">2. O detector de movimento (aceleração) é acessado via qual sensor?</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto.">Bússola</div>
  <div class="quiz-option" data-correct="true" data-feedback="✅ Correto!">Acelerômetro</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto.">GPS</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto.">Sensor de Luz</div>
  <div class="quiz-feedback"></div>
</div>

<div class="quiz-container">
  <div class="quiz-question">3. Onde as permissões devem ser declaradas obrigatoriamente?</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto.">build.gradle</div>
  <div class="quiz-option" data-correct="true" data-feedback="✅ Correto!">AndroidManifest.xml</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto.">MainActivity.kt</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto.">strings.xml</div>
  <div class="quiz-feedback"></div>
</div>

<div class="quiz-container">
  <div class="quiz-question">4. Qual API moderna é recomendada para simplificar o uso da Câmera?</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto.">Camera 1 API</div>
  <div class="quiz-option" data-correct="true" data-feedback="✅ Correto!">CameraX</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto.">OpenCV</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto.">SnapCamera</div>
  <div class="quiz-feedback"></div>
</div>

<div class="quiz-container">
  <div class="quiz-question">5. "Fused Location Provider" combina dados de quais fontes?</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto.">Apenas satélites</div>
  <div class="quiz-option" data-correct="true" data-feedback="✅ Correto! GPS, Wi-Fi e Redes Celulares.">GPS, Wi-Fi e Sensores do dispositivo</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto.">Bluetooth e Infravermelho</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto.">Apenas do chip da operadora</div>
  <div class="quiz-feedback"></div>
</div>

<div class="quiz-container">
  <div class="quiz-question">6. O que acontece se o App tentar acessar o GPS sem a permissão concedida?</div>
  <div class="quiz-option" data-correct="true" data-feedback="✅ Correto! Segurança do Android.">SecurityException (Crash)</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto.">Ele retorna localização (0,0)</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto.">O Android concede automaticamente</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto.">O GPS liga sozinho</div>
  <div class="quiz-feedback"></div>
</div>

<div class="quiz-container">
  <div class="quiz-question">7. Qual o equivalente ao Core Motion do iOS no Android?</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto.">MotionLayout</div>
  <div class="quiz-option" data-correct="true" data-feedback="✅ Correto!">SensorManager</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto.">HardwareController</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto.">InputSystem</div>
  <div class="quiz-feedback"></div>
</div>

<div class="quiz-container">
  <div class="quiz-question">8. Qual componente exibe a tela de biometria padrão do sistema?</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto.">FaceIDView</div>
  <div class="quiz-option" data-correct="true" data-feedback="✅ Correto!">BiometricPrompt</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto.">FingerprintManager (Legacy)</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto.">SecurityDialog</div>
  <div class="quiz-feedback"></div>
</div>

<div class="quiz-container">
  <div class="quiz-question">9. Qual permissão você pediria para criar um App de Bússola?</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto.">Nenhuma</div>
  <div class="quiz-option" data-correct="true" data-feedback="✅ Correto! Requer acesso a sensores de posição.">ACCESS_FINE_LOCATION</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto.">RECORD_AUDIO</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto.">VIBRATE</div>
  <div class="quiz-feedback"></div>
</div>

<div class="quiz-container">
  <div class="quiz-question">10. Para economizar bateria ao usar sensores, o que devemos fazer?</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto.">Continuar ouvindo sempre</div>
  <div class="quiz-option" data-correct="true" data-feedback="✅ Correto! Parar de ouvir quando a tela não estiver visível.">Remover o Listener (unregister) no onStop()</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto.">Desligar o celular</div>
  <div class="quiz-option" data-correct="false" data-feedback="Incorreto.">Usar Threads infinitas</div>
  <div class="quiz-feedback"></div>
</div>
