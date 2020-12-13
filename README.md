# amplifyapp
Criando uma aplicação AWS Amplifyapp

Criar a apliação local
-------------------------------------------
npx create-react-app amplifyapp
cd amplifyapp
npm start

Criar um repositório
-------------------------------------------
git init
git remote add origin git@github.com:username/reponame.git
git add .
git commit -m “initial commit”
git push origin master

Console de Gerenciamento da AWS
--------------------------------------------
Abra o Console de Gerenciamento da AWS em uma nova janela do navegador para que possa manter este guia detalhado aberto. Quando a tela carregar, digite seu nome de usuário e senha para começar. Em seguida, digite “Amplify” na barra de pesquisa e selecione AWS Amplify para abrir o console de serviço.

Implantar o app
--------------------------------------------
a. No console de serviço do AWS Amplify, selecione "Get Started" (Comece a usar) em Deploy (Implantar).
b. Selecione o GitHub como o repositório de serviço e Continue (Continuar).
c. Autentique no GitHub e retorne ao Console do Amplify. Escolha o repositório a ramificação principal que você criou anteriormente e selecione Next (Avançar).
d. Aceite as configurações de compilação padrão e selecione Next (Avançar).
e. Revise os detalhes finais e selecione Save and Deploy (Salvar e implantar).
f. O AWS Amplify agora criará seu código-fonte e implantará seu aplicativo em https://...amplifyapp.com.
g. Depois que a compilação for concluída, selecione a miniatura para ver seu aplicativo Web em funcionamento. 

Implantar alterações no código
---------------------------------------------
a. Edite src/App.js com o código abaixo e salve.
b. Envie as alterações para GitHub no prompt de comando (Windows) ou Terminal (macOS) para iniciar automaticamente uma nova compilação: 
git add .
git commit -m “changes for v2”
c. Depois que a compilação for concluída, selecione a miniatura no console do AWS Amplify para visualizar seu aplicativo atualizado.
git push origin master
