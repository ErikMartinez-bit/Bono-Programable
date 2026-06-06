# Bono-Programable
Presentación de las dos calculadoras y menu principal para el bono
Conteo Combinatorio
Desarrolle dos herramientas generales en Python Collab que permiten resolver problemas de conteo a partir de los datos que ingrese el usuario, automatizando los cálculos para cualquier valor válido.
Problemas Resueltos

Coeficientes Multinomiales
El programa calcula cuántas formas distintas existen para ordenar un conjunto de objetos con elementos repetidos. Funciona ingresando una palabra directamente (como BANANA) o una lista de frecuencias. Además, si la entrada es pequeña (hasta 8 caracteres), añadí una función para generar la lista completa de todas las palabras posibles.

Distribución de Objetos en Cajas
La herramienta cubre cinco variantes para repartir n objetos en k cajas, dependiendo de si los objetos son idénticos o distintos, y si se permiten o no las cajas vacías. También incluye el caso más complejo de distribución con límite de capacidad por caja usando el principio de Inclusión-Exclusión
**Nota sobre los Números de Stirling:Para resolver correctamente el caso de objetos distintos sin cajas vacías, me topé con los Números de Stirling de segunda especie. Como no venían en el enunciado original ni los hemos visto con ese nombre en el curso, me pareció interesante investigar cómo funcionaban y programarlos**


Estructura y Ejecución
El código está escrito en Python 3.10 o superior y no necesita ninguna librería externa. El proyecto incluye dos archivos: conteo_combinatorio.py (para usar desde la terminal con un menú interactivo) y conteo_combinatorio.ipynb (por si necesita abrirlo y ejecutarlo en Google Colab).
Al iniciar el programa (y al final del todo en las celdas del COLAB, vera un menú sencillo en la consola: HERRAMIENTA DE CONTEO COMBINATORIO
1. Correr todas las pruebas automáticas
2. Calculadora — Multinomial
3. Calculadora — Distribución de objetos en cajas
4. Salir

Las pruebas se encuentran comentaredas en el respectivo bloque de pruebas. Por si requiere una explicacion o un adelanto de lo que peude dar el resultado.
