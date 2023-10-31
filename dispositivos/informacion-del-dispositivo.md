# Información del Dispositivo

La información del dispositivo que se muestra en la lista es:

* **Usuario** - nombre del usuario registrado en el portal;
* **Identificación -** Identificación registrada para el dispositivo;
* **Teléfono** - número de teléfono;
* **IMEI** - número interno y único en cada dispositivo. En Android 10 ya no es posible capturar esta información del dispositivo porque utilizamos otro método para recibir esta información con el Enriquecimiento de URL;
* **ICCID** - número de la tarjeta SIM;
* **Modelo** - modelo de dispositivo;

Al hacer clic en el signo ">" junto al usuario el sistema muestra más información como se puede ver en la imagen de abajo.

![](<../.gitbook/assets/3 (5).png>)

* **Política -** nombre de la directiva asignada al dispositivo;
* **Fabricante -** nombre del fabricante del dispositivo;
* **Sistema operativo -** versión de Android o iOS;
* **Fecha de registro -** fecha y hora de registro del dispositivo;
* **Grupo -** grupo al que está asociado el dispositivo;
* **Status-** indica el estado del dispositivo. Los estados que puede tener un dispositivo están en la siguiente tabla.

<table data-header-hidden><thead><tr><th width="229"></th><th></th></tr></thead><tbody><tr><td><strong>Estado</strong></td><td><strong>Descripción</strong></td></tr><tr><td>Activo</td><td>El dispositivo está activo.</td></tr><tr><td>Desactivado</td><td>El dispositivo está desactivado.</td></tr><tr><td>Eliminado</td><td>El dispositivo ha sido eliminado. Este estado se usa en el reporte de estado final cuando el dispositivo confirma la eliminación.</td></tr><tr><td>Aprovisionando</td><td>Se está aprovisionando el dispositivo. Los dispositivos recién registrados permanecen en ese estado hasta que se aplica una directiva.</td></tr></tbody></table>

**Opciones de administración de dispositivos**

En la pantalla "Dispositivos" se puede acceder a las opciones de consulta y configuración del dispositivo utilizando los tres puntos "..." que aparecen a la derecha en la lista de dispositivos. Las opciones disponibles se muestran en la siguiente imagen.

![](<../.gitbook/assets/4 (5).png>)

Las opciones resaltadas en la figura se detallan en las siguientes subsecciones.

* **Historial de la Batería**

Para ver el historial de batería del dispositivo, haga clic en "Historial de batería".

El sistema mostrará la pantalla del historial de batería del dispositivo.

1. Seleccione una fecha para ver los datos del historial.
2. Desplazar el cursor sobre el gráfico para ver los valores en un momento específico.

<figure><img src="../.gitbook/assets/image (1) (1).png" alt=""><figcaption></figcaption></figure>

**Historial de Almacenamiento**

Para ver el historial de memoria libre en el almacenamiento interno del dispositivo, haga clic en "Historial de almacenamiento".

![](<../.gitbook/assets/6 (5).png>)

El sistema mostrará la pantalla del "Historial de almacenamiento" con el historial de memoria libre del dispositivo. Seleccione una fecha, para visualizar los datos del histórico.

Desplace el cursor sobre el gráfico para ver los valores en una hora específica.

**Reporte de no conformidad**

Para ver las inconsistencias en la configuración asignada al dispositivo, utilice la opción "reporte de no conformidad".

![](<../.gitbook/assets/7 (5).png>)

**Alterar Política**

Al elegir Alterar política, aparecerá en el centro de la pantalla un cuadro de diálogo para elegir la política que se asignará al dispositivo. Elija la política entre las políticas enumeradas y haga clic en actualizar para cambiar la política del dispositivo.

La política define las preferencias, incluidos los criterios de hardware, software, sistema operativo, seguridad, etc. Para obtener más información sobre Políticas, lea la sección de configuración de este manual.

![](<../.gitbook/assets/8 (5).png>)

**Deshabilitar Dispositivo**

Cuando se envía el comando 'Desactivar Dispositivos', se desactivan (o quedan bloqueadas) todas las aplicaciones que no son de Google, se permiten llamadas telefónicas y el estado del dispositivo cambian a "desactivado". Para desactivar un dispositivo, utilice la opción "Deshabilitar Dispositivo" en el menú de opciones del dispositivo. Esta opción solo está disponible para dispositivos que tienen el estado "Activo".

Para confirmar la operación, en la pantalla de confirmación haga clic en el botón "Deshabilitar".

**Activar dispositivo**

Esta opción solo aparece para dispositivos que están en el estado "Deshabilitado". Para activar un dispositivo deshabilitado, haga clic en "Activar dispositivo" en las opciones de administración del dispositivo.

![](<../.gitbook/assets/9 (5).png>)

Confirme la actualización haciendo clic en "Activar dispositivo" en el cuadro de diálogo, como se muestra en la secuencia.

![](<../.gitbook/assets/10 (4).png>)

**Desconectar la pantalla del dispositivo**

La opción "Apagar pantalla" envía un comando para apagar la pantalla del dispositivo. Al hacer clic en la opción "Apagar pantalla" el comando se ejecuta directamente y un mensaje aparecerá en la pantalla para informar que el comando ha sido enviado al dispositivo.

**Reiniciar el dispositivo**

Esta operación envía una orden para reiniciar el dispositivo. Seleccione la opción "Reiniciar dispositivo". Se muestra un mensaje en la pantalla del portal para confirmar el envío de la orden. El mensaje mostrado se muestra a continuación.

![](<../.gitbook/assets/11 (4).png>)

![](<../.gitbook/assets/12 (4).png>)

**Generar nueva contraseña del dispositivo**

El sistema permite generar una nueva contraseña para el dispositivo. Para realizar esta operación, elija la opción "Generar nueva contraseña del dispositivo" como se muestra en la imagen que se muestra a continuación.

![](<../.gitbook/assets/13 (4).png>)

Rellene los campos "Nueva contraseña" y "Confirmar nueva contraseña" con valores iguales para que el botón "Confirmar" esté habilitado. Al clicar en confirmar, la contraseña cambiará automáticamente. Opcionalmente, y según la necesidad, podrán ser marcadas las opciones:

* No permitir que otros administradores cambien la contraseña de nuevo hasta que el usuario la ingrese en el dispositivo;
* No pedir credenciales de usuario al iniciar el dispositivo;
* Bloquear el dispositivo después de restablecer la contraseña.

La pantalla para generar nueva contraseña del dispositivo se muestra a continuación.

![](<../.gitbook/assets/14 (4).png>)

**Remover dispositivo (WIPE)**

Esta operación le permite eliminar un dispositivo. Limpia los datos y configuraciones del dispositivo. Los dispositivos eliminados no aparecen en la lista de dispositivos de la empresa. La opción "Eliminar dispositivo" aparece en la lista de opciones del dispositivo en la pantalla de lista de dispositivos (menú "Dispositivos", opción "Listar dispositivos").

![](<../.gitbook/assets/15 (4).png>)

Como se puede ver en la siguiente imagen, se muestra un mensaje en la pantalla para información y advertencia. La operación no se puede deshacer, por lo tanto, confirme solo cuando esté seguro de que desea eliminar el dispositivo.

![](<../.gitbook/assets/16 (3).png>)

**Administrar información**

Esta opción permite acceder a la pantalla para editar datos del dispositivo, como: Usuario, identificación y Grupo.

![](<../.gitbook/assets/17 (3).png>)

![](<../.gitbook/assets/18 (3).png>)

Además de poder editar los datos, se muestran más abajo en la pantalla dos listas con la información de Software y Hardware relacionados con el dispositivo administrado:

![](<../.gitbook/assets/19 (2).png>)

**Información de Software**

* **Sistema operativo** - informa el nombre del sistema operativo;
* **Número de serie** - número de serie del dispositivo;
* **En conformida**d - es la adhesión del dispositivo a todas las configuraciones de políticas asignadas a él. Si no se ha aplicado alguna configuración, el valor de esta opción será "No". Puede acceder al "Reporte de no conformidad" en los tres puntos al final de la línea del dispositivo.
* **Estado Aplica**do - estado asignado al dispositivo;
* **Última fecha de Actualización** - fecha y hora en que se sincronizó la información del dispositivo con el portal. Esta fecha proviene de AMAPI (Google API), es decir, es la información que recopila la API de Google en el dispositivo;
* **Fecha de sincronización de polític**as - fecha y hora de la última sincronización de políticas;
* **Versión de Android** - informa el número de la versión de Android.
* **Versión de la política aplicada en el dispositivo** - informa el número de la versión aplicada en el dispositivo.
* **Nombre de la Política en el Portal** - nombre de la directiva asignada al dispositivo;
* **Nombre de la política aplicada en el Dispositivo** - Informa el nombre de la política aplicada en el dispositivo.

**Información sobre el hardware**

* **Almacenamiento Interno** - cuánto de almacenamiento interno tiene;
* **Batería** - ¿Cuántos % de batería está actualmente;
