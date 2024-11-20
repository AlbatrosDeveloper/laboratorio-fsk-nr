# Laboratorio

## Instrucciones:

1. Haz un clone de este repositorio.
2. Crea un branch con la nomenclatura `lab/apellido`.
3. Debes crear un backend en Node.js con Express y conexión a BDD mongoDB.
4. Debes crear un frontEnd en react o angular.
5. Debes crear una pequeña aplicación de pacientes.
6. Tienes 2 dias para entregar el laboratorio.
7. Debes subir el repositorio a su Github.
8. Se tomará en cuanta ir subiendo los cambios a medida que vayas avanzando.
9. Enviar el link del repositorio al correo: `andres.sosa@albatrosservices.com`

## Criterios

1. Debes crear un CRUD de pacientes con express y mongoDB.
2. Debes crear un formulario para agregar/editar/borrar pacientes.m (FrontEnd)
Campos de un paciente:
- id
- Nombre
- Apellido
- Fecha de nacimiento
- Dirección
- Teléfonos (pueden ser varios teléfonos)
- Emails (puedes ser varios emails)

3. Debes crear un CRUD para síntomas.
Campos de un síntoma:
- id
- Nombre
- Descripción

4. Debes crear endpoint(s) para poder relacionar pacientes con síntomas.

5. Extra (no obligatorio): 
- Crear una página de login.
- Validar si tiene login para poder acceder a la pantalla de pacientes.
- En Backend al momento de hacer login debe validar si el usuario existe (como un usuario admin), generar un token y devolverlo al frontEnd

## Cadena de conexión a la BDD 
Toma en cuenta que el nombre de la base de datos debe ser su apellido
En la cadena de conexión después del /<apellido>

Ejemplo: (si mi apellido es sosa)

`Cadena de conexión a la BDD: mongodb+srv://developer:E79TGSMIcGY81IYV@test-database.2n2x7.mongodb.net/sosa?retryWrites=true&w=majority&appName=test-database`

