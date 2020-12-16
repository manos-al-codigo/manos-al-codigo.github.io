+++
title = "Fecha"
weight = 3
+++

Este es un pequeño ejemplo de como obtener la fecha y presentarla de forma legible para el usuario. El programa es un poco largo pero su funcionamiento es bastante simple. Al final, el gato solamente muestra un mensaje diciendo qué día es hoy.

## Código completo

{{< figure src="/img/ejemplos/fecha-codigo.png" >}}

## Explicación

El proceso de realización de este programa está en orden. Para realizar un programa similar, basta con seguir estos pasos en orden.

#### Iniciar las variables del año y de la fecha

{{< figure src="/img/ejemplos/fecha-1.png" >}}

Para facilitar la creación del mensaje, vamos a guardar en una variable `año` el valor que la variable especial para el **Año Actual**. Es decir, en el caso de que sea 2020, la variable `año` tendrá el valor de **2020**.

Además, por razones similares, vamos a guardar en una variable `fecha` el número del día del mes que es. Este valor lo podemos obtener utilizando la variable especial para la **Fecha Actual**.

Hasta ahora tenemos las variables `fecha` y `año` listas.

#### Definir qué día de la semana es

{{< figure src="/img/ejemplos/fecha-2.png" >}}

Para definir qué día de la semana es, debemos realizar algunas comparaciones. Hay que recordar que el bloque de la variable especial de la fecha **Día de la Semana Actual** es un número que va del 1 al 7 y corresponde a una enumeración de los días de la semana, empezando desde el domingo (1) y terminando con el sábado (7).

Para esto, utilizaremos 7 bloques de **Si** y la condición para cada uno de estos bloques será: Verificar que **Día de la Semana Actual** sea 1, sea 2, sea 3, sea 4, sea 6, sea 6 o sea 7.

* Si **Día de la Semana Actual** es **1**, el día actual es **Domingo**, entonces guardamos en la variable `dia` el texto siguiente: *Domingo*.
* Si **Día de la Semana Actual** es **2**, el día actual es **Lunes**, entonces guardamos en la variable `dia` el texto siguiente: *Lunes*.
* Si **Día de la Semana Actual** es **3**, el día actual es **Martes**, entonces guardamos en la variable `dia` el texto siguiente: *Martes*.
* Si **Día de la Semana Actual** es **4**, el día actual es **Miércoles**, entonces guardamos en la variable `dia` el texto siguiente: *Miércoles*.
* Si **Día de la Semana Actual** es **5**, el día actual es **Jueves**, entonces guardamos en la variable `dia` el texto siguiente: *Jueves*.
* Si **Día de la Semana Actual** es **6**, el día actual es **Viernes**, entonces guardamos en la variable `dia` el texto siguiente: *Viernes*.
* Si **Día de la Semana Actual** es **7**, el día actual es **Sábado**, entonces guardamos en la variable `dia` el texto siguiente: *Sábado*.

Con este proceso hemos preparado la variable `dia`.

#### Definir qué mes es

{{< figure src="/img/ejemplos/fecha-3.png" >}}

Para el encontrar qué mes es, el proceso es bastante similar a lo que se hizo anteriormente para el día de la semana. Hay que recordar que la variable especial de la fecha **Mes Actual** devuelve un número del 1 al 12 para los números de los meses, empezando con enero (1) y terminando con diciembre (12).

De igual manera, utilizaremos 12 bloques de **Si** para verificar qué número del mes es y asignar a la variable `mes` el nombre del mes correspondiente.

* Si **Mes Actual** es **1**, el mes actual es **Enero**, entonces guardamos en la variable `mes` el texto siguiente: *Enero*.
* Si **Mes Actual** es **2**, el mes actual es **Febrero**, entonces guardamos en la variable `mes` el texto siguiente: *Febrero*.
* Si **Mes Actual** es **3**, el mes actual es **Marzo**, entonces guardamos en la variable `mes` el texto siguiente: *Marzo*.
* Si **Mes Actual** es **4**, el mes actual es **Abril**, entonces guardamos en la variable `mes` el texto siguiente: *Abril*.
* Si **Mes Actual** es **5**, el mes actual es **Mayo**, entonces guardamos en la variable `mes` el texto siguiente: *Mayo*.
* Si **Mes Actual** es **6**, el mes actual es **Junio**, entonces guardamos en la variable `mes` el texto siguiente: *Junio*.
* Si **Mes Actual** es **7**, el mes actual es **Julio**, entonces guardamos en la variable `mes` el texto siguiente: *Julio*.
* Si **Mes Actual** es **8**, el mes actual es **Agosto**, entonces guardamos en la variable `mes` el texto siguiente: *Agosto*.
* Si **Mes Actual** es **9**, el mes actual es **Septiembre**, entonces guardamos en la variable `mes` el texto siguiente: *Septiembre*.
* Si **Mes Actual** es **10**, el mes actual es **Octubre**, entonces guardamos en la variable `mes` el texto siguiente: *Octubre*.
* Si **Mes Actual** es **11**, el mes actual es **Noviembre**, entonces guardamos en la variable `mes` el texto siguiente: *Noviembre*.
* Si **Mes Actual** es **12**, el mes actual es **Diciembre**, entonces guardamos en la variable `mes` el texto siguiente: *Diciembre*.

Con esto hemos preparado la variable `mes`.

#### Mostrar la fecha completa

{{< figure src="/img/ejemplos/fecha-4.png" >}}

Teniendo listas las variables `año`, `fecha`, `mes` y `dia`, prepararemos el mensaje de la fecha en una nueva variable llamada `frase`. El mensaje tendrá la siguiente estructura:

**Hoy es `dia`, `fecha` de `mes` del año `año`.**

Hay que recordar que se debe usar el operador de **Unir** texto para juntar todas estas variables y pedazos de texto para formar la frase final. Puede ser un poco tedioso ya que tenemos que unir bastantes bloques de texto pero como muestra la imagen, el texto final se debería poder leer sin problema.

Teniendo lista la variable `frase`, lo único que resta es que el gato diga esta frase, para esto utilizamos el bloque **Decir frase**.

## Corriendo el programa

{{< figure src="/img/ejemplos/fecha-run-1.png" title="El gato muestra un mensaje la fecha completa." >}}

{{< archivos "contenido/ejemplos" "Fecha.sb3" >}}
