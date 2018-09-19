# Exemplo de Node usando Docker

Comandos usados para o Docker
BUILD
  docker build -t <container_name> .
RUN
  docker run -p 49160:8080 -d <container_name>