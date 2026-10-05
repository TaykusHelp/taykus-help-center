---
icon: circle-user-clock
---

# Cómo asignar un profesor a un horario

Los profesores se gestionan dentro del sistema como recursos, igual que las pistas o los deportes. Esto permite asignarlos a horarios y actividades para que puedan reservarse correctamente y evitar solapamientos en la planificación.

Antes de poder añadir un profesor a un horario, es necesario haber creado previamente su recurso en el sistema. Si todavía no se ha hecho, consulta primero el siguiente artículo:\
[como-anadir-a-un-profesor-nuevo.md](../grupo-de-recursos/como-anadir-a-un-profesor-nuevo.md "mention")

Una vez creado el recurso, solo queda vincularlo al horario correspondiente. A continuación te explicamos cómo hacerlo:

{% stepper %}
{% step %}
### Acceso a Configuración de Reservas

* Dirígete a la esquina superior derecha y clica en el icono de Configuración.
* En el desplegable que se abre, selecciona configuración.
*   Luego accede a Reservas.

    <div align="left"><figure><img src="../../../.gitbook/assets/image (40).png" alt=""><figcaption></figcaption></figure></div>


{% endstep %}

{% step %}
### Acceso a los horarios ya creados

*   Localiza el bloque Horarios y haz clic.

    <div align="left"><figure><img src="../../../.gitbook/assets/image (41).png" alt=""><figcaption></figcaption></figure></div>
*   Haz clic sobre el id del Horario.<br>

    <figure><img src="../../../.gitbook/assets/image (18).png" alt=""><figcaption></figcaption></figure>
*   Dirígete a la pestaña de **Horas de Apertura.**<br>

    <figure><img src="../../../.gitbook/assets/image (19).png" alt=""><figcaption></figcaption></figure>
{% endstep %}

{% step %}
### Asignar horario al profesor

* Clica en :heavy\_plus\_sign:
*   Se abre una ventana para cumplimentar de la siguiente manera:<br>

    <figure><img src="../../../.gitbook/assets/image (45).png" alt=""><figcaption></figcaption></figure>

    * **Recurso:** se busca y añade el nombre del profesor nuevo creado
    * **Inicio:** hora de inicio de este profesor.
    * **Fin:** hora de finalización de este profesor.
    * **Finaliza al dia siguiente:** marca la esta casilla si este horario termina igual o mayor que las 00:00
    * **Intervalos en minutos:** Define cada cuántos minutos se divide el calendario en bloques de tiempo disponibles para reservar. Por ejemplo, un intervalo de 30 minutos mostrará franjas de 09:00, 09:30, 10:00, 10:30, etc., sobre las que se construirán las reservas de profesores.
    * **Duración mínima:** Indica el tiempo mínimo que debe durar una reserva de un profesor. No puede ser menor que el intervalo y tiene que ser múltiplo de este.
    * **Duración máxima:** Indica el tiempo máximo que puede durar una reserva de un profesor. Tiene que ser múltiplo del intervalo.
* Clica en guardar para salvar cambios.
{% endstep %}

{% step %}
### Comprobar la disponibilidad del profesor en el horario

* Existen dos formas de comprobar que el profesor se ha asignado correctamente al horario:
  * **Primera:**&#x20;
    *   Dirígete al calendario y crea una reserva que implique seleccionar un profesor.

        <figure><img src="../../../.gitbook/assets/image (20).png" alt=""><figcaption></figcaption></figure>
    *   Comprueba que el profesor aparece en el listado de recursos disponibles y que puede seleccionarse.

        <figure><img src="../../../.gitbook/assets/image (21).png" alt=""><figcaption></figcaption></figure>
    * Intenta completar la reserva. Si el sistema permite realizarla, significa que el recurso está correctamente configurado.\
      ![](<../../../.gitbook/assets/image (22).png>)
  * **Segunda:**
    *   Dirígete al calendario y haz clic en la pestaña **Profesores**.<br>

        <figure><img src="../../../.gitbook/assets/image (23).png" alt=""><figcaption></figcaption></figure>
    *   Comprueba que el nombre del profesor aparece en la parrilla del calendario.

        <figure><img src="../../../.gitbook/assets/image (24).png" alt=""><figcaption></figcaption></figure>
{% endstep %}
{% endstepper %}

Comprobar el horario tras asignar un profesor es un paso fundamental para asegurarse de que el recurso está disponible y puede utilizarse sin incidencias. Realizar esta verificación evita errores en reservas futuras y garantiza que la planificación del calendario funcione correctamente.
