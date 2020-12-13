
# amplifyapp
Criando uma aplicação AWS Amplifyapp

Criar a apliação local
npx create-react-app amplifyapp cd amplifyapp npm start

Criar um repositório
git init git remote add origin git@github.com:username/reponame.git git add . git commit -m “initial commit” git push origin master

Console de Gerenciamento da AWS
Abra o Console de Gerenciamento da AWS em uma nova janela do navegador para que possa manter este guia detalhado aberto. Quando a tela carregar, digite seu nome de usuário e senha para começar. Em seguida, digite “Amplify” na barra de pesquisa e selecione AWS Amplify para abrir o console de serviço.

Implantar o app
a. No console de serviço do AWS Amplify, selecione "Get Started" (Comece a usar) em Deploy (Implantar). b. Selecione o GitHub como o repositório de serviço e Continue (Continuar). c. Autentique no GitHub e retorne ao Console do Amplify. Escolha o repositório a ramificação principal que você criou anteriormente e selecione Next (Avançar). d. Aceite as configurações de compilação padrão e selecione Next (Avançar). e. Revise os detalhes finais e selecione Save and Deploy (Salvar e implantar). f. O AWS Amplify agora criará seu código-fonte e implantará seu aplicativo em https://...amplifyapp.com. g. Depois que a compilação for concluída, selecione a miniatura para ver seu aplicativo Web em funcionamento.

Implantar alterações no código
a. Edite src/App.js com o código abaixo e salve. b. Envie as alterações para GitHub no prompt de comando (Windows) ou Terminal (macOS) para iniciar automaticamente uma nova compilação: git add . git commit -m “changes for v2” c. Depois que a compilação for concluída, selecione a miniatura no console do AWS Amplify para visualizar seu aplicativo atualizado. git push origin master

# Getting Started with Create React App

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Available Scripts

In the project directory, you can run:

### `yarn start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload if you make edits.\
You will also see any lint errors in the console.

### `yarn test`

Launches the test runner in the interactive watch mode.\
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `yarn build`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `yarn eject`

**Note: this is a one-way operation. Once you `eject`, you can’t go back!**

If you aren’t satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you’re on your own.

You don’t have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn’t feel obligated to use this feature. However we understand that this tool wouldn’t be useful if you couldn’t customize it when you are ready for it.

## Learn More

You can learn more in the [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started).

To learn React, check out the [React documentation](https://reactjs.org/).

### Code Splitting

This section has moved here: [https://facebook.github.io/create-react-app/docs/code-splitting](https://facebook.github.io/create-react-app/docs/code-splitting)

### Analyzing the Bundle Size

This section has moved here: [https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size](https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size)

### Making a Progressive Web App

This section has moved here: [https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app](https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app)

### Advanced Configuration

This section has moved here: [https://facebook.github.io/create-react-app/docs/advanced-configuration](https://facebook.github.io/create-react-app/docs/advanced-configuration)

### Deployment

This section has moved here: [https://facebook.github.io/create-react-app/docs/deployment](https://facebook.github.io/create-react-app/docs/deployment)

### `yarn build` fails to minify

This section has moved here: [https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify](https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify)
