# Instalación de MongoDB (versión libre Community Server)

## Instalación de mongod (servidor) 

1. Descarga el paquete de instalación desde [mongo](https://www.mongodb.com/try/download/community)

2. Durante la instalación desmarcar la instalación como servicio y mantener marcado la instalación
de Mongo Compass (GUI)

3. Se instala en:
```
C:\Program Files\MongoDB\Server\5.0\bin
````

4. Variable de entorno:

Editar las variables de entorno del sistema -> Variables de entorno -> Variables del sistema -> Path -> Editar y
pegamos una nueva con la ruta C:\Program Files\MongoDB\Server\5.0\bin

Comprobamos escribiendo mongod en cualquier ubicación

5. Crear directorio de datos

Creamos un directorio, por ejemplo, mongoData, en nuestro usuario

6. Levantado de servidor

```
mongod --dbpath <ruta-directorio-datos>
```

Levanta el servidor en localhost:27017 // --port <puerto> se puede levantar en un puerto diferente


