# Variables Let y Ambito de Alcance

* Como declarar variables con let

* Concepto de Ambito: Zona donde pueden ser 
  accedidas las variables 

* Bloque de la funcion: Lo que se guarda entre las
  2 llaves de la funcion (Ambito Local)

* Ambito global: Todo lo que esta fuera del 
 bloque de las funciones (Todo lo que este dentro 
 del ambito global puede ser accedido desde cualquier
lugar)

var nombre = "Random"

function saludar() {
console.log("Hola " + nombre)
}

saludar() // "Hola Random"

* Todas las variables que declaramos dentro
  de una funcion solo pueden ser accedida dentro
  de esa funcion.

var nombre = "Juan"

function saludar() {
var nombre = "Andres" 
// Esta variable es invisible desde el ambito global
console.log("Hola " + nombre)
}

saludar()  // Hola Andres
