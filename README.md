## Ubuntu Dockerfile


This repository contains a **Dockerfile** of [Ubuntu](http://www.ubuntu.com/) for [Docker](https://www.docker.com/).
It is not published in docker hub and is simply a helper image for dev on my laptop mainly for [homeassistant core developpement](https://developers.home-assistant.io/docs/development_environment)

### Usage
After cloning this repo and being in the pulled directory :
    docker build -t "ubuntu-py" .
    docker run -it --name "ubuntu-py" ubuntu-py
    docker rm ubuntu-py

Once in the container : 

    pip3 --version
    pyhon3 --version
    ...

### Credits
It is a fork of an old official [ubuntu image](https://github.com/dockerfile/ubuntu)

