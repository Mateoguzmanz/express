# API REST con Express para CRUD de Usuarios y Autenticación JWT con MongoDB
Este repositorio contiene una API REST desarrollada con Express que permite realizar operaciones CRUD (Crear, Leer, Actualizar, Eliminar) de usuarios, además de proporcionar un sistema de autenticación mediante tokens JWT (JSON Web Tokens). La aplicación utiliza MongoDB como base de datos para almacenar la información de los usuarios.

#Requisitos previos
Asegúrate de tener instalado Node.js y MongoDB en tu sistema antes de comenzar.
Node.js
MongoDB

#Configuración
Clona este repositorio en tu máquina local:
bash
Copy code
git clone https://github.com/tuusuario/api-rest-express-mongodb-jwt.git

#Instala las dependencias:
bash
Copy code
cd api-rest-express-mongodb-jwt
npm install

#Configura las variables de entorno:
Crea un archivo .env en la raíz del proyecto y define las siguientes variables:

#env
Copy code
PORT=3000
MONGODB_URI=tu_conexion_a_mongodb
SECRET_KEY=secreto_para_jwt
Sustituye tu_conexion_a_mongodb con la conexión real a tu base de datos MongoDB y secreto_para_jwt con una cadena secreta para firmar los tokens JWT.

Uso
#Inicia el servidor:
bash
Copy code
npm start
La API estará disponible en http://localhost:4000 (o el puerto que hayas configurado).

#Autenticación JWT:
Para realizar operaciones que requieren autenticación, incluye el token JWT en la cabecera de la solicitud:

http
Copy code
Authorization: Bearer tu_token_jwt

#Contribuciones
¡Las contribuciones son bienvenidas! Si encuentras algún problema o tienes alguna sugerencia, por favor, crea un issue o envía un pull request.

#Licencia
Este proyecto está bajo la Licencia MIT. Consulta el archivo LICENSE para más detalles.
