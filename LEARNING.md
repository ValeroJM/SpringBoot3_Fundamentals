# Aprendiendo Sprin Boot

### 05/23/2024
Estoy aprendiendo Spring Boot usando el curso de Pluralsight Spring Boot 3 Fundamentals de Jesper de Jong.

1. Hemos creadoun projecto nuevo usando Spring Initializr. Usando esta web https://start.spring.io/
2. He abierto el projecto en IntelliJ.
3. Para compliar el programa, aunque aún no hemos hecho nada, usamos el siguiente comando en el terminal:
```
$ ./mvnw package
```
Esto generará un archivo SNAPSHOT.jar en la carpeta target que contiene todas las dependencias y la applicación en si misma.

Para ejecutarla, una vez que estemos en la carpeta, escribimos en el terminal:
```
$ java -jar nombreDelArchivo-0.0.1-SNAPSHOT.jar
```
### 05/24/2024
El Spring web Application Framework tiene dos componentes
1. Spring Web MVC: Servlet API. Siguiendo los patrones: Model-View-Controller
2. Spring WebFlux: Functional Programming Reactive Streams (Para hacer aplicaciones web)

En el módulo 3 veremos:
* Data Model
* Repository Classes
* Controller Classes
  * Converting data from requests and to responses
  * Exception handling
  * Validation

