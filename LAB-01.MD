# Host Networking


## Comando a ejecutar en la maquina vagrant, que será nuestro host de ambiente docker.
```
docker run --name=busybox -it --rm --network=host busybox ip addr 
```

## Comando a ejecutar en la máquina vagrant
```
ip addr
```
