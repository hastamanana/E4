Как системному администратору данной организации вам поставлена задача собрать на докер образ Django
(Linux, nginx, Django, Postgres, Gunicorn) сервера. Все нужные сервисы должны быть проброшены на хост по стандартным
портам, реализация HTTPS не требуется, версии Django, nginx и Postgres не имеют значения, как и версия ядра Linux.
В проекте просто должна работать админка с заранее прописанным логином и паролем.

`https://www.docker.com/` //Установка Docker Desktop

После установки docker, загружаем проект на git

`sudo docker-compose up -d` //В среде lunix
`docker-compose up -d` //Docker Desktop (Windows или Macos)

логин: admin  
пароль: admin
