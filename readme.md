## Instrucciones para Ejecutar el API de Java

Descargar e instalar JDK 17 desde https://adoptium.net/es/temurin/releases/?arch=x64&package=jdk&version=17.

Dentro de la carpeta que contiene el archivo pom.xml:

Ejecutar
```
./mvnw package
./mvnw spring-boot:run
```

Estas instrucciones permitirán tener el API en ejecución en <http://localhost:8080> listo para ser utilizado por la aplicación Angular.