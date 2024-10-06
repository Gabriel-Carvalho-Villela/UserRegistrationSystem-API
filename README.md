# 🚀 UserRegistrationSystem-API

## 📝 Descrição do Sistema

A **UserRegistrationSystem-API** é uma API RESTful desenvolvida para o gerenciamento de usuários. As principais funcionalidades incluem:

- 🆕 **Cadastro de usuários**
- ✏️ **Atualização de informações de usuários**
- ❌ **Exclusão de usuários**

## ⚙️ Tecnologias Utilizadas

- **Node.js** com **Express** para a criação e gerenciamento do servidor.
- **MongoDB** com **Prisma** como ORM para o gerenciamento do banco de dados.
- Metodologia completa baseada em **CRUD** (Create, Read, Update, Delete).

## 🚀 Como Rodar o Servidor

Para iniciar o servidor em modo de desenvolvimento, siga os seguintes passos:

1. Clone o repositório: `git clone https://github.com/usuario/UserRegistrationSystem-API.git`

2. Instale as dependências: `npm install`

3. Crie um arquivo `.env` na raiz do projeto e configure a variável de ambiente com o link do banco de dados:

   `DATABASE=mongodb+srv://<usuario>:<senha>@cluster0.mongodb.net/<nome-do-banco>?retryWrites=true&w=majority`

4. Inicie o servidor: `node --watch server.js`

---

## 🗄️ Configuração do Banco de Dados

Esta API utiliza **MongoDB** com o **Prisma** como ORM. Para configurar o banco de dados, crie um arquivo `.env` na raiz do projeto e adicione a variável de ambiente `DATABASE` com a string de conexão correta do seu banco de dados.
