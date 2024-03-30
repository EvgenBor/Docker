### Сборка образа

sudo docker build . -t my_nginx

### Запуск контейнера

sudo docker run -d -p 8080:80 my_nginx