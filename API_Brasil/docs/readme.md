API de Capitais dos Estados Brasileiros

Descrição: API desenvolvida com Node.js, TypeScript e Express, que permite pesquisar as capitais dos 26 estados brasileiros e do Distrito Federal utilizando a sigla de cada estado.

Tecnologias utilizadas: Node.js, TypeScript e Express.

Instalação: Para instalar as dependências do projeto, execute o comando npm install.

Execução: Para iniciar o servidor em modo de desenvolvimento, utilize npm run dev. Após a inicialização, a aplicação estará disponível em http://localhost:3000.

Endpoint: A consulta das capitais é feita através do método GET /estados/:sigla, informando a sigla do estado desejado.

Exemplos de consulta: Para consultar São Paulo, utilize /estados/SP. Para o Rio de Janeiro, /estados/RJ. Para Minas Gerais, /estados/MG.

Respostas: O código HTTP 200 indica que o estado foi encontrado com sucesso. Já o código HTTP 404 informa que a sigla fornecida não corresponde a nenhum estado cadastrado na API.