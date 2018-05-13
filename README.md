# Node Red on Docker

## Build Image as Container
```
docker build -t prongbang/nodered .
```

## Start Container
```
docker run -d --restart=always -p 1880:1880 prongbang/noderedi:latest
```

## List process
```
docker ps
```