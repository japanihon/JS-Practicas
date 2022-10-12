## Default Values


function saludar(nombre, apellido = "Perez" ) {
console.log("Soy " + nombre + " " + apellido );
}

saludar("Juan") // Soy Juan Perez


-------- Otro Ejemplo ---------------------------------

function saludar(nombre, apellido) {
if (nombre === undefined) {
  nombre = "Juan" 
}
if (apellido === undefined) {
apellido = "Perez" 
}

console.log(`Soy ${nombre} ${apellido}`)

}

saludar()

Resultado:

Soy Juan Perez

// Se asignan esas 2 variables por defecto //

-------- Otro Ejemplo ---------------------------------


function saludar(nombre = "Juan", apellido = "Perez" ) {
console.log("Soy " + nombre + " " + apellido);
}

saludar(undefined, "Montoto") // Soy Juan Montoto

// Pasa el primer valor como por defecto y el segundo es asignado por
 nosotros //
