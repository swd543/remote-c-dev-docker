# remote-c-dev-docker
Docker templates for remote development of C++ apps without cluttering your system.

# Initalizing
Run `docker-compose up -d` to set up the build image and run it as a daemon.

# Set up
In CLion, set up a `docker` profile for remote debug and deployment as mentioned in [this article](https://austinmorlan.com/posts/docker_clion_development/).
Pull Docker and compose files by `https://raw.githubusercontent.com/swd543/remote-c-dev-docker/master/docker-compose.yml`

# Credits
A brilliant article by Austin Moran https://austinmorlan.com/posts/docker_clion_development/.