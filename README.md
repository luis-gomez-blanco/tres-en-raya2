# Tres en raya

Objetivo: Desarrollar el juego del Tres en Raya (Tic-Tac-Toe) en PHP. El juego permitirá a dos jugadores competir en un tablero 3x3, tratando de ser los primeros en alinear tres de sus fichas en fila, columna o diagonal.

Instrucciones:

  1. Crea un programa en PHP que permita a dos jugadores jugar al "Tres en Raya".
  2. Diseña un tablero de juego de 3x3 en el que los jugadores puedan realizar sus movimientos. Puedes emplear recursos gráficos si así lo deseas.
  3. El programa comenzará preguntando el nombre de los dos jugadores.
  4. A continuación, el juego debe mostrar el tablero vacío, donde cada casilla elegible debe ser un botón para que los jugadores ingresen sus movimientos de manera más sencilla.
  5. Seguidamente, se desarrolla el juego donde los jugadores irán alternando sus movimientos. El jugador 1 usará "X", mientras que el jugador 2 usará "O".
  6. Tras cada movimiento, el programa debe actualizar el tablero y mostrarlo por pantalla, para que los jugadores vean el estado actual del juego.
  7. El juego debe verificar en cada turno si alguno de los jugadores ha ganado al alinear tres de sus fichas en fila, columna o diagonal. En ese caso, el juego debe declarar al jugador ganador y terminar.
  8. Si el tablero se llena y ningún jugador ha ganado, el juego debe declarar un empate y terminar.
  9. Si un jugador intenta realizar un movimiento en una casilla ya ocupada, el programa debe mostrar un mensaje de error y permitir que el jugador realice otro movimiento.

  Bonus: Desarrollar un marcador que permita acumular puntos a cada jugador en sucesivas rondas. Al terminar la partida, se preguntará si desean competir otra vez. En caso positivo se irán acumulando las victorias, mientras que una respuesta negativa reiniciará los marcadores a la espera de un nuevo juego.

Requisitos: Se deben emplear matrices o listas para la representación del tablero del juego. Una posible representación del tablero podría ser esta:

[0,1,2]      [0,1,2]      [O,1,2]      [O,1,2]
[3,4,5]  --> [3,X,5]  --> [3,X,5]  --> [3,X,X] ...
[6,7,8]      [6,7,8]      [6,7,8]      [6,7,8]

Asegúrate de que el programa sea claro y fácil de entender, utilizando comentarios para explicar la lógica de tu código.
