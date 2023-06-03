---
lab:
  title: "Ruta de aprendizaje \_2 - Laboratorio\_2.1: Crear un recorrido del cliente sencillo"
  learning path: Explore the fundamentals of Dynamics 365 Marketing
  module: Explore Dynamics 365 Marketing
---

Ruta de aprendizaje 2 - Módulo 1: Explorar Dynamics 365 Marketing
========================

## Laboratorio de prácticas 2.1: Crear un recorrido del cliente sencillo

## Objetivos

En este ejercicio comprobará que los recorridos del cliente son un componente clave de Dynamics 365 Marketing. Creará un recorrido del cliente para servir de base a todo esfuerzo de marketing por guiar la ruta que sigue un cliente mientras interactúa con el proceso de marketing de la organización. El objetivo es que cuando el recorrido esté completo, se convierta en ingresos.

## Configuración del laboratorio

  - **Tiempo estimado**: 20 minutos

## Instrucciones

1. Abra la **aplicación Dynamics 365 Marketing**.

2. Cambie el área a **Marketing saliente**. 

3. Con la navegación de la izquierda, seleccione **Contactos**, debajo del grupo **Clientes**.

4. En la barra de comandos, haga clic en **Nuevo**.

5. Complete la página de **Nuevo contacto** como sigue.

    - **Nombre**: Jenny

    - **Apellidos**: Jones (sus iniciales)

    - **Correo electrónico**: Escriba una dirección de correo electrónico en la que pueda recibir correos.

    - **Dirección 1 Calle 1:** 101 Sample Ave

    - **Dirección 1: Ciudad:** Fargo

    - **Estado de la dirección 1:** ND

    - **Código postal de dirección 1:** 58103

6. Cuando complete el contacto, seleccione **Guardar &amp; cerrar**.

7. En la barra de comandos, seleccione Nuevo otra vez para crear otro contacto.

8. Rellene el segundo contacto como sigue:

    - **Nombre**: Marco

    - **Apellidos**: Gomez (sus iniciales)

    - **Correo electrónico**: Escriba una dirección de correo electrónico en la que pueda recibir correos.

    - **Dirección 1 Calle 1:** 101 Sample Ave

    - **Dirección 1: Ciudad:** Fargo

    - **Estado de la dirección 1:** ND

    - **Código postal de dirección 1:** 58103

**NOTA:** Utilizamos la misma dirección para facilitar el reconocimiento de los contactos como datos de ejemplo. 

9. Cuando complete el contacto, seleccione **Guardar &amp; cerrar**.

**IMPORTANTE:** Debido a la dirección, es posible que se desencadene la configuración de detección de duplicados de los sistemas. Si aparece la pantalla de registro duplicado, seleccione el botón **Omitir y guardar**. 

**Tarea 2: Creación de segmento de Fargo** 

A continuación, crearemos un nuevo segmento y agregaremos los contactos que creamos en la tarea anterior. 

1. En la navegación de la izquierda, seleccione **Segmentos**, debajo de **Marketing**. 

    2. En la barra de comandos, haga clic en **Nuevo**.

    3. En el menú desplegable que aparece, seleccione **Nuevo segmento dinámico**.

    4. En el cuadro de diálogo **Plantillas de segmentos** que se abre, seleccione **Omitir** para cerrarlo y continuar en la pantalla **Nuevo segmento**.

    5. Seleccione **Agregar bloque de consulta** para crear una consulta en la entidad de contactos. 

    6. Seleccione el texto fantasma **Seleccionar atributo**. 

    7. A continuación, escriba "ciudad" para filtrar la lista y elija **Dirección 1: Ciudad** de la lista.

    8. Deje la siguiente lista desplegable establecida en **Es**. 

    9. Seleccione la tercera lista desplegable, que contiene el texto fantasma **Escriba para buscar** y escriba **Fargo**.

    10. Haga clic para seleccionar el campo **Nombre** en la parte superior de la consulta y escriba **Contactos de Fargo (sus iniciales)** . (Es posible que tenga que seleccionar la flecha abajo situada junto al motivo del estado).

    11. Seleccione **Guardar** en la Barra de comandos para guardar su segmento.

    12. Seleccione **Publicar** para publicar el segmento.

    13. Espere aproximadamente un minuto y luego seleccione **Actualizar** en la Barra de comandos para actualizar la página. 

    14. Ahora debería ver que se ha agregado la pestaña **Miembros**. 

 

**Tarea 3: Crear un correo electrónico sencillo.** 

A continuación, crearemos un correo electrónico sencillo a partir de una plantilla existente que podremos aprovechar con nuestro recorrido del cliente. 

1. Con la navegación de la izquierda, seleccione **Correos electrónicos de marketing** en el grupo **Ejecución de marketing**.

2. En la barra de comandos, seleccione **Nuevo**.

3. En la pantalla **Plantillas de correo electrónico de marketing**, seleccione **1 columna** y, después, elija el botón **Seleccionar**. 

4. En la esquina superior izquierda del correo electrónico, seleccione el campo Nombre. (Tendrá texto similar a Email ypl [1 columna]).

5. Cambie el nombre a "**Mensajes de correo electrónico de ejemplo (sus iniciales)".**

6. En el campo **Asunto**, escriba el texto "**Vea lo que tenemos que ofrecer".** 

7. Seleccione el botón **Guardar**. 

8. Seleccione el botón **Publicar** para publicar el correo electrónico. 

 

**Tarea 4: Crear un recorrido del cliente.** 

Ahora que tenemos nuestro público objetivo, así como la actividad de correo electrónico que queremos usar, vamos a crear un recorrido del cliente. 

1. Con la navegación de la izquierda, seleccione **Recorridos del cliente** en el grupo **Ejecución de marketing**.

    2. En la barra de comandos, seleccione **Nuevo**.

    3. En el menú emergente **Plantillas de recorrido del cliente**, seleccione **Omitir** para empezar a crear un nuevo recorrido desde cero.

    4. Seleccione **Establecer público** (o, alternativamente, seleccione **+** ). Compruebe que el **Tipo de origen** está establecido en **Segmento** y seleccione el segmento **Contactos de Fargo** (sus iniciales) que creó en el ejercicio anterior. El primer mosaico se rellena con el nombre del segmento y el panel de **Público** muestra las propiedades del segmento.

    5. Seleccione **+** en el lienzo y luego seleccione **Enviar un correo electrónico** en el menú contextual.

    6. En la sección Enviar un correo electrónico, seleccione **Mensaje de correo electrónico de ejemplo** (sus iniciales) que creó anteriormente.

    7. Seleccione la pestaña General situada en la parte superior del registro del recorrido del cliente. Escriba la siguiente información en la pestaña **General**:

        - **Nombre**: Recorrido del cliente de Fargo (sus iniciales)

        - **Fecha y hora de inicio**: Escriba la fecha de hoy

        - **Fecha y hora de finalización**: Dentro de un mes

        - **Zona horaria**: Seleccione su zona horaria local

8. En la Barra de comandos, seleccione **Guardar** para guardar el trabajo que haya realizado hasta el momento.

9. Su recorrido ya está listo para comenzar. Para iniciar el recorrido, publíquelo mediante el botón **Publicar** de la Barra de comandos.

 
