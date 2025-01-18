# 1.5
```bash
docker pull devopsdockeruh/simple-web-service:alpine

docker image ls
REPOSITORY                          TAG       IMAGE ID       CREATED         SIZE
devopsdockeruh/simple-web-service   ubuntu    4e3362e907d5   3 years ago     83MB
devopsdockeruh/simple-web-service   alpine    fd312adc88e0   3 years ago     15.7MB

docker run -d --name alpine --rm -it devopsdockeruh/simple-web-service:alpine
docker exec -it alpine sh

/usr/src/app # tail -f ./text.log
2024-11-08 22:43:17 +0000 UTC
2024-11-08 22:43:19 +0000 UTC
2024-11-08 22:43:21 +0000 UTC
2024-11-08 22:43:23 +0000 UTC
2024-11-08 22:43:25 +0000 UTC
Secret message is: 'You can find the source code here: https://github.com/docker-hy'
```



# 1.6

```bash
docker run -it devopsdockeruh/pull_exercise


Unable to find image 'devopsdockeruh/pull_exercise:latest' locally
latest: Pulling from devopsdockeruh/pull_exercise
8e402f1a9c57: Pull complete
5e2195587d10: Pull complete
6f595b2fc66d: Pull complete
165f32bf4e94: Pull complete
67c4f504c224: Pull complete
Digest: sha256:7c0635934049afb9ca0481fb6a58b16100f990a0d62c8665b9cfb5c9ada8a99f
Status: Downloaded newer image for devopsdockeruh/pull_exercise:latest
WARNING: The requested image's platform (linux/amd64) does not match the detected host platform (linux/arm64/v8) and no specific platform was requested
Give me the password: basics
You found the correct password. Secret message is:
"This is the secret message"
```

