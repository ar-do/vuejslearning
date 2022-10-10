# vue_docker

#### Build Container
```
docker build -t dockerized-vue/dockerized-vue-app .
```

#### Run Container

```
docker run -it -p 8080:80 --rm --name dockerized-vue-app-1 dockerized-vue/dockerized-vue-app
```

Access App on localhost:8080

