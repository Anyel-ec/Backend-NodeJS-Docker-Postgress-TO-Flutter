### Instrucciones simplificadas para poner en marcha el servicio utilizando Docker:

1. Asegúrate de tener Docker en funcionamiento (ya sea Docker Desktop o el Demonio de Docker).
2. Haz una copia del archivo llamado __.env.template__ y cámbiale el nombre por __.env__.
3. Inicia los servicios ejecutando el siguiente comando en la terminal:
```
docker compose up -d
```
4. Llena la base de datos con datos temporales accediendo a este enlace en tu navegador:
```
http://localhost:3000/api/seed
```
5. Encuentra la documentación de los puntos finales disponibles aquí:
```
http://localhost:3000/api
```
Espero que esto te resulte más claro.