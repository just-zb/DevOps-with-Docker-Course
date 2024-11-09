# 1.3
```bash
docker run -d --name devops --rm -it devopsdockeruh/simple-web-service:ubuntu

docker exec -it devops tail -f ./text.log 

Secret message is: 'You can find the source code here: https://github.com/docker-hy'
```
# 1.4
```bash
docker run -d --name ubuntu_test --rm -it ubuntu 
docker exec ubuntu_test apt-get update
docker exec ubuntu_test apt-get -y install curl
docker exec -it ubuntu_test sh -c 'while true; do echo "Input website:"; read website; echo "Searching.."; sleep 1; curl http://$website; done'
helsinki.fi

<html>
<head><title>301 Moved Permanently</title></head>
<body>
<center><h1>301 Moved Permanently</h1></center>
<hr><center>nginx/1.24.0</center>
</body>
</html>
```
