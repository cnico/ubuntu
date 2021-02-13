## Ubuntu Dockerfile


This repository contains **Dockerfile** of [Ubuntu](http://www.ubuntu.com/) for [Docker](https://www.docker.com/).
It is not published anywhere and is simply a helper image for dev on my laptop.


### Usage
After cloning this repo and being in the pulled directory :

    docker build -t "ubuntu-pip" .
    docker run -it --rm dockerfile/ubuntu

Once in the container : 

    pip3 --version
    pyhon3 --version
    ...


