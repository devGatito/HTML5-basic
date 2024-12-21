# HTML:5

HTML significa **lenguaje de marcado de hipertexto**.

- HTML es el lenguaje de marcado estándar para crear páginas web.
- HTML describe la estructura de una página web.
- HTML consta de una serie de elementos.
- Los elementos HTML le indican al navegador cómo mostrar el contenido.
- Los elementos HTML etiquetan fragmentos de contenido como "esto es un encabezado", "esto es un párrafo", "esto es un enlace", etc.

## Cuerpo HTML
```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  </head>
  <body></body>
</html>
```

## Explicando la estructura

- **`<!DOCTYPE html>`**: La declaración define que este documento es un documento HTML5.
- **`<html>`**: El elemento raíz de una página HTML.
- **`<head>`**: Contiene metainformación sobre la página HTML.
- **`<title>`**: Especifica un título para la página HTML (se muestra en la barra de título del navegador o en la pestaña de la página).
- **`<body>`**: Define el cuerpo del documento y es un contenedor para todo el contenido visible, como encabezados, párrafos, imágenes, hipervínculos, tablas, listas, etc.
- **`<h1>`**: Define un encabezado grande.
- **`<p>`**: Define un párrafo.

## ¿Qué es un elemento HTML?

Un elemento HTML se define mediante una etiqueta de inicio, algún contenido y una etiqueta final:

```html
<tagname> El contenido va aquí... </tagname>
```

El elemento HTML es todo, desde la etiqueta de inicio hasta la etiqueta final:

```html
<h1>Mi primer encabezado</h1>
<p>Mi primer párrafo.</p>
