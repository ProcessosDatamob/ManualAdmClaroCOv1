# Modo Quiosco

Esta configuración tiene como objetivo permitir la creación de un entorno en el que el usuario del dispositivo solo pueda acceder a las aplicaciones previamente autorizadas por el administrador, es decir, solo se mostrarán los íconos de las aplicaciones seleccionadas en la pantalla del dispositivo.

Para acceder a la configuración del "Modo Quiosco", siga estos pasos:&#x20;

1. En la pantalla "Editar política", seleccione la pestaña "Modo Quiosco".&#x20;
2. Active el modo quiosco haciendo clic en el botón de activación.

<figure><img src="../../.gitbook/assets/image (5).png" alt=""><figcaption></figcaption></figure>

3. En la pantalla se mostrará un mensaje de confirmación. Confirme haciendo clic en el botón "Activar".

<figure><img src="../../.gitbook/assets/image (1) (1) (1) (1) (1) (1) (1).png" alt=""><figcaption></figcaption></figure>

4. Al activar el Modo Quiosco en la política y aprovisionar un dispositivo con esta política, la aplicación Kiosk Launcher Manager se instalará automáticamente en el dispositivo.

<figure><img src="../../.gitbook/assets/image (2) (1) (1) (1) (1).png" alt=""><figcaption></figcaption></figure>

5. Cuando el dispositivo instala la aplicación Kiosk, esta aplicación capturará la lista de todos los programas instalados en el dispositivo y enviará esta lista al Portal. Además, enviará las siguientes configuraciones gestionadas al portal:
   * Fondo de pantalla
   * Orientación de la pantalla
   * Lista de aplicaciones mostradas

También cambiará el lanzador (launcher) del dispositivo para el lanzador de la aplicación Kiosk, no permitirá que el usuario cambie el lanzador en el dispositivo y mantendrá la configuración del Modo Quiosco recibida en la política.

El fondo de pantalla se puede cargar en la política y se puede establecer la orientación de la pantalla, que se enviarán a la aplicación.

<figure><img src="../../.gitbook/assets/image (20).png" alt=""><figcaption></figcaption></figure>

Los aplicativos que se mostrarán en el dispositivo serán definidos en la política, es decir, solo los aplicativos autorizados en la política se mostrarán en el lanzador.
