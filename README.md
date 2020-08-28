# rocketseat-es6

Desafios propostos de JS ES6+ na plataforma da Rocketseat Starter

## Run via Yarn

`yarn init`

`yarn add @babel/cli`

`yarn add @babel/preset-env`

no arquivo `package.json`, adicione as seguintes linhas:

```json
"scripts": {
    "dev": "babel ./main.js -o ./bundle.js -w"
  }
```

e rode `yarn dev` no terminal para iniciar o bundler
