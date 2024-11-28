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
   ```bash
   git clone https://github.com/seu-usuario/nome-do-repositorio.git
Navegue até o diretório do projeto:

bash
Copiar código
cd nome-do-repositorio
Instale as dependências:

undefined
Copiar código
npm install
Inicie o MongoDB em sua máquina (se não estiver usando um serviço de nuvem).

Execute a aplicação:

sql
Copiar código
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
json
Copiar código
{
  "titulo": "Título do Livro",
  "autor": "Autor do Livro",
  "editora": "Editora do Livro"
}
Atualizar um livro existente
PUT /livros/:id
Body:
json
Copiar código
{
  "titulo": "Novo Título",
  "autor": "Novo Autor",
  "editora": "Nova Editora"
}
Excluir um livro
DELETE /livros/:id
Contribuição
Sinta-se à vontade para contribuir com melhorias! Para isso, siga os passos:

Faça um fork do projeto.
Crie uma nova branch (git checkout -b feature/nova-funcionalidade).
Faça suas alterações e commit (git commit -m 'Adicionando nova funcionalidade').
Envie para o branch (git push origin feature/nova-funcionalidade).
Abra um Pull Request.
Licença
Este projeto está licenciado sob a MIT License - veja o arquivo LICENSE para mais detalhes.

Contato
Se você tiver alguma dúvida ou sugestão, sinta-se à vontade para entrar em contato!
