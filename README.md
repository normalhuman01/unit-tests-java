# Pruebas unitarias - Digital Innovation One

##### Objetivos de la lección:
1. Presentar la pirámide de pruebas de software y detallar cada nivel.
2. Destacar la importancia de las pruebas unitarias durante el desarrollo.
3. Presentar los frameworks de referencia para pruebas: JUnit, Mockito y Hamcrest.
4. Codificar, compartir y aprender juntos.

##### Qué vamos a utilizar:
- Java 14
- Maven 3.6.2
- Spring Boot (última versión estable publicada)
- GIT/GITHUB para el versionado de código
- Frameworks JUnit, Mockito y Hamcrest

##### @Data 
- Genera getters y setters automáticamente.

##### DAO
- Objeto de Acceso a Datos
- Comunicación con la base de datos.

##### Opcional 
- Introducido en Java 8.

##### @Servicio 
- De dentro hacia fuera.

##### @RestController
- Un controlador que pasa datos sin parte gráfica.

##### Verbos HTTP típicos:
- GET -> Leer de la Base de Datos.
- PUT -> Actualizar/Reemplazar fila en Base de Datos.
- PATCH -> Actualizar/Modificar fila en Base de Datos.
- POST -> Crear un nuevo registro en la Base de Datos.
- DELETE -> Borrar de la base de datos.

##### API RESTful - Richardson

###### Glory Of Rest
- Nivel 3 - Controles hipermedia
- Nivel 2 - Verbos HTTP
- Nivel 1 - Recursos
- Nivel 0 - El pantano de la viruela

##### Pirámide de pruebas
- Pruebas UI -> appium
- Pruebas de integración -> UI Automator, espresso y AndroidJUnit4
- Pruebas Unitarias -> Mock, JUnit y mockito

##### Ventajas
- Sistema probado de extremo a extremo.
- Evolución segura: sin romper funcionalidades.
- Las pruebas son también una forma de documentación.
- Integración continua (IC)
- Despliegue continuo (DC)

##### Nivel 1: pruebas unitarias
- Mayor número de pruebas, menor coste y tiempo
- Pruebas realizadas por el desarrollador
- Rápidas, basadas en líneas de código
- Cobertura de varios escenarios para las líneas
- Integración con otro código: mediante mocks

##### Principales frameworks
- JUnit
- Mockito
- Hamcrest
- Spring Boot Starter Test: ¡acceso a todos los frameworks!

##### Constructor 
- Ayuda con las pruebas porque reúne todo.

##### Maven
- Añade calidad a las pruebas y las hace más potentes.

##### Inglés
- La mayoría de las pruebas de la empresa y de la comunidad están en inglés.

##### Terminal IDE
- git diff -> Lista todas las pruebas realizadas.

##### TDD 
- Prueba y simplifica el código.