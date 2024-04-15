```bash
$docker build -t mi-nginx:1.0 .
$docker run -it -d -p 8080:80 --name nginx mi-nginx:1.0

# Ojo con el Dockerfile COPY
```