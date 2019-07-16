# docker + nginx (http2)

### build & run
```
$ docker build --tag testapp .
$ ...
$ docker run -d --name testapp -p 443:443 -p 8082:80 testapp
$ ${UID}
```

### check
open browser and go `localhost:8082`

### stop or remove
```
$ docker stop ${UID}
$ docker rm ${UID}
```