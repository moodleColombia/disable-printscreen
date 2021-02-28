# disable-printscreen
Este es un proyecto abierto que tiene por propósito la creación de un plugin para Moodle que apoye a las instituciones en temas de antiplagio sobre sus cuestionarios. 

1. En este momento para poderlo usar en moodle, vas a ir al bloque de administración e ingresar al apartado de HTML Adicional.
2. Dentro vas a la sección llamada "Antes de cerrar BODY" y allí copias y pegas el código fuente.  
```html
    <!-- disable-printscreen -->
    <style>
        /* Todo el contenido del archivo watermark.css */
    </style>
    <script src="https://cdn.jsdelivr.net/npm/sweetalert2@10"></script>
    <script>
        // Todo el contenido del archivo disablePrintScreen.js
    </script>
```