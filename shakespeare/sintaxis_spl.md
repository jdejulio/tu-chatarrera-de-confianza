# Sintaxis para un buen teatro Shakespeariano
### Estructura
#### Título
Toda buena obra comienza con un título (nos aporta una idea general sobre lo que irá el programa). Todo lo que precede al primer punto **.** es el título. Su inclusión es **obligatoria**.

#### Lista de personajes
Los personajes sirven para **declarar variables**. Se debe usar un personaje Shakespeariano. 
```
Nombre, descripción
```
Ejemplo: 
```
Romeo, an extremely faithful lover
```
El compilador tomará a Romeo como una variable capaz de guardar un valor integer. 

#### Actos y Escenas
La obra está dividida en Actos, que a su vez son divididos en Escenas.
Sintaxis:
```
ACT número romano: descripción
```
```
SCENE número romano: descripción
```
Ejemplo:
```
ACT I: Romeo and Juliet express their feelings.
Scene III: Romeo's declaration.
```
#### Enter, Exit, Exeunt
Los personajes pueden entrar y abandonar el escenario. Un personaje en escenario puede hablarle a otro personaje en escenario, y otros personajes pueden entrar utilizando el constructo **Enter**. 
Los personajes pueden abandonar la escena utilizando el constructo **Exis**. El plural de Exit es **Exeunt** (utilizado sin más añadidos, hace que todos los personajes abandonen el escenario).
Cuando hay dos personajes en escena, el uso de "You" no será ambiguo. 

#### Frases
Las escenas están divididas en frases, puesto que los personajes en escena hablan entre ellos. 
Sintaxis:
```
Personaje: frases.
```
#### Constantes
Un sustantivo es una constante. 
Si el sustantivo es agradable, p. ejemplo, "flower" o neutro como "tree", su valor = 1.
Si es desagradable, como "pig" su valor = -1.
Si al sustantivo le precede un adjetivo, lo multiplica por 2. P. ejemplo:
* "beautiful flower" = 2 * 1
* "fat dirty pig" = 2 * 2 * (-1)

#### Operadores binarios (y unitarios)

* Suma: "the sum of X and Y"
* Resta: "the difference between"
* Multiplicación: "the product of"
* División (integer): "the quotient between"
* Resto división: "the remainder of the quotient between"
* Cubo: "the cube of"
* Factorial: "the factorial of"
* Cuadrado: "the square of"
* Raíz cuadrada: "the square root of"
* Múltiplo de dos: "twice"

Ejemplo: 
```
the sum of the difference between a big mighty proud kingdom and a horse and your golden hair
```
Se traducirá como:
```
the sum of the difference between (2*2*2) and 1 and 2
```
Que al final resulta:
```
8 - 1 + 2 = 7 + 2 = 9
```

#### Asignar valores

Las variables anteriores se pueden asignar a los personajes que están en escena. Por ejemplo
```
You stupid fatherless coward!
```
El compilador asigna el valor de -4 al personaje al que se está dirigiendo. 
Con el constructo "as adjective as" también se pueden hacer asignaciones. Por ejemplo:
```
You are as good as a beautiful red rose.
```
Esto haría que el compilador asignase el valor 4 al pesonaje al que se están dirigiendo. También se pueden hacer asignaciones utilizando los operadores binarios y unitarios. 
```
You are as prompt as the difference between the square of thyself and your golden hair.
```
La expresión "square of thyself" hace que el compilador calcule el cuadrado del valor asignado al personaje al que se habla. 

#### Salida
"Open your heart" hace que el personaje al que se le habla muestre por salida su valor numérico.
"Speak your mind" hace que el personaje al que se le habla muestre por salida su valor en caracter.

#### Entrada
"Listen to your heart" para leer un número.
"Open your mind" para leer un caracter.
El valor será asignado al personaje al que se está dirigiendo.

#### Goto
Las escenas y los actos actúan como etiquetas, así que los saltos son posibles. No es posible saltar a una escena en un acto diferente. La sintaxis sería:
```
Let us return to scene I.
```
También se puede decir "We shall" o "We must" y en vez de return decir "proceed"

#### Condicionales


