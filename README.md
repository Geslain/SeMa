# SeMa

![logo.png](logo.png)

SeMa is a tool made for bulk SMS send. SeMa simply stand for SEnd MessAge.


## Description

Please look into [api](api) and [client](client) for more information

## Install project

This project use the concept of [git submodules](https://git-scm.com/book/en/v2/Git-Tools-Submodules). In order to clone the project and its submodules you have to use the following command:

```
git clone --recursive git@github.com:Geslain/SeMa.git
```

## Start project

* First create a `.env` file. Environment variables are listed in `.env.template` file.

```
cp .env.template .env
```

* (Optional) Install [docker](https://docs.docker.com/engine/install/) and [docker compose](https://docs.docker.com/compose/install/)
* Launch docker compose
```
docker compose up
```
