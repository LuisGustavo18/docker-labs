\# Laboratório Docker Compose



\## Objetivo



Utilizar Docker Compose para criar e gerenciar um serviço Docker através de um arquivo de configuração YAML.



\## Conceitos praticados



\- Docker Compose

\- Serviços Docker

\- Imagens

\- Containers

\- Port Mapping



\## Arquivo docker-compose.yml



Configuração utilizada:



```yaml

services:

&#x20; nginx:

&#x20;   image: nginx:latest

&#x20;   container\_name: nginx-compose-lab

&#x20;   ports:

&#x20;     - "8083:80"

