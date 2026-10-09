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
**Fecha:** Septiembre 2026  
</div>



---
# Registro de Versiones del Informe 

# Registro de Versiones del Informe

| Versión | Fecha | Autor | Descripción de modificación |
| :------ | :---- | :---- | :-------------------------- |
| 1.0 | 2026-09-19 | Noctiva | Desarrollo del Capítulo I, Capítulo II, Capítulo III, Capítulo IV y el Sprint 1 del Capítulo V |
| 2.0 | 2026-10-08 | Noctiva | Implementación de mejoras según el feedback de evaluación en los Capítulos I al IV, y desarrollo del Sprint 2 del Capítulo V |

# Project Report Collaboration Insights 
| Recurso | URL |
| :--- | :--- |
| Organización del proyecto | https://github.com/upc-pre-202620-1asi0730-7793 |
| Repositorio del reporte | https://github.com/upc-pre-202620-1asi0730-7793/Report |
| Repositorio de la Landing Page | https://github.com/upc-pre-202620-1asi0730-7793/Landing-Page |

Durante la fase de preparación del informe, se llevaron a cabo las siguientes actividades:

AV1: Las tareas asignadas al AV1 han sido finalizadas y se encuentran correctamente documentadas en el repositorio de GitHub:

Se redactaron y crearon los contenidos asignados a cada miembro utilizando el formato Markdown, y se realizaron Conventional Commits para documentar el avance en el repositorio.
Se generaron los recursos necesarios y se agregaron las imágenes al repositorio en la carpeta assets correspondiente a cada rama del informe.
Se organizaron reuniones para coordinar el progreso de los componentes del informe y del Sprint 1, enfocado en el desarrollo de la Landing Page.

<div align="center">
<img src="resources/imgs/contributorsav1.png" alt="Commits del informe">
</div>


# Contenido 

## Tabla de contenidos 
- [Registro de Versiones del Informe](#registro-de-versiones-del-informe)
- [Registro de Versiones del Informe](#registro-de-versiones-del-informe-1)
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
      - [Segmento Objetivo 1: Trabajador de Turno Nocturno](#segmento-objetivo-1-trabajador-de-turno-nocturno)
      - [Segmento Objetivo 2: Contacto de Confianza](#segmento-objetivo-2-contacto-de-confianza)
    - [2.3.2. User Task Matrix.](#232-user-task-matrix)
    - [2.3.3. User Journey Mapping.](#233-user-journey-mapping)
      - [Segmento Objetivo 1: Trabajador de Turno Nocturno](#segmento-objetivo-1-trabajador-de-turno-nocturno-1)
      - [Segmento Objetivo 2: Contacto de Confianza](#segmento-objetivo-2-contacto-de-confianza-1)
    - [2.3.4. Empathy Mapping.](#234-empathy-mapping)
      - [Segmento Objetivo 1: Trabajador de Turno Nocturno](#segmento-objetivo-1-trabajador-de-turno-nocturno-2)
      - [Segmento Objetivo 2: Contacto de Confianza](#segmento-objetivo-2-contacto-de-confianza-2)
  - [2.4. Big Picture EventStorming.](#24-big-picture-eventstorming)
  - [2.5. Ubiquitous Language.](#25-ubiquitous-language)
- [Capítulo III: Requirements Specification](#capítulo-iii-requirements-specification)
  - [3.1. User Stories.](#31-user-stories)
- [Historias de Usuario - Noxway](#historias-de-usuario---noxway)
  - [| **US-30** | Moderar comunidad | Como moderador (Noxway), quiero auditar zonas y servicios reportados para evitar spam o "trolls", manteniendo el prestigio de los datos comunitarios frente a nuevos usuarios. | **Escenario 1:** Dado que ve un reporte pendiente, Cuando pulsa "Aprobar", Entonces el punto se publica a todos.**Escenario 2:** Dado que es un reporte vacío o de broma, Cuando pulsa "Rechazar", Entonces desaparece y el usuario generador pierde "Trust Score". | EP-10 |](#-us-30--moderar-comunidad--como-moderador-noxway-quiero-auditar-zonas-y-servicios-reportados-para-evitar-spam-o-trolls-manteniendo-el-prestigio-de-los-datos-comunitarios-frente-a-nuevos-usuarios--escenario-1-dado-que-ve-un-reporte-pendiente-cuando-pulsa-aprobar-entonces-el-punto-se-publica-a-todosescenario-2-dado-que-es-un-reporte-vacío-o-de-broma-cuando-pulsa-rechazar-entonces-desaparece-y-el-usuario-generador-pierde-trust-score--ep-10-)
  - [3.2. Impact Mapping.](#32-impact-mapping)
  - [3.3. Product Backlog.](#33-product-backlog)
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
      - [5.2.2.4.Development Evidence for Sprint Review.](#5224development-evidence-for-sprint-review)
      - [5.2.2.5.Execution Evidence for Sprint Review.](#5225execution-evidence-for-sprint-review)
      - [5.2.2.6.Services Documentation Evidence for Sprint Review.](#5226services-documentation-evidence-for-sprint-review)
      - [5.2.2.7.Software Deployment Evidence for Sprint Review.](#5227software-deployment-evidence-for-sprint-review)
      - [5.2.2.8.Team Collaboration Insights during Sprint.](#5228team-collaboration-insights-during-sprint)
- [Conclusiones](#conclusiones)
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
| Trabaja en equipo para proporcionar liderazgo en forma conjunta                                 |<ul><li><b>Patricio Farias, Ana Camila</b> <br> <b>AV1</b>:Lideré la gestión ágil, facilitación y articulación operativa del equipo a lo largo del ciclo de vida del sprint, asegurando el cumplimiento riguroso de los hitos y entregables fijados. Fomenté una comunicación transversal y continua entre las áreas de diseño, arquitectura y desarrollo, organizando y desglosando las tareas en el tablero de trabajo para optimizar la carga y mitigar bloqueos tempranos. Asimismo, impulsé sesiones colaborativas de toma de decisiones para resolver discrepancias técnicas y de alcance, garantizando la trazabilidad, coherencia e integración de los artefactos producidos y asegurando la alineación constante de los objetivos individuales con la visión global de la solución.<br> <b>TB1</b>: Lideré la estructuración y planificación del Sprint 2, asumiendo la responsabilidad de la gestión ágil del equipo. Como parte de este liderazgo, refiné el Product Backlog mediante la revisión y corrección exhaustiva de diversas User Stories, asegurando su viabilidad técnica y alineación con los objetivos de negocio de Noctiva.</li><br><li><b>Dextre Flores, Leonardo Felix</b> <br> <b>AV1</b>: Organicé mi contribución en una secuencia de artefactos relacionados entre sí, avanzando desde la vista general de la arquitectura hasta el diseño de clases y persistencia. Mantuve una nomenclatura consistente entre los Bounded Contexts, componentes, clases y estructuras de datos, y documenté las responsabilidades principales de cada elemento para facilitar su revisión y posterior utilización por los demás integrantes. También verifiqué la correspondencia entre las decisiones arquitectónicas y las User Stories previamente definidas, procurando evitar dependencias innecesarias entre contextos y dejando una estructura organizada que facilite posteriormente la distribución de tareas de implementación de frontend, backend y persistencia.</li><br><li><b>Salcedo Correa, Carlos Matthew</b> <br> <b>AV1</b>: Asumí el liderazgo técnico en el diseño de experiencia e interfaces de usuario (UX/UI) y en la estructuración de la arquitectura de información para el ecosistema digital de Noxway. Lideré la definición estratégica de SEO y metadatos tanto para la Landing Page pública como para la Web Application, y coordiné activamente con los responsables de requisitos la traducción de los objetivos de usuario hacia los flujos visuales del sistema (wireflows y user flows). Asimismo, proporcioné dirección técnica durante la implementación frontend del Landing Page, asegurando la consistencia entre los artefactos de diseño y el código fuente.</li></ul> <ul><li><b>Ramirez Rodriguez, Mauricio Joao</b> <br> <b>AV1</b>: Colaboré con el equipo planificando y llevando a cabo la fase de entrevistas para recoger los requerimientos del usuario, y elaboré los Style Guidelines del proyecto. Al definir y entregar estas pautas visuales a tiempo, facilité una referencia clara para el diseño de la interfaz, coordinando con el grupo para resolver dudas y cumplir con los objetivos fijados dentro del plazo previsto.</li><br><li><b>Cano Gomez, Yam</b> <br> <b>AV1</b>: Participé activamente en la coordinación y dinamización de las actividades del equipo, facilitando los canales de comunicación y la toma de decisiones conjuntas para asegurar el avance continuo del proyecto. Colaboré estrechamente en la revisión, consolidación y control de calidad de los distintos entregables, apoyando de manera constante a mis compañeros ante bloqueos o contingencias técnicas. Asimismo, promoví la alineación del grupo respecto a las prioridades y cronogramas establecidos, fomentando un entorno de trabajo colaborativo e integrando los aportes individuales para garantizar la coherencia global y el cumplimiento exitoso de los objetivos planteados.</li>  | El trabajo conjunto y la comunicación continua me permitieron asumir un rol activo en la toma de decisiones técnicas y metodológicas del grupo. Al facilitar la coordinación en la estructuración de los requisitos y consensuar la priorización de los artefactos ágiles, contribuí a un liderazgo distribuido donde cada integrante aportó valor de manera equitativa, logrando un flujo de trabajo organizado y alineado con los objetivos del proyecto. Asimismo, la coordinación entre UX/UI, SEO y desarrollo frontend permitió alinear la visión del producto con las necesidades del usuario, reforzando la colaboración y el liderazgo técnico del equipo. |
| Crea un entorno colaborativo e inclusivo, establece metas, planifica tareas y cumple objetivos. |<ul><li><b>Patricio Farias, Ana Camila</b> <br> <b>AV1</b>: Relalice las preguntas de la entrevistas, lo que permitió estructurar el needfinding mediante arquetipos de usuario, matrices de tareas, Journey Map y Empathy Mapp. A partir de estos hallazgos, modelé la lógica del dominio aplicando Big Picture EventStorming y definiendo un lenguaje ubicuo para alinear el negocio con el diseño del sistema. Finalmente, traduje estos requisitos a un marco ágil construyendo el Impact Mapping, especificando las historias de usuario y consolidando el Product Backlog priorizado para el desarrollo del producto.</li><br><li><b>Dextre Flores, Leonardo Felix</b> <br> <b>AV1</b>: Contribuí al diseño técnico de Noxway desarrollando los artefactos de arquitectura comprendidos entre las secciones 4.6.2 y 4.8.1. Definí la representación del sistema mediante los diagramas C4 de contexto, contenedores y componentes, estableciendo los principales actores, sistemas externos, unidades de software y responsabilidades de la solución. Posteriormente desarrollé los diagramas de clases correspondientes a los Bounded Contexts y módulos de soporte, manteniendo consistencia entre las entidades, servicios, interfaces, enumeraciones y relaciones del dominio. Finalmente, estructuré los diagramas de base de datos en PostgreSQL, especificando tablas, atributos, identificadores, claves y restricciones necesarias para mantener la integridad y la separación de responsabilidades entre contextos. Estas decisiones permitieron establecer una referencia técnica común para el equipo durante las siguientes etapas de desarrollo.</li><br><li><b>Salcedo Correa, Carlos Matthew</b> <br> <b>AV1</b>: Diseñé la arquitectura de información integral estableciendo los sistemas de búsqueda, navegación, SEO Tags y Meta Tags para la Landing Page y Web Application. A nivel visual y de interacción, diseñé los wireframes y mock-ups responsive (desktop y mobile) de la Landing Page, así como los wireframes, wireflows por User Goal, mock-ups y User Flow Diagrams (happy y unhappy paths) de la Web Application. Desarrollé además el prototipo interactivo en Figma y apoyé de forma colaborativa en la maquetación y desarrollo web de la Landing Page (HTML5, CSS3 y JavaScript), cumpliendo con los estándares de diseño y accesibilidad definidos.</li></ul> <ul><li><b>Ramirez Rodriguez, Mauricio Joao</b> <br> <b>AV1</b>:Fomenté un entorno colaborativo y estructurado al planificar y ejecutar la fase de entrevistas a los usuarios, definiendo objetivos claros para la recolección de información relevante para el equipo. Con base en estos hallazgos, elaboré los Style Guidelines del proyecto, estableciendo de manera organizada los estándares visuales, componentes y lineamientos de diseño. Gracias a la entrega oportuna de estas guías, facilité la alineación del equipo en el desarrollo de la interfaz, asegurando la coherencia del diseño y el cumplimiento puntual de las metas establecidas para el sprint. </li><br><li><b>Cano Gomez, Yam</b> <br> <b>AV1</b>: Promoví un entorno de trabajo colaborativo durante el desarrollo del Capítulo 1, organizando con el equipo el plan para las entrevistas y el Needfinding. Establecí metas para la recolección de información, prioricé las actividades del entregable y aseguré la participación activa de todos en el análisis de hallazgos. Además, facilité la consolidación de las User Personas, Empathy Maps y User Journey Maps, logrando que el equipo trabajara alineado y cumpliera a tiempo con los objetivos del proyecto.</li>| La articulación de las entrevistas y el análisis competitivo permitió integrar una visión común y fundamentada dentro del equipo, facilitando una planificación clara mediante herramientas como el EventStorming y el Impact Mapping. Este proceso colaborativo aseguró que la definición de historias de usuario y el Product Backlog respondieran a metas viables y medibles, cumpliendo oportunamente con los entregables de elicitación y especificación de requisitos. Asimismo, la definición de la arquitectura de información, el prototipado y la implementación visual aportaron un marco compartido para coordinar tareas, mantener consistencia entre diseño y desarrollo y asegurar la entrega de una experiencia alineada con los objetivos del proyecto. |

# Capítulo I: Introducción 

## 1.1. Startup Profile 
### 1.1.1 Descripción de la Startup
**Noctiva** es una startup dedicada a mejorar la seguridad, el bienestar y la vida social de los trabajadores que realizan su labor en horario nocturno. Nuestro alcance está dirigido a un segmento históricamente desatendido por las soluciones tecnológicas actuales: personal de seguridad, repartidores (delivery), enfermeros y personal de salud de turno noche, agentes de call centers 24 horas, y personal de limpieza nocturna, entre otros rubros que sostienen la operatividad de las ciudades mientras la mayoría de servicios están pensados para el horario diurno.
Como startup, buscamos posicionarnos como un referente en soluciones de seguridad y bienestar para trabajadores nocturnos, entendiendo las particularidades de un segmento que enfrenta mayores riesgos al transitar solo, dificultad para acceder a servicios abiertos de noche, y aislamiento de su círculo social por dormir cuando otros están despiertos.
**Misión:** Queremos ofrecer soluciones tecnológicas que devuelvan seguridad, comunidad y bienestar a quienes trabajan mientras la ciudad duerme, adaptando servicios y herramientas pensadas para el horario diurno a la realidad del turno nocturno.
**Visión:** Ser la startup líder en seguridad y bienestar para trabajadores de turno nocturno en el mercado peruano, comenzando por consolidar nuestra posición en Lima, para luego expandirnos a otras ciudades y sectores del país.

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
| **What: ¿Cuál es el problema?**|Los trabajadores de turno nocturno (seguridad, delivery, salud, call centers, limpieza, etc) se enfrentan a una ciudad y a unos servicios diseñados casi exclusivamente para el horario diurno. Esto se traduce en mayor riesgo al transitar solos por la noche, dificultad para encontrar comida o servicios abiertos, aislamiento de su círculo social por dormir cuando otros están despiertos, y nula capacidad de organizarse colectivamente debido a horarios dispersos.|
| **When: ¿Cuándo sucede este problema?**|El problema ocurre de manera constante durante las horas nocturnas y de madrugada, siendo más crítico en los trayectos de ida o vuelta del trabajo, cuando el transporte público es escaso, las calles están poco iluminadas y hay menor presencia de otras personas o autoridades.|
| **Where: ¿Dónde se produce este suceso?** |El problema está presente en las principales ciudades del país, pero es particularmente crítico en zonas urbanas de Lima con alta incidencia delictiva, poca iluminación pública y escasa oferta de servicios nocturnos, donde miles de trabajadores transitan diariamente sin herramientas que respalden su seguridad.|
| **Who: ¿Quiénes están involucrados?** |Están involucrados directamente los trabajadores de turno nocturno de distintos rubros (seguridad, delivery, enfermería, call centers, limpieza, etc), así como sus familiares, parejas y contactos de confianza, quienes también viven con incertidumbre y preocupación mientras el trabajador está en tránsito o en su jornada nocturna, sin ninguna forma de saber si llegó bien a su destino.|
| **Why: ¿Cuál es la causa del problema?** |La causa principal es que las ciudades, los servicios comerciales y las herramientas tecnológicas de seguridad y comunidad están mayoritariamente diseñados en función del horario diurno, dejando un vacío de soluciones específicas para quienes trabajan de noche. |
| **How: ¿Qué llevó a la persona a llegar a esta situación?** |La situación actual es resultado de una economía que exige servicios ininterrumpidos las 24 horas (seguridad, salud, delivery, atención al cliente, etc), sin que exista una infraestructura de apoyo equivalente para quienes sostienen esa operación nocturna, generando desprotección, desgaste físico y aislamiento social progresivo.|
| **How Much: ¿Cuánto es el impacto financiero?** |El impacto es tanto humano como económico: mayor exposición a asaltos y accidentes en el trayecto, deterioro de la salud por falta de descanso adecuado, pérdida de vínculos sociales y familiares, y un desgaste emocional constante en los contactos de confianza que viven con incertidumbre mientras el trabajador está en su turno nocturno. |

### 1.2.2 Lean UX Process.
#### 1.2.2.1. Lean UX Problem Statements.

El estado actual de **la seguridad y el bienestar de los trabajadores del turno nocturno en zonas urbanas del Perú** se ha enfocado principalmente en **los trabajadores del horario diurno**, dejando de lado a **guardias de seguridad, repartidores (delivery), personal de salud, agentes de call center, personal de limpieza, entre otros, que laboran en turno nocturno**, junto con sus puntos de dolor tales como **el riesgo constante al transitar solos de noche, la dificultad para encontrar servicios abiertos y confiables, el aislamiento de su círculo social debido a que duermen mientras otros están despiertos, y la nula capacidad de organizarse colectivamente debido a sus horarios dispersos**.

Lo que los productos/servicios existentes de seguridad personal y de compartición de ubicación no logran abordar es **una plataforma especializada que combine seguridad activa durante los trayectos, información confiable generada por la comunidad sobre la seguridad de las rutas y el entorno nocturno, y un espacio de comunidad y beneficios colectivos diseñado específicamente para la realidad del trabajo en turno nocturno**.

**Noxway** abordará esta brecha **ofreciendo un check-in de trayecto seguro con alertas automáticas a contactos de confianza, un sistema de calificación y reporte de seguridad de rutas alimentado por la comunidad, un mapa comunitario de servicios abiertos durante la noche, un sistema automático de alerta ante posibles incidentes cuando un trayecto no es confirmado, una bitácora de descanso y salud del sueño, y una comunidad con beneficios colectivos negociados mediante una suscripción mensual**.

Nuestro enfoque inicial serán **los trabajadores de turno nocturno de los rubros de seguridad, delivery, salud, call center, entre otros, en Lima Metropolitana, junto con sus contactos de confianza (familiares y parejas) que comparten la carga emocional de su seguridad durante estos trayectos**.

Sabremos que hemos tenido éxito cuando veamos **una reducción de los incidentes de seguridad reportados por nuestros usuarios, un uso recurrente y sostenido de la función de check-in de trayecto seguro, un volumen creciente de calificaciones de seguridad de rutas enviadas por la comunidad, un crecimiento orgánico de la comunidad de usuarios, y una tasa de conversión relevante de usuarios de prueba gratuita a suscriptores de pago**.

#### 1.2.2.2. Lean UX Assumptions.
**Business Assumptions**
* Creemos que existe un mercado desatendido de trabajadores nocturnos dispuestos a utilizar una plataforma dedicada a su bienestar.
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
1. Nuestros usuarios principales son trabajadores de turno nocturno entre 20 y 45 años, residentes en zonas urbanas de Lima, pertenecientes a los rubros de seguridad, delivery, salud y call centers, etc.
2. Nuestros usuarios secundarios son los contactos de confianza (familiares, parejas o amigos) de los trabajadores nocturnos, quienes reciben notificaciones automáticas sobre el estado de su trayecto.
3. Existen usuarios con rol de moderación dentro de la comunidad, encargados de validar reportes de incidentes y de información sobre servicios nocturnos.

**User Outcome and Benefit Assumptions**
1. Los trabajadores nocturnos desean sentirse acompañados y seguros durante sus trayectos, y obtienen tranquilidad al saber que un contacto de confianza será notificado automáticamente ante cualquier eventualidad.
2. Los trabajadores nocturnos desean encontrar rápidamente servicios abiertos y confiables durante la noche, y obtienen ahorro de tiempo y menor exposición a situaciones de riesgo.
3. Los trabajadores nocturnos desean sentirse parte de una comunidad que comprenda su realidad laboral, y obtienen acceso a información relevante y beneficios negociados colectivamente.
4. Los contactos de confianza desean tener certeza y tranquilidad sobre la seguridad de su familiar o pareja durante su trayecto nocturno, y obtienen visibilidad del estado del check-in y de la llegada segura, sin necesidad de estar llamando o preguntando constantemente.
5. Los trabajadores nocturnos desean saber qué tan segura es una ruta específica antes de tomarla, y obtienen información sobre la seguridad de la ruta gracias a las calificaciones y reportes dejados por otros usuarios que la transitaron recientemente.
6. Los trabajadores nocturnos desean comprender cómo su horario afecta su descanso, y obtienen visibilidad de sus patrones de sueño y alertas ante descanso insuficiente.
7. Los contactos de confianza desean enterarse a tiempo cuando el trayecto de su familiar o pareja presenta una situación anómala, y obtienen una alerta temprana y verificada sobre un posible incidente en el trayecto.

**Feature Assumptions**

1. Un check-in de trayecto seguro con aviso automático a contactos de confianza satisfará la necesidad de seguridad activa durante los desplazamientos nocturnos.
2. Un mapa comunitario de servicios activos de noche, validado por los propios usuarios, satisfará la necesidad de información confiable sobre el entorno.
3. Un sistema de reporte comunitario de incidentes y zonas de riesgo satisfará la necesidad de anticipar y evitar situaciones peligrosas.
4. Una bitácora de descanso y salud del sueño satisfará la necesidad de visibilizar y cuidar el bienestar físico del trabajador nocturno.
5. Una comunidad con beneficios colectivos negociados a través de la suscripción mensual satisfará la necesidad de pertenencia, ahorro y valor añadido para el trabajador nocturno.
6. Un sistema de calificación y reporte de ruta al finalizar cada trayecto (indicando si el usuario se sintió seguro o marcando un punto específico como sospechoso) satisfará la necesidad de contar con información colectiva y confiable sobre qué tan seguras son las rutas realmente transitadas.
7. Una función de marcado automático de "posible incidente" cuando el usuario no confirma su llegada dentro del tiempo estimado, con validación posterior del propio usuario, satisfará la necesidad de identificar rápidamente situaciones de riesgo reales y alimentar el mapa comunitario con datos verificados.
8. Un panel de seguimiento para contactos de confianza, que les permita ver en tiempo real el estado del trayecto y del check-in de la persona que los designó, satisfará la necesidad de tranquilidad y monitoreo sin invadir la privacidad del trabajador nocturno.

#### 1.2.2.3. Lean UX Hypothesis Statements.

**Hipótesis 1**

Creemos que lograremos **una retención a 30 días (usuarios con al menos un check-in en el mes 2 sobre usuarios con check-in en el mes 1) de al menos 60 %, durante los 3 meses posteriores al lanzamiento**  
Si **los trabajadores de turno nocturno en Lima**  
Alcanzan **tranquilidad al saber que un contacto de confianza será notificado automáticamente ante cualquier eventualidad**  
Con **la función de check-in de trayecto seguro con alertas automáticas a contactos de confianza**.

---

**Hipótesis 2**

Creemos que lograremos **un promedio de al menos 4 sesiones semanales por usuario activo y 3 búsquedas de servicios por semana, durante los 3 meses posteriores al lanzamiento**  
Si **los trabajadores de turno nocturno**  
Alcanzan **ahorro de tiempo y menor exposición a situaciones de riesgo**  
Con **el mapa comunitario de servicios activos durante la noche**.

---

**Hipótesis 3**

Creemos que lograremos **que al menos 80 % de los reportes de riesgo sean aprobados por moderación y que 70 % de las zonas de riesgo tengan 2 o más confirmaciones independientes, durante los 3 meses posteriores al lanzamiento**  
Si **los trabajadores de turno nocturno**  
Alcanzan **información sobre la seguridad de la ruta gracias a las calificaciones y reportes dejados por otros usuarios que la transitaron recientemente**  
Con **el sistema de reporte comunitario de incidentes**.

---

**Hipótesis 4**

Creemos que lograremos **una retención a 30 días (usuarios con al menos un check-in en el mes 2 sobre usuarios con check-in en el mes 1) de al menos 60 %, durante los 3 meses posteriores al lanzamiento**  
Si **los trabajadores de turno nocturno**  
Alcanzan **visibilidad de sus patrones de sueño y alertas ante descanso insuficiente**  
Con **la bitácora de descanso y salud del sueño**.

---

**Hipótesis 5**

Creemos que lograremos **una tasa de renovación de suscripción de al menos 70 % al tercer mes y que al menos 20 % de los nuevos registros llegue por recomendación, durante los 6 meses posteriores al lanzamiento**  
Si **los trabajadores de turno nocturno**  
Alcanzan **acceso a información relevante y beneficios negociados colectivamente**  
Con **la comunidad y sus beneficios colectivos negociados a través de la suscripción mensual**.

---

**Hipótesis 6**

Creemos que lograremos **que al menos 40 % de los trayectos finalizados reciba una calificación de ruta, durante los 3 meses posteriores al lanzamiento**  
Si **los trabajadores de turno nocturno**  
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
Si **los contactos de confianza (familiares y parejas de los trabajadores de turno nocturno)**  
Alcanzan **visibilidad del estado del check-in y de la llegada segura, sin necesidad de estar llamando o preguntando constantemente**  
Con **un panel de seguimiento dedicado para contactos de confianza**.

#### 1.2.2.4. Lean UX Canvas. 
Figura 1
<br>
Lean UX Canvas — Noxway
<br>
![Lean UX Canvas](resources/imgs/Lean_UX_Canvas.png)

## 1.3. Segmentos objetivo. 
**Segmento Objetivo 1: Trabajadores de turno nocturno**
**Aspectos demográficos:**
- **Edad:** 18 - 55 años.
- **Nivel socioeconómico:** Media - Baja.
- **Tipo de trabajador:** Personal de primera línea, trabajadores empleos temporales y servicios esenciales.
- **Rubro:** Seguridad privada, salud, delivery, call centers, limpieza y transporte.
- **Nivel de necesidad:** Alta dependencia de herramientas que garanticen su seguridad en rutas desoladas y faciliten encontrar servicios básicos abiertos de madrugada.

**Aspectos geográficos:**
- **Nacionalidad:** Peruana.
- **Zona geográfica:** Urbana y metropolitana (Lima).

**Aspectos psicográficos:**
- **Motivación:** Llegar sanos y salvos a sus hogares y lugares de trabajo, cuidar su salud del sueño, optimizar su tiempo y reducir sus gastos nocturnos.
- **Valores:** La seguridad personal, el bienestar físico y el respaldo de una comunidad.
- **Intereses:** Adopción de tecnología rápida y colaborativa que les permita evitar zonas de riesgo y acceder a beneficios o alertas en tiempo real.

---

**Segmento Objetivo 2: Contactos de confianza**
**Aspectos demográficos:**
- **Edad:** 18 - 60 años.
- **Nivel socioeconómico:** Media - Baja.
- **Vínculo:** Familiares directos (padres, hermanos), parejas o amigos cercanos del trabajador de turno nocturno.
- **Rubro:** Ocupaciones diversas.
- **Nivel de necesidad:** Alta necesidad de información y certeza sobre el estado y ubicación de su ser querido para mitigar la angustia durante la noche.

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
    <td colspan="5"> Con el objetivo de evaluar y comparar funcionalidades, tecnología, precios y estrategias de marketing de los principales competidores en seguridad personal y trayectos, para identificar nuestras fortalezas y debilidades, detectar oportunidades de negocio y definir los puntos que nos diferencian de la competencia frente al segmento específico de trabajadores de turno nocturno y sus contactos de confianza. </td>
  </tr>
  <tr></tr>
  <tr>
    <td colspan="2"></td>
    <td> Noxway <br> <img src="resources/imgs/chapter_ii/logo-noctiva.jpg" alt="Noxway" width="110" height="100"></img> </td>
    <td> bSafe <br> <img src="resources/imgs/chapter_ii/logo-bsafe.png" alt="bSafe" width="110" height="100"></img> </td>
    <td> Noonlight <br> <img src="resources/imgs/chapter_ii/logo-noonlight.png" alt="Noonlight" width="140" height="100"></img> </td>
    <td> Safetipin <br> <img src="resources/imgs/chapter_ii/logo-safetipin.png" alt="Safetipin" width="150" height="100"></img> </td>
  </tr>
  <tr>
    <td rowspan="2">Perfil</td>
    <td>Overview</td>
    <td> Noxway es una plataforma integral de seguridad, información y comunidad diseñada específicamente para trabajadores de turno nocturno y sus contactos de confianza, que combina check-in de trayecto seguro, calificación y reporte comunitario de rutas, mapa de servicios activos de noche y una comunidad con beneficios colectivos. </td>
    <td> bSafe es una app de seguridad personal que previene y documenta situaciones de riesgo mediante alarma SOS, grabación automática y una red de contactos "Guardians" que monitorean al usuario en tiempo real. </td>
    <td> Noonlight es una plataforma de seguridad conectada que permite pedir ayuda de forma silenciosa, enviando la ubicación exacta del usuario a despachadores profesionales que pueden movilizar servicios de emergencia. </td>
    <td> Safetipin es una app que genera puntajes de seguridad de calles y rutas a partir de auditorías y calificaciones de la comunidad, recomendando la ruta más segura y permitiendo compartir ubicación con contactos de confianza. </td>
  </tr>
  <tr>
    <td>Ventaja competitiva ¿Qué valor ofrece a los clientes?</td>
    <td> Ofrece una solución especializada para la realidad del trabajo nocturno; seguridad activa en el trayecto, calificación de rutas por la propia comunidad de trabajadores, e información confiable sobre servicios abiertos de noche. </td>
    <td> Ofrece prevención y evidencia documentada ante situaciones de riesgo mediante grabación automática y una red de contactos de confianza. </td>
    <td> Ofrece conexión directa y silenciosa con servicios de emergencia profesionales, sin depender de contactos personales. </td>
    <td> Ofrece información colectiva y verificada sobre qué tan segura es una calle o ruta específica, permitiendo decisiones de trayecto basadas en datos reales de la comunidad. </td>
  </tr>
  <tr>
    <td rowspan="2">Perfil de Marketing</td>
    <td> Mercado Objetivo </td>
    <td> Trabajadores de turno nocturno (seguridad, delivery, salud, call centers, limpieza, etc) y sus contactos de confianza (familiares, parejas), en zonas urbanas de Lima. </td>
    <td> Personas en general que buscan seguridad personal, con fuerte enfoque en mujeres y estudiantes universitarios. </td>
    <td> Usuarios individuales, estudiantes, y empresas que integran la app a dispositivos IoT y sistemas de seguridad residencial. </td>
    <td> Mujeres, jóvenes y comunidades urbanas en general, así como gobiernos locales y planificadores urbanos interesados en datos de seguridad de sus ciudades. </td>
  </tr>
  <tr>
    <td> Estrategias de Marketing </td>
    <td> Marketing de nicho dirigido a comunidades y grupos de trabajadores nocturnos en redes sociales, programa de referidos entre trabajadores y sus contactos de confianza. </td>
    <td> Testimonios de figuras públicas, presencia en medios internacionales, alianzas con instituciones educativas y comunidades. </td>
    <td> Alianzas B2B con marcas de seguridad del hogar e IoT (Wyze, Sabre, Roku), relaciones públicas con medios especializados en seguridad. </td>
    <td> Alianzas con ONGs, gobiernos locales y organizaciones de mujeres; presencia en medios enfocados en urbanismo y seguridad de género. </td>
  </tr>
  <tr>
    <td rowspan="3">Perfil de Producto</td>
    <td> Productos & Servicios </td>
    <td> Check-in de trayecto seguro, calificación y reporte de ruta, marcado automático de posible incidente, mapa comunitario de servicios nocturnos, bitácora de descanso y salud del sueño, comunidad con beneficios colectivos, panel de seguimiento para contactos de confianza. </td>
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
    <td> Especialización total en la realidad del trabajo nocturno, combinación única de check-in + calificación de rutas + comunidad, modelo de suscripción con beneficios tangibles adicionales. </td>
    <td> Reconocimiento internacional, tecnología robusta de grabación y evidencia, alianzas mediáticas de alto perfil. </td>
    <td> Conexión directa y profesional con servicios de emergencia, integración amplia con dispositivos IoT. </td>
    <td> Metodología de auditoría de seguridad probada y validada en 16 países, gran volumen de datos históricos, reconocimiento internacional en temas de seguridad urbana. </td>
  </tr>
  <tr>
    <td> Debilidades </td>
    <td> Dependencia de la adopción inicial y de la masa crítica de usuarios para que la calificación de rutas sea confiable. </td>
    <td> No está enfocada en las necesidades específicas de trabajadores nocturnos ni ofrece información comunitaria del entorno. </td>
    <td> Costo elevado del monitoreo profesional continuo; no ofrece funciones de comunidad ni calificación de rutas. </td>
    <td> No cuenta con check-in de trayecto ni aviso automático a contactos de confianza; su enfoque está más en datos para políticas públicas que en la experiencia diaria del usuario individual. </td>
  </tr>
  <tr>
    <td> Oportunidades </td>
    <td> Expansión hacia distintos rubros de trabajo nocturno y hacia otras ciudades del Perú. </td>
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

**Especialización en el trabajo nocturno:** A diferencia de bSafe, Noonlight y Safetipin, que ofrecen seguridad personal o auditoría urbana de forma genérica, **Noxway** se enfoca exclusivamente en la realidad de quienes trabajan de noche, combinando check-in de trayecto seguro, calificación de rutas, información comunitaria del entorno y bitácora de descanso, algo que ningún competidor ofrece de forma integrada.

**Calificación de rutas orientada a la acción, no solo al dato:** A diferencia de Safetipin, cuyo enfoque principal es generar datos para gobiernos y planificadores urbanos, **Noxway** utiliza la calificación de rutas directamente para beneficio inmediato del propio usuario (elegir una ruta más segura, recibir alertas de zonas de riesgo cerca de su ubicación en tiempo real).

**Vínculo emocional con contactos de confianza:** A diferencia de bSafe y Noonlight, donde el contacto de confianza solo recibe una alerta puntual ante una emergencia, **Noxway** ofrece un panel de seguimiento continuo pensado para la tranquilidad de familiares y parejas durante todo el trayecto, no solo en el peor escenario.

2. **Tácticas de Marketing:**

**Marketing de nicho y comunidades existentes:** Se realizarán campañas dirigidas específicamente a comunidades y grupos de trabajadores nocturnos en redes sociales, diferenciándonos del marketing masivo y genérico de bSafe y Noonlight.

**Programa de referidos entre trabajador y contacto de confianza:** A diferencia de los competidores, que no explotan este vínculo, **Noxway** incentivará que cada trabajador invite a sus contactos de confianza a la plataforma, generando crecimiento orgánico natural.

3. **Estrategias de Precios:**

**Suscripción con beneficios tangibles desde el inicio:** A diferencia del modelo freemium muy limitado de bSafe y Noonlight, y del modelo sin monetización directa al usuario de Safetipin, **Noxway** ofrecerá una suscripción mensual accesible que desde el primer mes incluye beneficios concretos (seguro básico, descuentos, alertas prioritarias), reforzando la percepción de valor frente al costo.

4. **Expansión y Adaptabilidad:**

**Enfoque regional inicial y expansión nacional:** **Noxway** comenzará en Lima, adaptándose a las necesidades específicas del contexto urbano peruano, antes de expandirse a otros departamentos del pais, a diferencia de competidores como Noonlight y Safetipin, que operan con un enfoque global desde su origen.

**Ecosistema local de servicios nocturnos:** Se buscarán alianzas con negocios y proveedores locales (farmacias, restaurantes, grifos) que deseen aparecer destacados en el mapa comunitario de servicios nocturnos, generando un ecosistema local que ningún competidor internacional replica.

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

#### Segmento Objetivo 1: Trabajador de Turno Nocturno
![User Persona - Jorge Luis Huamán](resources/imgs/up-Jorge%20Luis%20Huaman.png)

#### Segmento Objetivo 2: Contacto de Confianza
![User Persona - Rosa Elena Paredes](resources/imgs/up-Rosa%20Elena%20Paredes.png)


### 2.3.2. User Task Matrix. 
En esta sección se presenta el User Task Matrix, construido a partir de los User Persona que representan a los dos segmentos clave identificados:
* **Segmento Objetivo 1:** Trabajador de Turno Nocturno
* **Segmento Objetivo 2:** Contacto de Confianza

Las tareas fueron identificadas a partir del análisis cualitativo de entrevistas, y cada una fue evaluada según su frecuencia y nivel de importancia para los respectivos perfiles.

| Tarea / Actividad | Trabajador de Turno Nocturno (Frecuencia) | Trabajador de Turno Nocturno (Importancia) | Contacto de Confianza (Frecuencia) | Contacto de Confianza (Importancia) |
| :--- | :--- | :--- | :--- | :--- |
| Activar monitoreo o check-in de trayecto seguro al salir de casa o trabajo | Alta | Alta | Baja | Media |
| Consultar mapa colaborativo de zonas de riesgo y rutas seguras | Media | Alta | Baja | Baja |
| Buscar establecimientos nocturnos abiertos 24h (farmacias, comida, grifos) | Media | Media | Baja | Baja |
| Recibir notificación pasiva de salida y llegada segura del trabajador | Baja | Baja | Alta | Alta |
| Recibir alerta automática ante retraso excesivo o posible incidente | Baja | Alta | Baja | Alta |
| Calificar la seguridad de la ruta al completar el desplazamiento | Media | Media | Nunca | Baja |
| Registrar horas de descanso en la bitácora de sueño y bienestar | Media | Media | Nunca | Baja |
| Acceder a beneficios grupales y coberturas de seguro mediante membresía | Baja | Media | Baja | Baja |

### 2.3.3. User Journey Mapping. 
En esta sección se presentan los mapas de viaje de usuario, reflejando la experiencia integral de nuestros segmentos objetivos en el contexto actual: un entorno urbano carente de herramientas digitales especializadas para la dinámica del trabajo nocturno. Se analizan los puntos de fricción, canales y emociones que experimentan tanto el trabajador nocturno durante sus trayectos y jornadas, como su contacto de confianza desde el hogar.

#### Segmento Objetivo 1: Trabajador de Turno Nocturno

![User Journey Map - Jorge Luis Huamán](resources/imgs/jm-Jorge%20Luis%20Huaman.png)

#### Segmento Objetivo 2: Contacto de Confianza

![User Journey Map - Rosa Elena Paredes](resources/imgs/jm-Rosa%20Elena%20Paredes.png)

### 2.3.4. Empathy Mapping.
En esta sección se presentan los Empathy Maps. Estos nos ayudarán a comprender las experiencias, emociones y pensamientos que expresan los usuarios de cada segmento objetivo.

#### Segmento Objetivo 1: Trabajador de Turno Nocturno
![Empathy Map - Jorge Luis Huamán](resources/imgs/em-Jorge%20Luis%20Huaman.png)

#### Segmento Objetivo 2: Contacto de Confianza
![Empathy Map - Valeria Ríos](resources/imgs/em-Valeria%20R%C3%ADos.png)

## 2.4. Big Picture EventStorming.
En esta sección, el equipo presenta el modelado integral del dominio del negocio mediante la técnica de Big Picture EventStorming. A través de un espacio colaborativo virtual (Miro / Mural), exploramos de extremo a extremo el flujo operativo de nuestra solución: desde el registro y vinculación de contactos, la ejecución de trayectos seguros nocturnos y la gestión de alertas, hasta la colaboración comunitaria en mapas de servicios y la administración de beneficios por suscripción. Este ejercicio permite alinear el lenguaje ubicuo, identificar cuellos de botella y delimitar los subdominios del sistema. 

![Event Storming](resources/imgs/eventStorming.png)

## 2.5. Ubiquitous Language.
* **Night-Shift Worker (Trabajador de Turno Nocturno):** Usuario principal del sistema cuya jornada laboral se desarrolla durante horas nocturnas o de madrugada en rubros esenciales (seguridad privada, salud, delivery, call center, limpieza, etc.) y que enfrenta riesgos específicos de movilidad y aislamiento.
* **Trusted Contact (Contacto de Confianza):** Familiar directo, pareja o allegado designado por el trabajador nocturno para recibir notificaciones automáticas sobre el estado, inicio y término de sus trayectos sin invadir su privacidad.
* **Safe-Trip Check-In (Check-In de Trayecto Seguro):** Acción explícita mediante la cual el trabajador confirma el inicio o la llegada exitosa a su destino, activando o cerrando el protocolo de acompañamiento pasivo del sistema.
* **Safe Commute / Night Commute (Trayecto Seguro / Desplazamiento Nocturno):** Recorrido físico realizado por el trabajador entre su hogar y su lugar de trabajo (o viceversa) durante horarios nocturnos donde el transporte es limitado y el entorno urbano presenta mayor vulnerabilidad.
* **Possible Incident (Posible Incidente):** Estado de alerta temprana que se activa automáticamente cuando un trabajador no confirma su llegada dentro del tiempo estimado más el margen de tolerancia establecido, notificando al contacto de confianza.
* **Route Safety Rating (Calificación de Seguridad de Ruta):** Valoración colaborativa y cualitativa que realiza un trabajador al culminar su desplazamiento, calificando factores del entorno como iluminación, presencia de sospechosos, patrullaje o transitabilidad.
* **Risk Zone / Danger Spot (Zona de Riesgo / Punto de Peligro):** Ubicación geográfica o tramo vial reportado por la comunidad de trabajadores como inseguro debido a antecedentes de robos, escasa visibilidad o falta de resguardo ciudadano.
* **Night-Time Services Map (Mapa de Servicios Nocturnos):** Directorio georreferenciado y colaborativo de establecimientos que operan formalmente durante la madrugada (farmacias, grifos, locales de comida, talleres) y que han sido verificados por los usuarios.
* **Sleep & Rest Log (Bitácora de Descanso y Salud del Sueño):** Registro personal donde el trabajador documenta sus ciclos de sueño diurno y hábitos de reposo para monitorear su desgaste físico y recibir sugerencias de higiene del sueño.
* **Collective Benefits (Beneficios Colectivos):** Conjunto de ventajas comerciales, seguros básicos de accidentes y descuentos negociados en grupo para los usuarios que cuentan con una membresía activa.
* **Monthly Subscription (Suscripción Mensual):** Modelo de membresía recurrente que otorga acceso a coberturas complementarias de seguridad, seguros y beneficios exclusivos dentro de la plataforma.
* **Companion View (Panel de Seguimiento del Acompañante):** Interfaz simplificada y pasiva diseñada para el contacto de confianza, donde consulta el estado general del viaje y recibe alertas sin necesidad de realizar configuraciones complejas.
* **Community Moderator (Moderador de la Comunidad):** Rol asignado a usuarios verificados o miembros del equipo encargados de revisar, aprobar o desestimar reportes de nuevos servicios nocturnos o incidentes en el mapa.
* **Grace Period (Margen de Tolerancia de Arribo):** Ventana de tiempo prudencial añadida a la hora estimada de llegada que permite absorber retrasos de tráfico habituales antes de disparar un estado de posible incidente. 

# Capítulo III: Requirements Specification 

## 3.1. User Stories. 

Las historias de usuario para este proyecto se crearon en colaboración con el equipo de desarrollo, enfocándose en las necesidades principales de dos tipos de usuarios: los trabajadores nocturnos y los contactos de confianza.

Para mantener la organización, las historias se agruparon en épicas según sus funcionalidades. Los criterios de aceptación de cada historia se definieron utilizando la sintaxis Gherkin, asegurando que el equipo comprendiera el problema desde la perspectiva del usuario final.

**Epics**:
A continuación se presentan las Epics identificadas para el proyecto, que agrupan las principales funcionalidades de la plataforma orientada a la seguridad y el bienestar de los trabajadores de turno nocturno y sus contactos de confianza.

| Epic ID | Título | Descripción |
| :--- | :--- | :--- |
| **EP-01** | Gestión de Cuentas de Usuario | Esta epica se centra en todo lo necesario para que los usuarios (trabajadores de turno nocturno y contactos de confianza) puedan registrarse, iniciar sesión, recuperar su acceso y administrar su perfil de forma segura en la plataforma. |
| **EP-02** | Gestión de Contactos de Confianza | Esta epica abarca la funcionalidad que permite a los trabajadores nocturnos invitar, vincular y administrar a sus contactos de confianza, quienes recibirán información sobre el estado de sus trayectos. |
| **EP-03** | Check-In de Trayecto Seguro | Esta epica cubre el ciclo completo del check-in de trayecto: desde que el trabajador nocturno inicia un desplazamiento hasta que confirma su llegada o lo cancela. |
| **EP-04** | Detección y Gestión de Posibles Incidentes | Esta epica se encarga de la detección automática de posibles incidentes cuando un trayecto no es confirmado a tiempo, así como de su validación posterior y la notificación a los contactos de confianza. |
| **EP-05** | Mapa Comunitario de Servicios Nocturnos | Esta epica abarca la funcionalidad para que los trabajadores nocturnos busquen, reporten y validen colaborativamente los servicios y establecimientos abiertos durante la madrugada. |
| **EP-06** | Calificación y Reporte de Seguridad de Rutas | Esta epica cubre las funcionalidades que permiten a los trabajadores nocturnos calificar la seguridad de las rutas transitadas y reportar puntos específicos de riesgo, alimentando un mapa comunitario de zonas seguras e inseguras. |
| **EP-07** | Bitácora de Descanso y Salud del Sueño | Esta epica se centra en el registro y seguimiento de los hábitos de descanso del trabajador nocturno, brindando visibilidad y sugerencias sobre su salud del sueño. |
| **EP-08** | Comunidad y Beneficios Colectivos | Esta epica abarca la gestión de la suscripción mensual, el acceso a beneficios colectivos negociados (seguros básicos, descuentos) y el programa de referidos entre trabajadores y contactos de confianza. |
| **EP-09** | Panel de Seguimiento del Contacto de Confianza | Esta epica cubre la experiencia del contacto de confianza dentro de la plataforma, permitiéndole visualizar en tiempo real el estado del trayecto de su trabajador vinculado y configurar sus notificaciones. |
| **EP-10** | Moderación de la Comunidad | Esta epica se encarga de las funcionalidades que permiten a los moderadores de la comunidad revisar, aprobar o rechazar los reportes de servicios nocturnos e incidentes enviados por los usuarios, garantizando la calidad de la información colaborativa. |

---

**User Stories**:
Requisitos definidos junto con el conjunto de User Stories y Epics para los requisitos identificados. Las User Stories incluyen Acceptance Criteria redactados en tiempo presente, tercera persona, sin hacer referencia a detalles de interfaz de usuario, siguiendo la estructura de Gherkin (Given-When-Then). Se incluyen además User Stories para el sitio web estático (Landing Page), tomando como rol base visitante.

# Historias de Usuario - Noxway

| Epic / Story ID | Título | Descripción | Criterios de Aceptación | Relacionado con (Epic ID) |
| :--- | :--- | :--- | :--- | :--- |
| **US-01** | Registro de usuario | Como nuevo usuario, quiero registrarme indicando mi rol (trabajador o contacto) para integrarme a la red de soporte nocturno, contribuyendo a la meta de alcanzar 2,500 usuarios activos verificados. | **Escenario 1:** Dado que el nuevo usuario ingresa datos correctos, Cuando envía el formulario, Entonces su cuenta es creada y se le asigna el rol.<br><br>**Escenario 2:** Dado que el usuario omite campos o usa un correo ya registrado, Cuando envía el formulario, Entonces el sistema bloquea el registro y resalta el error. | EP-01 |
| **US-02** | Inicio de sesión | Como usuario registrado, quiero iniciar sesión de forma segura para acceder rápidamente a mis herramientas de protección, garantizando la meta de 75% de uso semanal de la plataforma. | **Escenario 1:** Dado que el usuario ingresa credenciales correctas, Cuando inicia sesión, Entonces el sistema concede el acceso a su panel.<br><br>**Escenario 2:** Dado que el usuario ingresa una contraseña errónea, Cuando intenta iniciar sesión, Entonces el sistema deniega el acceso con un mensaje de error. | EP-01 |
| **US-03** | Recuperación de contraseña | Como usuario, quiero solicitar la recuperación de mi contraseña para restablecer mi acceso sin fricciones, reduciendo la tasa de abandono temporal de la plataforma. | **Escenario 1:** Dado que el usuario ingresa un correo registrado, Cuando solicita la recuperación, Entonces se envía un enlace de restablecimiento.<br><br>**Escenario 2:** Dado que ingresa un correo no registrado, Cuando lo solicita, Entonces el sistema notifica que la cuenta no existe. | EP-01 |
| **US-04** | Edición de perfil | Como usuario, quiero editar mis datos para mantener mis métodos de contacto actualizados, asegurando que las alertas de emergencia lleguen al destino correcto sin retrasos. | **Escenario 1:** Dado que el usuario modifica sus datos, Cuando guarda los cambios, Entonces el perfil se actualiza.<br><br>**Escenario 2:** Dado que el usuario ingresa un teléfono con formato inválido, Cuando intenta guardar, Entonces el sistema rechaza la acción. | EP-01 |
| **US-05** | Conocer propuesta de valor (Landing) | Como visitante, quiero conocer la propuesta de valor en el "Hero" para entender cómo Noxway protege mis trayectos, acelerando mi decisión de registro para lograr la adopción temprana. | **Escenario 1:** Dado que el visitante entra a la Landing Page, Cuando carga la sección inicial, Entonces se muestra la propuesta de valor y los botones de llamado a la acción.<br><br>**Escenario 2:** Dado que el navegador tiene red inestable, Cuando la página carga parcialmente, Entonces se prioriza el texto principal de la propuesta de valor. | EP-01 |
| **US-31** | Visualizar video demostrativo | Como visitante, quiero reproducir el video explicativo para confiar en la solidez técnica del producto, impulsando el volumen de registros calificados a la plataforma. | **Escenario 1:** Dado que el visitante ubica la sección multimedia, Cuando pulsa reproducir, Entonces el video inicia sin interrupciones.<br><br>**Escenario 2:** Dado que el servidor de video falla, Cuando la sección carga, Entonces se muestra un mensaje alternativo de indisponibilidad. | EP-01 |
| **US-32** | Consultar testimonios | Como visitante, quiero leer testimonios de colegas para sentir respaldo y empatía, reduciendo la fricción emocional antes de comprometerme a usar la aplicación. | **Escenario 1:** Dado que el visitante ve el carrusel, Cuando desliza entre opciones, Entonces el sistema muestra testimonios diferentes.<br><br>**Escenario 2:** Dado que intenta interactuar en una pantalla táctil sin responder, Cuando hace swipe, Entonces el sistema asegura que la lectura del testimonio actual permanezca estática y legible. | EP-01 |
| **US-33** | Desplegar FAQ (Landing) | Como visitante, quiero expandir las preguntas frecuentes para resolver mis dudas de privacidad y costos, derribando objeciones e incentivando la creación de una cuenta. | **Escenario 1:** Dado que el visitante ve una pregunta colapsada, Cuando hace clic, Entonces la respuesta se expande.<br><br>**Escenario 2:** Dado que una respuesta ya está abierta, Cuando hace clic en otra, Entonces la anterior se repliega automáticamente para no saturar la pantalla. | EP-01 |
| **US-34** | Formulario de contacto | Como visitante, quiero enviar preguntas directas al equipo para resolver inquietudes técnicas, capturando "leads" interesados que contribuyan al crecimiento corporativo. | **Escenario 1:** Dado que completa todos los campos válidos, Cuando envía el formulario, Entonces recibe un mensaje de éxito.<br><br>**Escenario 2:** Dado que omite el correo electrónico, Cuando envía, Entonces el sistema bloquea el envío resaltando el campo requerido. | EP-01 |
| **US-35** | Cambiar idioma y tema | Como visitante, quiero alternar a "Modo Oscuro" o idioma para adaptar la visibilidad a mi turno nocturno, demostrando empatía con el usuario desde el primer contacto. | **Escenario 1:** Dado que el visitante acciona el interruptor de tema, Cuando se activa el modo oscuro, Entonces la paleta de colores cambia a contrastes aptos para la noche.<br><br>**Escenario 2:** Dado que el dispositivo no soporta el cambio dinámico, Cuando hace clic, Entonces se respeta el tema configurado a nivel de sistema por defecto. | EP-01 |
| **US-36** | Consultar Términos y Código Ético | Como visitante, quiero acceder a los Términos de Servicio y Código Ético desde el Footer para validar el tratamiento seguro de mi geolocalización, impulsando la confianza para registrarme. | **Escenario 1:** Dado que el visitante se desplaza al footer, Cuando hace clic en "Términos de Servicio", Entonces se despliega una ventana modal con las políticas (ACM/IEEE).<br><br>**Escenario 2:** Dado que hay una interrupción de carga, Cuando intenta abrir el enlace, Entonces se descarga una versión PDF de respaldo. | EP-01 |
| **US-37** |  Accesos Institucionales (Redes) | Como visitante, quiero poder ir a las redes sociales oficiales desde la Landing Page para validar que la comunidad está activa, reforzando la credibilidad institucional. | **Escenario 1:** Dado que el usuario visualiza los íconos de redes, Cuando hace clic en uno, Entonces se abre la página oficial en una pestaña nueva.<br><br>**Escenario 2:** Dado que el enlace de red social se encuentre temporalmente roto, Cuando se hace clic, Entonces el usuario se mantiene en la página sin errores 404 intrusivos. | EP-01 |
| **US-38** | Validar Zonas de Cobertura | Como visitante, quiero verificar el indicador de "Cobertura en Lima y Callao" para cerciorarme de que el servicio opera en mi distrito, mitigando el riesgo de suscribirme y no poder usarlo. | **Escenario 1:** Dado que el visitante localiza el bloque de Cobertura, Cuando lee la información, Entonces verifica el estado operativo (Ej. 24h Services Operational).<br><br>**Escenario 2:** Dado que el servicio sufra una caída regional, Cuando carga la sección, Entonces el indicador debe reflejar de forma transparente "Degradado" o "En mantenimiento". | EP-01 |
| **US-39** | Navegación Anclada (Smooth Scroll) | Como visitante, quiero utilizar los enlaces del header (Protocolo, Ecosistema, Planes) para desplazarme velozmente a mi área de interés, optimizando mi tiempo antes del turno. | **Escenario 1:** Dado que el visitante está en el Hero, Cuando hace clic en "Planes" en el header, Entonces la página hace scroll suave hasta la sección de suscripción.<br><br>**Escenario 2:** Dado que JavaScript esté desactivado en el navegador, Cuando hace clic en el enlace, Entonces la página salta de forma nativa a la sección (Fallback anchor link). | EP-01 |
| **US-06** | Invitar contacto de confianza | Como trabajador nocturno, quiero invitar a un contacto para integrarlo a mi monitoreo, contribuyendo directamente al objetivo estratégico de 60% de contactos vinculados. | **Escenario 1:** Dado que el trabajador ingresa un número válido, Cuando envía invitación, Entonces el sistema envía el enlace.<br><br>**Escenario 2:** Dado que intenta invitar a alguien ya vinculado, Cuando envía, Entonces el sistema informa la duplicidad y aborta el proceso. | EP-02 |
| **US-07** | Aceptar invitación de contacto | Como contacto de confianza, quiero aceptar una invitación para establecer el vínculo oficial de protección mutua, sumando al KPI de crecimiento de red de soporte activo. | **Escenario 1:** Dado que el contacto recibe la solicitud, Cuando hace clic en aceptar, Entonces el vínculo se formaliza en la base de datos.<br><br>**Escenario 2:** Dado que el contacto recibe la solicitud, Cuando hace clic en rechazar, Entonces el vínculo no se establece y el trabajador es notificado. | EP-02 |
| **US-08** | Remover contacto | Como trabajador nocturno, quiero eliminar un contacto obsoleto para resguardar la privacidad de mi geolocalización, evitando el envío de alertas erróneas a personas equivocadas. | **Escenario 1:** Dado que el trabajador confirma la eliminación, Cuando acciona el borrado, Entonces el contacto deja de recibir alertas.<br><br>**Escenario 2:** Dado que el trabajador presiona eliminar por error, Cuando el sistema solicita confirmación y este cancela, Entonces el contacto se mantiene vinculado. | EP-02 |
| **US-09** | Iniciar check-in seguro | Como trabajador nocturno, quiero iniciar mi trayecto con tiempo estimado para activar el seguimiento pasivo, garantizando el cumplimiento de la meta del 75% de uso semanal. | **Escenario 1:** Dado que el usuario fija destino y tiempo, Cuando inicia check-in, Entonces el sistema activa telemetría y avisa a contactos.<br><br>**Escenario 2:** Dado que intenta iniciar otro trayecto con uno ya en curso, Cuando pulsa iniciar, Entonces el sistema exige finalizar el anterior. | EP-03 |
| **US-10** | Confirmar llegada segura | Como trabajador nocturno, quiero marcar mi llegada para desactivar el rastreo y dar tranquilidad, evitando detenciones y falsas alarmas antes de la intervención de terceros. | **Escenario 1:** Dado que el trayecto está en curso, Cuando confirma llegada, Entonces se cierra el trayecto y se avisa a contactos.<br><br>**Escenario 2:** Dado que el trabajador pierde conexión a red, Cuando confirma llegada, Entonces la app guarda el estado localmente y sincroniza en cuanto vuelve el internet. | EP-03 |
| **US-11** | Cancelar check-in | Como trabajador nocturno, quiero cancelar un viaje activo por cambio de planes para mantener limpios mis registros, evitando el disparo de alertas de seguridad injustificadas. | **Escenario 1:** Dado que el trayecto está activo, Cuando se cancela, Entonces el monitoreo cesa sin alarmas.<br><br>**Escenario 2:** Dado que el viaje se encuentra en estado de "Posible Incidente", Cuando intenta cancelar sin justificar, Entonces el sistema exige un PIN o validación para descartar secuestro. | EP-03 |
| **US-12** | Marcado automático de incidente | Como trabajador nocturno, quiero que la app genere un posible incidente automático al vencer el tiempo, asegurando una intervención inmediata que reduzca un 30% los incidentes sin atender. | **Escenario 1:** Dado que el tiempo límite y tolerancia expiran, Cuando el cronómetro evalúa, Entonces dispara la alerta a contactos.<br><br>**Escenario 2:** Dado que el usuario se encuentra dentro del margen de tolerancia (ej. +10m por tráfico), Cuando el sistema evalúa, Entonces no se dispara aún el incidente. | EP-04 |
| **US-13** | Validar posible incidente | Como trabajador nocturno, quiero poder descartar un incidente marcado por el sistema para detener el pánico familiar, cumpliendo la meta de filtrar falsas alarmas efectivamente. | **Escenario 1:** Dado que se marca posible incidente, Cuando el usuario pulsa "Estoy Bien", Entonces se cierra la alerta como falso positivo.<br><br>**Escenario 2:** Dado que se marca posible incidente, Cuando el usuario no responde en 5 minutos, Entonces el sistema escala la severidad y muestra la ficha de rescate al contacto. | EP-04 |
| **US-14** | Recibir alerta en tiempo real | Como contacto de confianza, quiero recibir una notificación inmediata de emergencia para accionar directorios policiales, reduciendo tiempos de respuesta a incidentes críticos. | **Escenario 1:** Dado que se genera un incidente, Cuando se procesa en el backend, Entonces el contacto recibe SMS y push.<br><br>**Escenario 2:** Dado que el celular del contacto no tenga datos, Cuando el push falle, Entonces el sistema envía automáticamente un SMS tradicional (fallback). | EP-04 |
| **US-15** | Buscar servicios cercanos | Como trabajador nocturno, quiero ubicar farmacias/grifos abiertos de noche para evitar exponerme en calles vacías, incentivando la adopción y utilidad diaria de la plataforma. | **Escenario 1:** Dado que busca locales cerca, Cuando ejecuta, Entonces ve un mapa con servicios validados.<br><br>**Escenario 2:** Dado que no existan locales reportados en 5km, Cuando busca, Entonces se muestra un mensaje de área vacía sugiriendo reportar lugares conocidos. | EP-05 |
| **US-16** | Reportar servicio nuevo | Como trabajador nocturno, quiero añadir un comercio 24h al mapa para nutrir el ecosistema, contribuyendo a la meta de alcanzar 1,000 puntos nocturnos validados. | **Escenario 1:** Dado que ingresa datos válidos del comercio, Cuando envía, Entonces pasa a estado "Pendiente de validación".<br><br>**Escenario 2:** Dado que reporta una ubicación ya existente, Cuando envía, Entonces el sistema fusiona o alerta de la duplicidad. | EP-05 |
| **US-17** | Calificar servicio reportado | Como trabajador nocturno, quiero auditar y calificar servicios ajenos para mantener la veracidad del mapa, garantizando información segura para la comunidad activa. | **Escenario 1:** Dado que evalúa un servicio existente, Cuando vota positivo, Entonces sube el score de confiabilidad.<br><br>**Escenario 2:** Dado que un servicio recibe múltiples votos negativos, Cuando cruza el umbral bajo, Entonces es ocultado y mandado a moderación. | EP-05 |
| **US-18** | Calificar seguridad de ruta | Como trabajador nocturno, quiero calificar qué tan segura fue mi ruta al finalizar para crear mapas de calor, ayudando a lograr la métrica del 40% de viajes calificados. | **Escenario 1:** Dado que finaliza su viaje, Cuando califica con estrellas, Entonces se asocia el puntaje a esa vía.<br><br>**Escenario 2:** Dado que descarta la pantalla de calificación, Cuando lo hace, Entonces la ruta queda "sin calificar" pero no se bloquea la app. | EP-06 |
| **US-19** | Reportar punto de riesgo | Como trabajador nocturno, quiero marcar un cruce peligroso para prevenir asaltos a colegas, impactando en la reducción de incidentes reportados a nivel global. | **Escenario 1:** Dado que señala un punto con descripción, Cuando envía, Entonces aparece un marcador de peligro comunitario.<br><br>**Escenario 2:** Dado que marca un punto sin texto explicativo, Cuando envía, Entonces el sistema rechaza obligando a escribir un motivo corto. | EP-06 |
| **US-20** | Ver zonas de riesgo en mapa | Como trabajador nocturno, quiero visualizar las alertas de riesgo antes de arrancar mi moto/caminata para planificar desvíos seguros, materializando el valor de inteligencia comunitaria. | **Escenario 1:** Dado que consulta el mapa, Cuando navega, Entonces visualiza perímetros sombreados por riesgo.<br><br>**Escenario 2:** Dado que apaga su geolocalización, Cuando abre el mapa, Entonces el sistema pide permiso para ubicarlo antes de mostrar riesgos locales. | EP-06 |
| **US-21** | Registrar descanso | Como trabajador nocturno, quiero anotar mis horas de sueño diurno para monitorear desgaste crónico, incrementando la retención de usuarios preocupados por su salud. | **Escenario 1:** Dado que ingresa hora de dormir y despertar lógicas, Cuando guarda, Entonces se suman al acumulado semanal.<br><br>**Escenario 2:** Dado que pone hora final anterior a la inicial, Cuando guarda, Entonces arroja error de incongruencia horaria. | EP-07 |
| **US-22** | Historial de descanso | Como trabajador nocturno, quiero revisar mis gráficos semanales de descanso para demostrar mis patrones de higiene del sueño, justificando el valor de los módulos de bienestar. | **Escenario 1:** Dado que tiene datos históricos, Cuando abre la vista, Entonces ve gráficos estadísticos claros.<br><br>**Escenario 2:** Dado que no tiene registros previos, Cuando entra a la sección, Entonces se le presenta un "Estado vacío" amigable invitando a empezar. | EP-07 |
| **US-23** | Alerta por déficit de sueño | Como trabajador nocturno, quiero recibir advertencias si mi promedio de sueño baja drásticamente, previniendo accidentes laborales u operativos graves. | **Escenario 1:** Dado que el promedio baja de 5 horas semanales, Cuando el motor evalúa, Entonces lanza sugerencia de fatiga aguda.<br><br>**Escenario 2:** Dado que sus horas están estables, Cuando evalúa, Entonces no genera notificaciones intrusivas. | EP-07 |
| **US-24** | Consultar planes (Landing) | Como visitante, quiero comparar los planes (Esencial vs Centinela Pro) para visualizar beneficios y seguros, facilitando la conversión hacia la meta de 600 suscriptores de pago. | **Escenario 1:** Dado que mira los planes, Cuando hace clic en suscribir a "Centinela Pro", Entonces el checkout pre-selecciona el plan.<br><br>**Escenario 2:** Dado que la API de precios falla, Cuando carga la web, Entonces se muestran precios base almacenados en caché para no perder la venta. | EP-08 |
| **US-25** | Suscribirse (Pago) | Como trabajador nocturno, quiero ejecutar el pago de mi suscripción para desbloquear el monitoreo avanzado, garantizando el flujo de monetización de la plataforma. | **Escenario 1:** Dado que ingresa un método de pago válido, Cuando se procesa, Entonces se activa la membresía premium.<br><br>**Escenario 2:** Dado que la tarjeta no tiene fondos, Cuando se procesa, Entonces el sistema rechaza y mantiene al usuario en la capa Esencial gratuita. | EP-08 |
| **US-26** | Acceder a beneficios | Como suscriptor activo, quiero usar mi seguro y cupones de descuento (grifos/boticas) para obtener retorno de mi inversión mensual, asegurando una retención del 70%. | **Escenario 1:** Dado que tiene cuenta pro, Cuando entra a beneficios, Entonces genera códigos QR válidos para descuentos.<br><br>**Escenario 2:** Dado que es usuario gratuito, Cuando intenta acceder a seguros, Entonces la app le invita a hacer "Upgrade" mostrando el candado. | EP-08 |
| **US-27** | Referir contacto (Beneficio) | Como trabajador nocturno, quiero dar un código de invitación a un compañero para ganar meses gratis, acelerando la meta de adquisición y bajando el costo de marketing (CAC). | **Escenario 1:** Dado que un referido usa su código al registrarse, Cuando finaliza, Entonces el referidor gana su bonificación.<br><br>**Escenario 2:** Dado que el código ingresado es falso o expirado, Cuando se evalúa, Entonces arroja "Código inválido" pero deja que el registro fluya sin bono. | EP-08 |
| **US-28** | Companion View (Panel) | Como contacto de confianza, quiero ver el mapa satelital del viaje de mi familiar en tiempo real para no tener que llamarlo, cumpliendo la promesa de paz mental pasiva de la app. | **Escenario 1:** Dado que el viaje está activo, Cuando abre el enlace, Entonces ve un vehículo moviéndose en el mapa web.<br><br>**Escenario 2:** Dado que el viaje terminó hace horas, Cuando abre el enlace, Entonces se muestra estado "Llegada Confirmada" en lugar del mapa en vivo. | EP-09 |
| **US-29** | Configurar Notificaciones | Como contacto, quiero elegir solo alertas de inicio y emergencia (silenciando las de rutina) para no hartarme de la app, manteniendo mi cuenta vinculada permanentemente. | **Escenario 1:** Dado que apaga las alertas "SMS rutina", Cuando guarda, Entonces solo recibe emergencias.<br><br>**Escenario 2:** Dado que intenta apagar las "Alertas SOS", Cuando guarda, Entonces el sistema bloquea y advierte que las alertas críticas no se pueden apagar. | EP-09 |
| **US-30** | Moderar comunidad | Como moderador (Noxway), quiero auditar zonas y servicios reportados para evitar spam o "trolls", manteniendo el prestigio de los datos comunitarios frente a nuevos usuarios. | **Escenario 1:** Dado que ve un reporte pendiente, Cuando pulsa "Aprobar", Entonces el punto se publica a todos.<br><br>**Escenario 2:** Dado que es un reporte vacío o de broma, Cuando pulsa "Rechazar", Entonces desaparece y el usuario generador pierde "Trust Score". | EP-10 |
---

**Technical Stories:**
Las Technical Stories consideran el rol Developer en la redacción de la descripción, y se enfocan en las features del RESTful API necesarias para soportar cada una de las Epics del proyecto. Se ha definido una Technical Story por cada Epic identificada.

| Epic / Story ID | Título | Descripción | Criterios de Aceptación | Relacionado con (Epic ID) |
| :--- | :--- | :--- | :--- | :--- |
| **TS-01** | API de gestión de cuentas de usuario | Como desarrollador, busco implementar endpoints RESTful para el registro, inicio de sesión, recuperación de contraseña y edición de perfil, para que las aplicaciones cliente puedan gestionar cuentas de usuario de forma segura. | **Escenario 1: Registro de usuario vía API**<br>Dado que se envía una solicitud POST con los datos válidos de un nuevo usuario,<br>Cuando el endpoint de registro procesa la solicitud,<br>Entonces se crea el usuario y se retorna un token de autenticación.<br><br>**Escenario 2: Solicitud con datos inválidos**<br>Dado que se envía una solicitud POST con datos incompletos o inválidos,<br>Cuando el endpoint de registro procesa la solicitud,<br>Entonces se retorna un error de validación con el detalle de los campos incorrectos. | EP-01 |
| **TS-02** | API de gestión de contactos de confianza | Como desarrollador, busco exponer endpoints RESTful para invitar, aceptar, listar y eliminar contactos de confianza, para que el sistema pueda gestionar los vínculos entre usuarios. | **Escenario 1: Creación de invitación vía API**<br>Dado que se envía una solicitud POST con el identificador del trabajador y el contacto a invitar,<br>Cuando el endpoint procesa la solicitud,<br>Entonces se crea el registro de invitación con estado pendiente.<br><br>**Escenario 2: Eliminación de vínculo inexistente**<br>Dado que se envía una solicitud DELETE con un identificador de vínculo que no existe,<br>Cuando el endpoint procesa la solicitud,<br>Entonces se retorna un error indicando que el recurso no fue encontrado. | EP-02 |
| **TS-03** | API de check-in de trayecto seguro | Como desarrollador, busco implementar endpoints RESTful para iniciar, confirmar y cancelar check-ins de trayecto, para que la aplicación móvil pueda gestionar el estado de los desplazamientos en tiempo real. | **Escenario 1: Inicio de check-in vía API**<br>Dado que se envía una solicitud POST con el destino y el tiempo estimado de llegada,<br>Cuando el endpoint procesa la solicitud,<br>Entonces se crea el check-in con estado activo y se retorna su identificador.<br><br>**Escenario 2: Confirmación de check-in inexistente**<br>Dado que se envía una solicitud PATCH para confirmar un check-in con un identificador inválido,<br>Cuando el endpoint procesa la solicitud,<br>Entonces se retorna un error indicando que el check-in no existe. | EP-03 |
| **TS-04** | API de detección y gestión de incidentes | Como desarrollador, busco implementar un mecanismo que evalúe periódicamente los check-ins activos y exponga endpoints para validar posibles incidentes, con el fin de activar notificaciones automáticas a los contactos de confianza. | **Escenario 1: Generación automática de incidente por timeout**<br>Dado que un check-in activo supera el tiempo estimado más el margen de tolerancia configurado,<br>Cuando el proceso de evaluación se ejecuta,<br>Entonces se genera un registro de posible incidente y se dispara la notificación correspondiente.<br><br>**Escenario 2: Validación de incidente vía API**<br>Dado que se envía una solicitud PATCH indicando que el usuario se encuentra bien,<br>Cuando el endpoint procesa la solicitud,<br>Entonces el incidente se marca como resuelto y se registra en el historial. | EP-04 |
| **TS-05** | API del mapa comunitario de servicios nocturnos | Como desarrollador, busco implementar endpoints RESTful para crear, consultar y calificar servicios nocturnos, incluyendo búsqueda geoespacial, para alimentar el mapa comunitario. | **Escenario 1: Búsqueda geoespacial de servicios**<br>Dado que se envía una solicitud GET con coordenadas y un radio de búsqueda,<br>Cuando el endpoint procesa la solicitud,<br>Entonces se retorna la lista de servicios validados dentro del radio especificado.<br><br>**Escenario 2: Registro de un nuevo servicio**<br>Dado que se envía una solicitud POST con los datos de un nuevo servicio nocturno,<br>Cuando el endpoint procesa la solicitud,<br>Entonces el servicio se almacena con estado pendiente de validación. | EP-05 |
| **TS-06** | API de calificación y reporte de rutas | Como desarrollador, busco exponer endpoints RESTful para registrar calificaciones de seguridad de rutas y puntos de riesgo, permitiendo consultar un mapa de calor de zonas seguras e inseguras. | **Escenario 1: Registro de calificación de ruta**<br>Dado que se envía una solicitud POST con el identificador del trayecto y la calificación de seguridad,<br>Cuando el endpoint procesa la solicitud,<br>Entonces la calificación se almacena y se asocia a la ruta correspondiente.<br><br>**Escenario 2: Consulta de zonas de riesgo por área**<br>Dado que se envía una solicitud GET con los límites geográficos de un área,<br>Cuando el endpoint procesa la solicitud,<br>Entonces se retorna la lista de puntos de riesgo validados dentro de esa área. | EP-06 |
| **TS-07** | API de bitácora de descanso y salud del sueño | Como desarrollador, busco implementar endpoints RESTful para registrar y consultar horas de descanso, y un servicio que calcule sugerencias de higiene del sueño según los patrones registrados. | **Escenario 1: Registro de horas de descanso vía API**<br>Dado que se envía una solicitud POST con la hora de inicio y fin del descanso,<br>Cuando el endpoint procesa la solicitud,<br>Entonces el registro se almacena en la bitácora del usuario.<br><br>**Escenario 2: Cálculo de sugerencia por descanso insuficiente**<br>Dado que el promedio de horas de sueño de los últimos registros está por debajo del umbral configurado,<br>Cuando el servicio de análisis evalúa la bitácora,<br>Entonces se genera una sugerencia de higiene del sueño para el usuario. | EP-07 |
| **TS-08** | API de suscripciones y beneficios colectivos | Como desarrollador, busco integrar una pasarela de pagos y exponer endpoints RESTful para gestionar suscripciones, beneficios y códigos de referido, permitiendo automatizar el ciclo de vida de la membresía. | **Escenario 1: Activación de suscripción tras pago exitoso**<br>Dado que se recibe una confirmación de pago exitoso desde la pasarela de pagos,<br>Cuando el sistema procesa la notificación,<br>Entonces la suscripción del usuario se activa y se habilitan sus beneficios.<br><br>**Escenario 2: Aplicación de código de referido inválido**<br>Dado que se envía una solicitud POST con un código de referido inexistente,<br>Cuando el endpoint procesa la solicitud,<br>Entonces se retorna un error indicando que el código no es válido. | EP-08 |
| **TS-09** | API del panel de seguimiento del contacto de confianza | Como desarrollador, busco implementar un endpoint de consulta en tiempo real (o mediante actualizaciones periódicas) del estado del trayecto, así como la gestión de preferencias de notificación del contacto de confianza. | **Escenario 1: Consulta de estado de trayecto en tiempo real**<br>Dado que se envía una solicitud GET del estado del trayecto de un trabajador vinculado,<br>Cuando el endpoint procesa la solicitud,<br>Entonces se retorna el estado actual del check-in y el tiempo estimado de llegada.<br><br>**Escenario 2: Actualización de preferencias de notificación**<br>Dado que se envía una solicitud PUT con las preferencias de notificación seleccionadas,<br>Cuando el endpoint procesa la solicitud,<br>Entonces las preferencias se actualizan, excepto las notificaciones obligatorias de incidentes. | EP-09 |
| **TS-10** | API de moderación de la comunidad | Como desarrollador, busco exponer endpoints RESTful que permitan a los moderadores listar, aprobar o rechazar reportes pendientes de servicios e incidentes. | **Escenario 1: Listado de reportes pendientes**<br>Dado que se envía una solicitud GET filtrada por estado pendiente,<br>Cuando el endpoint procesa la solicitud,<br>Entonces se retorna la lista de reportes que aún no han sido revisados.<br><br>**Escenario 2: Aprobación de un reporte vía API**<br>Dado que se envía una solicitud PATCH para aprobar un reporte específico,<br>Cuando el endpoint procesa la solicitud,<br>Entonces el estado del reporte cambia a aprobado y se publica en la plataforma. | EP-10 |

---

## 3.2. Impact Mapping. 

En esta sección se presenta el Impact Mapping de la solución, técnica que permite alinear los objetivos estratégicos del negocio con las necesidades de nuestros dos User Personas (Jorge Luis Huamán y Rosa Elena Paredes), definiendo el impacto esperado en su comportamiento, los entregables de software a construir y las historias de usuario requeridas.

![Impact Mapping](resources/imgs/ImpactMap-OpenSource.png)

---
## 3.3. Product Backlog. 

| Orden | User Story Id | Título | Descripción | Story Points (1/2/3/5/8) |
| :---: | :---: | :--- | :--- | :---: |
| 1 | **US-05** | Conocer la propuesta de valor (Landing Page) | Como visitante del sitio web, quiero conocer la propuesta de valor y las funcionalidades principales de la plataforma en la landing page para decidir si deseo registrarme. | 2 |
| 2 | **US-24** | Consultar planes de suscripción (Landing Page) | Como visitante del sitio web, quiero consultar los planes de suscripción disponibles y sus beneficios para decidir si deseo registrarme en la plataforma. | 2 |
| 3 |**US-31** | Visualizar video de demostración y equipo en la Landing Page | Como visitante del sitio web, quiero reproducir el video explicativo sobre la plataforma y el equipo para comprender mejor el funcionamiento del servicio antes de crear una cuenta. | 2 |
| 4 |**US-32** | Consultar testimonios y casos de éxito en la Landing Page | Como visitante del sitio web, quiero explorar las experiencias y testimonios de otros trabajadores nocturnos para verificar la credibilidad y efectividad de la plataforma. | 2 |
| 5 | **US-33** | Desplegar preguntas frecuentes (FAQ) en la Landing Page | Como visitante del sitio web, quiero expandir y colapsar preguntas frecuentes para resolver dudas clave sobre el funcionamiento, privacidad y costos de la plataforma de manera inmediata. | 1 |
| 6 |**US-34** | Enviar formulario de contacto o soporte desde la Landing Page | Como visitante del sitio web, quiero enviar mis consultas a través del formulario de contacto para recibir asistencia o información personalizada por parte del equipo. | 2 |
| 7 |**US-35** | Cambiar idioma y tema visual en la Landing Page | Como visitante del sitio web, quiero alternar entre los idiomas disponibles (español e inglés) y ajustar el modo de visualización para adaptar la lectura a mis preferencias. | 3 |
| 8 | **US-09** | Iniciar check-in de trayecto seguro | Como trabajador nocturno, quiero iniciar un check-in de trayecto indicando mi destino y tiempo estimado de llegada para activar el acompañamiento pasivo del sistema. | 5 |
| 9 | **US-10** | Confirmar llegada segura | Como trabajador nocturno, quiero confirmar mi llegada al finalizar el trayecto para cerrar el check-in y notificar a mis contactos de confianza que llegué bien. | 3 |
| 10 | **US-12** | Marcado automático de posible incidente | Como trabajador nocturno, quiero que el sistema marque automáticamente un posible incidente cuando no confirmo mi llegada dentro del margen de tolerancia, para que mis contactos de confianza sean alertados. | 5 |
| 11 | **US-14** | Recibir alerta de posible incidente | Como contacto de confianza, quiero recibir una alerta inmediata cuando se detecte un posible incidente en el trayecto de mi trabajador vinculado para poder actuar rápidamente. | 3 |
| 12 | **US-28** | Visualizar estado de trayecto en tiempo real | Como contacto de confianza, quiero visualizar el estado actual del trayecto de mi trabajador vinculado para tener tranquilidad sin necesidad de llamarlo. | 5 |
| 13 | **US-06** | Invitar contacto de confianza | Como trabajador nocturno, quiero invitar a un contacto de confianza mediante su correo o número de teléfono para que pueda recibir notificaciones sobre mis trayectos. | 3 |
| 14 | **US-07** | Aceptar o rechazar invitación | Como contacto de confianza, quiero aceptar o rechazar una invitación recibida para decidir si deseo vincularme a un trabajador nocturno. | 2 |
| 15 | **US-13** | Validar posible incidente | Como trabajador nocturno, quiero validar o descartar un posible incidente marcado por el sistema para confirmar mi estado real ante mis contactos de confianza. | 3 |
| 16 | **US-11** | Cancelar check-in activo | Como trabajador nocturno, quiero cancelar un check-in en curso en caso de un cambio de planes para evitar que se generen alertas innecesarias. | 2 |
| 17 | **US-01** | Registro de usuario | Como nuevo usuario, quiero registrarme indicando mi rol (trabajador de turno nocturno o contacto de confianza) para poder acceder a la plataforma y sus funcionalidades. | 3 |
| 18 | **US-02** | Inicio de sesión | Como usuario registrado, quiero iniciar sesión con mi correo y contraseña para acceder a mi cuenta y a las funcionalidades correspondientes a mi rol. | 2 |
| 19 | **US-15** | Buscar servicios nocturnos cercanos | Como trabajador nocturno, quiero buscar en el mapa comunitario los servicios abiertos cerca de mi ubicación para encontrar rápidamente lo que necesito durante mi turno. | 5 |
| 20 | **US-20** | Visualizar mapa de zonas de riesgo | Como trabajador nocturno, quiero visualizar en el mapa las zonas calificadas como riesgosas por la comunidad para evitarlas antes de iniciar mi trayecto. | 5 |
| 21 | **US-18** | Calificar seguridad de ruta | Como trabajador nocturno, quiero calificar qué tan segura se sintió una ruta al finalizar mi trayecto para aportar información a la comunidad de trabajadores. | 3 |
| 22 | **US-19** | Reportar punto de riesgo específico | Como trabajador nocturno, quiero marcar un punto específico de la ruta como sospechoso o peligroso para alertar a otros usuarios sobre esa zona. | 3 |
| 23 | **US-16** | Reportar nuevo servicio nocturno | Como trabajador nocturno, quiero reportar un nuevo establecimiento abierto de madrugada para contribuir con información útil a la comunidad. | 3 |
| 24 | **US-17** | Calificar un servicio nocturno reportado | Como trabajador nocturno, quiero calificar la veracidad de un servicio reportado por otro usuario para ayudar a mantener el mapa comunitario actualizado y confiable. | 2 |
| 25 | **US-25** | Suscribirse al plan mensual | Como trabajador nocturno, quiero suscribirme al plan mensual de la plataforma para acceder a los beneficios colectivos negociados. | 5 |
| 26 | **US-26** | Acceder a beneficios y descuentos | Como trabajador nocturno con suscripción activa, quiero visualizar y acceder a los descuentos y beneficios negociados colectivamente para aprovecharlos. | 3 |
| 27 | **US-29** | Configurar preferencias de notificación | Como contacto de confianza, quiero configurar qué tipo de notificaciones deseo recibir (inicio de trayecto, llegada, posibles incidentes) para adaptar la app a mis necesidades. | 2 |
| 28 | **US-08** | Remover contacto de confianza | Como trabajador nocturno, quiero eliminar un contacto de confianza vinculado para dejar de compartir información sobre mis trayectos con él. | 2 |
| 29 | **US-21** | Registrar horas de descanso | Como trabajador nocturno, quiero registrar mis horas de sueño diurno para llevar un control de mi descanso y bienestar físico. | 3 |
| 30 | **US-22** | Visualizar historial de descanso | Como trabajador nocturno, quiero visualizar el historial de mis registros de sueño para identificar patrones en mi descanso a lo largo del tiempo. | 3 |
| 31 | **US-23** | Recibir sugerencia de higiene del sueño | Como trabajador nocturno, quiero recibir sugerencias cuando mi descanso ha sido insuficiente durante un periodo determinado para cuidar mi bienestar físico. | 3 |
| 32 | **US-30** | Revisar y aprobar reportes de la comunidad | Como moderador de la comunidad, quiero revisar los reportes de nuevos servicios e incidentes enviados por los usuarios para aprobarlos o rechazarlos antes de que sean visibles públicamente. | 5 |
| 33 | **US-27** | Referir a un contacto para obtener beneficio | Como trabajador nocturno, quiero invitar a otro trabajador mediante un código de referido para obtener un beneficio en mi suscripción cuando este se registre. | 3 |
| 34 | **US-04** | Edición de perfil | Como usuario, quiero editar mis datos personales y de contacto para mantener mi información actualizada dentro de la plataforma. | 2 |
| 35 | **US-03** | Recuperación de contraseña | Como usuario, quiero solicitar la recuperación de mi contraseña olvidada para poder restablecer el acceso a mi cuenta. | 3 |

---
<img src="resources/imgs/evidenciaTrello.png" alt="Trello" width="300">


**Trello:** [NoxWay Product Backlog](https://trello.com/invite/b/6aac8f9dc7251c019b6afd53/ATTI7b90483e43107e48d696e3beb440000b26CB42DE/noxway-product-backlog)

# Capítulo IV: Product Design 

## 4.1. Style Guidelines. 

### 4.1.1. General Style Guidelines.

**El estilo visual de la startup**

El estilo visual de la startup se fundamenta en los principios de seguridad, confianza, bienestar, accesibilidad y claridad visual, considerando que los usuarios principales son trabajadores que desarrollan sus actividades durante la noche, así como familiares, parejas y contactos de confianza que necesitan conocer su estado durante sus desplazamientos.

La interfaz está diseñada para funcionar en contextos nocturnos, donde la iluminación puede ser reducida y el usuario puede encontrarse realizando actividades laborales o desplazándose. Por ello, se prioriza una experiencia simple, intuitiva y de rápida comprensión, reduciendo la cantidad de elementos innecesarios y destacando únicamente la información relevante.

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

La selección de colores de la startup busca transmitir seguridad, confianza, tranquilidad y bienestar, utilizando una combinación que funcione correctamente tanto en ambientes nocturnos como en situaciones donde el usuario necesita identificar rápidamente una alerta.

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

**Justificación:** Esta estructura permite que los trabajadores nocturnos puedan utilizar la aplicación rápidamente mientras se encuentran trabajando o desplazándose.

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

La startup está diseñada principalmente para dispositivos móviles, debido a que los trabajadores utilizarán la plataforma durante sus desplazamientos nocturnos.

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
- Lectura clara en ambientes con poca iluminación.

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
- Mapa nocturno.
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

Debido a que la plataforma está orientada específicamente a trabajadores nocturnos, se establecen algunos componentes propios del sistema.

**Registro de trayecto seguro**

Permite iniciar un trayecto, seleccionar un destino y compartir el estado con los contactos de confianza.

**Contactos de confianza**

Permite registrar familiares, parejas o amigos que recibirán notificaciones relacionadas con el trayecto.

**Mapa nocturno**

Permite visualizar:

- Servicios abiertos durante la noche.
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
- Hábitos relacionados con el turno nocturno.

**Comunidad**

Permite a los trabajadores compartir información, experiencias y recomendaciones relacionadas con el trabajo nocturno.

**Beneficios**

Permite consultar descuentos, servicios y beneficios negociados para los trabajadores nocturnos mediante la suscripción a la plataforma.
## 4.2. Information Architecture.

### 4.2.1. Organization Systems.


Se utilizarán diversos métodos para organizar la información según su relevancia, contexto y frecuencia de uso. La presentación visual de la información se realizará mediante los siguientes sistemas de organización:

**Organización Jerárquica:** Se utilizará principalmente en el tablero principal, donde se priorizará la información relacionada con la seguridad del trabajador. Primero se mostrarán alertas críticas, estado del trayecto y notificaciones importantes; posteriormente se presentarán servicios nocturnos disponibles, información de la comunidad y datos relacionados con el bienestar.

**Organización Secuencial:** Se utilizará en los flujos de interacción que requieren seguir una serie de pasos, como el registro de un nuevo usuario, configuración de contactos de confianza, inicio de un trayecto seguro, confirmación de llegada, registro de descanso y reporte de un incidente.

**Organización Matricial:** Se utilizará para comparar información relacionada con servicios nocturnos, zonas de riesgo, reportes comunitarios y beneficios disponibles. Este sistema permitirá al usuario visualizar diferentes alternativas y tomar decisiones según criterios como distancia, horario de atención, nivel de seguridad o valoración de otros usuarios.

**Organización por categorías:** Se empleará para agrupar funcionalidades y contenidos relacionados. Por ejemplo, las opciones de seguridad incluirán trayectos, contactos de confianza y reportes de incidentes; mientras que las opciones de bienestar incluirán descanso, sueño y recomendaciones.ará para agrupar funcionalidades y contenidos relacionados. Por ejemplo, las opciones de seguridad incluirán trayectos, contactos de confianza y reportes de incidentes; mientras que las opciones de bienestar incluirán descanso, sueño y recomendaciones.


### 4.2.2. Labeling Systems.


En la startup, el sistema de etiquetado ha sido diseñado para maximizar la claridad y reducir la carga cognitiva de los usuarios. Todas las etiquetas utilizadas en la navegación, trayectos, mapas, comunidad, bienestar y configuración priorizarán la simplicidad, consistencia semántica y un lenguaje directo, claro y fácil de comprender.

El sistema de etiquetado considera que los usuarios principales pueden tener diferentes niveles de alfabetización digital. Por ello, se evitarán términos técnicos innecesarios y se utilizarán expresiones familiares para los trabajadores nocturnos y sus contactos de confianza.

**Principios clave del sistema de etiquetado:**

Las etiquetas evitarán tecnicismos innecesarios y ambigüedades. Se emplearán términos comunes que puedan ser comprendidos rápidamente por trabajadores, familiares y otros usuarios de la plataforma.

Un mismo concepto siempre se representará con la misma palabra en todos los entornos de la plataforma, incluyendo la aplicación móvil, aplicación web, notificaciones y comunicaciones.

Las etiquetas se limitarán preferentemente a 1-3 palabras, procurando que sean descriptivas, directas y fáciles de identificar.

Las etiquetas relacionadas con situaciones de seguridad tendrán un mayor peso visual y utilizarán colores e iconos de acuerdo con las directrices establecidas en la guía de estilo.

**Etiquetas principales por área**

**Navegación global:** Inicio, Trayecto, Mapa, Comunidad, Bienestar, Beneficios, Perfil.

**Página de inicio:** Mi estado, Mi trayecto, Alertas, Servicios cercanos, Actividad reciente.

**Seguridad y trayectos:** Iniciar trayecto, Finalizar trayecto, Confirmar llegada, Contactos de confianza, Compartir trayecto, Historial.

**Mapa nocturno:** Servicios abiertos, Zonas de riesgo, Incidentes, Rutas, Cerca de mí.

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
**Título:** Seguridad y bienestar para trabajadores nocturnos.

**Meta Descripción:** Plataforma digital para trabajadores nocturnos que ofrece seguimiento de trayectos, contactos de confianza, información sobre servicios abiertos, reportes comunitarios y herramientas de bienestar.

**Meta Palabras clave:** trabajadores nocturnos, seguridad nocturna, bienestar laboral, seguridad personal, trayecto seguro, servicios nocturnos, comunidad nocturna, Lima.

**Autor de la metaetiqueta:** [Noxway]

**Aplicación web**

**Título:** Seguridad y bienestar durante tu jornada nocturna.

**Meta Descripción:** Gestiona tus trayectos nocturnos, comparte tu estado con contactos de confianza, consulta zonas de riesgo y encuentra servicios disponibles durante la noche desde una sola plataforma.

**Meta Palabras clave:** seguridad para trabajadores nocturnos, seguimiento de trayectos, contactos de confianza, mapa nocturno, zonas de riesgo, servicios abiertos, bienestar nocturno.

**Autor de la metaetiqueta:** [Noxway]

### 4.2.4. Searching Systems.
Las decisiones de búsqueda en Noxway están orientadas a garantizar que los usuarios encuentren rápidamente información relevante sobre servicios nocturnos, zonas de riesgo, rutas, reportes comunitarios y beneficios, evitando que tengan que revisar grandes cantidades de información.

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

**Por tipo de servicio:** Restaurantes, farmacias, tiendas, centros de salud, transporte y otros servicios disponibles durante la noche.

**Por distancia:** Cerca de mí, menos de 1 km, menos de 3 km, menos de 5 km.

**Por horario:** Abierto ahora, abierto toda la noche, apertura próxima.

**Por seguridad:** Ruta recomendada, zona segura, zona de precaución, zona de riesgo.

**Por valoración:** Mejor valorados, más recientes y más reportados.

**Por fecha:** Reportes recientes, últimos 7 días y últimos 30 días.

**Apariencia de los datos después de la búsqueda**

**Listados de resultados:** Incluyen nombre del lugar o reporte, ubicación, distancia, horario de atención y valoración cuando corresponda.

**Resumen y descripción:** Cada resultado presenta información relevante, como descripción del servicio, reportes recientes, nivel de seguridad o comentarios de la comunidad.

**Ordenación y filtros aplicados:** El usuario podrá ordenar los resultados por cercanía, relevancia, valoración o fecha. Los filtros activos se mostrarán claramente en la parte superior de los resultados.

**Información comunitaria:** Los resultados relacionados con seguridad podrán incluir reportes y valoraciones realizadas por otros trabajadores nocturnos, permitiendo conocer experiencias recientes de la zona.

**Ubicación:** Los resultados podrán visualizarse tanto en formato de lista como en el mapa, facilitando la identificación de servicios y zonas relevantes cercanas al usuario.

### 4.2.5. Navigation Systems.
La estructura de navegación de la startup está diseñada para ofrecer una experiencia de usuario fluida y sencilla, asegurando un acceso rápido a las funcionalidades relacionadas con seguridad, trayectos, comunidad y bienestar.

La navegación prioriza especialmente las funciones que pueden ser utilizadas durante un desplazamiento nocturno, reduciendo la cantidad de pasos necesarios para acceder a información importante.

**Páginas principales**

**Inicio:** Dashboard principal con el estado del usuario, trayecto activo, alertas importantes, servicios cercanos y accesos rápidos.

**Mi trayecto:** Permite iniciar, consultar y finalizar trayectos, además de gestionar la información compartida con los contactos de confianza.

**Mapa:** Permite visualizar servicios abiertos durante la noche, zonas de riesgo, incidentes reportados y otros puntos relevantes.

**Comunidad:** Espacio donde los trabajadores pueden consultar y compartir experiencias, reportes, recomendaciones e información relacionada con el trabajo nocturno.

**Bienestar:** Sección destinada al registro de descanso, sueño y otros indicadores relacionados con el bienestar del trabajador nocturno.

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

**Mapa:** Permite navegar visualmente por la ubicación del usuario y consultar información relevante del entorno nocturno.

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


**Hero Section:** Presenta la propuesta de valor principal de forma contundente mediante un titular de alto impacto y un subtítulo explicativo enfocado en el acompañamiento y seguridad de trayectos nocturnos. Integra un llamado a la acción dual segmentado (Protect My Commute para el trabajador nocturno e I'm a Trusted Contact para acompañantes o familiares), complementado por un indicador visual de desplazamiento. 


**Protocolo:** Desglosa visualmente el flujo de funcionamiento operativo de la solución en cuatro fases consecutivas y numeradas: vinculación del círculo de confianza, inicio y estimación del trayecto de salida de turno, monitoreo pasivo de anomalías en segundo plano y confirmación unificada de llegada segura. 


**Ecosistema:** Organiza en una cuadrícula modular las cuatro capacidades tecnológicas y de bienestar clave que componen el servicio: Route & Commute Check-In (monitoreo de trayecto), 24-Hour Community Map (geolocalización de farmacias, grifos y puntos seguros abiertos de madrugada), Smart Alerts & Companion View (detección de desvíos y enlaces cifrados para familiares) y Rest Log & Collective Benefits (higiene del sueño circadiano y convenios). 


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
Los wireframes de las aplicaciones web de **Noxway** muestran cómo se estructuran las pantallas y dónde se ubican los elementos de navegación para cada uno de los roles clave del sistema: el **trabajador nocturno** y su **contacto de confianza**. Estos esquemas visuales, que se centran en la funcionalidad, la accesibilidad en entornos con poca luz y la facilidad de uso bajo condiciones de fatiga o urgencia, guían el diseño final. Su objetivo es asegurar que la aplicación sea intuitiva y que la interacción del usuario —desde iniciar un trayecto seguro y consultar el mapa 24 horas hasta monitorear un desplazamiento en vivo o coordinar auxilio distrital— sea fluida, rápida y eficiente, lo que ayuda a diseñadores y desarrolladores a optimizar la disposición de cada componente. 

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
El diagrama de flujo de usuario (User Flow Diagram) es una representación visual de los pasos que un usuario sigue al interactuar con una aplicación o sitio web. Muestra la secuencia de acciones que el usuario realiza para completar una tarea o meta específica (User Goal), lo que permite identificar posibles puntos de fricción, reducir la carga cognitiva en horarios nocturnos de alta fatiga y optimizar la experiencia integral del usuario.
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
En esta sección se presenta la arquitectura de software de Noxway desde el enfoque de Domain-Driven Design, tomando como base el Big Picture Event Storming desarrollado previamente.

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

El Context Diagram representa a Noxway como un único sistema de software y muestra a los principales actores y sistemas externos con los que interactúa. Los actores considerados son Night-Shift Worker, Trusted Contact y Community Moderator, de acuerdo con las interacciones principales representadas en la solución. Esta separación permite reflejar las responsabilidades relacionadas con el monitoreo de trayectos, la supervisión en vivo mediante el Companion View y la moderación del mapa comunitario.

Como sistemas externos se consideran Payment Gateway, Email Service, Push & SMS Service y Mapping & Geolocation Service. El Payment Gateway procesa los pagos asociados a las suscripciones de los planes (Centinela Pro, Cuadrilla Familiar); el Email Service soporta recuperación de contraseña y comunicaciones transaccionales; el Push & SMS Service suministra la infraestructura crítica para el envío de alertas de emergencia; y el Mapping Service provee la telemetría y geocodificación utilizada durante el monitoreo del trabajador.

C4 System Context Diagram de Noxway.

<img src="resources/imgs/context.png"
     alt="contextdiagram"
     style="">

## 4.6.3. Software Architecture Container Diagrams

La solución se distribuye en cinco containers principales: Landing Page, Mobile Application, Web Application, RESTful API y Relational Database. La Landing Page utiliza React y Next.js para presentar el modelo de negocio, el protocolo nocturno y captar registros. La Mobile Application, construida con Flutter y Dart, proporciona la experiencia principal en ruta para el trabajador nocturno. La Web Application utiliza React y TypeScript para proporcionar las experiencias autenticadas del Companion Portal y el panel de moderación. El RESTful API utiliza Node.js y Express para exponer servicios, aplicar reglas de negocio automáticas de incidentes y coordinar persistencia e integraciones. La información relacional y espacial se almacena en PostgreSQL.

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

La Web Application separa el Auth & Onboarding Module, Worker Portal, Companion Portal, Active Commute Tracker, 24h Community Map, Sleep & Wellness Log y Benefits & Subscriptions. Todas estas experiencias utilizan llamadas centralizadas y comparten componentes interactivos, manteniendo una única vía de comunicación con el RESTful API para garantizar la sincronización en tiempo real del estado de los trayectos.

C4 Component Diagram - Web Application.

<img src="resources/imgs/web.png"
     alt="componentdiagram"
     style="">

**RESTful API Components**

El RESTful API organiza sus componentes principales de acuerdo con los Bounded Contexts identificados en el Design-Level EventStorming: Account & Auth Controller, Trust Network Controller, Commute & Check-In Controller, Incident & Alert Manager, Community Map Service, Sleep Wellness Service, Subscription Controller y Moderation Controller.

Account & Auth Controller y Trust Network API concentran el registro, autenticación y gestión de vínculos. Commute Controller y el Incident Manager en segundo plano gestionan la telemetría, evaluación de tolerancia y disparo de alertas. Community Map Service procesa consultas espaciales de locales y zonas de riesgo. Sleep Wellness Service administra los registros de descanso diurno y sugerencias de fatiga. Subscription Controller gestiona planes, pagos y convenios colectivos.

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

El modelo concentra la abstracción `User`, de la cual heredan los roles específicos `NightWorker` y `TrustedContact`. `TrustLink` modela la clase de asociación que representa el vínculo de acompañamiento seguro entre un trabajador y su contacto de confianza, encapsulando su estado y vigencia.

Class Diagram - Identity & Network Management.

<img src="resources/imgs/ia-m.png"
     style="">

**Safe Commute & Incident Management**

`Commute` representa el núcleo del ciclo de vida del trayecto y se relaciona fuertemente con `TelemetryPing` mediante composición para registrar la ubicación y velocidad. `SafetyIncident` modela las situaciones de riesgo o demoras generadas durante el trayecto, interactuando con `NotificationPreference` para escalar las alertas a los canales correspondientes.

Class Diagram - Safe Commute Incident Management.

<img src="resources/imgs/management.png"
     style="">

**Community Intelligence**

`CommunityMap` actúa como la entidad agregadora para la consulta espacial. `NightServicePoint` representa los servicios verificados que operan en la madrugada y `RiskZone` modela los puntos de peligro reportados. `RouteRating` registra la calificación de seguridad asignada a las rutas una vez finalizado el desplazamiento.

Class Diagram - Community Intelligence.

<img src="resources/imgs/com.png"
     style="">

**Sleep Health & Wellness**

`SleepLog` representa el registro agregado diario de metas y déficits de sueño, mientras que `RestSession` registra periodos individuales de descanso fragmentado. `HygieneSuggestion` modela las recomendaciones emitidas por el sistema en función del nivel de fatiga detectado en el trabajador nocturno.

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

El modelo persiste los trayectos en la tabla `commutes`, complementada por `commute_checkpoints` para trazar los hitos de la ruta. La telemetría de alto volumen se aísla en `telemetry_pings`. Las anomalías generan registros en `safety_incidents`, los cuales mantienen su ciclo de vida y disparan registros de auditoría de notificaciones en `incident_alerts`.

Database Diagram - Safe Commute Incident Management.

<img src="resources/imgs/comu.png"
     style="">

**Community Intelligence**

El modelo persiste ubicaciones geoespaciales como `night_services` y `risk_zones`. Para garantizar la confiabilidad comunitaria, se emplean las tablas transaccionales `service_validations` y `risk_zone_confirmations`, que evitan votos duplicados por parte del mismo trabajador. Las encuestas de los desplazamientos se almacenan en `route_ratings`.

Database Diagram - Community Intelligence.

<img src="resources/imgs/commu.png"
     style="">

**Sleep Health & Wellness**

El modelo organiza la higiene del sueño separando el consolidado diario (`daily_sleep_logs`) de los periodos de descanso fraccionado (`sleep_sessions`). El sistema almacena en `hygiene_suggestions` las alertas emitidas por déficit de horas, las cuales se vinculan lógicamente al usuario que las recibe.

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

El código fuente implementa los siguientes estándares para garantizar el cumplimiento de accesibilidad[cite: 2]:

* **Roles explícitos**: Uso de roles WAI-ARIA como `role="banner"`, `role="dialog"`, `role="tablist"`, `role="tab"`, `role="tabpanel"`, `role="radiogroup"`, `role="radio"` y `role="contentinfo"`[cite: 2].
* **Estados dinámicos**: Control de visibilidad e interacción mediante los atributos `aria-expanded`, `aria-pressed`, `aria-selected`, `aria-hidden` y `hidden`[cite: 2].
* **Etiquetado claro**: Vinculación de controles mediante `aria-label`, `aria-labelledby`, `aria-controls` y `aria-live="polite"` para la lectura por tecnologías de asistencia[cite: 2].

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

NoxWay Sprint Backlog 
https://trello.com/invite/b/690c87e2eddd3d52ed83189d/ATTI96b986ca465d37e1b647b2fb1690fee5DC6EC0DE/noxway

#### 5.2.2.4.Development Evidence for Sprint Review.


#### 5.2.2.5.Execution Evidence for Sprint Review.
Capturas de la aplicacion web desplegada junto a un video demostrativo de su diseño y usabilidad


#### 5.2.2.6.Services Documentation Evidence for Sprint Review.


#### 5.2.2.7.Software Deployment Evidence for Sprint Review.
Durante este sprint, se completó el despliegue de la aplicacion web para habilitar su acceso público. El procedimiento inició con la creación y configuración de un repositorio público bajo la nomenclatura asignada al proyecto. Posteriormente, se cargó el código fuente y se activó el servicio de publicación web desde los ajustes del repositorio. Finalmente, se validó la disponibilidad y operatividad del sitio en línea, estableciendo un flujo de mantenimiento continuo en el cual cualquier cambio subido al repositorio se refleja automáticamente en producción.

*Evidencia de deployment 1*


#### 5.2.2.8.Team Collaboration Insights during Sprint.


# Conclusiones 
Identificación de un nicho desatendido y vulnerable: El proyecto identifica y atiende a un segmento de mercado que ha sido históricamente ignorado por las soluciones tecnológicas: los trabajadores de turno nocturno y sus contactos de confianza. El análisis y las entrevistas demuestran que las aplicaciones genéricas diseñadas para el horario diurno no logran resolver los riesgos de transitar de madrugada ni el aislamiento social que sufren estos trabajadores.

Solución integral y multifacética: Noxway no se limita a ser un simple botón de pánico, sino que propone un ecosistema tecnológico completo que aborda los principales puntos de dolor del usuario. Integra herramientas de seguridad activa (check-in de trayectos y alertas automáticas de posibles incidentes), inteligencia comunitaria (mapas de servicios 24h y reporte de zonas de riesgo) y monitoreo de la salud (bitácora de descanso y sueño).

Diseño altamente centrado en el usuario (UX/UI): La aplicación de la metodología Lean UX garantizó que el diseño de la interfaz considere las limitaciones físicas y el entorno del usuario. Se concluye que la plataforma prioriza interacciones rápidas, simples y de baja fricción, lo cual es crítico para trabajadores que operan bajo fatiga extrema o que temen exponer su teléfono celular en calles desoladas y peligrosas.

Arquitectura de software robusta y escalable: A nivel técnico, el proyecto exhibe una madurez arquitectónica estructurada a través de Domain-Driven Design (EventStorming) y el modelo C4. El sistema está correctamente modularizado en contextos de dominio claros, separando la gestión de trayectos seguros, la inteligencia de la comunidad, el bienestar del usuario y la gestión de suscripciones.

Modelo de negocio validado y sostenible: El proyecto concluye con una estrategia de monetización viable mediante un modelo de suscripción (Plan Centinela Pro y Cuadrilla Familiar) que ofrece beneficios colectivos tangibles. Al incluir descuentos negociados y seguros básicos de accidentes, Noxway supera la resistencia al pago de su segmento objetivo, al mismo tiempo que fomenta el crecimiento orgánico a través de un programa de referidos.

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
Landing Page: https://upcedupe-my.sharepoint.com/:v:/g/personal/u202421065_upc_edu_pe/IQBfINsAKTsuTZ5_fDXp19sKAa5z-SRiOqBqVa2xgvU_l0I?e=q8RIZT
Needfinding: https://upcedupe-my.sharepoint.com/:v:/g/personal/u20241i469_upc_edu_pe/IQAU7GDYOY4SSIVp6gNJG9wTAQNGKB7fI-6AUR8smTqqgLA?e=Rxeyjz