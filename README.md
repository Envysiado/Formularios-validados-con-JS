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

## Uso de Eventos en Formularios

En proyectos más complejos, se puede utilizar el método `addEventListener` para adjuntar eventos, como el evento de "submit", al formulario. Este evento se dispara cuando se envía el formulario y se utiliza para manejar la validación del mismo y realizar acciones como prevenir el comportamiento predeterminado del envío del formulario y mostrar mensajes de error o éxito.

Este README proporciona una visión general del funcionamiento de las etiquetas HTML en formularios web y la validación de entradas. Para más detalles sobre cómo implementar estas características, consulte la documentación oficial de HTML y JavaScript.



