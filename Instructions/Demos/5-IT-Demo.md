---
demo:
  title: 'Demostración: TI'
---

[Volver al índice](https://microsoftlearning.github.io/MS-4021-Copilot-Immersion-Experience/)

# Demostración: TI

**Escenario**:  

Como administrador de infraestructura de TI, planeas instalar un nuevo producto de seguridad de red en la red corporativa.

## Configuración de la demostración

Los documentos de ejemplo se encuentran en el repositorio de GitHub MS-4021 [aquí](https://github.com/MicrosoftLearning/MS-4021-Copilot-Immersion-Experience/tree/master/ResourceFiles).

Estos son los archivos específicos necesarios para esta demostración:

- [Contoso_CipherGuard_Product_Specification.docx](https://github.com/MicrosoftLearning/MS-4021-Copilot-Immersion-Experience/raw/master/ResourceFiles/Contoso_CipherGuard_Product_Specification.docx)

> **NOTA:** estos archivos pueden tardar hasta 10 minutos en sincronizarse con OneDrive después de su descarga. Para evitar retrasos durante la demostración, asegúrate con antelación de que estos archivos estén descargados y disponibles en OneDrive. Si los archivos no están disponibles, abre los documentos y copia los vínculos del archivo compartido para usarlos en la demostración.

## Demostraciones

### Copilot Chat

Empecemos pidiendo a Copilot que cree un plan de implementación del proyecto.

1. Abre un explorador y ve a [M365copilot.com](https://m365copilot.com/).

1. Asegúrate de que el modo web está seleccionado.

    ![Captura de pantalla que muestra la pestaña modo web.](../Prompts/Media/web-mode.png)

1. En Windows, escribe lo siguiente la ventana de solicitudes:

    ```text
    You are an IT infrastructure manager at Contoso. Your task is to create a detailed project implementation plan for installing a new network security product in your corporate network. Your plan should include key milestones, resource allocation, potential risks, and a timeline to ensure successful deployment and minimal disruption to operations.
    ```

    > **NOTA:** las indicaciones basadas en roles ayudan a Copilot a comprender las responsabilidades y el contexto del usuario, mejorando la relevancia y la especificidad de la salida.

1. Ahora vamos a mejorar el plan del proyecto pidiendo a Copilot que agregue nuevas secciones al plan:

    Escribe la siguiente indicación:

    ```text
    Please add the following sections to the existing plan: testing and QA, training, communication, documentation and reporting, stakeholder analysis, project timeline, and risk assessment and mitigation. Ensure these sections provide detailed action steps and align with the existing content. Avoid duplicating any items already included in the original plan.
    ```

1. Por último, pide a Copilot que genere el plan del proyecto propuesto en un documento de Word:

    Escribe la siguiente indicación:

    ```text
    Please export the project plan to a Word document.
    ```

1. Guarda el documento de Word generado como **Project_Implementation_Plan.docx**. Copia la dirección URL compartida del documento (habilita Autoguardado y selecciona la cuenta de OneDrive si se te solicita).

    ![Comparte el vínculo.](../Demos/Media/share-menu-with-copy-link-9fd1c60a.png)

### Copilot en Word

Ahora pediremos a Copilot que amplíe estas estrategias y redacte propuestas sobre cómo implementarlas.

1. Abre Word (ya sea en el explorador o en la aplicación de escritorio).

1. En el cuadro de indicaciones **Describe lo que deseas escribir**, escribe lo siguiente:

    ```text
    Using the Contoso [/CipherGuard Product Specification.docx] and the 'Project Implementation Plan' template provided in [paste in link to Project_Implementation_Plan.docx], draft a comprehensive project implementation plan for deploying Contoso CipherGuard. Ensure the plan aligns with the product specifications and follows the structure outlined in the template.
    ```

    > **NOTA:** los corchetes indican que se hace referencia a un documento.
    > 1. CipherGuard Product Specification.docx = [Contoso_CipherGuard_Product_Specification.docx](https://github.com/MicrosoftLearning/MS-4021-Copilot-Immersion-Experience/raw/master/ResourceFiles/Contoso_CipherGuard_Product_Specification.docx)
    > 1. Project Implementation Plan.docx = Usa el vínculo que copiaste en la demostración anterior.
    > Al hacer referencia a un documento, puedes pegar el vínculo directamente o hacer referencia al nombre de archivo si está disponible en OneDrive.

1. Selecciona **Mantener** o, si el tiempo lo permite, muestra cómo retocar el documento mediante Copilot.

1. Una vez finalizado, guarda el documento como **Contoso_Project_Plan.docx** y copia la dirección URL compartida (habilita Autoguardar y selecciona la cuenta de OneDrive si se te solicita).

    ![Comparte el vínculo.](../Demos/Media/share-menu-with-copy-link-9fd1c60a.png)

### Copilot en PowerPoint

Ahora usaremos Copilot para generar una presentación de PowerPoint basada en la nueva propuesta para implementar el producto Contoso CipherGuard.

1. Inicia Microsoft PowerPoint desde el explorador [PowerPoint.new](https://PowerPoint.new) o usa la aplicación de escritorio.

1. Abre una nueva presentación en blanco.

1. En el panel de Copilot, selecciona la indicación "Crear presentación a partir de archivo".

1. Pega el vínculo compartido del documento **Contoso_Project_Plan.docx** y selecciona **Enviar**.

    La indicación completa debe ser como la siguiente:

    ```text
    Create a presentation from [Link to Contoso_Project_Plan.docx].
    ```

1. Copilot comienza a generar diapositivas basadas en el plan del proyecto, proporcionando un esquema junto con características como, por ejemplo, notas para el ponente, imágenes, diseños de diapositivas y una etiqueta de confidencialidad general.

    > **NOTA:** la generación de diapositivas puede tardar hasta dos minutos, según la complejidad del documento y el número de diapositivas.

[Volver al índice](https://microsoftlearning.github.io/MS-4021-Copilot-Immersion-Experience/)
