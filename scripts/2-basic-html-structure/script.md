# Script Video 2: Estructura HTML basica

En esta leccion vamos a crear nuestra primera estructura usando HTML.

Antes de pasar al codigo, recordemos que una pagina web tiene una estructura. En una pagina real podemos encontrar partes como una cabecera, un cuerpo principal y una parte final.

HTML nos ayuda a ordenar todo ese contenido para que el navegador sepa que debe mostrar.

En una estructura HTML completa normalmente encontramos `DOCTYPE`, `html`, `head` y `body`.

`DOCTYPE html` le indica al navegador que estamos usando HTML moderno.

La etiqueta `html` representa toda la pagina.

Dentro de `html` tenemos `head` y `body`.

El `head` guarda informacion de la pagina, como el titulo que aparece en la pestana del navegador.

El `body` contiene todo lo que el usuario puede ver en la pagina, como titulos, textos, imagenes, enlaces y listas.

En CodePen no necesitamos escribir toda esa estructura completa, porque CodePen ya la prepara por nosotros. Por eso, en el panel de HTML vamos a escribir principalmente lo que iria dentro del `body`, es decir, el contenido visible de la pagina.

Primero vamos a crear un titulo principal usando la etiqueta `h1`.

La etiqueta `h1` se usa para representar el titulo mas importante de la pagina.

Escribimos:

```html
<h1>TITULO PRINCIPAL</h1>
```

Al ver el resultado, el navegador muestra ese texto como un titulo grande.

Ahora agregamos un parrafo usando la etiqueta `p`.

La etiqueta `p` sirve para escribir bloques de texto.

Escribimos:

```html
<p>En esta zona de la pagina va un parrafo.</p>
```

Aqui podemos ver que el texto aparece debajo del titulo.

Luego agregamos otro parrafo.

```html
<p>
  En esta otra parte vamos a escribir otro parrafo.
  <br />
  Solo que ahora usaremos un salto de linea.
</p>
```

Dentro de este parrafo usamos la etiqueta `br`.

La etiqueta `br` sirve para hacer un salto de linea. Es decir, permite que el texto continue en la siguiente linea.

Luego usamos la etiqueta `hr`.

```html
<hr />
```

La etiqueta `hr` crea una linea horizontal que sirve para separar secciones dentro de la pagina.

Ahora vamos a crear una seccion de listas.

Primero usamos un subtitulo con `h2`.

```html
<h2>LISTAS SIN ORDEN</h2>
```

La etiqueta `h2` sirve para crear un subtitulo o una seccion importante dentro de la pagina.

Debajo agregamos un parrafo explicando que una lista sin orden no tiene secuencia numerica.

```html
<p>Una lista sin orden no tiene secuencia numerica.</p>
```

Ahora creamos la lista usando `ul`.

```html
<ul>
  <li>item 1</li>
  <li>item 2</li>
  <li>item 3</li>
</ul>
```

La etiqueta `ul` sirve para crear una lista sin orden.

Cada elemento de la lista se escribe usando la etiqueta `li`.

Por eso, cada `li` representa un item dentro de la lista.

En el resultado podemos ver que el navegador muestra la lista con puntos.

Despues agregamos otra linea separadora con `hr`.

```html
<hr />
```

Ahora vamos a crear una lista ordenada.

Primero colocamos un subtitulo usando `h3`.

```html
<h3>LISTA ORDENADA</h3>
```

La etiqueta `h3` tambien sirve para crear un subtitulo, pero con menor importancia visual que `h2`.

Luego agregamos un parrafo.

```html
<p>Una lista ordenada es una lista con secuencia numerica.</p>
```

Ahora creamos la lista ordenada usando `ol`.

```html
<ol>
  <li>primer item</li>
  <li>segundo item</li>
  <li>tercer item</li>
</ol>
```

La etiqueta `ol` sirve para crear una lista ordenada.

Igual que antes, cada elemento se escribe con `li`.

La diferencia es que `ol` muestra los elementos con numeros.

Entonces, si usamos `ul`, la lista aparece con puntos.

Pero si usamos `ol`, la lista aparece con numeros.

En resumen, en esta leccion usamos varias etiquetas basicas de HTML.

Usamos `h1` para el titulo principal.

Usamos `p` para crear parrafos.

Usamos `br` para hacer un salto de linea.

Usamos `hr` para separar secciones.

Usamos `h2` y `h3` para crear subtitulos.

Usamos `ul` para una lista sin orden.

Usamos `ol` para una lista ordenada.

Y usamos `li` para cada elemento dentro de una lista.

Con estas etiquetas ya podemos crear una pagina sencilla y ordenada usando solo HTML.

En las siguientes lecciones se pueden agregar mas elementos, como imagenes, enlaces y estilos con CSS.
