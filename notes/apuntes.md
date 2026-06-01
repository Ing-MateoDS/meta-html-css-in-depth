HTML significa lenguaje de marcado de hipertexto

- hyper text markup language

Que significa:

- el hipertexto es un texto que contiene enlaces a otros textos, ejemplo
    - hace referencia a otros textos o cosas

```html
<a href="news.html">
this is a link
</a>
```

- el marcado se refiere a las etiquetas
    - en html se utilizan muchas etiquetas para indicar que algo tenga alguna funcion
    
    ```html
    <h1>
    this is a page heading
    </h1>
    ```
    

Actualmente se han agregado nuevas funciones a HTML, lo cual hace que sea mas facil usar que las versiones anteriores, estas nuevas compatibilidades son:

- contenido multimedia como audio y video
- diseño responsivo que permite se adapte el diseño del sitio tanto a pc como dispositivos moviles
- nuevos tipos de entrada de formularios, como:
    - controles deslizables
    - selectores de fecha
    - selectores de color
- nuevas funciones de validacion de formularios
- nuevas formas de trabajar con textos

El proposito del HTML en el navegador web es:

1. el uso de etiqueras HTML y sintaxis correcta
2. como se utilizan los elementos HTML en un documento web

Que se puede hacer con HTML:

- añadir imagenes a una pagina web con codigo HTML
- se puede usar para mostrar datos en tablas
- se pueden crear formularios con una amplia gama de entradas

Por ello, utilizar la estructura HTML correcta y los elementos apropiados como base es una parte esencial de crear sitios web accesibles.

El lenguage HTML, puede garantizar la accesibilidad de los sitios web al apoyar la tecnologia que las personas con discapacidad utilizan para interactuar con ellos y comprenderlos

Si HTML es el marco y la estructura de un edificio, CSS es la pintura, papel tapiz y accesorios y estilo en general.

CSS le indica al navegador web como mostrar los elementos HTML en la pantalla

Al igual que en un elevador los botones que llevan a cada piso tienen un numero para indicar a que piso van (semanticamente) en HTML se debe de utilzar igualmente las etiquetas semanticamente para describir el codigo.

El codigo del sitio web debe ir dentro del body, ahi va el encabezado, cuerpo y pie de pagina (header, main y footer). Debe quedar semanticamente de esta manera:

```html
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>

<body>
    <header>

    </header>
    <main>

    </main>
    <footer>

    </footer>

</body>

</html>
```

Ejemplo visual:

1. Logotipos del negocio y enlaces de navegacion (header/nav)
2. Seccion principal que contiene secciones y articulos (seccion y article)
3. Pie de pagina, contiene informacion de contacto y enlaces a redes sociales (footer)

!image.png

Es importante señalar que los elementos semanticos no se limitan a seguir la semantica que se vio en la seccion de **Article,** dado que su finalidad es describir la semantica del contenido, los elementos se pueden anidar uno dentro de otro si describen con precision el contenido