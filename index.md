---
title: Instrucciones hospedadas en línea
permalink: index.html
layout: home
---

A continuación, se enumeran los hipervínculos a cada una de las demostraciones.

## Demostraciones

{% assign demos = site.pages | where_exp:"page", "page.url contains '/Instructions/Demos'" %}
| Demostración |
| --- |
{% for activity in demos  %}| [{{ activity.demo.title }}]({{ site.github.url }}{{ activity.url }}) |
{% endfor %}

## Indicaciones de ejemplo para la experiencia de inmersión

#### [Ejecutivos](https://learn.microsoft.com/en-us/training/modules/envision-new-ideas-with-microsoft-365-copilot/) (redirige a Microsoft Learn)

#### [Comunicaciones](https://microsoftlearning.github.io/MS-4021-Copilot-Immersion-Experience/Instructions/Prompts/Communications-Prompts.html)

#### [RR. HH.](https://microsoftlearning.github.io/MS-4021-Copilot-Immersion-Experience/Instructions/Prompts/HR-Prompts.html)

#### [Ventas](https://microsoftlearning.github.io/MS-4021-Copilot-Immersion-Experience/Instructions/Prompts/Sales-Prompts.html)

#### [TI](https://microsoftlearning.github.io/MS-4021-Copilot-Immersion-Experience/Instructions/Prompts/IT-Prompts.html)

#### [Asistente ejecutivo](https://microsoftlearning.github.io/MS-4021-Copilot-Immersion-Experience/Instructions/Prompts/EA-Prompts.html)

#### [Administrador de negocio](https://microsoftlearning.github.io/MS-4021-Copilot-Immersion-Experience/Instructions/Prompts/Business-Manager-Prompts.html)

#### [Marketing](https://microsoftlearning.github.io/MS-4021-Copilot-Immersion-Experience/Instructions/Prompts/Marketing-Prompts.html)

#### [Operaciones](https://microsoftlearning.github.io/MS-4021-Copilot-Immersion-Experience/Instructions/Prompts/Operations-Prompts.html)

#### [Legal](https://microsoftlearning.github.io/MS-4021-Copilot-Immersion-Experience/Instructions/Prompts/Legal-Prompts.html)

#### [Finanzas](https://microsoftlearning.github.io/MS-4021-Copilot-Immersion-Experience/Instructions/Prompts/Finance-Prompts.html)