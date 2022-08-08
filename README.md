## Ejemplo de cliente Spring Boot SOAP

Este es un proyecto de ejemplo para demostrar cómo conectarse a servicios web SOAP desde un componente Spring Boot.

Llama a un servicio SOAP básico que convierte números en palabras, exponiendo esta función a través de un controlador REST.


### Build & run

Este proyecto fue construido con Spring Initializr utilizando un maven envuelto. Entonces, para compilar y ejecutar este proyecto, ejecute los siguientes comandos:

    git clone https://github.com/JordyV3/Cliente-Spring-Boot-SOAP.git
    ./mvnw package
    cd target
    java -jar soap-client-sample-0.0.1-SNAPSHOT.jar

Para probar, simplemente apunte su navegador a:

     http://localhost:8080/num2words/42

Esto debería mostrar algo como:

     cuarenta y dos

Gracias 🙂