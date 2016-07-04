# buscaminas_gnp
Buscaminas python

Buscaminas basico en linea de comandos

Usando 
* POO (clase casilla)

La clase casilla tiene los metodos:
  * muestro: en la cual pongo * antes de activar la casilla
  * tengo: Si la clase es una bomba o no (1=bomba,  0=no_bomba)

No cambiar el valor de tengo... Si se quiere 'mostrar' el numero de bombas cercanas, jugar con la variable muestro

Metodos:
  * Crea_arreglo: Crea un arreglo de casillas
  * llena_arreglo: llena el atributo tengo de cada casilla
  * pregunto: Pregunto el numero en X y en Y de la casilla que quiere activar. 
     <b> Ve si las coordenadas X y Y estan correctamente validadas</b>
  * Comparo: Activo la casilla que piden. 
      <b>X[b|,|.]Y-> Si no digitan b y hay una bomba, pierden el juego</b>
  * Muestra_arreglo: Muestro las diferentes pantallas
      <b>Piso bomba</b>
      <b>Indicaciones</b>
      <b>Ganar...</b>
      <b>Perder...</b>
      
