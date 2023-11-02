# 🌐 Proyecto: API Unificada para SQL y NoSQL

Este proyecto es una API unificada diseñada para interactuar con bases de datos SQL y NoSQL, facilitando el manejo de operaciones de datos con un modelo de cliente común y una interfaz de programación coherente.

## Requisitos previos

Para ejecutar este proyecto, necesitarás:

- [Node.js](https://nodejs.org/): Entorno de ejecución para JavaScript.
- [XAMPP](https://www.apachefriends.org/index.html): Para MySQL en un entorno de desarrollo local.
- [MongoDB Atlas](https://www.mongodb.com/cloud/atlas): Para alojar la base de datos NoSQL en la nube.

## Instalación de Dependencias

Este proyecto requiere las siguientes dependencias principales:

- `express`: Para la creación del servidor web y manejo de rutas.
- `sequelize`: ORM para interactuar con MySQL.
- `mongoose`: ODM para interactuar con MongoDB.
- `dotenv`: Para manejar variables de entorno.
- `cors`: Para habilitar CORS.
- `morgan`: Para el registro de solicitudes HTTP.
- `mysql2`: Cliente MySQL para Node.js.
- `nodemon`: Para reiniciar automáticamente el servidor durante el desarrollo.

Para instalar todas las dependencias necesarias, ejecuta el siguiente comando:

```bash
npm install
