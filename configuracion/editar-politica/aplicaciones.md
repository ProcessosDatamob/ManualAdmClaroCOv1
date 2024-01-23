# Aplicaciones

La pestaña de configuración de aplicaciones le permite administrar configuraciones, permisos, establecer el modo de instalación, así como, incluir y eliminar aplicaciones.

La pantalla "Editar política" situada en la pestaña "Aplicaciones" se muestra a continuación.

<figure><img src="../../.gitbook/assets/Captura de tela 2023-11-07 110836.png" alt=""><figcaption></figcaption></figure>

Las pantallas tienen las siguientes partes, según la numeración en la figura:

1. Modo de selección de aplicaciones en Play Store - permite controlar cómo se mostrarán las aplicaciones en los dispositivos registrados en esta política. En el modo "Restricta", los usuarios solo pueden ver e instalar desde Google Play Store las aplicaciones elegidas por el administrador. Las otras aplicaciones se eliminarán y no estarán disponibles en los dispositivos.

El modo “Abierta” permite la instalación de aplicaciones que no están en la Google Play Administrada, o sea el usuario podrá consultar e instalar cualquier aplicación disponible en la tienda Play Store.&#x20;

{% hint style="info" %}
**NOTA**

Al seleccionar la opción “Abierta”, las aplicaciones agregadas a la política mostrarán el tipo de instalación: Instalación Forzada, al entender que todas las aplicaciones ya están disponibles.
{% endhint %}

2. Utilice el cuadro de búsqueda para buscar aplicaciones dentro de la lista que aparece.
3. Lista de aplicaciones incluidas.
4. Tipo de instalación - Elija el tipo de instalación de cada dispositivo. Los tipos de instalación son: disponible, preinstalado, instalación forzada o bloqueado.

{% hint style="info" %}
**NOTA**

Si el usuario elige la opción “pre-instalada” deberá considerar que las aplicaciones se instalaran en ese momento ignorando si el dispositivo está en WIFI o si está usando la red de datos lo que podría traducirse en un alto consumo de datos. Es necesario asegurarse que el dispositivo esté conectado a WIFI si se utilizarán APPs “Pre-instaladas”.
{% endhint %}

5. Se pueden realizar más acciones ("...") con la aplicación: Configuración administrada, Permisos, Configuración avanzada y Quitar aplicación.
6. Agregar aplicaciones - permite agregar aplicaciones para la gestión. Importante: Las aplicaciones deben agregarse primero con Google Play Managed.&#x20;

## Agregar aplicaciones

La opción Agregar aplicaciones tendrá diferentes comportamientos cuando el Modo Quiosco está activado o desactivado.

* Modo Quiosco Desactivado: Al hacer clic en el botón "Agregar aplicaciones", si se trata de una política con Modo Quiosco Desactivado, se mostrará la lista de aplicaciones que se han agregado utilizando Google Play Administrada.
* Modo Quiosco Habilitado: Si la política que se está editando es una política con el Modo Quiosco Habilitado, al hacer clic en el botón Agregar aplicaciones, se mostrarán las 3 opciones para agregar las aplicaciones.



<figure><img src="../../.gitbook/assets/Captura de tela 2024-01-11 143003.png" alt=""><figcaption></figcaption></figure>

### Sistema

Haga clic en la opción "Sistema", y abrirá la pantalla "Añadir del sistema" Seleccionar el fabricante y el dispositivo Seleccionar una o más aplicaciones haciendo clic en la casilla Haga clic en el botón "Añadir seleccionados"

### Playstore

Haga clic en la opción "Playstore", y abrirá la pantalla "Agregar aplicaciones" Seleccionar una o más aplicaciones haciendo clic en la casilla Haga clic en el botón "Añadir seleccionados"

{% hint style="info" %}
IMPORTANTE

Las aplicaciones deben agregarse primero con Google Play Administrado.
{% endhint %}

### Manual

Haga clic en la opción "Manual", y abrirá la pantalla "Agregar aplicaciones manualmente" Rellenar los campos: Nombre de la aplicación (opcional), Nombre del paquete y haga clic en "Agregar".



## **Configuraciones Administradas**

Para acceder a la configuración administrada de una aplicación, debe estar en la pantalla "Editar política" con la pestaña "Aplicaciones" seleccionada. Siga los siguientes pasos:

1. Localice la aplicación deseada y haga clic en los tres puntos al final de la línea para mostrar el menú con más opciones;
2. Haga clic en "Configuración administrada".

<figure><img src="../../.gitbook/assets/Captura de tela 2023-11-06 174309.png" alt=""><figcaption></figcaption></figure>

{% hint style="info" %}
**IMPORTANTE**

La aplicación Security Browser es el navegador web predeterminado del sistema Claro Monitor Empresarial y con él es posible gestionar bloqueos de sitios por URL y categoría, así como monitorear la navegación del usuario. Consulte la "[Bloqueo de Sitios Web - Security Browser](../../bloqueo-de-sitios-web-security-browser.md)" para obtener información detallada sobre la instalación y configuración de la aplicación Security Browser.
{% endhint %}

Después del paso 2 se mostrará la siguiente pantalla. En esta pantalla tenemos los siguientes elementos:

3. Identificación de la aplicación seleccionada y la pantalla de configuración elegida ("Configuración administrada");
4. Lista de configuraciones administradas disponibles para la aplicación seleccionada. Al hacer clic en cada fila se muestran las preferencias;
5. Enlace para volver a la lista de aplicaciones.

![](<../../.gitbook/assets/3 (8).png>)

## **Permisos**

Para acceder a la configuración de permisos de una aplicación, debe estar en la pantalla "Editar política" con la pestaña "Aplicaciones" seleccionada. Siga los siguientes pasos:

1. Localice la aplicación deseada y haga clic en los tres puntos al final de la línea para mostrar el menú con más opciones;
2. Haga clic en "Permisos".

![](<../../.gitbook/assets/4 (6).png>)

Después del paso 2 se mostrará la siguiente pantalla. La lista blanca, que se puede configurar en la aplicación seleccionada, se muestra en esta pantalla.

![](<../../.gitbook/assets/5 (6).png>)

Los permisos se pueden configurar como: Solicitar al usuario, Activada o Denegada.

## **Configuraciones Avanzadas**

Para acceder a la configuración avanzada de una aplicación, debe estar en la pantalla "Editar política" con la pestaña "Aplicaciones" seleccionada. Siga los siguientes pasos:

1. Localice la aplicación deseada y haga clic en los tres puntos al final de la línea para mostrar el menú con más opciones;
2. Haga clic en "Configuración avanzada".

![](<../../.gitbook/assets/6 (6).png>)

Después del paso 2 se mostrará la siguiente pantalla. En esta pantalla tenemos los siguientes elementos:

* **Prioridad de actualización -** Establezca la prioridad de actualización de la aplicación como predefinida, retrasada o prioritaria.
* **Versión mínima -** permite definir una versión mínima de la aplicación.

![](<../../.gitbook/assets/7 (6).png>)

## **Eliminar Aplicación**

Para eliminar una aplicación de la directiva, debe estar en la pantalla "Editar política" con la pestaña "Aplicaciones" seleccionada. Siga los siguientes pasos:

1. Localice la aplicación deseada y haga clic en los tres puntos al final de la línea para mostrar el menú con más opciones;
2. Haga clic en "Eliminar aplicación".

![](<../../.gitbook/assets/8 (6).png>)

Después del paso 2 se mostrará la siguiente pantalla para confirmar la eliminación. Haga clic en el botón "Eliminar" para eliminar la aplicación de la lista.

![](<../../.gitbook/assets/9 (6).png>)

{% hint style="info" %}
**NOTA**

La aplicación se eliminará de la lista de aplicaciones de la política que se está editando, pero permanecerá en Aplicaciones administradas, se puede volver a incluir en la política y puede formar parte de la configuración de otras políticas.
{% endhint %}
