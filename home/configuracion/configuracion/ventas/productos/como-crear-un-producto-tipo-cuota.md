# Cómo crear un producto tipo Cuota

Los productos de tipo **Cuota** son los que se cobran de forma periódica, como una mensualidad, una cuota trimestral o una suscripción anual. En su ficha se define cada cuánto se cobran y cómo, para que el sistema gestione los cobros recurrentes.

A continuación, se detallan los pasos a seguir:

{% stepper %}
{% step %}
### Acceso a Productos

* Clica en el icono <i class="fa-gear" style="color:blue;">:gear:</i> de la esquina superior derecha y entra en **Configuración**.
* Clica en **Ventas**. Se abrirá directamente la pestaña **Productos**.
{% endstep %}

{% step %}
### Crear el producto

* Clica en :heavy\_plus\_sign:.
* Se abrirá la ficha del producto.
{% endstep %}

{% step %}
### General

<figure><img src="../../../.gitbook/assets/producto-cuota-general.png" alt=""><figcaption></figcaption></figure>

* **Logo:** opcional. Ayuda a reconocer el producto en el TPV. Puedes subir una imagen con **Explorar…** o elegir una de la **Galería**.
* **Nombre:** nombre descriptivo de la cuota. Campo obligatorio.
* **Categoría:** viene marcada como **Artículo** por defecto. Cámbiala a **Cuota**.
* **Precio bruto:** precio de venta al público, con impuestos. Campo obligatorio.
* **Precio neto:** precio sin impuestos. Se calcula automáticamente según el tipo de impuesto.
* **Tipo de impuestos:** elige en el desplegable el impuesto que se aplica a la cuota. Campo obligatorio.
* **Tipo de producto:** elige uno de los tipos de producto que ya tengas creados.
* **Puntos de fidelización:** cantidad que se recarga en el bono monedero del cliente por cada unidad comprada, en la unidad mínima de tu moneda (en euros, céntimos). Por ejemplo, si escribes 2, el cliente recibe 2 céntimos por cada unidad que compre.
{% endstep %}

{% step %}
### Venta online

* **Detalle:** texto opcional para explicar las condiciones de la cuota.
* **Venta online:** márcala si se puede comprar por internet.
* **Tendencia:** destaca la cuota en la venta online como opción recomendada.
* **Popular:** marca la cuota como opción popular.
{% endstep %}

{% step %}
### Venta periódica

<figure><img src="../../../.gitbook/assets/producto-cuota-venta-periodica.png" alt=""><figcaption></figcaption></figure>

* **Periodicidad:** elige en el desplegable cada cuánto se cobra la cuota.
* **Prorratear primero:** márcala para que, al inscribirse a mitad de periodo, el primer cobro sea proporcional.
* **Inscripción:** para cobrar una matrícula o inscripción. Elige un producto de tipo **Artículo** (créalo antes si no lo tienes). Consulta [Cómo crear un producto tipo Artículo](como-crear-un-producto-tipo-articulo.md).
* **Tipo Cliente Membresía:** al suscribirse a la cuota, el cliente pasa automáticamente a tener este tipo de cliente.
* **Tipo Cliente Baja Membresía:** al terminar la cuota, el cliente pasa automáticamente a tener este tipo de cliente.
* **Facturación bancaria:** márcala si la cuota se cobra por domiciliación.

> **Membresías:** con los dos campos de tipo de cliente, una cuota funciona como la de un gimnasio. Mientras el cliente la tiene, pasa a ser del tipo que elijas (por ejemplo, **Socio**) y disfruta de sus ventajas, como precios especiales. Cuando se da de baja, pasa al tipo de baja que hayas indicado. Consulta [Qué es una membresía y cómo funciona](../../../../ventas/ventas/cuotas/que-es-una-membresia-y-como-funciona.md).
{% endstep %}

{% step %}
### Cuotas automáticas

* **Días Cortesía Impago:** días que se esperan, desde el vencimiento, antes de cancelar la cuota por impago.
* **Emisión Automática:** márcala para que las cuotas se emitan solas el día siguiente a su vencimiento, sin tener que hacerlo a mano. Consulta [Cómo automatizar la emisión de cuotas](../../../../ventas/ventas/cuotas/como-automatizar-la-emision-de-cuotas.md).
* **Cancelar con Impago:** si la cuota no se paga en los días de cortesía, deja de emitirse y, si es una membresía, el cliente pasa al tipo de baja. Consulta [Cómo automatizar la cancelación por impago](../../../../ventas/ventas/cuotas/como-automatizar-la-cancelacion-por-impago.md).

> En los desplegables solo aparecen cinco opciones. Si no ves la que buscas, empieza a escribir su nombre.
{% endstep %}

{% step %}
### Guardar

* Clica en **Guardar**.
{% endstep %}
{% endstepper %}

Una vez creada, puedes gestionar las cuotas de cada jugador. Para saber cómo, consulta este artículo:

<a href="../../../../ventas/ventas/cuotas/como-ver-las-cuotas.md" class="button primary">Cómo ver las cuotas</a>
