---
demo:
  title: Demostración de Investigador y Analista
---

[Volver al índice](https://microsoftlearning.github.io/MS-4021-Copilot-Immersion-Experience/)

# Demostración de Investigador y Analista

En esta demostración se resalta cómo usar**Investigador** y**Analista**, dos agentes expertos integrados en la aplicación Copilot.  

- **Investigador** le ayuda a abordar tareas de investigación en varios pasos, mediante la combinación de datos web con los archivos y conocimientos de la empresa.  
- **Analista** piensa como un científico de datos cualificado, capaz de realizar análisis avanzados de datos y ejecución de Python, incluso si no sabe cómo programar.  

## Configuración de la demostración

Para completar estas demostraciones, deberá descargar el[Paquete de contenido: Demostración de Investigador y Analista](https://github.com/MicrosoftLearning/MS-4021-Copilot-Immersion-Experience/raw/refs/heads/master/ResourceFiles/Researcher_and_Analyst_Demo_Content_Pack.zip), que contiene todos los archivos y recursos necesarios.  

> **SUGERENCIA:** Antes de entregar la demostración, puede crear un sitio de SharePoint en el entorno de demostración a fin de almacenar todos los archivos y facilitar el acceso. Como alternativa, puede almacenar los archivos localmente y hacerles referencia directamente en los mensajes mediante**/**.  

Para acceder a estos agentes:  

- Abra la**aplicación Copilot** desde[m365.cloud.microsoft](https://m365.cloud.microsoft).  
- Seleccione**Investigador** o**Analista** en el panel de navegación.  

> **Nota:** Deberá apuntar Investigador y Analista a archivos internos (SharePoint u OneDrive) para obtener información fundamentada.

---

## Puntos de conversación

- **Investigador** actúa como un consultor altamente pagado: puede crear entregas estructuradas, bien citadas mediante la combinación de archivos internos, inteligencia de la competencia y orígenes web.  
- **Analista** es como tener un científico de datos a mano: compila modelos, ejecuta código de Python y visualiza tendencias al instante.  
- Los dos agentes explican su razonamiento de forma transparente para que pueda validar los resultados.  
- De manera conjunta, aceleran el trabajo estratégico (planes de marketing, segmentación de clientes, proyecciones financieras) para que pueda avanzar más rápido con confianza.  

---

## Pasos de la demostración

### Investigador: Crear un plan de marketing

> **IMPORTANTE:** Los pasos 1–4 deben completarse al principio del entrenamiento (como se indica en la diapositiva 5) a fin de que Investigador tenga tiempo suficiente para completar el primer mensaje.

1. Abra**Investigador** desde el panel de navegación.  

    ![Recorte de pantalla en el que se muestra la selección de Investigador en el menú M365 Copilot.](../Prompts/Media/researcher.png)  

1. Escriba lo siguiente:

    ```text
    Create a marketing plan for our newest SprintCycle EV charger launch. 
    Emphasize its AI-powered adaptive charging, modular design, and biometric access control. 
    Make sure to include recommendations on the right digital channels and content strategy. 
    Include insights from competitors and our past GTM campaigns.
    ```

1. Adjunte archivos de referencia mediante`/` (debe apuntar a SharePoint u OneDrive):  

   - **/SprintCycle Charger Product Launch.docx**  
   - *(Opcional)***/Contoso - PedalPerks GTM Plan.docx**  

1. Seleccione**Submit** (Enviar).  

Investigador hará lo siguiente:  

- Combinará información de archivos internos y de la web.  
- Estructurará un plan de marketing con recomendaciones sobre canales y estrategia de contenido.  
- Citará orígenes para que pueda validar su trabajo.  

> **Nota:** Investigador muestra su ruta de razonamiento ("cadena de pensamiento") y puede llamar a otros agentes cuando sea necesario.  

### Analista: Segmentación de clientes y modelado financiero

**Nota:** Esta demostración no se realiza para la versión ejecutiva del contenido, en su lugar, pase a la demostración de**Copilot Studio**.

1. Abra**Analista** desde el panel de navegación.

    ![Recorte de pantalla en el que se muestra la selección de Analista en el menú M365 Copilot.](../Prompts/Media/analyst.png)  

1. Escriba lo siguiente:

    ```text
    Find the right customer segment and demographic to sell our new EV charger, 
    include a graph to show how this will maximize our market opportunity.
    ```

1. Adjunte el archivo mediante**+**:  

   - **BoulderEV ebike Internal Market Forecast.xlsx**  

    ![Recorte de pantalla en el que se muestran los archivos adjuntos en Analista.](../Prompts/Media/Analyst-Attach-Files.png)  

1. Haga clic en**Enviar**.  

Analista hará lo siguiente:  

- Analizará el conjunto de datos.  
- Identificará los segmentos de clientes de mayor valor.  
- Proporcionará visualizaciones para fundamentar las recomendaciones.  

### Escenarios de Analista adicionales

Puede ejecutar estos mensajes adicionales de otras tareas. En cada uno se sigue el mismo patrón:**Mensaje → Adjuntar archivo → Enviar → Revisar los resultados.**

- **Proyección financiera**  

    ```text
    Build a 5-year financial projection from this data along with a graph to view revenue growth over time.
    ```  

    Archivo:**BoulderEV ebike Internal Market Forecast.xlsx**  

- **Rendimiento de ventas**  

    ```text
    Analyze sales volume across locations to identify our highest and lowest performing stores, 
    along with a visualization of the best-selling products.
    ```  

    Archivo:**BoulderEV ebike Internal Market Forecast.xlsx**  

- **Rendimiento de la campaña**  

    ```text
    Analyze and visualize how the marketing campaign performed across each target segment 
    and help me decide where to re-target our next campaign.
    ```  

    Archivo:**BoulderEV ebike Internal Market Forecast.xlsx**  

## Conclusión principal

- **Investigador**: acelera la estrategia y la planificación con investigación de alta calidad.  
- **Analista**: ofrece información controlada por datos con análisis avanzado y visualizaciones.  

De manera conjunta, Investigador y Analista acortan el camino de**la pregunta a la conclusión**, y convierten semanas de esfuerzo en minutos.  

[Volver al índice](https://microsoftlearning.github.io/MS-4021-Copilot-Immersion-Experience/)
