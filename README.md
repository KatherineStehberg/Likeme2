Desafío 4 de Backend con Node y Express

Instrucciones:
Uso de la base de datos
Se debe utilizar la base de datos "likeme" del proyecto anterior. Si no está creada, sigue estos pasos:

Crear la base de datos 'likeme' con el siguiente comando:

sql
Copiar código
CREATE DATABASE likeme;
Crear la tabla 'posts' con el siguiente comando:

sql
Copiar código
CREATE TABLE posts (
    id SERIAL,
    titulo VARCHAR(25),
    img VARCHAR(1000),
    descripcion VARCHAR(255),
    likes INT
);
Instrucciones generales para cargar el proyecto
Ejecutar npm install en los directorios /backend y /frontend para instalar las dependencias necesarias.

Renombrar el archivo '.env.template' (que contiene solo los nombres de las variables de entorno sin datos) a '.env' en el directorio /backend. Completa la información de las variables de entorno como sigue:

PORT: Puerto del backend
PGHOST: Host de la base de datos
PGUSER: Usuario de la base de datos
PGPASSWORD: Contraseña del usuario de la base de datos
PGDATABASE: Nombre de la base de datos
PGPORT: Puerto habilitado para conectarse a la base de datos

Para ejecutar el proyecto completo, usa el comando npm run dev en los directorios /backend y /frontend para levantar ambos servidores. Luego, accede a la URL del servidor de frontend para interactuar con la aplicación.

