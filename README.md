# docker-compose-nextjs-php
Starter kit for docker-compose, nextjs and php7

## Running locally in development mode

To get started, just clone the this repository and run `docker-compose up`:

    git clone https://github.com/kmusiclife/docker-compose-nextjs-php.git
    docker-compose up

If you require to setup new Next.js Project and run below commands:

    cd src/app
    git clone https://github.com/kmusiclife/nextjs-starter-bootstrap.git ./
    npm install
    cd ../../ # move to current docker path
    docker-compose up

