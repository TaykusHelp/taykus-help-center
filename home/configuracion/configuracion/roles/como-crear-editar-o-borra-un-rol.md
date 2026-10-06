---
icon: lock
---

# Cómo crear, editar o borrar un rol

Los **roles** deciden qué puede ver y hacer cada trabajador en Taykus. Cada usuario tiene un rol, y ese rol marca sus permisos en cada parte del programa.

### Vídeo explicativo

{% embed url="https://youtu.be/Vk6PSU2hFQU" %}

## Dónde están los roles

* Clica en el icono <i class="fa-gear" style="color:blue;">:gear:</i> de la esquina superior derecha y entra en **Configuración**.
* Clica en **Roles**.

<figure><img src="../../.gitbook/assets/image (7).png" alt=""><figcaption></figcaption></figure>

Verás el listado de roles y podrás abrir cada uno para ver sus permisos.

## Roles que vienen creados

<figure><img src="../../.gitbook/assets/image (9).png" alt=""><figcaption></figcaption></figure>

* **Admin Centro:** acceso completo a todo el programa.
* **Recepción:** acceso completo a reservas, academia y comunicaciones, y parcial a configuración.
* **Profesor:** acceso parcial a calendario, academia y jugadores.
* **Soporte Taykus:** acceso completo, para que el equipo de soporte pueda ayudarte con dudas o incidencias.

> Si no quieres que los profesores entren al programa como administradores, puedes darles una dirección de acceso solo para profesores, donde verán únicamente sus clases, alumnos y calendario. Por ejemplo: `https://mariademo.taykusdemo.com/teachers/login`

## Niveles de permisos

Cada rol tiene varios bloques de permisos. Junto a cada permiso puedes activar o desactivar estos niveles:

![](<../../.gitbook/assets/image (10).png>)

* **Ver:** el usuario puede ver la información.
* **Editar:** el usuario puede cambiar la información. Según el permiso, también puede crear, borrar o exportar.

## Modificar los permisos de un rol

{% stepper %}
{% step %}
### Abrir el rol

* Ve a **Configuración › Roles**.
* Clica sobre el **ID** del rol.
{% endstep %}

{% step %}
### Activar o desactivar permisos

* Revisa los bloques de permisos.
* Clica sobre el nivel que quieres cambiar:
  * En **verde**, el permiso está activado.    ![](<../../.gitbook/assets/image (11).png>)
  * En **rojo**, está desactivado.    ![](<../../.gitbook/assets/image (12).png>)
* Los cambios se guardan solos; no hace falta pulsar Guardar.
{% endstep %}
{% endstepper %}

## Crear un rol nuevo

{% stepper %}
{% step %}
### Crear el rol

* Ve a **Configuración › Roles**.
* Clica en la opción para crear un rol nuevo.
* Escribe el nombre del rol y guarda.
{% endstep %}

{% step %}
### Configurar sus permisos

* Abre el rol desde su **ID**.
* Activa o desactiva los permisos como se explica en el apartado anterior.
{% endstep %}
{% endstepper %}

## Borrar un rol

{% stepper %}
{% step %}
### Comprobar que nadie lo usa

* Antes de borrar un rol, revisa que ningún usuario lo tenga asignado. Si no, ese trabajador podría quedarse sin acceso.
{% endstep %}

{% step %}
### Borrar el rol

* Ve a **Configuración › Roles**.
* Abre el rol desde su **ID**.
* Usa la opción de borrar.
{% endstep %}
{% endstepper %}
