# PW

Square:  representa un cuadrado individual en el tablero de juego
Value: representa el valor del cuadrado, que puede ser 'X', 'O' o null
onSquareClick:es una función que se llama cuando se hace clic en el cuadrado

Board: tablero de juego y contiene nueve componentes Square
xIsNext:  booleano que determina cuál jugador es el siguiente en jugar, 'X' o 'O'
squares: matriz de 9 elementos que representa el estado actual del tablero
onPlay: función que se llama cuando se hace clic en un cuadrado, actualizando el estado del tablero

Game: componente principal que contiene el estado del juego y los otros dos componentes
useState: almacenar el historial de movimientos y el movimiento actual
handlePlay, jumpTo: se realiza un movimiento o cuando se hace clic en un botón de historial de movimiento

calculateWinner: función auxiliar que determina si hay un ganador en el juego actual. Recibe como entrada una matriz de 9 elementos que representa el estado actual del tablero y devuelve el valor del jugador ganador ('X' o 'O') o null si no hay un ganador.