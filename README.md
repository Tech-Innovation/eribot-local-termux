# Eribot Local Termux

## Description

On this repository you will find a guide about how to install all the software that is used on the Eribot Controller Device.

## Requirements

## Install

Clone the repositories
[Eribot Termux](https://github.com/Tech-Innovation/eribot-local-termux)

[Eribot Local Service](https://github.com/Tech-Innovation/eribot-local-service)

[Eribot Local Sync](https://github.com/Tech-Innovation/eribot-local-sync)

[Eribot Local Plataform Frontend](https://github.com/Tech-Innovation/eribot-local-plataform-frontend)

To the Termux terminal with git clone

## .bashrc file

``` bash
node-red &
cd ~/eribot-local-service/ ./start.sh &
cd ~/eribot-local-sync/ ./start.sh &
cd ~/eribot-local-plataform-frontend/ ./start.sh &
```
