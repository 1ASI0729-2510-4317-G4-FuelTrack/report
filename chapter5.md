# 5.1. Software Configuration Management
## 5.1.1. Software Development Environment Configuration

**Project Management:**
- WhatsApp: Es una aplicación de mensajería instantánea propiedad de Meta, en la cual coordinamos las tareas del equipo y facilitamos el intercambio de ideas y el apoyo continuo durante el desarrollo del proyecto.
- Google Meet: Es una herramienta de videoconferencias de Google, en la cual mantenemos una comunicación más verbal y directa, permitiendo planificar las tareas de manera colaborativa.
- Google Drive: Es un servicio de almacenamiento en la nube de Google, que utilizamos para compartir archivos de mayor tamaño e información relevante entre los integrantes del equipo.
- Trello: Es una herramienta visual basada en la metodología Kanban que facilita la organización de tareas, sprints y entregables a través de tableros interactivos y tarjetas movibles. Es especialmente útil para mantener el ritmo del equipo y asegurar la visibilidad en cada etapa del proyecto.

**Requirements Management:**
- UXPressia: Utilizada para la elaboración de User Personas, User Journey Maps e Impact Maps, lo que nos permite entender mejor a nuestros usuarios y planificar funcionalidades centradas en ellos.
- Zoom: Herramienta empleada para la realización de entrevistas a posibles usuarios, facilitando la obtención de información directa y valiosa para la definición de requisitos.
- Pivotal Tracker: Plataforma de gestión ágil que permite registrar, priorizar y desarrollar historias de usuario dentro de un backlog dinámico. Su enfoque en la velocidad de desarrollo, facilita la planificación y predicción precisa de futuras entregas del proyecto.

**Product UX/UI Design:**
- Figma: Plataforma utilizada para el diseño de wireframes, wireflows, mockups y prototipos interactivos, asegurando una visión clara y colaborativa de la interfaz del producto.
Software Development:
- Vertabelo: Herramienta usada para el diseño del modelo de base de datos, permitiendo una estructura clara y visual de las entidades y sus relaciones.
- Google Chrome: Navegador empleado para realizar pruebas de visualización y funcionalidad de la landing page, garantizando su correcto comportamiento en entornos reales.
- Visual Studio Code: Editor de código utilizado para programar en lenguajes como JavaScript y Gherkin, y para integrar funcionalidades mediante herramientas como GitHub.

**Software Documentation:**
- Google Docs: Documento colaborativo para registrar de manera detallada los informes, decisiones y evolución del proyecto.
- Structurizr: Utilizado para el diseño de diagramas C4, lo cual nos permite representar visualmente la arquitectura del software a distintos niveles de abstracción.

## 5.1.2. Source Code Management
En el proyecto, tenemos un repositorio de GitHub para la administrar y estructurar los avances del proyecto por medio de la creación de ramas. Para ello, implementamos el flujo de trabajo de Gitflow expuesta por Vincent Driessen, de tal forma que se puedan realizar las modificaciones entre todos los integrantes de manera segura entre versiones.

**Main branch:** Esta es la rama principal del proyecto, donde se mantiene el código en producción. Solo se actualiza cuando se ha completado y probado una nueva versión estable del sistema.

**Develop branch:** Es la rama de integración donde se fusionan las funcionalidades desarrolladas en las ramas feature antes de ser consideradas para producción. Todo el trabajo colaborativo se integra aquí para ser probado y revisado antes de pasar a la rama "main".

**Feature branches:** Estas ramas se crean a partir de la rama "develop" para trabajar en mejoras específicas, por ello estan divididas en diferentes secciones. Cada una de ellas se desarrolla en su propia rama con el fin de mantener el trabajo organizado y separado del resto del código. Una vez finalizada y probada, la rama se fusiona de nuevo en la rama "develop".

**Conventional commits:** Estos mensajes de confirmación se utilizan para mantener un historial de versiones claro, coherente y comprensible. Este formato establece una convención estructurada que facilita la lectura y el análisis de los cambios realizados en el repositorio. Cada mensaje se describe que tipo de cambios estamos realizando en su respectiva rama, y realizar un "pull request" para fusionar las ramas y establecer los cambios respectivos. Esta práctica no solo mejora la trazabilidad del desarrollo, sino que también permite automatizar procesos como la generación de registros de cambios y la comprensión del historial de versiones.

## 5.1.3. Source Code Style Guide & Conventions
Nuestro equipo adoptó las siguientes convenciones y guías de estilo para garantizar un código fuente coherente, legible y mantenible en los diferentes lenguajes y tecnologías utilizados en nuestra solución. Estas prácticas permiten una colaboración eficiente entre desarrolladores, reducen la deuda técnica y facilitan la escalabilidad de la plataforma.

**HTML:**

Seguimos las convenciones descritas en la guía oficial HTML Style Guide and Coding Conventions para fomentar una estructura limpia, semántica y predecible:

- Usar nombres de elementos en minúsculas.
- Cerrar todos los elementos HTML, incluso los que son opcionales.
- Usar nombres de atributos en minúsculas.
- Incluir siempre los atributos requeridos en elementos clave, especialmente en imágenes (alt) y formularios (name, id, etc.).
- Evitar líneas de código largas para mejorar la legibilidad.
- Utilizar sintaxis simplificada y estándar para hojas de estilo (link) y scripts externos (script).

**CSS:**

Aplicamos las siguientes convenciones para lograr un estilo consistente, ordenado y fácil de mantener:

- Usar minúsculas y guiones para los nombres de clases y selectores.
- Escribir un espacio después de los dos puntos y cerrar cada declaración con punto y coma.
- Agrupar reglas CSS relacionadas y separarlas con una línea en blanco para mejorar la claridad visual.
- Utilizar nombres de clases descriptivos, que reflejen la función o apariencia del elemento.
- Organizar el CSS por bloques lógicos o módulos.

**JavaScript:**

Definimos las siguientes convenciones para asegurar un código robusto, eficiente y comprensible:

- Declarar las variables al inicio del ámbito correspondiente, evitando la redeclaración innecesaria.
- Preferir el uso de const y let en lugar de var para controlar mejor el ámbito y la mutabilidad de las variables.
- Incluir comentarios descriptivos para explicar la funcionalidad de componentes, servicios, validaciones y lógica compleja.
- Mantener las funciones pequeñas y con una única responsabilidad.
- Aplicar principios de programación funcional y reactiva, así como patrones de diseño adecuados.

## 5.1.4. Software Deployment Configuration
**Entorno de Desarrollo**

Tecnologías utilizadas:

- HTML5
- CSS3
- Angular

Gestor de paquetes:

- npm para Angular

**Estrategia de Deployment**

- GitHub Pages
- Repositorio principal en GitHub

Flujo Gitflow:

- main: rama principal de producción
- develop: rama de integración principal
- feature/*: desarrollo de nuevas funcionalidades sobre develop
- Pull Requests se realizan desde feature/* hacia develop

# 5.2. Landing Page, Services & Applications Implementation
## 5.2.1. Sprint 1
En este primer sprint se desarrolló el landing page.

### 5.2.1.1. Sprint Planning 1
<table>
    <tr align="center">
        <td><strong>Sprint #</strong></td>
        <td><strong>Sprint 1</strong></td>
    </tr>
    <tr>
        <td colspan="2" align="center"><strong>Sprint Planning Background</strong></td>
    </tr>
    <tr align="center">
        <td>Date</td>
        <td>10/04/2025</td>
    </tr>
    <tr align="center">
        <td>Time</td>
        <td>11:00 PM</td>
    </tr>
    <tr align="center">
        <td>Location</td>
        <td>Meet</td>
    </tr>
    <tr align="center">
        <td>Prepared by</td>
        <td>Manuel Sanchez</td>
    </tr>
    <tr align="center">
        <td>Attendess (to planning meeting)</td>
        <td>Manuel Angel Sanchez Arenas - U201817507<br>
        Adrián Emanuel Valerio Garcia - U202210334<br>
        Luciana Carolina Choquehuanca Nuñez - U202319431<br>
        César Augusto Navarro Correa - U202310129<br>
        Franz Jair La Torre Valle - U202012378</td>
    </tr>
    <tr align="center">
        <td>Sprint 0 Review Summary</td>
        <td>No hubo sprint previo</td>
    </tr>
    <tr align="center">
        <td>Sprint 0 Retrospective Summary</td>
        <td>No hubo sprint previo</td>
    </tr>
    <tr>
        <td colspan="2" align="center"><strong>Sprint Goal & User Stories</strong></td>
    </tr>
    <tr align="center">
        <td>Sprint 1 Goal</td>
        <td>Desarrollar una landing page funcional y visualmente clara que comunique efectivamente la propuesta de valor de FuelTrack a nuestros dos segmentos clave de usuarios: proveedores de combustible y solicitantes de combustible. La página debe incluir secciones estratégicas como:<br>
•	Home, con un call to action para captar proveedores interesados.<br>
•	Are you a fuel requester?, con un call to action dirigido a potenciales solicitantes.<br>
•	Secciones informativas como About Us y How it works?, para explicar el funcionamiento del sistema.<br>
•	Secciones de validación social como Main Suppliers y Our Clients, para generar confianza mostrando empresas reales que ya usan el servicio.<br>
•	Una sección de contacto directo (Contact Us) para atención inmediata.<br>
•	Soporte de idioma bilingüe (español e inglés) para mayor accesibilidad.
</td>
    </tr>
    <tr align="center">
        <td>Sprint 1 Velocity</td>
        <td>12</td>
    </tr>
    <tr align="center">
        <td>Sum of Story Point</td>
        <td>22</td>
    </tr>
</table>

### 5.2.1.2. Aspect Leaders and Collaborators
| Team Member | GitHub Username | Landing Page | Documentation |
|-------------|-----------------|--------------|---------------|
| Sanchez Arenas, Manuel Angel | manuels7a | C | C |
| Valerio Garcia, Adrián Emanuel | adrianvalerio | C | C |
| Choquehuanca Nuñez, Luciana Carolina | Lucianxaaa | C | L |
| Navarro Correa, César Augusto | csr555-ui | L | C |
| La Torre Valle, Franz Jair | FranzJairLTV | C | C |

### 5.2.1.2. Sprint Backlog 1
<table>
    <tr align="center">
        <td colspan="2"><strong>Sprint #</strong></td>
        <td colspan="6"><strong>Sprint 1</strong></td>
    </tr>
    <tr align="center">
        <td colspan="2"><strong>User Story</strong></td>
        <td colspan="6"><strong>Work-Item / Task</strong></td>
    </tr>
    <tr align="center">
        <td><strong>Id</strong></td>
        <td><strong>Title</strong></td>
        <td><strong>Id</strong></td>
        <td><strong>Title</strong></td>
        <td><strong>Description</strong></td>
        <td><strong>Estimation (Hours)</strong></td>
        <td><strong>Assigned to</strong></td>
        <td><strong>Status (To do / In process / To review / Done)</strong></td>
    </tr>
    <tr align="center">
        <td>US-01</td>
        <td>Ver sección Home</td>
        <td>W-01</td>
        <td>Sección Home</td>
        <td>Como visitante (proveedor), quiero ver una sección de inicio que resuma el valor de FuelTrack para comprender rápidamente el objetivo del sistema</td>
        <td>5 horas</td>
        <td>Frezzia</td>
        <td>Done</td>
    </tr>
    <tr align="center">
        <td>US-02</td>
        <td>Ver sección About Us</td>
        <td>W-02</td>
        <td>Sección About Us</td>
        <td>Como visitante de ambos segmentos, quiero conocer quiénes están detrás de FuelTrack para confiar en el sistema</td>
        <td>4 horas</td>
        <td>Franz</td>
        <td>Done</td>
    </tr>
    <tr align="center">
        <td>US-03</td>
        <td>Ver sección How it Works?</td>
        <td>W-03</td>
        <td>Sección How it works?</td>
        <td>Como visitante de ambos segmentos, quiero entender cómo funciona FuelTrack paso a paso para evaluar si se ajusta a mis necesidades</td>
        <td>5 horas</td>
        <td>César</td>
        <td>Done</td>
    </tr>
    <tr align="center">
        <td>US-41</td>
        <td>Ver sección Main Suppliers</td>
        <td>W-04</td>
        <td>Sección Main Suppliers</td>
        <td>Como visitante de ambos segmentos, quiero conocer los principales proveedores de combustible que trabajan con FuelTrack para confiar en la plataforma</td>
        <td>4 horas</td>
        <td>Luciana</td>
        <td>Done</td>
    </tr>
    <tr align="center">
        <td>US-42</td>
        <td>Ver sección Our Clients</td>
        <td>W-05</td>
        <td>Sección Our Clients</td>
        <td>Como visitante de ambos segmentos, quiero conocer a las empresas que utilizan FuelTrack para tener confianza en la plataforma y saber que otras empresas ya la están usando</td>
        <td>6 horas</td>
        <td>Frezzia</td>
        <td>Done</td>
    </tr>
    <tr align="center">
        <td>US-04</td>
        <td>Enviar mensaje de contacto</td>
        <td>W-06</td>
        <td>Contacto</td>
        <td>Como visitante de ambos segmentos, quiero enviar un mensaje desde Contact Us para solicitar más información</td>
        <td>5 horas</td>
        <td>Adrián</td>
        <td>In Process</td>
    </tr>
    <tr align="center">
        <td>US-43</td>
        <td>Ver sección Are You A Fuel Requester?</td>
        <td>W-07</td>
        <td>Are You A Fuel Requester?</td>
        <td>Como visitante (solicitante), quiero saber si cumplo con los requisitos de solicitante de combustible para poder iniciar un proceso de registro o solicitud</td>
        <td>6 horas</td>
        <td>Manuel</td>
        <td>Done</td>
    </tr>
    <tr align="center">
        <td>US-44</td>
        <td>Cambiar idioma</td>
        <td>W-08</td>
        <td>Idioma</td>
        <td>Como visitante de ambos segmentos, quiero poder cambiar entre inglés y español para entender la plataforma en mi idioma preferido</td>
        <td>8 horas</td>
        <td>César</td>
        <td>In Process</td>
    </tr>
</table>

### 5.2.1.3. Development Evidence for Sprint Review
Durante el Sprint 1, el equipo de desarrollo de FuelTrack avanzó en la construcción de la Landing Page, cumpliendo con las User Stories priorizadas. Se trabajó en la maquetación de las secciones principales, implementación de estilos CSS, diseño responsive para diferentes dispositivos y subida de los cambios al repositorio grupal. Los commits fueron realizados en ramas feature/ y luego integrados a la rama develop mediante Pull Requests.

### 5.2.1.5. Execution Evidence for Sprint Review
En el sprint 1 se diseñó el primer modelo de la landing page. Esta cuenta con diferentes secciones para acceso de los usuarios. Algunas evidencias son:
- **Home:** Presenta de manera rápida el propósito y valor de FuelTrack para captar la atención del visitante.

![Home](img/Home.jpeg)
- **About Us:** Explica quiénes somos y nuestra misión para generar confianza.

![About Us](img/AboutUs.jpeg)
- **How it works?:** Describe de forma sencilla y visual el funcionamiento de FuelTrack paso a paso.

![How it works?](img/HowItWorks.jpeg)
- **Our Clients:** Muestra algunas de las empresas o usuarios que confían en FuelTrack como referencia de credibilidad.

![Our Clients](img/OurClients.jpeg)
- **Join:** Invita a nuevos usuarios o empresas a registrarse o solicitar información para unirse a FuelTrack.

![Join](img/Join.jpeg)
- **Contact Us:** Ofrece un formulario y datos de contacto directo para resolver dudas o solicitar soporte.

![Contact Us](img/ContactUs.jpeg)
- **Footer:** Contiene información adicional como redes sociales y enlaces de interés.

![Footer](img/Footer.jpeg)

### 5.2.1.6. Services Documentation Evidence for Sprint Review
Durante el Sprint 1, el equipo se enfocó en el desarrollo del Landing Page de FuelTrack, por lo cual no se implementaron ni documentaron endpoints relacionados a Web Services. Los trabajos de desarrollo backend, integración de API y documentación con OpenAPI están planificados para Sprints posteriores.

### 5.2.1.7. Software Deployment Evidence for Sprint Review
Durante este Sprint, nos enfocamos en asegurar un proceso de Deployment eficiente y efectivo, tanto para nuestra aplicación principal como para la Landing Page asociada y los Web Services que soportan la infraestructura de la aplicación. Este enfoque no solo buscó mejorar la experiencia de usuario final, sino también optimizar nuestro flujo de trabajo de desarrollo y despliegue continuo.

**Link:** 

### 5.2.1.8. Team Collaboration Insights during Sprint
Dividimos las tareas según las secciones acordadas durante las reuniones de planificación, ello nos permitió trabajar de manera eficiente y centrarnos en áreas específicas para optimizar el tiempo y los recursos. Dicha participación de los miembros del equipo se ve reflejado en los commits realizados en el repositorio de trabajo.

## 5.2.2. Sprint 2
En este segundo sprint se desarrollo el frontend para nuestra pagina web

### 5.2.2.1. Sprint Planning 2
En esta siguiente etapa de proyecto, nuestra principal objetivo sera desarrollar el frontend de nuestra pagina web mediante WebStorm como nuestro entorno de desarrollo

Repositorio Github: https://github.com/1ASI0729-2510-4317-G4-FuelTrack/FuelTrack-front-end

<table>
    <tr align="center">
        <td><strong>Sprint #</strong></td>
        <td><strong>Sprint 2</strong></td>
    </tr>
    <tr>
        <td colspan="2" align="center"><strong>Sprint Planning Background</strong></td>
    </tr>
    <tr align="center">
        <td>Date</td>
        <td>8/05/2025</td>
    </tr>
    <tr align="center">
        <td>Time</td>
        <td>8:00 PM</td>
    </tr>
    <tr align="center">
        <td>Location</td>
        <td>Discord</td>
    </tr>
    <tr align="center">
        <td>Prepared by</td>
        <td>Adrian Emanuel Valerio Garcia</td>
    </tr>
    <tr align="center">
        <td>Attendess (to planning meeting)</td>
        <td>Manuel Angel Sanchez Arenas - U201817507<br>
        Adrián Emanuel Valerio Garcia - U202210334<br>
        Luciana Carolina Choquehuanca Nuñez - U202319431<br>
        César Augusto Navarro Correa - U202310129<br>
        Franz Jair La Torre Valle - U202012378<br>
        Frezzia Eldaa Isabel Espinoza Paredes</td>
    </tr>
    <tr align="center">
        <td>Sprint 1 Review Summary</td>
        <td>En este primer sprint se desarrolló el landing page y el informe</td>
    </tr>
    <tr align="center">
        <td>Sprint 1 Retrospective Summary</td>
        <td>En este primer sprint se desarrolló el landing page y el informe</td>
    </tr>
    <tr>
        <td colspan="2" align="center"><strong>Sprint Goal & User Stories</strong></td>
    </tr>
    <tr align="center">
        <td>Sprint 2 Goal</td>
        <td>Desarrollar el FrontEnd para agregarlo al repositorio</td>
    </tr>
    <tr align="center">
        <td>Sprint 2 Velocity</td>
        <td>16</td>
    </tr>
    <tr align="center">
        <td>Sum of Story Point</td>
        <td>76</td>
    </tr>
</table>

### 5.2.2.2. Aspect Leaders and Collaborators

| Team Member                                  | GitHub Username   | Landing Page | Documentation | Frontend | Correcciones TB1 |
|---------------------------------------------|--------------------|--------------|----------------|----------|--------------|
| Sanchez Arenas, Manuel Angel                | manuels7a          | C            | C              | C        | L            |
| Valerio Garcia, Adrián Emanuel              | adrianvalerio      | C            | C              | L        | C            |
| Choquehuanca Nuñez, Luciana Carolina        | Lucianxaaa         | C            | L              | C        | L            |
| Navarro Correa, César Augusto               | csr555-ui          | L            | C              | C        | C            |
| La Torre Valle, Franz Jair                  | FranzJairLTV       | C            | C              | L        | C            |
| Frezzia Eldaa Isabel Espinoza Paredes       | fflushh            | C            | C              | C        | C            |

### 5.2.2.3. Sprint Backlog 2

<table>
    <tr align="center">
        <td colspan="2"><strong>Sprint #</strong></td>
        <td colspan="6"><strong>Sprint 2</strong></td>
    </tr>
    <tr align="center">
        <td colspan="2"><strong>User Story</strong></td>
        <td colspan="6"><strong>Work-Item / Task</strong></td>
    </tr>
    <tr align="center">
        <td><strong>Id</strong></td>
        <td><strong>Title</strong></td>
        <td><strong>Id</strong></td>
        <td><strong>Title</strong></td>
        <td><strong>Description</strong></td>
        <td><strong>Estimation (Hours)</strong></td>
        <td><strong>Assigned to</strong></td>
        <td><strong>Status (To do / In process / To review / Done)</strong></td>
    </tr>
    <tr align="center">
        <td>US-04</td>
        <td>Enviar mensaje de contacto</td>
        <td>W-09</td>
        <td>Implementar formulario de contacto</td>
        <td>Como visitante de ambos segmentos, quiero enviar un mensaje desde Contact Us para solicitar más información.</td>
        <td>5 horas</td>
        <td>Frezzia</td>
        <td>Done</td>
    </tr>
   <tr align="center">
        <td>US-05</td>
        <td>Registrar nuevo pedido</td>
        <td>W-10</td>
        <td>Crear formulario de registro de pedido</td>
        <td>Como solicitante, quiero registrar un pedido con tipo y cantidad de combustible para que el proveedor lo procese.</td>
        <td>6 horas</td>
        <td>Freezia</td>
        <td>Done</td>
    </tr>
    <tr align="center">
        <td>US-06</td>
        <td>Consultar estado del pedido</td>
        <td>W-11</td>
        <td>Mostrar estado de pedidos del usuario</td>
        <td>Como solicitante, quiero ver el estado de mis pedidos para saber si están aprobados, en tránsito o entregados.</td>
        <td>4 horas</td>
        <td>Freezia</td>
        <td>Done</td>
    </tr>
    <tr align="center">
        <td>US-07</td>
        <td>Confirmar recepción de pedido</td>
        <td>W-12</td>
        <td>Confirmar recepción desde interfaz</td>
        <td>Como solicitante, quiero confirmar que recibí el pedido para que el proveedor lo cierre.</td>
        <td>5 horas</td>
        <td>Freezia</td>
        <td>Done</td>
    </tr>
    <tr align="center">
        <td>US-08</td>
        <td>Registrar información de pago</td>
        <td>W-13</td>
        <td>Formulario de ingreso de pagos</td>
        <td>Como solicitante, quiero ingresar la información de los pagos correspondientes para validar el pedido ante el proveedor.</td>
        <td>4 horas</td>
        <td>Freezia</td>
        <td>Done</td>
    </tr>
    <tr align="center">
        <td>US-09</td>
        <td>Ver historial de pedidos</td>
        <td>W-14</td>
        <td>Mostrar el listado de pedidos y su información</td>
        <td>Como solicitante, quiero ver mis pedidos anteriores para tener control sobre mi consumo.</td>
        <td>4 horas</td>
        <td>Adrian</td>
        <td>Done</td>
    </tr>
    <tr align="center">
        <td>US-10</td>
        <td>Ver pedidos pendientes</td>
        <td>W-15</td>
        <td>Mostrar pedidos pendientes al proveedor</td>
        <td>Como proveedor, quiero ver todos los pedidos pendientes para analizarlos y tomar acción.</td>
        <td>4 horas</td>
        <td>Manuel</td>
        <td>Done</td>
    </tr>
    <tr align="center">
        <td>US-11</td>
        <td>Aprobar pedido</td>
        <td>W-16</td>
        <td>Aprobar pedidos desde panel proveedor</td>
        <td>Como proveedor, quiero aprobar pedidos según los depósitos hechos a mis cuentas bancarias.</td>
        <td>4 horas</td>
        <td>Freezia</td>
        <td>In Process</td>
    </tr>
    <tr align="center">
        <td>US-15</td>
        <td>Iniciar sesión</td>
        <td>W-17</td>
        <td>Implementar el ingreso de usuarios</td>
        <td>Como usuario registrado, quiero iniciar sesión con correo y contraseña para acceder a mi cuenta.</td>
        <td>5 horas</td>
        <td>César</td>
        <td>Done</td>
    </tr>
    <tr align="center">
        <td>US-16</td>
        <td>Recuperar contraseña</td>
        <td>W-18</td>
        <td>Formulario de recuperación de clave por correo</td>
        <td>Como usuario registrado, quiero recuperar mi contraseña para volver a acceder si la olvidé.</td>
        <td>5 horas</td>
        <td>Luciana</td>
        <td>In Process</td>
    </tr>
    <tr align="center">
        <td>US-17</td>
        <td>Cerrar sesión</td>
        <td>W-19</td>
        <td>Funcionalidad de cierre de sesión</td>
        <td>Como usuario registrado, quiero poder cerrar sesión para mantener segura mi cuenta.</td>
        <td>5 horas</td>
        <td>Franz</td>
        <td>In Process</td>
    </tr>
    <tr align="center">
        <td>US-18</td>
        <td>Ver resumen de pedidos (Solicitante)</td>
        <td>W-20</td>
        <td>Mostrar resumen de pedidos enviados del solicitante</td>
        <td>Como solicitante, quiero ver un resumen de mis pedidos para identificar cuántos están en proceso o completados.</td>
        <td>5 horas</td>
        <td>Freezia</td>
        <td>Done</td>
    </tr>
    <tr align="center">
        <td>US-19</td>
        <td>Ver resumen de pedidos (Proveedor)</td>
        <td>W-21</td>
        <td>Mostrar resumen de pedidos gestionados del proveedor</td>
        <td>Como proveedor, quiero ver un resumen de pedidos gestionados y pendientes para organizar a los clientes.</td>
        <td>5 horas</td>
        <td>Freezia</td>
        <td>Done</td>
    </tr>
    <tr align="center">
        <td>US-38</td>
        <td>Ver gráfico de consumo (Solicitante)</td>
        <td>W-22</td>
        <td>Generar gráfico de consumo mensual</td>
        <td>Como solicitante, quiero ver un gráfico de mi consumo mensual para tener control sobre el uso del combustible.</td>
        <td>5 horas</td>
        <td>Manuel</td>
        <td>Done</td>
    </tr>
    <tr align="center">
        <td>US-39</td>
        <td>Ver gráfico de ventas (Proveedor)</td>
        <td>W-23</td>
        <td>Generar gráfico de ventas mensuales</td>
        <td>Como proveedor, quiero ver un gráfico de ventas por mes para monitorear el rendimiento del negocio.</td>
        <td>5 horas</td>
        <td>Luciana</td>
        <td>Done</td>
    </tr>
</table>

### 5.2.2.4. Development Evidence for Sprint Review
Durante el Sprint 2, el equipo de desarrollo frontend de FuelTrack avanzó en la implementación de interfaces clave de la plataforma, cumpliendo con las User Stories priorizadas. Se trabajó en el diseño y maquetación de la página de login, así como en las vistas correspondientes a la creación de órdenes, desarrolladas inicialmente como pantallas estáticas para definir la estructura y la navegación del sistema.

Se aplicaron estilos CSS personalizados y componentes de Angular Material para asegurar una apariencia moderna, coherente y responsive en distintos dispositivos. Además, se estableció una estructura de carpetas modular dentro del proyecto Angular para mantener una organización clara del código.

### 5.2.2.5. Execution Evidence for Sprint Review
En el sprint 2 se diseñó el primer modelo del frontEnd con seccion para la navegacion tanto de cliente como de proveedor. Algunas evidencias son:

- **Home:** Presenta de manera rápida el propósito y valor de FuelTrack para captar la atención del visitante.

![Home](img/homefront.png)
- **Inicio de sesión:** Se muestra la pagina para los usuarios que ya tienen una cuenta, ya sean esto clientes o proveedores

![logiin](img/login1.png)
- **Registro:** Una interfaz donde le da la opcion al usuario de registrarse en nuestra pagina como cliente o proveedores

![How it works?](img/register.png)
- **Pagina de Analisis:** Muestra algunas de las empresas o usuarios que confían en FuelTrack como referencia de credibilidad.

![analyticsfront](img/analyticsfront.png)
- **Pagina de gestión de ordenes:** Se muestran las ordenes con sus diferentes estados y la informacion necesaria de cada orden

![orderfront](img/ordersfront.png)
- **Creación de orden:** Ofrece un formulario para llenar con los datos necesarios para que el proveedor genere la orden de envio.

![CreateOrder](img/CreateOrder.png)


### 5.2.2.6. Services Documentation Evidence for Sprint Review
Durante el Sprint 2, el equipo se enfocó en el desarrollo del frontend inicial de la plataforma FuelTrack, particularmente en la construcción de la Landing Page. En esta etapa se priorizó el diseño visual, la experiencia de usuario y la implementación de la estructura base de la interfaz.

### 5.2.2.7. Software Deployment Evidence for Sprint Review
Durante este Sprint, nos enfocamos en consolidar un proceso de desarrollo y deployment eficiente para el frontend de nuestra plataforma, construido con Angular. Implementamos una estructura modular que facilita la escalabilidad y el mantenimiento del código, apoyándonos en Angular Material para garantizar una interfaz moderna, responsiva y alineada con principios de diseño consistentes.

**Link:**[https://fueltrack-f9064.web.app/](https://fueltrack-f9064.web.app/)

### 5.2.2.8. Team Collaboration Insights during Sprint

Durante el Sprint 2, el equipo demostró una mejora en la colaboración y distribución de tareas. Las reuniones frecuentes ayudaron a coordinar avances, resolver bloqueos técnicos y asegurar que cada miembro comprendiera sus responsabilidades dentro del desarrollo frontend, y los canales de comunicación fueron efectivos para mantener una alineación constante entre los integrantes.

Además, se evidenció una actitud proactiva por parte del equipo al brindar apoyo mutuo entre los miembros, especialmente en la integración de Angular Material y el manejo de rutas dentro de la aplicación.

## Conclusiones 

- El proyecto FuelTrack planteó una solución clara y concreta para optimizar la gestión de pedidos de combustible, basada en una comprensión real del mercado y de las necesidades de los usuarios.

- Se validó la propuesta de valor a través de métodos ágiles como Lean UX, entrevistas y análisis de competencia, logrando definir un producto que resuelve problemas reales de eficiencia y comunicación.

- Se diseñó una experiencia de usuario consistente y accesible, destacando especialmente la *Landing Page*, que comunica de forma clara la oferta del servicio, apoya la conversión mediante call to actions estratégicos y genera confianza a través de testimonios y prueba social.

- El diseño de la plataforma web combinó buenas prácticas de arquitectura de información, navegación intuitiva y guías de estilo que garantizan una imagen profesional y coherente en toda la experiencia digital.

- A nivel técnico, se construyó una base sólida de arquitectura de software y base de datos, asegurando escalabilidad, mantenibilidad y alineación con los objetivos de negocio.

- El desarrollo del producto se organizó mediante una planificación iterativa, permitiendo construir, validar y mejorar de manera progresiva, asegurando que el resultado final responda tanto a las expectativas de los usuarios como a las metas de FuelTrack.

## Bibliografia

Interaction Design Foundation. (s.f.). *A simple introduction to Lean UX*. Recuperado de [https://www.interaction-design.org/literature/article/a-simple-introduction-to-lean-ux](https://www.interaction-design.org/literature/article/a-simple-introduction-to-lean-ux)

Baymard Institute. (s.f.). *The best practices and key principles of UX design*. Recuperado de [https://baymard.com/learn/ux-design-principles](https://baymard.com/learn/ux-design-principles)

Laubheimer, P. (2022, abril 10). *Information architecture: Study guide*. Nielsen Norman Group. Recuperado de [https://www.nngroup.com/articles/ia-study-guide/](https://www.nngroup.com/articles/ia-study-guide/)

UXPin. (2024, agosto). *Design consistency guide: UI and UX best practices*. Recuperado de [https://www.uxpin.com/studio/blog/guide-design-consistency-best-practices-ui-ux-designers/](https://www.uxpin.com/studio/blog/guide-design-consistency-best-practices-ui-ux-designers/)

CareerFoundry. (2023, enero 5). *A beginner’s guide to information architecture in UX*. Recuperado de [https://careerfoundry.com/en/blog/ux-design/a-beginners-guide-to-information-architecture/](https://careerfoundry.com/en/blog/ux-design/a-beginners-guide-to-information-architecture/)

Contentsquare. (2024, octubre). *What is Lean UX? The 3 key phases of Lean UX design*. Recuperado de [https://contentsquare.com/guides/ux/lean/](https://contentsquare.com/guides/ux/lean/)

UX Design Institute. (2022, noviembre 15). *What is Lean UX and why does it matter? A complete guide*. Recuperado de [https://www.uxdesigninstitute.com/blog/what-is-lean-ux/](https://www.uxdesigninstitute.com/blog/what-is-lean-ux/)

Windmill Digital. (2023, septiembre 10). *10 UX best practices for optimal user experience in 2024*. Recuperado de [https://windmill.digital/ten-ux-best-practices-for-optimal-user-experience-in-2024/](https://windmill.digital/ten-ux-best-practices-for-optimal-user-experience-in-2024/)

Smashing Magazine. (2020, julio 21). *Information and information architecture: The big picture*. Recuperado de [https://www.smashingmagazine.com/2020/07/information-architecture-big-picture/](https://www.smashingmagazine.com/2020/07/information-architecture-big-picture/)

UXAX. (2023, junio 18). *The Lean UX process: Streamlining user-centered design*. Recuperado de [https://www.uxax.org/post/the-lean-ux-process-streamlining-user-centered-design](https://www.uxax.org/post/the-lean-ux-process-streamlining-user-centered-design)

## Anexos 

- **Despliegue de la Landing Page:** [https://fueltrack-f9064.web.app/ ](https://fueltrack-f9064.web.app/)

- **Figma - User Flow Diagrams, Wireframes y Mockups:**  
[https://www.figma.com/design/Ikz9yUtR1XthBJ1ViO6gVc/LP-and-CTA?node-id=0-1&t=WJtigb6RJ2HtjPPw-1node-id=401-8424&t=kuv2vsPlXaFzVYvk-0](https://www.figma.com/design/Ikz9yUtR1XthBJ1ViO6gVc/LP-and-CTA?node-id=0-1&t=WJtigb6RJ2HtjPPw-1node-id=401-8424&t=kuv2vsPlXaFzVYvk-0)

- **Exposición del Proyecto (TB1):**  
