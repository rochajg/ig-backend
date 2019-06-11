# Instagram Clone

Aplicação feita em NodeJS utilizando conceitos de Upload de imagens e conexão com Banco de Dados não relacional (NoSQL).

Totalmente idealizada pelo pessoal da [@Rocketseat](https://github.com/Rocketseat).

## Como usar?

É importante ter em mente que essa é uma aplicação NodeJS, então tenha-o instalado. É recomendado ter o `yarn` instalado também:
```
npm i -g yarn
```

Depois de instalado o `yarn` instale as dependências do projeto com o comando:
```
yarn install
```

Para realizar a conexão com a base de dados Mongo, copie o arquivo `.env.example` e renomei-o para `.env`. 

Em seguida altere seu conteúdo com a URL de conexão da sua base de dados no campo `MONGODB_URL`.
```
module.exports = {
  MONGODB_URL: 'SUA_URL_DO_ATLAS_AQUI'
}
```

Para executar a aplicação utilize o comando `yarn dev` para iniciar o servidor local.