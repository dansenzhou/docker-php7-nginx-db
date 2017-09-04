# docker-php7-nginx-db
Docker compose for symfony/php projects with php 7.1, nginx, mysql database.
Project files go to app folder

# Create Docker VM:
docker-machine create -d virtualbox --virtualbox-memory 2048 --virtualbox-cpu-count 2 docker-app

# Start VM
docker-machine start docker-app

# Build&Run containers
docker-compose up -d


