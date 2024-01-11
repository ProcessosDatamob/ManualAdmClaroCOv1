# Opciones de administración de dispositivos

<mark style="background-color:orange;">En la pantalla de "Dispositivos" dentro de "Lista de Dispositivos" se puede acceder a la información del dispositivo haciendo clic en el botón de información:</mark>

<figure><img src="../../.gitbook/assets/Captura de tela 2024-01-11 144211.png" alt=""><figcaption></figcaption></figure>

### <mark style="background-color:orange;">Detalles</mark>&#x20;

* <mark style="background-color:orange;">Usuario - nombre del usuario registrado en el portal;</mark>&#x20;
* <mark style="background-color:orange;">Identificación - Identificación registrada para el dispositivo;</mark>&#x20;
* <mark style="background-color:orange;">Teléfono - número de teléfono;</mark>&#x20;
* <mark style="background-color:orange;">IMEI - número interno y único en cada dispositivo. En Android 10 ya no es posible capturar esta información del dispositivo porque utilizamos otro método para recibir esta información con el Enriquecimiento de URL;</mark>&#x20;
* <mark style="background-color:orange;">ICCID - número de chip SIM;</mark>&#x20;
* <mark style="background-color:orange;">Modelo - modelo de dispositivo;</mark>&#x20;
* <mark style="background-color:orange;">Fabricante - nombre del fabricante del dispositivo;</mark>&#x20;
* <mark style="background-color:orange;">Sistema Operativo - sistema operativo del dispositivo;</mark>&#x20;
* <mark style="background-color:orange;">Versión de Android - versión de Android del dispositivo;</mark>&#x20;

### <mark style="background-color:orange;">Instalación</mark>&#x20;

* <mark style="background-color:orange;">Fecha de registro - fecha de registro de los dispositivos;</mark>&#x20;
* <mark style="background-color:orange;">Modo de gestión - muestra el modo de gestión utilizado;</mark>&#x20;
* <mark style="background-color:orange;">Versión de la aplicación - versión de Companion instalado en el dispositivo;</mark>&#x20;
* <mark style="background-color:orange;">Nombre de la Política en el Portal - nombre de la directiva asignada al dispositivo;</mark>&#x20;
* <mark style="background-color:orange;">Fecha de la última comunicación - mostrará la fecha en que el dispositivo se comunicó por última vez con el portal;</mark>&#x20;

### <mark style="background-color:orange;">Hardware</mark>&#x20;

* <mark style="background-color:orange;">Almacenamiento Interno - cuánto de almacenamiento interno tiene;</mark>
* <mark style="background-color:orange;">Batería - Cuántos % de batería está actualmente;</mark>&#x20;

<mark style="background-color:orange;">Y haciendo clic en los tres puntos "..." a la derecha en la lista de dispositivos, aparecen las opciones de consulta y configuraciones del dispositivo, como se ilustra en la imagen de abajo:</mark>

<figure><img src="../../.gitbook/assets/Captura de tela 2023-11-03 143049.png" alt=""><figcaption></figcaption></figure>

Las opciones disponibles se muestran en la siguiente tabla:

<table><thead><tr><th width="233">Modo de Gestión</th><th>Opciones disponibles</th></tr></thead><tbody><tr><td>Android</td><td><p>Historial de la Batería </p><p>Historial de Almacenamiento</p><p>Reporte de no Conformidad </p><p>Alterar Politica </p><p>Habilitar/ Deshabilitar el dispositivo</p><p>Apagar Pantalla </p><p>Reiniciar Dispositivo </p><p>Generar nueva contraseña de dispositivo </p><p>Remover dispositivo (WIPE)</p><p>Administrar Información</p></td></tr><tr><td>Android Block SIM</td><td><p>Historial de la Batería </p><p>Historial de Almacenamiento</p><p>Reporte de no Conformidad </p><p>Alterar Política </p><p>Habilitar/ Deshabilitar el dispositivo</p><p>Apagar Pantalla </p><p>Reiniciar Dispositivo </p><p>Quitar Bloqueo de Pantalla</p><p>Remover dispositivo (WIPE)</p><p>Administrar Información</p></td></tr></tbody></table>

Las opciones resaltadas en la figura se detallan en las siguientes subsecciones.

**Historial de la Batería**

Para ver el historial de batería del dispositivo, haga clic en "Historial de batería".

El sistema mostrará la pantalla del historial de batería del dispositivo.

1. Seleccione una fecha para ver los datos del historial.
2. Desplazar el cursor sobre el gráfico para ver los valores en un momento específico.

<figure><img src="../../.gitbook/assets/image (23).png" alt=""><figcaption></figcaption></figure>

**Historial de Almacenamiento**

Para ver el historial de memoria libre en el almacenamiento interno del dispositivo, haga clic en "Historial de almacenamiento".

![](<../../.gitbook/assets/6 (5).png>)

El sistema mostrará la pantalla del "Historial de almacenamiento" con el historial de memoria libre del dispositivo. Seleccione una fecha, para visualizar los datos del histórico.

Desplace el cursor sobre el gráfico para ver los valores en una hora específica.

**Reporte de no conformidad**

Para ver las inconsistencias en la configuración asignada al dispositivo, utilice la opción "reporte de no conformidad".

![](<../../.gitbook/assets/7 (5).png>)

**Alterar Política**

Al elegir Alterar política, aparecerá en el centro de la pantalla un cuadro de diálogo para elegir la política que se asignará al dispositivo. Elija la política entre las políticas enumeradas y haga clic en actualizar para cambiar la política del dispositivo.

La política define las preferencias, incluidos los criterios de hardware, software, sistema operativo, seguridad, etc. Para obtener más información sobre Políticas, lea la sección de configuración de este manual.

<figure><img src="../../.gitbook/assets/image (8).png" alt=""><figcaption></figcaption></figure>

**Deshabilitar Dispositivo**

Cuando se envía el comando 'Desactivar Dispositivos', se desactivan (o quedan bloqueadas) todas las aplicaciones que no son de Google, se permiten llamadas telefónicas y el estado del dispositivo cambian a "desactivado". Para desactivar un dispositivo, utilice la opción "Deshabilitar Dispositivo" en el menú de opciones del dispositivo. Esta opción solo está disponible para dispositivos que tienen el estado "Activo".

Para confirmar la operación, en la pantalla de confirmación haga clic en el botón "Deshabilitar".

<figure><img src="../../.gitbook/assets/image (9).png" alt=""><figcaption></figcaption></figure>

**Activar dispositivo**

Esta opción solo aparece para dispositivos que están en el estado "Deshabilitado". Para activar un dispositivo deshabilitado, haga clic en "Activar dispositivo" en las opciones de administración del dispositivo.

Confirme la actualización haciendo clic en "Activar dispositivo" en el cuadro de diálogo.

**Desconectar la pantalla del dispositivo**

La opción "Apagar pantalla" envía un comando para apagar la pantalla del dispositivo. Al hacer clic en la opción "Apagar pantalla" el comando se ejecuta directamente y un mensaje aparecerá en la pantalla para informar que el comando ha sido enviado al dispositivo.

**Reiniciar el dispositivo**

Esta operación envía una orden para reiniciar el dispositivo. Seleccione la opción "Reiniciar dispositivo". Se muestra un mensaje en la pantalla del portal para confirmar el envío de la orden. El mensaje mostrado se muestra a continuación.

<figure><img src="../../.gitbook/assets/image (10).png" alt=""><figcaption></figcaption></figure>

**Generar nueva contraseña del dispositivo**

El sistema permite generar una nueva contraseña para el dispositivo. Para realizar esta operación, elija la opción "Generar nueva contraseña del dispositivo".

Rellene los campos "Nueva contraseña" y "Confirmar nueva contraseña" con valores iguales para que el botón "Confirmar" esté habilitado. Al clicar en confirmar, la contraseña cambiará automáticamente. Opcionalmente, y según la necesidad, podrán ser marcadas las opciones:

* No permitir que otros administradores cambien la contraseña de nuevo hasta que el usuario la ingrese en el dispositivo;
* No pedir credenciales de usuario al iniciar el dispositivo;
* Bloquear el dispositivo después de restablecer la contraseña.

La pantalla para generar nueva contraseña del dispositivo se muestra a continuación.

<figure><img src="../../.gitbook/assets/image (11).png" alt=""><figcaption></figcaption></figure>

**Remover dispositivo (WIPE)**

Esta operación le permite eliminar un dispositivo. Limpia los datos y configuraciones del dispositivo. Los dispositivos eliminados no aparecen en la lista de dispositivos de la empresa. La opción "Eliminar dispositivo" aparece en la lista de opciones del dispositivo en la pantalla de lista de dispositivos (menú "Dispositivos", opción "Listar dispositivos").

Como se puede ver en la siguiente imagen, se muestra un mensaje en la pantalla para información y advertencia. La operación no se puede deshacer, por lo tanto, confirme solo cuando esté seguro de que desea eliminar el dispositivo.

<figure><img src="../../.gitbook/assets/image (12).png" alt=""><figcaption></figcaption></figure>

**Administrar**

Esta opción permite acceder a la pantalla para editar datos del dispositivo, como: Usuario, identificación y Grupo.

<figure><img src="../../.gitbook/assets/Captura de tela 2024-01-11 145454.png" alt=""><figcaption></figcaption></figure>

Además de poder editar los datos, se muestran más abajo en la pantalla dos listas con la información de Software y Hardware relacionados con el dispositivo administrado:

### **Información de Software**

* Modo de gestión - muestra el modo de gestión utilizado&#x20;
* Versión de la aplicación - versión de Companion instalado en el dispositivo&#x20;
* Fecha de la última actualización - fecha y hora en que la información del dispositivo se sincronizó con el portal. Esta fecha proviene de AMAPI (API de Google), es decir, es la información recopilada por la API de Google en el dispositivo;&#x20;
* Nombre de la Política en el Portal - nombre de la directiva asignada al dispositivo;&#x20;

### Información sobre el hardware&#x20;

* Almacenamiento Interno - cuánto de almacenamiento interno tiene;&#x20;
* Batería - Cuántos % de batería está actualmente;
