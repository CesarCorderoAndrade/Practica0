Encabezados.
Agregue signos de número ( #) antes de una palabra o frase para cambiar el tamaño.
### Hola.   

Sintaxis alternativa
Alternativamente, en la línea debajo del texto, agregue cualquier cantidad de ==caracteres para el nivel de encabezado 1 o --caracteres para el nivel de encabezado 2.
== Hola
-- Hola   

Prácticas recomendadas para encabezados.
Colocar un espacio entre los signos de número y el nombre del encabezado.
Colocar líneas en blanco antes y después de un encabezado para mayor compatibilidad.  

Párrafos.
Para crear párrafos, utilice una línea en blanco para separar una o más líneas de texto.  

Saltos de línea
Para crear un salto de línea o una nueva línea ( <br>), finalice una línea con dos o más espacios y luego presione Enter.
Para mayor compatibilidad, utilice espacios en blanco finales o la <br>etiqueta HTML al final de la línea.  

Énfasis
Puedes agregar énfasis poniendo el texto en negrita o cursiva.  

Negrita
Para poner en negrita un texto, agregue dos asteriscos antes y después de una palabra o frase. Para poner en negrita la mitad de una palabra para enfatizarla, agregue dos asteriscos sin espacios alrededor de las letras.
**Ejemplo**
Esto es **un** ejemplo.  

Cursiva
Para poner un texto en cursiva, agregue un asterisco antes y después de una palabra o frase.
*Ejemplo*
Esto es *un* ejemplo. 

Negrita y cursiva
agregue tres asteriscos.
***Ejemplo***
Esto es ***un*** ejemplo.  


Citas en bloque
Para crear una cita en bloque, agregue una >antes de un párrafo.
>Ejemplo.
Citas en bloque con varios párrafos
Las citas en bloque pueden contener varios párrafos. Agregue una >en las líneas en blanco entre los párrafos.
>Ejemplo
>Ejemplo
>Ejemplo


Citas en bloque anidadas
Las citas en bloque se pueden anidar. Agregue un signo >>antes del párrafo que desea anidar.
>>Ejemplo
>
>>Ejemplo

Podemos combinar todo lo visto hasta ahora.
>##Ejemplo
>
>-Ejemplo
>
>**Ejemplo** *ejemplo*


Listas ordenadas
Para crear una lista ordenada, agregue elementos de línea con números seguidos de puntos.  


Listas desordenadas
Para crear una lista desordenada, agregue guiones ( -), asteriscos ( *) o signos más ( +) delante de los elementos de línea. Aplique sangría a uno o más elementos para crear una lista anidada.  
Si necesita comenzar un elemento de lista desordenada con un número seguido de un punto, puede usar una barra invertida ( \) para escapar del punto.  

Agregar elementos en listas
Para agregar otro elemento a una lista preservando la continuidad de la lista, sangre el elemento cuatro espacios o una tabulación, como se muestra en los siguientes ejemplos.  
Bloques de código
Los bloques de código suelen tener una sangría de cuatro espacios o una tabulación. Cuando están en una lista, se les aplica una sangría de ocho espacios o dos tabulaciones.  


Imágenes.
Para insertar imágenes se pone ![nombre de la imagen](dirección de la imagen)  
Podemos poner el titulo entre comillas despues de la URL.


![Pro](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSOI8Tcm49SjyeMvrB7J7QydOMvQ5MmKpRitg&s)  


Código
Para ver fragmentos de código usaremos comillas simples. Por ejemplo:

  `int a = 3;`  
  Si la palabra o frase que desea indicar como código incluye una o más comillas invertidas, puede escaparla encerrando la palabra o frase entre comillas invertidas dobles ( ``).  

  Bloques de código
Para crear bloques de código, sangre cada línea del bloque con al menos cuatro espacios o una tabulación.  

  
Reglas horizontales
Para crear una regla horizontal, utilice tres o más asteriscos ( ***), guiones ( ---) o guiones bajos ( ___) en una línea por separado.  

Para crear un enlace, encierre el texto del enlace entre corchetes (por ejemplo, [Duck Duck Go]) y luego siga inmediatamente con la URL entre paréntesis (por ejemplo, (https://duckduckgo.com)).  
Navegador favorito [Duck Duck Go](https://duckduckgo.com).  


Añadiendo títulos
Opcionalmente, puedes agregar un título a un enlace. Este aparecerá como información sobre herramientas cuando el usuario pase el cursor sobre el enlace. Para agregar un título, escríbalo entre comillas después de la URL.  

URL y direcciones de correo electrónico
Para convertir rápidamente una URL o dirección de correo electrónico en un enlace, enciérrelo entre corchetes angulares.

<https://www.markdownguide.org>
<fake@example.com>  

Formato de enlaces:
Para enfatizar los enlaces, agregue asteriscos antes y después de los corchetes y paréntesis. Para indicar que los enlaces son código , agregue comillas invertidas en los corchetes.

I love supporting the **[EFF](https://eff.org)**.
This is the *[Markdown Guide](https://www.markdownguide.org)*.
See the section on [`code`](#code).


Enlaces de estilo de referencia
Los enlaces de estilo de referencia son un tipo especial de enlace que facilita la visualización y lectura de las URL en Markdown. Los enlaces de estilo de referencia se construyen en dos partes: la parte que se mantiene en línea con el texto y la parte que se almacena en otro lugar del archivo para que el texto sea fácil de leer.

Cómo formatear la primera parte del enlace
La primera parte de un vínculo de estilo de referencia se formatea con dos conjuntos de corchetes. El primer conjunto de corchetes rodea el texto que debe aparecer vinculado. El segundo conjunto de corchetes muestra una etiqueta que se utiliza para señalar el vínculo que está almacenando en otra parte del documento.

Aunque no es obligatorio, puedes incluir un espacio entre el primer y el segundo par de corchetes. La etiqueta del segundo par de corchetes no distingue entre mayúsculas y minúsculas y puede incluir letras, números, espacios o signos de puntuación.

Esto significa que los siguientes formatos de ejemplo son aproximadamente equivalentes para la primera parte del enlace:

[hobbit-hole][1]
[hobbit-hole] [1]
Formateo de la segunda parte del enlace
La segunda parte de un enlace de estilo de referencia está formateada con los siguientes atributos:

La etiqueta, entre paréntesis, seguida inmediatamente de dos puntos y al menos un espacio (por ejemplo, [label]: ).
La URL del enlace, que opcionalmente puedes incluir entre corchetes angulares.
El título opcional para el enlace, que puede incluir entre comillas dobles, comillas simples o paréntesis.
Esto significa que los siguientes formatos de ejemplo son aproximadamente equivalentes para la segunda parte del enlace:

[1]: https://en.wikipedia.org/wiki/Hobbit#Lifestyle
[1]: https://en.wikipedia.org/wiki/Hobbit#Lifestyle "Hobbit lifestyles"
[1]: https://en.wikipedia.org/wiki/Hobbit#Lifestyle 'Hobbit lifestyles'
[1]: https://en.wikipedia.org/wiki/Hobbit#Lifestyle (Hobbit lifestyles)
[1]: <https://en.wikipedia.org/wiki/Hobbit#Lifestyle> "Hobbit lifestyles"
[1]: <https://en.wikipedia.org/wiki/Hobbit#Lifestyle> 'Hobbit lifestyles'
[1]: <https://en.wikipedia.org/wiki/Hobbit#Lifestyle> (Hobbit lifestyles)
Puedes colocar esta segunda parte del enlace en cualquier parte de tu documento Markdown. Algunas personas las colocan inmediatamente después del párrafo en el que aparecen, mientras que otras las colocan al final del documento (como notas finales o notas a pie de página).

Un ejemplo de cómo juntar las piezas
Digamos que agrega una URL como un enlace URL estándar a un párrafo y se ve así en Markdown:

In a hole in the ground there lived a hobbit. Not a nasty, dirty, wet hole, filled with the ends
of worms and an oozy smell, nor yet a dry, bare, sandy hole with nothing in it to sit down on or to
eat: it was a [hobbit-hole](https://en.wikipedia.org/wiki/Hobbit#Lifestyle "Hobbit lifestyles"), and that means comfort.
Aunque puede indicar información adicional interesante, la URL que se muestra en realidad no agrega mucho al texto sin formato existente, más allá de dificultar la lectura. Para solucionar esto, puede formatear la URL de esta manera:

In a hole in the ground there lived a hobbit. Not a nasty, dirty, wet hole, filled with the ends
of worms and an oozy smell, nor yet a dry, bare, sandy hole with nothing in it to sit down on or to
eat: it was a [hobbit-hole][1], and that means comfort.

[1]: <https://en.wikipedia.org/wiki/Hobbit#Lifestyle> "Hobbit lifestyles"
En ambos casos anteriores, el resultado generado sería idéntico:

En un agujero en el suelo vivía un hobbit. No era un agujero sucio, húmedo y desagradable, lleno de restos de gusanos y con un olor fétido, ni tampoco un agujero seco, vacío y arenoso en el que no había nada en lo que sentarse ni comer: era un agujero de hobbit , y eso significa comodidad.

y el HTML para el enlace sería:

<a href="https://en.wikipedia.org/wiki/Hobbit#Lifestyle" title="Hobbit lifestyles">hobbit-hole</a>  

HTML
tambien podemos usar formato HTML al escribir. En algunas versiones solo se puede usar un subconjunto de etiquetas HTML.  

Hacer tablas :
Puede crear tablas con canalizaciones | y guiones -. Los guiones se usan para crear cada encabezado de columna, mientras que las barras verticales separan cada columna. Debes incluir una línea en blanco antes de tu tabla para que se representen correctamente.
| First Header  | Second Header |
| ------------- | ------------- |
| Content Cell  | Content Cell  |
| Content Cell  | Content Cell  |  

Las barras verticales en cada lado de la tabla son opcionales.

Las celdas pueden variar en el ancho y no es necesario que estén perfectamente alineadas dentro de las columnas. Debe haber al menos tres guiones en cada columna de la línea de encabezamiento.
| Command | Description |
| --- | --- |
| git status | List all new or modified files |
| git diff | Show file differences that haven't been staged |  

Puede alinear el texto a la izquierda, a la derecha o en el centro de una columna al incluir dos puntos : a la izquierda, a la derecha o a ambos lados de los guiones en la línea de encabezamiento.
| Left-aligned | Center-aligned | Right-aligned |
| :---         |     :---:      |          ---: |
| git status   | git status     | git status    |
| git diff     | git diff       | git diff      |  

Para incluir una barra vertical | como contenido en su celda, utilice una \ antes de la barra vertical:
| Name     | Character |
| ---      | ---       |
| Backtick | `         |
| Pipe     | \|        |  

























Biografia:
https://www.markdownguide.org/basic-syntax/#heading-best-practices
https://docs.github.com/es/get-started/writing-on-github/working-with-advanced-formatting/organizing-information-with-tables
