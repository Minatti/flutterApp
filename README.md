# flutterApp
My first project with flutter


0. Como instalar Flutter e configurar?

* https://flutter.dev/

* Para cada tipo de sistema operacional é de uma forma, no meu caso estarei configurando para o Windows e seguirei as instruções da documentação.

** Requisitos do Sistema

Setup
Windows 10 x64

*Get the Flutter SDK
Baixar Flutter SDK

1. Download the following installation bundle to get the latest stable release of the Flutter SDK:

Baixar a última versão disponível para Flutter SDK

2. Extract the zip file and place the contained flutter in the desired installation location for the Flutter SDK (for example, %USERPROFILE%\flutter, D:\dev\flutter).

Extrair o arquivo zip para um local, de preferência não extraia para o "C:\", pois conforme informado na nota vai requerir previlégio elevado.

No meu caso fiz a extração em "D:\DevApp\"

Note: Do not install Flutter to a path that contains special characters or spaces.

Do not install Flutter in a directory like C:\Program Files\ that requires elevated privileges.


*Update your path

vá na barra iniciar e digite env e dê enter

abrirá a janela propriedades do sistema

Acesse Variáveis de Ambiente

Em Path, selecione para editar e clique

Procure por novo e clique em Novo

Aponte para o caminho onde extraiu o flutter
"D:\DevApp\flutter\bin" OK.

Finalizado esta parte 
abra o terminal(prompt)
digite "where flutter dart"

<img>
retorno = "C:\Users\workcarminatti>where flutter dart
D:\DevApp\flutter\bin\flutter
D:\DevApp\flutter\bin\flutter.bat
D:\DevApp\flutter\bin\dart
D:\DevApp\flutter\bin\dart.bat"

Vá para o seu diretório de desenvolvimento

Digite o seguinte comando "flutter doctor"

Será retornado um relatório de status referente as instalações

<img>

Vou optar por continuar a configuração com o editor vscode e não Android Studio.