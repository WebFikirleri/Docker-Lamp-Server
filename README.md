# Docker-Lamp-Server
Docker Apache PHP MariaDB server with docker compose.

[![Hits](https://hits.seeyoufarm.com/api/count/incr/badge.svg?url=https%3A%2F%2Fgithub.com%2FWebFikirleri%2FDocker-Lamp-Server&count_bg=%233D81C8&title_bg=%23555555&icon=github.svg&icon_color=%23E7E7E7&title=hits&edge_flat=true)](https://hits.seeyoufarm.com)

[![ko-fi](https://ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/Z8Z2LXJ6H)

## Usage:

#### This command clones the server files into the server directory

    git clone https://github.com/WebFikirleri/Docker-Lamp-Server.git server

#### Edit environments to cusomize server details

Rename or copy ".env.sample" file as ".env" and edit it a text editor.

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
