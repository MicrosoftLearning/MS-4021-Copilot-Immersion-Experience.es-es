---
demo:
  title: 'Demostración: finanzas'
---

[Volver al índice](https://microsoftlearning.github.io/MS-4021-Copilot-Immersion-Experience/)

# Demostración: finanzas

**Escenario**:  

Eres un analista financiero de Contoso. Eres responsable de evaluar el rendimiento de las ventas y el posicionamiento del mercado en el sector de carga para vehículos eléctricos. Tu objetivo es analizar los datos de ventas, generar información y preparar un resumen para el equipo.

## Configuración de la demostración

Los documentos de ejemplo se encuentran en el repositorio de GitHub MS-4021 [aquí](https://github.com/MicrosoftLearning/MS-4021-Copilot-Immersion-Experience/tree/master/ResourceFiles).

Estos son los archivos específicos necesarios para esta demostración:

- [EV_Charger_Sales_Analysis_v1.xlsx](https://github.com/MicrosoftLearning/MS-4021-Copilot-Immersion-Experience/raw/master/ResourceFiles/EV_Charger_Sales_Analysis_v1.xlsx)

### Copilot en Excel  

Usa Copilot en Excel para analizar los datos de ventas, identificar las principales tendencias y calcular métricas financieras.

1. Iniciar Excel y abrir el archivo  

1. Abra **EV_Charger_Sales_Analysis_v1.xlsx** en Excel (ya sea en el explorador o en la aplicación de escritorio).  

1. Ve a la pestaña **"Sales by Product"**.  

1. Seleccione **Copilot** en la cinta de Excel y, a continuación, seleccione **Aptitudes de aplicación** para abrir el panel de Copilot.

1. Usa Copilot para ordenar la tabla escribiendo la siguiente indicación:  

    ```text
    Sort the table by date in descending order, from the most recent to the oldest entry.
    ```  

    - Copilot ordenará la tabla y actualizará el conjunto de datos.  
    - Selecciona **"Aplicar"** después de ordenar.  

1. Insertar la columna "Total Revenue"  

    En el panel de Copilot, escribe la indicación siguiente:  

    ```text
    Add a new column named 'Total Revenue'. Populate it by multiplying 'Units Sold' by 'Product Price' for each row.
    ```  

    - Copilot creará la nueva columna y aplicará la fórmula.  
    - Selecciona **"Insertar columna".**  

1. Generar una tabla de resumen de ventas para 2024  

    En el panel de Copilot, escribe la indicación siguiente:  

    ```text
    Create a summary table for total sales in 2024. The table should include Product ID, total units sold, and total revenue.
    ```  

    - Copilot generará un resumen.  
    - Selecciona **"Agregar a una nueva hoja de datos"** para almacenar la tabla por separado.  
    - Asegúrate de que la tabla **solo incluye solo datos de 2024**.  
    - Vuelve a la pestaña **"Sales by Product"** o selecciona **"Volver a los datos"** en la última respuesta de Copilot.  

1. Identificar el producto más vendido  

    En el panel de Copilot, escribe la indicación siguiente:  

    ```text
    Identify the product ID with the highest total revenue in 2024. Provide both total revenue and total units sold for better comparison.
    ```  

    - Copilot analizará el conjunto de datos y proporcionará el producto más vendido.
    - Vuelve a la pestaña **"Sales by Product"** o selecciona **"Volver a los datos"** en la última respuesta de Copilot.  

1. Ordenar clientes por ingresos

    - Ve a la hoja **"Customers"** en Excel.

    En el panel de Copilot, escribe la indicación siguiente:  

    ```text
    Sort the 'Customers' tab by annual revenue in descending order.
    ```  

    - Copilot ordenará a los clientes por **ingresos anuales**.  
    - Selecciona **"Aplicar"** después de ordenar.  

1. Calcular el promedio de ingresos por cliente

    Escribe la siguiente indicación:  

    ```text
    Calculate the average revenue per customer.
    ```  

    - Copilot calculará el promedio y agregará el resultado.  
    - Selecciona **"Insertar fila"** para almacenar el valor medio de ingresos.  

1. Buscar el sector que usa la mayor potencia  

    En el panel de Copilot, escribe la indicación siguiente:  

    ```text
    Analyze the data to determine which industry has the highest total power consumption. Provide the industry name and total power usage.
    ```  

    - Copilot procesará los datos y devolverá el sector con el mayor consumo de energía.

1. Guarde el documento. Copia la dirección URL compartida del documento (habilita Autoguardado y selecciona la cuenta de OneDrive si se te solicita).

    ![Comparte el vínculo.](../Demos/Media/share-menu-with-copy-link-9fd1c60a.png)

### Copilot Chat

Usa Copilot Chat para comparar el rendimiento financiero con las pruebas comparativas del sector y los competidores.

1. Abre un explorador y ve a [M365copilot.com](https://m365copilot.com/).

1. Asegúrate de que el Modo web está seleccionado.

    ![Captura de pantalla que muestra la pestaña modo web.](../Prompts/Media/web-mode.png)

1. En Windows, escribe lo siguiente la ventana de solicitudes:

    ```text
    Our total revenue for [EV chargers] exceeded $50,000,000 for firth half of 2024. Compare this to the industry average and provide insights on whether we are above or below industry standards. If possible, include market share estimates and trends
    ```

1. Ahora pide a Copilot Chat que compare esto con los competidores:

    ```text
    Summarize the key financial statements of two major competitors in the [EV charging] industry. Include revenue, net profit, and any other relevant financial insights. If available, provide comparisons to our financial performance.
    ```

1. Por último, pide a Copilot que exporte el historial de chat hasta la fecha a un documento de Word:

    ```text
    Export this conversation, including financial insights, to a Word document for further review.
    ```

1. Selecciona el archivo vinculado para descargar y, a continuación, abre el documento.

1. Selecciona **Habilitar edición**.

1. El archivo debe tener un nombre similar a "**Charging_industry_Financial_Summary.docx**". Copia la dirección URL compartida del documento (habilita Autoguardado y selecciona la cuenta de OneDrive si se te solicita).

    ![Comparte el vínculo.](../Demos/Media/share-menu-with-copy-link-9fd1c60a.png)

### Copilot en Word

Usa Copilot en Word para resumir la información financiera en un correo electrónico para el equipo.

1. Abre un nuevo documento de Word (ya sea en el explorador o en la aplicación de escritorio).

1. En el cuadro de indicaciones **"Describe lo que deseas escribir",** escribe lo siguiente:

    ```text
    Draft an email to my team summarizing the key insights from [Charging_industry_Financial_Summary.docx].
    ```

    > **NOTA:** Adjunta el archivo Charging_industry_Financial_Summary.docx que creaste en la tarea anterior o pega el vínculo compartido directamente en la indicación para asegurarte de que Copilot tiene acceso al contenido pertinente.

1. Revisa la salida de Copilot. Antes de seleccionar **Mantener**, mejora la respuesta preguntando a Copilot:

    ```text
    Shorten this email draft
    ```

1. Otras mejoras opcionales:

    - Pide a Copilot que redacte de nuevo las secciones para obtener un tono más profesional.
    - Expande con secciones adicionales.
    - Hacer que sea menos formal

1. Una vez finalizado, puedes seleccionar **Mantener**

[Volver al índice](https://microsoftlearning.github.io/MS-4021-Copilot-Immersion-Experience/)
