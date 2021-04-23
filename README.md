<div align="center">

# Next Level Week 5 Rocketseat - NodeJs

![NodeJs](https://img.shields.io/badge/-Nodejs-339933?style=flat-square&logo=Node.js&logoColor=white "Node.js")
![Typescript](https://img.shields.io/badge/-Typescript-1572B6?style=flat-square&logo=typescript&logoColor=white "Typescript")
![SQLite](https://img.shields.io/badge/-SQLite-03BAFC?style=flat-square&logo=sqlite&logoColor=white "SQLite")

A **Next Level Week** é um evento da **Rocketseat** de imersão em tecnologia. Onde é uma semana de aulas com conteúdos incríveis e uma comunidade bem massa de se fazer network. Nesse evento há diversas tecnologias, esta por exemplo é a trilha de **NodeJs**.

![Banner](./.github/NLW05_banner.png)

_#juntosparaoproximonivel_

![Spaceship](./.github/NLW05_espaconave.jpg)

## Proposta do projeto NLW5 NodeJs

A proposta deste NLW é desenvolver um backend de um chat entre um usuário e alguém que dê suporte ao usuário, para isto irá ser utilizado o `NodeJs`, `Typescript`, `SQLite` e `Socket`.

## Conteúdo

**Dia 1**

O primeiro dia foi para explicar conceitos sobre as tecnologias a serem utilizadas, o motivo de utilizar `Typescript` ao invés do `Javascript`, o _database_ a ser utilizado e como iniciar o projeto e adicionar as dependências.

**Dia 2**

O segundo dia foi para entender os conceitos do `database` e as ferramentas que iriam ser utilizadas, além de terminar de fazer as configurações do `Typescript`.

O projeto irá utilizar o `SQLite`, e foi definido que o `Typeorm` será a ferramenta que irá configurar o _database_. Com o `Typeorm` foi criado o `migrations` e o nosso `database.sqlite`.

Foi feito também uma estrutura para criação de `Settings`, separados em **Entity**, **Repository** e **Controller**, além de ser configurado nas rotas.

**Entity**: É a `entidade`, é onde será definido os campos que ele poderá receber.
**Repository**: Ele é responsável pela manipulação dos dados entre a `entidade` e o `database`.
**Controller**: Ele é reponsável pela comunicação entre o quê está vindo da rota e o `repository`.

**Dia 3**

No terceiro dia a gente fez uma pequena refatoração do código criando um **Services** para fazer o gerenciamento da manipulação do `repository` e criamos a **Entity**, **Repository**, **Controller** e **Services** do `User` e `Messages`.

**Services**: São funções que o `Controller` irá utilizar.

**Dia 4**
No quarto e penúltimo dia a gente fez a implementação do websocket com o `socket.io` e fizemos uma pequena configuração do websocket e o client(html).

**Dia 5**

No quinto e último dia a gente finalizou a integração do socket, fazendo o fluxo de chat entre o usuário e atentente e assim terminamos a aplicação.

---

Agradecimento à **Rocketseat** 🚀 pelo evento incrível!💜

_Matheus Ishiyama_
