Comandos:

`docker run -it --name <nome_do_container> <imagem> bash`
  - Cria e inicia um novo container a partir da imagem especificada, com um terminal bash interativo.

`docker start <container>`
  - Inicia um container existente.

`docker ps -a`
 - Lista todos os containers, incluindo os que estão parados.

`docker build -t <nome_da_imagem>:<tag> .`
  - Constrói uma imagem a partir de um Dockerfile no diretório atual e a taggeia com o nome especificado.

`docker run --rm --name <nome_do_container> -p <porta_host>:<porta_container> <imagem>`
  - Cria e inicia um novo container a partir da imagem especificada, com a remoção automática do container quando ele é parado.

`docker logs <container>`
  - Exibe os logs de um container específico.

`docker push <nome_da_imagem>`
  - Faz o push de uma imagem para um registry.

`docker network create <nome_da_rede>`
  - Cria uma nova rede Docker.

`docker network list`
  - Lista todas as redes Docker.

`docker rm -f <container>`
  - Remove um container específico.

`docker-compose up`
  - Inicia os serviços definidos em um arquivo docker-compose.yml.

`docker-compose down`
  - Para e remove os containers, redes e volumes definidos no arquivo docker-compose.yml.