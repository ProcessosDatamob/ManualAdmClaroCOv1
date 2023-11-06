# DASHBOARD

Esta pantalla del sistema tiene como objetivo permitir al usuario la visualización y análisis de los diversos datos de consumos y usos recolectados de los dispositivos. Todos estos datos se detallarán en esta sección.

Para saber cómo acceder y analizar los datos mostrados en el Dashboard, siga los pasos descritos en esta sección.

1. La pantalla de Dashboard puede ser considerada la "Pantalla de Inicio" del sistema, pues se muestra tan pronto accedas al Portal, pero también se puede acceder haciendo clic en el menú "Dashboard". En un primer acceso, los indicadores de usuarios, dispositivos y consumos no tendrán aún información, por lo que estarán en cero.

<figure><img src=".gitbook/assets/image (7).png" alt=""><figcaption></figcaption></figure>

Al acceder a la pantalla, toda la información se mostrará separada por secciones. Cada sección corresponde a un dato diferente, recogido del dispositivo y toda la información se muestra de acuerdo con las opciones seleccionadas en el filtro (Empresa, Grupo o Usuario).

2. Al habilitar la opción de filtro "Roaming internacional", el sistema solo mostrará la información del consumo total de datos móviles del dispositivo y el consumo de SMS registrada cuando el dispositivo esté usando una conexión de roaming, pero no será posible ver el consumo de datos por aplicación y sitios web accedidos. No se muestran consumos en Wi-Fi ni en otras redes.

![](<.gitbook/assets/11 (4) (1).png>)

Los filtros "Empresa", "Grupo" y "Usuario" permiten realizar un análisis de los datos de los dispositivos de un nivel determinado.

3. Haga clic en el filtro "Empresa", escriba y seleccione el nombre de la empresa para mostrar la información recopilada de todos los dispositivos.

![](<.gitbook/assets/12 (4) (1).png>)

4. Haga clic en el filtro "Grupo", escriba y seleccione el nombre del grupo para mostrar la información recopilada de todos los dispositivos que forman parte de un grupo.

![](<.gitbook/assets/13 (4) (1).png>)

5. Haga clic en el filtro "Usuario" escriba y seleccione el usuario, para mostrar la información recopilada del dispositivo del usuario.

![](<.gitbook/assets/14 (4) (1).png>)

6. En la esquina superior derecha de la pantalla, tenemos algunos iconos que tienen las siguientes características:

* Notificaciones - En el icono ![](https://lh7-us.googleusercontent.com/LIqOOPLli\_-KQv0gbnkeBAgAG1\_EOWziv1kRkMmMtO2dOIvA17vDOpWbmtTw5\_2RUg1D-mUt1PWNvciaKyYAHysUPk47UBQ8yIufI8DmrX523Zqn\_ntcDKa0ff0KqkWZeeaDLHoJF9MB762IkIm6vw)el administrador puede ver las notificaciones del portal, por ejemplo, al solicitar la generación de un reporte.
* Salir - En el icono ![](https://lh7-us.googleusercontent.com/j1m2nV5Ek3EskKpbxU7f3L0pjGzk6bS\_IIhQcyG4gRWelRLC\_6CN6hWe5Q0n6z9dbN0vBiMMud6KV3tcG32wbF2i5trJ4F\_LxOeabAJFWyk3CJHmOgKvA8k9rmZqgc2yYZ\_fvvqCrdaxIesPrvL0nw) el administrador puede salir del portal y también está disponible allí el número de versión;

<figure><img src=".gitbook/assets/image (8).png" alt=""><figcaption></figcaption></figure>

**Barra de Estado**

La barra de estado de Dashboard muestra la situación actual de todos los usuarios y licencias de la empresa.

![](<.gitbook/assets/18 (4) (1).png>)

**Total de Usuarios**

Este indicador muestra el número total de usuarios de dispositivos que utilizan la aplicación <mark style="background-color:orange;">\<NomeProduto></mark>.

![](<.gitbook/assets/19 (4).png>)

**Total de Licencias**

Este indicador muestra el número total de licencias disponibles en el portal <mark style="background-color:orange;">\<NomeProduto></mark>.

![](<.gitbook/assets/20 (4).png>)

**Licencias sin uso**

Este indicador muestra el número total de licencias que no tienen dispositivo registrado en el portal. Es decir, son las licencias disponibles.

Al hacer clic en este indicador, el sistema mostrará la pantalla "Licencias contratadas". Para saber cómo usar esta pantalla, lea la sección "Licencias contratadas".

![](<.gitbook/assets/21 (1).png>)

**Dispositivos**

Este indicador muestra el número total de dispositivos que están activos en el sistema y los dispositivos sin comunicación. Además, permite al administrador tener la visibilidad de los dispositivos que están en Modo Quiosco.

![](<.gitbook/assets/0 (3) (1).png>)

* **TOTAL -** Estos dispositivos se consideran "activos" al instalar y activar la aplicación <mark style="background-color:orange;">\<NomeProduto></mark>. Al hacer clic en "Total" el indicador mostrará la pantalla "Lista de dispositivos" que contiene el reporte con la información clave de los dispositivos activos
* **SIN COMUNICACIÓN -** Este indicador muestra el número total de dispositivos que no están enviando datos a los servidores durante un período prolongado. Al hacer clic en "Sin comunicación" el sistema muestra la pantalla de dispositivos sin comunicación.

![Interface gráfica do usuário

Descrição gerada automaticamente com confiança baixa](<.gitbook/assets/1 (3) (1).png>)

Esta falta de comunicación puede ocurrir cuando el dispositivo se encuentra en las siguientes situaciones:

* Desconectado;
* Sin conexión a Internet;
* Aplicación desinstalada.

El cálculo de tiempo para considerar el dispositivo sin comunicación se basa en dos datos enviados por el dispositivo:

* Envío de consumos generales/información del dispositivo;
* Envío periódico de estado "Activo".

En caso de que pase más de 10 minutos y el Portal no reciba un de estos datos, el dispositivo es considerado como "Sin comunicación" y envía un comando al dispositivo para intentar restablecer la comunicación. Dependiendo de la situación del dispositivo, el restablecimiento de la comunicación puede ocurrir o no.

Al hacer clic en este indicador, el sistema mostrará una pantalla que contiene el reporte con la información de los dispositivos que no se comunican.

**Consumo de Datos**

Este indicador muestra el porcentaje de consumo de datos móviles de los dispositivos durante el ciclo con respecto al límite total configurado en el perfil de consumo. Si no se establece un límite en el perfil de consumo, el gráfico no muestra el porcentaje y el sistema solo muestra el valor total de datos en MB utilizado.

![Diagrama

Descrição gerada automaticamente](<.gitbook/assets/2 (3) (1).png>)

**Consumo de SMS**

Este indicador muestra el porcentaje de consumo de SMS enviados por los dispositivos durante el ciclo con respecto al límite total configurado en el perfil de consumo. Si no se establece un límite en el perfil de consumo, el gráfico no muestra el porcentaje y solo muestra el valor total de SMS utilizado.

![Uma imagem contendo Diagrama

Descrição gerada automaticamente](<.gitbook/assets/3 (3) (1).png>)

**Consumo de Datos por Aplicación**

Este gráfico muestra las 5 aplicaciones que más han consumido datos móviles durante el ciclo. Los datos mostrados se ordenan en porcentaje.

El valor porcentual de cada una de las 5 aplicaciones se calcula en relación con la suma total de consumo de todas las aplicaciones durante el ciclo.

Al hacer clic en el botón “Ver lista completa” el sistema exhibirá en pantalla todos los datos de las aplicaciones. Para saber cómo utilizar esa pantalla, lea la sección “[Aplicaciones](configuracion/editar-politica/aplicaciones.md)” en este manual.

![Uma imagem contendo Interface gráfica do usuário

Descrição gerada automaticamente](<.gitbook/assets/4 (3) (1).png>)

**Consumo de Datos por Usuario**

Esta gráfica muestra los 5 usuarios que más han consumido datos móviles durante el ciclo. Los datos mostrados se ordenan en porcentaje.

El valor porcentual de cada uno de los 5 usuarios se calcula en relación con la suma total de consumo de todos los usuarios durante el ciclo.

Al hacer clic en el botón "Ver lista completa" el sistema mostrará la pantalla con la información de consumo de la empresa. Para saber cómo utilizar esta pantalla, lea la sección "[Consumo dela empresa](empresa/consumo-de-la-empresa.md)" de este manual.

![Gráfico

Descrição gerada automaticamente](<.gitbook/assets/5 (3) (1).png>)

**Tiempo de uso por aplicación**

Este gráfico muestra las 5 aplicaciones más utilizadas durante el ciclo. Este tiempo se cuenta solo cuando la aplicación está en uso, y no necesita estar consumiendo datos. Las aplicaciones en segundo plano no se contabilizan en este análisis. También no se contabilizan uso en Wi-Fi ni en otras redes.

El valor porcentual de cada una de las 5 aplicaciones se calcula en relación con la suma total del tiempo de uso de todas las aplicaciones durante el ciclo.

Al hacer clic en el botón "Ver lista completa" el sistema mostrará la pantalla con la información de todas las aplicaciones. Para saber cómo utilizar esta pantalla, lea la sección "[Aplicaciones](configuracion/editar-politica/aplicaciones.md)" de este manual.

![](<.gitbook/assets/6 (3) (1).png>)

**Inventario de Dispositivos**

Este indicador muestra el porcentaje de los 5 fabricantes de dispositivos activos. El valor porcentual de cada uno de los 5 fabricantes se calcula en relación con la suma total de todos los dispositivos activos.

![Gráfico, Gráfico de explosão solar

Descrição gerada automaticamente](<.gitbook/assets/7 (2) (1) (1).png>)

**Sitios más visitados**

Este indicador muestra el porcentaje de los 5 sitios más visitados en los dispositivos durante el ciclo. El valor porcentual de cada uno de los 5 sitios se calcula en relación a la suma total de todos los accesos a los sitios durante el ciclo.

{% hint style="warning" %}
**ATENCIÓN**

Los sitios web visitados son obtenidos por el navegador web predeterminado del sistema Control Móvil Empresarial. Este navegador se llama Security Browser y necesita estar instalado y configurado en los dispositivos. Para obtener más información sobre la administración y configuración del navegador, visite el capítulo 16 Security Browser.
{% endhint %}

![Gráfico, Gráfico de barras

Descrição gerada automaticamente](<.gitbook/assets/8 (2) (1) (1).png>)

**Indicador de Consumo y su Historial**

Este indicador muestra en porcentaje los datos móviles y SMS consumidos en los últimos 6 ciclos. Para realizar el análisis individual de los consumos de datos móviles o SMS, acceda al punto "Consumos" en el menú "Empresa".

![Gráfico, Gráfico de barras

Descrição gerada automaticamente](<.gitbook/assets/9 (2) (1) (1).png>)

**Indicador de Nuevos Usuarios de dispositivos y su Historial**

Este indicador muestra la cantidad de usuarios de dispositivos activados en los últimos 6 ciclos y la evolución de los nuevos usuarios del ciclo actual con respecto a los del trimestre y del semestre.

Para realizar el análisis individual de los usuarios de dispositivos, haga clic en "Lista de dispositivos" en el menú "Dispositivos".

![Gráfico, Gráfico de barras

Descrição gerada automaticamente](<.gitbook/assets/10 (2) (1) (1).png>)

**Ubicación de los Dispositivos**

El mapa muestra la última ubicación de los dispositivos. Para que la ubicación se muestre y actualice, el dispositivo debe estar conectado a Internet, debe haber señal GPS y la configuración de "Modo de Localización" debe estar "Activa" en Ubicación en la política aplicada al dispositivo.

Lea la sección "Administrar políticas" de este manual para saber cómo activar el "Modo de ubicación" de los dispositivos.

La ubicación de los dispositivos se muestra con un marcador en el mapa, que puede estar en color verde o rojo, dependiendo del estado del dispositivo (verde = enviando datos y rojo = sin envío de datos). Para ver la información de la ubicación, haga clic en el marcador.

Utilice los recursos del mapa para optimizar la visualización de las ubicaciones.

![](<.gitbook/assets/11 (2) (1).png>)

![](<.gitbook/assets/12 (2) (1).png>)

**Manuales para Descargar**

En esta pantalla tendremos acceso a los manuales descargables. Al hacer clic en "Más información", se mostrará la pantalla con Documentos y Materiales de Apoyo.

![Uma imagem contendo Forma

Descrição gerada automaticamente](<.gitbook/assets/13 (2) (1).png>)

![Interface gráfica do usuário, Aplicativo

Descrição gerada automaticamente](<.gitbook/assets/14 (2) (1).png>)

**Alguna Duda**

A través de la sesión “_Alguna duda?_" tendremos acceso a la pantalla donde es posible visualizar las preguntas frecuentes realizadas por los usuarios:

![Interface gráfica do usuário, Aplicativo

Descrição gerada automaticamente](<.gitbook/assets/15 (1) (1) (1).png>)

Al hacer clic en "Más información", nos dirigiremos a la siguiente pantalla, donde es posible realizar una búsqueda a través del campo de escritura libre o bien filtrar por categoría.

<figure><img src=".gitbook/assets/image (1).png" alt=""><figcaption></figcaption></figure>

Al desplazar la pantalla más abajo, tendremos acceso a la lista de preguntas frecuentes

Y al final de la página tendremos acceso también a los manuales de descarga, así como tenemos en el Dashboard.

<figure><img src=".gitbook/assets/image.png" alt=""><figcaption></figcaption></figure>
