Este é um exemplo do tutorial de React que cria um jogo da velha, disponível em:
https://pt-br.react.dev/learn/tutorial-tic-tac-toe

As versões a serem criadas serão as seguintes:
1.0: versão do tutorial
1.1: implementação do desafio n. 1 (apenas para o movimento atual, mostre o texto ao invés de um botão)
1.2: implementação do desafio n. 2 (reescreva Board para que use dois loops que façam quadrados em vez de codificá-los)
1.3: implementação do desafio n. 3 (adicione um botão alternador que permite que você ordene os movimentos em ordem ascendente ou descendente)
1.4: implementação do desafio n. 4 (quando alguém ganhar, sublinhe os três quadrados que causaram a vitória (e quando ninguém ganhar, exiba uma mensagem sobre o resultado ter sido um empate)
1.5: implementação do desafio n. 5 (exiba a localização de cada movimento no formato (linha, coluna) e mova a lista do histórico)

npm run build

> react.dev@0.0.0 build
> react-scripts build

Creating an optimized production build...
Compiled successfully.

File sizes after gzip:

  45.98 kB  build/static/js/main.27c39fda.js
  392 B     build/static/css/main.9c5c5444.css

The project was built assuming it is hosted at /.
You can control this with the homepage field in your package.json.

The build folder is ready to be deployed.
You may serve it with a static server:

  npm install -g serve
  serve -s build

Find out more about deployment here:

  https://cra.link/deployment

One of your dependencies, babel-preset-react-app, is importing the
"@babel/plugin-proposal-private-property-in-object" package without
declaring it in its dependencies. This is currently working because
"@babel/plugin-proposal-private-property-in-object" is already in your
node_modules folder for unrelated reasons, but it may break at any time.

babel-preset-react-app is part of the create-react-app project, which
is not maintianed anymore. It is thus unlikely that this bug will
ever be fixed. Add "@babel/plugin-proposal-private-property-in-object" to
your devDependencies to work around this error. This will make this message
go away.