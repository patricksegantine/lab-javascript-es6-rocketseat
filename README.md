# lab-javascript-es6-rocketseat
Repositório para armazenamento do código fonte do curso gratuito de JavaScript ES6 da Rocketseat (https://rocketseat.com.br/starter)

O curso é uma introdução (para aqueles que ainda não estão familiarizados com os novos recursos do ECMAScript 6 ou superior) ou uma revisão.

De forma muito prática e objetiva, o curso aborda os seguintes recursos:
> classes
> arrow functions
> parametros padrão em funções
> desestruturação de objetos
> short syntax
> template literals
> import e export
> async e await
> try.. catch

> configurar um script no package.json:

"dev": "webpack-dev-server --mode=development"


> configurar o babel para transpilar o código ES6+ em javascript que os browsers entendam:

{
"presets": ["@babel/preset-env"],
  "plugins": [
    "@babel/plugin-transform-async-to-generator"
  ]
}


> configurar o webpack para empacotar o app:

module.exports = {
  entry: ['@babel/polyfill', './src/main.js'],
  ...
}


> utilizar a lib Axios para abstratir requisições Ajax:
