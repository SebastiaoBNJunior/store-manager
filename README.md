<div align="center">
  <h1>📖 Store Manager 💻</h1>
</div>

This project was developed while I was studying 'Software Architecture: Model, Service and Controller' at `Trybe` Programming School.

In this project, I developed an application for sales management. Through it, it's possible to create, view, update, and delete products and sales.

## 👨‍💻 Language and Technologies used

![Docker](https://img.shields.io/badge/docker-%230db7ed.svg?style=for-the-badge&logo=docker&logoColor=white)

![MySQL](https://img.shields.io/badge/mysql-4479A1.svg?style=for-the-badge&logo=mysql&logoColor=white)

![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E)

<details>
  <summary><strong>🏗 Project structure</strong></summary><br />

The implemented functions are inside the `src` folder.

Built folders:
<p>
    📁src/
        <br>📂controllers
        <br>📂middlewares
        <br>📂models
        <br>📂services
</p>
</details>

<details>
  <summary><strong>🖥️ To access</strong></summary><br />

1 - Clone the repository:
`git clone git@github.com:SebastiaoBNJunior/store-manager`

2 - Enter the repository folder you just cloned.

You must be using node version 16 (or higher).

To check your version, use the command:
`nvm --version`

3 - Quickstart with 🐳 Docker Compose:

# Instale as dependências
npm install

# Inicie os containers do compose `backend` e `db`
# A aplicação estará disponível em `http://localhost:3001` em modo de desenvolvimento
docker-compose up -d

or

Quickstart without 🐳 Docker Compose:

# Instale as dependências
npm install

# Inicie apenas o serviço `db` no compose
docker-compose up -d db

# Inicie a aplicação em modo de desenvolvimento
npm run dev:local

</details>


<details>
  <summary><strong>🔎 Linter</strong></summary><br />
  
### ESLint

To ensure code quality, the `ESLint` was used in this project.
So the code will be available with good development practices, being more readable and easy to maintain!

ESLint is a tool for identifying and reporting patterns found in ECMAScript/JavaScript code. In many ways it is similar to JSLint and JSHint with a few exceptions:

* ESLint uses Espree for JavaScript parsing.
* ESLint uses an AST to evaluate patterns in code.
* ESLint is completely 'pluggable', each of the rules is a plugin and you can add […]

</details>

<details>
  <summary><strong>🗣 Feedbacks</strong></summary><br />
  
_Give me feedbacks, I'm open to new ideas_ 😉

</details>
