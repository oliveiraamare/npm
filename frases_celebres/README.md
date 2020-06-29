# Citações!!!
> "Seja a mudança que você quer ver no mundo."
> - Mahatma Gandhi

## instalando

1. instale o `citacoes` e salve-o no seu `package.json`:

  ```
  npm install citacoes --save
  ```

2. insira-o na sua aplicação

  ```
  const citacoes = require('citacoes');
  ```

3. agora você possui a variável `citacoes` que aponta para um array de citações de livros e autores célebres!

  ```
  const citacoes = require('./citacoes.js')

  var quote = citacoes[Math.floor(Math.random()*citacoes.length)];

  console.log("" + quote.texto); //printa "Ler é sonhar pela mão de outrem."
  console.log("- " + quote.autor); // - Fernando Pessoa
  ```
  
https://github.com/oliveiraamare/npm/tree/master/citacoes