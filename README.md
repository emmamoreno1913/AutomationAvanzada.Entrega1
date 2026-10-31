Checkpoint 1 – Agente IA Autónomo

Descripción del proyecto:
Este proyecto consiste en el desarrollo de un agente de Inteligencia Artificial utilizando n8n, Groq y Google Sheets, orientado a automatizar consultas comerciales de una empresa ficticia llamada TechSolutions.
El agente interpreta las consultas de los usuarios, consulta un catálogo de productos y genera respuestas precisas utilizando herramientas externas y memoria conversacional.

Objetivos:
Automatizar consultas comerciales.
Consultar precios, stock y características de productos.
Utilizar un modelo de lenguaje para interpretar las solicitudes.
Incorporar memoria para mantener el contexto de las conversaciones.
Implementar notificaciones por correo electrónico.
Aplicar instrucciones y restricciones para evitar respuestas incorrectas.

Tecnologías utilizadas:
n8n Cloud 2.41.3: plataforma de automatización.
Groq: motor de razonamiento mediante modelo de lenguaje.
Google Sheets: catálogo de productos y fuente de información.
Simple Memory: gestión del contexto conversacional.
Gmail: envío de notificaciones y observabilidad.

Arquitectura del workflow:
El flujo recibe una consulta mediante Chat Trigger y la procesa a través de un AI Agent.
El agente utiliza Groq para interpretar la solicitud y Google Sheets como herramienta para consultar información comercial. Simple Memory permite conservar el contexto de la conversación.
Finalmente, Gmail envía una notificación con los datos de la interacción.

Resultado: 
Todas las pruebas funcionales realizadas fueron satisfactorias.
