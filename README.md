# ubuntu_in_docker

Чтобы создать контейнер с ubuntu 20.04
```cmd
docker run -it ubuntu:20.04
```

# Настройка

#### Первые команды 

```cmd
apt-get update && apt-get install -y lsb-release && apt-get clean all && apt -y install python3-pip
```
Проверить версию ubuntu

```cmd
lsb_release -a
```

В идеале выведет

```cmd
Distributor ID:	Ubuntu
Description:	Ubuntu 20.04.4 LTS
Release:	20.04
Codename:	focal

```
