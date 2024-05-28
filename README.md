# Carrito de Compra

Este es un proyecto de demostración para un carrito de compras utilizando Spring Boot.

## Requisitos

- **Java 22**: Asegúrate de tener la versión 22 de Java instalada en tu máquina.
- **Maven 3.3.0**: Utiliza Maven versión 3.3.0 para la gestión de dependencias y construcción del proyecto.
- **IDE IntelliJ**: El proyecto se desarrolló utilizando IntelliJ como IDE.
- **MySQL**: Aunque se incluye la dependencia para MySQL (`mysql-connector-j`), no es necesario crear una base de datos, ya que se utiliza JPA para la gestión de la base de datos y Spring Boot se encarga de crearla automáticamente.

## API Utilizada

Este proyecto hace uso de la API [FakeStoreAPI](https://fakestoreapi.com/docs) para obtener los datos de los productos.

## Dependencias

El proyecto utiliza las siguientes dependencias:

- `org.springframework.boot:spring-boot-starter-data-jpa`
- `org.springframework.boot:spring-boot-starter-security`
- `org.springframework.boot:spring-boot-starter-web`
- `org.springframework.boot:spring-boot-devtools`
- `com.mysql:mysql-connector-j`
- `org.projectlombok:lombok`
- `org.springframework.boot:spring-boot-starter-test`
- `org.springframework.boot:spring-boot-testcontainers`
- `org.springframework.security:spring-security-test`
- `org.testcontainers:junit-jupiter`
- `org.testcontainers:mysql`
