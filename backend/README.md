# ** BeHero **


# Informações (Métodos HTTP)
## GET: Buscar uma informação do Back-end
## POST: Criar uma informação no Back-end
## PUT: Alterar uma informação no Back-end
## DELETE: Deletar uma informação do Back-end

# Tipos de Parâmetros
## Query: Parâmetros nomeados enviados na rota após "?" (Filtros, paginação)
## Route Params: Parâmetros utilizados para identificar recursos
## Request Body: Corpo da requisição, utilizado para criar ou alterar recursos

# Criando o Projeto
```sh
$ npm init -y
```

# Configurando o Nodemon (-D apenas em Desenvolvimento)
```sh
$ npm install nodemon -D
```

# Nodemon: Alterar o arquivo `package.json`
```md
  "main": "index.js",
  "scripts": {
    "start": "nodemon index.js"
  },
  "keywords": [],
```

# Executar a aplicação com o Nodemon
```sh
$ npm start
```

# QueryBuilder (SQL): KNEX.js
# Instalando o KNEX.js
```sh
$ npm install knex
```

# Instalando o drive do SQLLite3 no KNEX.js
```sh
$ npm install sqlite3
```

# Criando o arquivo knex
```sh
$ npx knex init 
```

# Migrations
## Criando a Migrations de ONG
```sh
$ npx knex migrate:make create_ongs
```

## Executando a Migration
```sh
$ npx knex migrate:latest
```

# Criando a Migration de Ongs
```sh
$ npx knex migrate:make create_ongs
```
# Criando a Migration de Ongs
```sh
$ npx knex migrate:make create_incidents
```

# Status das migrations executadas
```sh
$ npx knex migrate:status
```

# Rollback
```sh
$ npx knex migrate:rollback
```

# Instalando o CORS
```sh
$ npm install cors 
```