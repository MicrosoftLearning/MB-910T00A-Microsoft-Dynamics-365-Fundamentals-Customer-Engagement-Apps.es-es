---
lab:
    title: 'Laboratorio 3.3: Laboratorio final de Dynamics 365 Customer Service'
    module: 'Módulo 3: Aprender los fundamentos de Dynamics 365 Customer Service'
---

Módulo 3: Aprender los fundamentos de Dynamics 365 Customer Service
========================

## Laboratorio de prácticas 3.3: Laboratorio final de Dynamics 365 Customer Service

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

A menudo, los clientes pueden tener problemas con su equipo. Si tienen problemas, estos se notifican al equipo de soporte de la compañía ABC. Los problemas se pueden notificar de varias maneras. En algunos casos, el equipo puede notificar problemas de forma proactiva. A medida que se notifican los problemas, los agentes intentan resolverlos de forma remota. Si no es posible, se enviará un técnico de servicio para resolver el problema. Últimamente ha estado arreglando muchos sensores que se habían apagado. Se ha dado cuenta de que se debía a un error del software. Quiere crear un artículo de conocimientos al que otros agentes puedan recurrir si se encuentran con el mismo problema. 

Como agente de soporte, es responsable de resolver los problemas notificados por los clientes. Ha recibido una llamada de Piper Smith. Piper ha notificado que uno de los sensores de su sistema no funciona. Tiene que registrar la llamada de Piper e intentar obtener una solución a su problema. 

Tras completar el laboratorio, habrá completado los siguientes procesos:

- Crear un artículo de conocimientos 

- Administrar casos con Customer Service Hub

- Crear y registrar un caso 

- Administrar un registro de caso en su ciclo de vida 

## Configuración del laboratorio

  - **Tiempo estimado**: 45 minutos

## Instrucciones

## Ejercicio 1: Crear y publicar un artículo de conocimientos

### Tarea 1: Crear un artículo de conocimientos

1. Si aún no lo ha hecho, abra la aplicación **Dynamics 365 Customer Service Hub**. 

2. En el panel izquierdo de la pantalla, seleccione **Artículos de conocimientos**. 

3. Para ver fácilmente qué artículos se encuentran en qué etapas, haga clic en el desplegable junto a **Mis artículos activos**. 

4. Seleccione **Artículos en borrador**. 

5. Utilice el selector de vista para seleccionar **Artículos aprobados**.  

6. Use el selector de vista para volver a **Mis artículos activos**.

7. En la **Barra de comandos**, seleccione el botón **Nuevo**. Una vez abierto el nuevo registro, seleccione la flecha desplegable junto al campo **Razón de estado** en la cabecera del registro, en la parte superior. Establezca el **Idioma** como **Inglés - Estados Unidos**.

8. Complete el artículo del siguiente modo:

	- **Título:** Sensor no funciona - sus iniciales

	- **Palabras clave:** Sensor, dañado, no funciona

	- **Descripción:** Ayuda a resolver escenarios en los que un sensor no funciona. 

9. Escriba el siguiente texto en el **diseñador de contenido**.   

	El sensor no funciona.

	Cuando un sensor no funcione como debería, haga lo siguiente:

	1. Localice y cambie las pilas del dispositivo. 

	2. Mantenga presionado el botón de encendido durante 3 segundos. 

	3. El dispositivo se abrirá en modo administrador. 

	4. Mantenga presionado el botón de emparejar hasta que la luz cambie de rojo a azul. 

	5. Presione el botón restablecer. 

	Una vez que se reinicie el dispositivo, volverá a estar en línea. 

10. En el editor de contenido, seleccione el texto de “el sensor no funciona”.

11. Cambie el tamaño de la fuente a **22** y seleccione el botón **Negrita**. 

12. En la **Barra de comandos**, seleccione el botón **Guardar** para guardar el Artículo de conocimientos y dejarlo abierto. 

13. En **Nuevo proceso**, seleccione la etapa **Autor** y, después, establezca el campo **Asunto del artículo** como **Servicio**. 

14. Establezca el campo **Marcar para revisión** como **Completado**.

15. Haga clic en el botón **Etapa siguiente** para avanzar a la etapa **Revisar**.

16. En la **Barra de comandos**, seleccione **Guardar y cerrar** para guardar los cambios y cerrar el artículo.

 

### Tarea 2: Administrar un artículo mediante el proceso de aprobación

En la mayoría de organizaciones, después de que el autor cree el registro, pasará por un proceso de aprobación antes de su publicación. La mayoría de las veces esto lo hace otra persona. Para este ejercicio, actuaremos como aprobador. 

1. En los Artículos de conocimientos, cambie la vista a **Artículos propuestos** para ver qué artículos necesitan aprobación. 

2. Abra el artículo **Sensor no funciona - sus iniciales** que acaba de crear.

3. En **Nuevo proceso**, seleccione la etapa **Revisar**. Establezca el campo **Revisar** en **Rechazado**.

4. En la pantalla de rechazar artículo de conocimiento, escriba el texto **Los pasos no funcionan cuando intento replicarlos.**

5. Seleccione el botón **Rechazar**.

6. Seleccione **Guardar y cerrar** para cerrar el registro del artículo.

7. Use el **selector de vista** para cambiar la vista a **Mis artículos activos**. 

8. Abra el registro **Sensor no funciona - sus iniciales**.

9. Cuando se abra, seleccione la pestaña **Resumen**. 

10. En la **Escala de tiempo** del registro aparecerá una nota que indica que el artículo se ha rechazado y el motivo. 

11. Seleccione la pestaña **Contenido**

12. En el campo **Contenido**, sitúe el ratón antes de la palabra **Pulsar** en el paso 5. 

13. Presione la tecla **Entrar**. 

14. Escriba el texto "Pulse el botón Confirmar". 

15. En la **Barra de comandos**, seleccione el botón **Guardar y cerrar**.

16. En el **selector de vista**, cambie a **Artículos propuestos**.

17. Abra el artículo **Sensor no funciona - sus iniciales**. 

18. En el flujo de proceso de negocio **Nuevo proceso**, seleccione la etapa **Revisar**.

19. Cambie el estado a **Aprobado**. 

20. Se le pedirá confirmación de la aprobación del artículo, seleccione **Aceptar**. 


### Tarea 3: Aprobar el artículo de conocimientos

Ahora que el artículo está aprobado, lo publicaremos para que esté disponible para otras personas que trabajan en casos. 

1. Haga clic en el botón **Etapa siguiente** para avanzar a la etapa **Publicar**. 

2. Marque **Establecer asociación de producto** como **Completado**. 

3. Cambie la **Fecha de expiración** a **un año a partir de hoy a las 00:00**. 

4. Haga clic en el botón **Finalizar** para completar el proceso. 

5. En la **Barra de comandos** del artículo, haga clic en **Publicar**. 

6. Confirme que está seleccionado lo siguiente:

	- **Publicar:** Ahora

	- **Estado de publicación:** Publicado

	- **Fecha de expiración:** Un año a partir de hoy a las 0:00

	- **Estado de expiración:** Expirada

	- **Estado de expiración:** Expirada

7. Haga clic en el botón **Publicar** para publicar el artículo.


## Ejercicio 2: Administrar un caso de soporte en su ciclo de vida


### Tarea 1: Crear y administrar un caso

1. Si aún no lo ha hecho, abra la aplicación **Dynamics 365 Customer Service Hub**. 

2. En el panel izquierdo de la pantalla, seleccione **Paneles**. Esta acción abrirá el panel del **Nivel 1**. 

3. En la **Barra de comandos**, haga clic en el botón **Mostrar filtro visual**.


4. Los demás paneles proporcionan detalles adicionales sobre la carga de casos actual. Puede trabajar con otros paneles con el selector de paneles. Cambie el panel de **Panel de nivel 1** a **Panel de nivel 2**. 

 

Ahora que se ha familiarizado con las diferentes vistas y paneles, crearemos un nuevo registro de caso para ayudar a Piper con su problema.

 

10. En el panel izquierdo de la pantalla, seleccione **Casos**. 

11. En la **Barra de comandos**, haga clic en **Nuevo** para crear un nuevo registro de caso.

12. Complete su nuevo registro de caso de la siguiente manera:

	- **Título del caso:** Sensor no funciona - sus iniciales

	- **Cliente:** Piper Smith

	- **Origen:** Teléfono

	- **Descripción:** Piper explica que uno de los sensores que ha recibido no funciona correctamente. 

13. Haga clic en el botón **Guardar** para guardar el registro y dejarlo abierto. 

14. En la **Escala de tiempo del registro**, haga clic en el **icono +** para agregar una nueva actividad. 

15. En el menú que aparece, seleccione **Llamada de teléfono**.

16. En **Creación rápida: llamada de teléfono**, complete la actividad del siguiente modo:

	- **Asunto:** Devolver la llamada a Piper

	- **Dirección:** Saliente

	- **Número de teléfono:**  888 555-1762

	- **Duración:** 15 minutos.

17. Seleccione el botón **Guardar y cerrar**. 

18. En el **proceso de teléfono a caso**, haga clic en la etapa **Identificar**.

19. Haga clic en el botón **Etapa siguiente** para avanzar a la etapa **Investigar**. 

20. Haga clic en la **X** de la etapa **Investigar** para cerrar la ventana y poder seguir trabajando. 

21. En la **Escala de tiempo del registro**, haga clic en el **icono +** para agregar una nueva actividad. 

22. En el menú que aparece, seleccione **Tarea**.

23. En **Creación rápida: llamada de teléfono**, complete la actividad del siguiente modo:

	- **Asunto:** Investigar el problema de Piper

	- **Descripción:** Acceder a la base de conocimiento para investigar el problema de Piper. 

	- **Duración:** 30 minutos.

24. Seleccione el botón **Guardar y cerrar**. 

25. En la parte derecha de la pantalla, localice y seleccione el icono en forma de libro **Conocimientos**. (Estará justo debajo del icono en forma de llave inglesa).

26. Comprobará que el título de su caso se ha introducido automáticamente en el campo de búsqueda. Localice y seleccione el artículo **Sensor no funciona - sus iniciales** que ha creado anteriormente. 

27. Se mostrará el contenido completo del artículo, seleccione el icono del **pulgar hacia arriba** al final del artículo para indicar que el artículo ha sido de ayuda. 

28. Seleccione el icono **Vincular este artículo con el registro actual**. Compruebe que aparece **Vinculado a caso**. 

 

### Tarea 2: Cerrar el caso

Ahora que hemos identificado una solución al problema del cliente, podremos resolver el caso. El primer paso para cerrar un caso es cerrar todas las actividades abiertas asociadas con el mismo. 

1. En la **escala de tiempo** del caso, mantenga el puntero sobre **la tarea de investigar el problema de Piper** que creó anteriormente.** Seleccione el icono de **la marca de verificación** para completar la actividad. 

2. En la pantalla **Cerrar tarea**, compruebe que el estado es completado y seleccione el botón **Cerrar**. El estado de la tarea debería ser **Cerrado**. 

3. Mantenga el puntero sobre **Devolver la llamada a Piper** que creó anteriormente**.** Seleccione el icono de **la marca de verificación** para completar la actividad. 

4. En la pantalla **Cerrar llamada de teléfono**, compruebe que los **Estados** son **Completado** y **Hecho**. Seleccione el botón **Cerrar**. Compruebe que la actividad aparece como cerrada en la escala de tiempo. 

5. En el **Proceso de teléfono a caso**, seleccione la etapa **Investigar** y después, **Etapa siguiente** para avanzar a la etapa **Resolver**. 

6. En la etapa **Resolver**, seleccione el botón **Finalizar** para completar el flujo del proceso. 

7. En la **Barra de comandos** del caso, seleccione **Resolver caso**.

8. En la ventana **Resolver caso**, establezca el campo **Resolución** en **Artículo de conocimiento**. 

9. Compruebe que el **tiempo total** y el **tiempo facturable** es de **45 minutos** (esto supone el tiempo total dedicado a la llamada y las tareas agregadas al registro). 

10. Haga clic en el botón **Resolver** para finalizar el proceso. 

