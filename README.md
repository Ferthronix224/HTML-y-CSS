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
**width:** Ancho.  
**height:** Alto.  
**background:** Color.  
**margin:** La propiedad margin establece los márgenes de un elemento especificando entre uno y cuatro valores, donde cada valor es una longitud, un porcentaje o auto. Los valores en porcentaje se refieren al ancho del elemento padre. Se permiten márgenes negativos.

Si se dan cuatro valores, se aplican a los márgenes superior, derecho, inferior e izquierdo, respectivamente. Si se da un valor, se aplica a todos los lados. Si se dan dos o tres valores, los valores faltantes se toman del lado opuesto.  
**border:** La propiedad border permite definir de golpe todos los bordes en una única regla de la hoja de estilos. Se puede utilizar border para definir el o los valores siguientes: border-width, border-style, border-color.  
**padding:**El área de padding es el espacio entre el contenido del elemento y su borde ( border ). No se permiten valores negativos. La propiedad padding es un atajo para evitar la asignación de cada lado por separado.  
**border-radius:** Permite especificar el redondeo de todas las esquinas de una caja CSS y definir la forma en que se debe hacer. Todos los elementos. inherit (se heredan las características del elemento padre).  
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

Hay 3 maneras de configurar colores en HTML que viene siendo por nombre, por color hexadecimal y por RGBA.
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
# Propiedades de Ubicación Parte 1

```html
<!doctype>
<html>
   <head>
      <meta charset="utf-8">
      <title>Propiedades de ubicacion</title>
   </head>
   <style>
      *{
      margin:0;
      padding:0;
      list-style:none;
      }
      header{
      position:relative;
      margin:auto;
      width:1000px;
      height:120px;
      background:#444;
      }
      nav{
      position:relative;
      margin:auto;
      width:1000px;
      height:48px;
      background:#aaa;
      }
      }
   </style>
   <body>
      <!--Inicia el cabezote-->
      <header>
         <div id="logo"></div>
         <div id="icono1"></div>
         <div id="icono2"></div>
         <div id="icono3"></div>
      </header>
      <!-- Cierra Cabezote -->
      <!-- Inicia Barra de Navegación -->
      <nav>
         <ul>
            <li class="botones"></li>
            <li class="botones"></li>
            <li class="botones"></li>
            <li class="botones"></li>
            <li class="botones"></li>
         </ul>
      </nav>
      <!-- Cierra Barra de Navegación -->
      <!--  Inicia parte Superior -->
      <div id="top">
         <ul>
            <li></li>
            <li></li>
            <li></li>
         </ul>
      </div>
      <!-- Cierra parte Superior -->
      <!-- Inicia Seccion -->
      <section>
         <aside id="izq"></aside>
         <article></article>
         <aside id="der"></aside>
      </section>
      <!-- Cierre Sección -- >
         <!-- Inicia pie de pagina -->
      <footer></footer>
      <!-- Cierra pie de pagina -->
   </body>
</html>

```
Es importante aclarar el uso de las margenes.  
Tenemos varias opciones de colocar margenes a una caja en posicion relativa.  

margin: auto -> Significa que sus margenes van a dar una respuesta automatica en el flujo de nudos y se ubique dentro en la pantalla en la parte central a nivel lateral y en la parte superior de la pantalla.  
Las margenes las podemos ubicar de acuerdo a las 4 margenes en donde esta posicionada la caja. Las cuales son:  
- top (Arriba)
- right (Derecha)
- bottom (Abajo)
- left (Izquierda)  

Ejemplo: "margin: 20px 30px 40px 50px"

# Propiedades de Ubicacion Parte 2

```html
<!doctype>
<html>
   <head>
      <meta charset="utf-8">
      <title>Propiedades de ubicacion</title>
   </head>
   <style>
      *{
      margin:0;
      padding:0;
      list-style:none;
      }
      header{
      position:relative;
      margin:20px auto;
      width:1000px;
      height:120px;
      background:#444;
      }
      nav{
      position:relative;
      margin:auto;
      width:1000px;
      height:48px;
      background:#aaa;
      }
      #top{
        position:relative;
        margin:20px auto;
        width:1000px;
        height:192px;
        background:#888;
      }
      section{
      position:relative;
      margin:auto;
      width:1000px;
      height:453px;
      background:#aaa;
      }
      footer{
        position:relative;
        margin:20px auto;
        width:1000px;
        height:70px;
        background:#888;
      }
      }
   </style>
   <body>
      <!--Inicia el cabezote-->
      <header>
         <div id="logo"></div>
         <div id="icono1"></div>
         <div id="icono2"></div>
         <div id="icono3"></div>
      </header>
      <!-- Cierra Cabezote -->
      <!-- Inicia Barra de Navegación -->
      <nav>
         <ul>
            <li class="botones"></li>
            <li class="botones"></li>
            <li class="botones"></li>
            <li class="botones"></li>
            <li class="botones"></li>
         </ul>
      </nav>
      <!-- Cierra Barra de Navegación -->
      <!--  Inicia parte Superior -->
      <div id="top">
         <ul>
            <li></li>
            <li></li>
            <li></li>
         </ul>
      </div>
      <!-- Cierra parte Superior -->
      <!-- Inicia Seccion -->
      <section>
         <aside id="izq"></aside>
         <article></article>
         <aside id="der"></aside>
      </section>
      <!-- Cierre Sección -- >
         <!-- Inicia pie de pagina -->
      <footer></footer>
      <!-- Cierra pie de pagina -->
   </body>
</html>

```

# Propiedades de Ubicación Parte 3

````html
<!doctype>
<html>
   <head>
      <meta charset="utf-8">
      <title>Propiedades de ubicacion</title>
   </head>
   <style>
      *{
      margin:0;
      padding:0;
      list-style:none;
      }
      header{
      position:relative;
      margin:20px auto;
      width:1000px;
      height:120px;
      background:#444;
      }
      #logo{
        position:absolute;
        top:30px;
        left:30px;
        width:200px;
        height:60px;
        background:#ccc;
      }
      .redes{
        position: absolute;
        width: 42px;
        height: 42px;
        background: #ccc;
        border-radius: 100%;
      }
      #icono1{
        top:42px;
        right: 120px;
      }
      #icono2{
        top:42px;
        right: 74px;
      }
      #icono3{
        top:42px;
        right: 19px;
      }
      nav{
      position:relative;
      margin:auto;
      width:1000px;
      height:48px;
      background:#aaa;
      }
      .botones{
        float:left;
        width: 196px;
        height: 48px;
        background: #333;
        margin: 0px 2px;
      }
      #top{
        position:relative;
        margin:20px auto;
        width:1000px;
        height:192px;
        background:#888;
      }
      section{
      position:relative;
      margin:auto;
      width:1000px;
      height:453px;
      background:#aaa;
      }
      footer{
        position:relative;
        margin:20px auto;
        width:1000px;
        height:70px;
        background:#888;
      }
      }
   </style>
   <body>
      <!--Inicia el cabezote-->
      <header>
         <div id="logo"></div>
         <div id="icono1" class="redes"></div>
         <div id="icono2" class="redes"></div>
         <div id="icono3" class="redes"></div>
      </header>
      <!-- Cierra Cabezote -->
      <!-- Inicia Barra de Navegación -->
      <nav>
         <ul>
            <li class="botones"></li>
            <li class="botones"></li>
            <li class="botones"></li>
            <li class="botones"></li>
            <li class="botones"></li>
         </ul>
      </nav>
      <!-- Cierra Barra de Navegación -->
      <!--  Inicia parte Superior -->
      <div id="top">
         <ul>
            <li></li>
            <li></li>
            <li></li>
         </ul>
      </div>
      <!-- Cierra parte Superior -->
      <!-- Inicia Seccion -->
      <section>
         <aside id="izq"></aside>
         <article></article>
         <aside id="der"></aside>
      </section>
      <!-- Cierre Sección -- >
         <!-- Inicia pie de pagina -->
      <footer></footer>
      <!-- Cierra pie de pagina -->
   </body>
</html>
```
# Propiedades de Ubicacion Parte 4

```html
<!doctype>
<html>
   <head>
      <meta charset="utf-8">
      <title>Propiedades de ubicacion</title>
   </head>
   <style>
      *{
      margin:0;
      padding:0;
      list-style:none;
      }
      header{
      position:relative;
      margin:20px auto;
      width:1000px;
      height:120px;
      background:#444;
      }
      #logo{
        position:absolute;
        top:30px;
        left:30px;
        width:200px;
        height:60px;
        background:#ccc;
      }
      .redes{
        position: absolute;
        width: 42px;
        height: 42px;
        background: #ccc;
        border-radius: 100%;
      }
      #icono1{
        top:42px;
        right: 120px;
      }
      #icono2{
        top:42px;
        right: 74px;
      }
      #icono3{
        top:42px;
        right: 19px;
      }
      nav{
      position:relative;
      margin:auto;
      width:1000px;
      height:48px;
      background:#aaa;
      }
      .botones{
        float:left;
        width: 196px;
        height: 48px;
        background: #333;
        margin: 0px 2px;
      }
      #top{
        position:relative;
        margin:20px auto;
        width:1000px;
        height:192px;
      }
      #top ul{
        width: 1010px;
        height: 192px;
      }
      #top ul li{
        float:left;
        width: 326px;
        height: 192px;
        background: black;
        margin-right: 10px;
      }
      section{
      position:relative;
      margin:auto;
      width:1000px;
      height:453px;
      background:#aaa;
      }
      aside#izq{
        position: absolute;
        left: 0;
        top:0;
        width: 200px;
        height: 453px;
        background: #333;
      }
      article{
        position: absolute;
        left: 200px;
        top:0;
        width: 600px;
        height: 453px;
        background: #667;
      }
      aside#der{
        position: absolute;
        right: 0;
        top:0;
        width: 200px;
        height: 453px;
        background: #333;
      }
      footer{
        position:relative;
        margin:20px auto;
        width:1000px;
        height:70px;
        background:#888;
      }
      }
   </style>
   <body>
      <!--Inicia el cabezote-->
      <header>
         <div id="logo"></div>

         <div id="icono1" class="redes"></div>
         <div id="icono2" class="redes"></div>
         <div id="icono3" class="redes"></div>
      </header>
      <!-- Cierra Cabezote -->
      <!-- Inicia Barra de Navegación -->
      <nav>
         <ul>
            <li class="botones"></li>
            <li class="botones"></li>
            <li class="botones"></li>
            <li class="botones"></li>
            <li class="botones"></li>
         </ul>
      </nav>
      <!-- Cierra Barra de Navegación -->
      <!--  Inicia parte Superior -->
      <div id="top">
         <ul>
            <li></li>
            <li></li>
            <li></li>
         </ul>
      </div>
      <!-- Cierra parte Superior -->
      <!-- Inicia Seccion -->
      <section>
         <aside id="izq"></aside>
         <article></article>
         <aside id="der"></aside>
      </section>
      <!-- Cierre Sección -- >
         <!-- Inicia pie de pagina -->
      <footer></footer>
      <!-- Cierra pie de pagina -->
   </body>
</html>
```
# Propiedades de Texto Parte 1
Pagina para buscar fuentes: https://fonts.google.com
```html
<!doctype>
<html>
   <head>
      <meta charset="utf-8">
      <title>Propiedades de ubicacion</title>
      <link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Pacifico&display=swap" rel="stylesheet">

<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Source+Code+Pro:wght@200&display=swap" rel="stylesheet">
   </head>
   <style>
      *{
      margin:0;
      padding:0;
      list-style:none;
      font-family: 'Source Code Pro', monospace;
      }
      header{
      position:relative;
      margin:20px auto;
      width:1000px;
      height:120px;
      }
      #logo{
        position:absolute;
        top:30px;
        left:30px;
        width:200px;
        height:60px;
        font-family: 'Pacifico', cursive;
        font-size: 50px;
        text-align: center;
        line-height: 60px;
      }
      .redes{
        position: absolute;
        width: 42px;
        height: 42px;
        background: #ccc;
        border-radius: 100%;
        text-align: center;
        line-height: 42px;
        color: white;
      }
      #icono1{
        top:42px;
        right: 120px;
        background: blue;
      }
      #icono2{
        top:42px;
        right: 74px;
        background: green;
      }
      #icono3{
        top:42px;
        right: 19px;
        background: red;
      }
      nav{
      position:relative;
      margin:auto;
      width:1000px;
      height:48px;
      background:#aaa;
      }
      .botones{
        float:left;
        width: 196px;
        height: 48px;
        background: rgba(100,0,255,1);
        margin: 0px 2px;
        font-family: 'Pacifico', cursive;
        color: white;
        text-align: center;
        line-height: 48px;
      }
      #top{
        position:relative;
        margin:20px auto;
        width:1000px;
        height:192px;
      }
      #top ul{
        width: 1010px;
        height: 192px;
      }
      #top ul li{
        float:left;
        width: 326px;
        height: 192px;
        background: gray;
        margin-right: 10px;
      }
      section{
      position:relative;
      margin:auto;
      width:1000px;
      height:453px;
      background:#aaa;
      }
      aside#izq{
        position: absolute;
        left: 0;
        top:0;
        width: 200px;
        height: 453px;
        background: #333;
      }
      article{
        position: absolute;
        left: 200px;
        top:0;
        width: 600px;
        height: 453px;
        background: #667;
      }
      aside#der{
        position: absolute;
        right: 0;
        top:0;
        width: 200px;
        height: 453px;
        background: #333;
      }
      footer{
        position:relative;
        margin:20px auto;
        width:1000px;
        height:70px;
        background:#888;
      }
      }
   </style>
   <body>
      <!--Inicia el cabezote-->
      <header>
         <div id="logo">Logotipo</div>

         <div id="icono1" class="redes">X</div>
         <div id="icono2" class="redes">X</div>
         <div id="icono3" class="redes">X</div>
      </header>
      <!-- Cierra Cabezote -->
      <!-- Inicia Barra de Navegación -->
      <nav>
         <ul>
            <li class="botones">Boton 1</li>
            <li class="botones">Boton 2</li>
            <li class="botones">Boton 3</li>
            <li class="botones">Boton 4</li>
            <li class="botones">Boton 5</li>
         </ul>
      </nav>
      <!-- Cierra Barra de Navegación -->
      <!--  Inicia parte Superior -->
      <div id="top">
         <ul>
            <li>
              <img src="img/1.jpg" height="100px" width="100px">
              <h1>Algo</h1>
              <p>lklcsajls lkcslajsclj</p>
            </li>
            <li>
              <img src="img/2.jpg" height="100px" width="100px">
              <h1>Algo</h1>
              <p>lklcsajls lkcslajsclj</p>
            </li>
            <li>
              <img src="img/3.jpg" height="100px" width="100px">
              <h1>Algo</h1>
              <p>lklcsajls lkcslajsclj</p>
            </li>
         </ul>
      </div>
      <!-- Cierra parte Superior -->
      <!-- Inicia Seccion -->
      <section>
         <aside id="izq"></aside>
         <article>
           <h1>Fierro pariente</h1>
           <p><img src="img/1.jpg" height="100px" width="100px">There’s no more horrific sound than the screams of a mother who has just lost her child. Those were the sounds that awoke me in the middle of the night when the neighbor's boy passed away during the night. Officially he died from an undiagnosed, hereditary heart condition, but the rumors told another story entirely.
           </p>
           <br>
           <p>Mary had always been a big part of our community, arranging barbecues and birthday parties, getting along with each and everyone in the neighborhood. All while being a working, single mother. Her son, Ulrich, was the most lively boy, outgoing and smart. We all expected big things from him as he grew up, and he loved the attention.
           </p>
         </article>
         <aside id="der"></aside>
      </section>
      <!-- Cierre Sección -- >
         <!-- Inicia pie de pagina -->
      <footer>
        &copy; Todos los derechos reservados.
      </footer>
      <!-- Cierra pie de pagina -->
   </body>
</html>
```
# Propiedades de Texto Parte 2
```html
<!doctype>
<html>
   <head>
      <meta charset="utf-8">
      <title>Propiedades de ubicacion</title>
      <link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Pacifico&display=swap" rel="stylesheet">

<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Source+Code+Pro:wght@200&display=swap" rel="stylesheet">
   </head>
   <style>
      *{
      margin:0;
      padding:0;
      list-style:none;
      font-family: 'Source Code Pro', monospace;
      }
      header{
      position:relative;
      margin:20px auto;
      width:1000px;
      height:120px;
      }
      #logo{
        position:absolute;
        top:30px;
        left:30px;
        width:200px;
        height:60px;
        font-family: 'Pacifico', cursive;
        font-size: 50px;
        text-align: center;
        line-height: 60px;
      }
      .redes{
        position: absolute;
        width: 42px;
        height: 42px;
        background: #ccc;
        border-radius: 100%;
        text-align: center;
        line-height: 42px;
        color: white;
      }
      #icono1{
        top:42px;
        right: 120px;
        background: blue;
      }
      #icono2{
        top:42px;
        right: 74px;
        background: green;
      }
      #icono3{
        top:42px;
        right: 19px;
        background: red;
      }
      nav{
      position:relative;
      margin:auto;
      width:1000px;
      height:48px;
      background:#aaa;
      }
      .botones{
        float:left;
        width: 196px;
        height: 48px;
        background: rgba(100,0,255,1);
        margin: 0px 2px;
        font-family: 'Pacifico', cursive;
        color: white;
        text-align: center;
        line-height: 48px;
      }
      #top{
        position:relative;
        margin:20px auto;
        width:1000px;
        height:192px;
      }
      #top ul{
        width: 1010px;
        height: 192px;
      }
      #top ul li{
        float:left;
        width: 326px;
        height: 192px;
        margin-right: 10px;
        text-align: center;
      }
      #top ul li img{
        border-radius: 100%;
        height: 100px;
      }
      #top ul li h1{
        font-family: 'Pacifico', cursive;
      }
      #top ul li p{
        font-size: 14px;
        margin: 10px;
      }
      section{
      position:relative;
      margin:auto;
      width:1000px;
      height:453px;
      }
      aside#izq{
        position: absolute;
        left: 0;
        top:0;
        width: 200px;
        height: 453px;
        background: #333;
      }
      article{
        position: absolute;
        left: 200px;
        top:0;
        width: 600px;
        height: 453px;
      }
      article h1{
        font-family: 'Pacifico', cursive;
        font-size: 40px;
        margin:20px;
      }
      article p{
        margin: 5px 20px;
        font-size: 14px;
        text-align: justify;
      }
      article p img{
        float: left;
        margin-right: 20px;
      }
      aside#der{
        position: absolute;
        right: 0;
        top:0;
        width: 200px;
        height: 453px;
        background: #333;
      }
      footer{
        position:relative;
        margin:20px auto;
        width:1000px;
        height:70px;
        text-align: center;
        line-height: 70px;
        color: white;
        background: rgba(100,0,255,1);
      }
      }
   </style>
   <body>
      <!--Inicia el cabezote-->
      <header>
         <div id="logo">Logotipo</div>

         <div id="icono1" class="redes">X</div>
         <div id="icono2" class="redes">X</div>
         <div id="icono3" class="redes">X</div>
      </header>
      <!-- Cierra Cabezote -->
      <!-- Inicia Barra de Navegación -->
      <nav>
         <ul>
            <li class="botones">Boton 1</li>
            <li class="botones">Boton 2</li>
            <li class="botones">Boton 3</li>
            <li class="botones">Boton 4</li>
            <li class="botones">Boton 5</li>
         </ul>
      </nav>
      <!-- Cierra Barra de Navegación -->
      <!--  Inicia parte Superior -->
      <div id="top">
         <ul>
            <li>
              <img src="img/1.jpg" height="100px" width="100px">
              <h1>Algo</h1>
              <p>lklcsajls lkcslajsclj</p>
            </li>
            <li>
              <img src="img/2.jpg" height="100px" width="100px">
              <h1>Algo</h1>
              <p>lklcsajls lkcslajsclj</p>
            </li>
            <li>
              <img src="img/3.jpg" height="100px" width="100px">
              <h1>Algo</h1>
              <p>lklcsajls lkcslajsclj</p>
            </li>
         </ul>
      </div>
      <!-- Cierra parte Superior -->
      <!-- Inicia Seccion -->
      <section>
         <aside id="izq"></aside>
         <article>
           <h1>Fierro pariente</h1>
           <p><img src="img/1.jpg" height="100px" width="100px">There’s no more horrific sound than the screams of a mother who has just lost her child. Those were the sounds that awoke me in the middle of the night when the neighbor's boy passed away during the night. Officially he died from an undiagnosed, hereditary heart condition, but the rumors told another story entirely.
           </p>
           <br>
           <p>Mary had always been a big part of our community, arranging barbecues and birthday parties, getting along with each and everyone in the neighborhood. All while being a working, single mother. Her son, Ulrich, was the most lively boy, outgoing and smart. We all expected big things from him as he grew up, and he loved the attention.
           </p>
         </article>
         <aside id="der"></aside>
      </section>
      <!-- Cierre Sección -- >
         <!-- Inicia pie de pagina -->
      <footer>
        &copy; Todos los derechos reservados.
      </footer>
      <!-- Cierra pie de pagina -->
   </body>
</html>

```
# Propiedades de lista
```html
<!doctype>
<html>
   <head>
      <meta charset="utf-8">
      <title>Propiedades de ubicacion</title>
      <link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Pacifico&display=swap" rel="stylesheet">

<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Source+Code+Pro:wght@200&display=swap" rel="stylesheet">
   </head>
   <style>
      *{
      margin:0;
      padding:0;
      list-style:none;
      font-family: 'Source Code Pro', monospace;
      }
      header{
      position:relative;
      margin:20px auto;
      width:1000px;
      height:120px;
      }
      #logo{
        position:absolute;
        top:30px;
        left:30px;
        width:200px;
        height:60px;
        font-family: 'Pacifico', cursive;
        font-size: 50px;
        text-align: center;
        line-height: 60px;
      }
      .redes{
        position: absolute;
        width: 42px;
        height: 42px;
        background: #ccc;
        border-radius: 100%;
        text-align: center;
        line-height: 42px;
        color: white;
      }
      #icono1{
        top:42px;
        right: 120px;
        background: blue;
      }
      #icono2{
        top:42px;
        right: 74px;
        background: green;
      }
      #icono3{
        top:42px;
        right: 19px;
        background: red;
      }
      nav{
      position:relative;
      margin:auto;
      width:1000px;
      height:48px;
      background:#aaa;
      }
      .botones{
        float:left;
        width: 196px;
        height: 48px;
        background: rgba(100,0,255,1);
        margin: 0px 2px;
        font-family: 'Pacifico', cursive;
        color: white;
        text-align: center;
        line-height: 48px;
      }
      #top{
        position:relative;
        margin:20px auto;
        width:1000px;
        height:192px;
      }
      #top ul{
        width: 1010px;
        height: 192px;
      }
      #top ul li{
        float:left;
        width: 326px;
        height: 192px;
        margin-right: 10px;
        text-align: center;
      }
      #top ul li img{
        border-radius: 100%;
        height: 100px;
      }
      #top ul li h1{
        font-family: 'Pacifico', cursive;
      }
      #top ul li p{
        font-size: 14px;
        margin: 10px;
      }
      section{
      position:relative;
      margin:auto;
      width:1000px;
      height:453px;
      }
      aside#izq{
        position: absolute;
        left: 0;
        top:0;
        width: 200px;
        height: 453px;
      }
      aside#izq ul li{
        background:#aaa;
        padding:10px;
        margin:2px 10px;
        list-style:square;
        list-style-position:inside;
      }
      article{
        position: absolute;
        left: 200px;
        top:0;
        width: 600px;
        height: 453px;
      }
      article h1{
        font-family: 'Pacifico', cursive;
        font-size: 40px;
        margin:20px;
      }
      article p{
        margin: 5px 20px;
        font-size: 14px;
        text-align: justify;
      }
      article p img{
        float: left;
        margin-right: 20px;
      }
      aside#der{
        position: absolute;
        right: 0;
        top:0;
        width: 200px;
        height: 453px;
        background: #333;
      }
      footer{
        position:relative;
        margin:20px auto;
        width:1000px;
        height:70px;
        text-align: center;
        line-height: 70px;
        color: white;
        background: rgba(100,0,255,1);
      }
      }
   </style>
   <body>
      <!--Inicia el cabezote-->
      <header>
         <div id="logo">Logotipo</div>

         <div id="icono1" class="redes">X</div>
         <div id="icono2" class="redes">X</div>
         <div id="icono3" class="redes">X</div>
      </header>
      <!-- Cierra Cabezote -->
      <!-- Inicia Barra de Navegación -->
      <nav>
         <ul>
            <li class="botones">Boton 1</li>
            <li class="botones">Boton 2</li>
            <li class="botones">Boton 3</li>
            <li class="botones">Boton 4</li>
            <li class="botones">Boton 5</li>
         </ul>
      </nav>
      <!-- Cierra Barra de Navegación -->
      <!--  Inicia parte Superior -->
      <div id="top">
         <ul>
            <li>
              <img src="img/1.jpg" height="100px" width="100px">
              <h1>Algo</h1>
              <p>lklcsajls lkcslajsclj</p>
            </li>
            <li>
              <img src="img/2.jpg" height="100px" width="100px">
              <h1>Algo</h1>
              <p>lklcsajls lkcslajsclj</p>
            </li>
            <li>
              <img src="img/3.jpg" height="100px" width="100px">
              <h1>Algo</h1>
              <p>lklcsajls lkcslajsclj</p>
            </li>
         </ul>
      </div>
      <!-- Cierra parte Superior -->
      <!-- Inicia Seccion -->
      <section>
         <aside id="izq">
           <ul>
          <li>Link 1</li>
          <li>Link 2</li>
          <li>Link 3</li>
          <li>Link 4</li>
           </ul>
         </aside>
         <article>
           <h1>Fierro pariente</h1>
           <p><img src="img/1.jpg" height="100px" width="100px">There’s no more horrific sound than the screams of a mother who has just lost her child. Those were the sounds that awoke me in the middle of the night when the neighbor's boy passed away during the night. Officially he died from an undiagnosed, hereditary heart condition, but the rumors told another story entirely.
           </p>
           <br>
           <p>Mary had always been a big part of our community, arranging barbecues and birthday parties, getting along with each and everyone in the neighborhood. All while being a working, single mother. Her son, Ulrich, was the most lively boy, outgoing and smart. We all expected big things from him as he grew up, and he loved the attention.
           </p>
         </article>
         <aside id="der"></aside>
      </section>
      <!-- Cierre Sección -- >
         <!-- Inicia pie de pagina -->
      <footer>
        &copy; Todos los derechos reservados.
        <!--http://www.ascii.cl/htmlcodes.htm-->
      </footer>
      <!-- Cierra pie de pagina -->
   </body>
</html>

```
# Estilos de formulario
```html
<!doctype>
<html>
   <head>
      <meta charset="utf-8">
      <title>Propiedades de ubicacion</title>
      <link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Pacifico&display=swap" rel="stylesheet">

<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Source+Code+Pro:wght@200&display=swap" rel="stylesheet">
   </head>
   <style>
      *{
      margin:0;
      padding:0;
      list-style:none;
      font-family: 'Source Code Pro', monospace;
      }
      header{
      position:relative;
      margin:20px auto;
      width:1000px;
      height:120px;
      }
      #logo{
        position:absolute;
        top:30px;
        left:30px;
        width:200px;
        height:60px;
        font-family: 'Pacifico', cursive;
        font-size: 50px;
        text-align: center;
        line-height: 60px;
      }
      .redes{
        position: absolute;
        width: 42px;
        height: 42px;
        background: #ccc;
        border-radius: 100%;
        text-align: center;
        line-height: 42px;
        color: white;
      }
      #icono1{
        top:42px;
        right: 120px;
        background: blue;
      }
      #icono2{
        top:42px;
        right: 74px;
        background: green;
      }
      #icono3{
        top:42px;
        right: 19px;
        background: red;
      }
      nav{
      position:relative;
      margin:auto;
      width:1000px;
      height:48px;
      background:#aaa;
      }
      .botones{
        float:left;
        width: 196px;
        height: 48px;
        background: rgba(100,0,255,1);
        margin: 0px 2px;
        font-family: 'Pacifico', cursive;
        color: white;
        text-align: center;
        line-height: 48px;
      }
      #top{
        position:relative;
        margin:20px auto;
        width:1000px;
        height:192px;
      }
      #top ul{
        width: 1010px;
        height: 192px;
      }
      #top ul li{
        float:left;
        width: 326px;
        height: 192px;
        margin-right: 10px;
        text-align: center;
      }
      #top ul li img{
        border-radius: 100%;
        height: 100px;
      }
      #top ul li h1{
        font-family: 'Pacifico', cursive;
      }
      #top ul li p{
        font-size: 14px;
        margin: 10px;
      }
      section{
      position:relative;
      margin:auto;
      width:1000px;
      height:453px;
      }
      aside#izq{
        position: absolute;
        left: 0;
        top:0;
        width: 200px;
        height: 453px;
      }
      aside#izq ul li{
        background:#aaa;
        padding:10px;
        margin:2px 10px;
        list-style:square;
        list-style-position:inside;
      }
      article{
        position: absolute;
        left: 200px;
        top:0;
        width: 600px;
        height: 453px;
      }
      article h1{
        font-family: 'Pacifico', cursive;
        font-size: 40px;
        margin:20px;
      }
      article p{
        margin: 5px 20px;
        font-size: 14px;
        text-align: justify;
      }
      article p img{
        float: left;
        margin-right: 20px;
      }
      aside#der{
        position: absolute;
        right: 0;
        top:0;
        width: 200px;
        height: 453px;
      }
      aside#der h1{
        width:200px;
        height:50px;
        line-height:50px;
        text-align:center;
        background: rgba(100,0,255,1);
        color:white;
        margin-bottom:5px;
      }
      aside#der input{
        padding:10px;
        margin:5px 0;
        width:176px;
      }
      aside#der input[type="text"]{
        background:url(img/usuario.jpg);
        background-repeat:no-repeat;
        background-position:right;
        background-size:contain;
      }
      aside#der input[type="password"]{
        background:url(img/password.png);
        background-repeat:no-repeat;
        background-position:right;
        background-size:contain;
      }
      footer{
        position:relative;
        margin:20px auto;
        width:1000px;
        height:70px;
        text-align: center;
        line-height: 70px;
        color: white;
        background: rgba(100,0,255,1);
      }
      }
   </style>
   <body>
      <!--Inicia el cabezote-->
      <header>
         <div id="logo">Logotipo</div>

         <div id="icono1" class="redes">X</div>
         <div id="icono2" class="redes">X</div>
         <div id="icono3" class="redes">X</div>
      </header>
      <!-- Cierra Cabezote -->
      <!-- Inicia Barra de Navegación -->
      <nav>
         <ul>
            <li class="botones">Boton 1</li>
            <li class="botones">Boton 2</li>
            <li class="botones">Boton 3</li>
            <li class="botones">Boton 4</li>
            <li class="botones">Boton 5</li>
         </ul>
      </nav>
      <!-- Cierra Barra de Navegación -->
      <!--  Inicia parte Superior -->
      <div id="top">
         <ul>
            <li>
              <img src="img/1.jpg" height="100px" width="100px">
              <h1>Algo</h1>
              <p>lklcsajls lkcslajsclj</p>
            </li>
            <li>
              <img src="img/2.jpg" height="100px" width="100px">
              <h1>Algo</h1>
              <p>lklcsajls lkcslajsclj</p>
            </li>
            <li>
              <img src="img/3.jpg" height="100px" width="100px">
              <h1>Algo</h1>
              <p>lklcsajls lkcslajsclj</p>
            </li>
         </ul>
      </div>
      <!-- Cierra parte Superior -->
      <!-- Inicia Seccion -->
      <section>
         <aside id="izq">
           <ul>
          <li>Link 1</li>
          <li>Link 2</li>
          <li>Link 3</li>
          <li>Link 4</li>
           </ul>
         </aside>
         <article>
           <h1>Fierro pariente</h1>
           <p><img src="img/1.jpg" height="100px" width="100px">There’s no more horrific sound than the screams of a mother who has just lost her child. Those were the sounds that awoke me in the middle of the night when the neighbor's boy passed away during the night. Officially he died from an undiagnosed, hereditary heart condition, but the rumors told another story entirely.
           </p>
           <br>
           <p>Mary had always been a big part of our community, arranging barbecues and birthday parties, getting along with each and everyone in the neighborhood. All while being a working, single mother. Her son, Ulrich, was the most lively boy, outgoing and smart. We all expected big things from him as he grew up, and he loved the attention.
           </p>
         </article>
         <aside id="der">
           <h1>Ingreso</h1>

           <form>
             <input type="text" placeholder="Nombre">

             <input type="password" placeholder="Contraseña">

             <input type="submit" value="Enviar">
           </form>
         </aside>
      </section>
      <!-- Cierre Sección -- >
         <!-- Inicia pie de pagina -->
      <footer>
        &copy; Todos los derechos reservados.
        <!--http://www.ascii.cl/htmlcodes.htm-->
      </footer>
      <!-- Cierra pie de pagina -->
   </body>
</html>
```
# Propiedades de Enlace

````html
<!doctype>
<html>
   <head>
      <meta charset="utf-8">
      <title>Propiedades de ubicacion</title>
      <link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Pacifico&display=swap" rel="stylesheet">

<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Source+Code+Pro:wght@200&display=swap" rel="stylesheet">
  <link href="estilo.css" type="text/css" rel="stylesheet" media="">
   </head>

   <body>
     <div id="chat">Chat</div>
      <!--Inicia el cabezote-->
      <header>
         <div id="logo">Logotipo</div>

         <div id="icono1" class="redes">X</div>
         <div id="icono2" class="redes">X</div>
         <div id="icono3" class="redes">X</div>
      </header>
      <!-- Cierra Cabezote -->
      <!-- Inicia Barra de Navegación -->
      <nav>
         <ul>
            <a href="#"><li class="botones">Boton 1</li></a>
            <a href="#"><li class="botones">Boton 2</li></a>
            <a href="#"><li class="botones">Boton 3</li></a>
            <a href="#"><li class="botones">Boton 4</li></a>
            <a href="#"><li class="botones">Boton 5</li></a>
         </ul>
      </nav>
      <!-- Cierra Barra de Navegación -->
      <!--  Inicia parte Superior -->
      <div id="top">
         <ul>
            <li>
              <img src="img/1.jpg" height="100px" width="100px">
              <h1>Algo</h1>
              <p>lklcsajls lkcslajsclj</p>
            </li>
            <li>
              <img src="img/2.jpg" height="100px" width="100px">
              <h1>Algo</h1>
              <p>lklcsajls lkcslajsclj</p>
            </li>
            <li>
              <img src="img/3.jpg" height="100px" width="100px">
              <h1>Algo</h1>
              <p>lklcsajls lkcslajsclj</p>
            </li>
         </ul>
      </div>
      <!-- Cierra parte Superior -->
      <!-- Inicia Seccion -->
      <section>
         <aside id="izq">
           <ul>
          <li><a href="#">Link 1</li></a>
          <li><a href="#">Link 2</li></a>
          <li><a href="#">Link 3</li></a>
          <li><a href="#">Link 4</li></a>
           </ul>
         </aside>
         <article>
           <h1>Fierro pariente</h1>
           <p><img src="img/1.jpg" height="100px" width="100px">There’s no more horrific sound than the screams of a mother who has just lost her child. Those were the sounds that awoke me in the middle of the night when the neighbor's boy passed away during the night. Officially he died from an undiagnosed, hereditary heart condition, but the rumors told another story entirely.
           </p>
           <br>
           <p>Mary had always been a big part of our community, arranging barbecues and birthday parties, getting along with each and everyone in the neighborhood. All while being a working, single mother. Her son, Ulrich, was the most lively boy, outgoing and smart. We all expected big things from him as he grew up, and he loved the attention.
           </p>
         </article>
         <aside id="der">
           <h1>Ingreso</h1>

           <form>
             <input type="text" placeholder="Nombre">

             <input type="password" placeholder="Contraseña">

             <input type="submit" value="Enviar">
           </form>
         </aside>
      </section>
      <!-- Cierre Sección -- >
         <!-- Inicia pie de pagina -->
      <footer>
        &copy; Todos los derechos reservados.
        <!--http://www.ascii.cl/htmlcodes.htm-->
      </footer>
      <!-- Cierra pie de pagina -->
   </body>
</html>
```
## CSS del codigo anterior
```css
*{
     margin:0;
     padding:0;
     list-style:none;
     font-family: 'Source Code Pro', monospace;
}
 #chat{
     position:fixed;
     width:250px;
     height:40px;
     background: magenta;
     bottom:0;
     right:20px;
     z-index:1;
     color:white;
     text-align:center;
     line-height:40px;
     font-family: 'Source Code Pro', monospace;
     font-size:20px;
     border-radius:20px 20px 0 0;
     cursor:pointer;
}
 header{
     position:relative;
     margin:20px auto;
     width:1000px;
     height:120px;
}
 #logo{
     position:absolute;
     top:30px;
     left:30px;
     width:200px;
     height:60px;
     font-family: 'Pacifico', cursive;
     font-size: 50px;
     text-align: center;
     line-height: 60px;
}
 .redes{
     position: absolute;
     width: 42px;
     height: 42px;
     background: #ccc;
     border-radius: 100%;
     text-align: center;
     line-height: 42px;
     color: white;
}
 #icono1{
     top:42px;
     right: 120px;
     background: blue;
}
 #icono2{
     top:42px;
     right: 74px;
     background: green;
}
 #icono3{
     top:42px;
     right: 19px;
     background: red;
}
 nav{
     position:relative;
     margin:auto;
     width:1000px;
     height:48px;
     background:#aaa;
}
 .botones{
     float:left;
     width: 196px;
     height: 48px;
     background: rgba(100,0,255,1);
     margin: 0px 2px;
     font-family: 'Pacifico', cursive;
     color: white;
     text-align: center;
     line-height: 48px;
}
 a .botones:hover{
     background:rgba(100,0,255,.4);
}
 a .botones:active{
     background:rgba(255,0,100,1);
}
 #top{
     position:relative;
     margin:20px auto;
     width:1000px;
     height:192px;
}
 #top ul{
     width: 1010px;
     height: 192px;
}
 #top ul li{
     float:left;
     width: 326px;
     height: 192px;
     margin-right: 10px;
     text-align: center;
}
 #top ul li img{
     border-radius: 100%;
     height: 100px;
}
 #top ul li h1{
     font-family: 'Pacifico', cursive;
}
 #top ul li p{
     font-size: 14px;
     margin: 10px;
}
 section{
     position:relative;
     margin:auto;
     width:1000px;
     height:453px;
}
 aside#izq{
     position: absolute;
     left: 0;
     top:0;
     width: 200px;
     height: 453px;
}
 aside#izq ul li{
     background:#aaa;
     padding:10px;
     margin:2px 10px;
     list-style:square;
     list-style-position:inside;
}
 aside#izq ul li a{
     text-decoration:none;
}
 article{
     position: absolute;
     left: 200px;
     top:0;
     width: 600px;
     height: 453px;
}
 article h1{
     font-family: 'Pacifico', cursive;
     font-size: 40px;
     margin:20px;
}
 article p{
     margin: 5px 20px;
     font-size: 14px;
     text-align: justify;
}
 article p img{
     float: left;
     margin-right: 20px;
}
 aside#der{
     position: absolute;
     right: 0;
     top:0;
     width: 200px;
     height: 453px;
}
 aside#der h1{
     width:200px;
     height:50px;
     line-height:50px;
     text-align:center;
     background: rgba(100,0,255,1);
     color:white;
     margin-bottom:5px;
}
 aside#der input{
     padding:10px;
     margin:5px 0;
     width:176px;
}
 aside#der input[type="text"]{
     background:url(img/usuario.jpg);
     background-repeat:no-repeat;
     background-position:right;
     background-size:contain;
}
 aside#der input[type="password"]{
     background:url(img/password.png);
     background-repeat:no-repeat;
     background-position:right;
     background-size:contain;
}
 footer{
     position:relative;
     margin:20px auto;
     width:1000px;
     height:70px;
     text-align: center;
     line-height: 70px;
     color: white;
     background: rgba(100,0,255,1);
}
	}
```
La vista de una pagina web varia con el dispositivo y sera menor en un telefono movil que en una pantalla de computadora.

Antes de las tabletas y telefonos moviles, las paginas web estaban diseñadas solo para pantallas de ordenador, y era comun que las paginas web tuvieran un diseño estatico y un tamañp fijo. Luego, cuando comenzamos a navegar por internet usando tabletas y telefonos moviles, las paginas web de tamaño fijo eran demasiado grandes para adaptarse a la ventana grafica.

Para solucionar esto, los navegadores de esos dispositivos redujeron la pagina web entera para ajustarla a la pantalla.  

# Etiqueta Meta Viewport

```html
<!DOCTYPE html>
<html lang="en">
<head>
	<meta charset="UTF-8">
	<meta name="viewport" content="width=device-width, initial-scale=1.0">

	<!-- el viewport(ventanza de visualizacion) el area visible del usuario de una pagina web. -->

	<!-- width=devide-width establece el ancho de la pagina para seguir el ancho de pantalla del dispositivo (que variara en funcion del dispositivo) -->

	<!-- initial-scale=1.0 fija el nivel del zoom inicial cuando la pagina se carga por primera vez por el navegador. -->

	<title>Document</title>
</head>
<body>

</body>
</html>
```
# Sistema de Filas y columnas

```html
<!DOCTYPE html>
<html>
<head>
	<meta charset="UTF-8">
	<meta name="viewport" content="width=device-width, initial-scale=1.0">
	<title>Document</title>
	<link rel="stylesheet" type="text/css" href="css/columnas.css">
</head>
<body>
	<div class="contenedor">

		<div class="fila">

			<div class="col-12">100%</div>

		</div>

		<div class="fila">

			<div class="col-6">50%</div>
			<div class="col-6">50%</div>

		</div>

		<div class="fila">

			<div class="col-4">33.33333333%</div>
			<div class="col-4">33.33333333%</div>
			<div class="col-4">33.33333333%</div>

		</div>

		<div class="fila">

			<div class="col-3">25%</div>
			<div class="col-3">25%</div>
			<div class="col-3">25%</div>
			<div class="col-3">25%</div>

		</div>

		<div class="fila">

			<div class="col-3">25%</div>
			<div class="col-9">75%</div>

		</div>

		<div class="fila">

			<div class="col-7">58.33%</div>
			<div class="col-5">41.67%</div>

		</div>

		<div class="fila">

			<div class="col-8">66.67%</div>
			<div class="col-2">16.66%</div>
			<div class="col-1">8.33%</div>
			<div class="col-1">8.33%</div>
		</div>

		<div class="fila">

			<div class="col-3">25%</div>
			<div class="col-3">25%</div>
			<div class="col-3">25%</div>

		</div>

		<div class="fila" style="background: red">

			<div class="col-3">25%</div>
			<div class="col-3">25%</div>
			<div class="col-3">25%</div>

		</div>

		<h1>Hello</h1>
	</div>
</body>
</html>
```
# CSS de Sistema de Filas y columnas
```css

*{
	margin: 0px;
	padding: 0px;
	list-style: none;
	text-decoration: none;
	font-family: sans-serif;
	box-sizing: border-box;/*Esto asegura que el relleno y el borde estan incluidos en el ancho total y la altura de las cajas html.*/
}

.contenedor{
	position: relative;
	margin: auto;
	width: 100%;
	height: auto;
}

.fila{
	position: relative;
	margin: auto;
	width: 100%;
	height: auto;
	/*Las columnas dentro de una fila estan flotando a la izquierda, y por lo tanto se toman fuera del flujo de la pagina , y otros elementos seran colocados en como si no fueran de las columnas. Para evitar esto, vamos añadir un estilo que despeja el flujo.*/
	clear: both;
	display: table;
}

[class*="col-"]{
	float: left;
	border: 1px solid black;
	padding: 20px;
}

.col-12{
	width: 100%;
	background: red;
}

.col-11{
	width: 91.66666666%;
	background: purple;
}

.col-10{
	width: 83.33333333%;
	background: red;
}

.col-9{
	width: 75%;
	background: hotpink;
}

.col-8{
	width: 66.66666667%;
	background: skyblue;
}

.col-7{
	width: 58.33333333%;
	background: skyblue;
}

.col-6{
	width: 50%;
	background: skyblue;
}

.col-5{
	width: 41.66666667%;
	background: skyblue;
}

.col-4{
	width: 33.33333333%;
	background: greenyellow;
}

.col-3{
	width: 25%;
	background: darkred;
}

.col-2{
	width: 16.66666666%;
	background: darkred;
}

.col-1{
	width: 8.33333333%;
	background: darkred;
}
```
# Media Query CSS (Consulta de Medios)

Consulta de medios es una tecnica CSS introducida en CSS3.

Utliza la regla @media para incluir un bloque de propiedades de CSS solo si una determinada condicion es verdadera.  

Una cosa que es muy util en Sublime Text es que puedo escribir la misma palabra en varios renglones al mismo tiempo con oprimir la tecla Ctrl en las partes donde quiera.  

Y si quiero cambiar esas palabras, debo de seleccionar una y luego oprimir Ctrl + D para que se vayan seleccionando las mismas palabras que le siguen.
