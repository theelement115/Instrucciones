# Instrucciones

El objetivo de la prueba es crear una pagina web sencilla en la que se puedan vizualisar y crear productos


1. Crear una API en Django rest con un modelo de productos con los siguientes datos:

   * name
   * stock
   * price
   * paused

2. la API debe permitir hacer el CRUD de productos

3. dockerizar la API, se puede usar Docker o Docker-Compose

4. crear un proyecto de angular para el desarrollo del front se puede usar cualquier framework de gui, pero se recomienda usar primeng por facilidad  https://primefaces.org/primeng/showcase/#/setup

5. Hacer en angular una pagina que permita crear un producto, puede ser un formulario simple con los 3 campos

6. Hacer en el mismo proyecto de angular, en otra url una pagina que permita visualizar los productos, la pagina debe parecerse al diseño propuesto. (se recomienda usar el dataview de primeng)

7. Hacer en la pagina de visualizacion un menu desde el que se pueda:

   * Abrir un dialog en el que se pueda cambiar el stock del producto seleccionado
   * Pausar el producto
   * Activar el producto
   * Eliminar el producto

8. Subir ambos proyectos (La api en django y la pagina en angular) a github o gitlab de manera publica y enviar el link al correo gerencia@zaito.co
