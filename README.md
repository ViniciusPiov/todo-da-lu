<h1 align="center">Aplicativo Lista de Tarefas</h1>

<p align="center">
  <img src="https://imgur.com/pZp4bAV.png" alt="Aplicativo Lista de Tarefas">
</p>

## Visão Geral

Este projeto é um aplicativo de Lista de Tarefas que inclui tanto um backend quanto um frontend. O backend é desenvolvido com Node.js e o framework Express, e o MySQL é usado como banco de dados para armazenar as tarefas. O frontend é construído com HTML, CSS e JavaScript puro.

## Pré-requisitos

Antes de começar, certifique-se de ter as seguintes ferramentas instaladas:

- Node.js: [Download e Instalação](https://nodejs.org/)
- Docker: [Download e Instalação](https://www.docker.com/)

## Configuração

1. Clone este repositório para o seu ambiente local:
```
git clone https://github.com/SUA_NOME_DE_USUARIO/lista-de-tarefas.git
```
2. Navegue até o diretório do projeto:
```
cd lista-de-tarefas
```
### Backend

3. Navegue até a pasta "backend":
```
cd backend
```
4. Instale as dependências do projeto:
```
npm install
```
5. Crie um arquivo `.env` na pasta "backend" e defina a configuração do seu banco de dados:
```
DB_HOST=seu-host-do-banco-de-dados
DB_USER=seu-usuario-do-banco-de-dados
DB_PASSWORD=sua-senha-do-banco-de-dados
DB_DATABASE=seu-nome-do-banco-de-dados
```
6. Inicie o servidor backend:
```
npm start
npm run dev
```
### Banco de Dados

7. No diretório raiz do projeto, inicie o contêiner Docker do MySQL:
```
docker-compose up -d
```
### Frontend

8. Navegue até a pasta "frontend":
```
cd frontend
```
9. Abra o arquivo `index.html` em um navegador da web ou hospede-o em um servidor HTTP.

## Uso

- Acesse o frontend através do seu navegador da web e adicione tarefas à lista.
- As tarefas serão armazenadas no banco de dados MySQL.

## Conclusão

Este projeto serve como uma demonstração de como construir um aplicativo de Lista de Tarefas com um backend Node.js, banco de dados MySQL e um frontend simples com HTML, CSS e JavaScript.

Lembre-se de substituir informações específicas, como os detalhes do banco de dados, de acordo com a sua configuração.

Sinta-se à vontade para expandir e melhorar este projeto de acordo com as suas necessidades!
