# LM
## Estructura minima de una web
```html
<html>
	<head>
		<title></title>
	</head>
	<body>
	
	</body>
</html>
```

## Explica las 3 formas de usar CSS en HTML
### Podemos utilizar el css detro del head con la siguiente etiqueta
```html
	<head>type="text/css"</head> 	
```
  ### En una pagina aparte
```html

<head>	
    <style type="text/css">
    </style>
</head>
```
### Dentro del html
```html

Con la etiqueta 
	<style></style>
```

## Crea una lista sin onrdenar con 5 ingredientes de una receta de cocina
```html
	<html>
	<head>
		<title></title>
	</head>
	<body>
		<ul>
		<li>Carne</li>
		<li>Sal</li>
		<li>Patatas</li>
		<li>Aceite</li>
		<li>Champiñones</li>
		</ul>	
	</body>
	</html>	
```
## Como se puede incluir javascript en html
### Añadiendo la etiqueta en el head
```html
<script></script>
```
### O creando un archivo externo con
```html
<script src="js/myscript.js"></script>
```
## Que diferencia hay entre una clase y una ID
Con el id solo podemos identificar un elemento, es decir, no podemos repetir el mismo id para varios elementos. Por el contrario, las clases si que se pueden asignar a varios elementos para que compartan una serie de características.

## Codigo para hacer un enlace a otra página y que esta se abra en una nueva ventana.
```html
<html>
	<head>
	</head>
	<body>
		<a href="https://www.youtube.com/">Youtube</a>
	</body>
</html>
```
## ¿Qué son las pseudoclases? Pon ejemplos.
Se usan para especificar un estado especial del elemento.
Esta es la sintaxis (w3schools)

selector:pseudo-class {
    property:value;

Estos son algunos ejemplos

p:first-child i{ para seleccionar todos los parrafos que sean el primer hijo

q:lang(no) { para hacer cambios segun la lengua que este utilizandose

a:hover{ hace que los elementos del tipo a respondan cuando el raton esté encima

:not(p){ afecta a todos los que no sean el elemento mencionado, en este caso p

## Explica el modelo de caja de CSS (margin, border y padding).
### Margin:
### Padding:
### Border:
## Explica que son los selectores de CSS y pon ejemplos
Utilizamos los selectores para asignar un conjunto de propiedades a los elementos indicados.
Algunos ejemplos son:

* Selector universal

. Selector de clase

p selector de parrafo

[attribute] selector de atributos




## Di a quien afectan:
### p a { color: red;
a todos los elementos a dentro de un elemento p
### p > a { color: red; }
a todos los a cuyo padre sea un p

### h1 + h2 { color: red }
a todos los h2 que esten al lado de un h1
### a[class] { color: blue; }
a todos los links que tengan asignada una classe

### a[class="externo"] { color: blue; }
a todos los links que tengan asignada una clase llamada externo
### a[href="http://www.ejemplo.com"] { color: blue; }
a todos los links que apunten a esa pagina.

 



