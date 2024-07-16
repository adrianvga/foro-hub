# Forohub

Forohub es una API REST de foro desarrollada en Java con Spring Boot, que permite a los usuarios crear, leer, actualizar y eliminar tópicos de discusión. 

## Funcionalidades

* Autenticación de usuarios utilizando JWT (JSON Web Token).
* Creación de nuevos usuarios.
* Creación, lectura, actualización y eliminación de tópicos.
* Listado de tópicos paginados y ordenados por fecha de creación.
* Validación de integridad para evitar la creación de tópicos duplicados y usuarios con datos duplicados.

## Tecnologías Utilizadas

* Java 21
* Spring Boot
* Spring Security
* Spring Data JPA
* MySQL
* JWT (JSON Web Token)
* Lombok



## Configuración
* Configura tu base de datos MySQL y asegúrate de que esté accesible en `application.properties`.
* Asegúrate de que la configuración de seguridad JWT esté correctamente establecida en `application.properties`.
* Ejecuta la aplicación desde tu IDE.

## Uso

* Registra nuevos usuarios utilizando el endpoint `/registrar`.
* Inicia sesión utilizando el endpoint `/login` para obtener un token JWT válido.
* Utiliza los endpoints `/topicos` para crear, listar, actualizar y eliminar tópicos.
* usa el token JWT para validar tu acceso
