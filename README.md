<h1 align="center"> Projeto Individual Módulo 3</h1>
<h2>Servidor Teste</h2>

Foi criado um servidor teste com Json-server.
O módulo JSON-server atua na criação de uma simulação de serviços REST do JSON por um curto espaço de tempo.
Sua aplicação facilita muito o desenvolvimento de aplicações, pois dispensa a necessidade de configurações 
complexas, as quais envolvem configurações extensas do servidor, apenas para 
realizar testes básicos entre a comunicação de seus arquivos JSON e seu sistema em construção.

Como realizar a instalação de um servidor Json, siga as instrucões abaixo.

-basta executar o seguinte comando no prompt:

$  npm install -g json-server

Para realizar os testes, precisamos apenas ter um arquivo contendo qualquer informação no formato JSON e com a adição .json no arquivo.

Quando for finalizado a intalação execute o seguinte comando:

$  json server --watch oArquivoCriado.json 

acaso não funcione use:

$  npx json server --watch oArquivoCriado.json

Ao apertar “Enter”, você verá algo bem parecido com isso:

 \{^_^}/ hi!

  Loading oArquivoCriado.json<br>
  Done

  Resources<br>
  http://localhost:3000/cursos<br>
  http://localhost:3000/prazos

  Home<br>
  http://localhost:3000

  Type s + enter at any time to create a snapshot of the database
  Watching...

Acessando o link  do HOME você terá acesso ao servidor local.

Para realizar os testes CRUD.
CRUD é uma sigla inglesa para “Create, Read, Update, Delete” — ou “Criar, Ler, Atualizar, Apagar”, em português.

Para isso, usaremos um facilitador, o Postman, uma API Client, um aplicativo. Ele ajuda e facilita durante os períodos
 de teste de uma aplicação, monitorando o tráfego em nosso servidor JSON, resumidamente.
