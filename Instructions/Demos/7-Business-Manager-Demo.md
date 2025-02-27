---
demo:
  title: 'Demostración: administrador de negocio'
---

[Volver al índice](https://microsoftlearning.github.io/MS-4021-Copilot-Immersion-Experience/)

# Demostración: administrador de negocio

**Escenario**:

Analiza el rendimiento de las ventas y los comentarios de los clientes para solucionar un problema con un producto y colabora con tu equipo para planificar mejoras.

## Configuración de demostración

Los documentos de ejemplo se encuentran en el repositorio de GitHub MS-4021 [aquí](https://github.com/MicrosoftLearning/MS-4021-Copilot-Immersion-Experience/tree/master/ResourceFiles).

Estos son los archivos específicos necesarios para esta demostración:

- [EV_Charger_Sales_Analysis_v1.xlsx](https://github.com/MicrosoftLearning/MS-4021-Copilot-Immersion-Experience/raw/master/ResourceFiles/EV_Charger_Sales_Analysis_v1.xlsx)

> **NOTA:** estos archivos pueden tardar hasta 10 minutos en sincronizarse con OneDrive después de su descarga. Para evitar retrasos durante la demostración, asegúrate con antelación de que estos archivos estén descargados y disponibles en OneDrive. Si los archivos no están disponibles, abre los documentos y copia los vínculos del archivo compartido para usarlos en la demostración.

## Pasos de la demostración

### Copilot en Excel

1. Inicia Excel (ya sea en el explorador o en la aplicación de escritorio) y abre el archivo **archivo EV_Charger_Sales_Analysis_v1.xlsx**.

1. **Ve a la pestaña "Sales by Product"** en el archivo de Excel.

1. Usa Copilot para calcular los ingresos mensuales:  

   Comencemos por averiguar qué categoría de tu negocio está impulsando la mayor parte de los ingresos. Esta hoja contiene tres años de datos de ventas, con miles de filas que muestran las ventas por producto por mes. Aunque es una tarea rutinaria, este volumen de datos puede ser complejo. Puedes pedir a Copilot que calcule rápidamente los ingresos mensuales por producto.

   Usa la siguiente indicación:

   ```text
   Calculate monthly revenue by product and add a column with total revenue - refer to the Prices worksheet.
   ```

    - Copilot sabe cómo hacerlo y a qué datos hacer referencia a través de pestañas.
    - Copilot crea un plan para calcular esos números, ejecuta ese plan y muestra su trabajo a medida que avanza, y te pide que hagas preguntas o iteraciones sobre la solución a la que llegó.
    - Haz clic en **+Insertar columna** y luego vuelve a la pestaña **Sales by Product**.

1. Usa Copilot para analizar los ingresos escribiendo la siguiente indicación en el panel de Copilot:

    ```text
    What is the total revenue for each category so far in 2024?
    ```

    - Copilot calculará los números y creará un gráfico de barras que puedes agregar a tu libro.
    - Haz clic en **+Agregar a una nueva hoja** y, a continuación, vuelve a la pestaña **Sales by Product**.

1. Ahora, usa Copilot para resaltar los productos con ventas bajas; para ello, escribe esta indicación:

    ```text
    Highlight rows where the value in column H is less than $100K.
    ```

    - Copilot aplicará un formato condicional, que te ayudará a identificar productos cuyo desempeño no se ajusta a tus estándares.

1. **Ve a la pestaña "Reviews"** para analizar los comentarios de los clientes.

1. Pide a Copilot que resuma las principales preocupaciones; para ello, escribe la siguiente indicación:

    ```text
    Summarize the top 3 customer concerns we should focus on.
    ```

    - Copilot analizará los comentarios y mostrará las tres principales preocupaciones de los clientes. Parece que la velocidad de carga es un problema de nueva aparición.

1. A continuación, resalta los comentarios que mencionan la velocidad de carga con la introducción de esta indicación:

    ```text
    Highlight reviews that mention issues related to charging speeds.
    ```

    - Copilot destacará todos los comentarios pertinentes del conjunto de datos.

### Copilot Chat

Ahora que hemos identificado que la velocidad de carga lenta es un problema clave, usa **Copilot Chat** para explorar el problema en profundidad e identificar posibles soluciones.

1. Abre un explorador y ve a [M365copilot.com](https://m365copilot.com/).  

1. Asegúrate de que el **Modo web** está seleccionado.  

    ![Captura de pantalla que muestra la pestaña modo web.](../Prompts/Media/web-mode.png)

1. Para investigar el problema, escribe la siguiente indicación:
  
    ```text
    Research common issues with EV charger speeds and identify potential causes or solutions. Summarize findings in a format suitable for a business presentation. Highlight any relevant industry benchmarks or competitor data.
    ```

   - Revisa el resumen de Copilot y solicita contexto adicional o tendencias recientes, si es necesario.  

1. Opcionalmente, mejora la salida:
   - Pregunta a Copilot por las tendencias o tecnologías recientes que abordan la eficiencia del cargador para vehículos eléctricos.

    ```text
    What are the latest innovations or technologies addressing slow EV charger speeds in 2024?
    ```

   - Solicita información sobre los competidores:

    ```text
    Assuming competitors in the EV charging market are improving speed by 20% annually, suggest how we could position our CC-2001 and CC-2000 models to stay competitive.
    ```

1. Pide a Copilot que piense en cinco preguntas estratégicas para formular al responsable del proyecto de cargadores para vehículos eléctricos:

    ```text
    Based on this information, suggest 5 strategic questions to ask the product team during our meeting tomorrow. Focus on identifying root causes, assessing risks, and brainstorming potential improvements.
    ```

### Copilot en Outlook

En esta demostración, usaremos Copilot en Outlook para organizar una reunión con el responsable del proyecto encargado de la línea de productos de cargadores para vehículos eléctricos para analizar las posibles soluciones.

1. Abre un explorador y ve a [outlook.office.com](https://outlook.office.com.com/).

1. Para abrir el panel de Copilot, selecciona el icono Copilot en la cinta de Outlook.

1. En la ventana de indicaciones, escribe lo siguiente:

    ```text
    I need to schedule a meeting with [/Pick a colleague] tomorrow afternoon to discuss the EV charger issue reports. Can you suggest a time that works? If they are unavailable, please suggest an alternative time.
    ```

1. Copilot deberá sugerir una hora y una fecha para la reunión. La indicación muestra un elemento de calendario que se puede enviar o editar, selecciona **Editar**.

1. Cambia al asistente de programación para mostrar que la hora sugerida por Copilot le va bien al jefe de proyecto. Ambos deberíais estar disponibles.

1. Vuelve a la pestaña de eventos y selecciona **Borrador con Copilot** en el cuerpo del evento.

1. En la ventana de indicaciones, escribe lo siguiente:

    ```text
    Create an agenda for a meeting to discuss slow charging speeds with our CC-2001 and CC-2000 models. Include time for an introduction to the issue, a review of any available data or customer feedback, and a brainstorming session for potential solutions.  
    ```

1. Opcionalmente, antes de seleccionar **Mantener**, puedes pedir a Copilot que alargue, acorte o cambie el tono de la agenda redactada.

[Volver al índice](https://microsoftlearning.github.io/MS-4021-Copilot-Immersion-Experience/)
