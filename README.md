# DockerEnv
PHP 7.2.2 + MariaDB + PHPMyAdmin

## Como executar:
* Tenha docker e docker-compose instalado, caso não possua docker siga este tutorial [DockerTutorial](https://docs.docker.com/install/)
* Para configurar o docker-composer acesse o `.env`


>APP_PORT=8080 __<- Porta da aplicação localhost:8080__

>APP_PATH=../teste __<- Local da pasta da aplicação.__

>MYSQL_DB=mydb __<- Nome do db criado durante o up do container__

>MYSQL_USER=db __<- Usuário DB__

>MYSQL_PASS=db __<- Senha DB__

>MYSQL_PASS_ROOT=rootpass __<- Senha ROOT Db__

Após configurar o `.env` é só abrir o terminar dentro da pasta do docker e executar o comando `docker-compose up` para rodar em background adicione `-d` no comando.
