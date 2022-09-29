# Clase-29-09
# Integrantes:
 * Campero José
 * Campohermoso Oscar
 * Fernández-Dávila Sergio
 * Barroso Marino
 * Guachalla Sergio

#Todos los participantes participaron 

#Juego de Pong
- Se accede al DOM mediante " var canvas = document.getElementById('canvas');" 
- El primer event listener es para la tecla de espacio, esto inicia el juego ya que cambia el gameState a 1.
- La funcion input() compara si las teclas presionadas son la de arriba o abajo, mediante la comparación del código ASCII.
- La función del movePlayer2() es la lógica de la computadora comparando la posición en el eje Y dentro del canvas,la cual modifica su trayectoria en base a su posición límite hasta que termine el juego.
- La función Box() crea un objeto de la pelota.
- La función createNewBall() crea una nueva pelota, además de ubicarla en el centro del canvas.
- La función ballBounce() modifica la dirección y la gravedad de la pelota.
- Las funciones displayScore1() y displayScore2() muestra la puntuación en el canvas de ambos jugadores.
- La función draw() llama a todas las funciones de dibujo.
- La funciones drawStartMenu(), drawOverMenu() y drawWinMenu() dibujan los diferentes game states.
- La función resetPlayers() reinica la posición de ambos jugadores.
- La función init() inica el bucle del juego.
- La función loop() es bucle principal.


Link del juego original: https://codepen.io/tingriley/pen/ZEEVyjp
