<!-- No borrar o modificar -->
[Inicio](./index.md)

## Sesión 8 

## Actividad: Aplicando estilos con selectores CSS
El objetivo de esta actividad es crear la estructura HTML básica de una página web y aplicar diferentes selectores CSS para modificar su presentación.

### Pasos:

1. Crea el esqueleto de una página web simple con la siguiente estructura:
+ Encabezado `<header>`
+ Tres párrafos `<p>`
+ Una imagen `<img>`
+ Un pie de página `<footer>`

2. Aplica los siguientes estilos usando selectores de etiqueta:
+ Color rojo a los encabezados `<h1>`
+ Color azul a los párrafos `<p>`
+ Borde grueso negro a la imagen `<img>`

3. Aplica los siguientes estilos usando seleccionadores de clase:
+ Color verde a los elementos con la clase ".destacado"
+ Tamaño de fuente grande a los elementos con la clase ".grande"

4. Aplica los siguientes estilos usando seleccionadores de ID:
+ Color amarillo al elemento con ID "#principal"
+ Sombra al elemento con ID "#sombras"

4. Aplica los siguientes estilos usando seleccionadores descendientes:
+ Color gris a los párrafos dentro de un <div>
+ Centrar el contenido de la sección <section>

## Solución activida 8

```html

<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <Style>
        h1 {
            background-color: black;
            color: red;
            width: 200px;
            text-align: center;
        }

        p {
            color: blue;
        }

        img {
            border: 10px solid black;
        }

        body {
            background-color: gray;
        }

        .destacado {
            color: rgb(21, 255, 0);
        }

        .grande {
            font-size: 30px;
        }

        .footer {
            background-color: black;
            color: red;
            width: 200px;
            text-align: center;
        }

        #principal {
            color: yellow;
        }

        #sombras {
            box-shadow: 10px 10px 10px blue;
            border-radius: 30px;
        }

        div p {
            background-color: black;
        }

        section p {
            text-align: center;
        }
    </Style>
</head>

<body>
    <header>
        <h1 id="sombras">Hola mundo</h1>
    </header>

    <div>
        <section>
            <p id="principal">Elemento 1</p>
            <p class="destacado">Elemento 2</p>
            <p class="grande">Elemento 3</p>
        </section>
    </div>

    <div>
        <img src="https://firebasestorage.googleapis.com/v0/b/fotos-269d3.appspot.com/o/estudiamos_mecanica_cabecera_blog_seas.jpg?alt=media&token=e169aaa2-f8c0-42bf-a96c-d59a7846633b&_gl=1*onqr2n*_ga*MTY4MDMwODQyNS4xNjk3MzE3ODgw*_ga_CW55HF8NVT*MTY5ODM1MjAzNy4yMC4xLjE2OTgzNTIwMzkuNTguMC4w"
            alt="Estudiamos mecanica">
    </div>

    <footer class="footer">
        <h1>Fin del trabajo</h1>
    </footer>
</body>

</html>

```
