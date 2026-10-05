# Personalizar precio de reservas por minutos de juego

Hay un gran número de personalizaciones que podemos hacer con el programa, entre ellas está la de personalizar el precio de una reserva en función de los minutos de duración, sin tener la necesidad de crear un producto nuevo.

Para hacer esto, los pasos a seguir son:

{% stepper %}
{% step %}
### Acceso a Configuración de Ventas

* Dirígete al menú de configuración situado en la esquina superior derecha.
* Clica en **Ventas** y directamente, se redirigirá a la pestaña de **Productos**.
{% endstep %}

{% step %}
### Acceso al producto

**El siguiente paso es clave** cuando se quiere aplicar un descuento. Especialmente en el caso de las reservas, donde existen diferentes franjas horarias como hora punta o hora valle, es fundamental identificar exactamente a qué servicio y a qué franja se va a aplicar ese descuento.

* Localiza en el listado el producto en cuestión.
*   Clica sobre el id, se redirigirá a la pestaña general del producto en cuestión.

    <div align="left"><figure><img src="../../../.gitbook/assets/image (90).png" alt=""><figcaption></figcaption></figure></div>
*   Selecciona la pestaña de **Precios especiales.**<br>

    <div align="left"><figure><img src="../../../.gitbook/assets/image (91).png" alt=""><figcaption></figcaption></figure></div>
{% endstep %}

{% step %}
### Crear precio especial

* Clica en :heavy\_plus\_sign:
*   Se abre una ventana que ha de cumplimentarse solo los siguientes campos:<br>

    <div align="left"><figure><img src="../../../.gitbook/assets/image (92).png" alt=""><figcaption></figcaption></figure></div>

    * **Minutos:** escribimos la duración a la que queremos estipular un nuevo precio (Ej: 60’, 120’, 180’, etc).
    * **Precio Bruto:** escribe con números el nuevo precio. Si se desea que salga gratis, tendría que poner el precio a cero.
* Clica en guardar para salvar cambios.
{% endstep %}
{% endstepper %}

Si el descuento debe afectar a más de una franja o a distintos tipos de producto, este proceso deberá repetirse para cada uno de ellos, asegurando así que la tarifa reducida se aplique solo donde corresponde y evitando errores en los precios.

Si se quiere establecer un precio distinto para cada número de participantes, es necesario crear una configuración por cada caso: una para 60 min, otra para 120, otra para 180, y así sucesivamente, repitiendo el proceso tantas veces como precios diferentes se quieran definir.
