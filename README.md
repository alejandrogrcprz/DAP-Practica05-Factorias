# DAP-Practica05-Factorias

## Alejandro García Pérez y Héctor Luís Mariño Fernández

### Componentes
<img width="411" height="709" alt="image" src="https://github.com/user-attachments/assets/0bff585b-41b9-4f92-88ee-fb7ef8bab249" />

   
🔍 Descripción de los componentes

 - Componente	Rol	Tecnología
 - Cliente Web	Interfaz gráfica (formulario, dashboard, etc.)	HTML/JS, React, Angular, o Thymeleaf
 - Controlador (Controller)	Expone endpoints REST o páginas web	@RestController o @Controller (Spring Boot)
 - Servicio (Service)	Lógica de negocio (usa la fábrica de BD)	Clase Java con @Service
 - DBFactory (Abstract Factory)	Interfaz para crear objetos de conexión (EntityManagerFactory)	Patrón de diseño
 - MySQLFactory / PostgresFactory	Implementaciones concretas que devuelven el EntityManagerFactory configurado	Hibernate / JPA
 - EntityManagerFactory / EntityManager	Gestiona sesiones, transacciones y consultas ORM	Hibernate
 - Entidades JPA	Representan tablas de la base de datos como clases Java	Anotaciones @Entity, @Id, etc.
 - Base de Datos SQL	Almacena los datos reales	MySQL, PostgreSQL, etc.
 - Spring Boot (framework base)	Gestiona dependencias, servidor embebido, configuración y DI	Spring Boot, Maven o Gradle
