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
# CSS
