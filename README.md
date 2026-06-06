# Bono-Programable

Presentación de las dos calculadoras y menu principal para el bono


Conteo Combinatorio

Desarrolle dos herramientas generales en Python Collab que permiten resolver problemas de conteo a partir de los datos que ingrese el usuario, automatizando los cálculos para cualquier valor válido.


Problemas Resueltos


Coeficientes Multinomiales

El programa calcula cuántas formas distintas existen para ordenar un conjunto de objetos con elementos repetidos. Funciona ingresando una palabra directamente (como BANANA) o una lista de frecuencias. Además, si la entrada es pequeña (hasta 8 caracteres), añadí una función para generar la lista completa de todas las palabras posibles.



Distribución de Objetos en Cajas

La herramienta cubre cinco variantes para repartir n objetos en k cajas, dependiendo de si los objetos son idénticos o distintos, y si se permiten o no las cajas vacías. También incluye el caso más complejo de distribución con límite de capacidad por caja usando el principio de Inclusión-Exclusión

**Nota sobre los Números de Stirling porque para resolver correctamente el caso de objetos distintos sin cajas vacías, me topé con los Números de Stirling de segunda especie. Como no venían en el enunciado original ni los hemos visto con ese nombre en el curso, me pareció interesante investigar cómo funcionaban y trabajarlos**


Estructura y Ejecución

El código está escrito en Python y no necesita ninguna librería externa. El proyecto incluye dos archivos: conteo_combinatorio.py (para usar desde la terminal con un menú interactivo) y conteo_combinatorio.ipynb (por si necesita abrirlo y ejecutarlo en Google Colab).
Al abrir el archivo en COLAB se sugiere que se ejecuten una por una todas las celdas del codigo, no tanto por ejecucion sino por claridad del código (y al final del todo en las celdas del COLAB), vera un menú sencillo en la consola: HERRAMIENTA DE CONTEO COMBINATORIO
1. Correr todas las pruebas automáticas
2. Calculadora — Multinomial
3. Calculadora — Distribución de objetos en cajas
4. Salir

Cómo ejecutar
En Google Colab:

Abrir colab.research.google.com
Archivo → Subir notebook → seleccionar conteo_combinatorio.ipynb
Ejecutar las celdas en orden con Ctrl+F9, o celda por celda con Shift+Enter

En Python local:

bashpython conteo_combinatorio.py
No requiere instalar librerías externas, solo Python 3.10 o superior.


Pruebas

<img width="665" height="360" alt="image" src="https://github.com/user-attachments/assets/1b9f9127-c983-401c-9ffb-df7db5abac65" />

<img width="1087" height="231" alt="image" src="https://github.com/user-attachments/assets/8c3dd336-1525-4dae-b67d-375cd6f1f98a" />

-
-
-

CASOS DE ENTRADA Y SALIDA EN MENU PRINCIPAL

EJERCICIO 1  "MANZANA"

<img width="780" height="437" alt="image" src="https://github.com/user-attachments/assets/aec73eab-4d0d-4ab2-b821-950d70fc69ed" />


-
-

EJERCICIO 2   10 objetos distintos, 3 cajas con limite de 4 objetos y se permiten estar vacias

<img width="593" height="456" alt="image" src="https://github.com/user-attachments/assets/12facabf-21d2-4a4a-be84-0ddb30c6ab35" />

