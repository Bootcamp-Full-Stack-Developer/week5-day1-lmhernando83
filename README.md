# Boream Scape Room!

A traves de esta práctica vamos a repasar todos
los conceptos aprendidos durante el prework.
Si te quedas atascado en algún punto, no dudes en volver a mirar la teoría 
buscar en internet información!

### Información Previa

En primer lugar debemos clonar este repositorio en nuestro equipo
para poder trabajar localmente con el código ya creado. 

Una vez tengamos el código en nuestro equipo, podemos ver 2 ficheros 
sobre los cuales vamos a trabajar: index.html y index.js. 

Ambos contienen algo de código base para el ejercicio, detente unos 
minutos a mirarlo, ya que te puede ayudar con las futuras iteraciones.

El objetivo de esta práctica es sacar a nuestro personaje del laberinto.
Puedes ir utilizando la consola del navegador para ver en que punto se 
encuentra el personaje en cada momento. 

Suerte y conseguid escapar!

### Iteración 1

Lo primero que debes hacer, es añadir en el fichero index.html el 
enlace con el fichero javascript, para que este se cargue al abrir el HTML.

Además, ya en el fichero Javascript puedes ver que tenemos un Objeto que
funcionara como personaje de nuestro Scape Room. Pero dicho personaje no 
tiene ninguna propiedad! Necesitamos que añadas las siguientes propiedades al personaje:

* Posicion: Sera un objeto que contiene dos claves x=4 e y=4.

### Iteración 2

La iteración uno ha sido sencilla! Sigamos con algo más complicado...
Necesitamos crear el mapa para del Scape Room! Para ello 
vamos a utilizar la función generateMap que ya hay creada, en ella,
debes crear un grid de 10x10. Dicho grid sera un array de dos dimensiones y debe tener
el valor 0 en todas sus celdas.

Tras crear el grid, debes modificarlo llamando a la función generateObstacles.
Dicha función modificara de manera aleatoria, ciertos valores de 0 cambiandolos
por 1 y funcionaran como los obstaculos del mapa.

Además, la salida del Scape Room sera la celda 0,0 y debe tener un valor S

## Iteración 3

Una vez hemos creado el mapa y le hemos añadido objetos, debemos comprobar el
movimiento del personaje. Para ello sigue los siguientes pasos:

Completa la función setInstructions y almacena el valor introducido por el usuario
en la variable moves.

Completa el método checkInstructions que debe recorrer la cadena introducida y 
llamar a los diferentes métodos de movimiento en función del valor de cada letra.

Completa las funciones moveNorth, moveSouth, moveEast y moveWest. Tienes completo el ejemplo para moveNorth.


## Iteration 4

Realiza comprobaciones, donde más te convenga, para saber si el personaje se ha 
encontrado un obstaculo. En caso de haber un obstaculo debes mostrar un mensaje
alert("") y el personaje debe permanecer en la última posición sin obstaculos.

## Iteration 5

Comprueba al final de las instrucciones si el personaje a encontrado la salida.

## Bonus 

¿Qué ocurre si el personaje se sale del grid? Realiza estas comprobaciones
y trata de manejar estos casos limites de la manera en que se te ocurra!


Mucha suerte y keep working!
