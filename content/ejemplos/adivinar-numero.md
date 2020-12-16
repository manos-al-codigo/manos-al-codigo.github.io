+++
title = "Adivinar número"
weight = 1
+++

Este pequeño juego trata de adivinar el número del 1 al 10 que el gato está pensando. Uno puede insertar un número y el gato le dirá si su número es más grande o más pequeño que el que él está pensando. Finalmente, una vez que se adivina el número el gato le dirá cuantos intentos le tomó hacerlo.

## Código completo

{{< figure src="/img/ejemplos/adivinar-numero-codigo.png" >}}

## Explicación

El proceso de realización de este programa está en orden. Para realizar un programa similar, basta con seguir estos pasos en orden.

#### Inicialización de variables

{{< figure src="/img/ejemplos/adivinar-numero-1.png" >}}

Primeramente, iniciamos las variables que vamos a usar `valorOriginal` e `intentos`.

¿Qué hacen estas variables?

* `valorOriginal`: El número al azar del 1 al 10 que el gato está pensando.
* `intentos`: El número de intentos. Cómo todavía no hemos empezado, esto tiene que valer **0**.

#### Repetir hasta adivinar

{{< figure src="/img/ejemplos/adivinar-numero-2.png" >}}

El resto del código está adentro de este bloque de repetición. Ya que el punto del juego es de adivinar el número que está pensando el gato, el momento que nosotros adivinemos, es decir `adivinado` es igual a `valorOriginal`, entonces habremos terminado el juego.

> La variable `adivinado` almacena el número que estamos insertando para adivinar. Esta variable no necesitaba un valor inicial y por eso no lo inicializamos previamente.

#### Preguntar el número al jugador

{{< figure src="/img/ejemplos/adivinar-numero-3.png" >}}

Primeramente, tenemos que aumentar el número de intentos ya que al adivinar el número estamos realizando un intento.

Luego, preguntamos al jugador qué número desea insertar para adivinar y esta respuesta la guarda a la variable `adivinado`. Cabe recordar que esta variable se ocupa de guardar el número adivinado y es esta variable que debemos comparar con el número del gato para saber si hemos adivinado o no. Esta comparación se realiza en la condición del bloque de repetición.

#### Responder si el número se adivinó

{{< figure src="/img/ejemplos/adivinar-numero-4.png" >}}

Después de haber preguntado al jugador qué número desea insertar, queremos hacer que el gato responda con un mensaje como *¡Adivinaste!* si es que sí se adivinó el número.

Utilizamos un bloque de **Si entonces Si No** y la condición que veremos verificar es si `adivinado` es igual a `valorOriginal`.

Si es que la condición es verdadera, enviamos el mensaje de *¡Adivinaste!*.

El mensaje está estructurado como: **¡Adivinaste! Te tomó `intentos` intentos.**

Basta reemplazar `intentos` con el valor que está guardado en la variable `intentos`. Para esto tenemos que usar el operador de **Unir** texto.

#### Responder si el número no se adivinó

{{< figure src="/img/ejemplos/adivinar-numero-5.png" >}}

Si la condición mencionada antes es falsa, es decir, que `adivinado` no es igual a `valorOriginal`, queremos que el gato dé una respuesta para ayudar al jugador a adivinar el número. Es decir, si es que el número `adivinado` es más grande que `valorOriginal`, le diremos al jugador que el número que el gato está pensando es más pequeño, si es que el número `adivinado` es más pequeño que `valorOriginal`, le diremos que el número que está pensando el gato es más grande.

Para hacer esto, insertamos un bloque de **Si** para verificar si `adivinado` es más pequeño que `valorOriginal`. Si se da esto, se le dice al jugador el siguiente mensaje:

**Mi número es más grande que `adivinado`**, donde `adivinado` corresponde al número que el jugador insertó.

Luego, hacemos lo mismo para el caso de que el número adivinado sea más grande que el número del gato. Insertamos otro bloque **Si** a continuación para verificar el caso contrario, es decir, si es que `adivinado` es más grande que `valorOriginal`. Si se da esto, se le dice al jugador el siguiente mensaje:

**Mi número es más pequeño que `adivinado`**, donde `adivinado` corresponde al número que el jugador insertó.

## Corriendo el programa

{{< figure src="/img/ejemplos/adivinar-numero-run-1.png" title="El gato pregunta el número a adivinar." >}}
{{< figure src="/img/ejemplos/adivinar-numero-run-2.png" title="Si el número es muy pequeño, el gato dice que su número es más grande." >}}
{{< figure src="/img/ejemplos/adivinar-numero-run-3.png" title="Si el número es muy grande, el gato dice que su número es más pequeño." >}}
{{< figure src="/img/ejemplos/adivinar-numero-run-4.png" title="Cuando adivinas el número, el gato te felicita." >}}

{{< archivos "contenido/ejemplos" "Adivinar-Numero.sb3" >}}
