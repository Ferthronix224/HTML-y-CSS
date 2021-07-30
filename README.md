# HTML

Las siglas de HTML son **H**yper **T**ext **M**arkup **L**anguage, en español Lenguaje marcado de hipertextos, es el lenguaje con el que se define el contenido de las páginas web. Básicamente se trata de un conjunto de etiquetas que sirven para definir el texto y otros elementos que compondrán una página web, como imágenes, listas, vídeos, etc.

Se puede trabajar el HTML con cualquier editor de codigo, desde el bloc de notas de Windows hasta programas profesionales como Adobe Dreamweaver.

El primer archivo de HTML siempre tiene que llamarse "index.html" porque es lo primero que detectan los navegadores.
## Estructura  
**doctype:** Se trata de una etiqueta simple que no necesita cierre y cuya función es facilitar información al servidor web que aloja la página. La información facilitada por ésta etiqueta se refiere al tipo de documento, además es necesaria para la comunicación entre el navegador y el servidor.  
**html:** Se trata de una etiqueta par y es la etiqueta que encierra todo el documento HTML.  
**head:** Es una etiqueta par, define la cabecera del documento y contiene información del mismo (metadatos, scripts, estilos, ubicación de documentos de estilos, título de la pagina entre otros datos).  
**body:** Es una etiqueta par y la conocemos como el cuerpo del sitio web. Todo lo que se escriba dentro de esta etiqueta será visible para los navegadores.
```html
<!doctype html>
<html>

<head>

</head>

<body>

</body>
</html>
```
## Cabecera  
meta: La función de meta viene siendo añadir información sobre la página.  
charset: Viene siendo la configuración en la página para definir el idioma que se usará.  
name: Tiene varias propiedades diferentes que dependiendo de lo que esta adentro es lo que se estará definiendo. Y el name va acompañado de "content" que ahí es donde tenemos que poner el contenido de lo que se definió en el name. En este ejemplo en la etiqueta simple "meta name" estamos poniendo el autor y el nombre del autor.  
Description: En la etiqueta simple "meta name" es la descripción que aparecerá en los navegadores.  
Keywords: En la etiqueta simple "meta name" son las palabras clave que usan los navegadores para filtrar las paginas.  
La etiqueta doble "title" es donde escribimos el nombre de la página.  
La etiqueta simple "link" sirve para vincular hojas de estilo o vincular el icono que aparece al lado del titulo en la parte superior de la página. rel: Es para definir lo que se va a relacionar. Y href: Es para buscar los archivos a usarse en la carpeta.  
```html
<!doctype html>
<html>
<head>
	<meta charset = "utf-8">
	<meta name = "Author" content = "Fernando Adolfo">
	<meta name = "Description" content = "Esta es la forma correcta de hacer páginas web">
	<meta name = "Keywords" content = "html, desarrollo web">
	<title>Mi primera página web</title>
	<link rel="icon" href="img/noun_html_2350456.png">
</head>

<body>
</body>
</html>
```
<img src = "https://user-images.githubusercontent.com/67721157/123534321-ff0d9d00-d6e1-11eb-9158-a8a095139105.png" width = "600" height = "350" alt = "ejemplo" align = "center" />

En la imagen se ve un buen diseño para una página web.

## Cuerpo

Las etiquetas dobles "header" son para el cabezote.  
Las etiquetas dobles "nav" son para la barra de navegación.  
Las etiquetas dobles "section" son para la sección principal.  
Las etiquetas dobles "aside" son para una columna.  
Las etiquetas dobles "article" son para un artículo.  
Las etiquetas dobles "h" seguido de un número entre el 1 y el 6 son para títulos, siendo 1 es más grande y el 6 el más pequeño.  
Las etiquetas dobles "p" son para escribir un párrafo.  
Las etiquetas dobles "b" son para poner el negritas el texto que se ponga adentro.  
La etiqueta simple "br" es para hacer un salto de línea.
La etiqueta simple "hr" es para poner un borde.  
Las etiquetas dobles "a" son para poner un link;  pones "href = "" " y en las comillas pones el link.  

```html
<!doctype html>
<html>
<head>
</head>

<body>
	<header></header>

	<nav></nav>

	<section></section>

	<aside></aside>

	<article></article>

	<h1>Título</h1>
	<h2>Título</h2>
	<h3>Título</h3>
	<h4>Título</h4>
	<h5>Título</h5>
	<h6>Título</h6>

	<p>Esto es un <b>párrafo.</b><br>Esto es otro párrafo.</p>

	<hr>

	<a href="">Vínculo</a>
</body>
</html>
```

**img:** Etiqueta doble para insertar imágenes, con src (source) buscas el link o la ubicación de las imágenes para insertarlas, con width pones el ancho, con height el alto, alt permite proporcionar un texto equivalente al objeto y aligh la posicion.  
**ol:** Etiqueta doble para hacer una lista númerica.  
**li:** Etiqueta doble para insertar items en la lista.  
**ul:** Etiqueta doble para hacer una lista de puntos.  
**table:** Etiqueta doble para declarar una tabla después puedes ponerle borde con "border="1"" dentro de la misma etiqueta de inicio.  
**tr:** Etiqueta doble para declarar una fila.  
**th:** Etiqueta doble para poner el valor de una columna.  
**meter:** Etiqueta doble para poner una barra de progreso, en "value" pones el valor, en "min" pones el valor mínimo de los valores posibles, en "max" pones el valor máximo de esos valores, en "high" pones un valor donde pones un limite que por ejemplo si fueran calificaciones el valor limite para pasar es de 70 para arriba".  
**footer** Etiqueta doble para poner el pie de página.  
```html
<!doctype html>
<html>
<head>
<meta charset="utf-8">
<title>Mi primera página</title>
</head>

<body>
	<img src="img/imagen.jpg" width = "600" alt = ""height = "350" align = "center">

	<ol>
		<li>Carro</li>
		<li>Barco</li>
		<li>Avion</li>
	</ol>

	<ul>
		<li>Carro</li>
		<li>Barco</li>
		<li>Avion</li>
	</ul>

	<table border="1">
		<tr>
			<th>Mes</th>
			<th>Ahorro</th>
		</tr>

		<tr>
			<th>Enero</th>
			<th>$100</th>
		</tr>

		<tr>
			<th>Febrero</th>
			<th>$200</th>
		</tr>
	</table>

	<h1>Resultados del examen</h1>
	<p>Fernando: <meter value = "90" min = "0" max = "100" high = "70"></meter></p>
	<p>Adolfo: <meter value = "69" min = "0" max = "100" high = "70"></meter></p>
	<p>Uriel: <meter value = "40" min = "0" max = "100" high = "70"></meter></p>
	<p>Johan: <meter value = "85" min = "0" max = "100" high = "70"></meter></p>

	<footer>Este es el pie de página</footer>
</body>
</html>
```

**figure:** Etiqueta doble que sirve para estructurar mejor en la maquetacion las imagenes que pongamos en nuestro documento.  
**figcaption: ** Etiqueta doble que sirve para ponerle descripción a las imagenes.  
**thead:** Etiqueta doble que se pone en las tablas para indicar que fila es la cabecera.  
**tbody:** Etiqueta doble que se pone en las tablas para indicar que filas son el cuerpo. Y una cosa que hay que tener en cuenta es que las columnas en el cuerpo se hace con la etiqueta doble **td**.  

```html
<!doctype html>
<html>
<head>
<meta charset="utf-8">
<title>Mi primera página</title>
</head>

<body>
	<figure>
	<img src="img/imagen.jpg" width = "600" height = "350" alt="" align = "center">
	</figure>
	<figcaption>Descripción de la imagen</figcaption>
	<ol>
		<li>Carro</li>
		<li>Barco</li>
		<li>Avion</li>
	</ol>

	<ul>
		<li>Carro</li>
		<li>Barco</li>
		<li>Avion</li>
	</ul>

	<table border="1">
		<thead>
			<tr>
				<th>Mes</th>
				<th>Ahorro</th>
			</tr>
		</thead>

		<tbody>
			<tr>
				<td>Enero</td>
				<td>$100</td>
			</tr>

			<tr>
				<td>Febrero</td>
				<td>$200</td>
			</tr>
		</tbody>			
	</table>

	<h1>Resultados del examen</h1>
	<p>Fernando: <meter value = "90" min = "0" max = "100" high = "70"></meter></p>
	<p>Adolfo: <meter value = "69" min = "0" max = "100" high = "70"></meter></p>
	<p>Uriel: <meter value = "40" min = "0" max = "100" high = "70"></meter></p>
	<p>Johan: <meter value = "85" min = "0" max = "100" high = "70"></meter></p>

	<h2>Resultados de ventas</h2>
	<p>Febrero: <progress value = "70" min = "0" max = "100"></progress></p>
	<p>Marzo: <progress value = "80" min = "0" max = "100"></progress></p>
	<p>Abril: <progress value = "90" min = "0" max = "100"></progress></p>
	<p>Mayo: <progress value = "100" min = "0" max = "100"></progress></p>

	<footer>Este es el pie de página</footer>
</body>
</html>
```
# Audio  

Para poner un audio se pone la etiqueta de audio y adentro se pone "autoplay, controls, loop y preload".  

```html
<!doctype html>
<html>
<head>
<meta charset="utf-8">
<title>Audio</title>
</head>

<body>
	<audio autoplay controls loop preload="auto">
	<!--Ogg MORBIS .ogg-->
	<!--MP3 .mp3-->
	<!--WAV .wav-->
	<!--ACC .m4a, .m4b, .m4p, .mp4, .acc-->

		<source src="audio/Fall Out Boy - Thnks Fr Th Mmrs (subtitulada al español)(MP3_128K).mp3">
	</audio>
</body>
</html>
```
# Video  

En el video se puede observar que estan los mismos atributos que audio sólo que aqui podemos personalizar el ancho y alto del video.  

```html
<!doctype html>
<html>
<head>
</head>

<body>
  <video autoplay controls loop width="500" height="200">
    <source src= "video/Fall Out Boy - Thnks fr th Mmrs (Official Music Video)(720P_HD).mp4" type="video/mp4">
  </video>
</body>
</html>
```

# Etiquetas de Medios  

Nos va a permitir insertar o incrustar documentos HTML, un vídeo en línea, un mapa, un reproductor de sonido en línea, entre otros elementos dentro del documento HTML5 principal.  


```html
<!doctype html>
<html>
<head>
</head>

<body>
  <iframe src="https://www.youtube.com/embed/gWBYrwyQxIM" width="500" height="300" frameborder = "0" allowfullscreen></iframe>
</body>
</html>
```
# Etiqueta Formulario

En HTML5 podemos crear formularios para que las personas puyedan registrarse, puedan enviar sus dudas, puedan escribir comentarios y puedan interartuar ccon el creador de la página.

**center:** Etiqueta doble que se usa para centrar las cosas.  
**form:** Etiqueta doble que se usa para los formularios.  
```html
<!doctype html>
<html>
<head>
  <meta charset = "utf-8">
</head>

<body>
  <center>
    <form>
      <label for="texto">Entrada de texto</label>
      <input id="texto" type = "text" placeholder = "Entrada de texto" value = "" required>
      <!--readonly-->

      <br>
      <br>

      <label for="correo">Entrada de correo</label>
      <input id="correo" type = "email" placeholder = "Entrada de correo" value = "" required>

      <br>
      <br>

      <label for="pass">Entrada de contraseña</label>
      <input id="pass" type = "password" placeholder = "Entrada de contraseña" value = "" required>

      <br>
      <br>

      <label for="numero">Entrada de números</label>
      <input id="numero" type = "number" value="0" min="-1" max="5">

      <br>
      <br>

      <select>
        <option>Opcion 1</option>
        <option>Opcion 2</option>
        <option>Opcion 3</option>
      </select>

      <br>
      <br>

      <input type="checkbox" id="rojo"><label for="rojo">Rojo</label>
      <input type="checkbox" id="amarillo"><label for="amarillo">Amarillo</label>
      <input type="checkbox" id="verde"><label for="verde">Verde</label>

      <br>
      <br>

      <input type="radio" id="blanco" name="radio" checked><label for="blanco">Blanco</label>
      <input type="radio" id="negro" name="radio"><label for="negro">Negro</label>

      <br>
      <br>

      <input type="submit" value="Enviar formulario">
    </form>
  </center>
</body>
</html>
```
# CSS

CSS (en inglés Cascading Style Sheets) es lo que se denomina lenguaje de hojas de estilo en cascada y se usa para estilizar elementos escritos en un lenguaje de marcado como HTML. CSS separa el contenido de la representación visual del sitio.  

# Sintaxis  

**style:** Etiqueta doble que se usa para poner el código del CSS y debe ponerse antes de cerrar el **head**.  

Hay 3 maneras de usar el CSS que viene siendo a traves de las etiquetas, mis id's y las clases/grupos.

**Etiquetas:** Simplemente pones el nombre de la etiqueta y abres llaves.  
**ID:** Pones un hashtag/gato luego el nombre del ID y abres llaves.  
**Clases/Grupos:** Pones un punto luego el nombre del grupo y abres llaves.

```html
<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8">
    <title>Sintaxis</title>

    <style>
      /*

      Selector{

        propiedad:valor;

    }

      */

      body{

        background:red;

      }

      #caja{
        width:200px;
        height:200px;
        background:yellow;
      }

      .grupo{
        width:200px;
        height:200px;
        background:blue;
        margin:10px;
      }
    </style>
  </head>
  <body>

    <div id="caja"></div>

    <div class="grupo"></div>
    <div class="grupo"></div>
    <div class="grupo"></div>

  </body>
</html>

```

# Propiedades de Forma

```html
<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8">
    <title>Propiedades de Forma</title>
    <style>
      header{
        width:1000px;
        height:200px;
        background:blue;
        margin:20px;
        border:5px solid yellow;
        padding:20px;
      }

      #logo{
        width:100px;
        height:100px;
        background:green;
        margin:20px;
        border:5px solid white;
        border-radius:10px;
      }
    </style>
  </head>
  <body>
    <header>
      <div id="logo">Logotipo</div>
    </header>
  </body>
</html>

```

## Propiedades de color
```html
<!doctype html>
<html>
  <head>
    <meta charset="utf-8">
    <title>Propiedades de color</title>
    <style>
      .grupo{
       width:200px;
       height:200px;
       margin:20px;
      }

      #c1{
      background:magenta;
      }

      #c2{
      background:#C70039;
      }

      #c3{
      background:rgba(2, 2, 2, 1);
      }
    </style>
  </head>
  <body>
    <div id="c1" class="grupo"></div>
    <div id="c2" class="grupo"></div>
    <div id="c3" class="grupo"></div>
  </body>
</html>
```
