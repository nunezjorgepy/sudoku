# sudoku
Intentaré recrear la página de Sudoku de Sven Neumann.

## Objetivos
El jugador tiene que colocar los números del 1 al 9 en cada fila, columna y sub-grilla de 3x3, sin repetirlos.

## Visibles
Al cargar la página, se verá una ventana centrada con las reglas del juego (se cerrará clickeando en el botón o fuera de la ventana).
Consta de una grilla de 3x3 (llamadas cajas o boxes), subdividida en sub-grillas de 3x3 (celdas o cells). Además se ve:
  - un pad con los números del 0 al 9 (llamada 'numberpad'), un boton de borrar, otros 3 para los distintos tipos de colocación de números, otro para los colores y otro para el pen tool;
  - otra división con las opciones de volver un paso atrás, volver uno adelante, verificar el resultado y marcar más de una celda;
  - otra división con las diferentes opciones;
  - las reglas del juego, visible en pantallas grandes;
  - Debajo de todo eso, un pequeño texto con el nombre del creador y su página web y patreon.

Arriba de todo se verá el header, con un menú "burguer", la opción "Play in SudokuPad" y un 'timer' bien a la derecha.

## Jugabilidad
- Cuando el jugador hace click en una celda, la misma tendrá un borde interno de color celeste y se le permitirá colocar un número (uno solo y SOLO un número).
- Podrá marcar más de una celda si esta activado el botón Select o si mantiene apretada la letra CTRL.
- Al presionar un número o en una de las casillas del numberpad, se escribirá el número en la casilla seleccionada. Si presiona la tecla borrar, se borrará el número ingresado en la casilla selecionada (de haber uno).
- Al clickear en la casilla 'check', se verifica si ganóa o si hay números mal anotados, mostrando un mensaje por pantalla (llamado 'check_window'), el cual puede dejar de mostrarse clickeando en un botón de la ventana o fuera de la misma.

## Funciones
De los botones:
  - Cada uno de los botones del 0 al 9 escribirá el número en la/s casilla/s seleccionada/s
  - 'Digit' permite entrar un número en la/s celda/s seleccionada/s
  - 'Corner' permite hacer el "corner-pencil-mark".
  - 'Centre' permite el "pencil-mark".
  - 'Color' permite cambiar el color de fondo de la/s celda/s seleccionada/s.
  
  - 'Undo' y 'Redo' volverá un paso atrás o adelante respectivamente.
  - 'Check' verifica si ganó o hay algo mal o que falta.
  - 'Select', estando activo, permite seleccionar más de una celda.

  - 'Settings' permite cambiar las opciones del juego. Se muestra en una ventana emergente.
  - 'FullScreen' permite ver el juego a pantalla completa.
  - 'Rules' abre la ventana emergente con las reglas del juego.
  - 'Info' permite ver los elementos de la ventana principal.
  - 'Restart' reinicia el juego y el contador (si el jugador lo quiere). Conviene ver la ventana que se abre al hacer clic ahí.
