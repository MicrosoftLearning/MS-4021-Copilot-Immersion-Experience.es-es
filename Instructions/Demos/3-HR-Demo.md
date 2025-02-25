---
demo:
  title: 'Demostración: RR. HH.'
---

[Volver al índice](https://microsoftlearning.github.io/MS-4021-Copilot-Immersion-Experience/)

# Demostración: RR. HH.

**Escenario**:  

Optimiza el proceso de contratación de un equipo de diseñadores de experiencia de usuario, creando una descripción de trabajo a medida, seleccionando candidatos en función de sus currículums y redactando una estrategia de contratación para alinear el equipo

## Configuración de la demostración

Los documentos de ejemplo se encuentran en el repositorio de GitHub MS-4021 [aquí](https://github.com/MicrosoftLearning/MS-4021-Copilot-Immersion-Experience/tree/master/ResourceFiles).

Estos son los archivos específicos necesarios para esta demostración:

- [Design_Team_Responsibilities.docx](https://github.com/MicrosoftLearning/MS-4021-Copilot-Immersion-Experience/raw/master/ResourceFiles/Graphic_Design_Institute_Design_Team_Responsibilities.docx)

- [Resume_Patti_Fernandez.docx](https://github.com/MicrosoftLearning/MS-4021-Copilot-Immersion-Experience/raw/master/ResourceFiles/Resume_Patti_Fernandez.docx)

- [Resume_Nestor_Wilke.docx](https://github.com/MicrosoftLearning/MS-4021-Copilot-Immersion-Experience/raw/master/ResourceFiles/Resume_Nestor_Wilke.docx)

- [Resume_Holly_Dickson.docx](https://github.com/MicrosoftLearning/MS-4021-Copilot-Immersion-Experience/raw/master/ResourceFiles/Resume_Holly_Dickson.docx)

- [Resume_Alex_Wilber.docx](https://github.com/MicrosoftLearning/MS-4021-Copilot-Immersion-Experience/raw/master/ResourceFiles/Resume_Alex_Wilber.docx)

> **NOTA:** estos archivos pueden tardar hasta 10 minutos en sincronizarse con OneDrive después de su descarga. Para evitar retrasos durante la demostración, asegúrate con antelación de que estos archivos estén descargados y disponibles en OneDrive. Si los archivos no están disponibles, abre los documentos y copia los vínculos del archivo compartido para usarlos en la demostración.

## Demostraciones

### Copilot en Word

Vamos a comenzar pidiendo a Copilot en Word que genere una descripción del trabajo.

1. Abre Word (ya sea en el explorador o en la aplicación de escritorio).

1. En el cuadro de indicaciones **"Describe lo que deseas escribir",** escribe lo siguiente:

    ```text
    I'm the HR Manager at the Graphic Design Institute. We've currently started the hiring process for a new Senior Animation Designer. Please review the attached document outlining the job responsibilities for this role and generate a detailed job description based on this information.

    [copy link or reference file to Design_Team_Responsibilities.docx]
    ```

    > **NOTA:** Adjunta el archivo Design_Team_Responsibilities.docx o pega el vínculo compartido directamente en la indicación para asegurarte de que Copilot tenga acceso al contenido pertinente.

1. Después de revisar y finalizar la descripción del trabajo, guarda el documento como **GDI_Job_Description.docx** y copia la dirección URL compartida para usarla en el paso siguiente. (Habilita Autoguardado y selecciona la cuenta de OneDrive si se te solicita).

    ![Comparte el vínculo.](../Demos/Media/share-menu-with-copy-link-9fd1c60a.png)

### Copilot Chat

A continuación, vamos a usar Copilot Chat para comparar los currículums que hemos recibido con la descripción del trabajo e identificar los mejores candidatos.

1. Abre un explorador y ve a [M365copilot.com](https://m365copilot.com/).

1. Asegúrate de que el Modo trabajo está seleccionado.

    ![Captura de pantalla que muestra la pestaña modo web.](../Prompts/Media/work-mode.png)

1. En Windows, escribe lo siguiente la ventana de solicitudes:

    ```text
    We are hiring for the position of Senior Animation Designer. Please analyze the attached resumes and compare them to the requirements outlined in the job description provided here: [paste link to GDI_Job_Description.docx]. Rank the candidates from most qualified to least qualified, based on their alignment with the role.

    [Resume - Patti Fernandez
    Resume - Nestor Wilke
    Resume - Holly Dickson
    Resume - Alex Wilber]
    ```

    > **NOTA:** adjunta los currículums o cárgalos en la ventana de solicitudes. Como alternativa, haz referencia a cada archivo mediante los vínculos compartidos o los nombres de archivo en tu OneDrive.

1. Opcionalmente, puedes pedir a Copilot Chat que exporte su respuesta a un documento de Word para destacar esta característica.

### Copilot en Outlook

Por último, usa Copilot en Outlook para redactar un correo electrónico al equipo de contratación con respecto a los principales candidatos.

1. Abre Outlook (ya sea en el explorador o en la aplicación de escritorio).

1. Selecciona **Nuevo correo electrónico**.

1. Selecciona **Copilot** en la cinta de opciones. Selecciona **Borrador con Copilot** en el menú desplegable.

1. En la ventana de solicitudes **"¿Qué quieres que diga este correo electrónico?"**, escribe lo siguiente:

    ```text
    Please draft an email to the hiring team to share that Nester Wilke and Patti Fernandez align best with the Senior Animation Designer role based on their qualifications. Include a recommendation to schedule interviews for these candidates and request feedback on next steps.
    ```

[Volver al índice](https://microsoftlearning.github.io/MS-4021-Copilot-Immersion-Experience/)
