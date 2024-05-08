# 4.1. Actividades
En estos apartados de Actividades se proponen ejercicios para que se realicen el  análisis (detallando los datos de entrada poniendo nombre a las variables y tipo de dato, el resultado o salida, indetificando nombre de variables y tipo de datos, y los calculos o proceso), el diseño en pseudocódigo (puede ser en pseint y guardar lo generado en el formato de pseint .psc) y la implementación en python (archivos .py). Cada solución puede ser almacenada en un repositorio personal de github que luego puede compartir.
## EJERCICIO 2
Un pintor de casas debe hacer un presupuesto para un cliente. Lo que cobra se calcula de acuerdo a los metros cuadrados que debe pintar. El cliente le indica que necesita conocer el costo de mano de obra para pintar una pared rectangular de un galpón. El pintor cobra un monto ﬁjo por cada metro cuadrado. Puedes hacer un algoritmo para calcular el costo de mano de obra para pintar la pared.

### Análisis
- ***DATOS DE ENTRADA:*** monto por metro cuadrado, largo de la pared rectangular, ancho de la pared rectangular
- ***DATOS DE SALIDA:*** costo total del trabajo
- ***VARIABLES:***
  - precio_metro: precio del metro cuadrado
  - largo: largo de la pared
  - ancho: ancho de la pared
  - metros_totales: cantidad de metros cuadrados de la pared
  - presupuesto: costo total de la mano de obra


### Pseudocódigo
```
Algoritmo metro_cuadrado
	Escribir "ingrese el precio por metro cuadrado"
	Leer precio_metro
	Escribir "ingrese el ancho de la pared"
	Leer ancho
	Escribir "ingrese el largo de la pared"
	Leer largo
	metros_totales <- ancho * largo
	presupuesto <- metros_totales * precio_metro
	Escribir "el presupuesto de la obra es: $",presupuesto
	
FinAlgoritmo
```
### Diagrama de flujo
![4 1 2 diagrama](https://github.com/terrenoa/actividades4.1ej2/assets/85424039/eea88aae-4187-499b-9e7b-28cab936471b)
