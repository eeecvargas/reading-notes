 ## CLASE 07
### ¿Qué es “Control Flow” (Control de Flujo)?

Básicamente el orden en el que la computadora o el programa ejecuta las declaraciones en un script. Pienso, por ejemplo, cuando declararmos variables, podemos asignar un valor a una varibale, pero si en la línea siguiente asignamos otro valor a la misma variable, al momento de mostrar en consola o imprimir el valor actual de la variable nos mostrará el último valor asignado, entonces el programa obedece un orden. Luego, si por ejemplo usamos condicionales sucede que lo que se va a imprimir resulta de la lectura de las condiciones, un recorrido de lo primero hacia lo último que satisface la condición, es un orden para validar el flujo de operaciones antes del resultado. Control de flujo. 
    
#### Más que leer y mostrar el resultado de frente, se hace un análisis de las condiciones requeridas y después de ese proceso recién se imprime validando las condiciones. UN ANÁLISIS (+ detallado) PREVIA EJECUCIÓN.#### 
    
##### Con unas pocas líneas de código puedes recorrer varías condiciones = controlar un “gran” flujo de información antes de ejecutar el resultado.
    
El flujo de control significa que cuando lees un script, no solo debes leer de principio a fin, sino también **observar la estructura del programa** y **cómo afecta el orden de ejecución**.


--------------

## ¿Qué es una “function” (Función) de JavaScript? 
    Una operación adaptada a un elemento de código. En JavaScript, una función es un bloque de código reutilizable que se utiliza para realizar una tarea específica. Las funciones suelen calcular un valor de retorno. Como vemos en este ejemplo: <script>
let x = mifuncion(4, 3);
 

function mifuncion(a, b) {
  return a * b;
}
document.write(x); 
document.getElementById("demo").innerHTML = x;
</script>

-----

## ¿Qué significa “invoke” o “call” en una función?
Llamar a la función. Cuando invocas o llamas a una función en JavaScript, el código dentro de la función se ejecuta y cualquier resultado se produce según lo definido en la función. Puedes crear tu función y luego reutilizarla en el código en vez de escribir paso a paso la operación que realiza cada vez que la necesites. Es más fácil y ordenado trabajar así.

-----

## ¿Para qué sirven los paréntesis () cuando defines una función?
Cuando defines una función, los “()” llaman a la función y hace que la aplican de acuerdo al valor dentro del paréntesis. Y si, por ejemplo, no se coloca nada dentro de los paréntesis, lo que devolverá será la misma función, o sea, cómo se definió esta, más no el resultado. 

###### [Aquí puedes ver cómo llamar a una función](https://scaler.com/topics/images/structure-of-a-javascript-function.webp)
