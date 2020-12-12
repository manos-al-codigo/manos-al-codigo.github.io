+++
title = "Eventos"
weight = 4
+++

{{< youtube Cvxgih0NiHA >}}

## Contenido

Hasta ahora lo único que he hecho fue abrir el editor de Scratch. Esta ventana de tutoriales la puedo cerrar.

Hemos visto hasta ahora con eventos que el que siempre usamos es **Al Presionar la Bandera** ya que cuando usamos esto podemos utilizar los demás bloques y al momento de clickear en **Play**, vemos que el código se ejecuta.

Pero yo puedo utilizar otros tipos de eventos para ejecutar código, dependiendo de qué evento sucede. Por ejemplo, en los juegos de video tenemos siempre esta opción de presionar botones, por ejemplo, las flechas, para hacer que el personaje se mueva de derecha a izquierda o de arriba abajo.

Para eso tenemos este evento que se llama **Al Presionar la Tecla**, yo puedo poner cuantos quiera de estos. Y al presionar la tecla, yo puedo cambiar el botón que yo quiera utilizar. Utilicemos las flechas, por ejemplo, vamos a utilizar la flecha derecha aquí, y el movimiento voy a hacer que el gato apunte a la dirección de la derecha, y que cambie **X**, porque recuerden que **X** corresponde al movimiento de izquierda a derecha, cambie en 10. Lo que significa que cada vez que yo presione la tecla de la derecha, el gato va a moverse hacia la derecha.

Hagamos lo mismo, pero con la flecha izquierda, voy a hacer que el gato apunte a la dirección hacia la izquierda, es decir -90 grados, y vamos a cambiar **X** en -10. Tiene que ser un número negativo para que vaya a la izquierda.

Podemos agregar otros más de estos, de hecho, voy a utilizar dos más para las flechas de arriba y la flecha de abajo. Voy a poner que apunte el gato hacia abajo para la flecha abajo, y que apunte hacia arriba para la flecha arriba. Puedo aquí cambiar la **Y**, porque la **Y** es el movimiento de arriba a abajo, y si es un número positivo, voy a ir hacia arriba, y un número negativo para ir hacia abajo.

Entonces, yo tengo mis eventos derecha, izquierda, abajo, arriba, y si es que utilizo los botones de mi teclado, arriba abajo, las flechas, puedo ver que el gato hace justamente este movimiento dependiendo qué botón utilice.

Puedo hacer muchos tipos de eventos, tipos de movimientos, por ejemplo, al presionar espacio, puedo hacer que el gato trate como que de saltar. Y una manera que puedo hacer esto, es utilizando el botón de **Deslizar en 1 Segundo**. Voy a cambiar el 1 segundo a 0.3 para que sea un poco rápido. Y como quiero que el gato solo se mueva de arriba abajo, voy a utilizar este bloque especial que dice **Posición en X** y lo voy a arrastrar a donde dice **X** en este bloque. Aquí lo único que voy a hacer es cambiar la Y para que diga 10, para que se mueva 10 unidades hacia arriba, y luego voy a deslizar este mismo bloque de nuevo. Le voy a poner 0.3 segundos, voy a volver a arrastrar este **Posición en X** y voy a cambiar Y en -10. Entonces cada vez que aplaste el botón de espacio, vemos que el gato como que está saltando. Puedo hacerlo que se mueva y luego salta. Eso tenemos para los eventos de presionar teclas.

Pero podemos utilizar otro tipo de eventos, por ejemplo, al hacer clic. Por ejemplo, si es que yo le hago clic al gato, puedo hacerle que diga *“Me cliqueaste!”*, le hago clic al gato y me dice *“Me cliqueaste”*. Puedo seguir utilizando los otros eventos al mismo tiempo.

También hay otros eventos, por ejemplo, cuando el volumen del sonido cambie. Esto hace uso del micrófono, y de hecho si es que ustedes utilizan este bloque, es muy probable que su navegador les pida acceder a su micrófono, cuando esto suceda, denle que sí.

Entonces al momento que yo utilice este bloque, puedo hacer que el gato haga un tipo de acción dependiendo del micrófono mío de mi computadora. Lo que significa que yo puedo hacer que el gato se mueva cuando yo esté hablando. Voy a hacer que piense *“Te escuché!”* por 2 segundos. Entonces cada vez que yo hable en el micrófono, pueden ver que el gato me está escuchando. Y repite *“Te escuché!”* cada vez que yo esté utilizando el micrófono.

También podemos utilizar otro tipo de eventos en el que un evento pueda llamar a otro evento. Por ejemplo, tenemos estos bloques especiales que dicen **Al Recibir “mensaje1”**, **Enviar “mensaje1”**, **Enviar “mensaje1” y Esperar**. Con **Al Recibir “mensaje1”**, yo puedo hacer que el código que esté adentro, por ejemplo, **Siguiente Disfraz** y que este evento suceda cada vez que el gato termine de escucharme. Entonces puedo utilizar el bloque de **Enviar “mensaje1”**, al momento que yo esté hablando, estoy haciendo que el evento de **Cuando el Volumen del Sonido** se ejecute, el momento de que termina de pensar, el código envía el evento *“mensaje1”* y el *“mensaje1”* se ejecuta aquí.

También tenemos la opción de **Enviar “mensaje1” y Esperar** lo que significa que, si yo pongo más bloques debajo de esto, por ejemplo, **Mover** y **Girar**, podemos ver que el gato va a hacer las dos cosas al mismo tiempo. Va a enviar el mensaje para que el disfraz cambie, pero también se va a mover los 10 pasos y va a girar justo al mismo tiempo. Utilizando el bloque de **Enviar “mensaje1” y Esperar**, podemos hacer que el gato, al momento de que envíe el *“mensaje1”*, pueda completar lo que está en el evento *“mensaje1”*, y luego de que este código se complete, va a continuar con lo que está abajo.

Eso es todo para lo que son eventos, tenemos muchas opciones en cuanto a cómo ejecutar código, y esto es bastante útil por ejemplo cuando uno quiere hacer un juego. Puedo hacer que el gato se mueva, suba, vaya a la izquierda, baje, salte, y estas son los conceptos muy básicos de un juego. Entonces podemos ver que, con este tipo de cosas, con eventos, podemos hacer juegos muy, muy poderosos.

{{< archivos "contenido/leccion-6" "Eventos.sb3" >}}
