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
    <tr>
      <td>Abkhazian</td>
      <td>ab</td>
    </tr>
    <tr>
    <td>Afar</td>
      <td>aa</td>
    </tr>
     <tr>
    <td>Afrikaans</td>
      <td>af</td>
    </tr>
    <tr>
    <td>Akan</td>
      <td>ak</td>
    </tr>
    <tr>
    <td>Albanian</td>
      <td>sq</td>
    </tr>
     <tr>
    <td>Amharic</td>
      <td>am</td>
    </tr>
    <td>Arabic</td>
      <td>ar</td>
    </tr>
     <td>Arabic</td>
      <td>ar</td>
    </tr>
Aragonese	an
Armenian	hy
Assamese	as
Avaric	av
Avestan	ae
Aymara	ay
Azerbaijani	az
Bambara	bm
Bashkir	ba
Basque	eu
Belarusian	be
Bengali (Bangla)	bn
Bihari	bh
Bislama	bi
Bosnian	bs
Breton	br
Bulgarian	bg
Burmese	my
Catalan	ca
Chamorro	ch
Chechen	ce
Chichewa, Chewa, Nyanja	ny
Chinese	zh
Chinese (Simplified)	zh-Hans
Chinese (Traditional)	zh-Hant
Chuvash	cv
Cornish	kw
Corsican	co
Cree	cr
Croatian	hr
Czech	cs
Danish	da
Divehi, Dhivehi, Maldivian	dv
Dutch	nl
Dzongkha	dz
English	en
Esperanto	eo
Estonian	et
Ewe	ee
Faroese	fo
Fijian	fj
Finnish	fi
French	fr
Fula, Fulah, Pulaar, Pular	ff
Galician	gl
Gaelic (Scottish)	gd
Gaelic (Manx)	gv
Georgian	ka
German	de
Greek	el
Greenlandic	kl
Guarani	gn
Gujarati	gu
Haitian Creole	ht
Hausa	ha
Hebrew	he
Herero	hz
Hindi	hi
Hiri Motu	ho
Hungarian	hu
Icelandic	is
Ido	io
Igbo	ig
Indonesian	id, in
Interlingua	ia
Interlingue	ie
Inuktitut	iu
Inupiak	ik
Irish	ga
Italian	it
Japanese	ja
Javanese	jv
Kalaallisut, Greenlandic	kl
Kannada	kn
Kanuri	kr
Kashmiri	ks
Kazakh	kk
Khmer	km
Kikuyu	ki
Kinyarwanda (Rwanda)	rw
Kirundi	rn
Kyrgyz	ky
Komi	kv
Kongo	kg
Korean	ko
Kurdish	ku
Kwanyama	kj
Lao	lo
Latin	la
Latvian (Lettish)	lv
Limburgish ( Limburger)	li
Lingala	ln
Lithuanian	lt
Luga-Katanga	lu
Luganda, Ganda	lg
Luxembourgish	lb
Manx	gv
Macedonian	mk
Malagasy	mg
Malay	ms
Malayalam	ml
Maltese	mt
Maori	mi
Marathi	mr
Marshallese	mh
Moldavian	mo
Mongolian	mn
Nauru	na
Navajo	nv
Ndonga	ng
Northern Ndebele	nd
Nepali	ne
Norwegian	no
Norwegian bokmål	nb
Norwegian nynorsk	nn
Nuosu	ii
Occitan	oc
Ojibwe	oj
Old Church Slavonic, Old Bulgarian	cu
Oriya	or
Oromo (Afaan Oromo)	om
Ossetian	os
Pāli	pi
Pashto, Pushto	ps
Persian (Farsi)	fa
Polish	pl
Portuguese	pt
Punjabi (Eastern)	pa
Quechua	qu
Romansh	rm
Romanian	ro
Russian	ru
Sami	se
Samoan	sm
Sango	sg
Sanskrit	sa
Serbian	sr
Serbo-Croatian	sh
Sesotho	st
Setswana	tn
Shona	sn
Sichuan Yi	ii
Sindhi	sd
Sinhalese	si
Siswati	ss
Slovak	sk
Slovenian	sl
Somali	so
Southern Ndebele	nr
Spanish	es
Sundanese	su
Swahili (Kiswahili)	sw
Swati	ss
Swedish	sv
Tagalog	tl
Tahitian	ty
Tajik	tg
Tamil	ta
Tatar	tt
Telugu	te
Thai	th
Tibetan	bo
Tigrinya	ti
Tonga	to
Tsonga	ts
Turkish	tr
Turkmen	tk
Twi	tw
Uyghur	ug
Ukrainian	uk
Urdu	ur
Uzbek	uz
Venda	ve
Vietnamese	vi
Volapük	vo
Wallon	wa
Welsh	cy
Wolof	wo
Western Frisian	fy
Xhosa	xh
Yiddish	yi, ji
Yoruba	yo
Zhuang, Chuang	za
Zulu	zu

    
    
    


  </tbody>
</table>
