<div align="center" style="margin-top: -5px;">

<img src="resources/imgs/UPC_logo_transparente.png"
     alt="UPC_logo_transparente"
     style="width: 18%; height: 30%; margin-bottom: -40px;">
     
  
**Universidad Peruana de Ciencias Aplicadas**  
**Carrera:** Ingeniería de Software  
**Curso:** Desarrollo de Aplicaciones Open Source (1ASI0730)  
**NRC:** 7793  


### Informe del Trabajo Final

 **Docente:** Fernández Robles, Ivan  
 **Equipo:** Noctiva  
 **Proyecto:** Noxway  



### Integrantes

| Código | Apellidos y Nombres |
| :---: | :--- |
| **U20241I469** | Patricio Farias, Ana Camila |
| **U202423775** | Cano Gomez, Yam Antony |
| **U202421823** | Dextre Flores, Leonardo Felix |
| **U202218235** | Ramirez Rodriguez, Mauricio Joao |
| **U202421065** | Salcedo Correa, Carlos Matthew |



**Período:** 202620  
**Fecha:** Octubre 2026  
</div>



---

# Registro de Versiones del Informe

| Versión | Fecha | Autor | Descripción de modificación |
| :------ | :---- | :---- | :-------------------------- |
| 1.0 | 2026-09-19 | Noctiva | Desarrollo del Capítulo I, Capítulo II, Capítulo III, Capítulo IV y el Sprint 1 del Capítulo V |
| 2.1 | 2026-11-04 | Noctiva | Adaptación de los textos del informe para trabajadores de turnos diurnos y nocturnos. |
| 2.0 | 2026-10-08 | Noctiva | Implementación de mejoras según el feedback de evaluación en los Capítulos I al IV, y desarrollo del Sprint 2 del Capítulo V |

# Project Report Collaboration Insights 
| Recurso | URL |
| :--- | :--- |
| Organización del proyecto | https://github.com/upc-pre-202620-1asi0730-7793 |
| Repositorio del reporte | https://github.com/upc-pre-202620-1asi0730-7793/Report |
| Repositorio de la Landing Page | https://github.com/upc-pre-202620-1asi0730-7793/Landing-Page |
| Repositorio del Frontend | https://github.com/upc-pre-202620-1asi0730-7793/Noxway-Frontend.git |


Durante la fase de preparación del informe, se llevaron a cabo las siguientes actividades:

AV1: Las tareas asignadas al AV1 han sido finalizadas y se encuentran correctamente documentadas en el repositorio de GitHub:

Se redactaron y crearon los contenidos asignados a cada miembro utilizando el formato Markdown, y se realizaron Conventional Commits para documentar el avance en el repositorio.
Se generaron los recursos necesarios y se agregaron las imágenes al repositorio en la carpeta resources correspondiente a cada rama del informe.
Se organizaron reuniones para coordinar el progreso de los componentes del informe y del Sprint 1, enfocado en el desarrollo de la Landing Page.

<div align="center">
<img src="resources/imgs/contributorsav1.png" alt="Commits del informe">
</div>

TB1: Las tareas correspondientes al Sprint 2 se documentaron en el repositorio de GitHub:

Se redactaron y actualizaron los contenidos del informe utilizando el formato Markdown, y se realizaron Conventional Commits para registrar los avances y la resolución de conflictos durante la integración de las ramas.
Se incorporaron las capturas de la aplicación web, la configuración de Firebase y las evidencias de despliegue en la carpeta resources/imgs/chapter_v del repositorio del informe.
Se organizaron los aportes del equipo mediante ramas de funcionalidades y Pull Requests para integrar los avances del frontend y de la documentación del Sprint 2.

<div align="center">
<img src="resources/imgs/tb1-collaboration.png" alt="Commits del informe">
</div>

# Contenido 

## Tabla de contenidos 
- [Registro de Versiones del Informe](#registro-de-versiones-del-informe)
- [Project Report Collaboration Insights](#project-report-collaboration-insights)
- [Contenido](#contenido)
  - [Tabla de contenidos](#tabla-de-contenidos)
- [Student Outcome](#student-outcome)
  - [Student Outcome](#student-outcome-1)
- [Capítulo I: Introducción](#capítulo-i-introducción)
  - [1.1. Startup Profile](#11-startup-profile)
    - [1.1.1 Descripción de la Startup](#111-descripción-de-la-startup)
    - [1.1.2. Perfiles de integrantes del equipo](#112-perfiles-de-integrantes-del-equipo)
  - [| **Foto** |                             |](#-foto------------------------------)
  - [| **Foto** | |](#-foto--)
  - [| **Foto** |                              |](#-foto-------------------------------)
  - [1.2. Solution Profile](#12-solution-profile)
    - [1.2.1 Antecedentes y problemática](#121-antecedentes-y-problemática)
    - [1.2.2 Lean UX Process.](#122-lean-ux-process)
      - [1.2.2.1. Lean UX Problem Statements.](#1221-lean-ux-problem-statements)
      - [1.2.2.2. Lean UX Assumptions.](#1222-lean-ux-assumptions)
      - [1.2.2.3. Lean UX Hypothesis Statements.](#1223-lean-ux-hypothesis-statements)
      - [1.2.2.4. Lean UX Canvas.](#1224-lean-ux-canvas)
  - [1.3. Segmentos objetivo.](#13-segmentos-objetivo)
- [Capítulo II: Requirements Elicitation \& Analysis](#capítulo-ii-requirements-elicitation--analysis)
  - [2.1. Competidores.](#21-competidores)
    - [2.1.1. Análisis competitivo](#211-análisis-competitivo)
    - [2.1.2. Estrategias y tácticas frente a competidores.](#212-estrategias-y-tácticas-frente-a-competidores)
    - [2.2.2. Registro de entrevistas](#222-registro-de-entrevistas)
  - [2.3. Needfinding.](#23-needfinding)
    - [2.3.1. User Personas.](#231-user-personas)
      - [Segmento Objetivo 1: Trabajador de Turno Diurno o Nocturno](#segmento-objetivo-1-trabajador-de-turno-diurno-o-nocturno)
      - [Segmento Objetivo 2: Contacto de Confianza](#segmento-objetivo-2-contacto-de-confianza)
    - [2.3.2. User Task Matrix.](#232-user-task-matrix)
    - [2.3.3. User Journey Mapping.](#233-user-journey-mapping)
      - [Segmento Objetivo 1: Trabajador de Turno Diurno o Nocturno](#segmento-objetivo-1-trabajador-de-turno-diurno-o-nocturno-1)
      - [Segmento Objetivo 2: Contacto de Confianza](#segmento-objetivo-2-contacto-de-confianza-1)
    - [2.3.4. Empathy Mapping.](#234-empathy-mapping)
      - [Segmento Objetivo 1: Trabajador de Turno Diurno o Nocturno](#segmento-objetivo-1-trabajador-de-turno-diurno-o-nocturno-2)
      - [Segmento Objetivo 2: Contacto de Confianza](#segmento-objetivo-2-contacto-de-confianza-2)
  - [2.4. Big Picture EventStorming.](#24-big-picture-eventstorming)
  - [2.5. Ubiquitous Language.](#25-ubiquitous-language)
- [Capítulo III: Requirements Specification](#capítulo-iii-requirements-specification)
  - [3.1. User Stories.](#31-user-stories)
  - [| **EP-16** | **Suscripciones, Conciliación de Pagos Offline y Beneficios (`subscriptions`)** | Como Developer, deseo habilitar endpoints RESTful para gestionar suscripciones a planes, conciliar órdenes de pago offline sin duplicidad y registrar el canje de cupones colectivos, para soportar la monetización y fidelización del modelo de negocio. | **Escenario 1: Activación de planes y control de referencias de pago****Dado** que un trabajador solicita un plan o beneficio en `/api/v1/subscriptions` o `/api/v1/benefits`, **cuando** se procesa el pago o reclamo de cupón, **entonces** el API garantiza la unicidad del comprobante y actualiza las coberturas del usuario. | - |](#-ep-16--suscripciones-conciliación-de-pagos-offline-y-beneficios-subscriptions--como-developer-deseo-habilitar-endpoints-restful-para-gestionar-suscripciones-a-planes-conciliar-órdenes-de-pago-offline-sin-duplicidad-y-registrar-el-canje-de-cupones-colectivos-para-soportar-la-monetización-y-fidelización-del-modelo-de-negocio--escenario-1-activación-de-planes-y-control-de-referencias-de-pagodado-que-un-trabajador-solicita-un-plan-o-beneficio-en-apiv1subscriptions-o-apiv1benefits-cuando-se-procesa-el-pago-o-reclamo-de-cupón-entonces-el-api-garantiza-la-unicidad-del-comprobante-y-actualiza-las-coberturas-del-usuario----)
- [Historias de Usuario - Noxway](#historias-de-usuario---noxway)
  - [| **US-30** | Moderar comunidad | Como moderador (Noxway), quiero auditar zonas y servicios reportados para evitar spam o "trolls", manteniendo el prestigio de los datos comunitarios frente a nuevos usuarios. | **Escenario 1:** Dado que ve un reporte pendiente, Cuando pulsa "Aprobar", Entonces el punto se publica a todos.**Escenario 2:** Dado que es un reporte vacío o de broma, Cuando pulsa "Rechazar", Entonces desaparece y el usuario generador pierde "Trust Score". | EP-10 |](#-us-30--moderar-comunidad--como-moderador-noxway-quiero-auditar-zonas-y-servicios-reportados-para-evitar-spam-o-trolls-manteniendo-el-prestigio-de-los-datos-comunitarios-frente-a-nuevos-usuarios--escenario-1-dado-que-ve-un-reporte-pendiente-cuando-pulsa-aprobar-entonces-el-punto-se-publica-a-todosescenario-2-dado-que-es-un-reporte-vacío-o-de-broma-cuando-pulsa-rechazar-entonces-desaparece-y-el-usuario-generador-pierde-trust-score--ep-10-)
  - [3.2. Impact Mapping.](#32-impact-mapping)
  - [3.3. Product Backlog.](#33-product-backlog)
  - [| 50 | US-03 | Recuperación de contraseña | Como usuario, quiero solicitar la recuperación de mi contraseña para restablecer mi acceso sin fricciones, reduciendo la tasa de abandono temporal de la plataforma. | 2 |](#-50--us-03--recuperación-de-contraseña--como-usuario-quiero-solicitar-la-recuperación-de-mi-contraseña-para-restablecer-mi-acceso-sin-fricciones-reduciendo-la-tasa-de-abandono-temporal-de-la-plataforma--2-)
- [Capítulo IV: Product Design](#capítulo-iv-product-design)
  - [4.1. Style Guidelines.](#41-style-guidelines)
    - [4.1.1. General Style Guidelines.](#411-general-style-guidelines)
      - [Principios de diseño](#principios-de-diseño)
    - [4.1.2. Web Style Guidelines.](#412-web-style-guidelines)
      - [4. Interacción (comportamiento UX)](#4-interacción-comportamiento-ux)
  - [4.2. Information Architecture.](#42-information-architecture)
    - [4.2.1. Organization Systems.](#421-organization-systems)
    - [4.2.2. Labeling Systems.](#422-labeling-systems)
    - [4.2.3. SEO Tags and Meta Tags](#423-seo-tags-and-meta-tags)
    - [4.2.4. Searching Systems.](#424-searching-systems)
    - [4.2.5. Navigation Systems.](#425-navigation-systems)
  - [4.3. Landing Page UI Design.](#43-landing-page-ui-design)
    - [4.3.1. Landing Page Wireframe.](#431-landing-page-wireframe)
    - [4.3.2. Landing Page Mock-up.](#432-landing-page-mock-up)
  - [4.4. Web Applications UX/UI Design.](#44-web-applications-uxui-design)
    - [4.4.1. Web Applications Wireframes.](#441-web-applications-wireframes)
    - [4.4.2. Web Applications Wireflow Diagrams.](#442-web-applications-wireflow-diagrams)
    - [4.4.3. Web Applications Mock-ups.](#443-web-applications-mock-ups)
    - [4.4.4. Web Applications User Flow Diagrams.](#444-web-applications-user-flow-diagrams)
  - [4.5. Web Applications Prototyping.](#45-web-applications-prototyping)
  - [4.6. Domain-Driven Software Architecture](#46-domain-driven-software-architecture)
    - [4.6.1. Design-Level EventStorming](#461-design-level-eventstorming)
  - [4.6.2. Software Architecture Context Diagram](#462-software-architecture-context-diagram)
  - [4.6.3. Software Architecture Container Diagrams](#463-software-architecture-container-diagrams)
  - [4.6.4. Software Architecture Components Diagrams](#464-software-architecture-components-diagrams)
  - [4.7. Software Object-Oriented Design](#47-software-object-oriented-design)
  - [4.7.1. Class Diagrams](#471-class-diagrams)
  - [4.8. Database Design](#48-database-design)
    - [4.8.1. Database Diagrams](#481-database-diagrams)
- [Capítulo V: Product Implementation, Validation \& Deployment](#capítulo-v-product-implementation-validation--deployment)
  - [5.1. Software Configuration Management.](#51-software-configuration-management)
    - [5.1.1. Software Development Environment Configuration.](#511-software-development-environment-configuration)
    - [5.1.2. Source Code Management.](#512-source-code-management)
    - [5.1.3. Source Code Style Guide \& Conventions.](#513-source-code-style-guide--conventions)
    - [5.1.4. Software Deployment Configuration.](#514-software-deployment-configuration)
  - [5.2. Landing Page, Services \& Applications Implementation.](#52-landing-page-services--applications-implementation)
    - [5.2.1. Sprint 1](#521-sprint-1)
      - [5.2.1.1. Sprint Planning 1.](#5211-sprint-planning-1)
      - [5.2.1.2. Aspect Leaders and Collaborators.](#5212-aspect-leaders-and-collaborators)
      - [5.2.1.3. Sprint Backlog 1.](#5213-sprint-backlog-1)
      - [5.2.1.5. Execution Evidence for Sprint Review.](#5215-execution-evidence-for-sprint-review)
      - [5.2.1.6. Services Documentation Evidence for Sprint Review.](#5216-services-documentation-evidence-for-sprint-review)
      - [5.2.1.7. Software Deployment Evidence for Sprint Review.](#5217-software-deployment-evidence-for-sprint-review)
      - [5.2.1.8. Team Collaboration Insights during Sprint.](#5218-team-collaboration-insights-during-sprint)
    - [5.2.1. Sprint 2](#521-sprint-2)
      - [5.2.2.1.Sprint Planning 2.](#5221sprint-planning-2)
      - [5.2.2.2. Aspect Leaders and Collaborators.](#5222-aspect-leaders-and-collaborators)
      - [5.2.2.3.Sprint Backlog 2.](#5223sprint-backlog-2)
      - [5.2.2.4. Development Evidence for Sprint Review.](#5224-development-evidence-for-sprint-review)
      - [5.2.2.5.Execution Evidence for Sprint Review.](#5225execution-evidence-for-sprint-review)
      - [5.2.2.6.Services Documentation Evidence for Sprint Review.](#5226services-documentation-evidence-for-sprint-review)
      - [5.2.2.7.Software Deployment Evidence for Sprint Review.](#5227software-deployment-evidence-for-sprint-review)
      - [5.2.2.8.Team Collaboration Insights during Sprint.](#5228team-collaboration-insights-during-sprint)
    - [5.2.3. Sprint 3](#523-sprint-3)
      - [5.2.3.1. Sprint Planning 3.](#5231-sprint-planning-3)
      - [5.2.3.2. Aspect Leaders and Collaborators.](#5232-aspect-leaders-and-collaborators)
      - [5.2.3.3. Sprint Backlog 3.](#5233-sprint-backlog-3)
      - [5.2.3.4. Development Evidence for Sprint Review.](#5234-development-evidence-for-sprint-review)
      - [5.2.3.5. Execution Evidence for Sprint Review.](#5235-execution-evidence-for-sprint-review)
      - [5.2.3.6. Services Documentation Evidence for Sprint Review.](#5236-services-documentation-evidence-for-sprint-review)
      - [5.2.3.7. Software Deployment Evidence for Sprint Review.](#5237-software-deployment-evidence-for-sprint-review)
      - [5.2.3.8. Team Collaboration Insights during Sprint.](#5238-team-collaboration-insights-during-sprint)
  - [5.3. Validation Interviews](#53-validation-interviews)
    - [5.3.1. Diseño de entrevistas](#531-diseño-de-entrevistas)
      - [Estructura de la sesión de validación](#estructura-de-la-sesión-de-validación)
      - [Segmento Objetivo 1: Trabajadores de Turno Nocturno y Rotativo (*Night \& Rotating Shift Workers*)](#segmento-objetivo-1-trabajadores-de-turno-nocturno-y-rotativo-night--rotating-shift-workers)
      - [Segmento Objetivo 2: Contactos de Confianza y Familiares (*Trusted Contacts / Family Companions*)](#segmento-objetivo-2-contactos-de-confianza-y-familiares-trusted-contacts--family-companions)
    - [5.3.2. Registro de Entrevistas](#532-registro-de-entrevistas)
      - [Segmento Objetivo 1: Trabajadores de Turno Nocturno](#segmento-objetivo-1-trabajadores-de-turno-nocturno)
        - [Entrevista de Validación #1 – Segmento 1](#entrevista-de-validación-1--segmento-1)
        - [Entrevista de Validación #2 – Segmento 1](#entrevista-de-validación-2--segmento-1)
        - [Entrevista de Validación #3 – Segmento 1](#entrevista-de-validación-3--segmento-1)
      - [Segmento Objetivo 2: Contactos de Confianza](#segmento-objetivo-2-contactos-de-confianza)
        - [Entrevista de Validación #4 – Segmento 2](#entrevista-de-validación-4--segmento-2)
        - [Entrevista de Validación #5 – Segmento 2](#entrevista-de-validación-5--segmento-2)
        - [Entrevista de Validación #6 – Segmento 2](#entrevista-de-validación-6--segmento-2)
    - [5.3.3. Evaluaciones según heurísticas](#533-evaluaciones-según-heurísticas)
      - [UX Heuristics \& Principles Evaluation: Usability - Inclusive Design - Information Architecture](#ux-heuristics--principles-evaluation-usability---inclusive-design---information-architecture)
        - [PROBLEMA #1: Ausencia de atajos de rutas habituales al iniciar un desplazamiento en `Mi Trayecto`](#problema-1-ausencia-de-atajos-de-rutas-habituales-al-iniciar-un-desplazamiento-en-mi-trayecto)
        - [PROBLEMA #2: Imposibilidad de adjuntar evidencia fotográfica al publicar un aviso en `Comunidad`](#problema-2-imposibilidad-de-adjuntar-evidencia-fotográfica-al-publicar-un-aviso-en-comunidad)
        - [PROBLEMA #3: Falta de alertas sonoras distintivas en el Companion Portal ante eventos de ruta o llegada segura](#problema-3-falta-de-alertas-sonoras-distintivas-en-el-companion-portal-ante-eventos-de-ruta-o-llegada-segura)
        - [PROBLEMA #4: Falta de un mapa desplegable dentro de las tarjetas de `Monitoreo en Vivo`](#problema-4-falta-de-un-mapa-desplegable-dentro-de-las-tarjetas-de-monitoreo-en-vivo)
        - [PROBLEMA #5: Etiquetas de enumeraciones en inglés (`DELIVERED`, `FAILED`, `MOTORCYCLE`) y subtítulos HTTP visibles en español](#problema-5-etiquetas-de-enumeraciones-en-inglés-delivered-failed-motorcycle-y-subtítulos-http-visibles-en-español)
  - [5.4. Video About-the-Product](#54-video-about-the-product)
- [Conclusiones](#conclusiones)
- [Video About-the-Team](#video-about-the-team)
- [Bibliografía](#bibliografía)
- [Anexos](#anexos)


# Student Outcome 
## Student Outcome
El curso contribuye al cumplimiento del Student Outcome ABET:

**ABET – EAC - Student Outcome 5**

**Criterio**: *La capacidad de funcionar efectivamente en un equipo cuyos miembros juntos proporcionan liderazgo, crean un entorno de colaboración e inclusivo, establecen objetivos, planifican tareas y cumplen objetivos.*

En el siguiente cuadro se describe las acciones realizadas y enunciados de conclusiones por parte del grupo, que permiten sustentar el haber alcanzado el logro del ABET – EAC - Student Outcome 5.

| Criterio específico                                                                             | Acciones realizadas                                                      | Conclusiones                   |
|-------------------------------------------------------------------------------------------------|--------------------------------------------------------------------------|--------------------------------|
| Trabaja en equipo para proporcionar liderazgo en forma conjunta                                 |<ul><li><b>Patricio Farias, Ana Camila</b> <br> <b>AV1</b>:Lideré la gestión ágil, facilitación y articulación operativa del equipo a lo largo del ciclo de vida del sprint, asegurando el cumplimiento riguroso de los hitos y entregables fijados. Fomenté una comunicación transversal y continua entre las áreas de diseño, arquitectura y desarrollo, organizando y desglosando las tareas en el tablero de trabajo para optimizar la carga y mitigar bloqueos tempranos. Asimismo, impulsé sesiones colaborativas de toma de decisiones para resolver discrepancias técnicas y de alcance, garantizando la trazabilidad, coherencia e integración de los artefactos producidos y asegurando la alineación constante de los objetivos individuales con la visión global de la solución.<br> <b>TB1</b>: Lideré la estructuración y planificación del Sprint 2, asumiendo la responsabilidad de la gestión ágil del equipo. Como parte de este liderazgo, refiné el Product Backlog mediante la revisión y corrección exhaustiva de diversas User Stories, asegurando su viabilidad técnica y alineación con los objetivos de negocio de Noctiva.</li><br><li><b>Dextre Flores, Leonardo Felix</b> <br> <b>AV1</b>: Organicé mi contribución en una secuencia de artefactos relacionados entre sí, avanzando desde la vista general de la arquitectura hasta el diseño de clases y persistencia. Mantuve una nomenclatura consistente entre los Bounded Contexts, componentes, clases y estructuras de datos, y documenté las responsabilidades principales de cada elemento para facilitar su revisión y posterior utilización por los demás integrantes. También verifiqué la correspondencia entre las decisiones arquitectónicas y las User Stories previamente definidas, procurando evitar dependencias innecesarias entre contextos y dejando una estructura organizada que facilite posteriormente la distribución de tareas de implementación de frontend, backend y persistencia. <br> <b>TB1</b>: Asumí la responsabilidad sobre la consistencia técnica de la arquitectura al liderar la revisión y corrección de los diagramas del sistema. Asimismo, tomé la iniciativa en la refactorización y corrección de mis respectivos Bounded Contexts para garantizar una arquitectura limpia y escalable de cara al desarrollo del software. </li><br><li><b>Salcedo Correa, Carlos Matthew</b> <br> <b>AV1</b>: Asumí el liderazgo técnico en el diseño de experiencia e interfaces de usuario (UX/UI) y en la estructuración de la arquitectura de información para el ecosistema digital de Noxway. Lideré la definición estratégica de SEO y metadatos tanto para la Landing Page pública como para la Web Application, y coordiné activamente con los responsables de requisitos la traducción de los objetivos de usuario hacia los flujos visuales del sistema (wireflows y user flows). Asimismo, proporcioné dirección técnica durante la implementación frontend del Landing Page, asegurando la consistencia entre los artefactos de diseño y el código fuente. <br> <b>TB1</b>: Lideré las actividades orientadas a la puesta en producción, asumiendo un rol clave en el proceso de despliegue (deployment) de la aplicación web. De igual forma, tomé la iniciativa para optimizar la Landing Page, diseñando e integrando nuevos elementos y secciones que enriquecen la propuesta de valor del producto. </li></ul> <ul><li><b>Ramirez Rodriguez, Mauricio Joao</b> <br> <b>AV1</b>: Colaboré con el equipo planificando y llevando a cabo la fase de entrevistas para recoger los requerimientos del usuario, y elaboré los Style Guidelines del proyecto. Al definir y entregar estas pautas visuales a tiempo, facilité una referencia clara para el diseño de la interfaz, coordinando con el grupo para resolver dudas y cumplir con los objetivos fijados dentro del plazo previsto. <br> <b>TB1</b>: Contribuí al control de calidad de los entregables mediante la revisión transversal del documento formal, aplicando correcciones de formato y afinando pequeños detalles técnicos para asegurar una presentación adecuada de los artefactos del proyecto. </li><br><li><b>Cano Gomez, Yam</b> <br> <b>AV1</b>: Participé activamente en la coordinación y dinamización de las actividades del equipo, facilitando los canales de comunicación y la toma de decisiones conjuntas para asegurar el avance continuo del proyecto. Colaboré estrechamente en la revisión, consolidación y control de calidad de los distintos entregables, apoyando de manera constante a mis compañeros ante bloqueos o contingencias técnicas. Asimismo, promoví la alineación del grupo respecto a las prioridades y cronogramas establecidos, fomentando un entorno de trabajo colaborativo e integrando los aportes individuales para garantizar la coherencia global y el cumplimiento exitoso de los objetivos planteados. <br> <b>TB1</b>: Apoyé de manera activa en el liderazgo de la gestión del proyecto, colaborando estrechamente en la creación y organización del Sprint 2. Mi participación ayudó a distribuir estratégicamente la carga de trabajo y a establecer una hoja de ruta técnica clara para la iteración. </li>  | **av1:** El trabajo conjunto y la comunicación continua me permitieron asumir un rol activo en la toma de decisiones técnicas y metodológicas del grupo. Al facilitar la coordinación en la estructuración de los requisitos y consensuar la priorización de los artefactos ágiles, contribuí a un liderazgo distribuido donde cada integrante aportó valor de manera equitativa, logrando un flujo de trabajo organizado y alineado con los objetivos del proyecto. Asimismo, la coordinación entre UX/UI, SEO y desarrollo frontend permitió alinear la visión del producto con las necesidades del usuario, reforzando la colaboración y el liderazgo técnico del equipo. <br> **tb1:** Durante el Sprint 2 correspondiente a la entrega TB1, el equipo consolidó un modelo de liderazgo distribuido en el que los roles de gestión ágil, arquitectura, despliegue y documentación fueron asumidos proactivamente por distintos integrantes. La articulación continua entre la mayoría de los miembros permitió una toma de decisiones eficiente para organizar la carga de trabajo y superar desafíos técnicos en la programación. Esto garantizó que los avances individuales se integraran de forma coherente bajo una misma visión arquitectónica.|
| Crea un entorno colaborativo e inclusivo, establece metas, planifica tareas y cumple objetivos. |<ul><li><b>Patricio Farias, Ana Camila</b> <br> <b>AV1</b>: Relalice las preguntas de la entrevistas, lo que permitió estructurar el needfinding mediante arquetipos de usuario, matrices de tareas, Journey Map y Empathy Mapp. A partir de estos hallazgos, modelé la lógica del dominio aplicando Big Picture EventStorming y definiendo un lenguaje ubicuo para alinear el negocio con el diseño del sistema. Finalmente, traduje estos requisitos a un marco ágil construyendo el Impact Mapping, especificando las historias de usuario y consolidando el Product Backlog priorizado para el desarrollo del producto. <br> <b>TB1</b>: Fomenté un entorno estructurado al planificar las metas del Sprint 2 y participar activamente en la implementación de la aplicación web. Desarrollé la lógica de mis respectivos Bounded Contexts, coordinando de forma continua con mis compañeros para integrar mi código sin fricciones y cumplir con los plazos pactados. </li><br><li><b>Dextre Flores, Leonardo Felix</b> <br> <b>AV1</b>: Contribuí al diseño técnico de Noxway desarrollando los artefactos de arquitectura comprendidos entre las secciones 4.6.2 y 4.8.1. Definí la representación del sistema mediante los diagramas C4 de contexto, contenedores y componentes, estableciendo los principales actores, sistemas externos, unidades de software y responsabilidades de la solución. Posteriormente desarrollé los diagramas de clases correspondientes a los Bounded Contexts y módulos de soporte, manteniendo consistencia entre las entidades, servicios, interfaces, enumeraciones y relaciones del dominio. Finalmente, estructuré los diagramas de base de datos en PostgreSQL, especificando tablas, atributos, identificadores, claves y restricciones necesarias para mantener la integridad y la separación de responsabilidades entre contextos. Estas decisiones permitieron establecer una referencia técnica común para el equipo durante las siguientes etapas de desarrollo. <br> <b>TB1</b>: Colaboré decididamente en la fase de implementación de Noxway, sincronizando el avance de mi código con el de mis compañeros. Al alinear las correcciones de mis Bounded Contexts con los objetivos del sprint, aseguré el cumplimiento oportuno de mis responsabilidades de desarrollo. </li><br><li><b>Salcedo Correa, Carlos Matthew</b> <br> <b>AV1</b>: Diseñé la arquitectura de información integral estableciendo los sistemas de búsqueda, navegación, SEO Tags y Meta Tags para la Landing Page y Web Application. A nivel visual y de interacción, diseñé los wireframes y mock-ups responsive (desktop y mobile) de la Landing Page, así como los wireframes, wireflows por User Goal, mock-ups y User Flow Diagrams (happy y unhappy paths) de la Web Application. Desarrollé además el prototipo interactivo en Figma y apoyé de forma colaborativa en la maquetación y desarrollo web de la Landing Page (HTML5, CSS3 y JavaScript), cumpliendo con los estándares de diseño y accesibilidad definidos. <br> <b>TB1</b>: Impulsé el avance del grupo mediante el desarrollo de mis Bounded Contexts asignados y brindando soporte continuo durante la codificación de la aplicación web. Mi colaboración en la fase final de despliegue aseguró que alcanzáramos la meta conjunta de tener una versión accesible y funcional para la evaluación. </li></ul> <ul><li><b>Ramirez Rodriguez, Mauricio Joao</b> <br> <b>AV1</b>:Fomenté un entorno colaborativo y estructurado al planificar y ejecutar la fase de entrevistas a los usuarios, definiendo objetivos claros para la recolección de información relevante para el equipo. Con base en estos hallazgos, elaboré los Style Guidelines del proyecto, estableciendo de manera organizada los estándares visuales, componentes y lineamientos de diseño. Gracias a la entrega oportuna de estas guías, facilité la alineación del equipo en el desarrollo de la interfaz, asegurando la coherencia del diseño y el cumplimiento puntual de las metas establecidas para el sprint. <br> <b>TB1</b>: Apoyé en el cumplimiento de las metas documentales del sprint revisando el trabajo conjunto de forma asíncrona. Mi enfoque estuvo dirigido a pulir detalles formales del informe final, aportando a la consolidación del entregable requerido para el cierre de la iteración. </li><br><li><b>Cano Gomez, Yam</b> <br> <b>AV1</b>: Promoví un entorno de trabajo colaborativo durante el desarrollo del Capítulo 1, organizando con el equipo el plan para las entrevistas y el Needfinding. Establecí metas para la recolección de información, prioricé las actividades del entregable y aseguré la participación activa de todos en el análisis de hallazgos. Además, facilité la consolidación de las User Personas, Empathy Maps y User Journey Maps, logrando que el equipo trabajara alineado y cumpliera a tiempo con los objetivos del proyecto.<br> <bTB1</b>: Mantuve una comunicación fluida y constante con las áreas de desarrollo para avanzar de forma sostenida en la implementación de mis Bounded Contexts. Al apoyar en la corrección de la documentación y en la planificación del sprint, fortalecí la organización interna para el cumplimiento de nuestros plazos. </li>| **av1:** La articulación de las entrevistas y el análisis competitivo permitió integrar una visión común y fundamentada dentro del equipo, facilitando una planificación clara mediante herramientas como el EventStorming y el Impact Mapping. Este proceso colaborativo aseguró que la definición de historias de usuario y el Product Backlog respondieran a metas viables y medibles, cumpliendo oportunamente con los entregables de elicitación y especificación de requisitos. Asimismo, la definición de la arquitectura de información, el prototipado y la implementación visual aportaron un marco compartido para coordinar tareas, mantener consistencia entre diseño y desarrollo y asegurar la entrega de una experiencia alineada con los objetivos del proyecto.  <br> **tb1:** La planificación del Sprint 2 y la alta interacción comunicativa establecida entre Ana Camila, Leonardo, Yam y Carlos establecieron un entorno altamente colaborativo que fue clave para cumplir con las metas de implementación y despliegue de la aplicación web. A pesar de presentarse una participación asíncrona y de menor involucramiento por parte de algunos integrantes, el sólido compromiso, la comunicación constante y el apoyo mutuo del núcleo central de desarrollo garantizaron que se superaran los bloqueos técnicos y se lograran exitosamente los objetivos de este hito. |

# Capítulo I: Introducción 

## 1.1. Startup Profile 
### 1.1.1 Descripción de la Startup
**Noctiva** es una startup dedicada a mejorar la seguridad, el bienestar y la vida social de los trabajadores que realizan su labor en horarios diurnos y nocturnos. Nuestro alcance está dirigido a un segmento históricamente desatendido por las soluciones tecnológicas actuales: personal de seguridad, repartidores (delivery), enfermeros y personal de salud de turnos diurnos y nocturnos, agentes de call centers 24 horas, y personal de limpieza, entre otros rubros que sostienen la operatividad de las ciudades a lo largo del día y de la noche.
Como startup, buscamos posicionarnos como un referente en soluciones de seguridad y bienestar para trabajadores de turnos diurnos y nocturnos, entendiendo las particularidades de un segmento que enfrenta mayores riesgos al transitar solo, dificultad para acceder a servicios abiertos en el horario de sus desplazamientos, y aislamiento de su círculo social por las diferencias entre sus horarios de trabajo y descanso.
**Misión:** Queremos ofrecer soluciones tecnológicas que devuelvan seguridad, comunidad y bienestar a quienes trabajan de día y de noche, adaptando servicios y herramientas a la realidad de los distintos turnos laborales.
**Visión:** Ser la startup líder en seguridad y bienestar para trabajadores de turnos diurnos y nocturnos en el mercado peruano, comenzando por consolidar nuestra posición en Lima, para luego expandirnos a otras ciudades y sectores del país.

### 1.1.2. Perfiles de integrantes del equipo 

| **Integrante** | Patricio Farias Ana Camila |
| :--- |:---------------------------|
| **Código del Estudiante** |  U20241I469   |
| **Carrera** | Ingeniería de Software  |
| **Descripción** | Mi nombre es Camila Patricio. Tengo 20 años, soy estudiante de Ingeniería de Software y considero que mis principales fortalezas son la responsabilidad, el compromiso y la disposición para aprender constantemente. Puedo aportar a mi grupo habilidades en programación, análisis de problemas y búsqueda de soluciones creativas. Además, me caracterizo por trabajar en equipo de manera colaborativa y organizada. Mi propósito es aportar mis conocimientos y esfuerzo para que logremos juntos los objetivos de nuestro proyecto.                           |
| **Foto** | <img src="resources/imgs/Camila.png" alt="Camila" width="200" height="240">                            |
--------------


| **Integrante** | Cano Gomez Yam Antony Gabriel |
| :--- | :--- |
| **Código del Estudiante** | U202423775 |
| **Carrera** | Ingeniería de Software |
| **Descripción** |Mi nombre es Yam Cano,tengo 20 años y soy estudiante de la carrera de ingeniería de software,ademas soy una persona proactiva ;cuento con habilidades analíticas y lógicas en programación, lo que me permite abordar problemas en base a mi carrera,además estoy buscando nuevas oportunidades para aprender y aplicar mis conocimientos, lo que me ayuda a crecer tanto a nivel académico como personal. |
| **Foto** |<img src="resources/imgs/Yam.png" alt="Yam" width="200" height="240"> |
----------------------

| **Integrante** | Dextre Flores Leonardo Felix |
| :--- |:-----------------------------|
| **Código del Estudiante** | U202421823                   |
| **Carrera** | Ingeniería de Software       |
| **Descripción** |  Soy Leonardo Dextre, tengo 23 años, actualmente estoy cursando el cuarto ciclo de mi carrera ingeniería de software en la UPC. Entre mis habilidades más destacadas es saber un poco de programación especialmente en C++ y un poco en Python. Además, tengo básico conocimiento en programas de Microsoft como el Excel. Mis pasatiempos son ver películas y jugar videojuegos. Mi objetivo con el curso es aprender más cosas acerca de mi carrera y poder aplicarlo en mi futuro laboral como profesional.     |
| **Foto** |  <img src="resources/imgs/LeonardoDextre.png" alt="Leonardo Dextre" width="200" height="240">                            |
---------------------

| **Integrante** | Ramirez Rodriguez, Mauricio Joao |
| :--- | :--- |
| **Código del Estudiante** | U202218235 |
| **Carrera** | Ingeniería de Software |
| **Descripción** | Estudiante de Ingeniería de Software de 22 años, orientado al desarrollo de soluciones tecnológicas eficientes y de alto impacto. Me caracterizo por mi responsabilidad, alto grado de compromiso y una constante disposición hacia el aprendizaje adaptativo y la mejora continua. Aporto al equipo competencias en lógica de programación, análisis y resolución de problemas complejos, así como un enfoque estructurado para el diseño de soluciones creativas. Además, me destaco por mi capacidad para trabajar en equipo de manera colaborativa, proactiva y organizada. Mi propósito fundamental es integrar mis conocimientos técnicos y disciplina de trabajo para asegurar el cumplimiento riguroso de los objetivos planteados en nuestro proyecto. |
| **Foto** | <img src="resources/imgs/Mauricio.jpeg" alt="Mauricio Ramirez" width="200" height="240">   |

| **Integrante** | Salcedo Correa Carlos Matthew |
| :--- |:-----------------------------|
| **Código del Estudiante** | U202421065|
| **Carrera** | Ingeniería de Software       |
| **Descripción** | Soy Carlos Salcedo, tengo 18 años y actualmente curso el cuarto ciclo de la carrera de Ingeniería de Software en la Universidad Peruana de Ciencias Aplicadas (UPC). Cuento con conocimientos de nivel básico a intermedio en el lenguaje de programación C++, así como habilidades básicas en diseño. Además, tengo afinidad por el arte, especialmente el dibujo, y un fuerte interés por la música. Me considero una persona comprometida, responsable y con disposición constante para aprender. Mi objetivo en este curso es profundizar en los temas relacionados con mi carrera, fortalecer mis habilidades y prepararme para aplicarlas de manera efectiva en mi futuro profesional.                             |
| **Foto** |  <img src="resources/imgs/Salcedo.png" alt="Salcedo.png" width="200" height="240">                            |


## 1.2. Solution Profile
### 1.2.1 Antecedentes y problemática 
| 5w & 2H | Descripcion                                                                                                                                                                                                                                                                                                                                                                                                                                                        |
|---------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **What: ¿Cuál es el problema?**|Los trabajadores de turnos diurnos y nocturnos (seguridad, delivery, salud, call centers, limpieza, etc) se enfrentan a una ciudad y a unos servicios que no siempre se ajustan a sus horarios laborales. Esto se traduce en mayor riesgo al transitar solos durante sus desplazamientos, dificultad para encontrar comida o servicios abiertos, aislamiento de su círculo social por las diferencias entre sus horarios de trabajo y descanso, y nula capacidad de organizarse colectivamente debido a horarios dispersos.|
| **When: ¿Cuándo sucede este problema?**|El problema ocurre de manera constante durante el día y la noche, siendo más crítico en los trayectos de ida o vuelta del trabajo, según la disponibilidad de transporte público, la iluminación y la presencia de otras personas o autoridades.|
| **Where: ¿Dónde se produce este suceso?** |El problema está presente en las principales ciudades del país, pero es particularmente crítico en zonas urbanas de Lima con alta incidencia delictiva, poca iluminación pública y disponibilidad variable de servicios según el horario, donde miles de trabajadores transitan diariamente sin herramientas que respalden su seguridad.|
| **Who: ¿Quiénes están involucrados?** |Están involucrados directamente los trabajadores de turnos diurnos y nocturnos de distintos rubros (seguridad, delivery, enfermería, call centers, limpieza, etc), así como sus familiares, parejas y contactos de confianza, quienes también viven con incertidumbre y preocupación mientras el trabajador está en tránsito o en su jornada laboral, sin ninguna forma de saber si llegó bien a su destino.|
| **Why: ¿Cuál es la causa del problema?** |La causa principal es que las ciudades, los servicios comerciales y las herramientas tecnológicas de seguridad y comunidad no siempre se ajustan a los distintos horarios laborales, sin atender de forma integrada las necesidades de quienes trabajan en distintos horarios. |
| **How: ¿Qué llevó a la persona a llegar a esta situación?** |La situación actual es resultado de una economía que exige servicios ininterrumpidos las 24 horas (seguridad, salud, delivery, atención al cliente, etc), sin que exista una infraestructura de apoyo equivalente para quienes sostienen esa operación diurna y nocturna, generando desprotección, desgaste físico y aislamiento social progresivo.|
| **How Much: ¿Cuánto es el impacto financiero?** |El impacto es tanto humano como económico: mayor exposición a asaltos y accidentes en el trayecto, deterioro de la salud por falta de descanso adecuado, pérdida de vínculos sociales y familiares, y un desgaste emocional constante en los contactos de confianza que viven con incertidumbre mientras el trabajador está en su turno laboral. |

### 1.2.2 Lean UX Process.
#### 1.2.2.1. Lean UX Problem Statements.

El estado actual de **la seguridad y el bienestar de los trabajadores de turnos diurnos y nocturnos en zonas urbanas del Perú** requiere considerar las necesidades de **los trabajadores de distintos horarios**, incluyendo a **guardias de seguridad, repartidores (delivery), personal de salud, agentes de call center, personal de limpieza, entre otros, que laboran en turnos diurnos y nocturnos**, junto con sus puntos de dolor tales como **el riesgo constante al transitar solos de día o de noche, la dificultad para encontrar servicios abiertos y confiables, el aislamiento de su círculo social debido a que tienen distintos horarios de trabajo y descanso, y la nula capacidad de organizarse colectivamente debido a sus horarios dispersos**.

Lo que los productos/servicios existentes de seguridad personal y de compartición de ubicación no logran abordar es **una plataforma especializada que combine seguridad activa durante los trayectos, información confiable generada por la comunidad sobre la seguridad de las rutas y el entorno del trayecto, y un espacio de comunidad y beneficios colectivos diseñado específicamente para la realidad del trabajo en turnos diurnos y nocturnos**.

**Noxway** abordará esta brecha **ofreciendo un check-in de trayecto seguro con alertas automáticas a contactos de confianza, un sistema de calificación y reporte de seguridad de rutas alimentado por la comunidad, un mapa comunitario de servicios abiertos según el horario de consulta, un sistema automático de alerta ante posibles incidentes cuando un trayecto no es confirmado, una bitácora de descanso y salud del sueño, y una comunidad con beneficios colectivos negociados mediante una suscripción mensual**.

Nuestro enfoque inicial serán **los trabajadores de turnos diurnos y nocturnos de los rubros de seguridad, delivery, salud, call center, entre otros, en Lima Metropolitana, junto con sus contactos de confianza (familiares y parejas) que comparten la carga emocional de su seguridad durante estos trayectos**.

Sabremos que hemos tenido éxito cuando veamos **una reducción de los incidentes de seguridad reportados por nuestros usuarios, un uso recurrente y sostenido de la función de check-in de trayecto seguro, un volumen creciente de calificaciones de seguridad de rutas enviadas por la comunidad, un crecimiento orgánico de la comunidad de usuarios, y una tasa de conversión relevante de usuarios de prueba gratuita a suscriptores de pago**.

#### 1.2.2.2. Lean UX Assumptions.
**Business Assumptions**
* Creemos que existe un mercado desatendido de trabajadores de turnos diurnos y nocturnos dispuestos a utilizar una plataforma dedicada a su bienestar.
* Creemos que un modelo de crecimiento basado en referidos entre el trabajador y sus contactos de confianza (familiares, parejas) reducirá el costo de adquisición de usuarios y acelerará el crecimiento orgánico de la plataforma.
* Creemos que un modelo de monetización mediante suscripción mensual con beneficios como seguro básico, descuentos negociados colectivamente y alertas de seguridad prioritarias es viable y sostenible para este segmento, gracias a la posibilidad de negociar estos beneficios con terceros.

**Business Outcome Assumptions**
* Creemos que lograremos una reducción de al menos 30 % en los incidentes de seguridad reportados por los usuarios activos respecto a su línea base autodeclarada, en un plazo de 8 meses desde el lanzamiento del MVP.
* Creemos que lograremos al menos 500 suscripciones mensuales activas, en un plazo de 8 meses desde el lanzamiento.
* Creemos que lograremos que al menos 30 % de los nuevos registros provenga de invitaciones de contactos de confianza y que el costo de adquisición por usuario sea 25 % menor al de canales pagados, durante los 6 meses posteriores al lanzamiento.
* Creemos que lograremos una retención a 30 días (usuarios con al menos un check-in en el mes 2 sobre usuarios con check-in en el mes 1) de al menos 60 %, durante los 3 meses posteriores al lanzamiento.
* Creemos que lograremos un promedio de al menos 4 sesiones semanales por usuario activo y 3 búsquedas de servicios por semana, durante los 3 meses posteriores al lanzamiento.
* Creemos que lograremos que al menos 80 % de los reportes de riesgo sean aprobados por moderación y que 70 % de las zonas de riesgo tengan 2 o más confirmaciones independientes, durante los 3 meses posteriores al lanzamiento.
* Creemos que lograremos una tasa de renovación de suscripción de al menos 70 % al tercer mes y que al menos 20 % de los nuevos registros llegue por recomendación, durante los 6 meses posteriores al lanzamiento.
* Creemos que lograremos que al menos 40 % de los trayectos finalizados reciba una calificación de ruta, durante los 3 meses posteriores al lanzamiento.
* Creemos que lograremos una mediana de 5 minutos o menos entre el vencimiento del margen de tolerancia y la primera acción del contacto de confianza, con no más de 15 % de incidentes cerrados como falso positivo, durante un piloto de 8 semanas.

**User Assumptions**
1. Nuestros usuarios principales son trabajadores de turnos diurnos y nocturnos entre 20 y 45 años, residentes en zonas urbanas de Lima, pertenecientes a los rubros de seguridad, delivery, salud y call centers, etc.
2. Nuestros usuarios secundarios son los contactos de confianza (familiares, parejas o amigos) de los trabajadores de turnos diurnos y nocturnos, quienes reciben notificaciones automáticas sobre el estado de su trayecto.
3. Existen usuarios con rol de moderación dentro de la comunidad, encargados de validar reportes de incidentes y de información sobre servicios cercanos.

**User Outcome and Benefit Assumptions**
1. Los trabajadores de turnos diurnos y nocturnos desean sentirse acompañados y seguros durante sus trayectos, y obtienen tranquilidad al saber que un contacto de confianza será notificado automáticamente ante cualquier eventualidad.
2. Los trabajadores de turnos diurnos y nocturnos desean encontrar rápidamente servicios abiertos y confiables durante el día y la noche, y obtienen ahorro de tiempo y menor exposición a situaciones de riesgo.
3. Los trabajadores de turnos diurnos y nocturnos desean sentirse parte de una comunidad que comprenda su realidad laboral, y obtienen acceso a información relevante y beneficios negociados colectivamente.
4. Los contactos de confianza desean tener certeza y tranquilidad sobre la seguridad de su familiar o pareja durante su trayecto, y obtienen visibilidad del estado del check-in y de la llegada segura, sin necesidad de estar llamando o preguntando constantemente.
5. Los trabajadores de turnos diurnos y nocturnos desean saber qué tan segura es una ruta específica antes de tomarla, y obtienen información sobre la seguridad de la ruta gracias a las calificaciones y reportes dejados por otros usuarios que la transitaron recientemente.
6. Los trabajadores de turnos diurnos y nocturnos desean comprender cómo su horario afecta su descanso, y obtienen visibilidad de sus patrones de sueño y alertas ante descanso insuficiente.
7. Los contactos de confianza desean enterarse a tiempo cuando el trayecto de su familiar o pareja presenta una situación anómala, y obtienen una alerta temprana y verificada sobre un posible incidente en el trayecto.

**Feature Assumptions**

1. Un check-in de trayecto seguro con aviso automático a contactos de confianza satisfará la necesidad de seguridad activa durante los desplazamientos diurnos y nocturnos.
2. Un mapa comunitario de servicios activos según el horario de consulta, validado por los propios usuarios, satisfará la necesidad de información confiable sobre el entorno.
3. Un sistema de reporte comunitario de incidentes y zonas de riesgo satisfará la necesidad de anticipar y evitar situaciones peligrosas.
4. Una bitácora de descanso y salud del sueño satisfará la necesidad de visibilizar y cuidar el bienestar físico del trabajador de turno diurno o nocturno.
5. Una comunidad con beneficios colectivos negociados a través de la suscripción mensual satisfará la necesidad de pertenencia, ahorro y valor añadido para el trabajador de turno diurno o nocturno.
6. Un sistema de calificación y reporte de ruta al finalizar cada trayecto (indicando si el usuario se sintió seguro o marcando un punto específico como sospechoso) satisfará la necesidad de contar con información colectiva y confiable sobre qué tan seguras son las rutas realmente transitadas.
7. Una función de marcado automático de "posible incidente" cuando el usuario no confirma su llegada dentro del tiempo estimado, con validación posterior del propio usuario, satisfará la necesidad de identificar rápidamente situaciones de riesgo reales y alimentar el mapa comunitario con datos verificados.
8. Un panel de seguimiento para contactos de confianza, que les permita ver en tiempo real el estado del trayecto y del check-in de la persona que los designó, satisfará la necesidad de tranquilidad y monitoreo sin invadir la privacidad del trabajador de turno diurno o nocturno.

#### 1.2.2.3. Lean UX Hypothesis Statements.

**Hipótesis 1**

Creemos que lograremos **una retención a 30 días (usuarios con al menos un check-in en el mes 2 sobre usuarios con check-in en el mes 1) de al menos 60 %, durante los 3 meses posteriores al lanzamiento**  
Si **los trabajadores de turnos diurnos y nocturnos en Lima**  
Alcanzan **tranquilidad al saber que un contacto de confianza será notificado automáticamente ante cualquier eventualidad**  
Con **la función de check-in de trayecto seguro con alertas automáticas a contactos de confianza**.

---

**Hipótesis 2**

Creemos que lograremos **un promedio de al menos 4 sesiones semanales por usuario activo y 3 búsquedas de servicios por semana, durante los 3 meses posteriores al lanzamiento**  
Si **los trabajadores de turnos diurnos y nocturnos**  
Alcanzan **ahorro de tiempo y menor exposición a situaciones de riesgo**  
Con **el mapa comunitario de servicios activos según el horario de consulta**.

---

**Hipótesis 3**

Creemos que lograremos **que al menos 80 % de los reportes de riesgo sean aprobados por moderación y que 70 % de las zonas de riesgo tengan 2 o más confirmaciones independientes, durante los 3 meses posteriores al lanzamiento**  
Si **los trabajadores de turnos diurnos y nocturnos**  
Alcanzan **información sobre la seguridad de la ruta gracias a las calificaciones y reportes dejados por otros usuarios que la transitaron recientemente**  
Con **el sistema de reporte comunitario de incidentes**.

---

**Hipótesis 4**

Creemos que lograremos **una retención a 30 días (usuarios con al menos un check-in en el mes 2 sobre usuarios con check-in en el mes 1) de al menos 60 %, durante los 3 meses posteriores al lanzamiento**  
Si **los trabajadores de turnos diurnos y nocturnos**  
Alcanzan **visibilidad de sus patrones de sueño y alertas ante descanso insuficiente**  
Con **la bitácora de descanso y salud del sueño**.

---

**Hipótesis 5**

Creemos que lograremos **una tasa de renovación de suscripción de al menos 70 % al tercer mes y que al menos 20 % de los nuevos registros llegue por recomendación, durante los 6 meses posteriores al lanzamiento**  
Si **los trabajadores de turnos diurnos y nocturnos**  
Alcanzan **acceso a información relevante y beneficios negociados colectivamente**  
Con **la comunidad y sus beneficios colectivos negociados a través de la suscripción mensual**.

---

**Hipótesis 6**

Creemos que lograremos **que al menos 40 % de los trayectos finalizados reciba una calificación de ruta, durante los 3 meses posteriores al lanzamiento**  
Si **los trabajadores de turnos diurnos y nocturnos**  
Alcanzan **información sobre la seguridad de la ruta gracias a las calificaciones y reportes dejados por otros usuarios que la transitaron recientemente**  
Con **el sistema de calificación y reporte de rutas**.

---

**Hipótesis 7**

Creemos que lograremos **una mediana de 5 minutos o menos entre el vencimiento del margen de tolerancia y la primera acción del contacto de confianza, con no más de 15 % de incidentes cerrados como falso positivo, durante un piloto de 8 semanas**  
Si **los contactos de confianza**  
Alcanzan **una alerta temprana y verificada sobre un posible incidente en el trayecto**  
Con **la función de marcado automático de "posible incidente" cuando la llegada no es confirmada**.

---

**Hipótesis 8**

Creemos que lograremos **que al menos 30 % de los nuevos registros provenga de invitaciones de contactos de confianza y que el costo de adquisición por usuario sea 25 % menor al de canales pagados, durante los 6 meses posteriores al lanzamiento**  
Si **los contactos de confianza (familiares y parejas de los trabajadores de turnos diurnos y nocturnos)**  
Alcanzan **visibilidad del estado del check-in y de la llegada segura, sin necesidad de estar llamando o preguntando constantemente**  
Con **un panel de seguimiento dedicado para contactos de confianza**.

#### 1.2.2.4. Lean UX Canvas. 
Figura 1
<br>
Lean UX Canvas — Noxway
<br>
![Lean UX Canvas](resources/imgs/Lean_UX_Canvas.png)

## 1.3. Segmentos objetivo. 
**Segmento Objetivo 1: Trabajadores de turnos diurnos y nocturnos**
**Aspectos demográficos:**
- **Edad:** 18 - 55 años.
- **Nivel socioeconómico:** Media - Baja.
- **Tipo de trabajador:** Personal de primera línea, trabajadores empleos temporales y servicios esenciales.
- **Rubro:** Seguridad privada, salud, delivery, call centers, limpieza y transporte.
- **Nivel de necesidad:** Alta dependencia de herramientas que garanticen su seguridad en rutas desoladas y faciliten encontrar servicios básicos abiertos según el horario de sus desplazamientos.

**Aspectos geográficos:**
- **Nacionalidad:** Peruana.
- **Zona geográfica:** Urbana y metropolitana (Lima).

**Aspectos psicográficos:**
- **Motivación:** Llegar sanos y salvos a sus hogares y lugares de trabajo, cuidar su salud del sueño, optimizar su tiempo y reducir sus gastos durante sus turnos.
- **Valores:** La seguridad personal, el bienestar físico y el respaldo de una comunidad.
- **Intereses:** Adopción de tecnología rápida y colaborativa que les permita evitar zonas de riesgo y acceder a beneficios o alertas en tiempo real.

---

**Segmento Objetivo 2: Contactos de confianza**
**Aspectos demográficos:**
- **Edad:** 18 - 60 años.
- **Nivel socioeconómico:** Media - Baja.
- **Vínculo:** Familiares directos (padres, hermanos), parejas o amigos cercanos del trabajador de turno diurno o nocturno.
- **Rubro:** Ocupaciones diversas.
- **Nivel de necesidad:** Alta necesidad de información y certeza sobre el estado y ubicación de su ser querido para mitigar la angustia durante el día y la noche.

**Aspectos geográficos:**
- **Nacionalidad:** Peruana.
- **Zona geográfica:** Urbana y metropolitana (Lima).

**Aspectos psicográficos:**
- **Motivación:** Velar por la integridad física de su ser querido mientras este se encuentra trabajando, asegurándose de que llegue con bien a su destino sin tener que interrumpir su jornada laboral.
- **Valores:** La familia, la protección, la empatía y la tranquilidad.
- **Intereses:** Uso de aplicaciones confiables de monitoreo pasivo y notificaciones automáticas que no requieran conocimientos técnicos avanzados para su configuración.

# Capítulo II: Requirements Elicitation & Analysis 

## 2.1. Competidores.
**Competidor 1: BSafe**
bSafe es una aplicación de seguridad personal originada en Noruega, enfocada en prevenir y documentar situaciones de riesgo mediante activación por voz, transmisión en vivo, grabación de audio/video, llamadas falsas y una red de contactos de confianza ("Guardians") que reciben la ubicación en tiempo real del usuario ante una alerta SOS.

---

**Competidor 2: Noonlight**
Noonlight (anteriormente SafeTrek) es una plataforma de seguridad conectada que permite pedir ayuda de forma silenciosa con un botón de pánico, enviando la ubicación exacta del usuario a despachadores profesionales que pueden movilizar servicios de emergencia sin necesidad de hablar o marcar a la policía.

---

**Competidor 3: Safetipin**
Safetipin es una aplicación originada en India que genera "puntajes de seguridad" de calles, rutas y zonas urbanas a partir de auditorías y calificaciones hechas por la propia comunidad de usuarios (iluminación, visibilidad, presencia de gente, transporte disponible, entre otros factores). Con esta información, recomienda a los usuarios la ruta más segura (no necesariamente la más corta) y permite compartir la ubicación en tiempo real con contactos de confianza.

### 2.1.1. Análisis competitivo
<table> 
  <tr>
    <th colspan="7"> Competitive Analysis Landscape </th>
  </tr>
  <tr>
    <td colspan="2" rowspan="2">¿Por qué llevar a cabo este análisis?</td>
    <td colspan="5"> Con el objetivo de evaluar y comparar funcionalidades, tecnología, precios y estrategias de marketing de los principales competidores en seguridad personal y trayectos, para identificar nuestras fortalezas y debilidades, detectar oportunidades de negocio y definir los puntos que nos diferencian de la competencia frente al segmento específico de trabajadores de turnos diurnos y nocturnos y sus contactos de confianza. </td>
  </tr>
  <tr></tr>
  <tr>
    <td colspan="2"></td>
    <td> Noxway <br> <img src="resources/imgs/chapter_ii/logo-noxway-day-night.png" alt="Noxway" width="110" height="100"></img> </td>
    <td> bSafe <br> <img src="resources/imgs/chapter_ii/logo-bsafe.png" alt="bSafe" width="110" height="100"></img> </td>
    <td> Noonlight <br> <img src="resources/imgs/chapter_ii/logo-noonlight.png" alt="Noonlight" width="140" height="100"></img> </td>
    <td> Safetipin <br> <img src="resources/imgs/chapter_ii/logo-safetipin.png" alt="Safetipin" width="150" height="100"></img> </td>
  </tr>
  <tr>
    <td rowspan="2">Perfil</td>
    <td>Overview</td>
    <td> Noxway es una plataforma integral de seguridad, información y comunidad diseñada específicamente para trabajadores de turnos diurnos y nocturnos y sus contactos de confianza, que combina check-in de trayecto seguro, calificación y reporte comunitario de rutas, mapa de servicios activos según el horario de consulta y una comunidad con beneficios colectivos. </td>
    <td> bSafe es una app de seguridad personal que previene y documenta situaciones de riesgo mediante alarma SOS, grabación automática y una red de contactos "Guardians" que monitorean al usuario en tiempo real. </td>
    <td> Noonlight es una plataforma de seguridad conectada que permite pedir ayuda de forma silenciosa, enviando la ubicación exacta del usuario a despachadores profesionales que pueden movilizar servicios de emergencia. </td>
    <td> Safetipin es una app que genera puntajes de seguridad de calles y rutas a partir de auditorías y calificaciones de la comunidad, recomendando la ruta más segura y permitiendo compartir ubicación con contactos de confianza. </td>
  </tr>
  <tr>
    <td>Ventaja competitiva ¿Qué valor ofrece a los clientes?</td>
    <td> Ofrece una solución especializada para la realidad del trabajo en turnos diurnos y nocturnos; seguridad activa en el trayecto, calificación de rutas por la propia comunidad de trabajadores, e información confiable sobre servicios abiertos en el horario de sus desplazamientos. </td>
    <td> Ofrece prevención y evidencia documentada ante situaciones de riesgo mediante grabación automática y una red de contactos de confianza. </td>
    <td> Ofrece conexión directa y silenciosa con servicios de emergencia profesionales, sin depender de contactos personales. </td>
    <td> Ofrece información colectiva y verificada sobre qué tan segura es una calle o ruta específica, permitiendo decisiones de trayecto basadas en datos reales de la comunidad. </td>
  </tr>
  <tr>
    <td rowspan="2">Perfil de Marketing</td>
    <td> Mercado Objetivo </td>
    <td> Trabajadores de turnos diurnos y nocturnos (seguridad, delivery, salud, call centers, limpieza, etc) y sus contactos de confianza (familiares, parejas), en zonas urbanas de Lima. </td>
    <td> Personas en general que buscan seguridad personal, con fuerte enfoque en mujeres y estudiantes universitarios. </td>
    <td> Usuarios individuales, estudiantes, y empresas que integran la app a dispositivos IoT y sistemas de seguridad residencial. </td>
    <td> Mujeres, jóvenes y comunidades urbanas en general, así como gobiernos locales y planificadores urbanos interesados en datos de seguridad de sus ciudades. </td>
  </tr>
  <tr>
    <td> Estrategias de Marketing </td>
    <td> Marketing de nicho dirigido a comunidades y grupos de trabajadores de turnos diurnos y nocturnos en redes sociales, programa de referidos entre trabajadores y sus contactos de confianza. </td>
    <td> Testimonios de figuras públicas, presencia en medios internacionales, alianzas con instituciones educativas y comunidades. </td>
    <td> Alianzas B2B con marcas de seguridad del hogar e IoT (Wyze, Sabre, Roku), relaciones públicas con medios especializados en seguridad. </td>
    <td> Alianzas con ONGs, gobiernos locales y organizaciones de mujeres; presencia en medios enfocados en urbanismo y seguridad de género. </td>
  </tr>
  <tr>
    <td rowspan="3">Perfil de Producto</td>
    <td> Productos & Servicios </td>
    <td> Check-in de trayecto seguro, calificación y reporte de ruta, marcado automático de posible incidente, mapa comunitario de servicios cercanos, bitácora de descanso y salud del sueño, comunidad con beneficios colectivos, panel de seguimiento para contactos de confianza. </td>
    <td> Botón SOS por voz o táctil, transmisión en vivo, grabación automática de audio/video, llamadas falsas, red de contactos "Guardians". </td>
    <td> Botón de pánico silencioso, conexión directa con despachadores profesionales, monitoreo 24/7 opcional, integración con dispositivos IoT. </td>
    <td> Auditorías de seguridad por parámetros (iluminación, visibilidad, transporte, gente en la calle), puntaje de seguridad por zona/ruta, recomendación de ruta más segura, seguimiento de ubicación con contactos. </td>
  </tr>
  <tr>
    <td> Precios & Costos </td>
    <td> Suscripción mensual con beneficios (seguro básico, descuentos negociados colectivamente y alertas de seguridad prioritarias). </td>
    <td> Versión gratuita limitada; planes premium desde USD 1.99/mes hasta USD 19.99/año con funciones adicionales. </td>
    <td> Versión gratuita con funciones esenciales; monitoreo profesional 24/7 desde USD 9.99/mes. </td>
    <td> Aplicación gratuita para usuarios finales; el modelo de negocio principal es la venta de datos y reportes a gobiernos y organizaciones urbanas. </td>
  </tr>
  <tr>
    <td>Canales de distribución (Web y/o Móvil)</td>
    <td> Aplicación móvil disponible para iOS y Android, con integración a mapas y geolocalización. </td>
    <td> Aplicación móvil disponible para iOS y Android. </td>
    <td> Aplicación móvil disponible para iOS y Android, con APIs para integración con productos de terceros. </td>
    <td> Aplicación móvil disponible para iOS y Android, además de una plataforma web para gobiernos y organizaciones. </td>
  </tr>
  <tr>
    <td rowspan="4"> Análisis SWOT </td>
    <td> Fortalezas </td>
    <td> Especialización total en la realidad del trabajo en turnos diurnos y nocturnos, combinación única de check-in + calificación de rutas + comunidad, modelo de suscripción con beneficios tangibles adicionales. </td>
    <td> Reconocimiento internacional, tecnología robusta de grabación y evidencia, alianzas mediáticas de alto perfil. </td>
    <td> Conexión directa y profesional con servicios de emergencia, integración amplia con dispositivos IoT. </td>
    <td> Metodología de auditoría de seguridad probada y validada en 16 países, gran volumen de datos históricos, reconocimiento internacional en temas de seguridad urbana. </td>
  </tr>
  <tr>
    <td> Debilidades </td>
    <td> Dependencia de la adopción inicial y de la masa crítica de usuarios para que la calificación de rutas sea confiable. </td>
    <td> No está enfocada en las necesidades específicas de trabajadores de turnos diurnos y nocturnos ni ofrece información comunitaria del entorno. </td>
    <td> Costo elevado del monitoreo profesional continuo; no ofrece funciones de comunidad ni calificación de rutas. </td>
    <td> No cuenta con check-in de trayecto ni aviso automático a contactos de confianza; su enfoque está más en datos para políticas públicas que en la experiencia diaria del usuario individual. </td>
  </tr>
  <tr>
    <td> Oportunidades </td>
    <td> Expansión hacia distintos rubros de trabajo en turnos diurnos y nocturnos y hacia otras ciudades del Perú. </td>
    <td> Expansión hacia nuevos segmentos corporativos y de seguridad comunitaria. </td>
    <td> Expansión de alianzas B2B con más fabricantes de dispositivos de seguridad. </td>
    <td> Expansión hacia nuevos países de Latinoamérica y alianzas con más gobiernos locales. </td>
  </tr>
  <tr>
    <td> Amenazas </td>
    <td> Ingreso de aplicaciones genéricas de seguridad personal al mercado peruano con mayor reconocimiento de marca. </td>
    <td> Competencia de apps con enfoque más específico por industria o segmento. </td>
    <td> Dependencia de asociaciones B2B que podrían cambiar de proveedor. </td>
    <td> Al no monetizar directamente con el usuario final, depende de financiamiento externo (ONGs, gobiernos) que puede ser inestable. </td>
  </tr>
</table>

### 2.1.2. Estrategias y tácticas frente a competidores.
A partir del análisis competitivo, se han identificado las siguientes estrategias y tácticas para diferenciar a **Noxway** frente a los actores del mercado de seguridad personal y trayectos:

1. **Estrategias de Diferenciación:**

**Especialización en el trabajo en turnos diurnos y nocturnos:** A diferencia de bSafe, Noonlight y Safetipin, que ofrecen seguridad personal o auditoría urbana de forma genérica, **Noxway** se enfoca exclusivamente en la realidad de quienes trabajan de día y de noche, combinando check-in de trayecto seguro, calificación de rutas, información comunitaria del entorno y bitácora de descanso, algo que ningún competidor ofrece de forma integrada.

**Calificación de rutas orientada a la acción, no solo al dato:** A diferencia de Safetipin, cuyo enfoque principal es generar datos para gobiernos y planificadores urbanos, **Noxway** utiliza la calificación de rutas directamente para beneficio inmediato del propio usuario (elegir una ruta más segura, recibir alertas de zonas de riesgo cerca de su ubicación en tiempo real).

**Vínculo emocional con contactos de confianza:** A diferencia de bSafe y Noonlight, donde el contacto de confianza solo recibe una alerta puntual ante una emergencia, **Noxway** ofrece un panel de seguimiento continuo pensado para la tranquilidad de familiares y parejas durante todo el trayecto, no solo en el peor escenario.

2. **Tácticas de Marketing:**

**Marketing de nicho y comunidades existentes:** Se realizarán campañas dirigidas específicamente a comunidades y grupos de trabajadores de turnos diurnos y nocturnos en redes sociales, diferenciándonos del marketing masivo y genérico de bSafe y Noonlight.

**Programa de referidos entre trabajador y contacto de confianza:** A diferencia de los competidores, que no explotan este vínculo, **Noxway** incentivará que cada trabajador invite a sus contactos de confianza a la plataforma, generando crecimiento orgánico natural.

3. **Estrategias de Precios:**

**Suscripción con beneficios tangibles desde el inicio:** A diferencia del modelo freemium muy limitado de bSafe y Noonlight, y del modelo sin monetización directa al usuario de Safetipin, **Noxway** ofrecerá una suscripción mensual accesible que desde el primer mes incluye beneficios concretos (seguro básico, descuentos, alertas prioritarias), reforzando la percepción de valor frente al costo.

4. **Expansión y Adaptabilidad:**

**Enfoque regional inicial y expansión nacional:** **Noxway** comenzará en Lima, adaptándose a las necesidades específicas del contexto urbano peruano, antes de expandirse a otros departamentos del pais, a diferencia de competidores como Noonlight y Safetipin, que operan con un enfoque global desde su origen.

**Ecosistema local de servicios cercanos:** Se buscarán alianzas con negocios y proveedores locales (farmacias, restaurantes, grifos) que deseen aparecer destacados en el mapa comunitario de servicios cercanos, generando un ecosistema local que ningún competidor internacional replica.

### 2.2.2. Registro de entrevistas

*Registro de entrevistas — Segmento 1*

**Entrevista 1**

| Campo        | Detalle                                                                                                                                                                                                                                                                                                                |
| :----------- | :--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Nombre**   | Drago Duarte                                                                                                                                                                                                                                                                                                           |
| **Edad**     | 24 años                                                                                                                                                                                                                                                                                                                |
| **Distrito** | Chorrillos                                                                                                                                                                                                                                                                                                             |
| **Duración** | 4:31 min                                                                                                                                                                                                                                                                                                               |
| **Timing**   | Inicia 0:00 - Termina 4:31                                                                                                                                                                                                                                                                                           |
| **Enlace**   | [Ver entrevista](https://onedrive.live.com/photos?photosData=%2Fshare%2F59720A664BBCD4C3%21sb06a811007d645cda1d31517e8b2a7fa%3Fithint%3Dvideo%26e%3DwwHFBM%26migratedtospo%3Dtrue&redeem=aHR0cHM6Ly8xZHJ2Lm1zL3YvYy81OTcyMGE2NjRiYmNkNGMzL0lRQVFnV3F3MWdmTlJhSFRGUmZvc3FmNkFSMnFYV3VFTFVQMkQxU0JxUHpJQmNrP2U9d3dIRkJN) |

<div align="center">
<img src="resources/imgs/chapter_ii/entrevista1_segmento1.png" alt="Entrevista 1 - Segmento 1" width="600">
</div>

**Resumen:** Drago Duarte trabaja en el turno de madrugada en una tienda Tambo de Chorrillos. Su mayor preocupación es regresar a casa por calles desoladas y quedarse dormido en el transporte público. Actualmente, utiliza WhatsApp para avisar a su madre y compartir su ubicación. Considera útil una aplicación que envíe alertas automáticas y muestre zonas peligrosas, siempre que no consuma demasiada batería ni genere falsas alarmas. Estaría dispuesto a pagar si ofrece beneficios concretos, como seguros contra robos o descuentos.

---

**Entrevista 2**

| Campo            | Detalle                                                                                                                                                                                                                                                                                                                |
| :--------------- | :--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Nombre**       | Marco Antonio Quispe                                                                                                                                                                                                                                                                                                   |
| **Edad**         | 30 años                                                                                                                                                                                                                                                                                                                |
| **Distrito**     | San Martín de Porres                                                                                                                                                                                                                                                                                                   |
| **Duración**     | 5:34 min                                                                                                                                                                                                                                                                                                               |
| **Timing**       | Inicia 4:32 - Termina 10:06                                                                                                                                                                                                                                                                                           |
| **Estado civil** | Soltero                                                                                                                                                                                                                                                                                                                |
| **Ocupación**    | Agente de seguridad en almacén logístico (Callao), turno nocturno                                                                                                                                                                                                                                                      |
| **Enlace**       | [Ver entrevista](https://onedrive.live.com/photos?photosData=%2Fshare%2F59720A664BBCD4C3%21sb06a811007d645cda1d31517e8b2a7fa%3Fithint%3Dvideo%26e%3DwwHFBM%26migratedtospo%3Dtrue&redeem=aHR0cHM6Ly8xZHJ2Lm1zL3YvYy81OTcyMGE2NjRiYmNkNGMzL0lRQVFnV3F3MWdmTlJhSFRGUmZvc3FmNkFSMnFYV3VFTFVQMkQxU0JxUHpJQmNrP2U9d3dIRkJN) |

<div align="center">
<img src="resources/imgs/chapter_ii/entrevista2segmento1.png" alt="Entrevista 2 - Segmento 1" width="600">
</div>

**Resumen:** Marco Antonio trabaja como agente de seguridad en un almacén logístico del Callao durante el turno nocturno. Su principal preocupación es el regreso a casa, debido al cansancio y la inseguridad en el transporte público. Se comunica con su hermano por WhatsApp, pero evita compartir su ubicación continuamente porque necesita conservar la batería. Valora las alertas automáticas y una aplicación fácil de utilizar. No pagaría por una suscripción básica, salvo que incluya beneficios económicos, y dejaría de utilizarla si consume mucha batería o genera falsas alarmas.

---

**Entrevista 3**

| Campo            | Detalle                                                                                                                                                                                                                                                                                                                |
| :--------------- | :--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Nombre**       | Luis Mendoza Miranda                                                                                                                                                                                                                                                                                                   |
| **Edad**         | 32 años                                                                                                                                                                                                                                                                                                                |
| **Distrito**     | San Martín de Porres                                                                                                                                                                                                                                                                                                   |
| **Duración**     | 4:20 min                                                                                                                                                                                                                                                                                                               |
| **Timing**       | Inicia 10:07 - Termina 14:27                                                                                                                                                                                                                                                                                          |
| **Estado civil** | Soltero                                                                                                                                                                                                                                                                                                                |
| **Ocupación**    | Agente de seguridad privada                                                                                                                                                                                                                                                                                            |
| **Enlace**       | [Ver entrevista](https://onedrive.live.com/photos?photosData=%2Fshare%2F59720A664BBCD4C3%21sb06a811007d645cda1d31517e8b2a7fa%3Fithint%3Dvideo%26e%3DwwHFBM%26migratedtospo%3Dtrue&redeem=aHR0cHM6Ly8xZHJ2Lm1zL3YvYy81OTcyMGE2NjRiYmNkNGMzL0lRQVFnV3F3MWdmTlJhSFRGUmZvc3FmNkFSMnFYV3VFTFVQMkQxU0JxUHpJQmNrP2U9d3dIRkJN) |

<div align="center">
<img src="resources/imgs/chapter_ii/entrevista3_segmento1.png" alt="Entrevista 3 - Segmento 1" width="600">
</div>

**Resumen:** Luis trabaja como agente de seguridad privada en el turno nocturno y realiza largos desplazamientos entre San Martín de Porres y San Isidro. Su principal preocupación es la inseguridad durante los trayectos y la espera en los paraderos. Comparte su ubicación por WhatsApp con su pareja y considera valiosas las alertas automáticas y los reportes de zonas peligrosas. También le interesa una comunidad para compartir alertas, pero solo utilizaría la aplicación si es gratuita, sencilla y no consume demasiada batería o datos.

---

*Registro de entrevistas — Segmento 2*

**Entrevista 1**

| Campo        | Detalle                                                                                                                                                                                                                                                                                                                |
| :----------- | :--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Nombre**   | Juan Gutiérrez                                                                                                                                                                                                                                                                                                         |
| **Edad**     | 24 años                                                                                                                                                                                                                                                                                                                |
| **Distrito** | San Juan de Miraflores                                                                                                                                                                                                                                                                                                 |
| **Duración** | 4:25 min                                                                                                                                                                                                                                                                                                               |
| **Timing**   |Inicia 23:42 - Termina 28:07                                                                                                                                                                                                                                                                                        |
| **Enlace**   | [Ver entrevista](https://onedrive.live.com/photos?photosData=%2Fshare%2F59720A664BBCD4C3%21sb06a811007d645cda1d31517e8b2a7fa%3Fithint%3Dvideo%26e%3DwwHFBM%26migratedtospo%3Dtrue&redeem=aHR0cHM6Ly8xZHJ2Lm1zL3YvYy81OTcyMGE2NjRiYmNkNGMzL0lRQVFnV3F3MWdmTlJhSFRGUmZvc3FmNkFSMnFYV3VFTFVQMkQxU0JxUHpJQmNrP2U9d3dIRkJN) |

<div align="center">
<img src="resources/imgs/chapter_ii/entrevista1_segmento2.png" alt="Entrevista 1 - Segmento 2" width="600">
</div>

**Resumen:** Juan Gutiérrez es un estudiante universitario que cumple el papel de contacto de confianza de su hermano menor, quien trabaja de madrugada. Su principal preocupación es que su hermano llegue sano y salvo a casa. Actualmente, se comunican por WhatsApp para confirmar sus desplazamientos y ha experimentado angustia cuando el celular de su hermano se quedó sin batería. Considera útil una aplicación que envíe notificaciones automáticas y precisas, siempre que proteja la batería y evite falsas alarmas.

---

**Entrevista 2**

| Campo            | Detalle                                                                                                                                                                                                                                                                                                                |
| :--------------- | :--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Nombre**       | Roberto Carlos Fernández                                                                                                                                                                                                                                                                                               |
| **Edad**         | 42 años                                                                                                                                                                                                                                                                                                                |
| **Estado civil** | Casado                                                                                                                                                                                                                                                                                                                 |
| **Ocupación**    | Freelance                                                                                                                                                                                                                                                                                                              |
| **Distrito**     | San Juan de Lurigancho                                                                                                                                                                                                                                                                                                 |
| **Duración**     | 5:19 min                                                                                                                                                                                                                                                                                                               |
| **Timing**       | Inicia 18:22 - Termina 23:41                                                                                                                                                                                                                                                                                         |
| **Enlace**       | [Ver entrevista](https://onedrive.live.com/photos?photosData=%2Fshare%2F59720A664BBCD4C3%21sb06a811007d645cda1d31517e8b2a7fa%3Fithint%3Dvideo%26e%3DwwHFBM%26migratedtospo%3Dtrue&redeem=aHR0cHM6Ly8xZHJ2Lm1zL3YvYy81OTcyMGE2NjRiYmNkNGMzL0lRQVFnV3F3MWdmTlJhSFRGUmZvc3FmNkFSMnFYV3VFTFVQMkQxU0JxUHpJQmNrP2U9d3dIRkJN) |

<div align="center">
<img src="resources/imgs/chapter_ii/entrevistaSegmento2-Roberto.png" alt="Entrevista 2 - Segmento 2" width="600">
</div>

**Resumen:** Roberto Carlos Fernández es un trabajador independiente que se preocupa por la seguridad de su esposa durante sus turnos nocturnos. La falta de comunicación y un episodio en el que el celular de ella se quedó sin batería le generaron mucha angustia. Actualmente, esperan mensajes por WhatsApp para confirmar la llegada a casa. Considera que una aplicación con alertas automáticas ante retrasos o anomalías le permitiría descansar con mayor tranquilidad. Sin embargo, exige que la ubicación se comparta únicamente durante los trayectos autorizados y que se proteja la privacidad de su esposa.

---

**Entrevista 3**

| Campo        | Detalle                                                                                                                                                                                                                                                                                                                |
| :----------- | :--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Nombre**   | Ronald Ramírez                                                                                                                                                                                                                                                                                                         |
| **Edad**     | 51 años                                                                                                                                                                                                                                                                                                                |
| **Distrito** | Bellavista, Callao                                                                                                                                                                                                                                                                                                     |
| **Duración** | 3:53 min                                                                                                                                                                                                                                                                                                               |
| **Timing**   |Inicia 14:28 - Termina 18:21                                                                                                                                                                                                                                                                                         |
| **Enlace**   | [Ver entrevista](https://onedrive.live.com/photos?photosData=%2Fshare%2F59720A664BBCD4C3%21sb06a811007d645cda1d31517e8b2a7fa%3Fithint%3Dvideo%26e%3DwwHFBM%26migratedtospo%3Dtrue&redeem=aHR0cHM6Ly8xZHJ2Lm1zL3YvYy81OTcyMGE2NjRiYmNkNGMzL0lRQVFnV3F3MWdmTlJhSFRGUmZvc3FmNkFSMnFYV3VFTFVQMkQxU0JxUHpJQmNrP2U9d3dIRkJN) |

<div align="center">
<img src="resources/imgs/chapter_ii/entrevista3_segmento2.png" alt="Entrevista 3 - Segmento 2" width="600">
</div>

**Resumen:** Ronald Ramírez trabaja como asistente administrativo y se preocupa por la seguridad de su esposa, quien labora como enfermera en el turno nocturno. Para mantenerse informado, espera mensajes de confirmación cuando ella llega a su destino y permanece atento al celular durante la noche. Considera que las notificaciones automáticas de llegada le brindarían tranquilidad y le permitirían descansar mejor. Confiaría en una aplicación que ofrezca ubicación y alertas precisas, siempre que evite falsas alarmas y no consuma demasiada batería.


## 2.3. Needfinding. 

### 2.3.1. User Personas. 

En esta sección se presentan las fichas de User Personas construidas a partir de los datos recolectados del análisis de entrevistas a nuestros segmentos objetivos. Estas fichas permiten representar de forma clara y estratégica los perfiles de cada segmento objetivo, considerando sus metas, habilidades, motivaciones y dificultades. De esta manera se integra la perspectiva del usuario y tendencias del sector para identificar oportunidades en el mercado y ofrecer una solución alineada a lo que el usuario necesita.

#### Segmento Objetivo 1: Trabajador de Turno Diurno o Nocturno
![User Persona - Jorge Luis Huamán](resources/imgs/up-Jorge%20Luis%20Huaman.png)

#### Segmento Objetivo 2: Contacto de Confianza
![User Persona - Rosa Elena Paredes](resources/imgs/up-Rosa%20Elena%20Paredes.png)


### 2.3.2. User Task Matrix. 
En esta sección se presenta el User Task Matrix, construido a partir de los User Persona que representan a los dos segmentos clave identificados:
* **Segmento Objetivo 1:** Trabajador de Turno Diurno o Nocturno
* **Segmento Objetivo 2:** Contacto de Confianza

Las tareas fueron identificadas a partir del análisis cualitativo de entrevistas, y cada una fue evaluada según su frecuencia y nivel de importancia para los respectivos perfiles.

| Tarea / Actividad | Trabajador de Turno Diurno o Nocturno (Frecuencia) | Trabajador de Turno Diurno o Nocturno (Importancia) | Contacto de Confianza (Frecuencia) | Contacto de Confianza (Importancia) |
| :--- | :--- | :--- | :--- | :--- |
| Activar monitoreo o check-in de trayecto seguro al salir de casa o trabajo | Alta | Alta | Baja | Media |
| Consultar mapa colaborativo de zonas de riesgo y rutas seguras | Media | Alta | Baja | Baja |
| Buscar establecimientos abiertos según el horario del trayecto (farmacias, comida, grifos) | Media | Media | Baja | Baja |
| Recibir notificación pasiva de salida y llegada segura del trabajador | Baja | Baja | Alta | Alta |
| Recibir alerta automática ante retraso excesivo o posible incidente | Baja | Alta | Baja | Alta |
| Calificar la seguridad de la ruta al completar el desplazamiento | Media | Media | Nunca | Baja |
| Registrar horas de descanso en la bitácora de sueño y bienestar | Media | Media | Nunca | Baja |
| Acceder a beneficios grupales y coberturas de seguro mediante membresía | Baja | Media | Baja | Baja |

### 2.3.3. User Journey Mapping. 
En esta sección se presentan los mapas de viaje de usuario, reflejando la experiencia integral de nuestros segmentos objetivos en el contexto actual: un entorno urbano carente de herramientas digitales especializadas para la dinámica del trabajo en turnos diurnos y nocturnos. Se analizan los puntos de fricción, canales y emociones que experimentan tanto el trabajador de turno diurno o nocturno durante sus trayectos y jornadas, como su contacto de confianza desde el hogar.

#### Segmento Objetivo 1: Trabajador de Turno Diurno o Nocturno

![User Journey Map - Jorge Luis Huamán](resources/imgs/jm-Jorge%20Luis%20Huaman.png)

#### Segmento Objetivo 2: Contacto de Confianza

![User Journey Map - Rosa Elena Paredes](resources/imgs/jm-Rosa%20Elena%20Paredes.png)

### 2.3.4. Empathy Mapping.
En esta sección se presentan los Empathy Maps. Estos nos ayudarán a comprender las experiencias, emociones y pensamientos que expresan los usuarios de cada segmento objetivo.

#### Segmento Objetivo 1: Trabajador de Turno Diurno o Nocturno
![Empathy Map - Jorge Luis Huamán](resources/imgs/em-Jorge%20Luis%20Huaman.png)

#### Segmento Objetivo 2: Contacto de Confianza
![Empathy Map - Valeria Ríos](resources/imgs/em-Valeria%20R%C3%ADos.png)

## 2.4. Big Picture EventStorming.
En esta sección, el equipo presenta el modelado integral del dominio del negocio mediante la técnica de Big Picture EventStorming. A través de un espacio colaborativo virtual (Miro / Mural), exploramos de extremo a extremo el flujo operativo de nuestra solución: desde el registro y vinculación de contactos, la ejecución de trayectos seguros diurnos y nocturnos y la gestión de alertas, hasta la colaboración comunitaria en mapas de servicios y la administración de beneficios por suscripción. Este ejercicio permite alinear el lenguaje ubicuo, identificar cuellos de botella y delimitar los subdominios del sistema. 

![Event Storming](resources/imgs/eventStorming.png)

## 2.5. Ubiquitous Language.
* **Worker (Trabajador de Turno Diurno o Nocturno):** Usuario principal del sistema cuya jornada laboral se desarrolla durante horas diurnas o nocturnas en rubros esenciales (seguridad privada, salud, delivery, call center, limpieza, etc.) y que enfrenta riesgos específicos de movilidad y aislamiento.
* **Trusted Contact (Contacto de Confianza):** Familiar directo, pareja o allegado designado por el trabajador de turno diurno o nocturno para recibir notificaciones automáticas sobre el estado, inicio y término de sus trayectos sin invadir su privacidad.
* **Safe-Trip Check-In (Check-In de Trayecto Seguro):** Acción explícita mediante la cual el trabajador confirma el inicio o la llegada exitosa a su destino, activando o cerrando el protocolo de acompañamiento pasivo del sistema.
* **Safe Commute (Trayecto Seguro / Desplazamiento Diurno o Nocturno):** Recorrido físico realizado por el trabajador entre su hogar y su lugar de trabajo (o viceversa) durante horarios diurnos o nocturnos, con condiciones de transporte y del entorno urbano que varían según el momento del desplazamiento.
* **Possible Incident (Posible Incidente):** Estado de alerta temprana que se activa automáticamente cuando un trabajador no confirma su llegada dentro del tiempo estimado más el margen de tolerancia establecido, notificando al contacto de confianza.
* **Route Safety Rating (Calificación de Seguridad de Ruta):** Valoración colaborativa y cualitativa que realiza un trabajador al culminar su desplazamiento, calificando factores del entorno como iluminación, presencia de sospechosos, patrullaje o transitabilidad.
* **Risk Zone / Danger Spot (Zona de Riesgo / Punto de Peligro):** Ubicación geográfica o tramo vial reportado por la comunidad de trabajadores como inseguro debido a antecedentes de robos, escasa visibilidad o falta de resguardo ciudadano.
* **Nearby Services Map (Mapa de Servicios Cercanos):** Directorio georreferenciado y colaborativo de establecimientos que operan formalmente en horarios diurnos, nocturnos o continuos (farmacias, grifos, locales de comida, talleres) y que han sido verificados por los usuarios.
* **Sleep & Rest Log (Bitácora de Descanso y Salud del Sueño):** Registro personal donde el trabajador documenta sus ciclos de sueño diurno o nocturno y hábitos de reposo para monitorear su desgaste físico y recibir sugerencias de higiene del sueño.
* **Collective Benefits (Beneficios Colectivos):** Conjunto de ventajas comerciales, seguros básicos de accidentes y descuentos negociados en grupo para los usuarios que cuentan con una membresía activa.
* **Monthly Subscription (Suscripción Mensual):** Modelo de membresía recurrente que otorga acceso a coberturas complementarias de seguridad, seguros y beneficios exclusivos dentro de la plataforma.
* **Companion View (Panel de Seguimiento del Acompañante):** Interfaz simplificada y pasiva diseñada para el contacto de confianza, donde consulta el estado general del viaje y recibe alertas sin necesidad de realizar configuraciones complejas.
* **Community Moderator (Moderador de la Comunidad):** Rol asignado a usuarios verificados o miembros del equipo encargados de revisar, aprobar o desestimar reportes de nuevos servicios cercanos o incidentes en el mapa.
* **Grace Period (Margen de Tolerancia de Arribo):** Ventana de tiempo prudencial añadida a la hora estimada de llegada que permite absorber retrasos de tráfico habituales antes de disparar un estado de posible incidente. 

# Capítulo III: Requirements Specification 

## 3.1. User Stories. 

Las historias de usuario para este proyecto se crearon en colaboración con el equipo de desarrollo, enfocándose en las necesidades principales de dos tipos de usuarios: los trabajadores de turnos diurnos y nocturnos y los contactos de confianza.

Para mantener la organización, las historias se agruparon en épicas según sus funcionalidades. Los criterios de aceptación de cada historia se definieron utilizando la sintaxis Gherkin, asegurando que el equipo comprendiera el problema desde la perspectiva del usuario final.

**Epics**:
A continuación se presentan las Epics identificadas para el proyecto, que agrupan las principales funcionalidades de la plataforma orientada a la seguridad y el bienestar de los trabajadores de turnos diurnos y nocturnos y sus contactos de confianza.

| Epic ID | Título | Descripción |
| :--- | :--- | :--- |
| **EP-01** | Gestión de Cuentas de Usuario | Esta epica se centra en todo lo necesario para que los usuarios (trabajadores de turnos diurnos y nocturnos y contactos de confianza) puedan registrarse, iniciar sesión, recuperar su acceso y administrar su perfil de forma segura en la plataforma. |
| **EP-02** | Gestión de Contactos de Confianza | Esta epica abarca la funcionalidad que permite a los trabajadores de turnos diurnos y nocturnos invitar, vincular y administrar a sus contactos de confianza, quienes recibirán información sobre el estado de sus trayectos. |
| **EP-03** | Check-In de Trayecto Seguro | Esta epica cubre el ciclo completo del check-in de trayecto: desde que el trabajador de turno diurno o nocturno inicia un desplazamiento hasta que confirma su llegada o lo cancela. |
| **EP-04** | Detección y Gestión de Posibles Incidentes | Esta epica se encarga de la detección automática de posibles incidentes cuando un trayecto no es confirmado a tiempo, así como de su validación posterior y la notificación a los contactos de confianza. |
| **EP-05** | Mapa Comunitario de Servicios Cercanos | Esta epica abarca la funcionalidad para que los trabajadores de turnos diurnos y nocturnos busquen, reporten y validen colaborativamente los servicios y establecimientos abiertos según el horario de consulta. |
| **EP-06** | Calificación y Reporte de Seguridad de Rutas | Esta epica cubre las funcionalidades que permiten a los trabajadores de turnos diurnos y nocturnos calificar la seguridad de las rutas transitadas y reportar puntos específicos de riesgo, alimentando un mapa comunitario de zonas seguras e inseguras. |
| **EP-07** | Bitácora de Descanso y Salud del Sueño | Esta epica se centra en el registro y seguimiento de los hábitos de descanso del trabajador de turno diurno o nocturno, brindando visibilidad y sugerencias sobre su salud del sueño. |
| **EP-08** | Comunidad y Beneficios Colectivos | Esta epica abarca la gestión de la suscripción mensual, el acceso a beneficios colectivos negociados (seguros básicos, descuentos) y el programa de referidos entre trabajadores y contactos de confianza. |
| **EP-09** | Panel de Seguimiento del Contacto de Confianza | Esta epica cubre la experiencia del contacto de confianza dentro de la plataforma, permitiéndole visualizar en tiempo real el estado del trayecto de su trabajador vinculado y configurar sus notificaciones. |
| **EP-10** | Moderación de la Comunidad | Esta epica se encarga de las funcionalidades que permiten a los moderadores de la comunidad revisar, aprobar o rechazar los reportes de servicios cercanos e incidentes enviados por los usuarios, garantizando la calidad de la información colaborativa. |
| **EP-11** | **Arquitectura Transversal, Contexto de Actor y Manejo de Errores (API Cross-Cutting)** | Como Developer, deseo contar con mecanismos transversales de resolución de identidad por cabecera, consulta de estado de autenticación e internacionalización de errores bajo el estándar RFC 9457, para garantizar respuestas consistentes en todos los endpoints del RESTful API. | **Escenario 1: Operaciones transversales del API habilitadas**<br>**Dado** que el servidor RESTful API opera sobre la ruta base `/api/v1` con carga útil `application/json`, **cuando** procesa cualquier petición entrante con las cabeceras `X-Actor-Id` y `Accept-Language`, **entonces** resuelve el contexto de ejecución del actor y localiza los mensajes de salida en español o inglés. | - |
| **EP-12** | **Gestión de Perfiles Operativos y Vínculos de Confianza (`profiles`)** | Como Developer, deseo disponer de servicios RESTful para administrar la ficha operativa del trabajador nocturno y el ciclo de vida de sus enlaces con contactos de confianza, para soportar la sincronización de turnos y permisos de acompañamiento. | **Escenario 1: Persistencia de perfiles y vínculos**<br>**Dado** que el bounded context `profiles` gestiona cuentas y relaciones de confianza, **cuando** los clientes consumen los endpoints de `/api/v1/accounts/me` y `/api/v1/trust-links`, **entonces** el sistema valida las reglas de cupo por plan y actualiza el estado del vínculo. | - |
| **EP-13** | **Monitoreo de Trayectos Seguros, Telemetría GPS e Incidentes SOS (`commuting`)** | Como Developer, deseo proveer endpoints RESTful para el registro de desplazamientos nocturnos, ingesta de coordenadas GPS, avisos de demora y despacho de alertas SOS en tiempo real, para alimentar tanto el Portal del Trabajador como el Companion Portal. | **Escenario 1: Trazabilidad de rutas y alertas en vivo**<br>**Dado** que existe un trayecto activo registrado por un trabajador, **cuando** se emiten eventos de telemetría o incidentes SOS hacia `/api/v1/commutes`, **entonces** los endpoints de `/api/v1/companion` exponen el estado actualizado a los contactos vinculados. | - |
| **EP-14** | **Mapa Comunitario 24h, Avisos Geolocalizados y Moderación (`community` & `moderation`)** | Como Developer, deseo exponer servicios RESTful para consultar y calificar puntos seguros 24h, publicar avisos geolocalizados y moderar reportes ciudadanos, para mantener actualizada la cartografía colaborativa de seguridad nocturna. | **Escenario 1: Gobernanza de datos geográficos comunitarios**<br>**Dado** que los usuarios interactúan con `/api/v1/community` y `/api/v1/moderation`, **cuando** registran votos, avisos o decisiones administrativas, **entonces** el API valida las invariantes geográficas y recalcula los niveles de confianza. | - |
| **EP-15** | **Bitácora de Descanso y Recuperación de Sueño (`wellness`)** | Como Developer, deseo implementar endpoints RESTful para registrar sesiones de sueño sin solapamientos, configurar metas diarias y calcular métricas semanales, para respaldar el seguimiento de salud del trabajador nocturno. | **Escenario 1: Control de integridad en registros de descanso**<br>**Dado** que el módulo `wellness` procesa intervalos temporales de sueño, **cuando** se invocan los servicios bajo `/api/v1/wellness`, **entonces** el sistema previene cruces de horarios y calcula el déficit acumulado. | - |
| **EP-16** | **Suscripciones, Conciliación de Pagos Offline y Beneficios (`subscriptions`)** | Como Developer, deseo habilitar endpoints RESTful para gestionar suscripciones a planes, conciliar órdenes de pago offline sin duplicidad y registrar el canje de cupones colectivos, para soportar la monetización y fidelización del modelo de negocio. | **Escenario 1: Activación de planes y control de referencias de pago**<br>**Dado** que un trabajador solicita un plan o beneficio en `/api/v1/subscriptions` o `/api/v1/benefits`, **cuando** se procesa el pago o reclamo de cupón, **entonces** el API garantiza la unicidad del comprobante y actualiza las coberturas del usuario. | - |
---

**User Stories**:
Requisitos definidos junto con el conjunto de User Stories y Epics para los requisitos identificados. Las User Stories incluyen Acceptance Criteria redactados en tiempo presente, tercera persona, sin hacer referencia a detalles de interfaz de usuario, siguiendo la estructura de Gherkin (Given-When-Then). Se incluyen además User Stories para el sitio web estático (Landing Page), tomando como rol base visitante.

# Historias de Usuario - Noxway

| Epic / Story ID | Título | Descripción | Criterios de Aceptación | Relacionado con (Epic ID) |
| :--- | :--- | :--- | :--- | :--- |
| **US-01** | Registro de usuario | Como nuevo usuario, quiero registrarme indicando mi rol (trabajador o contacto) para integrarme a la red de soporte para distintos turnos, contribuyendo a la meta de alcanzar 2,500 usuarios activos verificados. | **Escenario 1:** Dado que el nuevo usuario ingresa datos correctos, Cuando envía el formulario, Entonces su cuenta es creada y se le asigna el rol.<br><br>**Escenario 2:** Dado que el usuario omite campos o usa un correo ya registrado, Cuando envía el formulario, Entonces el sistema bloquea el registro y resalta el error. | EP-01 |
| **US-02** | Inicio de sesión | Como usuario registrado, quiero iniciar sesión de forma segura para acceder rápidamente a mis herramientas de protección, garantizando la meta de 75% de uso semanal de la plataforma. | **Escenario 1:** Dado que el usuario ingresa credenciales correctas, Cuando inicia sesión, Entonces el sistema concede el acceso a su panel.<br><br>**Escenario 2:** Dado que el usuario ingresa una contraseña errónea, Cuando intenta iniciar sesión, Entonces el sistema deniega el acceso con un mensaje de error. | EP-01 |
| **US-03** | Recuperación de contraseña | Como usuario, quiero solicitar la recuperación de mi contraseña para restablecer mi acceso sin fricciones, reduciendo la tasa de abandono temporal de la plataforma. | **Escenario 1:** Dado que el usuario ingresa un correo registrado, Cuando solicita la recuperación, Entonces se envía un enlace de restablecimiento.<br><br>**Escenario 2:** Dado que ingresa un correo no registrado, Cuando lo solicita, Entonces el sistema notifica que la cuenta no existe. | EP-01 |
| **US-04** | Edición de perfil | Como usuario, quiero editar mis datos para mantener mis métodos de contacto actualizados, asegurando que las alertas de emergencia lleguen al destino correcto sin retrasos. | **Escenario 1:** Dado que el usuario modifica sus datos, Cuando guarda los cambios, Entonces el perfil se actualiza.<br><br>**Escenario 2:** Dado que el usuario ingresa un teléfono con formato inválido, Cuando intenta guardar, Entonces el sistema rechaza la acción. | EP-01 |
| **US-05** | Conocer propuesta de valor (Landing) | Como visitante, quiero conocer la propuesta de valor en el "Hero" para entender cómo Noxway protege mis trayectos, acelerando mi decisión de registro para lograr la adopción temprana. | **Escenario 1:** Dado que el visitante entra a la Landing Page, Cuando carga la sección inicial, Entonces se muestra la propuesta de valor y los botones de llamado a la acción.<br><br>**Escenario 2:** Dado que el navegador tiene red inestable, Cuando la página carga parcialmente, Entonces se prioriza el texto principal de la propuesta de valor. | EP-01 |
| **US-31** | Visualizar video demostrativo | Como visitante, quiero reproducir el video explicativo para confiar en la solidez técnica del producto, impulsando el volumen de registros calificados a la plataforma. | **Escenario 1:** Dado que el visitante ubica la sección multimedia, Cuando pulsa reproducir, Entonces el video inicia sin interrupciones.<br><br>**Escenario 2:** Dado que el servidor de video falla, Cuando la sección carga, Entonces se muestra un mensaje alternativo de indisponibilidad. | EP-01 |
| **US-32** | Consultar testimonios | Como visitante, quiero leer testimonios de colegas para sentir respaldo y empatía, reduciendo la fricción emocional antes de comprometerme a usar la aplicación. | **Escenario 1:** Dado que el visitante ve el carrusel, Cuando desliza entre opciones, Entonces el sistema muestra testimonios diferentes.<br><br>**Escenario 2:** Dado que intenta interactuar en una pantalla táctil sin responder, Cuando hace swipe, Entonces el sistema asegura que la lectura del testimonio actual permanezca estática y legible. | EP-01 |
| **US-33** | Desplegar FAQ (Landing) | Como visitante, quiero expandir las preguntas frecuentes para resolver mis dudas de privacidad y costos, derribando objeciones e incentivando la creación de una cuenta. | **Escenario 1:** Dado que el visitante ve una pregunta colapsada, Cuando hace clic, Entonces la respuesta se expande.<br><br>**Escenario 2:** Dado que una respuesta ya está abierta, Cuando hace clic en otra, Entonces la anterior se repliega automáticamente para no saturar la pantalla. | EP-01 |
| **US-34** | Formulario de contacto | Como visitante, quiero enviar preguntas directas al equipo para resolver inquietudes técnicas, capturando "leads" interesados que contribuyan al crecimiento corporativo. | **Escenario 1:** Dado que completa todos los campos válidos, Cuando envía el formulario, Entonces recibe un mensaje de éxito.<br><br>**Escenario 2:** Dado que omite el correo electrónico, Cuando envía, Entonces el sistema bloquea el envío resaltando el campo requerido. | EP-01 |
| **US-35** | Cambiar idioma y tema | Como visitante, quiero alternar a "Modo Oscuro" o idioma para adaptar la visibilidad a las condiciones de iluminación de mi turno, demostrando empatía con el usuario desde el primer contacto. | **Escenario 1:** Dado que el visitante acciona el interruptor de tema, Cuando se activa el modo oscuro, Entonces la paleta de colores cambia a contrastes aptos para condiciones de poca luz.<br><br>**Escenario 2:** Dado que el dispositivo no soporta el cambio dinámico, Cuando hace clic, Entonces se respeta el tema configurado a nivel de sistema por defecto. | EP-01 |
| **US-36** | Consultar Términos y Código Ético | Como visitante, quiero acceder a los Términos de Servicio y Código Ético desde el Footer para validar el tratamiento seguro de mi geolocalización, impulsando la confianza para registrarme. | **Escenario 1:** Dado que el visitante se desplaza al footer, Cuando hace clic en "Términos de Servicio", Entonces se despliega una ventana modal con las políticas (ACM/IEEE).<br><br>**Escenario 2:** Dado que hay una interrupción de carga, Cuando intenta abrir el enlace, Entonces se descarga una versión PDF de respaldo. | EP-01 |
| **US-37** |  Accesos Institucionales (Redes) | Como visitante, quiero poder ir a las redes sociales oficiales desde la Landing Page para validar que la comunidad está activa, reforzando la credibilidad institucional. | **Escenario 1:** Dado que el usuario visualiza los íconos de redes, Cuando hace clic en uno, Entonces se abre la página oficial en una pestaña nueva.<br><br>**Escenario 2:** Dado que el enlace de red social se encuentre temporalmente roto, Cuando se hace clic, Entonces el usuario se mantiene en la página sin errores 404 intrusivos. | EP-01 |
| **US-38** | Validar Zonas de Cobertura | Como visitante, quiero verificar el indicador de "Cobertura en Lima y Callao" para cerciorarme de que el servicio opera en mi distrito, mitigando el riesgo de suscribirme y no poder usarlo. | **Escenario 1:** Dado que el visitante localiza el bloque de Cobertura, Cuando lee la información, Entonces verifica el estado operativo (Ej. 24h Services Operational).<br><br>**Escenario 2:** Dado que el servicio sufra una caída regional, Cuando carga la sección, Entonces el indicador debe reflejar de forma transparente "Degradado" o "En mantenimiento". | EP-01 |
| **US-39** | Navegación Anclada (Smooth Scroll) | Como visitante, quiero utilizar los enlaces del header (Protocolo, Ecosistema, Planes) para desplazarme velozmente a mi área de interés, optimizando mi tiempo antes del turno. | **Escenario 1:** Dado que el visitante está en el Hero, Cuando hace clic en "Planes" en el header, Entonces la página hace scroll suave hasta la sección de suscripción.<br><br>**Escenario 2:** Dado que JavaScript esté desactivado en el navegador, Cuando hace clic en el enlace, Entonces la página salta de forma nativa a la sección (Fallback anchor link). | EP-01 |
| **US-06** | Invitar contacto de confianza | Como trabajador de turno diurno o nocturno, quiero invitar a un contacto para integrarlo a mi monitoreo, contribuyendo directamente al objetivo estratégico de 60% de contactos vinculados. | **Escenario 1:** Dado que el trabajador ingresa un número válido, Cuando envía invitación, Entonces el sistema envía el enlace.<br><br>**Escenario 2:** Dado que intenta invitar a alguien ya vinculado, Cuando envía, Entonces el sistema informa la duplicidad y aborta el proceso. | EP-02 |
| **US-07** | Aceptar invitación de contacto | Como contacto de confianza, quiero aceptar una invitación para establecer el vínculo oficial de protección mutua, sumando al KPI de crecimiento de red de soporte activo. | **Escenario 1:** Dado que el contacto recibe la solicitud, Cuando hace clic en aceptar, Entonces el vínculo se formaliza en la base de datos.<br><br>**Escenario 2:** Dado que el contacto recibe la solicitud, Cuando hace clic en rechazar, Entonces el vínculo no se establece y el trabajador es notificado. | EP-02 |
| **US-08** | Remover contacto | Como trabajador de turno diurno o nocturno, quiero eliminar un contacto obsoleto para resguardar la privacidad de mi geolocalización, evitando el envío de alertas erróneas a personas equivocadas. | **Escenario 1:** Dado que el trabajador confirma la eliminación, Cuando acciona el borrado, Entonces el contacto deja de recibir alertas.<br><br>**Escenario 2:** Dado que el trabajador presiona eliminar por error, Cuando el sistema solicita confirmación y este cancela, Entonces el contacto se mantiene vinculado. | EP-02 |
| **US-09** | Iniciar check-in seguro | Como trabajador de turno diurno o nocturno, quiero iniciar mi trayecto con tiempo estimado para activar el seguimiento pasivo, garantizando el cumplimiento de la meta del 75% de uso semanal. | **Escenario 1:** Dado que el usuario fija destino y tiempo, Cuando inicia check-in, Entonces el sistema activa telemetría y avisa a contactos.<br><br>**Escenario 2:** Dado que intenta iniciar otro trayecto con uno ya en curso, Cuando pulsa iniciar, Entonces el sistema exige finalizar el anterior. | EP-03 |
| **US-10** | Confirmar llegada segura | Como trabajador de turno diurno o nocturno, quiero marcar mi llegada para desactivar el rastreo y dar tranquilidad, evitando detenciones y falsas alarmas antes de la intervención de terceros. | **Escenario 1:** Dado que el trayecto está en curso, Cuando confirma llegada, Entonces se cierra el trayecto y se avisa a contactos.<br><br>**Escenario 2:** Dado que el trabajador pierde conexión a red, Cuando confirma llegada, Entonces la app guarda el estado localmente y sincroniza en cuanto vuelve el internet. | EP-03 |
| **US-11** | Cancelar check-in | Como trabajador de turno diurno o nocturno, quiero cancelar un viaje activo por cambio de planes para mantener limpios mis registros, evitando el disparo de alertas de seguridad injustificadas. | **Escenario 1:** Dado que el trayecto está activo, Cuando se cancela, Entonces el monitoreo cesa sin alarmas.<br><br>**Escenario 2:** Dado que el viaje se encuentra en estado de "Posible Incidente", Cuando intenta cancelar sin justificar, Entonces el sistema exige un PIN o validación para descartar secuestro. | EP-03 |
| **US-12** | Marcado automático de incidente | Como trabajador de turno diurno o nocturno, quiero que la app genere un posible incidente automático al vencer el tiempo, asegurando una intervención inmediata que reduzca un 30% los incidentes sin atender. | **Escenario 1:** Dado que el tiempo límite y tolerancia expiran, Cuando el cronómetro evalúa, Entonces dispara la alerta a contactos.<br><br>**Escenario 2:** Dado que el usuario se encuentra dentro del margen de tolerancia (ej. +10m por tráfico), Cuando el sistema evalúa, Entonces no se dispara aún el incidente. | EP-04 |
| **US-13** | Validar posible incidente | Como trabajador de turno diurno o nocturno, quiero poder descartar un incidente marcado por el sistema para detener el pánico familiar, cumpliendo la meta de filtrar falsas alarmas efectivamente. | **Escenario 1:** Dado que se marca posible incidente, Cuando el usuario pulsa "Estoy Bien", Entonces se cierra la alerta como falso positivo.<br><br>**Escenario 2:** Dado que se marca posible incidente, Cuando el usuario no responde en 5 minutos, Entonces el sistema escala la severidad y muestra la ficha de rescate al contacto. | EP-04 |
| **US-14** | Recibir alerta en tiempo real | Como contacto de confianza, quiero recibir una notificación inmediata de emergencia para accionar directorios policiales, reduciendo tiempos de respuesta a incidentes críticos. | **Escenario 1:** Dado que se genera un incidente, Cuando se procesa en el backend, Entonces el contacto recibe SMS y push.<br><br>**Escenario 2:** Dado que el celular del contacto no tenga datos, Cuando el push falle, Entonces el sistema envía automáticamente un SMS tradicional (fallback). | EP-04 |
| **US-15** | Buscar servicios cercanos | Como trabajador de turno diurno o nocturno, quiero ubicar farmacias/grifos abiertos según el horario de consulta para evitar exponerme en calles vacías, incentivando la adopción y utilidad diaria de la plataforma. | **Escenario 1:** Dado que busca locales cerca, Cuando ejecuta, Entonces ve un mapa con servicios validados.<br><br>**Escenario 2:** Dado que no existan locales reportados en 5km, Cuando busca, Entonces se muestra un mensaje de área vacía sugiriendo reportar lugares conocidos. | EP-05 |
| **US-16** | Reportar servicio nuevo | Como trabajador de turno diurno o nocturno, quiero añadir un comercio con su horario de atención al mapa para nutrir el ecosistema, contribuyendo a la meta de alcanzar 1,000 servicios cercanos validados. | **Escenario 1:** Dado que ingresa datos válidos del comercio, Cuando envía, Entonces pasa a estado "Pendiente de validación".<br><br>**Escenario 2:** Dado que reporta una ubicación ya existente, Cuando envía, Entonces el sistema fusiona o alerta de la duplicidad. | EP-05 |
| **US-17** | Calificar servicio reportado | Como trabajador de turno diurno o nocturno, quiero auditar y calificar servicios ajenos para mantener la veracidad del mapa, garantizando información segura para la comunidad activa. | **Escenario 1:** Dado que evalúa un servicio existente, Cuando vota positivo, Entonces sube el score de confiabilidad.<br><br>**Escenario 2:** Dado que un servicio recibe múltiples votos negativos, Cuando cruza el umbral bajo, Entonces es ocultado y mandado a moderación. | EP-05 |
| **US-18** | Calificar seguridad de ruta | Como trabajador de turno diurno o nocturno, quiero calificar qué tan segura fue mi ruta al finalizar para crear mapas de calor, ayudando a lograr la métrica del 40% de viajes calificados. | **Escenario 1:** Dado que finaliza su viaje, Cuando califica con estrellas, Entonces se asocia el puntaje a esa vía.<br><br>**Escenario 2:** Dado que descarta la pantalla de calificación, Cuando lo hace, Entonces la ruta queda "sin calificar" pero no se bloquea la app. | EP-06 |
| **US-19** | Reportar punto de riesgo | Como trabajador de turno diurno o nocturno, quiero marcar un cruce peligroso para prevenir asaltos a colegas, impactando en la reducción de incidentes reportados a nivel global. | **Escenario 1:** Dado que señala un punto con descripción, Cuando envía, Entonces aparece un marcador de peligro comunitario.<br><br>**Escenario 2:** Dado que marca un punto sin texto explicativo, Cuando envía, Entonces el sistema rechaza obligando a escribir un motivo corto. | EP-06 |
| **US-20** | Ver zonas de riesgo en mapa | Como trabajador de turno diurno o nocturno, quiero visualizar las alertas de riesgo antes de arrancar mi moto/caminata para planificar desvíos seguros, materializando el valor de inteligencia comunitaria. | **Escenario 1:** Dado que consulta el mapa, Cuando navega, Entonces visualiza perímetros sombreados por riesgo.<br><br>**Escenario 2:** Dado que apaga su geolocalización, Cuando abre el mapa, Entonces el sistema pide permiso para ubicarlo antes de mostrar riesgos locales. | EP-06 |
| **US-21** | Registrar descanso | Como trabajador de turno diurno o nocturno, quiero anotar mis horas de sueño diurno o nocturno para monitorear desgaste crónico, incrementando la retención de usuarios preocupados por su salud. | **Escenario 1:** Dado que ingresa hora de dormir y despertar lógicas, Cuando guarda, Entonces se suman al acumulado semanal.<br><br>**Escenario 2:** Dado que pone hora final anterior a la inicial, Cuando guarda, Entonces arroja error de incongruencia horaria. | EP-07 |
| **US-22** | Historial de descanso | Como trabajador de turno diurno o nocturno, quiero revisar mis gráficos semanales de descanso para demostrar mis patrones de higiene del sueño, justificando el valor de los módulos de bienestar. | **Escenario 1:** Dado que tiene datos históricos, Cuando abre la vista, Entonces ve gráficos estadísticos claros.<br><br>**Escenario 2:** Dado que no tiene registros previos, Cuando entra a la sección, Entonces se le presenta un "Estado vacío" amigable invitando a empezar. | EP-07 |
| **US-23** | Alerta por déficit de sueño | Como trabajador de turno diurno o nocturno, quiero recibir advertencias si mi promedio de sueño baja drásticamente, previniendo accidentes laborales u operativos graves. | **Escenario 1:** Dado que el promedio baja de 5 horas semanales, Cuando el motor evalúa, Entonces lanza sugerencia de fatiga aguda.<br><br>**Escenario 2:** Dado que sus horas están estables, Cuando evalúa, Entonces no genera notificaciones intrusivas. | EP-07 |
| **US-24** | Consultar planes (Landing) | Como visitante, quiero comparar los planes (Esencial vs Centinela Pro) para visualizar beneficios y seguros, facilitando la conversión hacia la meta de 600 suscriptores de pago. | **Escenario 1:** Dado que mira los planes, Cuando hace clic en suscribir a "Centinela Pro", Entonces el checkout pre-selecciona el plan.<br><br>**Escenario 2:** Dado que la API de precios falla, Cuando carga la web, Entonces se muestran precios base almacenados en caché para no perder la venta. | EP-08 |
| **US-25** | Suscribirse (Pago) | Como trabajador de turno diurno o nocturno, quiero ejecutar el pago de mi suscripción para desbloquear el monitoreo avanzado, garantizando el flujo de monetización de la plataforma. | **Escenario 1:** Dado que ingresa un método de pago válido, Cuando se procesa, Entonces se activa la membresía premium.<br><br>**Escenario 2:** Dado que la tarjeta no tiene fondos, Cuando se procesa, Entonces el sistema rechaza y mantiene al usuario en la capa Esencial gratuita. | EP-08 |
| **US-26** | Acceder a beneficios | Como suscriptor activo, quiero usar mi seguro y cupones de descuento (grifos/boticas) para obtener retorno de mi inversión mensual, asegurando una retención del 70%. | **Escenario 1:** Dado que tiene cuenta pro, Cuando entra a beneficios, Entonces genera códigos QR válidos para descuentos.<br><br>**Escenario 2:** Dado que es usuario gratuito, Cuando intenta acceder a seguros, Entonces la app le invita a hacer "Upgrade" mostrando el candado. | EP-08 |
| **US-27** | Referir contacto (Beneficio) | Como trabajador de turno diurno o nocturno, quiero dar un código de invitación a un compañero para ganar meses gratis, acelerando la meta de adquisición y bajando el costo de marketing (CAC). | **Escenario 1:** Dado que un referido usa su código al registrarse, Cuando finaliza, Entonces el referidor gana su bonificación.<br><br>**Escenario 2:** Dado que el código ingresado es falso o expirado, Cuando se evalúa, Entonces arroja "Código inválido" pero deja que el registro fluya sin bono. | EP-08 |
| **US-28** | Companion View (Panel) | Como contacto de confianza, quiero ver el mapa satelital del viaje de mi familiar en tiempo real para no tener que llamarlo, cumpliendo la promesa de paz mental pasiva de la app. | **Escenario 1:** Dado que el viaje está activo, Cuando abre el enlace, Entonces ve un vehículo moviéndose en el mapa web.<br><br>**Escenario 2:** Dado que el viaje terminó hace horas, Cuando abre el enlace, Entonces se muestra estado "Llegada Confirmada" en lugar del mapa en vivo. | EP-09 |
| **US-29** | Configurar Notificaciones | Como contacto, quiero elegir solo alertas de inicio y emergencia (silenciando las de rutina) para no hartarme de la app, manteniendo mi cuenta vinculada permanentemente. | **Escenario 1:** Dado que apaga las alertas "SMS rutina", Cuando guarda, Entonces solo recibe emergencias.<br><br>**Escenario 2:** Dado que intenta apagar las "Alertas SOS", Cuando guarda, Entonces el sistema bloquea y advierte que las alertas críticas no se pueden apagar. | EP-09 |
| **US-30** | Moderar comunidad | Como moderador (Noxway), quiero auditar zonas y servicios reportados para evitar spam o "trolls", manteniendo el prestigio de los datos comunitarios frente a nuevos usuarios. | **Escenario 1:** Dado que ve un reporte pendiente, Cuando pulsa "Aprobar", Entonces el punto se publica a todos.<br><br>**Escenario 2:** Dado que es un reporte vacío o de broma, Cuando pulsa "Rechazar", Entonces desaparece y el usuario generador pierde "Trust Score". | EP-10 |
---

**Technical Stories:**
Las Technical Stories consideran el rol Developer en la redacción de la descripción, y se enfocan en las features del RESTful API necesarias para soportar cada una de las Epics del proyecto. Se ha definido una Technical Story por cada Epic identificada.

| Epic / Story ID | Título | Descripción | Criterios de Aceptación | Relacionado con (Epic ID) |
| :--- | :--- | :--- | :--- | :--- |
| **TS01** | **Resolución de Actor y Estado Estructurado de IAM** | Como Developer, deseo identificar al actor activo mediante la cabecera `X-Actor-Id` y exponer el estado del módulo IAM en `/api/v1/auth/status`, para permitir la operación de los portales de Trabajador, Contacto de Confianza y Administrador mientras la autenticación JWT permanece diferida. | **Escenario 1: Consulta de estado IAM con seguridad deshabilitada**<br>**Dado** que la propiedad `app.security.enabled` se encuentra configurada en `false`, **cuando** el cliente envía una petición `GET /api/v1/auth/status`, **entonces** el servicio responde con código `200 OK` e incluye en el cuerpo JSON los atributos `securityEnabled: false`, `mode: "STRUCTURED_PENDING_IMPLEMENTATION"` y `defaultWorkerId: "00000000-0000-0000-0000-000000000101"`.<br><br>**Escenario 2: Resolución de actor por defecto (Fallback)**<br>**Dado** que `app.security.enabled` es `false` y el cliente omite la cabecera `X-Actor-Id` en la petición HTTP, **cuando** invoca cualquier endpoint protegido bajo `/api/v1`, **entonces** el API asigna automáticamente el contexto de ejecución al trabajador principal `00000000-0000-0000-0000-000000000101` y procesa la solicitud.<br><br>**Escenario 3: Invocación de contrato IAM diferido**<br>**Dado** que `app.security.enabled` está en `false`, **cuando** el cliente envía una petición `POST` hacia `/api/v1/auth/sign-in`, `/api/v1/auth/sign-up`, `/api/v1/auth/sign-out` o `/api/v1/auth/password-reset`, **entonces** el API responde con estado `501 Not Implemented` y un objeto `ProblemDetail` RFC 9457 localizado según la cabecera `Accept-Language`. | EP-11 |
| **TS02** | **Manejo Estandarizado de Errores con RFC 9457 Problem Details** | Como Developer, deseo que todas las respuestas de error (`4xx` y `5xx`) del RESTful API cumplan con el estándar RFC 9457 Problem Details y soporten la cabecera `Accept-Language`, para presentar diagnósticos estructurados y localizados (`es`/`en`) al cliente consumidor. | **Escenario 1: Error de validación de campos de entrada (`400 Bad Request`)**<br>**Dado** que el cliente envía una carga útil JSON con campos requeridos faltantes o formatos inválidos junto con `Accept-Language: es`, **cuando** el API evalúa el cuerpo de la petición, **entonces** responde con estado `400 Bad Request`, `type: "https://api.noxway.pe/problems/validation-error"` y el detalle de `errors` por cada campo.<br><br>**Escenario 2: Acceso denegado o recurso inexistente (`403 Forbidden` y `404 Not Found`)**<br>**Dado** que un actor intenta modificar un recurso perteneciente a otro trabajador o consulta un identificador inexistente o no aprobado, **cuando** el API verifica los permisos de propiedad y la existencia del registro, **entonces** retorna `403 Forbidden` (`type: ".../problems/forbidden"`) o `404 Not Found` (`type: ".../problems/not-found"`) respectivamente.<br><br>**Escenario 3: Conflicto de estado o violación de regla de dominio (`409 Conflict` y `422 Unprocessable Entity`)**<br>**Dado** que el cliente intenta duplicar un recurso único o incumple una invariante de negocio, **cuando** el dominio rechaza la transacción, **entonces** el API responde con `409 Conflict` (`type: ".../problems/conflict"`) ante duplicidades o `422 Unprocessable Entity` (`type: ".../problems/rule-violation"`) ante violaciones de reglas de dominio. | EP-11 |
| **TS03** | **Consulta y Actualización de Perfil y Turno Laboral** | Como Developer, deseo proveer el endpoint `GET` y `PUT /api/v1/accounts/me` para consultar y actualizar el nombre, teléfono, tipo de turno (`NIGHT`, `DAY`, `ROTATING`), horario de jornada y zona horaria del actor, para mantener sincronizada su ficha operativa. | **Escenario 1: Consulta exitosa del perfil propio**<br>**Dado** un trabajador activo identificado mediante la cabecera `X-Actor-Id`, **cuando** el cliente envía una petición `GET /api/v1/accounts/me`, **entonces** el API responde con código `200 OK` y devuelve la representación JSON actual del perfil y turno laboral.<br><br>**Escenario 2: Actualización válida de datos y jornada laboral**<br>**Dado** un trabajador activo identificado por `X-Actor-Id`, **cuando** envía `PUT /api/v1/accounts/me` con valores válidos en `fullName`, `phone`, `shiftType`, `shiftStart`, `shiftEnd` y `timeZone`, **entonces** el API persiste los cambios y responde con código `200 OK` incluyendo el perfil actualizado.<br><br>**Escenario 3: Rechazo por parámetros de perfil inválidos**<br>**Dado** que el cliente envía `PUT /api/v1/accounts/me` con un `shiftType` no reconocido o campos obligatorios vacíos, **cuando** el API valida el esquema de entrada, **entonces** rechaza la petición con estado `400 Bad Request` bajo el formato RFC 9457. | EP-12 |
| **TS04** | **Invitación y Ciclo de Vida de Contactos de Confianza (`TrustLink`)** | Como Developer, deseo exponer los endpoints `POST /api/v1/trust-links` y `POST /api/v1/trust-links/{id}/accept` validando el cupo del plan de suscripción del trabajador, para gestionar el envío y aceptación de vínculos de monitoreo en vivo. | **Escenario 1: Creación de invitación dentro del límite del plan**<br>**Dado** que el trabajador posee cupo disponible según su suscripción (`ESSENTIAL`: 1 contacto; `SENTINEL_PRO` o `FAMILY_CREW`: hasta 5 contactos), **cuando** envía `POST /api/v1/trust-links` con `{ "contactEmail": "rosa.paredes@noxway.pe" }`, **entonces** el API registra el vínculo en estado `PENDING` y responde con código `201 Created`.<br><br>**Escenario 2: Bloqueo por límite de contactos del plan superado**<br>**Dado** que un trabajador suscrito al plan `ESSENTIAL` ya registra 1 vínculo de confianza activo, **cuando** envía `POST /api/v1/trust-links` para invitar a un segundo contacto, **entonces** el API rechaza la operación con estado `422 Unprocessable Entity` (`rule-violation`).<br><br>**Escenario 3: Aceptación del vínculo por el contacto de confianza**<br>**Dado** que existe una solicitud de vínculo en estado `PENDING` dirigida al actor destinatario, **cuando** el contacto envía `POST /api/v1/trust-links/{id}/accept`, **entonces** el vínculo cambia a estado `ACTIVE`, retorna `200 OK` y habilita la visibilidad del trabajador en `/api/v1/companion/live`. | EP-12 |
| **TS05** | **Inicio de Trayecto Nocturno, Telemetría GPS, Demora y Llegada Segura** | Como Developer, deseo implementar los endpoints `POST /api/v1/commutes`, `/telemetry`, `/delay` y `/arrive` restringiendo la concurrencia a un único trayecto activo por trabajador, para registrar el seguimiento GPS y el cierre seguro de cada desplazamiento. | **Escenario 1: Inicio de trayecto y restricción de trayecto único activo**<br>**Dado** que el trabajador no tiene recorridos en curso, **cuando** envía `POST /api/v1/commutes` con origen, destino y medio de transporte, **entonces** el API crea el trayecto en estado `ACTIVE` (`201 Created`); pero si ya posee un trayecto en estado `ACTIVE` o `DELAYED` e intenta abrir otro simultáneamente, el API responde con estado `409 Conflict`.<br><br>**Escenario 2: Ingesta de ping de telemetría GPS**<br>**Dado** que el trabajador mantiene un trayecto activo identificado por `{id}`, **cuando** envía `POST /api/v1/commutes/{id}/telemetry` con `latitude`, `longitude`, `speed` y `recordedAt`, **entonces** el API almacena la coordenada, responde con código `201 Created` y actualiza el último ping expuesto en `GET /api/v1/companion/live`.<br><br>**Escenario 3: Reporte de demora y confirmación de llegada segura**<br>**Dado** un trayecto en estado `ACTIVE`, **cuando** el trabajador envía `POST /api/v1/commutes/{id}/delay` o `POST /api/v1/commutes/{id}/arrive`, **entonces** el API transiciona el estado a `DELAYED` o `ARRIVED` respectivamente, responde `200 OK` y genera las notificaciones hacia los contactos vinculados. | EP-13 |
| **TS06** | **Emisión de Incidentes SOS y Monitoreo en Vivo del Companion** | Como Developer, deseo habilitar el endpoint `POST /api/v1/commutes/{id}/incidents` para el disparo de emergencias SOS y los endpoints `GET /api/v1/companion/live` y `/alerts`, para que los contactos de confianza supervisen la ruta y atiendan alertas críticas. | **Escenario 1: Disparo de incidente SOS durante un trayecto**<br>**Dado** que el trabajador se encuentra en un trayecto activo, **cuando** envía `POST /api/v1/commutes/{id}/incidents` con `{ "type": "SOS" }`, **entonces** el API crea el incidente en estado `OPEN`, encola las alertas multicanal y responde con código `201 Created`.<br><br>**Escenario 2: Consulta de monitoreo en vivo y alertas por el contacto**<br>**Dado** que un trabajador vinculado ha iniciado ruta o disparado un incidente `SOS`, **cuando** el contacto de confianza activo consulta `GET /api/v1/companion/live` y `GET /api/v1/companion/alerts`, **entonces** el API responde `200 OK` entregando el incidente `OPEN`, las coordenadas del último ping GPS y el historial de entregas por canal (`IN_APP`, `WHATSAPP`, `EMAIL`).<br><br>**Escenario 3: Acceso restringido a contactos sin vínculo activo**<br>**Dado** que un actor no posee un `TrustLink` en estado `ACTIVE` con el trabajador, **cuando** intenta acceder a los datos del trayecto o resolver un incidente ajeno, **entonces** el API deniega o filtra el recurso conforme a las políticas de autorización (`403 Forbidden`). | EP-13 |
| **TS07** | **Exploración de Locales 24h, Zonas de Riesgo y Votación de Confianza** | Como Developer, deseo proveer los endpoints `GET /api/v1/community/services`, `GET /api/v1/community/risk-zones` y `PUT /api/v1/community/services/{id}/vote`, para listar puntos seguros 24h y recalcular su puntaje de confianza comunitaria. | **Escenario 1: Consulta filtrada de servicios 24h y zonas de riesgo**<br>**Dado** que existen puntos de servicio en estado `APPROVED` y zonas de riesgo registradas, **cuando** el cliente envía `GET /api/v1/community/services` o `GET /api/v1/community/risk-zones`, **entonces** el API responde con código `200 OK` y la colección georreferenciada de locales y alertas.<br><br>**Escenario 2: Registro y recálculo de voto de confianza (`+1`, `-1`, `0`)**<br>**Dado** un punto de servicio en estado `APPROVED`, **cuando** un usuario envía `PUT /api/v1/community/services/{id}/vote` con `{ "direction": 1 }`, `{ "direction": -1 }` o `{ "direction": 0 }` (para retirar el voto), **entonces** el API recalcula dinámicamente `trustScore`, `upvotes`, `downvotes` y `myVote`, respondiendo `200 OK`.<br><br>**Escenario 3: Intento de votación sobre punto inexistente o no aprobado**<br>**Dado** que un punto de servicio aún se encuentra en estado `PENDING` o no existe, **cuando** el cliente envía `PUT /api/v1/community/services/{id}/vote`, **entonces** el API responde con estado `404 Not Found` (`not-found`). | EP-14 |
| **TS08** | **Publicación de Avisos Comunitarios con Categoría y Coordenadas Geográficas** | Como Developer, deseo exponer el endpoint `POST /api/v1/community/posts` validando la integridad del par de coordenadas geográficas y enriqueciendo los datos del autor, para permitir la publicación de avisos comunitarios vinculados al mapa 24h. | **Escenario 1: Publicación exitosa de aviso con categoría y coordenadas válidas**<br>**Dado** un trabajador autenticado por contexto que selecciona un punto en el mapa, **cuando** envía `POST /api/v1/community/posts` con `title`, `content`, `district` (o valor por defecto `"Lima"`), `category`, `latitude` y `longitude`, **entonces** el API persiste el aviso, enriquece automáticamente `authorName` y `authorRole`, y responde con código `201 Created`.<br><br>**Escenario 2: Rechazo por coordenadas geográficas incompletas**<br>**Dado** que el cliente envía una petición `POST /api/v1/community/posts` proporcionando `latitude` sin `longitude` (o viceversa), **cuando** el API ejecuta la validación de invariante geográfica, **entonces** rechaza la solicitud respondiendo con estado `422 Unprocessable Entity` (`rule-violation`).<br><br>**Escenario 3: Publicación de aviso comunitario sin geolocalización opcional**<br>**Dado** que el usuario redacta un aviso informativo general con `title`, `content`, `district` y `category` omitiendo ambos campos de coordenadas (`latitude` y `longitude` nulos), **cuando** envía `POST /api/v1/community/posts`, **entonces** el API registra el aviso textual exitosamente y responde `201 Created`. | EP-14 |
| **TS09** | **Moderación Administrativa de Puntos 24h y Zonas de Riesgo** | Como Developer, deseo implementar los endpoints `GET /api/v1/moderation/reports` y `POST /api/v1/moderation/reports/{id}/decision` restringidos a roles de moderación, para aprobar o rechazar los reportes antes de su publicación en el mapa 24h. | **Escenario 1: Listado de cola de reportes pendientes de moderación**<br>**Dado** un actor con rol `MODERATOR` o `ADMIN`, **cuando** envía la petición `GET /api/v1/moderation/reports?status=PENDING`, **entonces** el API responde con código `200 OK` y la lista de reportes de locales 24h y zonas de riesgo pendientes de revisión.<br><br>**Escenario 2: Aprobación o rechazo de reporte ciudadano**<br>**Dado** un reporte en estado `PENDING` identificado por `{id}`, **cuando** el moderador envía `POST /api/v1/moderation/reports/{id}/decision` indicando la acción de aprobación o rechazo y el motivo, **entonces** el API actualiza el estado a `APPROVED` (habilitándolo en el mapa público) o `REJECTED` y responde `200 OK`.<br><br>**Escenario 3: Bloqueo de moderación para usuarios sin privilegios**<br>**Dado** un actor con rol estándar de trabajador o contacto sin permisos de administración, **cuando** intenta invocar `POST /api/v1/moderation/reports/{id}/decision`, **entonces** el API rechaza la petición con estado `403 Forbidden` (`forbidden`). | EP-14 |
| **TS10** | **Bitácora de Descanso sin Solapamientos y Meta Diaria de Sueño** | Como Developer, deseo proveer los endpoints `POST /api/v1/wellness/rest-sessions`, `PUT /api/v1/wellness/goal` y `GET /api/v1/wellness/summary` validando rangos de minutos y cruces horarios, para gestionar la recuperación de sueño del trabajador. | **Escenario 1: Registro exitoso de sesión de descanso sin cruces**<br>**Dado** que el trabajador envía un intervalo de descanso válido que no se cruza con registros previos, **cuando** invoca `POST /api/v1/wellness/rest-sessions` con fecha, hora de inicio, fin y notas, **entonces** el API almacena la sesión y responde con código `201 Created`.<br><br>**Escenario 2: Rechazo por solapamiento de intervalo de descanso**<br>**Dado** que el trabajador ya posee una sesión de sueño registrada entre las `08:00` y las `14:00` de la misma fecha, **cuando** envía `POST /api/v1/wellness/rest-sessions` con un intervalo que se solapa parcial o totalmente con dicho horario, **entonces** el API rechaza el registro con estado `422 Unprocessable Entity` (`rule-violation`).<br><br>**Escenario 3: Configuración de meta diaria dentro del rango permitido y resumen semanal**<br>**Dado** un trabajador activo, **cuando** envía `PUT /api/v1/wellness/goal` con un valor entre `240` y `720` minutos y luego consulta `GET /api/v1/wellness/summary`, **entonces** el API actualiza la meta (`200 OK`) y retorna el promedio semanal y déficit de sueño calculado; si el valor está fuera del rango `240–720`, responde `422 Unprocessable Entity` o `400 Bad Request`. | EP-15 |
| **TS11** | **Suscripción a Planes, Conciliación de Pago Offline y Canje de Cupones** | Como Developer, deseo habilitar los endpoints `POST /api/v1/subscriptions`, `POST /api/v1/subscriptions/{id}/payments`, `POST /api/v1/payments/{id}/confirm-offline` y `POST /api/v1/benefits/{id}/claims`, para procesar altas de planes, pagos por Yape/Plin y recompensas por referidos. | **Escenario 1: Creación de orden de suscripción y registro de pago offline**<br>**Dado** un trabajador que elige un plan del catálogo (`SENTINEL_PRO` o `FAMILY_CREW`), **cuando** envía `POST /api/v1/subscriptions` y registra el comprobante mediante `POST /api/v1/subscriptions/{id}/payments`, **entonces** el API crea la orden de pago en estado `PENDING` y responde con código `201 Created`.<br><br>**Escenario 2: Conciliación exitosa de comprobante offline y activación por 30 días**<br>**Dado** un pago en estado `PENDING`, **cuando** el administrador ejecuta `POST /api/v1/payments/{id}/confirm-offline` con una referencia única como `{ "reference": "YAPE-987654" }`, **entonces** el pago pasa a estado `CONFIRMED`, la suscripción cambia a `ACTIVE` por 30 días, se acredita la recompensa al referente si aplica y el API responde `200 OK`.<br><br>**Escenario 3: Rechazo por referencia de pago offline duplicada y canje de beneficio**<br>**Dado** que la referencia `YAPE-987654` ya fue utilizada en un pago confirmado previamente, **cuando** se intenta reutilizar en otro registro de pago, **entonces** el API responde con estado `409 Conflict`; asimismo, cuando un trabajador con plan activo invoca `POST /api/v1/benefits/{id}/claims`, el API valida la elegibilidad del plan y genera el cupón canjeado (`201 Created`). | EP-16 |

---

## 3.2. Impact Mapping. 

En esta sección se presenta el Impact Mapping de la solución, técnica que permite alinear los objetivos estratégicos del negocio con las necesidades de nuestros dos User Personas (Jorge Luis Huamán y Rosa Elena Paredes), definiendo el impacto esperado en su comportamiento, los entregables de software a construir y las historias de usuario requeridas.

![Impact Mapping](resources/imgs/ImpactMap-OpenSource.png)

---
## 3.3. Product Backlog. 

| # Orden | User Story Id | Título | Descripción | Story Points (1/2/3/5/8) |
| :---: | :---: | :--- | :--- | :---: |
| 1 | US-05 | Conocer propuesta de valor (Landing) | Como visitante, quiero conocer la propuesta de valor en el "Hero" para entender cómo Noxway protege mis trayectos, acelerando mi decisión de registro para lograr la adopción temprana. | 2 |
| 2 | US-24 | Consultar planes (Landing) | Como visitante, quiero comparar los planes (Esencial vs Centinela Pro) para visualizar beneficios y seguros, facilitando la conversión hacia la meta de 600 suscriptores de pago. | 2 |
| 3 | US-31 | Visualizar video demostrativo | Como visitante, quiero reproducir el video explicativo para confiar en la solidez técnica del producto, impulsando el volumen de registros calificados a la plataforma. | 2 |
| 4 | US-32 | Consultar testimonios | Como visitante, quiero leer testimonios de colegas para sentir respaldo y empatía, reduciendo la fricción emocional antes de comprometerme a usar la aplicación. | 2 |
| 5 | US-33 | Desplegar FAQ (Landing) | Como visitante, quiero expandir las preguntas frecuentes para resolver mis dudas de privacidad y costos, derribando objeciones e incentivando la creación de una cuenta. | 1 |
| 6 | US-35 | Cambiar idioma y tema | Como visitante, quiero alternar a "Modo Oscuro" o idioma para adaptar la visibilidad a las condiciones de iluminación de mi turno, demostrando empatía con el usuario desde el primer contacto. | 2 |
| 7 | US-38 | Validar Zonas de Cobertura | Como visitante, quiero verificar el indicador de "Cobertura en Lima y Callao" para cerciorarme de que el servicio opera en mi distrito, mitigando el riesgo de suscribirme y no poder usarlo. | 1 |
| 8 | US-39 | Navegación Anclada (Smooth Scroll) | Como visitante, quiero utilizar los enlaces del header (Protocolo, Ecosistema, Planes) para desplazarme velozmente a mi área de interés, optimizando mi tiempo antes del turno. | 1 |
| 9 | US-34 | Formulario de contacto | Como visitante, quiero enviar preguntas directas al equipo para resolver inquietudes técnicas, capturando "leads" interesados que contribuyan al crecimiento corporativo. | 2 |
| 10 | US-36 | Consultar Términos y Código Ético | Como visitante, quiero acceder a los Términos de Servicio y Código Ético desde el Footer para validar el tratamiento seguro de mi geolocalización, impulsando la confianza para registrarme. | 1 |
| 11 | US-37 | Accesos Institucionales (Redes) | Como visitante, quiero poder ir a las redes sociales oficiales desde la Landing Page para validar que la comunidad está activa, reforzando la credibilidad institucional. | 1 |
| 12 | TS-01 | Resolución de Actor y Estado Estructurado de IAM | Como Developer, deseo identificar al actor activo mediante la cabecera `X-Actor-Id` y consultar el estado del módulo IAM en `/api/v1/auth/status`, para operar los portales de Trabajador, Contacto de Confianza y Administrador sin bloqueos mientras el módulo JWT permanece diferido. | 3 |
| 13 | TS-02 | Manejo Estandarizado de Errores con RFC 9457 Problem Details | Como Developer, deseo que todas las respuestas de error (`4xx` y `5xx`) del RESTful API sigan el estándar RFC 9457 Problem Details, para mostrar mensajes claros y localizados (`es`/`en`) en la interfaz. | 3 |
| 14 | US-09 | Iniciar check-in seguro | Como trabajador de turno diurno o nocturno, quiero iniciar mi trayecto con tiempo estimado para activar el seguimiento pasivo, garantizando el cumplimiento de la meta del 75% de uso semanal. | 5 |
| 15 | TS-05 | Iniciar Trayecto Nocturno, Registrar Ping GPS y Confirmar Llegada | Como Developer, deseo implementar los endpoints `POST /api/v1/commutes`, `/telemetry`, `/delay` y `/arrive` restringiendo la concurrencia a un único trayecto activo por trabajador, para que los contactos conozcan la ubicación y estado en tiempo real. | 8 |
| 16 | US-10 | Confirmar llegada segura | Como trabajador de turno diurno o nocturno, quiero marcar mi llegada para desactivar el rastreo y dar tranquilidad, evitando detenciones y falsas alarmas antes de la intervención de terceros. | 3 |
| 17 | US-11 | Cancelar check-in | Como trabajador de turno diurno o nocturno, quiero cancelar un viaje activo por cambio de planes para mantener limpios mis registros, evitando el disparo de alertas de seguridad injustificadas. | 3 |
| 18 | US-28 | Companion View (Panel) | Como contacto de confianza, quiero ver el mapa satelital del viaje de mi familiar en tiempo real para no tener que llamarlo, cumpliendo la promesa de paz mental pasiva de la app. | 5 |
| 19 | TS-06 | Emisión de Incidentes SOS y Monitoreo en Vivo del Companion | Como Developer, deseo habilitar el endpoint `POST /api/v1/commutes/{id}/incidents` y los endpoints `GET /api/v1/companion/live` y `/alerts`, para visualizar el trayecto en curso, la última coordenada GPS en OpenStreetMap y resolver incidentes SOS abiertos. | 8 |
| 20 | US-12 | Marcado automático de incidente | Como trabajador de turno diurno o nocturno, quiero que la app genere un posible incidente automático al vencer el tiempo, asegurando una intervención inmediata que reduzca un 30% los incidentes sin atender. | 5 |
| 21 | US-13 | Validar posible incidente | Como trabajador de turno diurno o nocturno, quiero poder descartar un incidente marcado por el sistema para detener el pánico familiar, cumpliendo la meta de filtrar falsas alarmas efectivamente. | 3 |
| 22 | US-14 | Recibir alerta en tiempo real | Como contacto de confianza, quiero recibir una notificación inmediata de emergencia para accionar directorios policiales, reduciendo tiempos de respuesta a incidentes críticos. | 5 |
| 23 | US-29 | Configurar Notificaciones | Como contacto, quiero elegir solo alertas de inicio y emergencia (silenciando las de rutina) para no hartarme de la app, manteniendo mi cuenta vinculada permanentemente. | 3 |
| 24 | US-06 | Invitar contacto de confianza | Como trabajador de turno diurno o nocturno, quiero invitar a un contacto para integrarlo a mi monitoreo, contribuyendo directamente al objetivo estratégico de 60% de contactos vinculados. | 3 |
| 25 | TS-04 | Invitación y Ciclo de Vida de Contactos de Confianza (`TrustLink`) | Como Developer, deseo exponer los endpoints `POST /api/v1/trust-links` y `POST /api/v1/trust-links/{id}/accept` respetando el cupo del plan de suscripción, para gestionar las invitaciones y habilitar el monitoreo en vivo. | 5 |
| 26 | US-07 | Aceptar invitación de contacto | Como contacto de confianza, quiero aceptar una invitación para establecer el vínculo oficial de protección mutua, sumando al KPI de crecimiento de red de soporte activo. | 3 |
| 27 | US-08 | Remover contacto | Como trabajador de turno diurno o nocturno, quiero eliminar un contacto obsoleto para resguardar la privacidad de mi geolocalización, evitando el envío de alertas erróneas a personas equivocadas. | 2 |
| 28 | US-15 | Buscar servicios cercanos | Como trabajador de turno diurno o nocturno, quiero ubicar farmacias/grifos abiertos según el horario de consulta para evitar exponerme en calles vacías, incentivando la adopción y utilidad diaria de la plataforma. | 5 |
| 29 | TS-07 | Exploración de Locales 24h, Zonas de Riesgo y Votación de Confianza | Como Developer, deseo proveer los endpoints `GET /api/v1/community/services`, `GET /api/v1/community/risk-zones` y `PUT /api/v1/community/services/{id}/vote`, para explorar puntos 24h en OpenStreetMap y recalcular su puntaje de confianza. | 5 |
| 30 | US-16 | Reportar servicio nuevo | Como trabajador de turno diurno o nocturno, quiero añadir un comercio con su horario de atención al mapa para nutrir el ecosistema, contribuyendo a la meta de alcanzar 1,000 servicios cercanos validados. | 3 |
| 31 | US-17 | Calificar servicio reportado | Como trabajador de turno diurno o nocturno, quiero auditar y calificar servicios ajenos para mantener la veracidad del mapa, garantizando información segura para la comunidad activa. | 3 |
| 32 | US-20 | Ver zonas de riesgo en mapa | Como trabajador de turno diurno o nocturno, quiero visualizar las alertas de riesgo antes de arrancar mi moto/caminata para planificar desvíos seguros, materializando el valor de inteligencia comunitaria. | 3 |
| 33 | US-19 | Reportar punto de riesgo | Como trabajador de turno diurno o nocturno, quiero marcar un cruce peligroso para prevenir asaltos a colegas, impactando en la reducción de incidentes reportados a nivel global. | 3 |
| 34 | TS-08 | Publicación de Avisos Comunitarios con Categoría y Punto en OpenStreetMap | Como Developer, deseo exponer el endpoint `POST /api/v1/community/posts` indicando categoría y coordenadas válidas en OpenStreetMap, para alertar a otros trabajadores y permitirles abrir el punto directamente en `Mapa 24h`. | 5 |
| 35 | US-18 | Calificar seguridad de ruta | Como trabajador de turno diurno o nocturno, quiero calificar qué tan segura fue mi ruta al finalizar para crear mapas de calor, ayudando a lograr la métrica del 40% de viajes calificados. | 2 |
| 36 | US-21 | Registrar descanso | Como trabajador de turno diurno o nocturno, quiero anotar mis horas de sueño diurno o nocturno para monitorear desgaste crónico, incrementando la retención de usuarios preocupados por su salud. | 3 |
| 37 | TS-10 | Bitácora de Descanso sin Solapamientos y Meta Diaria | Como Developer, deseo proveer los endpoints `POST /api/v1/wellness/rest-sessions`, `PUT /api/v1/wellness/goal` y `GET /api/v1/wellness/summary`, para registrar sesiones sin solapamientos y controlar el déficit de sueño acumulado. | 5 |
| 38 | US-22 | Historial de descanso | Como trabajador de turno diurno o nocturno, quiero revisar mis gráficos semanales de descanso para demostrar mis patrones de higiene del sueño, justificando el valor de los módulos de bienestar. | 3 |
| 39 | US-23 | Alerta por déficit de sueño | Como trabajador de turno diurno o nocturno, quiero recibir advertencias si mi promedio de sueño baja drásticamente, previniendo accidentes laborales u operativos graves. | 3 |
| 40 | US-25 | Suscribirse (Pago) | Como trabajador de turno diurno o nocturno, quiero ejecutar el pago de mi suscripción para desbloquear el monitoreo avanzado, garantizando el flujo de monetización de la plataforma. | 5 |
| 41 | TS-11 | Suscripción a Planes, Conciliación de Pago Offline y Cupones | Como Developer, deseo habilitar los endpoints `POST /api/v1/subscriptions`, `/payments`, `/confirm-offline` y `POST /api/v1/benefits/{id}/claims`, para activar planes por 30 días, validar referencias únicas de pago offline y canjear beneficios. | 8 |
| 42 | US-26 | Acceder a beneficios | Como suscriptor activo, quiero usar mi seguro y cupones de descuento (grifos/boticas) para obtener retorno de mi inversión mensual, asegurando una retención del 70%. | 3 |
| 43 | US-27 | Referir contacto (Beneficio) | Como trabajador de turno diurno o nocturno, quiero dar un código de invitación a un compañero para ganar meses gratis, acelerando la meta de adquisición y bajando el costo de marketing (CAC). | 3 |
| 44 | US-04 | Edición de perfil | Como usuario, quiero editar mis datos para mantener mis métodos de contacto actualizados, asegurando que las alertas de emergencia lleguen al destino correcto sin retrasos. | 2 |
| 45 | TS-03 | Gestión de Perfil y Turno Laboral | Como Developer, deseo proveer el endpoint `GET/PUT /api/v1/accounts/me` para consultar y actualizar nombre, teléfono, tipo de turno (`NIGHT`, `DAY`, `ROTATING`), horario y zona horaria, para mantener sincronizada la ficha operativa. | 3 |
| 46 | US-30 | Moderar comunidad | Como moderador (Noxway), quiero auditar zonas y servicios reportados para evitar spam o "trolls", manteniendo el prestigio de los datos comunitarios frente a nuevos usuarios. | 3 |
| 47 | TS-09 | Moderación Administrativa de Puntos 24h y Zonas de Riesgo | Como Developer, deseo implementar los endpoints `GET /api/v1/moderation/reports?status=PENDING` y `POST /api/v1/moderation/reports/{id}/decision`, para asegurar la calidad de los datos publicados en el mapa 24h. | 5 |
| 48 | US-01 | Registro de usuario | Como nuevo usuario, quiero registrarme indicando mi rol (trabajador o contacto) para integrarme a la red de soporte para distintos turnos, contribuyendo a la meta de alcanzar 2,500 usuarios activos verificados. | 3 |
| 49 | US-02 | Inicio de sesión | Como usuario registrado, quiero iniciar sesión de forma segura para acceder rápidamente a mis herramientas de protección, garantizando la meta de 75% de uso semanal de la plataforma. | 3 |
| 50 | US-03 | Recuperación de contraseña | Como usuario, quiero solicitar la recuperación de mi contraseña para restablecer mi acceso sin fricciones, reduciendo la tasa de abandono temporal de la plataforma. | 2 |
---
<img src="resources/imgs/evidenciaTrello.png" alt="Trello" width="300">


**Trello:** [NoxWay Product Backlog](https://trello.com/invite/b/6aac8f9dc7251c019b6afd53/ATTI7b90483e43107e48d696e3beb440000b26CB42DE/noxway-product-backlog)

# Capítulo IV: Product Design 

## 4.1. Style Guidelines. 

### 4.1.1. General Style Guidelines.

**El estilo visual de la startup**

El estilo visual de la startup se fundamenta en los principios de seguridad, confianza, bienestar, accesibilidad y claridad visual, considerando que los usuarios principales son trabajadores que desarrollan sus actividades en horarios diurnos o nocturnos, así como familiares, parejas y contactos de confianza que necesitan conocer su estado durante sus desplazamientos.

La interfaz está diseñada para funcionar en contextos diurnos y nocturnos, donde la iluminación puede variar y el usuario puede encontrarse realizando actividades laborales o desplazándose. Por ello, se prioriza una experiencia simple, intuitiva y de rápida comprensión, reduciendo la cantidad de elementos innecesarios y destacando únicamente la información relevante.

Asimismo, la solución está dirigida a usuarios con distintos niveles de alfabetización digital, por lo que se evita el uso de tecnicismos y se emplean componentes visuales familiares, mensajes directos e iconografía universal.

#### Principios de diseño

**Simplicidad:** Se priorizan interfaces limpias y fáciles de comprender, reduciendo la carga cognitiva y mostrando únicamente las acciones e información necesarias para cada momento.

**Seguridad:** Las funciones relacionadas con emergencias, trayectos y posibles incidentes deben ser fácilmente identificables. Las acciones críticas tendrán una ubicación y comportamiento consistente para que puedan ejecutarse rápidamente.

**Confianza:** La interfaz debe transmitir protección y confiabilidad mediante colores, mensajes y componentes visuales coherentes. El usuario debe comprender en todo momento qué información está compartiendo y con quién.

**Consistencia:** Se mantiene un uso uniforme de colores, tipografías, iconos, botones, tarjetas y estados en todos los módulos de la plataforma.

**Jerarquía visual:** La información se organiza según su nivel de importancia, destacando especialmente alertas de seguridad, estado del trayecto, posibles incidentes y notificaciones dirigidas a los contactos de confianza.

**Accesibilidad:** Se utilizan contrastes adecuados, tamaños de texto legibles, botones de tamaño apropiado y etiquetas claras para facilitar la interacción de usuarios con diferentes capacidades y niveles de experiencia tecnológica.

**Privacidad:** La información relacionada con ubicación, trayectos y contactos de confianza se presenta de manera clara, evitando exponer información personal innecesaria y permitiendo al usuario comprender cuándo se está compartiendo su ubicación.

**Paleta de colores**

La selección de colores de la startup busca transmitir seguridad, confianza, tranquilidad y bienestar, utilizando una combinación que funcione correctamente tanto en ambientes diurnos y nocturnos como en situaciones donde el usuario necesita identificar rápidamente una alerta.

Se propone utilizar una paleta basada en tonos oscuros y colores de acento:

| Color | Uso | Significado |
|---|---|---|
| Azul oscuro | Fondo principal y navegación | Seguridad y confianza |
| Azul | Botones y acciones principales | Confianza y tecnología |
| Verde | Estados positivos | Seguridad, bienestar y confirmación |
| Amarillo o ámbar | Advertencias | Precaución |
| Rojo | Emergencias e incidentes | Peligro y atención inmediata |
| Blanco o gris claro | Textos y superficies | Legibilidad |

La utilización de colores de alerta se realizará de manera controlada. El rojo estará reservado principalmente para situaciones críticas, como una emergencia o un posible incidente, evitando utilizarlo como elemento decorativo.

**Tipografía**

Se seleccionan las tipografías Poppins y Roboto debido a su buena legibilidad en dispositivos digitales y a su apariencia moderna y accesible.

- **Poppins:** títulos, encabezados y elementos destacados.
- **Roboto:** textos, descripciones, formularios, mensajes y contenido informativo.

**Jerarquía tipográfica**

| Elemento | Tipografía | Uso | Tamaño |
|---|---|---|---|
| Encabezado 1 | Poppins | Títulos principales | 28-36 px |
| Encabezado 2 | Poppins | Títulos de sección | 22-30 px |
| Encabezado 3 | Poppins | Tarjetas y subsecciones | 18-24 px |
| Texto principal | Roboto | Información principal | 14-16 px |
| Texto secundario | Roboto | Información complementaria | 12-14 px |
| Botones | Roboto | Acciones | 14-16 px |

**Espaciado**

Se define un sistema de espaciado basado en múltiplos de 8 px, con el objetivo de mantener una distribución consistente:

- **8 px:** separación mínima entre elementos relacionados.
- **16 px:** separación estándar entre componentes.
- **24 px:** separación entre secciones.
- **32 px:** separación entre bloques principales.
- **40 px o más:** separación de áreas principales de la interfaz.

Este sistema permite mantener una estructura ordenada y facilita la adaptación de la interfaz a diferentes tamaños de pantalla.

**Tono de comunicación**

El tono de comunicación de la startup es:

- **Sereno y tranquilizador**, especialmente durante situaciones de riesgo.
- **Claro y directo**, evitando tecnicismos innecesarios.
- **Cercano pero profesional**, considerando que el sistema acompaña al usuario durante situaciones personales y laborales.
- **Preventivo**, priorizando información que permita anticipar situaciones de riesgo.
- **Respetuoso**, considerando la diversidad de trabajadores y contextos laborales.
- **Orientado a la acción**, indicando claramente qué puede hacer el usuario ante cada situación.

Como referencia, se priorizan mensajes directos y fáciles de comprender. Por ejemplo:

> "Tu trayecto está activo. Tu contacto de confianza puede ver tu estado."

En lugar de utilizar mensajes técnicos como:

> "El servicio de geolocalización se encuentra ejecutando el proceso de seguimiento."

### 4.1.2. Web Style Guidelines.
**1. Diseño y estructura**

La interfaz de la startup sigue una estructura orientada a proporcionar acceso rápido a las principales funciones de seguridad, comunidad y bienestar.

Se utiliza una navegación principal que permite acceder rápidamente a:

- Inicio.
- Mi trayecto.
- Mapa.
- Comunidad.
- Bienestar.
- Beneficios.
- Perfil.

El contenido se organiza mediante tarjetas y secciones claramente diferenciadas, priorizando la información relacionada con el estado del trayecto y la seguridad del usuario.

Las funciones críticas, como iniciar trayecto, confirmar llegada o reportar una emergencia, deben encontrarse disponibles con el menor número posible de pasos.

**Justificación:** Esta estructura permite que los trabajadores de turnos diurnos y nocturnos puedan utilizar la aplicación rápidamente mientras se encuentran trabajando o desplazándose.

**2. Sistema de grillas**

Se utiliza un sistema de diseño basado en una grilla de 12 columnas para escritorio y estructuras adaptativas para dispositivos móviles.

Las principales características son:

- Espaciado basado en múltiplos de 8 px.
- Contenedores responsivos.
- Distribución consistente de tarjetas.
- Márgenes adaptables.
- Componentes reutilizables.

**Justificación:** Permite mantener una estructura visual consistente y facilita la adaptación de la plataforma a diferentes dispositivos y resoluciones.

**3. Componentes UI principales**

**Tarjetas**

Las tarjetas se utilizan para agrupar información relacionada, por ejemplo:

- Estado del trayecto.
- Contactos de confianza.
- Servicios abiertos.
- Reportes de seguridad.
- Estado del descanso.
- Beneficios disponibles.
- Publicaciones de la comunidad.

Cada tarjeta debe mostrar información concreta y permitir identificar rápidamente su función.

**Botones**

Se establecen tres tipos principales:

**Primario:** Se utiliza para las acciones principales, como iniciar trayecto, confirmar llegada, guardar información o unirse a la comunidad.

**Secundario:** Se utiliza para acciones alternativas, como ver detalles, editar información, cancelar o consultar el historial.

**Peligro:** Se utiliza para acciones relacionadas con situaciones críticas, como reportar un incidente, cancelar un trayecto o activar una emergencia.

Los botones contemplan los siguientes estados:

- Normal.
- Hover o flotar.
- Activo.
- Deshabilitado.
- Cargando.

Las acciones críticas deberán presentar una diferenciación visual clara para evitar errores.

**Insignias o Badges**

Las insignias permiten identificar rápidamente los estados dentro del sistema.

Algunos ejemplos son:

- **Trayecto seguro**
- **En camino**
- **Precaución**
- **Posible incidente**
- **Emergencia**
- **Trayecto finalizado**

Los colores siempre estarán acompañados por texto o iconografía para no depender únicamente del color.

**Formularios**

Los formularios deben presentar:

- Etiquetas visibles.
- Campos claramente diferenciados.
- Validación en tiempo real.
- Mensajes de error específicos.
- Indicadores de campos obligatorios.

Ejemplo:

> "Número de teléfono es obligatorio."

En lugar de utilizar mensajes genéricos como:

> "Error de validación."

**Notificaciones**

Las notificaciones proporcionarán retroalimentación sobre eventos importantes.

Se utilizarán para:

- Confirmación de llegada.
- Inicio de trayecto.
- Posible incidente.
- Reportes de la comunidad.
- Alertas de seguridad.
- Errores.
- Confirmaciones de acciones.

Se contemplan dos tipos principales:

**Tostadas (Toast):** Para confirmaciones y mensajes informativos de corta duración.

**Alertas dentro de la interfaz:** Para situaciones importantes que requieren la atención del usuario.

#### 4. Interacción (comportamiento UX)

**Feedback inmediato**

El sistema debe proporcionar retroalimentación inmediata después de cada acción relevante.

Ejemplos:

- "Trayecto iniciado correctamente."
- "Llegada confirmada."
- "Tu contacto de confianza ha sido notificado."
- "Reporte enviado para revisión."

**Justificación:** La retroalimentación inmediata permite reducir la incertidumbre y aumenta la confianza del usuario en el funcionamiento de la plataforma.

**Restricciones de acciones**

El sistema debe evitar acciones que puedan generar información incorrecta o poner en riesgo al usuario.

Por ejemplo:

- No se puede confirmar una llegada si no existe un trayecto activo.
- No se puede finalizar un trayecto que ya fue cerrado.
- Un reporte de emergencia requiere una confirmación para evitar activaciones accidentales.
- La información de ubicación solo se comparte durante el periodo autorizado por el usuario.
- Un posible incidente puede requerir confirmación posterior por parte del trabajador.

**Visualización del estado**

Los estados del sistema se representan mediante una combinación de:

- Colores.
- Iconos.
- Texto.
- Indicadores de progreso.
- Líneas de tiempo.

Por ejemplo, un trayecto puede visualizarse como:

**Inicio → En camino → Cerca del destino → Llegada confirmada**

Esto permite que tanto el trabajador como su contacto de confianza comprendan rápidamente el estado actual del trayecto.

**5. Diseño adaptable**

La startup está diseñada principalmente para dispositivos móviles, debido a que los trabajadores utilizarán la plataforma durante sus desplazamientos diurnos y nocturnos.

También se contempla su uso en:

- Smartphone.
- Tablet.
- Escritorio.

**Móvil**

La versión móvil prioriza:

- Acciones principales accesibles con una mano.
- Botones grandes.
- Navegación simplificada.
- Acceso rápido a emergencia.
- Mapa y ubicación.
- Estado del trayecto.
- Notificaciones.
- Lectura clara tanto bajo luz diurna intensa como en ambientes con poca iluminación, con contraste y tema visual ajustables.

**Tablet y escritorio**

Se aprovecha el espacio disponible para presentar:

- Mapas de mayor tamaño.
- Historial de trayectos.
- Información de comunidad.
- Estadísticas de bienestar.
- Administración de contactos.
- Beneficios y servicios disponibles.

**6. Navegación**

La navegación debe ser simple y consistente.

**Móvil**

Se utiliza una barra de navegación inferior para acceder a las funciones principales:

**Inicio | Trayecto | Mapa | Comunidad | Perfil**

Las funciones de emergencia y seguridad deben permanecer fácilmente accesibles.

**Escritorio**

Se utiliza una barra lateral persistente con las principales secciones:

- Inicio.
- Mis trayectos.
- Mapa de servicios cercanos.
- Comunidad.
- Bienestar.
- Beneficios.
- Contactos de confianza.
- Perfil.

También se pueden utilizar migas de pan en las secciones con mayor profundidad de navegación.

**7. Iconografía**

Se utilizarán iconos simples, reconocibles y consistentes para facilitar la comprensión de las funcionalidades.

Algunos ejemplos son:

| Función | Icono sugerido |
|---|---|
| Inicio | Casa |
| Trayecto | Ubicación |
| Emergencia | Alerta |
| Seguridad | Escudo |
| Contacto de confianza | Personas |
| Mapa | Mapa |
| Comunidad | Personas |
| Reportar incidente | Advertencia |
| Bienestar y sueño | Luna |
| Beneficios | Regalo |
| Configuración | Configuración |
| Notificaciones | Campana |

Los iconos deberán utilizarse como complemento del texto y no como único mecanismo de comunicación.

**8. Componentes específicos de la solución**

Debido a que la plataforma está orientada específicamente a trabajadores de turnos diurnos y nocturnos, se establecen algunos componentes propios del sistema.

**Registro de trayecto seguro**

Permite iniciar un trayecto, seleccionar un destino y compartir el estado con los contactos de confianza.

**Contactos de confianza**

Permite registrar familiares, parejas o amigos que recibirán notificaciones relacionadas con el trayecto.

**Mapa de servicios cercanos**

Permite visualizar:

- Servicios abiertos según la fecha y hora de consulta, con horarios diurnos, nocturnos o de atención continua.
- Zonas reportadas como inseguras.
- Incidentes registrados.
- Información proporcionada por la comunidad.

**Reporte de incidentes**

Permite registrar situaciones como:

- Robo.
- Acoso.
- Zona peligrosa.
- Mala iluminación.
- Accidente.
- Situación sospechosa.

**Registro de bienestar**

Permite registrar información relacionada con:

- Horas de sueño.
- Descanso.
- Fatiga.
- Hábitos relacionados con el turno diurno o nocturno.

**Comunidad**

Permite a los trabajadores compartir información, experiencias y recomendaciones relacionadas con el trabajo en turnos diurnos y nocturnos.

**Beneficios**

Permite consultar descuentos, servicios y beneficios negociados para los trabajadores de turnos diurnos y nocturnos mediante la suscripción a la plataforma.
## 4.2. Information Architecture.

### 4.2.1. Organization Systems.


Se utilizarán diversos métodos para organizar la información según su relevancia, contexto y frecuencia de uso. La presentación visual de la información se realizará mediante los siguientes sistemas de organización:

**Organización Jerárquica:** Se utilizará principalmente en el tablero principal, donde se priorizará la información relacionada con la seguridad del trabajador. Primero se mostrarán alertas críticas, estado del trayecto y notificaciones importantes; posteriormente se presentarán servicios cercanos disponibles, información de la comunidad y datos relacionados con el bienestar.

**Organización Secuencial:** Se utilizará en los flujos de interacción que requieren seguir una serie de pasos, como el registro de un nuevo usuario, configuración de contactos de confianza, inicio de un trayecto seguro, confirmación de llegada, registro de descanso y reporte de un incidente.

**Organización Matricial:** Se utilizará para comparar información relacionada con servicios cercanos, zonas de riesgo, reportes comunitarios y beneficios disponibles. Este sistema permitirá al usuario visualizar diferentes alternativas y tomar decisiones según criterios como distancia, horario de atención, nivel de seguridad o valoración de otros usuarios.

**Organización por categorías:** Se empleará para agrupar funcionalidades y contenidos relacionados. Por ejemplo, las opciones de seguridad incluirán trayectos, contactos de confianza y reportes de incidentes; mientras que las opciones de bienestar incluirán descanso, sueño y recomendaciones.


### 4.2.2. Labeling Systems.


En la startup, el sistema de etiquetado ha sido diseñado para maximizar la claridad y reducir la carga cognitiva de los usuarios. Todas las etiquetas utilizadas en la navegación, trayectos, mapas, comunidad, bienestar y configuración priorizarán la simplicidad, consistencia semántica y un lenguaje directo, claro y fácil de comprender.

El sistema de etiquetado considera que los usuarios principales pueden tener diferentes niveles de alfabetización digital. Por ello, se evitarán términos técnicos innecesarios y se utilizarán expresiones familiares para los trabajadores de turnos diurnos y nocturnos y sus contactos de confianza.

**Principios clave del sistema de etiquetado:**

Las etiquetas evitarán tecnicismos innecesarios y ambigüedades. Se emplearán términos comunes que puedan ser comprendidos rápidamente por trabajadores, familiares y otros usuarios de la plataforma.

Un mismo concepto siempre se representará con la misma palabra en todos los entornos de la plataforma, incluyendo la aplicación móvil, aplicación web, notificaciones y comunicaciones.

Las etiquetas se limitarán preferentemente a 1-3 palabras, procurando que sean descriptivas, directas y fáciles de identificar.

Las etiquetas relacionadas con situaciones de seguridad tendrán un mayor peso visual y utilizarán colores e iconos de acuerdo con las directrices establecidas en la guía de estilo.

**Etiquetas principales por área**

**Navegación global:** Inicio, Trayecto, Mapa, Comunidad, Bienestar, Beneficios, Perfil.

**Página de inicio:** Mi estado, Mi trayecto, Alertas, Servicios cercanos, Actividad reciente.

**Seguridad y trayectos:** Iniciar trayecto, Finalizar trayecto, Confirmar llegada, Contactos de confianza, Compartir trayecto, Historial.

**Mapa de servicios cercanos:** Servicios abiertos, Zonas de riesgo, Incidentes, Rutas, Cerca de mí.

**Comunidad:** Publicaciones, Reportes, Recomendaciones, Experiencias, Comentarios.

**Bienestar:** Descanso, Sueño, Registro, Historial, Recomendaciones.

**Beneficios:** Beneficios disponibles, Descuentos, Seguro, Suscripción.

**Acciones del usuario:** Crear cuenta, Iniciar sesión, Iniciar trayecto, Confirmar llegada, Reportar incidente, Compartir ubicación, Añadir contacto, Registrar descanso, Ver beneficio, Cerrar sesión.

**Asociaciones entre etiquetas**

Algunas etiquetas se utilizarán en conjunto para facilitar la comprensión del estado del sistema:

- "Trayecto seguro"
- "Contacto de confianza"
- "Posible incidente"
- "Zona de riesgo"
- "Servicio abierto"
- "Llegada confirmada"
- "Descanso insuficiente"
- "Beneficio disponible"
- "Reporte verificado"
### 4.2.3. SEO Tags and Meta Tags
**Página de inicio**
**Título:** Seguridad y bienestar para trabajadores de turnos diurnos y nocturnos.

**Meta Descripción:** Plataforma digital para trabajadores de turnos diurnos y nocturnos que ofrece seguimiento de trayectos, contactos de confianza, información sobre servicios abiertos, reportes comunitarios y herramientas de bienestar.

**Meta Palabras clave:** trabajadores de turnos diurnos y nocturnos, seguridad diurna y nocturna, bienestar laboral, seguridad personal, trayecto seguro, servicios cercanos, comunidad de trabajadores, Lima.

**Autor de la metaetiqueta:** [Noxway]

**Aplicación web**

**Título:** Seguridad y bienestar durante tu jornada laboral.

**Meta Descripción:** Gestiona tus trayectos diurnos y nocturnos, comparte tu estado con contactos de confianza, consulta zonas de riesgo y encuentra servicios disponibles durante el día y la noche desde una sola plataforma.

**Meta Palabras clave:** seguridad para trabajadores de turnos diurnos y nocturnos, seguimiento de trayectos, contactos de confianza, mapa de servicios cercanos, zonas de riesgo, servicios abiertos, bienestar laboral.

**Autor de la metaetiqueta:** [Noxway]

### 4.2.4. Searching Systems.
Las decisiones de búsqueda en Noxway están orientadas a garantizar que los usuarios encuentren rápidamente información relevante sobre servicios cercanos, zonas de riesgo, rutas, reportes comunitarios y beneficios, evitando que tengan que revisar grandes cantidades de información.

**Opciones de búsqueda**

**Barra de búsqueda**

Permite ingresar términos específicos como nombre de un servicio, ubicación, tipo de establecimiento, zona, incidente o beneficio.

Los resultados podrán actualizarse conforme el usuario escribe, mostrando las opciones más relevantes según su ubicación y los criterios seleccionados.

**Categorías**

- Restaurantes abiertos
- Farmacias
- Tiendas
- Centros de salud
- Transporte
- Zonas de riesgo
- Incidentes
- Beneficios
- Servicios para trabajadores

**Etiquetas populares**

- Servicio abierto
- Zona segura
- Zona de riesgo
- Incidente reportado
- Ruta recomendada
- Beneficio disponible

**Filtros disponibles**

**Por tipo de servicio:** Restaurantes, farmacias, tiendas, centros de salud, transporte y otros servicios disponibles durante el día y la noche.

**Por distancia:** Cerca de mí, menos de 1 km, menos de 3 km, menos de 5 km.

**Por horario:** Abierto ahora, atención 24 horas, apertura próxima. La disponibilidad se determina según el horario de atención y la zona horaria del establecimiento; un servicio no necesita operar las 24 horas para aparecer en el mapa. Los intervalos que cruzan medianoche se consideran hasta su cierre del día siguiente.

**Por seguridad:** Ruta recomendada, zona segura, zona de precaución, zona de riesgo.

**Por valoración:** Mejor valorados, más recientes y más reportados.

**Por fecha:** Reportes recientes, últimos 7 días y últimos 30 días.

**Apariencia de los datos después de la búsqueda**

**Listados de resultados:** Incluyen nombre del lugar o reporte, ubicación, distancia, horario de atención y valoración cuando corresponda.

**Resumen y descripción:** Cada resultado presenta información relevante, como descripción del servicio, reportes recientes, nivel de seguridad o comentarios de la comunidad.

**Ordenación y filtros aplicados:** El usuario podrá ordenar los resultados por cercanía, relevancia, valoración o fecha. Los filtros activos se mostrarán claramente en la parte superior de los resultados.

**Información comunitaria:** Los resultados relacionados con seguridad podrán incluir reportes y valoraciones realizadas por otros trabajadores de turnos diurnos y nocturnos, permitiendo conocer experiencias recientes de la zona.

**Ubicación:** Los resultados podrán visualizarse tanto en formato de lista como en el mapa, facilitando la identificación de servicios y zonas relevantes cercanas al usuario.

### 4.2.5. Navigation Systems.
La estructura de navegación de la startup está diseñada para ofrecer una experiencia de usuario fluida y sencilla, asegurando un acceso rápido a las funcionalidades relacionadas con seguridad, trayectos, comunidad y bienestar.

La navegación prioriza especialmente las funciones que pueden ser utilizadas durante un desplazamiento diurno o nocturno, reduciendo la cantidad de pasos necesarios para acceder a información importante.

**Páginas principales**

**Inicio:** Dashboard principal con el estado del usuario, trayecto activo, alertas importantes, servicios cercanos y accesos rápidos.

**Mi trayecto:** Permite iniciar, consultar y finalizar trayectos, además de gestionar la información compartida con los contactos de confianza.

**Mapa:** Permite visualizar servicios abiertos según el horario de consulta, zonas de riesgo, incidentes reportados y otros puntos relevantes.

**Comunidad:** Espacio donde los trabajadores pueden consultar y compartir experiencias, reportes, recomendaciones e información relacionada con el trabajo en turnos diurnos y nocturnos.

**Bienestar:** Sección destinada al registro de descanso, sueño y otros indicadores relacionados con el bienestar del trabajador de turno diurno o nocturno.

**Beneficios:** Permite consultar descuentos, servicios y beneficios disponibles para los usuarios suscritos.

**Perfil:** Permite administrar información personal, contactos de confianza, preferencias, privacidad y configuración de la cuenta.

**Opciones de usuario**

**Iniciar sesión:** Acceso para usuarios registrados.

**Registrarme:** Registro de nuevos trabajadores y contactos de confianza.

**Perfil:** Configuración y gestión de información personal.

**Contactos de confianza:** Administración de familiares, parejas o amigos autorizados para recibir información sobre los trayectos.

**Configuración:** Gestión de preferencias, privacidad, notificaciones y permisos de ubicación.

**Cerrar sesión:** Salida segura de la cuenta.

**Búsqueda y navegación**

**Barra de búsqueda:** Disponible en las secciones donde sea necesario localizar servicios, lugares, reportes o beneficios.

**Categorías:** Permiten filtrar rápidamente la información por tipo de servicio, incidente o contenido.

**Explorar:** Facilita el acceso a módulos principales como Mapa, Comunidad, Bienestar y Beneficios.

**Mapa:** Permite navegar visualmente por la ubicación del usuario y consultar información relevante del entorno del trayecto.

**Navegación de seguridad**

Las funciones relacionadas con seguridad tendrán acceso prioritario desde la interfaz.

El usuario podrá acceder rápidamente a:

- Iniciar trayecto.
- Compartir trayecto.
- Confirmar llegada.
- Consultar contactos de confianza.
- Reportar un incidente.
- Consultar zonas de riesgo.
- Activar una alerta de emergencia.

Estas funciones tendrán una ubicación consistente para facilitar su identificación y reducir el tiempo de interacción en situaciones críticas.

**Marca e identidad**

El nombre y logotipo de la startup estarán visibles en las principales vistas de la plataforma, asegurando coherencia de marca.

Los colores, tipografías, iconografía y componentes visuales seguirán los lineamientos definidos en la guía de estilo, reforzando los conceptos de seguridad, confianza, bienestar y comunidad.

La navegación mantendrá una estructura consistente en todas las vistas para que los usuarios puedan identificar rápidamente dónde se encuentran y cómo regresar a las funciones principales

## 4.3. Landing Page UI Design. 

### 4.3.1. Landing Page Wireframe. 
El wireframe de la Landing Page de Noxway fue elaborado en un nivel de fidelidad media para definir la distribución espacial, la jerarquía de los contenidos, la cuadrícula de diseño y los flujos de interacción del usuario, prescindiendo deliberadamente de ornamentos estéticos, fotografía o colores finales. Esto permitió concentrar la evaluación en la usabilidad estructural, el orden lógico del mensaje y los puntos de contacto para la conversión.
La estructura alámbrica de la página está organizada en diez secciones continuas que conducen al usuario a través de un embudo informativo coherente:


**Header:** Contiene el logotipo de la marca (Noxway by Noctiva), un menú de navegación principal con enlaces de anclaje rápido a los bloques clave, un selector de idioma bilingüe (EN/ES) y una llamada a la acción principal de registro orientada al ingreso directo a la plataforma. 


**Hero Section:** Presenta la propuesta de valor principal de forma contundente mediante un titular de alto impacto y un subtítulo explicativo enfocado en el acompañamiento y seguridad de trayectos diurnos y nocturnos. Integra un llamado a la acción dual segmentado (Protect My Commute para el trabajador de turno diurno o nocturno e I'm a Trusted Contact para acompañantes o familiares), complementado por un indicador visual de desplazamiento. 


**Protocolo:** Desglosa visualmente el flujo de funcionamiento operativo de la solución en cuatro fases consecutivas y numeradas: vinculación del círculo de confianza, inicio y estimación del trayecto de ida o regreso del trabajo, en horario diurno o nocturno, monitoreo pasivo de anomalías en segundo plano y confirmación unificada de llegada segura.


**Ecosistema:** Organiza en una cuadrícula modular las cuatro capacidades tecnológicas y de bienestar clave que componen el servicio: Route & Commute Check-In (monitoreo de trayecto), Community Services Map (geolocalización de farmacias, grifos y puntos de atención disponibles según la fecha y hora de consulta), Smart Alerts & Companion View (detección de desvíos y enlaces cifrados para familiares) y Rest Log & Collective Benefits (higiene del sueño circadiano y convenios).


**Testimonios:** Dispone de una interfaz basada en pestañas interactivas para reproducir dos piezas audiovisuales estratégicas: el recorrido demostrativo funcional del producto (About the Product) y el video de sustentación de ingeniería, retrospectiva ágil y equipo (About the Team) 


**Planes de Suscripción:** Expone un modelo comparativo horizontal tipo ledger con alternador de facturación mensual y anual (con descuento visible). Contrasta con claridad los niveles de cobertura: Plan Esencial (gratuito), Plan Centinela Pro (monitoreo prioritario recomendado) y Plan Familiar/Cuadrilla (protección multiusuario colaborativa), finalizando con una barra de resumen dinámico para confirmar la selección. 


**Contacto(Formulario):** Contenedor asimétrico de conversión final que aloja un formulario lineal y accesible compuesto por campos mínimos estructurados (nombre, canal de contacto directo y perfil de rol), asociado al plan seleccionado para agilizar la captación de usuarios tempranos. 


**Footer:** Cierra la arquitectura de la página con la identidad corporativa, enlaces a redes sociales oficiales, mapa de navegación interno, indicador de estado operativo en tiempo real del servicio en Lima y un acceso directo e inequívoco a los Términos de Servicio y Código de Ética profesional (alineado a los estándares ACM/IEEE y CIP). 

<img src="resources/imgs/LandingPage-Wireframe.png"
     alt="Landing-Wireframe"
     style="">

*Nota:* Elaboración propia. Elaborado en: https://www.figma.com/design/kARtlqhljeRK63rGx1Dmea/Sin-t%C3%ADtulo?node-id=0-1


### 4.3.2. Landing Page Mock-up. 

<img src="resources/imgs/LandingPage-Mockup.png"
     alt="Landing-Wireframe"
     style="">
Elaborado en: https://www.figma.com/design/kARtlqhljeRK63rGx1Dmea/Sin-t%C3%ADtulo?node-id=0-1

## 4.4. Web Applications UX/UI Design. 

### 4.4.1. Web Applications Wireframes.
Los wireframes de las aplicaciones web de **Noxway** muestran cómo se estructuran las pantallas y dónde se ubican los elementos de navegación para cada uno de los roles clave del sistema: el **trabajador de turno diurno o nocturno** y su **contacto de confianza**. Estos esquemas visuales, que se centran en la funcionalidad, la accesibilidad con iluminación diurna o nocturna y la facilidad de uso bajo condiciones de fatiga o urgencia, guían el diseño final. Su objetivo es asegurar que la aplicación sea intuitiva y que la interacción del usuario —desde iniciar un trayecto seguro y consultar el mapa de servicios cercanos según su horario de atención hasta monitorear un desplazamiento en vivo o coordinar auxilio distrital— sea fluida, rápida y eficiente, lo que ayuda a diseñadores y desarrolladores a optimizar la disposición de cada componente.

<img src="resources/imgs/AppWeb-Wireframe1.png"
     alt="AppWeb-Wireframe1"
     style="">

<img src="resources/imgs/AppWeb-Wireframe2.png"
     alt="AppWeb-Wireframe2"
     style="">

<img src="resources/imgs/AppWeb-Wireframe3.png"
     alt="AppWeb-Wireframe3"
     style="">

<img src="resources/imgs/AppWeb-Wireframe4.png"
     alt="AppWeb-Wireframe4"
     style="">

<img src="resources/imgs/AppWeb-Wireframe5.png"
     alt="AppWeb-Wireframe5"
     style="">

<img src="resources/imgs/AppWeb-Wireframe6.png"
     alt="AppWeb-Wireframe6"
     style="">

<img src="resources/imgs/AppWeb-Wireframe7.png"
     alt="AppWeb-Wireframe7"
     style="">

<img src="resources/imgs/AppWeb-Wireframe8.png"
     alt="AppWeb-Wireframe8"
     style="">

<img src="resources/imgs/AppWeb-Wireframe9.png"
     alt="AppWeb-Wireframe9"
     style="">

<img src="resources/imgs/AppWeb-Wireframe10.png"
     alt="AppWeb-Wireframe10"
     style="">

<img src="resources/imgs/AppWeb-Wireframe11.png"
     alt="AppWeb-Wireframe11"
     style="">

<img src="resources/imgs/AppWeb-Wireframe12.png"
     alt="AppWeb-Wireframe12"
     style="">

<img src="resources/imgs/AppWeb-Wireframe13.png"
     alt="AppWeb-Wireframe13"
     style="">

<img src="resources/imgs/AppWeb-Wireframe14.png"
     alt="AppWeb-Wireframe14"
     style="">

<img src="resources/imgs/AppWeb-Wireframe15.png"
     alt="AppWeb-Wireframe15"
     style="">

<img src="resources/imgs/AppWeb-Wireframe16.png"
     alt="AppWeb-Wireframe16"
     style="">

<img src="resources/imgs/AppWeb-Wireframe17.png"
     alt="AppWeb-Wireframe17"
     style="">

<img src="resources/imgs/AppWeb-Wireframe18.png"
     alt="AppWeb-Wireframe18"
     style=""> 

### 4.4.2. Web Applications Wireflow Diagrams.
Los diagramas de wireflow para aplicaciones web son esquemas que integran la estructura visual de las pantallas (wireframes) con la lógica de transición de los diagramas de flujo. Esta herramienta articula la arquitectura de información y las rutas de navegación del sistema, ofreciendo una perspectiva integral sobre cómo el usuario interactúa y se desplaza a través de los distintos escenarios de la interfaz. 

<img src="resources/imgs/Wireflow Diagrams.png"
     alt="AppWeb-Wireframe18"
     style=""> 
     
### 4.4.3. Web Applications Mock-ups.

<img src="resources/imgs/AppWeb-Mockup1.png"
     alt="AppWeb-Mockup1"
     style="">

<img src="resources/imgs/AppWeb-Mockup2.png"
     alt="AppWeb-Mockup2"
     style="">

<img src="resources/imgs/AppWeb-Mockup3.png"
     alt="AppWeb-Mockup3"
     style="">

<img src="resources/imgs/AppWeb-Mockup4.png"
     alt="AppWeb-Mockup4"
     style="">

<img src="resources/imgs/AppWeb-Mockup5.png"
     alt="AppWeb-Mockup5"
     style="">

<img src="resources/imgs/AppWeb-Mockup6.png"
     alt="AppWeb-Mockup6"
     style="">

<img src="resources/imgs/AppWeb-Mockup7.png"
     alt="AppWeb-Mockup7"
     style="">

<img src="resources/imgs/AppWeb-Mockup8.png"
     alt="AppWeb-Mockup8"
     style="">

<img src="resources/imgs/AppWeb-Mockup9.png"
     alt="AppWeb-Mockup9"
     style="">

<img src="resources/imgs/AppWeb-Mockup10.png"
     alt="AppWeb-Mockup10"
     style="">

<img src="resources/imgs/AppWeb-Mockup11.png"
     alt="AppWeb-Mockup11"
     style="">

<img src="resources/imgs/AppWeb-Mockup12.png"
     alt="AppWeb-Mockup12"
     style="">

<img src="resources/imgs/AppWeb-Mockup13.png"
     alt="AppWeb-Mockup13"
     style="">

<img src="resources/imgs/AppWeb-Mockup14.png"
     alt="AppWeb-Mockup14"
     style="">

<img src="resources/imgs/AppWeb-Mockup15.png"
     alt="AppWeb-Mockup15"
     style="">

<img src="resources/imgs/AppWeb-Mockup16.png"
     alt="AppWeb-Mockup16"
     style="">

<img src="resources/imgs/AppWeb-Mockup17.png"
     alt="AppWeb-Mockup17"
     style="">

<img src="resources/imgs/AppWeb-Mockup18.png"
     alt="AppWeb-Mockup18"
     style="">

Elaborado en: https://www.figma.com/design/kARtlqhljeRK63rGx1Dmea/Sin-t%C3%ADtulo?node-id=1-2


### 4.4.4. Web Applications User Flow Diagrams. 
El diagrama de flujo de usuario (User Flow Diagram) es una representación visual de los pasos que un usuario sigue al interactuar con una aplicación o sitio web. Muestra la secuencia de acciones que el usuario realiza para completar una tarea o meta específica (User Goal), lo que permite identificar posibles puntos de fricción, reducir la carga cognitiva en distintos horarios y condiciones de fatiga y optimizar la experiencia integral del usuario.
Para la versión móvil de Noxway, los flujos de usuario fueron derivados directamente de la arquitectura de pantallas de la aplicación web, adaptando los componentes a un factor de forma compacto de una sola columna y áreas táctiles ergonómicas. A continuación, se detallan y grafican los tres User Goals principales del sistema:

<img src="resources/imgs/User-Flow-Diagrams-1.png"
     alt="User Flow Diagrams 1"
     style="">

<img src="resources/imgs/User-Flow-Diagrams-2.png"
     alt="User Flow Diagrams 2"
     style="">

<img src="resources/imgs/User-Flow-Diagrams-3.png"
     alt="User Flow Diagrams 3"
     style="">


## 4.5. Web Applications Prototyping. 

Prototipo de la aplicacion web Noxway en figma: [Prototipo Noxway](https://www.figma.com/design/kARtlqhljeRK63rGx1Dmea/Sin-t%C3%ADtulo?node-id=1-2)

<img src="resources/imgs/AppWeb-Mockup10.png"
     alt="AppWeb-Mockup10"
     style="">

Video del flujo del prototipo: [FLUJO PROTOTIPO NOXWAY](https://upcedupe-my.sharepoint.com/:v:/g/personal/u202421065_upc_edu_pe/IQAYZZW6h9uES4m-8cKkzqzdAS0EJflx7OEtdVV1vr92oU4?e=fZUsN5)


## 4.6. Domain-Driven Software Architecture
### 4.6.1. Design-Level EventStorming
En esta sección se presenta la arquitectura de software de Noxway desde el enfoque de Domain-Driven Design, tomando como base el Big Picture Event Storming desarrollado previamente. El actor `Worker` representa al trabajador de turno diurno o nocturno; ambos utilizan los mismos contextos de dominio para gestionar trayectos, contactos, servicios, descanso y beneficios.

**Identity & Network Management**
<br>
<br>
<img src="resources/imgs/management.png"
     alt="eventstorming"
     style="">
<br>
<br>
**Safe Commute & Incident Mangement**
<br>
<br>
<img src="resources/imgs/safe-commute.png"
     alt="eventstorming"
     style="">
<br>
<br>
**Sleep Health & Wellnes**
<br>
<br>
<img src="resources/imgs/sleep-health.png"
     alt="eventstorming"
     style="">
<br>
<br>
**Community Intelligence**
<br>
<br>
<img src="resources/imgs/community.png"
     alt="eventstorming"
     style="">
<br>
<br>
**Subscriptions & Collective Benefits**
<br>
<br>
<img src="resources/imgs/subscription.png"
     alt="eventstorming"
     style="">
<br>
<br>
**Moderation & Governance**
<br>
<br>
<img src="resources/imgs/modera.png"
     alt="eventstorming"
     style="">

Miro: https://miro.com/app/board/uXjVGa9f9SI=/?share_link_id=254891487404

## 4.6.2. Software Architecture Context Diagram

El Context Diagram representa a Noxway como un único sistema de software y muestra a los principales actores y sistemas externos con los que interactúa. Los actores considerados son Worker, Trusted Contact y Community Moderator, de acuerdo con las interacciones principales representadas en la solución. Esta separación permite reflejar las responsabilidades relacionadas con el monitoreo de trayectos, la supervisión en vivo mediante el Companion View y la moderación del mapa comunitario.

Como sistemas externos se consideran Payment Gateway, Email Service, Push & SMS Service y Mapping & Geolocation Service. El Payment Gateway procesa los pagos asociados a las suscripciones de los planes (Centinela Pro, Cuadrilla Familiar); el Email Service soporta recuperación de contraseña y comunicaciones transaccionales; el Push & SMS Service suministra la infraestructura crítica para el envío de alertas de emergencia; y el Mapping Service provee la telemetría y geocodificación utilizada durante el monitoreo del trabajador.

C4 System Context Diagram de Noxway.

<img src="resources/imgs/context.png"
     alt="contextdiagram"
     style="">

## 4.6.3. Software Architecture Container Diagrams

La solución se distribuye en cinco containers principales: Landing Page, Mobile Application, Web Application, RESTful API y Relational Database. La Landing Page utiliza React y Next.js para presentar el modelo de negocio, el protocolo de acompañamiento y captar registros. La Mobile Application, construida con Flutter y Dart, proporciona la experiencia principal en ruta para el trabajador de turno diurno o nocturno. La Web Application utiliza React y TypeScript para proporcionar las experiencias autenticadas del Companion Portal y el panel de moderación. El RESTful API utiliza Node.js y Express para exponer servicios, aplicar reglas de negocio automáticas de incidentes y coordinar persistencia e integraciones. La información relacional y espacial se almacena en PostgreSQL.

Los CTA de la Landing Page redirigen hacia el flujo de registro centralizado. Tanto la Mobile App como la Web Application se comunican con el RESTful API mediante HTTPS y JSON. El RESTful API es el único container que accede a la base de datos y a los servicios externos.

C4 Container Diagram de Noxway.

<img src="resources/imgs/container.png"
     alt="containerdiagram"
     style="">

## 4.6.4. Software Architecture Components Diagrams

**Landing Page Components**
La Landing Page se descompone en Hero & Protocol Section, Ecosystem & Features, Subscription Plans View y Registration Funnel. Estas secciones exponen visualmente el flujo de cuatro pasos (Vincular, Iniciar, Monitorear, Confirmar) y las capacidades tecnológicas del sistema. El Registration Funnel permite captar datos iniciales y redirigir a los visitantes hacia la experiencia correspondiente (Worker o Contact) en la Web Application, comunicándose directamente con el RESTful API.

C4 Component Diagram - Landing Page.

<img src="resources/imgs/landingdiagram.png"
     alt="componentdiagram"
     style="">
     
     **Web Application Components**

La Web Application separa el Auth & Onboarding Module, Worker Portal, Companion Portal, Active Commute Tracker, Community Services Map, Sleep & Wellness Log y Benefits & Subscriptions. Todas estas experiencias utilizan llamadas centralizadas y comparten componentes interactivos, manteniendo una única vía de comunicación con el RESTful API para garantizar la sincronización en tiempo real del estado de los trayectos.

C4 Component Diagram - Web Application.

<img src="resources/imgs/web.png"
     alt="componentdiagram"
     style="">

**RESTful API Components**

El RESTful API organiza sus componentes principales de acuerdo con los Bounded Contexts identificados en el Design-Level EventStorming: Account & Auth Controller, Trust Network Controller, Commute & Check-In Controller, Incident & Alert Manager, Community Map Service, Sleep Wellness Service, Subscription Controller y Moderation Controller.

Account & Auth Controller y Trust Network API concentran el registro, autenticación y gestión de vínculos. Commute Controller y el Incident Manager en segundo plano gestionan la telemetría, evaluación de tolerancia y disparo de alertas. Community Map Service procesa consultas espaciales de locales y zonas de riesgo, considerando la fecha, hora y zona horaria al consultar la disponibilidad de los establecimientos. Sleep Wellness Service administra los registros de descanso diurno o nocturno y sugerencias de fatiga. Subscription Controller gestiona planes, pagos y convenios colectivos.

Persistence Layer concentra el acceso hacia PostgreSQL y External Integrations encapsula la comunicación con Payment Gateway, Email Service, SMS/Push Service y Map APIs.

C4 Component Diagram - RESTful API.

<img src="resources/imgs/api.png"
     alt="componentdiagram"
     style="">

**Relational Database Components**

El container Relational Database se organiza mediante separación lógica de datos. Los esquemas `users_network_schema`, `commute_incident_schema`, `community_data_schema`, `wellness_schema`, `subscription_schema` y `moderation_schema` corresponden a los Bounded Contexts identificados. 

Esta organización permite conservar límites de responsabilidad a nivel de persistencia, separando datos transaccionales críticos (como la telemetría) de datos espaciales y de facturación, aun cuando PostgreSQL sea desplegado inicialmente como una única instancia.

C4 Component Diagram - Relational Database.

<img src="resources/imgs/database.png"
     alt="componentdiagram"
     style="">

## 4.7. Software Object-Oriented Design

El diseño orientado a objetos se organiza de acuerdo con los Bounded Contexts identificados en el Design-Level EventStorming y con los módulos de soporte necesarios para mantener trazabilidad con las User Stories del Capítulo III. Los nombres de clases, atributos, métodos e interfaces se mantienen en inglés y se especifican relaciones, multiplicidades y visibilidad de miembros.

## 4.7.1. Class Diagrams

**Identity & Network Management**

El modelo concentra la abstracción `User`, de la cual heredan los roles específicos `Worker` y `TrustedContact`. `TrustLink` modela la clase de asociación que representa el vínculo de acompañamiento seguro entre un trabajador y su contacto de confianza, encapsulando su estado y vigencia.

Class Diagram - Identity & Network Management.

<img src="resources/imgs/ia-m.png"
     style="">

**Safe Commute & Incident Management**

`Commute` representa el núcleo del ciclo de vida del trayecto y se relaciona fuertemente con `TelemetryPing` mediante composición para registrar la ubicación y velocidad. `SafetyIncident` modela las situaciones de riesgo o demoras generadas durante el trayecto, interactuando con `NotificationPreference` para escalar las alertas a los canales correspondientes. `startTime` y `estimatedArrivalTime` incluyen fecha y hora: el trayecto puede iniciarse de día o de noche y continuar al día siguiente sin cerrarse a medianoche. La evaluación del margen de tolerancia depende del tiempo transcurrido y del estado del trayecto, no del turno laboral.

Class Diagram - Safe Commute Incident Management.

<img src="resources/imgs/incide.png"
     alt="Class Diagram - Safe Commute and Incident Management"
     style="">

**Community Intelligence**

`CommunityMap` actúa como la entidad agregadora para la consulta espacial. `ServicePoint` representa los servicios verificados con atención diurna, nocturna o continua, sin restringirlos a establecimientos de 24 horas. Cada servicio conserva su zona horaria y sus intervalos semanales de atención mediante el objeto de valor `ServiceOpeningInterval`, para determinar si está abierto en el momento consultado. `RiskZone` modela los puntos de peligro reportados y `RouteRating` registra la calificación de seguridad asignada a las rutas una vez finalizado el desplazamiento.

Class Diagram - Community Intelligence.

```mermaid
classDiagram
    direction TB
    class CommunityMap {
        <<AggregateRoot>>
        -UUID mapId
        -String currentRegion
        +loadActiveServices(Float radius, DateTime referenceTime) List~ServicePoint~
        +loadRiskZones(Float radius) List~RiskZone~
        +registerServicePoint(ServicePoint newService) void
        +reportRiskZone(RiskZone newZone) void
    }
    class ServicePoint {
        <<Entity>>
        -UUID serviceId
        -String name
        -ServiceType type
        -Float latitude
        -Float longitude
        -Integer trustScore
        -Boolean isVerified
        -String timeZone
        +upvote() void
        +downvote() void
        +verifyStatus() Boolean
        +isOpenAt(DateTime referenceTime) Boolean
    }
    class ServiceOpeningInterval {
        <<ValueObject>>
        -Integer dayOfWeek
        -LocalTime opensAt
        -LocalTime closesAt
        -Boolean closesNextDay
        -Boolean is24Hours
    }
    class RiskZone {
        <<Entity>>
        -UUID zoneId
        -String description
        -RiskLevel riskLevel
        -Float latitude
        -Float longitude
        -DateTime reportedAt
        +confirmRisk() void
        +resolveRisk() void
    }
    class RouteRating {
        <<Entity>>
        -UUID ratingId
        -UUID commuteId
        -Integer score
        -String comments
        -DateTime createdAt
        +submitRating() void
    }
    class ServiceType {
        <<enumeration>>
        PHARMACY
        GAS_STATION
        HOSPITAL
        POLICE_STATION
    }
    class RiskLevel {
        <<enumeration>>
        LOW
        MEDIUM
        HIGH
    }
    class ServicePointReported {
        <<DomainEvent>>
        +UUID serviceId
        +UUID reportedBy
        +DateTime timestamp
    }
    class DangerSpotReported {
        <<DomainEvent>>
        +UUID zoneId
        +String riskLevel
        +DateTime timestamp
    }
    class RouteSafetyRated {
        <<DomainEvent>>
        +UUID commuteId
        +Integer score
        +DateTime timestamp
    }
    CommunityMap "1" --> "0..*" ServicePoint : displays
    CommunityMap "1" --> "0..*" RiskZone : displays
    CommunityMap "1" o-- "0..*" RouteRating : aggregates
    ServicePoint "1" *-- "1..*" ServiceOpeningInterval : opening hours
    ServicePoint --> ServiceType : type
    RiskZone --> RiskLevel : risk level
    CommunityMap ..> ServicePointReported : generates
    CommunityMap ..> DangerSpotReported : generates
    CommunityMap ..> RouteSafetyRated : generates
```

Los horarios se expresan en la zona horaria del establecimiento, inicialmente `America/Lima`. `dayOfWeek` identifica el día de apertura (1 = lunes, 7 = domingo); se admiten varios intervalos por día y la ausencia de intervalos indica cierre. `closesNextDay` permite representar, por ejemplo, una apertura del lunes a las 22:00 con cierre el martes a las 06:00. `is24Hours` identifica atención continua durante ese día. Las consultas consideran también los intervalos iniciados el día anterior; no se deduce disponibilidad únicamente de la categoría o del turno del trabajador.

**Sleep Health & Wellness**

`SleepLog` representa el registro agregado diario de metas y déficits de sueño, mientras que `RestSession` registra periodos individuales de descanso diurno o nocturno, continuos o fragmentados. Sus valores `startTime` y `endTime` incluyen fecha y hora y permiten que una sesión termine al día siguiente; la duración se calcula entre ambos instantes y no se reinicia a medianoche. `HygieneSuggestion` modela las recomendaciones emitidas por el sistema en función del nivel de fatiga detectado en el trabajador de turno diurno o nocturno.

Class Diagram - Sleep Health Wellness.

<img src="resources/imgs/sleep.png"
     style="">

**Subscriptions & Collective Benefits**

`Subscription` representa el plan (Esencial, Centinela Pro, etc.) activo de un trabajador, el cual genera registros en `PaymentTransaction` por su facturación recurrente. `CollectiveBenefit` modela los seguros y convenios habilitados, mientras que `ReferralCode` administra la lógica del programa de crecimiento por referidos.

Class Diagram - Subscriptions Collective Benefits.

<img src="resources/imgs/subs.png"
     style="">

**Moderation & Governance**

`ModerationQueue` representa la bandeja de tareas de los moderadores del sistema. `CommunityReport` modela de forma abstracta los elementos enviados por los usuarios y `ModerationAction` mantiene el registro auditable de las decisiones (aprobación o rechazo) aplicadas sobre dichos reportes.

Class Diagram - Moderation Governance.

<img src="resources/imgs/moderation.png"
     style="">

---

## 4.8. Database Design

El diseño de base de datos utiliza PostgreSQL como DBMS relacional y conserva la separación lógica establecida por los Bounded Contexts identificados en el Design-Level EventStorming. Se ha considerado el soporte de PostGIS para los esquemas que requieren consultas espaciales (latitud y longitud).

Se utiliza lowercase_snake_case para tablas y columnas, UUID para identificadores, TIMESTAMPTZ para instantes que representan un momento real en el tiempo, DATE para fechas sin componente horario y NUMERIC para valores exactos. Los diagramas especifican claves primarias, claves foráneas internas, restricciones de unicidad, nulabilidad y reglas CHECK necesarias para mantener la integridad de los datos.

Las relaciones internas de cada Bounded Context se representan mediante claves foráneas. Cuando una entidad necesita identificar información administrada por otro contexto, se conserva únicamente el identificador como referencia lógica, evitando introducir dependencias de persistencia que mezclen responsabilidades de dominio.

### 4.8.1. Database Diagrams

**Identity & Network Management**

El modelo persiste las cuentas en `users` y su información demográfica en `user_profiles`. El control de acceso se maneja a través de `roles` y `user_roles`. Los dispositivos móviles se registran en `user_devices` para posibilitar el envío de notificaciones push. La creación de la red de acompañamiento utiliza `trust_invitations` para gestionar los tokens enviados externamente y `trust_links` para consolidar el vínculo aceptado.

Database Diagram - Identity & Network Management.

<img src="resources/imgs/iden.png"
     style="">

**Safe Commute & Incident Management**

El modelo persiste los trayectos en la tabla `commutes`, complementada por `commute_checkpoints` para trazar los hitos de la ruta. `start_time` y `estimated_arrival` conservan la fecha y hora completas para desplazamientos diurnos o nocturnos que pueden cruzar medianoche; la llegada estimada debe ser posterior al inicio. La telemetría de alto volumen se aísla en `telemetry_pings`. Las anomalías generan registros en `safety_incidents`, los cuales mantienen su ciclo de vida y disparan registros de auditoría de notificaciones en `incident_alerts`.

Database Diagram - Safe Commute Incident Management.

<img src="resources/imgs/comu.png"
     style="">

**Community Intelligence**

El modelo persiste ubicaciones geoespaciales como `services` y `risk_zones`. `services.time_zone` y la tabla `service_opening_intervals` permiten consultar la disponibilidad de establecimientos con atención diurna, nocturna o continua. Para garantizar la confiabilidad comunitaria, se emplean las tablas transaccionales `service_validations` y `risk_zone_confirmations`, que evitan votos duplicados por parte del mismo trabajador. Las encuestas de los desplazamientos se almacenan en `route_ratings`. Esta ampliación corresponde al diseño de persistencia propuesto; su implementación se documentará con las evidencias del desarrollo.

Database Diagram - Community Intelligence.

```mermaid
erDiagram
    services ||--|{ service_opening_intervals : defines
    services ||--o{ service_validations : receives
    risk_zones ||--o{ risk_zone_confirmations : receives
    services {
        uuid id PK
        uuid reported_by
        varchar name
        varchar category
        numeric latitude
        numeric longitude
        int verification_score
        varchar status
        varchar time_zone
        timestamptz created_at
        timestamptz updated_at
    }
    service_opening_intervals {
        uuid id PK
        uuid service_id FK
        smallint day_of_week
        time opens_at
        time closes_at
        boolean closes_next_day
        boolean is_24_hours
    }
    service_validations {
        uuid id PK
        uuid service_id FK
        uuid worker_id
        boolean is_positive
        timestamptz created_at
    }
    risk_zones {
        uuid id PK
        uuid reported_by
        varchar risk_category
        text description
        numeric latitude
        numeric longitude
        varchar status
        timestamptz reported_at
        timestamptz expires_at "nullable"
    }
    risk_zone_confirmations {
        uuid id PK
        uuid risk_zone_id FK
        uuid worker_id
        boolean is_confirmed
        timestamptz created_at
    }
    route_ratings {
        uuid id PK
        uuid commute_id
        uuid worker_id
        int safety_score
        varchar lighting_quality "nullable"
        text comments "nullable"
        timestamptz created_at
    }
```

`service_opening_intervals` traduce el objeto de valor `ServiceOpeningInterval` a persistencia. Sus columnas son obligatorias; `day_of_week` está entre 1 y 7 y `service_id` referencia a `services.id`. Un intervalo normal exige `closes_at > opens_at`; uno que cruza medianoche exige `closes_next_day = true` y `closes_at < opens_at`. Para atención continua se utiliza `is_24_hours = true`, con ambas horas en `00:00` y `closes_next_day = true`. No se admiten intervalos superpuestos del mismo servicio, incluso al cruzar el límite semanal, ni intervalos adicionales en un día cubierto por atención continua. `time_zone` es obligatoria y contiene una zona IANA válida, inicialmente `America/Lima`.

Se mantienen las restricciones `UNIQUE(service_id, worker_id)` en `service_validations` y `UNIQUE(risk_zone_id, worker_id)` en `risk_zone_confirmations`. Los identificadores de trabajadores y trayectos son referencias lógicas a otros contextos. La búsqueda “Abierto ahora” combina el horario semanal con la fecha y hora consultadas en la zona del servicio, incluyendo intervalos iniciados el día anterior.

**Sleep Health & Wellness**

El modelo organiza la higiene del sueño separando el consolidado diario (`daily_sleep_logs`) de los periodos de descanso diurno o nocturno, continuos o fraccionados (`sleep_sessions`). Los campos `start_time` y `end_time` incluyen fecha y hora y admiten fechas distintas, siempre que el fin sea posterior al inicio. Para evitar duplicar minutos al cruzar medianoche, el consolidado asigna cada sesión a la fecha local de inicio y conserva su duración completa. El sistema almacena en `hygiene_suggestions` las alertas emitidas por déficit de horas, las cuales se vinculan lógicamente al usuario que las recibe.

Database Diagram - Sleep Health Wellness.

<img src="resources/imgs/health.png"
     style="">

**Subscriptions & Collective Benefits**

El modelo persiste el catálogo de servicios en `subscription_plans`. La tabla `subscriptions` mantiene el estado de membresía del usuario, apoyándose en `payment_transactions` para el historial de facturación. Los convenios de seguros y descuentos se guardan en `collective_benefits`. El esquema de fidelización emplea `referral_codes` y audita sus canjes mediante `referral_usages`.

Database Diagram - Subscriptions Payment Management.

<img src="resources/imgs/sub.png"
     style="">

**Moderation & Governance**

El modelo implementa un diseño polimórfico en `moderation_tasks` (`entity_type` y `entity_id`) para centralizar en una sola cola los reportes de distintos orígenes. Las decisiones tomadas por los moderadores generan una pista de auditoría inmutable en `moderation_logs` para sustentar cualquier aprobación o rechazo.

Database Diagram - Moderation Governance.

<img src="resources/imgs/mode.png"
     style="">


# Capítulo V: Product Implementation, Validation & Deployment  


## 5.1. Software Configuration Management. 

### 5.1.1. Software Development Environment Configuration. 

**Project Management**

Para la administración del proyecto, se utilizaron varias herramientas para la comunicación, la planificación y el control de versiones.

| Plataforma                   | Descripción                                                                                                                                                                                             | Enlace               |
| :--------------------------: | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | :------------------- |
| Trello                       | Esta plataforma de gestión de proyectos ofrece el seguimiento detallado del progreso de cada tarea, además de permitir la designación de responsables para cada actividad dentro del equipo de trabajo. | https://trello.com   |
| Herramientas de Comunicación | La comunicación interna del equipo se gestionó a través de Discord y WhatsApp para reuniones y mensajes rápidos, respectivamente.                                                                       | https://discord.com/ |
| GitHub                       | Se creó una organización para centralizar el código fuente y su versionado, lo que permitió un control de versiones eficiente y una gestión ordenada.                                                   | https://github.com   |

**Requirement Management**

En la fase inicial, se emplearon herramientas para la recolección y organización de los requisitos del proyecto, lo que aseguró una base sólida para el desarrollo.

| Plataforma | Descripción                                                                                                                                                                                                     | Enlace                 |
| :--------: | :-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | :--------------------- |
| UXPressia  | Fue la herramienta principal para el diseño. Permitió al equipo crear y validar propuestas de diseño con wireframes, mockups y prototipos interactivos, lo que aseguró un producto final efectivo y atractivo.  | https://uxpressia.com/ |
| Miro       | Esta herramienta se usó para visualizar y desarrollar los escenarios "As-Is" (estado actual) y "To-Be" (estado futuro), lo que ayudó a planificar la evolución del proyecto.                                    | https://miro.com/es/   |

**Product UX/UI Desing**

Para el diseño de la experiencia y la interfaz de usuario, se usó una plataforma colaborativa que simplificó el flujo de trabajo.

| Plataforma | Descripción        																																															  |						  |
| :--------: | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | :-------------------- |
| Figma      | Fue la herramienta principal para el diseño. Permitió al equipo crear y validar propuestas de diseño con wireframes, mockups y prototipos interactivos, lo que aseguró un producto final efectivo y atractivo. | https://www.figma.com |

**Software Development**

El desarrollo se realizó utilizando un conjunto de lenguajes y entornos de programación que garantizan la estructura, el estilo y la interactividad del producto.

| Plataforma          | Descripción                                                                                                                                    | Link                                       |
|---------------------| :--------------------------------------------------------------------------------------------------------------------------------------------- | :----------------------------------------- |
| HTML                | Sirve para definir la estructura y el contenido de una página web.                                                                             | https://www.w3schools.com/html/default.asp |
| CSS                 | Se encarga de la presentación visual y el estilo de la página web.                                                                             | https://www.w3schools.com/css/default.asp  |
| JS                  | Añade interactividad y dinamismo a la página web.                                                                                              | https://www.w3schools.com/js/default.asp   |
| Visual Studio Code  | Entorno de desarrollo que facilita la escritura, edición, depuración y gestión de código para una amplia gama de lenguajes y proyectos.        | https://code.visualstudio.com              |
| JetBrains ToolBox   | Aplicación de gestión que contiene IDEs como IntelliJ IDEA, WebStorm y Rider (cada miembro del equipo trabajó en alguna de estas herramientas) | https://www.jetbrains.com/toolbox-app/     |

**Software Documentation**

La documentación y la publicación del proyecto se manejaron con herramientas que optimizan la colaboración y el despliegue final.

| Plataforma | Descripción                                             | Link                                                              |
|------------|---------------------------------------------------------|-------------------------------------------------------------------|
| GitHub     | Gestión de la documentación en función a repositorios y organizaciones | https://github.com      |
| Markdown   | Formato base para la presentación y documentación del proyecto | https://markdown.es/                     |

Se utilizó la estrategia GitHub Flow para la colaboración y el control de versiones, usando ramas específicas para cada funcionalidad. Esto mantuvo el proyecto organizado. También sirvió como repositorio central para toda la documentación.
Para el despliegue de la Landing Page se utilizó GitHub Pages, una herramienta perfecta para publicar sitios web estáticos.
<br>

### 5.1.2. Source Code Management. 

En esta sección, el equipo establece los medios y esquemas de organización para el seguimiento de modificaciones durante el ciclo de vida del proyecto. Para ello, se utiliza **GitHub** como plataforma y sistema de control de versiones.

**Repositorios del Proyecto:**
*   **Organización:** https://github.com/upc-pre-202620-1asi0730-7793
*   **Informe (Report):** https://github.com/upc-pre-202620-1asi0730-7793/Report
*   **Landing Page:** https://github.com/upc-pre-202620-1asi0730-7793/Landing-Page

**Flujo de Trabajo (Workflow): GitFlow**
Se adopta como referencia el modelo [GitFlow de Vincent Driessen](https://nvie.com/posts/a-successful-git-branching-model/) como esquema de control de versiones, definiendo las siguientes ramas principales para proteger el código de producción:
*   `main`: Contiene el código de producción final. Siempre estable y listo para el público.
*   `develop`: Rama de integración o desarrollo. Aquí se une todo el código nuevo de las características terminadas antes de preparar un lanzamiento.

**Convenciones de Nomenclatura de Ramas (En inglés):**
Para las ramas de apoyo temporales que se derivan de `develop` o `main`, se aplican las siguientes convenciones:

| Tipo | Prefijo | Formato | Ejemplo |
| :--- | :--- | :--- | :--- |
| **Característica (Feature)** | `feature/` | `feature/descriptive-name` | `feature/hero-section` |
| **Lanzamiento (Release)** | `release/` | `release/x.y.z` | `release/1.0.0` |
| **Corrección urgente (Hotfix)** | `hotfix/` | `hotfix/x.y.z-description` | `hotfix/1.0.1-navbar-fix` |

**Versionado de releases:**

Los releases de software seguirán [Semantic Versioning 2.0.0](https://semver.org/spec/v2.0.0.html), con el formato `MAJOR.MINOR.PATCH`. Una vez establecida la API pública en `1.0.0`, se incrementará `MAJOR` ante cambios incompatibles, `MINOR` al agregar funcionalidades compatibles y `PATCH` al corregir errores sin romper compatibilidad. Durante el desarrollo inicial se utilizará `0.y.z`. Estos números corresponden a releases de software; el registro de versiones del informe identifica sus revisiones mediante commits.

**Convenciones de Commits (Conventional Commits 1.0.0):**
Para asegurar la trazabilidad y mantener un historial estructurado, se aplica el estándar [Conventional Commits 1.0.0](https://www.conventionalcommits.org/en/v1.0.0/) para los mensajes de los commits en todos los repositorios, utilizando el idioma inglés de forma predeterminada. Basándonos en la Convención Angular, se emplearán los siguientes prefijos estandarizados:

*   `feat:` Introduce una nueva característica a la base de código.
*   `fix:` Corrige un error (bug) en el código.
*   `docs:` Actualizaciones exclusivas de documentación.
*   `style:` Cambios que no afectan el significado del código (espacios, formato, etc.).
*   `refactor:` Cambio de código que ni corrige un error ni añade una característica.
*   `perf:` Mejora de rendimiento.
*   `test:` Adición o corrección de pruebas.
*   `build:` Cambios en el sistema de construcción o dependencias externas.
*   `ci:` Cambios en archivos de configuración y scripts de CI.
*   `chore:` Mantenimiento general, sin cambios en el código de producción.


### 5.1.3. Source Code Style Guide & Conventions.

Para asegurar la calidad, mantenibilidad y coherencia de nuestra solución, hemos definido un conjunto de convenciones y buenas prácticas. Dado que la plataforma Noxway se presenta inicialmente a través de una landing page interactiva, nos centramos en los estándares para HTML, CSS y JavaScript, los pilares de nuestro desarrollo.

**Convenciones de Nomenclatura**

Para mantener la consistencia y la claridad a lo largo del código fuente, seguimos las siguientes reglas de nombrado:

* **Variables y Funciones en JavaScript**: Se utiliza la convención `camelCase` (ej. `selectedPlan`, `initializeVideos()`). Los nombres deben ser completamente descriptivos del comportamiento o dato almacenado.
* **Constantes en JavaScript**: Se utilizan letras mayúsculas separadas por guiones bajos (`SNAKE_CASE`) para definir valores inmutables o de configuración global.
* **Clases e Identificadores en HTML/CSS**: Se utiliza estrictamente la convención `kebab-case` en minúsculas para todos los nombres de clases e identificadores `id` (ej. `site-header`, `hero-section`, `btn-primary-hero`, `hamburger-btn`, `mobile-drawer`).
* **Atributos Personalizados (`data-*`)**: Se emplean nombres en `kebab-case` para almacenar metadatos de traducción e interacción dinámica (ej. `data-i18n`, `data-lang`, `data-plan-id`, `data-role-target`).
* **Archivos y Directorios**: Los nombres de archivos y carpetas se escriben íntegramente en minúsculas separando las palabras mediante guiones cortos (`kebab-case`) (ej. `index.html`, `style.css`, `i18n.js`, `main.js`, `hero-night-poster.jpg`).

**Estructura Semántica (HTML)**

La estructura de nuestro documento HTML se basa en la semántica web, utilizando etiquetas con un significado claro tanto para el navegador como para los desarrolladores. Esto no solo mejora la accesibilidad (WAI-ARIA) y el posicionamiento SEO, sino que también facilita la comprensión y auditoría del código. A continuación, se detallan las etiquetas utilizadas en el proyecto:

* `<!DOCTYPE html>`: Define el tipo de documento como HTML5.
* `<html lang="en">`: Elemento raíz del documento HTML con la declaración del idioma principal.
* `<head>`: Encabezado del documento donde se incluyen metadatos esenciales, favicon, etiquetas Open Graph y enlaces a hojas de estilo y tipografías externas.
* `<meta>`: Define los metadatos del sitio (codificación `UTF-8`, configuración de `viewport` para diseño adaptable, descripción, palabras clave y metadatos para redes sociales).
* `<title>`: Especifica el título visible del sitio en la pestaña del navegador.
* `<link>`: Enlaza recursos externos como las fuentes tipográficas (`Poppins` y `Roboto`), librerías de iconos (`FontAwesome`) y la hoja de estilos principal (`css/style.css`).
* `<body>`: Cuerpo del documento que alberga todo el contenido visible e interactivo de la interfaz.
* `<a>`: Enlaces de navegación interna, accesos directos de accesibilidad (`skip-to-content`), redes sociales y botones de acción.
* `<header>`: Encabezado principal del sitio (`site-header`) que contiene el logotipo de Noxway y el menú de navegación.
* `<nav>`: Contenedor semántico para la barra de navegación principal (`desktop-nav`) y el menú desplegable para dispositivos móviles (`mobile-nav-drawer`).
* `<ul>` y `<li>`: Listas no ordenadas para agrupar las opciones del menú de navegación y características de los planes.
* `<button>`: Elementos interactivos para el control de accesibilidad, selección de idioma (`EN` | `ES`), menú hamburguesa, acordeón de preguntas frecuentes y navegadores de testimonios y videos.
* `<main>`: Contenedor principal que agrupa las secciones funcionales de la landing page:
  * **Sección Inicio (`#inicio`)**: Presentación principal (*Hero*) estructurada con `<h1>`, `<p>`, video de fondo (`<video>`, `<source>`) y botones de llamada a la acción.
  * **Protocolo Nocturno (`#trayecto`)**: Describe el flujo del servicio mediante tarjetas estructuradas con `<article class="protocol-step">`.
  * **Ecosistema (`#mapa`)**: Muestra las funcionalidades clave organizadas en tarjetas `<article class="ecosystem-card">` e imágenes con carga diferida (`loading="lazy"`).
  * **Muestra Multimedia (`#videos`)**: Sección interactiva con reproductores de video embebidos mediante la etiqueta `<iframe>`.
  * **Testimonios (`#comunidad`)**: Galería interactiva con pestañas de selección y testimonios destacados en bloques `<blockquote>`.
  * **Planes de Suscripción (`#planes`)**: Matriz de tarifas estructurada con artículos interactivos (`<article class="pricing-row">`).
  * **Preguntas Frecuentes (`#faq`)**: Acordeón funcional construido con `<button>` y paneles `<div class="faq-answer-panel">`.
  * **Registro y Contacto (`#registro`)**: Formulario interactivo compuesto por `<form>`, `<input>` y `<select>`.
* `<article>`: Define bloques de contenido independientes y reutilizables dentro de las secciones.
* `<footer>`: Pie de página (`site-footer`) que incluye derechos de autor, enlaces a términos legales y navegación secundaria.
* `<div>`: Contenedores genéricos utilizados para maquetación, ventanas modales de términos y condiciones (`terms-modal-overlay`) y agrupaciones visuales.
* `<script>`: Carga de los archivos JavaScript (`js/i18n.js` y `js/main.js`) para gestionar la internacionalización y la interactividad del sitio.

**Estilos y Maquetación (CSS)**

Nuestra guía de estilo para CSS se centra en la claridad, simplicidad y consistencia visual. Se han definido propiedades clave para el diseño visual y la adaptabilidad del sitio:

* `width` y `height`: Controlan las dimensiones y proporciones de contenedores, tarjetas e imágenes.
* `padding` y `margin`: Establecen el espaciado interno y externo entre elementos para mantener una maquetación limpia.
* `font-family`: Establece la tipografía del sitio, utilizando `Poppins` para títulos y `Roboto` para textos de cuerpo.
* `font-size` y `font-weight`: Determinan la jerarquía visual y el grosor del texto.
* `color` y `background-color`: Definen la paleta croma nocturna del sitio (tonos oscuros con acentos brillantes).
* `display` y `flexbox`: Estructuran la alineación y distribución responsiva de los elementos en la barra de navegación, cuadrículas y formularios.

**Estándares de Accesibilidad (WAI-ARIA)**

El código fuente implementa los siguientes estándares para garantizar el cumplimiento de accesibilidad:

* **Roles explícitos**: Uso de roles WAI-ARIA como `role="banner"`, `role="dialog"`, `role="tablist"`, `role="tab"`, `role="tabpanel"`, `role="radiogroup"`, `role="radio"` y `role="contentinfo"`.
* **Estados dinámicos**: Control de visibilidad e interacción mediante los atributos `aria-expanded`, `aria-pressed`, `aria-selected`, `aria-hidden` y `hidden`.
* **Etiquetado claro**: Vinculación de controles mediante `aria-label`, `aria-labelledby`, `aria-controls` y `aria-live="polite"` para la lectura por tecnologías de asistencia.

### 5.1.4. Software Deployment Configuration.

Para poder publicar nuestra landing page, seguimos una serie de pasos específicos utilizando GitHub Pages, que permite alojar sitios web estáticos directamente desde un repositorio.

El despliegue en GitHub Pages requiere que los archivos estén organizados de una manera particular para que la plataforma los reconozca y los sirva correctamente.

 **1. Organización del Repositorio**

Los archivos del proyecto están organizados de la siguiente manera dentro del repositorio:

* **Página Principal**: El archivo `index.html` se ubica en la carpeta raíz del repositorio como punto de entrada de la solución.
* **Hojas de Estilo**: Los estilos globales del sitio se encuentran dentro de la carpeta `css/` bajo el archivo `css/style.css`.
* **Archivos JavaScript**: Los scripts se organizan en la carpeta `js/`. El archivo `js/i18n.js` se utiliza para gestionar las traducciones del sitio, mientras que `js/main.js` controla las interacciones del usuario.
* **Recursos Multimedia**: Las imágenes, gráficos y fondos multimedia se guardan dentro de la carpeta `assets/images/`.

** 2. Subida de Archivos**
Una vez que los archivos están correctamente organizados y verificados en el entorno local, se suben al repositorio a través de un *commit* y se sincronizan con la rama principal.

 **3. Configuración en GitHub Pages**

Para habilitar la publicación en la plataforma, se realiza la siguiente configuración:

1. Se navega a la pestaña **Settings** > **Pages** dentro del repositorio.
2. Se selecciona la rama `main` como la fuente de despliegue.
3. Se configura la carpeta raíz (`/root`) como el origen de la página.

**4. Despliegue Automático**

* GitHub Pages inicia un proceso de verificación y despliegue automático.
* Al finalizar el proceso, la plataforma genera una URL pública para acceder a la landing page.
* El archivo `js/i18n.js` es cargado por el script principal `js/main.js` para permitir que los usuarios cambien el idioma de la página de forma dinámica.

## 5.2. Landing Page, Services & Applications Implementation. 

### 5.2.1. Sprint 1

#### 5.2.1.1. Sprint Planning 1.

El Sprint Planning 1 se enfocó en el desarrollo e implementación de la primera versión funcional del sitio web estático (Landing Page) de Noxway. El objetivo principal de esta iteración es establecer la presencia digital del producto, comunicando claramente la propuesta de valor tanto para los trabajadores de turno nocturno como para sus contactos de confianza, integrando información sobre los planes de suscripción, testimonios y demostraciones visuales de la plataforma.

| Sprint # | Sprint 1 |
| :--- | :--- |
| **Sprint Planning Background** | |
| **Date** | 2026-09-19 |
| **Time** | 1:00 PM |
| **Location** | Reunión virtual mediante Discord |
| **Prepared By** |  Ana Camila Patricio Farias|
| **Attendees (to planning meeting)** | Ana Patricio,Yam Cano,Leonardo Dextre,Mauricio Ramirez,Carlos Salcedo|
| **Sprint 1 Review Summary** |  |
| **Sprint 1 Retrospective Summary** | Durante este sprint, todos los integrantes compartieron sus ideas respecto a la plataforma web, tales como el rubro, los segmentos objetivos, beneficios, funcionalidades. Tuvimos tareas bien organizadas y realizadas, que se puede verificar en los avances del informe y del Landing Page |
| **Sprint Goal & User Stories** | |
| **Sprint 1 Goal** | Nuestro enfoque está en implementar la landing page de nuestra plataforma, asegurando su adaptabilidad a diferentes dispositivos, coherencia visual y funcionalidad multilingüe. Creemos que esto ofrece una experiencia de navegación más clara, atractiva y accesible a los usuarios potenciales de nuestra solución. Esto se confirmará cuando los usuarios puedan cambiar el idioma fácilmente desde la interfaz, navegar la página sin errores visuales desde cualquier dispositivo, y se valide que imágenes y textos estén correctamente integrados y espaciados.|
| **Sprint 1 Velocity** | 15 Story Points |
| **Sum of Story Points** | 14 Story Points |

#### 5.2.1.2. Aspect Leaders and Collaborators. 
A continuación, se detalla la matriz de liderazgo y colaboración (LACX) para los aspectos clave abordados en este sprint.  

| Team Member (Last Name, First Name) | GitHub Username | Landing Page (HTML/CSS/JS)<br>Leader (L) / Collaborator (C) | UX/UI & Prototyping<br>Leader (L) / Collaborator (C) | Project Documentation<br>Leader (L) / Collaborator (C) |
| :--- | :--- | :---: | :---: | :---: |
| Cano Gomez, Yam Antony  | Yam-1CG | C | C | L |
| Ramirez Rodriguez, Mauricio Joao  | MauRicio1321rr  | C | C | C |
| Dextre Dextre Flores, Leonardo | Leo-dex45 | C | C | C |
| Patricio Farias, Ana Camila | anacamilapatricio-sketch | C | L | C |
| Salcedo Correa, Carlos Mathhew | Matthewnhfe | L | L | C |
#### 5.2.1.3. Sprint Backlog 1. 
| User Story Id | User Story Title | Task Id | Task Title | Task Description | Estimation (Hours) | Assigned To | Status |
| :---: | :--- | :---: | :--- | :--- | :---: | :---: | :---: |
| **US-05** | Conocer la propuesta de valor | **UT-01** | Crear la sección 'Hero' y Beneficios | Añadir la sección principal con la propuesta de valor y el llamado a la acción hacia el registro. | 2 | Camila | Done |
| **US-24** | Consultar planes de suscripción (Landing Page) | **UT-01** | Crear la sección 'Planes' | Maquetar las tarjetas con los planes de suscripción, beneficios y redirección con plan preseleccionado. | 2 | Leonardo | Done |
| **US-31** | Visualizar video de demostración y equipo en la Landing Page | **UT-01** | Integrar sección multimedia y equipo | Añadir el reproductor de video explicativo y mensaje de fallback ante fallas de carga. | 2 | Carlos | Done |
| **US-32** | Consultar testimonios y casos de éxito en la Landing Page | **UT-01** | Crear la sección 'Testimonios' | Implementar el slider/carrusel responsivo con citas, autores y casos de éxito de trabajadores nocturnos. | 2 | Yam | Done |
| **US-33** | Desplegar preguntas frecuentes (FAQ) en la Landing Page | **UT-01** | Crear la sección 'FAQ' | Agregar el acordeón interactivo para expandir y colapsar las dudas frecuentes. | 1 | Mauricio | Done |
| **US-34** | Enviar formulario de contacto o soporte desde la Landing Page | **UT-01** | Crear formulario de contacto | Agregar formulario con validación de campos obligatorios, formato de email y confirmación de envío. | 1.5 | Camila | Done |
| **US-35** | Cambiar idioma y tema visual en la Landing Page | **UT-01** | Implementar switch de idioma y tema | Añadir selector para alternar español/inglés y botón para modo claro/oscuro. | 2 | Carlos | Done |

<img src="resources/imgs/sprin1.png">

NoxWay Sprint Backlog 
https://trello.com/invite/b/690c87e2eddd3d52ed83189d/ATTI96b986ca465d37e1b647b2fb1690fee5DC6EC0DE/noxway



En este primer Sprint hemos realizado la implementación de nuestra Landing Page, donde todo el equipo ha aportado en varias tareas. En la siguiente tabla se muestran los commits realizados para evidenciar el desarrollo.

| Repository | Branch | Commit Id | Commit Message | Commit Message Body | Commited on (Date) |
| :--- | :--- | :--- | :--- | :--- | :--- |
| upc-pre-202620-1asi0730-7793 | main | 1712d6c | Merge pull request #4 from upc-pre-202620-1asi0730-7793/develop | Merge pull request #4 from upc-pre-202620-1asi0730-7793/develop | 19/09/2026 |
| upc-pre-202620-1asi0730-7793 | main | 7fe7538 | fix(landing): link youtube in index.html | link youtube in index.html | 19/09/2026 |
| upc-pre-202620-1asi0730-7793 | main | ed85441 | Merge pull request #3 from upc-pre-202620-1asi0730-7793/develop | Merge pull request #3 from upc-pre-202620-1asi0730-7793/develop | 19/09/2026 |
| upc-pre-202620-1asi0730-7793 | main | 2889157 | feat(i18n): implement bilingual dictionaries and translation engine in i18n.js | implement bilingual dictionaries and translation engine in i18n.js | 19/09/2026 |
| upc-pre-202620-1asi0730-7793 | main | 47d9cd6 | fix(landing): correct general structure and syntax errors in main.js | correct general structure and syntax errors in main.js | 19/09/2026 |
| upc-pre-202620-1asi0730-7793 | main | 3685bb3 | fix(landing): correct general structure and syntax errors in index.html | correct general structure and syntax errors in index.html | 19/09/2026 |
| upc-pre-202620-1asi0730-7793 | main | 2ed91c3 | Merge pull request feature/final-finalpart-style | Merge pull request feature/final-finalpart-style | 19/09/2026 |
| upc-pre-202620-1asi0730-7793 | main | 4045767 | feat: add final style adjustments to landing page | add final style adjustments to landing page | 19/09/2026 |
| upc-pre-202620-1asi0730-7793 | main | db796f1 | feat(landing): add subscription plans section in index.html | add subscription plans section in index.html | 19/09/2026 |
| upc-pre-202620-1asi0730-7793 | main | f8d0f1d | feat(landing): implement reveal on scroll logic for protocol and ecosystem in main.js | implement reveal on scroll logic for protocol and ecosystem in main.js | 19/09/2026 |
| upc-pre-202620-1asi0730-7793 | main | 8d6439e | style(landing): add styles for video and testimonial sections in styles.css | add styles for video and testimonial sections in styles.css | 19/09/2026 |
| upc-pre-202620-1asi0730-7793 | main | 5627df0 | feat(landing): implement initialization, responsive menu and hero video control | implement initialization, responsive menu and hero video control | 19/09/2026 |
| upc-pre-202620-1asi0730-7793 | main | f0a6a1f | style(landing): add styles for night protocol and ecosystem sections in styles.css | add styles for night protocol and ecosystem sections in styles.css | 19/09/2026 |
| upc-pre-202620-1asi0730-7793 | main | ae391c4 | style(landing): add css variables, reset, header, navigation and hero styles in styles.css | add css variables, reset, header, navigation and hero styles in styles.css | 19/09/2026 |
| upc-pre-202620-1asi0730-7793 | main | 795c91c | Merge pull request feature/final-preview-landingpage | Merge pull request feature/final-preview-landingpage | 19/09/2026 |
| upc-pre-202620-1asi0730-7793 | main | f20d424 | feat(landing): add contact section, footer and terms modal markup | add contact section, footer and terms modal markup | 19/09/2026 |
| upc-pre-202620-1asi0730-7793 | main | 3e57cf8 | feat(landing): add video showcase and testimonials sections in index.html | add video showcase and testimonials sections in index.html | 19/09/2026 |
| upc-pre-202620-1asi0730-7793 | main | 7816c6c | chore(assets): add required image assets for landing page | add required image assets for landing page | 19/09/2026 |
| upc-pre-202620-1asi0730-7793 | main | aa5543b | feat(landing): add night protocol and ecosystem sections in index.html | add night protocol and ecosystem sections in index.html | 19/09/2026 |
| upc-pre-202620-1asi0730-7793 | main | 1c254f0 | feat(landing): add base html structure, navigation bar and hero section in index.html | add base html structure, navigation bar and hero section in index.html | 19/09/2026 |
| upc-pre-202620-1asi0730-7793 | main | 0ec1b1e | feat(landing): add core structure, styles, main scripts and i18n support | add core structure, styles, main scripts and i18n support | 19/09/2026 |

#### 5.2.1.5. Execution Evidence for Sprint Review. 
Capturas de la página desplegada junto a un video demostrativo de su diseño y usabilidad

<img src="resources/imgs/Landing-Desplegada.png">

link de la landing: https://upc-pre-202620-1asi0730-7793.github.io/Landing-Page/
link del video: https://upcedupe-my.sharepoint.com/:v:/g/personal/u202421065_upc_edu_pe/IQBfINsAKTsuTZ5_fDXp19sKAa5z-SRiOqBqVa2xgvU_l0I?e=q8RIZT

#### 5.2.1.6. Services Documentation Evidence for Sprint Review. 
Durante este Sprint, el equipo de desarrollo se centró en definir la visión inicial del backend y la arquitectura de servicios RESTful de Noxway, estableciendo las bases necesarias para el funcionamiento interno de la plataforma. Esta etapa permitió organizar la estructura principal del sistema y proyectar cómo se gestionará la información crítica relacionada con los check-ins de trayectos, la vinculación de contactos de confianza y el mapa comunitario 24 horas.

El backend de Noxway estará orientado a facilitar la administración de procesos clave dentro del entorno de trabajo nocturno, permitiendo un manejo más ordenado y seguro de la telemetría, el envío automático de alertas ante posibles incidentes y la gestión de la bitácora de descanso. Asimismo, servirá como soporte centralizado para garantizar la integración fluida y en tiempo real entre la aplicación móvil de los trabajadores y el portal web de los acompañantes (Companion View), contribuyendo a mejorar la eficiencia y el control durante situaciones de vulnerabilidad en la madrugada.

Este avance representa un paso importante para el crecimiento del proyecto, ya que permitirá consolidar una base tecnológica sólida y bien documentada sobre la cual se desarrollarán e integrarán las siguientes etapas del ecosistema de seguridad nocturna.

Durante el Sprint 1, el alcance de desarrollo e implementación técnica estuvo enfocado de manera exclusiva en la construcción, optimización y despliegue público de la Landing Page estática de Noxway, con el objetivo de validar la propuesta de valor comercial y captar el interés de los segmentos objetivo (trabajadores nocturnos y contactos de confianza).

Debido a que la arquitectura de servicios (RESTful API), la base de datos y la lógica de negocio central de la plataforma móvil y web forman parte del alcance de las siguientes iteraciones (Sprints posteriores), en esta fase inicial aún no se cuenta con implementaciones a nivel de backend.

#### 5.2.1.7. Software Deployment Evidence for Sprint Review. 
Durante este sprint, se completó el despliegue de la landing page para habilitar su acceso público mediante GitHub Pages. El procedimiento inició con la creación y configuración de un repositorio público bajo la nomenclatura asignada al proyecto. Posteriormente, se cargó el código fuente y se activó el servicio de publicación web desde los ajustes del repositorio. Finalmente, se validó la disponibilidad y operatividad del sitio en línea, estableciendo un flujo de mantenimiento continuo en el cual cualquier cambio subido al repositorio se refleja automáticamente en producción.

*Evidencia de deployment 1*
<br>
<img src="resources/imgs/Github-Pages-Nowxay.png">

#### 5.2.1.8. Team Collaboration Insights during Sprint. 

<img src="resources/imgs/Colaboration1.png">

<img src="resources/imgs/Colaboration2.png">


### 5.2.1. Sprint 2

#### 5.2.2.1.Sprint Planning 2.
El Sprint Planning 2 se enfocó en el despliegue funcional del sitio web estático (Landing Page) de Noxway y de la primera version de la pagina web de Noxway. El objetivo principal de esta iteración es establecer la presencia digital del producto, comunicando claramente la propuesta de valor tanto para los trabajadores de turno nocturno como para sus contactos de confianza, integrando información sobre los planes de suscripción, testimonios y demostraciones visuales de la plataforma.

| Sprint # | Sprint 2 |
| :--- | :--- |
| **Sprint Planning Background** | |
| **Date** | 2026-10-01 |
| **Time** | 1:00 PM |
| **Location** | Reunión virtual mediante Discord |
| **Prepared By** |  Ana Camila Patricio Farias|
| **Attendees (to planning meeting)** | Ana Patricio,Yam Cano,Leonardo Dextre,Mauricio Ramirez,Carlos Salcedo|
| **Sprint 2 Review Summary** |  |
| **Sprint 2 Retrospective Summary** | Durante este sprint, todos los integrantes compartieron sus ideas respecto a la aplicacion web, los bounded context, arquitectura DDD, funcionalidades. Tuvimos tareas bien organizadas y realizadas, que se puede verificar en los avances del informe y de la pagina web |
| **Sprint Goal & User Stories** | |
| **Sprint 2 Goal** | Nuestro enfoque está en implementar las correciones a la Landing Page y el despliegue de la aplicacion web, asegurando su coherencia visual y funcionalidad multilingüe y que la puedan usar nuestro dos segementos objetivos. Creemos que esto ofrece una experiencia de navegación más clara, atractiva y accesible a nuestros usuarios potenciales de nuestra solución. Esto se confirmará cuando los usuarios puedan cambiar el idioma fácilmente desde la interfaz, que puedan navergar intuitivamente en la aplicacion sin errores visuales desde cualquier dispositivo, y se valide que imágenes, textos y direcciones estén correctamente integrados y espaciados.|
| **Sprint 2 Velocity** | 13 Story Points |
| **Sum of Story Points** | 14 Story Points |

#### 5.2.2.2. Aspect Leaders and Collaborators.

A continuación, se detalla la matriz de liderazgo y colaboración (LACX) para los aspectos clave abordados en este sprint.  

| Team Member (Last Name, First Name) | GitHub Username | Aplicaion web <br>Leader (L) / Collaborator (C) | Despliegue de la aplicacion web <br>Leader (L) / Collaborator (C) | Project Documentation<br>Leader (L) / Collaborator (C) |
| :--- | :--- | :---: | :---: | :---: |
| Cano Gomez, Yam Antony  | Yam-1CG | C | C | L |
| Ramirez Rodriguez, Mauricio Joao  | MauRicio1321rr  | C | C | C |
| Dextre Dextre Flores, Leonardo | Leo-dex45 | L | L | C |
| Patricio Farias, Ana Camila | anacamilapatricio-sketch | L | C | L |
| Salcedo Correa, Carlos Mathhew | Matthewnhfe | L | L | C |

#### 5.2.2.3.Sprint Backlog 2.

| User Story Id | User Story Title | Task Id | Task Title | Task Description | Estimation (Hours) | Assigned To | Status |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| **US-06** | Invitar contacto de confianza | UT-01 | Formulario de invitación | Implementar formulario para enviar invitaciones por correo/teléfono y conectar con el API. | 3 | Camila | Done |
| **US-07** | Aceptar o rechazar invitación | UT-01 | Gestión de invitación entrante | Desarrollar la vista para que el contacto acepte/rechace y actualizar el estado del vínculo. | 2 | Carlos | Done |
| **US-08** | Remover contacto de confianza | UT-01 | Opción de eliminar contacto | Añadir botón de eliminación con modal de confirmación en la lista de contactos vinculados. | 2 | Leonardo | Done |
| **US-09** | Iniciar check-in de trayecto seguro | UT-01 | Interfaz de inicio de check-in | Crear formulario para ingresar destino y tiempo estimado e iniciar la telemetría en vivo. | 5 | Carlos | Done |
| **US-10** | Confirmar llegada segura | UT-01 | Botón de confirmación de llegada | Implementar botón para finalizar el check-in activo, deteniendo el rastreo y notificando. | 3 | Camila | Done |
| **US-11** | Cancelar check-in activo | UT-01 | Cancelación de trayecto | Desarrollar lógica para cancelar un trayecto en curso desde el dashboard del trabajador. | 2 | Camila | Done |
| **US-12** | Marcado automático de posible incidente | UT-01 | Cronómetro y alerta automática | Implementar lógica para evaluar tolerancia de tiempo y disparar el incidente en la UI. | 4 | Leonardo | Done |
| **US-13** | Validar posible incidente | UT-01 | Modal de validación | Crear interfaz para que el trabajador descarte (falso positivo) o confirme una alerta. | 3 | Carlos | Done |
| **US-14** | Recibir alerta de posible incidente | UT-01 | Recepción de alertas en Companion | Desarrollar notificaciones push y alertas visuales resaltadas en el portal del contacto. | 3 | Camila | Done |
| **US-15** | Buscar servicios nocturnos cercanos | UT-01 | Mapa de servicios 24h | Integrar mapa interactivo con pines de locales abiertos de madrugada y barra de búsqueda. | 5 | Yam | Done |
| **US-16** | Reportar nuevo servicio nocturno | UT-01 | Formulario de nuevo local | Crear formulario para registrar información y coordenadas de un nuevo servicio 24h. | 3 | Leonardo | Done |
| **US-17** | Calificar un servicio nocturno reportado | UT-01 | Sistema de votos para servicios | Añadir botones de upvote/downvote para calificar la veracidad en los detalles del servicio. | 2 | Carlos | Done |
| **US-18** | Calificar seguridad de ruta | UT-01 | Encuesta de seguridad post-trayecto | Implementar modal de estrellas y comentarios que aparece al confirmar la llegada segura. | 3 | Camila | Done |
| **US-19** | Reportar punto de riesgo específico | UT-01 | Marcador de riesgo en mapa | Desarrollar opción para colocar un pin de peligro con descripción en el mapa comunitario. | 3 | Yam | Done |
| **US-20** | Visualizar mapa de zonas de riesgo | UT-01 | Capa de zonas de riesgo | Mostrar perímetros sombreados y advertencias de peligro superpuestas sobre el mapa 24h. | 4 | Leonardo | Done |
| **US-21** | Registrar horas de descanso | UT-01 | Formulario de bitácora de sueño | Implementar vista para ingresar horas de inicio y fin del descanso diurno del trabajador. | 2 | Carlos | Done |
| **US-22** | Visualizar historial de descanso | UT-01 | Gráficos de historial de sueño | Integrar librería de gráficos para mostrar patrones de descanso semanales y déficits. | 4 | Camila | Done |
| **US-23** | Recibir sugerencia de higiene del sueño | UT-01 | Tarjetas de sugerencias | Mostrar alertas de interfaz y recomendaciones basadas en el déficit de sueño calculado. | 2 | Yam | Done |
| **US-25** | Suscribirse al plan mensual | UT-01 | Flujo de pago y suscripción | Integrar pasarela de pago y actualizar el estado de membresía (Centinela Pro) en el perfil. | 5 | Leonardo | Done |
| **US-26** | Acceder a beneficios y descuentos | UT-01 | Catálogo de convenios y QR | Desarrollar la vista de recompensas con generación de código QR dinámico para suscriptores. | 3 | Carlos | Done |
| **US-27** | Referir a un contacto (beneficio) | UT-01 | Generador de enlaces | Implementar sección para copiar código de referido personal y ver el progreso de recompensas. | 2 | Camila | Done |
| **US-28** | Visualizar estado de trayecto en tiempo real | UT-01 | Mapa de rastreo en vivo | Desarrollar el panel del contacto para mostrar la ubicación en movimiento, velocidad y ETA. | 5 | Yam | Done |
| **US-29** | Configurar preferencias de notificación | UT-01 | Panel de ajustes de alertas | Crear vista con interruptores (switches) para habilitar/deshabilitar notificaciones de rutina. | 2 | Leonardo | Done |
| **US-30** | Revisar y aprobar reportes de la comunidad | UT-01 | Bandeja de moderación | Implementar interfaz para listar reportes pendientes y botones de aprobación/rechazo. | 4 | Carlos | Done |

<img src="resources/imgs/spring2.png">

**NoxWay Sprint Backlog:** 
https://trello.com/invite/b/690c87e2eddd3d52ed83189d/ATTI96b986ca465d37e1b647b2fb1690fee5DC6EC0DE/noxway

Durante el Sprint 2, el equipo trabajó en la implementación del frontend de la aplicación web de Noxway, tomando como referencia las historias de usuario y las tareas definidas en el Sprint Backlog 2. A continuación, se presentan los commits realizados en el repositorio Noxway-Frontend como evidencia del desarrollo y de la integración de los cambios durante esta iteración.

#### 5.2.2.4. Development Evidence for Sprint Review.

Durante el Sprint 2, el equipo desarrolló el frontend de la aplicación web de Noxway, incorporando la estructura de navegación, el dashboard del trabajador y las vistas correspondientes a contactos de confianza, trayectos, comunidad, descanso y beneficios. Asimismo, se realizaron ajustes de traducción, configuración de servicios y correcciones de navegación para integrar los distintos módulos de la aplicación.

A continuación, se presenta una selección de commits representativos del repositorio Noxway-Frontend, perteneciente a la organización upc-pre-202620-1asi0730-7793. Esta selección evidencia los principales cambios registrados durante la iteración. El historial también registra el uso de datos simulados mediante JSON Server y endpoints mock de Beeceptor.

| Repository | Branch | Commit Id | Commit Message | Descripción del cambio | Committed on (Date) |
| :--- | :--- | :--- | :--- | :--- | :--- |
| Noxway-Frontend | main | b197353 | feat(shared): align application layout with Figma design | Alinea la estructura visual de la aplicación con el diseño de referencia en Figma. | 06/10/2026 |
| Noxway-Frontend | main | 36e037a | feat(routes): configure application routes | Configura las rutas de navegación de la aplicación web. | 06/10/2026 |
| Noxway-Frontend | main | a47a1f5 | feat(dashboard): align worker dashboard with Figma design | Ajusta el dashboard del trabajador al diseño de referencia en Figma. | 06/10/2026 |
| Noxway-Frontend | main | 7a009d6 | feat(dashboard): consume dashboard data from json server | Incorpora el consumo de datos del dashboard desde JSON Server. | 06/10/2026 |
| Noxway-Frontend | main | 1712d7c | feat(shared): implement base api configuration and core services | Implementa la configuración base de la API y los servicios centrales compartidos. | 08/10/2026 |
| Noxway-Frontend | main | d61eb6d | feat(shared): create layout, footer and language switcher components | Crea los componentes de estructura general, pie de página y selector de idioma. | 08/10/2026 |
| Noxway-Frontend | main | 93801e5 | feat(iam): implement trustedcontacts component logic and invitation actions | Implementa la lógica del componente de contactos de confianza y las acciones de invitación. | 08/10/2026 |
| Noxway-Frontend | main | 0a8bcf9 | feat(iam): implement profile component logic with privacy toggles | Implementa la lógica del perfil y los controles de privacidad. | 08/10/2026 |
| Noxway-Frontend | main | ac3646d | feat(companion): create history and invitations views | Crea las vistas de historial e invitaciones del contacto de confianza. | 08/10/2026 |
| Noxway-Frontend | main | ebe93a0 | feat(companion): build alerts and emergency views | Construye las vistas de alertas y emergencias del módulo Companion. | 08/10/2026 |
| Noxway-Frontend | main | 5d88583 | feat(companion): implement live tracking and profile views | Incorpora las vistas de seguimiento y perfil del módulo Companion. | 08/10/2026 |
| Noxway-Frontend | main | bd44b9b | feat(commute): implement journey component logic and telemetry events | Implementa la lógica del componente de trayecto y sus eventos de telemetría. | 08/10/2026 |
| Noxway-Frontend | main | 4c5a377 | feat(commute): create journey tracking template with checkpoint progress | Crea la plantilla de seguimiento del trayecto con visualización del progreso por puntos de control. | 08/10/2026 |
| Noxway-Frontend | main | 0e9aac8 | feat(community): implement mapview component logic with filter signals | Implementa la lógica de la vista del mapa y el estado de sus filtros mediante signals. | 08/10/2026 |
| Noxway-Frontend | main | 65cbe49 | feat(community): implement community feed component logic | Implementa la lógica del componente de publicaciones de la comunidad. | 08/10/2026 |
| Noxway-Frontend | main | 82568ff | feat(wellness): implement Wellness component logic and rest logger | Implementa la lógica del componente de bienestar y el registro de descanso. | 08/10/2026 |
| Noxway-Frontend | main | 66cd1d0 | feat(wellness): add Wellness view template with diurnal sleep chart and habits | Añade la plantilla de bienestar con gráfico de sueño diurno y hábitos. | 08/10/2026 |
| Noxway-Frontend | main | dfc61ce | feat(subscriptions): implement Benefits component logic and signals | Implementa la lógica del componente de beneficios y su estado mediante signals. | 08/10/2026 |
| Noxway-Frontend | main | 888fb27 | fix(i18n): correct translation dictionary keys and dynamic page titles | Corrige las claves del diccionario de traducciones y los títulos dinámicos de las páginas. | 08/10/2026 |
| Noxway-Frontend | main | 9818459 | fix(layout): correct sidebar navigation options and language bindings | Corrige las opciones de navegación de la barra lateral y sus enlaces con el idioma seleccionado. | 08/10/2026 |
| Noxway-Frontend | main | ab4b9aa | feat(api): connect services to beeceptor mock endpoints for production | Conecta los servicios con endpoints simulados de Beeceptor para el entorno de producción. | 08/10/2026 |
| Noxway-Frontend | main | 698e327 | Merge pull request #2 from upc-pre-202620-1asi0730-7793/develop | Registra la integración de la rama develop en main mediante el Pull Request #2. | 08/10/2026 |

**Historial completo de commits:** [Noxway-Frontend — main](https://github.com/upc-pre-202620-1asi0730-7793/Noxway-Frontend/commits/main/).

#### 5.2.2.5.Execution Evidence for Sprint Review.
En esta sección se presentan las evidencias de ejecución de la aplicación web de Noxway correspondientes al Sprint 2. Las capturas muestran las interfaces desarrolladas y los resultados de las interacciones realizadas desde los perfiles del trabajador nocturno y del contacto de confianza.

**Aplicación web desplegada:** [Noxway](https://noxway-frontend.web.app/)

**Dashboard del trabajador**

![Dashboard del trabajador](resources/imgs/chapter_v/Noxway-dashboard.png)

*Figura 1. Vista principal del dashboard del trabajador.*

**Perfil del usuario**

![Perfil del usuario](resources/imgs/chapter_v/Noxway-perfil.png)

*Figura 2. Interfaz del perfil del usuario.*

**Contactos de confianza**

![Contactos de confianza](resources/imgs/chapter_v/Noxway-Contactos%20de%20confianza.png)

*Figura 3. Interfaz de gestión de contactos de confianza.*

**Trayecto seguro**

![Trayecto seguro](resources/imgs/chapter_v/Noxway-trayecto.png)

*Figura 4. Vista del trayecto del trabajador.*

**Mapa nocturno**

![Mapa nocturno](resources/imgs/chapter_v/Noxway-mapa.png)

*Figura 5. Interfaz del mapa nocturno.*

**Comunidad**

![Comunidad de Noxway](resources/imgs/chapter_v/Noxway-Comunidad.png)

*Figura 6. Vista del módulo de comunidad.*

**Beneficios**

![Beneficios de Noxway](resources/imgs/chapter_v/Noxway-Beneficios.png)

*Figura 7. Vista del módulo de beneficios.*

#### 5.2.2.6.Services Documentation Evidence for Sprint Review.

Durante el Sprint 2 se implementaron servicios de consulta en el frontend de Noxway para obtener información del dashboard, los trayectos, los contactos de confianza, la comunidad, el bienestar, las suscripciones y el módulo Companion.

En el entorno de desarrollo se utiliza JSON Server con datos de muestra definidos en db.json. La configuración de producción establece Beeceptor como servidor mock para los servicios que utilizan environment.apiUrl. El servicio de trayectos mantiene una dirección local independiente.

Las operaciones identificadas en los servicios específicos del frontend corresponden a solicitudes GET, sin parámetros de ruta, parámetros de consulta ni cuerpo de solicitud. Las respuestas esperadas se describen a continuación. Los ejemplos presentan únicamente algunos campos de los datos de muestra; no representan respuestas completas ni pruebas de ejecución.

**URL base local:** `http://localhost:3000`

**URL base configurada para producción:** `https://noxwayapi.free.beeceptor.com`

| Acción | Método HTTP | Sintaxis de llamada local | Parámetros / cuerpo | Ejemplo parcial de respuesta | Explicación |
| :--- | :--- | :--- | :--- | :--- | :--- |
| Consultar dashboard | GET | `http://localhost:3000/dashboard` | Ninguno | `[{"id":1,"safeTripsPercentage":100,"servicesCount":14}]` | Devuelve una colección con indicadores y datos del dashboard del trabajador. |
| Consultar trayecto | GET | `http://localhost:3000/commute` | Ninguno | `[{"id":1,"remainingTime":"18:42 min","routeRating":5}]` | Devuelve una colección de trayectos. El frontend selecciona el primer elemento para mostrarlo. |
| Consultar puntos del mapa | GET | `http://localhost:3000/mapPoints` | Ninguno | `[{"id":1,"type":"pharmacy","lat":-11.992,"lng":-77.072}]` | Devuelve los puntos de servicios nocturnos y zonas de riesgo representados en el mapa. |
| Consultar publicaciones | GET | `http://localhost:3000/communityPosts` | Ninguno | `[{"id":1,"authorName":"Marcos Huamán","upvotes":28}]` | Devuelve las publicaciones de muestra de la comunidad. |
| Consultar bienestar | GET | `http://localhost:3000/wellness` | Ninguno | `[{"id":1,"lastRestDuration":"6h 45m","weeklyAverage":"6.8 hrs"}]` | Devuelve una colección con resumen, historial y sugerencias de descanso. El frontend selecciona el primer elemento. |
| Consultar suscripción | GET | `http://localhost:3000/subscriptions` | Ninguno | `[{"id":1,"planName":"Plan Centinela Pro","referralCode":"JORGE-NOX26"}]` | Devuelve una colección con el plan, los beneficios y los datos de referidos. El frontend selecciona el primer elemento. |
| Consultar contactos | GET | `http://localhost:3000/trustedContacts` | Ninguno | `[{"id":1,"name":"Rosa Elena Paredes","statusType":"active"}]` | Devuelve la lista de contactos de confianza de muestra. |
| Consultar perfil del trabajador | GET | `http://localhost:3000/userProfile` | Ninguno | `[{"id":1,"fullName":"Jorge Luis Huamán Quispe","privacyGpsActiveOnly":true}]` | Devuelve una colección con información del perfil. El frontend selecciona el primer elemento. |
| Consultar seguimiento Companion | GET | `http://localhost:3000/companionLive` | Ninguno | `[{"id":1,"workerName":"Jorge Luis Huamán","battery":"84%"}]` | Devuelve una colección con datos simulados de seguimiento del trabajador. El frontend selecciona el primer elemento. |
| Consultar historial Companion | GET | `http://localhost:3000/companionHistory` | Ninguno | `{"stats":{"monitoredRoutes":"48 Rutas"},"records":[{"id":1,"status":"Monitoreo Activo"}]}` | Devuelve un objeto con estadísticas y registros de trayectos. |
| Consultar alertas Companion | GET | `http://localhost:3000/companionAlerts` | Ninguno | `{"channels":[{"id":"whatsapp","enabled":true}],"logs":[{"id":1,"type":"check"}]}` | Devuelve la configuración de canales y el historial de alertas de muestra. |
| Consultar información de emergencia | GET | `http://localhost:3000/companionEmergency` | Ninguno | `{"rescueProtocol":{"title":"Protocolo de Auxilio Rápido & Ficha de Rescate"},"serenazgo":[{"id":1}],"nationalLines":[{"id":"pnp"}]}` | Devuelve información de muestra del protocolo de auxilio y los contactos de emergencia. |
| Consultar invitaciones Companion | GET | `http://localhost:3000/companionInvitations` | Ninguno | `{"pending":{"id":1,"status":"PENDIENTE DE CONFIRMACIÓN"},"activeWorkers":[{"id":1}],"steps":[{"step":"01"}]}` | Devuelve la invitación pendiente, los trabajadores vinculados y los pasos informativos de vinculación. |
| Consultar perfil Companion | GET | `http://localhost:3000/companionProfile` | Ninguno | `{"fullName":"Rosa Elena Paredes Morales","verified":true}` | Devuelve un objeto con los datos del perfil del contacto de confianza. |

**Repositorio que contiene los servicios de consumo y datos simulados:** [Noxway-Frontend](https://github.com/upc-pre-202620-1asi0730-7793/Noxway-Frontend).

#### 5.2.2.7.Software Deployment Evidence for Sprint Review.


Durante el Sprint 2 se realizó el despliegue de la primera versión del frontend de Noxway mediante Firebase Hosting, habilitando su acceso público desde un navegador web. El proyecto utilizado para el alojamiento se identifica como noxway-frontend.

La configuración del proyecto Angular contempla una compilación para producción y el uso del archivo environment.production.ts. La consola de Firebase registra la publicación de la aplicación el 8 de octubre de 2026. A continuación, se presentan las evidencias del proyecto utilizado y de la publicación realizada.

**Plataforma de alojamiento:** Firebase Hosting.

**Repositorio del frontend:** [Noxway-Frontend](https://github.com/upc-pre-202620-1asi0730-7793/Noxway-Frontend).

**Aplicación web desplegada:** [Noxway](https://noxway-frontend.web.app/).

**Configuración del proyecto en Firebase**

![Configuración del proyecto Firebase](resources/imgs/chapter_v/Noxway-firebase-configuracion.png)

*Figura 1. Configuración general del proyecto noxway-frontend utilizado para el alojamiento de la aplicación web.*

**Evidencia de publicación en Firebase Hosting**

![Publicación en Firebase Hosting](resources/imgs/chapter_v/Noxway-firebase-despliegue.png)

*Figura 2. Panel de Firebase Hosting que registra el estado «Implementado» y la publicación realizada el 8 de octubre de 2026.*


#### 5.2.2.8.Team Collaboration Insights during Sprint.

Durante el Sprint 2, el equipo organizó el desarrollo del frontend de Noxway mediante ramas de funcionalidades y la integración de cambios en develop y main. El historial de GitHub registra aportes en la estructura compartida, el dashboard, los contactos de confianza, los trayectos, la comunidad, el bienestar y el módulo Companion.

La siguiente tabla resume los aportes identificados en el historial de commits revisado:

| Integrante | Usuario de GitHub | Aportes registrados |
| :--- | :--- | :--- |
| Cano Gomez, Yam Antony | Yam-1CG | Desarrollo de la estructura visual, navegación y dashboard; configuración y consumo de datos mediante JSON Server. |
| Dextre Flores, Leonardo Felix | leo-dex45 | Desarrollo de los módulos de perfil, contactos de confianza, comunidad, mapa y trayectos, incluyendo modelos y servicios. |
| Patricio Farias, Ana Camila | anacamilapatricio-sketch | Desarrollo de las vistas y servicios de Companion, componentes compartidos y dashboard; integración de develop en main mediante el Pull Request #2. |
| Salcedo Correa, Carlos Matthew | Matthewnhfe | Desarrollo de bienestar y suscripciones; configuración de entornos y conexión con Beeceptor; correcciones de navegación y traducciones. |

**Contribuciones al repositorio**

![Contribuciones del equipo durante el Sprint 2](resources/imgs/chapter_v/Noxway-colaboracion-contributors.png)

*Figura 1. Analíticos de contribución de los integrantes al repositorio Noxway-Frontend.*

**Historial de commits e integración**

![Commits e integración del Sprint 2](resources/imgs/chapter_v/Noxway-colaboracion-commits.png)

*Figura 2. Historial de commits que registra aportes e integración de las funcionalidades desarrolladas durante el Sprint 2.*

### 5.2.3. Sprint 3

#### 5.2.3.1. Sprint Planning 3.

El Sprint Planning 3 se llevó a cabo el 25 de octubre de 2026 y marcó el inicio formal de la fase de implementación del backend transaccional de Noxway. Durante esta reunión, el equipo planificó la transición desde los servicios simulados (JSON Server y Beeceptor utilizados durante el Sprint 2) hacia un RESTful API desarrollado en el lenguaje de programación Java 21 sobre el framework Spring Boot 3, adoptando los principios de Domain-Driven Design (DDD), segregación de comandos y consultas (CQRS), Arquitectura Hexagonal (puertos y adaptadores) y persistencia relacional con PostgreSQL.

El objetivo principal de la iteración fue materializar los cinco Bounded Contexts del sistema (Identity/Profiles, Commuting & Telemetry, Community & Moderation, Sleep Wellness y Subscriptions), asegurando el soporte para las historias técnicas transversales (resolución de actor mediante la cabecera `X-Actor-Id` y manejo estructurado de errores conforme a RFC 9457 Problem Details) y las historias de usuario de negocio asociadas a los trayectos seguros, mapa comunitario 24h, bitácora de descanso y suscripciones con pagos fuera de línea.

| Sprint # | Sprint 3 |
| :--- | :--- |
| **Sprint Planning Background** | |
| **Date** | 2026-10-25 |
| **Time** | 10:00 PM |
| **Location** | Reunión virtual mediante Discord |
| **Prepared By** | Patricio Farias, Ana Camila |
| **Attendees (to planning meeting)** | Patricio Farias, Ana Camila; Cano Gomez, Yam Antony; Dextre Flores, Leonardo Felix; Ramirez Rodriguez, Mauricio Joao; Salcedo Correa, Carlos Matthew |
| **Sprint 2 Review Summary** | Durante el Sprint 2 se concluyó y desplegó la primera versión del Frontend Web en Angular 18 sobre Firebase Hosting, integrando las interfaces del Portal del Trabajador y del Companion Portal con datos simulados vía JSON Server y Beeceptor. Los evaluadores y el Product Owner validaron favorablemente el diseño visual adaptativo y el cumplimiento de las guías de estilo basadas en Material Design, estableciendo como requisito prioritario para el Sprint 3 sustituir los servicios mock por un backend RESTful transaccional con persistencia real en PostgreSQL, que soporte el flujo completo de telemetría de trayectos, mapa de locales 24h, bitácora de descanso y órdenes de suscripción. |
| **Sprint 2 Retrospective Summary** | En la retrospectiva del Sprint 2, el equipo identificó una sólida sinergia en el diseño de interfaces y componentes Angular, pero reconoció la necesidad de coordinar estrictamente los contratos de datos y la arquitectura técnica antes de codificar la lógica del servidor. Se acordó adoptar Domain-Driven Design (DDD) con 4 capas bien delimitadas (Domain, Application, Infrastructure, Interfaces), aislamiento de Bounded Contexts mediante puertos y adaptadores (Arquitectura Hexagonal), estandarizar los códigos de respuesta y detalle de problemas bajo RFC 9457, emplear ramas de funcionalidad (`feature/`) integradas mediante Pull Requests revisados para evitar conflictos de integración, y definir la configuración de despliegue cloud desde etapas tempranas del sprint. |
| **Sprint Goal & User Stories** | |
| **Sprint 3 Goal** | Nuestro enfoque está en diseñar, implementar, documentar y desplegar el RESTful API de backend para la plataforma Noxway utilizando Java 21, Spring Boot y Domain-Driven Design con CQRS, dando soporte integral a los Bounded Contexts de Identity/Profiles, Commuting & Telemetry, Community & Moderation, Sleep Wellness y Subscriptions. Creemos que esto proporciona a los trabajadores nocturnos y a sus contactos de confianza una persistencia segura, telemetría de trayectos en tiempo real, registro de sueño y catálogo de servicios 24h, sustituyendo los servicios simulados por un backend transaccional de alta disponibilidad. Esto se confirmará cuando todos los endpoints RESTful respondan satisfactoriamente con persistencia en base de datos PostgreSQL, se manejen excepciones con el estándar RFC 9457 Problem Details, la documentación interactiva OpenAPI/Swagger esté operativa y el servicio se encuentre desplegado y accesible en la nube mediante Docker.<br><br> |
| **Sprint 3 Velocity** | 26 Story Points |
| **Sum of Story Points** | 25 Story Points |

#### 5.2.3.2. Aspect Leaders and Collaborators.

Para optimizar la comunicación técnica y asegurar una clara distribución de responsabilidades en la construcción del backend, se elaboró la matriz de liderazgo y colaboración (LACX, *Leadership-and-Collaboration Matrix*). En este sprint, cada aspecto corresponde a un Bounded Context o componente estructural crítico de la arquitectura DDD multicapa. Cada integrante asumió el rol de líder (L) en el contexto de su especialidad, encargándose del diseño del modelo de dominio, entidades JPA, mappers, servicios de aplicación y controladores REST, actuando simultáneamente como colaborador (C) en las tareas transversales y de integración.

| Team Member (Last Name, First Name) | GitHub Username | Architecture, IAM & Shared Kernel<br>Leader (L) / Collaborator (C) | Commuting & Telemetry GPS<br>Leader (L) / Collaborator (C) | Community & Moderation 24h<br>Leader (L) / Collaborator (C) | Sleep Wellness<br>Leader (L) / Collaborator (C) | Subscriptions & Payments<br>Leader (L) / Collaborator (C) | Cloud Deployment, Docker & DB<br>Leader (L) / Collaborator (C) |
| :--- | :--- | :---: | :---: | :---: | :---: | :---: | :---: |
| Cano Gomez, Yam Antony | Yam-1CG | L | C | L | C | C | C |
| Patricio Farias, Ana Camila | anc-f4 | C | L | C | C | C | C |
| Dextre Flores, Leonardo Felix | leo-dex45 | C | C | C | C | L | C |
| Ramirez Rodriguez, Mauricio Joao | MauRicio1321m | C | C | C | L | C | C |
| Salcedo Correa, Carlos Matthew | Matthewnhfe | C | C | C | C | L | L |

La organización de la matriz LACX guarda estricta relación con la asignación de tareas en el Sprint Backlog y con el historial de commits verificado en el repositorio del backend:
* **Yam Antony Cano Gomez** lideró la arquitectura base del proyecto, la configuración transversal de seguridad estructurada (IAM), el Shared Kernel y la integración de ramas en develop.
* **Ana Camila Patricio Farias** lideró el Bounded Context de Commuting, abarcando el ciclo de vida de trayectos seguros, telemetría GPS continua y el portal de acompañamiento en vivo (Companion View).
* **Leonardo Felix Dextre Flores** lideró el Bounded Context de Community & Moderation, implementando la cartografía de locales 24h, zonas de riesgo, publicaciones geolocalizadas con OpenStreetMap y moderación administrativa.
* **Mauricio Joao Ramirez Rodriguez** lideró el Bounded Context de Sleep Wellness, diseñando la bitácora de descanso diurno/nocturno, el validador de invariantes contra solapamiento de horarios y el cálculo de déficit de sueño semanal.
* **Carlos Matthew Salcedo Correa** lideró el Bounded Context de Subscriptions & Payments, la conciliación de órdenes de pago offline con verificación de unicidad, el catálogo de beneficios, el manejo global de excepciones RFC 9457, la sincronización de contratos OpenAPI y el empaquetado multi-stage Docker para despliegue en Render y Clever Cloud.

#### 5.2.3.3. Sprint Backlog 3.

El Sprint Backlog 3 reúne las historias técnicas de arquitectura y las historias de usuario de negocio priorizadas para la construcción del backend de Noxway. Cada historia fue descompuesta en tareas técnicas específicas categorizadas por capa arquitectónica (Dominio, Persistencia/Infraestructura, Aplicación/CQRS e Interfaces REST), asignadas a los integrantes según la matriz LACX y gestionadas a través del tablero interactivo del proyecto.

**Tablero del Sprint Backlog en Trello:**
* **URL pública del tablero:** https://trello.com/invite/b/6af8c429e9b2ba2d044ce0d4/ATTIf6dbb9fc0bfcb4a02a4cd4b9418e58f34A4908E7/noxway-sprint-3

![Sprint 03 - Trello](resources/imgs/sprint03.png)

| Sprint # | Sprint 3 | | | | | | |
| :--- | :--- | :--- | :--- | :--- | :---: | :---: | :---: |
| **Story Id** | **Story Title** | **Task Id** | **Task Title** | **Task Description** | **Estimation (Hours)** | **Assigned To** | **Status** |
| **TS-ARCH001** | Resolución de Actor y Estado Estructurado de IAM | TK-01 | Filtro de resolución de actor | Implementar filtro HTTP para extraer la cabecera `X-Actor-Id` y asignar el trabajador principal por defecto en modo desarrollo (`app.security.enabled=false`). | 4 | Yam Cano | Done |
| **TS-ARCH001** | Resolución de Actor y Estado Estructurado de IAM | TK-02 | Endpoints de estado y fallback IAM | Crear endpoint `GET /api/v1/auth/status` y configurar respuestas `501 Not Implemented` localizadas para sign-in/sign-up diferidos. | 3 | Yam Cano | Done |
| **TS-ARCH002** | Manejo Estandarizado de Errores con RFC 9457 | TK-03 | Manejador global de excepciones | Diseñar `GlobalExceptionHandler` que transforme excepciones de negocio y validación en esquemas `ProblemDetail` (RFC 9457). | 4 | Carlos Salcedo | Done |
| **TS-ARCH002** | Manejo Estandarizado de Errores con RFC 9457 | TK-04 | Internacionalización de errores | Configurar soporte bilingüe (`Accept-Language: es/en`) en las descripciones y mensajes de error del manejador global. | 3 | Carlos Salcedo | Done |
| **US-PRO001** | Gestión de Perfil y Turno Laboral | TK-05 | Modelo de dominio y persistencia de perfiles | Modelar agregado `WorkerProfile`, entidad de turno laboral (`WorkShift`), mapeos JPA y adaptador de persistencia. | 4 | Yam Cano | Done |
| **US-PRO001** | Gestión de Perfil y Turno Laboral | TK-06 | Servicios y controladores de cuentas | Implementar servicio de aplicación y controladores REST para consultas y actualizaciones en `GET/PUT /api/v1/accounts/me`. | 4 | Yam Cano | Done |
| **US-PRO002** | Invitación y Ciclo de Vida de Contactos (`TrustLink`) | TK-07 | Reglas de límite de contactos | Modelar agregado `TrustLink`, estados (`PENDING`, `ACTIVE`) e invariante de validación de cupo según plan de suscripción. | 5 | Yam Cano | Done |
| **US-PRO002** | Invitación y Ciclo de Vida de Contactos (`TrustLink`) | TK-08 | Endpoints de vinculación de confianza | Desarrollar endpoints para enviar invitación, listar contactos activos y ejecutar aceptación vía `POST /api/v1/trust-links/{id}/accept`. | 4 | Yam Cano | Done |
| **US-COM001** | Iniciar Trayecto, Registrar Ping GPS y Llegada | TK-09 | Agregado Commute y regla de trayecto único | Crear modelo `Commute`, estados (`ACTIVE`, `DELAYED`, `ARRIVED`) y validación de conflicto ante intentos de trayecto simultáneo. | 6 | Camila Patricio | Done |
| **US-COM001** | Iniciar Trayecto, Registrar Ping GPS y Llegada | TK-10 | Telemetría GPS y ciclo de trayecto | Desarrollar endpoints para registrar pings GPS (`POST /commutes/{id}/telemetry`), reportar demora (`/delay`) y confirmar llegada (`/arrive`). | 5 | Camila Patricio | Done |
| **US-COM002** | Emisión de SOS y Monitoreo Companion | TK-11 | Gestión de incidentes SOS | Implementar modelo de incidentes, despacho de alertas críticas y persistencia de estado de emergencia abierto. | 5 | Camila Patricio | Done |
| **US-COM002** | Emisión de SOS y Monitoreo Companion | TK-12 | Endpoints Companion en vivo | Crear endpoints de consulta en tiempo real `GET /api/v1/companion/live` y `GET /api/v1/companion/alerts` con última coordenada registrada. | 4 | Camila Patricio | Done |
| **US-MAP001** | Exploración de Locales 24h y Votación de Confianza | TK-13 | Entidades de servicio y zonas de riesgo | Modelar agregado `ServicePoint`, entidad `RiskZone`, repositorios JPA y adaptadores de persistencia espacial. | 5 | Leonardo Dextre | Done |
| **US-MAP001** | Exploración de Locales 24h y Votación de Confianza | TK-14 | Algoritmo de trustScore y votación | Desarrollar lógica de cálculo de `trustScore` con votos `+1`, `-1` y retracción de voto (`0`) en `PUT /community/services/{id}/vote`. | 4 | Leonardo Dextre | Done |
| **US-MAP002** | Publicación de Avisos Comunitarios con OpenStreetMap | TK-15 | Publicación de avisos con validación geográfica | Crear endpoint `POST /community/posts` con validación de invariante geográfica (latitud/longitud obligatoriamente en pareja). | 4 | Leonardo Dextre | Done |
| **US-MAP002** | Publicación de Avisos Comunitarios con OpenStreetMap | TK-16 | Enriquecimiento de metadatos de autor | Implementar servicio para inyectar automáticamente el distrito predeterminado ("Lima") y los metadatos del autor activo. | 3 | Leonardo Dextre | Done |
| **US-MOD001** | Moderación Administrativa de Puntos 24h | TK-17 | Cola de moderación y resoluciones | Desarrollar endpoints para listar reportes pendientes (`GET /moderation/reports`) y registrar decisiones (`APPROVED` / `REJECTED`). | 4 | Leonardo Dextre | Done |
| **US-WEL001** | Bitácora de Descanso sin Solapamientos y Meta Diaria | TK-18 | Agregado RestSession y regla antisolapamiento | Modelar agregado `RestSession` con validador de invariante de no superposición horaria para descanso diurno o nocturno. | 5 | Mauricio Ramirez | Done |
| **US-WEL001** | Bitácora de Descanso sin Solapamientos y Meta Diaria | TK-19 | Meta de descanso y resumen semanal | Implementar configuración de meta diaria (240 a 720 min) y cálculo automatizado del promedio semanal y déficit acumulado. | 4 | Mauricio Ramirez | Done |
| **US-SUB001** | Suscripción a Planes, Pagos Offline y Cupones | TK-20 | Modelado de planes y órdenes de pago | Modelar agregado `Subscription`, planes (`ESSENTIAL`, `SENTINEL_PRO`, `FAMILY_CREW`) y ciclo de vida de pagos. | 5 | Carlos Salcedo | Done |
| **US-SUB001** | Suscripción a Planes, Pagos Offline y Cupones | TK-21 | Conciliación de comprobante y beneficios | Implementar confirmación de pago offline con validación de unicidad de referencia bancaria y registro de reclamo de beneficios. | 5 | Carlos Salcedo | Done |
| **TS-DEPL001** | Empaquetado Docker y Despliegue Cloud | TK-22 | Dockerfile multi-stage y pool HikariCP | Configurar Dockerfile multi-etapa (Maven + Temurin 21) y límites del pool HikariCP para bases de datos en Clever Cloud y Render. | 4 | Carlos Salcedo | Done |

#### 5.2.3.4. Development Evidence for Sprint Review.

Durante el transcurso del Sprint 3, el equipo completó la arquitectura y codificación del backend en el repositorio `Noxway-Backend` de la organización `upc-pre-202620-1asi0730-7793` en GitHub. Se aplicó estrictamente el flujo de trabajo GitFlow, ramificando desde `develop` mediante ramas de funcionalidad (`feature/`) y solicitudes de extracción (*Pull Requests*) revisadas.

A continuación, se presenta una selección representativa con los commits más importantes y de mayor impacto arquitectónico registrados en el repositorio del backend durante la iteración, reflejando el progreso estructurado en cada uno de los Bounded Contexts y la integración continua del sistema:

| Repository | Branch | Commit Id | Commit Message | Commit Message Body | Commited on (Date) |
| :--- | :--- | :--- | :--- | :--- | :--- |
| Noxway-Backend | main | 1471c0e | chore: initial commit | Initialize backend repository with root structure and base configuration | 05/11/2026 |
| Noxway-Backend | develop | f53c999 | chore(project): import project structure and configuration | Initialize Spring Boot project structure, Maven dependencies and properties | 05/11/2026 |
| Noxway-Backend | develop | 9a75f2d | chore(identity): import existing shared infrastructure and security | Import shared infrastructure, web configuration and security filters | 05/11/2026 |
| Noxway-Backend | feature/identity-module | 82ed765 | chore(identity): import existing identity domain models | Import identity domain models, user account and credential rules | 05/11/2026 |
| Noxway-Backend | feature/identity-module | 7ce9053 | chore(identity): import existing identity API and access contracts | Import identity REST controllers and security contracts | 05/11/2026 |
| Noxway-Backend | develop | 0752e79 | chore(integration): merge existing identity module import | Merge pull request for identity and access module import | 05/11/2026 |
| Noxway-Backend | feature/commuting-module | a083446 | chore(commuting): import existing first domain model group | Import initial domain aggregates and entities for commuting context | 05/11/2026 |
| Noxway-Backend | feature/commuting-module | 8b16a3a | chore(commuting): import existing persistence adapters | Import persistence adapters implementing repository ports | 05/11/2026 |
| Noxway-Backend | feature/commuting-module | 1abaeff | chore(commuting): import existing API contracts and infrastructure jobs | Import API contracts and infrastructure jobs for commuting context | 05/11/2026 |
| Noxway-Backend | develop | d3d626b | chore(integration): merge existing commuting module import | Merge pull request for commuting module import | 05/11/2026 |
| Noxway-Backend | feature/community-module | 7a0944e | chore(community): import existing first domain model group | Import initial domain models and aggregates for community context | 05/11/2026 |
| Noxway-Backend | feature/community-module | 15ee61f | chore(community): import existing persistence adapters | Import persistence repository adapters for community bounded context | 05/11/2026 |
| Noxway-Backend | feature/community-module | 050ec52 | chore(community): import existing API contracts and infrastructure jobs | Import community REST controllers, resource schemas and jobs | 05/11/2026 |
| Noxway-Backend | develop | ba9fe7b | chore(integration): merge existing community module import | Merge pull request for community module import | 05/11/2026 |
| Noxway-Backend | feature/subscriptions-module | c24c6f4 | chore(subscriptions): import existing first domain model group | Import first domain model group for subscriptions bounded context | 05/11/2026 |
| Noxway-Backend | feature/subscriptions-module | e67d585 | chore(subscriptions): import existing persistence adapters | Import repository persistence adapters for subscriptions | 05/11/2026 |
| Noxway-Backend | feature/subscriptions-module | 8674fe3 | chore(subscriptions): import existing API contracts and infrastructure jobs | Import API controllers and background jobs for subscriptions | 05/11/2026 |
| Noxway-Backend | develop | c022989 | chore(integration): merge existing subscriptions module import | Merge pull request for subscriptions module import | 05/11/2026 |
| Noxway-Backend | feature/wellness-import | 19735b4 | chore(wellness): import existing rest session model and rules | Import rest session domain model and overlap validation rules | 06/11/2026 |
| Noxway-Backend | feature/wellness-import | 31cd0a0 | chore(wellness): import existing rest session repository adapter | Import repository adapter for rest session persistence | 06/11/2026 |
| Noxway-Backend | feature/wellness-import | 8deb273 | chore(wellness): import existing REST controller | Import REST controller for sleep wellness endpoints | 06/11/2026 |
| Noxway-Backend | develop | abbb4b9 | chore(integration): merge feature/wellness-import | Merge pull request for wellness module import into develop | 06/11/2026 |
| Noxway-Backend | develop | 4d6f522 | feat(platform): complete 4-layer DDD, CQRS, ACL and structured IAM backend | Complete 4-layer DDD, CQRS, ACL and structured IAM backend architecture | 13/11/2026 |
| Noxway-Backend | develop | 44ad639 | fix(platform): support vote retraction and disable smtp health check when unconfigured | Support vote retraction (0) and disable SMTP health check when unconfigured | 13/11/2026 |
| Noxway-Backend | feature/global-platform-completion | ce14927 | feat(community): store optional category and coordinates on posts | Support optional category and geographic coordinates on community posts | 13/11/2026 |
| Noxway-Backend | develop | e848a22 | Merge branch 'feature/global-platform-completion' into develop | Merge feature/global-platform-completion into develop branch | 13/11/2026 |
| Noxway-Backend | develop | 498d475 | fix(community): default optional post district and enrich author metadata on creation | Default optional post district and enrich author metadata on post creation | 13/11/2026 |
| Noxway-Backend | develop | cf056f1 | docs: add class diagram, C4 software architecture, user stories, ADRs, and enhanced README | Document class diagram, C4 architecture, user stories, ADRs and README | 13/11/2026 |
| Noxway-Backend | feature/general-audit-and-osm-telemetry | 3e9438e | chore(deploy): add multi-stage Dockerfile and HikariCP pool limits for Render and Clever Cloud | Add multi-stage Dockerfile and configure HikariCP pool limits for deployment on Render and Clever Cloud | 14/11/2026 |
| Noxway-Backend | develop | a6503c1 | Merge branch 'feature/general-audit-and-osm-telemetry' into develop | Merge feature/general-audit-and-osm-telemetry into develop branch | 14/11/2026 |


#### 5.2.3.5. Execution Evidence for Sprint Review.

En esta sección se presentan las evidencias de ejecución y comportamiento en tiempo de ejecución del backend de Noxway, demostrando la operatividad de los servicios RESTful en concordancia con los criterios de aceptación de las historias de usuario y técnicas desarrolladas en el Sprint 3.

Las pruebas de ejecución fueron llevadas a cabo mediante solicitudes HTTP sobre Postman y la consola interactiva de Swagger UI, verificando la persistencia transaccional en la base de datos relacional PostgreSQL (instancia en Clever Cloud) y la adhesión al estándar RFC 9457 Problem Details en los escenarios de excepción.

**1. Inicio de la aplicación Spring Boot y conexión de persistencia**
El servidor inicia correctamente en el puerto 8080. El pool de conexiones HikariCP se inicializa apuntando a la base de datos PostgreSQL remota, validando los esquemas relacionales y mapeando las entidades JPA correspondientes a cada Bounded Context.


**2. Resolución de Actor y Estado de Seguridad IAM**
Al consultar el estado del módulo de autenticación mediante `GET /api/v1/auth/status`, el servicio responde con código `200 OK` indicando el modo estructurado y el identificador del trabajador asignado por defecto para el entorno de desarrollo. Asimismo, al invocar operaciones diferidas como `POST /api/v1/auth/sign-in`, el sistema emite un código `501 Not Implemented` con el estándar RFC 9457 localizado según la cabecera `Accept-Language: es`.


**3. Gestión de Ficha Operativa y Turno Laboral**
El trabajador nocturno actualiza su horario de jornada nocturna y datos de contacto mediante `PUT /api/v1/accounts/me`, recibiendo una confirmación `200 OK` con los datos actualizados y sincronizados con su cuenta.


**4. Invitación y Ciclo de Vida de Contactos de Confianza**
El trabajador invita a un contacto registrado mediante `POST /api/v1/trust-links`. Si el plan del trabajador supera el límite permitido (por ejemplo, más de 1 contacto en plan `ESSENTIAL`), el API rechaza la solicitud con `422 Unprocessable Entity`. Al recibir la invitación, el contacto destinatario la acepta invocando `POST /api/v1/trust-links/{id}/accept`.


**5. Iniciar Trayecto Seguro y Telemetría GPS**
El trabajador inicia un trayecto hacia su centro laboral. La regla de invariante previene la apertura simultánea de dos trayectos activos, respondiendo `409 Conflict` si existiera uno previo sin culminar. Una vez iniciado, la aplicación móvil envía pings periódicos de telemetría geolocalizada.


**6. Monitoreo en Vivo de Companion y Alerta SOS**
El contacto de confianza consulta el estado en tiempo real mediante `GET /api/v1/companion/live`. Cuando el trabajador dispara un evento de emergencia mediante `POST /api/v1/commutes/{id}/incidents` con `type: "SOS"`, el incidente se propaga de inmediato al canal de alertas del acompañante.


**7. Exploración de Locales 24h y Votación de Confianza**
Los usuarios consultan puntos de servicio nocturno aprobados y votan favorablemente (+1), desfavorablemente (-1) o retiran su voto (0), recalculando automáticamente el `trustScore` y reflejando las métricas consolidadas.


**8. Publicación Comunitaria con Coordenadas OpenStreetMap**
Un usuario publica un aviso de seguridad marcando la ubicación en el mapa. Si se proporciona una coordenada incompleta (latitud sin longitud), el API rechaza la petición con código `422 Unprocessable Entity` bajo el estándar RFC 9457.


**9. Bitácora de Descanso y Validación contra Solapamiento**
Un trabajador registra una sesión de descanso diurno. Al intentar registrar una segunda sesión que se solape con el mismo rango horario, el dominio bloquea el registro para preservar la coherencia biológica emitiendo un error `422 Unprocessable Entity`.


**10. Suscripción y Conciliación de Pago Offline**
Un trabajador suscribe el plan `SENTINEL_PRO` y genera una orden de pago. El administrador concilia el comprobante bancario vía `POST /api/v1/payments/{id}/confirm-offline`. Si otra orden intenta reutilizar el mismo número de recibo (`"YAPE-987654"`), el sistema responde `409 Conflict`.


#### 5.2.3.6. Services Documentation Evidence for Sprint Review.

La documentación de los servicios web del backend de Noxway se generó automáticamente utilizando **OpenAPI Specification 3.0** mediante la biblioteca `springdoc-openapi-starter-webmvc-ui` (Swagger UI). Esta herramienta expone una consola interactiva donde es posible examinar la especificación de esquemas de datos, cabeceras requeridas (`X-Actor-Id`, `Accept-Language`), códigos de estado HTTP y ejecutar solicitudes de prueba en tiempo real.

**Enlaces de acceso a la documentación OpenAPI / Swagger UI:**
* **URL de documentación local:** http://localhost:8080/swagger-ui.html
* **Especificación OpenAPI:** https://noxway-backend.onrender.com/swagger-ui.html
* **Repositorio de Web Services:** https://github.com/upc-pre-202620-1asi0730-7793/Report.git

A continuación, se detalla la matriz completa de endpoints expuestos por el backend, indicando las acciones, verbos HTTP, rutas, parámetros, esquemas de respuesta y códigos de estado conforme a la especificación implementada:

| Acción | Método HTTP | Ruta del Endpoint | Parámetros / Cuerpo de Solicitud | Ejemplo de Respuesta (JSON) | Explicación y Códigos de Estado |
| :--- | :---: | :--- | :--- | :--- | :--- |
| Consultar estado IAM | GET | `/api/v1/auth/status` | Ninguno (Cabecera opcional `Accept-Language`) | `{"securityEnabled":false,"mode":"STRUCTURED_PENDING_IMPLEMENTATION","defaultWorkerId":"00000000-0000-0000-0000-000000000101"}` | Informa el estado del subsistema de autenticación y el actor predeterminado. `200 OK`. |
| Autenticación diferida | POST | `/api/v1/auth/sign-in` | `{"email":"...","password":"..."}` | `{"type":"https://api.noxway.pe/problems/not-implemented","status":501,"title":"Not Implemented"}` | Endpoint de inicio de sesión diferido. Responde `501 Not Implemented` con esquema RFC 9457. |
| Consultar cuenta de usuario | GET | `/api/v1/accounts/me` | Cabecera obligatoria `X-Actor-Id` | `{"id":"...","fullName":"Jorge Huamán","shiftType":"NIGHT","timeZone":"America/Lima"}` | Recupera el perfil operativo y preferencias de turno del trabajador autenticado. `200 OK`, `404 Not Found`. |
| Actualizar turno y perfil | PUT | `/api/v1/accounts/me` | `{"fullName":"...","phone":"...","shiftType":"NIGHT","shiftStart":"22:00:00","shiftEnd":"06:00:00","timeZone":"America/Lima"}` | `{"id":"...","fullName":"...","shiftType":"NIGHT","updatedAt":"..."}` | Actualiza la información operativa y de contacto del trabajador. `200 OK`, `400 Bad Request`. |
| Listar contactos de confianza | GET | `/api/v1/trust-links` | Cabecera obligatoria `X-Actor-Id` | `[{"id":"...","contactEmail":"rosa@noxway.pe","status":"ACTIVE","relationship":"FAMILY"}]` | Retorna los vínculos de confianza creados por el trabajador. `200 OK`. |
| Invitar contacto de confianza | POST | `/api/v1/trust-links` | `{"contactEmail":"rosa.paredes@noxway.pe","relationship":"FAMILY"}` | `{"id":"...","contactEmail":"rosa.paredes@noxway.pe","status":"PENDING"}` | Crea una invitación de confianza validando cupos del plan. `201 Created`, `422 Unprocessable Entity` (límite superado). |
| Aceptar vínculo de confianza | POST | `/api/v1/trust-links/{id}/accept` | Parámetro de ruta: `id` (UUID del vínculo) | `{"id":"...","status":"ACTIVE","acceptedAt":"2026-11-14T..."}` | El contacto acepta la invitación y habilita el monitoreo. `200 OK`, `404 Not Found`. |
| Eliminar vínculo de confianza | DELETE | `/api/v1/trust-links/{id}` | Parámetro de ruta: `id` (UUID del vínculo) | Ninguno (Cuerpo vacío) | Revoca el enlace de supervisión mutua. `204 No Content`, `404 Not Found`. |
| Iniciar trayecto seguro | POST | `/api/v1/commutes` | `{"origin":"Sede Central","destination":"Av. Javier Prado 1200","estimatedMinutes":35}` | `{"id":"...","status":"ACTIVE","startedAt":"...","estimatedArrival":"..."}` | Registra el inicio de un desplazamiento. Rechaza con `409 Conflict` si ya existe un trayecto en curso. `201 Created`. |
| Consultar trayecto activo | GET | `/api/v1/commutes/active` | Cabecera obligatoria `X-Actor-Id` | `{"id":"...","status":"ACTIVE","lastPing":{"latitude":-12.086,"longitude":-77.034}}` | Recupera el trayecto abierto del trabajador. `200 OK`, `404 Not Found`. |
| Registrar telemetría GPS | POST | `/api/v1/commutes/{id}/telemetry` | `{"latitude":-12.086432,"longitude":-77.034521,"speed":24.5,"batteryLevel":88,"recordedAt":"..."}` | `{"id":"...","latitude":-12.086432,"longitude":-77.034521,"recordedAt":"..."}` | Persiste las coordenadas GPS y métricas de desplazamiento del trayecto. `201 Created`, `404 Not Found`. |
| Reportar demora en trayecto | POST | `/api/v1/commutes/{id}/delay` | `{"extraMinutes":15,"reason":"Congestión vehicular nocturna"}` | `{"id":"...","status":"DELAYED","newEstimatedArrival":"..."}` | Modifica el tiempo estimado de llegada y notifica a los contactos. `200 OK`. |
| Confirmar llegada segura | POST | `/api/v1/commutes/{id}/arrive` | `{"arrivedAt":"2026-11-14T23:40:00Z","rating":5}` | `{"id":"...","status":"ARRIVED","completedAt":"..."}` | Finaliza el trayecto seguro con confirmación de éxito. `200 OK`. |
| Emitir incidente SOS | POST | `/api/v1/commutes/{id}/incidents` | `{"type":"SOS","latitude":-12.086432,"longitude":-77.034521,"notes":"Alerta de pánico"}` | `{"id":"...","type":"SOS","status":"OPEN","reportedAt":"..."}` | Abre un incidente crítico y dispara alertas inmediatas al Companion Portal. `201 Created`. |
| Consultar seguimiento Companion | GET | `/api/v1/companion/live` | Cabecera obligatoria `X-Actor-Id` (contacto de confianza) | `{"workerName":"Jorge Huamán","commuteStatus":"ACTIVE","lastPing":{"lat":-12.086,"lng":-77.034}}` | Provee al contacto de confianza la posición GPS en vivo del trabajador vinculado. `200 OK`. |
| Consultar alertas de acompañante | GET | `/api/v1/companion/alerts` | Cabecera obligatoria `X-Actor-Id` | `[{"id":"...","type":"SOS","workerName":"Jorge Huamán","status":"OPEN","createdAt":"..."}]` | Retorna los eventos e incidentes generados durante los trayectos supervisados. `200 OK`. |
| Listar servicios 24h del mapa | GET | `/api/v1/community/services` | Parámetros opcionales: `category`, `district`, `openOnly` | `[{"id":"...","name":"Mifarma 24h","category":"PHARMACY","trustScore":92.5,"lat":-12.08,"lng":-77.03}]` | Retorna los locales nocturnos verificados y su puntuación comunitaria. `200 OK`. |
| Calificar servicio (voto) | PUT | `/api/v1/community/services/{id}/vote` | `{"direction":1}` (Valores permitidos: `1`, `-1`, `0`) | `{"serviceId":"...","trustScore":92.5,"upvotes":38,"downvotes":3,"myVote":1}` | Registra o retira el voto de veracidad comunitaria. `200 OK`, `400 Bad Request`. |
| Listar zonas de riesgo | GET | `/api/v1/community/risk-zones` | Parámetros opcionales: `district` | `[{"id":"...","title":"Zona con poca iluminación","severity":"HIGH","lat":-12.09,"lng":-77.04}]` | Consulta las zonas de alerta reportadas por la comunidad. `200 OK`. |
| Listar avisos comunitarios | GET | `/api/v1/community/posts` | Parámetros opcionales: `category`, `district`, `page`, `size` | `[{"id":"...","title":"Aviso de patrullaje","category":"SEGURIDAD","authorName":"Jorge H.","upvotes":14}]` | Consulta las publicaciones del tablón vecinal y alertas nocturnas. `200 OK`. |
| Publicar aviso geolocalizado | POST | `/api/v1/community/posts` | `{"title":"...","content":"...","category":"Zona de riesgo","latitude":-12.0789,"longitude":-77.034}` | `{"id":"...","title":"...","authorName":"...","latitude":-12.0789,"longitude":-77.034,"createdAt":"..."}` | Publica un aviso en el mapa. Rechaza con `422 Unprocessable Entity` si las coordenadas están incompletas. `201 Created`. |
| Listar reportes de moderación | GET | `/api/v1/moderation/reports` | Parámetros opcionales: `status=PENDING` | `[{"id":"...","targetType":"SERVICE_POINT","reason":"Local clausurado","status":"PENDING"}]` | Permite a administradores revisar la cola de denuncias o solicitudes pendientes. `200 OK`, `403 Forbidden`. |
| Decidir reporte de moderación | POST | `/api/v1/moderation/reports/{id}/decision` | `{"decision":"APPROVED","comment":"Verificación en campo efectuada"}` | `{"id":"...","status":"RESOLVED","decision":"APPROVED","decidedAt":"..."}` | Aplica una resolución administrativa (`APPROVED` o `REJECTED`). `200 OK`. |
| Registrar sesión de descanso | POST | `/api/v1/wellness/rest-sessions` | `{"startTime":"...","endTime":"...","qualityRating":4,"notes":"..."}` | `{"id":"...","durationMinutes":360,"efficiencyPercentage":85}` | Registra un bloque de descanso. Rechaza con `422 Unprocessable Entity` ante solapamiento de horarios. `201 Created`. |
| Listar descansos del usuario | GET | `/api/v1/wellness/rest-sessions` | Cabecera obligatoria `X-Actor-Id` | `[{"id":"...","startTime":"...","endTime":"...","durationMinutes":360}]` | Obtiene el historial de registros de sueño del trabajador. `200 OK`. |
| Configurar meta de sueño | PUT | `/api/v1/wellness/goal` | `{"dailyTargetMinutes":480}` (Rango válido: 240 a 720 min) | `{"dailyTargetMinutes":480,"weeklyTargetMinutes":3360,"updatedAt":"..."}` | Actualiza la meta diaria de sueño del trabajador. `200 OK`, `400 Bad Request`. |
| Consultar resumen semanal | GET | `/api/v1/wellness/summary` | Cabecera obligatoria `X-Actor-Id` | `{"weeklyAverageMinutes":410,"accumulatedDeficitMinutes":70,"suggestedHabits":["...", "..."]}` | Calcula métricas consolidadas de sueño y sugerencias de higiene del descanso. `200 OK`. |
| Listar planes de suscripción | GET | `/api/v1/subscriptions/plans` | Ninguno | `[{"id":"SENTINEL_PRO","name":"Centinela Pro","price":19.90,"maxTrustContacts":5}]` | Retorna el catálogo de planes comerciales disponibles. `200 OK`. |
| Crear orden de suscripción | POST | `/api/v1/subscriptions` | `{"planId":"SENTINEL_PRO","referralCode":"CARLOS-REF1"}` | `{"id":"...","planId":"SENTINEL_PRO","status":"PENDING_PAYMENT","amount":19.90}` | Inicia el proceso de suscripción a un plan. `201 Created`. |
| Generar orden de pago offline | POST | `/api/v1/subscriptions/{id}/payments` | `{"paymentMethod":"YAPE_OFFLINE","amount":19.90}` | `{"id":"...","subscriptionId":"...","status":"PENDING","instructions":"Transferir a..."}` | Genera una orden de abono bancario/billetera digital fuera de línea. `201 Created`. |
| Confirmar pago offline | POST | `/api/v1/payments/{id}/confirm-offline` | `{"reference":"YAPE-987654"}` | `{"id":"...","status":"CONFIRMED","subscriptionStatus":"ACTIVE","confirmedAt":"..."}` | Valida el comprobante bancario garantizando unicidad de referencia (`409 Conflict` ante duplicados) y activa la suscripción. `200 OK`. |
| Listar catálogo de beneficios | GET | `/api/v1/benefits` | Cabecera opcional `X-Actor-Id` | `[{"id":"...","partnerName":"Grifo Primax 24h","discount":"15% en cafetería nocturna"}]` | Consulta los convenios y recompensas activas para suscriptores. `200 OK`. |
| Canjear beneficio de suscripción | POST | `/api/v1/benefits/{id}/claims` | Cabecera obligatoria `X-Actor-Id` | `{"id":"...","benefitId":"...","claimCode":"NOX-PRIMAX-8821","expiresAt":"..."}` | Emite un cupón o código de descuento exclusivo según el plan activo. `201 Created`, `422 Unprocessable Entity`. |

#### 5.2.3.7. Software Deployment Evidence for Sprint Review.

El despliegue de los servicios del backend se diseñó bajo una infraestructura basada en la nube de alta disponibilidad, empleando contenedores Linux y servicios gestionados para garantizar escalabilidad, seguridad y persistencia transaccional.

**1. Plataformas en la nube utilizadas:**
* **Base de datos relacional:** **Clever Cloud**, alojando una instancia dedicada de **PostgreSQL 16**. Proporciona respaldo automático, cifrado en reposo y métricas de salud en tiempo real.
* **Plataforma de despliegue de aplicaciones:** **Render Cloud Platform**, alojando el servicio web containerizado a partir de una imagen Docker construida mediante integración continua conectada al repositorio de GitHub.

**2. Empaquetado mediante Dockerfile multi-etapa (*Multi-stage build*):**
Para optimizar el tamaño de la imagen final y garantizar que las herramientas del compilador no se expongan en el entorno de ejecución, se configuró un archivo `Dockerfile` en dos etapas:
* **Etapa 1 (Builder):** Emplea la imagen `maven:3.9.6-eclipse-temurin-21-alpine` para descargar dependencias, compilar el código fuente Java 21 y generar el archivo binario empaquetado (`noxway-platform-1.0.0.jar`), omitiendo pruebas unitarias pesadas durante la etapa de empaquetado final (`-DskipTests`).
* **Etapa 2 (Runtime):** Utiliza una imagen ligera `eclipse-temurin:21-jre-alpine`, asigna un usuario de sistema sin privilegios de administrador (`appuser:appgroup`), expone el puerto estándar `8080` y ejecuta la aplicación mediante el comando de inicio optimizado para contenedores.


**3. Configuración de variables de entorno y límites de conexión HikariCP:**
En el panel de administración de Render se definieron las variables de entorno seguras para la conexión hacia la base de datos remota, incluyendo el perfil activo (`SPRING_PROFILES_ACTIVE=prod`), la URL JDBC de conexión, credenciales de acceso seguras, el puerto de escucha (`SERVER_PORT=8080`) y el límite máximo del pool HikariCP (`SPRING_DATASOURCE_HIKARI_MAXIMUM_POOL_SIZE=5`) implementado en el commit `3e9438e` para preservar los descriptores de conexión en los entornos sandbox de Clever Cloud y Render.

**4. Evidencias del despliegue en la nube:**

![Backend](resources/imgs/backendsprint3.png)

![Frontend](resources/imgs/firebasesprint3.png)


**5. Direcciones públicas de acceso:**
* **API Base URL:** https://noxway-backend.onrender.com/swagger-ui.html
  


#### 5.2.3.8. Team Collaboration Insights during Sprint.

Durante el Sprint 3, la dinámica de trabajo colaborativo se concentró en la construcción coordinada de la solución de backend, garantizando que cada miembro del equipo asumiera la responsabilidad de un Bounded Context y de los contratos de interacción correspondientes. Se implementó una política estricta de branches bajo el modelo GitFlow, donde ninguna modificación fue incorporada directamente sobre la rama `main` ni sobre `develop` sin pasar previamente por revisión de código y validación de compatibilidad con los demás módulos.

La siguiente tabla resume los aportes específicos de cada integrante registrados en el repositorio `Noxway-Backend` a lo largo de la iteración:

| Integrante | Usuario de GitHub | Aportes Registrados en el Backend |
| :--- | :--- | :--- |
| **Cano Gomez, Yam Antony** | `Yam-1CG` | Inicialización del proyecto Spring Boot y configuración base de dependencias Maven; modelado de dominio, entidades JPA, mappers y adaptadores de persistencia de Identity; configuración transversal de seguridad estructurada (IAM) y Shared Kernel; gestión de integración de ramas en develop mediante Pull Requests (merges de identity, community, commuting, subscriptions y wellness). |
| **Patricio Farias, Ana Camila** | `anc-f4` | Diseño e implementación completa del Bounded Context de Commuting; modelos de agregados de trayectos (`Commute`) y pings de telemetría GPS; contratos de repositorio y servicios de dominio; entidades JPA y repositorios Spring Data; mappers y adaptadores de persistencia; comandos y servicios de aplicación CQRS; controladores REST y contratos de API para inicio, seguimiento, demoras, llegadas y monitoreo en vivo de Companion. |
| **Dextre Flores, Leonardo Felix** | `leo-dex45` | Diseño e implementación del Bounded Context de Community & Moderation; modelos de dominio para puntos de servicio 24h, zonas de riesgo y publicaciones comunitarias; entidades JPA, repositorios y adaptadores de persistencia; servicios de aplicación para cálculo de `trustScore` y votación ciudadana; controladores REST y contratos de API con integración espacial de coordenadas para OpenStreetMap y OpenFreeMap. |
| **Ramirez Rodriguez, Mauricio Joao** | `MauRicio1321m` | Diseño e implementación del Bounded Context de Sleep Wellness; modelos de dominio de sesiones de descanso diurno/nocturno con reglas invariantes contra solapamiento temporal y metas diarias de descanso; entidades JPA, repositorios Spring Data y mappers; comandos y servicios de aplicación CQRS; controlador REST para registro de descanso, metas y resumen de déficit semanal. |
| **Salcedo Correa, Carlos Matthew** | `Matthewnhfe` | Diseño e implementación del Bounded Context de Subscriptions & Payments (órdenes de pago offline, activación de membresías Centinela Pro y cupones de beneficios); consolidación de la arquitectura 4-capas DDD, CQRS y ACL; manejo estandarizado de excepciones RFC 9457 Problem Details; documentación integral OpenAPI/Swagger; configuración de Dockerfile multi-stage y límites HikariCP para el despliegue en Render y Clever Cloud. |

**Evidencias de analíticos de colaboración en GitHub:**

![Insight](resources/imgs/insightsprint3.png)

## 5.3. Validation Interviews

En esta sección se documentan y detallan las actividades correspondientes a las sesiones de validación realizadas con usuarios representativos de los segmentos objetivo de **Noxway**. El propósito de estas pruebas es evaluar la comprensión del modelo de negocio, la usabilidad, la arquitectura de la información y el diseño inclusivo (internacionalización `i18n` en inglés/español y accesibilidad `a11y` con modo Día/Noche) tanto en el **Landing Page** como en la **Web Application**, la cual comprende el **Portal del Trabajador** y el **Portal del Contacto de Confianza (Companion Portal)**.

### 5.3.1. Diseño de entrevistas

Para estructurar las sesiones de validación de manera consistente y objetiva, el equipo definió un protocolo de prueba centrado en la ejecución de tareas (*task-based usability testing*) aplicando la técnica de pensamiento en voz alta (*Think-Aloud Protocol*), complementado con un banco de preguntas abiertas de cierre para recoger apreciaciones cualitativas sobre cada flujo interactuado.

#### Estructura de la sesión de validación

1. **Bienvenida y contexto:** Explicación del propósito de la sesión de validación (evaluar la experiencia de uso de **Noxway**) y confirmación del consentimiento para registrar la prueba en video con fines académicos.
2. **Identificación del participante:** Registro de nombres y apellidos, edad, distrito de residencia, ocupación y relación con el segmento objetivo evaluado.
3. **Interacción con el Landing Page:** Navegación libre y guiada por el sitio web estático para validar la propuesta de valor, las secciones informativas, la tabla de planes y el direccionamiento hacia la aplicación web mediante los botones *call-to-action* (CTA).
4. **Ejecución de User Flows en la Web Application:** Desarrollo de tareas representativas del *core business* dentro del portal correspondiente a su perfil, alternando entre el Portal del Trabajador y el Companion Portal según el segmento.
5. **Ronda de preguntas de validación:** Respuesta a las 5 preguntas estandarizadas del segmento para recoger observaciones sobre usabilidad, arquitectura de información y diseño inclusivo.

#### Segmento Objetivo 1: Trabajadores de Turno Nocturno y Rotativo (*Night & Rotating Shift Workers*)

* **Elementos incluidos en la sesión:** Landing Page (`Hero`, `How it Works`, `Features`, `Platform & Team Videos`, `Testimonials`, `Pricing`, `FAQ`) y Web Application – Portal del Trabajador (`Dashboard`, `Mi Trayecto`, `Mapa 24h`, `Comunidad`, `Bienestar & Sueño`, `Beneficios & Planes`, `Contactos Confianza`, `Mi Perfil` y botón `Estado SOS`).
* **User Flows validados en la sesión:**
  * **UF-LP-01 (Exploración del Landing Page y redirección):** Revisión de la propuesta de valor, cambio de idioma (`EN`/`ES`), comparación de los planes (*Essential*, *Sentinel Pro*, *Family Crew*) y acceso a la Web Application desde el *call-to-action* principal.
  * **UF-WK-01 (Registro de trayecto activo, check-in seguro y alerta SOS):** Ingreso a `Mi Trayecto`, registro de origen, destino y medio de transporte (motocicleta, auto o transporte público), activación del monitoreo con telemetría GPS, revisión del historial de desplazamientos y verificación del botón permanente `Estado SOS`.
  * **UF-WK-02 (Búsqueda de locales seguros y reporte en el Mapa 24h):** Uso de filtros por categoría (`Farmacias`, `Supermercados`, `Grifos`, `Puntos Noxway 24h`, `Zonas de riesgo`), activación de `Solo abiertos 24 horas`, consulta del listado lateral por distancia y uso de los botones `Reportar local` y `Reportar peligro`.
  * **UF-WK-03 (Consulta y publicación de avisos en la Comunidad):** Filtrado de reportes comunitarios por distrito (Lima Centro, Miraflores, Lince, etc.), lectura de alertas sobre neblina o patrullaje de serenazgo y creación de un nuevo aviso comunitario.
  * **UF-WK-04 (Gestión de descanso en Bienestar & Sueño):** Consulta de métricas de los últimos 7 días (horas promedio, deuda de sueño y calidad), registro de una sesión de descanso post-turno y actualización de la meta diaria de sueño.
  * **UF-WK-05 (Suscripción a planes, canje de beneficios e invitación de contactos):** Revisión del catálogo de planes en `Beneficios & Planes`, registro de código de pago offline (`Yape/Plin/Agente`), canje de cupones colectivos (auxilio vial, farmacias, grifos) y envío de invitación por correo electrónico en `Contactos Confianza`.

* **Preguntas de validación aplicadas al Segmento 1:**
  1. Al explorar la página principal de **Noxway**, ¿qué tan claro te resultó entender los beneficios que ofrece, comparar los planes de suscripción y entrar a tu portal de trabajador?
  2. Cuando probaste iniciar tu ruta hacia casa indicando tu punto de partida, destino y medio de transporte, ¿qué tan rápido y sencillo te pareció activar el recorrido y ubicar el botón rojo de emergencia (`Estado SOS`)?
  3. Al buscar lugares abiertos de madrugada (como farmacias o grifos) en el mapa y revisar los avisos de otros trabajadores por distrito, ¿sentiste que la información está bien organizada y es fácil de filtrar?
  4. ¿Qué te pareció la sección para anotar tus horas de sueño después del turno y qué tan fácil fue revisar los descuentos o invitar a un familiar como contacto de confianza?
  5. Pensando en que usarías la plataforma de noche y con cansancio acumulado, ¿qué opinas de los colores del modo oscuro (`Noche`/`Día`), el cambio de idioma (`ES`/`EN`) y qué detalle mejorarías para tu uso diario?

#### Segmento Objetivo 2: Contactos de Confianza y Familiares (*Trusted Contacts / Family Companions*)

* **Elementos incluidos en la sesión:** Landing Page (`Hero`, `Testimonials`, `Pricing`, `FAQ`) y Web Application – Companion Portal (`Monitoreo en Vivo`, `Historial de Rutas`, `Avisos & Alertas`, `Auxilio & Serenazgo`, `Invitaciones` y `Mi Perfil de Contacto`).
* **User Flows validados en la sesión:**
  * **UF-LP-02 (Revisión del enfoque familiar en el Landing Page):** Exploración de testimonios, revisión de cobertura grupal (*Family Crew*), lectura de preguntas frecuentes y acceso al portal de acompañamiento.
  * **UF-TC-01 (Aceptación de vínculo de confianza):** Acceso a la vista `Invitaciones`, verificación de solicitudes enviadas por trabajadores (nombre, correo y tipo de turno) y aceptación del vínculo de confianza.
  * **UF-TC-02 (Monitoreo en vivo e historial de rutas):** Supervisión en `Monitoreo en Vivo` del estado actual de los trabajadores acompañados (en ruta activa con ETA y medio de transporte, o en reposo) y revisión cronológica de llegadas seguras en `Historial de Rutas`.
  * **UF-TC-03 (Configuración de canales y gestión de cola de alertas):** Revisión en `Avisos & Alertas` del listado de notificaciones (`IN_APP`, `WHATSAPP`, `EMAIL`), habilitación de canales y horarios de recepción (incluyendo SMS) y uso de `Reintentar` o `Despachar Pendientes` en la cola de entregas.
  * **UF-TC-04 (Consulta del directorio de Auxilio y Serenazgo):** Verificación del estado de incidentes SOS activos y acceso rápido a las líneas oficiales de emergencia en el Perú (Policía `105`, SAMU `106`, Bomberos `116`, Serenazgo de Lima `01-318-5050` y Línea `100`).

* **Preguntas de validación aplicadas al Segmento 2:**
  1. Al ver la página informativa de **Noxway** y luego entrar a la sección de `Invitaciones` para aceptar acompañar a tu familiar, ¿qué tan claro y sencillo te pareció todo el proceso inicial?
  2. Al revisar la pantalla de `Monitoreo en Vivo`, ¿lograste identificar rápido si tu familiar está en camino, en qué transporte va y a qué hora llega, así como consultar sus viajes pasados en el historial?
  3. Dentro del centro de avisos (`Avisos & Alertas`), ¿qué tan fácil fue entender por qué medio te llegan las alertas (WhatsApp, correo o dentro de la web) y cómo reintentar un envío si alguno falló?
  4. Si ocurriera algún imprevisto en la madrugada, ¿qué tan útil y accesible te parece tener el directorio de emergencias (Policía 105, SAMU 106, Bomberos 116 y Serenazgo) dentro de la misma pantalla?
  5. ¿Te resultó cómodo moverte por el menú lateral, cambiar entre el modo `Día`/`Noche` o el idioma, y qué cambiarías o agregarías para sentir aún más tranquilidad cuando tu familiar regresa de noche?

---

### 5.3.2. Registro de Entrevistas

A continuación, se presenta el consolidado en video y el registro detallado de las 6 entrevistas de validación realizadas.
---

#### Segmento Objetivo 1: Trabajadores de Turno Nocturno

##### Entrevista de Validación #1 – Segmento 1

| Campo | Detalle |
| :--- | :--- |
| **Nombres y Apellidos** | Luis Mendoza Miranda |
| **Edad** | 32 años |
| **Distrito** | San Martín de Porres |
| **Segmento Objetivo** | Trabajadores de Turno Nocturno (Agente de seguridad privada – ruta San Isidro a San Martín de Porres) |
| **Fecha de entrevista** | 14/11/2026 |
| **URL del Video (Stream)** | `[Colocar URL de Microsoft Stream]` |
| **Timing de Inicio** | `00:00` |
| **Duración** | `04:15` |

![Captura Entrevista 1 - Luis Mendoza Miranda](path/to/screenshot-validation-1.png)

**Resumen descriptivo de apreciaciones:**
Durante la sesión de validación, Luis Mendoza Miranda interactuó inicialmente con el **Landing Page**, señalando que desde el primer vistazo se comprende que la plataforma está pensada para quienes trabajan de madrugada y que las tarjetas informativas junto con los precios en soles (como el plan *Centinela Pro*) permiten ingresar de forma directa a la aplicación web mediante el botón principal. Al ejecutar el flujo de inicio de ruta en la vista `Mi Trayecto`, destacó la rapidez para registrar su punto de partida en San Isidro hacia su domicilio en San Martín de Porres al salir cansado de su turno de seguridad privada, resaltando además que el botón rojo de `Estado SOS` permanece visible en todo momento en la esquina inferior izquierda, lo que brinda tranquilidad en recorridos largos. En la prueba del `Mapa 24h` y `Comunidad`, calificó como excelente el filtro de establecimientos abiertos las 24 horas para ubicar grifos o locales seguros en ruta, así como el filtrado por distritos (San Isidro y San Martín de Porres) para revisar avisos sobre calles oscuras o patrullaje activo. Respecto a `Bienestar & Sueño` y `Beneficios & Planes`, valoró el gráfico semanal para organizar su descanso tras las guardias nocturnas, las opciones de descuentos y la rapidez para invitar a un familiar por correo en `Contactos Confianza`. Finalmente, destacó el alivio visual del modo `Noche` y la respuesta inmediata del cambio de idioma (`ES`/`EN`), sugiriendo como mejora poder guardar rutas habituales (como "San Isidro - San Martín de Porres") para activarlas con un solo toque al salir del trabajo.

---

##### Entrevista de Validación #2 – Segmento 1

| Campo | Detalle |
| :--- | :--- |
| **Nombres y Apellidos** | Drago Duarte |
| **Edad** | 24 años |
| **Distrito** | Chorrillos |
| **Segmento Objetivo** | Trabajadores de Turno Nocturno (Trabajador de turno de madrugada en tienda Tambo – Chorrillos) |
| **Fecha de entrevista** | 14/11/2026 |
| **URL del Video (Stream)** | https://www.youtube.com/watch?v=feB3KrqfYXc |
| **Timing de Inicio** | 0:00 |
| **Duración** | 10:00 |

![Captura Entrevista 2 - Drago Duarte](resources/imgs/dragoduarte.png)

**Resumen descriptivo de apreciaciones:**
Drago Duarte evaluó el **Landing Page** resaltando el orden con el que se presenta el proceso desde la salida del turno hasta la llegada segura a casa, así como la claridad de las preguntas frecuentes y el atractivo del plan *Cuadrilla Familiar* para compartirlo con compañeros de trabajo. Al interactuar con el **Portal del Trabajador**, indicó que el `Dashboard` ofrece un resumen claro de su estado y que la vista `Mi Trayecto` le permitió registrar su salida desde la tienda Tambo en Chorrillos en pocos segundos, brindándole confianza que el historial guarde la hora exacta de salida y llegada junto al botón `Estado SOS` siempre visible sobre el fondo oscuro. Durante la validación de las vistas `Mapa 24h` y `Comunidad`, enfatizó la utilidad de publicar y leer reportes filtrados por distrito cuando sale de madrugada en Chorrillos para identificar calles peligrosas o desiertas con hora exacta y ubicación en el mapa. En cuanto a `Bienestar & Sueño`, destacó la facilidad para ajustar su meta diaria a 7.5 horas y registrar su descanso post-turno ante los cambios constantes de horario, además de valorar la rapidez para agregar a un familiar en `Contactos Confianza` y el soporte de pagos mediante Yape o Plin en `Beneficios & Planes`. Finalmente, aprobó el contraste de las letras blancas y azules en el modo `Noche` y los selectores de idioma y tema, sugiriendo permitir subir una fotografía rápida del lugar al publicar un aviso en `Comunidad` para complementar el reporte.

---

##### Entrevista de Validación #3 – Segmento 1

| Campo | Detalle |
| :--- | :--- |
| **Nombres y Apellidos** | Marco Antonio Quispe |
| **Edad** | 30 años |
| **Distrito** | San Martín de Porres |
| **Segmento Objetivo** | Trabajadores de Turno Nocturno (Agente de seguridad en almacén logístico en el Callao) |
| **Fecha de entrevista** | 14/11/2026 |
| **URL del Video (Stream)** | https://upcedupe-my.sharepoint.com/:v:/g/personal/u202421823_upc_edu_pe/IQA5WXdo5JSwQaqSeeKQT1u6AR-uhaoefldLChuJvnWBJwU?e=NVNJuU |
| **Timing de Inicio** | 0:05 |
| **Duración** | 6:00 |

![Captura Entrevista 3 - Marco Antonio](resources/imgs/marcoantonio.png)

**Resumen descriptivo de apreciaciones:**
Marco Antonio Quispe manifestó que la presentación del **Landing Page** es directa y aborda acertadamente los riesgos de movilizarse de madrugada desde zonas como el Callao, destacando que el precio de 12 soles mensuales del plan *Sentinel Pro* resulta muy razonable y que el acceso a la aplicación web es inmediato. Durante las pruebas en el **Portal del Trabajador**, señaló que al salir de guardia a las 6:00 a. m. o en cambios de turno de medianoche requiere rapidez, logrando registrar en `Mi Trayecto` su salida desde el almacén en el Callao hacia su casa en San Martín de Porres en segundos, respaldado por el botón rojo de `Estado SOS` en la parte inferior izquierda. Al explorar `Mapa 24h` y `Comunidad`, resaltó el valor de filtrar grifos y farmacias abiertas las 24 horas ordenadas por cercanía cuando transita por zonas industriales poco concurridas, así como leer alertas de otros compañeros sobre calles oscuras o patrullaje activo. De igual manera, calificó como muy intuitivo el flujo para agregar a su esposa en `Contactos Confianza`, consultar los descuentos en `Beneficios & Planes` y registrar su sueño en `Bienestar & Sueño`. Respecto al diseño visual e inclusivo, destacó que el modo `Noche` evita la fatiga visual tras una jornada de vigilancia y sugirió que, al iniciar una ruta, el sistema envíe automáticamente un mensaje de confirmación por WhatsApp al contacto de confianza sin necesidad de abrir la web.

---

#### Segmento Objetivo 2: Contactos de Confianza

##### Entrevista de Validación #4 – Segmento 2

| Campo | Detalle |
| :--- | :--- |
| **Nombres y Apellidos** | Juan Gutiérrez |
| **Edad** | 24 años |
| **Distrito** | San Juan de Miraflores |
| **Segmento Objetivo** | Contactos de Confianza (Estudiante universitario y contacto de confianza de su hermano menor) |
| **Fecha de entrevista** | 14/11/2026 |
| **URL del Video (Stream)** | https://www.youtube.com/watch?v=FUaV13-r20E |
| **Timing de Inicio** | 0:00 |
| **Duración** | 7:12 |

![Captura Entrevista 4 - Juan Gutiérrez](resources/imgs/juaninterview.png)

**Resumen descriptivo de apreciaciones:**
Juan Gutiérrez inició la validación en el **Landing Page**, señalando que la información permite comprender con rapidez el valor del sistema para las familias. Al ingresar al **Companion Portal** y dirigirse a la vista `Invitaciones`, visualizó de inmediato la solicitud enviada por su hermano menor y completó el vínculo con un solo clic en el botón "Aceptar". En la vista `Monitoreo en Vivo`, identificó con claridad la tarjeta de su hermano indicando que se encontraba en trayecto hacia San Juan de Miraflores, su medio de transporte y la hora estimada de llegada (ETA), además de consultar sin dificultad la constancia de sus recorridos previos en `Historial de Rutas`. Respecto a la vista `Avisos & Alertas`, destacó la claridad de las etiquetas que especifican el canal de envío (`WHATSAPP`, `EMAIL`, `IN_APP`) junto con los indicadores de estado en verde o rojo, resultándole muy práctico configurar WhatsApp como canal principal mientras estudia de noche. Asimismo, calificó como indispensable el directorio de `Auxilio & Serenazgo` con accesos directos a la Policía (105), SAMU (106), Bomberos (116) y Serenazgo para reaccionar sin perder tiempo ante cualquier imprevisto de madrugada. Finalmente, aprobó la fluidez del menú lateral y el selector `Día`/`Noche`, sugiriendo incorporar una alerta sonora distintiva para identificar al instante cuando su hermano llega a salvo a su destino.

---

##### Entrevista de Validación #5 – Segmento 2

| Campo | Detalle |
| :--- | :--- |
| **Nombres y Apellidos** | Ronald Ramírez |
| **Edad** | 51 años |
| **Distrito** | Bellavista, Callao |
| **Segmento Objetivo** | Contactos de Confianza (Esposo de trabajadora en turno nocturno) |
| **Fecha de entrevista** | 14/11/2026 |
| **URL del Video (Stream)** | https://upcedupe-my.sharepoint.com/:v:/g/personal/u202218235_upc_edu_pe/IQBQLBYmf-PTSoUTj-tlAQcoASW-cv5cecSmw5pLSEfc09M?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJPbmVEcml2ZUZvckJ1c2luZXNzIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXciLCJyZWZlcnJhbFZpZXciOiJNeUZpbGVzTGlua0NvcHkifX0&e=qOUTUa |
| **Timing de Inicio** | 0:00 |
| **Duración** | 07:03 |

![Captura Entrevista 5 - Ronald Ramírez](resources/imgs/ronaldinterview.png)

**Resumen descriptivo de apreciaciones:**
Ronald Ramírez señaló que el **Landing Page** va directo al grano y explica con claridad cómo conecta al trabajador nocturno con su familia. Al interactuar con la vista `Invitaciones` del **Companion Portal**, destacó la limpieza visual para mostrar las solicitudes de vínculo y el tipo de turno, logrando aceptar la invitación de su esposa en apenas cinco segundos. Durante la prueba de `Monitoreo en Vivo` e `Historial de Rutas`, comentó que visualizar directamente el punto de partida, el destino hacia Bellavista (Callao) y la hora estimada de llegada evita que su esposa tenga que exponerse sacando el teléfono en plena calle para mandar mensajes a cada rato. En la vista `Avisos & Alertas`, valoró el indicador numérico rojo en el menú lateral que avisa sobre las 6 alertas registradas, permitiendo distinguir cuáles llegaron por la aplicación, WhatsApp o correo, así como activar el canal de SMS y programar el horario nocturno. Igualmente, afirmó que `Auxilio & Serenazgo` brinda un gran respaldo al centralizar los teléfonos oficiales de la Policía, SAMU y Serenazgo junto al estado de incidentes SOS activos del familiar monitoreado. Por último, elogió la fluidez de la navegación y el contraste del modo `Noche` para revisar la pantalla a las 5:00 a. m. con la luz apagada, recomendando que la página emita un sonido corto de notificación cuando ingrese una alerta de inicio de ruta o demora mientras la pestaña está abierta en la computadora.

---

##### Entrevista de Validación #6 – Segmento 2

| Campo | Detalle |
| :--- | :--- |
| **Nombres y Apellidos** | Roberto Carlos Fernández |
| **Edad** | 42 años |
| **Distrito** | San Juan de Lurigancho |
| **Segmento Objetivo** | Contactos de Confianza (Profesional freelance, casado y supervisor de grupo familiar) |
| **Fecha de entrevista** | 14/11/2026 |
| **URL del Video (Stream)** | https://upcedupe-my.sharepoint.com/:v:/g/personal/u20241i469_upc_edu_pe/IQDjrpuFsu3xTqU67M1gfmZhAZ2aJCbQQMdsG9X1SITMOv4?e=Xnngtc |
| **Timing de Inicio** | `00:02` |
| **Duración** | `05:12` |

![Captura Entrevista 6 - Roberto Carlos Fernández](resources/imgs/VI-Roberto.png)

**Resumen descriptivo de apreciaciones:**
Roberto Carlos Fernández validó el **Landing Page** destacando la claridad de los videos demostrativos y la tabla comparativa de planes familiares. Dentro del **Companion Portal**, recorrió la vista `Invitaciones` comprobando la facilidad para aceptar o rechazar tanto vínculos de confianza como invitaciones a planes grupales. En la vista `Monitoreo en Vivo`, resaltó la ventaja de supervisar simultáneamente a más de un familiar en pantalla, diferenciando rápidamente quién está en ruta activa con su hora estimada de llegada y quién se encuentra en reposo, además de utilizar los botones superiores en `Historial de Rutas` para filtrar alertas entre todos los canales, WhatsApp o correo. Al evaluar `Avisos & Alertas`, destacó la división lógica de la pantalla entre el listado de alertas recibidas a la izquierda y la configuración de canales y cola de entregas a la derecha, valorando especialmente el botón `Despachar Pendientes` para destrabar avisos retenidos con un solo clic. También calificó como sumamente útil la vista `Auxilio & Serenazgo` por presentar en tarjetas grandes los números del 105, SAMU, Bomberos, Serenazgo y Línea 100 junto al monitor SOS, y la rapidez de `Mi Perfil de Contacto` y del botón para alternar entre portales. Como mejora, propuso incluir un pequeño mapa desplegable dentro de la tarjeta del trabajador en `Monitoreo en Vivo` para visualizar el punto exacto en el mapa además de la dirección escrita.

---
### 5.3.3. Evaluaciones según heurísticas

A continuación, se presenta la consolidación de la evaluación heurística de Usabilidad, Arquitectura de Información y Diseño Inclusivo derivada de las sesiones de validación.

#### UX Heuristics & Principles Evaluation: Usability - Inclusive Design - Information Architecture

* **CARRERA:** Ingeniería de Software
* **CURSO:** Desarrollo de Aplicaciones Open Source
* **SECCIÓN:** 7793
* **PROFESORES:** Todos
* **AUDITOR:** SeniorsInProcess
* **CLIENTE(S):** Luis Mendoza Miranda, Drago Duarte, Marco Antonio Quispe, Juan Gutiérrez, Ronald Ramírez, Roberto Carlos Fernández

**SITE / APP A EVALUAR:**
Noxway (Landing Page, Web Application – Portal del Trabajador y Web Application – Companion Portal)

**TAREAS A EVALUAR:**
El alcance de esta evaluación incluye la revisión de la usabilidad de las siguientes tareas:
1. Exploración del Landing Page, cambio de idioma (`ES`/`EN`), revisión de planes y redirección hacia la Web Application.
2. Inicio de trayecto activo, registro de origen, destino y medio de transporte, y verificación del botón `Estado SOS` en `Mi Trayecto`.
3. Búsqueda y filtrado de establecimientos abiertos las 24 horas y reporte de locales o peligros en `Mapa 24h`.
4. Filtrado por distrito y publicación de avisos de seguridad vial/urbana en `Comunidad`.
5. Registro de sesión de descanso post-turno y actualización de meta diaria de sueño en `Bienestar & Sueño`.
6. Revisión de planes, registro de pagos offline (`Yape/Plin`), canje de beneficios colectivos e invitación de contactos en `Beneficios & Planes` y `Contactos Confianza`.
7. Aceptación de invitaciones de vínculo de acompañamiento y supervisión en tiempo real en `Invitaciones` y `Monitoreo en Vivo` (Companion Portal).
8. Configuración de canales de notificación, reintento de envíos en `Avisos & Alertas` y consulta de números de emergencia en `Auxilio & Serenazgo`.

No están incluidas en esta versión de la evaluación las siguientes tareas:
1. Procesamiento de cobros recurrentes automatizados mediante pasarela bancaria de tarjetas de crédito/débito.
2. Moderación administrativa global de cuentas desde un backoffice externo de soporte técnico.
3. Integración directa por hardware con dispositivos vestibles (smartwatches) mediante Bluetooth nativo.

**ESCALA DE SEVERIDAD:**
Los errores serán puntuados tomando en cuenta la siguiente escala de severidad:

| Nivel | Descripción |
| :---: | :--- |
| **1** | **Problema superficial:** puede ser fácilmente superado por el usuario u ocurre con muy poca frecuencia. No necesita ser arreglado a no ser que exista disponibilidad de tiempo. |
| **2** | **Problema menor:** puede ocurrir un poco más frecuentemente o es un poco más difícil de superar para el usuario. Se le debería asignar una prioridad baja resolverlo de cara al siguiente *release*. |
| **3** | **Problema mayor:** ocurre frecuentemente o los usuarios no son capaces de resolverlo. Es importante que sea corregido y se le debe asignar una prioridad alta. |
| **4** | **Problema muy grave:** un error de gran impacto que impide al usuario continuar con el uso de la herramienta. Es imperativo que sea corregido antes del lanzamiento. |

**TABLA RESUMEN:**

| # | Problema | Escala de severidad | Heurística/Principio violada(o) |
| :---: | :--- | :---: | :--- |
| **1** | Al iniciar un desplazamiento en `Mi Trayecto`, el usuario debe digitar manualmente el origen y destino en cada turno sin contar con atajos de rutas habituales (p. ej., "San Isidro - San Martín de Porres"). | 2 | Usability: Flexibilidad y eficiencia de uso |
| **2** | Al publicar un reporte en la vista `Comunidad`, el formulario solo admite texto y no permite adjuntar una fotografía rápida del lugar o incidencia reportada. | 2 | Usability: Correspondencia entre el sistema y el mundo real / Flexibilidad de uso |
| **3** | Ausencia de notificaciones sonoras opcionales en el navegador del Companion Portal cuando ingresa una alerta de inicio de ruta, demora o llegada segura en `Avisos & Alertas` y `Monitoreo en Vivo`. | 2 | Usability: Visibilidad del estado del sistema / Inclusive Design: Proporciona experiencias comparables |
| **4** | En la vista `Monitoreo en Vivo` del Companion Portal, la tarjeta del trabajador muestra la ruta de forma textual pero no incluye un pequeño mapa desplegable con el punto GPS exacto. | 2 | Information Architecture: Is it usable? / Usability: Visibilidad del estado del sistema |
| **5** | Las etiquetas de estado de entrega (`DELIVERED`, `PENDING_PROVIDER`, `FAILED`) y de turno/transporte (`MOTORCYCLE`, `NIGHT`, `ROTATING`), así como subtítulos de rutas HTTP (`POST /wellness/rest`), se muestran con valores técnicos en inglés aun con el idioma español (`ES`) activo. | 1 | Inclusive Design: Internacionalización (`i18n`) / Usability: Diseño estético y minimalista |

---

**DESCRIPCIÓN DE PROBLEMAS:**

##### PROBLEMA #1: Ausencia de atajos de rutas habituales al iniciar un desplazamiento en `Mi Trayecto`
* **Severidad:** 2
* **Heurística violada:** Usabilidad – Flexibilidad y eficiencia de uso
* **Problema:**
  Cuando el trabajador nocturno ingresa a la vista `Mi Trayecto` al finalizar su jornada (por ejemplo, al salir de un turno de seguridad en San Isidro rumbo a San Martín de Porres o desde un almacén en el Callao), debe escribir manualmente la dirección de origen y de destino antes de presionar "Iniciar Trayecto y Compartir Estado". Dado que el usuario realiza el mismo recorrido habitual todas las noches y se encuentra con cansancio acumulado, digitar ambos campos repetidamente incrementa el esfuerzo de interacción.
  *(Incluir captura de pantalla de la vista `Mi Trayecto`)*.
* **Recomendación:**
  Agregar chips o botones de selección rápida de rutas guardadas ("Casa", "Trabajo" o "Ruta habitual: San Isidro - SMP") debajo de los campos de origen y destino para activar el recorrido y disparar la confirmación automática por WhatsApp con un solo toque.

##### PROBLEMA #2: Imposibilidad de adjuntar evidencia fotográfica al publicar un aviso en `Comunidad`
* **Severidad:** 2
* **Heurística violada:** Usabilidad – Correspondencia entre el sistema y el mundo real / Flexibilidad y eficiencia de uso
* **Problema:**
  En la vista `Comunidad`, cuando el trabajador nocturno redacta un nuevo aviso sobre el estado de una vía (como falta de iluminación, neblina densa o presencia de serenazgo en distritos como Chorrillos o Lima Centro), el formulario únicamente permite ingresar campos de texto, sin ofrecer un control para subir o capturar una fotografía rápida del lugar que respalde visualmente el reporte ante otros compañeros.
  *(Incluir captura de pantalla del formulario de publicación en la vista `Comunidad`)*.
* **Recomendación:**
  Incorporar un botón opcional de carga de imagen ("Adjuntar foto del lugar") dentro del formulario de creación de avisos comunitarios con previsualización en miniatura antes de publicar.

##### PROBLEMA #3: Falta de alertas sonoras distintivas en el Companion Portal ante eventos de ruta o llegada segura
* **Severidad:** 2
* **Heurística violada:** Usabilidad – Visibilidad del estado del sistema / Inclusive Design – Proporciona experiencias comparables
* **Problema:**
  En las vistas `Monitoreo en Vivo` y `Avisos & Alertas` del Companion Portal, cuando se registra un evento importante (inicio de trayecto, demora en ruta o llegada segura a destino), la interfaz actualiza los indicadores visuales y el contador numérico rojo del menú lateral, pero no emite una señal auditiva. Si el contacto de confianza tiene la pestaña abierta en su computadora o teléfono durante la madrugada mientras realiza otra actividad o descansa con la luz apagada, puede no percatarse inmediatamente del cambio de estado.
  *(Incluir captura de pantalla de la vista `Avisos & Alertas`)*.
* **Recomendación:**
  Añadir un interruptor de "Alerta sonora en navegador" dentro de las preferencias de `Avisos & Alertas` que reproduzca un tono corto y diferenciable cuando ingrese una notificación de llegada segura o una alerta de demora/SOS.

##### PROBLEMA #4: Falta de un mapa desplegable dentro de las tarjetas de `Monitoreo en Vivo`
* **Severidad:** 2
* **Heurística violada:** Information Architecture – Is it usable? / Usabilidad – Visibilidad del estado del sistema
* **Problema:**
  En la vista `Monitoreo en Vivo` del Companion Portal, el contacto de confianza visualiza el punto de partida, el destino, el medio de transporte y la hora estimada de llegada (ETA) en formato de texto dentro de la tarjeta de cada trabajador supervisado, pero no cuenta con un pequeño mapa desplegable en la misma tarjeta para observar gráficamente el último punto GPS reportado sin cambiar de contexto.
  *(Incluir captura de pantalla de la vista `Monitoreo en Vivo`)*.
* **Recomendación:**
  Incorporar un acordeón o botón desplegable "Ver ubicación en mapa" dentro de cada tarjeta de trabajador en `Monitoreo en Vivo` reutilizando el visor cartográfico de Leaflet implementado en `Mapa 24h`.

##### PROBLEMA #5: Etiquetas de enumeraciones en inglés (`DELIVERED`, `FAILED`, `MOTORCYCLE`) y subtítulos HTTP visibles en español
* **Severidad:** 1
* **Heurística violada:** Inclusive Design – Internacionalización (`i18n`) / Usabilidad – Diseño estético y minimalista
* **Problema:**
  En las vistas `Monitoreo en Vivo`, `Historial de Rutas` y `Avisos & Alertas`, algunos *badges* de estado (`DELIVERED`, `PENDING_PROVIDER`, `FAILED`, `MOTORCYCLE`, `NIGHT`, `ROTATING`) conservan su valor técnico en inglés cuando la interfaz está configurada en español (`ES`), y en los encabezados de formularios de `Bienestar & Sueño` y `Mi Perfil` se visualizan subtítulos de rutas HTTP (`POST /wellness/rest`, `PUT /accounts/me`).
  *(Incluir captura de pantalla de la vista `Avisos & Alertas` o `Bienestar & Sueño`)*.
* **Recomendación:**
  Pasar todos los valores de las enumeraciones por los archivos de traducción (`i18n`) según el idioma seleccionado y ocultar las etiquetas de rutas HTTP en el entorno de despliegue final.


## 5.4. Video About-the-Product


# Conclusiones 
Identificación de un nicho desatendido y vulnerable: El proyecto identifica y atiende a un segmento de mercado que ha sido históricamente ignorado por las soluciones tecnológicas: los trabajadores de turnos diurnos y nocturnos y sus contactos de confianza. El análisis y las entrevistas iniciales recogen los riesgos de transitar de madrugada y el aislamiento social de los trabajadores nocturnos; estos hallazgos orientan la propuesta para distintos horarios laborales.

Solución integral y multifacética: Noxway no se limita a ser un simple botón de pánico, sino que propone un ecosistema tecnológico completo que aborda los principales puntos de dolor del usuario. Integra herramientas de seguridad activa (check-in de trayectos y alertas automáticas de posibles incidentes), inteligencia comunitaria (mapas de servicios 24h y reporte de zonas de riesgo) y monitoreo de la salud (bitácora de descanso y sueño).

Diseño altamente centrado en el usuario (UX/UI): La aplicación de la metodología Lean UX garantizó que el diseño de la interfaz considere las limitaciones físicas y el entorno del usuario. Se concluye que la plataforma prioriza interacciones rápidas, simples y de baja fricción, lo cual es crítico para trabajadores que operan bajo fatiga extrema o que temen exponer su teléfono celular en calles desoladas y peligrosas.

Arquitectura de software robusta y escalable: A nivel técnico, el proyecto exhibe una madurez arquitectónica estructurada a través de Domain-Driven Design (EventStorming) y el modelo C4. El sistema está correctamente modularizado en contextos de dominio claros, separando la gestión de trayectos seguros, la inteligencia de la comunidad, el bienestar del usuario y la gestión de suscripciones.

Modelo de negocio validado y sostenible: El proyecto concluye con una estrategia de monetización viable mediante un modelo de suscripción (Plan Centinela Pro y Cuadrilla Familiar) que ofrece beneficios colectivos tangibles. Al incluir descuentos negociados y seguros básicos de accidentes, Noxway supera la resistencia al pago de su segmento objetivo, al mismo tiempo que fomenta el crecimiento orgánico a través de un programa de referidos.

# Video About-the-Team


# Bibliografía 
Adzic, G. (2012). Impact mapping: Making a big impact with software products and projects. Provoking Thoughts.
https://www.impactmapping.org/book.html

Brandolini, A. (2021). Introducing EventStorming. Leanpub.
https://leanpub.com/introducing_eventstorming

Brown, S. (2018). Software architecture for developers. Leanpub.
https://leanpub.com/software-architecture-for-developers

Cohn, M. (2004). User stories applied: For agile software development. Addison-Wesley Professional.
https://www.oreilly.com/library/view/user-stories-applied/0321205685/

Evans, E. (2004). Domain-driven design: Tackling complexity in the heart of software. Addison-Wesley Professional.
https://www.domainlanguage.com/ddd/

Gothelf, J., & Seiden, J. (2021). Lean UX: Designing great products with agile teams (3.ª ed.). O'Reilly Media.
https://www.oreilly.com/library/view/lean-ux-3rd/9781492092885/

Osterwalder, A., Pigneur, Y., Bernarda, G., & Smith, A. (2014). Value proposition design: How to create products and services customers want. John Wiley & Sons.
https://www.strategyzer.com/books/value-proposition-design

Rosenfeld, L., Morville, P., & Arango, J. (2015). Information architecture: For the web and beyond (4.ª ed.). O'Reilly Media.
https://www.oreilly.com/library/view/information-architecture-4th/9781491913529/

# Anexos
Enlaces teams archivos complementarios

Landing Page:

 https://upcedupe-my.sharepoint.com/:v:/g/personal/u202421065_upc_edu_pe/IQBfINsAKTsuTZ5_fDXp19sKAa5z-SRiOqBqVa2xgvU_l0I?e=q8RIZT

Needfinding: 

https://upcedupe-my.sharepoint.com/:v:/g/personal/u20241i469_upc_edu_pe/IQAU7GDYOY4SSIVp6gNJG9wTAQNGKB7fI-6AUR8smTqqgLA?e=Rxeyjz

Video Fronendt:

https://upcedupe-my.sharepoint.com/:v:/g/personal/u202421065_upc_edu_pe/IQDW4Rio9DvlRKEOT-S5IOoTAVZrK5HIVP8vPeBjPaUsWKY?e=h0f0wH
