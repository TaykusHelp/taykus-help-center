---
icon: money-bill-transfer
---

# Generación del Q19 (Domiciliación de recibos bancarios)

En este artículo veremos cómo crear un archivo **Q19** para la gestión de remesas de cuotas, cómo añadir las líneas correspondientes y qué comprobaciones realizar antes de cerrarlo y descargarlo.

A continuación, te dejamos un video explicativo donde podrás conocer el paso a paso:

### Video Explicativo

{% embed url="https://youtu.be/IA2_rz0yjHM" %}

En este artículo detallaremos como realizar este proceso:

### Antes de empezar

Antes de generar un Q19, revisa que estén creados estos datos en:

* **Configuración > Ventas > Empresas**

Para saber como hacerlo puedes consultar el siguiente artículo:

* [antes-de-empezar-a-remesar.md](antes-de-empezar-a-remesar.md "mention")

{% stepper %}
{% step %}
### Acceso al apartado Q19

* Dirígete al menú izquierdo y selecciona **Ventas.**
* Haz clin en **Q19**.
*   Desde este apartado podrás consultar remesas ya creadas o generar una nueva.<br>

    <figure><img src="../../.gitbook/assets/image (12).png" alt=""><figcaption></figcaption></figure>
{% endstep %}

{% step %}
### Crear un nuevo archivo Q19

Una vez dentro de **Q19**, pulsa el botón de **añadir** para crear un nuevo archivo.

A continuación, completa los campos principales:

* **Descripción**: introduce un nombre identificativo para la remesa.\
  Ejemplo: **REMESA CUOTAS SOCIOS ABRIL 2026**
* **ID de emisor**: selecciona el emisor correspondiente.
*   **Comentarios**: este campo es opcional.<br>

    <figure><img src="../../.gitbook/assets/image (13).png" alt=""><figcaption></figcaption></figure>

Cuando hayas completado la información, pulsa en **Guardar**.
{% endstep %}

{% step %}
### Añadir las líneas al Q19

*   Una vez guardado el archivo, accede a la sección **Líneas Q19** y pulsa el botón **+** para añadir las líneas que se incluirán en la remesa.<br>

    <figure><img src="../../.gitbook/assets/image (14).png" alt=""><figcaption></figcaption></figure>
*   Se abrirá una ventana con las **Líneas de venta**, desde la que podrás localizar fácilmente las cuotas que deban incluirse en el archivo.<br>

    <figure><img src="../../.gitbook/assets/image (15).png" alt=""><figcaption></figcaption></figure>
{% endstep %}

{% step %}
### Filtrar correctamente las líneas

Para localizar únicamente las líneas que deben formar parte de la remesa, es importante aplicar los filtros adecuados.

* #### Estado del ticket
  * Filtra por **Pendiente**, para mostrar solo las líneas que todavía no han sido procesadas.
* #### Fecha de vencimiento
  * Utiliza este filtro para localizar las cuotas del periodo que deseas remesar.
* #### Tipo de producto
  * Filtra por **Cuotas Socio**, de forma que solo aparezcan las líneas correspondientes a cuotas de socios y no otros productos o reservas.

Una vez aplicados los filtros, selecciona las líneas que quieras incluir y pulsa en **Seleccionar**.
{% endstep %}

{% step %}
### Comprobar si existen errores

Puede saltar un aviso al seleccionar las líneas en el paso anterior de **Error**, seleccionamos **OK** y comprobamos dichos errores.

<figure><img src="../../.gitbook/assets/image (16).png" alt=""><figcaption></figcaption></figure>

*   Dentro del mismo archivo Q19 encontrarás también la pestaña **Errores**.<br>

    <figure><img src="../../.gitbook/assets/image (17).png" alt=""><figcaption></figcaption></figure>
* Desde esta pestaña podrás detectar incidencias antes de cerrar la remesa. Si alguna línea no debe incluirse o presenta algún problema, revísala antes de continuar y selecciona descartar.
* Además, desde el propio Q19 puedes eliminar líneas añadidas si necesitas corregir la selección.
{% endstep %}

{% step %}
### Revisar las líneas añadidas

*   Al volver al archivo Q19, verás las líneas incorporadas dentro del apartado **Líneas**.<br>

    <figure><img src="../../.gitbook/assets/image (18).png" alt=""><figcaption></figcaption></figure>
* Desde aquí podrás comprobar información como:
  * **Jugador**
  * **Titular de la cuenta**
  * **Concepto**
  * **Importe**
* Es importante revisar que las líneas incluidas sean correctas antes de continuar.
{% endstep %}

{% step %}
### Cerrar el archivo Q19

* Cuando hayas comprobado que todas las líneas son correctas, clica sobre cerrar.
* El programa abrirá un aviso informativo informado del importe total y número de pagos.\
  ![](<../../.gitbook/assets/image (19).png>)
* Clica sobre **OK.**
* Una vez hecho esto, el archivo cambiará su estado a **Cerrado.**
* Este paso es imprescindible para dejar el archivo preparado correctamente.
{% endstep %}

{% step %}
### Descargar el archivo

*   Cuando el estado del Q19 sea **Cerrado**, ya podrás utilizar la opción de **Descargar** para obtener el archivo generado.<br>

    <figure><img src="../../.gitbook/assets/image (20).png" alt=""><figcaption></figcaption></figure>
* Este será el archivo que podrás utilizar para la gestión de la remesa y subir al banco.
{% endstep %}
{% endstepper %}

Antes de cerrar y descargar el archivo, recuerda comprobar que las líneas incluidas correspondan al periodo correcto, que pertenezcan al tipo de producto **Cuotas Socio** y que no exista ninguna incidencia en la pestaña de errores.

De esta forma, podrás generar correctamente el archivo Q19 con las líneas que deban incluirse en la remesa.
