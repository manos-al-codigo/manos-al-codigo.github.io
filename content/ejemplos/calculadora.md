+++
title = "Calculadora"
weight = 2
+++

Este es un pequeño ejemplo de una calculadora que puede hacer las operaciones básicas de suma, resta, multiplicación y división entre solo dos números.

## Código completo

{{< figure src="/img/ejemplos/calculadora-codigo.png" >}}

## Explicación

El proceso de realización de este programa está en orden. Para realizar un programa similar, basta con seguir estos pasos en orden.

#### Preguntar por la operación a realizar

{{< figure src="/img/ejemplos/calculadora-1.png" >}}

Al iniciar el programa damos la bienvenida al usuario con el mensaje: **¡Bienvenidos a mi calculadora!**. Luego, el preguntamos al usuario qué operación desea realizar. Como siempre hemos hecho, el valor de la respuesta se la guarda en una variable, en este caso llamada `operacion`.

#### Verificar si la operación es conocida

{{< figure src="/img/ejemplos/calculadora-2.png" >}}

Luego, utilizamos el bloque **Si entonces Si No** porque queremos verificar que la operación sea conocida. La condición, que es un poco larga, está verificando si la variable `operacion` tiene alguno de los valores siguientes:

* `+`, para la suma.
* `-`, para la resta.
* `*`, para la multiplicación.
* `/`, para la división.

Esta condición se hace a través de varios operadores **o** Booleanos ya que queremos verificar que alguna de las igualdades sea verdadera. Basta con que una sea verdadera para que podamos ejecutar el código que se encuentra adentro de la parte de arriba.

En el caso de que la variable `operacion` no sea ninguno de los símbolos mencionados previamente, ejecutamos lo que se encuentra dentro del bloque **Si No**. Si llegamos a esto es porque la operación no es conocida. Por esto mandamos el mensaje **No conozco esa operación. :(**.

Ya que el código de los cálculos se encuentra dentro del bloque **Si** (porque solo podemos hacer los cálculos con una operación válida), podemos agregar otros bloques que se ejecutarán después de hacer los cálculos (o no) después del bloque **Si entonces Si No**. En este caso queremos despedirnos del usuario, por lo que enviamos el mensaje **¡Adiós!** justo al final.

#### Preguntar los números para hacer el cálculo

{{< figure src="/img/ejemplos/calculadora-3.png" >}}

Una vez que hayamos verificado que la operación es correcta, le pedimos al usuario los números con los que vamos a realizar el cálculo.

Le preguntamos al usuario por el número 1 y luego guardamos la respuesta en una variable llamada `numero1`.

Repetimos esto para el número 2, se lo preguntamos al usuario y su respuesta se la guarda en una variable llamada `numero2`.

#### Mostrar la respuesta del cálculo

{{< figure src="/img/ejemplos/calculadora-4.png" >}}

Teniéndo los números listos, procederemos a realizar el cálculo. El cálculo es distinto para cada operación, si pusimos **+** como operación estamos esperando hacer una suma. Para hacer esto vamos a utilizar 4 bloques **Si** y ejecutaremos cosas distintas dependiendo de qué valor tiene la operación.

* Si la operación es **+**, le responderemos al usuario que la respuesta es `numero1` **+** `numero2`.
* Si la operación es **-**, le responderemos al usuario que la respuesta es `numero1` **-** `numero2`.
* Si la operación es **\***, le responderemos al usuario que la respuesta es `numero1` **\*** `numero2`.
* Si la operación es **/**, le responderemos al usuario que la respuesta es `numero1` **/** `numero2`.

Eso es todo, recuerden que se usa el operador de **Unir** texto para poder agregar el resultado del cálculo adentro del mensaje.

## Corriendo el programa

{{< figure src="/img/ejemplos/calculadora-run-1.png" title="El gato pregunta qué operación se debe realizar." >}}
{{< figure src="/img/ejemplos/calculadora-run-2.png" title="Si no se inserta ninguna de las operaciones conocidas (+, -, *, /) entonces el gato dice que no conoce esa operación y el programa se termina." >}}
{{< figure src="/img/ejemplos/calculadora-run-3.png" title="Al preguntar la operación se deben insertar las operaciones conocidas (+, -, *, /). En este caso se insertó +." >}}
{{< figure src="/img/ejemplos/calculadora-run-4.png" title="El gato pregunta por el número 1. En este caso 2." >}}
{{< figure src="/img/ejemplos/calculadora-run-5.png" title="El gato pregunta por el número 2. En este caso también 2." >}}
{{< figure src="/img/ejemplos/calculadora-run-6.png" title="El gato responde con el resultado de la operación. En este caso, se realizó 2+2, y la respuesta es 4." >}}

{{< archivos "contenido/ejemplos" "Calculadora.sb3" >}}
