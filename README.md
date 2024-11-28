# API REST de Livros

Esta é uma API REST desenvolvida com Node.js, Express e MongoDB para gerenciar informações sobre livros e suas editoras. A API permite realizar operações de CRUD (Criar, Ler, Atualizar e Deletar) e inclui funcionalidades de busca por editora.

## Funcionalidades

- Listar todos os livros
- Buscar livros por editora
- Cadastrar novos livros
- Atualizar informações de livros existentes
- Excluir livros

## Tecnologias Utilizadas

- Node.js
- Express
- MongoDB
- Mongoose

## Pré-requisitos

Antes de começar, você precisará ter instalado em sua máquina:

- [Node.js](https://nodejs.org/)
- [MongoDB](https://www.mongodb.com/try/download/community)

## Instalação

1. Clone o repositório:
   git clone https://github.com/allansalmeida/API-Rest-JS-MongoDB/
   
2. Navegue até o diretório do projeto:
   cd nome-do-repositorio

3. Instale as dependências:
   npm install

4. Inicie o MongoDB em sua máquina (se não estiver usando um serviço de nuvem).

5. Execute a aplicação:
   npm start
   
A API estará disponível em http://localhost:3000.

Endpoints
Listar todos os livros
GET /livros

Buscar livros por editora
GET /livros/busca?editora=NomeDaEditora

Cadastrar um novo livro
POST /livros
Body:
{
  "titulo": "Título do Livro",
  "autor": "Autor do Livro",
  "editora": "Editora do Livro"
}

Atualizar um livro existente
PUT /livros/:id
Body:
{
  "titulo": "Novo Título",
  "autor": "Novo Autor",
  "editora": "Nova Editora"
}

Excluir um livro
DELETE /livros/:id

Contribuição
Sinta-se à vontade para contribuir com melhorias! Para isso, siga os passos:

1. Faça um fork do projeto.
2. Crie uma nova branch (git checkout -b feature/nova-funcionalidade).
3. Faça suas alterações e commit (git commit -m 'Adicionando nova funcionalidade').
4. Envie para o branch (git push origin feature/nova-funcionalidade).
5. Abra um Pull Request.

Contato
Se você tiver alguma dúvida ou sugestão, sinta-se à vontade para entrar em contato!
LinkedIn: https://www.linkedin.com/in/allan-almeida/
