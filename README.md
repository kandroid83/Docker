# Домашнее задание к занятию 4 «Оркестрация группой Docker контейнеров на примере Docker Compose»

## Задание 1 
https://hub.docker.com/repository/docker/android83/custom-nginx/general

## Задание 2

### 1. Запустите ваш образ custom-nginx:1.0.0 командой docker run в соответвии с требованиями:
    имя контейнера "ФИО-custom-nginx-t2"
    контейнер работает в фоне
    контейнер опубликован на порту хост системы 127.0.0.1:8080
![Com-1](Com-1.png)


### 2. Не удаляя, переименуйте контейнер в "custom-nginx-t2"
### 3. Выполните команду date +"%d-%m-%Y %T.%N %Z" ; sleep 0.150 ; docker ps ; ss -tlpn | grep 127.0.0.1:8080  ; docker logs custom-nginx-t2 -n1 ; docker exec -it custom-nginx-t2 base64 /usr/share/nginx/html/index.html
### 4. Убедитесь с помощью curl или веб браузера, что индекс-страница доступна.
![Com-2-4](Com-2-4.png)
![Cont-1](Cont-1.png)
