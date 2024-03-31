## Encurtamento de url

Começamos o projeto rodando o comando **npm init -y** para criarmos somente o arquivo **package.json**.
Depois instamoso TypeScript dentro da aplicação rodando o seguinte comando **npm i typescript @types/node tsx -D**.
Criamos a pasta src, onde ficara a aplicação, e criamos o arquivo **server.ts** . Modificamos o arquivo package.json, criando o script “dev”.
Rodamos o comando **npx tsc —init**, onde ele criará o arquivo **tsconfing.json**. 
Após isso, você irá precisar ir ate o GitHub da Microsoft/TypeScript, e dentro do arquivo tsconfig/bases copiar o arquivo de acordo com a versão do Node que você possui instalado.
Instalamos o Fastify rodando o comando **npm i fastify**. 
Depois instalamos a extensão no **VSCode** da **REST Client** e criamos o arquivo **client.http**.
Neste projeto utilizaremos o Docker e os Bancos serão o *PostgreSQL* e o *Redis*.
Criaremos o arquivo **docker-compose.yml** e dentro dele as conexões com o PostgreSQL e o Redis.
Rodamos o comando **docker compose up -d** para rodar os serviços.
Criamos uma pasta lib com dois arquivos, um para o PostgreSQL e um para o Redis, que serão as conexões. 
Instalaremos dentro do projeto o PostgreSQL e o Redis, rodando o comando **npm i postgres redis**. 
Para ajudar na criação das rotas iremos instalar a biblioteca zod, rodando o comando **npm i zod**.
