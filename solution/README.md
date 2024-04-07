# Installation de Docker Engine (docker et docker-compose)
sudo apt update
sudo apt install -y docker.io
sudo systemctl enable docker --now

docker --version
docker-compose --version

Reference : https://www.kali.org/docs/containers/installing-docker-on-kali/ 


# Désactiver l'antivirus
Sur votre machine physique (Windows?)

# Exécuter les commandes
Sur votre machine hôte (Kali Linux)


## Terminal 1 
docker-compose build --no-cache
docker-compose up -d


## Terminal 2 : Zion
docker exec -it zion /bin/bash

## Terminal 3 : Neo
docker exec -it neo /bin/bash

## Terminal 4 : Smith
---------------------
docker exec -it smith /bin/bash
ssh root@10.0.0.4



# Trouble shooting
docker-compose down

docker network ls
docker network rm network_ID

docker images ls
docker rmi image_ID

docker container ls
docker rm container_ID

docker ps --all
docker stop container_ID
docker container prune


