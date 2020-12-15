+++
title = "Condicionales"
weight = 7
+++

{{< youtube aZIxWia_yZA >}}

## Contenido

Hasta ahora solo he abierto el editor de Scratch, voy a cerrar la ventana de tutoriales. Como siempre voy a ir a **Eventos**, agregar el evento de siempre, de la bandera, y voy a ir a **Control**.

En **Control** vamos a tener varios bloques que podemos usar, pero los que voy a mostrar ahora son el de **Si** y **Si – Si No**. Pueden ver que adentro de este bloque tengo la opción de poner más bloques adentro. Pero también puedo poner un bloque puntiagudo aquí, como los Booleanos, el de Verdadero y Falso. Pueden leer esto como si fuese una frase de verdad. Si es que esto es verdad hago esto, en cambio aquí estoy diciendo: Si es que esto es verdad, hago esto, o si no, hago lo otro.

Vamos a poner un ejemplo, voy a ir a **Operadores** y voy a coger un operador Booleano, por ejemplo, el de igualdad. Por ejemplo, aquí, si el 50 es 50 entonces todo lo que está dentro de aquí se va a ejecutar. Voy a poner esto aquí adentro y voy a poner algo que me muestre que sí está ejecutando, por ejemplo, voy a ir a **Apariencia** a **Decir Algo por 2 Segundos** y voy a decir “50 es igual a 50”. Si le doy a **Play** veo que el gato dice “50 es igual a 50”.

Pero que tal si yo cambio esto para que no sea verdadero, por ejemplo, 13 es igual a 50. Como 13 no es igual a 50, al momento de ejecutar veo que el gato no dice nada. Entonces al momento de utilizar esto, solo si es que la condición que está aquí es real, es verdadero, entonces se ejecuta lo que está adentro. Si no es así, entonces salta. Por ejemplo, voy a poner algo aquí que diga “Terminé” y veo que solo dice “Terminé”, no dijo “50 es igual a 50”.

Entonces aquí entre el otro bloque, por ejemplo, el **Si con Si No**, voy a arrastrar este mismo de aquí, lo voy a poner acá, y voy a decir que “50 es igual a 50” por 2 segundos o que diga otra cosa “13 no es igual a 50”. Voy a volver a poner el “Terminé” aquí debajo, le pongo **Play** y dice “13 no es igual a 50”, “Terminé”.

Puedo a cambiar esto devuelta a 50 y veo que dice “50 es igual a 50”. Para que la frase de abajo tenga un poco más de sentido, porque si es que yo pongo otro valor, por ejemplo, 25, igual me está diciendo “13 no es igual a 50”. Si recuerdan cómo se podía hacer esto, era a través de variables. Voy a crear una nueva variable que voy a decir “numero”, voy a arrastrar el bloque de **Establecer**, voy a ponerlo al inicio, quiero la variable “numero” y que cambie a 25.

Voy a conectar esto y voy a tomar la variable “numero”, la voy a poner aquí porque quiero comparar “numero” con el valor 50, y utilizando los operadores de **Unir Palabras**, voy a unir la variable “numero” con “no es igual a 50”. Voy a poner esto aquí y al momento de darle **Play** veo que dice “25 no es igual a 50”. Y si es que pongo 30 aquí, me dice de nuevo “30 no es igual a 50”. En cambio, aquí si pongo 50, me va a decir “50 es igual a 50” porque como yo estuve comparando el valor de “numero” que es 50 con el número 50, el código de arriba se ejecuta porque la condición es verdadera.

En cambio, si yo cambio esto a 25 de nuevo, la condición es falsa porque 25 no es igual a 50, entonces se ejecuta lo que está abajo. Tomen en cuenta que ustedes pueden agregar cuantos quieran de estos, pueden agregar uno nuevo acá, pueden agregar adentro cuantos ustedes quieran de estos. Puedo poner más operadores, por ejemplo, **“Manzana” contiene “a”** y que diga otra cosa que sea, por ejemplo, “Manzana sí contiene a a”. Voy a borrar este que está de más, le voy a dar **Play**, dice “25 no es igual…” ¿Y por qué no se ejecutó el de aquí? Era porque la condición inicial del “numero” igual a 50 no fue verdadero, entonces todo lo que estaba aquí se ignoró.

Voy a cambiar la variable de nuevo a 50 para ver que sí se ejecuta, dice “50 es igual a 50” y luego “manzana sí contiene a a”.

Eso es todo sobre lo que trata condicionales. Hay que recordar entonces que, con estos bloques especiales, podemos decidir si una cierta cantidad de código se ejecuta dependiendo de si es que una condición es verdadera o falsa. Tenemos entonces los bloques de **Si** y los de **Si y Si No** que son distintos, hacen cosas distintas, pero por detrás es algo muy similar. Estoy observando si es que la condición que le paso es verdadera y al momento de que sea verdadera, va a ejecutar el código de arriba, pero si es que no, va a ejecutar el código del si no.

{{< archivos "contenido/leccion-9" "Condicionales.sb3" >}}
