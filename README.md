# primos-checkins

Hay que activar el Contenido No Seguro del sitio para que funcione correctamente

### Instalación:
Disclaimer: **Esta herramienta solo funciona en la máquina prime**
(Esto por configuraciones con el sistema de login de Microsoft)

Una vez clonado el repo en la máquina:
```
./run.sh
```
Estaría bueno crear un docker-compose.yml para esto, anótalo Mario Hugo


# Información general sobre servicios de primos

Todos los servicios que tiene Primos están o deberían estar alojados en prime.
Prime es una máquina dentro del departamento de infromática.

### Para acceder a prime desde la red de la U:
- Acceder a APU
- Desde APU ejecutar:
```
ssh primo@prime
```

Podrán ver el estado de los servicios (todos en Docker container) ejecutando:
```
docker ps -a
```
