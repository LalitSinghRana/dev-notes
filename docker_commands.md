# Docker Commands

### START WSL :
> - wsl

### START DOCKER
> - sudo dockerd

### BUILD AN IMAGE (FROM A DOCKER FILE)
> - docker build -t {image_name:version} .

### START A NEW CONTAINER (FROM AN IMAGE)
> - docker run {image_name:version}
> - docker run -p {local_port}:{container_port} {image_name:version}

### STOP A RUNNING CONTAINER
> - docker ps
> - docker stop {container Id}

### REMOVE AN IMAGE
> - docker images
> - docker image rm {image_name:version}
> - docker image rm {image_name:version} --force