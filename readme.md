This repository is a docker-compose file of the vaultwarden project to self host a vaultwarden server.
All the credits for vaultwarden goes to https://github.com/dani-garcia/vaultwarden/

# I/ Prerequisite

You need to have a Domain Name or a subdomain. 

# II/ Installation

- Pull the project and go into the directory : 

`git pull https://github.com/Yusi-San/docker-compose-vaultwarden.git`

`cd docker-compose-vaultwarden`

- Change the environment variables :

And add your email, admin token and domain/subdomain in it.

`nano .env`

You can generate a strong admin token with the command : 

`openssl rand -base64 48`

- Start :  

`docker-compose up -d`

