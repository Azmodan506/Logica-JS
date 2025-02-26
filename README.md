# Logica-JS
Logica JavaScript


Dia 1

let numeroUn = '9'

let stringUn = '1'

let numeroVeinticinco = 25

let stringTreinta = '30'

let numeroDiez = 52

let stringDiez = '10'


if ( numeroUn == stringUn) {

  console.log('Las variables numeroUn y stringUn tienen el mismo valor, pero tipos diferentes')

} else {

  console.log('Las variables numeroUn y stringUn no tienen el mismo valor')

}



if (numeroVeinticinco === stringTreinta) {

  console.log('Las variables numeroTreinta y stringTreinta tienen el mismo valor y el mismo tipo')

} else {

  console.log('Las variables numeroTreinta y stringTreinta no tienen el mismo tipo')

}

 

if ( numeroDiez == stringDiez) {

  console.log('Las variables numeroDiez y stringDiez tienen el mismo valor, pero tipos diferentes')

} else {

  console.log('Las variables numeroDiez y stringDiez no tienen el mismo valor')

}

/////// Dia 2 /////

Dia 2

///
Las variables son los bloques básicos de construcción de cualquier sistema y son esenciales para procesar cualquier tipo de información, ya sea de una persona que ha iniciado sesión en el sistema o incluso para mostrar detalles de productos en un catálogo de comercio electrónico.

 

Por eso, hoy te voy a enseñar a desarrollar un programa simulando una de esas aplicaciones. Debe pedir al usuario responder 3 preguntas:

 

- ¿Cuál es tu nombre?
- ¿Cuántos años tienes?
- ¿Qué lenguaje de programación estás estudiando?

 

A medida que se hagan las preguntas, la persona que esté usando el programa debe responder cada una de ellas.

 

Al final, el sistema mostrará el mensaje:

 

"Hola [nombre], tienes [edad] años y ya estás aprendiendo [lenguaje]!"

Observa que cada información entre [ ] es una de las respuestas dadas por la persona.


///


let nombre = prompt('¿cual es tu nombre?')
let Edad = prompt('¿Cuántos años tienes?')
let Lenguaje= prompt('¿Qué lenguaje de programación estás estudiando?')

console.log(`Hola ${nombre}, tienes ${Edad} años y ya estás aprendiendo ${Lenguaje}!`);
