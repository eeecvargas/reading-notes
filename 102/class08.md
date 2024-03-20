# CLASE 08
### ¿Qué es una “expresión” en JavaScript?
    
    Básicamente una expresión es una pieza de código que genera un resultado.
    Hay dos tipos de expresiones: con efectos secundarios(ejem: x=7) , y las que en algún sentido evalúan y luego resuelven en base a un valor(ejem: 3+4, donde tenemos dos valores: 3 y 4).
    
    op=gral, exp=aplicado
    
    **Categorías de expresión:**
    
    Las **expresiones** usan **operadores**.
    
    - **Aritméticas**: 3.14159. Generalmente usa operadores aritméticos.
    - **Cadenas**: se evalúa como una cadena de caracteres, por ejemplo, "Fred" o "234". 
    - **Lógicas**: `true` o `false`. A menudo implica operadores lógicos.
    - **Expresiones** **primarias**: palabras clave básicas y expresiones generales en JavaScript: this, por ejemplo.
    ´´ Utiliza la palabra clave this para hacer referencia al objeto actual. En general, this se refiere al objeto que llama en un método. Usa this con la notación de punto o entre corchetes:
    
Supongamos que una función llamada validate valida la propiedad value de un objeto, dado el objeto y los valores alto y bajo:
function validate(obj, lowval, hival) {
  if (obj.value < lowval || obj.value > hival) {
    console.log("¡Valor no válido!");
  }
}
Puedes llamar a validate en el controlador de eventos onChange de cada elemento de formulario, utilizando this para pasarlo al elemento de formulario, como en el siguiente ejemplo:

HTML
Copy to Clipboard
<p>Ingresa un número entre 18 y 99:</p>
<input type="text" name="age" size="3" onChange="validate(this, 18, 99);" />´´
