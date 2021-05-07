# Actividad_03
Semana Tec Actividad 3 PAC-MAN
</br>
Este repositorio cuenta con coommits y branches que fueron creados para realizar lo pedido en la actividad 3.

## Tabla de Contenidos
1. [Información General](#general-info)
2. [Collaboration](#collaboration)

## Información General
Para esta actividad se nos dio la tarea de modificar un juego de pacman, en donde se nos pedía realizar modificiación al tablero, así como hacer a los fantamas más inteligentes dentro del juego.

## Fantasmas más inteligentes (Chava27)
Para este reto fue importante analizar a fondo las funciones que controlar el comportamiento de los fantasmas a lo largo del juego, haciendo que estos permanezcan dentro de los pasillo y que no salgan del juego. Al hacer que los fantasmas fueran más rápido
en otro de los retos de esta actividad, pudimos observar que al multiplicar course por una constante k mayor a 1 en la función point.move(course*k), ocasionaba que el objeto, en este caso los fantasmas o pacman, obtuvieran mayor rapidez. 
</br>
</br>
Con esto en mente se nos ocurrio establecer una nueva condición dentro del código, donde cualquier fantasma al encontrarse ya sea en la misma posición en x o en y con pacman, estos tendrian un aumento de velocidad hasta que pacman estufiese fuera de su posición. Esto se puede observar en la línea 151, donde creamos la condición if con resultado de aumento en us velocidad con point.move(course*3) al igual que cambiar el color del fantasma a magenta. Esta nueva condición ocasiona que cuando algún fantasma se encuentre en cerca de pacman, este aumentará su velocidad y cambiará de color a magenta.
</br>
</br>

## Collaboration 
