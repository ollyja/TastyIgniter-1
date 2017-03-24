# TastyIgniter Docker

clone the repo

    git clone https://github.com/ThisIsQasim/TastyIgniter

Run with docker compose for automatic database configuration

    cd TastyIgniter
    docker-compose up
    
Browse to port 8001 of your docker host and setup


Alternatively if you don't want to use docker compose you run it manually

build the docker image

    cd TastyIgniter
    docker build -t TastyIgniter .
    
Run the docker

    docker run -d -p 80:80 TastyIgniter
    
Run the setup, connect to db and you're done.

## Credits
TastyIgniter: https://github.com/tastyigniter/TastyIgniter
