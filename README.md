1 - Criar conta Dynatrace



## Instalação do Docker
curl -fsSL https://get.docker.com |bash

## Criando imagen Docker


docker build .


docker images


docker tag ID_DA_IMAGEM SEU_ID/serverapp01


docker images


docker login


docker push SEU_ID/serverapp01


docker run -d -p 5000:5000 --name app01 dmoraesrs/serverapp01


docker container ls
