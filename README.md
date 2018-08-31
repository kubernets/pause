# pause

github addr [https://github.com/kubernets/pause](https://github.com/kubernets/pause)

docker hub addr [https://hub.docker.com/u/kubernets](https://hub.docker.com/u/kubernets)

use shell script to pull docker image and replace origin tag

> wget https://github.com/kubernets/pause/raw/master/get-pause-image.sh

## Arch and Version

- [**amd64** 3.1](https://hub.docker.com/r/kubernets/pause-amd64)

    > docker pull kubernets/pause-amd64:3.1

    > docker tag kubernets/pause-amd64:3.1 gcr.io/google_containers/pause-amd64:3.1 

    > docker rmi kubernets/pause-amd64:3.1
