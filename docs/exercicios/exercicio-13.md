# Exercícios 13 - Sensores e Hardware 📸

## 🟢 Fáceis

1.  **Permissões**: Qual a diferença entre uma permissão "Normal" e uma "Perigosa" no Android?
2.  **GPS**: Qual biblioteca do Google Play Services é recomendada para obter a localização?

## 🟡 Médios

3.  **SensorManager**:
    Para que serve o método `registerListener`? O que acontece se esquecermos de chamar o `unregisterListener` no `onStop()` ou `onDestroy()` da Activity?
4.  **CameraX**:
    Cite os 3 principais casos de uso (Use Cases) da biblioteca CameraX e para que servem.

## 🔴 Desafio

5.  **Privacidade**:
    Se o usuário negar uma permissão perigosa (ex: Câmera) e marcar "Não perguntar novamente", como o desenvolvedor deve agir para que o usuário possa reativar essa permissão? É possível abrir o pop-up de novo direto pelo código?