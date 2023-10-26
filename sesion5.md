<!-- No borrar o modificar -->
[Inicio](./index.md)

## Sesión 5 

## Actividad: Diseñar un formulario de pedido de un producto

### Objetivo:
Aplicar los conocimientos sobre los tipos de etiquetas HTML para diseñar un formulario de pedido de un producto.

### Instrucciones:

1. Crear un nuevo documento HTML.

2. Crear un formulario con los siguientes campos:
+ Nombre del producto
+ Cantidad
+ Precio unitario
+ Precio total
+ Dirección de envío
+ Información de contacto (nombre, correo electrónico, número de teléfono)

3. Agregar los siguientes campos relacionados al formulario:
+ Método de pago
+ Fecha de entrega
+ Comentarios

4. Utilizar las etiquetas HTML apropiados para cada campo.

## Solución actividad 5

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
        <h1>Fomulario en html</h1>
    </header>
    <form action="" method="post" autocomplete="on">
        <div>
            <label for="producto">Nombre del producto:</label>
            <input type="text" name="producto" id="producto" placeholder="Nombre del producto" required>
        </div>
        <br>
        <div>
            <label for="cantidad">Cantidad:</label>
            <input type="number" name="cantidad" id="cantidad" placeholder="Cantidad" min="0" required>
        </div>
        <br>
        <div>
            <label for="precio unitario">Precio unitario:</label>
            <input type="number" name="precio unitario" id="precio unitario" placeholder="Precio unitario" min="0"
                required>
        </div>
        <br>
        <div>
            <label for="precio total">Precio total:</label>
            <input type="number" name="precio total" id="precio total" placeholder="Precio total" min="0" required>
        </div>
        <br>
        <div>
            <label for="dirección de envío">Dirección de envío:</label>
            <input type="text" name="dirección de envío" id="dirección de envío" placeholder="Dirección de envío"
                required>
        </div>
        <h2>Información de contacto</h2>
        <div>
            <label for="nombre">Nombre:</label>
            <input type="text" name="nombre" id="nombre" placeholder="Nombre" required>
        </div>
        <br>
        <div>
            <label for="correo">Correo electrónico:</label>
            <input type="email" name="correo" id="correo" placeholder="Correo electrónico">
        </div>
        <br>
        <div>
            <label for="telefono">Número de teléfono:</label>
            <input type="tel" name="telefono" id="telefono" placeholder="Número de teléfono" required>
        </div>
        <br>
        <div>
            <label for="pago">Método de pago:</label>
            <select name="pago" id="pago" required>
                <option value="Tarjeta">Tarjeta</option>
                <option value="Efectivo">Efectivo</option>
            </select>
        </div>
        <br>
        <div>
            <label for="fecha">Fecha de entrega:</label>
            <input type="date" name="fecha" id="fecha" placeholder="Fecha de entrega" required>
        </div>
        <br>
        <div>
            <label for="comentario">Dejenos su comentario:</label>
            <br>
            <textarea name="comentario" id="comentario" placeholder="Dejenos su comentario" cols="50"
                rows="10"></textarea>
        </div>
        <br>
        <div>
            <button type="submit" name="boton 1" id="boton 1" value="Enviar">Enviar</button>
        </div>
    </form>
</body>

</html>

```
