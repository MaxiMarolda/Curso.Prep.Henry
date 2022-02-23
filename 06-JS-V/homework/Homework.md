# Homework: Javascript V

## Instrucciones
---
1. En un archivo de texto separado que debes crear, escribe explicaciones de los siguientes conceptos como si se lo estuvieras explicando a un niño de 12 años. Hacer esto te ayudará a descubrir rápidamente cualquier agujero en tu comprensión.

* `prototype`
* _Constructors_ (de Clases)

2. Desde la carpeta `Prep` en la carpeta donde clonaste el repo, ingresa el comando `npm test JSV.test.js` para correr los tests automatizados. Al principio, todos los tests estarán fallados/rotos. Encontrarás las funciones para hacer pasar los tests en el archivo `homework.js`.

### Aca tendras acceso a las [Soluciones](https://github.com/atralice/Curso.Prep.Henry/blob/solution/06-JS-V/homework/homework.js)

## Solución

### * `prototype` 
-- Es un concepto que permite crear elementos (funciones) que "derivan" o "Heredan" funciones a todos los elementos de su misma clase. Es decir que permite crear objetos que aunque no tengan todas las funciones definidas, van a poder invocar la funciones "metodos" definidos en el propotipo del cual derivan. Esto permite crear software mas liviano y escalable ya que no hace falta repetir la misma función para cada objeto creado de una misma "clase".

### * _Constructors_ (de clases)
Es una pieza de código que permite crear multiples instancias de objetos iguales, derivadas se un mismo prototipo. Por ejemplo si creo un Constructor de autos, voy a poder crear todos los Autos que quiera y todos van a ser exactamente igual en sus propiedades y van a heredar las mismas funciones/metodos.