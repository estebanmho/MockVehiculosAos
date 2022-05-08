# *Especificación de un servicio*

## Subsistema 2 **Gestión de Vehículos** Grupo 7

## Enunciado

Gestión de los vehículos que son propiedad de los clientes y que se reparan y/o revisan en el taller. Cada vehículo estará identificado de forma única por su VIN.

## Herramientas

Para el diseño y trabajo de nuestra especificación, hemos utilizado las siguientes herramientas:

- **Visual Studio Code**
 - *Extension Docker*
 - *Extension OpenAPI(Swagger) Editor*
- **Docker**

## Instalación y Despliegue (Opción 1)

 1. Clonamos el repositorio github del proyecto
 2. Instalamos Docker y VSC(con sus dos extensiones)
 3. Iniciamos Docker
 4. Iniciamos VSC y localizamos el archivo docker-compose.yml
 5. Ejecutamos Compose up con click derecho en el archivo
 6. Tras terminar de buildear, nos dirigimos a [localhost](http://localhost:8000/)
 7. Podemos disfrutar de probar nuestra especificación

## Instalación y Despliegue (Opción 2)
### *Comandos a ejecutar en el CMD de Windows*

 1. Accedemos a la carpeta raíz del proyecto.
 2. Ejecutamos el siguiente comando: `docker compose build`
 3. Ejecutamos el siguiente comando: `docker compose up` 
 4. Si nos dirigimos a esta url [127.0.0.1](http://127.0.0.1:8000/) nos mostrará la especificación.