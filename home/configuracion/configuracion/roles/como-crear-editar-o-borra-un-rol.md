---
icon: lock
---

# Cómo crear, editar o borra un rol

En Taykus, los roles permiten definir qué puede ver y hacer cada usuario dentro del programa. Cada trabajador deberá tener asignado un rol, y ese rol determinará los permisos que tendrá sobre las diferentes áreas del sistema.

En este artículo veremos cómo consultar los roles existentes, modificar sus permisos, crear nuevos roles y eliminar aquellos que ya no sean necesarios.

### Video Explicativo

En el siguiente video se muestra cómo gestionar los roles dentro de Taykus:

{% embed url="https://youtu.be/Vk6PSU2hFQU" %}

{% stepper %}
{% step %}
### Acceso al apartado de Roles

* Para acceder a la configuración de roles, entra en Configuración.
* Clica sobre Roles.

<figure><img src="../../.gitbook/assets/image (7).png" alt=""><figcaption></figcaption></figure>

* Desde este apartado podrás ver el listado de roles disponibles en el sistema y acceder a la configuración de permisos de cada uno de ellos.
{% endstep %}

{% step %}
### Roles creados por defecto

*   Por defecto, Taykus incluye varios roles ya creados:<br>

    <figure><img src="../../.gitbook/assets/image (9).png" alt=""><figcaption></figcaption></figure>

    *   **Admin Centro**

        Permite tener acceso completo a todo el programa.
    *   **Recepción**

        Permite el acceso completo a reservas, academia y comunicaciones, además de un acceso parcial a configuración.
    *   **Profesor**

        Permite un acceso parcial a calendario, academia y jugadores.

    > **Nota importante:**\
    > Si no queremos que los profesores entren al programa como administradores, y solo queremos que puedan ver sus clases, alumnos y calendarios, podemos facilitarles una URL de acceso exclusiva para profesores.
    >
    > Ejemplo:\
    > `https://mariademo.taykusdemo.com/teachers/logi`

    *   **Soporte Taykus**

        Permite el acceso completo al programa para que el equipo de soporte pueda ayudar en la gestión de dudas o resolución de incidencias.
{% endstep %}

{% step %}
### Niveles de permisos

Dentro de cada rol encontraremos diferentes bloques de permisos. En cada bloque se muestra un listado con todos los permisos disponibles y, a la derecha de cada uno, los niveles que podemos activar o desactivar.

Los niveles de permisos son:\
![](<../../.gitbook/assets/image (10).png>)

* **Ver:**\
  Permite que el usuario pueda ver la información ya creada.
* **Editar:**\
  Permite que el usuario pueda modificar registros ya creados. Según el permiso, también puede permitir crear nuevos registros, eliminarlos o exportarlos.
{% endstep %}
{% endstepper %}

***

### Cómo modificar los permisos de un rol

Para modificar los permisos de un rol ya existente:

1. Accede a **Configuración > Roles**.
2. Localiza el rol que quieres modificar.
3. Haz clic sobre el **ID** del rol.
4. Dentro del rol, revisa los diferentes bloques de permisos.
5. Activa o desactiva los niveles de permisos que necesites.

Para cambiar un permiso, simplemente haz clic sobre el nivel correspondiente:

* Si el permiso está permitido, aparecerá en **verde**.\
  ![](<../../.gitbook/assets/image (11).png>)
* Si el permiso está desactivado, aparecerá en **rojo**.\
  ![](<../../.gitbook/assets/image (12).png>)

Los cambios se guardan automáticamente, por lo que no será necesario pulsar ningún botón adicional de guardar.

***

### Cómo crear un nuevo rol

También puedes crear un nuevo rol personalizado para tus trabajadores.

Para hacerlo:

1. Accede a **Configuración > Roles**.
2. Haz clic en la opción para crear un nuevo rol.
3. Introduce el nombre del rol.
4. Guarda los cambios.
5. Una vez creado, accede al rol desde su **ID**.
6. Configura los permisos necesarios siguiendo el mismo proceso explicado anteriormente.

De esta forma podrás adaptar los permisos según las funciones reales de cada trabajador dentro del centro.

***

### Cómo eliminar un rol

Si necesitas eliminar un rol que ya no se utiliza:

1. Accede a **Configuración > Roles**.
2. Entra en el rol correspondiente desde su **ID**.
3. Utiliza la opción de eliminación disponible.

Antes de eliminar un rol, es recomendable revisar que ningún usuario lo tenga asignado, para evitar que algún trabajador pierda acceso o permisos dentro del programa.

***

La gestión de roles permite controlar el acceso de cada usuario dentro de Taykus y adaptar los permisos según las funciones de cada trabajador. Así, cada persona podrá acceder únicamente a las áreas que necesita para realizar su trabajo, manteniendo una configuración más segura y ordenada dentro del centro.
