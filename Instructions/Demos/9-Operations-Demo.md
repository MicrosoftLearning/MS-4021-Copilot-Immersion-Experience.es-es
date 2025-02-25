---
demo:
  title: 'Demostración: operaciones'
---

[Volver al índice](https://microsoftlearning.github.io/MS-4021-Copilot-Immersion-Experience/)

# Demostración: operaciones

## Escenario

Eres un administrador de operaciones en Contoso, responsable de la adquisición de proveedores y la ejecución de proyectos. Tu objetivo es revisar las RFP anteriores, extraer los criterios de selección clave y redactar una nueva RFP para una próxima iniciativa.

## Configuración de la demostración

Los documentos de ejemplo se encuentran en el repositorio de GitHub MS-4021 [aquí](https://github.com/MicrosoftLearning/MS-4021-Copilot-Immersion-Experience/tree/master/ResourceFiles).

Estos son los archivos específicos necesarios para esta demostración:

- [Contoso_Completed_RFP.docx](https://github.com/MicrosoftLearning/MS-4021-Copilot-Immersion-Experience/raw/master/ResourceFiles/Contoso_Completed_RFP.docx)

- [Project_Guidelines_Contoso.docx](https://github.com/MicrosoftLearning/MS-4021-Copilot-Immersion-Experience/raw/master/ResourceFiles/Project_Guidelines_Contoso.docx)

- [Contoso_RFP_Template.docx](https://github.com/MicrosoftLearning/MS-4021-Copilot-Immersion-Experience/raw/master/ResourceFiles/Contoso_RFP_Template.docx)

> **NOTA:** estos archivos pueden tardar hasta 10 minutos en sincronizarse con OneDrive después de su descarga. Para evitar retrasos durante la demostración, asegúrate con antelación de que estos archivos estén descargados y disponibles en OneDrive. Si los archivos no están disponibles, abre los documentos y copia los vínculos del archivo compartido para usarlos en la demostración.

## Demostraciones

### Copilot en Word

Comencemos por hacerle a Copilot en Word algunas preguntas sobre un documento de solicitud de propuesta (RFP).

1. Abre Word (ya sea en el explorador o en la aplicación de escritorio).
1
1. Abre el siguiente documento: [Contoso_Completed_RFP.docx](https://github.com/MicrosoftLearning/MS-4021-Copilot-Immersion-Experience/raw/master/ResourceFiles/Contoso_Completed_RFP.docx)

1. Para abrir el panel de Chat, selecciona el icono Copilot en la cinta de opciones de Word.

    ![Captura de pantalla que muestra la pestaña Modo trabajo.](../Demos/Media/copilot-ribbon-word.png)

1. En el panel de chat, selecciona o escribe la indicación:

   ```text
   Summarize this document
   ```

1. Después, escribe la siguiente indicación:

   ```text
   Analyze this document and generate a categorized list of required items needed to create an RFP.
   ```

1. A continuación, escribe para pedir a Copilot que cree una plantilla RFP:

   ```text
   Analyze this document and create an RFP template based on the content.
   ```

    > **NOTA:** no es necesario copiar el contenido generado, ya que usaremos un documento de plantilla creado previamente en la siguiente demostración. Sin embargo, puedes mostrar cómo copiar la respuesta de Copilot o insertarla en el documento si es relevante para tu público.

### Copilot Chat

Ahora que hemos resumido el documento RFP y hemos creado una plantilla RFP, usaremos Copilot Chat para resumir los requisitos del proyecto para una nueva RFP.

1. Abre un explorador y ve a [M365copilot.com](https://m365copilot.com/).  

1. Asegúrate de que el **Modo web** está seleccionado.

    ![Captura de pantalla que muestra la pestaña modo web.](../Prompts/Media/web-mode.png)

1. Escribe la siguiente indicación:

   ```text
   Summarize [Project_Guidelines_Contoso.docx] highlighting the key objectives, scope, implementation timeline, budget, compliance needs, and vendor selection criteria in a bulleted list.
   ```

    > **NOTA:** los corchetes indican que se hace referencia a un documento. Usa el vínculo: [Project_Guidelines_Contoso.docx](https://github.com/MicrosoftLearning/MS-4021-Copilot-Immersion-Experience/raw/master/ResourceFiles/Project_Guidelines_Contoso.docx)

1. A continuación, pide a Copilot que extraiga los criterios de selección de proveedores:

   ```text
   Extract and summarize the key vendor selection criteria from this document, including weight percentages and evaluation factors.
   ```

1. Después, pide a Copilot que cree una RFP en función de las directrices del proyecto:

   ```text
   Using the project requirements outlined above, draft an RFP using the following template: [Contoso_RFP_Template.docx].
   ```

    > **NOTA:** los corchetes indican que se hace referencia a un documento.

1. **Copia la RFP** generada en el Portapapeles para usarla en la siguiente demostración.

1. Opcionalmente, pide a Copilot que exporte la RFP generada a un documento de Word.

### Copilot en Outlook

Por último, usa Copilot en Outlook para redactar un correo electrónico para los posibles proveedores que resume el documento RFP.

1. Abre Outlook (ya sea en el explorador o en la aplicación de escritorio).

1. Selecciona **Nuevo correo electrónico**.

1. Seleccione **Copilot** en la cinta de opciones. Selecciona **Borrador con Copilot** en el menú desplegable.

1. En la ventana de solicitudes **"¿Qué quieres que diga este correo electrónico?"**, escribe:

   ```text
   Draft an email to potential suppliers summarizing the RFP below:

   [paste contents of RFP]
   ```

    > **NOTA:** pega el contenido de RFP que copiaste de la demostración anterior.

1. Una vez generado el borrador, puedes usar la característica **Ajustar** para modificar el tono, la longitud o el nivel de formalidad.

[Volver al índice](https://microsoftlearning.github.io/MS-4021-Copilot-Immersion-Experience/)
