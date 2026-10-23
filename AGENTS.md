# AGENTS.md

Instrucciones persistentes para agentes autónomos que trabajen en este repositorio.

## Estructura del Proyecto
- `pom.xml`: Configuración de Maven y dependencias (Spring Boot 4.0.0, Java 25).
- `src/main/java/com/poc/demo/`: Código fuente principal de la aplicación Spring Boot.
- `src/test/java/com/poc/demo/`: Pruebas automatizadas (JUnit 5, MockMvc).

## Comandos Principales
- **Compilar y ejecutar pruebas:**
  ```bash
  mvn clean test
  ```
- **Ejecutar la aplicación:**
  ```bash
  mvn spring-boot:run
  ```

## Convenciones y Normas
- Mantener compatibilidad estricta con **Java 25**.
- Usar Spring Boot (versión estable actual 4.0.0).
- No añadir dependencias innecesarias, bases de datos, Docker o Kubernetes a menos que se solicite explícitamente.
- No incluir secretos, credenciales ni tokens en ningún archivo del repositorio.
- No realizar commits ni pushes automáticos a GitHub.
- Verificar siempre los cambios ejecutando `mvn clean test` antes de concluir cualquier tarea.
