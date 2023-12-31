
# Tasty Point

 ![Universidad Aplicada de Ciencias Aplicadas](https://upload.wikimedia.org/wikipedia/commons/f/fc/UPC_logo_transparente.png)

Carrera:
Ingeniería de Software

Nombre del curso:
Arquitectura de Software Emergentes

Sección:
WS82

Nombre del profesor:
Royer Edelwer Rojas Malasquez

"Informe de Trabajo Final"

Nombre del startup:
Tasty Point

Nombre del producto:
TastyPoint

Relación de integrantes:

- Marco Antoni Mendoza Rodriguez
- Claudia Lucia Rozas Gamero (U201922910)
- Andres Christian Reynoso (U202010196)
- David Antonio Torres Vilchez (U202010942)
- Adrian Marquina Vichino (U202017487)

Mes y año:
Setiembre 2023

Ciclo:
2023-2

## Registro de Versiones del Informe

| Version | Fecha| Autor | Descripción de la Modificación |
|-----------|-----------|-----------|-----------|
| 1.0 | 22/08/2023 | Andres Christian Reynoso | Se agrego el contenido relacionado al primer entregable TB1 |
| 2.0 | 7/09/2023 | David Torres Vilchez | Se agrego el contenido relacionado al primer entregable TB1 |
| 3.0 | 8/09/2023 | Claudia Rozas | Avance del capítulo 4 para el entregable TB1 |
| 3.0 | 9/09/2023 | Marco Mendoza | Avance del capítulo 4 para el entregable TB1 y correcciones en la documentación |
| 4.0 | 9/09/2023 | Adrian Marquina | Puntos faltantes de la TB1 (startup, link en los indices, styles) |
| 5.0 | 23/09/2023 | Claudia Rozas | Avance del capítulo 5 para la elaboración del TP |
| 6.0 | 25/09/2023 | Andres Reynoso | Avance del capítulo 6 para la elaboración del TP |
| 7.0 | 26/09/2023 | Adrian Marquina | Puntos faltantes del TP (landing page wireframes, landing page, style guidelines, indices, outcomes, formateo y estilos) |
| 8.0 | 31/10/2023 | Claudia Rozas | Diseño de mock-ups de la aplicación web y desarrollo del mismo |
| 9.0 | 31/10/2023 | David Torres Vilchez  | Mobile User Flows y desarrollo de la mobile app|
| 10.0 | 03/11/2023 | Adrian Marquina  | Punto 7 y sprint 1, incluido placeholders, landing page y otros|

## Project Report Collaboration Insights

**Enlace del Project Report: [https://github.com/Arquitectura-Software-2023/Project-Report.git](https://github.com/Arquitectura-Software-2023/Project-Report.git)**

## Contenido

- [Tabla de contenidos](#contenido)

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
    - [2.3.3. Empathy Mapping](#233-empathy-mapping)
    - [2.3.4. As-is Scenario Mapping](#234-as-is-scenario-mapping)

- [Capítulo III: Requirements Specification](#capítulo-iii-requirements-specification)
  - [3.1. To-Be Scenario Mapping](#31-to-be-scenario-mapping)
  - [3.2. User Stories](#32-user-stories)
  - [3.3. Impact Mapping](#33-impact-mapping)
  - [3.4. Product Backlog](#34-product-backlog)

- [Capítulo IV: Strategic-Level Software Design](#capítulo-iv-solution-software-design)
  - [4.1. Strategic-Level Attribute-Driven Design](#41-strategic-level-attribute-driven-design)
    - [4.1.1. Design Purpose](#411-design-purpose)
    - [4.1.2. Attribute-Driven Design Inputs](#412-attribute-driven-design-inputs)
      - [4.1.2.1. Primary Functionality (Primary User Stories)](#4121-primary-functionality-primary-user-stories)
      - [4.1.2.2. Quality attribute Scenarios](#4122-quality-attribute-scenarios)
      - [4.1.2.3. Constraints](#4123-constraints)
    - [4.1.3. Architectural Drivers Backlog. 6/40 V1.0](#413-architectural-drivers-backlog-640-v10)
    - [4.1.4. Architectural Design Decisions](#414-architectural-design-decisions)
    - [4.1.5. Quality Attribute Scenario Refinements](#415-quality-attribute-scenario-refinements)
  - [4.2. Strategic-Level Domain-Driven Design](#42-strategic-level-domain-driven-design)
    - [4.2.1. EventStorming](#421-eventstorming)
    - [4.2.2. Candidate Context Discovery](#422-candidate-context-discovery)
    - [4.2.3. Domain Message Flows Modeling](#423-domain-message-flows-modeling)
    - [4.2.4. Bounded Context Canvases](#424-bounded-context-canvases)
    - [4.2.5. Context Mapping](#425-context-mapping)
  - [4.3. Software Architecture](#43-software-architecture)
    - [4.3.1. Software Architecture System Landscape Diagram](#431-software-architecture-system-landscape-diagram)
    - [4.3.2. Software Architecture Context Level Diagrams](#432-software-architecture-context-level-diagrams)
    - [4.3.3. Software Architecture Deployment Diagrams](#433-software-architecture-container-level-diagrams)

- [Capítulo V: Tactical-Level Software Design](#capítulo-v-tactical-level-software-design)
  - [5.1 Bounded Context: Monitoring Context](#51-bounded-context-monitoring-context)
    - [5.1.1 Domain Layer](#511-domain-layer)
    - [5.1.2. Interface Layer](#512-interface-layer)
    - [5.1.3 Application Layer](#513-application-layer)
    - [5.1.4 Infrastructure Layer](#514-infrastructure-layer)
    - [5.1.5 Bounded  Context  Software Architecture Component Level Diagrams](#515-bounded-context-software-architecture-component-level-diagrams)
    - [5.1.6 Bounded Context Software Architecture code Level Diagrams](#516-bounded-context-software-architecture-code-level-diagrams)
      - [5.1.6.1 Bounded Context Domain Level Class Diagram](#5161-bounded-context-domain-level-class-diagram)
      - [5.1.6.2 Bounded Context Database Design Diagram](#5162-bounded-context-database-design-diagram)
  - [5.2 Bounded Context: Booking Context](#52-bounded-context-booking-context)
    - [5.2.1 Domain Layer](#521-domain-layer)
    - [5.2.2. Interface Layer](#522-interface-layer)
    - [5.2.3 Application Layer](#523-application-layer)
    - [5.2.4 Infrastructure Layer](#524-infrastructure-layer)
    - [5.2.5 Bounded  Context  Software Architecture Component Level Diagrams](#525-bounded-context-software-architecture-component-level-diagrams)
    - [5.2.6 Bounded Context Software Architecture code Level Diagrams](#526-bounded-context-software-architecture-code-level-diagrams)
      - [5.2.6.1 Bounded Context Domain Level Class Diagram](#5261-bounded-context-domain-level-class-diagram)
      - [5.2.6.2 Bounded Context Database  Design Diagram](#5262-bounded-context-database-design-diagram)
  - [5.3 Bounded Context: Stock Inventory Context](#53-bounded-context-stock-inventory-context)
    - [5.3.1 Domain Layer](#531-domain-layer)
    - [5.3.2. Interface Layer](#532-interface-layer)
    - [5.3.3 Application Layer](#533-application-layer)
    - [5.3.4 Infrastructure Layer](#534-infrastructure-layer)
    - [5.3.5 Bounded  Context  Software Architecture Component Level Diagrams](#535-bounded-context-software-architecture-code-level-diagrams)
    - [5.3.6 Bounded Context Software Architecture code Level Diagrams](#536-bounded-context-software-architecture-code-level-diagrams)
      - [5.3.6.1 Bounded Context Domain Level Class Diagram](#5361-bounded-context-domain-level-class-diagram)
      - [5.3.6.2 Bounded Context Database  Design Diagram](#5362-bounded-context-database-design-diagram)
  - [5.4 Bounded Context: Purchase Context](#54-bounded-context-purchase-context)
    - [5.4.1 Domain Layer](#541-domain-layer)
    - [5.4.2. Interface Layer](#542-interface-layer)
    - [5.4.3 Application Layer](#543-application-layer)
    - [5.4.4 Infrastructure Layer](#544-infrastructure-layer)
    - [5.4.5 Bounded  Context  Software Architecture Component Level Diagrams](#545-bounded-context-software-architecture-code-level-diagrams)
    - [5.4.6 Bounded Context Software Architecture code Level Diagrams](#546-bounded-context-software-architecture-code-level-diagrams)
      - [5.4.6.1 Bounded Context Domain Level Class Diagram](#5461-bounded-context-domain-level-class-diagram)
      - [5.4.6.2 Bounded Context Database  Design Diagram](#5462-bounded-context-database-design-diagram)
      - [5.4.6.3 General Domain Level Class Diagram](#5463-general-domain-level-class-diagram)
      - [5.4.6.4 General Database Design Diagram](#5464-general-database-design-diagram)
  - [Capítulo VI: Solution UX Design](#capítulo-vi-solution-ux-design)
    - [6.1. Style Guidelines](#61-style-guidelines)
      - [6.1.1. General Style Guidelines](#611-general-style-guidelines)
      - [6.1.2. Web & Mobile Style Guidelines](#612-web--mobile-style-guidelines)
    - [6.2. Arquitectura de la Información](#62-arquitectura-de-la-información)
      - [6.2.1. Sistemas de Organización](#621-sistemas-de-organización)
      - [6.2.2. Sistemas de Etiquetado](#622-sistemas-de-etiquetado)
      - [6.2.3. Etiquetas SEO y Metaetiquetas](#623-etiquetas-seo-y-metaetiquetas)
      - [6.2.4. Sistemas de Búsqueda](#624-sistemas-de-búsqueda)
      - [6.2.5. Sistemas de Navegación](#625-sistemas-de-navegación)
    - [6.3. Landing Page UI Design](#63-landing-page-ui-design)
      - [6.3.1. Landing Page Wireframe](#631-landing-page-wireframe)
      - [6.3.2. Landing Page Mock-up](#632-landing-page-mock-up)
    - [6.4. Applications UX/UI Design](#64-applications-uxui-design)
      - [6.4.1. Applications Wireframes](#641-applications-wireframes)
      - [6.4.2. Applications Wireflow Diagrams](#642-applications-wireflow-diagrams)
  - [Capítulo VII: Product Implementation, Validation & Deployment](#capítulo-vii-product-implementation-validation--deployment)
    - [7.1. Software Configuration Management](#71-software-configuration-management)
      - [7.1.1. Software Development Environment Configuration](#711-software-development-environment-configuration)
      - [7.1.2. Source Code Management](#712-source-code-management)
      - [7.1.3. Source Code Style Guide & Conventions](#713-source-code-style-guide--conventions)
      - [7.1.4. Software Deployment Configuration](#714-software-deployment-configuration)
    - [7.2. Solution Implementation](#72-solution-implementation)
      - [7.2.1. Sprint 1](#721-sprint-1)
        - [7.2.1.1. Sprint 1 Planning](#7211-sprint-1-planning)
        - [7.2.1.2. Sprint 1 Backlog](#7212-sprint-1-backlog)
        - [7.2.1.3. Development Evidence for Sprint Review](#7213-development-evidence-for-sprint-review)
        - [7.2.1.4. Testing Suite Evidence for Sprint Review](#7214-testing-suite-evidence-for-sprint-review)
        - [7.2.1.5. Execution Evidence for Sprint Review](#7215-execution-evidence-for-sprint-review)
        - [7.2.1.6. Services Documentation Evidence for Sprint Review](#7216-services-documentation-evidence-for-sprint-review)
        - [7.2.1.7. Software Deployment Evidence for Sprint Review](#7217-software-deployment-evidence-for-sprint-review)
        - [7.2.1.8. Team Collaboration Insights during Sprint](#7218-team-collaboration-insights-during-sprint)
      - [7.2.2. Sprint 2](#722-sprint-2)
        - [7.2.2.1. Sprint 2 Planning](#7221-sprint-2-planning)
        - [7.2.2.2. Sprint 2 Backlog](#7222-sprint-2-backlog)
        - [7.2.2.3. Development Evidence for Sprint Review](#7223-development-evidence-for-sprint-review)
        - [7.2.2.4. Testing Suite Evidence for Sprint Review](#7224-testing-suite-evidence-for-sprint-review)
        - [7.2.2.5. Execution Evidence for Sprint Review](#7225-execution-evidence-for-sprint-review)
        - [7.2.2.6. Services Documentation Evidence for Sprint Review](#7226-services-documentation-evidence-for-sprint-review)
        - [7.2.2.7. Software Deployment Evidence for Sprint Review](#7227-software-deployment-evidence-for-sprint-review)
        - [7.2.2.8. Team Collaboration Insights during Sprint](#7228-team-collaboration-insights-during-sprint)
    - [7.3. Validation Interviews](#73-validation-interviews)
      - [7.3.1. Diseño de Entrevistas](#731-diseño-de-entrevistas)
      - [7.3.2. Registro de Entrevistas](#732-registro-de-entrevistas)
      - [7.3.3. Evaluaciones segun Heuristicas](#733-evaluaciones-segun-heuristicas)
    - [Video About the Product](#74-video-about-the-product)
  - [Conclusiones](#conclusiones)
  - [Bibliografia](#bibliografia)
  - [Anexos](#anexos)

# Student Outcome

- **TB1**

|  Criterio específico | Participa en equipos multidisciplinarios con eficacia, eficiencia y objetividad, en el marco de un proyecto en soluciones de ingeniería de software | Conoce al menos un sector empresarial o dominio de aplicación de soluciones de software | Conocimientos de nuevos métodos de colaboración y comunicación |
|-----------|-----------|-----------|-----------|
| Andres Christian Reynoso | **Acciones:** Para este entregable hemos hecho coordinaciones en equipo para poder desarrollar los puntos relacionados a la TB1 **Conclusiones:** Gracias a esto pudimos desarrollar con mas velocidad este entregable. |  **Acciones:** El conocer a nuestros segmentos objetivos con el desarrollo delos UX es un paso fundamental para desarrollar el proyecto. **Conclusiones:** De esta forma, pudimos ponernos mejor en los zapatos de nuestros usuarios. |  **Acciones:** Los repositorios de github, al igual que las reuniones de discord ayudaron a fomentar comunicacion entre los miembros del equipo. **Conclusiones:** La comunicacion entre el equipo es fundamental para los avances del proyecto. |
| David Torres Vilchez | **Acciones:** Para este entregable realizamos una serie de reuniones por medio de discord para la distribucion de las tareas correspondientes **Conclusiones:** El trabajo colaborativo nos ayuda a aser mas eficaces. |  **Acciones:** Se realizo una investigacion enfocada en startaups con objetivos similares al nuestro.  **Conclusiones:** el análisis de competidores es fundamental para el planteamiento de requisitos|  **Acciones:** Realice las tareas asignadas a mi persona para poder cumplir con el trabajo colaborativo **Conclusiones:** El compromiso en entornos de desarrollo colaborativos es fundamental para lograr los alcances establecidos.|
| Claudia Rozas | **Acciones:** Para este entregable definimos los puntos a desarrollar para cada persona según su preferencia **Conclusiones:** Escuchar a los demás nos ayudó a completar con éxito el TB1 |  **Acciones:** Averigué acerca del negocio, cuáles podrían ser nuestros servicios, etc **Conclusiones:** Logré entender nuestro concepto |  **Acciones:** Descubrí algunas páginas que nos podrían ayudar en nuestro trabajo a lo largo del curso **Conclusiones:** Logré incorporar esas páginas en nuestro proyecto |
| Adrian Marquina | **Acciones:** Participe y contribui al desarrollo de la TB1 de forma efectiva y objetiva. **Conclusiones:** Logre resultados deseables con mi participacion. |  **Acciones:** Investigue como incluir VR en nuestro marco de negocio. **Conclusiones:** Logre incorporar VR a nuestro modelo de negocio, palmandolo en la mision y vision de la startup. |  **Acciones:** Me comunique efectivamente con mi equipo para coordinar las responsabilidades a cumplir. **Conclusiones:** Logue participar y coordinar las actividades. Asimismo, las cumpli segun lo requerido. |
| Marco Mendoza Rodriguez | **Acciones:** Fui participe de la primera reunión entre el equipo para formular ideas en base al proyecto a trabajar. Realizamos lluvia de ideas y de las cuales se eligió presentar una al profesor. **Conclusiones:** Realicemos las US con fines de lograr dar hincapié al desarrollo de la aplicación que posteriormente se realizará. |  **Acciones:** Elegimos trabajar con Tasty Point, nuestra startup. Evidenciamos que no existe un competidor absoluto en Perú, pero sí en Europa, identifiquemos que la idea de negocio es exitosa por su gran acogida clientela. **Conclusiones:** Realicemos conjuntamente el análisis del segmento objetivo, a su vez los competidores y establecimos una línea desde ese foco de trabajo.  |  **Acciones:** Utilicemos las herramientas tecnológicas para realizar una mejor comunicación asertiva. Zoom, los productos de office y las herramientas indicadas en la guía para realizar los mapas que requiere dicho capítulo. **Conclusiones:** Adquirimos conocimientos previos de temas nuevos que partimos de ello para realizar el análisis correspondiente.  |

- **TP**

|  Criterio específico | Participa en equipos multidisciplinarios con eficacia, eficiencia y objetividad, en el marco de un proyecto en soluciones de ingeniería de software | Conoce al menos un sector empresarial o dominio de aplicación de soluciones de software | Conocimientos de nuevos métodos de colaboración y comunicación |
|-----------|-----------|-----------|-----------|
| Andres Christian Reynoso | **Acciones:** El desarrollo de wireframes y mockups nos ayudan a entender como funcionara nuestra aplicacion por desarrollar. **Conclusiones:** El objetivo de esto es prototipear como funcionara nuestro aplicativo. |  **Acciones:** El desarrollo de los mockups y wireframes ayudan a darnos a entender como se sentiran nuestros segmentos objetivo. **Conclusiones:** Gracias a esto, podemos desarrollar y tener una idea principal de nuestro proyecto. | **Acciones:** Los repositorios de github, aplicaciones como figma, y las reuniones de discord ayudaron a fomentar comunicacion entre los miembros del equipo. **Conclusiones:** La comunicacion entre el equipo es fundamental para los avances del proyecto. |
| David Torres Vilchez | **Acciones:**  Participar en el entorno colaborativo de github y en el desarrollo del apartado de informaction architecture  **Conclusiones:** La organización en el diseño de interfaces es crucial para la usabilidad y la satisfacción del usuario.|  **Acciones:** Establecer la arquitectura de la información de nuestros aplicativos web y móviles **Conclusiones:** La coherencia en el diseño es esencial para la retención de usuarios y la satisfacción del cliente.|  **Acciones:** El diseño y arquitectura de los sitemas de búsqueda y de labeling **Conclusiones:** La organización lógica de estos elementos contribuye a una experiencia de usuario más fluida.|
| Claudia Rozas | **Acciones:** El desarrollo de los bounded context nos ayuda a entender mejor lo que se busca que tenga la aplicación **Conclusiones:** Logré entender y averiguar más acerca de este tema |  **Acciones:** Averigué más sobre lo que contienen los infrastructure layer  **Conclusiones:** Entendí más a profundidad ese concepto |  **Acciones:** Investigué sober herrmaientas que se me hicieran más fácil graficar para los bounded context **Conclusiones:** Esto me ayudó para poder terminar con más eficacia el proyecto|
| Adrian Marquina |**Acciones:** Participe y contribui al desarrollo de la TB1 de forma efectiva y objetiva, tomando un poco mas de responsabilidad de lo requerido. **Conclusiones:** Logre resultados deseables con mi participacion. |  **Acciones:** Investigue guias de estilos que sean acorde a nuestro negocio. **Conclusiones:** Logre identificar una guia acorde a nuestro negocio y lo aplique al landing page. |  **Acciones:** Me comunique efectivamente con mi equipo para coordinar las responsabilidades a cumplir. **Conclusiones:** Logue participar y coordinar las actividades. Asimismo, las cumpli segun lo requerido. |
| Marco Mendoza Rodriguez | **Acciones:** Para encontrar soluciones alternativas a la TP, se tuvo que estudiar a detalle la continuación y además analizar sigilosamente los puntos que tienen que ser desarrollados. **Conclusiones:**  Gracias a esto pudimos entender con mas claridad los puntos a desarrollar|  **Acciones:** Conocer las herramientas de solución, así como el UXPresia, Lucid Chart y los editores de código son determinantes para encontrar soluciones. Son herramientas que sirven de mucha ayuda para organizar la información y  lograr encontrar una solución. **Conclusiones:** Estas herramientas nos ayudaron a graficar mejor nuestro futuro proyecto. |  **Acciones:** Los métodos de comunicación son WhatsApp, Discord. Estos medios son de mucha ayuda, porque permiten a todos los miembros de grupo estar al pendiente de lo que vayamos realizando. **Conclusiones:** Las reuniones de grupo nos ayudaron a realizar y dividir los puntos en relacion al entregable. |

- **TB2**

|  Criterio específico | Participa en equipos multidisciplinarios con eficacia, eficiencia y objetividad, en el marco de un proyecto en soluciones de ingeniería de software | Conoce al menos un sector empresarial o dominio de aplicación de soluciones de software | Conocimientos de nuevos métodos de colaboración y comunicación |
|-----------|-----------|-----------|-----------|
| Andres Christian Reynoso | **Acciones:** El desarrollo de mockups y programacion web nos ayudan a desarrollar los primeros pasos de nuestra aplicacion. **Conclusiones:** El objetivo de este primer sprint es poder desarrollar la aplicacion que se ha estado planificando por mucho tiempo. |  **Acciones:** El desarrollo temprano de nuestra aplicacion nos ayudan a ver puntos por corregir y que cosas no funcionan a diferencia de nuestros mock ups. **Conclusiones:** Gracias a esto nos ayuda a mejorar nuestro proyecto y facilitar su uso para nuestros usuarios |  **Acciones:** La comunicacion y coordinacion efectiva con mi equipo fue fundamental para dividirnos las aplicaciones. **Conclusiones:** La organización del equipo nos ayudo a realizar un mayor avance del trabajo a lo planificado oficialmente. |
| David Torres Vilchez | **Acciones:** Realice las tareas asignadas a mi persona dentro del sprint. **Conclusiones:** El uso de figma para realizar el diseño de la aplicación en entornos colaborativos es de gran ayuda para la organización del equipo|  **Acciones:** Realice los user flows del apartado mobile de la aplicación junto con el desarrollo de la versión móvil **Conclusiones:** Tener un buen conocimiento de la estructura del negocio aporta en la experiencia del usuario. |  **Acciones:** Se realizaron reuniones constantes en equipo para planificar los objetivos del sprint **Conclusiones:** La comunicación dentro del equipo de desarrollo es fundamental. |
| Claudia Rozas | **Acciones:** Se desarrolló los mock-ups de la aplicación web **Conclusiones:** Es bueno trabajar en equipo para que se pueda llegar a una conclusión|  **Acciones:** Se diseñó la aplicación web **Conclusiones:** Con ayuda de un compañero, se pudo lograr el despliegue|  **Acciones:** Se buscó nueva información de cómo levantar la aplicación web **Conclusiones:** La investigación y el compañerismo es buen aliado |
| Adrian Marquina | **Acciones:** Me encarge de elaborar el landing page, tambien de organizar al equipo durante el sprint. **Conclusiones:** Logramos como equipo establecer las ceremonias y participar en ellas. Asimismo, complete mi compromiso del sprint 1. |  **Acciones:** Me encarge de desplegar el landing page y habilitar los recursos para el web app en Azure. **Conclusiones:** Logre desplegar el landing page configurando un pipeline de Ci/CD con github actios, asimismo, se elaboro el primer appraco para el pipeline de CI/CD de web app. |  **Acciones:** Participe en las ceremonias establecidas con el equipo. **Conclusiones:** Logramos dejar un registro de nuestras ceremonias incluido la participacion y decisiones tomadas. |
| Marco Mendoza Rodriguez | **Acciones:**  Me encargupe de desarrollar el prototipo VR, a su vez contribuí con ideas aprendidas en el curso para el desarrollo de Tasty Point. **Conclusiones:** Elaborar reuniones y una comunicación entre mis compañeros contribuyó a lograr grandes beneficios y buen desempeño en el equipo. |  **Acciones:** Con el prototipo buscamos comercializar productos y evitar el desperdicio, buscamos usar tecnologias emergentes con el afan de vender. **Conclusiones:** Aprender nuevas tecnologias emergentes benefica a gran media el sector industrial y comercial. |  **Acciones:** Nos comuniquemos por Discort y canales como WhatsApp y Google Meet. **Conclusiones:** La responsabilidad y el compromiso de todos fue evidente para obtener grandes beneficios. |

- **TF**

|  Criterio específico | Participa en equipos multidisciplinarios con eficacia, eficiencia y objetividad, en el marco de un proyecto en soluciones de ingeniería de software | Conoce al menos un sector empresarial o dominio de aplicación de soluciones de software | Conocimientos de nuevos métodos de colaboración y comunicación |
|-----------|-----------|-----------|-----------|
| Andres Christian Reynoso |  **Acciones:** El desarrollo de correcciones nos ayudan a mejorar nuestra aplicacion en base a nuestro publico objetivo. **Conclusiones:** El objetivo de esto es mejorar nuestro aplicativo. |  **Acciones:** El desarrollo de las mejoras ayudan a darnos a entender como es que la aplicacion mejorara para nuestro segmento objetivo. **Conclusiones:** Gracias a esto, podemos desarrollar las conclusiones de nuestro proyecto. | **Acciones:** Los repositorios de github y las reuniones de equipo nos ayudaron a mejorar la comunicacion entre los miembros del equipo. **Conclusiones:** La comunicacion entre el equipo fue muy importante durante el desarrollo del trabajo. |
| David Torres Vilchez | **Acciones:** **Conclusiones:** | **Acciones:** **Conclusiones:** | **Acciones:** **Conclusiones:** |
| Claudia Rozas | **Acciones:** **Conclusiones:** | **Acciones:** **Conclusiones:** | **Acciones:** **Conclusiones:** |
| Adrian Marquina | **Acciones:** **Conclusiones:** | **Acciones:** **Conclusiones:** | **Acciones:** **Conclusiones:** |
| Marco Mendoza Rodriguez | **Acciones:** Me ocupé de la creación del prototipo de realidad virtual, al mismo tiempo que aporté con conceptos adquiridos en el curso para la elaboración de Tasty Point. **Conclusiones:** Facilitar reuniones efectivas y fomentar una comunicación fluida entre mis compañeros ha sido fundamental para alcanzar notables beneficios y un rendimiento destacado en el equipo. | **Acciones:** Mediante el prototipo, aspiramos a poner en el mercado productos y prevenir el desperdicio, empleando tecnologías emergentes con el objetivo de impulsar las ventas. **Conclusiones:** Se concluyó satisfactoriamente hacer las tecnologias emergentes y el desarrollo de las app web y movil | **Acciones:** La comunicación y compromiso fueron determinantes para conseguir grandes logros **Conclusiones:** Nos esforzamos para cumplir con los objetivos y metas trazadas del curso, asi como tambien elaborar prototipos desde cero.|

## Capítulo I: Introducción

### 1.1. Startup Profile

### 1.1.1. Descripción de la Startup

Tasty Point es una startup que nace con el objetivo de reducir el porcentaje de comida desechada. Para ello, crearemos una aplicación web y móvil con el mismo nombre de nuestra startup utilizando realidad virtual (VR) para reunir diferentes restaurantes   y cadenas alimenticias para aprovechar sus productos no consumidos, pero que poseen aún se encuentran en un buen estado para su consumo y ofrecerlos a un precio reducido. Con la ayuda de Tasty Point, encontrar platos según la preferencia del usuario a   un buen precio es interactivo, sencillo y económico.
**Misión**
Somos una compañía de tecnología comprometida con la creación de aplicaciones web y móviles eficientes e innovadoras que permitan a nuestros usuarios poder acceder a una amplia gama de opciones en el área de alimentos de una manera ágil, sostenible y   económica.
**Visión**
Promover una cultura de consumo responsable y eficaz, donde todos nuestros clientes afiliados puedan acceder a alimentos nutritivos, deliciosos y económicos. Asimismo, contribuir al desarrollo de los comercios de alimentos preparados en el Perú    transformando lo que sería una pérdida por desperdicio en ganancias.

### 1.1.2. Perfiles de integrantes del equipo

| Nombre| Descripción|
|-----------|-----------|
|Andres Christian Reynoso  | Mi nombre es Andres Christian Reynoso, tengo 20 años y estudio en la carrera de Ingenieria de Software, estoy dispuesto a apoyar a mis compañeros en los momentos que sean necesarios.|
|Claudia Lucia Rozas Gamero| Mi nombres es Claudia Rozas, tengo 23 años y estudio Ingeniería de Software. Me gusta mucho el rubro de Data y estoy comprometida con mi equipo y/o proyectos |
|Marco Antoni Mendoza Rodriguez|  Soy estudiante del 9° ciclo de Ing Software, aparcionado por el desarrollo de Software, me gusta estudiar el desarrollo de tecnologias emergentes que dispongan de innovación y uso en la actualidad|
|Adrian Marquina Vichino| Estudiante de la carrera de ingeniería de software. Tengo experiencia trabajando como full-stack developer. |
|David Antonio Torres Vilchez| Me encuentro cursando la carrera de ingeniería de software en la Universidad Peruana de Ciencias Aplicadas. Tengo conocimientos en programación, buen desenvolvimiento trabajando bajo presión, optimismo y motivación por cumplir con los objetivos del proyecto.  |

### 1.2. Solution Profile

### 1.2.1 Antecedentes y problemática

The 5 ‘W’s y 2 ‘H’s  

- **1. What (Qué):**  
 El problema encontrado es la gran cantidad de alimentos disponibles desperdiciados en Perú y el Mundo que, por consiguiente, generan pérdidas económicas y ecológicas que afectan a los restaurantes y la  población.  
- **2. When (Cuándo):**  
 Este problema tiene más tiempo del que se tiene conciencia. Según la Organización de las Naciones Unidas para la Alimentación y la Agricultura (s.f.), "el número de personas afectadas por el hambre ha  aumentado lentamente desde 2014". Lo que evidencia la existencia de este dañoso problema.  
 La relación de lo anterior con nuestros públicos objetivos ocurre al concluir la venta del día o semana. Los clientes no agotaron el stock disponible del restaurante tradicional o de comida rápida, lo  que resulta en el desecho de estos platos o ingredientes restantes que no están lo suficientemente frescos para ser aprovechados en la siguiente jornada.  
 Nuestro primer cliente, el consumidor, usará el producto cuando esté buscando un plato de comida a un precio menor o un método para combatir la problemática del desperdicio de comida.  
 El comprador podrá elegir entre una variedad de platos disponibles en nuestra aplicación web. Estos platos son ofrecidos por nuestro segundo cliente, el restaurante tradicional o de comida rápida.
- **3. Where (dónde):**  
 El cliente podrá usar el producto desde su dispositivo móvil de preferencia. Esto le permitirá ordenar su comida desde cualquier lugar en el que se encuentre y recibirla, usando los servicios ofrecidos  por el restaurante.  
- **4. Who (quién):**  
 Como se mencionó en algún párrafo anterior, nuestra aplicación web cuenta con 2 clientes:  
  - El cliente consumidor, es quien ordena sus platos en la plataforma debido a la preocupación que la problemática del desperdicio de comida pueda generar si no es combatida, o simplemente    debido a los precios bajos de los platos ofrecidos en la plataforma.  
  - Y el cliente Restaurante, tradicional o de comida rápida, es quien ofrece las opciones disponibles de platos en la plataforma como una forma de minimizar las pérdidas económicas     generadas al "tirar" los productos no lo suficiente frescos para una siguiente jornada.  
- **5. Why (por qué):**  
 El problema del desperdicio de comida se debe a varios factores y ocurre en varias etapas (alimentos que se pierden después de la cosecha, durante la fase de venta al por menor de elementos primarios,  etc.). Sin embargo, Tasty Point se enfoca en el derroche de alimentos generados por el no agotamiento del stock en ingredientes y platos concluidos, problema consecuente de la falta de demanda.
 Tasty point busca solucionar el problema ofreciendo estos platos restantes de manera directa a los clientes, explícitamente a un precio menor.  
- **1. How (cómo):**  
 Tasty food es usado cuando:  
  - El consumidor busca una manera de combatir la problemática del desperdicio de comida, o simplemente busca alimentos ofrecidos a precios bajos, teniendo la opción de acceder a un catálogo en realidad virtual de los productos que ofrecen los restaurantes.  
  - El cliente Restaurante, tradicional o de comida rápida, busca una forma de minimizar las pérdidas generadas al "tirar" los productos que no pudieron venderse y no son lo suficientemente    frescos para una siguiente jornada.  
- **2. How much (cuánto) :**  
 De acuerdo con la ONU, Programa para el medio ambiente (2021), "se estima que 931 millones de toneladas de alimentos, o 17% del total de alimentos disponibles para los consumidores en 2019, terminaron  en los basureros de hogares, minoristas, restaurantes y otros servicios alimentarios". Estas cifras evidencian la gran cantidad de comida que se desperdicia de manera global y, de la misma manera al   mencionar a minoristas y hogares además de restaurantes, dejan entrever que es un problema del que nadie está exento.  

### 1.2.2 Lean UX Process

#### 1.2.2.1. Lean UX Problem Statements

    El desperdicio de alimentos es un problema global que afecta a restaurantes, minoristas y consumidores. Grandes cantidades de comida apta para el consumo terminan en la basura, generando pérdidas económicas y ambientales.
    Este problema lleva años ocurriendo, pero ha empeorado desde 2014 según la FAO. Los restaurantes tradicionales y de comida rápida se ven especialmente afectados al desechar ingredientes y platos que no pudieron vender al final del día o la semana.
    En el país no existen iniciativas para aprovechar los excedentes no vendidos de restaurantes, los cuales terminan en la basura a pesar de ser comida en buen estado. Esto perjudica a los restaurantes con menores ingresos e implica derrochar recursos en la producción de comida que no llega a consumirse.

Tasty Point es una Startup que ofrece la calidad y garantía de sus dichos productos, cubriendo la necesidad de cada uno de los peruanos, estar presente en el mercado, por lo que no existe otra startup  que ofrezca dicho servicio en el país. Tasty Point al ser una empresa pionera en el Perú establece un vínculo directo entre consumidor y la variedad de menú que esté interesado, ofreciendo así   disponibilidad y confianza a sus usuarios.  La facilidad de compra es estrictamente seguro, avala firmeza en sus medios de pagos e interacción con la APP WEB, haciendo que tu experiencia sea amigable e  interactiva con sus usuarios.  

Tasty Point al estar introducido al mercado peruano, país de una de las mejores gastronomías del mundo, ofrece a sus consumidores una variedad de platos al gusto del cliente y promueve la cultura de la  sana alimentación, responsable del buen cuidado de la salud e incentiva a la estabilización del consumo nutritivo. Pone a disposición una catálogo en realidad virtual con una amplia variedad de platos elaborados a base de productos de la  costa, sierra y selva.  

#### 1.2.2.2. Lean UX Assumptions

- **Business Outcome**

 En este apartado, analizaremos el impacto que nuestra propuesta pueda generar, bajo diversos aspectos, con el propósito de cumplir con nuestro objetivo.

 1. Agilizar la búsqueda de productos alimenticios que ofrecen los restaurantes  
  Es importante permitir al consumidor una eficiente navegación a través de nuestra app web con el propósito de agilizar la búsqueda de diversos restaurantes.  
 2. Mejorar las propuestas del mercado  
  Todos los consumidores buscan la mejor oferta/demanda y este caso no es la excepción, ofreciendo una reducción del precio original a aquel producto que no se desea desechar.  
 3. Promoviendo el servicio de delivery  
   En tiempos de pandemia, las aglomeraciones pueden llegar a ser perjudiciales, por lo que con Tasty Point, los consumidores no tendrán que preocuparse por ello.  

- **User**

Aquellos que residan en Lima Metropolitana y requieren de un servicio como el nuestro, forman parte de nuestro segmento objetivo, para ser portadores de los beneficios que Tasty Point tiene para dar.

1. Consumidores  
2. Restaurantes

- **User Outcome**

En este siguiente apartado, se presentan los beneficios adquiridos en base a la interacción de los usuarios con nuestra app web.

 1. Consumidores  
  Nos enfocamos en aquellas personas que consumen y adquieren sus productos alimenticios vía delivery y que prefieren elegir un plato de comida cualquiera con tal que esté en buen estado y a un buen precio.  
 2. Restaurantes  
  Nos enfocamos en aquellos restaurantes que poseen un porcentaje moderado/alto de productos desechados por día.

- **Features**

 1. Nuestros consumidores podrán pedir los alimentos que sobraron de una gran cantidad de restaurantes a un precio accesible.  
 2. Los dueños de restaurantes podrán evitar el desperdicio de alimentos y generar ingresos con la venta de sus productos sobrantes a un buen precio a través de la aplicación subiendo sus   productos de forma sencilla.  
 3. Los dueños de restaurantes podrán añadir sus promociones en la plataforma para atraer consumidores.  
 4. El sistema de búsqueda le brindara al consumidor el platillo que se ajuste mejor a sus preferencias como restaurante, tipo de comida, rango de precio, entre otros.  
 5. Los consumidores podrán calificar y dejar reseñas de los restaurantes en los que pidieron.  
 6. Los consumidores podrán visualizar notificaciones de las promociones de sus restaurantes favoritos.  
 7. Los consumidores podrán comunicarse con los dueños de los restaurantes ante cualquier inconveniente mediante su información de contacto en su perfil.  

#### 1.2.2.3. Lean UX Hypothesis Statements

- Hypothesis 1:  
 Creemos que agilizar la búsqueda de productos alimenticios que ofrecen los restaurantes se logrará si el consumidor obtiene un plato de comida de calidad y a buen precio con el sistema de búsqueda que  le brindará al consumidor el platillo que se ajuste mejor a sus preferencias como restaurante, tipo de comida, rango de precio, entre otros.

- Hypothesis 2:  
 Creemos que agilizar la búsqueda de productos alimenticios que ofrecen los restaurantes se logrará si el representante de restaurante obtiene un menor porcentaje de desperdicios con la capacidad de   poder evitar el desperdicio de alimentos y generar ingresos con la venta de sus productos sobrantes a un buen precio a través de la aplicación.  

- Hypothesis 3:  
 Creemos que mejorar las propuestas del mercado se logrará si el representante de restaurante obtiene mejores ganancias gracias a la venta de residuos de comida con la capacidad de añadir sus promociones  en la plataforma para atraer consumidores.

- Hypothesis 4:  
  Creemos que mejorar las propuestas del mercado se logrará si el consumidor obtiene precios más bajos gracias a la compra de residuos de comida con la capacidad de poder pedir los alimentos que sobraron  de una gran cantidad de restaurantes a un precio accesible.

- Hypothesis 5:  
 Creemos que agilizar la búsqueda de productos alimenticios que ofrecen los restaurantes se logrará si el consumidor obtiene un plato de comida de calidad y a buen precio con la capacidad de poder   visualizar notificaciones de las promociones de sus restaurantes favoritos.

- Hypothesis 6:
 Creemos que mejorar las propuestas del mercado se logrará si el consumidor obtiene una mejor experiencia de adquisición de los productos residuales con la capacidad de poder calificar y dejar reseñas de  los restaurantes en los que pidieron.

- Hypothesis 7:
 Creemos que mejorar las propuestas del mercado se logrará si el consumidor obtiene una mejor experiencia de adquisición de los productos residuales con la capacidad de poder calificar y dejar reseñas de  los restaurantes en los que pidieron.  

#### 1.2.2.4. Lean UX Canvas

  ![image](https://github.com/Arquitectura-Software-2023/Project-Report/assets/89096127/c11ae688-02bc-4029-a001-c3b764d40cfb)

### 1.3. Segmentos objetivo  

Para definir los segmentos objetivos que se verían beneficiados en la solución de esta problemática, hemos realizado investigaciones que nos han ayudado a esclarecer dichos segmentos. Como en todo   proyecto, existen dos grandes grupos, los cuales son aquellos que invierten en el proyecto, más conocidos como clientes, y aquellos a los que consumen el producto o servicio, los cuales son los   consumidores. Dentro de estos grupos definimos a nuestros clientes como aquellos dueños(as) de restaurantes que desean incrementar sus ventas y evitar el desperdicio de comida, estos se encuentran en un
  rango de edad entre los 30 a 50 años, preocupados por el cuidado de los recursos del planeta, con conciencia ambiental y decidido a incrementar sus ganancias.  
  Por otro lado, en el sector de consumidores identificamos a aquellos comensales que desean adquirir alimentos por un bajo precio. Estos se encuentran en un rango de edades entre los 18 a 30 años, usuarios de diversas tecnologías, en muchos casos recién independizados, y que desean ayudar a disminuir el desperdicio de comida que generan los restaurantes. Asimismo, se ayudaría a familias que cuentan con algún dispositivo electrónico en casa y que deseen disminuir sus gastos en alimentos.  

## Capítulo II: Requirements Elicitation & Analysis

### 2.1. Competidores

### 2.1.1. Análisis competitivo

1. Too good to go es la aplicación más grande que lucha contra el desperdicio de alimentos de la actualidad. Con un aproximado de 5 millones de usuarios en el mundo en 9 países, muchos usuarios están  satisfechos, porque se evitó el desperdicio de comida desde el 2018.

      ![image](https://github.com/Arquitectura-Software-2023/Project-Report/assets/89096127/3c80e7a9-3a33-40f8-9f1d-ea377ffafbfe)

2. Phenix es la empresa emergente líder que lucha contra el desperdicio de la comida con sedes en diferentes partes del mundo y desde su fundación en 2014 a la fecha llevan recaudando 60 toneladas de  comida que sin su presencia hubieran sido desperdiciados. Dicha empresa tiene aliados como distribuidores, fabricantes, mayoristas y tiendas alimentarias.

      ![image](https://github.com/Arquitectura-Software-2023/Project-Report/assets/89096127/dd833f5f-14fd-4351-ba1d-82532e92684a)

3. Olio nace en el 2014 con la fundación de Teesa Cook, en mira a que en el mundo la tercera parte de alimentos que consumimos se tira a la basura esto, incentivó a poner en marcha a Olio. Dicho   startup conecta a vecinos entre sí y con negocios locales para que la comida que no es consumida se comparta en vez de tirarla a la basura. Alimentos, verduras y productos por vencer son ofertados de  una manera particular, y comercialmente bien adquiridos, a la fecha cuenta con alrededor de 5 millones de usuarios y 35 millones de porciones de comida compartida.

      ![image](https://github.com/Arquitectura-Software-2023/Project-Report/assets/89096127/0853750c-1c63-4484-a351-52bf6389d16a)

**¿Por qué llevar a cabo este análisis?**  

 Porque este análisis nos permitirá añadir nuevas funciones, mejorar las que ya tenemos y así ofrecer un servicio de calidad y competitivo.

 ¿Puede nuestra aplicación (y plataforma) competir con aplicaciones que tengas intereses comunes frente a la venta de comidas a un mejor precio que poseen las mismas características y funciones?

 | Competidor       | To Good to Go                                                   | Phenix                                                         | Olio                                                      |
|------------------|-----------------------------------------------------------------|----------------------------------------------------------------|-----------------------------------------------------------|
| Perfil           | Desde el año 2018, viene creciendo esta empresa...             | En el año 2014 nació esta prometedora idea de negocio...     | Por el 2014 nace Olio con el objetivo de compartir más... |
| Ventaja competitiva | La iniciativa del negocio involucra el compromiso...        | A la fecha 2.5 millones de usuarios vienen comprometidos...  | Alrededor de 5 millones de personas están registradas... |
| Perfil de Marketing | Mercado objetivo | Vende productos a nivel extranjero y abarca tiendas en diferentes partes de Europa, sin presencia en América. | Vende productos a nivel extranjero y abarca tiendas en diferentes partes de Europa, sin presencia en América. | Vende productos a nivel extranjero y abarca tiendas en diferentes partes de Europa, sin presencia en América. |
| Estrategias de marketing | Ofertar productos a un menor precio. | Diversidad de productos y platos, ofertas irresistibles por medio de su aplicativo. | Atención al cliente y facilidad de encontrar lo que el cliente viene a buscar. |
| Perfil de Producto | Productos & Servicios | Desde su año de fundación, viene beneficiando a gran cantidad de población... | Viene luchando por la rentabilidad económica de la sociedad, demostrando que si existe ideas para un mundo más justo, humano y sostenible... | Más de 35 millones de porciones de comida repartidas en el mundo, Olio crea un mundo donde nada valioso se desperdicie y todas las personas tengan suficiente qué comer sin destruir nuestro planeta en el proceso... |
| Precios & Costos | Ofrece costos y porciones de comida a un bajo precio. Irresistible en sus porciones de comida que comercializa. | Ofrece costos y porciones de comida a un bajo precio. Irresistible en sus porciones de comida que comercializa. | Ofrece costos y porciones de comida a un bajo precio. Irresistible en sus porciones de comida que comercializa. |
| Canales de distribución (Web y/o Móvil) | App móvil | App móvil | App móvil |
| Análisis SWOT    | **Fortalezas:** El usuario que pretenda acceder debe de hacerlo mediante una aplicación móvil, donde el usuario se registra y realiza sus pedidos. También tienen una página web. | **Fortalezas:** Phenix utiliza la aplicación móvil para captar clientes, a su vez una página que respalda el negocio. | **Fortalezas:** Utiliza una APP móvil y página web, interactiva eficaz y segura que ofrece las comidas que tienen. |
|                  | **Debilidades:** Solo tiene presencia en algunos países de Europa y es una empresa emergente con mínima población clientela. | **Debilidades:** Solo tiene presencia en algunos países de Europa y es una empresa emergente con mínima población clientela. | **Debilidades:** Solo tiene presencia en algunos países de Europa y es una empresa emergente con mínima población clientela. |
|                  | **Oportunidades:** Tiene aceptación en Europa y millones de usuario muestran su respaldo a la iniciativa. | **Oportunidades:** Tiene aceptación en Europa y millones de usuario muestran su respaldo a la iniciativa. | **Oportunidades:** Tiene aceptación en Europa y millones de usuario muestran su respaldo a la iniciativa. |
|                  | **Amenazas:** No presenta mercado en América y no comercializa por delivery. | **Amenazas:** No presenta mercado en América y no comercializa por delivery. | **Amenazas:** No presenta mercado en América y no comercializa por delivery. |

| Indicadores de Comparación | Too Good to Go                                                 | Phenix                                                       | Olio                                                      | Tasty Point                                                  |
|---------------------------|---------------------------------------------------------------|--------------------------------------------------------------|-----------------------------------------------------------|--------------------------------------------------------------|
| Años en el mercado        | Desde el año 2018, viene creciendo esta empresa, cumpliendo con 4 años en el mercado. | En el año 2014 nació esta prometedora idea de negocio que desde su presencia en el mercado viene generando gran aclamación por el público. | Por el 2014 nace Olio con el objetivo de compartir más, y desperdiciar menos comida. Esta empresa beneficia a muchas personas, tiene una aceptación única y sobre todo cuenta con gran respaldo. | Al ser un startup emergente, no cuenta con tiempo de experiencia. |
| Aceptación de la clientela | La iniciativa del negocio involucra el compromiso y el respaldo de casi 5 millones de usuarios en 9 países del mundo. | A la fecha 2.5 millones de usuarios vienen comprometidos con Phenix y siendo beneficiados de dicho startup. | Alrededor de 5 millones de personas están registradas en Olio. | En las entrevistas realizadas se evidencia el respaldo y el buen impacto que genera el startup emergente. |
| Impacto social             | Desde su año de fundación, viene beneficiando a gran cantidad de población, así tal que evitó que la tercera parte del desperdicio de comida sea una pérdida. | Viene luchando por la rentabilidad económica de la sociedad, demostrando que si existe ideas para un mundo más justo, humano y sostenible. | Más de 35 millones de porciones de comida repartidas en el mundo, Olio crea un mundo donde nada valioso se desperdicie y todas las personas tengan suficiente qué comer sin destruir nuestro planeta en el proceso. | Efectivamente el impacto social que tendría la app web es significativo, por lo que contribuimos con una noche causa y de una manera efectiva. |
| Tecnología utilizada para captar clientes | El usuario que pretenda acceder debe de hacerlo mediante una aplicación móvil, donde el usuario se registra y realiza sus pedidos. También tienen una página web. | Phenix utiliza la aplicación móvil para captar clientes, a su vez una página que respalda el negocio. | Utiliza una APP móvil y página web, interactiva eficaz y segura que ofrece las comidas que tienen. | La tecnología usada para lograr llegar a nuestros clientes es la App web y el uso de un catálogo de realidad virtual, donde se presentan los servicios y las novedades que ofrecemos. |
| Presencia en el extranjero  | Se originó en Dinamarca y a la fecha está fundado en países como: Noruega, Holanda, Alemania, Reino Unido, Francia, Bélgica, Suiza y España. No cuenta con tiendas en América, esto se torna difícil porque no permite extender su mercado. | Phenix está presente en 5 países del mundo con más de 30 filiales en diferentes ciudades. Presencia en pocos países del mundo, sigue siendo un startup emergente. | Olio va creciendo cada vez más y en 60 países del mundo tiene presencia. Alberga a 80 mil empleados entre chefs, cocineros y demás trabajadores. No presenta mucho público objetivo en América y mucho menos en Perú. Al no tener presencia presenta dificultad. | Se prevé que al momento de poner a disposición de las personas interesantes se irán sumando y al atravesar un año superar los 100.000 usuarios registrados en nuestra Aplicación Web. Somos un startup emergente y no tenemos experiencia en el mercado. Presenta cierta dificultad para impactar en el negocio. |

### 2.1.2. Estrategias y tácticas frente a competidores  

 Analizando nuestras propias debilidades, al ser un startup que recién ingresamos al mercado, no tenemos asegurados a los clientes y tampoco experiencia. Entonces, en base a las propias ideas y el   estudio previo a los competidores de Tasty Point, surgen las siguientes estrategias:  

- Establecer lazos de sociedad entre proveedores de las diferentes zonas del país (Costa, Sierra y Selva) para tener una mejor variedad de los platos y ser impartidos en la ciudad. Por lo tanto, se   considera ampliar la cantidad de asociados que proveen los recursos (mercadería a revender) mediante incentivos porcentuales de ganancia.  
- Crear mayor publicidad que exhibe nuestro startup, con el fin de auto promoverse y conseguir más alianzas con mercados, cadenas de restaurantes y diversas entidades públicas y privadas.
- Para conseguir ventaja sobre el competidor se estudia el mercado actual y la demanda. Es necesario enfocar el nicho de negocio acorde a los segmentos objetivos que buscamos.
  Haciendo un breve estudio sigiloso de las debilidades de los competidores de Tasty Point se plantean las siguientes tácticas con el fin de superarnos como startup.  
- Enfatizar la satisfacción y el feedback de nuestros clientes para así promover la comodidad y fidelidad para con nuestra marca.  
- Materializar los conceptos que presentamos con el fin de realizar teaser de nuestros cambios/mejoras y así recibir una precrítica.  
- Realizar campañas publicitarias para dar a conocer nuestra marca y así crear conciencia en las personas que nos desconocen.  
- Convencer a las personas que es de suma importancia cuidar la comida, por lo que es el primordial sustento de la vida.
- Impartir canales de publicidad, Radio, Facebook, Instagram: Con la idea de persuadir a la población juvenil y captar mayor número de usuarios.  
- Estar en constante innovación   y cambio, esto será útil para llamar la atención de los usuarios, especialmente los relacionados con VR.

### 2.2. Entrevistas

### 2.2.1. Diseño de entrevistas

 ¡Hola, buen día!, permítame presentarme y hablarle un poco acerca de mi proyecto, soy el estudiante [...] de la carrera de Ingeniería de Software. Mi proyecto trata acerca de la creación de una   aplicación en donde se publican y venden comidas que han sobrado del día, de restaurantes y de cualquier otro establecimiento de comida a un menor precio, esto con la finalidad de ayudar a disminuir el  desperdicio de comida y ofrecerlos a un precio accesible; para ello a mi equipo y a mí nos agradaría contar con su opinión, ¿podría concedernos una entrevista?  

- INTRODUCCIÓN  
  - ¿Cuál es su nombre?, ¿Cuál es su edad?, ¿Cuál es su formación?, ¿Dónde se ubica su negocio?  
- PRE-PROBLEMÁTICA  
  - ¿Qué tipo de alimentos venden en su establecimiento?  
  - ¿Cuál es la edad promedio de sus clientes?  
  - ¿Cuáles son los alimentos que más vende y cuáles son los que menos vende?  
  - ¿Le ha causado problemas el desperdicio de comida?  
- PROBLEMÁTICA  
  - ¿Qué sucede con los alimentos que sobran al final del día?  
  - ¿Qué porcentaje de sus ganancias se ve afectado por estas pérdidas?  
  - ¿Qué alternativa propondría para disminuir el desperdicio de comida?  
  - ¿Conoce alguna aplicación en dónde pueda ofertar la comida que le ha sobrado al final del día? De ser así, ¿cuáles y qué tal ha sido su experiencia?  
  - ¿Hace uso de algún medio para crecer sus ventas?  

- PRESENTACIÓN DE LA APP  
  - ¿Estaría dispuesto(a) a ofertar la comida que le resta al final del día?  
  - ¿Qué descuento aplicaría a sus comidas?  
  - ¿Se encontraría interesado en mostrar sus platos un entorno VR?  
  - ¿Le resultaría útil usar una App en dónde pueda ofertar sus alimentos? De ser así, ¿qué le gustaría que la App tuviera?  

### 2.2.2. Registro de entrevistas

Entrevista 1: Alejandro Rojas
![entrevista](https://media.discordapp.net/attachments/912089666939916348/1148765168013152398/image.png?width=1392&height=669)

- Duracion: 06:46
- Enlace: <https://upcedupe-my.sharepoint.com/:v:/g/personal/u202010196_upc_edu_pe/ETDhQlAQWthGipanM-mMBa4BXFzPBPXX0srJm7TCC5EydQ?e=6KtsbI>
- Análisis: Alejandro es un chico joven de 19  años que estudia la carrera de ciencias de la computacion, nos ha mencionado como es que nunca se habia percatado de la problematica que estamos tratando, siendo que la gente deja la comida desperdiciada, a su vez nos menciona que en la semana hasta entre 200 y 300 soles en comida y que le encantaria la idea de nuestra aplicacion.

Entrevista 2: Guisseppe Garrido Daza
![image](https://cdn.discordapp.com/attachments/1149534515509858338/1150420334923763842/image.png)

- Duracion: 06:45
- Enlace: <https://upcedupe-my.sharepoint.com/:v:/g/personal/u202010942_upc_edu_pe/ESrkBUt9F_hGnyZsi3zsCmwBIfXyJ5h6IJLv3_LbWr-NZA?>
- Resumen: Guisseppe es un joven de 20 años, estudiante de Ing Industrial de la Universidad Nacional Mayor de San Marcos. Él es una persona amable y muy estudiosa, se caracteriza por ser sociable, emprendedor y responsable. Suele utilizar los buscadores de Google, usa Facebook y WhatsApp para realizar sus consultas y tener una mayor comunicación con sus compañeros de estudio y a su vez estar actualizado. Él nos menciona su interés por Tasty Point y a su vez recalca el gran impacto que tendría esto dentro de la comunidad universitaria.

Entrevista 3: Hugo Pahuacho
![image](https://github.com/Arquitectura-Software-2023/Project-Report/assets/89096127/48172d63-1680-4ff7-b02f-55f22d1800a4)

- Duracion: 05:00
- Enlace: <https://upcedupe-my.sharepoint.com/:v:/g/personal/u201922910_upc_edu_pe/ERWU51GT8iFHpNfysZ7mpoEBP2d-AlppHdLSnTYeU_E2VQ?e=WCwIPn>
- Análisis: Es un chico universitario que en sus tiempos libres trabaja en una cafetería. Él nos comenta que vende tortas, sanguches y bebidas y que lo que más se vende son las dos últimas cosas. También, nos indica que pierde aproximadamente el 20% de lo que vende al final del día y que le gustaría aprovecharlo más.

Entrevista 4: Roberto Carlos
![image](https://cdn.discordapp.com/attachments/1149534515509858338/1150193394740625408/image.png?width=1392&height=669)

- Duracion: 08:09
- Enlace: <https://upcedupe-my.sharepoint.com/:v:/g/personal/u202010942_upc_edu_pe/ESrkBUt9F_hGnyZsi3zsCmwBIfXyJ5h6IJLv3_LbWr-NZA?e=EYltRK&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZyIsInJlZmVycmFsQXBwUGxhdGZvcm0iOiJXZWIiLCJyZWZlcnJhbE1vZGUiOiJ2aWV3In19>
- Análisis: Roberto Salazar Risco es un estudiante de 21 años que por vacaciones decidió abrir un foodtruck de comida rápida como alitas, hamburguesas, sándwiches, entre otros. Roberto nos comenta que el producto más vendido son sus hamburguesas y que el menos vendido son unas butifarras. Según él, el porcentaje de ganancias afectado es de aproximadamente el 5-8%. No ha llegado a ver una aplicación enfocada en evitar desperdicios. Él está dispuesto a dar un descuento alto con el fin de reducir los desechos de alimentos.

### 2.2.3. Análisis de entrevistas

**Segmento Cliente:**

Se entrevistaron a 2 personas del segmento representantes de las cadenas de restaurantes, y los resultados son los siguientes:
De los lugares visitados, las entrevistadas al responder la pregunta “¿Qué tipo de alimentos venden en su establecimiento?” hacen mención en su mayoría que venden comida rápida.

![g1](https://cdn.discordapp.com/attachments/1149534515509858338/1150409000022716477/image.png)

Se entrevistaron a 2 personas del segmento representantes de las cadenas de restaurantes, y los resultados son los siguientes:
De los lugares visitados, las entrevistadas al responder la pregunta “¿Qué tipo de alimentos venden en su establecimiento?” hacen mención en su mayoría que venden comida rápida.

![g2](https://cdn.discordapp.com/attachments/1149534515509858338/1150409847876104272/image.png)

El 100% de las entrevistadas respondió “sí” a la pregunta “¿Estaría dispuesto(a) a ofertar la comida que le resta al final del día?”, esto con la finalidad de incrementar sus ventas y reducir el desperdicio de comida, siendo parte del objetivo de la aplicación.

![g3](https://cdn.discordapp.com/attachments/1149534515509858338/1150410114268930078/image.png)

Cabe resaltar que ambos entrevistados están dispuestos a ofrecer descuentos de hasta el 20% con tal de evitar pérdidas y ambos poseen desde un 5% de pérdidas en alimentos que puede llegar hasta un 12%.

**Segmento Consumidor:**

Se entrevistaron a 2 personas del segmento consumidor, y los resultados son los siguientes:
De los entrevistados al responder la pregunta “¿Con qué frecuencia compra alimentos preparados en establecimientos?”, las respuestas son variadas, hay quien compran de 1 a 2 veces por semana, quién compra de 2 a 3 veces por semana. Estos datos son de ayuda para conocer la frecuencia posible con la que usarían la aplicación.

![g4](https://media.discordapp.net/attachments/1149534515509858338/1150415643573760000/image.png)

De la pregunta “¿Cuál es el promedio de dinero que gasta en dichos alimentos por semanas?”, se obtuvo como respuesta que llegan a usar cantidades entre 100 y 300 soles por semana, esto nos permite conocer los precios promedios a los que los restaurantes tendrán que ofertar sus platillos.
  
![g5](https://cdn.discordapp.com/attachments/1149534515509858338/1150416755471155300/image.png)

De la pregunta “¿Sabe usted qué ocurre con los alimentos que no son vendidos durante el día en un establecimiento de comida? De ser su respuesta no, ¿qué se imagina que ocurre con esos alimentos?”, la respuesta de los entrevistados fue que suponen que los desechan y esto les debe de generar pérdidas a los restaurantes.

![g6](https://cdn.discordapp.com/attachments/1149534515509858338/1150417583133179924/image.png)

De la pregunta “¿Usaría una app en donde pueda encontrar alimentos que han quedado en un establecimiento de comida?”, el 100% de los entrevistados nos comenta que lo harían porque los precios serian más baratos y estarian evitando el desecho de alimentos.

![g7](https://cdn.discordapp.com/attachments/1149534515509858338/1150418599467556864/image.png)

### 2.3. Needfinding

### 2.3.1. User Personas

**Segmento Cliente:**

![Segmento Cliente](https://cdn.discordapp.com/attachments/1149534515509858338/1149535401007124560/Imagen1.png)

**Segmento Consumidor:**

![Segmento Consumidor](https://cdn.discordapp.com/attachments/1149534515509858338/1149536883643273347/Imagen2.jpg)

### 2.3.2. User Task Matrix

![Task Matrix](https://cdn.discordapp.com/attachments/1149534515509858338/1150074524415565834/image.png)
  
### 2.3.3. Empathy Mapping

**Segmento Cliente:**

![Segmento Cliente](https://cdn.discordapp.com/attachments/1149534515509858338/1149538442393432155/Imagen3.png)

**Segmento Consumidor:**

![Segmento Consumidor](https://cdn.discordapp.com/attachments/1149534515509858338/1149538756341280858/Imagen4.png)

### 2.3.4. As-is Scenario Mapping

**Consumidor:** los usuarios que van a comprar los alimentos.

| Steps | Buscar opciones en el entorno | Revisar las opciones por internet | Realizar pedido | Recibir pedido |
| -------------- | -------------- | -------------- | -------------- | -------------- |
| Doing | Buscar comida dentro de la casa | - Buscar opciones de comida a domicilio por internet. - Seleccionar cualquier aplicación | Seleccionar una opción económica dentro de la aplicación | Recibir el pedido solicitado por delivery |
| Thinking | No hay comida disponible, debo de buscar opciones por internet | Existen muchas aplicaciones de comida a domicilio | Me hubiera gustado una mejor oferta | Espero que el pedido sea de mi agrado |
| Feeling | Desilusionado | Abrumado | Frustrado | Decepcionado |

**Cliente:** cadena de restaurantes y comidas.

| Steps | Seleccion de Platos a Ofertar | Oferta los Platos | Venta de los Platos| Analisis de Ingreso |
| -------------- | -------------- | -------------- | -------------- | -------------- |
| Doing | - Revisar el stock del restaurante. - Separar los Platos que estan por caducar | - Buscar la mejor oferta de ofertarlos. - Colocar la oferta en la carta del restaurante. | - Pagar por marketing. - Vender los platos. | Realizar el presupuesto maestro |
| Thinking | En cuanto tengo que reducir el precio del plato para atraer consumidores? | Las nuevas ofertas traerán consumidores? | - Espero que la inversión no sea en vano. - Esperemos que se vendan todos los platos. | Se obtuvo ingresos? |
| Feeling | Angustia | Dudoso | Preocupado | Preocupado |

## Capítulo III: Requirements Specification

### 3.1. To-Be Scenario Mapping

**Consumidor:** los usuarios que van a comprar los alimentos.

| Steps | Buscar opciones en el entorno | Revisar las opciones por internet | Realizar pedido | Recibir pedido |
| -------------- | -------------- | -------------- | -------------- | -------------- |
| Doing | Buscar comida dentro de la casa | - Buscar opciones de comida a domicilio por internet. - Seleccionar Tasty Point por su iniciativa | Seleccionar el plato de comida que deseo del catálogo en realidad virtual | Recibir el pedido solicitado por delivery |
| Thinking | No hay comida disponible, debo de buscar opciones por internet | No tuve problemas en escoger al servicio a domicilio | Los precios son muy bajos | Espero que el pedido sea de mi agrado |
| Feeling | Desilusionado | Aliviado | Sorprendido | Satisfecho |

**Cliente:** cadena de restaurantes y comidas.

| Steps | Seleccion de Platos a Ofertar | Oferta los Platos | Venta de los Platos| Analisis de Ingreso |
| -------------- | -------------- | -------------- | -------------- | -------------- |
| Doing | - Revisar el stock del restaurante. - Separar los Platos que estan por caducar | - Buscar la mejor oferta de ofertarlos. - Entregar la informacion necesaria a TastyPoint | Verificar Pedidos | Realizar el presupuesto maestro |
| Thinking | Cuanto tengo que reducir el precio del plato para atraer consumidores? | Ataeremos consumidores? Los precios son accesibles? | Esperemos que se vendan todos los platos. | Se obtuvo ingresos? |
| Feeling | Angustia | Dudoso | Con calma | Ansioso |

### 3.2. User Stories

#### User Stories Consumer

| Story ID | Titulo | Descripcion | Criterios de Aceptacion | Escenarios |
|-----------|-----------|-----------|-----------|-----------|
| US01 | Registro de Consumidor | Como consumidor quiero crear una cuenta para acceder a la aplicación. | CA1: Dado que el consumidor se encuentra en la ventana de registro y completa todos los campos. Cuando presiona el botón registrarse. Entonces podrá acceder a la aplicación. CA2: Dado que el consumidor se encuentra en la ventana de registro y no completa todos los campos obligatorios. Cuando presiona el botón registrarse. Entonces esos campos se marcan de rojo Y se muestra el mensaje: “Complete los campos obligatorios”. CA3: Dado que el consumidor se encuentra en la ventana de registro y completa erróneamente los campos. Cuando presiona el botón registrarse. Entonces se muestra el siguiente mensaje: “Complete los campos correctamente”. | E1: El consumidor quiere registrarse en la aplicación. E2: El consumidor no completa los campos obligatorios. E3: El consumidor intenta registrarse, pero no completa con datos correctos los campos obligatorios. |
| US02 | Monitorear el perfil | Como consumidor quiero ver el perfil de mi cuenta para corroborar que mis datos sean correctos. | Dado que el consumidor quiere ver su perfil. Cuando presiona el icono de perfil ubicado en la sección de menú. Entonces la aplicación muestra la información del perfil del consumidor. | El consumidor quiere ver su perfil. |
| US03 | Cerrar sesión de consumidor | Como consumidor quiero cerrar sesión para salir de mi cuenta.| CA1: Dado que el consumidor se encuentra en la aplicación. Cuando presiona el icono de perfil ubicado en la sección de menú. Entonces se le mostrará un mensaje: ¿Está seguro de cerrar sesión? Y el consumidor selecciona la opción sí para cerrar la sesión. CA2: Dado que el consumidor se encuentra en la aplicación. Cuando presiona el botón de cerrar sesión. Entonces se le mostrará un mensaje: ¿Está seguro de cerrar sesión? Y el consumidor selecciona la opción no para mantener iniciada la sesión. | E1:  El consumidor quiere cerrar sesión en el sistema. E2: El consumidor presiona por error el botón de “Cerrar sesión “.|
| US04 | Pagar el envío de productos | Como consumidor quiero pagar el envio del pedido. | CA1: Dado que el consumidor se encuentra en la ventana “Pago”. Cuando se llena el campo de número de cuenta correctamente y presione el botón de Pagar. Entonces la aplicación mostrará un icono de verificado. CA2:  Dado que el consumidor se encuentra en la ventana “Pago”. Cuando no se llena el campo de número de cuenta correctamente Y presione el botón de Pagar. Entonces la aplicación mostrará un mensaje de error y el borde del campo se volverá rojo.| E1: El consumidor desea colocar su cuenta bancaria. E2: El consumidor rellena el campo de su cuenta bancaria incorrectamente. |
| US05 | Visualizar todas las notificaciones | Como consumidor, quiero visualizar las notificaciones para estar informado sobre las ofertas que ofrezcan los restaurantes. | Dado que el consumidor se encuentra en la aplicación, cuando ingresa a la sección de notificaciones, entonces le aparecen las notificaciones realizadas por los restaurantes registrados en la aplicación. |  Ver ofertas publicadas por restaurantes. |
| US06 | Fijar favoritos | Como consumidor quiero guardar la información de mis productos favoritos | CA1: Dado que el consumidor, se encuentra en la ventana “Lista de productos”, cuando presiona el icono de corazón vacío que posee el artículo en la lista de productos publicados por los restaurantes registrados en la aplicación, entonces se añaden los datos del producto a la sección de favoritos y el icono de corazón vacío cambia por uno lleno. CA2: Dado que el consumidor, se encuentra en la ventana “Lista de productos”, cuando presiona el icono de corazón lleno que posee el artículo en la lista de productos publicados por los restaurantes registrados en la aplicación, entonces se eliminan los datos del producto a la sección de favoritos y el icono de corazón lleno cambia por uno vacío. | E1: Guardar productos favoritos. E2: Eliminar producto de favoritos |
| US07 | Visualizar productos y sus datos | Como consumidor quiero ver la lista de los productos publicados por los restaurantes registrados en la aplicación para poder comprarlos. | CA1: Dado que el consumidor ha inicializado su sesión, cuando presione el icono de Lista en el menú entonces será dirigido a la ventana de “Lista de productos”, y podrá visualizar los productos organizados con sus respectivas fotos y ciertos datos puntuales como descripción. CA2: Dado que el consumidor ha inicializado su sesión, cuando presione el icono de Lista en el menú entonces será dirigido a la ventana de “Lista de productos”, y podrá visualizar el mensaje: “No hay productos publicados”. | E1: El consumidor quiere visualizar algunos productos para comprarlos. E2: El consumidor quiere visualizar algunos productos para comprarlos, pero no hay productos. |
| US08 | Filtrar restaurante | Como consumidor quiero filtrar la lista de restaurantes registrados en la aplicación para poder encontrar rápidamente los productos de mi restaurante de preferencia. | CA1: Dado que el consumidor está en la sección Lista de productos, cuando ingrese el nombre del restaurante en la barra de navegación ubicado en la parte superior, entonces se mostrarán los datos de los productos de los restaurantes registrados en la aplicación. CA2: Dado que el consumidor está en la sección Lista de productos, cuando ingrese el nombre del restaurante en la barra de navegación ubicado en la parte superior, entonces se mostrará el mensaje: “Restaurante no encontrado”. | E1: El consumidor visualiza los restaurantes deseados. E2: No hay restaurantes registrados en la aplicación con el nombre del usuario. |
| US09 | Compartir comentario| Como consumidor quiero redactar un comentario sobre un determinado restaurante acerca de mi experiencia con ellos para poder compartir mi opinión con los demás.| Dado que el consumidor se encuentra en la ventana de reseñas, cuando ingrese su comentario y presione el botón de publicar entonces se publicará el comentario. | El consumidor exceda el límite de caracteres permitidos. |
| US10 | Filtrar productos | Como consumidor quiero filtrar la lista de productos registrados en la aplicación para poder encontrar rápidamente el producto que deseo. | CA1: Dado que el consumidor está en la sección Lista de productos, cuando ingrese el nombre del producto en la barra de navegación ubicado en la parte superior, entonces se mostrarán los datos de los productos de los restaurantes registrados en la aplicación. CA2: Dado que el consumidor está en la sección Lista de productos, cuando ingrese el nombre del producto en la barra de navegación ubicado en la parte superior, entonces se mostrará el mensaje: “Producto no encontrado”. | E1: El consumidor visualiza los productos deseados. E2: No hay productos registrados en la aplicación con el nombre del usuario. |

#### User Stories Business

| Story ID | Titulo | Descripcion | Criterios de Aceptacion | Escenarios |
|-----------|-----------|-----------|-----------|-----------|
| US11 | Registro de Cliente | Como cliente quiero crear una cuenta para acceder a la aplicación. |CA1:  Dado que el cliente se encuentra en la ventana de registro y completa todos los campos. Cuando presiona el botón registrarse. Entonces podrá acceder a la aplicación. CA2: Dado que el cliente se encuentra en la ventana de registro y no completa todos los campos obligatorios. Cuando presiona el botón registrarse. Entonces esos campos se marcan de rojo y se muestra el mensaje: “Complete los campos obligatorios”. CA3: Dado que el cliente se encuentra en la ventana de registro y completa erróneamente los campos. Cuando presiona el botón registrarse. Entonces se muestra el siguiente mensaje: “Complete los campos correctamente”.| E1: El cliente quiere registrarse en la aplicación. E2: El cliente no completa los campos obligatorios. E3: El cliente intenta registrarse, pero no completa con datos correctos los campos obligatorios.|
| US12 | Pago de suscripción | Como cliente deseo poder pagar la suscripción desde la aplicación para acceder a más beneficios. | CA1: Dado que el cliente ya se encuentra registrado. Cuando el cliente desee usar alguna función de la aplicación. Entonces la aplicación le mostrará una pantalla con las opciones de suscripción al servicio. CA2: Dado que el cliente visualiza las opciones de suscripción. Cuando el cliente selecciona una de las opciones. Entonces la aplicación lo redirigirá a una pantalla en la que podrá ingresar la tarjeta de crédito o débito con la que realizará el pago. CA3: Dado que el cliente ya ingresó los datos necesarios para el pago. Cuando el cliente seleccione el botón Pagar. Entonces la aplicación le mostrará un mensaje de “Pago realizado con éxito”. Y el cliente podrá utilizar la aplicación. CA4: Dado que el cliente ya ingresó los datos necesarios para el pago. Cuando el cliente seleccione el botón Pagar. Y la aplicación detecte algún inconveniente. Entonces la aplicación le mostrará un mensaje de “El pago no se pudo realizar. Inténtelo de nuevo más tarde”. | E1: Visualización de las opciones de suscripción E2: El cliente ingresa los datos de su tarjeta. E3: Realización exitosa del pago E4: Realización fallida del pago |
| US13 | Publicación de platos sobrantes | Como cliente deseo poder publicar los platos que me sobraron en el día para poder vender lo máximo posible. | CA1: Dado que el cliente posee excedentes de platos del día. Y el cliente se encuentra en la ventana de “Catálogo” y desea publicar sus excedentes. Cuando el cliente seleccione la opción Publicar. Entonces la aplicación le preguntará qué desea publicar (platos de comida o insumos) CA2: Dado que el cliente se encuentra en la pantalla de elección de plato o insumo. Cuando el cliente escoja la opción de plato de comida. Entonces la aplicación le pedirá que ingrese una serie de datos sobre el plato (nombre del plato, cantidad, precio verdadero, precio ofrecido, entre otros). CA3: Dado que el cliente se encuentra en la pantalla de completado de datos del plato de comida. Cuando el cliente complete correctamente los datos. Y seleccione la opción publicar. Entonces la aplicación le mostrará un mensaje “Publicación realizada”.| E1: Cliente selecciona producto a publicar E2: Cliente ingresa los datos del plato E3: Cliente realiza la publicación |
| US14 | Publicación de insumos sobrantes | Como cliente quiero publicar los insumos sobrantes del día para reducir al mínimo los desperdicios de estos. | CA1: Dado que el cliente posee excedentes de insumos del día. Y el cliente se encuentra en la ventana “Catálogo” y desea publicar sus excedentes. Cuando el cliente seleccione la opción Publicar. Entonces la aplicación le preguntará qué desea publicar (platos de comida o insumos) CA2: Dado que el cliente se encuentra en la pantalla de elección de plato o insumo. Cuando el cliente escoja la opción de insumo. Entonces la aplicación le pedirá que ingrese los datos del insumo (nombre del insumo, porciones, precio estimado, entre otros). CA3: Dado que el cliente se encuentra en la pantalla de completado de datos del insumo. Cuando el cliente complete correctamente los datos. Y seleccione la opción publicar. Entonces la aplicación le mostrará un mensaje “Publicación realizada”.| E1: Cliente selecciona producto a publicar E2: Cliente ingresa descripción del insumo E3: Cliente realiza la publicación |
| US15 | Medios de contacto | Como cliente quiero enlazar todos los medios de comunicación que poseo para permitir a mis consumidores contactarse directamente con nosotros. | Dado que el cliente se encuentra en la ventana “Perfil”, cuando selecciona “Agregar redes sociales” y los agrega, entonces la aplicación mostrará un mensaje “Se agregó con éxito”. | Añadir redes sociales |
| US16 | Ver opciones disponibles | Como cliente quiero ver las opciones que ofrece Tasty Point para conocer el funcionamiento de la app y elegir alguna de sus opciones disponibles. | Dado que el cliente ha iniciado sesión, se encuentra en la ventana principal de Tasty point y desea ver las opciones disponibles de la app. Cuando el cliente seleccione el símbolo listo. Entonces la aplicación mostrará las opciones disponibles: "Inicio", "Agregar", "Catálogo", "Perfil”, en formato de lista. | El cliente ingresa correctamente a la lista de opciones. |
| US17 | Ver pedidos |Como cliente quiero ver la lista de pedidos solicitados en mi restaurante, para conocer la demanda a través de la App web. | Dado que el cliente ha iniciado sesión, se encuentra en la ventana principal de Tasty point y hace clic en la sección “Órdenes”, cuando el cliente se encuentre en dicha sección, entonces aparecerá una lista con los nombres de los consumidores que realizaron un pedido en específico con fecha, hora y cantidad ordenada. | El cliente ingresa al registro de pedidos. |
| US18 | Ver el catálogo de platos e insumos | Como cliente quiero ver el catálogo actual de platos e insumos ofrecidos por mi establecimiento para corroborar que los datos de la App coincidan con mi inventario. | CA1: Dado que el cliente ha iniciado sesión, se encuentra en la lista de opciones ofrecida de Tasty point y desea revisar su catálogo. Cuando el cliente seleccione la opción "Catálogo". Entonces la aplicación mostrará la totalidad de platos e insumos registrados por el cliente, junto a datos pertinentes como: la cantidad actual, reservas hechas y tipo de recojo o envío disponible. CA2: Dado que el cliente se encuentra en la lista de platos e insumos disponibles ofrecidos por su establecimiento, y desea ver sólo los platos o insumos ofrecidos por su establecimiento. Cuando el cliente seleccione la opción filtro y elija la opción “platos” o “insumos”. Entonces la aplicación listará solo platos o solo insumos (dependiendo de la opción del cliente) junto a sus datos pertinentes. | E1: El cliente elige la opción catálogo. E2: El cliente elige ver solo platos o solo insumos del catálogo. |
| US19 | Abrir vista de consumidor | Como cliente quiero contar con la vista de consumidor para asegurar que mis productos se vean atractivos para los consumidores. | Dado que el cliente se encuentra en la ventana “Catálogo”, Cuando el cliente presione la opción: “Vista de consumidor”. Entonces la aplicación mostrará la ventana “Vista de consumidor” con los productos organizados de la forma en las que se le presenta al cliente. | El cliente ingresa a “vista de consumidor” |
| US20 | Editar las características de un plato o insumo |Como cliente quiero ser capaz de editar las características que coloqué sobre algún plato o insumo para corregir errores o actualizar la información. | CA1: Dado que el cliente se encuentra en la ventana “Catálogo” y quiera editar algún dato presentado. Cuando el cliente seleccione el botón editar del plato a editar. Entonces la aplicación permitirá la edición de los datos o multimedia ingresados (Nombre del plato, precio real, precio ofrecido, tipo de recojo o envío, foto del plato/insumo, etc). CA2: Dado que el cliente ha terminado de editar los datos requeridos y quiere guardar los cambios. Cuando el cliente elija el botón aceptar. Entonces se guardará y actualizará la información ofrecida; y se mostrará una ventana emergente de “Se han guardado los cambios”. | E1: El cliente ingresa correctamente al modo edición. E2: El cliente guarda correctamente los datos editados. |
| US21 | Contar con un CTA (Call To Action) potencialmente atractivo | Como cliente es de mi interés que las ventas aumenten, por lo tanto, es de suma importancia que dentro de la app exista algún botón o enlace que los direccione a la carta disponible en mi restaurante y asegurar su compra. | Dado que el cliente se encuentra dentro de la aplicación cuando decida qué platillo consumir, entonces aparecen CTA atractivos de los restaurantes asociados a la aplicación, apareciendo botones con enlaces que los envía a la página del restaurante. | El cliente asegura una venta y se guarda el registro del platillo, siendo así que para la compra futura se recomiendan platillos similares. |
| US22 | Poder leer los comentarios de los usuarios. | Como cliente quiero leer el feedback de los comensales para mejorar. | Dado que el cliente se encuentra dentro de la ventana “Reseñas de consumidores” cuando se dirige al área de opiniones, entonces puede leer los comentarios de los consumidores. | El cliente entra en la sección de consumidores y visualiza quiénes han hecho comentarios. |

#### User Stories Landing Page

| Story ID | Titulo | Descripcion | Criterios de Aceptacion | Escenarios |
|-----------|-----------|-----------|-----------|-----------|
| US23 | Botón call to action | Como usuario deseo que el landing page posea un botón call-to-action para poder acceder directamente hacia la aplicación | Dado que el usuario se encuentra en el landing page. Cuando el usuario seleccione el botón Call to action llamado Comenzar. Entonces el sistema redirigirá al usuario a la aplicación web. | Presión del botón CTA|
| US24 | Visualización de planes de suscripción. | Como usuario deseo poder visualizar los planes de suscripción en el landing page para poder informarme cuanto son las cantidades por pagar por el servicio. | CA1: Dado que el usuario se encuentra en el landing page. Cuando el usuario seleccione la opción Planes de suscripción. Entonces el landing page le mostrará los planes de suscripción. CA2: Dado que el usuario se encuentra en el landing page. Cuando el usuario deslice el landing page hacia abajo. Entonces la aplicación permitirá visualizar los planes de suscripción. | E1: Selección de opción para visualizar planes. E2:Desliza la pantalla para visualizar planes.|
| US25 | Visualización de redes sociales | Como usuario deseo poder acceder a las redes sociales del startup por medio del landing page para conocer más acerca de este.|Dado que el usuario se encuentra en el landing page. Cuando el usuario deslice la página hasta el final. Entonces la aplicación mostrará el footer en el cual se encontrarán las redes sociales y demás información.|Visualización de redes sociales en el Footer.|
| US26 | Web responsive | Como usuario deseo que la aplicación web sea totalmente responsive para poder usarlo desde distintos dispositivos. | Dado que el usuario utiliza el landing page. Cuando el usuario ingresa a la aplicación desde distintos dispositivos. Entonces la aplicación se adaptará a todos los dispositivos. Y la aplicación continuará funcional y visualmente estable.|Usuario ingresa desde distintos dispositivos.|
| US27 | Visualizar la sección home del landing page | Como usuario quiero ver la sección “home” para ver la información principal. | Dado que el usuario se encuentra en el landing page, cuando se dirija a la sección de home, entonces visualiza una breve descripción de la aplicación e información de sus segmentos. | Usuario se dirige a la sección “home” de la landing page.|
| US28 | Visualizar la sección "about us" en landing page | Como usuario quiero ver la sección “about us” para saber porque TastyPoint es innovadora en el área de comida a domicilio. | Dado que el usuario se encuentra en el landing page, cuando se dirija a la sección de about us”, entonces visualizará la información de TastyPoint. | Usuario se dirige a la sección “about us” de la landing page.
| US29 |Visualizar la sección "segments" en landing page | Como usuario quiero ver la sección “segments” para conocer a quienes está dirigida la aplicación y sus beneficios.|Dado que el usuario se encuentra en el landing page, cuando se dirija a la sección de “segments”, entonces visualiza el público objetivo de TastyPoint y las características de la aplicación en cada uno.|Usuario se dirige a la sección “segments” de la landing page|

### 3.3. Impact Mapping

**Segmento Cliente:**
![Impact Map 1](https://media.discordapp.net/attachments/912089666939916348/1148756492040802304/Flowchart.jpg?width=1397&height=669)

**Segmento usuario:**
![Impact Map 2](https://media.discordapp.net/attachments/912089666939916348/1148762107676987412/Flowchart_1.jpg?width=1047&height=669)

### 3.4. Product Backlog

| #Orden | User Story ID | Título | Descripción | Story Points (1/2/3/5/8) |
|-----------|-----------|-----------|-----------|-----------|
| 1 | US23 | Botón call to action | Como usuario deseo que el landing page posea un botón call-to-action para poder acceder directamente hacia la aplicación. | 1
| 2 | US27 | Visualizar la sección home del landing page | Como usuario quiero ver la sección “home” para ver la información principal.| 2
| 3 | US28 | Visualizar la sección "about us" en landing page | Como usuario quiero ver la sección “about us” para saber porque TastyPoint es innovadora en el área de comida a domicilio.| 1
| 4 | US29 | Visualizar la sección "segments" en landing page. | Como usuario quiero ver la sección “segments” para conocer a quienes está dirigida la aplicación y sus beneficios. | 1
| 5 | US24 | Visualización de planes de suscripción.|Como usuario deseo poder visualizar los planes de suscripción en el landing page para poder informarme cuanto son las cantidades por pagar por el servicio.|2
| 6 | US25|Visualización de redes sociales.|Como usuario deseo poder acceder a las redes sociales del startup por medio del landing page para conocer más acerca de este.|1
| 7 | US13|Publicación de platos sobrantes|Como cliente deseo poder publicar los platos que me sobraron en el día para poder vender lo máximo posible|5
| 8 | US14|Publicación de insumos sobrantes|Como cliente quiero publicar los insumos sobrantes del día para reducir al mínimo los desperdicios de estos|5
|9|US20|Editar las características de un plato o insumo|Como cliente quiero ser capaz de editar las características que coloqué sobre algún plato o insumo para corregir errores o actualizar la información.|3
|10|US21|Contar con un CTA (Call To Action) potencialmente atractivo|Como cliente es de mi interés que las ventas aumenten, por lo tanto, es de suma importancia que dentro de la App exista algún botón o enlace que los direccione a la carta disponible en mi restaurante y asegurar su compra.|5
|11|US18|Ver el catálogo de platos e insumos|Como cliente quiero ver el catálogo actual de platos e insumos ofrecidos por mi establecimiento para corroborar que los datos de la app coincidan con mi inventario.| 3
|12|US12|Pago de suscripción|Como cliente deseo poder pagar la suscripción desde la aplicación para facilitar un control de pagos|5
|13|US07|Visualizar productos y sus datos|Como consumidor quiero ver la lista de los productos publicados por los restaurantes registrados en la aplicación para poder comprarlos.|3
|14|US17|Ver pedidos|Como cliente quiero ver la lista de pedidos solicitados en mi restaurante, para conocer la demanda a través de la App web.|3
|15|US08|Filtrar restaurante|Como consumidor quiero filtrar la lista de restaurantes registrados en la aplicación para poder encontrar rápidamente los productos de mi restaurante de preferencia.|3
|16|US10|Filtrar productos|Como consumidor quiero filtrar la lista de productos registrados en la aplicación para poder encontrar rápidamente el producto que deseo.|3
|17|US06|Fijar favoritos|Como consumidor quiero clasificar de manera favorita mis productos para lograr visualizar la disponibilidad en la sección “Mis favoritos”|3
|18|US04|Pagar el envío de productos|Como consumidor quiero pagar mi envío para recibirlo plácidamente en mi casa|5
|19|US09|Compartir comentario|Como consumidor quiero redactar un comentario sobre algo en específico para poder compartir mi experiencia con los demás.|2
| 20|US22|Poder leer los comentarios de los usuarios|Como cliente quiero leer el feedback de los comensales para mejorar.|3
|21|US16|Ver opciones disponibles|Como cliente quiero ver las opciones que ofrece Tasty Point para conocer el funcionamiento de la app y elegir alguna de sus opciones disponibles.|2
|22|US19|Abrir vista de consumidor|Como cliente quiero contar con la vista de consumidor para asegurar que mis productos se vean atractivos para los consumidores.|3
|23|US15|Medios de contacto|Como cliente quiero enlazar todos los medios de comunicación que poseo para permitir a los clientes contactarse directamente con nosotros.|2
|24|US05|Visualizar todas las notificaciones|Como consumidor, quiero visualizar las principales notificaciones para estar informado sobre las ofertas y promociones que ofrezca la aplicación|2
|25|US11|Registro de cliente|Como cliente deseo poder registrarme en la aplicación para acceder a todos sus beneficios|3
|26|US01|Registro de Consumidor|Como consumidor quiero crear una cuenta para poder realizar compras de platos de comida a un bajo precio.|3
|27|US02|Monitorear el perfil|Como consumidor quiero ver el perfil de mi cuenta para corroborar que mis datos sean correctos.|3
|28|US03|Cerrar sesión de consumidor|Como consumidor deseo poder cerrar sesión para no dejar expuesta mi cuenta en mi ordenador|2
|29|US28|Web responsive|Como usuario deseo que la aplicación web sea totalmente responsive para poder usarlo desde distintos dispositivos.|2

## Capítulo IV: Solution Software Design

### 4.1. Strategic-Level Attribute-Driven Design

### 4.1.1. Design Purpose

Primero, es necesario recalcar nuestras 2 intenciones al crear la marca: Evitar el desperdicio de comida, y distribuir comida buena y barata.
Al fusionar estas 2 ideas, conseguimos Tasty point (algo como los Recycling Points/puntos de reciclaje). Un punto al que cualquiera puede acceder, donde puedes obtener buena comida y además ayudar al medio ambiente combatiendo el desperdicio de alimentos.
Nuestro punto es... hay buena comida aquí. ¡Ven a conseguirla!
El color principal de la marca es el Naranja: Este representa la vitalidad y confiabilidad que queremos representar para nuestros clientes.

![image](https://github.com/Arquitectura-Software-2023/Project-Report/assets/89089512/7673e8bf-b2a2-43ab-8e92-9f9f236b1f05)

Colors:

![image](https://github.com/Arquitectura-Software-2023/Project-Report/assets/89089512/42dfb1d8-7f9b-4329-9e7f-cdf836121c03)

Nuestra aplicación web usará el Patrón en Z:

![image](https://github.com/Arquitectura-Software-2023/Project-Report/assets/89089512/a242fb41-8bc5-4113-a49a-2de56cae7ffd)

### 4.1.2. Attribute-Driven Design Inputs

#### 4.1.2.1. Primary Functionality (Primary User Stories)
  
Criterios considerados en el diseño de Tasty Point:

#### Web Usability

- Facilita la interacción gracias el uso de fuentes distinguibles y del tamaño adecuado.
- Estructura el contenido: navegación en forma Z
- Simplifica y sintetiza: Textos directos sin perder la amabilidad que queremos proyectar como marca.

#### Primary User Stories Consumer

| Story ID | Titulo | Descripcion | Criterios de Aceptacion | Escenarios |
|-----------|-----------|-----------|-----------|-----------|
| US01 | Registro de Consumidor | Como consumidor quiero crear una cuenta para acceder a la aplicación. | CA1: Dado que el consumidor se encuentra en la ventana de registro y completa todos los campos. Cuando presiona el botón registrarse. Entonces podrá acceder a la aplicación. CA2: Dado que el consumidor se encuentra en la ventana de registro y no completa todos los campos obligatorios. Cuando presiona el botón registrarse. Entonces esos campos se marcan de rojo Y se muestra el mensaje: “Complete los campos obligatorios”. CA3: Dado que el consumidor se encuentra en la ventana de registro y completa erróneamente los campos. Cuando presiona el botón registrarse. Entonces se muestra el siguiente mensaje: “Complete los campos correctamente”. | E1: El consumidor quiere registrarse en la aplicación. E2: El consumidor no completa los campos obligatorios. E3: El consumidor intenta registrarse, pero no completa con datos correctos los campos obligatorios. |
| US02 | Monitorear el perfil | Como consumidor quiero ver el perfil de mi cuenta para corroborar que mis datos sean correctos. | Dado que el consumidor quiere ver su perfil. Cuando presiona el icono de perfil ubicado en la sección de menú. Entonces la aplicación muestra la información del perfil del consumidor. | El consumidor quiere ver su perfil. |
| US03 | Cerrar sesión de consumidor | Como consumidor quiero cerrar sesión para salir de mi cuenta.| CA1: Dado que el consumidor se encuentra en la aplicación. Cuando presiona el icono de perfil ubicado en la sección de menú. Entonces se le mostrará un mensaje: ¿Está seguro de cerrar sesión? Y el consumidor selecciona la opción sí para cerrar la sesión. CA2: Dado que el consumidor se encuentra en la aplicación. Cuando presiona el botón de cerrar sesión. Entonces se le mostrará un mensaje: ¿Está seguro de cerrar sesión? Y el consumidor selecciona la opción no para mantener iniciada la sesión. | E1:  El consumidor quiere cerrar sesión en el sistema. E2: El consumidor presiona por error el botón de “Cerrar sesión “.|

Inclusive design:
Los servicios brindados por la página deben ser accesibles a todo nuestro público objetivo, en este caso, ya que nuestro público objetivo abarca personas entre 20 y 40 años, las pautas consideradas son:
• Colores contrastantes y fuentes distinguibles para los usuarios con problemas de visión.
• Descripción de las imágenes empleadas para lectores de pantalla.
• Consistencia externa: Cumplir con los patrones de diseño comunes
• Formato de imágenes png para conservar la calidad.
Internationalization and Accessibility:
El idioma por defecto empleado en los productos para la solución de este proyecto es el inglés.

Responsive Web Design: Tanto el Landing page como la app web responden al dispositivo en el que el usuario ingresa. Ya que cuentan con una versión en vista web y mobile.

#### 4.1.2.2. Quality attribute Scenarios

#### Landing page

En el landing page se organizará el contenido de forma jerárquica. Mostrando primero una breve descripción de Tasty Point y luego ramificando las entradas para los 2 públicos objetivos a los que queremos llegar.

#### App web

En la aplicación web, se mostrarán los platos ordenados por tópicos, desde el más popular, hasta el menos popular.
La aplicación también contará con opciones para cambiar el orden en que se presentan los productos. Por ejemplo: Ordenado por fechas: del más reciente al más antiguo, ordenado por fechas: del más antiguo al más reciente, ordenado en orden alfabético: a – z, ordenado en orden alfabético: z – a, etc.

#### 4.1.2.3. Constraints

#### Landing page constrains

En el encabezado del landing page se emplean las etiquetas de “Home”, “About us”, “Features”, “Pricing” y el botón “Sign up”; que direccionan al usuario a la sección elegida de la página web.
También se emplearon los botones: “Customers” y “Business”.
Que direccionan a los usuarios a la sección de la página destinada para ellos.
App web:
En la aplicación web se mostrarán las secciones en una barra lateral a la izquierda de la pantalla. Estas direccionarán a la sección que busque el usuario.
Landing page:
Título: Tasty Point: The best way to help reduce food waste in Peru.
Description: With Tasty Point, you can help fight food waste. We have different environments according to the segment to which it belongs.
Keywords: “comida”, “medio ambiente”, “comida económica”, “ofertas de comida”, “aplicación web”, “desperdicio de comida”, “bajo presupuesto”, “ahorro”, “comida rápida”, “rico y económico”.
Author: Outsiders

#### App web constrains

Título: Tasty Point
Description: Tasty Point’s app web. Buy tasty food and help reduce food waste.
Keywords: “App web”, “comida”, “medio ambiente”, “comida económica”, “ofertas de comida”, “aplicación web”, “desperdicio de comida”, “bajo presupuesto”, “ahorro”, “comida rápida”, “rico y económico”.

La aplicación web de Tasty point contará con filtros al presentar los platos del día. Filtros como:
• Tipo de comida.
• Nombre del Restaurante/Local de comida.
• Precios.
Además, los platos se presentarán por defecto en orden de popularidad. Sin embargo, los usuarios también podrán elegir su orden de presentación preferido, como: Ordenado por fechas: del más reciente al más antiguo, ordenado por fechas: del más antiguo al más reciente, ordenado en orden alfabético: a – z, ordenado en orden alfabético: z – a, etc.
Como adicional, las opciones de platos disponibles tendrán un color distinguible a los ojos del usuario.

Landing page:
Se usa un menú de navegación fija. De manera que, aunque el usuario haya elegido una opción a seguir, el menú siempre permanecerá a su disposición.
También incluye un pie de página para enlazar secciones pertinentes del Landing page.
App Web:
Se incluye una barra lateral para mostrar las opciones que el usuario puede elegir, opciones como: "Inicio", "Agregar", "Catálogo", "Reservaciones actuales", "Más información", etc.

### 4.1.3. Architectural Drivers Backlog. 6/40 V1.0

 ![image](https://github.com/Arquitectura-Software-2023/Project-Report/assets/89089512/7bb3ad47-c42f-41b7-9933-43a4a61d5e52)

### 4.1.4. Architectural Design Decisions

 ![image](https://github.com/Arquitectura-Software-2023/Project-Report/assets/89089512/413e7009-15f8-4788-aaf4-457d2673aa80)

### 4.1.5. Quality Attribute Scenario Refinements

 1. Rendimiento (Performance):

Escenario Refinado: Durante las horas pico del almuerzo (12:00 p.m. a 1:00 p.m.), se espera que Tasty Point reciba un promedio de 500 pedidos por minuto en la ciudad capital de Lima, Perú.
Estímulo: Múltiples usuarios realizan pedidos simultáneos en la plataforma durante el almuerzo.
Respuesta Refinada: El sistema debe procesar cada pedido en menos de 5 segundos y mantener un tiempo de respuesta promedio de 2 segundos para garantizar una experiencia de usuario fluida.
Medición: Tiempo promedio de procesamiento de pedidos durante las horas pico y carga de procesamiento en el servidor.
2. Seguridad (Security):

Escenario Refinado: Un usuario inicia sesión y realiza un pedido, ingresando información de tarjeta de crédito para el pago.
Estímulo: Usuario proporciona información de inicio de sesión y detalles de pago.
Respuesta Refinada: Todos los datos de usuario y detalles de pago se cifran utilizando un estándar de cifrado AES-256 antes de almacenarse en la base de datos. Además, se implementa una autenticación de dos factores (2FA) para las transacciones financieras.
Medición: La auditoría de seguridad registra y monitorea cualquier intento de acceso no autorizado o actividades sospechosas.
3. Disponibilidad (Availability):

Escenario Refinado: El sistema de Tasty Point debe estar disponible el 99.9% del tiempo mensualmente, excluyendo el tiempo de mantenimiento programado.
Estímulo: Usuarios acceden a la plataforma en cualquier momento.
Respuesta Refinada: El sistema se implementa en múltiples servidores distribuidos geográficamente, y se realiza un mantenimiento planificado fuera de las horas pico para garantizar la disponibilidad.
Medición: Tiempo de inactividad planificado y no planificado registrado y comparado con el objetivo de disponibilidad.
4. Usabilidad (Usability):

Escenario Refinado: Un usuario nuevo descarga la aplicación móvil de Tasty Point y realiza su primer pedido.
Estímulo: Usuario interactúa con la aplicación móvil por primera vez.
Respuesta Refinada: La aplicación guía al usuario a través del proceso de registro, búsqueda de restaurantes, selección de platos y pago de una manera intuitiva y sin complicaciones.
Medición: Se recopilan comentarios de los usuarios nuevos y se realizan encuestas para evaluar la facilidad de uso y la satisfacción del usuario.

## 4.2. Strategic-Level Domain-Driven Design

### 4.2.1. EventStorming

#### Contexto Inicial

En el mundo, el 33% de la comida producida por cadenas de restaurantes se desperdicia.
Algunas empresas están promoviendo la reutilización y la venta de porciones de comida a precios reducidos, especialmente dirigidas a la población joven.
Este modelo de negocio ha tenido éxito en Europa, pero aún no está disponible en Perú.
Eventos de Negocio:

![image](https://github.com/Arquitectura-Software-2023/Project-Report/assets/89089512/72c8fca4-bc69-488e-b417-fcb015f860b7)

Roles y responsabilidades en la empresa.
Tecnologías utilizadas para la plataforma.
Estrategias de marketing y promoción.
Colaboración con restaurantes locales.
Gestión de la calidad de los alimentos ofrecidos.
Seguimiento y medición de la satisfacción del cliente.
Posibles expansiones a otros mercados en el futuro.

### 4.2.2. Candidate Context Discovery

El proceso de "Candidate Context Discovery" para la startup "Tasty Point" implica la identificación y evaluación de candidatos que encajen adecuadamente con la misión, visión y valores de la empresa, así como con las demandas específicas de la industria alimentaria y la cultura peruana. A continuación, se describe cómo se llevaría a cabo este proceso:

#### Paso 1: Análisis de Requisitos del Puesto

- Definir claramente los requisitos y habilidades necesarios para los puestos disponibles en Tasty Point, como chefs, personal de servicio al cliente, desarrolladores de aplicaciones, entre otros.

#### Paso 2: Reclutamiento y Difusión

- Iniciar un proceso de reclutamiento que incluya la publicación de las vacantes en plataformas de empleo, redes sociales y otros canales relevantes.
- Fomentar la participación de la comunidad local y la industria de alimentos y restaurantes en la búsqueda de talento.

#### Paso 3: Evaluación de Currículum Vitae

- Revisar los currículums de los candidatos para identificar habilidades, experiencias y educación relevante para los puestos.
- Buscar candidatos que tengan experiencia en la industria alimentaria y/o en startups relacionadas con la alimentación.

#### Paso 4: Entrevistas Iniciales

- Realizar entrevistas iniciales con los candidatos para conocer su historial laboral, motivaciones y alineación con la cultura y valores de Tasty Point.
- Evaluar la capacidad de los candidatos para trabajar en un entorno de inicio y su interés en reducir el desperdicio de alimentos.

#### Paso 5: Evaluación de Habilidades Técnicas

- Para puestos técnicos, como desarrolladores de aplicaciones, realizar pruebas técnicas o ejercicios prácticos para evaluar las habilidades necesarias.

#### Paso 6: Evaluación de Ajuste Cultural

- Evaluar la compatibilidad cultural de los candidatos mediante preguntas y discusiones específicas relacionadas con la cultura de la empresa y la industria alimentaria.

#### Paso 7: Entrevistas Finales

- Realizar entrevistas finales con los candidatos destacados para profundizar en sus habilidades, experiencias y su pasión por la misión de Tasty Point.
- Evaluar su capacidad para trabajar en equipo y adaptarse a un entorno dinámico.

#### Paso 8: Verificación de Referencias

- Contactar a las referencias proporcionadas por los candidatos para obtener información adicional sobre su desempeño y antecedentes laborales.

#### Paso 9: Selección y Oferta de Empleo

- Seleccionar a los candidatos más adecuados para cada puesto y hacerles una oferta de empleo.
- Proporcionar detalles sobre la cultura y las expectativas de la empresa.

#### Paso 10: Integración y Desarrollo Continuo

- Una vez contratados, proporcionar a los nuevos empleados un proceso de integración sólido.
- Continuar desarrollando y capacitando a los empleados para que estén alineados con los objetivos y valores de Tasty Point.

El proceso de "Candidate Context Discovery" para Tasty Point se centra en encontrar candidatos que no solo tengan las habilidades técnicas necesarias, sino que también compartan la pasión por reducir el desperdicio de alimentos y promover la sana alimentación, contribuyendo así al éxito de la startup.

### 4.2.3. Domain Message Flows Modeling

En esta sección se presentarán los wireflows relacionados a los wireframes de la aplicación web y las historias de usuario.

1. Como consumidor quiero ver el perfil de mi cuenta para corroborar que mis datos sean correctos.

    ![image](https://github.com/Arquitectura-Software-2023/Project-Report/assets/89089512/e099dfc9-bfc0-46a6-8e9a-48bf5ebe1c34)

2. Como consumidor, quiero visualizar las principales notificaciones para estar informado sobre las ofertas y promociones que ofrezca la aplicación
  
    ![image](https://github.com/Arquitectura-Software-2023/Project-Report/assets/89089512/a3f0d55b-077f-4e22-9c5a-be5a7734666e)

3. Como consumidor quiero clasificar de manera favorita mis productos para lograr visualizar la disponibilidad en la sección “Mis favoritos”

    ![image](https://github.com/Arquitectura-Software-2023/Project-Report/assets/89089512/2ec0b0d7-ed4a-4898-baca-3944ffbaf13a)

4. Como consumidor quiero ver el catálogo de los productos alimenticios de primera necesidad para comprarlos.

    ![image](https://github.com/Arquitectura-Software-2023/Project-Report/assets/89089512/b686310b-5d9d-4c43-846f-87c720db180e)

5. Como consumidor quiero ver el catálogo de los productos alimenticios de primera necesidad para comprarlos

    ![image](https://github.com/Arquitectura-Software-2023/Project-Report/assets/89089512/5678a282-2c58-4486-a021-44597f813a2c)

En esta sección se presentarán los diseños realizados para la implementación del Landing page, tanto en Wireframe como Mockup.
A continuación, se mostrará el diseño en un modelo de tipo Wireframe para el Landing Page de la aplicación Tasty Point. Para mayor detalle, visualizar el enlace de Figma.
Link a Figma: <https://www.figma.com/file/VroQCK2bhcvc3SDwavm84T/Landing-Page-Wireframe-Tasty-Point?node-id=0%3A1>

### 4.2.4. Bounded Context Canvases

![image](https://github.com/Arquitectura-Software-2023/Project-Report/assets/89089512/c68c5c0a-6b3a-4518-b98f-f568c86f9f56)

### 4.2.5. Context Mapping

![image](https://github.com/Arquitectura-Software-2023/Project-Report/assets/89089512/df97086d-13c3-434b-9a45-fbacd428ea4e)

En este diagrama:

Problemática: Representa la situación global de desperdicio de comida en cadenas de restaurantes en todo el mundo.

StartUp: Tasty Point: Es el centro de atención y solución para esta problemática.

Consumidores (Población Juvenil): Representa el grupo demográfico al que Tasty Point se dirige principalmente.

Restaurantes: Son los socios o colaboradores potenciales de Tasty Point que pueden proporcionar alimentos para su plataforma.

Proveedores de Alimentos: Son los proveedores de alimentos que suministran a los restaurantes y, por lo tanto, pueden influir en la oferta de Tasty Point.

Reguladores y Autoridades: Representa a las autoridades gubernamentales y reguladores que pueden tener un papel en la regulación de la industria alimentaria y el desperdicio de alimentos.

## 4.3. Software Architecture

### 4.3.1. Software Architecture System Landscape Diagram

![image](https://github.com/Arquitectura-Software-2023/Project-Report/assets/89089512/93a8f4ed-a859-4fce-a0dd-21cb169c8172)

Problemática: Representa la situación global de desperdicio de comida en cadenas de restaurantes en todo el mundo.

Tasty Point (Startup): Es el sistema central que aborda esta problemática a través de su plataforma web y aplicación móvil.

Plataforma Web (Frontend): La interfaz de usuario web que permite a los consumidores pedir comida, explorar menús y realizar pagos.

Aplicación Móvil (Frontend): La aplicación móvil que ofrece a los consumidores una experiencia similar a la web, pero en dispositivos móviles.

Backend (Gestión de Datos): El sistema de backend que gestiona datos, pedidos, transacciones y la lógica empresarial de Tasty Point.

Restaurantes: Representa la integración de Tasty Point con los restaurantes que proporcionan comida a la plataforma.

Proveedores de Alimentos: Los proveedores de alimentos que suministran los ingredientes a los restaurantes asociados.

Reguladores y Autoridades: Los organismos gubernamentales y reguladores que pueden interactuar con Tasty Point en relación con la regulación de la industria alimentaria.

### 4.3.2. Software Architecture Context Level Diagrams

Mediante el Context Diagram pretendemos mostrar el panorama general de la interacción entre el segmento objetivo: Tanto clientes como consumidores. Ahí podemos mostrar la interacción con la aplicación y los segmentos.

![image](https://github.com/Arquitectura-Software-2023/Project-Report/assets/89089512/e3853df0-2c32-4de6-830c-08fe530515fb)

### 4.3.3. Software Architecture Container Level Diagrams

En este diagrama se puede apreciar el funcionamiento que tienen los Bounded Context en relación con la aplicación. .

![image](https://github.com/Arquitectura-Software-2023/Project-Report/assets/89089512/4fb481b0-a809-4386-bb8f-af0cdad64769)

### 4.3.4. Software Architecture Deployment Diagrams

En esta imagen se evidencia de manera detallada al diagrama: Tanto como sus controllers, services y repositorios, a su vez su base datos donde está almacenado.

![image](https://github.com/Arquitectura-Software-2023/Project-Report/assets/89089512/f5d47080-b63d-48d8-bc43-7202c6c287a2)

## Capítulo V: Tactical-Level Software Design

## 5.1 Bounded Context: Monitoring Context

### 5.1.1 Domain Layer

| Nombre             | Monitoring Context                           |
|-------------------|--------------------------------------------|
| Categories         | Entity                                     |
| Propósito          | Clase que se encarga de monitorear el estado de los productos disponibles de Tasty Point. |
| Attributes                                                    |
| - Nombre           | Tipo de Dato: String   Visibilidad: Private |
| - Title            | Tipo de Dato: String   Visibilidad: Private |
| - Image            | Tipo de Dato: String   Visibilidad: Private |
| - Description      | Tipo de Dato: String   Visibilidad: Private |
| - Cost             | Tipo de Dato: String   Visibilidad: Private |
| - Status           | Tipo de Dato: String   Visibilidad: Private |
| Methods                                                        |
| - Name             | Tipo de retorno: void   Visibilidad: public |
| - Add Offer        | Tipo de retorno: String   Visibilidad: public |
| - getPlace         | Tipo de retorno: String   Visibilidad: public |
| - getImage         | Tipo de retorno: String   Visibilidad: public |
| - GetDescription   | Tipo de retorno: String   Visibilidad: public |
| - getCost          | Tipo de retorno: String   Visibilidad: public |
| Nombre             MonitoringContext, se encargan de monitorear el estado de los productos disponibles de Tasty Point.                            |
| ListByID          | String                                       |
| ListName          | String                                       |
| Create            | Void                                         |
| Update            | Void                                         |
| Delete            | Void                                         |

### 5.1.2. Interface Layer

| Nombre             | Monitoring Context                           |
|-------------------|--------------------------------------------|
| Categories         | Monitoring                                  |
| Propósito          | Visualizar las solicitudes HTTP relacionadas con la disponibilidad de productos, se comunica directamente con la capa de servicios para procesar solicitudes. |
| Métodos            |                                            |
| - Nombre           | Tipo de retorno: Promise   Visibilidad: Public |
| - getStatus        | Tipo de retorno: Promise   Visibilidad: Public |
| - getValidation    | Tipo de retorno: Promise   Visibilidad: Public |

### 5.1.3 Application Layer

| Nombre           | MonitoringHandler  |
|------------------|--------------------|
| Categories       | EventHandler       |
| Propósito        | Validar datos de disponibilidad |
| SI               | SI                 |

### 5.1.4 Infrastructure Layer

| Nombre           | Monitoring Context                      |
|------------------|-----------------------------------------|
| Categories       | Repository                               |
| Propósito        | Monitorear internamente la disponibilidad de productos que se ofrece. |
| Métodos          |                                           |
| - Create         | void   public                            |
| - Update         | void   public                            |
| - Edit           | void   public                            |
| - Delete         | void   public                            |
| - GetById        | monitor   public                         |
| - GetAll         | Array\<Offer\>   public                    |

### 5.1.5 Bounded Context Software Architecture Component Level Diagrams

![image](https://github.com/Arquitectura-Software-2023/Project-Report/assets/89096127/a47cab59-4e95-4550-b8d7-c9c5d7b78b9a)

### 5.1.6 Bounded Context Software Architecture code Level Diagrams

#### 5.1.6.1 Bounded Context Domain Level Class Diagram

![image](https://github.com/Arquitectura-Software-2023/Project-Report/assets/89096127/a00f02c5-6752-48ed-bde9-45d5fd3fbafc)

#### 5.1.6.2 Bounded Context Database Design Diagram

![image](https://github.com/Arquitectura-Software-2023/Project-Report/assets/89096127/eb0d4cb1-d6fd-4489-abd1-178ae7671dbe)

## 5.2 Bounded Context: Booking Context

### 5.2.1 Domain Layer

| Nombre             | Booking Context                             |
|-------------------|---------------------------------------------|
| Categories         | Entity                                      |
| Propósito          | Clase que se encarga de monitorear la reserva de productos |
| Attributes         |                                             |
| - Nombre           | Tipo de Dato: String   Visibilidad: Private |
| - Title            | Tipo de Dato: String   Visibilidad: Private |
| - Image            | Tipo de Dato: String   Visibilidad: Private |
| - Description      | Tipo de Dato: String   Visibilidad: Private |
| - Cost             | Tipo de Dato: String   Visibilidad: Private |
| - Status           | Tipo de Dato: String   Visibilidad: Private |
| Methods            |                                             |
| - Name             | Tipo de retorno: void   Visibilidad: public |
| - Add Offer        | Tipo de retorno: String   Visibilidad: public |
| - getPlace         | Tipo de retorno: String   Visibilidad: public |
| - getImage         | Tipo de retorno: String   Visibilidad: public |
| - GetDescription   | Tipo de retorno: String   Visibilidad: public |
| - getDisponibilidad | Tipo de retorno: String   Visibilidad: public |
| Nombre            | BookingContext                               |
| ListByID          | String                                       |
| ListName          | String                                       |
| Search            | Void                                         |
| Update            | Void                                         |
| Delete            | Void                                         |

### 5.2.2. Interface Layer

| Nombre           | Booking Context                             |
|------------------|--------------------------------------------|
| Categories       | Booking                                    |
| Propósito        | Visualizar las solicitudes HTTP relacionadas con la reserva de productos, se comunica directamente con la capa de servicios para procesar reservaciones. |
| Métodos          |                                            |
| - Nombre         | Tipo de retorno: Promise   Visibilidad: Public |
| - getStatus      | Tipo de retorno: Promise   Visibilidad: Public |
| - getValidation  | Tipo de retorno: Promise   Visibilidad: Public |

### 5.2.3 Application Layer

| Nombre           | MonitoringHandler  |
|------------------|--------------------|
| Categories       | EventHandler       |
| Propósito        | Validar datos de disponibilidad |
| SI               | SI                 |

### 5.2.4 Infrastructure Layer

| Nombre           | Booking Context                      |
|------------------|-------------------------------------|
| Categories       | Repository                          |
| Propósito        | Monitorear internamente la reserva que realizan los clientes de productos que se ofrece. |
| Métodos          |                                     |
| - Create         | void   public                        |
| - Update         | void   Public                        |
| - Edit           | void   Public                        |
| - Delete         | void   Public                        |
| - GetById        | monitor   Public                     |
| - GetAll         | Array\<Offer\>   Public                |

### 5.2.5 Bounded Context Software Architecture Component Level Diagrams

![image](https://github.com/Arquitectura-Software-2023/Project-Report/assets/89096127/2665227d-ab64-4cda-b107-d23e45dd4996)

### 5.2.6 Bounded Context Software Architecture code Level Diagrams

#### 5.2.6.1 Bounded Context Domain Level Class Diagram

![image](https://github.com/Arquitectura-Software-2023/Project-Report/assets/89096127/1c0a2bc6-d9d6-4c4d-ac31-cdd99a47174f)

#### 5.2.6.2 Bounded Context Database Design Diagram

![image](https://github.com/Arquitectura-Software-2023/Project-Report/assets/89096127/138d232a-a07f-48b9-84cc-e3344a0dc721)

## 5.3 Bounded Context: Stock Inventory Context

### 5.3.1 Domain Layer

| Nombre             | Stock Inventory Context                |
|-------------------|---------------------------------------|
| Categories         | Entity                                |
| Propósito          | Clase que se encarga de visualizar el inventario de productos |
| Attributes         |                                       |
| - Nombre           | Tipo de Dato: String   Visibilidad: Private |
| - Title            | Tipo de Dato: String   Visibilidad: Private |
| - Image            | Tipo de Dato: String   Visibilidad: Private |
| - Description      | Tipo de Dato: String   Visibilidad: Private |
| - Cost             | Tipo de Dato: String   Visibilidad: Private |
| - Status           | Tipo de Dato: String   Visibilidad: Private |
| Métodos            |                                       |
| - Name             | Tipo de retorno: void   Visibilidad: public |
| - Add Offer        | Tipo de retorno: String   Visibilidad: public |
| - getPlace         | Tipo de retorno: String   Visibilidad: public |
| - getImage         | Tipo de retorno: String   Visibilidad: public |
| - GetDescription   | Tipo de retorno: String   Visibilidad: public |
| - getPrice         | Tipo de retorno: Int   Visibilidad: public |
| Nombre            | InventoryContext                        |
| ListByID          | String                                  |
| ListName          | String                                  |
| Search            | Void                                    |
| Update            | Void                                    |
| Delete            | Void                                    |

### 5.3.2. Interface Layer

| Nombre           | Booking Context                             |
|------------------|--------------------------------------------|
| Categories       | Booking                                    |
| Propósito        | Evidenciar las solicitudes HTTP relacionadas con la visualización de productos, se comunica directamente con la capa de servicios para procesar reservaciones. |
| Métodos          |                                            |
| - Nombre         | Tipo de retorno: Promise   Visibilidad: Public |
| - getStatus      | Tipo de retorno: Promise   Visibilidad: Public |
| - getValidation  | Tipo de retorno: Promise   Visibilidad: Public |

### 5.3.3 Application Layer

| Nombre           | MonitoringHandler  |
|------------------|--------------------|
| Categories       | EventHandler       |
| Propósito        | Validar datos de disponibilidad |
| SI               | SI                 |

### 5.3.4 Infrastructure Layer

| Nombre             | StockInventoryContext               |
|-------------------|------------------------------------|
| Categories         | Repository                         |
| Propósito          | Monitorear internamente la disponibilidad y organización que realizan los clientes de productos que se ofrece. |
| Métodos            |                                    |
| - Create           | void   public                       |
| - Update           | void   Public                       |
| - Edit             | void   Public                       |
| - Delete           | void   Public                       |
| - GetById          | monitor   Public                    |
| - GetAll           | Array\<Offer\>   Public               |

### 5.3.5 Bounded Context Software Architecture Code Level Diagrams

![image](https://github.com/Arquitectura-Software-2023/Project-Report/assets/89096127/3ff9106c-d472-44f6-ae02-5bf9c626798d)

### 5.3.6 Bounded Context Software Architecture code Level Diagrams

#### 5.3.6.1 Bounded Context Domain Level Class Diagram

![image](https://github.com/Arquitectura-Software-2023/Project-Report/assets/89096127/4f735f8d-f534-4633-b47f-6094b46d6ce9)

#### 5.3.6.2 Bounded Context Database Design Diagram

![image](https://github.com/Arquitectura-Software-2023/Project-Report/assets/89096127/f2b0a42a-bcb8-45cb-afd4-e0b7fbf4db27)

## 5.4 Bounded Context: Purchase Context

### 5.4.1 Domain Layer

| Nombre             | Purchase Context                          |
|-------------------|-----------------------------------------|
| Categories         | Entity                                  |
| Propósito          | Clase que se encarga de validar la compra y ver la disponibilidad de productos disponibles de Tasty Point. |
| Attributes         |                                         |
| - Nombre           | Tipo de Dato: String   Visibilidad: Private |
| - Title            | Tipo de Dato: String   Visibilidad: Private |
| - Image            | Tipo de Dato: String   Visibilidad: Private |
| - Description      | Tipo de Dato: String   Visibilidad: Private |
| - Cost             | Tipo de Dato: String   Visibilidad: Private |
| - Status           | Tipo de Dato: String   Visibilidad: Private |
| Métodos            |                                         |
| - Name             | Tipo de retorno: void   Visibilidad: public |
| - Add Offer        | Tipo de retorno: String   Visibilidad: public |
| - getPlace         | Tipo de retorno: String   Visibilidad: public |
| - getImage         | Tipo de retorno: String   Visibilidad: public |
| - GetDescription   | Tipo de retorno: String   Visibilidad: public |
| - getPrice         | Tipo de retorno: Int   Visibilidad: public |
| Nombre            | InventoryContext                         |
| ListByID          | String                                  |
| ListName          | String                                  |
| Search            | Void                                    |
| Update            | Void                                    |
| Delete            | Void                                    |

### 5.4.2. Interface Layer

| Nombre           | Purchase Context                           |
|------------------|-------------------------------------------|
| Categories       | Purchase                                  |
| Propósito        | Visualizar las solicitudes HTTP relacionadas con la visualización de productos para comprar, la cual se comunica directamente con la capa de servicios para procesar reservaciones. |
| Métodos          |                                           |
| - Nombre         | Tipo de retorno: Promise   Visibilidad: Public |
| - getStatus      | Tipo de retorno: Promise   Visibilidad: Public |
| - getValidation  | Tipo de retorno: Promise   Visibilidad: Public |

### 5.4.3 Application Layer

| Nombre           | MonitoringHandler  |
|------------------|--------------------|
| Categories       | EventHandler       |
| Propósito        | Validar datos de disponibilidad |
| SI               | SI                 |

### 5.4.4 Infrastructure Layer

| Nombre             | Purchase Context                         |
|-------------------|------------------------------------------|
| Categories         | Repository                               |
| Propósito          | Monitorear internamente la disponibilidad y organización que realizan los clientes de productos que se ofrece para realizar compra. |
| Métodos            |                                          |
| - Create           | void   public                            |
| - Update           | void   Public                            |
| - Edit             | void   Public                            |
| - Delete           | void   Public                            |
| - GetById          | monitor   Public                         |
| - GetAll           | Array\<Offer\>   Public                    |

### 5.4.5 Bounded Context Software Architecture Code Level Diagrams

![image](https://github.com/Arquitectura-Software-2023/Project-Report/assets/89096127/b89a15d1-d43f-4e92-82e5-4ced0a05ace5)

### 5.4.6 Bounded Context Software Architecture code Level Diagrams

#### 5.4.6.1 Bounded Context Domain Level Class Diagram

![image](https://github.com/Arquitectura-Software-2023/Project-Report/assets/89096127/bf603129-c44e-4757-8dd2-c3c9d63c3dfc)

#### 5.4.6.2 Bounded Context Database Design Diagram

![image](https://github.com/Arquitectura-Software-2023/Project-Report/assets/89096127/610a55f4-d96a-40ff-bd83-ee24070540a7)

#### 5.4.6.3 General Domain Level Class Diagram

![image](https://github.com/Arquitectura-Software-2023/Project-Report/assets/89096127/85e7980b-040e-40d6-817a-7532a7468630)

#### 5.4.6.4 General Database Design Diagram

![image](https://github.com/Arquitectura-Software-2023/Project-Report/assets/89096127/997517ce-741c-4f81-83e7-09742f2c8a4c)

## Capítulo VI: Solution UX Design

### 6.1. Style Guidelines

### 6.1.1. General Style Guidelines

Toda empresa, sin importar su rubro, necesita de Style Guidelines. Esta guía es el pilar que mantendrá unido el sistema mediante el cual la empresa ofrece sus servicios y productos. Asimismo, permite que haya una comunicación coherente dentro del entorno de la compañía. En nuestro caso, en Tasty Point vamos a crear nuestra Guía de Estilo de Marca basándonos en una plantilla disponible en Figma. Para elaborarla, consideraremos 5 elementos clave:

Misión: Somos una compañía de tecnología comprometida con la creación de aplicaciones web y móviles eficientes e innovadoras que permitan a nuestros usuarios poder acceder a una amplia gama de opciones en el área de alimentos de una manera ágil, sostenible y   económica.
Visión: Promover una cultura de consumo responsable y eficaz, donde todos nuestros clientes afiliados puedan acceder a alimentos nutritivos, deliciosos y económicos. Asimismo, contribuir al desarrollo de los comercios de alimentos preparados en el Perú    transformando lo que sería una pérdida por desperdicio en ganancias.
Públicos objetivos:
Dueños(as) de restaurantes que desean incrementar sus ventas y evitar el desperdicio de comida, estos se encuentran en un
rango de edad entre los 30 a 50 años, preocupados por el cuidado de los recursos del planeta, con conciencia ambiental y decidido a incrementar sus ganancias.
Consumidores en un rango de edades entre los 18 a 30 años, usuarios de diversas tecnologías, en muchos casos recién independizados, y que desean ayudar a disminuir el desperdicio de comida que generan los restaurantes.

Dicho esto, usaremos la guia de diseños de Carbon Design System de IBM como nuestra base.

**Colors**
![Alt text](Images/Colors.png)

**Typography**
![Alt text](Images/Typography.png)

**Spacing** (Base de 4px u 8px)
![Alt text](Images/Spacing.png)

## 6.1.2. Web & Mobile Style Guidelines

### Criterios considerados en el diseño de Tasty Point

**Web Usability:**

- Facilita la interacción gracias al uso de fuentes distinguibles y del tamaño adecuado.
- Estructura el contenido: navegación en forma de "Z".
- Simplifica y sintetiza: Textos directos sin perder la amabilidad que queremos proyectar como marca.

- **Mobile Usability (Usabilidad en Dispositivos Móviles):**
- Adapta las fuentes y elementos para pantallas más pequeñas, manteniendo la legibilidad.
- Asegura una navegación intuitiva en dispositivos móviles.
- Simplifica y condensa los textos para una experiencia cómoda en dispositivos móviles, manteniendo la amabilidad de la marca.

**Inclusive Design:**
Los servicios brindados por la página deben ser accesibles a todo nuestro público objetivo, en este caso, ya que nuestro público objetivo abarca personas entre 20 y 40 años, las pautas consideradas son:

- Colores contrastantes y fuentes distinguibles para los usuarios con problemas de visión.
- Descripción de las imágenes empleadas para lectores de pantalla.
- Consistencia externa: Cumplir con los patrones de diseño comunes.
- Formato de imágenes PNG para conservar la calidad.

**Internationalization and Accessibility:**
El idioma por defecto empleado en los productos para la solución de este proyecto es el inglés.

**Responsive Web Design:**
Tanto el Landing page como la app web responden al dispositivo en el que el usuario ingresa, ya que cuentan con una versión en vista web y mobile.

### 6.2. Arquitectura de la Información

### 6.2.1. Sistemas de Organización

**Landing Page:** En la página de inicio, se organizará el contenido de forma jerárquica. Primero, se mostrará una breve descripción de Tasty Point y luego se ramificarán las entradas para los 2 públicos objetivos a los que queremos llegar, tanto en la aplicación móvil como en la web.

**Aplicación Web y Aplicación Móvil:** En la aplicación web, las secciones se mostrarán en una barra lateral a la izquierda de la pantalla, y estas direccionarán a la sección que busca el usuario. De manera similar, en la aplicación móvil, se utilizará una interfaz de navegación intuitiva que permitirá a los usuarios acceder a las diferentes secciones de la aplicación con facilidad. Los botones y las pestañas estarán diseñados de manera coherente tanto en la versión web como en la versión móvil para ofrecer una experiencia de usuario consistente en ambas plataformas.

### 6.2.2. Sistemas de Etiquetado

**Landing Page:** En el encabezado de la página de inicio se emplean las etiquetas "Home," "About us," "Features," "Pricing" y el botón "Sign up," que direccionan al usuario a la sección elegida de la página web o la aplicación móvil. También se emplean los botones "Customers" y "Business" que direccionan a los usuarios a la sección de la página destinada para ellos.

**Aplicación Web y Aplicación Móvil:** En la aplicación web y móvil, las secciones se mostrarán en una barra lateral a la izquierda de la pantalla, y estas direccionarán a la sección que busca el usuario en ambas plataformas.

### 6.2.3. Etiquetas SEO y Metaetiquetas

**Landing Page:**

- **Título:** Tasty Point: La mejor manera de reducir el desperdicio de alimentos en Perú.
- **Descripción:** Con Tasty Point, puedes ayudar a combatir el desperdicio de alimentos. Tenemos diferentes entornos según el segmento al que pertenezca.
- **Palabras clave:** "comida", "medio ambiente", "comida económica", "ofertas de comida", "aplicación web", "desperdicio de comida", "bajo presupuesto", "ahorro", "comida rápida", "rico y económico".
- **Autor:** Outsiders

**Aplicación Web y Aplicación Móvil:**

- **Título:** Tasty Point
- **Descripción:** Aplicación web de Tasty Point. Compra comida deliciosa y ayuda a reducir el desperdicio de alimentos.
- **Palabras clave:** "Aplicación web","Aplicación móvil", "comida", "medio ambiente", "comida económica", "ofertas de comida", "aplicación web", "desperdicio de comida", "bajo presupuesto", "ahorro", "comida rápida", "rico y económico".

### 6.2.4. Sistemas de Búsqueda

La aplicación web y móvil de Tasty Point contará con filtros al presentar los platos del día, como:

- Tipo de comida.
- Nombre del Restaurante/Local de comida.
- Precios.

Además, los platos se presentarán por defecto en orden de popularidad en ambas versiones. Sin embargo, los usuarios también podrán elegir su orden de presentación preferido, como: ordenado por fechas (del más reciente al más antiguo), ordenado por fechas (del más antiguo al más reciente), ordenado en orden alfabético (a – z), ordenado en orden alfabético (z – a), etc. Como adicional, las opciones de platos disponibles tendrán un color distinguible a los ojos del usuario en ambas aplicaciones.

### 6.2.5. Sistemas de Navegación

**Landing Page:** Se utiliza un menú de navegación fija en ambas aplicaciones, de manera que, aunque el usuario haya elegido una opción a seguir, el menú siempre permanecerá a su disposición. También incluye un pie de página para enlazar secciones pertinentes de la página de inicio en ambas versiones.

**Aplicación Web y Aplicación Móvil:** Se incluye una barra lateral en ambas aplicaciones para mostrar las opciones que el usuario puede elegir, como "Inicio," "Agregar," "Catálogo," "Reservaciones actuales," "Más información," etc. En Tasty Point, se ha implementado una experiencia de catálogo mediante Realidad Virtual (VR) como una opción adicional para brindar a los usuarios de ambas aplicaciones una experiencia única e inmersiva al explorar productos y restaurantes.

### 6.3. Landing Page UI Design

### 6.3.1. Landing Page Wireframe

Enlace: <https://www.figma.com/file/ALKxX67sA2RFvViO0F8V9j/Landing-Page-Wireframe-Tasty-Point-(Copy)?type=design&node-id=26%3A31&mode=design&t=ehxwjTAlwGq8jg8d-1>

### 6.3.2. Landing Page Mock-up

Enlace: <https://www.figma.com/file/kPETY9zYCJ0cCAMyuPRArk/MockUpp?type=design&node-id=0%3A1&mode=design&t=SfurMCRvtLhDLFAd-1>

### 6.4. Applications UX/UI Design

Enlace: <https://www.figma.com/file/WbmwYMchV36UXVx5T9Q5Yn/Untitled?type=design&node-id=1%3A2&mode=design&t=St7eqWND2jSJG8FW-1>

### 6.4.1. Applications Wireframes

Mobile App:

![image](https://media.discordapp.net/attachments/912089666939916348/1155686562454052874/image.png?width=1310&height=618)
![image](https://media.discordapp.net/attachments/912089666939916348/1155686892071829555/image.png?width=964&height=310)
![image](https://media.discordapp.net/attachments/912089666939916348/1155687008853827646/image.png?width=615&height=621)
![image](https://media.discordapp.net/attachments/912089666939916348/1155687092882518046/image.png?width=839&height=617)
![image](https://media.discordapp.net/attachments/912089666939916348/1155687135375007784/image.png?width=319&height=669)
![image](https://media.discordapp.net/attachments/912089666939916348/1155687188999192596/image.png?width=365&height=481)
![image](https://media.discordapp.net/attachments/912089666939916348/1155687263808782416/image.png?width=640&height=320)

Web Application:

![image](https://media.discordapp.net/attachments/912089666939916348/1155688193069420624/image.png?width=888&height=625)

![image](https://media.discordapp.net/attachments/912089666939916348/1155688252590784522/image.png?width=1346&height=592)

![image](https://media.discordapp.net/attachments/912089666939916348/1155688328746762358/image.png?width=959&height=669)

![image](https://media.discordapp.net/attachments/912089666939916348/1155688393229996102/image.png?width=1165&height=669)

![image](https://media.discordapp.net/attachments/912089666939916348/1155688453183377448/image.png?width=1345&height=669)

![image](https://media.discordapp.net/attachments/912089666939916348/1155688599539429527/image.png?width=1028&height=669)

![image](https://media.discordapp.net/attachments/912089666939916348/1155688659182440549/image.png?width=679&height=669)
![image](https://media.discordapp.net/attachments/912089666939916348/1155688758486773882/image.png?width=834&height=554)

### 6.4.2. Applications Wireflow Diagrams

En esta sección se presentarán los wireflows relacionados a los wireframes de la aplicación web y las historias de usuario.

1. Como consumidor quiero ver el perfil de mi cuenta para corroborar que mis datos sean correctos.
![image](https://media.discordapp.net/attachments/912089666939916348/1155693766502527097/Flowchart.jpg?width=1157&height=669)
2. Como consumidor, quiero visualizar las principales notificaciones para estar informado sobre las ofertas y promociones que ofrezca la aplicación
![image](https://media.discordapp.net/attachments/912089666939916348/1155695261864173599/Flowchart_1.jpg?width=1137&height=668)
3. Como consumidor quiero clasificar de manera favorita mis productos para lograr visualizar la disponibilidad en la sección “Mis favoritos”
![image](https://media.discordapp.net/attachments/912089666939916348/1155696665731280986/Flowchart_2.jpg?width=1198&height=669)
4. Como consumidor quiero ver el catálogo de los productos alimenticios de primera necesidad para comprarlos.
![image](https://media.discordapp.net/attachments/912089666939916348/1155697417346355312/Flowchart_3.jpg?width=765&height=669)
5. Como consumidor quiero ver el catálogo de los productos alimenticios de primera necesidad para comprarlos
![image](https://media.discordapp.net/attachments/912089666939916348/1155699210822353037/Flowchart_4.jpg?width=1251&height=669)

### 6.4.3. Applications Mock-ups

Mobile mock-ups(<https://www.figma.com/file/87yjJhAfCGQ9awLcKsH7EG/mockuptasty?type=design&node-id=0%3A1&mode=design&t=kSFT1kq185livZVs-1>):

![image](https://github.com/Arquitectura-Software-2023/Project-Report/assets/89089640/7b3e9571-e40b-4807-8175-6444cae3b9c0?width=1198&height=669)

![image](https://github.com/Arquitectura-Software-2023/Project-Report/assets/89089640/c3090125-b4dd-4254-9c2c-6b974f188bb2?width=1198&height=669)

![image](https://github.com/Arquitectura-Software-2023/Project-Report/assets/89089640/34f13a78-dfd0-49a0-a5c0-55c46dd34112?width=1198&height=669)

![image](https://github.com/Arquitectura-Software-2023/Project-Report/assets/89089640/7f8814aa-3856-4f49-b008-006d55477076?width=1198&height=669)

![image](https://github.com/Arquitectura-Software-2023/Project-Report/assets/89089640/e9ac55f9-06c0-4183-b602-27683fb3cf3a?width=1198&height=369)

Desktop Web Applications: <https://www.figma.com/file/WbmwYMchV36UXVx5T9Q5Yn/Wireframes-TastyPoint?type=design&node-id=34-2&mode=design&t=KtxNjkLC11IMyY4J-0>

![image](https://media.discordapp.net/attachments/973358848159133696/1169776180254224414/image.png?ex=6556a1f6&is=65442cf6&hm=e03618d87a1de83eb1a138aae137d89bead3abe4fb04c8e5a94429dc823c3319&=&width=1056&height=669)

![image](https://media.discordapp.net/attachments/973358848159133696/1169776876064084008/image.png?ex=6556a29c&is=65442d9c&hm=47b685635dd6d8ec3a8d138f48666692da85b71a85e5dc36a63c520a96aa2160&=&width=1348&height=605)

![image](https://media.discordapp.net/attachments/973358848159133696/1169776947472113785/image.png?ex=6556a2ad&is=65442dad&hm=005734141baeb9aa4bfa84ff0a7a0373a8e82ee0ab15bf73641097adcbd762b2&=&width=1327&height=617)

![image](https://media.discordapp.net/attachments/973358848159133696/1169777012647407716/image.png?ex=6556a2bd&is=65442dbd&hm=456b725ff48888a245150000d4c70fff4fd45ffbf26afdb8ff9bfb9cd641a3f9&=&width=1375&height=614)

![image](https://media.discordapp.net/attachments/973358848159133696/1169777071715795005/image.png?ex=6556a2cb&is=65442dcb&hm=113405fe1596edeb6774c9450baab29833c81b1abbbf6481fc3cd02b29823a7c&=&width=1085&height=669)

![image](https://media.discordapp.net/attachments/973358848159133696/1169777164019834910/image.png?ex=6556a2e1&is=65442de1&hm=097eeeb9c9c494abbd8ad9603ce0b72d1297bdce049d14d97690e9bcfb7dee86&=&width=978&height=669)

![image](https://media.discordapp.net/attachments/973358848159133696/1169777242654658631/image.png?ex=6556a2f4&is=65442df4&hm=0ba0d200c3d45188ee51b290392d631b4b235f9a6da860b4084bdf66180df77b&=&width=1380&height=630)

### 6.4.4. Applications User Flow Diagrams

Mobile user flow diagrams(<https://www.figma.com/file/hXXW0qrVtjezWIP9ub7pt4/Untitled?type=whiteboard&node-id=0%3A1&t=0nx6v5IW0oYnPtDf-1>):

![image](https://github.com/Arquitectura-Software-2023/Project-Report/assets/89089640/2f7f877d-81b4-459e-9f67-3e70027be8c4?width=1198&height=680)

![image](https://github.com/Arquitectura-Software-2023/Project-Report/assets/89089640/14fb4182-6df4-4e98-9fe8-e4b32736df60?width=1198&height=680)

![image](https://github.com/Arquitectura-Software-2023/Project-Report/assets/89089640/686cb75a-ac02-4a7a-bf60-f7d418162d45?width=1198&height=680)

![image](https://github.com/Arquitectura-Software-2023/Project-Report/assets/89089640/b68f7f64-a6eb-458f-8ae6-a16c294e433f?width=1198&height=680)

## 6.5. Applications Prototyping

Link del prototipo: <https://www.figma.com/proto/87yjJhAfCGQ9awLcKsH7EG/mockuptasty?type=design&node-id=501-2&t=tpCLr4biP864FRLh-1&scaling=scale-down&page-id=0%3A1&starting-point-node-id=501%3A2&mode=design>

![image](https://github.com/Arquitectura-Software-2023/Project-Report/assets/89089640/3b74fc8d-a6ee-4456-a95b-40d871ac668f?width=1198&height=369)

Link del prototipo web: <https://www.figma.com/file/WbmwYMchV36UXVx5T9Q5Yn/Wireframes-TastyPoint?type=design&node-id=34-2&mode=design&t=kmavh7ADmLwmhtSq-0>

![image](https://github.com/Arquitectura-Software-2023/Project-Report/assets/89096127/719f4876-e116-40a4-b0b6-70aa8f511728)

## Capítulo VII: Product Implementation, Validation & Deployment

## 7.1. Software Configuration Management

### 7.1.1. Software Development Environment Configuration

Usaremos un set de herramientas que nos permitiran desarrollar las distitas soluciones que ofrecemos. Para una mejor visualicion, lo hemos separado en caterogias. En la siguiente lista podran observar las herramientas con sus enlaces de cada categoria.

**Editores:**

- [Visual Studio 2022](https://visualstudio.microsoft.com/vs/)
- [Visual Studio code](https://code.visualstudio.com/)

**SDKs y Runtimes:**

- [.Net 6 LTS](https://dotnet.microsoft.com/en-us/download/visual-studio-sdks)
- [Node 18.18.2 Hydrogen LTS](https://nodejs.org/en/download/releases)

**Frameworks:**

- [ASP.Net 6 LTS](https://dotnet.microsoft.com/en-us/download/visual-studio-sdks)
- [Vue 3](https://vuejs.org/)
- [Dart](https://dart.dev/)

**Engines:**

- [Unity LTS Release 2022.3.12f1](https://unity.com/releases/editor/qa/lts-releases)

**Bases de datos:**

- [MySql](https://www.mysql.com/)

**Control de versiones:**

- [Git](https://git-scm.com/)
- [Github](https://github.com)

### 7.1.2. Source Code Management

Par nuestro control de versiones usaremos [Git](https://git-scm.com/). Asimismo, usaremos [Github](https://github.com) para almacenar nuestros repositorios de git. Para una mayor organizacion, hemos creado una organizacion donde tendremos nuestros repositorios. Tambien nos facilitara crear equipos y restringir permisos. El enlace a la organizacion es el siguiente: [Organizacion](https://github.com/Arquitectura-Software-2023)

| Desarrollo                | Repositorio                         | Enlace |
|---------------------------|-------------------------------------|--------|
| Proyecto                  | Project-Report                      | [Repositorio](https://github.com/Arquitectura-Software-2023/Project-Report) |
| Landing Page              | TastyPoint-landing-page             | [Repositorio](https://github.com/Arquitectura-Software-2023/TastyPoint-landing-page) |
| Aplicacion Web - Frontend | TastyPoint-FrontEnd-Web-Application | [Repositorio](https://github.com/Arquitectura-Software-2023/TastyPoint-FrontEnd-Web-Application) |
| Aplicacion Web - Backend | Web-Services-TastyPoint             | [Repositorio](https://github.com/Arquitectura-Software-2023/Web-Services-TastyPoint) |
| Aplicacion Móvil - Frontend | Mobile-App             | [Repositorio](https://github.com/Arquitectura-Software-2023/Mobile-App) |
| Aplicacion VR | TastyPoint_VR_Project  | [Repositorio](https://github.com/Arquitectura-Software-2023/TastyPoint_VR_Project) |

### 7.1.3. Source Code Style Guide & Conventions

Para nuestro Code Style, optamos por escoger los lineamientos de [Google](https://google.github.io/styleguide/). Esta decision fue tomada pues el equipo ya ha trabajdo anteriormente con esta guia de estimos. Asimismo, debido a la relevancia de esta guia de estilo, existen muchas herramientas que se encargan de asegurar que se cumpla atravez de linters y style checkers. Esto facilitada nuestra implementacion de nuestro pipeline de integracion continua. Finalmente, durante el desarrollo, agregaremos reglas especiales que solo se aplican a nuestro proyecto.

### 7.1.4. Software Deployment Configuration

Nuestro deployment se dara con distinta herramientas dependiendo del producto. Esto se debe a que poseemos creditos en ellas, lo cual nos permite lanzar un primer release sin elevar los costos planificados.

| Desarrollo                | Nube                                 |
|---------------------------|--------------------------------------|
| Proyecto                  | [Github](https://github.com)         |
| Landing Page              | [Azure](https://azure.microsoft.com) |
| Aplicacion Web - Frontend | [Netlify](https://netlify.com) |
| Aplicacion Web - Backtend | [Azure](https://azure.microsoft.com) |
| Aplicacion VR | [Unity](https://unity.com/) |

## 7.2. Solution Implementation

### 7.2.1. Sprint 1

#### 7.2.1.1. Sprint 1 Planning

| Sprint Planning | 1 |
|-----------------|---|
| Fecha | 16/10/2023 - 08:00 |
| Lugar | Remote - Discord |
| Asistentes | Todo el equipo |
| Resultados y Acuerdos | Software Development Environment Configuration, Source Code Management, Source Code Style Guide & Conventions, Software Deployment Configuration y Spring Backlog 1 |

#### 7.2.1.2. Sprint 1 Backlog

#### Sprint Backlog 1 Consumer

| Story ID | Titulo | Descripcion | Criterios de Aceptacion | Escenarios | Responsable | Puntos | Estado |
|-----------|-----------|-----------|-----------|-----------|-----------|-----------|-----------|
| US01 | Registro de Consumidor | Como consumidor quiero crear una cuenta para acceder a la aplicación. | CA1: Dado que el consumidor se encuentra en la ventana de registro y completa todos los campos. Cuando presiona el botón registrarse. Entonces podrá acceder a la aplicación. CA2: Dado que el consumidor se encuentra en la ventana de registro y no completa todos los campos obligatorios. Cuando presiona el botón registrarse. Entonces esos campos se marcan de rojo Y se muestra el mensaje: “Complete los campos obligatorios”. CA3: Dado que el consumidor se encuentra en la ventana de registro y completa erróneamente los campos. Cuando presiona el botón registrarse. Entonces se muestra el siguiente mensaje: “Complete los campos correctamente”. | E1: El consumidor quiere registrarse en la aplicación. E2: El consumidor no completa los campos obligatorios. E3: El consumidor intenta registrarse, pero no completa con datos correctos los campos obligatorios. |Andres Reynoso| 3 | Done|
| US02 | Monitorear el perfil | Como consumidor quiero ver el perfil de mi cuenta para corroborar que mis datos sean correctos. | Dado que el consumidor quiere ver su perfil. Cuando presiona el icono de perfil ubicado en la sección de menú. Entonces la aplicación muestra la información del perfil del consumidor. | El consumidor quiere ver su perfil. | Andres Reynoso| 3 | In Progress|
| US03 | Cerrar sesión de consumidor | Como consumidor quiero cerrar sesión para salir de mi cuenta.| CA1: Dado que el consumidor se encuentra en la aplicación. Cuando presiona el icono de perfil ubicado en la sección de menú. Entonces se le mostrará un mensaje: ¿Está seguro de cerrar sesión? Y el consumidor selecciona la opción sí para cerrar la sesión. CA2: Dado que el consumidor se encuentra en la aplicación. Cuando presiona el botón de cerrar sesión. Entonces se le mostrará un mensaje: ¿Está seguro de cerrar sesión? Y el consumidor selecciona la opción no para mantener iniciada la sesión. | E1:  El consumidor quiere cerrar sesión en el sistema. E2: El consumidor presiona por error el botón de “Cerrar sesión “.| Claudia Rozas| 2 | In Progress|
| US05 | Visualizar todas las notificaciones | Como consumidor, quiero visualizar las notificaciones para estar informado sobre las ofertas que ofrezcan los restaurantes. | Dado que el consumidor se encuentra en la aplicación, cuando ingresa a la sección de notificaciones, entonces le aparecen las notificaciones realizadas por los restaurantes registrados en la aplicación. |  Ver ofertas publicadas por restaurantes. | Andres Reynoso | 2 |Done|
| US06 | Fijar favoritos | Como consumidor quiero guardar la información de mis productos favoritos | CA1: Dado que el consumidor, se encuentra en la ventana “Lista de productos”, cuando presiona el icono de corazón vacío que posee el artículo en la lista de productos publicados por los restaurantes registrados en la aplicación, entonces se añaden los datos del producto a la sección de favoritos y el icono de corazón vacío cambia por uno lleno. CA2: Dado que el consumidor, se encuentra en la ventana “Lista de productos”, cuando presiona el icono de corazón lleno que posee el artículo en la lista de productos publicados por los restaurantes registrados en la aplicación, entonces se eliminan los datos del producto a la sección de favoritos y el icono de corazón lleno cambia por uno vacío. | E1: Guardar productos favoritos. E2: Eliminar producto de favoritos | Claudia Rozas | 3 | In Progress|
| US07 | Visualizar productos y sus datos | Como consumidor quiero ver la lista de los productos publicados por los restaurantes registrados en la aplicación para poder comprarlos. | CA1: Dado que el consumidor ha inicializado su sesión, cuando presione el icono de Lista en el menú entonces será dirigido a la ventana de “Lista de productos”, y podrá visualizar los productos organizados con sus respectivas fotos y ciertos datos puntuales como descripción. CA2: Dado que el consumidor ha inicializado su sesión, cuando presione el icono de Lista en el menú entonces será dirigido a la ventana de “Lista de productos”, y podrá visualizar el mensaje: “No hay productos publicados”. | E1: El consumidor quiere visualizar algunos productos para comprarlos. E2: El consumidor quiere visualizar algunos productos para comprarlos, pero no hay productos. | Claudia Rozas | 3 | In Progress|
| US09 | Compartir comentario| Como consumidor quiero redactar un comentario sobre un determinado restaurante acerca de mi experiencia con ellos para poder compartir mi opinión con los demás.| Dado que el consumidor se encuentra en la ventana de reseñas, cuando ingrese su comentario y presione el botón de publicar entonces se publicará el comentario. | El consumidor exceda el límite de caracteres permitidos. | Claudia Rozas | 2 | In Progress|

#### Sprint Backlog 1 Business

| Story ID | Titulo | Descripcion | Criterios de Aceptacion | Escenarios | Responsable | Puntos | Estado |
|-----------|-----------|-----------|-----------|-----------|-----------|-----------|-----------|
| US11 | Registro de Cliente | Como cliente quiero crear una cuenta para acceder a la aplicación. |CA1:  Dado que el cliente se encuentra en la ventana de registro y completa todos los campos. Cuando presiona el botón registrarse. Entonces podrá acceder a la aplicación. CA2: Dado que el cliente se encuentra en la ventana de registro y no completa todos los campos obligatorios. Cuando presiona el botón registrarse. Entonces esos campos se marcan de rojo y se muestra el mensaje: “Complete los campos obligatorios”. CA3: Dado que el cliente se encuentra en la ventana de registro y completa erróneamente los campos. Cuando presiona el botón registrarse. Entonces se muestra el siguiente mensaje: “Complete los campos correctamente”.| E1: El cliente quiere registrarse en la aplicación. E2: El cliente no completa los campos obligatorios. E3: El cliente intenta registrarse, pero no completa con datos correctos los campos obligatorios.| Andres Reynoso| 3 | Done|
| US15 | Medios de contacto | Como cliente quiero enlazar todos los medios de comunicación que poseo para permitir a mis consumidores contactarse directamente con nosotros. | Dado que el cliente se encuentra en la ventana “Perfil”, cuando selecciona “Agregar redes sociales” y los agrega, entonces la aplicación mostrará un mensaje “Se agregó con éxito”. | Añadir redes sociales | Andres Reynoso| 2 | In Progress|
| US17 | Ver pedidos |Como cliente quiero ver la lista de pedidos solicitados en mi restaurante, para conocer la demanda a través de la App web. | Dado que el cliente ha iniciado sesión, se encuentra en la ventana principal de Tasty point y hace clic en la sección “Órdenes”, cuando el cliente se encuentre en dicha sección, entonces aparecerá una lista con los nombres de los consumidores que realizaron un pedido en específico con fecha, hora y cantidad ordenada. | El cliente ingresa al registro de pedidos. |Claudia Rozas| 3 | In Progress|
| US18 | Ver el catálogo de platos e insumos | Como cliente quiero ver el catálogo actual de platos e insumos ofrecidos por mi establecimiento para corroborar que los datos de la App coincidan con mi inventario. | CA1: Dado que el cliente ha iniciado sesión, se encuentra en la lista de opciones ofrecida de Tasty point y desea revisar su catálogo. Cuando el cliente seleccione la opción "Catálogo". Entonces la aplicación mostrará la totalidad de platos e insumos registrados por el cliente, junto a datos pertinentes como: la cantidad actual, reservas hechas y tipo de recojo o envío disponible. CA2: Dado que el cliente se encuentra en la lista de platos e insumos disponibles ofrecidos por su establecimiento, y desea ver sólo los platos o insumos ofrecidos por su establecimiento. Cuando el cliente seleccione la opción filtro y elija la opción “platos” o “insumos”. Entonces la aplicación listará solo platos o solo insumos (dependiendo de la opción del cliente) junto a sus datos pertinentes. | E1: El cliente elige la opción catálogo. E2: El cliente elige ver solo platos o solo insumos del catálogo. |Claudia Rozas| 3 | In Progress|
| US19 | Abrir vista de consumidor | Como cliente quiero contar con la vista de consumidor para asegurar que mis productos se vean atractivos para los consumidores. | Dado que el cliente se encuentra en la ventana “Catálogo”, Cuando el cliente presione la opción: “Vista de consumidor”. Entonces la aplicación mostrará la ventana “Vista de consumidor” con los productos organizados de la forma en las que se le presenta al cliente. | El cliente ingresa a “vista de consumidor” |Andres Reynoso| 3 | Done|
| US22 | Poder leer los comentarios de los usuarios. | Como cliente quiero leer el feedback de los comensales para mejorar. | Dado que el cliente se encuentra dentro de la ventana “Reseñas de consumidores” cuando se dirige al área de opiniones, entonces puede leer los comentarios de los consumidores. | El cliente entra en la sección de consumidores y visualiza quiénes han hecho comentarios.| Andres Reynoso| 3 | In Progress|

#### Sprint Backlog 1 Landing Page

| Story ID | Titulo | Descripcion | Criterios de Aceptacion | Escenarios | Responsable | Puntos | Estado |
|-----------|-----------|-----------|-----------|-----------|-----------|-----------|-----------|
| US27 | Visualizar la sección home del landing page | Como usuario quiero ver la sección “home” para ver la información principal. | Dado que el usuario se encuentra en el landing page, cuando se dirija a la sección de home, entonces visualiza una breve descripción de la aplicación e información de sus segmentos. | Usuario se dirige a la sección “home” de la landing page.| Adrian Marquina | 5 | En progreso |
| US28 | Visualizar la sección "about us" en landing page | Como usuario quiero ver la sección “about us” para saber porque TastyPoint es innovadora en el área de comida a domicilio. | Dado que el usuario se encuentra en el landing page, cuando se dirija a la sección de about us”, entonces visualizará la información de TastyPoint. | Usuario se dirige a la sección “about us” de la landing page. | Adrian Marquina | 5 | En progreso |
| US29 |Visualizar la sección "segments" en landing page | Como usuario quiero ver la sección “segments” para conocer a quienes está dirigida la aplicación y sus beneficios.|Dado que el usuario se encuentra en el landing page, cuando se dirija a la sección de “segments”, entonces visualiza el público objetivo de TastyPoint y las características de la aplicación en cada uno.|Usuario se dirige a la sección “segments” de la landing page | Adrian Marquina | 5 | En progreso |

#### 7.2.1.3. Development Evidence for Sprint Review

#### Sprint Backlog 1 Development Evidence Web Application

| Repositorio | Commit | Mensaje | Autor |
|-------------|-------------|-------------|-------------|
|TastyPoint-FrontEnd-Web-Application|a470f5737dae15a63a0080aea951bc398af104c4 |Added Web Application, currently missing features | Andres Reynoso |
|TastyPoint-FrontEnd-Web-Application |0379cc63d954d4fa82a0dd7381dcfd2a569f552a |Added Layout Segment |Andres Reynoso |
|TastyPoint-FrontEnd-Web-Application |2542129dcb4ff17f51db920d04c20e35c42b2224 |Added Layout |Andres Reynoso |
|TastyPoint-FrontEnd-Web-Application |696ce9bb78812e9521b8e084e503ac532542eef5 |Added Orders component |Andres Reynoso |
|TastyPoint-FrontEnd-Web-Application |69a58e3e6e8c1d938b34d077c80e40d3e597f091 |Added Profile |Andres Reynoso |
|TastyPoint-FrontEnd-Web-Application |38f092cc28157843bf12b4966efafc3f135db803 |added security |Claudia Rozas |
|TastyPoint-FrontEnd-Web-Application |73842ea48ff9220629ef0462928c4ba10524c765 |added selling |Claudia Rozas |
|TastyPoint-FrontEnd-Web-Application |2e21e5ed70651353dc83ca0daa3262e9b951ab87 |Added Publishing |Andres Reynoso |
|TastyPoint-FrontEnd-Web-Application |4d53fb3046adf4e08ad4bfe3ad35bfc25c72223b |added selling |Claudia Rozas |
|TastyPoint-FrontEnd-Web-Application |885b8946b84a9c25a23d421dff403563e76d2323 |added shared | Claudia Rozas|
|TastyPoint-FrontEnd-Web-Application |ede4361d9f255c6039cb4e6fba140dc981e40be7 |added social |Claudia Rozas |
|TastyPoint-FrontEnd-Web-Application |e1594fb0bffeffaf5fb09af99adacb7f30c8f37e |Fixed Routes |Andres Reynoso |
|TastyPoint-FrontEnd-Web-Application |e97b5f65586ad8fe94619aa01c078a90811d6775 |Fixed routes and uses fake API |Andres Reynoso |
|TastyPoint-FrontEnd-Web-Application |419c5538e26b57224ce5abe97e12899c30be2cb0 |Fixed styles for security to match with mock ups |Andres Reynoso |
|TastyPoint-FrontEnd-Web-Application |249a54f1e60911a7a79c96837c97221ee2327ad4 |Added styles for consumers to match with mock ups |Andres Reynoso |
|TastyPoint-FrontEnd-Web-Application |96773931332614fea1c26f7d7c523f645b1500c2 |Fixed settings for business, also added new styles | Andres Reynoso|

#### Sprint Backlog 1 Development Evidence Mobile Application

| Repositorio | Commit | Mensaje | Autor |
|-------------|-------------|-------------|-------------|
|Mobile-App|71b6ef070860d01b4a5d33c3ab13abd13cf431b8|added mobile app|David Torres|

#### Sprint Backlog 1 Development Evidence VR Application

| Repositorio | Commit | Mensaje | Autor |
|-------------|-------------|-------------|-------------|
|TastyPoint_VR_Project|797d05eb527d92ac237315e99a88960abaac52be|Add files via upload|Marco Mendoza|

#### Sprint Backlog 1 Development Evidence Landing Page

| Repositorio | Commit | Mensaje | Autor |
|-------------|-------------|-------------|-------------|
| TastyPoint-landing-page | 6b030de0613ebd540511da021b7676f0df59fd50 | deployment | Adrian Marquina |
| TastyPoint-landing-page | 23e4521efa2576a0232de0137b222a713d7a5beb | deployment | Adrian Marquina |
| TastyPoint-landing-page | 1d3be24bfa01f2e8557296521813c6cc5a8e5245 | ci: add Azure Static Web Apps workflow file  | Adrian Marquina |
| TastyPoint-landing-page | 41c4739bf813d86a54acaf676c793a47bd5800e7 | Content | Adrian Marquina |
| TastyPoint-landing-page | cbc186bb2bd2515e01c50154c6923fc859cd35ec | added first sections structure | Adrian Marquina |
| TastyPoint-landing-page | 689cdbac816d305867a4ff38f96a488ebb915f4f | tailwind primary colors | Adrian Marquina |
| TastyPoint-landing-page | 0a894b01ba1989dc38dca560cc713ce0bbae22d0 | setup | Adrian Marquina |
| TastyPoint-landing-page | 8e80881e245e2cb91a165634d3f673cadbc294ff | first commit | Adrian Marquina |

#### 7.2.1.4. Testing Suite Evidence for Sprint Review

#### Sprint Backlog 1 Testing Suite Evidence Consumer

| ID de Prueba | Story ID | Descripción de la Prueba                                           | Pasos de Prueba                                                | Resultado Esperado                                                                                                   | Responsable de la Prueba | Estado de la Prueba |
|--------------|----------|--------------------------------------------------------------------|----------------------------------------------------------------|---------------------------------------------------------------------------------------------------------------------|-------------------------|---------------------|
| T1 | US01 | Creacion de usuario, email y password  | 1. Navegar a la aplicacion. 2. Ir a la seccion de sign in | El usuario deberia de crearse una cuenta | Andres Reynoso | Done |
| T2 | US02 | Visualizacion de pagina de perfil | 1. Registrarse en la aplicacion. 2. Ir a Settings | El usuario deberia de visualizar la seccion de modificar perfil | Andres Reynoso | In Progress |
| T3 | US03 | Cerrar Sesion de usuario | 1. Ir a la seccion de Sign Out. 2. Aceptar el mensaje | El usuario deberia de poder cerrar sesion con normalidad | Claudia Rozas | In Progress |
| T4 | US05 | Verificacion de Notificaciones | 1. Iniciar Sesion. 2. Ir a la seccion de Notifications | El usuario deberia de ver las notificaciones | Andres Reynoso | Done |
| T5 | US06 | Marcar como favorito  | 1. Ir a la lista. 2. Darle click al corazon al lado del producto.| El usuario deberia de tener la opcion de marcar como favoritos | Claudia Rozas | In Progress |
| T6 | US07 | Verificacion de Productos Publicados | 1. Iniciar Sesion. 2. Ir a la seccion de List| El usuario deberia de visualizar los productos que estan publicados | Claudia Rozas | In Progress |
| T7 | US09 | Desarrollo de comentario| 1. El usuario va a la pagina de un restaurante. 2. Escribe su comentario debajo del perfil. | El usuario deberia de poder dejar su comentario en la pagina del restaurante | Claudia Rozas | In Progress |

#### Sprint Backlog 1 Testing Suite Evidence Business

| ID de Prueba | Story ID | Descripción de la Prueba                                           | Pasos de Prueba                                                | Resultado Esperado                                                                                                   | Responsable de la Prueba | Estado de la Prueba |
|--------------|----------|--------------------------------------------------------------------|----------------------------------------------------------------|---------------------------------------------------------------------------------------------------------------------|-------------------------|---------------------|
| T8 | US11 |Creacion de username, email y password | 1. Ingresa a la app. 2. Ir a la seccion de Register | El usuario deberia crearse su cuenta | Andres Reynoso | Done |
| T9 | US15 | El usuario agrega sus redes como facebook | 1. El usuario se registra. 2. Va a settings. | El usuario agrega sus redes sociales | Andres Reynoso | In Progress |
| T10 | US17 | Vista de los pedidos que otros usuarios han ordenado | 1. El usuario va a "Ordenes". 2. Se visualizaran los pedidos realizados por los clientes. | El usuario ingresa al registro de pedidos | Claudia Rozas | In Progress |
| T11  | US18 | Visualizacion el catalogo de platos que hay | 1. El usuario ingresa a la aplicacion. 2. El usuario va a la seccion "Catalogo" | El usuario ve el catalogo de platos | Claudia Rozas | In Progress |
| T12  | US19 | Visualizacion de vista de consumidor | 1. El usuario va a la seccion de "Catalogo". 2. El usuario presiona "Vista de consumidor" | El usuario ve la vista de consumidor | Andres Reynoso | Done |
| T13  | US22 | Visualizacion de comentarios | 1. El usuario ve el perfil de su restaurante 2. El usuario ve los comentarios publicados | El usuario lee los comentarios de los usuarios | Andres Reynoso | In Progress |

#### Sprint Backlog 1 Testing Suite Evidence Landing Page

Para el sprint 1, solo se construyo la matriz de pruebas.

| ID de Prueba | Story ID | Descripción de la Prueba                                           | Pasos de Prueba                                                | Resultado Esperado                                                                                                   | Responsable de la Prueba | Estado de la Prueba |
|--------------|----------|--------------------------------------------------------------------|----------------------------------------------------------------|---------------------------------------------------------------------------------------------------------------------|-------------------------|---------------------|
| T1           | US27     | Verificar la visualización de la sección "home" en la landing page | 1. Navegar a la landing page<br>2. Hacer clic en la sección "home" o desplazarse hasta ella | El usuario debería ver una breve descripción de la aplicación e información de sus segmentos                          | Adrian Marquina         | Pendiente           |
| T2           | US28     | Verificar la visualización de la sección "about us" en landing page | 1. Navegar a la landing page<br>2. Hacer clic en la sección "about us" o desplazarse hasta ella | El usuario debería ver la información sobre por qué TastyPoint es innovadora en el área de comida a domicilio         | Adrian Marquina         | Pendiente           |
| T3           | US29     | Verificar la visualización de la sección "segments" en landing page | 1. Navegar a la landing page<br>2. Hacer clic en la sección "segments" o desplazarse hasta ella | El usuario debería ver información sobre el público objetivo de TastyPoint y las características de la aplicación     | Adrian Marquina         | Pendiente           |

#### 7.2.1.5. Execution Evidence for Sprint Review

#### Sprint Backlog 1 Execution Evidence Web Application

![Web Execution](https://media.discordapp.net/attachments/973358848159133696/1169810425639084124/image.png?ex=6556c1db&is=65444cdb&hm=f2ed9a3c0121d746e24f86d3de5357fef2fc7ce528ad8c5d6eed4daaee598611&=&width=961&height=669)

Commits in Web Aplication Repository:

![Web Commits](https://media.discordapp.net/attachments/973358848159133696/1169810159938322502/image.png?ex=6556c19c&is=65444c9c&hm=f3ca90d21e891cda0447edd0fab65558e0cdecd6f98a7e7bdf40399697c395c8&=&width=1308&height=669)

#### Sprint Backlog 1 Execution Evidence Mobile Application

![Mobile Execution](Images/sprint-1-mobile-execution-1.png)

Commits in Mobile Aplication Repository:

![image](https://github.com/Arquitectura-Software-2023/Project-Report/assets/89089640/eff28606-8e8a-4ecf-9911-9e1d19548e0c)

#### Sprint Backlog 1 Execution Evidence VR Application

![VR Execution](Images/sprint-1-vr-execution-1.png)

Commits in VR Aplication Repository:

![VR Commits](Images/sprint-1-vr-commits-1.png)

#### Sprint Backlog 1 Execution Evidence Landing Page

![Landing Execution](Images/sprint-1-landing-execution-1.png)

Commits in Landing Page Repository:

![Landing Commits](Images/sprint-1-landing-commits-1.png)

#### 7.2.1.6. Services Documentation Evidence for Sprint Review

#### Sprint Backlog 1 Documentation Evidence Consumer

| ID de Documento | Story ID | Tipo de Documento           | Descripción                                                  | Responsable       | Fecha de Última Actualización | Estado     |
|-----------------|----------|-----------------------------|--------------------------------------------------------------|----------------------------------|-------------------|-------------------------------|
| D1 | US01 | Especificación de Requisitos | Documento detallando los requisitos y funcionalidades de la sección Sign In| Claudia Rozas |31/10/2023 |Pendiente |
| D2 | US02 | Especificación de Requisitos | Documento detallando los requisitos y funcionalidades de la sección Settings| Andres Reynoso |31/10/2023 |Pendiente |
| D3 | US03 | Especificación de Requisitos | Documento detallando los requisitos y funcionalidades de la sección Sign Out| Claudia Rozas |31/10/2023 |Pendiente |
| D4 | US05 | Especificación de Requisitos | Documento detallando los requisitos y funcionalidades de la sección Notifications | Claudia Rozas |31/10/2023 |Pendiente |
| D5 | US06 | Especificación de Requisitos | Documento detallando los requisitos y funcionalidades de la sección Favorites | Andres Reynoso | 31/10/2023 | Pendiente |
| D6 | US07 | Especificación de Requisitos | Documento detallando los requisitos y funcionalidades de la sección List | Claudia Rozas | 31/10/2023 | Pendiente |
| D7 | US09 | Especificación de Requisitos | Documento detallando los requisitos y funcionalidades de la sección de comentarios  | Andres Reynoso | | Pendiente |
| D8 | US01 | Diseño de Interfaz | Documento con los mockups y diseños de la sección Sign In | Claudia Rozas | 02/11/2023 | Done |
| D9 | US02 | Diseño de Interfaz | Documento con los mockups y diseños de la sección Settings | Andres Reynoso | 02/11/2023 | Done |
| D10 | US03 | Diseño de Interfaz | Documento con los mockups y diseños de la sección Sign Out  | Claudia Rozas | 02/11/2023 | Done |
| D11 | US05 | Diseño de Interfaz | Documento con los mockups y diseños de la sección Notifications | Claudia Rozas | 02/11/2023 | Done |
| D12 | US06 | Diseño de Interfaz | Documento con los mockups y diseños de la sección Favorites | Andres Reynoso  | 02/11/2023 | Done |
| D13 | US07 | Diseño de Interfaz | Documento con los mockups y diseños de la sección List | Claudia Rozas | 02/11/2023 | Done |
| D14 | US09 | Diseño de Interfaz | Documento con los mockups y diseños de la sección de comentarios | Andres Reynoso | 02/11/2023 | Done |
| D15 | US01 | Manual de Usuario | Documento que guía al usuario en cómo utilizar el Sign In | Claudia Rozas | 31/10/2023 | Pendiente |
| D16 | US02 | Manual de Usuario | Documento que guía al usuario en cómo utilizar la sección Settings | Andres Reynoso | 01/11/2023 | Pendiente |
| D17 | US03 | Manual de Usuario | Documento que guía al usuario en cómo utilizar el Sign Out | Claudia Rozas | 31/10/2023 | Pendiente |
| D18 | US05 | Manual de Usuario | Documento que guía al usuario en cómo ver la sección Notifications | Claudia Rozas |  31/10/2023 | Pendiente |
| D19 | US06 | Manual de Usuario | Documento que guía al usuario en cómo utilizar la sección Favorites | Andres Reynoso | 31/10/2023 | Pendiente |
| D20 | US07 | Manual de Usuario | Documento que guía al usuario en cómo ver la sección List | Claudia Rozas | 31/10/2023 | Pendiente |
| D21 | US09 | Manual de Usuario | Documento que guía al usuario en cómo realizar un comentario | Andres Reynoso | 31/10/2023 | Pendiente |

#### Sprint Backlog 1 Documentation Evidence Business

| ID de Documento | Story ID | Tipo de Documento           | Descripción                                                  | Responsable       | Fecha de Última Actualización | Estado     |
|-----------------|----------|-----------------------------|--------------------------------------------------------------|----------------------------------|-------------------|-------------------------------|
| D22 | US11 | Especificación de Requisitos | Documento detallando los requisitos y funcionalidades de la sección Sign In| Andres Reynoso |31/10/2023 |Pendiente |
| D23 | US15 | Especificación de Requisitos | Documento detallando los requisitos y funcionalidades de la sección de Settings| Claudia Rozas |01/11/2023 |Pendiente |
| D24 | US17 | Especificación de Requisitos | Documento detallando los requisitos y funcionalidades de la sección Orders| Claudia Rozas |01/11/2023 |Pendiente |
| D25 | US18 | Especificación de Requisitos | Documento detallando los requisitos y funcionalidades de la sección Catalogue | Andres Reynoso |01/11/2023 |Pendiente |
| D26 | US19 | Especificación de Requisitos | Documento detallando los requisitos y funcionalidades de la sección Consumer View | Andres Reynoso | 29/10/2023 | Pendiente |
| D27 | US22 | Especificación de Requisitos | Documento detallando los requisitos y funcionalidades de la sección del perfil de restaurante | Andres Reynoso | 31/10/2023 | Pendiente |
| D28 | US11 | Diseño de Interfaz | Documento con los mockups y diseños de la sección Sign In | Claudia Rozas | 02/11/2023 | Done |
| D29 | US15 | Diseño de Interfaz | Documento con los mockups y diseños de la sección Settings | Andres Reynoso | 02/11/2023 | Done |
| D30 | US17 | Diseño de Interfaz | Documento con los mockups y diseños de la sección Orders  | Andres Reynoso | 02/11/2023 | Done |
| D31 | US18 | Diseño de Interfaz | Documento con los mockups y diseños de la sección Catalogue | Claudia Rozas | 02/11/2023 | Done |
| D32 | US19 | Diseño de Interfaz | Documento con los mockups y diseños de la sección Consumer View | Claudia Rozas  | 02/11/2023 | Done |
| D33 | US22 | Diseño de Interfaz | Documento con los mockups y diseños de la sección del perfil de restaurante | Claudia Rozas | 02/11/2023 | Done |
| D34 | US11 | Manual de Usuario | Documento que guía al usuario en cómo utilizar el Sign In | Claudia Rozas | 31/10/2023 | Pendiente |
| D35 | US15 | Manual de Usuario | Documento que guía al usuario en cómo utilizar la sección Settings | Andres Reynoso | 01/11/2023 | Pendiente |
| D36 | US17 | Manual de Usuario | Documento que guía al usuario en cómo utilizar Orders | Claudia Rozas | 31/10/2023 | Pendiente |
| D37 | US18 | Manual de Usuario | Documento que guía al usuario en cómo ver la sección Catalogue | Claudia Rozas |  30/10/2023 | Pendiente |
| D38 | US19 | Manual de Usuario | Documento que guía al usuario en cómo utilizar la sección Consumer View | Claudia Rozas | 30/10/2023 | Pendiente |
| D39 | US22 | Manual de Usuario | Documento que guía al usuario en cómo ver el perfil de restaurante | Andres Reynoso | 01/11/2023 | Pendiente |

#### Sprint Backlog 1 Documentation Evidence Landing Page

Para el sprint 1 solo se logro desarrollar la matriz de documentos.

| ID de Documento | Story ID | Tipo de Documento           | Descripción                                                  | Responsable       | Fecha de Última Actualización | Estado     |
|-----------------|----------|-----------------------------|--------------------------------------------------------------|----------------------------------|-------------------------------|------------|
| D1              | US27     | Especificación de Requisitos | Documento detallando los requisitos y funcionalidades de la sección "home" en la landing page. | Adrian Marquina   | 29/10/2023                    | Pendiente   |
| D2              | US28     | Especificación de Requisitos | Documento detallando los requisitos y funcionalidades de la sección "about us" en la landing page. | Adrian Marquina   | 29/10/2023                    | Pendiente   |
| D3              | US29     | Especificación de Requisitos | Documento detallando los requisitos y funcionalidades de la sección "segments" en la landing page.| Adrian Marquina   | 29/10/2023                    | Pendiente   |
| D4              | US27     | Diseño de Interfaz           | Documento con los mockups y diseños de la sección "home" en la landing page.| Diseñador Gráfico | 29/10/2023                    | Pendiente |
| D5              | US28     | Diseño de Interfaz           | Documento con los mockups y diseños de la sección "about us" en la landing page. | Diseñador Gráfico | 29/10/2023                    | Pendiente |
| D6              | US29     | Diseño de Interfaz           | Documento con los mockups y diseños de la sección "segments" en la landing page. | Diseñador Gráfico | 29/10/2023                    | Pendiente |
| D7              | US27     | Manual de Usuario            | Documento que guía al usuario en cómo utilizar la sección "home" en la landing page. | Equipo de Soporte | 29/10/2023                    | Pendiente   |
| D8              | US28     | Manual de Usuario            | Documento que guía al usuario en cómo utilizar la sección "about us" en la landing page. | Equipo de Soporte | 29/10/2023                    | Pendiente   |
| D9              | US29     | Manual de Usuario            | Documento que guía al usuario en cómo utilizar la sección "segments" en la landing page. | Equipo de Soporte | 29/10/2023                    | Pendiente   |

#### 7.2.1.7. Software Deployment Evidence for Sprint Review

#### Sprint Backlog 1 Deployment Evidence Web Application

Para desarrollar el deployment del Web Application, se ha usado Netlify, debido a su facilidad de uso. Para el despliegue simplemente se vinculo el repositorio de GitHub con el programa y automaticamente te deja el enlace.

Debido a que se uso el fake API en este sprint, se tendra que despleagar el json de forma local.
![image](https://media.discordapp.net/attachments/973358848159133696/1169813031270748240/image.png?ex=6556c448&is=65444f48&hm=ce252caace8fe53d2333b3e00bb0aeb970d8c79b0514f47a96113bfba94f9515&=&width=1190&height=669)

A continuacion podemos observar que la aplicacion se ha desplegado de forma correcta:

![image](https://media.discordapp.net/attachments/973358848159133696/1169814061693808670/image.png?ex=6556c53e&is=6544503e&hm=77a3b59e693ea73861b3ad39d7f68259ba4838c259b332c5a279bf09fa27bd13&=&width=1190&height=669)

Enlace desplegado: [https://tastypoint.netlify.app](https://tastypoint.netlify.app/)

#### Sprint Backlog 1 Deployment Evidence Mobile Application

![image](https://github.com/Arquitectura-Software-2023/Project-Report/assets/89089640/5f315ff4-5bbb-4569-a512-6feac90fb087&height=600)

#### Sprint Backlog 1 Deployment Evidence VR Application

![Menu](Images/sprint-1-vr-deployment-1.png)
![Store inside 1](Images/sprint-1-vr-deployment-2.png)
![Store inside 2](Images/sprint-1-vr-deployment-3.png)

#### Sprint Backlog 1 Deployment Evidence Landing Page

Se implemento el pipeline de despliegue continuo con azure. Acontinuacion, se adjunta la evidencia del despliegue del landing page: [Url](https://jolly-field-04c7e7710.4.azurestaticapps.net/) <https://jolly-field-04c7e7710.4.azurestaticapps.net/>

Deployment
![Github Action detail](Images/sprint-1-landing-deployment-1.png)
![Azure portal](Images/sprint-1-landing-deployment-2.png)
![Deployed landing page](Images/sprint-1-landing-deployment-3.png)

#### 7.2.1.8. Team Collaboration Insights during Sprint

| Sprint Review | 1 |
|-----------------|---|
| Fecha | 20/10/2023 - 08:00 |
| Lugar | Remote - Discord |
| Asistentes | Todo el equipo |
| Resultados y Acuerdos | Revisamos el avance total del desarrollo, se encontraba en el 40% de lo comprometido |

| Sprint Review | 2 |
|-----------------|---|
| Fecha | 27/10/2023 - 08:00 |
| Lugar | Remote - Discord |
| Asistentes | Todo el equipo |
| Resultados y Acuerdos | Revisamos el avance total del desarrollo, se encontraba en el 80% de lo comprometido |

### 7.2.2. Sprint 2

#### 7.2.2.1. Sprint 2 Planning

| Sprint Planning | 1 |
|-----------------|---|
| Fecha | 06/11/2023 - 08:00 |
| Lugar | Remote - Discord |
| Asistentes | Todo el equipo |
| Resultados y Acuerdos | Spring Backlog 2 |

#### 7.2.2.2. Sprint 2 Backlog

#### Sprint Backlog 2 Consumer

| Story ID | Titulo | Descripcion | Criterios de Aceptacion | Escenarios | Responsable | Puntos | Estado |
|-----------|-----------|-----------|-----------|-----------|-----------|-----------|-----------|
| US01 | Registro de Consumidor | Como consumidor quiero crear una cuenta para acceder a la aplicación. | CA1: Dado que el consumidor se encuentra en la ventana de registro y completa todos los campos. Cuando presiona el botón registrarse. Entonces podrá acceder a la aplicación. CA2: Dado que el consumidor se encuentra en la ventana de registro y no completa todos los campos obligatorios. Cuando presiona el botón registrarse. Entonces esos campos se marcan de rojo Y se muestra el mensaje: “Complete los campos obligatorios”. CA3: Dado que el consumidor se encuentra en la ventana de registro y completa erróneamente los campos. Cuando presiona el botón registrarse. Entonces se muestra el siguiente mensaje: “Complete los campos correctamente”. | E1: El consumidor quiere registrarse en la aplicación. E2: El consumidor no completa los campos obligatorios. E3: El consumidor intenta registrarse, pero no completa con datos correctos los campos obligatorios. |Andres Reynoso| 3 | Done|
| US02 | Monitorear el perfil | Como consumidor quiero ver el perfil de mi cuenta para corroborar que mis datos sean correctos. | Dado que el consumidor quiere ver su perfil. Cuando presiona el icono de perfil ubicado en la sección de menú. Entonces la aplicación muestra la información del perfil del consumidor. | El consumidor quiere ver su perfil. | Andres Reynoso| 3 | Done|
| US03 | Cerrar sesión de consumidor | Como consumidor quiero cerrar sesión para salir de mi cuenta.| CA1: Dado que el consumidor se encuentra en la aplicación. Cuando presiona el icono de perfil ubicado en la sección de menú. Entonces se le mostrará un mensaje: ¿Está seguro de cerrar sesión? Y el consumidor selecciona la opción sí para cerrar la sesión. CA2: Dado que el consumidor se encuentra en la aplicación. Cuando presiona el botón de cerrar sesión. Entonces se le mostrará un mensaje: ¿Está seguro de cerrar sesión? Y el consumidor selecciona la opción no para mantener iniciada la sesión. | E1:  El consumidor quiere cerrar sesión en el sistema. E2: El consumidor presiona por error el botón de “Cerrar sesión “.| Claudia Rozas| 2 | Done|
| US05 | Visualizar todas las notificaciones | Como consumidor, quiero visualizar las notificaciones para estar informado sobre las ofertas que ofrezcan los restaurantes. | Dado que el consumidor se encuentra en la aplicación, cuando ingresa a la sección de notificaciones, entonces le aparecen las notificaciones realizadas por los restaurantes registrados en la aplicación. |  Ver ofertas publicadas por restaurantes. | Andres Reynoso | 2 |Done|

#### Sprint Backlog 2 Business

| Story ID | Titulo | Descripcion | Criterios de Aceptacion | Escenarios | Responsable | Puntos | Estado |
|-----------|-----------|-----------|-----------|-----------|-----------|-----------|-----------|
| US11 | Registro de Cliente | Como cliente quiero crear una cuenta para acceder a la aplicación. |CA1:  Dado que el cliente se encuentra en la ventana de registro y completa todos los campos. Cuando presiona el botón registrarse. Entonces podrá acceder a la aplicación. CA2: Dado que el cliente se encuentra en la ventana de registro y no completa todos los campos obligatorios. Cuando presiona el botón registrarse. Entonces esos campos se marcan de rojo y se muestra el mensaje: “Complete los campos obligatorios”. CA3: Dado que el cliente se encuentra en la ventana de registro y completa erróneamente los campos. Cuando presiona el botón registrarse. Entonces se muestra el siguiente mensaje: “Complete los campos correctamente”.| E1: El cliente quiere registrarse en la aplicación. E2: El cliente no completa los campos obligatorios. E3: El cliente intenta registrarse, pero no completa con datos correctos los campos obligatorios.| Andres Reynoso| 3 | Done|
| US15 | Medios de contacto | Como cliente quiero enlazar todos los medios de comunicación que poseo para permitir a mis consumidores contactarse directamente con nosotros. | Dado que el cliente se encuentra en la ventana “Perfil”, cuando selecciona “Agregar redes sociales” y los agrega, entonces la aplicación mostrará un mensaje “Se agregó con éxito”. | Añadir redes sociales | Andres Reynoso| 2 | Done|
| US17 | Ver pedidos |Como cliente quiero ver la lista de pedidos solicitados en mi restaurante, para conocer la demanda a través de la App web. | Dado que el cliente ha iniciado sesión, se encuentra en la ventana principal de Tasty point y hace clic en la sección “Órdenes”, cuando el cliente se encuentre en dicha sección, entonces aparecerá una lista con los nombres de los consumidores que realizaron un pedido en específico con fecha, hora y cantidad ordenada. | El cliente ingresa al registro de pedidos. |Claudia Rozas| 3 | Done|

#### Sprint Backlog 2 Landing Page

| Story ID | Titulo | Descripcion | Criterios de Aceptacion | Escenarios | Responsable | Puntos | Estado |
|-----------|-----------|-----------|-----------|-----------|-----------|-----------|-----------|
| US27 | Visualizar la sección home del landing page | Como usuario quiero ver la sección “home” para ver la información principal. | Dado que el usuario se encuentra en el landing page, cuando se dirija a la sección de home, entonces visualiza una breve descripción de la aplicación e información de sus segmentos. | Usuario se dirige a la sección “home” de la landing page.| Adrian Marquina | 5 | Done |
| US28 | Visualizar la sección "about us" en landing page | Como usuario quiero ver la sección “about us” para saber porque TastyPoint es innovadora en el área de comida a domicilio. | Dado que el usuario se encuentra en el landing page, cuando se dirija a la sección de about us”, entonces visualizará la información de TastyPoint. | Usuario se dirige a la sección “about us” de la landing page. | Adrian Marquina | 5 | Done |
| US29 |Visualizar la sección "segments" en landing page | Como usuario quiero ver la sección “segments” para conocer a quienes está dirigida la aplicación y sus beneficios.|Dado que el usuario se encuentra en el landing page, cuando se dirija a la sección de “segments”, entonces visualiza el público objetivo de TastyPoint y las características de la aplicación en cada uno.|Usuario se dirige a la sección “segments” de la landing page | Adrian Marquina | 5 | In Progress |
| US23 | Botón call to action | Como usuario deseo que el landing page posea un botón call-to-action para poder acceder directamente hacia la aplicación | Dado que el usuario se encuentra en el landing page. Cuando el usuario seleccione el botón Call to action llamado Comenzar. Entonces el sistema redirigirá al usuario a la aplicación web. | Presión del botón CTA | Adrian Marquina | 5 | QA |
| US25 | Visualización de planes de suscripción | Como usuario deseo poder visualizar los planes de suscripción en el landing page para poder informarme cuanto son las cantidades por pagar por el servicio. | CA1: Dado que el usuario se encuentra en el landing page. Cuando el usuario seleccione la opción Planes de suscripción. Entonces el landing page le mostrará los planes de suscripción. CA2: Dado que el usuario se encuentra en el landing page. Cuando el usuario deslice el landing page hacia abajo. Entonces la aplicación permitirá visualizar los planes de suscripción. | E1: Selección de opción para visualizar planes. E2:Desliza la pantalla para visualizar planes. | Adrian Marquina | 5 | To Do |
| US26 | Visualización de redes sociales | Como usuario deseo poder acceder a las redes sociales del startup por medio del landing page para conocer más acerca de este. | Dado que el usuario se encuentra en el landing page. Cuando el usuario deslice la página hasta el final. Entonces la aplicación mostrará el footer en el cual se encontrarán las redes sociales y demás información. | Visualización de redes sociales en el Footer. | Adrian Marquina | 5 | In Progress |

#### 7.2.2.3. Development Evidence for Sprint Review

#### Sprint Backlog 2 Development Evidence Web Application

| Repositorio | Commit | Mensaje | Autor |
|-------------|-------------|-------------|-------------|
|TastyPoint-FrontEnd-Web-Application |ede4361d9f255c6039cb4e6fba140dc981e40be7 |added social |Claudia Rozas |
|TastyPoint-FrontEnd-Web-Application |e1594fb0bffeffaf5fb09af99adacb7f30c8f37e |Fixed Routes |Andres Reynoso |
|TastyPoint-FrontEnd-Web-Application |e97b5f65586ad8fe94619aa01c078a90811d6775 |Fixed routes and uses fake API |Andres Reynoso |
|TastyPoint-FrontEnd-Web-Application |419c5538e26b57224ce5abe97e12899c30be2cb0 |Fixed styles for security to match with mock ups |Andres Reynoso |
|TastyPoint-FrontEnd-Web-Application |249a54f1e60911a7a79c96837c97221ee2327ad4 |Added styles for consumers to match with mock ups |Andres Reynoso |
|TastyPoint-FrontEnd-Web-Application |96773931332614fea1c26f7d7c523f645b1500c2 |Fixed settings for business, also added new styles | Andres Reynoso|

#### Sprint Backlog   Development Evidence Mobile Application

| Repositorio | Commit | Mensaje | Autor |
|-------------|-------------|-------------|-------------|
| Mobile-App  | 7135b0133fc470c78aa13e2c3e157ef16c6d3e78  | Fixed features: add quantity, delete, add product.  | David Torres |

#### Sprint Backlog 2 Development Evidence VR Application

| Repositorio | Commit | Mensaje | Autor |
|-------------|-------------|-------------|-------------|
| TastyPoint_VR_Project | c883cfb7c35e20694e46291baa298cb74997dc02 | Create README.md | Marco Mendoza |
| TastyPoint_VR_Project | d87758a3706c56e79dcc516bf7f7788ea97b7da9 | Add files via upload | Marco Mendoza |
| TastyPoint_VR_Project | 1c032622a01ca38e3d0fcc7bff51cd44ff53f8b5 | Add files via upload | Marco Mendoza |
| TastyPoint_VR_Project | 7663f72124133c2e1765619d0cfb2d4ea9063e93 | Add files via upload | Marco Mendoza |

#### Sprint Backlog 2 Development Evidence Landing Page

| Repositorio | Commit | Mensaje | Autor |
|-------------|-------------|-------------|-------------|
| TastyPoint-landing-page | 6696eed14a2c0a4657a01d646f9ec323d180b2fe | Home | Adrian Marquina |
| TastyPoint-landing-page | 58bb59d67d2f24de6f795b8705c48d0372a1de9e | About us | Adrian Marquina |
| TastyPoint-landing-page | a920ad4f3d488e2f193eed3f837a0014798e6467 | Footer first approach | Adrian Marquina |

#### 7.2.2.4. Testing Suite Evidence for Sprint Review

#### Sprint Backlog 2 Testing Suite Evidence Consumer

| ID de Prueba | Story ID | Descripción de la Prueba                                           | Pasos de Prueba                                                | Resultado Esperado                                                                                                   | Responsable de la Prueba | Estado de la Prueba |
|--------------|----------|--------------------------------------------------------------------|----------------------------------------------------------------|---------------------------------------------------------------------------------------------------------------------|-------------------------|---------------------|
| T1 | US01 | Creacion de usuario, email y password  | 1. Navegar a la aplicacion. 2. Ir a la seccion de sign in | El usuario deberia de crearse una cuenta | Andres Reynoso | Done |
| T2 | US02 | Visualizacion de pagina de perfil | 1. Registrarse en la aplicacion. 2. Ir a Settings | El usuario deberia de visualizar la seccion de modificar perfil | Andres Reynoso | Done |
| T3 | US03 | Cerrar Sesion de usuario | 1. Ir a la seccion de Sign Out. 2. Aceptar el mensaje | El usuario deberia de poder cerrar sesion con normalidad | Claudia Rozas | Done |
| T4 | US05 | Verificacion de Notificaciones | 1. Iniciar Sesion. 2. Ir a la seccion de Notifications | El usuario deberia de ver las notificaciones | Andres Reynoso | Done |
| T5 | US06 | Marcar como favorito  | 1. Ir a la lista. 2. Darle click al corazon al lado del producto.| El usuario deberia de tener la opcion de marcar como favoritos | Claudia Rozas | Done |
| T6 | US07 | Verificacion de Productos Publicados | 1. Iniciar Sesion. 2. Ir a la seccion de List| El usuario deberia de visualizar los productos que estan publicados | Claudia Rozas | Done |
| T7 | US09 | Desarrollo de comentario| 1. El usuario va a la pagina de un restaurante. 2. Escribe su comentario debajo del perfil. | El usuario deberia de poder dejar su comentario en la pagina del restaurante | Claudia Rozas | Done |

#### Sprint Backlog 2 Testing Suite Evidence Business

| ID de Prueba | Story ID | Descripción de la Prueba                                           | Pasos de Prueba                                                | Resultado Esperado                                                                                                   | Responsable de la Prueba | Estado de la Prueba |
|--------------|----------|--------------------------------------------------------------------|----------------------------------------------------------------|---------------------------------------------------------------------------------------------------------------------|-------------------------|---------------------|
| T8 | US11 |Creacion de username, email y password | 1. Ingresa a la app. 2. Ir a la seccion de Register | El usuario deberia crearse su cuenta | Andres Reynoso | Done |
| T9 | US15 | El usuario agrega sus redes como facebook | 1. El usuario se registra. 2. Va a settings. | El usuario agrega sus redes sociales | Andres Reynoso | Done |
| T10 | US17 | Vista de los pedidos que otros usuarios han ordenado | 1. El usuario va a "Ordenes". 2. Se visualizaran los pedidos realizados por los clientes. | El usuario ingresa al registro de pedidos | Claudia Rozas | Done |
| T11  | US18 | Visualizacion el catalogo de platos que hay | 1. El usuario ingresa a la aplicacion. 2. El usuario va a la seccion "Catalogo" | El usuario ve el catalogo de platos | Claudia Rozas | Done |
| T12  | US19 | Visualizacion de vista de consumidor | 1. El usuario va a la seccion de "Catalogo". 2. El usuario presiona "Vista de consumidor" | El usuario ve la vista de consumidor | Andres Reynoso | Done |
| T13  | US22 | Visualizacion de comentarios | 1. El usuario ve el perfil de su restaurante 2. El usuario ve los comentarios publicados | El usuario lee los comentarios de los usuarios | Andres Reynoso | Done |

#### Sprint Backlog 2 Testing Suite Evidence Landing Page

| ID de Prueba | Story ID | Descripción de la Prueba                                           | Pasos de Prueba                                                | Resultado Esperado                                                                                                   | Responsable de la Prueba | Estado de la Prueba |
|--------------|----------|--------------------------------------------------------------------|----------------------------------------------------------------|---------------------------------------------------------------------------------------------------------------------|-------------------------|---------------------|
| T1           | US27     | Verificar la visualización de la sección "home" en la landing page | 1. Navegar a la landing page<br>2. Hacer clic en la sección "home" o desplazarse hasta ella | El usuario debería ver una breve descripción de la aplicación e información de sus segmentos                          | Adrian Marquina         | Done           |
| T2           | US28     | Verificar la visualización de la sección "about us" en landing page | 1. Navegar a la landing page<br>2. Hacer clic en la sección "about us" o desplazarse hasta ella | El usuario debería ver la información sobre por qué TastyPoint es innovadora en el área de comida a domicilio         | Adrian Marquina         | Done           |
| T3           | US29     | Verificar la visualización de la sección "segments" en landing page | 1. Navegar a la landing page<br>2. Hacer clic en la sección "segments" o desplazarse hasta ella | El usuario debería ver información sobre el público objetivo de TastyPoint y las características de la aplicación     | Adrian Marquina         | Done           |

#### 7.2.2.5. Execution Evidence for Sprint Review

#### Sprint Backlog 2 Execution Evidence Web Application

![Web Execution](https://media.discordapp.net/attachments/714193289888399362/1176665755085983815/image.png?ex=656fb261&is=655d3d61&hm=759b09ae516e272a4e17f9f7b2ae4c1c0123b357d9375d72a345a5881ad51a9b&=&width=1093&height=669)

Commits in Web Aplication Repository:

![Web Commits](https://media.discordapp.net/attachments/714193289888399362/1176665095821078608/image.png?ex=656fb1c4&is=655d3cc4&hm=4ac4bf6030e0960f8f8fd01813c18c9e34833d860d3f418392fdf59b9b47d4d4&=&width=1440&height=669)

#### Sprint Backlog 2 Execution Evidence Mobile Application

![Mobile Execution](https://github.com/Arquitectura-Software-2023/Project-Report/assets/89089640/f8f2a20c-bb42-44f7-a7df-d4286194e192)

Commits in Mobile Aplication Repository:

![Mobile Commits](https://github.com/Arquitectura-Software-2023/Project-Report/assets/89089640/5f529f93-2e8d-45ef-9e0c-0ffac613ff3e)

#### Sprint Backlog 2 Execution Evidence VR Application

![VR Execution](Images/sprint-2-vr-execution-1.png)

Commits in VR Aplication Repository:

![VR Commits](Images/sprint-2-vr-commits-1.png)

#### Sprint Backlog 2 Execution Evidence Landing Page

![Landing Execution](Images/sprint-2-landing-execution-1.png)

Commits in Landing Page Repository:

![Landing Commits](Images/sprint-2-landing-commits-1.png)

#### 7.2.2.6. Services Documentation Evidence for Sprint Review

#### Sprint Backlog 2 Documentation Evidence Consumer

| ID de Documento | Story ID | Tipo de Documento           | Descripción                                                  | Responsable       | Fecha de Última Actualización | Estado     |
|-----------------|----------|-----------------------------|--------------------------------------------------------------|----------------------------------|-------------------|-------------------------------|
| D1 | US01 | Especificación de Requisitos | Documento detallando los requisitos y funcionalidades de la sección Sign In| Claudia Rozas |21/11/2023  | Done |
| D2 | US02 | Especificación de Requisitos | Documento detallando los requisitos y funcionalidades de la sección Settings| Andres Reynoso |21/11/2023 | Done |
| D3 | US03 | Especificación de Requisitos | Documento detallando los requisitos y funcionalidades de la sección Sign Out| Claudia Rozas |21/11/2023  | Done |
| D4 | US05 | Especificación de Requisitos | Documento detallando los requisitos y funcionalidades de la sección Notifications | Claudia Rozas |21/11/2023  |Done |
| D8 | US01 | Diseño de Interfaz | Documento con los mockups y diseños de la sección Sign In | Claudia Rozas |21/11/2023  | Done |
| D9 | US02 | Diseño de Interfaz | Documento con los mockups y diseños de la sección Settings | Andres Reynoso | 21/11/2023  | Done |
| D10 | US03 | Diseño de Interfaz | Documento con los mockups y diseños de la sección Sign Out  | Claudia Rozas |21/11/2023  | Done |
| D11 | US05 | Diseño de Interfaz | Documento con los mockups y diseños de la sección Notifications | Claudia Rozas | 21/11/2023  | Done |
| D15 | US01 | Manual de Usuario | Documento que guía al usuario en cómo utilizar el Sign In | Claudia Rozas | 21/11/2023  | Done |
| D16 | US02 | Manual de Usuario | Documento que guía al usuario en cómo utilizar la sección Settings | Andres Reynoso | 21/11/2023  | Done |
| D17 | US03 | Manual de Usuario | Documento que guía al usuario en cómo utilizar el Sign Out | Claudia Rozas | 21/11/2023  | Done |
| D18 | US05 | Manual de Usuario | Documento que guía al usuario en cómo ver la sección Notifications | Claudia Rozas |  21/11/2023  | Done |

#### Sprint Backlog 2 Documentation Evidence Business

| ID de Documento | Story ID | Tipo de Documento           | Descripción                                                  | Responsable       | Fecha de Última Actualización | Estado     |
|-----------------|----------|-----------------------------|--------------------------------------------------------------|----------------------------------|-------------------|-------------------------------|
| D22 | US11 | Especificación de Requisitos | Documento detallando los requisitos y funcionalidades de la sección Sign In| Andres Reynoso |21/11/2023 | Done |
| D23 | US15 | Especificación de Requisitos | Documento detallando los requisitos y funcionalidades de la sección de Settings| Claudia Rozas |21/11/2023  | Done |
| D24 | US17 | Especificación de Requisitos | Documento detallando los requisitos y funcionalidades de la sección Orders| Claudia Rozas |21/11/2023  | Done |
| D28 | US11 | Diseño de Interfaz | Documento con los mockups y diseños de la sección Sign In | Claudia Rozas | 21/11/2023  | Done |
| D29 | US15 | Diseño de Interfaz | Documento con los mockups y diseños de la sección Settings | Andres Reynoso |21/11/2023  | Done |
| D30 | US17 | Diseño de Interfaz | Documento con los mockups y diseños de la sección Orders  | Andres Reynoso |21/11/2023  | Done |
| D34 | US11 | Manual de Usuario | Documento que guía al usuario en cómo utilizar el Sign In | Claudia Rozas | 21/11/2023  | Done |
| D35 | US15 | Manual de Usuario | Documento que guía al usuario en cómo utilizar la sección Settings | Andres Reynoso | 21/11/2023  | Done |
| D36 | US17 | Manual de Usuario | Documento que guía al usuario en cómo utilizar Orders | Claudia Rozas | 21/11/2023  | Done |

#### Sprint Backlog 2 Documentation Evidence Landing Page

| ID de Documento | Story ID | Tipo de Documento           | Descripción                                                  | Responsable       | Fecha de Última Actualización | Estado     |
|-----------------|----------|-----------------------------|--------------------------------------------------------------|----------------------------------|-------------------------------|------------|
| D1              | US27     | Especificación de Requisitos | Documento detallando los requisitos y funcionalidades de la sección "home" en la landing page. | Adrian Marquina   | 29/10/2023                    | Done   |
| D2              | US28     | Especificación de Requisitos | Documento detallando los requisitos y funcionalidades de la sección "about us" en la landing page. | Adrian Marquina   | 29/10/2023                    | Done   |
| D3              | US29     | Especificación de Requisitos | Documento detallando los requisitos y funcionalidades de la sección "segments" en la landing page.| Adrian Marquina   | 29/10/2023                    | Done   |
| D4              | US27     | Diseño de Interfaz           | Documento con los mockups y diseños de la sección "home" en la landing page.| Diseñador Gráfico | 29/10/2023                    | Done |
| D5              | US28     | Diseño de Interfaz           | Documento con los mockups y diseños de la sección "about us" en la landing page. | Diseñador Gráfico | 29/10/2023                    | Done |
| D6              | US29     | Diseño de Interfaz           | Documento con los mockups y diseños de la sección "segments" en la landing page. | Diseñador Gráfico | 29/10/2023                    | Done |
| D7              | US27     | Manual de Usuario            | Documento que guía al usuario en cómo utilizar la sección "home" en la landing page. | Equipo de Soporte | 29/10/2023                    | Done   |
| D8              | US28     | Manual de Usuario            | Documento que guía al usuario en cómo utilizar la sección "about us" en la landing page. | Equipo de Soporte | 29/10/2023                    | Done   |
| D9              | US29     | Manual de Usuario            | Documento que guía al usuario en cómo utilizar la sección "segments" en la landing page. | Equipo de Soporte | 29/10/2023                    | Done   |

#### 7.2.2.7. Software Deployment Evidence for Sprint Review

#### Sprint Backlog 2 Deployment Evidence Web Application

Para desarrollar el deployment del Web Application, se ha usado Netlify, debido a su facilidad de uso. Para el despliegue simplemente se vinculo el repositorio de GitHub con el programa y automaticamente te deja el enlace. A continuacion podemos observar que la aplicacion se ha desplegado de forma correcta:

![Sprint Backlog 2 Deployment Evidence Web Application](https://media.discordapp.net/attachments/973358848159133696/1169814061693808670/image.png?ex=6556c53e&is=6544503e&hm=77a3b59e693ea73861b3ad39d7f68259ba4838c259b332c5a279bf09fa27bd13&=&width=1190&height=669)

Enlace desplegado: [https://tastypoint.netlify.app](https://tastypoint.netlify.app/)

#### Sprint Backlog 2 Deployment Evidence Mobile Application

Despliegue de base de datos MySql para el aplicativo.

![Sprint Backlog 2 Deployment Evidence Mobile Application](https://github.com/Arquitectura-Software-2023/Project-Report/assets/89089640/6fe9d80d-5101-45ad-8c2e-8237862fd81d)

#### Sprint Backlog 2 Deployment Evidence VR Application

![Sprint Backlog 2 Deployment Evidence VR Application](Images/sprint-2-vr-deployment-1.png)

![Sprint Backlog 2 Deployment Evidence VR Application](Images/sprint-2-vr-deployment-2.png)

![Sprint Backlog 2 Deployment Evidence VR Application](Images/sprint-2-vr-deployment-3.png)

#### Sprint Backlog 2 Deployment Evidence Landing Page

![Landing Page](Images/sprint-2-landing-deployment-1.png)
![Landing Page](Images/sprint-2-landing-deployment-2.png)
![Landing Page](Images/sprint-2-landing-deployment-3.png)

#### 7.2.2.8. Team Collaboration Insights during Sprint

| Sprint 2 Review | 1 |
|-----------------|---|
| Fecha | 10/11/2023 - 08:00 |
| Lugar | Remote - Discord |
| Asistentes | Todo el equipo |
| Resultados y Acuerdos | Revisamos el avance total del desarrollo, se encontraba en el 30% de lo comprometido |

| Sprint 2 Review | 2 |
|-----------------|---|
| Fecha | 17/10/2023 - 08:00 |
| Lugar | Remote - Discord |
| Asistentes | Todo el equipo |
| Resultados y Acuerdos | Revisamos el avance total del desarrollo, se encontraba en el 70% de lo comprometido |

## 7.3. Validation Interviews

### 7.3.1. Diseño de Entrevistas

**Consumidor:**

Buenos días, me presento, soy ( ) y pertenezco a la carrera de Ingeniería de Software de la UPC. Gracias por acceder a la entrevista, y antes de comenzar con las preguntas, realizaré una breve introducción a nuestro proyecto. Este tiene por nombre Tasty Point y se basa en la distribución de los productos que los establecimientos alimenticios, no llegan a vender durante su jornada. Usted como consumidor, podrá comprar estos productos a través de nuestra aplicación a un menor precio, pero agrupados en paquetes, en la cual se encontrarán los productos de cierto restaurante específico. Dicho esto, comencemos con las validaciones.

 1. ¿Cuál es su nombre completo?

 2. ¿Cuántos años tiene?

 3. En general, ¿Que te ha parecido nuestra aplicacion?

 4. ¿Le gusta la paleta de colores utilizadas?

 5. ¿Cree que cumple con el proposito de ayudar a los consumidores?

 6. ¿Tiene alguna recomendación con respecto a nuestra aplicación?

**Representante de negocio:**

Buenos días, me presento, soy ( ) y pertenezco a la carrera de Ingeniería de Software de la UPC. Gracias por acceder a la entrevista, y antes de comenzar con las preguntas, realizaré una breve introducción a nuestro proyecto. Este tiene por nombre Tasty Point y se basa en la distribución de los productos que los establecimientos alimenticios, no llegan a vender durante su jornada.Por lo que pueden estos establecimientos generar ganancias adicionales con los alimentos que ya habian sido considerado perdidas, asimismo, ayudar a cuidar el planeta disminuyendo el desperdicio de alimentos. Dicho esto, comencemos con las validaciones.

 1. ¿Cuál es su nombre completo?

 2. ¿Cuántos años tiene?

 3. En general, ¿Que te ha parecido nuestra aplicacion?

 4. ¿Le gusta la paleta de colores utilizadas?

 5. ¿Cree que cumple con el proposito de ayudar a los restaurantes?

 6. ¿Tiene alguna recomendación con respecto a nuestra aplicación?

### 7.3.2. Registro de Entrevistas

Entrevista Alejandro Rojas

- Enlace: <https://youtu.be/d76nc7US9HE>
  
- Resumen: Alejandro nos ha comentado que le gusta la primera version de nuestro proyecto, nos indica que algunas secciones estan algo llenas de blanco pero que en general le agrada la paleta de colores y lo intuitiva que es la aplicacion. Por ultimo, nos menciona que no agregaria mas funcionalidades a las que ya se estaran implementando.

Entrevista Diego Cabrera

- Enlace: <https://upcedupe-my.sharepoint.com/:v:/g/personal/u202010942_upc_edu_pe/EbDswuDPM4ZBpIpsYn3Q7HIB9dhb1evjRTgd5ChGFSPe4g?e=W46N4Q&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D>
  
- Resumen: La entrevista a Diego Cabrera Zelada nos proporcionó una mejor visualización de la forma en la que el usuario navega por medio de las funciones de la aplicación móvil y cómo las características implementadas son recibidas. Diego menciono su agrado por la paleta de colores y como esta es cómoda a la vista, así también como las funcionalidades implementadas, el único punto que resalto fue la funcionalidad de la barra de navegación y si se pudieran implementar más pasarelas de pago.

### 7.3.3. Evaluaciones segun Heuristicas

Análisis de los errores identificados:

Web Application:

•Problema #1: La ubicación de las imágenes no es correcta, lo que provoca una falta de alineación entre las imágenes y el texto.
 •Severidad: 4
 •Heurística infringida: Usabilidad: Visibilidad del sistema
 •Descripción: Durante las entrevistas, se observó que los usuarios señalaron este aspecto como una área que necesita mejoras, ya que la alineación entre el texto y las imágenes no es la adecuada. Por lo tanto, es fundamental abordar esta cuestión.
 •Recomendación: Se aconseja ajustar el texto de manera que esté en armonía con las imágenes y se adapte correctamente a la pantalla.

•Problema #2: Existe un exceso de espacio entre las imágenes y el texto.
 •Severidad: 4
 •Heurística infringida: Usabilidad: Visibilidad del sistema
 •Descripción: El espacio que se encuentra dentro de este margen es esencial, ya que afecta la percepción de un diseño dinámico. En consecuencia, se requiere una alineación adecuada entre las imágenes y el texto.
 •Recomendación: Es importante alinear las imágenes y aplicar un diseño que organice toda la información de forma ordenada.

•Problema #3: Los botones no están diseñados de acuerdo con el diseño general.
 •Severidad: 4
 •Heurística infringida: Usabilidad: Visibilidad del sistema
 •Descripción: Los botones deben seguir una estructura que se adapte a todos los elementos interactivos del diseño.
 •Recomendación: Se debe mejorar el llamado a la acción (call to action) para lograr una navegación más fluida y un diseño interactivo más efectivo.

 Mobile Application:

 •Problema #1: Ausencia de una pantalla para confirmar el cierre de sesión.
 •Severidad: 2
 •Heurística infringida: Prevención de errores
 •Descripción: Al dar al botón de cerrar sesión no aparece ninguna pantalla de confirmación, por lo cual si el usuario lo presiona por casualidad tendría que volver a ingresar su correo y contraseña el cual sería un fastidio para el usuario.
 •Recomendación: Se aconseja añadir una notificación para confirmar el cierre de sesión.

•Problema #2: Incluye una barra de búsqueda, pero no cumple su función en su totalidad.
 •Severidad: 4
 •Heurística infringida: Information Architecture – Is it usable?
 •Descripción: Al momento de realizar la búsqueda de un plato de comida, no se muestran laos productos demostrando la falta de funcionamiento de la barra de búsqueda.
 •Recomendación: Se aconseja corregir la funcionalidad de búsqueda o eliminar la barra de navegación innecesaria.

## 7.4. Video About the Product

A continuacion se demostrara un video explicando el primer prototipo de nuestro producto

Enlace: <https://youtu.be/xSLxkfcY4LA>

Mobile application:

Enlace: <https://upcedupe-my.sharepoint.com/:v:/g/personal/u202010942_upc_edu_pe/EW30-rYh3NFFk4-N4g5TcWgBmBGIEfA8gIzpZQG46Gz-6Q?e=YwEbaA&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D>

## 7.5. Video About the Team

A continuacion se demostrara un video sobre el equipo de desarrollo:

Enlace: <https://youtu.be/UhUfWYJhiXQ>

## Conclusiones

La startup Tasty Point se dedica a combatir el desperdicio de alimentos y venderlos a precios justos y más asequibles. Su idea está bien definida y cumple con los estándares del curso. Es importante destacar que el desarrollo del proyecto se inicia con una idea de negocio que tiene un impacto positivo a nivel global y se planean mejoras continuas para garantizar su éxito a largo plazo.

Se recomienda continuar el desarrollo de la aplicación utilizando User Stories, ya que esto ayuda a definir claramente las características y requisitos, brindando una guía sólida para el proceso de desarrollo. Además, herramientas como el Product Backlog son útiles para organizar el tiempo de manera eficiente.

Es esencial realizar un estudio más profundo del código del proyecto, especialmente la página de inicio, para mejorar la eficiencia y la comprensión del mismo. También se necesita un mayor compromiso y dedicación para abordar dudas e inquietudes, lo que puede ser una barrera para resolver problemas de manera efectiva.

En esta entrega, se desarollo principalmente el frontend, validándolo con los usuarios y obteniendo recomendaciones para mejorar y realizar correcciones. Además, se avanzó en el desarrollo del backend para mejorar la usabilidad de la lógica del sitio web, y se espera implementar la mayoría de las recomendaciones y cambios en la entrega final.

El uso de herramientas como GitHub y otras colaborativas es fundamental para el desarrollo rápido del proyecto y para evitar errores en el código. También hemos logrado mejorar la velocidad y eficiencia de los programas desarrollados, implementando extracciones, herencias, extensiones y control de errores, entre otros.

## Bibliografia

Peña, C. y Luna, F (SF). Programador Web Full Stack. Desarrollo Web frontend y backend  PHP. Fox andina. <https://books.google.es/books?hl=es&lr=&id=SyBFDwAAQBAJ&oi=fnd&pg=PA1&dq=backend+de+una+pagina+web&ots=-cjv2Nu6kY&sig=dicgnbj4GXulGbtpqHMDC6XtVTQ#v=onepage&q=backend%20de%20una%20pagina%20web&f=false>

Aranda, J. ()Fortalecimiento del frontend y el backend del sitio web <www.vendetucarroya.com> [Tesis de doctorado]. Universidad Distrital Francisco José De Caldas. <https://repository.udistrital.edu.co/bitstream/handle/11349/13876/FORTALECIMIENTO%20DEL%20FRONTEND%20Y%20BACKEND%20DEL%20SITIO%20WEB%20WWW.VENDETUCARROYA.COM.CO.pdf?sequence=1&isAllowed=y>

Pierre, V.(2020). How to build a backend app with TypeScript, Node.js, and Express. JavaScript in Plain English. <https://javascript.plainenglish.io/typescript-node-js-express-js-create-a-backend-application-f5110dbe5c19>

Pham, A(2020). Developing back-end of a web application with NestJS framework. [Tesis de licenciatura]. Lab University of Applied Science. <https://www.theseus.fi/bitstream/handle/10024/353200/Pham_Duc.pdf?isAllowed=y&sequence=2>

## Anexos

Organizacion en Github: <https://github.com/Arquitectura-Software-2023>
Landing Page desplegado: <https://jolly-field-04c7e7710.4.azurestaticapps.net/>
Web app desplegado: <https://tastypoint.netlify.app/>
Video about the team: <https://youtu.be/UhUfWYJhiXQ>
Video about the product: <https://youtu.be/xSLxkfcY4LA>
