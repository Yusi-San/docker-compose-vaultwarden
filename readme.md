This repository is a docker-compose file of the vaultwarden project to self host a vaultwarden server.
All the credits for vaultwarden goes to https://github.com/dani-garcia/vaultwarden/

I/ Prerequisite

You need to have a Domain Name or a subdomain. 

II/ Installation

- Debian : 
sudo apt update
sudo apt install docker docker-compose

git pull https://github.com/Yusi-San/docker-compose-vaultwarden.git

cd docker-compose-vaultwarden

You can generate a strong admin token with the command : 

openssl rand -base64 48

Change the environment variables :

nano .env

add your email

docker-compose up -d

