---
published: true
categories: Level1
---
## Condicionales, tomando decisiones

Alguna vez en nuestras vidas hemos tomado decisiones, en la programación también se ejecutan decisiones y son conocidas como condicionales. Aprender las condicionales en programación es una de las cosas mas indispensables, ya que como son la toma de decisiones de forma lógica, permiten a nuestros programas ejecutar de una forma lógica.

En ruby, para poder ejecutar una condición, se utiliza el `if`, veamos como funciona:

<div class="activity"> 
 💻 Ejecuta el código debajo y logra entender como funciona el código.
</div>

<iframe src="https://paiza.io/projects/e/q6-hd6qVsJlztWkTnEtXFg?theme=twilight" width="100%" height="500" scrolling="no" seamless="seamless"></iframe>

Repasemos de nuevo lo que ha pasado en el bloque de arriba:

1.- Tenemos dos variables (x & y) a los cuales se les asigna un número cada uno.
2.- Después usamos el condicional `if` acompañado de nuestras dos variables.
3.- Si notaste, tenemos un `>` que indica **mayor que** (consulta la tabla de operadores aqui).
4.- Dentro de nuestro `if` tenemos un `puts "hola mundo"`, lo que indica que si **x**(30) es mayor a **y**(20) entonces se imprimirá en la consola “Hola mundo”.
5.- Siempre que se use una condicional se usa el `end` que indica que el `if` se cierra. Si no se coloca un `end` ruby tomará esto como error.


## Else, casos contrarios

¡Muy bien! El concepto de If ha quedado explicado, es bastante sencillo de entender estos conceptos. Ahora expliquemos el `else`. ¿Que es el `else`? Bueno tomando el ejemplo de las decisiones, a veces queremos tomar una decision contraria, es decir, un plan b. 

Veamos el siguiente ejemplo:

<img src="https://res.cloudinary.com/craftwebs/image/upload/v1583547905/Captura_de_pantalla_2020-03-06_a_la_s_20.22.08_suxn10.png">

<div class="activity"> 
 💻 Ejecuta el código debajo y logra entender como funciona el código.
</div>

<iframe src="https://paiza.io/projects/e/cw4U1uV8I3QGZyxFl2J9OQ?theme=twilight" width="100%" height="500" scrolling="no" seamless="seamless"></iframe>

Repasemos de nuevo lo que ha pasado en el bloque de arriba:

Tenemos dos variables, uno `veinte` y otro llamado `treinta`, ambos se les asigna un numero
Usamos nuestro `if` con la misma lógica del ejercicio arriba pero ahora tenemos dos `puts`
Si notaste, tenemos el `else` que solo se va a ejecutar si la primera condicional **no** se cumple
En consola, se imprime `”soy menor”`.