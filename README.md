# docker + nginx (http2)

### build & run
```
$ docker build --tag testapp .
$ ...
$ docker run -d --name testapp -p 443:443 -p 8081:80 testapp
$ 165c5df24780f42af219b54efc147a15e6a299d6e4dd0f3a6837cb0c1b92f252
```

### check
open browser and go `localhost:8082`

### stop or remove
```
$ docker stop 165c5df24780f42af219b54efc147a15e6a299d6e4dd0f3a6837cb0c1b92f252
$ docker rm 165c5df24780f42af219b54efc147a15e6a299d6e4dd0f3a6837cb0c1b92f252
```