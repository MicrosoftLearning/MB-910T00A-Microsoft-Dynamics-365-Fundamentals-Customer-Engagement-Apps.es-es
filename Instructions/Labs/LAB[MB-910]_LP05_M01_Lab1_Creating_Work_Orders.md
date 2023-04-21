---
lab:
  title: "Laboratorio\_5.1: Creación de órdenes de trabajo en Dynamics\_365\_Field\_Service"
  learning path: Learn the Fundamentals of Dynamics 365 Field Service
  module: Explore Dynamics 365 Field Service
---

Módulo 1: Exploración de Dynamics 365 Field Service
========================

## Laboratorio de prácticas 5.1: Generar órdenes de trabajo en Dynamics 365 Field Service

## Configuración del laboratorio

  - **Tiempo estimado**: 20 minutos

## Instrucciones

1. Si aún no la ha abierto, abra la aplicación **Dynamics 365 Field Service**.  

2. En el panel izquierdo de la pantalla, seleccione **Casos**.  

3. En la **Barra de comandos**, haga clic en **Nuevo** para crear un nuevo registro de caso. 

4. Complete su nuevo registro de caso de la siguiente manera: 

    - **Título del caso:** Sobrecalentamiento de la unidad de control 

    - **Cliente:** A. Datum Corporation 

    - **Origen:** Phone 

5. Seleccione la pestaña **Servicio de campo** 

6. En el campo **Tipo de incidente**, seleccione **Sobrecalentamiento de la unidad**. 

7. En la **Barra de comandos**, seleccione **Guardar y cerrar** para guardar y cerrar el registro.  

 

Volveremos al registro de caso que ha creado más adelante. Ahora examinemos cómo crear un registro de orden de trabajo de forma manual.  

 

8. En el panel de navegación de la izquierda, seleccione **Órdenes de trabajo**. 

9. En la **Barra de comandos**, haga clic en **Nuevo** para crear una nueva orden de trabajo. 

10. Complete los detalles de la orden de trabajo con lo siguiente: 

    - **Cuenta de servicio:** Adventure Works 

    - **Lista de precios:** Tarifas de facturación de EE. UU. 

    - **Tipo de incidente principal**: Pérdida de conexión de línea 

    - **Gravable:** No 

11. Seleccione la pestaña **Configuración**. 

12. Establezca el campo **Zona de servicio** en **WA**. 

13. En **Preferencias**, configure las preferencias de la siguiente manera: 

    - **Hora de inicio prometida:** Hoy, 9:00 horas 

    - **Hora de finalización prometida:** Hoy, 11:00 horas 

14. Seleccione **Guardar y cerrar** para guardar los cambios y salir de la orden de trabajo. 

 

Escalar registros de casos es otra manera de crear órdenes de trabajo. En este ejemplo, escalaremos el caso de sobrecalentamiento de unidad de control que creamos anteriormente.  

 

15. En la navegación de la izquierda, seleccione **Casos**.  

16. Abra el caso **Sobrecalentamiento de la unidad de control** que creó anteriormente.  

17. En la **Barra de comandos**, haga clic en el botón **Convertir en orden de trabajo**.  

18. Una vez se ha completado la creación de la orden de trabajo, haga clic en el botón **Aceptar** en la ventana emergente para ver los detalles de la orden de la trabajo.  

19. Seleccione la pestaña **Servicios** y compruebe que los servicios **Inspeccionar estado del sistema** e **Inspeccionar rango de movimiento** se han agregado a la orden de trabajo. 

**NOTA:** Si no los ve inicialmente, presione F5 para actualizar la pantalla.  

20. Seleccione la pestaña **Tarea de servicio** y compruebe que se han agregado 4 tareas. 

Las nuevas órdenes de trabajo están listas para programarse. 
