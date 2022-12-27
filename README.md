#  Chapter I - Desafio 01: Conceitos do Node.js :rocket: :purple_heart:

## :dart: Objetivo

Criar uma aplicação para gerenciar *todos* de usuários.

## :white_check_mark: Requisitos

### Rotas da aplicação
- [x] POST /users
- [x] GET /todos
- [x] POST /todos
- [x] PUT /todos/:id
- [x] PATCH /todos/:id/done
- [x] DELETE /todos/:id

### Específicação dos testes
- [x] Should be able to create a new user
- [x] Should not be able to create a new user when username already exists
- [x] Should be able to list all user's todos
- [x] Should be able to create a new todo
- [x] Should be able to update a todo
- [x] Should not be able to update a non existing todo
- [x] Should be able to mark a todo as done
- [x] Should not be able to mark a non existing todo as done
- [x] Should be able to delete a todo
- [x] Should not be able to delete a non existing todo

## :computer: Instalação ##

```bash
# Clone este repositório
$ git clone https://github.com/pvsmda/desafio-01-ConceitosDoNodeJS.git
# Entre na pasta
$ cd desafio-01-ConceitosDoNodeJS
# Instale as dependências
$ yarn ou yarn install
# Execute a aplicação em modo de desenvolvimento
$ yarn dev
# O servidor inciará na porta:3333
acesse <http://localhost:3333>
```
