# AAI-NOITE-17659-GABRIELLA-SHIBATA
AAI NOITE UNIFECAF 17659 GABRIELLA PARENTE SHIBATA


 **//COMO CRIAR UM PROJETO REACT NATIVE DO ZERO E SUBIR NO GITHUB**

 //Comando para instalar o Expo e criar o projeto de aplicação:
npx create-expo-app AAI --template blank

//Para o caso de precisar rodar na web, instalar as dependências:
npx expo install react-dom react-native-web @expo/metro-runtime

//Comando para selecionar a pasta do projeto:
cd [nome da pasta]

//Executar o seguinte código para iniciar um servidor de desenvolvimento no terminal:
npx expo start

//Comando para iniciar um repositório Git:
git init

//Comando para vincular um repositório remoto ao repositório local:
git remote add origin https://github.com/gapashi/AAI-NOITE-17659-GABRIELLA-SHIBATA

//Comando para adicionar todos os arquivos da pasta na fila de commit:
git add . --> todos os arquivos
git add meu_arquivo.tsx --> arquivo novo ou específico
git add meu_diretório --> um diretório inteiro

//Comando para gravar as mudanças (commit):
git commit -m "AAI-NOITE-ADS5NA"

//Comando para subir todos os aqruivos no repositório remoto:
git push -u origin master

**//COMO CLONAR UM PROJETO E RODÁ-LO**

//Comando para clonar o projeto:
git clone https://github.com/gapashi/AAI-NOITE-17659-GABRIELLA-SHIBATA

//Comando para selecionar a pasta dos arquivos:
cd [nome da pasta]

//Comando para abrir o editor de código Visual Studio Code:
code .

//Comando para trocar para a branch atual do arquivo salvo no repositório:
git checkout [nome da branch]

//Comando para subir a branch atual que se quer trabalhar no editor de código e definir o repositório remoto upstream:
git push --set-upstream origin [nome da branch]

//Comando apra rodar a aplicação:
npm run start


