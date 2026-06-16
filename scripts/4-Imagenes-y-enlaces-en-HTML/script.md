# Script Video 4: Imágenes y enlaces en HTML

**Duración estimada**: 7 minutos 15 segundos

---

## Introducción (0:00 – 0:25)

En esta lección vamos a aprender cómo agregar imágenes y enlaces en una página web usando HTML.

En la lección anterior vimos elementos comunes como títulos, párrafos y listas. Ahora vamos a mejorar nuestra página agregando contenido visual y enlaces hacia otras páginas.

Para eso usaremos dos etiquetas muy importantes: `img` y `a`.

---

## ¿Para qué sirven las imágenes? (0:25 – 1:20)

Las imágenes ayudan a que una página web sea más visual, atractiva y fácil de entender.

Una página que solo tiene texto puede verse simple o poco llamativa.

En cambio, cuando agregamos imágenes, el contenido se vuelve más claro para el usuario.

Por ejemplo, si una página habla sobre deportes, viajes o comida, una imagen puede ayudar a representar mejor el tema.

---

## Etiqueta img (1:20 – 2:20)

Para insertar una imagen en HTML usamos la etiqueta `img`.

Esta etiqueta sirve para mostrar imágenes dentro de una página web.

La estructura básica es:

```html
<img src="imagen.jpg" alt="Descripción de la imagen">
```

La etiqueta `img` tiene dos atributos importantes.

El atributo `src` indica la ruta o dirección de la imagen.

El atributo `alt` describe la imagen. Este texto aparece si la imagen no carga y también ayuda a la accesibilidad.

Un detalle importante es que la etiqueta `img` no necesita etiqueta de cierre.

---

## ¿Para qué sirven los enlaces? (2:20 – 3:10)

Los enlaces permiten conectar una página con otra.

Gracias a los enlaces, el usuario puede navegar entre diferentes sitios web, páginas internas o recursos externos.

Por ejemplo, podemos crear un enlace que lleve a una página con más información sobre un deporte, una noticia o una imagen.

En HTML, los enlaces se crean usando la etiqueta `a`.

---

## Etiqueta a (3:10 – 4:10)

La etiqueta `a` sirve para crear enlaces.

Su estructura básica es:

```html
<a href="https://www.ejemplo.com">Visitar página</a>
```

El atributo `href` indica la dirección a la que llevará el enlace.

El texto que va entre la etiqueta de apertura y cierre es el texto visible que verá el usuario.

También podemos usar el atributo `target="_blank"` para abrir el enlace en una nueva pestaña:

```html
<a href="https://www.ejemplo.com" target="_blank">Visitar página</a>
```

Esto es útil cuando queremos que el usuario abra otro sitio sin cerrar la página actual.

---

## Desarrollo práctico en CodePen (4:10 – 6:30)

Ahora pasamos a CodePen para aplicar lo aprendido.

Primero conservamos la estructura que venimos trabajando sobre nuestro deporte favorito.

Podemos tener un título principal:

```html
<h1>Mi deporte favorito</h1>
```

Luego agregamos un párrafo explicando el tema:

```html
<p>El fútbol es un deporte muy popular porque permite compartir momentos, desarrollar habilidades y trabajar en equipo.</p>
```

Después agregamos una imagen usando la etiqueta `img`:

```html
<img src="https://ejemplo.com/imagen-futbol.jpg" alt="Imagen relacionada con fútbol">
```

Aquí el atributo `src` contiene la dirección de la imagen.

El atributo `alt` describe lo que representa la imagen.

Luego podemos agregar un subtítulo para colocar más información:

```html
<h2>Más información</h2>
```

Debajo creamos un enlace usando la etiqueta `a`:

```html
<a href="https://www.ejemplo.com" target="_blank">Visitar página</a>
```

Este enlace permitirá que el usuario abra una página externa para consultar más información.

Si usamos `target="_blank"`, el enlace se abrirá en una nueva pestaña.

---

## Resultado en la página (6:30 – 6:55)

Al ejecutar el código, podemos ver que la página ahora tiene un título, un párrafo, una imagen y un enlace.

La imagen hace que la página se vea más visual.

El enlace permite que el usuario pueda ir a otra página para encontrar más información.

Con esto, nuestra página deja de ser solo texto y empieza a parecerse más a una página web real.

---

## Cierre (6:55 – 7:15)

En esta lección aprendimos a usar la etiqueta `img` para insertar imágenes y la etiqueta `a` para crear enlaces.

También vimos atributos importantes como `src`, `alt`, `href` y `target`.

Las imágenes ayudan a mejorar la presentación visual de una página, mientras que los enlaces permiten navegar hacia otros recursos.

Con estas etiquetas podemos crear páginas más completas, visuales e interactivas usando HTML.
