# Práctica S5 - Retos JavaScript

Práctica de JavaScript de Ingeniería Web sobre DOM, eventos y validación de formularios. Hice 2 retos.

## Reto 2: cuarto tema inicial

Agregué un cuarto tema al arreglo `temas` en `js/app.js` (está marcado con el comentario `// RETO 2`).

Se ve en la sección "Temas de la práctica": ahora salen 4 tarjetas y el contador dice 4.

## Reto 4: nombre de mínimo 5 caracteres

Cambié la validación del nombre de 3 a 5 caracteres en la función `validarRegistro` de `js/app.js` (comentario `// RETO 4`). También cambié el `minlength` del campo nombre en `index.html`.

Se ve en la sección "Registro para el taller": si el nombre tiene menos de 5 caracteres sale el error "Ingresa al menos 5 caracteres." y no se registra.
## Validación del formulario de registro

Quité `novalidate` del formulario en `index.html` para que el navegador use los atributos `required` (nombre, correo y rol) y `minlength="5"` (nombre). Esa es la validación en el HTML.

Si alguien quita esos atributos desde el navegador, la función `validarRegistro` de `js/app.js` vuelve a revisar los campos y muestra el error en pantalla. Esa es la validación en JavaScript.

Se ve en la sección "Registro para el taller": si se envía el formulario vacío o con un nombre de menos de 5 caracteres, no se registra la persona.