# Formularios-validados-con-JS

# Funcionamiento de las Etiquetas HTML en Formularios Web



## Etiqueta `<input>`

La etiqueta `<input>` se utiliza para crear campos de entrada interactivos en formularios web. Puede tomar varios tipos de entrada, como texto, contraseña, casilla de verificación, botón de radio, número, fecha, entre otros. A continuación, se muestran algunos ejemplos de uso:

- Texto: `<input type="text" name="nombre">`
- Contraseña: `<input type="password" name="contrasena">`
- Casilla de Verificación: `<input type="checkbox" name="opcion" value="valor">`
- Botón de Radio: `<input type="radio" name="opcion" value="valor1">`
- Número: `<input type="number" name="edad">`
- Fecha: `<input type="date" name="fechaNacimiento">`

Además del atributo `type`, se pueden utilizar otros atributos como `name`, `value`, `placeholder`, `required`, `readonly`, `disabled`, entre otros, para personalizar su comportamiento y apariencia.

## Etiqueta `<button>`

La etiqueta `<button>` se utiliza para crear botones interactivos en una página web. Puede contener texto, imágenes u otros elementos HTML. A continuación, se muestra un ejemplo de uso:

- Texto del Botón: `<button>Enviar</button>`
- Imagen como Botón: `<button><img src="boton.png" alt="Enviar"></button>`

Se pueden utilizar varios atributos, como `onclick`, `type`, `class`, `id`, `style`, etc., para personalizar su comportamiento y apariencia.

## Validación de las Entradas

En la validación de las entradas, se utilizan expresiones regulares y comprobaciones para asegurar que los campos del formulario contengan datos válidos. Algunos de los campos validados incluyen ID, nombre y apellidos, teléfono, correo electrónico, edad y fecha de nacimiento.

## Uso de Evento

En este proyecto, se utilizó el método addEventListener para adjuntar un evento de "submit" al formulario. Este evento se dispara cuando se envía el formulario.

`formulario.addEventListener("submit", function(event) {
    // Código para manejar el envío del formulario
});`

Previene el comportamiento predeterminado de enviar el formulario utilizando event.preventDefault();.

Obtiene los valores de los campos del formulario, como ID, nombre, apellidos, teléfono, correo electrónico, edad y fecha de nacimiento.

Realiza validaciones específicas para cada campo del formulario, asegurando que cumplan con ciertos criterios:

Verifica que el ID tenga exactamente 5 dígitos.

Asegura que tanto el nombre como los apellidos no estén vacíos.

Formatea el campo de teléfono para que coincida con el formato (###)###-#### y luego verifica que tenga este formato.

Verifica que el correo electrónico tenga un formato válido.

Asegura que la edad sea un número positivo mayor que cero.

Verifica que la fecha de nacimiento tenga el formato AAAA-MM-DD.

Muestra mensajes de error en caso de que alguna validación falle, indicando qué campos tienen errores específicos.

En caso de que todos los campos pasen las validaciones, muestra un mensaje de éxito indicando que el formulario se ha enviado correctamente.



