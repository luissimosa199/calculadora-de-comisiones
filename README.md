# Calculadora de Comisiones

## Calculadora de comisiones para ventas de planes Movistar

Este proyecto tiene como fin calcular las comisiones de las ventas que realizamos
para Movistar (ventas de abonos telefónicos).

Cada venta representa una comisión de 21% del valor real del plan sin impuestos.

En este caso los datos de entrada es un string con la cantidad de gigas del plan y
opcionalmente el tipo de gestión en el que se realizó la venta (in/out).

La Calculadora de Comisiones utiliza una expresión regular (RegEx) para calcular
la cantidad, tipos de plan y gestión para luego almacenar los valores en variables.

Estas variables se le muestran al usuario con el cálculo del total de comisiones,
y cantidad de ventas en total y por gestión. Si el usuario no ingresa el tipo de
gestión la Calculadora omite la verificación y solo calcula el total.

## Herramientas

- HTML, CSS y JavaScript

## Live code

https://luissimosa199.github.io/calculadora-de-comisiones
