# Spring Boot Java 25 PoC

Proyecto mínimo de Spring Boot con Java 25 y Maven para la prueba de concepto de desarrollo remoto con Coder y OpenCode.

## Requisitos
- Java 25 (OpenJDK / Microsoft OpenJDK 25)
- Maven 3.9+ / 3.10+

## Compilar y Ejecutar
Para compilar el proyecto y ejecutar las pruebas automatizadas:
```bash
mvn clean test
```

Para arrancar la aplicación en modo desarrollo:
```bash
mvn spring-boot:run
```

## Pruebas de la API
Una vez arrancada la aplicación, se puede comprobar el endpoint REST:
```bash
curl http://localhost:8080/api/hello
```
Debe devolver una respuesta JSON:
```json
{"message":"Hello, World!"}
```
