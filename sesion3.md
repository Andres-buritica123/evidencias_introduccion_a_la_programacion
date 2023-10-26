<!-- No borrar o modificar -->
[Inicio](./index.md)

## Sesión 3 

## Actividad: Adición de contenido multimedia en un sitio web utilizando etiquetas HTML5

Completa el siguiente código HTML añadiendo el contenido multimedia correspondiente en cada sección:

+ 4 Imagenes
+ 2 Videos
+ 4 Audios
+ 2 Inline Frame

Utiliza encabezados para títulos en cada elemento (<h1>...<h6>).

Crea una descripción para cada elemento utilizando párrafos (<p>).

Además, puedes emplear las siguientes etiquetas para mejorar la estructura y estilo de tu contenido:

+ Usa <strong> para resaltar texto importante.
+ Utiliza <br> para insertar saltos de línea si es necesario.
+ Agrega <span> para aplicar estilos específicos a porciones de texto.
+ Emplea <i> para enfatizar o dar énfasis a palabras o frases.
+ Utiliza <u> para subrayar texto cuando sea necesario.
+ Considera el uso de <div> para crear secciones o contenedores para tu contenido, lo que puede facilitar la organización y el diseño de la página.

## Plantilla Inicial

```html

<!DOCTYPE html>
<html>

<head>
    <title>Etiquetas Multimedia HTML5</title>
    <style>
        body {
            font-family: Arial, sans-serif;
        }

        header {
            background-color: #333333;
            color: white;
            padding: 20px;
            text-align: center;
        }

        section {
            border: 1px solid #ddd;
            padding: 20px;
            margin-bottom: 20px;
        }

        h2 {
            color: blue;
        }

        footer {
            background-color: #333;
            color: white;
            padding: 20px;
            text-align: center;
        }
    </style>
</head>

<body>

    <header>
        <h1>Etiquetas Multimedia HTML5</h1>
        <h3>La forma más fácil de agregar multimedia a tus sitios web</h3>
    </header>

    <section>
        <h2>Imágenes</h2>
        <p>Contenido sobre imágenes...</p>
    </section>

    <section>
        <h2>Videos</h2>
        <p>Contenido sobre videos...</p>
    </section>

    <section>
        <h2>Audios</h2>
        <p>Contenido sobre audios...</p>

    </section>

    <section>
        <h2>iFrames</h2>
        <p>Contenido sobre iframes...</p>
    </section>

    <footer>
        Nombre Completo
        <br>
        <br>
        CESDE
        <br>
        <br>
        &copy;2023
    </footer>

</body>

</html>

```

## Semántica y Estructura de la Plantilla

El código HTML y CSS proporcionado describe un sitio web que trata sobre etiquetas multimedia en HTML5. A continuación, se desglosa la semántica y estructura del sitio:

`<!DOCTYPE html>`: Esto define el tipo de documento como HTML5.

`<html>`: La etiqueta raíz que envuelve todo el contenido HTML del sitio.

`<head>`: Aquí se encuentran las metainformaciones y enlaces a recursos externos. En este caso, se define el título de la página y se incluye un bloque `<style>` para agregar reglas de estilo CSS.

`<title>`: Establece el título de la página en la pestaña del navegador.

`<style>`: Contiene reglas de estilo CSS que afectan al diseño y la apariencia de sitio.

`<body>`: Aquí se coloca el contenido principal visible de la página.

`<header>`: Sección de encabezado que contiene el título principal y un subtítulo.

`<h1>` y `<h3>`: Encabezados de nivel 1 y 3, respectivamente, que proporcionan títulos jerárquicos y estructuran la información del encabezado.

`<section>`: Define una sección de contenido temático. Se utilizan para agrupar información relacionada.

`<h2>`: Encabezado de nivel 2 que se utiliza para los títulos de las secciones de contenido.

`<p>`: Párrafo de texto que contiene contenido informativo sobre las imágenes, videos, audios y iframes.

`<footer>`: Pie de página que contiene información de autoría y derechos de autor. Incluye saltos de línea `<br>` para separar las líneas de texto.

En cuanto al estilo, el CSS define reglas para la apariencia visual del sitio:

+ La fuente del cuerpo del sitio es Arial o una fuente sans-serif en caso de que Arial no esté disponible.
+ El encabezado (`<header>`) tiene un fondo oscuro, texto blanco y un espacio de relleno.
+ Cada sección (`<section>`) tiene un borde, un espacio de relleno y un margen inferior.
+ Los encabezados de nivel 1 y 3 están centrados.
+ Los encabezados de nivel 2 (`<h2>`) tienen color azul.
+ El pie de página (`<footer>`) tiene un fondo oscuro, texto blanco, espacio de relleno y está centrado.

Este sitio utiliza HTML5 y CSS para presentar información sobre etiquetas multimedia en HTML5, con una estructura semántica que utiliza encabezados, párrafos y secciones para organizar y presentar el contenido. El estilo CSS proporciona una apariencia visual coherente y agradable.

## Solución activida 3

```html

<!DOCTYPE html>
<html lang="en">
<!DOCTYPE html>
<html>

<head>
    <title>Etiquetas Multimedia HTML5</title>
    <style>
        body {
            font-family: Arial, sans-serif;
        }

        header {
            background-color: rgba(98, 0, 255, 0.534);
            color: rgb(0, 0, 0);
            padding: 20px;
            text-align: center;
        }

        section {
            border: 1px solid #000000;
            padding: 20px;
            margin-bottom: 20px;
        }

        h2 {
            color: rgb(255, 0, 0);
        }

        footer {
            background-color: rgba(98, 0, 255, 0.534);
            color: rgb(0, 0, 0);
            padding: 20px;
            text-align: center;
        }
    </style>
</head>

<body>

    <header>
        <h1>Etiquetas Multimedia HTML5</h1>
        <h3>La forma más fácil de agregar multimedia a tus sitios web</h3>
    </header>

    <section>
        <h2>Imágenes</h2>
        <h3>Graffitis</h3>
        <p>Se llama <strong>grafiti, grafito</strong> o <strong>pintada </strong>a una modalidad de pintura libre,
            destacada por su ilegalidad,
            generalmente realizada en espacios urbanos. Su origen se remonta a las inscripciones que han quedado en
            paredes desde los tiempos del Imperio romano, especialmente las que son de carácter satírico o crítico. Para
            denominar estas inscripciones de época arqueológica es más frecuente el uso de la palabra «grafito».</p>
        <img src="https://firebasestorage.googleapis.com/v0/b/fotos-269d3.appspot.com/o/tecnicas-del-graffiti-.jpg?alt=media&token=8b3b1c66-0340-4bcf-b56c-65329a27b80b&_gl=1*iqkmfv*_ga*MTY4MDMwODQyNS4xNjk3MzE3ODgw*_ga_CW55HF8NVT*MTY5ODM0NDIxNy4xOC4xLjE2OTgzNDUxMTEuNjAuMC4w" alt="Graffitis Urbanos" height="200" width="350">
        <h3>Algunos tipos de Graffitis</h3>
        <p><strong><u>Tag (Firma):</u></strong> Es la base del graffiti, la firma. Como en un principio el objetivo era
            escribir
            el nombre el mayor número de veces posible, las letras eran legibles y sencillas, lo que conllevaba también
            un menor tiempo de ejecución. Además, en esta primera época aún no se tenían referencias de otros estilos y
            la técnica era muy básica. </p>
        <img src="https://firebasestorage.googleapis.com/v0/b/fotos-269d3.appspot.com/o/tag.jpg?alt=media&token=7409a763-290e-49e6-91c6-2fc6514ecbd2&_gl=1*tmqlcp*_ga*MTY4MDMwODQyNS4xNjk3MzE3ODgw*_ga_CW55HF8NVT*MTY5ODM0NDIxNy4xOC4xLjE2OTgzNDUxNzcuNjAuMC4w" alt="Tag de un Graffiti" height="200" width="350">
        <p><strong><u>Wild Style (Estilo Salvaje):</u></strong> El estilo genuino del sur del Bronx es, quizás, el más
            popular y extendido. Surgió como resultado de la búsqueda de una mayor complejidad. Lleva adornos que no
            forman parte de la letra: círculos, espirales, picos, flechas, que le aportan dinamismo. Surge en la época
            de la guerra de estilos, en la que la única manera de identificar al autor era a través de su estilo.</p>
        <img src="https://firebasestorage.googleapis.com/v0/b/fotos-269d3.appspot.com/o/WildStyle.jpg?alt=media&token=fc9c8b28-f8d2-4d3f-a310-3b9b53aebff8&_gl=1*znwrzq*_ga*MTY4MDMwODQyNS4xNjk3MzE3ODgw*_ga_CW55HF8NVT*MTY5ODM0NDIxNy4xOC4xLjE2OTgzNDUyNDMuNTQuMC4w" alt="WildStyle Graffitis" height="200" width="350">
        <p><strong><u>Model Pastel (Estilo 3d):</u></strong> Busca crear un efecto de tridimensionalidad en las letras.
            A veces, el diseño de las letras pasa a un segundo plano y cobra más importancia su relleno. El efecto 3D se
            consigue por el uso del color, la forma de las letras en perspectiva, el cambio de ángulo de visión... Su
            carácter es menos espontáneo y más artístico, ya que requiere mayor dedicación. Al contrario que los demás,
            este estilo nació en Europa.</p>
        <img src="https://firebasestorage.googleapis.com/v0/b/fotos-269d3.appspot.com/o/Model%20pastel.jpg?alt=media&token=786d1230-f4f3-43a3-bde7-e7501fd649d5&_gl=1*ntqilb*_ga*MTY4MDMwODQyNS4xNjk3MzE3ODgw*_ga_CW55HF8NVT*MTY5ODM0NDIxNy4xOC4xLjE2OTgzNDUzMTYuNjAuMC4w" alt="Model pastel Graffitis" height="200" width="350">
        <p><strong><u>Graffiti Orgánico:</u></strong> Es un estilo relativamente novedoso. En una misma pieza se unen
            varios estilos. Las letras cobran un carácter propio adoptando formas de objetos, fusionando así el dibujo
            de letras tradicionales de graffiti con complementos como personajes u objetos.</p>
        <img src="https://firebasestorage.googleapis.com/v0/b/fotos-269d3.appspot.com/o/Graffiti%20Oraganico.jpg?alt=media&token=be9a95a2-ebcf-4260-a626-e798e6616191&_gl=1*b5sljc*_ga*MTY4MDMwODQyNS4xNjk3MzE3ODgw*_ga_CW55HF8NVT*MTY5ODM0NDIxNy4xOC4xLjE2OTgzNDUzOTEuNjAuMC4w" alt="Graffitis Orgánicos" height="200" width="350">
        <p><strong><u>Iconos:</u></strong> Pueden considerarse una derivación de los personajes, aunque un icono suele
            ser más esquemático y fácil en su ejecución. Su función es llamar la atención, ya que es más fácil recordar
            un icono que un nombre. Algunos escritores llegaron a sustituirlos por su firma. En los iconos se busca la
            originalidad y el impacto.</p>
        <img src="https://firebasestorage.googleapis.com/v0/b/fotos-269d3.appspot.com/o/Iconos.jpg?alt=media&token=3ccc808f-2cca-4305-a593-096dd9423fb5&_gl=1*irluis*_ga*MTY4MDMwODQyNS4xNjk3MzE3ODgw*_ga_CW55HF8NVT*MTY5ODM0NDIxNy4xOC4xLjE2OTgzNDU0NTMuNjAuMC4w" alt="Iconos en los Graffitis" height="200" width="350">
        <p><strong><u>Graffiti Abstracto:</u></strong> Es el grado extremo, donde el graffiti pierde su identidad, ya
            que las letras dejan de serlo, y el relleno de colores degradados pasa a ocupar la superficie entera del
            soporte.</p>
        <img src="https://firebasestorage.googleapis.com/v0/b/fotos-269d3.appspot.com/o/Graffiti%20Abstracto.jpeg?alt=media&token=a7f846d6-2595-40fb-92b5-c2b0061be7e6&_gl=1*1hlk1fw*_ga*MTY4MDMwODQyNS4xNjk3MzE3ODgw*_ga_CW55HF8NVT*MTY5ODM0NDIxNy4xOC4xLjE2OTgzNDU1MDkuNC4wLjA." alt="Graffitis Abstractos" height="200" width="350">
    </section>

    <section>
        <h2>Videos</h2>
        <h3>Paisajes</h3>
        <p><strong><u>Paisaje Urbano:</u></strong></P>
        <p>Rueda de la Fortuna</p>
        <video src="https://firebasestorage.googleapis.com/v0/b/fotos-269d3.appspot.com/o/Rueda%20de%20la%20Fortuna.mp4?alt=media&token=2877c146-10ca-48fa-aa69-7fbd09150fea&_gl=1*1ktcp61*_ga*MTY4MDMwODQyNS4xNjk3MzE3ODgw*_ga_CW55HF8NVT*MTY5ODM0NDIxNy4xOC4xLjE2OTgzNDQ4MjQuNjAuMC4w" height="200" width="350" controls></video>
        <p><strong><u>Paisaje Natural:</u></strong></P>
        <p>Vosgos Francia Nieve</p>
        <video src="https://firebasestorage.googleapis.com/v0/b/fotos-269d3.appspot.com/o/Vosgos%20Francia%20Nieve.mp4?alt=media&token=6f4043ca-9d02-40c8-9018-27a637539f58&_gl=1*1fz8erz*_ga*MTY4MDMwODQyNS4xNjk3MzE3ODgw*_ga_CW55HF8NVT*MTY5ODM0NDIxNy4xOC4xLjE2OTgzNDQ4NzIuMTIuMC4w" height="200" width="350" controls></video>
    </section>

    <section>
        <h2>Audios</h2>
        <h3>Musica</h3>
        <audio src="https://firebasestorage.googleapis.com/v0/b/fotos-269d3.appspot.com/o/good-night-160166.mp3?alt=media&token=98fd5068-b086-4dfc-97f9-239f649bcbe9&_gl=1*1fhhw0*_ga*MTY4MDMwODQyNS4xNjk3MzE3ODgw*_ga_CW55HF8NVT*MTY5ODM0NzQ5OC4xOS4wLjE2OTgzNDc0OTguNjAuMC4w" height="200" width="350" controls></audio>
        <audio src="https://firebasestorage.googleapis.com/v0/b/fotos-269d3.appspot.com/o/leonell-cassio-the-paranormal-is-real-ft-carrie-163742.mp3?alt=media&token=c58d2b62-1437-4d48-b9c6-077c76e87276&_gl=1*1a6ae3u*_ga*MTY4MDMwODQyNS4xNjk3MzE3ODgw*_ga_CW55HF8NVT*MTY5ODM0NzQ5OC4xOS4xLjE2OTgzNDc1NDkuOS4wLjA." height="200" width="350"
            controls></audio>
        <audio src="https://firebasestorage.googleapis.com/v0/b/fotos-269d3.appspot.com/o/seductive-chill-hip-hop-instrumental-hear-me-134134.mp3?alt=media&token=05969bc3-d8b2-4bfe-a4f1-078c753056ae&_gl=1*1qh74u0*_ga*MTY4MDMwODQyNS4xNjk3MzE3ODgw*_ga_CW55HF8NVT*MTY5ODM0NzQ5OC4xOS4xLjE2OTgzNDc2MTAuNjAuMC4w" height="200" width="350" controls></audio>
        <audio src="https://firebasestorage.googleapis.com/v0/b/fotos-269d3.appspot.com/o/unlock-me-149058.mp3?alt=media&token=a216d97c-bd75-458b-9001-b19bebe84e39&_gl=1*14rutgo*_ga*MTY4MDMwODQyNS4xNjk3MzE3ODgw*_ga_CW55HF8NVT*MTY5ODM0NzQ5OC4xOS4xLjE2OTgzNDc2NDkuMjEuMC4w" height="200" width="350" controls></audio>
    </section>

    <section>
        <h2>iFrames</h2>
        <p><strong><u>Video:</u></strong></P>
        <p>¿Qué pasaría si la Tierra fuera expulsada del Sistema Solar? Tierra interestelar</p>
        <iframe width="560" height="315" src="https://www.youtube.com/embed/3TmZfguAamE?si=I8uIUIXAThmlH__4"
            title="YouTube video player" frameborder="0"
            allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share"
            allowfullscreen></iframe>
        <p><strong><u>Pagina wed:</u></strong></P>
        <p>Teoria del Big_Bang</p>
        <iframe width="560" height="315" src="https://es.wikipedia.org/wiki/Big_Bang" frameborder="0"></iframe>

    </section>

    <footer>
        <strong>Andrés Felipe Buritica</strong>
        <br>
        <br>
        <strong>CESDE</strong>
        <br>
        <br>
        <strong>&copy;2023</strong>
    </footer>

</body>

</html>

</html>

```
