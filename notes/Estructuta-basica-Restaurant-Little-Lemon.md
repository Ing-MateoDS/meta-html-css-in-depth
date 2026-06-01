1. Header element
2. Nav element
3. Main element
4. Footer element

- El header se utilizara para mostrar el logotipo de Little Lemon
- El nav, para la estructura de navegacion del sitio web
- el main, se encargara del contenido principal del sitio web
- el footer, se utilizara para mostrar la informacion de los derechos de autor

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Little Lemon</title>
    <link rel="stylesheet" href="style.css" />
  </head>

  <body>
    <header></header>
    <nav>
      <ul>
        <li><a href="#home">Home</a></li>
        <li><a href="#about">About</a></li>
        <li><a href="#contact">Contact</a></li>
      </ul>
    </nav>
    <main></main>
    <footer></footer>
  </body>
</html>
```

Cuando un motor de busqueda lea este documento, las etiquetas semanticas ayudaran a que el software entienda el prosito y el significado de las diferentes secciones del documento

Asi quedo organizado semanticamente el primer ejercicio, lo que garantiza la accesibilidad y la optimizacion del motor de busqueda.

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <!-- titulo del sitio web y enlace a la hoja de estilos css para el diseño del sitio web -->
    <title>Little Lemon</title>
    <link rel="stylesheet" href="style.css" />
  </head>

  <body>
    <header>
      <!-- insertar una imagen para el logotipo y describir que es -->
      <img src="logo.png" alt="Little Lemon Logo" />
    </header>
    <nav>
      <ul>
        <li><a href="#index.html">Home</a></li>
        <li><a href="#location.html">Location</a></li>
        <li><a href="#blog.html">Blog</a></li>
      </ul>
    </nav>
    <main>
      <!-- Habra dos entradas de blog -->
      <h1>Blog</h1>
      <article>
        <h2>20% off this weekend</h2>
        <p>Don't miss out on our limited-time offer!</p>
      </article>
      <article>
        <h2>Our New Menu</h2>
        <p>We're excited to announce our new menu with delicious dishes!</p>
      </article>
    </main>
    <footer>
      <p>Copyright Little Lemon</p>
    </footer>
  </body>
</html>
```
