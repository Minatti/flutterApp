# flutterApp
My first project with flutter

# Install and config Flutter OnWindows
# Page: https://flutter.dev/

0. Get the Flutter SDK (Baixar Flutter SDK)

* [0.1] Download the following installation bundle to get the latest stable release of the Flutter SDK:
* [0.2] Extract the zip file and place the contained flutter in the desired installation location for the Flutter SDK (for example, %USERPROFILE%\flutter, D:\dev\flutter).
  ** Path = "D:\DevApp\"
  ** Note: Do not install Flutter to a path that contains special characters or spaces.
  ** Do not install Flutter in a directory like C:\Program Files\ that requires elevated privileges.


1. Update your path

* [1.1] vá na barra iniciar e digite env e dê enter
* [1.2] abrirá a janela propriedades do sistema
* [1.3] Acesse Variáveis de Ambiente
* [1.4] Em Path, selecione para editar e clique
* [1.5] Procure por novo e clique em Novo
* [1.6] Aponte para o caminho onde extraiu o flutter = "D:\DevApp\flutter\bin"
Finalizado esta parte...
* [1.7] abra o terminal(prompt)
* [1.8] digite "where flutter dart"
- `Retorno:
           "C:\Users\workcarminatti>where flutter dart
            D:\DevApp\flutter\bin\flutter
            D:\DevApp\flutter\bin\flutter.bat
            D:\DevApp\flutter\bin\dart
            D:\DevApp\flutter\bin\dart.bat"`
* [1.9] Vá para o seu diretório de desenvolvimento
* [2.0] Digite o seguinte comando "flutter doctor"
***Será retornado um relatório de status referente as instalações
* [2.1] Vou optar por continuar a configuração com o editor VScode e não Android Studio.
