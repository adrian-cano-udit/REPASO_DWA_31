# REPASO_DWA_31

- Para ajuste de línea Alt+Z

CREAR ESTRUCTURA BÁSICA DEL HTML

+ CREAR UN HEADER (DENTRO DEL HEADER UN H1), UN NAV, UN MAIN (DENTRO DE MAIN 3 SECTION) Y UN FOOTER 
+ HACER UN COMMIT -> BASIC HTML 


        <meta name="viewport" content="width=device-width, initial-scale=1.0">

Esta etiqueta <meta> es indispensable si vamos a crear una web responsive


CSS 

El selector universal * -> selecciona todos los elementos del HTML.


MODELO DE CAJAS DE HTML Y CSS

Todos los elementos de HTML son cajas y estas tienen diferentes propiedades como padding, border y margin (contando desde dentro hacia fuera de la caja).


- Crear un selector que SOLO afecte al p que hay dentro del header, cambiar colo y tamaño.



SELECTORES COMBINADOS DE CSS:

header > p -> selecciona todos los elementos p que son hijos directos de header

header p -> selcciona todos los p que son hijos de un header a cualquier nivel (puede haber un p dentro de un div)


TAREAS A REALIZAR:

Centrar todo el texto del header.

Convertir el nav y ul y li, en un menu horizontal CENTRADO. Los enlaces que no aparezcan en azul (ponerlos en negrita) y que tampoco esten subrayados.


Un efecto hover sobre cada una de las opciones de menú. Cambia de color el fondo de cada opcion generando una caja con los bordes redondeados. Se invierten los colores del fondo de la cajita y del texto.


## VARIABLES DE CSS:

Las declaramos al principio del archivo de CSS en la psuedo-clase :root {}, los nombre deben comenzar con --nombre-de-variable

Llamamos o invocamos con la función var(--valor)