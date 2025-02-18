# Django-crm-Mysql-Docker-Container
Implement for Django-CRM project MySQL container powered by Docker

This is an implementation for [Django-CRM](https://github.com/DjangoCRM/django-crm) main project and implement a simple docker compose file to create a MySQL container DB for the application.

## Pre-requirement ##
- You need a linux (Ubuntu, Fedora, Debian, etc...) workstation
- You need a local copy of Django-CRM repo
- You need a docker engine installed, follow this [Official Docker Installation Guide](https://docs.docker.com/engine/install/)

## Installation instruction ##
Clone or download the project and copy the docker folder inside Django-CRM project folder.
![Docker folder Example](/img/dockerfolder.png "docker folder")
Inside the docker folder run `./start_dev.sh` shell command, this include:
- Clean up previous MySQL docker
- Configure new Django-CRM container (also download mysql engine image)
- Install all requirements for Django-CRM project
- Setup all data inside DB
- Start the application Django-CRM

![docker running](/img/docker_running.png "running")
  
