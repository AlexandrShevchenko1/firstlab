## Как запустить Docker-контейнер с JupyterHub

### Шаг 0:
Открыть терминал
### Шаг 1:
Склонировать репозиторий на локальный компьютер. (В окне терминала ввести следующую команду:
```
git clone https://github.com/xzescha/docker-jupiter/tree/main
```
### Шаг 2:
Создать docker-образ при помощи следующей команды:
```
docker build -t <имя образа> <путь к образу на компьютере (скорее всего папка загрузки (Windows) или /Users/<username>(Mac))>/docker-jupyter
```
### Шаг 3:
Запустить контейнер с образом с помощью команды ниже:
```
docker run --name <имя контейнера> -p 80:8000 <имя образа>
```
### Шаг 4:
Наслаждаться!
## Конец!
