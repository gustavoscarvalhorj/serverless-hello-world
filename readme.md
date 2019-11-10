# Iniciando com Serverless #

## Introdução ##
O objetivo deste repositório é compartilhar o meu primeiro passo para entender como funciona o mundo **serveless**. Neste caso, estou utilizando como stack: **NodeJS** e **AWS Lambda**.

Este projeto foi construído com o node.js, portanto, estamos utilizando o **express** para entregar uma página HTML sempre que a aplicação for requisitada. 


## Tutoriais seguidos: ##

**I just launched a serverless website in 15 minutes de John Demian**
https://hackernoon.com/i-just-launched-a-serverless-website-in-15-minutes-8e399c827fef


**Configurando as credenciais na AWS. Passos 2 e 3 de Adnan Rahić**
https://hackernoon.com/a-crash-course-on-serverless-with-node-js-632b37d58b44

## Pré-Requisitos: ##
Para executar este projeto, você precisará ter em sua estação as seguintes ferramentas:

- Git
- NodeJS 8+

## Executando no ambiente local: ##
Executar as seguintes instruções através da linha de comando da sua estação de trabalho:

- `git clone`: Para clonar este repositório em sua estação de trabalho.

- `npm install`: Para instalar todas as dependências deste projeto. Executar dentro da pasta que foi clonada.

- `node local.js`: Para executar este projeto em sua estação de trabalho. Após executar, o link http://localhost:3001/ estará disponível.

## Para fazer deploy deste projeto na AWS: ##
- Rodar o comando `npm install -g serverless` para ser possível utilizar os comandos `serverless`.

- Configurar a chave de conexão com a AWS conforme descrito nos passos 2 e 3 do tutorial disponibilizado acima. 

- Realizar a publicação. Vide primeiro tutorial.
