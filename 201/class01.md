#   Este tema es importante porque me ayuda a comprender no solo la estructura y visualización de una página web sino además la comunicación entre otros agentes participantes encargados de llevar la información de manera clara y concisa. Se relaciona con el módulo ya que revisaremos mayor documentación relacionada a páginas web.


# Poema corto
# Cómo http envía datos entre computadoras
+ http es el idioma*
+ Lo hace como un mensajero que lleva cartas de ida y vuelta entre dos personas que viven en diferentes casas.
+  1. el navegador: "navo" va a la casa de direcciones "denese" y encuentra la drección real de la casa(el servidor) donde el sitio web "websito" vive.

+ 2. navo envía una petición http a la casa pidiendole que le de una copia de websito para un cliente, este mensaje y todos los dempas datos enviados o intercambiados entre el cliente y la casa se nvían a través de conexion a internet usando tcp/ip(?)

+ 3. si la casa aprueba la solicitud del cliente, la casa le enviará un mensaje de confirmación: 200 OK, y así enviará los archivos de websito a navo mediante paquetes que contendrán datos. 
+ 4. navo reune los paquetes y con eso forma un sitio web completo y te lo muestra y da, tú feliz con la copia de websito :)

+ 5. El mensajero
+    hola denese, te saluda navo
+    ¿sabes dónde está websito?
+    soy el amo de las direcciones, ¿por qué no lo sabría?, replicó denese
+    y con la dirección revelada
+    navo llama a la casa dubitativo
+    la casa le dio el sí y envía los paquetes llenos de datos
+    navo apurado exclama: ¡tantos paquetes, pero yo satisfecho!
+    el cliente abre su puerta: gracias navo, ¡qué haría sin tu garbo!

#   Cómo los archivos HTML, CSS y JS son “analizados” en el navegador

+    Los clasifica de acuerdo a su estructura, el navegador navo lee el archivo html línea por línea y crea a partir de eso un mapa, un árbol de elementos que representa la estructura y contenido de la página. Después navo se centra en buscar los archivos css contenidos en la página web, los lee y los incorpora a sus estructura previa. finalmente, el navegador navo analiza los archivos javascript vinculados a la página, este último pudiendo manipular el árbol de elementos, entre otras cosas que le agregan esa interacción a la página web.


#   ¿Cómo puedes encontrar imágenes para agregar a una página web?

+      Existen varias formas, por ejemplo, una de ellas es usando google images con la función de búsqeuda avanzada, donde al seleccionar las opciones "reutilización con modificaciones" o "reutilización no comercial" puedes usar esas imágenes de manera legal.

#    ¿Cómo creas una String en comparación con un Number en Javascript?

+   Para crear un string asignas el valor de la variable representado en letras mediante comillas simples o dobles, para un número no es necesario usarlas.

#   ¿Qué es una Variable y por qué son importantes en JavaScript?
+  una variable es la caja simbólica que almacena determinados datos o valores diversos: números, letras, elementos de verdad(booleanos), etc. nos importa porque a partir de ellos podemos desarrollar páginas web bien estrucutradas y sobretodo interactivas. + datos útiles + dinamismo + interacción con el cliente

# INTRODUCCIÓN A HTML

## 1. ¿Qué es un atributo en html?
+  Es como el adjetivos del sustantivo(elemento), por ejemplo el atribto href se usa en la etiqueta '<a>' para especificar la url a la que debe dirigirse el enlace.
## 2. Describe la anatomía de un elemento en HTML.
+   Consta de una etiqueta de APERTURA, CONTENIDO y una etiqueta de CIERRE.
## 3. ¿Cuál es la diferencia entre las etiquetas <article> y <section>?
+   article es para contenido independiente, mientras que section para agrupar contenido de un relacionado con un mismo tema dentro de una página.
## 4. Qué elementos se incluyen en una página web “típica”?
+   generalmente la página web contendrá elementos como encabezados, navegación, contenido principal, secciones, articulos, pies de pa´gina, entre otros. (header, nav, main, section, article, footer,...)
## 5. ¿Cómo influyen los metadatos en el Posicionamiento en buscadores (SEO)?
+   los metadatos dan info de una página web a los motores de búsqueda, estos últimos utilizan esta info para determinar qué tan relevante es la página web y asignar su posición (al inicio, en el medio o al final) en los resultados de búsqueda.

## 6. ¿Cómo se utliza la etiqueta <meta> en HTML cuando se quiere especificar metadatos?

+   Esta pregunta es interesante. 
La etiqueta <meta> se utiliza en la sección <head> de un documento HTML para proporcionar metadatos sobre la página. Por ejemplo, <meta name="description" content="Descripción de la página"> se utiliza para especificar la descripción de la página, que los motores de búsqueda PUEDEN MOSTRAR en los resultados de búsqueda. (extraído de "https://...") O, sea es como motores de búsqueda - friendly. Mayor exposición.



# Miscelánea

## Cómo empiezo a diseñar mi sitio web
+ 1.    Primer paso para diseñar una página web: Tener claro lo que se quiere lograr, tener un objetivo y una visión.

+ 2.    ¿Cuál es la pregunta más importante que se debe responder al diseñar una página web?
+       ¿Qué es exactamente lo que quiero lograr?
+       ¿Cómo un sitio web me ayudará a alcanzar mis metas?
+       ¿Qué es necesario hacer, y en qué orden, para alcanzar mis metas? *[útil](https://developer.mozilla.org/es/docs/Learn/Common_questions/Design_and_accessibility/Thinking_before_coding)*

## Semántica
+ 1. ¿Por qué se debe utilizar un elemento <h1> en vez de un <span> para mostrar un título de primer nivel?
+    El <h1> es como el megáfono que grita "¡Este es el título principal!". Ayuda a los motores de búsqueda y a las personas a entender de qué trata tu ensayo y qué es lo más importante. En cambio, <span> es más como una simple caja de texto sin ningún significado especial. Puedes ponerle texto, pero no comunica de manera clara que es el título principal. (cht) lo que repercute en los motores de búsqueda, entre otros efectos.


+ 2. ¿Cuáles son los beneficios de utilizar etiquetas semánticas en nuestro HTML?
+   claridad, son como señales de transito; mejora la posición en resultados de búsqueda, accesibilidad, dado que guarda un orden más personas pueden entender el contenido, etc. Usa etiquetas semánticas sigue las reglas de la "carretera" de la web.


## ¿Qué es Javascript?

### 2 cosas que requieren Javascript en el navegador 

+   La validación de formularios----> puede asegurarse de que hayas completado todos los campos obligatorios y que la dirección de correo electrónico sea válida.
+   Interacciones de usuario----->JavaScript permite crear interacciones dinámicas en una página web, como mostrar u ocultar contenido, animar elementos, cambiar imágenes al pasar el cursor sobre ellas, entre otras cosas que le aportan dinamismo :)

### Cómo añadir JavaScript a un documento en HTML

+ Abrimos el doc html
+ encuentra el lugar idóneo para agregar e javascript: por ejemplo, en la sección head o usto antes de cerrar la etiqueta body.
+ agrega la etiqueta script:`<script src="script.js"></script>` , script.js sería el nombre del doc.
+ ahora sí lo enlazamos, guarda los cambios en el doc html y verás el efecto! ;)




