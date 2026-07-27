\# Laboratório Docker Network



\## Objetivo



Entender como containers Docker se comunicam utilizando uma rede personalizada.



\## Conceitos praticados



\- Docker Networks

\- Comunicação entre containers

\- Containers isolados

\- Cliente e servidor



\## Ambiente



\- Docker Desktop

\- Windows

\- Containers Linux



\## Comandos utilizados



Criar uma rede:



```bash

docker network create minha-rede



\## Teste de comunicação



Foi criado um container cliente Ubuntu para acessar o servidor Nginx através da rede Docker.



Comando utilizado:



```bash

curl servidor-web

