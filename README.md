## Docker basic commands
```
docker pull -> descarga una imagen de la red. 
docker build -> construye una imagen.
docker run [-p 8080:80] [--name=<nombre_contenedor>] <nombre_imagen> -> lanza un contenedor.
docker run -it <nombre_imagen> -> lanza un contenedor manteniedo la entrada estandar abierta y usando el terminal por defecto.
docker exec <container_name> <command> -> ejecutamos un comando en el contenedor.
docker stop -> para un contenedor.
docker rm <container_name> -> elimina un contenedor.
docker rmi <image_id> -> elimina una imagen.
docker ps -> contenedores en ejecución.
docker ps -a -> contenedores en ejecución y parados.
docker images -> imagenes descargadas o construidas.
```
