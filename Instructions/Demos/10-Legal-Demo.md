---
demo:
  title: 'Demostración: legal'
---

[Volver al índice](https://microsoftlearning.github.io/MS-4021-Copilot-Immersion-Experience/)

# Demostración: legal

**Escenario**:  

Eres un asesor legal de Contoso. Eres responsable de evaluar si el software de selección de currículums mediante IA de la empresa cumple con la Ley de IA de la UE. Tu objetivo es investigar los riesgos legales, redactar un resumen ejecutivo y transmitir las recomendaciones a la dirección.

## Configuración de la demostración

No se requieren documentos de ejemplo para esta demostración.

## Demostraciones

### Copilot Chat

Empecemos por investigar la Ley de IA y su posible impacto en la herramienta de contratación mediante IA de Contoso.

1. Abre un explorador y ve a [M365copilot.com](https://m365copilot.com/).

1. Asegúrate de que el **Modo web** está seleccionado.

    ![Captura de pantalla que muestra la pestaña modo web.](../Prompts/Media/web-mode.png)

1. En Windows, escribe lo siguiente la ventana de solicitudes:

    ```text
      Contoso is launching an AI Resume Screening Software to evaluate job applicants. As a legal advisor, I need to assess whether it complies with the EU Artificial Intelligence Act. Summarize key provisions related to AI in hiring, compliance requirements for high-risk systems, and potential legal risks.
    ```

1. Revisa la respuesta de Copilot y toma notas sobre los riesgos legales y los requisitos de cumplimiento pertinentes.

1. Ahora le formularemos a Copilot una serie de preguntas de seguimiento para recopilar más información:

    ```text
    Does the AI Act classify resume screening software as a high-risk AI system?
    ```

    ```text
    What are the key obligations for high-risk AI systems under the AI Act?
    ```

    ```text
    Are there any exemptions in the AI Act that could apply to Contoso’s system?
    ```

1. Ahora pide a Copilot que resuma toda la información que tiene de momento:

    ```text
    Summarize all the information we've discussed into a structured list, ensuring no key details are missed. Then, export the summary to a Word document
    ```

1. Selecciona el hipervínculo que proporciona Copilot para el nuevo documento de Word para abrirlo.

1. Una vez abierto, selecciona **Habilitar edición** y, a continuación, activa "Autoguardado". Selecciona la cuenta de OneDrive cuando se te solicite.

1. Copia la dirección URL compartida para usarla en el paso siguiente. (Habilita Autoguardado y selecciona la cuenta de OneDrive si se te solicita).

    ![Comparte el vínculo.](../Demos/Media/share-menu-with-copy-link-9fd1c60a.png)

### Copilot en Word

Ahora, redactaremos un resumen ejecutivo que describe los riesgos legales y las recomendaciones para la dirección de Contoso.

1. Abre una nueva instancia de Word, ya sea en el explorador o en la aplicación de escritorio.

1. En el cuadro de indicaciones **"Describe lo que deseas escribir",** escribe lo siguiente:

    ```text
    Reference the following document [Link to exported Copilot Chat summary from the first task] and draft an executive summary outlining key legal risks, compliance requirements, and recommendations for Contoso’s AI Resume Screening Software.
    ```

    > **NOTA:** Adjunta el documento o pega el vínculo compartido directamente en la indicación para asegurarte de que Copilot pueda acceder al contenido pertinente.

1. Revisa la salida de Copilot. Antes de seleccionar **Mantener**, mejora la respuesta preguntando a Copilot:

    ```text
    Add a section on the potential business impact of these compliance requirements.
    ```

1. Otras mejoras opcionales:

    - Pide a Copilot que redacte de nuevo las secciones para obtener un tono más profesional.
    - Solicita una versión más corta y concisa si el resumen es demasiado largo.
    - Expande con secciones adicionales.

1. Después de revisar y finalizar el documento, **copia el resumen ejecutivo generado** en el Portapapeles para usarlo en la siguiente demostración.

### Copilot en Outlook

Por último, redactaremos un correo electrónico a la dirección de Contoso que resume nuestros hallazgos y pasos siguientes.

1. Abre Outlook (ya sea en el explorador o en la aplicación de escritorio).

1. Selecciona **Nuevo correo electrónico**.

1. Selecciona **Copilot** en la cinta de opciones. Selecciona **Borrador con Copilot** en el menú desplegable.

1. En la ventana de indicaciones **"¿Qué quieres que diga este correo electrónico?"**, escribe:

   ```text
    Draft an email to Contoso’s executive leadership summarizing our legal assessment of the AI Resume Screening Software under the EU AI Act. Use the following executive summary as a reference.

    [paste Executive Summary from the previous task]

    Conclude the email with a request for leadership’s input on the next steps, including a proposed compliance review meeting.
   ```

    > **NOTA:** pega el contenido del resumen ejecutivo que copiaste de la demostración anterior.

1. Una vez generado el borrador, puedes usar la característica **Ajustar** para modificar el tono, la longitud o el nivel de formalidad.

[Volver al índice](https://microsoftlearning.github.io/MS-4021-Copilot-Immersion-Experience/)
