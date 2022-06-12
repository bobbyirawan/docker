# docker

## create image 
```
docker build --tag app-golang:1.0 .
```
## create container
```
docker container create --name app1 -p 8080:8080 app-golang:1.0
```


##### container

1. run container 
```
docker container start app1
```

2. cek run container
```
docker container ls
```

3. cek list container 
```
docker container ls -a
```

4. cek log container
```
docker container logs  name_container
```




