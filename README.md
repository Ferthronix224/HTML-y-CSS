# HTML

Las siglas de HTML son **H**yper **T**ext **M**arkup **L**anguage, en español Lenguaje marcado de hipertextos, es el lenguaje con el que se define el contenido de las páginas web. Básicamente se trata de un conjunto de etiquetas que sirven para definir el texto y otros elementos que compondrán una página web, como imágenes, listas, vídeos, etc.

Se puede trabajar el HTML con cualquier editor de codigo, desde el bloc de notas de Windows hasta programas profesionales como Adobe Dreamweaver.

El primer archivo de HTML siempre tiene que llamarse "index.html" porque es lo primero que detectan los navegadores.
## Estructura  
**doctype:** Se trata de una etiqueta simple que no necesita cierre y cuya función es facilitar información al servidor web que aloja página. La información facilitada por ésta etiqueta se refiere al tipo de documento, además es necesaria para la comunicación entre el navegador y el servidor.  
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

Las etiquetas dobles "img" son para insertar imágenes, con src (source) buscas el link o la ubicación de las imágenes para insertarlas, con width pones el ancho, con height el alto, alt permite proporcionar un texto equivalente al objeto y aligh la posicion.  
Las etiquetas dobles "ol" son para hacer una lista númerica.  
Las etiquetas dobles "li" son para insertar items en la lista.  
Las etiquetas dobles "ul" son para hacer una lista de puntos.  
Las etiquetas dobles "table" son para declarar una tabla después puedes ponerle borde con "border="1"" dentro de la misma etiqueta de inicio.  
Las etiquetas dobles "tr" son para declarar una fila.  
Las etiquetas dobles "th" son para poner el valor de una columna.  
Las etiquetas dobles "meter" son para poner una barra de progreso, en "value" pones el valor, en "min" pones el valor mínimo de los valores posibles, en "max" pones el valor máximo de esos valores, en "high" pones un valor donde pones un limite que por ejemplo si fueran calificaciones el valor limite para pasar es de 70 para arriba".  
Las etiquetas dobles "footer" son para poner el pie de página.  
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
# CSS
