Estos son los dos elementos clave del contenido principal **Article** y **Section.**

Article → el contenido que iran dentro del Article, representa una composicion completamente autonoma del sitio y se puede distribuir de forma independiente.

Ejemplos de Article:

- Forum post → publicacion en un foro
- Article → articulo
- Blog post → entrada de blog
- User comment → comentario enviado por un usuario
- Interactive widget → widget interactivo

Un gadget o cualquier otro elemento independiente del contenido

Un ejemplo claro de donde puede utilizarse el Article:

Puede utilizarse al desarrollar un blog personal o para contar algo, ya que es un buena practica inluir el contenido de la entrada del blog dentro del elemento article, ya que es una composicion completa e independiente de una pagina web.

Ejemplo:

1. primero agregar el article dentro del elemento de entrada principal (main)
2. agregar un elemento de encabezado (h2/ heading tag)
3. agregar un parrafo que describe el blog (p/ paragraph tag)

```html
<main>
  <article>
    <h2>My summer vacation</h2>
    <p>
      This summer, I went to the beach with my family. We had a great time
      swimming in the ocean and building sandcastles. We also went on a boat
      tour and saw some dolphins. It was a wonderful vacation!
    </p>
  </article>
</main>
```

Todo esto va dentro del main (elemento principal de la pagina) es por que justamente el main es el contenido principal de la pagina.

- dentro del main puede haber varios **Article**

Un article deberia quedar asi:

1. tener un header (encabezado)
2. tener un titulo de blog (h2/ heading tag)
3. un elemento de parrafo que describe la fecha y el autor (p/paragraph tag)
4. dentro del main, en un parrafo describir el contenido de la entrada principal del blog

```html
<main>
  <article>
    <header>
      <h2>My summer vacation</h2>
      <p>
        This summer, I went to the beach with my family. We had a great time
        swimming in the ocean and building sandcastles. We also went on a boat
        tour and saw some dolphins. It was a wonderful vacation!
      </p>
    </header>
    <main>
      <p>This was my most memorable summer vacation so far!</p>
    </main>
  </article>
</main>
```
