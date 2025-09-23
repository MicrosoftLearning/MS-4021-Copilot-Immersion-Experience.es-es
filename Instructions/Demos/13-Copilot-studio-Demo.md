---
demo:
  title: "Creación de un agente con Copilot\_Studio lite"
---

[Volver al índice](https://microsoftlearning.github.io/MS-4021-Copilot-Immersion-Experience/)

---

# Creación y publicación de un agente mediante Copilot Chat lite

En esta demostración se explica cómo crear un asistente virtual mediante Copilot Studio lite a través de Copilot Chat y publicarlo en Microsoft 365 Copilot.

## Configuración de la demostración

Para completar estas demostraciones, deberá descargar los siguientes archivos:

- [**Delivery Drone Press Release.docx**](https://github.com/MicrosoftLearning/MS-4008-Microsoft-365-Copilot-Interactive-Experience-for-Executives/raw/master/ResourceFiles/Delivery_Drone_Press_Release.docx)
- [**Delivery Drone Troubleshooting.docx**](https://github.com/MicrosoftLearning/MS-4008-Microsoft-365-Copilot-Interactive-Experience-for-Executives/raw/master/ResourceFiles/Delivery_Drone_Troubleshooting.docx)
- [**Delivery Drone SOP.docx**](https://github.com/MicrosoftLearning/MS-4008-Microsoft-365-Copilot-Interactive-Experience-for-Executives/raw/master/ResourceFiles/Delivery_Drone_SOP.docx)
- [**Upselling Opportunities.docx**](https://github.com/MicrosoftLearning/MS-4008-Microsoft-365-Copilot-Interactive-Experience-for-Executives/raw/master/ResourceFiles/Upselling_Opportunities.docx)
- [**Delivery Drone FAQ.docx**](https://github.com/MicrosoftLearning/MS-4008-Microsoft-365-Copilot-Interactive-Experience-for-Executives/raw/master/ResourceFiles/Delivery_Drone_FAQ.docx)

> **SUGERENCIA:** Antes de entregar la demostración, puede crear un sitio de SharePoint en el entorno de demostración a fin de almacenar todos los archivos y facilitar el acceso. Como alternativa, puede almacenar los archivos localmente y hacerles referencia directamente en los mensajes mediante **/**.

## Puntos de conversación

Copilot Studio lite permite crear copilotos personalizados, adaptados a proyectos, departamentos o bases de conocimiento específicos. Podemos darles una personalidad, establecer sus límites y proporcionarles documentos específicos para garantizar respuestas fundamentadas de alta calidad.

En esta demostración, se creará un asistente virtual para el proyecto de entrega de drones ReleCloud. El asistente sabrá todo lo que se ha cargado y ayudará a responder a preguntas del equipo, lo que ahorra tiempo y mejora la productividad.

## Pasos de la demostración

### Paso 1: Navegación a Copilot Studio lite

1. Vaya a [https://m365.cloud.microsoft/chat](https://m365.cloud.microsoft/chat) y seleccione **Crear agente** en el panel de navegación.

    ![Recorte de pantalla en el que se muestra el enlace Crear un agente.](../Prompts/Media/create-agent.png)

1. Inicie sesión con sus credenciales.

### Paso 2: Definición del agente

1. Agregue la siguiente descripción cuando se le solicite:

    ```text
    You're a virtual project manager assistant for our drone delivery project. You know everything about the project from the documents we've shared with you, and are happy to help team members get the information they need.
    ```

   ![Recorte de pantalla en el que se muestra la característica Describir.](../Prompts/Media/create-agent-through-describe.png)

1. Asigne un nombre al asistente:

    ```text
    Drone Delivery Assistant
    ```

1. Si se le pide confirmación:

    ```text
    Yes, thank you
    ```

1. Si se le pide qué se debe evitar o resaltar:

    ```text
    Please be clear and concise and avoid long answers. Where possible, refer primarily to the knowledge shared with you. If you don't know the answer, refer them to the drone delivery project manager.
    ```

1. Si se le pide el tono de voz:

    ```text
    Friendly and professional
    ```

> **IMPORTANTE:**  Es posible que no se le pidan todas estas opciones, en función del entorno. Si no se le solicita, puede agregar esta información mediante la pestaña **Configurar** de Copilot Studio lite.

### Paso 3: Configuración del agente

1. Seleccione **Configurar** para abrir el editor del agente.
1. Revise y, opcionalmente, actualice la sección **Instrucciones**:

    ```text
    Your name is Drone Delivery Project Manager Assistant. You serve as a virtual project manager for the ReleCloud drone delivery project, with comprehensive knowledge from shared documents. Be clear and concise, avoiding long answers. If the answer is unknown, refer to the drone delivery project manager.
    ```

1. Desplácese hacia abajo hasta la sección **Conocimientos** y seleccione la burbuja de texto **Buscar por nombre o escribir una URL**. Seleccione **Archivos** y agregue los siguientes documentos a la base de conocimiento del agente:

    - **Delivery Drone Press Release.docx**
    - **Delivery Drone Troubleshooting.docx**
    - **Delivery Drone SOP.docx**
    - **Upselling Opportunities.docx**
    - **Delivery Drone FAQ.docx**

        ![Recorte de pantalla en el que se muestran los orígenes de conocimiento.](../Prompts/Media/knowledge-sources.png)

### Paso 4: Prueba del agente

En el panel de pruebas de la derecha, intente formular algunas de las siguientes preguntas:

- `Tell me about the ReleCloud Delivery Drone.`
- `How do I fix the drone error code D-101?`
- `What are the upsell opportunities for ReleCloud?`
- `What’s the duration of Phase 1 of the delivery drone project?`

> **IMPORTANTE:**   El agente puede tardar algún tiempo en procesar los documentos y proporcionar respuestas precisas. Si recibe un mensaje de error, espere unos minutos y vuelva a intentarlo.

> **SUGERENCIA:** También puede realizar la prueba desde Microsoft Teams una vez que el agente esté activo.

### Paso 5: Publicación y uso compartido

1. Seleccione **Crear** para publicar el agente.
1. Seleccione **Cambiar la configuración de uso compartido** y elija **Cualquiera de la organización**.
1. Copie el vínculo para compartir y péguelo en un chat de Teams para facilitar el acceso.

Cuando esté activo, puede interactuar con el agente en el chat de Teams o mediante @mentions.

[Volver al índice](https://microsoftlearning.github.io/MS-4021-Copilot-Immersion-Experience/)
