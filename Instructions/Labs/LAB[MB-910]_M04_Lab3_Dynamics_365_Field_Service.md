---
lab:
    title: 'Laboratorio 4.3: Laboratorio final de Dynamics 365 Field Service'
    module: 'Módulo 4: Aprender los fundamentos de Dynamics 365 Field Service'
---

Módulo 4: Aprender los fundamentos de Dynamics 365 Field Service
========================

## Laboratorio de prácticas 4.3: Laboratorio final de Dynamics 365 Field Service

## Escenario de laboratorio

La compañía ABC está especializada en la fabricación, venta, instalación y reparaciones de equipos de seguridad. Sus productos incluyen cámaras de seguridad para interiores y exteriores, sensores de humedad e incendios, servicios de supervisión y más. 

La compañía ABC utiliza las aplicaciones de Dynamics 365 para comunicarse con sus clientes en diferentes áreas de su organización, desde ventas hasta el servicio técnico. 

**Ventas y marketing**

La compañía ABC se dirige a sus clientes residenciales de forma directa a través de campañas de marketing dirigidas. Los clientes se eligen en función de su ciudad y otros factores. Los materiales de marketing se envían por correo electrónico y se guían en función de la interacción con el mismo. 

Aunque algunos de los productos más pequeños se venden al por menor, la mayoría de los productos se venden directamente a los consumidores a través del equipo de ventas interno.

Internamente, se centran en dos áreas clave: 

- **Clientes residenciales:** los clientes residenciales suelen buscar componentes individuales o una solución integral de hogar. Estos ciclos de ventas suelen ser más cortos y originarse en redes sociales, páginas web, recomendaciones o contacto directo con el posible cliente. Ya que los clientes residenciales suelen centrarse en productos específicos o instalaciones más pequeñas, los ciclos de ventas suelen durar un par de días o semanas. 

- **Clientes empresariales:** los comerciales para empresas se centran en clientes que necesitan una solución empresarial más especializada y a su medida. Para las ventas a empresas se suelen implicar varias ubicaciones con comunicación conjunta y son necesarios múltiples recursos para completar el proyecto. Estos ciclos de ventas suelen ser más largos y hay que movilizar a muchas más partes. 

Es importante que todos los comerciales de la compañía ABC tengan las herramientas y guías necesarias independientemente de su área de enfoque para vender a sus clientes. 

**Instalación del sistema:**

el proceso de instalación del equipo de seguridad comprado varía en función del tipo de cliente al que se ha vendido. 

- **Clientes residenciales:** ya que las instalaciones residenciales se suelen hacer en menos de un día, se les encarga a empleados internos. Una vez realizada la venta, se crea una orden de trabajo y se identifica y programa a un técnico cualificado para realizar la instalación. 

- **Clientes empresariales:** las implementaciones en empresas pueden llevar meses y se requiere un director del proyecto para supervisar las operaciones del día a día. Esto incluye la creación de planes de proyecto, definición de equipos de proyecto y la programación de recursos. 

**Servicio y soporte:**

una vez instalados los sistemas, la compañía ABC proporciona soporte posventa. Si un cliente tiene un problema, puede contactar con soporte al cliente. Un agente trabajará con el cliente de forma remota para resolver el problema. Si el problema no se puede resolver de forma remota, el agente de soporte puede escalar el problema a una orden de trabajo que se asignará a un técnico de servicio cualificado para que se encargue de ella. 

## Objetivos

Usualmente, la compañía ABC envía técnicos de servicio para encargarse de tareas para el cliente en uno de tres escenarios. 

- Si se ha comprado un nuevo sistema de seguridad y ha de ser instalado.

- Si un agente de soporte es incapaz de resolver un problema del cliente de forma remota.

- Si un contacto del cliente contacta directamente para un servicio in situ. 

Hace poco, un cliente empresarial, Active Transport, Inc., contactó con el equipo de soporte por un problema que estaban teniendo con una de las cámaras de su sistema de seguridad. El técnico de soporte fue incapaz de resolver el problema de forma remota, así que habrá que enviar un técnico de servicio. En este escenario, llevará a cabo lo siguiente:

- Convertir un registro de caso en una orden de trabajo

- Programar una orden de trabajo

- Resolver una orden de trabajo mediante la aplicación móvil 

## Configuración del laboratorio

  - **Tiempo estimado**: 45 minutos

## Instrucciones

## Ejercicio 1: Crear un caso y escalar a una orden de trabajo 

### Tarea 1: Crear un registro de caso

1. Si aún no la ha abierto, abra la aplicación **Dynamics 365 Field Service**. 

2. En el panel izquierdo de la pantalla, seleccione **Casos**. 

3. En la **Barra de comandos**, haga clic en **Nuevo** para crear un nuevo registro de caso.

4. Complete su nuevo registro de caso de la siguiente manera:

	- **Título del caso:** Cámara dañada

	- **Cliente:** Best For You Organics Company

	- **Origen:** Teléfono

	Guarde el registro.

5. Seleccione la pestaña **Servicio de campo**

6. En el campo **Tipo de incidente**, seleccione **Cámara dañada**. (Crear nuevo)

7. En la **Barra de comandos**, seleccione **Guardar y cerrar** para guardar y cerrar el registro. 

 

### Tarea 2: Crear una orden de trabajo de forma manual

Volveremos al registro de caso que ha creado más adelante. Ahora examinemos cómo crear un registro de orden de trabajo de forma manual. 

 

1. En el panel de navegación de la izquierda, seleccione **Órdenes de trabajo**.

2. En la **Barra de comandos**, haga clic en **Nuevo** para crear una nueva orden de trabajo.

3. Complete los detalles de la orden de trabajo con lo siguiente:

	- **Cuenta de servicio:** Margie's Travel

	- **Lista de precios:** Office 365 US (muestra)

	- **Tipo de orden de trabajo**: Servicio

	- **Gravable:** No

	Guarde el registro y asigne el tipo de incidente principal

	- **Tipo de incidente principal**: Abandono (crear nuevo)

4. Apúntese el número de la orden de trabajo para asegurarse de que trabaja con la orden de trabajo correcta más adelante. 

5. Seleccione la pestaña **Configuración**.

6. Establezca el campo **Zona de servicio** en **WA**.

7. En **Preferencias**, configure las preferencias de la siguiente manera:

	- **Tiempo desde comprometido:** Hoy, 9:00 horas

	- **Tiempo hasta comprometido:** Hoy, 11:00 horas

8. Seleccione **Guardar y cerrar** para guardar los cambios y salir de la orden de trabajo.

 

### Tarea 3: Generar una orden de trabajo a partir de un caso

Escalar registros de casos es otra manera de crear órdenes de trabajo. En este caso, escalaremos el registro de caso de la cámara dañada que hemos creado anteriormente. 

 

1. En la navegación de la izquierda, seleccione **Casos**. 

2. Abra el caso **Cámara dañada**que ha creado anteriormente. 

3. En la **Barra de comandos**, haga clic en el botón **Convertir en orden de trabajo**. 

4. Una vez se ha completado la creación de la orden de trabajo, haga clic en el botón **OK** en la ventana emergente para ver los detalles de orden de la trabajo. 

 

Sus dos nuevas órdenes de trabajo están listas para ser programadas. 

## Ejercicio 2: Programar elementos con Dynamics 365 Field Service  

### Tarea 1: Programar directamente a partir de una orden de trabajo

1. En la navegación de la izquierda, seleccione **Tablero de programación**.

2. En la parte superior derecha de la pantalla, establezca la experiencia **Nuevo tablero de programación** en **Activada**. 

3. En el campo de búsqueda **Buscar recursos**, escriba Aidan Knaggs. 

4. En la parte inferior de la pantalla, en el panel de requisitos, seleccione **Órdenes de trabajo sin programar**.  (Si no se muestra el panel de requisitos, haga clic en la flecha en la parte inferior de la pantalla para expandirlo). 

5. Localice la orden de trabajo de **Munson’s Pickles** que ha creado desde el registro de caso. (Recuerde el número de la orden de trabajo). 

6. Arrastre el registro de **Munson’s Pickles** y colóquelo en un hueco libre en el registro de contacto de Aiden. 

7. A veces tendrá que volver a programar una orden de trabajo debido a conflictos con los técnicos u otros elementos. Esto lo pueden hacer los distribuidores fácilmente desde el tablero de programación. 

 

### Tarea 2: Programar con el tablero de programación

1. En la navegación de la izquierda, seleccione **Tablero de programación**.

2. Escriba el nombre de su cuenta de usuario en el campo de búsqueda de **Buscar recursos**. (Debería mostrarse su registro de recurso).

3. En la parte inferior de la pantalla, en el panel de requisitos, seleccione **Órdenes de trabajo sin programar**.  (Si no se muestra el panel de requisitos, haga clic en la flecha en la parte inferior de la pantalla para expandirlo). 

4. Localice la orden de trabajo de **Active Transport** que ha creado desde el registro de caso. (Recuerde el número de la orden de trabajo). 

5. Arrastre el registro de **Active Transport** y colóquelo en un hueco libre en su registro de usuario. El texto aparecerá en verde si la franja horaria coincide con la franja preferida del cliente.

6. A veces tendrá que volver a programar una orden de trabajo debido a conflictos con los técnicos u otros elementos. Esto lo pueden hacer los distribuidores fácilmente desde el tablero de programación. 

7. Haga clic en el cuadro de búsqueda de recursos del tablero de programación (ubicado justo encima de la columna del nombre del recurso), escriba **Brady** y localice la orden de trabajo programada para **Brady Hannon** más adelante hoy. 

8. **Haga clic con el botón derecho** en el elemento programado. En el menú que aparece, seleccione **Sustituir recurso**. Haga clic en el campo de selección/búsqueda, seleccione su registro de recurso y haga clic en **Reasignar**.
