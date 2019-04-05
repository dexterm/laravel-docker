# laravel-docker
PHP Laravel inside a docker container

#database password is
secret

#If your database fails to connect via php
Modify the .env file
DB_CONNECTION=mysql
DB_HOST=db #name of the docker service (do not use 127 or any ip address)
DB_PORT=3306
DB_DATABASE=laravel
DB_USERNAME=root
DB_PASSWORD=secret
