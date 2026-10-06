---
icon: tennis-ball
---

# Cómo crear un recurso

Un **recurso** es todo lo que se puede reservar o asignar a una actividad: una pista, un campo o un profesor. Los recursos se agrupan por deporte (pádel, tenis, fútbol…) y, con ellos, el sistema sabe qué está disponible y en qué horario, para organizar las reservas sin solapes.

Normalmente las instalaciones del club ya se crean en la configuración inicial. Si necesitas añadir una nueva, sigue estos pasos.

A continuación, se detallan los pasos a seguir:

{% stepper %}
{% step %}
### Acceso a Grupo de recursos

* Clica en el icono <i class="fa-gear" style="color:blue;">:gear:</i> de la esquina superior derecha y entra en **Configuración**.
* Clica en **Reservas**. Se abrirá directamente el bloque **Grupo de recursos**.
{% endstep %}

{% step %}
### Crear el deporte (grupo de recursos)

Si el deporte ya existe, pasa directamente al paso 4.

* Clica en <i class="fa-plus-large">:plus-large:</i> para crear un nuevo deporte o no deporte.
* Se abrirá esta ventana. En el ejemplo, creamos el tenis:

<figure><img src="../../../.gitbook/assets/image (68).png" alt=""><figcaption></figcaption></figure>

Estos son los campos obligatorios:

* **Nombre:** el nombre del deporte. Si vas a crear profesores, elige **No Deporte**.
*   **Orden:** la posición en la que se verá en el calendario.

    <figure><img src="../../../.gitbook/assets/image (67).png" alt=""><figcaption></figcaption></figure>
* **Deporte:** el deporte.
* **Categoría:** el tipo de recurso.
* **Intervalos en minutos:** cada cuántos minutos se divide el calendario.
* **Duración mínima:** lo mínimo que puede durar una reserva.
* **Duración máxima:** lo máximo que puede durar una reserva.
{% endstep %}

{% step %}
### Campos opcionales del deporte

* **Modifica nivel:** márcala si los resultados de este deporte suben o bajan el nivel del jugador.
* **Alto celda calendario:** la altura de las casillas del calendario. Por defecto es 35. Para ver 4 jugadores en una reserva de 1 hora con franjas de 30 minutos, se recomienda 90.
* **Mostrar jugadores:** márcala para ver los jugadores directamente en la reserva del calendario.
* **Discontinuado:** márcala para dejar de usar este deporte.
* **Mostrar iniciales participantes:** márcala para que en el display salgan las iniciales en lugar del nombre completo.
* **Máximo tiempo entre reservas online:** el espacio libre que se puede dejar entre una reserva online y otra.
* **Espacio entre reservas en apertura/cierre:** igual que el anterior, pero teniendo en cuenta también la hora de apertura y de cierre.
* **Tiempo mín. entre reservas admin:** el espacio libre mínimo entre una reserva hecha desde administración y otra.
* **Hora inicio día:** la hora a la que empieza el día, con un número entero entre 0 y 23.
{% endstep %}

{% step %}
### Añadir las pistas (recursos)

* Clica sobre el **ID** del deporte o no deporte.
*   Ve al bloque **Recursos**.

    <div align="left"><figure><img src="../../../.gitbook/assets/image (69).png" alt=""><figcaption></figcaption></figure></div>
* Clica en <i class="fa-plus-large">:plus-large:</i>.
* Se abrirá otra ventana:
  * **Nombre:** el nombre de la pista. Lo ideal es el deporte y su número (por ejemplo, _Pádel 1_). Si la pista está patrocinada, puedes usar el nombre del patrocinador.
  * **Orden:** la posición en la que aparecerá la pista en el calendario.
  * **Tipo de pista:** interior, exterior, cubierta, etc.
  * **Suelo/pared:** depende del deporte. En tenis o fútbol se elige el tipo de suelo; en pádel o squash, el tipo de pared.
*   **Guardar y nuevo:** si vas a crear varias pistas, usa esta opción. Se guarda la pista y se abre otra con casi todo rellenado, salvo el nombre y el orden.

    <figure><img src="../../../.gitbook/assets/image (72).png" alt=""><figcaption></figcaption></figure>
{% endstep %}
{% endstepper %}

> **Importante:** la pista todavía no aparecerá en el calendario. Antes tienes que darle un horario:

[como-crear-un-horario.md](../horarios/como-crear-un-horario.md "mention")
