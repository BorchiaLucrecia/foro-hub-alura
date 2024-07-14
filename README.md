# ForoHub
**Alumno: Leila Lucrecia Borchia  
Curso: Alura Latam + Oracle, Especialización Backend**

Bienvenido a ForoHub, una API REST para gestionar tópicos en un foro, creada como parte del desafío del curso de Especialización Backend de Alura Latam + Oracle.

## Descripción

ForoHub es una API que permite a los usuarios realizar operaciones CRUD (Crear, Leer, Actualizar, Eliminar) sobre tópicos en un foro. Esta API está desarrollada usando Spring Boot y sigue las mejores prácticas del modelo REST. Las principales funcionalidades incluyen:

- Crear un nuevo tópico
- Mostrar todos los tópicos creados
- Mostrar un tópico específico
- Actualizar un tópico
- Eliminar un tópico

## Tecnologías Utilizadas

- **Java** (versión 17 o superior)
- **Maven** (versión 4 o superior)
- **Spring Boot** (versión 3 o superior)
- **MySQL** (versión 8 o superior)

## Dependencias

Las dependencias necesarias para este proyecto incluyen:

- Lombok
- Spring Web
- Spring Boot DevTools
- Spring Data JPA
- Flyway Migration
- MySQL Driver
- Validation
- Spring Security
- **JWT** (JSON Web Token) para autenticación

## Configuración del Proyecto

Para configurar el proyecto, sigue estos pasos:

1. Clona el repositorio:
   ```bash
   git clone [URL del repositorio]
2. Configura la base de datos MySQL y actualiza las credenciales en el archivo application.properties.
3. Ejecuta las migraciones de Flyway para crear las tablas necesarias.
4. Inicia la aplicación utilizando tu IDE preferido o ejecuta
    ```bash
    mvn spring-boot:run

## Seguridad JWT

  Para agregar mayor seguridad a la aplicación, se ha implementado autenticación mediante tokens JWT (JSON Web Token).
  
## Base de Datos  

La base de datos incluye la tabla de tópicos con los siguientes campos:

  - `id`: Identificador único del tópico
  - `título`: Título del tópico
  - `mensaje`: Contenido del tópico
  - `fecha de creación`: Fecha de creación del tópico
  - `status`: Estado del tópico
  - `autor`: Autor del tópico
  - `curso`: Curso relacionado con el tópico

## Autenticación y Autorización

El acceso a la API está restringido mediante Spring Security, garantizando que solo los usuarios autenticados puedan realizar operaciones CRUD.





