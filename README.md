<div>
  <h1 align="center">Hola, soy Paula 👋 </h1>
</div>


## Sobre mi ☝️

- Desarrolladora de software en formación.
- Apasionada por el aprendizaje continuo y la creación de soluciones tecnológicas.
- Tengo experiencia desarrollando aplicaciones web y APIs REST utilizando Java, JavaScript con Node.JS y frameworks como React y Tailwind CSS. He trabajado con bases de datos relacionales como MySQL y he desarrollado proyectos tanto en frontend como en backend.

## Proyectos destacados 💥

* 🛒 **API para gestión de una librería:**

Esta API permite gestionar los usuarios, libros y préstamos de una librería. Está desarrollada siguiendo el patrón de diseño que incluye DAO (Data Access Object), DTO (Data Transfer Object) y entidades (modelo o entity). Ademas cuenta con una base de datos relacional, para el manejo de datos.

Estructura del modelo:
- Usuario: Representan a los lectores o clientes
Relación:  Un usuario puede tener muchos préstamos.
- Libros: Representa los libros disponibles en la librería.
Relación: Un libro puede estar asociado a muchos préstamos.
- Préstamos: Funciona como una tabla intermedia entre usuarios y libros.
Relación: Cada préstamo está vinculado a un único usuario y a un único libro.

Características técnicas:
- Se puede probar usando Postman o cualquier otro entorno que permita realizar peticiones HTTP de forma similar (como Insomnia, Thunder Client, etc). 
- La documentación está disponible mediante swagger, lo que facilita la comprensión de los endpoints y cómo interactuar con ellos.

Desarrollada en Java.

* 📚 **API para gestión de una tienda:**

Esta API permite administrar operaciones básicas de compra y venta dentro de una tienda. Está estructurada con un controlador, rutas bien definidas y una conexión a una base de datos para el manejo de información.

Estructura del modelo:
- Compra: Representa las adquisiciones realizadas por la tienda (productos que ingresan al inventario).
- Venta: Representa las transacciones de productos vendidos a los clientes. 
Relación: Un producto puede estar asociado a muchas ventas.

Características técnicas:
- Cuenta con un controlador encargado de gestionar la lógica de negocio.
- Las rutas definen los endpoints disponibles para las operaciones CRUD.
- Tiene una conexión establecida con una base de datos, donde se almacena la información de compras y ventas.
- Se puede probar usando Postman o cualquier otro entorno que permita realizar peticiones HTTP de forma similar (como Insomnia, Thunder Client, etc).

- ⚽ **Aplicación con arquitectura de microservicios:**

Esta aplicación está desarrollada en Java con Spring Boot siguiendo una arquitectura de microservicios, lo cual permite una mejor escalabilidad, mantenimiento independiente y despliegue modular.

Microservicios implementados:
- Microservicio de Players: Se encarga de la gestión de los jugadores: creación, consulta, actualización y eliminación.
- Microservicio de Teams: Administra toda la información relacionada con los equipos.

Arquitectura y herramientas:
Spring Boot: Marco principal para el desarrollo de los microservicios.
Spring Cloud Eureka: Utilizado como servidor de descubrimiento de servicios, lo que permite que los microservicios se registren y se comuniquen entre sí dinámicamente.
Spring Cloud Gateway: Actúa como API Gateway, centralizando las peticiones y redirigiéndolas al microservicio correspondiente.

Prueba:
Las peticiones a los endpoint se pueden probar usando Postman o herramientas similares (Insomnia, Thunder Client, etc).
  
- 🕵️ **Web Scraping a bolsa de empleo:**

Este proyecto consiste en realizar web scraping a una página de ofertas laborales similar a El Empleo, con el objetivo de extraer información útil de cada oferta publicada.

Herramientas y tecnologías usadas:
- JavaScript con Puppeter: Biblioteca que permite controlar un navegador (como Chrome o Chromium) de forma automatizada para extraer datos de sitios web dinámicos.

Funcionamiento: 
El script accede a la página de ofertas de empleo y extrae datos clave como:
- Título del cargo
- Las vacantes disponibles
- Ciudad

Los datos extraídos se imprimen en la consola y se almacenan en objetos para su posterior uso o almacenamiento. 

Me interesa seguir creciendo en el desarrollo backend y arquitectura de software. 
