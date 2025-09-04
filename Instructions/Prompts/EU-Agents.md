---
task:
  title: 'Experiencia de inmersión: Agentes (usuarios empresariales)'
---

## Experiencia de inmersión: Agentes (usuarios empresariales)

Descubra cómo Microsoft 365 Copilot y Copilot Studio pueden ayudarle a resolver desafíos de productividad cotidianos mediante el diseño de un **agente simple basado en recuperación**. En este ejercicio simplificado se le guiará por la identificación de un problema común, la exploración de cómo la inteligencia artificial podría ayudar y, después, la creación de un agente sencillo para probarlo.  

Realizarás tres tareas:

- Identificación de un punto débil de productividad  
- Exploración de cómo la inteligencia artificial podría ayudar con la recuperación y la organización  
- Compilación y prueba de un agente sencillo en **Copilot Studio**  

> **NOTA:** Se proporcionan mensajes de ejemplo para ayudarle a empezar: no dude en personalizarlos para adaptarlos a su situación.  
>
> Si quiere ayudar a generar o refinar mensajes, pruebe el <a href="https://appsource.microsoft.com/en-us/product/office/WA200007578" target="_blank">agente Asistente de solicitudes</a>, que puede sugerir, mejorar y evaluar mensajes para que obtenga mejores resultados con Copilot.

### Tarea 1: Identificar un punto débil de productividad  

Piense en un problema común en su trabajo diario, algo que le ralentiza o que dificulta encontrar o organizar la información. Puede reflexionar individualmente o usar **Copilot Chat** como asociado para ayudarle a generar ideas y exponer puntos débiles comunes.

Ejemplos:

- Búsqueda de la versión más reciente de un documento  
- Recopilación de actualizaciones de varios correos electrónicos o chats  
- Recordar detalles de proyectos o reuniones anteriores  

**Pasos**:  

- Abra una nueva pestaña del explorador y vaya a [m365.cloud.microsoft/chat](https://m365.cloud.microsoft/chat). 

- Asegúrese de que la pestaña **Modo Trabajo** está seleccionada en **Copilot Chat**.  

   ![Recorte de pantalla en el que se muestra la pestaña Modo trabajo en Copilot Chat.](../Prompts/Media/work-mode.png)  

    **Mensaje de muestra:**

    ```text
    Summarize the top challenges I face in my daily work, based on recent emails, chats, and documents. Show results in a simple list with: 
    
    - Title (short label for the issue) 
    - Description (1–2 sentences) 
    ```  

### Tarea 2: Exploración de ideas de soluciones de IA con Investigador  

Use el **Agente Investigador** para explorar cómo Copilot o los agentes pueden ayudar con el desafío elegido.

**Pasos**:  

- En el menú Copilot Chat expanda **Agentes** y seleccione **Investigador**.  

   ![Recorte de pantalla en el que se muestra la selección de Investigador en el menú M365 Copilot.](../Prompts/Media/researcher.png)  

- Pruebe un mensaje de ejemplo como este:  

   ```text
   Explore possible AI solutions to help with [insert productivity issue]. Focus on retrieval-based approaches using Microsoft Copilot or Copilot Studio agents. Summarize two or three ways an agent could help me find, organize, or summarize information more efficiently.
   ```  

    > **SUGERENCIA:** Céntrese en casos de uso prácticos y cotidianos, como mostrar rápidamente un documento o extraer actualizaciones de varios orígenes.
  
    > **NOTA:** Investigador puede tardar entre 5 y 10 minutos en completarse, en función de la solicitud. Sus respuestas son muy detalladas, por lo que mientras funciona, intente ejecutar el mismo mensaje en Copilot Chat. La comparación de las dos salidas es una excelente manera de ver cómo aborda la tarea cada herramienta.
    
### Tarea 3: Creación y prueba del agente  

Ahora, cree un agente de recuperación simple en **Copilot Studio** para abordar el desafío.  

**Pasos**:  

1. En el menú **Copilot Chat**, seleccione **Crear agente**.

   ![Recorte de pantalla en el que se muestra el enlace Crear un agente.](../Prompts/Media/create-agent.png)  

1. En la pestaña **Describir**, escriba el rol del agente. Por ejemplo:  

   ```text
   You’re a virtual assistant that helps me with [key task]. Be concise and always reference my recent files or resources when possible.
   ```  

   ![Recorte de pantalla en el que se muestra el agente de descripción con el mensaje de ejemplo rellenado.](../Prompts/Media/create-agent-through-describe.png)  

1. Seleccione la pestaña **Configurar** y agregue una fuente de conocimiento (por ejemplo, **Mis correos electrónicos** o **Mis chats y reuniones de Teams**).

    ![Recorte de pantalla en el que se muestra la sección de orígenes de conocimiento en el generador de agentes.](../Prompts/Media/knowledge-sources.png)

1. Pruebe el agente con el panel **Probar** y realice los retoques necesarios.  
1. Seleccione **Crear** para publicar el agente y empezar a usarlo.  

> **SUGERENCIA:** Incluso un agente muy sencillo, como uno que le ayuda a encontrar archivos recientes del proyecto, puede mostrar la eficacia de la recuperación en su trabajo diario.
