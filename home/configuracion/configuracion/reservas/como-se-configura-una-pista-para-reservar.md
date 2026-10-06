---
icon: list-check
---

# Cómo se configura una pista para reservar

Para que una pista se pueda reservar no basta con crearla: hacen falta seis piezas configuradas y conectadas entre sí. Normalmente todo esto queda hecho en la configuración inicial del club, pero es importante conocer la cadena completa cuando añades una pista nueva, cambias horarios o algo no aparece como esperabas.

## Las seis piezas, en orden

{% stepper %}
{% step %}
### Deporte (grupo de recursos)

Por ejemplo, _Pádel_. Agrupa las pistas de un mismo deporte y define cómo se divide el calendario y cuánto pueden durar las reservas.

[como-crear-un-recurso.md](grupo-de-recursos/como-crear-un-recurso.md "mention")
{% endstep %}

{% step %}
### Pista (recurso)

Por ejemplo, _Pádel 1_. Se crea dentro de su deporte.

[como-crear-un-recurso.md](grupo-de-recursos/como-crear-un-recurso.md "mention")
{% endstep %}

{% step %}
### Horario

La pista tiene que estar añadida en las **Horas de apertura** de un horario. Si no, no aparece en el calendario.

[como-crear-un-horario.md](horarios/como-crear-un-horario.md "mention")
{% endstep %}

{% step %}
### Precio (producto tipo Servicio)

El producto que marca cuánto cuesta la reserva. Por ejemplo, _Pádel hora punta – 90 min – 30 €_.

[como-crear-un-producto-tipo-servicio.md](../ventas/productos/como-crear-un-producto-tipo-servicio.md "mention")
{% endstep %}

{% step %}
### Precios por calendario

El producto se asigna a las franjas horarias de la pista. Las franjas tienen que cubrir **todo** el horario de apertura.

[como-poner-precios-al-horario.md](precios-por-calendario/como-poner-precios-al-horario.md "mention")
{% endstep %}

{% step %}
### Tipo de reserva

La pista tiene que estar añadida en la pestaña **Recursos** del tipo de reserva. Si no, ese tipo de reserva no aparece como opción al reservar en esa pista.

[como-crear-un-tipo-de-reserva.md](tipos-de-reserva/como-crear-un-tipo-de-reserva.md "mention")
{% endstep %}
{% endstepper %}

## Si algo no funciona

Casi siempre el problema es que una de las piezas no está conectada con las demás.

* **La pista no aparece en el calendario.**\
  Comprueba que la pista está añadida en las **Horas de apertura** del horario (paso 3).
* **Al reservar no aparece el tipo de reserva que quiero.**\
  Añade la pista en la pestaña **Recursos** de ese tipo de reserva (paso 6).
* **La reserva sale a 0 €.**\
  Revisa los **precios por calendario** (paso 5):
  * Que la pista esté añadida en la franja.
  * Que la franja cubra la hora de la reserva.
  * Si la franja termina a las 00:00 o más tarde, que esté marcada **Finaliza al día siguiente**.
* **He ampliado el horario y no me deja reservar en las horas nuevas.**\
  Al ampliar el horario de apertura (paso 3), amplía también la franja en **precios por calendario** (paso 5). Las dos tienen que coincidir.
