# Estudo_Docker

### Comando de instalação
`curl -fsSL https://get.docker.com -o get-docker.sh && sudo sh get-docker.sh`

#### Comando de Correção - (denied while trying to connect to the Docker daemon socket)
`sudo chmod 666 /var/run/docker.sock`

### Gerar um Container a partir de uma Imagem
`docker run -dti --name NOME_ESCOLHIDO_CONTAINER NOME_IMAGEM`

### Execultar comandos no Container
`docker exec NOME_CONTAINER mkdir /NOME_PASTA` ou `docker exec NOME_CONTAINER mkdir ls /`

### Acessar o Bash de um Container Ubuntu
`docker exec -ti NOME_CONTAINER /bin/bash`

### Copiando arquivos de fora para dentro do Container
`docker cp NOME_ARQUIVO NOME_CONTAINER:/NOME_PASTA`

### Encerrar um Container
`docker stop NOME_CONTAINER`

### Remover um Container
`docker rm NOME_CONTAINER`
