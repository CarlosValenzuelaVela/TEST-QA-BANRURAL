Error 1
Descripciòn
El numero random debe de ser dentro del 1 al 100 y en la funciòn math.random esta para 10 numeros
Soluciòn
Se debe de cambiar para 100 numeros.
let randomNumber = Math.floor(Math.random() * 100) + 1;

Error 2
Descripciòn
El numero de intentos que se tiene en la constante son 5 la cual es ATTEMPS
Soluciòn
eliminar la constante y en la condicion eliminar la constante y colocar el numero de intentos la cual es 10
else if (guessCount === 10)

Error 3
Descripciòn
No existe funcion que valide si el numero ingresado es entero 
Soluciòn
Agregar funcion que valide si el numero ingresado es entero o decimal y si es debe mostrarse una alerta al usuario y no se debe incrementar un intento de prueba.
if ( Number.isInteger(userGuess))

Error 4
Descripciòn
La condicion que si el numero ingresado y el numero random son iguales, la condiciòn imprime que perdio y no es asi.
Soluciòn
Se debe de cambiar lo que imprime y cambiar el color.
if (userGuess === randomNumber) {
          lastResult.textContent = 'Felicitaciones! adivinaste el número!';
          lastResult.style.backgroundColor = 'green';
          lowOrHi.textContent = '';
          
Error 5
Descripciòn
La condicion que alcanzaba el limite de intentos imprime que se ha adivinado el numero pero es lo contrario.
Soluciòn
else if (guessCount === 10) {
          lastResult.textContent = '!!!Pérdistes!!!';
          lowOrHi.textContent = '';
          setGameOver();
          
