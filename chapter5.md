# 5.1. Software Configuration Management.
## 5.1.1. Software Development Environment Configuration.

**Project Management:**
- WhatsApp: Es una aplicación de mensajería instantánea propiedad de Meta, en la cual coordinamos las tareas del equipo y facilitamos el intercambio de ideas y el apoyo continuo durante el desarrollo del proyecto.
- Google Meet: Es una herramienta de videoconferencias de Google, en la cual mantenemos una comunicación más verbal y directa, permitiendo planificar las tareas de manera colaborativa.
- Google Drive: Es un servicio de almacenamiento en la nube de Google, que utilizamos para compartir archivos de mayor tamaño e información relevante entre los integrantes del equipo.

**Requirements Management:**
- UXPressia: Utilizada para la elaboración de User Personas, User Journey Maps e Impact Maps, lo que nos permite entender mejor a nuestros usuarios y planificar funcionalidades centradas en ellos.
- Zoom: Herramienta empleada para la realización de entrevistas a posibles usuarios, facilitando la obtención de información directa y valiosa para la definición de requisitos.

**Product UX/UI Design:**
- Figma: Plataforma utilizada para el diseño de wireframes, wireflows, mockups y prototipos interactivos, asegurando una visión clara y colaborativa de la interfaz del producto.
Software Development:
- Vertabelo: Herramienta usada para el diseño del modelo de base de datos, permitiendo una estructura clara y visual de las entidades y sus relaciones.
- Google Chrome: Navegador empleado para realizar pruebas de visualización y funcionalidad de la landing page, garantizando su correcto comportamiento en entornos reales.
- Visual Studio Code: Editor de código utilizado para programar en lenguajes como JavaScript y Gherkin, y para integrar funcionalidades mediante herramientas como GitHub.

**Software Documentation:**
- Google Docs: Documento colaborativo para registrar de manera detallada los informes, decisiones y evolución del proyecto.
- Structurizr: Utilizado para el diseño de diagramas C4, lo cual nos permite representar visualmente la arquitectura del software a distintos niveles de abstracción.

## 5.1.2. Source Code Management.
En el proyecto, tenemos un repositorio de GitHub para la administrar y estructurar los avances del proyecto por medio de la creación de ramas. Para ello, implementamos el flujo de trabajo de Gitflow expuesta por Vincent Driessen, de tal forma que se puedan realizar las modificaciones entre todos los integrantes de manera segura entre versiones.

**Main branch:** Esta es la rama principal del proyecto, donde se mantiene el código en producción. Solo se actualiza cuando se ha completado y probado una nueva versión estable del sistema.

**Develop branch:** Es la rama de integración donde se fusionan las funcionalidades desarrolladas en las ramas feature antes de ser consideradas para producción. Todo el trabajo colaborativo se integra aquí para ser probado y revisado antes de pasar a la rama "main".

**Feature branches:** Estas ramas se crean a partir de la rama "develop" para trabajar en mejoras específicas, por ello estan divididas en diferentes secciones. Cada una de ellas se desarrolla en su propia rama con el fin de mantener el trabajo organizado y separado del resto del código. Una vez finalizada y probada, la rama se fusiona de nuevo en la rama "develop".

**Conventional commits:** Estos mensajes de confirmación se utilizan para mantener un historial de versiones claro, coherente y comprensible. Este formato establece una convención estructurada que facilita la lectura y el análisis de los cambios realizados en el repositorio. Cada mensaje se describe que tipo de cambios estamos realizando en su respectiva rama, y realizar un "pull request" para fusionar las ramas y establecer los cambios respectivos. Esta práctica no solo mejora la trazabilidad del desarrollo, sino que también permite automatizar procesos como la generación de registros de cambios y la comprensión del historial de versiones.
