## Const

Var y Let son dinamicas porque se les pueden
asignar nuevos valores

Const crea una asociacion constante (fija)

Const nos asegura que no se reasignara valor
a esa variable.

Si podemos mutar propiedades del valor
asociado a la constante

const persona = { nombre: "Juan" }

persona = { nombre: "Andres" } 

console.log(persona.nombre) 
// Error de asignamiento

Nota: Pero si puedo cambiar la propiedad del valor asociado a la constante

const persona = { nombre: "Random" }

persona.nombre = "Andres"  

console.log(persona.nombre)  // Andres

+ El OBJETO sigue siendo el mismo, lo que se muta es una propiedad del mismo

+ Const y Let no son alzadas, no se pueden
 acceder antes de la inicializacion
