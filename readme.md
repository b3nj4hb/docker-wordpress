# Dependencias
``` bash
paru -S docker docker-compose
sudo systemctl start docker
sudo usermod -aG docker $USER
```
# Iniciar archivo Docker Compose
``` bash
docker-compose up -d
```
# Comandos
``` bash
# Listar containers en la pc
docker ps
docker ps -a
# Imagenes
docker images
docker rmi nombre
docker rmi $(docker images -q)
# Configurar wordpress
http://localhost:8000
# Entrar en el contenedor
docker exec -it nombre_del_contenedor bash
# Detener contenedor
docker stop id
# Eliminar contenedor
docker rm id
docker rm $(docker ps -a -q)
```
