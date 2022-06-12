# docker

## create image 
```
docker build --tag app-golang:1.0 .
```
## create container
```
docker container create --name app1 -p 8080:8080 app-golang:1.0
```

## run container 
```
docker container start app1
```

