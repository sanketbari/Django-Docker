# Django-Docker
Setting up a simple Django/PostgreSQL infrastructure using docker-compose and dockerfile.

# Dockerfile
The Dockerfile defines an application’s image content via one or more build commands that configure that image. Once built, you can run the image in a container.

# docker-compose.yml
The docker-compose.yml file describes the services that make your app. In this example those services are a web server and database. The compose file also describes which Docker images these services use, how they link together, any volumes they might need mounted inside the containers.

# requirements.txt
The requirements.txt file enlists the required softwares. The requirements.txt file is referenced in the dockerfile so that the softwares could get downloaded.
