---
icon: business-time
---

# Cómo crear un tipo de reserva

Los **tipos de reserva** son categorías (escuela, clase particular, partido…) que dan a cada reserva sus propias reglas: color, precio, duración, quién puede reservar y cómo. Con ellos:

* Distingues de un vistazo cada reserva en el calendario por su color.
* Ves en los informes cuántas reservas hay de cada tipo.
* Puedes cobrar un precio distinto al habitual según el tipo de reserva.

<div align="left"><figure><img src="../../../.gitbook/assets/image (96).png" alt=""><figcaption></figcaption></figure></div>

A continuación, se detallan los pasos a seguir:

{% stepper %}
{% step %}
### Acceso a Tipos de reservas

* Clica en el icono <i class="fa-gear" style="color:blue;">:gear:</i> de la esquina superior derecha y entra en **Configuración**.
* Clica en **Reservas**.\
  ![](<../../../.gitbook/assets/image (97).png>)
*   Clica en el bloque **Tipos de reservas**.<br>

    <figure><img src="../../../.gitbook/assets/image (98).png" alt=""><figcaption></figcaption></figure>
{% endstep %}

{% step %}
### Crear el tipo de reserva

* Clica en :heavy\_plus\_sign:.
*   Se abrirá esta ventana:<br>

    <figure><img src="../../../.gitbook/assets/image (99).png" alt=""><figcaption></figcaption></figure>

    <figure><img src="../../../.gitbook/assets/image (100).png" alt=""><figcaption></figcaption></figure>

    <figure><img src="../../../.gitbook/assets/image (101).png" alt=""><figcaption></figcaption></figure>

    <figure><img src="../../../.gitbook/assets/image (102).png" alt=""><figcaption></figcaption></figure>

> **Importante:** los campos marcados con un asterisco (\*) son obligatorios.

#### Datos generales

* **Descripción (\*):** el nombre del tipo de reserva.
* **Categoría:** opcional. Una subfamilia para este tipo.
* **Orden:** la posición en la que aparece en el calendario.
* **Descripción extendida:** opcional. Detalles sobre este tipo de reserva.
* **Imagen:** opcional. Ayuda a reconocer el tipo de reserva.

#### Precio

* **Tipo de precio (\*):** elige en el desplegable:
  * **Por recurso:** se cobra el precio configurado en los horarios.
  * **Por persona:** se cobra el precio de los horarios a cada participante.
  * **Gratis:** no se cobra nada.
* **Precio:** un precio fijo para este tipo de reserva, sin tener en cuenta los precios por calendario.
* **Reserva por plaza:** márcala solo si el tipo de precio es **Por persona**.

#### Reserva y cancelación online

* **Es público:** márcala para que se pueda reservar online.
* **Permite cancelar online:** si está activada, los jugadores pueden cancelar online. Si no, solo puede cancelar el club.
* **Mínimo de minutos de anticipación:** con cuánta antelación mínima se puede reservar.
* **Máximo de minutos de anticipación:** con cuánta antelación máxima se puede reservar.
* **Minutos de anticipación para cancelaciones:** hasta cuántos minutos antes se puede cancelar.
* **Minutos pre reserva:** los minutos que la pista queda guardada mientras el jugador termina de reservar.
* **Horas antes que expire:** cuántas horas antes de la reserva caduca si no se completa.
* **Devolver pago al anular y caducar:** márcala para que el jugador recupere el dinero si la reserva se cancela o caduca sin completarse.

#### Participantes y nivel

* **Número mínimo de participantes (\*):** el mínimo de personas para este tipo de reserva.
* **Número máximo de participantes (\*):** el máximo de personas.
* **Nivel mínimo** y **nivel máximo:** el nivel de juego permitido.
* **Género:**
  * **Masculino:** solo pueden reservar usuarios masculinos.
  * **Femenino:** solo pueden reservar usuarias femeninas.
  * **Abierto:** puede reservar cualquier persona.

#### Límites

* **Permitir personalizar duración:** permite cambiar la hora de fin al crear la reserva desde administración.
* **Número máximo de reservas por día:** cuántas reservas de este tipo se pueden hacer al día.
* **Máximo número de reservas:** si hay anticipación máxima, cuenta las reservas desde hoy hasta esa anticipación. Si no, cuenta todas las reservas desde hoy.
* **Restricciones de máximas reservas online y admin:** los límites se aplican tanto a las reservas online como a las del club.

#### Apariencia

* **Colores:** el color de este tipo de reserva en el calendario. Puede ser fijo o cambiar según el estado de la reserva.
{% endstep %}

{% step %}
### Añadir los recursos

* En **Tipos de reserva**, clica sobre el **ID** del tipo que acabas de crear.
*   Abre la pestaña **Recursos**.

    <figure><img src="../../../.gitbook/assets/image (103).png" alt=""><figcaption></figcaption></figure>
* Clica en :heavy\_plus\_sign:.
*   Se abrirá esta ventana:<br>

    <figure><img src="../../../.gitbook/assets/image (104).png" alt=""><figcaption></figcaption></figure>

    * **Grupo de recursos:** el recurso que ocupa este tipo de reserva.
    * **Minutos bloqueados antes de la reserva:** cuántos minutos antes se bloquea el recurso para prepararlo. Por ejemplo, si la reserva empieza a las 10:00 y pones 10 minutos, la pista se bloquea desde las 9:50.
    * **Duración:** la duración por defecto de la reserva.
    * **Duraciones permitidas:** las duraciones que se pueden elegir, en minutos y separadas por espacios (por ejemplo: `30 60 120`). Si lo dejas vacío, se calculan según la configuración del grupo de recursos.
    * **Recurso primario:** el recurso que se elige en primer lugar.
    * **Seleccionable online:** márcala para que el jugador pueda elegir este recurso al reservar por internet.
* Clica en **Guardar**.

> Si el tipo de reserva ocupa dos recursos (por ejemplo, pista y profesor), repite este paso para cada uno.
{% endstep %}
{% endstepper %}

## Si algo no funciona

* **El tipo de reserva no aparece al reservar en una pista:** añade esa pista en la pestaña **Recursos** del tipo de reserva (paso 3).
