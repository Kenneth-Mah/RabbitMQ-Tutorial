# RabbitMQ-Tutorial

https://www.rabbitmq.com/getstarted.html

RabbitMQ Tutorials 1-5 completed using VS Code Dev Containers.

### How dev container works

Basic understanding of dev container is that in the .devcontainer file, devcontainer.json refers to docker-compose.yml, which in turn refers to Dockerfile.

Use the "postCreateCommand" property in the devcontainer.json to manage the installation of additional software (referencing the requirements.txt file).

### Repository notes

Each subdirectory is supposed be a standalone tutorial. Due to the repository's resulting file structure, dev container only works in the subdirectories. 

The docker-compose.yml in the parent directory allows for the initialisation of a standalone docker container (not the one used in the tutorials). It is started using the following command:
```
docker compose up
```
