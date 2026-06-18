# Introduciéndonos a colores, fuentes y diseños

## Práctica 4: Dale vida a tu página web

```html
<!-- HTML base-->
<h1 id="titulo-principal">Mi Primera Página con Estilo</h1>

<p>HTML crea la estructura de la página, como si fuera el esqueleto. Pero se ve un poco aburrido por sí solo.</p>

<p class="destacado">Este texto tiene fondo amarillo.</p>

<p>CSS es la ropa que le da color, fuentes y vida a este contenido.</p>
```

```css
/* Task 1: Escribe un selector de etiqueta */
h1 {
  color: darkblue;
}

/* Task 2: Escribe un selector de clase */
.destacado {
  background-color: yellow;
}

/* Task 3: Escribe un selector de ID */
#titulo-principal {
  font-size: 36px;
}

/* Task 4: Escribe las propiedades para cambiar el color de fondo y texto */
body {
  background-color: #f0f4f8;
  color: #333333;
}

/* Task 5: Escribe las propiedades para cambiar el tipo de fuente y tamaño del texto */
p {
  font-family: Arial, sans-serif;
  font-size: 16px;
}

/* Task 5: Escribe las propiedades para centrar el título principal */
h1 {
  text-align: center;
}
```