# ubuntu

### Настройка

#### Первые команды 

```cmd
sudo apt-get update && sudo apt-get install -y lsb-release && sudo apt-get clean all && sudo apt -y install python3-pip clang git vim cmake curl
```
Проверить версию ubuntu

```cmd
lsb_release -a
```

#### Настройка

##### vim

[Vundle](https://github.com/VundleVim/Vundle.vim)

Поменять второе имя в консоли

```
sudo hostnamectl set-hostname новое_имя
```

Telegram
```
sudo apt install telegram-desktop
```

# ubuntu_in_docker

Чтобы создать контейнер с ubuntu 20.04
```cmd
docker run -it ubuntu:20.04
```


Release:	20.04
Codename:	focal

```
