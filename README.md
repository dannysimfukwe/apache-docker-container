# Running Apache, Mysql with Docker

## Usage

> Install Docker if you haven't already 

```
git clone https://github.com/dannysimfukwe/apache-docker-container.git

cd apache-docker-container

docker-compose  build



```

## Running the container

```
docker run -d -p 3000:80 dockerphpapache_web // dockerphpapache_web is the name of the container you built

open your browser to see the running container http://localhost:3000

```

> Enjoy