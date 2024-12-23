# | HTML:5

HTML significa **lenguaje de marcado de hipertexto**.

- HTML es el lenguaje de marcado estándar para crear páginas web.
- HTML describe la estructura de una página web.
- HTML consta de una serie de elementos.
- Los elementos HTML le indican al navegador cómo mostrar el contenido.
- Los elementos HTML etiquetan fragmentos de contenido como "esto es un encabezado", "esto es un párrafo", "esto es un enlace", etc.

## | Cuerpo HTML

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

## | Explicando la estructura

- **`<!DOCTYPE html>`**: La declaración define que este documento es un documento HTML5.
- **`<html>`**: El elemento raíz de una página HTML.
- **`<head>`**: Contiene metainformación sobre la página HTML.
- **`<title>`**: Especifica un título para la página HTML (se muestra en la barra de título del navegador o en la pestaña de la página).
- **`<body>`**: Define el cuerpo del documento y es un contenedor para todo el contenido visible, como encabezados, párrafos, imágenes, hipervínculos, tablas, listas, etc.
- **`<h1>`**: Define un encabezado grande.
- **`<p>`**: Define un párrafo.

## | ¿Qué es un elemento HTML?

Un elemento HTML se define mediante una etiqueta de inicio, algún contenido y una etiqueta final:

```html
<tagname> El contenido va aquí... </tagname>
```

# | El elemento HTML es todo, desde la etiqueta de inicio hasta la etiqueta final:

```html
<h1>Mi primer encabezado</h1>
<p>Mi primer párrafo.</p>
# Tabla de Etiquetas HTML
```

# | Etiqueta

<table>
  <thead>
    <tr>
      <th>Inicio de Etiqueta</th>
      <th>Contenido del Elemento</th>
      <th>Cierre de Etiqueta</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><code>&lt;h1&gt;</code></td>
      <td>Mi Cabecera</td>
      <td><code>&lt;/h1&gt;</code></td>
    </tr>
    <tr>
      <td><code>&lt;p&gt;</code></td>
      <td>Mi párrafo</td>
      <td><code>&lt;/p&gt;</code></td>
    </tr>
    <tr>
      <td><code>&lt;br&gt;</code></td>
      <td>Ninguno</td>
      <td>Ninguno</td>
    </tr>
  </tbody>
</table>

<strong>Nota:</strong> Algunos elementos HTML no tienen contenido (como el elemento <code>&lt;br&gt;</code>).
Estos elementos se denominan <em>elementos vacíos</em>. ¡Los elementos vacíos no tienen etiqueta de cierre!

<strong>Navegadores web El propósito de un navegador web </strong> (Chrome, Edge, Firefox, Safari) <strong>es leer documentos HTML y mostrarlos correctamente.</strong>

# Documentos HTML

Los encabezados HTML se definen con las etiquetas - **`<h1> a <h6>.`**

- **`<h1>define el encabezado más importante</h1>`**
<h1>Soy un Encabezado </h1>

- **`<h2>soy  el segundo encabezado importante</h2>`**
<h2>This is heading 2</h2>

- **`<h3>soy  el tercer encabezado importante</h3>`**
<h3>This is heading 3</h3>

- **`<h4>soy  el cuarto encabezado importante</h4>`**
<h4>This is heading 4</h4>

- **`<h5>soy  el quinto encabezado importante</h5>`**
<h5>This is heading 5</h5>

- **`<h5>soy  el sexto encabezado importante</h5>`**
<h5>This is heading 6</h5>

# Los parrafos se definen asi

Los párrafos HTML se definen asi **` <p> etiqueta: </p>`**

# La etiquetas asi

**`<a href="https://google.com">This is a link</a>`**
<a href="https://google.com">Puedes presionarme</a>
El destino del enlace se especifica en el `href` atributo.
Los atributos se utilizan para proporcionar información adicional sobre los elementos HTML.
Aprenderá más sobre los atributos en un capítulo posterior.

# Imágenes HTML

Las imágenes HTML se definen con la `<img>` etiqueta.

El archivo de origen `(src)`, el texto alternativo `(alt)`, `width` y `height` se proporcionan como atributos

# Ver codigo fuente

Simplemente precionando el codigo `ctrl + u ` o haga clic derecho en la página y seleccione "Ver código fuente de la página". Se abrirá una nueva pestaña que contiene el código fuente HTML de la página.

# Inspeccionar un elemento HTML:

Haz clic derecho en un elemento (o en un área en blanco) y elige `"Inspeccionar"` para ver de qué están compuestos los elementos (verás tanto el HTML como el CSS). También puedes editar el HTML o el CSS sobre la marcha en el panel Elementos o Estilos que se abre.

# Cambiar color de etiqueta directamente desde HTML, con css:

`<p style='color:red'></p>`

# Como cambiar de idioma tu pagina web

Siempre debe incluir el langatributo dentro de la `<html>`etiqueta para declarar el idioma de la página web. Esto tiene como objetivo ayudar a los motores de búsqueda y navegadores.

```
<html lang="en">
```

También se pueden añadir códigos de país al código de idioma en el lang atributo. De esta forma, los dos primeros caracteres definen el idioma de la página HTML y los dos últimos, el país.

El siguiente ejemplo especifica inglés como idioma y Estados Unidos como país:

```
<html lang="en-US">
```

tambien otra forma es con xml es asi

```
<html xmlns="http://www.w3.org/1999/xhtml" lang="en" xml:lang="en">
</html>
```

# ISO html Lenguaje
<table>
  <thead>
    <tr>
      <th>Lenguaje</th>
      <th>ISO CODE</th>
    </tr>
  </thead>
  <tbody>
    <tr><td>Abkhazian</td><td>ab</td></tr>
    <tr><td>Afar</td><td>aa</td></tr>
    <tr><td>Afrikaans</td><td>af</td></tr>
    <tr><td>Akan</td><td>ak</td></tr>
    <tr><td>Albanian</td><td>sq</td></tr>
    <tr><td>Amharic</td><td>am</td></tr>
    <tr><td>Arabic</td><td>ar</td></tr>
    <tr><td>Aragonese</td><td>an</td></tr>
    <tr><td>Armenian</td><td>hy</td></tr>
    <tr><td>Assamese</td><td>as</td></tr>
    <tr><td>Avaric</td><td>av</td></tr>
    <tr><td>Avestan</td><td>ae</td></tr>
    <tr><td>Aymara</td><td>ay</td></tr>
    <tr><td>Azerbaijani</td><td>az</td></tr>
    <tr><td>Bambara</td><td>bm</td></tr>
    <tr><td>Bashkir</td><td>ba</td></tr>
    <tr><td>Basque</td><td>eu</td></tr>
    <tr><td>Belarusian</td><td>be</td></tr>
    <tr><td>Bengali (Bangla)</td><td>bn</td></tr>
    <tr><td>Bihari</td><td>bh</td></tr>
    <tr><td>Bislama</td><td>bi</td></tr>
    <tr><td>Bosnian</td><td>bs</td></tr>
    <tr><td>Breton</td><td>br</td></tr>
    <tr><td>Bulgarian</td><td>bg</td></tr>
    <tr><td>Burmese</td><td>my</td></tr>
    <tr><td>Catalan</td><td>ca</td></tr>
    <tr><td>Chamorro</td><td>ch</td></tr>
    <tr><td>Chechen</td><td>ce</td></tr>
    <tr><td>Chichewa, Chewa, Nyanja</td><td>ny</td></tr>
    <tr><td>Chinese</td><td>zh</td></tr>
    <tr><td>Chinese (Simplified)</td><td>zh-Hans</td></tr>
    <tr><td>Chinese (Traditional)</td><td>zh-Hant</td></tr>
    <tr><td>Chuvash</td><td>cv</td></tr>
    <tr><td>Cornish</td><td>kw</td></tr>
    <tr><td>Corsican</td><td>co</td></tr>
    <tr><td>Cree</td><td>cr</td></tr>
    <tr><td>Croatian</td><td>hr</td></tr>
    <tr><td>Czech</td><td>cs</td></tr>
    <tr><td>Danish</td><td>da</td></tr>
    <tr><td>Divehi, Dhivehi, Maldivian</td><td>dv</td></tr>
    <tr><td>Dutch</td><td>nl</td></tr>
    <tr><td>Dzongkha</td><td>dz</td></tr>
    <tr><td>English</td><td>en</td></tr>
    <tr><td>Esperanto</td><td>eo</td></tr>
    <tr><td>Estonian</td><td>et</td></tr>
    <tr><td>Ewe</td><td>ee</td></tr>
    <tr><td>Faroese</td><td>fo</td></tr>
    <tr><td>Fijian</td><td>fj</td></tr>
    <tr><td>Finnish</td><td>fi</td></tr>
    <tr><td>French</td><td>fr</td></tr>
    <tr><td>Fula, Fulah, Pulaar, Pular</td><td>ff</td></tr>
    <tr><td>Galician</td><td>gl</td></tr>
    <tr><td>Gaelic (Scottish)</td><td>gd</td></tr>
    <tr><td>Gaelic (Manx)</td><td>gv</td></tr>
    <tr><td>Georgian</td><td>ka</td></tr>
    <tr><td>German</td><td>de</td></tr>
    <tr><td>Greek</td><td>el</td></tr>
    <tr><td>Greenlandic</td><td>kl</td></tr>
    <tr><td>Guarani</td><td>gn</td></tr>
    <tr><td>Gujarati</td><td>gu</td></tr>
    <tr><td>Haitian Creole</td><td>ht</td></tr>
    <tr><td>Hausa</td><td>ha</td></tr>
    <tr><td>Hebrew</td><td>he</td></tr>
    <tr><td>Herero</td><td>hz</td></tr>
    <tr><td>Hindi</td><td>hi</td></tr>
    <tr><td>Hiri Motu</td><td>ho</td></tr>
    <tr><td>Hungarian</td><td>hu</td></tr>
    <tr><td>Icelandic</td><td>is</td></tr>
    <tr><td>Ido</td><td>io</td></tr>
    <tr><td>Igbo</td><td>ig</td></tr>
    <tr><td>Indonesian</td><td>id</td></tr>
    <tr><td>Interlingua</td><td>ia</td></tr>
    <tr><td>Interlingue</td><td>ie</td></tr>
    <tr><td>Inuktitut</td><td>iu</td></tr>
    <tr><td>Inupiak</td><td>ik</td></tr>
    <tr><td>Irish</td><td>ga</td></tr>
    <tr><td>Italian</td><td>it</td></tr>
    <tr><td>Japanese</td><td>ja</td></tr>
    <tr><td>Javanese</td><td>jv</td></tr>
    <tr><td>Kalaallisut, Greenlandic</td><td>kl</td></tr>
    <tr><td>Kannada</td><td>kn</td></tr>
    <tr><td>Kanuri</td><td>kr</td></tr>
    <tr><td>Kashmiri</td><td>ks</td></tr>
    <tr><td>Kazakh</td><td>kk</td></tr>
    <tr><td>Khmer</td><td>km</td></tr>
    <tr><td>Kikuyu</td><td>ki</td></tr>
    <tr><td>Kinyarwanda (Rwanda)</td><td>rw</td></tr>
    <tr><td>Kirundi</td><td>rn</td></tr>
    <tr><td>Kyrgyz</td><td>ky</td></tr>
    <tr><td>Komi</td><td>kv</td></tr>
    <tr><td>Kongo</td><td>kg</td></tr>
    <tr><td>Korean</td><td>ko</td></tr>
    <tr><td>Kurdish</td><td>ku</td></tr>
    <tr><td>Kwanyama</td><td>kj</td></tr>
    <tr><td>Lao</td><td>lo</td></tr>
    <tr><td>Latin</td><td>la</td></tr>
    <tr><td>Latvian (Lettish)</td><td>lv</td></tr>
    <tr><td>Limburgish (Limburger)</td><td>li</td></tr>
    <tr><td>Lingala</td><td>ln</td></tr>
    <tr><td>Lithuanian</td><td>lt</td></tr>
    <tr><td>Luga-Katanga</td><td>lu</td></tr>
    <tr><td>Luganda, Ganda</td><td>lg</td></tr>
    <tr><td>Luxembourgish</td><td>lb</td></tr>
    <tr><td>Manx</td><td>gv</td></tr>
    <tr><td>Macedonian</td><td>mk</td></tr>
    <tr><td>Malagasy</td><td>mg</td></tr>
    <tr><td>Malay</td><td>ms</td></tr>
    <tr><td>Malayalam</td><td>ml</td></tr>
    <tr><td>Maltese</td><td>mt</td></tr>
    <tr><td>Maori</td><td>mi</td></tr>
    <tr><td>Marathi</td><td>mr</td></tr>
    <tr><td>Marshallese</td><td>mh</td></tr>
    <tr><td>Moldavian</td><td>mo</td></tr>
    <tr><td>Mongolian</td><td>mn</td></tr>
    <tr><td>Nauru</td><td>na</td></tr>
    <tr><td>Navajo</td><td>nv</td></tr>
    <tr><td>Ndonga</td><td>ng</td></tr>
    <tr><td>Northern Ndebele</td><td>nd</td></tr>
    <tr><td>Nepali</td><td>ne</td></tr>
    <tr><td>Norwegian</td><td>no</td></tr>
    <tr><td>Norwegian bokmål</td><td>nb</td></tr>
    <tr><td>Norwegian nynorsk</td><td>nn</td></tr>
    <tr><td>Nuosu</td><td>ii</td></tr>
    <tr><td>Occitan</td><td>oc</td></tr>
    <tr><td>Ojibwe</td><td>oj</td></tr>
    <tr><td>Old Church Slavonic, Old Bulgarian</td><td>cu</td></tr>
    <tr><td>Oriya</td><td>or</td></tr>
    <tr><td>Oromo (Afaan Oromo)</td><td>om</td></tr>
    <tr><td>Ossetian</td><td>os</td></tr>
    <tr><td>Pāli</td><td>pi</td></tr>
    <tr><td>Pashto, Pushto</td><td>ps</td></tr>
    <tr><td>Persian (Farsi)</td><td>fa</td></tr>
    <tr><td>Polish</td><td>pl</td></tr>
    <tr><td>Portuguese</td><td>pt</td></tr>
    <tr><td>Punjabi (Eastern)</td><td>pa</td></tr>
    <tr><td>Quechua</td><td>qu</td></tr>
    <tr><td>Romansh</td><td>rm</td></tr>
    <tr><td>Romanian</td><td>ro</td></tr>
    <tr><td>Russian</td><td>ru</td></tr>
    <tr><td>Sami</td><td>se</td></tr>
    <tr><td>Samoan</td><td>sm</td></tr>
    <tr><td>Sango</td><td>sg</td></tr>
    <tr><td>Sanskrit</td><td>sa</td></tr>
    <tr><td>Serbian</td><td>sr</td></tr>
    <tr><td>Serbo-Croatian</td><td>sh</td></tr>
    <tr><td>Sesotho</td><td>st</td></tr>
    <tr><td>Setswana</td><td>tn</td></tr>
    <tr><td>Shona</td><td>sn</td></tr>
    <tr><td>Sichuan Yi</td><td>ii</td></tr>
    <tr><td>Sindhi</td><td>sd</td></tr>
    <tr><td>Sinhalese</td><td>si</td></tr>
    <tr><td>Siswati</td><td>ss</td></tr>
    <tr><td>Slovak</td><td>sk</td></tr>
    <tr><td>Slovenian</td><td>sl</td></tr>
    <tr><td>Somali</td><td>so</td></tr>
    <tr><td>Southern Ndebele</td><td>nr</td></tr>
    <tr><td>Spanish</td><td>es</td></tr>
    <tr><td>Sundanese</td><td>su</td></tr>
    <tr><td>Swahili (Kiswahili)</td><td>sw</td></tr>
    <tr><td>Swati</td><td>ss</td></tr>
    <tr><td>Swedish</td><td>sv</td></tr>
    <tr><td>Tagalog</td><td>tl</td></tr>
    <tr><td>Tahitian</td><td>ty</td></tr>
    <tr><td>Tajik</td><td>tg</td></tr>
    <tr><td>Tamil</td><td>ta</td></tr>
    <tr><td>Tatar</td><td>tt</td></tr>
    <tr><td>Telugu</td><td>te</td></tr>
    <tr><td>Thai</td><td>th</td></tr>
    <tr><td>Tibetan</td><td>bo</td></tr>
    <tr><td>Tigrinya</td><td>ti</td></tr>
    <tr><td>Tonga</td><td>to</td></tr>
    <tr><td>Tsonga</td><td>ts</td></tr>
    <tr><td>Turkish</td><td>tr</td></tr>
    <tr><td>Turkmen</td><td>tk</td></tr>
    <tr><td>Twi</td><td>tw</td></tr>
    <tr><td>Uyghur</td><td>ug</td></tr>
    <tr><td>Ukrainian</td><td>uk</td></tr>
    <tr><td>Urdu</td><td>ur</td></tr>
    <tr><td>Uzbek</td><td>uz</td></tr>
    <tr><td>Venda</td><td>ve</td></tr>
    <tr><td>Vietnamese</td><td>vi</td></tr>
    <tr><td>Volapük</td><td>vo</td></tr>
    <tr><td>Wallon</td><td>wa</td></tr>
    <tr><td>Welsh</td><td>cy</td></tr>
    <tr><td>Wolof</td><td>wo</td></tr>
    <tr><td>Western Frisian</td><td>fy</td></tr>
    <tr><td>Xhosa</td><td>xh</td></tr>
    <tr><td>Yiddish</td><td>yi</td></tr>
    <tr><td>Yoruba</td><td>yo</td></tr>
    <tr><td>Zhuang, Chuang</td><td>za</td></tr>
    <tr><td>Zulu</td><td>zu</td></tr>
  </tbody>
</table>

# Tooltip
El título Atributo
El `title` atributo define información adicional sobre un elemento.
El valor del atributo de título se mostrará como información sobre herramientas cuando pase el mouse sobre el elemento:
Ejemplo
   ` <p title="Soy un tooltip">Esto es una etiqueta</p>`

<strong>Nota:</strong>Utilice siempre atributos en minúscula. tambien
<strong>Siemre entre comillas  
`<a href="https://google.com">Visit our HTML tutorial</a>`
</strong>

# Encabezados más grandes
Cada encabezado HTML tiene un tamaño predeterminado. Sin embargo, puedes especificar el tamaño de cualquier encabezado con el style atributo , utilizando la propiedad CSS font-size:
  `<h1 style="font-size: 64px;">Encabezado Grande</h1>`
