# Modo Quiosco

Esta configuración tiene como objetivo permitir la creación de un entorno en el que el usuario del dispositivo solo pueda acceder a las aplicaciones previamente autorizadas por el administrador, es decir, solo se mostrarán los íconos de las aplicaciones seleccionadas en la pantalla del dispositivo.

Para acceder a la configuración del "Modo Quiosco", siga estos pasos:&#x20;

1. En la pantalla "Editar política", seleccione la pestaña "Modo Quiosco".&#x20;
2. Active el modo quiosco haciendo clic en el botón de activación.

<figure><img src="../../.gitbook/assets/Captura de tela 2024-01-11 135757.png" alt=""><figcaption></figcaption></figure>

3. En la pantalla se mostrará un mensaje de confirmación. Confirme haciendo clic en el botón "Activar".

<figure><img src="../../.gitbook/assets/image (19).png" alt=""><figcaption></figcaption></figure>

4. Al activar el Modo Quiosco en la política y aprovisionar un dispositivo con esta política, la aplicación Kiosk Launcher Manager se instalará automáticamente en el dispositivo.

<figure><img src="../../.gitbook/assets/image.png" alt=""><figcaption></figcaption></figure>

5. Cuando el dispositivo instala la aplicación Kiosk, esta aplicación capturará la lista de todos los programas instalados en el dispositivo y enviará esta lista al Portal. Además, enviará las siguientes configuraciones gestionadas al portal:
   * Fondo de pantalla
   * <mark style="background-color:orange;">Color de fuente de los iconos</mark>&#x20;
   * <mark style="background-color:orange;">Orientación de pantalla</mark>&#x20;
   * <mark style="background-color:orange;">Tamaño de iconos y fuentes</mark>&#x20;
   * <mark style="background-color:orange;">Ordenación de los iconos</mark>&#x20;
   * <mark style="background-color:orange;">Posicionamiento de la imagen</mark>

También cambiará el lanzador (launcher) del dispositivo para el lanzador de la aplicación Kiosk, no permitirá que el usuario cambie el lanzador en el dispositivo y mantendrá la configuración del Modo Quiosco recibida en la política.

<mark style="background-color:orange;">**Fondo de pantall**</mark><mark style="background-color:orange;">a - se puede realizar la carga de una imagen de fondo de pantalla en la política y establecer la orientación de la pantalla, que se enviará a la aplicación</mark>

<mark style="background-color:orange;">**Color de fuente de los iconos**</mark> <mark style="background-color:orange;"></mark><mark style="background-color:orange;">- permite configurar el color del texto de los iconos en la pantalla de inicio</mark>

<mark style="background-color:orange;">**Orientación de pantalla**</mark> <mark style="background-color:orange;"></mark><mark style="background-color:orange;">- permite seleccionar la orientación de pantalla para el dispositivo, y el valor predeterminado es: "Definido por el usuario"</mark>

<mark style="background-color:orange;">**Tamaño de iconos y Fuentes**</mark> <mark style="background-color:orange;"></mark><mark style="background-color:orange;">- permite seleccionar las siguientes opciones de tamaño de pantalla: Estándar del sistema (predeterminado), Pequeño (75%) y Grande (125%)</mark>

<mark style="background-color:orange;">**Ordenación de los iconos**</mark> <mark style="background-color:orange;"></mark><mark style="background-color:orange;">- permite realizar la ordenación de los iconos</mark>

<mark style="background-color:orange;">**Posicionamiento de la imagen**</mark> <mark style="background-color:orange;"></mark><mark style="background-color:orange;">- permite seleccionar la posición de la imagen del fondo de pantalla en la pantalla de inicio del dispositivo</mark>

<mark style="background-color:orange;">Las aplicaciones que se mostrarán en el dispositivo se establecerán en la directiva, es decir, solo las aplicaciones liberadas en la directiva se mostrarán en Laucher.</mark>
