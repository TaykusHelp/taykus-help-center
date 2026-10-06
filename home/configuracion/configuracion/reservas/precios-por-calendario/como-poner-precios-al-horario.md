---
icon: display-chart-up-circle-dollar
---

# Cómo poner precios al horario

En **Precios por calendario** se decide qué precio tiene cada reserva según el día y la hora. Por ejemplo, puedes cobrar distinto en hora punta y en hora valle. Cada franja usa un producto de tipo **Servicio**, que es el que marca el precio.

> **Importante:** aquí solo se cambian los **precios**. No cambia la apertura ni la disponibilidad de las pistas. Para eso, consulta:
>
> [como-crear-un-horario.md](../horarios/como-crear-un-horario.md "mention")

A continuación, se detallan los pasos a seguir:

{% stepper %}
{% step %}
### Acceso a Precios por calendario

* Clica en el icono <i class="fa-gear" style="color:blue;">:gear:</i> de la esquina superior derecha y entra en **Configuración**.
*   Clica en **Reservas**.

    <div align="left"><figure><img src="../../../.gitbook/assets/image (56).png" alt=""><figcaption></figcaption></figure></div>
*   Clica en el bloque **Precios por calendario**.<br>

    <figure><img src="../../../.gitbook/assets/image (74).png" alt=""><figcaption></figcaption></figure>
{% endstep %}

{% step %}
### Crear el calendario de precios

* Clica en :heavy\_plus\_sign:.
*   Se abrirá esta ventana:

    <div align="left"><figure><img src="../../../.gitbook/assets/image (60).png" alt=""><figcaption></figcaption></figure></div>

    * **Nombre:** te recomendamos que indique los días de la semana que incluye.
    * **Prioridad:** un número que decide qué precio manda si dos coinciden. Se aplica primero el de **número más alto**. Lo habitual es poner el número más bajo a entre semana, uno mayor al fin de semana (así puedes aplicar el precio de fin de semana a un día entre semana) y el más alto a festivos o cerrado.
    * **Inicio:** fecha desde la que se aplican estos precios. Si es desde ya, déjalo vacío.
    * **Fin:** fecha hasta la que se aplican. Si no hay fecha de fin prevista, déjalo vacío.
    * **Día de la semana:** marca los días en los que se aplican estos precios.
* Clica en **Guardar**.
{% endstep %}

{% step %}
### Añadir las franjas de precio

Dentro de un mismo día puedes tener varias franjas con precios distintos (por ejemplo, hora punta y hora valle).

* Clica sobre el **ID** del calendario de precios.
*   Ve al bloque **Precios**.

    <div align="left"><figure><img src="../../../.gitbook/assets/image (105).png" alt=""><figcaption></figcaption></figure></div>
* Clica en :heavy\_plus\_sign:.
*   Se abrirá esta ventana:

    <figure><img src="../../../.gitbook/assets/image (106).png" alt=""><figcaption></figcaption></figure>

    * **Recurso:** las pistas o profesores a los que se aplica el precio.
    * **Inicio:** hora en la que empieza la franja.
    * **Fin:** hora en la que termina la franja.
    * **Finaliza al día siguiente:** márcala si la franja termina a las 00:00 o más tarde.
    * **Aplicar este precio en solapamientos:** si una reserva ocupa dos franjas, se cobrará toda con este precio en lugar de repartirla entre los dos.
    * **Producto:** el producto de tipo **Servicio** que marca el precio de esta franja.
* Clica en <i class="fa-floppy-disk" style="color:green;">:floppy-disk:</i> para guardar.
{% endstep %}
{% endstepper %}

> Si hay varias franjas con precios distintos, repite el último paso para cada una.

## Si algo no funciona

* **La reserva sale a 0 €:** revisa que la pista está añadida en la franja, que la franja cubre la hora de la reserva y, si termina a las 00:00 o más tarde, que está marcada **Finaliza al día siguiente**.
* **He ampliado el horario de apertura y no me deja reservar en las horas nuevas:** amplía también aquí la franja de precio. El horario y los precios tienen que cubrir las mismas horas.
* **Un festivo cobra el precio normal:** revisa que el calendario de precios de festivo tiene una prioridad más alta que el de entre semana.
