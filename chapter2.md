# Capítulo II: Requirements Elicitation & Analysis 
## 2.1. Competidores.

PetroApp es una plataforma digital que facilita la compra y venta de combustible, principalmente orientada a consumidores finales y estaciones de servicio. Permite ubicar estaciones cercanas, gestionar pagos electrónicos y controlar el consumo desde una app. Esta enfocada principalmente en el uso personal, pero también ofrece soluciones para empresas, con funcionalidades que permiten cierta trazabilidad y control, aunque con menos enfoque en el flujo completo del pedido corporativo.

FuelCloud es una solución tecnológica centrada en el control del despacho de combustible mediante una combinación de hardware y software. Este ofrece monitoreo en tiempo real, control de acceso al combustible, reportes detallados de consumo y ubicación, lo que la hace ideal para empresas con tanques propios. Además, se enfoca más en el control físico del combustible que en la gestión administrativa o logística del pedido entre proveedor y cliente.

Wialon es una plataforma global de gestión de flotas que incluye funcionalidades para el control de combustible, seguimiento de vehículos por GPS, y análisis de consumo. Ofrece herramientas de visualización en tiempo real, alertas automatizadas y reportes avanzados. Si bien no gestiona directamente el flujo de pedidos entre proveedores y solicitantes, es altamente utilizada por empresas distribuidoras y logísticas que transportan combustible, lo que la convierte en un competidor indirecto pero funcionalmente cercano a FuelTrack.

### 2.1.1. Análisis competitivo.

| Competitive Analysis Landscape | 
--------------------------------------------|
| **¿Por qué llevar a cabo este análisis?** |
|Este análisis se está llevando a cabo porque queremos conocer las ventajas y desventajas de nuestra aplicación frente a la competencia, y cómo nos diferenciamos de ellas.

| **Categoría** | ![FuelTrack](img/logo-fueltrack.jpg)**FuelTrack** | ![Zavgar Online](img/logo-zavgar.jpg)**Zavgar** | ![FuelCloud](img/logo-fuelcloud.jpg) **FuelCloud** | ![Wialon](img/logo-wialon.jpg)**Wialon** |
| ------------- |----------------- |------------------|------------------|------------------------|
| **Overview** | Plataforma web que digitaliza y estructura el proceso completo de pedido de combustible entre empresas y proveedores. | SaaS para la gestión de consumo de combustible de flotas, con enfoque en eficiencia, monitoreo y costos. | Solución con hardware/software para el control físico del despacho de combustible.| Plataforma de gestión de flotas con control de combustible, GPS y reportes operativos. |
| **Ventaja competitiva** | Especialización en el flujo completo de pedido, despacho y análisis; integración de pagos y logística; UI intuitiva. | No requiere hardware; ofrece métricas, control de gastos y reportes sobre consumo. | Control físico preciso del combustible, monitoreo en tiempo real. | Seguimiento en tiempo real, visualización de rutas, integración con sensores de combustible. |
| **¿Qué valor ofrece al cliente?** | Trazabilidad total, eficiencia operativa, reportes de consumo y validación segura de pedidos. | Optimización de costos y control sobre el uso de combustible en flotas. | Seguridad y precisión operativa en el control de combustible. | Trazabilidad de flotas, alertas automáticas, análisis de rutas y consumo de combustible. |
| **Mercado objetivo** | Empresas que solicitan combustible a proveedores. | Empresas con flotas vehiculares que desean monitorear y reducir el consumo de combustible. | Empresas con tanques de combustible propios. | Empresas logísticas, distribuidoras y de transporte de combustible. |
| **Estrategias de marketing**| Alianzas con proveedores, demostraciones de ahorro, marketing de contenido enfocado en eficiencia. | Enfoque digital, contenido técnico, integración con proveedores de tarjetas de combustible. | Ferias industriales, distribuidores, venta consultiva entre empresas. | Alianzas con distribuidores de GPS, marketing técnico, ferias de transporte. |
| **Productos & Servicios** | Plataforma para gestión completa de pedidos, seguimiento, reportes, validación y alertas. | Plataforma web con módulo de abastecimiento, reportes de consumo, integración GPS y tarjetas. | Hardware IoT y software para gestión, y control de combustible. | Plataforma SaaS + app móvil con monitoreo, alertas, mapas y módulos personalizables. |
| **Precios & Costos** | Modelo SaaS con suscripción escalable según volumen y servicios. | SaaS con modelos por flota activa o vehículos monitoreados. | Venta e instalación de hardware + licencias de software. | Modelo SaaS modular, basado en vehículos activos y funcionalidades activadas. |
| **Canales de distribución** | Web app responsive, potencial app móvil futura. | Web app, marketing digital y comunidad de flotas. | Plataforma web + hardware instalado en sitio. | Red de partners global, distribuidores locales e integradores de sistemas GPS. |
| **Fortalezas** | Enfoque especializado, experiencia de usuario optimizada, integraciones clave, análisis avanzado de consumo. | Implementación ágil, sin hardware, fácil adopción en empresas medianas. | Control físico riguroso, solución probada en industrias exigentes.| Plataforma robusta, cobertura internacional, integración con más de 2,400 dispositivos GPS. |
| **Debilidades** | Nueva en el mercado, menor reconocimiento de marca, necesita consolidar confianza. | No gestiona el flujo completo del pedido, enfoque parcial en flotas. | Alto costo, dependencia de hardware, menor adaptabilidad en mercados emergentes. | No gestiona pedidos entre proveedor y solicitante, requiere configuración técnica inicial. |
| **Oportunidades** | Alta informalidad en el sector, digitalización creciente en logística, necesidad de trazabilidad y control. | Mayor conciencia en eficiencia de flotas y digitalización de costos operativos. | Nuevos mercados industriales con enfoque en seguridad y control. | Creciente necesidad de control logístico y monitoreo de distribución en países en desarrollo. |
| **Amenazas**  | Aparición de soluciones similares, resistencia al cambio en empresas tradicionales, competencia ERP. | SaaS especializados con mayor cobertura funcional (ERP, proveedores, logística). | SaaS ágiles y sin hardware físico, que ofrecen soluciones más accesibles. | SaaS más específicos y ligeros, enfocados exclusivamente en la trazabilidad de entregas. |

### 2.1.2. Estrategias y tácticas frente a competidores.

#### a. Diferenciación a través de especialización
Una de las principales estrategias de **FuelTrack** es la **especialización en el flujo completo de pedido de combustible**. A diferencia de soluciones como **Zavgar**, que están orientadas principalmente al control y análisis del consumo de combustible en flotas, nuestra plataforma se enfoca en las **interacciones B2B** entre empresas solicitantes y proveedores. Esto nos permite ofrecer un **control dedicado del pedido**, **gestión de la logística**, y **reportes detallados de consumo y entregas**, lo cual no está presente en la mayoría de las plataformas competidoras.

- **Táctica**: Desarrollar funcionalidades para la **validación automática de pagos**, **gestión de stock en tiempo real** y la **optimización del transporte** logrando la automatización de procesos que solo eran logrados de forma manual. Esto crea una ventaja frente a competidores como **FuelCloud**, que se centran más en el control físico del combustible y menos en la administración a nivel operativo.

#### b. Innovación en la interfaz de usuario y experiencia

El sistema de **FuelTrack** está diseñado para ofrecer una **experiencia de usuario optimizada**, algo que **Wialon**, **FuelCloud** y la propia **OSINERGMIN** no abordan en sus plataformas. Al ser una solución especializada y dirigida a una tarea específica, podemos dedicar más recursos en crear una interfaz intuitiva y procesos bien definidos brindando comodidad y seguridad a nuestros usuarios.

- **Táctica**: Diseñar una **interfaz intuitiva y consistente** que permita a los usuarios acceder a reportes de consumo, validar pedidos y coordinar logística con facilidad. Además, ofrecer **soporte y formación continua** para asegurar que los usuarios aprovechen al máximo todas las funcionalidades del sistema.

#### c. Flexibilidad en precios y modelo SaaS escalable
El modelo de precios de **FuelTrack** ofrece **planes escalables basados en suscripción**, lo que hace que sea más accesible para medianas y grandes empresas. Esto es más competitivo frente a **Wialon**, que puede no ser una opción viable para empresas que solo requieren una solución de pedidos de combustible. También es más asequible que **FuelCloud**, que requiere una inversión considerable en hardware, instalación y mantenimiento.

- **Táctica**: Ofrecer un modelo de suscripción flexible y **precios competitivos**, con **múltiples niveles de suscripción** adaptados a las necesidades de diferentes empresas. Esto permitirá que empresas de menor tamaño puedan acceder a la plataforma sin comprometer su presupuesto, a la vez que se asegura el crecimiento a largo plazo a medida que la empresa crece.

#### d. Aprovechamiento de la digitalización en la logística
El sector de la logística está experimentando una transformación digital acelerada. **FuelTrack** se aprovechará de esta tendencia buscando la integración de la plataforma con otras soluciones logísticas (como los sistemas de gestión de vehículos o flotas). De esta forma podemos ofrecer una solución más completa y eficiente.

- **Táctica**: Colaborar con empresas de **gestión de flotas** para optimizar el proceso de asignación de vehículos, cisternas y choferes. También se considerará la posibilidad de integrar **sensores IoT** en los camiones de reparto para un control más preciso sobre el combustible transportado y la entrega.

#### e. Expansión hacia mercados internacionales
Si bien **FuelTrack** está inicialmente orientada a empresas locales, el modelo de negocio y la flexibilidad de la plataforma la hacen ideal para expandirse a **mercados internacionales**. Competidores como **Wialon** ya tienen presencia en mercados globales, pero su enfoque en empresas grandes y sus altos costos de implementación pueden ser una barrera para empresas de menor tamaño, limitando su alcance.

- **Táctica**: Iniciar la expansión en mercados emergentes donde la digitalización en la logística es una necesidad creciente. Esto incluirá la **localización de la plataforma** (idioma, moneda, regulaciones locales) para facilitar la adaptabilidad de los nuevos mercados.

## 2.2. Entrevistas.
### 2.2.1. Diseño de entrevistas.

Para comprender mejor a nuestros segmentos objetivo, se han definido dos entrevistas diferenciadas según el segmento objetivo: 
- Proveedores de combustible
- Empresas con contratos de suministro (clientes corporativos)

---
#### A. Proveedores de Combustible

**Preguntas:**

1. ¿Cómo gestionan actualmente los pedidos de empresas clientes?
2. ¿Usan algún sistema digital para registrar pedidos o es manual?
3. ¿Qué pasos se siguen desde que un cliente hace un pedido hasta que se entregue?
4. ¿Cómo controlan que lo despachado coincida con lo solicitado?
5. ¿Qué tipo de reportes requieren generar (volúmenes, facturación, entregas, etc.)?
6. ¿Tienen un sistema para validar el stock antes de preparar el despacho de un pedido?
7. ¿Cómo hacen el seguimiento de los pedidos? ¿Informan al cliente en tiempo real?
8. ¿Qué problemas suelen ocurrir en el proceso de atención de pedidos empresariales?
9. ¿Cómo se realiza la conciliación de pagos con los clientes?
10. ¿Estarían dispuestos a integrar su sistema actual con una plataforma SaaS que unifique y centralice estos procesos?

---

#### B. Empresas Solicitantes

**Preguntas:**

1. ¿Cómo solicitan actualmente combustible a su proveedor?
2. ¿Utilizan un sistema propio o envían pedidos por correo, WhatsApp, etc.?
3. ¿Cómo verifican que lo entregado coincida con lo solicitado?
4. ¿Tienen problemas con entregas incompletas o fuera de tiempo?
5. ¿Con qué frecuencia necesitan reportes de consumo, entregas o pagos?
6. ¿Qué tan importante es para ustedes tener trazabilidad de cada entrega?
7. ¿Quiénes son los responsables de validar pedidos y autorizar pagos?
8. ¿Cómo gestionan las reprogramaciones o cancelaciones de pedidos?
9. ¿Qué herramientas utilizan para monitorear el consumo mensual?
10. ¿Qué mejoras desearían ver en el proceso actual?

---

### 2.2.2. Registro de entrevistas.

#### Entrevista 1 – Segmento: Empresa Solicitante
![entrevista_segmento1](img/entrevista1_segmento1.png) 
- Nombres: Nombre inventado
- Apellidos: Apellido inventado
- Edad: … años
- Distrito: Lima
- URL de Entrevista: 
- Duración:
- Resumen:<br>
    Martín explicó que actualmente los pedidos de combustible se realizan principalmente por WhatsApp o llamadas, recurriendo al correo solo en situaciones excepcionales o programadas. La empresa no cuenta con un sistema formal para esto; han intentado usar una hoja de Excel compartida, pero no siempre está actualizada, generando inconsistencias.<br>
    La validación de entregas se realiza de forma manual. El encargado de patio compara el volumen entregado con lo solicitado usando una guía de despacho, aunque señaló que en zonas alejadas muchas veces no coinciden los valores exactos.<br>
    Uno de los principales problemas mencionados es la frecuencia de entregas tardías o incompletas, especialmente en regiones remotas como la sierra o selva, lo que repercute directamente en la operación diaria.<br>
    Sobre reportes, el área operativa requiere información semanal y la gerencia mensualmente. Todo esto se realiza en Excel, consolidando reportes enviados por los jefes de zona: un proceso lento y propenso a errores. Para reprogramaciones, las coordinaciones se hacen por teléfono y se pierde el registro de esos cambios.<br>
    Cuando se le consultó por mejoras, Martín fue claro: desean una plataforma que les permita hacer el pedido, hacerle seguimiento, confirmar la entrega, generar reportes y validar el consumo —todo en un solo lugar. También expresó que le gustaría tener visibilidad en tiempo real del estado del pedido.

---

#### Entrevistado N°2
![entrevista_segmento1](img/entrevista2_segmento1.png) 
- Nombres: Nombre inventado
- Apellidos: Apellido inventado
- Edad: … años
- Distrito: Lima
- URL de Entrevista: 
- Duración:
- Resumen:<br>
    

---

#### Entrevistado N°3
![entrevista_segmento1](img/entrevista3_segmento1.png) 
- Nombres: Nombre inventado
- Apellidos: Apellido inventado
- Edad: … años
- Distrito: Lima  
- URL de Entrevista: 
- Duración:
- Resumen:<br>
    

---

#### Entrevistado N°4
![entrevista_segmento1](img/entrevista4_segmento2.png) 
- Nombres: Nombre inventado
- Apellidos: Apellido inventado
- Edad: … años
- Distrito: Lima
- URL de Entrevista: 
- Duración:
- Resumen:<br>
    _Nombre inventado_ indica que los pedidos de empresas clientes se gestionan mediante llamadas, WhatsApp y correos electrónicos.<br>No utilizan ningún sistema digital centralizado; todo se registra manualmente en hojas Excel. Desde que reciben el pedido, se valida la disponibilidad en almacén, se programa la entrega y se despacha.<br>
    SEl control de lo entregado se hace comparando guías físicas, y los reportes de volúmenes y entregas se elaboran a fin de mes de forma manual. No cuentan con un sistema automático para validar stock y no ofrecen seguimiento en tiempo real al cliente. Los problemas más comunes son confusiones en las direcciones, pedidos mal registrados o falta de confirmación de pago a tiempo. La conciliación se hace por correo y muchas veces demora. Estaría dispuesto a integrar su proceso a una plataforma SaaS si ésta es simple, rápida y confiable. Usa principalmente celular en el trabajo, se apoya en WhatsApp y Excel, y considera que tiene un nivel medio de habilidad tecnológica.

---

#### Entrevistado N°5
![entrevista_segmento1](img/entrevista5_segmento2.png) 
- Nombres: Zahir
- Apellidos: Sanchez
- Edad: 19 años
- Distrito: Lima
- URL de Entrevista: 
- Duración: 00:05:35
- Resumen:<br>
    Zahir es encargado del registro de pedidos de Petromax, que se dedica a la venta de combustible. Maneja los pedidos de forma semimanual ya que estos llegan primero a través de correo y luego su información pasa a su sistema interno. Tiene la necesidad de generar reportes tanto mensualmente como diariamente, y principalmente deben mostrar datos de ventas y consumo. Siente que es un gran problema el registro de pedidos, ya que cuando identifican un error de información, el pedido se encuentra en estado avanzado. Siente que seríal ideal centralizar todos estos procesos, principallmente por el registro y la conciliación de pagos.

---

#### Entrevistado N°6
![entrevista_segmento1](img/entrevista6_segmento2.png) 
- Nombres: Kevyn
- Apellidos: Chacon
- Edad: 31 años
- Distrito: Lima
- URL de Entrevista: 
- Duración: 00:07:06
- Resumen:<br>
    Kevyn es un parte del area de operaciones de Energex que utiliza combustible para sus vehículos. Recibe los pedidos por correo y usa Excel para su registro y gestión. Se siente frustrado por la dificultad para hacer una gestión de las solicitudes de combustible. Es necesaria la comunicación con sus clientes para que estén al tanto del despacho de sus pedidos. Cree que una solución como FuelTrack podría ayudar a mejorar la comunicación con los proveedores y optimizar el proceso de pedidos.

---

### 2.2.3. Análisis de entrevistas.

#### <u>SEGMENTO 1: Empresas solicitantes de combustible</u>

#### Características objetivas:

| Variable | Porcentaje | Observaciones |
|----------|------------|---------------|
| Edad entre 30 y 45 años | 100% | Todos los entrevistados tienen entre 33 y 45 años. |
| Cargo relacionado a logística | 100% | Los tres pertenecen a áreas de operaciones o logística. |
| Usa computadora y celular | 100% | Todos usan laptop/PC y móvil para sus actividades. |
| Utiliza WhatsApp para coordinar | 66% | 2 de 3 lo usan como canal principal con el proveedor. |
| Manejo de hojas Excel o Google | 100% | Todos gestionan sus pedidos manualmente en planillas. |
| Nivel medio de familiaridad digital | 100% | Dominan software básico (Drive, correo, hojas de cálculo). |

#### Características subjetivas:

| Variable | Porcentaje | Observaciones |
|----------|------------|---------------|
| Necesita trazabilidad del pedido | 100% | Todos demandan claridad en el estado y avance del pedido. |
| Frustración por depósitos no validados | 66% | 2 de 3 se quejan de retrasos debido a validación manual. |
| Deseo de un sistema unificado | 100% | Los 3 expresaron querer centralizar todo el proceso. |
| Receptividad positiva a tecnología | 100% | Todos están abiertos a soluciones digitales con buena UX. |

#### <u>SEGMENTO 2: Proveedores de combustible</u>

#### Características objetivas:

| Variable | Porcentaje | Observaciones |
|----------|------------|---------------|
| Edad entre 39 y 48 años | 100% | Todos en este rango. |
| Cargo en operaciones/logística | 100% | Incluye jefes de planta, despacho o ventas. |
| Utiliza laptop/PC y celular | 100% | Equipamiento estándar en planta o administración. |
| Nivel de digitalización medio | 66% | 2 de 3 usan sistemas propios o ERPs básicos. |
| Gestión mediante correo y llamadas | 100% | El proceso actual es altamente manual. |

#### Características subjetivas:

| Variable | Porcentaje | Observaciones |
|----------|------------|---------------|
| Problemas con conciliación bancaria | 100% | Todos mencionan validación lenta de pagos como cuello de botella. |
| Necesidad de validar stock antes de liberar | 66% | 2 de 3 destacaron esto como un punto crítico. |
| Dificultades en la asignación de vehículos | 66% | Errores de programación y disponibilidad afectan la entrega. |
| Deseo de automatización de procesos | 100% | Todos visualizan mejoras en eficiencia si se digitalizan etapas clave. |

## 2.3. Needfinding.
### 2.3.1. User Personas.

a. User Persona 1: Empresas solicitantes de combustible
![userpersona_segmento1](img/userpersona_segmento1.png)

b. User Persona 2: Proveedores de combustible
![userpersona_segmento2](img/userpersona_segmento2.png)

### 2.3.2. User Task Matrix.

| **Tarea**                                      | **David Miller – Frecuencia** | **David Miller – Importancia** | **Ana Pérez – Frecuencia** | **Ana Pérez – Importancia** |
|------------------------------------------------|-------------------------------|---------------------------------|-----------------------------|------------------------------|
| Revisar nivel de stock de combustible          | Alta | Alta | Baja | Baja |
| Realizar pedido de combustible                 | Media | Alta | Alta | Alta |
| Validar confirmación de pedido                 | Alta | Alta | Alta | Alta |
| Hacer seguimiento a la entrega                 | Alta | Alta | Alta | Alta |
| Supervisar descarga y recepción                | Media | Alta | Media | Media |
| Evaluar proceso post-servicio                  | Baja | Media | Alta | Alta |
| Gestionar atención al cliente                  | Media | Alta | Alta | Alta |
| Revisar encuestas o feedback                   | Baja | Media | Media | Alta |

### 2.3.3. User Journey Mapping.

En el caso del **solicitante**, el recorrido empieza con la generación de un pedido por correo o llamada, seguido por la validación manual del depósito, la espera de aprobación por parte del proveedor, la coordinación del despacho, y finalmente el registro manual de la entrega.

En el caso del **proveedor**, el flujo parte desde la recepción del pedido, luego incluye la verificación del estado de cuenta, la aprobación manual, la asignación de planta y vehículo, y en muchos casos, la reprogramación por problemas de disponibilidad.

a. User Persona 1: Empresas solicitantes de combustible
![userjourneymap_userpersona1](img/userjourneymap_userpersona1.png)

b. User Persona 2: Proveedores de combustible
![userjourneymap_userpersona2](img/userjourneymap_userpersona2.png)

### 2.3.4. Empathy Mapping.

![empathymap_segmento1](img/empathymap_segmento1.png)
![empathymap_segmento1](img/empathymap_segmento2.png)

### 2.3.5. As-is Scenario Mapping. 
### As-Is Scenario Mapping

| FASES | Comunicación | Solicitar pedido | Seguimiento | Entrega |
|-------|--------------|------------------|-------------|---------|
| **DOING** | Llamadas, correos, WhatsApp sin orden. | El solicitante explica los datos del pedido a mano. | Se hacen llamadas para preguntar por el estado. | Se confirma por llamada o mensaje. |
| **THINKING** | "¿Habrán recibido mi mensaje?" | "¿Me habrán entendido bien?" | "¿Dónde estará nuestro pedido?" | "¿Ya habrán llegado?" |
| **FEELING** | Frustración, desorganización. | Incertidumbre, falta de confianza. | Ansiedad, impaciencia. | Duda, estrés. |

## 2.4. Ubiquitous Language. 

| Término | Definición | Segmentos relacionados |
|---------|------------|------------------------|
| **Requester (Solicitante)** | Usuario representante de una empresa requiere abastecimiento de combustible | Solicitante |
| **Supplier (Proveedor)** | Empresa que ofrece combustibles al por mayor y compite mediante precios, descuentos y promociones. | Proveedor |
| **Fuel (Combustible)** | Recurso energético que es ofertado por los proveedores. Ejemplos: gasohol, diésel, GNV. | Solicitante, Proveedor |
| **Plant (Planta)** | Punto de distribución del combustible perteneciente a al proveedor. | Solicitante, Proveedor |
| **Price per gallon (Precio por galón)** | Valor económico que el proveedor establece por cada galón de combustible. Puede variar según planta, tipo de combustible, etc. | Solicitante, Proveedor |
| **Discount (Descuento)** | Reducción aplicada sobre el precio ofrecido, ya sea por volumen, fidelización u otras condicioens. | Solicitante, Proveedor |
| **Quotation (Cotización)** | Propuesta formal que un proveedor genera detallando precios, productos, entre otras condiciones | Solicitante, Proveedor |
| **Price Table (Tabla de precios)** | Grilla o tabla que muestra los precios ofrecidos por planta, proveedor y tipo de combustible. | Solicitante |
| **Negotiation (Negociación)**   | Intercambio de condiciones entre solicitante y proveedor para alcanzar un acuerdo favorable para ambas partes. | Solicitante, Proveedor |
| **Consumption Volume (Volumen de consumo)** | Cantidad de combustible estimada que una empresa solicita regularmente en un periodo determinado. | Solicitante |
| **Purchase History (Historial de compras)** | Registro de cotizaciones y compras o pedidos previos hechos por el solicitante dentro del sistema. | Solicitante |