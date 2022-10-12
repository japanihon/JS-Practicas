## Hoisting

QuokkaJs --> Para escribir directamente JS en VSCode

* Cuando una variable es declarada pero no es inicializada
es undefined 

* Se puede invocar una funcion antes de declararla

* JS busca en memoria primero las variables y funciones declaradas

* JS busca en memoria y ve que hay una variable declarada pero no inicializada,
es decir no tiene un valor asignado

1. console.log(nombre) // undefined

2. var nombre  // Declaracion

3. nombre = "Random" // Inicializacion

4. console.log(nombre) // Random
