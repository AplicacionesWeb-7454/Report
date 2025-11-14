## **Universidad Peruana De Ciencias Aplicadas**  

### Facultad de Ingenieria  
### Carrera de Ingenieria de Software   
### Ciclo: 2025-02
### 7454 | Aplicaciones Web 
### Profesor: Angel Augusto Velasquez Nuñez



### **Informe de Trabajo Final**  
### Startup: Turing Almost Complete 
### Producto: Pandora's Fresh  



### Integrantes:
- Vidal Malaga, Jareth Beycker  (u202316878)
- Seminario Castillo, Diego Vicente  (u202412591)
- Chuchon Choquimamani, Jhon Alexander  (u20231c895)
- Llamozas Diaz, Edson Diego  (u202319398)
- Mendoza Vergara, Alejandro Franklin (u202312343)

---

### **Registro de Versiones del Informe**
| Versión | Fecha       | Autor             | Descripción de modificación            |
|---------|-------------|-------------------|----------------------------------------|
| 0.1     | 06/04/2025  | Llamozas Diaz, Edson Diego  <br> Vidal Malaga, Jareth Beycker <br> Chuchon Choquimamani, Jhon Alexander <br> | Desarrollo del capítulo 1 y 2             |
| 0.2     | 12/04/2025  | Vidal Malaga, Jareth Beycker          | Desarrollo del capítulo 3                    |
| 0.3     | 18/04/2025  | Seminario Castillo, Diego Vicente <br> Chuchon Choquimamani, Jhon Alexander <br> Mendoza Vergara, Alejandro Franklin   | Desarrollo del capítulo 4 y sprint 1         |

---

### **Project Report Collaboration Insights**

- URL Repositorio: https://github.com/AplicacionesWeb-7454/Report.git
  
<img src="https://raw.githubusercontent.com/AplicacionesWeb-7454/Report/main/assets/img/chapter1/VDD.PNG" alt="VDD" style="width:auto; height:auto;">

<img src="https://raw.githubusercontent.com/AplicacionesWeb-7454/Report/main/assets/img/chapter1/CONTRI.PNG" alt="CONTRI" style="width:auto; height:auto;">



---

### **Contenido**

- [Capítulo I: Introducción](#capítulo-i-introducción)  
  - [1.1. Startup Profile](#11-startup-profile)  
    - [1.1.1. Descripción de la Startup](#111-descripción-de-la-startup)  
    - [1.1.2. Perfiles de integrantes del equipo](#112-perfiles-de-integrantes-del-equipo)  
  - [1.2. Solution Profile](#12-solution-profile)  
    - [1.2.1. Antecedentes y problemática](#121-antecedentes-y-problemática)  
    - [1.2.2. Lean UX Process](#122-lean-ux-process)  
      - [1.2.2.1. Lean UX Problem Statements](#1221-lean-ux-problem-statements)  
      - [1.2.2.2. Lean UX Assumptions](#1222-lean-ux-assumptions)  
      - [1.2.2.3. Lean UX Hypothesis Statements](#1223-lean-ux-hypothesis-statements)  
      - [1.2.2.4. Lean UX Canvas](#1224-lean-ux-canvas)  
  - [1.3. Segmentos objetivo](#13-segmentos-objetivo)  

- [Capítulo II: Requirements Elicitation & Analysis](#capítulo-ii-requirements-elicitation--analysis)  
  - [2.1. Competidores](#21-competidores)  
    - [2.1.1. Análisis competitivo](#211-análisis-competitivo)  
    - [2.1.2. Estrategias y tácticas frente a competidores](#212-estrategias-y-tácticas-frente-a-competidores)  
  - [2.2. Entrevistas](#22-entrevistas)  
    - [2.2.1. Diseño de entrevistas](#221-diseño-de-entrevistas)  
    - [2.2.2. Registro de entrevistas](#222-registro-de-entrevistas)  
    - [2.2.3. Análisis de entrevistas](#223-análisis-de-entrevistas)  
  - [2.3. Needfinding](#23-needfinding)  
    - [2.3.1. User Personas](#231-user-personas)  
    - [2.3.2. User Task Matrix](#232-user-task-matrix)  
    - [2.3.3. User Journey Mapping](#233-user-journey-mapping)  
    - [2.3.4. Empathy Mapping](#234-empathy-mapping)  
  - [2.4. Big Picture Event Storming](#24-big-picture-event-storming)  
  - [2.5. Ubiquitous Language](#25-ubiquitous-language)  

- [Capítulo III: Requirements Specification](#capítulo-iii-requirements-specification)  
  - [3.1. User Stories](#31-user-stories)  
  - [3.2. Impact Mapping](#32-impact-mapping)  
  - [3.3. Product Backlog](#33-product-backlog)  

- [Capítulo IV: Product Design](#capítulo-iv-product-design)  
  - [4.1. Style Guidelines](#41-style-guidelines)  
    - [4.1.1. General Style Guidelines](#411-general-style-guidelines)  
    - [4.1.2. Web Style Guidelines](#412-web-style-guidelines)  
  - [4.2. Information Architecture](#42-information-architecture)  
    - [4.2.1. Organization Systems](#421-organization-systems)  
    - [4.2.2. Labeling Systems](#422-labeling-systems)  
    - [4.2.3. SEO Tags and Meta Tags](#423-seo-tags-and-meta-tags)  
    - [4.2.4. Searching Systems](#424-searching-systems)  
    - [4.2.5. Navigation Systems](#425-navigation-systems)  
  - [4.3. Landing Page UI Design](#43-landing-page-ui-design)  
    - [4.3.1. Landing Page Wireframe](#431-landing-page-wireframe) 
    - [4.3.2. Landing Page Mock-up](#432-landing-page-mock-up)  
  - [4.4. Web Applications UX/UI Design](#44-web-applications-uxui-design)  
    - [4.4.1. Web Applications Wireframes](#441-web-applications-wireframes)  
    - [4.4.2. Web Applications Wireflow Diagrams](#442-web-applications-wireflow-diagrams)  
    - [4.4.2. Web Applications Mock-ups](#442-web-applications-mock-ups)  
    - [4.4.3. Web Applications User Flow Diagrams](#443-web-applications-user-flow-diagrams)  
  - [4.5. Web Applications Prototyping](#45-web-applications-prototyping)  
  - [4.6. Domain-Driven Software Architecture](#46-domain-driven-software-architecture)  
    - [4.6.1. Design-Level Event Storming](#461-design-level-event-storming)  
    - [4.6.2. Software Architecture Context Diagram](#462-software-architecture-context-diagram)  
    - [4.6.3. Software Architecture Container Diagrams](#463-software-architecture-container-diagrams)  
    - [4.6.4. Software Architecture Components Diagrams](#464-software-architecture-components-diagrams)  
  - [4.7. Software Object-Oriented Design](#47-software-object-oriented-design)  
    - [4.7.1. Class Diagrams](#471-class-diagrams)  
  - [4.8. Database Design](#48-database-design)  
    - [4.8.1. Database Diagrams](#481-database-diagrams)  

- [Capítulo V: Product Implementation, Validation & Deployment](#capítulo-v-product-implementation-validation--deployment)  
  - [5.1. Software Configuration Management](#51-software-configuration-management)  
    - [5.1.1. Software Development Environment Configuration](#511-software-development-environment-configuration)  
    - [5.1.2. Source Code Management](#512-source-code-management)  
    - [5.1.3. Source Code Style Guide & Conventions](#513-source-code-style-guide--conventions)  
    - [5.1.4. Software Deployment Configuration](#514-software-deployment-configuration)  
  - [5.2. Landing Page, Services & Applications Implementation](#52-landing-page-services--applications-implementation)  
    - [5.2.1. Sprint 1](#521-sprint-1)  
      - [5.2.1.1. Sprint Planning 1](#5211-sprint-planning-1)  
      - [5.2.1.2. Aspect Leaders and Collaborators](#5212-aspect-leaders-and-collaborators)  
      - [5.2.1.3. Sprint Backlog n](#5213-sprint-backlog-1)  
      - [5.2.1.4. Development Evidence for Sprint Review](#5214-development-evidence-for-sprint-review)  
      - [5.2.1.5. Execution Evidence for Sprint Review](#5215-execution-evidence-for-sprint-review)  
      - [5.2.1.6. Services Documentation Evidence for Sprint Review](#5216-services-documentation-evidence-for-sprint-review)  
      - [5.2.1.7. Software Deployment Evidence for Sprint Review](#5217-software-deployment-evidence-for-sprint-review)  
      - [5.2.1.8. Team Collaboration Insights during Sprint](#5218-team-collaboration-insights-during-sprint)
      - [5.2.2. Sprint 2](#522-sprint-2)
      - [5.2.2.1. Sprint Planning 2](5221-sprint-planning-2)


---

### **Student Outcome**

| Criterio específico                                                | Acciones realizadas                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  | Conclusiones |
|--------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|--------------|
| Comunica oralmente con efectividad a diferentes rangos de audiencia | **Jareth Vidal** <br> TB1: Expliqué con claridad los análisis de competidores, user personas, journey mapping, historias de usuario, arquitectura, diseño orientado a objetos y base de datos, adaptando mi lenguaje según la audiencia y utilizando recursos visuales para comunicar efectivamente los avances del proyecto. <br> **Diego Seminario** <br> TB1: Presenté y sustenté las guías de estilo, arquitectura de información y mock-ups web utilizando un lenguaje claro y apoyos visuales, facilitando la comprensión de las decisiones de diseño ante públicos con distintos niveles técnicos. <br>TP: Desarrolle la mejora de los web application asi mismo desarrolle mi bc user-management guiandose a las respectivas hu. <br> **Jhon Chuchon** <br> TB1: Expliqué los resultados del diseño y análisis de entrevistas, así como los wireframes y mock-ups de la landing page, adaptando mi lenguaje y argumentos para transmitir con claridad las necesidades del usuario y las decisiones de diseño. <br> TP: Presentéla parte del bounded context de la parte de notificación y alertas, tambien expliqué con claridad el design level event storming, adaptando mi lenguaje y conocimientos para transmitir con claridad nuestra idea de trabajo <br> **Edson Llamozas** <br> TB1: Presenté la descripción de la startup, el proceso Lean UX y los segmentos objetivo explicando con claridad la problemática y las hipótesis del proyecto, adecuando mi lenguaje y ejemplos según la audiencia. <br> **Alejandro Mendoza** <br> TB1: Expuse los procesos de configuración, desarrollo e implementación del software, explicando las evidencias del sprint 1 y las decisiones técnicas con claridad, adaptando el lenguaje según el público y destacando el trabajo colaborativo del equipo.<br> TP: Al desarrollar el bounded context referente al reporting and analytics pude enfocarme en las necesidades de todo tipo de audiencia y que estos reciban reportes sencillos de entender <br> **Jareth Vidal** <br> TP: Al desarrollar el Business Case de monitoreo IoT, adapté el enfoque según el perfil de cada audiencia. Incorporé mejoras a entregas anteriores con base en su feedback, logrando una comunicación más clara y efectiva entre áreas técnicas y estratégicas.                          | **TB1:** <br> Durante el desarrollo del proyecto, nuestro equipo demostró una comunicación oral efectiva al presentar cada etapa, desde la identificación del problema hasta la implementación del sistema. Expusimos ideas, decisiones técnicas y resultados de forma clara y estructurada, adaptando el lenguaje según la audiencia. Además, utilizamos recursos visuales como diagramas, mock-ups y evidencias de desarrollo, lo que facilitó la comprensión de los contenidos y permitió sostener una interacción fluida con docentes, compañeros y evaluadores. <br> **TP:** <br> Como equipo, elaboramos propuestas funcionales para Pandora Fresh, abordando módulos como monitoreo IoT, alertas, inventario, login, reportes y analítica. Mejoramos entregas anteriores incorporando retroalimentación de perfiles técnicos, operativos y estratégicos, lo que permitió comunicar oralmente de forma clara y efectiva según cada audiencia.          |  
| Comunica por escrito con efectividad a diferentes rangos de audiencia | **Jareth Vidal** <br> TB1: Redacté con claridad los apartados de análisis competitivo, user personas, historias de usuario, arquitectura, diseño y base de datos, empleando un lenguaje técnico y estructurado según la audiencia, para comunicar de forma efectiva los resultados y decisiones del proyecto. <br> **Diego Seminario** <br> TB1: Documenté de manera estructurada las guías de estilo, sistemas de organización y navegación, así como los mock-ups web, empleando redacción técnica y visual coherente que permitió comunicar con precisión las propuestas de diseño.   <br> TP: Desarrollando el bc user management comprendi como es la asignacion de roles para nuestro trabajo , asi mismo la autenticacion de los correos ,contraseñas,etc<br> **Jhon Chuchon** <br> TB1: Elaboré los documentos de entrevistas, análisis y diseño visual de la landing page con redacción clara y organizada, utilizando lenguaje técnico y descriptivo que facilitó la comprensión de los hallazgos y propuestas. <br> **Edson Llamozas** <br> TB1: Redacté de forma estructurada la descripción de la startup, los perfiles del equipo y el proceso Lean UX, empleando un lenguaje formal y preciso que permitió comunicar claramente la problemática y los objetivos del proyecto. <br> **Alejandro Mendoza** <br> TB1: Documenté la configuración del entorno, gestión del código y desarrollo por sprints con redacción técnica y ordenada, presentando evidencias, convenciones y resultados que reflejan el avance y la calidad del proyecto.<br> TP: Al desarrollar el bounded context de reporting and analytics pude comunicar de manera escrita a distintas audiencias, además el trabajo en el reporte facilitó mi comprensión en los temas y el problema tratado <br> **Jareth Vidal** <br> TP: Al redactar el Business Case de monitoreo IoT, estructuré el contenido para ser comprensible tanto para perfiles técnicos como estratégicos. Usé lenguaje preciso, visualizaciones claras y enfoques diferenciados según el lector, lo que facilitó la toma de decisiones y el alineamiento entre áreas. | **TB1:** <br> Como equipo, elaboramos una documentación completa, coherente y organizada que abarcó desde la introducción del proyecto hasta su implementación. Empleamos un lenguaje técnico y formal adecuado para distintos públicos, complementado con gráficos, tablas y evidencias. Esto nos permitió comunicar de manera efectiva los objetivos, procesos y resultados obtenidos, reflejando el trabajo colaborativo y la solidez del proyecto en cada una de sus etapas. <br> **TP:** <br> Como equipo, elaboramos documentación funcional para Pandora Fresh, cubriendo módulos como monitoreo IoT, alertas, inventario, login, reportes y analítica. Redactamos entregables claros y estructurados, adaptando el lenguaje y el nivel de detalle según el perfil técnico, operativo o estratégico de cada audiencia, lo que facilitó la comprensión y validación transversal del proyecto.            |


---

# **Capítulo I: Introducción**

## 1.1. Startup Profile
### 1.1.1. Descripción de la Startup

Pandora’s Fresh es una startup innovadora del sector FoodTech (Tecnología Alimentaria) fundada con la misión de combatir el desperdicio de alimentos y revolucionar la gestión de inventarios para productos perecibles. Nuestra visión es convertirnos en el socio tecnológico esencial para mercados locales, restaurantes y pequeños productores, permitiéndoles operar con máxima eficiencia y sostenibilidad.

Operamos en un mercado donde la trazabilidad y el control de variables ambientales son críticas, pero a menudo se gestionan con métodos manuales y propensos a errores. Pandora’s Fresh cierra esta brecha tecnológica al ofrecer una plataforma integral que combina hardware de sensores IoT y un software inteligente. Esta solución permite el monitoreo en tiempo real de condiciones críticas como temperatura, humedad y fechas de caducidad, enviando alertas proactivas para prevenir pérdidas.

Nuestro valor principal radica en transformar datos brutos en insights accionables. No solo mostramos el estado del inventario, sino que predecimos riesgos, automatizamos reportes y facilitamos la toma de decisiones basada en datos, lo que se traduce directamente en ahorro de costos, reducción de mermas y una mejora significativa en la calidad y seguridad de los alimentos.

Propuesta de Valor: Ofrecemos control absoluto, tranquilidad y eficiencia en la gestión de productos perecibles a través de una plataforma intuitiva, confiable y diseñada específicamente para las necesidades del sector alimentario local.

### 1.1.2. Perfiles de integrantes del equipo
| Foto                                                                                                                                                                 | Descripción |
|----------------------------------------------------------------------------------------------------------------------------------------------------------------------|---|
| <img width="150" src="https://raw.githubusercontent.com/AplicacionesWeb-7454/Report/main/assets/img/FotosNuestras/Alejandro.jpeg  "> | Mi nombre es Alejandro Mendoza y soy estudiante de la carrera de Ingeniería de Software.Actualmente tengo experiencia en C++ y Python.Estoy interesado en seguir aprendiendo sobre diferentes lenguajes de programación y en la creación de distintas aplicaciones web y móviles,por lo que intento dar todo de mí para tener buenos resultados.|
| <img width="150" src="https://raw.githubusercontent.com/AplicacionesWeb-7454/Report/main/assets/img/FotosNuestras/JarethVidal.jpg">   | Mi nombre es Jareth Vidal estoy estudiando la carrera de Ingeniería de Software y actualmente me encuentro cursando el quinto ciclo. Me gusta el deporte y mantenerme en constante aprendizaje. Tengo conocimientos en  C++, HTML, CSS y JavaScript y un poco de Python, así como habilidades para la adaptabilidad y la responsabilidad. |
| <img width="150" src="https://raw.githubusercontent.com/AplicacionesWeb-7454/Report/main/assets/img/FotosNuestras/Edson.jpeg">          |Mi nombre es Edson,tengo 19 años y soy estudiante de Ingeniería de Software en la UPC, sede San Miguel. Soy responsable con mi grupo de trabajo . Tengo conocimientos en C++ y Python.|   
| <img width="150" src="https://raw.githubusercontent.com/AplicacionesWeb-7454/Report/main/assets/img/FotosNuestras/JhonChuchon.png">          |Mi nombre es Jhon,tengo 19 años y soy estudiante de Ingeniería de Software en la UPC, sede San Miguel. Soy una persona decidida,  responsable y honesta con mi grupo de trabajo ,siendo lo más útil posible. Tengo conocimientos en C++,C# y php. Cada día trato de dar una mejor versión de mi y aprender de mis errores. |   
| <img width="150" src="https://raw.githubusercontent.com/AplicacionesWeb-7454/Report/main/assets/img/FotosNuestras/Diego.png">          |Mi nombre es Diego,tengo 22 años y soy estudiante de Ingeniería de Software en la UPC, sede San Miguel tengo conocimientos en diferentes lenguajes de programacion como Python y Javascript |   

## 1.2. Solution Profile

### 1.2.1. Antecedentes y Problemática

####  Descripción del problema  
La gestión de inventarios de productos perecibles en mercados locales, restaurantes y pequeñas empresas se realiza mayoritariamente mediante métodos manuales y sistemas genéricos. Esta falta de especialización conlleva a una ausencia de visibilidad en tiempo real sobre el estado de los productos, generando altos índices de desperdicio de alimentos, pérdidas económicas significativas y posibles riesgos para la salud del consumidor.

---

####  Técnica 5W+2H

**What? (¿Qué?)**  
La problemática principal es la pérdida y el desperdicio de productos perecibles debido a una gestión de inventario ineficiente, que no permite monitorear proactivamente variables críticas como la temperatura, la humedad y las fechas de caducidad.

**When? (¿Cuándo?)**  
El problema ocurre constantemente a lo largo de la cadena de suministro, pero se intensifica durante el almacenamiento y la venta, especialmente en picos de demanda o fallas de refrigeración (por ejemplo, cortes de energía). También es crítico justo antes de que los productos alcancen su fecha de vencimiento.

**Where? (¿Dónde?)**  
Este problema es común en pequeños y medianos negocios del sector alimentario, como bodegas, mercados de abastos, restaurantes y puestos de venta fresca, donde el acceso a tecnologías avanzadas es limitado por su costo y complejidad.

**Who? (¿Quién?)**  
Los principales afectados son los propietarios y gerentes de estos negocios, quienes sufren las pérdidas económicas. También se ve afectado el personal de almacén, que trabaja con información imprecisa, y el consumidor final, que puede recibir productos en mal estado o pagar precios más altos debido a la ineficiencia operativa.

**Why? (¿Por qué?)**  
La raíz del problema es la desconexión entre el estado físico real del producto y los métodos de gestión utilizados. Las herramientas actuales (libretas, Excel, sistemas genéricos) dependen de revisiones manuales y registros retrospectivos, lo que impide una reacción inmediata ante condiciones que degradan la mercancía.

**How? (¿Cómo?)**  
Los procesos actuales son reactivos. Un empleado debe revisar físicamente cada producto o cámara frigorífica para registrar temperaturas y fechas, lo cual es propenso a errores humanos, consume tiempo y no ofrece alertas instantáneas ante una falla. Esto genera que los productos se echen a perder sin advertencia previa.

**How Much? (¿Cuánto?)**  
Según la FAO, cerca de un tercio de todos los alimentos producidos a nivel mundial se desperdicia. Para un negocio local, esto puede representar entre el 5% y el 20% de su inventario anual, afectando directamente la rentabilidad, aumentando costos de operación y exponiendo a posibles sanciones por salubridad.

---

### 1.2.2. Lean UX Process

#### 1.2.2.1. Lean UX Problem Statements

Nuestra plataforma **Pandora’s Fresh** ofrece una solución integral para la gestión de inventarios de productos perecibles. El objetivo de esta startup es reemplazar los métodos manuales y sistemas genéricos —como libretas físicas, hojas de cálculo o software no especializado— por un sistema digital centralizado que permita el monitoreo en tiempo real de variables críticas y la gestión proactiva del inventario.

Luego de analizar la metodología utilizada actualmente en mercados y restaurantes, identificamos un desafío clave: la dependencia en métodos reactivos y desconectados del estado físico real de la mercancía, lo que genera desperdicio de alimentos, pérdidas económicas y riesgos sanitarios. Esta falta de visibilidad impacta directamente en la rentabilidad y sostenibilidad operativa de los negocios.

En el contexto actual, donde la eficiencia operativa y la sostenibilidad son prioridades, **Pandora’s Fresh** busca transformar datos ambientales en **insights accionables**, ayudando a las empresas a evitar pérdidas, optimizar compras y garantizar la calidad de sus productos.

El segmento inicial está compuesto por **pequeños y medianos restaurantes y puestos de mercados de abastos en Lima Metropolitana**, los más afectados por el desperdicio y con mayor urgencia de modernizar su gestión.

---

#### 1.2.2.2. Lean UX Assumptions

**Business Assumptions**
- Los negocios de alimentos están buscando tecnologías accesibles para reducir desperdicios y mejorar su rentabilidad.  
- Los gerentes y propietarios están dispuestos a invertir en una solución que les brinde control total y tranquilidad sobre su inventario.  
- La trazabilidad e higiene en la gestión de alimentos son factores competitivos valorados por los consumidores.  
- La automatización del control de temperatura y humedad es percibida como una necesidad para operar de forma eficiente.  
- El problema del desperdicio es tan crítico que los usuarios estarían dispuestos a abandonar métodos tradicionales por una solución digital.

**User Assumptions**
- **¿Quién es el usuario?** Propietarios, gerentes de restaurantes y encargados de almacén o bodega en mercados.  
- **¿Dónde encaja el producto?** Pandora’s Fresh se integra en su flujo de trabajo diario como herramienta central de gestión, reemplazando revisiones manuales y ofreciendo datos en tiempo real.  
- **¿Qué problemas resuelve?** Falta de visibilidad, control deficiente de caducidad y ausencia de alertas preventivas.  
- **¿Cuándo y cómo se usa?** Durante la operación diaria, de forma proactiva y reactiva ante alertas, para monitorear, planificar compras o verificar productos específicos.  
- **¿Qué características son importantes?** Alertas en tiempo real, seguimiento de caducidad, dashboard de inventario, reportes de merma y gestión intuitiva.  
- **¿Cómo debe verse y comportarse?** Interfaz limpia, visual e intuitiva; prioriza alertas, confiabilidad y rapidez, comportándose de forma proactiva ante eventos críticos.

**Feature Assumptions**
- Las alertas en tiempo real sobre temperatura y humedad permitirán prevenir pérdidas inmediatas.  
- Las notificaciones anticipadas sobre caducidad ayudarán a planificar ventas y reducir desperdicio.  
- Un dashboard con métricas claras mejorará la toma de decisiones estratégicas.  
- La interfaz móvil y web aumentará la adopción y facilidad de uso.  
- La automatización de reportes de inventario y merma ahorrará tiempo valioso al personal.

---

#### 1.2.2.3. Lean UX Hypothesis Statements

**Hypothesis Statement 01**  
Creemos que el monitoreo en tiempo real de temperatura y humedad mediante sensores IoT reducirá las pérdidas de inventario causadas por condiciones ambientales inadecuadas.  
**Éxito medido:** Después de tres meses, los usuarios reportarán una reducción del **25%** en productos perdidos por degradación.

**Hypothesis Statement 02**  
Creemos que las notificaciones proactivas sobre productos próximos a vencer permitirán aplicar estrategias de venta (ofertas o descuentos) para reducir el desperdicio.  
**Éxito medido:** El **80%** de las alertas de caducidad generarán una acción correctiva por parte del usuario.

**Hypothesis Statement 03**  
Creemos que centralizar la gestión del inventario en una plataforma intuitiva reducirá el tiempo dedicado a inventarios manuales.  
**Éxito medido:** Los usuarios reportarán una reducción del **40%** en el tiempo destinado a gestión manual tras un mes de uso.

**Hypothesis Statement 04**  
Creemos que proveer datos claros sobre las causas y costos de la merma aumentará la conciencia operativa y promoverá mejoras.  
**Éxito medido:** El **90%** de los usuarios consultará los reportes de merma al menos una vez por semana para ajustar pedidos o procesos.

#### 1.2.2.4. Lean UX Canvas.

La imagen muestra un Lean UX Canvas para Pandora Fresh,Resume problemas de disponibilidad, propone una plataforma logística y tecnológica, identifica usuarios clave, valida hipótesis de adopción y establece un plan de acción con tiempos definidos.

<img src="https://raw.githubusercontent.com/AplicacionesWeb-7454/Report/main/assets/img/chapter1/Lean%20UX%20Canvas%20Template.png" alt="Lean UX Canvas Template">

## 1.3. Segmentos objetivo.
A. Pequeños y Medianos Restaurantes (PYMES)
Establecimientos gastronómicos cuyo modelo de negocio depende de la frescura y calidad de sus insumos. Manejan un inventario diverso de productos perecibles (vegetales, carnes, lácteos) en cámaras de refrigeración y almacenes, pero carecen de sistemas especializados para su control. Están motivados por reducir costos operativos, minimizar el desperdicio de alimento y garantizar la calidad y seguridad de los platos que sirven a sus clientes.

Necesidades:

Prevenir la pérdida de inventario por mal almacenamiento o caducidad.

Automatizar el control de temperatura de sus cámaras frigoríficas.

Optimizar el proceso de compra basándose en el estado real de su inventario.

Garantizar el cumplimiento de normas de salubridad.

Motivaciones:

Aumentar la rentabilidad al reducir significativamente la merma.

Mejorar la eficiencia operativa al ahorrar tiempo en gestión manual.

Ofrecer un menú de mayor calidad y seguridad al cliente final.

B. Proveedores y Puestos en Mercados de Abastos
Comercios ubicados en mercados tradicionales que se dedican a la venta al por mayor y menor de productos frescos (frutas, verduras, carnes, pescados). Operan en un entorno de alto volumen y rotación, donde la trazabilidad es mínima y las pérdidas por deterioro son absorbidas como parte del costo operativo. Son altamente sensibles al precio pero reconocen la necesidad de modernizarse para ser más competitivos.

Necesidades:

Tener visibilidad en tiempo real del estado de su mercancía perecedera.

Recibir alertas inmediatas para vender o procesar productos que están próximos a dañarse.

Evitar pérdidas económicas por loteos de productos echados a perder.

Digitalizar sus operaciones para competir con cadenas de retail más grandes.

Motivaciones:

Maximizar el rendimiento de cada lote de productos adquirido.

Tomar decisiones rápidas (como hacer ofertas) para salvar inventario vulnerable.

Ganar una ventaja competitiva al ofrecer una gestión de calidad más transparente.
---

# **Capítulo II: Requirements Elicitation & Analysis**
## 2.1. Competidores.
### 2.1.1. Análisis competitivo.

| Por qué llevar a cabo este análisis? | Este análisis permite identificar quiénes son los competidores directos e indirectos de Pandora’s Fresh, conocer sus fortalezas y debilidades, y determinar cómo posicionar nuestra solución para destacar en el mercado de gestión de inventarios de productos perecibles. |
|--------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|

| Características | MarketMan | xtraCHEF / Toast | Yellow Dog Inventory | Afresh / RELEX Solutions | **Pandora's Fresh** |
|-----------------|-----------|-----------------|--------------------|-------------------------|------------------|
| **Perfil**      | Software de gestión de inventarios para restaurantes y bares. | Plataforma de automatización contable y control de inventarios para restaurantes. | Gestión de inventarios para restaurantes, catering y bares. | Software de optimización de inventarios frescos para supermercados y minoristas. | Plataforma integral de gestión de inventarios perecibles con IoT y analítica predictiva, enfocada en PYMEs locales y mercados. |
| **Ventaja competitiva**<br>¿Qué valor ofrece a los clientes? | Control de costos, reducción de desperdicio, digitalización de inventarios. | Automatización contable, control de inventarios, informes financieros. | Control de inventarios y reducción de pérdidas. | Predicción de demanda, optimización de reabastecimiento de productos frescos. | Monitoreo en tiempo real de variables críticas (temperatura, humedad, caducidad), alertas proactivas, predicción de riesgos y toma de decisiones basada en datos. |
| **Mercado objetivo** | Restaurantes y bares medianos. | Restaurantes y bares. | Restaurantes pequeños, catering y bares. | Supermercados y minoristas grandes. | Pequeños y medianos restaurantes y puestos de mercados de abastos en Lima Metropolitana. |
| **Estrategias de marketing** | Demostraciones y webinars para restaurantes. | Integración con sistemas de punto de venta, marketing digital. | Promociones a restaurantes y bares locales. | Ventas B2B directas y consultoría para grandes retailers. | Alianzas locales, demostraciones en vivo, educación sobre sostenibilidad y reducción de desperdicio, marketing digital enfocado en PYMEs. |
| **Precios & Costos** | Suscripción mensual según tamaño del negocio. | Suscripción basada en volumen de transacciones. | Suscripción mensual para pequeñas empresas. | Licencias empresariales personalizadas. | Modelo escalable basado en suscripción, adaptado a PYMEs, con opción de hardware IoT incluido. |
| **Productos & Servicios** | Software de inventario, reportes de costos, alertas básicas. | Software contable y de inventario, reportes financieros. | Software de inventarios, reportes y alertas. | Software de optimización de inventario fresco, predicción de demanda. | Software + hardware IoT, monitoreo en tiempo real, alertas proactivas, reportes automáticos, insights predictivos, gestión centralizada. |
| **Canales de distribución**  | Online, ventas directas, partners de restaurantes. | Integraciones con POS, ventas directas. | Online, ventas directas a restaurantes. | Ventas directas B2B y consultores especializados. | Online, demostraciones en sitio, alianzas locales con mercados y asociaciones de restaurantes. |
| **Fortalezas**               | Fácil de usar, reduce desperdicio, digitaliza inventarios. | Integración con contabilidad, automatiza tareas financieras. | Control básico de inventarios, fácil de implementar. | IA avanzada para predicción de demanda, optimización de inventarios. | Monitoreo en tiempo real, IoT, predicción de riesgos, enfoque en PYMEs y sostenibilidad, insights accionables. |
| **Debilidades**              | No incluye monitoreo ambiental ni predicción de riesgos. | No integra sensores ni alertas en tiempo real. | Funcionalidades limitadas, no predictivo. | Enfocado en grandes retailers, costoso para PYMEs. | Nuevo en el mercado, requiere educación a clientes sobre tecnología IoT. |
| **Oportunidades**            | Crecimiento en adopción digital de restaurantes. | Expansión a nuevos mercados y cadenas de restaurantes. | Digitalización de PYMEs, integración con IoT. | Expansión a mercados emergentes y PYMEs. | Liderar digitalización de PYMEs locales, promover sostenibilidad, expandir monitoreo IoT a otros mercados. |
| **Amenazas**                 | Competencia de software más avanzado y económico. | Competencia de soluciones más integrales. | Competencia de nuevas startups con IoT y analítica predictiva. | Competencia de soluciones especializadas para PYMEs. | Entrada de competidores globales, reticencia de negocios locales a adoptar tecnología nueva. |


### 2.1.2. Estrategias y tácticas frente a competidores.

| Estrategia | Objetivo | Tácticas |
|------------|---------|----------|
| **Diferenciación tecnológica** | Destacar como la solución más avanzada para PYMEs y mercados locales | - Integración de sensores IoT para monitoreo en tiempo real. <br> - Alertas proactivas y predicción de riesgos. <br> - Panel de control intuitivo con insights accionables. |
| **Foco en PYMEs locales** | Atacar un nicho desatendido por competidores grandes | - Campañas de marketing local en Lima Metropolitana. <br> - Alianzas con mercados de abastos y asociaciones de restaurantes. <br> - Pricing escalable adaptado a pequeños negocios. |
| **Sostenibilidad y reducción de desperdicio** | Posicionarse como aliado de eficiencia y responsabilidad | - Promover casos de éxito que muestren reducción de mermas. <br> - Contenido educativo sobre sostenibilidad y buenas prácticas. <br> - Certificaciones o reconocimientos de sostenibilidad para clientes. |
| **Educación y confianza tecnológica** | Reducir la reticencia de negocios a adoptar IoT y software | - Webinars, workshops y demostraciones en sitio. <br> - Manuales simples y soporte personalizado. <br> - Programas de onboarding rápido. |
| **Marketing de prueba y recomendación** | Generar adopción inicial y boca a boca | - Versiones piloto gratuitas o con descuento. <br> - Testimonios de clientes satisfechos. <br> - Programa de referidos para atraer nuevos negocios. |

## 2.2. Entrevistas.
### 2.2.1. Diseño de entrevistas.

- Preguntas para el primer segmento:
  
  - ¿Podría contarme brevemente en qué consiste su trabajo diario como jefe de cocina?
    
  - ¿Cómo decide qué cantidad de productos comprar a sus proveedores?
    
  - ¿Cómo lleva el control de las existencias que tiene disponibles?
    
  - ¿Cómo gestionan actualmente el inventario de alimentos en la cocina?
    
  - ¿Qué herramientas o métodos usan para controlar las fechas de caducidad y el estado de los productos?
    
  - ¿Qué tan seguido enfrentan problemas de falta o exceso de insumos?
    
  - ¿Cómo es la coordinación entre usted y el área de compras o proveedores?
    
  - ¿Qué procesos siguen para asegurar la calidad y frescura de los ingredientes antes de usarlos?
    
  - ¿Cómo garantizan el cumplimiento de normas de higiene y seguridad alimentaria en la cocina?
    
  - ¿Utilizan actualmente alguna herramienta digital para gestionar inventarios o pedidos?
    
  - ¿Qué funcionalidades cree que serían útiles en una herramienta pensada para la gestión de cocina?
    
  - ¿Qué consejo le daría a alguien que está empezando en este rol?

- Preguntas para el segundo segmento:
  
  - ¿Podría explicarme cómo gestiona actualmente el inventario de productos frescos, lácteos y otros artículos perecederos?

  - ¿Cuáles son los mayores desafíos o dolores de cabeza que enfrenta con la gestión de estos productos perecederos?

  - ¿Cómo hace un seguimiento actualmente de cosas como las fechas de caducidad o la frescura de los productos?

  - El desperdicio de alimentos es un desafío común en la industria. ¿Puede describir cómo se manifiesta eso en su negocio? ¿Con qué frecuencia tiene que tirar artículos?

  - ¿Qué impacto tiene este desperdicio en su negocio, tanto financiero como operativo?

  - ¿Ha tenido alguna vez una situación en la que se quedó sin un producto fresco inesperadamente durante las horas pico? ¿Qué pasó?

  - ¿Qué herramientas o software utiliza hoy en día para la gestión de inventarios? ¿Es un sistema dedicado, una hoja de cálculo o simplemente lápiz y papel?

  - ¿Qué le gusta de su método actual? ¿Qué le disgusta?

  - ¿Cómo monitoriza el entorno de almacenamiento, como la temperatura en su cámara frigorífica o congelador? ¿Es manual?

  - ¿Quién participa en el proceso de inventario y cuánto tiempo suele llevar cada día o semana?

  - Si una varita mágica pudiera resolver tres de sus problemas de inventario, ¿cuáles serían?

  - ¿Cómo mejoraría su día si pudiera ver la cantidad exacta y la fecha de caducidad de cada artículo en su inventario desde su teléfono o computadora?

  - ¿Y si pudiera recibir alertas automáticas en su teléfono cuando la temperatura de un refrigerador se desvía de un rango seguro o cuando un producto específico está a punto de caducar? ¿Qué tan útil sería eso?

  - ¿Qué valor tendría un informe que predijera sus niveles de desperdicio, ayudándole a tomar decisiones de compra más inteligentes para la próxima semana?

  - Imagine que pudiera escanear un producto cuando llega y que se agregara automáticamente a su inventario digital. ¿Cuánto tiempo le ahorraría eso?

  - ¿Cómo decide cuánto pedir de un artículo perecedero cada semana?

  - Si un sistema pudiera reducir su desperdicio de alimentos en un 20% o más, ¿qué significaría eso para su resultado final?

  - ¿Preferiría un sistema independiente o uno que se integre con otras herramientas que utiliza, como su sistema de punto de venta (TPV)?

  - Para una solución que le ahorra tiempo, reduce el desperdicio y le da tranquilidad, ¿cómo preferiría pagar? ¿Una suscripción mensual, una licencia única o por característica?

  - ¿Cuál sería el siguiente paso para usted si estuviera interesado en una solución como esta?

### 2.2.2. Registro de entrevistas.
- **Primer Segmento:**
  - **Entrevista 1**
    
  <img src="https://raw.githubusercontent.com/AplicacionesWeb-7454/Report/main/assets/img/chapter2/ruddy2.png" alt="ruddy2">
  
  - Link: https://upcedupe-my.sharepoint.com/:v:/g/personal/u20231c895_upc_edu_pe/EXkmlWxS3NpHv9hDBiurNwcBlFnjgQoeZh0RsF828AGlBw?e=jk1iL5&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D
  - Resumen: El entrevistado, Rudy Allan, explica que como jefe de cocina sus principales funciones son la planificación y control del trabajo, la verificación del estado de los alimentos, la capacitación del personal, la elaboración de menús y la supervisión del servicio. La compra de productos depende del número de platos previstos al día, variando entre semana y fines de semana, y el control de existencias se realiza mayormente con compras diarias para garantizar frescura. No usan herramientas digitales ni métodos avanzados para caducidad, sino revisiones manuales. Señala que los problemas de exceso o falta de insumos son frecuentes, y que la coordinación con proveedores se da con pedidos uno o dos días antes, muchas veces por WhatsApp. Para asegurar calidad e higiene se enfocan en verificar los insumos y mantener limpieza constante en el personal y la cocina. Reconoce que herramientas digitales podrían ser útiles en restaurantes grandes, pero en mercados pequeños no suelen implementarse. Finalmente, aconseja a nuevos cocineros tener paciencia y mantener siempre la limpieza como base de un buen trabajo.


<img src="https://raw.githubusercontent.com/AplicacionesWeb-7454/Report/main/assets/img/chapter2/gabriel.png" alt="gabriel">

<br>
-Nombre: Gabriel Perez <br>
-Duracion: 4:46 <br>
-link: https://upcedupe-my.sharepoint.com/:v:/g/personal/u20231c895_upc_edu_pe/ESIjhDORP8FGuPgOT3T3fK0B8Cico_2K69HDn-tLlOBCAQ?e=WqQM2o&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D

  - **Entrevista 2**
  - Resumen: El jefe de cocina Gabriel Pérez organiza y supervisa al equipo, planifica menús y mantiene el orden e higiene, además de coordinar compras e inventario. Actualmente controla existencias con hojas de cálculo y conteos físicos, aunque reconoce que el sistema es manual y poco actualizado. Usa etiquetas y el método PEPS para fechas de vencimiento, pero sin alertas automáticas, lo que genera pérdidas frecuentes por exceso o escasez de insumos. La coordinación con proveedores es manual, vía WhatsApp o llamadas. Para garantizar calidad revisan color, olor y temperatura, y cumplen protocolos básicos de higiene. No utilizan herramientas digitales especializadas, pero considera útiles funciones como registro automático de entradas y salidas, alertas de caducidad, monitoreo de temperatura y reportes de consumo/desperdicio. Destaca que en este rol la paciencia, organización y comunicación con el equipo son claves.


 
- **Segundo Segmento:**
  - **Entrevista 1**
    
<img src="https://raw.githubusercontent.com/AplicacionesWeb-7454/Report/main/assets/img/chapter2/adolfo.png" alt="adolfo">

<br>
-Nombre: Adolfo Choquemamani <br>
-Duración 9:57 <br>
-Link: https://upcedupe-my.sharepoint.com/:v:/g/personal/u20231c895_upc_edu_pe/EVUziQ6m9XBPhb2HrK9j5CEBkUQtFc5x-vQDvtKd6nETcQ?e=Mxldvw&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D

  - Resumen: El comerciante maneja su inventario de perecibles de forma manual con un cuaderno y memoria, lo que le genera pérdidas por vencimiento de lácteos y pan, además de quedarse sin stock en horas pico. Su mayor dolor es encontrar el equilibrio entre no traer de más ni de menos, ya que esto afecta sus ventas y genera desperdicio. Le gustaría contar con un sistema sencillo en el celular que le permita registrar automáticamente productos, recibir alertas de caducidad y tener reportes que predigan ventas y desperdicios. Valora la rapidez y bajo costo de su método actual, pero reconoce que pierde tiempo revisando manualmente y que se olvida de productos en el almacén. Ve mucho valor en una solución digital que le ahorre tiempo, reduzca pérdidas y le dé tranquilidad, y estaría dispuesto a pagar una suscripción mensual accesible si realmente le ayuda a organizarse y ahorrar dinero.

- **Entrevista 2**
    
 <img src="https://raw.githubusercontent.com/AplicacionesWeb-7454/Report/main/assets/img/chapter2/entrevista4P.PNG" alt="Entrevista 4P" style="width:auto; height:auto;">
 
  - Nombre: Janeth Chavez
   
  - Inicio: 0:02
     
  - Final: 11:46
     
  - Link : https://upcedupe-my.sharepoint.com/:v:/g/personal/u202316878_upc_edu_pe/EbKhJrwDTxFDuHgwF-VxLAIBVTElY_l2hPki17Y-d_wgsA?
    e=K9UKkX&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D
   
  - Resumen: Janeth Chávez, dueña de un puesto de mercado, gestiona su inventario de productos perecederos (frutas, verduras, lácteos y embutidos) de forma manual, utilizando un cuaderno o su celular para anotar las cantidades y revisando los productos diariamente “al ojo”. Entre sus principales dificultades se encuentran el desperdicio frecuente de mercadería por vencimiento o deterioro, la falta de control preciso de fechas de caducidad y la dificultad para calcular correctamente las cantidades de compra, lo que genera tanto pérdidas económicas como desabastecimiento en días de alta demanda. Además, el monitoreo de la temperatura y el almacenamiento se realiza de manera manual, lo que incrementa el riesgo de deterioro. Aunque valora la simplicidad y el bajo costo de su método actual, reconoce que este sistema le hace perder tiempo y precisión. Janeth muestra interés en adoptar una solución digital que le permita ver el inventario y las fechas de caducidad desde su celular, recibir alertas automáticas ante productos próximos a vencer o cambios de temperatura, e incluso integrar el control de stock con su punto de venta. Considera que una herramienta así reduciría el desperdicio, mejoraría su organización y aumentaría sus ganancias, prefiriendo un modelo de suscripción mensual accesible con la posibilidad de probarlo previamente.

### 2.2.3. Análisis de entrevistas.

Los tres casos entrevistados —dos jefes de cocina y un comerciante minorista de abarrotes— reflejan una realidad común en la gestión de inventarios de alimentos: la predominancia de métodos manuales y una fuerte dependencia de la experiencia personal más que de procesos estandarizados o herramientas tecnológicas. Aunque los contextos de trabajo son distintos, los problemas centrales coinciden y permiten identificar patrones clave.

En el ámbito de restaurantes, tanto Rudy Allan como Gabriel Pérez describen que las compras se hacen en función del menú y la cantidad estimada de comensales, apoyándose en la intuición y la revisión visual de productos. Si bien existe un intento por organizarse con hojas de cálculo o con métodos como PEPS, en la práctica estos registros suelen estar desactualizados o incompletos, lo que provoca errores en la planificación y genera pérdidas por caducidad. La coordinación con proveedores es principalmente reactiva y se maneja por canales informales como WhatsApp o llamadas. Esto deja en evidencia que la toma de decisiones está marcada más por la experiencia del jefe de cocina y la improvisación diaria que por un sistema que garantice precisión y previsión.

Por otro lado, el comerciante de abarrotes ilustra una situación muy similar, aunque en menor escala. Lleva todo en un cuaderno y mucho de memoria, lo que le resulta práctico y barato, pero también riesgoso. Su principal dolor está en los perecibles: lácteos, pan y embutidos, donde el control visual de fechas de vencimiento no siempre es suficiente para evitar pérdidas. Además, enfrenta el dilema constante de traer cantidades exactas: si se pasa, pierde dinero por caducidad; si compra de menos, pierde ventas y clientes. En su caso, la falta de rotación ordenada y el espacio limitado en el almacén agravan la dificultad para mantener un inventario eficiente.

En conjunto, los tres entrevistados evidencian problemáticas comunes:

  - Desperdicio constante de alimentos, principalmente por caducidad o sobrecompra.

  - Falta de precisión en el cálculo de compras, al basarse en intuición o experiencia en lugar de datos objetivos.

  - Carencia de sistemas automatizados, que obliga a gastar tiempo en revisiones manuales y genera margen de error.

  - Dependencia de la memoria y del trabajo individual, lo que aumenta el riesgo de olvidos, inconsistencias y sobrecarga de responsabilidades.

  - Canales de coordinación informales con proveedores, que dificultan planificar a largo plazo.

Al mismo tiempo, los tres muestran disposición a adoptar soluciones digitales siempre que cumplan ciertas condiciones: deben ser fáciles de usar en el celular, no requerir infraestructura costosa (como computadoras o TPV avanzados), ofrecer alertas automáticas sobre caducidad o stock bajo, y generar reportes que permitan anticiparse a la demanda. Además, se valora la posibilidad de ahorrar tiempo en el registro de entradas y salidas y de reducir el desperdicio económico derivado de malas decisiones de compra.

Este análisis confirma que existe una necesidad transversal de digitalización en la gestión de inventarios alimentarios, tanto en restaurantes como en negocios pequeños. La falta de estandarización y control centralizado genera pérdidas de dinero, tiempo y clientes. Aquí surge una oportunidad estratégica para Pandora Fresh: posicionarse como una solución práctica, accesible y flexible que se adapte a distintos niveles de operación (desde un puesto de abarrotes hasta una cocina profesional), resolviendo los problemas de caducidad, optimización de compras y eficiencia en el control diario.

En síntesis, los hallazgos de las entrevistas muestran que la problemática no es aislada ni depende solo del tamaño del negocio, sino que responde a un vacío tecnológico en la forma como se gestionan inventarios perecibles. Si se logra cubrir esta brecha con un sistema sencillo y económico, se puede generar un impacto real en la reducción de desperdicios, la optimización del tiempo de trabajo y la mejora en la rentabilidad de los negocios.

## 2.3. Needfinding.
### 2.3.1. User Personas.

- User Persona 1: Primer Segmento <br>
  La imagen muestra el perfil de Diego Ríos, gerente de un restaurante en Lima. Se destaca su compromiso con la frescura y calidad de los alimentos, su preferencia por procesos artesanales y su búsqueda constante de eficiencia. Incluye sus motivaciones,     objetivos, frustraciones y rasgos de personalidad, lo que lo convierte en una persona clave para entender las necesidades del sector gastronómico local.
  
  <img src="https://raw.githubusercontent.com/AplicacionesWeb-7454/Report/main/assets/img/chapter2/UserPersona1.jpg" alt="User Persona - Diego Ríos" style="max-width:100; height:auto;">

- User Persona 2: Segundo Segmento <br>
  La imagen muestra el perfil de Carlos Díaz, dueño de puestos de mercado en Lima. Refleja su experiencia vendiendo productos frescos, sus motivaciones por mantener calidad y competitividad, y sus frustraciones con pérdidas por productos dañados y falta de herramientas de gestión. También se destacan sus objetivos de mejorar rotación, ventas y equipamiento, junto con rasgos de personalidad que lo muestran como observador, racional y extrovertido. Es una representación clara de un usuario clave en el sector de alimentos frescos.
  
  <img src="https://raw.githubusercontent.com/AplicacionesWeb-7454/Report/main/assets/img/chapter2/UserPersona2.jpg" alt="User Persona - Carlos Diaz" style="max-width:100; height:auto;">

### 2.3.2. User Task Matrix.

- **Segmento 1: Gerentes de Pequeños y Medianos Restaurantes (AS IS)**
  
| Tarea principal                                   | Frecuencia | Importancia |
|---------------------------------------------------|------------|-------------|
| Revisar inventario en libretas o Excel            | Alta       | Alta        |
| Verificar fechas de caducidad manualmente         | Media      | Alta        |
| Revisar cámaras de refrigeración de forma visual  | Alta       | Alta        |
| Registrar compras con boletas o apuntes sueltos   | Media      | Media       |
| Descartar insumos dañados sin registro formal     | Media      | Alta        |
| Elaborar reportes contables a mano o en hojas     | Baja       | Alta        |
  
- **Segmento 2: Dueños de Puestos en Mercados de Abastos (AS IS)**

| Tarea principal                                   | Frecuencia | Importancia |
|---------------------------------------------------|------------|-------------|
| Revisar visualmente el estado de frutas/verduras  | Alta       | Alta        |
| Separar productos malogrados durante la venta     | Alta       | Alta        |
| Ajustar precios según deterioro o exceso de stock | Alta       | Media       |
| Controlar inventario de memoria o en papel        | Media      | Alta        |
| Negociar precios rápidos con clientes             | Alta       | Media       |
| Asumir pérdidas como parte del costo operativo    | Media      | Alta        |

### 2.3.3. User Journey Mapping.

En esta sección se presentan los **User Journey Maps** de los segmentos definidos.  
El objetivo es ilustrar el recorrido end-to-end actual de cada User Persona, mostrando cómo gestionan sus actividades cotidianas relacionadas con el manejo de inventarios de productos perecibles, **sin la existencia de la solución Pandora’s Fresh**. 

- User Journey Mapping 1: Primer Segmento <br>
  La imagen muestra un User Journey Mapping con cinco etapas del proceso operativo en negocios de alimentos, destacando acciones, pensamientos y emociones. Identifica puntos críticos donde la tecnología puede mejorar control, eficiencia y experiencia.
  
  <img src="https://raw.githubusercontent.com/AplicacionesWeb-7454/Report/main/assets/img/chapter2/UserJourneyMapping1.jpg" alt="User Journey Mapping 1" style="max-width:100; height:auto;">

- User Journey Mapping 2: Segundo Segmento <br>
  La imagen muestra un User Journey Mapping de un vendedor minorista, con cinco etapas del día. Refleja acciones, pensamientos y emociones, destacando desafíos como presión, incertidumbre y pérdidas.
  
  <img src="https://raw.githubusercontent.com/AplicacionesWeb-7454/Report/main/assets/img/chapter2/UserJourneyMapping2.jpg" alt="User Journey Mapping 1"  style="max-width:100; height:auto;">
  
### 2.3.4. Empathy Mapping.

- Empathy Mapping 1 <br>
  Empathy Mapping de un cliente gastronómico que revela preocupaciones por costos y calidad, frustraciones por pérdidas y deseos de control y eficiencia.
  <img src="https://raw.githubusercontent.com/AplicacionesWeb-7454/Report/main/assets/img/chapter2/EmpathyMapping1.jpg" alt="Empathy Mapping 1" style="max-width:100; height:auto;">

- Empathy Mapping 2 <br>
  Empathy Mapping de un vendedor agrícola que prioriza volumen sobre calidad, enfrenta pérdidas y busca modernizar su negocio con más control y trazabilidad.
  <img src="https://raw.githubusercontent.com/AplicacionesWeb-7454/Report/main/assets/img/chapter2/EmpathyMapping2.jpg" alt="Empathy Mapping 2" style="max-width:100; height:auto;">
  
## 2.4. Big Picture Event Storming.



## 2.5. Ubiquitous Language.

- **Perishable Goods (Productos perecibles)**: Alimentos con vida útil limitada (frutas, verduras, carnes, lácteos, pescados) que requieren condiciones específicas de almacenamiento para mantener su frescura.  
- **Food Waste (Desperdicio de alimentos)**: Pérdida de productos alimenticios que no llegan a ser consumidos debido a caducidad, deterioro o mala gestión de inventario.  
- **Traceability (Trazabilidad)**: Capacidad de rastrear el origen, almacenamiento y estado de un producto a lo largo de la cadena de suministro.  
- **Inventory Management (Gestión de inventarios)**: Conjunto de prácticas para controlar la entrada, almacenamiento y salida de productos perecibles en restaurantes, mercados o almacenes.  
- **Cold Chain (Cadena de frío)**: Proceso logístico que asegura la conservación de alimentos perecibles a bajas temperaturas desde la producción hasta la venta.  
- **Stock Rotation (Rotación de inventario)**: Método de organización de productos donde los más antiguos se venden o usan primero (ej. método FIFO: First In, First Out).  
- **Shrinkage (Merma)**: Pérdida de valor o cantidad de productos por caducidad, deterioro, manipulación o robo.  
- **Food Safety (Seguridad alimentaria)**: Conjunto de prácticas para garantizar que los alimentos sean seguros para el consumo humano.  
- **Supplier (Proveedor)**: Persona o empresa que abastece a restaurantes o mercados con productos frescos.  
- **Customer Demand (Demanda del cliente)**: Cantidad y tipo de productos que los consumidores esperan encontrar disponibles en condiciones óptimas.  
- **Shelf Life (Vida útil)**: Tiempo durante el cual un producto perecible mantiene sus características de calidad y seguridad para el consumo.  
- **Spoilage (Descomposición/Deterioro)**: Estado en el cual los alimentos pierden frescura y ya no son aptos para la venta o consumo.  
- **Overstocking (Sobreabastecimiento)**: Exceso de inventario que supera la demanda real, generando riesgo de desperdicio.  
- **Understocking (Desabastecimiento)**: Falta de inventario suficiente para cubrir la demanda, ocasionando pérdidas de ventas y clientes insatisfechos.  
- **Quality Control (Control de calidad)**: Procedimientos para evaluar y garantizar que los productos perecibles cumplen con los estándares establecidos de frescura y seguridad.  

---

# **Capítulo III: Requirements Specification**
## 3.1. User Stories.


| User Story ID | Título | Description | Acceptance Criteria | Epic Relacionado |
|---------------|--------|-------------|---------------------|------------------|
| US01 | Navegación clara | Como visitante, quiero un menú claro y visible (Acerca de, Funcionalidades, Beneficiados, etc.), para ubicarme rápido en la página. | **Given** que estoy en cualquier sección de la página, **when** navego por el sitio, **then** el menú debe estar fijo y accesible en todo momento. | EP01 |
| US02 | Acciones rápidas | Como visitante nuevo, quiero ver botones de acción rápida (Acerca de / Descarga), para decidir de inmediato si sigo explorando o bajo la app. | **Given** que ingreso a la página, **when** hago el primer scroll, **then** los botones de acción deben estar visibles. | EP01 |
| US03 | Ver Acerca de Nosotros | Como interesado en la app, quiero conocer la historia, misión, visión, valores y al equipo, para confiar en la propuesta y sentir seguridad en quiénes la desarrollan. | **Given** que accedo a la sección "Acerca de Nosotros", **when** la reviso, **then** debo ver texto e imágenes del equipo. | EP01 |
| US04 | Ver Funcionalidades | Como visitante curioso, quiero ver un listado de funcionalidades explicadas de forma simple y visual, para entender qué puede hacer la app y si se adapta a mi negocio. | **Given** que estoy en la sección de funcionalidades, **when** reviso el contenido, **then** debo ver mínimo 5 funcionalidades clave. | EP01 |
| US05 | Ver Beneficiarios | Como potencial cliente, quiero conocer qué tipos de usuarios se benefician (restaurantes, proveedores, consumidores), para identificarme y validar que la app me sirve. | **Given** que estoy en la sección de beneficiarios, **when** la leo, **then** debo ver ejemplos claros de beneficiarios. | EP01 |
| US06 | Ver Testimonios | Como nuevo visitante, quiero leer testimonios de otros usuarios reales, para ganar confianza en Pandora’s Fresh. | **Given** que estoy en la sección de testimonios, **when** reviso la página, **then** debo ver al menos 3 testimonios de clientes. | EP01 |
| US07 | Ver Preguntas Frecuentes | Como usuario confundido, quiero acceder a una sección de preguntas frecuentes, para resolver mis dudas rápidamente sin contactar soporte. | **Given** que accedo a la sección FAQ, **when** reviso el contenido, **then** debo ver mínimo 5 preguntas frecuentes. | EP01 |
| US08 | Ver Términos y Condiciones | Como cliente responsable, quiero poder revisar los Términos y Condiciones, para conocer mis derechos y obligaciones antes de usar la app. | **Given** que estoy en el footer, **when** busco el enlace, **then** debo poder acceder a los Términos y Condiciones. | EP01 |
| US09 | Formulario de Contacto | Como usuario con dudas o problemas, quiero tener un medio de contacto o feedback, para comunicarme fácilmente con el equipo. | **Given** que estoy en la sección de contacto, **when** lleno el formulario, **then** debo poder ingresar nombre, correo y mensaje. | EP01 |
| US10 | Registrar productos | Como administrador, quiero registrar mis productos perecibles en la app, para llevar un control digital del inventario. | **Given** que accedo al registro de productos, **when** ingreso la información, **then** debo poder guardar nombre, categoría, cantidad y fecha de caducidad. | EP02 |
| US11 | Editar inventario | Como administrador, quiero modificar la información de mis productos, para actualizar datos en caso de cambios. | **Given** que selecciono un producto, **when** lo edito, **then** debo poder actualizar cualquier campo del producto. | EP02 |
| US12 | Eliminar productos | Como administrador, quiero eliminar productos del inventario, para mantener la base de datos limpia y actualizada. | **Given** que selecciono un producto, **when** intento borrarlo, **then** el sistema debe pedirme confirmación antes de eliminarlo. | EP02 |
| US13 | Consultar inventario | Como usuario, quiero ver el estado general del inventario, para conocer disponibilidad y fechas de caducidad. | **Given** que accedo al inventario, **when** lo consulto, **then** debo ver lista filtrada por estado y fecha. | EP02 |
| US14 | Categorizar inventario | Como usuario, quiero organizar los productos por categorías (frutas, carnes, lácteos), para encontrarlos más rápido. | **Given** que tengo productos registrados, **when** los organizo, **then** debo poder asignar y filtrar por categoría. | EP02 |
| US15 | Escaneo de códigos | Como usuario, quiero escanear códigos de barras o QR, para registrar productos más rápido. | **Given** que activo el escáner en la app, **when** escaneo un código, **then** se deben registrar los datos básicos del producto. | EP02 |
| US16 | Monitorear temperatura | Como encargado, quiero ver en tiempo real la temperatura de almacenamiento, para garantizar condiciones seguras. | **Given** que estoy en la sección de monitoreo, **when** reviso la temperatura, **then** debo ver gráficos actualizados cada 5 min. | EP03 |
| US17 | Monitorear humedad | Como encargado, quiero ver en tiempo real los niveles de humedad, para evitar que los productos se deterioren. | **Given** que accedo al monitoreo de humedad, **when** consulto el sistema, **then** debo ver el nivel actual y alertas si supera límites. | EP03 |
| US18 | Conectar sensores IoT | Como administrador, quiero vincular sensores a la app, para registrar automáticamente las condiciones ambientales. | **Given** que tengo un sensor, **when** lo emparejo, **then** la app debe permitir conectarlo con un código único. | EP03 |
| US19 | Historial ambiental | Como usuario, quiero consultar el historial de temperatura y humedad, para analizar tendencias y riesgos. | **Given** que accedo al historial, **when** reviso los registros, **then** debo ver datos de al menos 30 días. | EP03 |
| US20 | Alertas de desconexión | Como usuario, quiero recibir una alerta si un sensor deja de transmitir, para actuar de inmediato. | **Given** que un sensor se desconecta, **when** ocurre la falla, **then** debo recibir notificación por app y correo. | EP03 |
| US21 | Reporte de inventario | Como administrador, quiero generar reportes de inventario actuales, para tomar decisiones informadas. | **Given** que estoy en la sección de reportes, **when** genero uno, **then** debo poder exportarlo en PDF y Excel. | EP04 |
| US22 | Reporte de mermas | Como administrador, quiero reportes de pérdidas, para conocer causas y costos asociados. | **Given** que consulto el módulo de mermas, **when** genero un reporte, **then** debo ver cálculos por fecha y tipo de producto. | EP04 |
| US23 | Reporte de caducidades | Como usuario, quiero ver un listado de productos próximos a vencer, para tomar acciones preventivas. | **Given** que consulto reportes de caducidad, **when** genero el listado, **then** debo ver productos con menos de 5 días de vida útil. | EP04 |
| US24 | Exportar reportes | Como administrador, quiero exportar mis reportes a formatos estándar, para compartirlos fácilmente. | **Given** que genero un reporte, **when** lo exporto, **then** debo obtenerlo en PDF, Excel y CSV. | EP04 |
| US25 | Dashboard general | Como gerente, quiero ver un tablero con métricas clave, para tener un panorama rápido del inventario. | **Given** que accedo al dashboard, **when** lo consulto, **then** debo ver inventario total, pérdidas y alertas. | EP04 |
| US26 | Alertas por caducidad | Como usuario, quiero recibir notificaciones de productos próximos a vencer, para evitar pérdidas. | **Given** que un producto está por vencer, **when** falten 3 días, **then** debo recibir la alerta. | EP05 |
| US27 | Alertas por temperatura | Como usuario, quiero recibir alertas cuando la temperatura esté fuera de rango, para proteger mis productos. | **Given** que la temperatura sale del rango, **when** ocurre, **then** debo recibir alerta push inmediata. | EP05 |
| US28 | Alertas por humedad | Como usuario, quiero recibir alertas de humedad fuera de rango, para evitar deterioro. | **Given** que el nivel de humedad cambia, **when** supera el límite, **then** debo recibir notificación en tiempo real con el valor exacto. | EP05 |
| US29 | Alertas personalizadas | Como usuario, quiero configurar mis propios rangos de alertas, para adaptarlas a mis necesidades. | **Given** que accedo a la configuración de alertas, **when** ajusto los umbrales, **then** debo poder personalizar cada producto. | EP05 |
| US30 | Notificaciones por correo | Como usuario, quiero recibir notificaciones también en mi correo, para no depender solo del celular. | **Given** que tengo correo registrado, **when** se genera una alerta, **then** debo recibirla en tiempo real en mi bandeja. | EP05 |
| US31 | Registro de cuenta | Como nuevo usuario, quiero registrarme en la app con correo y contraseña, para empezar a usar Pandora’s Fresh. | **Given** que ingreso mis datos, **when** intento registrarme, **then** el sistema debe validar correo único y contraseña segura. | EP06 |
| US32 | Iniciar sesión | Como usuario, quiero acceder con mis credenciales, para entrar a mi cuenta personal. | **Given** que tengo cuenta creada, **when** ingreso correo y contraseña correctos, **then** debo poder iniciar sesión. | EP06 |
| US33 | Cierre de sesión | Como usuario, quiero poder cerrar sesión, para proteger mi información en dispositivos compartidos. | **Given** que estoy logueado, **when** cierro sesión, **then** debo ser redirigido a la pantalla principal. | EP06 |
| US34 | Recuperar contraseña | Como usuario, quiero recuperar mi contraseña en caso de olvido, para volver a acceder a mi cuenta. | **Given** que olvidé mi contraseña, **when** solicito recuperación, **then** debo recibir un correo con enlace para restablecerla. | EP06 |
| US35 | Editar perfil | Como usuario, quiero actualizar mis datos personales, para mantener mi información vigente. | **Given** que estoy en mi perfil, **when** edito mis datos, **then** debo poder modificar nombre, correo y contraseña. | EP06 |
| US36 | Roles de usuario | Como administrador, quiero asignar roles (admin, empleado), para controlar accesos en la app. | **Given** que gestiono usuarios, **when** asigno un rol, **then** el sistema debe limitar funciones según el rol asignado. | EP06 |
| US37 | Recordar sesión | Como usuario frecuente, quiero mantener mi sesión activa, para no loguearme cada vez. | **Given** que ingreso a la app, **when** selecciono "recordarme", **then** mi sesión debe mantenerse iniciada. | EP06 |
| US38 | Borrar cuenta | Como usuario, quiero eliminar mi cuenta de forma permanente, para dejar de usar el servicio. | **Given** que decido borrar mi cuenta, **when** confirmo la acción, **then** el sistema debe eliminarla y avisar consecuencias. | EP06 |
| US39 | Notificación de login | Como usuario, quiero recibir un correo cuando alguien inicie sesión en mi cuenta, para detectar accesos no autorizados. | **Given** que se inicia sesión en mi cuenta, **when** ocurre, **then** debo recibir un correo en menos de 5 min. | EP06 |
| US40 | Registro con Google | Como usuario, quiero registrarme usando mi cuenta Google, para acelerar el proceso de acceso. | **Given** que estoy en el registro, **when** selecciono Google, **then** debo poder acceder mediante OAuth. | EP06 |
| US41 | Integración móvil | Como usuario, quiero acceder desde mi celular, para gestionar inventario en cualquier lugar. | **Given** que uso la app móvil, **when** la instalo, **then** debe funcionar en Android e iOS. | EP02 |
| US42 | Multidispositivo | Como usuario, quiero usar la app en varios dispositivos, para tener sincronización en tiempo real. | **Given** que accedo desde distintos dispositivos, **when** hago cambios, **then** estos deben reflejarse en todos. | EP02 |
| US43 | Vista rápida | Como usuario, quiero ver un resumen rápido del inventario en el inicio, para ahorrar tiempo. | **Given** que entro al inicio, **when** lo reviso, **then** debo ver estado general y alertas recientes. | EP02 |
| US44 | Filtros avanzados | Como usuario, quiero aplicar filtros avanzados (categoría, estado, caducidad), para encontrar productos fácilmente. | **Given** que estoy en el inventario, **when** aplico filtros, **then** los resultados deben mostrarse de inmediato. | EP02 |
| US45 | Buscador inteligente | Como usuario, quiero buscar productos por nombre o código, para ubicar rápidamente ítems. | **Given** que estoy en la lista de productos, **when** uso el buscador, **then** debo ver resultados en menos de 2 segundos. | EP02 |
| US46 | Reporte mensual automático | Como administrador, quiero recibir un reporte mensual automático de inventario y pérdidas, para planificar mejor. | **Given** que llega fin de mes, **when** se genera el reporte, **then** debo recibirlo automáticamente en PDF. | EP04 |
| US47 | Compartir reportes | Como gerente, quiero compartir reportes con mis socios, para mantenerlos informados. | **Given** que tengo un reporte, **when** lo envío, **then** debo poder mandarlo por correo desde la app. | EP04 |
| US48 | Alertas de energía | Como usuario, quiero recibir alertas cuando haya cortes de energía, para prevenir pérdida de productos. | **Given** que ocurre un corte de energía, **when** se detecta, **then** debo recibir notificación en menos de 1 min. | EP05 |
| US49 | Registro por invitación | Como administrador, quiero invitar a empleados a registrarse en la app, para que accedan a sus funciones. | **Given** que quiero registrar un empleado, **when** genero una invitación, **then** el invitado debe recibir un correo con link único. | EP06 |
| US50 | Confirmación de acciones críticas | Como usuario, quiero que la app me pida confirmación en acciones críticas (eliminar producto, borrar cuenta), para evitar errores. | **Given** que intento realizar una acción crítica, **when** la confirmo, **then** el sistema debe mostrar ventana de confirmación antes de ejecutarla. | EP06 |
| TS1 | Backend User Management | Implementación de los servicios backend para la gestión de usuarios: registro, login, recuperación de contraseña, roles, sesiones y seguridad. | **Given** que el backend está activo, **when** se reciben solicitudes de gestión de usuarios, **then** el sistema debe validar datos, manejar autenticación y devolver respuestas correctas. | EP06 |
| TS2 | Backend Inventory | Desarrollo del backend para CRUD de productos, filtros avanzados, categorización, escaneo y vista rápida de inventario. | **Given** que se envían solicitudes al inventario, **when** se procesa información, **then** el backend debe registrar, editar, eliminar, consultar y filtrar datos correctamente. | EP02 |
| TS3 | Backend IoT-Monitoring | Implementación del backend para sensores IoT: lectura de temperatura/humedad, vinculación de sensores, historial y alertas por desconexión. | **Given** que un sensor transmite datos, **when** llegan al backend, **then** deben almacenarse, procesarse y generar alertas si corresponde. | EP03 |
| TS4 | Backend Reporting & Analytics | Backend para generación de reportes, cálculos , exportación (PDF/Excel/CSV), automatización mensual y dashboard analítico. | **Given** que se solicita un reporte, **when** el backend procesa los datos, **then** debe generar el archivo solicitado y enviarlo correctamente. | EP04 |
| TS5 | Alerts & Notifications Backend | Backend para envío de alertas por  caducidad y notificaciones push personalizadas. | **Given** que ocurre un evento crítico, **when** se detecta en el backend, **then** debe enviar la alerta correspondiente por los canales configurados. | EP05 |


- Epicas:
  
| Epic ID | Título | Descripción |
|---------|--------|-------------|
| EP01 | Landing Page | Asegura que los visitantes comprendan rápidamente el propósito de Pandora’s Fresh a través de una página clara, atractiva y funcional. |
| EP02 | Gestión de Inventario | Permite a los usuarios registrar, organizar y consultar productos perecibles, con datos como cantidades, fechas de caducidad y condiciones de almacenamiento. |
| EP03 | Monitoreo en Tiempo Real | Habilita el control constante de variables críticas (temperatura, humedad) mediante sensores IoT conectados a la plataforma. |
| EP04 | Reportes y Trazabilidad | Genera reportes automáticos sobre estado del inventario, mermas y causas, asegurando la trazabilidad de los productos perecibles. |
| EP05 | Notificaciones y Alertas | Envía alertas proactivas sobre riesgos en inventario (caducidad cercana, cambios ambientales) para reducir desperdicio y pérdidas. |
| EP06 | Registro y Gestión de Usuarios | Permite a los usuarios crear cuentas, iniciar sesión y gestionar su perfil, garantizando experiencias personalizadas y seguras. |


  
## 3.2. Impact Mapping.

<img src="https://raw.githubusercontent.com/AplicacionesWeb-7454/Report/main/assets/img/chapter3/ImpactMapping.png" alt="ImpactMapping" style="max-width:100; height:auto;">

## 3.3. Product Backlog.

| #Orden | User Story ID | Descripción | Story Point(1/3/5/8) |
|--------|---------------|-------------|-------------|
| 1 | US01 | Como visitante, quiero un menú claro y visible (Acerca de, Funcionalidades, Beneficiados, etc.), para ubicarme rápido en la página. | 3 |
| 2 | US02 | Como visitante nuevo, quiero ver botones de acción rápida (Acerca de / Descarga), para decidir de inmediato si sigo explorando o bajo la app. | 3 |
| 3 | US03 | Como interesado en la app, quiero conocer la historia, misión, visión, valores y al equipo, para confiar en la propuesta y sentir seguridad en quiénes la desarrollan. | 5 |
| 4 | US04 | Como visitante curioso, quiero ver un listado de funcionalidades explicadas de forma simple y visual, para entender qué puede hacer la app y si se adapta a mi negocio. | 5 |
| 5 | US05 | Como potencial cliente, quiero conocer qué tipos de usuarios se benefician (restaurantes, proveedores, consumidores), para identificarme y validar que la app me sirve. | 3 |
| 6 | US06 | Como nuevo visitante, quiero leer testimonios de otros usuarios reales, para ganar confianza en Pandora’s Fresh. | 3 |
| 7 | US07 | Como usuario confundido, quiero acceder a una sección de preguntas frecuentes, para resolver mis dudas rápidamente sin contactar soporte. | 3 |
| 8 | US08 | Como cliente responsable, quiero poder revisar los Términos y Condiciones, para conocer mis derechos y obligaciones antes de usar la app. | 2 |
| 9 | US09 | Como usuario con dudas o problemas, quiero tener un medio de contacto o feedback, para comunicarme fácilmente con el equipo. | 3 |
| 10 | US10 | Como administrador, quiero registrar mis productos perecibles en la app, para llevar un control digital del inventario. | 5 |
| 11 | US11 | Como administrador, quiero modificar la información de mis productos, para actualizar datos en caso de cambios. | 3 |
| 12 | US12 | Como administrador, quiero eliminar productos del inventario, para mantener la base de datos limpia y actualizada. | 3 |
| 13 | US13 | Como usuario, quiero ver el estado general del inventario, para conocer disponibilidad y fechas de caducidad. | 5 |
| 14 | US14 | Como usuario, quiero organizar los productos por categorías (frutas, carnes, lácteos), para encontrarlos más rápido. | 3 |
| 15 | US15 | Como usuario, quiero escanear códigos de barras o QR, para registrar productos más rápido. | 8 |
| 16 | US16 | Como encargado, quiero ver en tiempo real la temperatura de almacenamiento, para garantizar condiciones seguras. | 8 |
| 17 | US17 | Como encargado, quiero ver en tiempo real los niveles de humedad, para evitar que los productos se deterioren. | 8 |
| 18 | US18 | Como administrador, quiero vincular sensores a la app, para registrar automáticamente las condiciones ambientales. | 8 |
| 19 | US19 | Como usuario, quiero consultar el historial de temperatura y humedad, para analizar tendencias y riesgos. | 5 |
| 20 | US20 | Como usuario, quiero recibir una alerta si un sensor deja de transmitir, para actuar de inmediato. | 5 |
| 21 | US21 | Como administrador, quiero generar reportes de inventario actuales, para tomar decisiones informadas. | 5 |
| 22 | US22 | Como administrador, quiero reportes de pérdidas, para conocer causas y costos asociados. | 5 |
| 23 | US23 | Como usuario, quiero ver un listado de productos próximos a vencer, para tomar acciones preventivas. | 3 |
| 24 | US24 | Como administrador, quiero exportar mis reportes a formatos estándar, para compartirlos fácilmente. | 5 |
| 25 | US25 | Como gerente, quiero ver un tablero con métricas clave, para tener un panorama rápido del inventario. | 8 |
| 26 | US26 | Como usuario, quiero recibir notificaciones de productos próximos a vencer, para evitar pérdidas. | 3 |
| 27 | US27 | Como usuario, quiero recibir alertas cuando la temperatura esté fuera de rango, para proteger mis productos. | 5 |
| 28 | US28 | Como usuario, quiero recibir alertas de humedad fuera de rango, para evitar deterioro. | 5 |
| 29 | US29 | Como usuario, quiero configurar mis propios rangos de alertas, para adaptarlas a mis necesidades. | 5 |
| 30 | US30 | Como usuario, quiero recibir notificaciones también en mi correo, para no depender solo del celular. | 3 |
| 31 | US31 | Como nuevo usuario, quiero registrarme en la app con correo y contraseña, para empezar a usar Pandora’s Fresh. | 5 |
| 32 | US32 | Como usuario, quiero acceder con mis credenciales, para entrar a mi cuenta personal. | 3 |
| 33 | US33 | Como usuario, quiero poder cerrar sesión, para proteger mi información en dispositivos compartidos. | 2 |
| 34 | US34 | Como usuario, quiero recuperar mi contraseña en caso de olvido, para volver a acceder a mi cuenta. | 3 |
| 35 | US35 | Como usuario, quiero actualizar mis datos personales, para mantener mi información vigente. | 3 |
| 36 | US36 | Como administrador, quiero asignar roles (admin, empleado), para controlar accesos en la app. | 5 |
| 37 | US37 | Como usuario frecuente, quiero mantener mi sesión activa, para no loguearme cada vez. | 2 |
| 38 | US38 | Como usuario, quiero eliminar mi cuenta de forma permanente, para dejar de usar el servicio. | 3 |
| 39 | US39 | Como usuario, quiero recibir un correo cuando alguien inicie sesión en mi cuenta, para detectar accesos no autorizados. | 3 |
| 40 | US40 | Como usuario, quiero registrarme usando mi cuenta Google, para acelerar el proceso de acceso. | 5 |
| 41 | US41 | Como usuario, quiero acceder desde mi celular, para gestionar inventario en cualquier lugar. | 8 |
| 42 | US42 | Como usuario, quiero usar la app en varios dispositivos, para tener sincronización en tiempo real. | 8 |
| 43 | US43 | Como usuario, quiero ver un resumen rápido del inventario en el inicio, para ahorrar tiempo. | 5 |
| 44 | US44 | Como usuario, quiero aplicar filtros avanzados (categoría, estado, caducidad), para encontrar productos fácilmente. | 5 |
| 45 | US45 | Como usuario, quiero buscar productos por nombre o código, para ubicar rápidamente ítems. | 5 |
| 46 | US46 | Como administrador, quiero recibir un reporte mensual automático de inventario y pérdidas, para planificar mejor. | 5 |
| 47 | US47 | Como gerente, quiero compartir reportes con mis socios, para mantenerlos informados. | 3 |
| 48 | US48 | Como usuario, quiero recibir alertas cuando haya cortes de energía, para prevenir pérdida de productos. | 5 |
| 49 | US49 | Como administrador, quiero invitar a empleados a registrarse en la app, para que accedan a sus funciones. | 5 |
| 50 | US50 | Como usuario, quiero que la app me pida confirmación en acciones críticas (eliminar producto, borrar cuenta), para evitar errores. | 3 |
| 51 | TS01 | Implementación de los servicios backend para la gestión de usuarios: registro, login, recuperación de contraseña, roles, sesiones y seguridad. | 8 |
| 52 | TS02 | Desarrollo del backend para CRUD de productos, filtros avanzados, categorización, escaneo y vista rápida de inventario. | 8 |
| 53 | TS03 | Backend para sensores IoT: lectura de temperatura/humedad, vinculación, historial y alertas por desconexión. | 8 |
| 54 | TS04 | Backend para reportes, cálculos, exportación (PDF/Excel/CSV), automatización mensual y dashboard analítico. | 8 |
| 55 | TS05 | Backend para envío de alertas por caducidad y notificaciones push personalizadas. | 5 |

- Link Trello: https://trello.com/invite/b/68e82dc4aa24c7aadbc4cc21/ATTI0f71e2d868b5d516dd4b989004bb7a9348800ED5/kanban-template
  
<img src="https://raw.githubusercontent.com/AplicacionesWeb-7454/Report/main/assets/img/chapter3/Trello1.PNG" alt="Trello1.PNG" style="max-width:100; height:auto;">


---

# **Capítulo IV: Product Design**
## 4.1. Style Guidelines.
En la realización de este capitulo, abordaremos el diseño integral de la startup, cubriendo aspectos clave como el estilo visual, los diagramas C4 para la arquitectura del sistema, los diagramas de clases, y los modelos de base de datos, proporcionando una visión clara y estructurada de la infraestructura y el funcionamiento del proyecto.
# **CAPÍTULO IV: PRODUCT DESIGN**
## 4.1. Style Guidelines
En esta sección, presentaremos el concepto de diseño para la página web y la aplicación, de modo que nuestros usuarios tengan una interfaz amigable y funcional. Con este propósito, hemos optado por utilizar elementos visuales que sean amigables y atractivos a la vista.

### 4.1.1. General Style Guidelines
Nuestra paleta de colores se ha diseñado para reflejar la frescura, confiabilidad y modernidad que representa Pandora's Fresh en la gestión de productos perecibles. Los colores seleccionados transmiten profesionalismo, claridad y la esencia de frescura que caracteriza a nuestra marca.

Chromatic Colors
#1cb4d4 (Azul Confianza - Secundario)
Este azul vibrante representa confianza y profesionalismo, ideal para elementos interactivos como botones y llamadas a la acción. Transmite la seriedad y eficiencia que los usuarios esperan de una herramienta de gestión profesional.

<p align="center"> <img src="https://raw.githubusercontent.com/AplicacionesWeb-7454/Report/main/assets/img/chapter4/colors/1cb4d4.png" style="width:500px; height:auto;"> </p>

#00bab3 (Turquesa Frescura - Acento)
Este tono turquesa evoca frescura y vitalidad, representando perfectamente la naturaleza perecible de los productos que gestionamos. Se utiliza para resaltar acciones importantes y elementos que requieren atención especial.

<p align="center"> <img src="https://raw.githubusercontent.com/AplicacionesWeb-7454/Report/main/assets/img/chapter4/colors/00bab3.png" style="width:500px; height:auto;"> </p>

#071d49 (Azul Profesional - Oscuro)
Un azul marino profundo que aporta seriedad y contraste. Perfecto para encabezados y elementos que requieren jerarquía visual, transmitiendo la confiabilidad y seguridad que ofrece nuestra plataforma.

<p align="center"> <img src="https://raw.githubusercontent.com/AplicacionesWeb-7454/Report/main/assets/img/chapter4/colors/071d49.png" style="width:500px; height:auto;"> </p>

Background Colors
#ccedfc (Azul Claridad - Primario)
Un azul claro que sugiere transparencia y claridad en la gestión de productos. Funciona como fondo principal, creando una sensación de limpieza y espacio que facilita la visualización de la información.

<p align="center"> <img src="https://raw.githubusercontent.com/AplicacionesWeb-7454/Report/main/assets/img/chapter4/colors/ccedfc.png" style="width:500px; height:auto;"> </p>

#ffffff (Blanco Pureza - Luz)
Blanco puro que representa la pureza e higiene necesaria en el manejo de productos perecibles. Se utiliza como fondo secundario y para elementos que necesitan máximo contraste.

<p align="center"> <img src="https://raw.githubusercontent.com/AplicacionesWeb-7454/Report/main/assets/img/chapter4/colors/ffffff.jpg" style="width:500px; height:auto;"> </p>
**Typography: Sans Serif**

Utilizamos dos familias tipográficas que complementan perfectamente los valores de Pandora's Fresh:

Big Shoulders
Una tipografía condensada y moderna que aporta fuerza y presencia visual. Ideal para titulares y elementos que requieran impacto.

<p align="center"> <div style="font-family: 'Big Shoulders', sans-serif; font-size: 36px; font-weight: 700; color: #071d49;"> Big Shoulders - Impacto Visual </div> </p>
Montserrat
Una tipografía sans-serif limpia y altamente legible, perfecta para textos largos y contenido de interfaz.

### Jerarquía tipográfica:

Big Shoulders Bold (700): Títulos principales y encabezados destacados

Big Shoulders Medium (500): Subtítulos y elementos de navegación

Montserrat Regular (400): Cuerpo de texto principal

Montserrat Light (300): Textos secundarios y descripciones

### 4.1.3. Iconography
El logotipo de Pandora's Fresh representa perfectamente nuestra esencia:

<p align="center"> <img src="https://raw.githubusercontent.com/AplicacionesWeb-7454/Report/main/assets/img/chapter4/pandora-removebg-preview.png" alt="Pandora's Fresh Logo" style="width:300px; height:auto;"> </p>
El diseño del logotipo combina elementos modernos y orgánicos que comunican:

Frescura: Las líneas fluidas y orgánicas representan productos frescos y naturales

Tecnología: La tipografía moderna y estructurada refleja nuestro enfoque tecnológico

Confianza: La combinación equilibrada transmite profesionalismo y confiabilidad

### 4.1.4. Component Styles
Botones
Botón primario: Fondo #1cb4d4, texto blanco, bordes redondeados de 8px

Botón secundario: Fondo transparente, borde #1cb4d4 2px, texto #1cb4d4

Botón de acento: Fondo #00bab3, texto blanco, para acciones destacadas

### Tarjetas
Sombra suave (0 4px 12px rgba(7, 29, 73, 0.1)), fondo blanco, bordes redondeados de 12px, y uso estratégico de colores de la paleta.

### Formularios
Campos con bordes sutiles (#ccedfc), etiquetas en #071d49 con Montserrat Medium, y focos destacados con borde #00bab3.

### 4.1.5. Uso de Espacios y Layout
Sistema de rejilla de 12 columnas con espaciado consistente basado en múltiplos de 8px:

Margen entre secciones: 64px

Padding interno: 24px

Espaciado entre elementos: 16px

Radio de bordes: 8px

Esta guía de estilos asegura una experiencia coherente y profesional en toda la plataforma Pandora's Fresh, reforzando los valores de confiabilidad, frescura y eficiencia que representamos.


### 4.1.2. Web Style Guidelines

Las guías de estilo web de Pandora's Fresh han sido desarrolladas con el objetivo de ofrecer una experiencia óptima y coherente en todos los dispositivos. Nuestra plataforma está diseñada bajo los principios del Web Responsive Design, lo que garantiza que cada elemento de la interfaz se adapte fluidamente a distintos tamaños de pantalla, desde teléfonos móviles hasta monitores de escritorio.

Uno de los pilares visuales de nuestra interfaz es la implementación del patrón de diseño en forma de Z, el cual guía de manera intuitiva la mirada del usuario a lo largo de la página. Este flujo comienza en la esquina superior izquierda, atraviesa el contenido principal y finaliza en la esquina inferior derecha.

Este recorrido natural permite que la navegación sea clara y eficiente, facilitando el acceso a información clave como monitoreo de productos, alertas de caducidad y gestión de inventarios. El diseño adaptable y el uso estratégico del patrón en Z aseguran que, sin importar el dispositivo utilizado, la experiencia de usuario sea constante y centrada en las necesidades de restaurantes, mercados y proveedores.

Estas directrices no solo definen la estética de Pandora's Fresh, sino que también refuerzan nuestro compromiso con un entorno digital accesible, eficiente y orientado a la optimización de la gestión de productos perecibles.
## 4.2. Information Architecture

### 4.2.1. Organization Systems

- Sistemas de Organización Visual:

Organización secuencial: Se utilizará este tipo de sistema para explicar la información sobre la plataforma web de forma consecutiva. Así el usuario podrá ir conociendo paso a paso el funcionamiento de la aplicación a través del Landing Page, dirigiéndolo a cada sección en orden para conocer desde la introducción de la aplicación web, el equipo que conforma el startup, nuestras funcionalidades, beneficios hasta demostraciones de uso y formas de contacto.

- Esquemas de Categorización de Contenido:

Por tópicos: El diseño de la Landing Page se divide por tópicos que distribuyen los diferentes temas a tratar de nuestra plataforma, presentando cada tópico de manera individual en una sección donde se explicará con detalle la información necesaria para el uso de la plataforma en diferentes aspectos.
### 4.2.2. Labeling Systems

En la Landing Page, se ha hecho uso de etiquetas con un lenguaje sencillo que indican de manera clara al usuario la funcionalidad de cada una:

- Inicio: Muestra información principal y resumida de nuestra aplicación web.

- Acerca de Nosotros: Presenta al equipo y la misión de Pandora's Fresh.

- Funcionalidades: Explica las características principales de la plataforma.

- Beneficiados: Describe los segmentos de usuarios que se benefician de nuestra solución.

- Testimonios: Muestra experiencias de usuarios actuales.

- Soporte: Proporciona acceso a ayuda y contacto.

- Descarga: Incluye botones de descarga para iOS y Android.

- Empezar Ahora: Call to action principal para registro inmediato.

### 4.2.3. SEO Tags and Meta Tags

**Landing Page:** 

- Title: Pandora's Fresh - Gestión Inteligente de Productos Perecibles

- Meta Description: Plataforma de gestión inteligente para productos perecibles que ayuda a restaurantes y mercados a reducir desperdicios y optimizar inventarios.

- Keywords: gestión de inventarios, productos perecibles, reducción de desperdicios, sensores IoT, restaurantes, mercados, alertas de caducidad, optimización de stock

- Author: Turing Almost Completed

### 4.2.4. Searching Systems

**Aplicación Web:** 
Los usuarios registrados tendrán acceso a diferentes sistemas de búsqueda:

- Restaurantes:

Búsqueda de productos por proximidad de caducidad

- Filtrado de inventario por categorías

Búsqueda de alertas y notificaciones

- Mercados y Proveedores:

Búsqueda de productos por estado de frescura

Filtrado por fechas de entrada y salida

Búsqueda de reportes y analytics

### 4.2.5. Navigation Systems

**Landing Page:** La navegación está diseñada para ser intuitiva y eficiente:

Header fijo con menú de navegación principal

Navegación por anclajes a secciones específicas

Menú móvil optimizado para dispositivos táctiles

Botones Call to Action estratégicamente ubicados

Footer completo con enlaces importantes y información de contacto

**Aplicación Web:**

Dashboard personalizado según tipo de usuario

Menú lateral con acceso rápido a todas las funcionalidades

Breadcrumbs para facilitar la navegación contextual

Barra de búsqueda global en todas las secciones

Notificaciones y alertas accesibles desde cualquier pantalla

Esta arquitectura de información asegura que los usuarios puedan encontrar rápidamente lo que necesitan, tanto en la landing page de información como en la aplicación web funcional, manteniendo una experiencia coherente y alineada con los objetivos de negocio de Pandora's Fresh.
## 4.3. Landing Page UI Design.
### 4.3.1. Landing Page Wireframe.
<p align="center">
  <img src="https://raw.githubusercontent.com/AplicacionesWeb-7454/Report/main/assets/img/chapter4/landing1.png" style="width:500px; height:auto;">
</p>
<p align="center">
  <img src="https://raw.githubusercontent.com/AplicacionesWeb-7454/Report/main/assets/img/chapter4/landing2.png" style="width:500px; height:auto;">
</p>
<p align="center">
  <img src="https://raw.githubusercontent.com/AplicacionesWeb-7454/Report/main/assets/img/chapter4/landing3.png" style="width:500px; height:auto;">
</p>
<p align="center">
  <img src="https://raw.githubusercontent.com/AplicacionesWeb-7454/Report/main/assets/img/chapter4/landing4.png" style="width:500px; height:auto;">
</p>
<p align="center">
  <img src="https://raw.githubusercontent.com/AplicacionesWeb-7454/Report/main/assets/img/chapter4/landing5.png" style="width:500px; height:auto;">
</p>
<p align="center">
  <img src="https://raw.githubusercontent.com/AplicacionesWeb-7454/Report/main/assets/img/chapter4/landing6.png" style="width:500px; height:auto;">
</p>
<p align="center">
  <img src="https://raw.githubusercontent.com/AplicacionesWeb-7454/Report/main/assets/img/chapter4/landing7.png" style="width:500px; height:auto;">
</p>
<p align="center">
  <img src="https://raw.githubusercontent.com/AplicacionesWeb-7454/Report/main/assets/img/chapter4/landing8.png" style="width:500px; height:auto;">
</p>
<p align="center">
  <img src="https://raw.githubusercontent.com/AplicacionesWeb-7454/Report/main/assets/img/chapter4/landing9.png" style="width:500px; height:auto;">
</p>

### 4.3.2. Landing Page Mock-up.

<p align="center">
  <img src="https://raw.githubusercontent.com/AplicacionesWeb-7454/Report/main/assets/img/chapter4/MOCK-1.png" style="width:500px; height:auto;">
</p>
<p align="center">
  <img src="https://raw.githubusercontent.com/AplicacionesWeb-7454/Report/main/assets/img/chapter4/Mock-2.png" style="width:500px; height:auto;">
</p>
<p align="center">
  <img src="https://raw.githubusercontent.com/AplicacionesWeb-7454/Report/main/assets/img/chapter4/mock-3.png" style="width:500px; height:auto;">
</p>
<p align="center">
  <img src="https://raw.githubusercontent.com/AplicacionesWeb-7454/Report/main/assets/img/chapter4/mock-4.png" style="width:500px; height:auto;">
</p>
<p align="center">
  <img src="https://raw.githubusercontent.com/AplicacionesWeb-7454/Report/main/assets/img/chapter4/mock-5.png" style="width:500px; height:auto;">
</p>
<p align="center">
  <img src="https://raw.githubusercontent.com/AplicacionesWeb-7454/Report/main/assets/img/chapter4/mock-6.png" style="width:500px; height:auto;">
</p>
<p align="center">
  <img src="https://raw.githubusercontent.com/AplicacionesWeb-7454/Report/main/assets/img/chapter4/mock-7.png" style="width:500px; height:auto;">
</p>
<p align="center">
  <img src="https://raw.githubusercontent.com/AplicacionesWeb-7454/Report/main/assets/img/chapter4/mock-8.png" style="width:500px; height:auto;">
</p>
<p align="center">
  <img src="https://raw.githubusercontent.com/AplicacionesWeb-7454/Report/main/assets/img/chapter4/mock-9.png" style="width:500px; height:auto;">
</p>
<p align="center">
  <img src="https://raw.githubusercontent.com/AplicacionesWeb-7454/Report/main/assets/img/chapter4/mock-10.png" style="width:500px; height:auto;">
</p>

## 4.4. Web Applications UX/UI Design.
### 4.4.1. Web Applications Wireframes.

<p align="center">
  <img src="https://raw.githubusercontent.com/AplicacionesWeb-7454/Report/main/assets/img/chapter4/web-wire1.png" style="width:500px; height:auto;">
</p>
<p align="center">
  <img src="https://raw.githubusercontent.com/AplicacionesWeb-7454/Report/main/assets/img/chapter4/web-wire2.png" style="width:500px; height:auto;">
</p>
<p align="center">
  <img src="https://raw.githubusercontent.com/AplicacionesWeb-7454/Report/main/assets/img/chapter4/web-wire3.png" style="width:500px; height:auto;">
</p>
<p align="center">
  <img src="https://raw.githubusercontent.com/AplicacionesWeb-7454/Report/main/assets/img/chapter4/web-wire4.png" style="width:500px; height:auto;">
</p>
<p align="center">
  <img src="https://raw.githubusercontent.com/AplicacionesWeb-7454/Report/main/assets/img/chapter4/web-wire5.png" style="width:500px; height:auto;">
</p>



### 4.4.2. Web Applications Wireflow Diagrams.
### 4.4.2. Web Applications Mock-ups.

<p align="center">
  <img src="https://raw.githubusercontent.com/AplicacionesWeb-7454/Report/main/assets/img/chapter4/WEB1.png" alt="WEB1" style="width:500px; height:auto;">
</p>

<p align="center">
  <img src="https://raw.githubusercontent.com/AplicacionesWeb-7454/Report/main/assets/img/chapter4/WEB2.png" alt="WEB2" style="width:500px; height:auto;">
</p>

<p align="center">
  <img src="https://raw.githubusercontent.com/AplicacionesWeb-7454/Report/main/assets/img/chapter4/WEB3.png" alt="WEB3" style="width:500px; height:auto;">
</p>

<p align="center">
  <img src="https://raw.githubusercontent.com/AplicacionesWeb-7454/Report/main/assets/img/chapter4/WEB4.png" alt="WEB4" style="width:500px; height:auto;">
</p>

<p align="center">
  <img src="https://raw.githubusercontent.com/AplicacionesWeb-7454/Report/main/assets/img/chapter4/WEB5.png" alt="WEB5" style="width:500px; height:auto;">
</p>

<p align="center">
  <img src="https://raw.githubusercontent.com/AplicacionesWeb-7454/Report/main/assets/img/chapter4/WEB6.png" alt="WEB6" style="width:500px; height:auto;">
</p>

<p align="center">
  <img src="https://raw.githubusercontent.com/AplicacionesWeb-7454/Report/main/assets/img/chapter4/WEB7.png" alt="WEB7" style="width:500px; height:auto;">
</p>

<p align="center">
  <img src="https://raw.githubusercontent.com/AplicacionesWeb-7454/Report/main/assets/img/chapter4/WEB8.png" alt="WEB8" style="width:500px; height:auto;">
</p>


## 4.6. Domain-Driven Software Architecture.
### 4.6.1. Design-Level Event Storming.
<img src="https://raw.githubusercontent.com/AplicacionesWeb-7454/Report/main/assets/img/chapter4/registro%20y%20ges.png">

<img src="https://raw.githubusercontent.com/AplicacionesWeb-7454/Report/main/assets/img/chapter4/monitoreo%20y%20reportes.png">

<img src="https://raw.githubusercontent.com/AplicacionesWeb-7454/Report/main/assets/img/chapter4/notifi.png">

Para mirar mejor nuestro Design-Level EventStorming https://miro.com/app/board/uXjVJ8EOOzw=/?share_link_id=433285595421
### 4.6.2. Software Architecture Context Diagram.

<img src="https://raw.githubusercontent.com/AplicacionesWeb-7454/Report/main/assets/img/chapter4/DiagramContext.jpeg" alt="DiagramContext" style="max-width:100%; margin-bottom:10px;">


### 4.6.3. Software Architecture Container Diagrams.

<img src="https://raw.githubusercontent.com/AplicacionesWeb-7454/Report/main/assets/img/chapter4/DiagramContainer.jpeg" alt="DiagramContainer" style="max-width:100%; margin-bottom:10px;">

### 4.6.4. Software Architecture Components Diagrams.

- Bounded Context Gestion de Usuarios y Accesos
<img src="https://raw.githubusercontent.com/AplicacionesWeb-7454/Report/main/assets/img/chapter4/BC_GestionUsuarios.jpeg" alt="BC_GestionUsuarios" style="max-width:100%; margin-bottom:10px;">

- Bounded Context Gestion de Inventario
<img src="https://raw.githubusercontent.com/AplicacionesWeb-7454/Report/main/assets/img/chapter4/BC_GestionInventario.jpeg" alt="BC_GestionInventario" style="max-width:100%; margin-bottom:10px;">

- Bounded Context Monitoreo IoT
<img src="https://raw.githubusercontent.com/AplicacionesWeb-7454/Report/main/assets/img/chapter4/BC_MonitoreoIoT.jpeg" alt="BC_MonitoreoIoT" style="max-width:100%; margin-bottom:10px;">

- Bounded Context Reportes y Analitica
<img src="https://raw.githubusercontent.com/AplicacionesWeb-7454/Report/main/assets/img/chapter4/BC_ReporteAnalitica.jpeg" alt="BC_ReporteAnalitica" style="max-width:100%; margin-bottom:10px;">

- Bounded Context Alertas y Notificaciones
<img src="https://raw.githubusercontent.com/AplicacionesWeb-7454/Report/main/assets/img/chapter4/BC_AlertasNotificaciones.jpeg" alt="BC_AlertasNotificaciones" style="max-width:100%; margin-bottom:10px;">

## 4.7. Software Object-Oriented Design.
### 4.7.1. Class Diagrams.

<img src="https://raw.githubusercontent.com/AplicacionesWeb-7454/Report/main/assets/img/chapter4/DiagramaClases.png" alt="DiagramaClases" style="max-width:100%; margin-bottom:10px;">

## 4.8. Database Design.
### 4.8.1. Database Diagrams.

<img src="https://raw.githubusercontent.com/AplicacionesWeb-7454/Report/main/assets/img/chapter4/DataBaseDiagram.png" alt="DataBaseDiagram" style="max-width:100%; margin-bottom:10px;">


---

# **Capítulo V: Product Implementation, Validation & Deployment**
## 5.1. Software Configuration Management.
### 5.1.1. Software Development Environment Configuration.
| Tipo de Actividad       | Herramienta / Producto | URL                                | Motivos de uso                                                                 |
|--------------------------|-------------------------|------------------------------------|--------------------------------------------------------------------------------|
| UX/UI Design             | Figma                  | https://www.figma.com/es-la        | Realizar los diseños de interfaz y de experiencia de usuario para nuestra solución. |
| Desarrollo de Software   | VS Code                | https://code.visualstudio.com      | Desarrollar la Landing Page de nuestra solución.                                |
| Documentación            | GitHub                 | https://github.com                 | Realizar la documentación de nuestra propuesta.                                 |
| Gestión de Requisitos    | Miro                    | https://miro.com/                | Para organizar, colaborar y realizar un seguimiento del trabajo de manera eficiente. |
| Reuniones                | Discord                | https://discord.com/               | Reuniones con el equipo.                                                        |
### 5.1.2. Source Code Management.
**Link Repositorio Report**

Link: https://github.com/AplicacionesWeb-7454/Report.git

**Link Repositorio Landing**

Link: https://github.com/AplicacionesWeb-7454/LandingPage.git


**Workflow – GitFlow**

Se implementará el modelo **GitFlow** para el manejo de ramas:

- **main**: rama principal, contiene solo versiones estables listas para producción.
- **develop**: rama de integración, donde se juntan las nuevas funcionalidades antes de liberar una versión.
- **feature/***: cada nueva funcionalidad tendrá su propio branch.
    - Ejemplo: feature/login-auth
- **release/***: rama usada para preparar una nueva versión antes de pasar a producción.
    - Ejemplo: release/1.0.0
- **hotfix/***: ramas para corregir errores críticos en producción.
    - Ejemplo: hotfix/fix-login-bug


**Versionado**

Se aplicará **Semantic Versioning (SemVer 2.0.0):**

- **Formato**: MAJOR.MINOR.PATCH
- **Ejemplo**: v1.2.3

### Significado:
- **MAJOR**: cambios incompatibles.
- **MINOR**: nuevas funcionalidades sin romper compatibilidad.
- **PATCH**: corrección de bugs.


**Commits**

Se utilizarán los estándares de **Conventional Commits**:

- **feat**: nueva funcionalidad.
- **fix**: corrección de bug.
- **docs**: cambios en documentación.
- **style**: cambios de formato (no afectan código).
- **refactor**: cambios internos sin alterar funcionalidad.
- **test**: pruebas añadidas o corregidas.
- **chore**: tareas de mantenimiento.
### 5.1.3. Source Code Style Guide & Conventions.
- HTML
    - "p" Utiliza esta etiqueta para dividir el texto en párrafos.
    - "a" Permite crear enlaces hacia otras páginas web.
    - "ul" Crea una lista no ordenada (sin numeración).
    - "li" Define cada elemento dentro de una lista.
    - "meta" Se incluye en la sección de encabezado del HTML y no es visible en la página.
    - "h1" Indica el encabezado más importante del contenido.
    - "div" Agrupa diferentes secciones de contenido.

- CSS
    - width: Define el ancho de un elemento.
    - height: Establece el alto de un elemento.
    - padding: Crea espacio interno entre el borde y el contenido.
    - font-family: Determina el tipo de fuente.
    - font-size: Ajusta el tamaño de la fuente.
    - font-weight: Controla el grosor o peso de la fuente.
    - font-style: Configura el estilo de la fuente (normal, cursiva, etc.).
    - text-align: Alinea el texto según lo especificado (izquierda, centro, derecha).
    - color: Aplica color al texto o al borde del elemento.
    - background-color: Define el color de fondo del elemento.

### 5.1.4. Software Deployment Configuration.

**Entorno de Desarrollo:**

Tecnologías utilizadas:
- HTML
- CSS
- JavaScript
- Vue (con Vite como empaquetador y servidor de desarrollo)

Gestor de paquetes:
- **npm** para Vue (administración de dependencias y scripts de build).

**Estrategia de Deployment:**
- **GitHub Pages** para desplegar la versión estática del Landing Page.
- **Azure App Services** para desplegar los servicios backend (API RESTful).

**Flujo Gitflow aplicado:**
- `main`: Rama principal de producción.
- `develop`: Rama de integración principal.
- `feature/*`: Desarrollo de nuevas funcionalidades sobre `develop`.
- Pull Requests realizados desde `feature/*` hacia `develop`, y de `develop` hacia `main` al completar un ciclo.



## 5.2. Landing Page, Services & Applications Implementation.
### 5.2.1. Sprint 1
En esta sección, se documentará y explicará, en términos de producto y colaboración, el primer sprint de trabajo.
### 5.2.1.1. Sprint Planning 1.
| **Sprint #**                  | Sprint 1                                                                                                                                                                            |
|--------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Sprint Planning Background** |                                                                                                                                                                                     |
| **Date**                       | 19 de septiembre del 2025                                                                                                                                                           |
| **Time**                       | 18:00 horas                                                                                                                                                                         |
| **Location**                   | Modalidad remota a través de la plataforma Discord                                                                                                                                  |
| **Prepared By**                | Todos los integrantes del equipo Pandoras Fresh                                                                                                                                     |
| **Attendees (to planning meeting)** | Todos los integrantes del equipo Pandoras Fresh                                                                                                                                     |
| **Sprint 0 Review Summary**    | Dado que es nuestro primer sprint de desarrollo, aún no se ha realizado un resumen del sprint anterior.                                                                             |
| **Sprint 0 Retrospective Summary** | No se identificaron mejoras ya que es el primer sprint.                                                                                                                             |
| **Sprint Goal & User Stories** | US01, US02, US03, US04, US05, US06, US07, US08, US09                                                                                                                                |
| **Sprint 1 Goal**              | En este sprint, nuestro enfoque está en describir nuestra startup y en construir la estructura de la Landing Page, realizar las entrevisas, y tener definidos nuestros user stories |
| **Sprint 1 Velocity**          | 5                                                                                                                                                                                   |
| **Sum of Story Points**        | 5                                                                                                                                                                                   
### 5.2.1.2. Aspect Leaders and Collaborators.
| Team Member (Last Name, First Name) | Github Username | Elaboracion de User Stories Leader (L), Collaborator (C) | Desarrollo del landing page Leader (L), Collaborator (C) | Descripcion y desarrollo de los primeros capitulos Leader (L), Collaborator (C) |
|-------------------------------------|-----------------| ------------------------------------------------------- |----------------------------------------------------------| -------------------------------------------------- |
| Llamozas, Diego                     | Diego Llamozas  | (C)                                                     | (C)                                                      | (C)                                                |
| Vidal, Jareth                       | Jareth341       | (L)                                                     | (L)                                                      | (C)                                                |
| Chuchon, Jhon                       | JhonChuchon     | (C)                                                     | (C)                                                      | (C)                                                |
| Seminario, Diego                    | DiegoSeminario  | (C)                                                     | (C)                                                      | (C)                                                |
| Mendoza, Alejandro                  | AlexBoo578      |                 (C)                                         | (C)                                                      |        (C)                                  |

### 5.2.1.3. Sprint Backlog 1.
| Sprint # | Sprint 1 |             |                   |                 |                                                |
|----------|---|-------------|-------------------|-----------------|------------------------------------------------|
|          | User Story |             |                   |                 |                                                ||
| Id       | Title | Description | Estimation(hours) | Assigned to     | Status (To-do / In-Process / To-Review / Done) |
| US01     | Navegación clara	  |       Como visitante, quiero un menú claro y visible (Acerca de, Funcionalidades, Beneficiados, etc.), para ubicarme rápido en la página.	      | 4                 | Jareth341       | Done                                           |
| US02     | Acciones rápidas	 |    Como visitante nuevo, quiero ver botones de acción rápida (Acerca de / Descarga), para decidir de inmediato si sigo explorando o bajo la app.	         | 3                 | Diego Llamozas  |          Done                                      |
| US03     | Ver Acerca de Nosotros	 |     Como interesado en la app, quiero conocer la historia, misión, visión, valores y al equipo, para confiar en la propuesta y sentir seguridad en quiénes la desarrollan.	        | 4                 | Jhon Chuchon    |                         Done                       |
| US04     | Ver Funcionalidades	  |    Como visitante curioso, quiero ver un listado de funcionalidades explicadas de forma simple y visual, para entender qué puede hacer la app y si se adapta a mi negocio.	         | 5                 | Diego Seminario |                               Done                 |
| US05     | Ver Beneficiarios	 |      Como potencial cliente, quiero conocer qué tipos de usuarios se benefician (restaurantes, proveedores, consumidores), para identificarme y validar que la app me sirve.	       | 4                 | AlexBoo578      |                                     Done           |
| US06     | Ver Testimonios	 |     Como nuevo visitante, quiero leer testimonios de otros usuarios reales, para ganar confianza en Pandora’s Fresh.	        | 4                 | Jareth341       |                             Done                   |
| US07     | Ver Preguntas Frecuentes	 |       Como usuario confundido, quiero acceder a una sección de preguntas frecuentes, para resolver mis dudas rápidamente sin contactar soporte.	      | 5                 | Diego Llamozas  |                                           Done     |
| US08     | Ver Términos y Condiciones	 |   Como cliente responsable, quiero poder revisar los Términos y Condiciones, para conocer mis derechos y obligaciones antes de usar la app.	          | 5                 | Jhon Chuchon    |                                           Done     |
| US09     | Formulario de Contacto	 |     Como usuario con dudas o problemas, quiero tener un medio de contacto o feedback, para comunicarme fácilmente con el equipo.	        | 4                 | Diego Seminario |                                         Done       |
### 5.2.1.4. Development Evidence for Sprint Review.

En esta sección se presenta la evidencia detallada del desarrollo alcanzado durante el Sprint 1, enfocado en la implementación de la Landing Page de Pandora Fresh. Durante este primer sprint, el equipo  se concentró en establecer los fundamentos técnicos y visuales de la plataforma web que conectará a nuestros usuarios.

Durante este Sprint, el equipo logró avances significativos en la implementación del proyecto. Se completó la estructura y diseño de la landing page, integrando las secciones principales como navegación, testimonios, funcionalidades, formulario de contacto, redes sociales y servicios. Además, se documentaron los commits y ramas utilizados, asegurando trazabilidad y colaboración efectiva entre los miembros del equipo. A continuación, se presenta la evidencia de los principales entregables y contribuciones realizadas durante el Sprint.

| Repository | Branch | Commit Id | Commit Message | Commit Message Body | Commited on (Date) |
|------------|--------|-----------|----------------|--------------------|--------------------|
| PandoraFresh-Report | Chapter1 | a1b2c3d | docs:(chapter-I)"add format of team member profiles" | Added structured format for team member profiles including personal information, skills, and role descriptions for each team member in the startup profile section | 15/09/2025 |
| PandoraFresh-Report | Chapter1 | e4f5g6h | docs(chapter-1):"adding Competitive Analysis Landscape and Strategy and tactis front Rivals "" | Implemented comprehensive competitive analysis section with detailed competitor research, market positioning analysis, and strategic approaches to compete effectively in the market | 16/09/2025 |
| PandoraFresh-Report | Chapter1 | i7j8k9l | docs(chapter-1): add introduction structure for QuizzBee project and finalize Desing interview | Created complete introduction structure for QuizzBee project including startup description, solution profile, and finalized interview design questions for user research | 17/09/2025 |
| PandoraFresh-Report | Chapter2 | m0n1o2p | docs(chapter-II):"add summary of interview" | Added comprehensive summary of conducted interviews including key insights, user feedback analysis, and findings that will inform the product development process | 18/09/2025 |
| PandoraFresh-Report | Chapter2| q3r4s5t | fix(empathymapping): fix empathy map images | Fixed empathy mapping images by correcting display issues, updating broken links, and ensuring proper visualization of user personas and their emotional journey maps | 19/09/2025 |
| PandoraFresh-Report | Chapter2 | u6v7w8x | feat: Update the description on the Product Backlog. | Updated Product Backlog descriptions to align with user stories format, ensuring consistency between narrative descriptions and acceptance criteria across all user stories | 15/09/2025 |
| PandoraFresh-Report | Chapter3 | y9z0a1b | feat: restructure user stories format | Restructured user stories from Given-When-Then format to narrative format using "Como [rol], quiero [objetivo] para [beneficio]" structure for better clarity and consistency | 16/09/2025 |
| PandoraFresh-Report | Chapter3 | c2d3e4f | docs(chapter-III):"add epic with description and title" | Added comprehensive epic stories section with detailed descriptions and titles for each epic, establishing clear connections between user stories and business objectives | 17/09/2025 |
| PandoraFresh-Report | Chapter4 | g5h6i7j | Delete assets/img/chapter-IV/wireframe1.png | Removed outdated wireframe image file that was no longer needed and replaced with updated design mockups that better represent the current UI/UX design approach | 19/09/2025 |
| PandoraFresh-Report | Chapter5 | k8l9m0n | feat: update aspect leaders and collaborators | Updated aspect leaders and collaborators table with current team member assignments, defining clear roles and responsibilities for each sprint activity and deliverable | 20/09/2025 |



### 5.2.1.5. Execution Evidence for Sprint Review.
**Resumen:**

El sprint culminó con la implementación completa de una Landing Page funcional y visualmente atractiva que incorpora todas las características esenciales definidas en las historias de usuario prioritarias. Se estableció una base tecnológica simple pero eficiente

Los principales logros incluyen la implementación exitosa del sistema de internacionalización que permite a los usuarios poder visualizar lo escencial del proyecto, garantizando accesibilidad para nuestros segmentos objetivo. Adicionalmente se desarrollo un boton para que pueda visualizar la web-application

La Landing Page resultante presenta una estructura clara y profesional que comunica efectivamente la propuesta de valor de PandoraFresh . Se implementaron secciones clave como la presentación de servicios principales, explicación del proceso de funcionamiento, características detalladas del producto, e información de contacto con múltiples canales de comunicación.

En este Sprint se logró desplegar la primera versión funcional de la landing page del proyecto, cumpliendo con los objetivos planteados en el backlog. El equipo trabajó de manera colaborativa para implementar y publicar las principales secciones, asegurando una experiencia de usuario coherente y alineada con los requerimientos iniciales. A continuación, se presenta la evidencia visual y el enlace de acceso a la landing page desplegada

Enlace de la Landing Page: <br>
https://pandorafresh.netlify.app

<img src="https://raw.githubusercontent.com/AplicacionesWeb-7454/Report/chapter05-sprint1/assets/img/chapter5/Hero-section.png" alt="HeroSection" style="max-width:100; height:auto;">

### 5.2.1.6. Services Documentation Evidence for Sprint Review.

Para esta entrega no se han empleado APIS, por lo cuál no se he requerido hacer una documentación sobre servicios implementados durante el Sprint

### 5.2.1.7. Software Deployment Evidence for Sprint Review.
Durante este Sprint, el equipo realizó el despliegue exitoso de la landing page utilizando la plataforma Netlify. El objetivo fue asegurar que la solución estuviera disponible en línea para su revisión y validación ,estableciendo un flujo de trabajo automatizado que garantiza la entrega rápida y confiable de nuevas funcionalidades. El proceso de despliegue se diseñó con el objetivo de minimizar el tiempo de inactividad y maximizar la eficiencia del equipo de desarrollo.


Estrategia de Despliegue Implementada:

Se adoptó una arquitectura de despliegue moderno utilizando Netlify como plataforma de hosting, aprovechando sus capacidades de integración continua y entrega continua (CI/CD). Esta elección tecnológica permite despliegues automáticos, rollbacks instantáneos y una infraestructura escalable que se adapta perfectamente a las necesidades del proyecto quizbee.

**Pasos realizados durante el despliegue:**
1. Se creó una cuenta y espacio de trabajo en Netlify para el proyecto.
2. Se conectó el repositorio de la landing page alojado en GitHub con Netlify, permitiendo la integración continua.
3. Se configuró la rama principal del repositorio como fuente de despliegue automático.
4. Se ajustaron las opciones de build y publish para asegurar la correcta generación de archivos estáticos.
5. Se realizó el primer despliegue, verificando que la landing page estuviera accesible públicamente y funcionando correctamente.
6. Se validó el acceso desde diferentes dispositivos y navegadores para garantizar la experiencia de usuario.
7. Se documentó la URL de acceso y se compartió con el equipo para revisión y feedback.
 

**Design:**

Para realizar el diseño de los wireframes y mockups de la Landing Page para este Sprint,
se hizo uso de la plataforma Figma.

1. Se accede a través de la página oficial de Figma: https://www.figma.com/login
   
<img src="https://raw.githubusercontent.com/AplicacionesWeb-7454/Report/main/assets/img/chapter5/figma.png" alt="figma" style="width:auto; height:auto;">

2. Luego, se crea un Draft que nos servirá como base para el proyecto colaborativo.

<img src="https://raw.githubusercontent.com/AplicacionesWeb-7454/Report/main/assets/img/chapter5/figma2.PNG" alt="figma2" style="width:auto; height:auto;">

**Deployment Para la landing page, se utilizará Netlify para el despliegue de la página.**

<img src="https://raw.githubusercontent.com/AplicacionesWeb-7454/Report/main/assets/img/chapter5/deployLanding1.PNG" alt="DeploymentLanding" style="max-width:100; height:auto;">
<img src="https://raw.githubusercontent.com/AplicacionesWeb-7454/Report/main/assets/img/chapter5/deployLanding2.PNG" alt="DeploymentLanding" style="max-width:100; height:auto;">

Para nuestro proyecto se crearon 2 repositorios, el cuál fue:

**Documentación:** 
Link Repositorio: https://github.com/AplicacionesWeb-7454/Report.git

Este repositorio contiene el informe de nuestro proyecto.

**Landing Page:**
- Link Repositorio: https://github.com/AplicacionesWeb-7454/LandingPage.git

Este repositorio se usa para realizar el informe del proyecto de manera continua y subir la landing page.

### 5.2.1.8. Team Collaboration Insights during Sprint.

**Resumen:**
Durante este Sprint, las actividades de implementación se desarrollaron de manera colaborativa y organizada. El equipo utilizó herramientas como GitHub para la gestión de versiones y asignación de tareas, y Discord para la comunicación y coordinación diaria. Cada integrante asumió responsabilidades específicas según el backlog y los aspectos definidos en la planificación, participando activamente en el desarrollo, revisión de código y validación de entregables.

Se promovió la revisión cruzada de avances, el registro de commits detallados y la documentación de los cambios realizados. Las reuniones periódicas permitieron resolver dudas, ajustar prioridades y asegurar que todos los miembros estuvieran alineados con los objetivos del Sprint. Esta dinámica facilitó la integración continua y la entrega oportuna de los resultados esperados.

**Evidencia de Colaboración:**

<img src="https://raw.githubusercontent.com/AplicacionesWeb-7454/Report/main/assets/img/chapter1/CONTRI.PNG" alt="CONTRI" style="width:auto; height:auto;">

### 5.2.2. Sprint 2
En esta sección, se documentará y explicará, en términos de producto y colaboración, el segundo sprint de trabajo:
#### 5.2.2.1. Sprint Planning 2

| **Sprint #**                        | Sprint 2                                                                                              |
|-------------------------------------|-------------------------------------------------------------------------------------------------------|
| **Sprint Planning Background**      |                                                                                                       |
| **Date**                            | 9 de octubre de 2025                                                                                  |
| **Time**                            | 18:00                                                                                                 |
| **Location**                        | Modalidad remota a través de la plataforma Discord                                                    |
| **Prepared By**                     | Todos los integrantes del equipo Pandoras Fresh                                                       |
| **Attendees (to planning meeting)** | Todos los integrantes del equipo Pandoras Fresh                                                       |
| **Sprint 2 Review Summary**         | En el sprint anterior, se realizo los primeros puntos del reporte y la Landing Page                   |
| **Sprint 2 Retrospective Summary**  | Se mejoró gran parte del desarrollo del sprint, dado los conocimientos para desplegar la landing page |
| **Sprint Goal & User Stories**      | US08, US09, US10,US11, US12,US13,US14,US15,US16,US17,US18,US19,US20,US21,US22,US23,US24,US25          |
| **Sprint 2 Goal**                   | El objetivo de este sprint es desplegar el frontend de la aplicación web                              |
| **Sprint 2 Velocity**               | 5                                                                                                     |
| **Sum of Story Points**             | 5                                                                                                     

#### 5.2.2.2 Aspect Leaders and collaborations

| Team Member (Last Name, First Name) | Github Username | Elaboracion de User Stories Leader (L), Collaborator (C) | Desarrollo del landing page Leader (L), Collaborator (C) | Descripcion y desarrollo de los primeros capitulos Leader (L), Collaborator (C) |
|-------------------------------------|-----------------| ------------------------------------------------------- |----------------------------------------------------------| -------------------------------------------------- |
| Llamozas, Diego                     | Diego Llamozas  | (C)                                                     | (C)                                                      | (C)                                                |
| Vidal, Jareth                       | Jareth341       | (L)                                                     | (L)                                                      | (C)                                                |
| Chuchon, Jhon                       | JhonChuchon     | (C)                                                     | (C)                                                      | (C)                                                |
| Seminario, Diego                    | DiegoSeminario  | (C)                                                     | (C)                                                      | (C)                                                |
| Mendoza, Alejandro                  | AlexBoo578      |                 (C)                                         | (C)                                                      |        (C)                                  |

### 5.2.2.3. Sprint Backlog 2

Durante este Sprint, el equipo centró sus esfuerzos en el desarrollo de la capa Frontend de la aplicación, estableciendo las bases visuales y funcionales que interactúan directamente con los usuarios. Se priorizó la implementación de componentes clave asociados a cada uno de los bounded contexts asignados individualmente a los integrantes, lo cual permitió una distribución clara de responsabilidades y un avance paralelo de las funcionalidades. Cada miembro del equipo asumió el liderazgo en el desarrollo de un conjunto específico de componentes, asegurando coherencia y continuidad en cada dominio funcional.

Además, como parte del compromiso con la experiencia del usuario, se implementó una nueva versión de la Landing Page, con un enfoque visual renovado. Esta incluye imágenes representativas de los servicios ofrecidos, buscando captar la atención desde el primer contacto y comunicar de manera más efectiva la propuesta de valor de la plataforma. Esta mejora visual no solo fortalece la identidad de marca, sino que también establece una conexión más directa con las necesidades de los usuarios.

Este es nuestro link de invitación a nuestro Trello : https://trello.com/invite/b/68e82dc4aa24c7aadbc4cc21/ATTI0f71e2d868b5d516dd4b989004bb7a9348800ED5/kanban-template

<img src="https://raw.githubusercontent.com/AplicacionesWeb-7454/Report/main/assets/img/chapter5/sprintback2.PNG" alt="SprintBack" style="width:auto; height:auto;">

| Sprint # | Sprint 2 |
|--------------|--------------|

| **User Story Id** | **User Story Title** | **Task Id** | **Task Title** | **Description** | **Estimation (Hours)** | **Assigned To** | **Status** |
|-------------------|----------------------|--------------|----------------|-----------------|------------------------|-----------------|-------------|
| **US10** | Registrar productos | T-10 | Implementar registro de productos | Permitir registrar productos perecibles con nombre, categoría, cantidad y fecha de caducidad. | 3 | **Jareth Vidal** | Done |
| **US11** | Editar inventario | T-11 | Implementar edición de productos | Habilitar la actualización de datos en productos existentes. | 2 | **Edson Llamosas** | Done |
| **US12** | Eliminar productos | T-12 | Implementar eliminación de productos | Permitir eliminar productos con confirmación previa. | 2 | **Diego Seminario** | Done |
| **US13** | Consultar inventario | T-13 | Implementar visualización del inventario | Mostrar lista general del inventario filtrada por estado y fecha. | 2 | **Alejandro Mendoza** | Done |
| **US14** | Categorizar inventario | T-14 | Implementar categorización de productos | Permitir asignar categorías y filtrar productos según tipo. | 2 | **Jhon Chuuchon** | Done |
| **US15** | Escaneo de códigos | T-15 | Implementar escáner de productos | Permitir registrar productos escaneando código de barras o QR. | 3 | **Jareth Vidal** | Done |
| **US16** | Monitorear temperatura | T-16 | Implementar monitoreo de temperatura | Mostrar temperatura actual y gráficos actualizados cada 5 minutos. | 3 | **Edson Llamosas** | Done |
| **US17** | Monitorear humedad | T-17 | Implementar monitoreo de humedad | Mostrar niveles de humedad con alertas cuando superen límites seguros. | 3 | **Diego Seminario** | Done |
| **US18** | Conectar sensores IoT | T-18 | Implementar conexión de sensores | Permitir emparejar sensores mediante código único para registrar condiciones ambientales. | 3 | **Alejandro Mendoza** | Done |
| **US19** | Historial ambiental | T-19 | Implementar historial ambiental | Mostrar registros de temperatura y humedad de los últimos 30 días. | 2 | **Jhon Chuuchon** | Done |
| **US20** | Alertas de desconexión | T-20 | Implementar alertas de desconexión | Enviar notificación por app y correo si un sensor deja de transmitir datos. | 2 | **Jareth Vidal** | Done |
| **US21** | Reporte de inventario | T-21 | Implementar generación de reportes de inventario | Permitir generar reportes actualizados exportables en PDF y Excel. | 3 | **Edson Llamosas** | Done |
| **US22** | Reporte de mermas | T-22 | Implementar reporte de mermas | Mostrar pérdidas de productos con cálculos por tipo y fecha. | 2 | **Diego Seminario** | Done |
| **US23** | Reporte de caducidades | T-23 | Implementar reporte de caducidades | Mostrar listado de productos próximos a vencer (menos de 5 días). | 2 | **Alejandro Mendoza** | Done |
| **US24** | Exportar reportes | T-24 | Implementar exportación de reportes | Permitir exportar reportes en formatos PDF, Excel y CSV. | 2 | **Jhon Chuuchon** | Done |
| **US25** | Dashboard general | T-25 | Implementar dashboard de control | Mostrar métricas clave del inventario: total, pérdidas y alertas. | 3 | **Jareth Vidal** | Done |

### 5.2.2.4. Development Evidence for Sprint Review

Durante el Sprint se avanzó en la implementación de los siguientes productos: Landing Page, Aplicaciones Web y Servicios Web. A continuación se presenta la evidencia de desarrollo mediante commits registrados en los repositorios utilizados durante este periodo. La tabla incluye el nombre del repositorio, rama de trabajo, identificador del commit, mensaje del commit, descripción detallada del cambio y la fecha en que se realizó.

| Repository | Branch | Commit Id | Commit Message | Commit Message Body | Commited on (Date) |
|------------|--------|-----------|----------------|--------------------|--------------------|
| pandoras-fresh-frontend-official | feature-user | e792f8a | feat(feature-user): bc/user-management  | Implements user management endpoints with updated flow integration. | 7/10/2025 |
| pandoras-fresh-frontend-official | feature-user | 7247e35 | feat(feature-user): update/language | Updates db.json and refactors file structure for consistency. | 7/10/2025 |
| pandoras-fresh-frontend-official | inventory | ba20d49 | feat(views): add box inventory management interfaces | Adds subscription management and payment integration to inventory views. | 26/09/2024 |
| pandoras-fresh-frontend-official | inventory | c4250eb | feat(services): implement box inventory management services | Integrates zone.js for event handling and service enhancements. | 26/09/2024 |
| pandoras-fresh-frontend-official | inventory | 43e03eb | feat(domain): add box-based inventory domain models | Adds core domain models for box inventory with zone.js event support. | 26/09/2024 |
| pandoras-fresh-frontend-official | iot-monitoring | 6005715 | feat: implementa filtrado reactivo por zona y estado en vista de | Adds profile domain entity, controller logic, and Material UI profile component. | 06/09/2024 |
| pandoras-fresh-frontend-official | iot-monitoring | 7a799d2 | feat: implementa filtrado reactivo por zona y estado en vista de | Adds initial user entity for monitoring module. | 07/09/2024 |
| pandoras-fresh-frontend-official | reporting-analytics | 510d178 | feat(reporting-routes): add routing for reporting and analytics views | Adds speaking repository service for analytics workflow. | 07/09/2024 |
| pandoras-fresh-frontend-official | reporting-analytics | 6db38fb | feat(report-generator): implement report generation form with scheduling and preview functionality | Implements scheduling logic and preview UI for generated reports. | 07/09/2024 |
| pandoras-fresh-frontend-official | alerta-notificacion1 | 4d3a50b | Push | Sets up initial alert-notification module configuration. | 07/09/2024 |
| pandoras-fresh-frontend-official | alerta-notificacion1 | 4f821eb | fix(alert-notification): fix alert notification | Fixes alert notification setup and improves module initialization. | 07/09/2024 |

### 5.2.2.5. Execution Evidence for Sprint Review.
Durante este Sprint, el equipo logró implementar exitosamente las principales vistas del frontend de la aplicación Quizzbee, priorizando una experiencia de usuario fluida, intuitiva y visualmente coherente con el diseño propuesto. Se completó la estructura de navegación entre módulos clave, así como la visualización de datos simulados y el despliegue de componentes funcionales para cada uno de los bounded contexts asignados.

El enfoque colaborativo permitió que cada integrante trabajara de forma autónoma y coordinada en su respectivo contexto funcional, asegurando así una integración efectiva de los distintos componentes en la interfaz final. Como evidencia del progreso, a continuación se presentan capturas de pantalla de las vistas más representativas desarrolladas durante este Sprint.

**Reporting and analytics BC:**

<img src="https://raw.githubusercontent.com/AplicacionesWeb-7454/Report/main/assets/img/chapter5/BC_RA1.png" alt="BC_RA1" style="max-width:100; height:auto;">
<img src="https://raw.githubusercontent.com/AplicacionesWeb-7454/Report/main/assets/img/chapter5/BC_RA2.png" alt="BC_RA2" style="max-width:100; height:auto;">

**Inventory BC:**

<img src="https://raw.githubusercontent.com/AplicacionesWeb-7454/Report/main/assets/img/chapter5/Screenshot 2025-10-10 02.23.50.png" alt="BC_IN_1" style="max-width:100; height:auto;">
<img src="https://raw.githubusercontent.com/AplicacionesWeb-7454/Report/main/assets/img/chapter5/Screenshot 2025-10-10 03.46.02.png" alt="BC_IN_2" style="max-width:100; height:auto;">
<img src="https://raw.githubusercontent.com/AplicacionesWeb-7454/Report/main/assets/img/chapter5/Screenshot 2025-10-10 03.46.11.png" alt="BC_IN_3" style="max-width:100; height:auto;">
<img src="https://raw.githubusercontent.com/AplicacionesWeb-7454/Report/main/assets/img/chapter5/Screenshot 2025-10-10 03.46.18.png" alt="BC_IN_4" style="max-width:100; height:auto;">
<img src="https://raw.githubusercontent.com/AplicacionesWeb-7454/Report/main/assets/img/chapter5/Screenshot 2025-10-10 03.46.26.png" alt="BC_IN_5" style="max-width:100; height:auto;">

**User Management BC:**
<img src="https://raw.githubusercontent.com/AplicacionesWeb-7454/Report/main/assets/img/chapter5/login.png" alt="login" style="max-width:100; height:auto;">
<img src="https://raw.githubusercontent.com/AplicacionesWeb-7454/Report/main/assets/img/chapter5/register.png" alt="register" style="max-width:100; height:auto;">

**IoT Monitoring BC:**

<img src="https://raw.githubusercontent.com/AplicacionesWeb-7454/Report/main/assets/img/chapter5/monitoring1.PNG"  style="max-width:100; height:auto;">
<img src="https://raw.githubusercontent.com/AplicacionesWeb-7454/Report/main/assets/img/chapter5/monitoring2.PNG"  style="max-width:100; height:auto;">

### 5.2.2.6. Services Documentation Evidence for Sprint Review
Durante el Sprint 2, el equipo se centró en el desarrollo de la parte visual y dinámica del frontend de PandoraFresh, utilizando Vue para las funcionalidades interactivas y Firebase para el despliegue

Repositorio de Web Services (Planificado para los próximos sprints): Se ha preparado el repositorio que se utilizará para el desarrollo de la lógica del backend y para la implementación de los endpoints REST que se necesitarán en los próximos sprints
### 5.2.2.7. Software Deployment Evidence for Sprint Review

Aquí se presentará la evidencia del despliegue del software realizado en el Sprint 2. Se podrán añadir capturas de pantalla, enlaces a entornos desplegados, logs de despliegue y cualquier otro recurso que demuestre el proceso y resultado del deployment. (Las imágenes y evidencias serán añadidas posteriormente).

<img src="https://raw.githubusercontent.com/AplicacionesWeb-7454/Report/main/assets/img/chapter5/FIRE1.png" alt="Registro Firebase" style="width:auto; height:auto;">
Nos registramos 
<img src="https://raw.githubusercontent.com/AplicacionesWeb-7454/Report/main/assets/img/chapter5/FIRE2.png" alt="Endpoints públicas" style="width:auto; height:auto;">
Ya registrados podemos crear nuestras endpoints públicas
<img src="https://raw.githubusercontent.com/AplicacionesWeb-7454/Report/main/assets/img/chapter5/FIRE3.png" alt="Creación de endpoints" style="width:auto; height:auto;">

Y en el serverBasePath: Ponemos la url de nuestro endPoint pública
<img src="https://raw.githubusercontent.com/AplicacionesWeb-7454/Report/main/assets/img/chapter5/FIRE4.png" alt="ServerBasePath" style="width:auto; height:auto;">


Firebase Firebase es una plataforma de desarrollo de aplicaciones web y móviles proporcionada por Google, diseñada para ayudar a los desarrolladores a crear, gestionar y escalar aplicaciones rápidamente. Firebase ofrece una variedad de servicios que facilitan tanto el desarrollo como la gestión de aplicaciones en tiempo real<br>

<img src="https://raw.githubusercontent.com/AplicacionesWeb-7454/Report/main/assets/img/chapter5/FIRE5.png" alt="Firebase overview" style="width:auto; height:auto;">

 Nos registramos con una cuenta de google y vamos a la consola
 
<img src="https://raw.githubusercontent.com/AplicacionesWeb-7454/Report/main/assets/img/chapter5/FIRE6.png" alt="Consola Firebase" style="width:auto; height:auto;">
 
 Creamos un nuevo proyecto de firebase
 
<img src="https://raw.githubusercontent.com/AplicacionesWeb-7454/Report/main/assets/img/chapter5/FIRE7.png" alt="Nuevo proyecto Firebase" style="width:auto; height:auto;">
 Ponemos un nombre para el proyecto
 
<img src="https://raw.githubusercontent.com/AplicacionesWeb-7454/Report/main/assets/img/chapter5/FIRE8.png" alt="Nombre del proyecto" style="width:auto; height:auto;">

 Vamos al apartado de hosting

 
<img src="https://raw.githubusercontent.com/AplicacionesWeb-7454/Report/main/assets/img/chapter5/FIRE9.png" alt="Apartado Hosting" style="width:auto; height:auto;">

 Se configura el firebase hosting en nuestro proyecto de intellij idea
<img src="https://raw.githubusercontent.com/AplicacionesWeb-7454/Report/main/assets/img/chapter5/FIRE10.png" alt="Configuración en IntelliJ" style="width:auto; height:auto;">

Limk del frontend : 
 
 Con esto ya tendríamos nuestro hosting desplegado con los siguientes comandos

ng build
sudo npm install -g firebase-tools
firebase login
firebase init
firebase deploy

### 5.2.2.8. Team Collaboration Insights during Sprint

En este apartado se presenta un resumen de la dinámica de trabajo colaborativo y la gestión de tareas realizada por el equipo durante el Sprint 2. Se incluyen evidencias visuales que muestran la participación activa de los integrantes, así como el registro de los commits y contribuciones en el repositorio. Estas evidencias reflejan el compromiso, la organización y la comunicación efectiva que caracterizaron el desarrollo de este sprint.

<img src="https://raw.githubusercontent.com/AplicacionesWeb-7454/Report/main/assets/img/chapter1/CONTRI.PNG" alt="CONTRI" style="width:auto; height:auto;">

### 5.2.3. Sprint 3
En esta sección se registra el avance del producto y las acciones colaborativas realizadas por el equipo durante el desarrollo del Sprint 3.

### 5.2.3.1. Sprint Planning 3.

Durante la reunión de planificación del Sprint 3, el equipo identificó los objetivos prioritarios en función del alcance general del proyecto. Se establecieron entregables enfocados en mejorar la funcionalidad de la plataforma y avanzar con la implementación de módulos esenciales. A continuación, se resumen los acuerdos principales:

| **Sprint #** | Sprint 3 |
|---------------|-----------|
| **Sprint Planning Background** |  |
| **Date** | 1/11/2025  |
| **Time** | 13:00 horas  |
| **Location** |  Modalidad remota a través de la plataforma Discord  |
| **Prepared By** | Todos los integrantes del equipo PandoraFresh |
| **Attendees (to planning meeting)** | Todos los integrantes del equipo PandoraFresh |
| **Sprint n – 3 Review Summary** |  Durante el Sprint anterior, se realizaron correcciones sugeridas por el profesor en el informe del proyecto, y se logró desarrollar la primera versión de la aplicación Front End. Este avance permitió establecer la base del sistema, con un diseño visual inicial y funcionalidades básicas. Aunque algunas pantallas no fueron completadas, el producto resultante fue funcional y bien recibido.   |
| **Sprint n – 3 Retrospective Summary** | El equipo expresó satisfacción con el trabajo colaborativo, destacando la mejora en la comunicación interna y la distribución de tareas. Se identificaron oportunidades de mejora en la organización del tiempo y planificación de actividades. Se acordó priorizar la definición clara de objetivos semanales para mejorar la eficiencia del equipo. |
| **Sprint Goal & User Stories** | TS1, TS2, TS3, TS4, TS5, TS6, TS7, TS8  |
| **Sprint 3 Goal** |  Nuestro enfoque se centra en el desarrollo y consolidación de la API de PandoraFresh, que constituye el núcleo funcional de la plataforma. Esta API implementa un conjunto de endpoints clave que soportan la creación, gestión                       del inventario, así como la administración de cada alimento y creacon sensores para el monitoreo Iot.El objetivo principal es garantizar un flujo completo y coherente entre las acciones del usuario y sus alimentos, permitiendo que la interaccion sea segura.  |
| **Sprint 3 Velocity** | 100%|
| **Sum of Story Points** | La suma de Story Points atendidos es de 21 story points|

### 5.2.3.2. Aspect Leaders and Collaborators.

En esta sección se presenta la Leadership-and-Collaboration Matrix (LACX) para el Sprint 3, enfocada en la integración casi completa entre la Frontend Web Application y los Web Services RESTful del backend de PandoraFresh. Esta matriz define los roles y responsabilidades de cada miembro del equipo durante el proceso de integración y pruebas.

Principales Aspectos Considerados en el Sprint 3: Para el Sprint 3, se han identificado cuatro aspectos fundamentales que abarcan la integración y pruebas completas: API Integration (Integración de API): Este aspecto engloba la conexión de la aplicación frontend con los servicios RESTful del backend, incluyendo llamadas a endpoints, manejo de respuestas y errores. End-to-End Testing (Pruebas de extremo a extremo): Comprende la implementación de pruebas automatizadas que validan flujos completos desde la interfaz de usuario hasta el backend. Error Handling & User Feedback (Manejo de errores y retroalimentación al usuario): Incluye la implementación de mecanismos para manejar errores de API y proporcionar retroalimentación clara a los usuarios. Documentation & Deployment (Documentación y Despliegue): Abarca la actualización de la documentación técnica y la estrategia de despliegue continuo para la aplicación integrada.

| Team Member (Last Name, First Name) | Github Username |  Iventory| IoT Monitoring | User Management |  Reporting and Analytics | Alerts and Notification |
|-------------------------------------|-----------------| -------- |----------------| --------------- | -------------------------|-------------------------|
| Llamozas, Diego                     | Diego Llamozas  | (L)      | (C)            | (C)             |   (C)                    | (C)                     |
| Vidal, Jareth                       | Jareth341       | (C)      | (L)            | (C)             |   (C)                    | (C)                     |
| Chuchon, Jhon                       | JhonChuchon     | (C)      | (C)            | (C)             |   (C)                    | (L)                     |
| Seminario, Diego                    | DiegoSeminario  | (C)      | (C)            | (L)             |   (C)                    | (C)                     |
| Mendoza, Alejandro                  | AlexBoo578      | (C)      | (C)            | (C)             |   (L)                    | (C)                     |

### 5.2.3.2.3. Sprint Backlog 3. 

Durante este Sprint, el equipo enfocó sus esfuerzos en el desarrollo de la capa Backend de la aplicación, implementando la lógica de negocio y los servicios necesarios para dar soporte funcional a cada uno de los bounded contexts. Se priorizó la creación de entidades, controladores, servicios y repositorios en base a una arquitectura por capas y principios de diseño orientado a dominios. Cada integrante asumió la implementación del backend correspondiente a su bounded context asignado, permitiendo un desarrollo distribuido y coherente. Esta fase ha sido clave para establecer la base de comunicación entre el frontend y la lógica del sistema, asegurando la persistencia de datos y el correcto flujo de la información. 

| **User Story Id** | **User Story Title** | **Task Id** | **Task Title** | **Description** | **Estimation (Hours)** | **Assigned To** | **Status** |
|-------------------|----------------------|--------------|----------------|-----------------|------------------------|-----------------|-------------|
| **TS01** | Backend API User Management | T-01 | Implementar creación de cuenta | Implementar el endpoint para registrar nuevos usuarios, validando datos y almacenando la información correctamente. | 2 | Diego Seminario | Done |
| **TS02** | Backend API Inventory | T-02 | Implementar creación de inventario | Implementar endpoints para crear, editar y eliminar productos del inventario, incluyendo validaciones básicas. | 1 | Edson Llamozas| Done |
| **TS03** | Backend API IoT Monitoring | T-03 | Implementar creación de sensores | Implementar endpoints para registrar sensores, vincularlos y recibir datos de temperatura y humedad. | 3 | Jareth Vidal | Done |
| **TS04** | Backend API Reporting and Analytics | T-04 | Implementar reportes | Implementar el endpoint para generar reportes, procesar datos y retornar archivos en los formatos requeridos. | 2 | Alejandro Mendoza | Done |
| **TS05** | Backend API Alerts and Notification | T-05 | Implementar notificación de caducidad | Implementar endpoints para enviar alertas de productos próximos a vencer y gestionar notificaciones configuradas por el usuario. | 1 | Jhon Chuchon | Done |

Este es nuestro link de invitación a nuestro Trello: https://trello.com/invite/b/68e82dc4aa24c7aadbc4cc21/ATTI0f71e2d868b5d516dd4b989004bb7a9348800ED5/kanban-template

### 5.2.3.4. Development Evidence for Sprint Review.

| Repository | Branch | Commit Id | Commit Message | Commit Message Body | Commited on (Date) |
|------------|--------|-----------|----------------|--------------------|--------------------|
|pandoras-fresh-frontend-official |  |   |   |  |  21/10/2025 |
|  pandoras-fresh-frontend-official |  |   |  | | 3/11/2025 |
|  pandoras-fresh-frontend-official |  |  ||  | 9/11/2024 |

### 5.2.3.5.  Execution Evidence for Sprint Review
En esta sección, Tenemos los endpoints para PandoraFresh:

### 5.2.3.6. Services Documentation Evidence for Sprint Review. 
 
### 5.2.3.7.  Software Deployment Evidence for Sprint Review. 

 Link Landing Desplegado: https://pandorafresh.netlify.app/
 Link del frontend despluegado: 
 Evidencias:

### 5.2.3.8.  Team Collaboration Insights during Sprint.

## 5.3. Validation Interviews

### 5.3.1. Diseño de Entrevistas

En esta sección se presenta el diseño de las entrevistas de validación realizadas para la plataforma **PandoraFresh**, aplicadas a los segmentos objetivo identificados durante el proceso de investigación.  
Cada entrevista busca recopilar percepciones sobre la **facilidad de uso**, **interfaz**, **flujo de navegación**, **motivación**, y **valor percibido** de las funcionalidades principales tanto del *Landing Page* como de la aplicación.

## **Entrevistas por Segmento - Plataforma PandoraFresh**

#### **Segmento 1: Personas que quieren reforzar lo aprendido de algún idioma**

---

#### **Segmento 2: Personas que ya dominan algún idioma**

### 5.3.2. Registro de Entrevistas.

#### Segmento 1:
#### Segmento 2:


---




