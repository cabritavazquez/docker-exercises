```bash
$docker pull nginx
$docker images # Mostrar la imagen
$docker run -d --name lcabrita-nginx nginx
$docker ps # Mostrar contendedor corriendo
$docker stop lcabrita-nginx
$docker ps -a
$docker run lcabrita-nginx
$docker exec -it  lcabrita-nginx sh
$docker stop lcabrita-nginx
$docker rm lcabrita-nginx
$docker rmi lcabrita-nginx
```