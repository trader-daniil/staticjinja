# StaticJinjaPlus

В репозитории содержатся два DockerFile для создания образа с приложением [StaticJinjaPlus](https://github.com/trader-daniil/StaticJinjaPlus)

# Образы

В репозитории есть 2 образа:

- Dockerfile.python где в качестве базового слоя выбран python
- Dockerfile.ubuntu где в качестве базового слоя выбран ubuntu

# Запуск

Для создания образа воспользуйтесь командой [build](https://docs.docker.com/reference/cli/docker/), укажите нужный файл сброки аргументом [-f](https://www.baeldung.com/ops/multiple-dockerfiles) после укажите путь к нужному файлу

