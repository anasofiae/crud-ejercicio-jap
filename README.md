# crud-ejercicio-jap
Entrega obligatoria JaP. Trabajando con CRUD

En esta entrega grupal trabajaremos en una aplicación CRUD, capaz de conectarse con un servidor y realizar modificaciones en una base de datos.

Para ello, haremos uso de un mock server, o servidor simulado, que nos permitirá crear rápidamente los recursos backend necesarios y concentrarnos en el trabajo en cliente. 

Antes de empezar, debemos configurar el servidor.

Los endpoints a los que realizar las solicitudes serán:

Listar: GET https://SECRET.mockapi.io/users
Devuelve un json con una lista que contiene todos los registros.

Obtener 1: GET https://SECRET.mockapi.io/users/:id
Recibe un id en la url y devuelve un json con el registro cuyo id haya sido solicitado.

Agregar: POST https://SECRET.mockapi.io/users
Recibe un json con un objeto con los atributos name y lastname, (en el body) lo agrega a la base de datos (asignándole un id) y devuelve un json con el registro creado.

Modificar: PUT https://SECRET.mockapi.io/users/:id
Recibe un id en la url y un json con un objeto con los atributos name y lastname, (en el body), modifica con dichos datos el registro cuyo id coincida con el recibido, y devuelve un json con el registro modificado.

Eliminar: DELETE https://SECRET.mockapi.io/users/:id
Recibe un id en la url, elimina el registro cuyo id coincida con el recibido, y devuelve un json con el registro eliminado.
