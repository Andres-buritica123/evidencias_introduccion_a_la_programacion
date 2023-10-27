<!-- No borrar o modificar -->
[Inicio](./index.md)

## Sesión 9 

## Actividad: Propiedades de espaciado y unidades de medida

### Objetivo:
Practicar el uso de las propiedades de espaciado margin, padding, border y border-radius, con diferentes unidades de medida.

1. Crea un nuevo archivo HTML y CSS.

2. En el archivo HTML, agrega el siguiente código:

```html

<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <title>Propiedades de espaciado</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <div class="contenedor">
    <div class="elemento"></div>
  </div>
</body>
</html>

```

3. En el archivo CSS, agrega el siguiente código:

```css

.contenedor {
  width: 200px;
  height: 200px;
}

.elemento {
  width: 100px;
  height: 100px;
}

```

4. Abre el archivo HTML en tu navegador. Verás un cuadrado de 100x100 píxeles.

5. Practicar el uso de las propiedades de espaciado.
+ Margin: Agrega un margen de 10 píxeles a todos los lados del elemento.

```css

.elemento {
  margin: 10px;
  width: 100px;
  height: 100px;
}

```

+ Padding: Agrega un relleno de 20 píxeles a todos los lados del elemento.

```css

.elemento {
  padding: 20px;
  margin: 10px;
  width: 100px;
  height: 100px;
}

```

+ Border-radius: Agrega un radio de esquina de 10 píxeles.

```css

.elemento {
  border-radius: 10px;
  border: 5px solid red;
  padding: 20px;
  margin: 10px;
  width: 100px;
  height: 100px;
}

```

+ Unidades de medida: Prueba diferentes unidades de medida para las propiedades de espaciado. Por ejemplo, puedes usar unidades porcentuales (%) para establecer un margen o relleno del 50%.

```css

.elemento {
  border-radius: 10px;
  border: 5px solid red;
  margin: 50%;
  padding: 50%;
  width: 100px;
  height: 100px;
}

```

## Preguntas:

1. ¿Qué es la propiedad `margin`?

2. ¿Qué es la propiedad `padding`?

3. ¿Qué es la propiedad `border`?

4. ¿Qué es la propiedad `border-radius`?

5. ¿Qué unidades de medida se pueden utilizar para las propiedades de espaciado?

## Solución actividad 9

1. La propiedad CSS margin establece el margen para los cuatro lados. Es una abreviación para evitar tener que establecer cada lado por separado con las otras propiedades de margen: margin-top, margin-right, margin-bottom y margin-left.

2. La propiedad padding es la que crea el espacio o área alrededor del contenido de un elemento. Consiste en el relleno superior, derecho, inferior e izquierdo. En CSS se escriben como padding-top, padding-right, padding-bottom y padding-left.

3. La propiedad border permite definir en una única regla todos los bordes de los elementos seleccionados. Se puede utilizar border para definir el o los valores siguientes: border-width, border-style, border-color.

4. La propiedad CSS border-top-left-radius establece el redondeo de la esquina superior izquierda del elemento. El redondeo puede ser un círculo o una elipse, o si uno de los valores es 0, no se redondeará la esquina, dejándola cuadrada.

5. Píxeles (px), points (pt), porcentaje (%), ems (em), rem (rem), view height (vh), centimetros (cm), milimetros (mm), pulgadas (in) y picas (pc).
