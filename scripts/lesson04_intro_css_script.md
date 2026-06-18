# GUÍA DE VIDEO: LECCIÓN 4 (INTRODUCCIÓN A CSS)

---

## Introducción

Mira estas dos páginas.

Las dos tienen exactamente el mismo contenido HTML, los mismos títulos, los mismos párrafos y la misma información.

Sin embargo, una se ve mucho más atractiva y agradable de leer que la otra.

La diferencia entre ambas se llama CSS, y hoy vas a aprender a utilizarlo.

CSS significa *Cascading Style Sheets*, u hojas de estilo en cascada.

Si HTML es la estructura de una página web, CSS es la capa visual.

En esta lección vamos a utilizar CodePen, que es una herramienta que nos permite escribir código directamente desde el navegador y ver los resultados casi al instante.

En la pantalla puedes ver que ya preparé un pequeño ejemplo en HTML.

Hay que escribir los estilos en el panel de CSS que se encuentra a la derecha y, unos segundos después, veremos cómo cambian los elementos en la vista previa.

Vamos a comenzar.

---

## ¿Cómo funciona una regla CSS?

Antes de escribir estilos, necesitamos entender cómo se ha construido una regla CSS.

Esta consta de tres partes.

Primero, el selector, que le indica al navegador qué elementos queremos modificar.

Después tenemos la propiedad, que indica qué característica queremos cambiar.

Y finalmente tenemos el valor, que indica cómo queremos que quede esa característica.

Por ejemplo, aquí el selector es la letra `p`.

Eso significa que estamos seleccionando todos los párrafos.

La propiedad es `color` y el valor es `blue`.

Traducido al lenguaje cotidiano, esta regla dice: todos los párrafos deben mostrarse en color azul.

Ahora que entendemos la estructura básica de una regla CSS, veamos los selectores más importantes.

---

## Selector de etiqueta

El primer selector que aprenderemos es el selector de etiqueta.

Es el más sencillo de todos.

Simplemente escribimos el nombre de una etiqueta HTML para modificar todos los elementos de ese tipo.

Por ejemplo, en nuestro HTML ya existe un título principal.

Voy a seleccionarlo utilizando la etiqueta `h1`.

Ahora abro las llaves que contienen las propiedades que quiero aplicar.

Dentro escribo la propiedad `color`.

Después de los dos puntos escribo el valor `darkblue` y termino la línea con un punto y coma.

Esperamos un momento y observamos el resultado.

El título cambió de color.

---

## Selector de clase

Ahora vamos a aprender uno de los selectores más utilizados en el desarrollo web: las clases.

Las clases sirven para agrupar elementos y aplicarles estilos específicos.

Primero vemos dónde aparece una clase en HTML.

Aquí tengo un párrafo.

Vemos que dentro de la etiqueta de apertura aparece algo nuevo.

Esto se llama atributo `class` y su valor es `destacado`.

Ahora que el elemento tiene una clase, podemos seleccionarlo desde CSS.

Voy al panel.

Para seleccionar una clase escribimos un punto.

Este es importante, ya que le va a indicar al navegador que estamos buscando una clase.

Después escribimos el nombre `destacado`.

Abro las llaves y agrego la propiedad `background-color`.

Su valor será `yellow`.

Después de unos segundos aparece el cambio.

Ahora el párrafo tiene un fondo amarillo.

Y lo mejor es que cualquier elemento que tenga la clase `destacado` recibirá exactamente el mismo estilo.

Un error común al comenzar es crear un ID para todo.

En proyectos reales, la mayoría de estilos suelen aplicarse mediante clases porque son mucho más fáciles de reutilizar.

---

## Selector de ID

El siguiente selector es el ID.

Los IDs se utilizan cuando queremos identificar un elemento único dentro de la página.

Por ejemplo, tenemos en la parte de HTML un ID que es el título principal.

Vamos a seleccionarlo desde CSS.

Para seleccionar un ID utilizamos el símbolo numeral.

Después escribimos exactamente el mismo nombre del ID.

En este caso, `titulo-principal`.

Abro llaves y utilizaré la propiedad `font-size`.

Esta propiedad controla el tamaño del texto.

Le asignaré el valor de 36 píxeles y, cuando la vista previa se actualice, el título se volverá más grande.

---

## Colores

Ahora que sabemos seleccionar elementos, vamos a ver las propiedades esenciales.

Comencemos por los colores.

Voy a seleccionar el elemento `body`, ya que este contiene prácticamente todo el contenido visible de la página.

Primero escribiré la propiedad `background-color`, ya que esta va a cambiar el color de fondo.

Como valor utilizaré un código hexadecimal.

Estos permiten elegir colores de forma muy precisa.

Pero si también quieres algo más general, puedes hacer como en los casos anteriores y escribir directamente el color, como por ejemplo `darkblue`.

Ahora agregaré la propiedad `color`, que va a controlar el color del texto.

Después de unos segundos podemos ver cómo cambia toda la apariencia de la página.

---

## Fuentes y tipografía

Otro aspecto importante del diseño es la tipografía.

Las fuentes influyen mucho en la apariencia de una página.

Voy a seleccionar todos los párrafos y primero utilizaré la propiedad `font-family`, ya que esta va a definir la fuente.

Escribo `Arial`, después agrego una coma y luego `sans-serif`.

Esto funciona como respaldo, ya que si el dispositivo no tiene Arial disponible, utilizará otra fuente de la familia `sans-serif`.

Ahora agregaré la propiedad `font-size` y el valor será de 16 píxeles.

Cuando la vista previa se actualiza, los párrafos cambian de apariencia.

Cuando empieces a diseñar páginas web, evita utilizar demasiadas fuentes diferentes.

Dos fuentes suelen ser suficientes para mantener un diseño limpio y profesional.

---

## Centrar texto

Ahora veamos una propiedad muy utilizada: cómo centrar texto.

Voy a volver a seleccionar el título principal y utilizaré la propiedad `text-align`.

Esta controla la alineación del texto.

Su valor será `center`.

Cuando se actualiza la vista previa, el título se moverá al centro.

Muchos principiantes intentan centrar contenido agregando espacios manualmente.

Esto puede funcionar por casualidad, pero no es la forma correcta, ya que CSS incluye herramientas específicas para controlar la alineación.

---

## Práctica y cierre

Ahora que ya aprendiste los conceptos fundamentales de CSS, es momento de que practiques.

En la descripción encontrarás un pequeño código HTML con el título de "Reto".

Vas a copiarlo en la página de CodePen y, en la parte de CSS, empezarás a modificar.

Cambiarás el color del título, elegirás una fuente diferente para los párrafos y centrarás tu nombre.

No olvides que no existe una única respuesta correcta.

CSS se aprende experimentando.
