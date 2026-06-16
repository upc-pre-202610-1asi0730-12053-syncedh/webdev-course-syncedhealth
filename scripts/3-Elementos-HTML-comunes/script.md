# Script Video 3: Elementos HTML comunes

**Duración estimada**: 5 minutos 40 segundos

---

## Introducción (0:00 – 0:25)

En esta lección vamos a conocer algunos elementos comunes de HTML.

Estos elementos nos ayudan a organizar el contenido visible de una página web, como títulos, subtítulos, párrafos, saltos de línea y listas.

Para esta práctica usaremos CodePen, porque nos permite escribir HTML y ver el resultado directamente en el navegador.

---

## Presentación de CodePen (0:25 – 0:55)

Primero ingresamos a CodePen.

CodePen es una herramienta en línea que nos permite escribir código HTML, CSS y JavaScript sin instalar nada.

En esta lección nos enfocaremos en el panel de HTML.

Todo lo que escribamos en esta sección aparecerá como contenido visible en la parte de resultado.

---

## Encabezados en HTML (0:55 – 1:40)

Comenzaremos usando etiquetas de encabezado.

Los encabezados sirven para crear títulos y subtítulos dentro de una página web.

La etiqueta `h1` representa el título principal de la página.

Por ejemplo:

```html
<h1>Mi deporte favorito</h1>
```

En este caso, el navegador muestra el texto como un título grande.

También existen otros encabezados como `h2` y `h3`.

La etiqueta `h2` se usa para subtítulos o secciones importantes.

La etiqueta `h3` se usa para subsecciones con menor importancia visual.

Por ejemplo:

```html
<h2>¿Por qué me gusta?</h2>
<h3>Pasos para practicarlo</h3>
```

---

## Párrafos en HTML (1:40 – 2:30)

Después del título principal, agregamos un párrafo usando la etiqueta `p`.

La etiqueta `p` sirve para escribir bloques de texto dentro de la página.

Por ejemplo:

```html
<p>El fútbol es un deporte muy popular porque permite compartir momentos, desarrollar habilidades, velocidad y coordinación.</p>
```

Al colocar este código, el navegador muestra el texto debajo del título principal.

Los párrafos nos permiten explicar ideas o agregar información relacionada con el tema de la página.

---

## Saltos de línea (2:30 – 3:00)

Dentro de un párrafo también podemos usar saltos de línea.

Para eso usamos la etiqueta `br`.

La etiqueta `br` sirve para continuar el texto en la siguiente línea sin crear un nuevo párrafo completo.

Por ejemplo:

```html
<p>
  El fútbol es un deporte muy popular.
  <br>
  También ayuda a mejorar la coordinación.
</p>
```

Con esto, el texto se separa en dos líneas dentro del mismo bloque.

---

## Listas sin orden (3:00 – 4:05)

Ahora vamos a crear una lista sin orden.

Una lista sin orden se usa cuando los elementos no necesitan seguir una secuencia numérica.

Primero colocamos un subtítulo con `h2`:

```html
<h2>¿Por qué me gusta?</h2>
```

Luego creamos la lista usando la etiqueta `ul`.

Dentro de `ul`, cada elemento se escribe con la etiqueta `li`.

Por ejemplo:

```html
<ul>
  <li>Es muy entretenido</li>
  <li>Ayuda a trabajar en equipo</li>
  <li>Permite conocer amigos</li>
</ul>
```

La etiqueta `ul` crea una lista con viñetas.

La etiqueta `li` representa cada elemento de la lista.

En el resultado podemos ver que cada elemento aparece con un punto al inicio.

---

## Listas ordenadas (4:05 – 5:00)

También podemos crear listas ordenadas.

Una lista ordenada se usa cuando los elementos sí deben seguir un orden o una secuencia.

Primero colocamos un subtítulo con `h3`:

```html
<h3>Pasos para practicarlo</h3>
```

Luego usamos la etiqueta `ol` para crear la lista numerada:

```html
<ol>
  <li>Elegir un lugar amplio</li>
  <li>Reunir a compañeros</li>
  <li>Practicar constantemente</li>
</ol>
```

La etiqueta `ol` crea una lista ordenada.

Igual que antes, cada elemento se escribe usando `li`.

La diferencia es que `ol` muestra los elementos con números, mientras que `ul` los muestra con viñetas.

---

## Resumen final (5:00 – 5:40)

En esta lección aprendimos varios elementos comunes de HTML.

Usamos `h1` para crear el título principal.

Usamos `h2` y `h3` para crear subtítulos y secciones.

Usamos `p` para escribir párrafos.

Usamos `br` para crear saltos de línea.

Usamos `ul` para crear listas con viñetas.

Usamos `ol` para crear listas numeradas.

Y usamos `li` para escribir cada elemento dentro de una lista.

Con estas etiquetas ya podemos crear una página web sencilla, ordenada y con contenido estructurado.

En la siguiente lección veremos cómo agregar imágenes y enlaces en HTML.
