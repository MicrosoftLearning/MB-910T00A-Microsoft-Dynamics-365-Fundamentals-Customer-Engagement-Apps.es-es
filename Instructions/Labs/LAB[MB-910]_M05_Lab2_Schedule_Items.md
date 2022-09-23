---
lab:
  title: 'Laboratorio 4.2: Programar elementos en Dynamics 365 Field Service'
  module: 'Module 4: Learn the Fundamentals of Dynamics 365 Field Service'
ms.openlocfilehash: ca0728e865cf16478ab84f160cf34538e521c91e
ms.sourcegitcommit: 6065e6a662bd0407d37fcc565c1b2da1c916255d
ms.translationtype: HT
ms.contentlocale: es-ES
ms.lasthandoff: 04/29/2022
ms.locfileid: "144405069"
---
<a name="module-4-learn-the-fundamentals-of-dynamics-365-field-service"></a>Módulo 4: Aspectos básicos de Dynamics 365 Field Service
========================

## <a name="practice-lab-42---schedule-items-in-dynamics-365-field-service"></a>Laboratorio de prácticas 4.2 Programar elementos en Dynamics 365 Field Service

## <a name="lab-setup"></a>Configuración del laboratorio

  - **Tiempo estimado**: 20 minutos

  **Nota:** El panel Requisitos de reserva no se puede abrir en Internet Explorer. Use Microsoft Edge o Google Chrome para completar este ejercicio.
  
## <a name="instructions"></a>Instrucciones

1.  Si aún no la ha abierto, abra la aplicación **Dynamics 365 Field Service**.  

2.  En el panel de navegación de la izquierda, seleccione **Órdenes de trabajo**.

3.  En la **Barra de comandos**, haga clic en **Nuevo** para crear una nueva orden de trabajo.

4.  Complete los detalles de la orden de trabajo con lo siguiente:
    - Cuenta de servicio: ADatum Corporation
    - Tipo de incidente principal: Lector de MRI inactivo
    - Gravable: No
    
5.  Seleccione **Guardar y cerrar** para guardar los cambios y salir de la orden de trabajo.

6.  En la **Barra de comandos** de la **órden de trabajo**, seleccione el botón **Reservar**.  Esto iniciará el **Asistente de programación**.  

7.  Se le presentarán opciones para programar el elemento.  Seleccione el registro de **Ryan Brim**.

8.  En la ventana **Crear reserva de recursos**, establezca la **hora de inicio** en el **comienzo de la siguiente hora**.

9.  Establezca la **hora de finalización** 2,5 horas después.  

10. Haga clic en el botón **Reservar y finalizar** para reservar el recurso y cerrar la ventana de programación.  

11. Una vez de vuelta en la vista de la orden de trabajo, haga clic en **Guardar y cerrar** en la **Barra de comandos**.  

12. En la navegación de la izquierda, seleccione **Tablero de programación**.

13. En la parte inferior de la pantalla, en el panel de requisitos, seleccione **Órdenes de trabajo sin programar**.

14. Seleccione la orden de trabajo **Adventure Works** que creó antes con el número de la orden de trabajo apuntada. En el menú que aparece, seleccione **Buscar disponibilidad.** .  

15. Esto iniciará el **Asistente de programación**.  

16. Se le presentarán opciones para programar el elemento.  Seleccione el registro de Bob Kozak.

17. En la ventana **Crear reserva de recursos**, establezca la **hora de inicio** en el **comienzo de la siguiente hora**.

18. Establezca la **hora de finalización** 2,5 horas después.
  
19. Haga clic en el botón **Reservar y finalizar** para reservar el recurso y cerrar la ventana de programación. 

20. A veces tendrá que volver a programar una orden de trabajo debido a conflictos con los técnicos u otros elementos.  Esto lo pueden hacer los distribuidores fácilmente desde el tablero de programación.  

21. Haga clic en el cuadro de búsqueda de recursos del tablero de programación (ubicado justo encima de la columna del nombre del recurso), escriba Ryan y localice la orden de trabajo programada para Ryan hoy más tarde.  

22. Haga clic con el botón derecho en la orden de trabajo y, en el menú que aparece, seleccione **Sustituir recurso** y, después, **Encontrar sustitución**.


