# Alterar o Docker Compose para o Novo Projeto #

1 - Editar o arquivo docker-compose.yml colocando nome correto do containers para o projeto

2 - Executar o comando docker-compose build para build dos containers

3 - Executar o comando docker-compose up para subir os containers  (incluir -d para executar daemon)



# Configuração Xdebug para MAC #

Para funcionamento correto no MAC é necessario adicionar um alias de rede para o container docker
Executar o seguinte comando:

sudo ifconfig lo0 alias 10.254.254.254
