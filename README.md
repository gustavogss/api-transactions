# REST API

- API para gerenciamento de transações

## Stacks :robot:

- [Nodejs](https://nodejs.org/pt/learn/getting-started/introduction-to-nodejs)
- [Typescript](https://www.typescriptlang.org/docs/handbook/typescript-in-5-minutes.html)
- [Zod](https://zod.dev/)
- [Fastify](https://fastify.dev/docs/latest/)
- [Fastify Cookie](https://www.npmjs.com/package/@fastify/cookie)
- [Knexjs](https://knexjs.org/guide/)
- [SQLite3](https://www.sqlite.org/)
- [Dotenv](https://www.npmjs.com/package/dotenv)

## Features

- [x] O usuário deve poder criar uma nova transação
- [x] O usuário deve poder obter um resumo da sua conta
- [x] O usuário deve poder listar todas as transações
- [x] O usuário deve poder obter informações sobre uma única transação
- [x] O sistema deve identificar o usuário entre as requesições
- [x] A transação pode ser do tipo: crédito ou débito

## Routes

- GET /transactions
- GET ID /transactions/id
- POST /transactions

  ```body.json
  {
    "title":"Freelancer",
    "amount": 1000
  }
  ```

- SUMMARY /transactions/summary
