# VideoSockets
Esta aplicación desarrollada en Nodejs y React, le permite visualizar un video en muchos clientes y pausarlo/reproducirlo, afectando a todos los clientes al mismo tiempo.

# Instalación
Comandos para instalar:
```
npm install
```

# Ejecución del server
Para ejecutar el server correr el comando:
```
npm start
```
Iniciará un servidor en el puerto 3000 y para acceder al frontend hay que ir a esta url: http://localhost:3000/
(el mismo servidor sirve los archivos del front)

# Tests e2e
Están desarrollados con **Cypress**. Están en la siguiente carpeta: **cypress/integration/tests**

Correr pruebas con:
```
node_modules/.bin/cypress open
```

# Archivos
El código fuente se encuentra en la carpeta **src**.

**Backend:** el archivo **index.es6.js** contiene el código del backend. **index.js** es la versión traspilada a ES5.

**Frontend:** En la carpeta **front** se encuentra el código del frontend.
