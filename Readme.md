# Git on Docker (Alpine Linux Image)

## Save Dockerfile on a folder Ex: Git
**Caution: Only one dockerfile per folder**

### Generate image

docker build -t `<name>` .

`<name>` = Ex: apache or your_docker_hub_name/dhcp:1.0

### Running Container

docker run -it `<name>` /bin/sh

### If don't generate image, get from docker hub

docker run -it paulocorreia/alpine_git:1.0 /bin/sh

### Testing

inside your container type git help
