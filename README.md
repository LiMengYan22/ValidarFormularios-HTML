# ValidarFormularios-HTML
Validación de Formularios con expresiones regulares, en HTML *(anti SQL injections..)*
<hr>

**Simple:** <input type="text" name="pais" title="TRES LETRAS espacio y signos"pattern="[A-Za-z ,.-]{3}">

**Otro** pattern="[a-zA-Z0-9.€]"
----------------------------------------------------------------------------------------
## Validaciones con expresiones regulares:

Según wikipedia: Una expresión regular, a menudo llamada también regex, es una secuencia de caracteres que forma
un patrón de búsqueda, principalmente utilizada para la búsqueda de patrones de cadenas de caracteres u operaciones
de sustituciones.
Y esa misma posibilidad se ha añadido al control de validez de cadenas en los formularios de HTML5. Ahora mediante
el atributo pattern, podemos añadir a los <input> de tipo texto como validación por medio de una expresión regular
personalizada.
Imaginemos que queremos incluir en el típico formulario de alta que algunos de los campos como nombre, apellidos,
email, usuario y contraseña pasen una validación de cadena.

<hr>
*Algunas Referencias:*
https://www.w3schools.com/html/html_form_attributes.asp
http://html5pattern.com/
https://oscargascon.es/validacion-de-formularios-con-html5-y-expresiones-regulares-sin-uso-de-js-utilizacion-de-css-y-fontawesome-para-mostrar-campos-validos-en-formularios/
