---
icon: business-time
---

# Cómo crear un tipo de reserva

Los tipos de reserva son categorías que asignan características específicas (como color, precio y duración) a cada reserva. Esto permite diferenciar el propósito de la reserva, como para la escuela, clases particulares, partidos, entre otros, y visualizarlo a través de un código de color en la ocupación. Además, los informes permiten consultar cuántas reservas corresponden a cada tipo. Otra funcionalidad importante es que los tipos de reserva permiten aplicar precios especiales, cobrando una tarifa distinta a la estándar, según el tipo de reserva asignado.

<div align="left"><figure><img src="../../../.gitbook/assets/image (96).png" alt=""><figcaption></figcaption></figure></div>

{% stepper %}
{% step %}
### Acceso a configuración de Reservas:

* Dirígete a la esquina superior derecha y clica en el icono de Configuración.
* En el desplegable que se abre, selecciona configuración.
* Luego accede a Reservas.\
  ![](<../../../.gitbook/assets/image (97).png>)
*   Localiza el bloque **Tipos de Reservas** y haz clic.<br>

    <figure><img src="../../../.gitbook/assets/image (98).png" alt=""><figcaption></figcaption></figure>
{% endstep %}

{% step %}
### Crear nuevo tipo de reserva

* Clica en :heavy\_plus\_sign:
*   Se abre una ventana que debemos de cumplimentar de la siguiente manera:<br>

    <figure><img src="../../../.gitbook/assets/image (99).png" alt=""><figcaption></figcaption></figure>

    <figure><img src="../../../.gitbook/assets/image (100).png" alt=""><figcaption></figcaption></figure>

    <figure><img src="../../../.gitbook/assets/image (101).png" alt=""><figcaption></figcaption></figure>

    <figure><img src="../../../.gitbook/assets/image (102).png" alt=""><figcaption></figcaption></figure>



    * **Descripción(\*):** Especifica el nombre del tipo de reserva.
    * **Categoría:** Si deseas, puedes añadir una subfamilia para este tipo.
    * **Tipo de Precio(\*):** Selecciona el tipo de precio del bono desde el desplegable:
      * **Por recurso:** Se acoge al precio configurado según los horarios.
      * **Por persona:** Se ajusta al precio de los horarios y se cobra a cada participante.
      * **Gratis:** No se cobrará ningún importe.
    * **Precio:** Establece un precio fijo para este tipo de reserva, independientemente de los precios por calendario.
    * **Reserva por Plaza:** Esta opción solo se selecciona si el tipo de precio es "Por persona".
    * **Orden:** Define el orden de aparición en el calendario para este tipo de reserva.
    * **Es Público:** Marca esta opción si deseas que el tipo de reserva sea accesible online.
    * **Permite Cancelar Online:** Si está activada, los usuarios podrán cancelar online. Si no, solo lo podrá hacer el administrador.
    * **Mínimo de minutos de anticipación:** Establece la anticipación mínima (en minutos) para realizar una reserva.
    * **Máximo de minutos de anticipación:** Define la anticipación máxima (en minutos) para realizar una reserva.
    * **Minutos de anticipación para cancelaciones:** Especifica el tiempo mínimo (en minutos) requerido para cancelar una reserva.
    * **Descripción Extendida:** Este campo es opcional, pero puedes usarlo para añadir detalles adicionales sobre este tipo de reserva.
    * **Imagen:** Si lo deseas, puedes asociar una imagen para facilitar la identificación del tipo de reserva.
    * **Minutos Pre Reserva:** Son los minutos que se guarda la pista mientras se realiza la reserva.
    * **Horas Antes que Expire:** Define el número de horas antes de que expire la reserva.
    * **Devolver Pago al Anular y Caducar:** Si seleccionas esta opción, el usuario recibirá el reembolso si la reserva es cancelada o caduca sin completarse.
    * **Número Mínimo de Participantes (\*):** Establece el mínimo de personas necesarias para este tipo de reserva.
    * **Número Máximo de Participantes (\*):** Establece el máximo de personas que pueden hacer este tipo de reserva.
    * **Nivel Mínimo:** Establece el nivel mínimo requerido para este tipo de reserva.
    * **Nivel Máximo:** Establece el nivel máximo requerido para este tipo de reserva.
    * **Género:** Elige entre tres opciones:
    * **Masculino:** Solo permite reservas para usuarios masculinos.
    * **Femenino:** Solo permite reservas para usuarias femeninas.
    * **Abierto:** Permite reservas para cualquier usuario.
    * **Permitir Personalizar Duración:** Esta opción permite editar la hora de fin de la reserva cuando se crea desde el administrador.
    * **Número Máximo de Reservas por Día:** Limita el número de reservas diarias que se pueden hacer de este tipo de reserva.
    * **Máximo Número de Reservas:** Si se establece la anticipación máxima, contará las reservas desde la fecha de creación hasta la anticipación máxima. Si no, contará todas las reservas desde la fecha de creación.
    * **Restricciones de Máximas Reservas Online y Admin:** Las restricciones aplican tanto a las reservas online como a las realizadas por el administrador.
    * **Colores:** Asigna diferentes colores para este tipo de reserva. Puedes elegir si deseas que el color sea fijo o que varíe dependiendo de su estado.
* _<mark style="background-color:yellow;">**Nota importante: Los apartados señalados con un asterisco (\*) son obligatorios para completar la creación del tipo de reserva.**</mark>_
{% endstep %}

{% step %}
### Añadir recursos

* Dentro de tipos de reserva, localiza la reserva creada y clica en id.
*   Clica sobre la pestaña de **Recursos.**

    <figure><img src="../../../.gitbook/assets/image (103).png" alt=""><figcaption></figcaption></figure>
* Clica en :heavy\_plus\_sign:
*   Se abre una ventana que deberemos de cumplimentar de la siguiente manera:<br>

    <figure><img src="../../../.gitbook/assets/image (104).png" alt=""><figcaption></figcaption></figure>

    * **Grupo de recursos:** selecciona en el desplegable, el recurso que se quiere bloquear.
      * _<mark style="background-color:yellow;">**Nota:**</mark> <mark style="background-color:yellow;"></mark><mark style="background-color:yellow;">si queremos bloquear dos recursos como pista y profesor, deberemos hacer este proceso como recursos se quieran bloquear.</mark>_
    * **Minutos bloqueados antes de la Reserva:** Indica cuántos minutos antes del inicio de la reserva el recurso quedará bloqueado para su preparación. Por ejemplo, si la reserva empieza a las 10:00 y se configuran 10 minutos, la pista se bloqueará a partir de las 9:50.
    * **Duración:** Indica la duración por defecto de la reserva.
    * **Duraciones Permitidas:** indican las duraciones que se permitirán para las reservas. Deben introducirse en minutos, usando solo números y separados por espacios (por ejemplo: 30 60 120). Si no se rellena este campo, el sistema calculará automáticamente las duraciones en base a la configuración del grupo de recursos.
    * **Recurso primario:** Recurso a seleccionar en primer lugar.
    * **Seleccionable Online:** Indica si el recurso podrá ser seleccionado por los usuarios en la reserva online. Si se marca esta opción, el jugador podrá elegirlo directamente desde internet.
* Clica en guardar para salvar cambios.
{% endstep %}
{% endstepper %}
