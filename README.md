# HTML

Las siglas de HTML son **H**yper **T**ext **M**arkup **L**anguage, en español Lenguaje marcado de hipertextos, es el lenguaje con el que se define el contenido de las páginas web. Básicamente se trata de un conjunto de etiquetas que sirven para definir el texto y otros elementos que compondrán una página web, como imágenes, listas, vídeos, etc.

Se puede trabajar el HTML con cualquier editor de codigo, desde el bloc de notas de Windows hasta programas profesionales como Adobe Dreamweaver.

El primer archivo de HTML aiempre tiene que llamarse "index.html" porque es lo primero que detectan los navegadores.
## Estructura  
```html
<!doctype html>
<!--doctype: Se trata de una etiqueta simple que no necesita cierre y cuya función es facilitar información al servidor web que aloja página. La información facilitada por ésta etiqueta se refiere al tipo de documento, además es necesaria para la comunicación entre el navegador y el servidor.-->
<html>
<!--html: Se trata de una etiqueta par y es la etiqueta que encierra todo el documento HTML-->	

<head>
<!--head: Es una etiqueta par, define la cabecera del documento y contiene información del mismo (metadatos, scripts, estilos, ubicación de documentos de estilos, título de la pagina entre otros datos)-->	

</head>

<body>
<!--body: Es una etiqueta par y la conocemos como el cuerpo del sitio web. Todo lo que se escriba dentro de esta etiqueta será visible para los navegadores.-->	
	
</body>
</html>
```
## Cabecera  

```html
<!doctype html>
<html>
<head>
	<!-- meta: La función de meta viene siendo añadir información sobre la página-->
	<meta charset = "utf-8">
	<!-- charset: Viene siendo la configuración en la página para definir el idioma que se usará.-->
	<meta name = "Author" content = "Fernando Adolfo">
	<!-- name: Tiene varias propiedades diferentes que dependiendo de lo que esta adentro es lo que se estará definiendo. Y el name va acompañado de "content" que ahí es donde tenemos que poner el contenido de lo que se definió en el name. En este ejemplo en la etiqueta simple "meta name" estamos poniendo el autor y el nombre del autor.-->
	<meta name = "Description" content = "Esta es la forma correcta de hacer páginas web">
	<!-- Description: En la etiqueta simple "meta name" es la descripción que aparecerá en los navegadores.-->
	<meta name = "Keywords" content = "html, desarrollo web">
	<!-- Keywords: En la etiqueta simple "meta name" son las palabras clave que usan los navegadores para filtrar las paginas-->
	<title>Mi primera página web</title>
	<!-- La etiqueta doble "title" es donde escribimos el nombre de la página-->
	<link rel="icon" href="img/noun_html_2350456.png">
	<!-- La etiqueta simple "link" sirve para vincular hojas de estilo o vincular el icono que aparece al lado del titulo en la parte superior de la página. rel: Es para definir lo que se va a relacionar. Y href: Es para buscar los archivos a usarse en la carpeta.-->
</head>

<body>
</body>
</html>
```
<img src = "https://user-images.githubusercontent.com/67721157/123534321-ff0d9d00-d6e1-11eb-9158-a8a095139105.png" width = "600" height = "350" alt = "ejemplo" align = "center" />

En la imagen se ve un buen diseño para una página web.

## Cuerpo
```html
<!doctype html>
<html>
<head>
</head>

<body>
	<header>Cabezote</header>
	
	<nav>Barra de navegación</nav>
	
	<section>Sección principal</section>
	
	<aside>Columna</aside>
	
	<article>Artículo</article>
	
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

En la parte anterior la etiqueta doble "b" es para poner en negritas las letras.  
La etiqueta simple "br"es para hacer un salto de línea.  
La etiqueta simple "hr" es para poner un borde.

```html
<!doctype html>
<html>
<head>
<meta charset="utf-8">
<title>Mi primera página</title>
</head>

<body>
	<img src="img/imagen.jpg" width = "600" height = "350" align = "center">
<!--img es la etiqueta para insertar imágenes, con src (source) buscas el link o la ubicación de las imágenes para insertarlas, con width pones elancho, con height el alto y aligh la posicion-->	
	<ol>
		<li>Carro</li>
		<li>Barco</li>
		<li>Avion</li>
	</ol>
	<!--ol es la etiqueta doble con la que haces una lista númerica-->
	<!--li es la etiqueta doble con la que pones items en la lista-->
	<ul>
		<li>Carro</li>
		<li>Barco</li>
		<li>Avion</li>
	</ul>
	<!--ul es la etiqueta doble con la que haces una lista de puntos-->
	
	<table border="1">
		<tr>
			<th>Mes</th>
			<th>Ahorro</th> <!--th es la etiqueta doble donde pones el valor de una columna-->
		</tr> <!--tr es la etiqueta doble donde declaras una fila-->
		
		<tr>
			<th>Enero</th>
			<th>$100</th>
		</tr>
		
		<tr>
			<th>Febrero</th>
			<th>$200</th>
		</tr>
	</table> <!--table es la etiqueta doble con la que declaras una tabla despues puedes ponerle borde con "border="1" dentro de la misma etiqueta de inicio"-->
	
	<h1>Resultados del examen</h1>
	<p>Fernando: <meter value = "90" min = "0" max = "100" high = "70"></meter></p>
	<p>Adolfo: <meter value = "69" min = "0" max = "100" high = "70"></meter></p>
	<p>Uriel: <meter value = "40" min = "0" max = "100" high = "70"></meter></p>
	<p>Johan: <meter value = "85" min = "0" max = "100" high = "70"></meter></p><!--meter es la etiqueta doble para poner una barra de progreso, en "value" pones el valor, en "min" pones el valor mínimo de los valores posibles, en "max" pones el valor máximo de esos valores, en "high" pones un valor donde pones un limite que por ejemplo si fueran calificaciones el valor limite para pasar es de 70 para arriba-->
	
	<footer>Este es el pie de página</footer> <!--footer viene siendo el pie de página-->
</body>
</html>
```
# CSS
