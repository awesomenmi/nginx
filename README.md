# Web сервера 

[Ссылка](https://hub.docker.com/r/41201506/nginx-antiddos) на образ в Dockerhub.

Команды для работы с образом:

```
docker pull 41201506/nginx-antiddos:latest
docker run -p 80:80 41201506/nginx-antiddos:latest
```

```
[root@localhost homew26]# curl http://localhost/otus.txt
<html>
<head><title>302 Found</title></head>
<body>
<center><h1>302 Found</h1></center>
<hr><center>nginx/1.19.0</center>
</body>
</html>
```

![alt-текст](https://github.com/awesomenmi/nginx/blob/master/Screenshot%20from%202020-07-09%2023-01-10.png)

