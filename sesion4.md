<!-- No borrar o modificar -->
[Inicio](./index.md)

## Sesión 4

## Actividad: Crear una tabla HTML con información sobre productos.
Escribir una tabla HTML con 10 filas que muestre información sobre productos reales. La tabla debe tener las siguientes columnas:

+ Código
+ Nombre
+ Descripción
+ Precio
+ Stock
+ Fecha de creación

Además, combinar celdas en la tabla con los atributos rowspan y colspan, como se muestra en la siguiente imagen.

![Tabla de html](https://firebasestorage.googleapis.com/v0/b/cesde-7fe22.appspot.com/o/IP%2FIPS4-1.png?alt=media&token=b46ee6fd-97c8-400e-af16-cc88c3819d00)

## Solución actividad 4

```html

<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Tabla</title>
</head>

<body>
    <table border="1" cellpadding="5" cellspacing="5" align="center">
        <thead>
            <tr>
                <th colspan="7">Inventario de una papeleria</th>
            </tr>
            <tr>
                <th>Codigo</th>
                <th>Producto</th>
                <th>Descripción</th>
                <th>Stokc inicial</th>
                <th>Entrada</th>
                <th>Salida</th>
                <th>Total</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td>P001</td>
                <td>Papel bond</td>
                <td>Paquete 100 hojas</td>
                <td>100</td>
                <td>36</td>
                <td>96</td>
                <td>40</td>
            </tr>
            <tr>
                <td>P002</td>
                <td>Papel vegetal</td>
                <td>Paquete 100 hojas</td>
                <td>124</td>
                <td>65</td>
                <td>50</td>
                <td>139</td>
            </tr>
            <tr>
                <td>P003</td>
                <td>Papel de colores</td>
                <td>Paquete 100 hojas</td>
                <td>150</td>
                <td>15</td>
                <td>0</td>
                <td>165</td>
            </tr>
            <tr>
                <td>P004</td>
                <td>Papel opalina</td>
                <td>Paquete 100 hojas</td>
                <td>100</td>
                <td>50</td>
                <td>20</td>
                <td>130</td>
            </tr>
            <tr>
                <td>P005</td>
                <td>Papel satinado</td>
                <td>Paquete 100 hojas</td>
                <td>30</td>
                <td>2</td>
                <td>5</td>
                <td>27</td>
            </tr>
            <tr>
                <td>X001</td>
                <td>Calculadora sencilla</td>
                <td>Individual</td>
                <td>300</td>
                <td>0</td>
                <td>3</td>
                <td>297</td>
            </tr>
            <tr>
                <td>X002</td>
                <td>Calculadora infantil</td>
                <td>Individual</td>
                <td>257</td>
                <td>0</td>
                <td>12</td>
                <td>245</td>
            </tr>
            <tr>
                <td>X003</td>
                <td>Calculadora profesional</td>
                <td>Individual</td>
                <td>200</td>
                <td>42</td>
                <td>0</td>
                <td>242</td>
            </tr>
            <tr>
                <td>X004</td>
                <td>Calculadora especial</td>
                <td>Individual</td>
                <td>108</td>
                <td>10</td>
                <td>7</td>
                <td>111</td>
            </tr>
            <tr>
                <td>B001</td>
                <td>Lapiz negro</td>
                <td>Individual</td>
                <td>1000</td>
                <td>300</td>
                <td>0</td>
                <td>1300</td>
            </tr>
            <tr>
                <td>B002</td>
                <td>Lapiz rojo</td>
                <td>Individual</td>
                <td>704</td>
                <td>450</td>
                <td>0</td>
                <td>1154</td>
            </tr>
            <tr>
                <td>B003</td>
                <td>Lapiz bicolor</td>
                <td>Individual</td>
                <td>499</td>
                <td>79</td>
                <td>0</td>
                <td>578</td>
            </tr>
            <tr>
                <td>B004</td>
                <Td>Lapices de colores</Td>
                <td>Caja de 20</td>
                <td>662</td>
                <td>45</td>
                <td>0</td>
                <td>707</td>
            </tr>
        </tbody>

    </table>
</body>

</html>

```
