---
icon: display-chart-up-circle-dollar
---

# Cómo poner precios al horario

Configurar precios permite definir y gestionar las tarifas que se aplican a los distintos servicios del club. De este modo podrás establecer importes claros y coherentes según el tipo de reserva, su duración o condiciones, asegurando que el sistema calcule correctamente los cobros. En este artículo aprenderás cómo crear y asignar precios paso a paso.

En este apartado solo se gestionan las tarifas. Los precios se aplican sobre los horarios que ya tengas configurados, pero no modifican la apertura ni la disponibilidad de las pistas o actividades. Si necesitas cambiar también el horario, deberás hacerlo desde el apartado correspondiente a horarios.

Para saber como accede al siguiente apartado:\
[como-crear-un-horario.md](../horarios/como-crear-un-horario.md "mention")

{% stepper %}
{% step %}
### Acceso a Precios por Calendario

* Dirígete a la esquina superior derecha y clica en el icono de **Configuración**.
* En el desplegable que se abre, selecciona **configuración**.&#x20;
*   Luego accede a **Reservas**.

    <div align="left"><figure><img src="../../../.gitbook/assets/image (56).png" alt=""><figcaption></figcaption></figure></div>
*   Localiza el bloque **Precios por Calendario** y haz clic.<br>

    <figure><img src="../../../.gitbook/assets/image (74).png" alt=""><figcaption></figcaption></figure>
{% endstep %}

{% step %}
### Crear un nuevo horario

* Clica en :heavy\_plus\_sign:.
*   Se abre el siguiente menú para completar de la siguiente manera.

    <div align="left"><figure><img src="../../../.gitbook/assets/image (60).png" alt=""><figcaption></figcaption></figure></div>

    * **Nombre:** Escribe el titulo del horario, es recomendable que corresponda a los días de la semana que va a abarcar.
    * **Prioridad:** Es necesario asignar una prioridad numérica a cada precio. Se recomienda utilizar valores bajos, ya que el sistema aplica primero los precios con mayor prioridad (número más bajo). De este modo, si un precio general tiene mayor prioridad que un precio de festivo, se aplicará el primero y no el de festivo, aunque la fecha coincida.
    * **Inicio:** Fecha en la que comienza a aplicar estos precios, si es inmediata no es necesario completar.&#x20;
    * **Fin:** Fecha en la que finalizan estos precios, si son continuos y no hay previsión de cambio de precios, no es necesario completar.
    * **Día de la semana:** Marca las casillas correspondiente a los días de la semana en que se va a aplicar este horario.
* Clica en guardar para salvar cambios.
{% endstep %}

{% step %}
### Añadir precios al horario

En este paso se crearán las franjas horarias a las que se aplicarán los distintos precios. El sistema permite definir tramos de tiempo con tarifas diferentes dentro de un mismo día, de modo que, por ejemplo, una hora punta y una hora valle puedan tener precios distintos según el horario configurado.

* Selección el id del horario en cuestión.
*   Dirígete al bloque de **Precios**.

    <div align="left"><figure><img src="../../../.gitbook/assets/image (105).png" alt=""><figcaption></figcaption></figure></div>
* Clica en :heavy\_plus\_sign:.
*   Se abre una ventana que debemos cumplimentar de la siguiente manera:

    <figure><img src="../../../.gitbook/assets/image (106).png" alt=""><figcaption></figcaption></figure>

    * **Recurso:** se añaden todas las pistas o profesores a los que se vaya a aplicar este horario.
    * **Inicio:** Hora de inicio de esta franja horaria a la que se aplicará este precio.
    * **Fin:** Hora de fin de esta franja horaria a la que se aplicará este precio.
    * **Finaliza al día siguiente:** marca la esta casilla si este horario termina igual o mayor que las 00:00.
    * **Aplicar este precio en solapamientos:** En caso de solapamiento, se aplicará este precio a todo el periodo afectado, en lugar de dividir el coste entre los distintos tramos que se superponen.
    * **Producto:** Selecciona el producto de tipo **Servicio** que se aplicará a esta franja horaria.
* Clica en <i class="fa-floppy-disk" style="color:green;">:floppy-disk:</i> para salvar cambios.
{% endstep %}
{% endstepper %}

Si existen varias franjas con precios distintos, se deberá repetir este proceso para cada una de ellas.
