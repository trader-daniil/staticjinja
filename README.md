# StaticJinjaPlus

В репозитории содержатся два DockerFile для создания образа с приложением [StaticJinjaPlus](https://github.com/trader-daniil/StaticJinjaPlus)

# Образы

В репозитории есть 2 образа:

- Dockerfile.python где в качестве базового слоя выбран python
- Dockerfile.ubuntu где в качестве базового слоя выбран ubuntu

# Запуск

Для создания образа воспользуйтесь командой [build](https://docs.docker.com/reference/cli/docker/), укажите нужный файл сброки аргументом [-f](https://www.baeldung.com/ops/multiple-dockerfiles) после укажите путь к нужному файлу

# Поддержка 

Для того, чтобы добавить новую версию в образ на [DockerHub](https://hub.docker.com/repository/docker/traderdaniil/static-jinja-plus/general), создайте образ из вашего контейнера при помощи команды [commit](https://docs.docker.com/reference/cli/docker/container/commit/) в названии образа укажите traderdaniil/static-jinja-plus:<версия_вашего_образа>. Затем Вы можете залить свою версию образа на Dockerub, используя команды [push](https://docs.docker.com/reference/cli/docker/image/push/), указав тег traderdaniil/static-jinja-plus:<версия_вашего_образа>. Вы сможете залить образ только формата  traderdaniil/static-jinja-plus:<версия_вашего_образа>, если Вы назвали свой образ иначе, то переименуйте его, используя команду [tag](https://docs.docker.com/reference/cli/docker/image/tag/)

