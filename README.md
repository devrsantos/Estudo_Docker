# Estudo_Docker

### Comando de instalação
`curl -fsSL https://get.docker.com -o get-docker.sh && sudo sh get-docker.sh`
#### Comando de Correção - (denied while trying to connect to the Docker daemon socket)
`sudo chmod 666 /var/run/docker.sock`
### Execultar comandos no Container
Exemplo: `docker exec Ubuntu-A mkdir /nome_pasta` ou `docker exec Ubuntu-A mkdir ls /`
