# Docker-Lamp-Server
Docker Apache PHP MariaDB server with docker compose.

## Usage:

#### This command clones the server files into the server directory

    git clone https://github.com/WebFikirleri/Docker-Lamp-Server.git server

#### Edit environments to cusomize server details
For Linux:

    cp .env.sample .env
    nano .env

For Windows:

    COPY .env.sample .env
    NOTEPAD .env

#### Copy your frontend PHP files into this directory
    /www/frontend

#### Copy your backend PHP files into this directory

    /www/backend

#### Your database files will be stored in this directory

    /data/mariadb

#### Execute this command to run server

    docker compose up -d
