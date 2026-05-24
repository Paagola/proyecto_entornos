# Proyecto Objetos — Mejora Técnica

Juego de simulación por consola en Java donde personajes Buenos huyen de los Malos en un tablero de 100×20 celdas.

## Rama de trabajo
El desarrollo de la mejora se ha realizado en la rama `mejora`. La rama `master` conserva el estado inicial del proyecto.

## Mejoras aplicadas
- Migración del proyecto a **Maven** (`pom.xml`, estructura `src/main/java`)
- **Refactorización** del código: corrección de herencia incorrecta, simplificación de condicionales y limpieza de constructores
- **Pruebas unitarias** con JUnit 5 (`ElementoTest`, `PersonajeTest`)
- **Análisis estático** con SonarLint y corrección de problemas detectados
- **Javadoc** en todas las clases principales (`mvn javadoc:javadoc`)
- **Integración continua** con GitHub Actions: compila y ejecuta los tests automáticamente en cada push

## Comandos principales
```bash
mvn compile      # Compilar el proyecto
mvn test         # Ejecutar las pruebas unitarias
mvn javadoc:javadoc  # Generar la documentación HTML
```
