### Сборка образа

docker build -t stock_products .

### Запуск контейнера

docker run --name stock_products_container -d -p 8000:8000 stock_products