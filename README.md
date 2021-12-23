# docker-container

## build all
```
docker-compose up -d --build
```

## build only mysql service
```
docker-compose up -d --build mysql
```

## start all
```
docker-compose start
```

## stop all
```
docker-compose stop
```

## start only mysql
```
docker start mysql
```

## stop only mysql
```
docker stop mysql
```

## ssh to mysql service
```
docker exex -it docker-container_mysql_1 bash
```
