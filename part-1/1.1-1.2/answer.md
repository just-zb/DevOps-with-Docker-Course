# 1.1

```bash
docker run -d nginx
docker run -d nginx
docker run -d nginx
docker ps
CONTAINER ID   IMAGE     COMMAND                  CREATED         STATUS         PORTS     NAMES
7b5ff74b0799   nginx     "/docker-entrypoint.…"   3 seconds ago   Up 2 seconds   80/tcp    suspicious_lovelace
050310f29e8e   nginx     "/docker-entrypoint.…"   4 seconds ago   Up 3 seconds   80/tcp    crazy_merkle
6a7b1d61fa35   nginx     "/docker-entrypoint.…"   5 seconds ago   Up 4 seconds   80/tcp    cranky_wilson

docker stop 7b5 050
7b5
050

docker ps -a
CONTAINER ID   IMAGE     COMMAND                  CREATED              STATUS                      PORTS     NAMES
7b5ff74b0799   nginx     "/docker-entrypoint.…"   About a minute ago   Exited (0) 58 seconds ago             suspicious_lovelace
050310f29e8e   nginx     "/docker-entrypoint.…"   About a minute ago   Exited (0) 58 seconds ago             crazy_merkle
6a7b1d61fa35   nginx     "/docker-entrypoint.…"   About a minute ago   Up About a minute           80/tcp    cranky_wilson
```



# 1.2

```bash
docker stop 6a7

docker ps -a
CONTAINER ID   IMAGE     COMMAND                  CREATED         STATUS                      PORTS     NAMES
7b5ff74b0799   nginx     "/docker-entrypoint.…"   4 minutes ago   Exited (0) 3 minutes ago              suspicious_lovelace
050310f29e8e   nginx     "/docker-entrypoint.…"   4 minutes ago   Exited (0) 3 minutes ago              crazy_merkle
6a7b1d61fa35   nginx     "/docker-entrypoint.…"   4 minutes ago   Exited (0) 11 seconds ago             cranky_wilson

docker rm 7b5 050 6a7
7b5
050
6a7

docker image rm nginx
Untagged: nginx:latest
Untagged: nginx@sha256:9ff236ed47fe39cf1f0acf349d0e5137f8b8a6fd0b46e5117a401010e56222e1
Deleted: sha256:48b4217efe5ed7e85a8946668b6adedb8242a5433da2c53273fb4c112f4c5d99
Deleted: sha256:a909fbe8bfce66857a1656f2af048458e6f337e11a8de903b667687871d280ea
Deleted: sha256:bc98d56e2bbc34c558e86313efe3cf1594217d6d69b9e65a548b1006ea0d0b76
Deleted: sha256:666b6e3f5b6d6edbccf1398c7616cdfa504a92702870b1654dbaba54cf94be62
Deleted: sha256:424e350eea49081757fcdd45a0c69edf0db3ebe48caf482a6933cd1a7f950d05
Deleted: sha256:de92af9aad4b7a5966d4fcf033af04c89bb26f09c9965832d63b0bb6be353189
Deleted: sha256:600b64cb4d8a8d46b359be2be3564fb8b4a7e8775698ec2eacf4f2a004e85234
Deleted: sha256:6e5a1bc9659a34c2721239cd7ba5c8a14200f98c6e2c49531ba6559aa1c43f67

docker ps
CONTAINER ID   IMAGE     COMMAND   CREATED   STATUS    PORTS     NAMES

docker image ls
REPOSITORY               TAG       IMAGE ID       CREATED         SIZE
```

