Посмотреть список образов  
```
docker images
```

Сохранить репозиторий в архив:
```
docker save REPOSITORY > File.tar
```



Формат Dockerfile:
```
FROM ubuntu:16.04  
RUN  apt update
```

Собрать образ:
```
docker build .
или
docker build - < Dockerfile
или
docker build -t ImageName
```

Удалить образ
```
docker rmi ImageId/ImageName
```
