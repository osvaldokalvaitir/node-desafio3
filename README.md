# Node - Desafio 3

Aplicação Marketplace usando Node.js, Express, Mongoose, Json Web Token, Nodemailer, Joi, Kue e Sentry.

## Desafio

Nesse terceiro desafio você irá melhorar a aplicação desenvolvida durante o terceiro módulo com as seguintes funcionalidades:

- Armazene as intenções de compra (Purchase) no MongoDB criando um Model e salvando os dados da purchase no método `store` do PurchaseController;
- Crie uma nova rota para o vendedor aceitar uma intenção de compra declarando o item como vendido e a partir desse momento o anúncio não deve ser mais exibido nas listagens e não deve ser mais possível realizar uma intenção de compra para esse anúncio;
- O Ad deve possui um campo adicional chamado `purchasedBy` que armazena o ID da Purchase que o vendedor aceitou, caso esse campo esteja presente, quer dizer que o anúncio foi vendido;

## Resumo

Esta aplicação foi desenvolvida para realizar os seguintes procedimentos:

- Adiciona novos usuários
- Adiciona nova sessão quando o usuário logar
- Adiciona novos anúncios
- Lista todos os anúncios que não estão vendidos podendo receber filtros
- Lista somente dados de um anúncio selecionado
- Edita dados de anúncios existentes
- Exclui anúncios existentes
- Adiciona nova intenção de compra
- Aceita intenção de compra declarando o item como vendido

## Índice

- [Desenvolvimento](#desenvolvimento)

  - [Configurações Iniciais](#configurações-iniciais)

  - [Instalação do Projeto](#instalação-do-projeto)

  - [Execução do Projeto](#execução-do-projeto)

  - [Bibliotecas](#bibliotecas)

  - [Outras Ferramentas](#outras-ferramentas)

## Desenvolvimento

### Configurações Iniciais

Clique [aqui](https://github.com/osvaldokalvaitir/projects-settings/blob/master/README.md) e siga as Configurações Iniciais.

### Instalação do Projeto

Clique [aqui](https://github.com/osvaldokalvaitir/projects-settings/blob/master/nodejs/nodejs.md) e siga a Instalação de Projeto.

### Execução do Projeto

Clique [aqui](https://github.com/osvaldokalvaitir/projects-settings/blob/master/nodejs/nodejs.md) e siga a Execução de Projeto.

### Bibliotecas

- [@sentry/node](https://github.com/osvaldokalvaitir/projects-settings/blob/master/nodejs/libs/@sentry-node.md)

- [bcrypt.js](https://github.com/osvaldokalvaitir/projects-settings/blob/master/nodejs/libs/bcryptjs.md)

- [dotenv](https://github.com/osvaldokalvaitir/projects-settings/blob/master/nodejs/libs/dotenv.md)

- [ESLint](https://github.com/osvaldokalvaitir/projects-settings/blob/master/nodejs/libs/eslint.md)

- [Express](https://github.com/osvaldokalvaitir/projects-settings/blob/master/nodejs/libs/express.md)

- [Express Async Handler](https://github.com/osvaldokalvaitir/projects-settings/blob/master/nodejs/libs/express-async-handler.md)

- [Express Handlebars](https://github.com/osvaldokalvaitir/projects-settings/blob/master/nodejs/libs/express-handlebars.md)

- [Express Handlebars plugin for Nodemailer](https://github.com/osvaldokalvaitir/projects-settings/blob/master/nodejs/libs/nodemailer-express-handlebars.md)

- [Express Validation](https://github.com/osvaldokalvaitir/projects-settings/blob/master/nodejs/libs/express-validation.md)

- [Joi](https://github.com/osvaldokalvaitir/projects-settings/blob/master/nodejs/libs/joi.md)

- [Json Web Token](https://github.com/osvaldokalvaitir/projects-settings/blob/master/nodejs/libs/jsonwebtoken.md)

- [Kue](https://github.com/osvaldokalvaitir/projects-settings/blob/master/nodejs/libs/kue.md)

- [Mongoose](https://github.com/osvaldokalvaitir/projects-settings/blob/master/nodejs/libs/mongoose.md)

- [Mongoose Paginate](https://github.com/osvaldokalvaitir/projects-settings/blob/master/nodejs/libs/mongoose-paginate.md)

- [Nodemailer](https://github.com/osvaldokalvaitir/projects-settings/blob/master/nodejs/libs/nodemailer.md)

- [Nodemon](https://github.com/osvaldokalvaitir/projects-settings/blob/master/nodejs/libs/nodemon.md)

- [requireDir](https://github.com/osvaldokalvaitir/projects-settings/blob/master/nodejs/libs/requiredir.md)

- [Youch](https://github.com/osvaldokalvaitir/projects-settings/blob/master/nodejs/libs/youch.md)

### Outras Ferramentas

- [Docker](https://github.com/osvaldokalvaitir/projects-settings/blob/master/docker/docker.md)

  - Imagem do MongoDB: [mongo](https://github.com/osvaldokalvaitir/projects-settings/blob/master/docker/images/mongo.md)

  - Imagem do Redis: [redis:alpine](https://github.com/osvaldokalvaitir/projects-settings/blob/master/docker/images/redis-alpine.md)

- [Mailtrap](https://github.com/osvaldokalvaitir/projects-settings/blob/master/email/mailtrap.md)

- [Insomnia](https://github.com/osvaldokalvaitir/projects-settings/blob/master/api/insomnia.md)

- [Sentry](https://github.com/osvaldokalvaitir/projects-settings/blob/master/errors/sentry.md)
