# challange-oracle-foro-hub
Esta aplicación se realizó como parte de la formación en Oracle Next Eucation (ONE) y Alura Latam, usando Spring Boot, MySQL y Security de Spring.

# Características

    La API se centra específicamente en los tópicos y permite realizar las operaciones CRUD: Crear, Consultar, Actualizar y Eliminar tópicos.
    Los datos se guardan en una base de datos relacional llamada foro_hub para la persistencia de la información, la cual incluye las siguientes tablas:
        Topicos
        Respuesta
        Curso
        Usuario
    Se implementa la autenticación de JWT (JSON Web Token) para validar usuarios con correo y contraseña, los cuales están registrados en la base de datos de usuarios.
    Se implementan las validaciones de negocio para no recibir solicitudes con campos nulos y para no permitir el registro de tópicos duplicados con el mismo título y mensaje.
    Se siguen las mejores prácticas y se sigue el modelo de desarrollo SOLID, permitiendo continuar con el desarrollo y la implementación de nuevas funcionalidades en la API Foro Hub.

Tecnologías Usadas

    Java 17
    Spring Boot 3.0
    Spring Data JPA
    Hibernate
    Maven
    Lombok
