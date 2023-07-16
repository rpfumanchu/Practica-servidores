# Despliegue en Servidores AWS

## Ejercicio 1

- Utilizar node como servidor de aplicación utilizando PM2 o supervisor como gestor de procesos
  node para que siempre esté en ejecución. La aplicación node deberá reiniciarse
  automáticamente al arrancar el servidor (en el startup).
- Utilizar nginx como proxy inverso que se encargue de recibir las peticiones HTTP y derivárselas
  a node.
- Los archivos estáticos de la aplicación (imágenes, css, etc.) deberán ser servidos por nginx (no
  por node). Para poder diferenciar quién sirve estos estáticos, se deberá añadir una cabecera
  HTTP cuando se sirvan estáticos cuyo valor sea: X-Owner (la X- indica que es una cabecera
  personalizada).

## Ejercicio 2.

- Si se accede al servidor web indicando la dirección IP del servidor en lugar del nombre de
  dominio, se deberá carga la práctica realizada en el módulo de React o React Avanzado (a
  elección del alumno).

## URL disponibles:

### Para la práctica de node con BD mongo.

#### Direcció IP:

http://100.26.97.7

### Para la práctica de React.

#### DNS:

http://ec2-100-26-97-7.compute-1.amazonaws.com/login

- ### Usuario por defecto.

  - Email: rober@gmail.com
  - Password: 123123

- ### Esta práctica de React usa el back que nos proporcionó David, puedes probarla en esta url.

http://100.26.97.7/api/swagger/#/adverts

- ### Además en esta otra url podrás comprobar la respuesta sin hacer login.

http://100.26.97.7/api/v1/adverts/tags
