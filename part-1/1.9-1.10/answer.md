# 1.9

```bash
docker run -it -d -v "$(pwd)/text.log:/usr/src/app/text.log" devopsdockeruh/simple-web-service

tail -f text.log
2024-11-09 11:25:20 +0000 UTC
2024-11-09 11:25:22 +0000 UTC
2024-11-09 11:25:24 +0000 UTC
2024-11-09 11:25:26 +0000 UTC
2024-11-09 11:25:28 +0000 UTC
Secret message is: 'You can find the source code here: https://github.com/docker-hy'
```



# 1.10

```bash
docker run -it -d -p 8888:8080 devopsdockeruh/simple-web-service server

```

![CleanShot 2024-11-09 at 1 .32.01@2x](/Users/michael/Library/Application Support/CleanShot/media/media_VKps3tvIex/CleanShot 2024-11-09 at 1 .32.01@2x.png)