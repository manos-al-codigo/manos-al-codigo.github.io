+++
title = "Movimiento y apariencia"
weight = 3
+++

{{< youtube sxWr_sPkegk >}}

## Contenido

Hasta ahora solamente he abierto un editor de Scratch, pero si no recuerdan cómo entrar aquí, vayan a la página [scratch.mit.edu](https://scratch.mit.edu) y hagan clic en crear. Una vez en el editor, pueden cerrar la ventana de tutorial y lo que tenemos entonces son la lista de bloques que podemos utilizar y la previsualización del gatito.

Antes que nada, hay que recordar que hay que clickear en eventos a la izquierda y arrastrar el bloque que dice **Al Presionar la Bandera**. Una vez aquí podemos ya utilizar los diferentes bloques. El número 1 es el **Mover 10 pasos**, podemos cambiar este número de hecho, podemos poner 50 si queremos. Esto hará que el gato se mueva en la dirección que está viendo 50 pasos. Si hago clic en **Play**, se ve que se movió a la derecha 50 pasos.

Puedo hacer que el gato gire, voy a remover el botón de mover y solamente voy a poner girar. En este caso, estoy girando en la dirección de las manecillas del reloj 15 grados. Igual si presiono **Play**, se ve como el gato empieza a girar en esta misma dirección 15 grados cada vez que presione **Play**.

Pero también hay cómo girar de otro lado, por ejemplo, en el lado contrario. Puedo hacer que gire 90 grados, que es un cuarto de círculo. Pero también puedo decirle que el gato vaya a una posición aleatoria, en este caso. Si hago clic en **Play**, se va a mover en todas estas direcciones aleatorias. Pero también puedo cambiar esto haciendo clic aquí y darle al **Puntero del Ratón**. Y ahora el gato va a ir en la dirección del puntero del ratón. Nótese que cómo estoy haciendo clic aquí, el gato siempre trata de ir hacia la bandera.

Pero yo también puedo decirle que vaya a una posición en particular. Estas son las coordenadas, si es que yo pongo 0 en **X** y 0 en **Y**, el gato se va a encontrar en el centro. Aquí lo único que hay que tener en cuenta es que las **X** son de izquierda a derecha y **Y** son de arriba a abajo. Si pongo un número positivo para el X se va a ir a la derecha, si pongo un número negativo, -50, se va a ir a la izquierda. Si pongo un número positivo en la **Y** va a ir arriba y si pongo un número negativo en la **Y** va a ir hacia abajo.

Pero hemos visto que el gato está moviéndose de manera muy rápida y podríamos hacer que el gato se mueva de una forma más lenta para que podamos ver cómo se mueve. Para eso hay que utilizar el bloque que se llama **Deslizar**. Tenemos dos bloques que dicen **Deslizar en 1 Segundo a Posición Aleatoria** lo que significa que durante un segundo vamos a poder ver al gato moviéndose, y se va a ir a una dirección aleatoria. Si hago clic en **Play** podemos ver cómo se mueve en una dirección distinta. Igualmente, de nuevo, y de nuevo, y podemos inclusive decirle que vaya al puntero del ratón.

Pero también podemos utilizar el siguiente bloque que hace que se mueva en la dirección que le digamos. Si ponemos (50; 50), se va a ir hacia arriba a la derecha. Igualmente, podemos hacer que el gato apunte a una cierta dirección, por ejemplo, si hago clic aquí puedo seleccionar la dirección a la que quiero que el gato vea, por ejemplo, a la derecha. Esto hará que el gato siempre esté viendo a la derecha. Puedo hacer que apunte en la dirección del ratón, por ejemplo, aquí.

Puedo hacer también que el gato cambie su dirección de izquierda a derecha en la cantidad que yo quisiera aquí poner. Por ejemplo, si pongo 50 aquí, se va a ir a la derecha, pero aquí si pongo -50 se va a la izquierda. Puedo también utilizar el botón que dice **Fijar X a 50**, esto significa que todo el tiempo se va a poner en 50. ¿Y ahora cuál es la diferencia entre **Cambiar X en 50** y **Fijar X a 50**? Si pongo **Cambiar X en 50**, esto hará que el gato, cada vez que yo presione el botón, vaya 50 pasos a la derecha. Pero en cambio, si yo pongo **Fijar X a 50**, cada vez que yo presione el botón, siempre va a estar en la posición 50.

Además del **Fijar X** y **Cambiar X**, también podemos **Cambiar Y** y **Fijar Y** que hace lo mismo, pero de arriba hacia abajo. Puedo hacer clic en **Cambiar Y en 10** y se va a ir hacia arriba, o puedo poner **Fijar Y a 50** y se va a quedar siempre en 50.

Pero también hay algo muy interesante, yo puedo hacer que el gato se deslice hacia la derecha, voy a poner 300 a la derecha. Vemos que el gato se va muy lejos y de hecho ya no podemos verlo, pero podemos utilizar el botón que dice **Rebotar si Toca un Borde** para que el gato, al momento que inicie, se rebote contra la pared y cambie de dirección. Para hacer que esto se vea un poquito mejor voy a hacer que el gato siempre inicie en la mitad. Entonces, **Fijar X a 0** y **Fijar Y a 0**. Si le doy clic a **Play**, vemos que el gato trató de moverse hacia la derecha y luego al momento que llegó se fue a la izquierda porque rebotó.

También podemos inclusive ver cómo cambia la dirección, podemos hacer de izquierda a derecha si es que queremos que el gato cambie su dirección de izquierda a derecha, o podemos hacer que vaya en otra dirección, y vemos que cambia la dirección.

Ahora lo que voy a hacer es que voy a borrar todos estos bloques y voy a hacer que el gato inicie siempre desde la mitad, entonces **X igual a 0** y **Fijar Y a 0**, y quiero que apunte a la derecha. Entonces hago clic aquí y hago 90 para que gire a la derecha. Entonces iniciamos, y aquí es cómo estábamos antes. Voy a hacer que el gato se deslice durante 1 segundo a una posición aleatoria y que rebote si toca un borde, y que el estilo de rotación sea de izquierda a derecha. Le doy a **Play** todo el tiempo y vemos que el gato siempre inicia desde el medio y va a una dirección distinta.

Eso tenemos hasta ahora para el movimiento, pero ¿Qué tal la apariencia?

La apariencia tiene todo que ver con cómo luce el gato. Si arrastramos el botón que dice **Decir “Hola” por 2 segundos**, al momento que hagamos **Play**, el gato va a decir “Hola” y se va a quedar el mensaje por 2 segundos. Pero si no nos interesa cuánto tiempo demora el mensaje, podemos utilizar otro bloque que solo dice **Decir “Hola”**. Yo puedo cambiar el mensaje, puede decir “Chao”. Le doy clic aquí y vemos que el gato dice esto.

Podemos también inclusive cambiar cómo luce la burbuja del mensaje. Podemos utilizar el botón que dice **Pensar** para tener otro estilo de burbuja. Igualmente, podemos utilizar el otro botón en el caso en el que no nos interese qué tan largo debería ser el mensaje. Si le doy clic aquí, el mensaje se va a quedar para siempre.

También tenemos el concepto de disfraz, el cual nos permite cambiar cómo luce el personaje. Puedo arrastrar el bloque de cambiar de disfraz, el momento de darle **Play**, se ve que el gato siempre está cambiado en este nuevo disfraz. Puedo cambiar este por **Disfraz 1** y vemos que se cambia. Esto de los disfraces se puede obtener en la parte de arriba a la izquierda en **Disfraces**, tenemos los 2 disfraces disponibles. Pero, en lugar de tener que definir qué disfraz se tiene que usar, podemos utilizar el bloque que dice **Siguiente Disfraz**, que, al momento de darle **Play**, vemos que va cambiando entre sí.

También podemos cambiar el fondo, pero obviamente no tenemos fondos predeterminados, tendríamos que crear uno y subirlo acá. Si le doy clic, no va a pasar nada. Además, de igual forma que para el disfraz, se puede cambiar el fondo definiendo qué fondo se va a escoger o utilizando el fondo siguiente, que va a ser lo mismo.

También puedo cambiar el tamaño del gato, hay el botón que dice **Cambiar Tamaño en 10**, y cada vez que presione **Play**, el gato se va a volver más grande en 10%. Puedo poner un número negativo aquí para hacer que se haga más chiquito. Pero también puedo definir el tamaño absoluto, utilizando el bloque de **Fijar Tamaño a 100%**. Si hago **Play** aquí, el gato siempre va a estar en su tamaño original. Puedo poner aquí 200% para que el gato sea doblemente grande.

Puedo también cambiar el efecto, le puedo agregar efectos de: color, ojo de pez, remolino, pixelear, mosaico, todos estos. Si hago clic en **Play**, vemos que el gato va cambiando de color. Puedo cambiar este valor a 50 y este color cambia. Puedo agregar ojo de pez, puedo agregar remolino, pixelear, mosaico, brillo y desvanecer. También podemos tener la opción de quitar los efectos y cada vez que dé clic en **Play**, no va a pasar nada porque después de que cambié el efecto, los quité.

También tenemos bloques para mostrar u ocultar el gato. Si es que le doy a ocultar y le doy a **Play**, el gato desaparece. Si es que pongo mostrar, le doy a **Play**, el gato vuelve a aparecer. También tenemos el concepto de capa, en el cual, si es que el gato está en la capa de al frente, siempre va a estar visible. Si tenemos un fondo, le pongo en la capa de atrás, el gato puede que desaparezca porque va a estar detrás del fondo.

Podemos combinar todos estos bloques que hemos visto para hacer algo interesante. Por ejemplo, voy a utilizar todo este bloque que utilizamos al inicio, voy a hacer que diga “Hola” antes de moverse, que piense al final de moverse, y que luego vuelva a moverse al puntero del ratón en 0.5 segundos. Si le doy a **Play**, vemos que el gato dice “Hola”, se mueve, piensa “Hmm” y se movió a la dirección del puntero.

Entonces, con todos estos bloques podemos hacer un sinfín de cosas, hasta ahora hemos visto solamente **Movimiento y Apariencia**, pero hay bastantes, bastantes bloques que podemos utilizar. Más adelante vamos a ver cómo utilizar todos estos bloques para que puedan realizar cosas muy, muy interesantes.

{{< archivos "contenido/leccion-5" "Movimiento-Apariencia.sb3" >}}
