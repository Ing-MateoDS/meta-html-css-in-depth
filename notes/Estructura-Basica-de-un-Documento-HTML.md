Estructura

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Document</title>
  </head>
  <body></body>
</html>
```

Al igual que en un elevador los botones que llevan a cada piso tienen un numero para indicar a que piso van (semanticamente) en HTML se debe de utilzar igualmente las etiquetas semanticamente para describir el codigo.

El codigo del sitio web debe ir dentro del body, ahi va el encabezado, cuerpo y pie de pagina (header, main y footer). Debe quedar semanticamente de esta manera:

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Document</title>
  </head>

  <body>
    <header></header>
    <main></main>
    <footer></footer>
  </body>
</html>
```

Ejemplo visual:

1. Logotipos del negocio y enlaces de navegacion (header/nav)
2. Seccion principal que contiene secciones y articulos (seccion y article)
3. Pie de pagina, contiene informacion de contacto y enlaces a redes sociales (footer)
