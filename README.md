# docker_rails_mysql_basic
Configuracion basica para un entorno con rails y mysql

* git clone https://github.com/JuIturra/docker_rails_mysql_basic.git
* cd docker_rails_mysql_basic

* docker-compose build
* sudo chown -R $USER:$USER .
* docker-compose run web rails new . --force --no-deps --database=mysql
* docker-compose up
