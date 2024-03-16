# Formularios-validados-con-JS

# Funcionamiento de la etiqueta `<input>`

La etiqueta `<input>` se utiliza para crear campos de entrada interactivos en formularios web. Puede tomar varios tipos de entrada dependiendo del valor del atributo `type`.

### Tipos de entrada:

- **Text**: Este es el tipo de entrada predeterminado. Se utiliza para permitir a los usuarios ingresar texto.
  ```html
  <input type="text" name="nombre">

- **Password**: Este tipo de entrada oculta el texto ingresado, generalmente se usa para contraseñas.

  ```html
  <input type="password" name="contrasena">

- **Checkbox**: Se utiliza para permitir a los usuarios seleccionar múltiples opciones de una lista.

  ```html
  <input type="checkbox" name="opcion" value="valor">

- **Radio**: Similar a un checkbox, pero solo se puede seleccionar una opción de una lista.

  ```html
  <input type="radio" name="opcion" value="valor1">
  <input type="radio" name="opcion" value="valor2">

- **Number**: Se utiliza para permitir a los usuarios ingresar un número.

 ```html
  <input type="number" name="edad">

- **Date**: Se utiliza para permitir a los usuarios seleccionar una fecha.

```html
<input type="date" name="fechaNacimiento">

Estos son solo algunos ejemplos de los muchos tipos de entrada que puede crear con la etiqueta <input>.

Atributos adicionales:
Además del atributo type, hay varios otros atributos que puede usar con la etiqueta <input> para personalizar su comportamiento y apariencia:

name: Identifica el campo de entrada cuando se envía el formulario.
value: Define el valor inicial del campo de entrada.
placeholder: Proporciona un texto de marcador de posición que se muestra cuando el campo está vacío.
required: Indica que el campo es obligatorio y no se puede enviar el formulario sin completarlo.
readonly: Hace que el campo sea de solo lectura y no se pueda modificar.
disabled: Deshabilita el campo de entrada para que no se pueda seleccionar ni modificar.

