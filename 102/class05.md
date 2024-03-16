# CLASE 05


## 1. ¿Cuál es el propósito de CSS?
El propósito principal de CSS (Cascading Style Sheets) es controlar la presentación y el estilo de los elementos HTML en una página web. Permite definir cómo se verán los elementos, como su color, tamaño, posición, espaciado, fuente, entre otros aspectos visuales. Esto ayuda a separar la estructura (HTML) del diseño (CSS) y facilita la creación de páginas web estéticamente atractivas y con un bonito y funcional diseño.

## 2. ¿Cuáles son las tres formas de insertar CSS en tu proyecto?

Hay tres formas diferentes de aplicar CSS a un documento HTML, sin embargo, la forma más habitual y útil de hacerlo: 
1. vincular el CSS desde el encabezado del documento.
 [ejem](https://developer.mozilla.org/es/docs/Learn/CSS/First_steps/Getting_started].

 2. Otra forma es estilo en línea, donde se aplica directamente a un elemento HTML utilizando el atributo style, ejemplo :
`<p style="color: blue; font-size: 18px;">Este es un párrafo con estilo en línea :).</p>`

3. Hojas de estilo externas:

Para una mejor organización y mantenimiento del código, se pueden crear archivos CSS independientes y vincularlos al HTML. Así, se almacena en un archivo separado con extensión .css y se enlaza con el documento HTML utilizando la etiqueta <link> en la sección <head>.
 Por ejemplo:
 ´
"<head>
  <link rel="stylesheet" href="estilos.css">
</head>"
´

## 3. Ejemplo de una regla CSS que daría texto rojo a todos los elementos:

La siguiente regla CSS aplica color rojo al texto de todos los elementos en un documento HTML:
Primero, en un archivo estilos.css aparte y luego vincularlo al html.

´body {
  color: red;
}´
En este ejemplo, la regla se aplicará a todo el contenido textual del cuerpo del documento HTML, haciendo que el texto de todos los elementos sean de color rojo.
