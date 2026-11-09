# API de Capitais Brasileiras

## Descrição

API desenvolvida utilizando Node.js, TypeScript e Express.
Permite consultar as capitais dos 26 estados brasileiros
e do Distrito Federal por meio da sigla da unidade federativa.

## Tecnologias utilizadas

- Node.js
- TypeScript
- Express

## Instalação

Instale as dependências:

npm install

## Execução

Execute o servidor em modo de desenvolvimento:

npm run dev

O servidor estará disponível em:

http://localhost:3000

## Endpoint

GET /estados/:sigla

## Exemplos

Consultar São Paulo:

http://localhost:3000/estados/SP

Consultar Rio de Janeiro:

http://localhost:3000/estados/RJ

Consultar Minas Gerais:

http://localhost:3000/estados/MG

## Respostas

HTTP 200: Estado encontrado.

HTTP 404: Estado não encontrado.
