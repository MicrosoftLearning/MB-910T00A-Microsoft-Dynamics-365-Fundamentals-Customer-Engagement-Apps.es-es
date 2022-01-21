---
lab:
    title: 'Laboratorio 2.3: Laboratorio final de Dynamics 365 Sales'
    module: 'Módulo 2: Aprender los fundamentos de Dynamics 365 Sales'
---

Módulo 2: Aprender los fundamentos de Dynamics 365 Sales
========================

## Laboratorio de prácticas 2.3: Laboratorio de proyecto final de Dynamics 365 Sales

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

Está trabajando como representante de ventas en la sección de ventas residenciales de la compañía ABC. Aunque muchos de sus clientes potenciales provienen de eventos patrocinados por la compañía, campañas de marketing y listas compradas, a menudo los también clientes le consultan directamente. Cuando recibe esas consultas, debe escribirlas manualmente y trabajar con ellas a lo largo del ciclo de vida de las ventas. 

Recientemente, recibió una llamada de alguien llamado Piper Smith. Hubo una serie de robos en su barrio y le gustaría comprar un equipo de seguridad para el hogar. Va a introducir el cliente potencial de Piper en el sistema, intentará calificarla y hacerla avanzar en el ciclo de ventas. 

Tras completar el laboratorio, habrá completado los siguientes procesos:

- Introducir un cliente potencial en Dynamics 365 Sales

- Calificar y convertir un cliente potencial en una oportunidad de venta.

- Administrar las actividades diarias asociadas a una oportunidad. 

- Agregar una oferta a una oportunidad. 

- Cerrar una oportunidad de venta. 

- Generar una factura. 

## Configuración del laboratorio

  - **Tiempo estimado**: 30 minutos

## Instrucciones
  
## Ejercicio 1: Crear y calificar un cliente potencial en Dynamics 365 Sales


### Tarea 1: Crear un nuevo cliente potencial

1. Si es necesario, abra el navegador InPrivate y acceda a [Https://home.Dynamics.com](https://home.dynamics.com/) 

2. Cuando se le pida, escriba las credenciales proporcionadas por el instructor. 

3. En la lista de aplicaciones que aparece, seleccione **Centro de ventas.**

4. Con la navegación de la parte izquierda de la pantalla, seleccione **Clientes potenciales**. 

5. Para ver todos los clientes potenciales de ventas actuales en el sistema, seleccione el desplegable junto a **Mis clientes potenciales abiertos**, y desde el menú que aparece, seleccione **Clientes potenciales activos**. 

6. Para volver a su lista de clientes potenciales, seleccione el desplegable junto a clientes potenciales activos, y desde el menú que aparece, seleccione **Mis clientes potenciales abiertos**. 

7. A continuación, cree un nuevo cliente potencial para Piper Smith, desde la vista **Mis clientes potenciales abiertos**, y seleccione el botón **Nuevo** en la Barra de comandos.

8. Complete su nuevo registro de cliente potencial de la siguiente manera:

	- **Tema:** búsqueda de equipamiento nuevo – “Su nombre”

	- **Nombre:** Piper

	- **Apellidos:** Smith – Sus iniciales

	- **Teléfono móvil:** 888 555-1762

	- **Correo electrónico:** piper@sample.com


9. Seleccione el botón **Guardar** de la Barra de comandos para guardar el nuevo cliente potencial y dejarlo abierto.

10. Observe el flujo de proceso de negocio **Cliente potencial a Oportunidad** en la parte superior del registro. Haga clic en **Etapa de calificación** para seleccionarla. Complete la etapa del siguiente modo:

	- **Calendario de compra:** Este trimestre

	- **Presupuesto estimado:** 10000 

	- **Proceso de compra:** Individual

	- **Identificación de los responsables de toma de decisiones:** Completado

11. Haga clic en la **X** para cerrar la ventana. 

12. Vaya a **Escala de tiempo del registro** en la mitad de la pantalla y haga clic en el **Icono +** para agregar una nueva actividad. 

13. En el menú que aparece, seleccione **Llamada de teléfono**.

14. En la pantalla de creación rápida de llamadas telefónicas, complete la llamada de teléfono como se muestra a continuación:

	- **Asunto:** Búsqueda de equipamiento de seguridad para el hogar

	- **Número de teléfono:** 888 555-1762

	- **Dirección:** Entrante

	- **Descripción:** Después de algunos casos en su vecindario, busca comprar un sistema de seguridad. 

15. Seleccione el botón **Guardar y cerrar**.

16. Observe que la actividad **Búsqueda de equipo de seguridad para el hogar** aparece ahora en el registro **Escala de tiempo**. Mantenga el puntero sobre la actividad y seleccione el **icono de marca de verificación** de cierre de actividad para marcar la llamada de teléfono como completada. 

17. En la ventana **Cerrar llamada de teléfono**, compruebe que el estado sea **Completada** y seleccione el botón **Cerrar**.

 

**IMPORTANTE:** No cierre la ventana del cliente potencial. Déjela abierta porque la utilizaremos en la siguiente tarea. 

 

### Tarea 2: Calificar al cliente potencial como oportunidad

Después de visitar a Piper, identifica que hay suficiente interés por su parte para continuar, y que tenemos productos y servicios que la beneficiarían. A continuación, calificará el registro del cliente potencial. Esto creará un registro de oportunidad relacionado y pasará a la siguiente etapa del proceso de ventas cliente potencial a oportunidad. 

1. En la **Barra de comandos**, seleccione el botón **Calificar**. 

2. Una vez que el sistema califica al cliente potencial, se creará un nuevo registro de oportunidad y el proceso comercial avanzará a la etapa **Desarrollar**. Seleccione la etapa **Calificar** para ver el registro de cliente potencial original. 

3. Seleccione la etapa **Cualificar** para volver al cliente potencial.

4. Haga clic en **Guardar y cerrar** para cerrar el registro de cliente potencial que acaba de crear. 

 

 

## Ejercicio 2: Administrar una oportunidad de ventas con Dynamics 365 Sales

Ahora que hemos calificado con éxito el cliente potencial como una oportunidad, es el momento de trabajar la oportunidad a través de su ciclo de vida.

### Tarea 1: Administrar una oportunidad de ventas y crear una oferta 

1. En el panel izquierdo de la pantalla, seleccione **Oportunidades**. 

2. Seleccione la flecha desplegable junto a la vista **Mis oportunidades abiertas**; en el menú que aparece, seleccione **Todas las oportunidades**.

3. En la Barra de comandos, seleccione mostrar gráfico. Observe que el gráfico de **clientes principales** se muestra basado en la tabla de oportunidades. 

4. Seleccione la flecha desplegable junto a los **clientes principales**; en el menú que aparece, seleccione **Canalización de ventas**.

5. Seleccione la parte de calificación del embudo. Fíjese en que la lista de oportunidades cambia para mostrar las oportunidades en la etapa de calificación. 

6. Haga clic en cualquier lugar del espacio en blanco del gráfico para volver a mostrar todas las oportunidades abiertas. 

7. Seleccione la flecha desplegable junto a la vista **Oportunidades abiertas**; en el menú que aparece, seleccione **Mis oportunidades abiertas**. **Búsqueda de equipo de seguridad – Sus iniciales** será probablemente el único elemento que aparezca, y el gráfico debería reflejarlo. 

8. En la **Barra de comandos**, seleccione el botón **Ocultar gráfico**. 

9. Abra **Búsqueda de equipo de seguridad – Sus iniciales** creado cuando calificó el cliente potencial anteriormente. Tenga en cuenta que el registro ya se encuentra en la fase **Desarrollar**, ya que se creó a partir de un cliente potencial ya calificado.  

10. En el encabezado de la oportunidad **Búsqueda de equipo de seguridad – Sus iniciales**, en la parte superior del registro, seleccione la flecha hacia abajo junto al campo del propietario. 

11. Complete los siguientes pasos:

	- **Fecha de cierre estimada:** mañana

	- **Beneficios estimados:** 12.500,00

12. Vaya a **Escala de tiempo del registro** en la mitad de la pantalla y haga clic en el **Icono +** para agregar una nueva actividad. 

13. En el menú que aparece, seleccione **Cita**.

14. En **Creación rápida:**En la pantalla de **Cita**, complete lo siguiente:

	- **Asunto:** Cita rápida – “Sus iniciales”

	- **Ubicación:** En línea

	- **Hora de inicio**: Mañana @ 10:00 a. m.

	- **Hora de finalización:** Mañana @ 10:30 a. m.

15. En la Barra de comandos, seleccione **Guardar y cerrar**

16. En el flujo del proceso de negocio de cliente potencial a oportunidad, seleccione la etapa **Desarrollar**. Tenga en cuenta que debe identificar las partes interesadas y los competidores.

17. Haga clic en la **X** de la ventana para cerrarla y poder continuar trabajando. 

18. En la subcuadrícula de **Partes interesadas**, observe que **Piper** ya está definida como parte interesada. 

19. En la subcuadrícula de equipo de ventas, seleccione los **Puntos suspensivos verticales**. En el menú que aparece, seleccione **Nueva conexión**. 

20. En el campo **Búsqueda**, escriba el texto **Sistema** y seleccione el registro de **Administrador del sistema**. Una vez completado, haga clic en el botón **Agregar**. El administrador del sistema debería aparecer ahora en el equipo de ventas. Si no lo hace, seleccione el botón **Actualizar** de la Barra de comandos. 

21. En la subcuadrícula Competidores, seleccione los **tres puntos verticales**. En el menú que aparece, seleccione **Agregar competidor existente**. 

22. En la pantalla **Buscar registro**, seleccione **Nuevo registro** y luego **Competidores**.

23. En la creación rápida: En la pantalla **Competidor**, escriba **Coho Security - “sus iniciales”** en el campo **Nombre**.

24. Seleccione el botón **Guardar y cerrar**.

25. Asegúrese de que el registro de Coho Security que acaba de crear esté seleccionado y seleccione el botón **Agregar**. 

26. Seleccione la etapa **Desarrollar** en el flujo de proceso de negocio **Cliente potencial a oportunidad**. Establezca los pasos **Identificar partes interesadas** e **Identificar competidores** en **Completado**. 

27. Haga clic en el botón **Etapa siguiente** para avanzar a la etapa **Proponer**.

28. En la etapa **Proponer**, marque **Identificar el equipo de ventas** como **Completado**.

29. Haga clic en la **X** en la etapa Proponer para cerrar la ventana. 

30. En el registro de la oportunidad, seleccione la pestaña **Ofertas**. 

31. En la subcuadrícula Ofertas, seleccione **Nueva oferta**.

 

**IMPORTANTE:** Dado que estos entornos tienen varias aplicaciones de primera parte desplegadas, puede que el formulario de oferta que se muestra actualmente no sea el correcto para la funcionalidad relacionada con las ventas. Si el texto bajo el nombre de la oferta **Búsqueda de equipo de seguridad – Sus iniciales** dice: **Oferta . Oferta**, se carga la forma correcta. Si dice, **Oferta . Información de Field Service**, tendrá que cambiarlo. Si necesita cambiarlo, seleccione la flecha desplegable junto a **Cita . Información de Field Service**. En el menú que aparece, seleccione **Oferta**. 

 

### Tarea 2: Administrar una oferta

Ahora que tiene una oferta relacionada, la preparará para presentársela a un cliente. En circunstancias normales, puede que agreguemos productos al registro de oferta antes de que se entregue al cliente. Como trabajamos en entornos compartidos, vamos a omitir el agregado de líneas de oferta y a revisar la entrega de la oferta. 


1. Ahora debe seleccionar una lista de precios para adjuntarla a la oportunidad.  En **Lista de precios**, en el panel izquierdo, seleccione el icono de búsqueda y luego seleccione **Office 365 USA (muestra)** en las opciones. En la **Barra de comandos**, haga clic en el botón **Activar oferta** para activar la oferta. 

2. Ahora que se ha creado la oferta, vamos a actualizar el registro de la oportunidad para reflejar los datos nuevos. En el registro de la oferta, seleccione la oportunidad **Búsqueda de equipo nuevo** – **“Su nombre”** en el campo **Oportunidad**, bajo la sección **Información de ventas**. El registro de la oportunidad debería abrirse en su pantalla. 

3. En el registro de la oportunidad, seleccione la etapa **Proponer**. 

4. Marque **Desarrollar propuesta**, **Completar revisión interna** y **Presentar propuesta** como **Completadas**, y haga clic en el botón **Etapa siguiente** para avanzar a la etapa **Cierre**. 

5. En la etapa **Cierre**, marque los pasos **Completar propuesta final**, **Presentar propuesta final**, **Enviar nota de agradecimiento** y **Archivar sesión de análisis** como **Completado**. 

6. Establezca **Confirmar fecha de decisión** en **Fecha actual**. 

7. Seleccione el botón **Finalizar**. 

8. Haga clic en la **X** en la etapa Cierre para cerrar la ventana. 

9. Seleccione la pestaña **Ofertas**. 

10. Abra la oferta **Búsqueda de equipo de seguridad – Sus iniciales**. 

11. En la **Barra de comandos**, seleccione el botón **Crear pedido**.

12. Complete la ventana de crear pedido de la siguiente forma:

	- **Razón para el estado:** Ganado

	- **Fecha en la que se logró:** Fecha de hoy

	- **Cerrar oportunidad:** Sí

	- **Calcular ingresos reales a partir de ofertas:** No

	- **Ingresos reales:** 12 500 $

13. Seleccione el botón **Aceptar**. 

El sistema crea un nuevo pedido de ventas relacionado con el elemento. Además, cerrará tanto el registro de la oferta como el de la oportunidad relacionada. Una vez que todo esté completado, el pedido se abrirá en su pantalla. Deje el pedido abierto. 

###  

### Tarea 3: Administrar el pedido y la factura

Ahora que ha creado un pedido de ventas, cerraremos el pedido y generaremos una factura. En circunstancias normales, los productos del registro de oferta se agregarán al pedido de ventas. Como trabajamos en entornos compartidos, vamos a avanzar como si hubiera productos agregados. 

 

1. En la **Barra de comandos**, seleccione el botón **Realizar pedido**. 

2. Complete la ventana de realizar pedido de la siguiente forma:

	- **Razón para el estado:** Completo

	- **Fecha de realización:** Fecha de hoy

3. Seleccione el botón **Realizar**. 

4. En la **Barra de comandos** del pedido, seleccione el botón **Crear factura**. 

5. En la **Barra de comandos**, seleccione el botón **Factura pagada**. Seleccione Aceptar.
