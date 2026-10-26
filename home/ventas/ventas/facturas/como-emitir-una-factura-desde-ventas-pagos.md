# Cómo emitir una factura desde Ventas > Pagos

Desde **Ventas › Pagos** puedes emitir la factura de una venta a partir de su pago. Se hace igual que desde **Ventas › Líneas**, pero en este listado hay que clicar en el número de la columna **Venta**.

A continuación, se detallan los pasos a seguir:

### Antes de empezar

Antes de emitir la factura, revisa que estén creados estos datos en:

* **Configuración > Ventas > Empresas**
* **Configuración > Ventas > Empresas clientes**

Para saber cómo hacerlo, consulta estos artículos:

<a href="https://app.gitbook.com/s/V0h7jTfpeuZY1RmPEtNK/configuracion/ventas/empresas/como-configurar-los-datos-de-empresa" class="button primary">Cómo configurar los datos de empresa</a>

<a href="https://app.gitbook.com/s/V0h7jTfpeuZY1RmPEtNK/configuracion/ventas/empresas-clientes/como-crear-empresas-cliente-en-el-sistema" class="button primary">Cómo crear empresas cliente en el sistema</a>

{% stepper %}
{% step %}
### Acceso a Ventas - Pagos

* En el menú lateral, accede a **Ventas**.
* Haz clic en **Pagos**.
*   Busca el pago de la venta que quieras facturar.<br>

    <figure><img src="../../.gitbook/assets/pagos-listado.png" alt=""><figcaption></figcaption></figure>
{% endstep %}

{% step %}
### Cómo emitir la factura

* Una vez localizado el pago, haz clic sobre el número de la columna **Venta** (no sobre el **Id**).
*   Dentro de la venta, pulsa el botón **Emitir factura**.<br>

    <figure><img src="../../.gitbook/assets/image (7).png" alt=""><figcaption></figcaption></figure>
* Se abrirá una ventana con los datos de facturación.
{% endstep %}

{% step %}
### Completar los datos de la factura

En el bloque **Emisor**:

* Selecciona la **empresa emisora** en el campo **Empresa**.
* El sistema rellenará automáticamente los datos asociados, como:
  * Nombre
  * CIF
  * Email
  * Teléfono

<figure><img src="../../.gitbook/assets/image (8).png" alt=""><figcaption></figcaption></figure>

En el bloque **Cliente**, puedes elegir entre dos opciones:

**Persona física**

Si la factura es para un particular:

* Deja marcada la opción **Persona física**.
* Revisa o completa los datos del cliente:
  * Nombre completo
  * DNI
  * Email
  * Teléfono
  * Dirección

<figure><img src="../../.gitbook/assets/image (9).png" alt=""><figcaption></figcaption></figure>

**Empresa**

Si la factura es para una empresa:

* Marca la opción **Empresa**.
* En el campo **Empresa cliente**, selecciona la empresa correspondiente.
* El sistema completará automáticamente los datos fiscales de esa empresa.

<figure><img src="../../.gitbook/assets/image (10).png" alt=""><figcaption></figcaption></figure>


{% endstep %}

{% step %}
### Guardar la factura

* Cuando todos los datos estén revisados, pulsa el icono de **guardar**.
* El sistema generará la factura asociada a esa venta.
{% endstep %}
{% endstepper %}

> **Importante:** en **Ventas › Cobros con Bonos** se hace exactamente igual: clica en el número de la columna **Venta** y sigue los mismos pasos.
