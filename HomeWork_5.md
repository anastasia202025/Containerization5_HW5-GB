Создаем директорию "compose" и переходим в неё:
mkdir compose

cd compose

В данной директории создаем файл "compose.yaml" и меняем его содержимое:
nano compose.yaml
![Alt text](image.png)

Создаем сервис из 2-х контейнеров (web и db)

![Alt text](image-1.png)
Запуск Docker Compose:
docker-compose up -d

Проверяем активность контейнера

docker-compose ps
![Alt text](image-2.png)
