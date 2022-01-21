---
lab:
    title: 'Laboratorio 5.1: Crear un cliente potencial basado en proyecto'
    module: 'Módulo 5: Aprender los fundamentos de Dynamics 365 Project Operations'
---

Módulo 5: Aprender los Fundamentos de Dynamics 365 Project Operations
========================

## Laboratorio de prácticas 5.1: Crear un cliente potencial basado en proyecto

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

Los comerciales de la compañía ABC se centran en clientes que necesitan una solución empresarial más especializada y a su medida. Por esto, en sus ventas a empresas se suelen implicar varias ubicaciones con comunicación conjunta y son necesarios múltiples recursos para completar el proyecto. Los ciclos de venta de la compañía ABC llevan muchos meses y requieren la movilización de varias partes para su implementación. 

Una vez que se haya vendido un sistema a un cliente empresarial, la implementación del mismo puede llevar varios meses. Cada proyecto se asigna a un director del proyecto que supervisa la planificación del proyecto y las operaciones del día a día. Esto incluye la creación de planes de proyecto, definición de equipos de proyecto y la programación de recursos. 

Como comercial para empresas, es responsable de vender soluciones de seguridad personalizadas de gama alta a los clientes. Recientemente recibió una llamada de una compañía llamada Consolidated Sample. Les gustaría tener una solución de seguridad integrada en todas sus ubicaciones. Introducirá en el sistema el cliente potencial para Consolidated Sample, avanzará en el ciclo de venta del proyecto y creará el proyecto correspondiente. 

Tras completar el laboratorio, habrá completado los siguientes procesos:

- Introducir un cliente potencial de proyecto en Dynamics 365 Sales

## Configuración del laboratorio

  - **Tiempo estimado**: 10 minutos

## Instrucciones

## Ejercicio 1: Crear un cliente potencial basado en proyecto

### Tarea 1: Crear un nuevo cliente potencial

1. Si es necesario, abra el navegador InPrivate y acceda a [Https://home.Dynamics.com](https://home.dynamics.com/) 

2. Cuando se le pida, escriba las credenciales proporcionadas por el instructor. 

3. De la lista de aplicaciones que aparece, seleccione **Project Service**. 

4. Si no aparece Project Service, visite trials.dynamics.com e instale la versión de prueba de la aplicación. 

	- Correo electrónico del trabajo: correo electrónico del inquilino. 

	- Número de teléfono: teléfono móvil

5. En el panel izquierdo de la pantalla, seleccione el área **Ventas**. 

6. Con la navegación, seleccione **Clientes potenciales**. 

7. Para ver todos los clientes potenciales de ventas actuales en el sistema, seleccione el desplegable junto a **Mis clientes potenciales abiertos**, y desde el menú que aparece, seleccione **Clientes potenciales activos**. 

8. Para volver a su lista de clientes potenciales, seleccione el desplegable junto a clientes potenciales activos, y desde el menú que aparece, seleccione **Mis clientes potenciales abiertos**. 

9. Ahora crearemos un nuevo cliente potencial para una compañía llamada Consolidated Sample. En la vista **Mis clientes potenciales abiertos**, seleccione el botón **Nuevo** en la Barra de comandos.

10. Complete su nuevo registro de cliente potencial de la siguiente manera:

	- **Tema:** Implementación global completa - sus iniciales

	- **Tipo:** Basado en tarea

	- **Nombre:** Jean

	- **Apellidos:** Anderson - sus iniciales

	- **Teléfono del trabajo:** 888 555-8855

	- **Correo electrónico:** jean@sample.com

	- **Compañía:** Consolidated Sample - sus iniciales

	- **Calle 1:** 219 91<sup data-htmlnode="">st</sup> Ave N

	- **Ciudad:** Seattle

	- **Estado o provincia**: WA

	- **Código postal:** 98001 

11. Seleccione el botón **Guardar** de la Barra de comandos para guardar el nuevo cliente potencial y dejarlo abierto.

12. Observe el flujo de proceso de negocio **Cliente potencial a Oportunidad** en la parte superior del registro. Haga clic en **Etapa de calificación** para seleccionarla. Complete la etapa del siguiente modo:

	- **Calendario de compra:** Este trimestre

	- **Presupuesto estimado:** 25000  

	- **Proceso de compra:** Comité

	- **Identificación de los responsables de toma de decisiones:** Completado

13. Haga clic en la **X** para cerrar la ventana. 

14. Vaya a **Escala de tiempo del registro** en la mitad de la pantalla y haga clic en el **Icono +** para agregar una nueva actividad. 

15. En el menú que aparece, seleccione **Llamada de teléfono**.

16. En la pantalla de creación rápida de llamadas telefónicas, complete la llamada de teléfono como se muestra a continuación:

	- **Asunto:** Llamada de calificación inicial - sus iniciales  

	- **Número de teléfono:** 888 555-8855

	- **Dirección:** Saliente

	- **Descripción:** Conversación inicial con Jean para determinar la calificación inicial. 

17. Seleccione el botón **Guardar y cerrar**.

18. Observe que la actividad **Llamada de teléfono inicial** aparece ahora en la **Escala de tiempo del registro**. Mantenga el puntero sobre la actividad y seleccione el **icono de marca de verificación** de cierre de actividad para marcar la llamada de teléfono como completada. 

19. En la ventana **Cerrar llamada de teléfono**, compruebe que el estado sea **Completada** y seleccione el botón **Cerrar**.

 

### Tarea 2: Calificar el cliente potencial y convertirlo en oportunidad para su calificación futura

1. En la **Barra de comandos**, seleccione el botón **Calificar**. 

2. Una vez que el sistema califica al cliente potencial, se creará un nuevo registro de oportunidad y el proceso comercial avanzará a la etapa **Desarrollar**. Seleccione la etapa **Calificar** para ver el registro de cliente potencial original. 

3. Seleccione la etapa **Desarrollar** para volver a la oportunidad.

4. Haga clic en **Guardar y cerrar** para cerrar el registro de oportunidad que acaba de crear. 

