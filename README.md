# Webpack Starter Configuration

Este es el proyecto inicial para crear aplicaciones utilizando **Webpack**.

### Notas previas:

Reconstrucción de los módulos de Node
```
npm install
```

#### Creación del directorio */dist* :dvd:
```
npm run build
```

Por defecto, se ha configurado Webpack para que cuando se use el comando ```npm run build``` lance la aplicación en modo **producción**. Para poder correrlo en modo de **desarrollo** es necesario ejecutar ```npm run build:dev```

#### Lanzar Webpack Dev Server :rocket:

La configuración inicial contempla el servidor local de desarrollo mediante el comando ```npm start```, abriendo un servidor en el puerto (por defecto 8080).