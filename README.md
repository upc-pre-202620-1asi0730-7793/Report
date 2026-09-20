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

```text
Código         Apellidos y Nombres
     U20241I469     Patricio Farias, Ana Camila
U202423775     Cano Gomez, Yam Antony
       U202421823     Dextre Flores, Leonardo Felix
          U202218235     Ramirez Rodriguez, Mauricio Joao
        U202421065     Salcedo Correa, Carlos Matthew
```



**Período:** 202620  
**Fecha:** Septiembre 2026  
</div>



---
# Registro de Versiones del Informe 

|Versión|Fecha|Autor|Descripción de modificación|
|:------|:----|:----|:--------------------|
|||||

# Project Report Collaboration Insights 

# Contenido 

## Tabla de contenidos 
- [Registro de Versiones del Informe](#registro-de-versiones-del-informe)
- [Project Report Collaboration Insights](#project-report-collaboration-insights)
- [Contenido](#contenido)
  - [Tabla de contenidos](#tabla-de-contenidos)
- [Student Outcome](#student-outcome)
- [Capítulo I: Introducción](#capítulo-i-introducción)
  - [1.1. Startup Profile](#11-startup-profile)
    - [1.1.1. Descripción de la Startup](#111-descripción-de-la-startup)
    - [1.1.2. Perfiles de integrantes del equipo](#112-perfiles-de-integrantes-del-equipo)
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
    - [2.1.1. Análisis competitivo.](#211-análisis-competitivo)
    - [2.1.2. Estrategias y tácticas frente a competidores.](#212-estrategias-y-tácticas-frente-a-competidores)
  - [2.2. Entrevistas.](#22-entrevistas)
    - [2.2.1. Diseño de entrevistas.](#221-diseño-de-entrevistas)
    - [2.2.2. Registro de entrevistas.](#222-registro-de-entrevistas)
    - [2.2.3. Análisis de entrevistas.](#223-análisis-de-entrevistas)
  - [2.3. Needfinding.](#23-needfinding)
    - [2.3.1. User Personas.](#231-user-personas)
    - [2.3.2. User Task Matrix.](#232-user-task-matrix)
    - [2.3.3. User Journey Mapping.](#233-user-journey-mapping)
    - [2.3.4. Empathy Mapping.](#234-empathy-mapping)
  - [2.4. Big Picture EventStorming.](#24-big-picture-eventstorming)
  - [2.5. Ubiquitous Language.](#25-ubiquitous-language)
- [Capítulo III: Requirements Specification](#capítulo-iii-requirements-specification)
  - [3.1. User Stories.](#31-user-stories)
  - [3.2. Impact Mapping.](#32-impact-mapping)
  - [3.3. Product Backlog.](#33-product-backlog)
- [Capítulo IV: Product Design](#capítulo-iv-product-design)
  - [4.1. Style Guidelines.](#41-style-guidelines)
    - [4.1.1. General Style Guidelines.](#411-general-style-guidelines)
    - [4.1.2. Web Style Guidelines.](#412-web-style-guidelines)
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
    - [4.4.2. Web Applications Mock-ups.](#442-web-applications-mock-ups)
    - [4.4.3. Web Applications User Flow Diagrams.](#443-web-applications-user-flow-diagrams)
  - [4.5. Web Applications Prototyping.](#45-web-applications-prototyping)
  - [4.6. Domain-Driven Software Architecture.](#46-domain-driven-software-architecture)
    - [4.6.1. Design-Level EventStorming.](#461-design-level-eventstorming)
    - [4.6.2. Software Architecture Context Diagram.](#462-software-architecture-context-diagram)
    - [4.6.3. Software Architecture Container Diagrams.](#463-software-architecture-container-diagrams)
    - [4.6.4. Software Architecture Components Diagrams.](#464-software-architecture-components-diagrams)
  - [4.7. Software Object-Oriented Design.](#47-software-object-oriented-design)
    - [4.7.1. Class Diagrams.](#471-class-diagrams)
  - [4.8. Database Design.](#48-database-design)
    - [4.8.1. Database Diagrams.](#481-database-diagrams)
- [Capítulo V: Product Implementation, Validation \& Deployment](#capítulo-v-product-implementation-validation--deployment)
  - [5.1. Software Configuration Management.](#51-software-configuration-management)
    - [5.1.1. Software Development Environment Configuration.](#511-software-development-environment-configuration)
    - [5.1.2. Source Code Management.](#512-source-code-management)
    - [5.1.3. Source Code Style Guide \& Conventions.](#513-source-code-style-guide--conventions)
    - [5.1.4. Software Deployment Configuration.](#514-software-deployment-configuration)
  - [5.2. Landing Page, Services \& Applications Implementation.](#52-landing-page-services--applications-implementation)
    - [5.2.X. Sprint n](#52x-sprint-n)
      - [5.2.X.1. Sprint Planning n.](#52x1-sprint-planning-n)
      - [5.2.X.2. Aspect Leaders and Collaborators.](#52x2-aspect-leaders-and-collaborators)
      - [5.2.X.3. Sprint Backlog n.](#52x3-sprint-backlog-n)
      - [5.2.X.4. Development Evidence for Sprint Review.](#52x4-development-evidence-for-sprint-review)
      - [5.2.X.5. Execution Evidence for Sprint Review.](#52x5-execution-evidence-for-sprint-review)
      - [5.2.X.6. Services Documentation Evidence for Sprint Review.](#52x6-services-documentation-evidence-for-sprint-review)
      - [5.2.X.7. Software Deployment Evidence for Sprint Review.](#52x7-software-deployment-evidence-for-sprint-review)
      - [5.2.X.8. Team Collaboration Insights during Sprint.](#52x8-team-collaboration-insights-during-sprint)
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
| Trabaja en equipo para proporcionar liderazgo en forma conjunta                                 |<ul><li><b>Patricio Farias, Ana Camila</b> <br> <b>AV1</b>:Lideré la gestión ágil, facilitación y articulación operativa del equipo a lo largo del ciclo de vida del sprint, asegurando el cumplimiento riguroso de los hitos y entregables fijados. Fomenté una comunicación transversal y continua entre las áreas de diseño, arquitectura y desarrollo, organizando y desglosando las tareas en el tablero de trabajo para optimizar la carga y mitigar bloqueos tempranos. Asimismo, impulsé sesiones colaborativas de toma de decisiones para resolver discrepancias técnicas y de alcance, garantizando la trazabilidad, coherencia e integración de los artefactos producidos y asegurando la alineación constante de los objetivos individuales con la visión global de la solución.</li><br><li><b>Dextre Flores, Leonardo Felix</b> <br> <b>AV1</b>: Organicé mi contribución en una secuencia de artefactos relacionados entre sí, avanzando desde la vista general de la arquitectura hasta el diseño de clases y persistencia. Mantuve una nomenclatura consistente entre los Bounded Contexts, componentes, clases y estructuras de datos, y documenté las responsabilidades principales de cada elemento para facilitar su revisión y posterior utilización por los demás integrantes. También verifiqué la correspondencia entre las decisiones arquitectónicas y las User Stories previamente definidas, procurando evitar dependencias innecesarias entre contextos y dejando una estructura organizada que facilite posteriormente la distribución de tareas de implementación de frontend, backend y persistencia.</li><br><li><b>Salcedo Correa, Carlos Matthew</b> <br> <b>AV1</b>: Asumí el liderazgo técnico en el diseño de experiencia e interfaces de usuario (UX/UI) y en la estructuración de la arquitectura de información para el ecosistema digital de Prothia. Lideré la definición estratégica de SEO y metadatos tanto para la Landing Page pública como para la Web Application, y coordiné activamente con los responsables de requisitos la traducción de los objetivos de usuario hacia los flujos visuales del sistema (wireflows y user flows). Asimismo, proporcioné dirección técnica durante la implementación frontend del Landing Page, asegurando la consistencia entre los artefactos de diseño y el código fuente.</li></ul> <ul><li><b>Ramirez Rodriguez, Mauricio Joao</b> <br> <b>AV1</b>: Colaboré con el equipo planificando y llevando a cabo la fase de entrevistas para recoger los requerimientos del usuario, y elaboré los Style Guidelines del proyecto. Al definir y entregar estas pautas visuales a tiempo, facilité una referencia clara para el diseño de la interfaz, coordinando con el grupo para resolver dudas y cumplir con los objetivos fijados dentro del plazo previsto.</li><br><li><b>Cano Gomez, Yam</b> <br> <b>AV1</b>: Participé activamente en la coordinación y dinamización de las actividades del equipo, facilitando los canales de comunicación y la toma de decisiones conjuntas para asegurar el avance continuo del proyecto. Colaboré estrechamente en la revisión, consolidación y control de calidad de los distintos entregables, apoyando de manera constante a mis compañeros ante bloqueos o contingencias técnicas. Asimismo, promoví la alineación del grupo respecto a las prioridades y cronogramas establecidos, fomentando un entorno de trabajo colaborativo e integrando los aportes individuales para garantizar la coherencia global y el cumplimiento exitoso de los objetivos planteados.</li>  | El trabajo conjunto y la comunicación continua me permitieron asumir un rol activo en la toma de decisiones técnicas y metodológicas del grupo. Al facilitar la coordinación en la estructuración de los requisitos y consensuar la priorización de los artefactos ágiles, contribuí a un liderazgo distribuido donde cada integrante aportó valor de manera equitativa, logrando un flujo de trabajo organizado y alineado con los objetivos del proyecto. Asimismo, la coordinación entre UX/UI, SEO y desarrollo frontend permitió alinear la visión del producto con las necesidades del usuario, reforzando la colaboración y el liderazgo técnico del equipo. |
| Crea un entorno colaborativo e inclusivo, establece metas, planifica tareas y cumple objetivos. |<ul><li><b>Patricio Farias, Ana Camila</b> <br> <b>AV1</b>: Relalice las preguntas de la entrevistas, lo que permitió estructurar el needfinding mediante arquetipos de usuario, matrices de tareas, Journey Map y Empathy Mapp. A partir de estos hallazgos, modelé la lógica del dominio aplicando Big Picture EventStorming y definiendo un lenguaje ubicuo para alinear el negocio con el diseño del sistema. Finalmente, traduje estos requisitos a un marco ágil construyendo el Impact Mapping, especificando las historias de usuario y consolidando el Product Backlog priorizado para el desarrollo del producto.</li><br><li><b>Dextre Flores, Leonardo Felix</b> <br> <b>AV1</b>: Contribuí al diseño técnico de Prothia desarrollando los artefactos de arquitectura comprendidos entre las secciones 4.6.2 y 4.8.1. Definí la representación del sistema mediante los diagramas C4 de contexto, contenedores y componentes, estableciendo los principales actores, sistemas externos, unidades de software y responsabilidades de la solución. Posteriormente desarrollé los diagramas de clases correspondientes a los Bounded Contexts y módulos de soporte, manteniendo consistencia entre las entidades, servicios, interfaces, enumeraciones y relaciones del dominio. Finalmente, estructuré los diagramas de base de datos en PostgreSQL, especificando tablas, atributos, identificadores, claves y restricciones necesarias para mantener la integridad y la separación de responsabilidades entre contextos. Estas decisiones permitieron establecer una referencia técnica común para el equipo durante las siguientes etapas de desarrollo.</li><br><li><b>Salcedo Correa, Carlos Matthew</b> <br> <b>AV1</b>: Diseñé la arquitectura de información integral estableciendo los sistemas de búsqueda, navegación, SEO Tags y Meta Tags para la Landing Page y Web Application. A nivel visual y de interacción, diseñé los wireframes y mock-ups responsive (desktop y mobile) de la Landing Page, así como los wireframes, wireflows por User Goal, mock-ups y User Flow Diagrams (happy y unhappy paths) de la Web Application. Desarrollé además el prototipo interactivo en Figma y apoyé de forma colaborativa en la maquetación y desarrollo web de la Landing Page (HTML5, CSS3 y JavaScript), cumpliendo con los estándares de diseño y accesibilidad definidos.</li></ul> <ul><li><b>Ramirez Rodriguez, Mauricio Joao</b> <br> <b>AV1</b>:Fomenté un entorno colaborativo y estructurado al planificar y ejecutar la fase de entrevistas a los usuarios, definiendo objetivos claros para la recolección de información relevante para el equipo. Con base en estos hallazgos, elaboré los Style Guidelines del proyecto, estableciendo de manera organizada los estándares visuales, componentes y lineamientos de diseño. Gracias a la entrega oportuna de estas guías, facilité la alineación del equipo en el desarrollo de la interfaz, asegurando la coherencia del diseño y el cumplimiento puntual de las metas establecidas para el sprint. </li><br><li><b>Cano Gomez, Yam</b> <br> <b>AV1</b>: Promoví un entorno de trabajo colaborativo durante el desarrollo del Capítulo 1, organizando con el equipo el plan para las entrevistas y el Needfinding. Establecí metas para la recolección de información, prioricé las actividades del entregable y aseguré la participación activa de todos en el análisis de hallazgos. Además, facilité la consolidación de las User Personas, Empathy Maps y User Journey Maps, logrando que el equipo trabajara alineado y cumpliera a tiempo con los objetivos del proyecto.</li>| La articulación de las entrevistas y el análisis competitivo permitió integrar una visión común y fundamentada dentro del equipo, facilitando una planificación clara mediante herramientas como el EventStorming y el Impact Mapping. Este proceso colaborativo aseguró que la definición de historias de usuario y el Product Backlog respondieran a metas viables y medibles, cumpliendo oportunamente con los entregables de elicitación y especificación de requisitos. Asimismo, la definición de la arquitectura de información, el prototipado y la implementación visual aportaron un marco compartido para coordinar tareas, mantener consistencia entre diseño y desarrollo y asegurar la entrega de una experiencia alineada con los objetivos del proyecto. |

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
| **Descripción** | |
| **Foto** | |
----------------------

| **Integrante** | Dextre Flores Leonardo Felix |
| :--- |:-----------------------------|
| **Código del Estudiante** | U202421823                   |
| **Carrera** | Ingeniería de Software       |
| **Descripción** |                              |
| **Foto** |                              |
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
| **Descripción** |                              |
| **Foto** |                              |


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
* Creemos que lograremos una reducción medible en los incidentes de seguridad reportados por nuestros usuarios activos frente a su situación previa sin la plataforma.
* Creemos que lograremos un incremento sostenido en el número de suscripciones mensuales activas mes a mes.
* Creemos que lograremos reducir el costo de adquisición de usuarios mediante el programa de referidos entre trabajadores nocturnos y sus contactos de confianza.

**User Assumptions**
1. Nuestros usuarios principales son trabajadores de turno nocturno entre 20 y 45 años, residentes en zonas urbanas de Lima, pertenecientes a los rubros de seguridad, delivery, salud y call centers, etc.
2. Nuestros usuarios secundarios son los contactos de confianza (familiares, parejas o amigos) de los trabajadores nocturnos, quienes reciben notificaciones automáticas sobre el estado de su trayecto.
3. Existen usuarios con rol de moderación dentro de la comunidad, encargados de validar reportes de incidentes y de información sobre servicios nocturnos.

**User Outcome and Benefit Assumptions**
1. Los trabajadores nocturnos desean sentirse acompañados y seguros durante sus trayectos, y obtienen tranquilidad al saber que un contacto de confianza será notificado automáticamente ante cualquier eventualidad.
2. Los trabajadores nocturnos desean encontrar rápidamente servicios abiertos y confiables durante la noche, y obtienen ahorro de tiempo y menor exposición a situaciones de riesgo.
3. Los trabajadores nocturnos desean sentirse parte de una comunidad que comprenda su realidad laboral, y obtienen acceso a información relevante y beneficios negociados colectivamente.
4. Los contactos de confianza desean tener certeza y tranquilidad sobre la seguridad de su familiar o pareja durante su trayecto nocturno, y obtienen visibilidad del estado del check-in y de la llegada segura, sin necesidad de estar llamando o preguntando constantemente.
5. Los trabajadores nocturnos desean saber qué tan segura es una ruta específica antes de tomarla, y obtienen esa información gracias a las calificaciones y reportes dejados por otros usuarios que la transitaron recientemente.

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

Creemos que lograremos **un aumento en la retención mensual de usuarios activos**
Si **los trabajadores de turno nocturno en Lima**
Obtienen **mayor tranquilidad y acompañamiento durante sus trayectos**
Con **la función de check-in de trayecto seguro y alertas automáticas a contactos de confianza**.

---

**Hipótesis 2**

Creemos que lograremos **un aumento en la frecuencia diaria de uso de la aplicación**
Si **los trabajadores de turno nocturno**
Obtienen **acceso rápido y confiable a servicios abiertos cerca de su ubicación**
Con **el mapa comunitario de servicios activos durante la noche**.

---

**Hipótesis 3**

Creemos que lograremos **una mejora en la calidad y confiabilidad de la información de seguridad de la plataforma**
Si **los trabajadores de turno nocturno**
Obtienen **visibilidad de las zonas de riesgo identificadas por otros usuarios**
Con **el sistema de reporte comunitario de incidentes**.

---

**Hipótesis 4**

Creemos que lograremos **un mayor compromiso (engagement) de los usuarios con la plataforma a largo plazo**
Si **los trabajadores de turno nocturno**
Obtienen **visibilidad de sus patrones de descanso y alertas sobre descanso insuficiente**
Con **la bitácora de descanso y salud del sueño**.

---

**Hipótesis 5**

Creemos que lograremos **una mayor retención de suscriptores y crecimiento orgánico por recomendación (boca a boca)**
Si **los trabajadores de turno nocturno**
Obtienen **un sentido de pertenencia y acceso a beneficios negociados colectivamente (descuentos, seguro básico)**
Con **la comunidad y sus beneficios colectivos negociados a través de la suscripción mensual**.

---

**Hipótesis 6**

Creemos que lograremos **un aumento en el volumen y la calidad de la información de seguridad comunitaria disponible en la plataforma**
Si **los trabajadores de turno nocturno**
Obtienen **la posibilidad de calificar su trayecto y reportar puntos de riesgo específicos al finalizar cada viaje**
Con **el sistema de calificación y reporte de rutas**.

---

**Hipótesis 7**

Creemos que lograremos **una reducción en el tiempo de reacción ante una situación de riesgo real durante un trayecto**
Si **los contactos de confianza y la comunidad de usuarios**
Obtienen **una alerta temprana y verificada sobre un posible incidente en una ruta específica**
Con **la función de marcado automático de "posible incidente" activada cuando la llegada no es confirmada**.

---

**Hipótesis 8**

Creemos que lograremos **un mayor crecimiento orgánico por recomendación (boca a boca) y una reducción del costo de adquisición de usuarios**
Si **los contactos de confianza (familiares y parejas) de los trabajadores de turno nocturno**
Obtienen **visibilidad en tiempo real y tranquilidad respecto al estado del trayecto de su ser querido**
Con **una vista de acompañamiento dedicada para contactos de confianza**.

#### 1.2.2.4. Lean UX Canvas. 
Figura 1
<br>
Lean UX Canvas — SkyCrop
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
    <td> (producto) es una plataforma integral de seguridad, información y comunidad diseñada específicamente para trabajadores de turno nocturno y sus contactos de confianza, que combina check-in de trayecto seguro, calificación y reporte comunitario de rutas, mapa de servicios activos de noche y una comunidad con beneficios colectivos. </td>
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
A partir del análisis competitivo, se han identificado las siguientes estrategias y tácticas para diferenciar a **(producto)** frente a los actores del mercado de seguridad personal y trayectos:

1. **Estrategias de Diferenciación:**

**Especialización en el trabajo nocturno:** A diferencia de bSafe, Noonlight y Safetipin, que ofrecen seguridad personal o auditoría urbana de forma genérica, **(producto)** se enfoca exclusivamente en la realidad de quienes trabajan de noche, combinando check-in de trayecto seguro, calificación de rutas, información comunitaria del entorno y bitácora de descanso, algo que ningún competidor ofrece de forma integrada.

**Calificación de rutas orientada a la acción, no solo al dato:** A diferencia de Safetipin, cuyo enfoque principal es generar datos para gobiernos y planificadores urbanos, **(producto)** utiliza la calificación de rutas directamente para beneficio inmediato del propio usuario (elegir una ruta más segura, recibir alertas de zonas de riesgo cerca de su ubicación en tiempo real).

**Vínculo emocional con contactos de confianza:** A diferencia de bSafe y Noonlight, donde el contacto de confianza solo recibe una alerta puntual ante una emergencia, **(producto)** ofrece un panel de seguimiento continuo pensado para la tranquilidad de familiares y parejas durante todo el trayecto, no solo en el peor escenario.

2. **Tácticas de Marketing:**

**Marketing de nicho y comunidades existentes:** Se realizarán campañas dirigidas específicamente a comunidades y grupos de trabajadores nocturnos en redes sociales, diferenciándonos del marketing masivo y genérico de bSafe y Noonlight.

**Programa de referidos entre trabajador y contacto de confianza:** A diferencia de los competidores, que no explotan este vínculo, **(producto)** incentivará que cada trabajador invite a sus contactos de confianza a la plataforma, generando crecimiento orgánico natural.

3. **Estrategias de Precios:**

**Suscripción con beneficios tangibles desde el inicio:** A diferencia del modelo freemium muy limitado de bSafe y Noonlight, y del modelo sin monetización directa al usuario de Safetipin, **(producto)** ofrecerá una suscripción mensual accesible que desde el primer mes incluye beneficios concretos (seguro básico, descuentos, alertas prioritarias), reforzando la percepción de valor frente al costo.

4. **Expansión y Adaptabilidad:**

**Enfoque regional inicial y expansión nacional:** **(producto)** comenzará en Lima, adaptándose a las necesidades específicas del contexto urbano peruano, antes de expandirse a otros departamentos del pais, a diferencia de competidores como Noonlight y Safetipin, que operan con un enfoque global desde su origen.

**Ecosistema local de servicios nocturnos:** Se buscarán alianzas con negocios y proveedores locales (farmacias, restaurantes, grifos) que deseen aparecer destacados en el mapa comunitario de servicios nocturnos, generando un ecosistema local que ningún competidor internacional replica.

## 2.2. Entrevistas. 

### 2.2.1. Diseño de entrevistas. 
En esta sección, se han planteado diversas preguntas dirigidas a nuestros segmentos objetivos con el objetivo de obtener información relevante, como opiniones o descripciones. Estos datos serán fundamentales para el desarrollo de nuestra solución.

### Segmento Objetivo 1: Trabajadores de turno nocturno

1. ¿Cuál es su nombre, edad, género, distrito de residencia y estado civil?
2. ¿A qué se dedica actualmente, en qué rubro (seguridad, delivery, salud, call center, limpieza, etc.) y hace cuánto tiempo trabaja en turno nocturno?
3. ¿Cómo describiría su personalidad, y qué tan cómodo(a) se siente usando aplicaciones o herramientas tecnológicas nuevas?
4. ¿Qué dispositivo utiliza con más frecuencia y a través de qué canales digitales suele comunicarse o informarse (WhatsApp, redes sociales, apps, etc.)?
5. ¿Cuál es su principal objetivo relacionado con su trabajo nocturno, y cuál es su mayor frustración o preocupación al respecto?
6. Cuénteme cómo es un día típico de su turno nocturno, desde que sale de casa hasta que regresa, incluyendo cómo es su trayecto de ida y vuelta.
7. ¿Alguna vez se ha sentido inseguro(a) o ha vivido una situación de riesgo durante su trayecto nocturno? ¿Puede describirla?
8. ¿Actualmente utiliza alguna herramienta o método para sentirse más seguro(a) en sus trayectos (llamar a alguien, compartir ubicación, etc.)?
9. ¿Qué tan valioso le resultaría contar con una aplicación que avise automáticamente a un contacto de confianza si usted no llega a su destino, y que además le permita calificar o reportar qué tan segura sintió una ruta?
10. ¿Le interesaría formar parte de una comunidad de trabajadores de su mismo rubro para compartir información o beneficios, y estaría dispuesto(a) a pagar una suscripción mensual por ello?
11. ¿Qué características considera indispensables para usar una aplicación de este tipo, y qué situaciones lo llevarían a dejar de usarla?

### Segmento Objetivo 2: Contactos de confianza de trabajadores de turno nocturno

1. ¿Cuál es su nombre, edad, género, distrito de residencia y estado civil?
2. ¿A qué se dedica, y tiene algún familiar, pareja o amigo cercano que trabaje en turno nocturno? ¿Qué relación tiene con esa persona y hace cuánto tiempo trabaja de noche?
3. ¿Cómo describiría su personalidad? ¿Se considera una persona más bien tranquila o más bien ansiosa frente a este tipo de situaciones?
4. ¿Qué aplicaciones usa con más frecuencia en su día a día, y qué tan cómodo(a) se siente aprendiendo a usar una app nueva?
5. Describa cómo es para usted una noche o madrugada típica mientras esa persona está trabajando: ¿qué hace, en qué piensa, revisa el celular con frecuencia?
6. ¿Qué es lo que más le preocupa cuando piensa en la seguridad de esa persona durante su turno o trayecto nocturno?
7. ¿Ha vivido algún momento de angustia real pensando que algo le pudo haber pasado a esa persona? Cuénteme qué ocurrió y cómo lo resolvió.
8. Actualmente, ¿cómo se entera usted de que esa persona llegó bien a su destino? ¿Espera una llamada, un mensaje, o simplemente asume que todo está bien si no recibe noticias?
9. Si esa persona no le avisara dentro del tiempo que usted espera, ¿qué haría? ¿Cuánto tiempo suele esperar antes de preocuparse o intentar contactarla?
10. ¿Qué opina de que una aplicación pueda avisarle automáticamente si esa persona no confirma su llegada, sin que usted tenga que estar pendiente o llamando?
11. ¿Le generaría alguna duda o incomodidad que la ubicación de esa persona se comparta con usted a través de una app? ¿Por qué?
12. ¿Qué la haría confiar en una herramienta así, y qué la haría dejar de usarla o desconfiar de ella?

### 2.2.2. Registro de entrevistas. 
*Registro de entrevistas — Segmento 1*

**Entrevista 1**

| Campo | Detalle                                                                                                                                                                                                                                                                                                                      |
| :--- |:-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Nombre** | Drago Duarte                                                                                                                                                                                                                                                                                                                 |
| **Edad** | 24 años                                                                                                                                                                                                                                                                                                                      |
| **Distrito** | Chorrillos                                                                                                                                                                                                                                                                                                                   |
| **Duración** | 6:02 min                                                                                                                                                                                                                                                                                                                     |
| **Enlace** | https://upcedupe-my.sharepoint.com/:v:/g/personal/u202423775_upc_edu_pe/IQDux7_TpQIoTKigcJ3OziyvAXGE5JXh1KMyGmiDjG4cnek?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJPbmVEcml2ZUZvckJ1c2luZXNzIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXciLCJyZWZlcnJhbFZpZXciOiJNeUZpbGVzTGlua0NvcHkifX0&e=au78gP |

<div align="center">
<img src="resources/imgs/chapter_ii/entrevista1_segmento1.png" alt="Entrevista 1 - Segmento 1" width="600">
</div>

**Resumen**: En esta entrevista, Drago Duarte, un joven de 24 años que trabaja como cajero y vendedor en un Tambo en Chorrillos, comparte su experiencia en el turno de madrugada (9:00 p.m. a 5:00 a.m.). Destaca que su mayor temor es el trayecto de regreso a casa, donde camina por calles desoladas y suele quedarse dormido en el bus, temiendo que le arranchen el celular. Relata un momento de angustia cuando fue seguido por una mototaxi sin luces y tuvo que refugiarse en un grifo. Actualmente, depende de WhatsApp para avisar a su madre y compartir su ubicación, pero se preocupa por quedarse sin datos o batería. Drago valida fuertemente la propuesta de una aplicación que notifique automáticamente a sus contactos y muestre zonas de riesgo en el mapa. Asimismo, afirma que pagaría una suscripción mensual si esta le brinda beneficios tangibles, como un seguro contra robos o descuentos. Sin embargo, recalca que desinstalaría la aplicación si esta consume demasiada batería, presenta errores técnicos o envía falsas alarmas que asusten a su familia.

---
**Entrevista 2**
| Campo | Detalle                                                                                                                                                                                                                                                                                                                      |
| :--- |:-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Nombre** | Marco Antonio Quispe |
| **Edad** | 30 años                                                                                                                                                                                                                                                                                                                      |
| **Distrito** | San Martín de Porres   |
| **Duración** | 7:16 min     |
| **Estado civil** | Soltero   |
| **Ocupación** | Agente de seguridad en almacén logístico (Callao) - Turno nocturno (4 años de experiencia). |
| **Enlace** | https://upcedupe-my.sharepoint.com/:v:/g/personal/u202421823_upc_edu_pe/IQBt_DltFWNKTqbjRVt3MTrsAV1-egdQTWMKSC1w_pa1fGg?e=6o9jIc |

<div align="center">
<img src="resources/imgs/chapter_ii/entrevista2segmento1.png" alt="Entrevista 2 - Segmento 1" width="600">
</div>

**Resumen**: Marco Antonio es un hombre de 30 años, soltero, que reside en San Martín de Porres. Trabaja desde hace 4 años como agente de seguridad en el turno nocturno de un almacén logístico en el Callao. Su rutina implica desplazamientos largos y desgastantes, cruzando la Panamericana Norte de 5:30 p.m. a 7:00 p.m., y retornando a las 6:00 a.m. Su principal motivación es mantener su empleo para aportar económicamente a su hogar, pero su mayor vulnerabilidad y frustración radican en el trayecto de regreso, cuando el agotamiento extremo y el frío se combinan con la desolación y el peligro de las calles a primeras horas de la mañana. 

El trayecto de salida representa una fricción crítica y un riesgo latente comprobado, habiendo sido ya víctima de robo en el transporte público por quedarse dormido debido al cansancio. Para mitigar esta inseguridad, actualmente tiene un protocolo analógico/digital básico: envía mensajes por WhatsApp a su hermano al subir y bajar del bus. Evita compartir su ubicación en tiempo real porque su dispositivo suele terminar el turno con batería crítica (alrededor del 15%), y prioriza mantener el celular encendido antes que activar el GPS continuo. 

De personalidad tranquila pero siempre alerta y pragmática, Marco es un usuario tecnológico funcional y estrictamente "Mobile-First" que utiliza un smartphone Android. Sus canales digitales principales son WhatsApp, que usa tanto para reportes laborales como familiares, y plataformas de consumo rápido como Facebook y TikTok para entretenerse en "tiempos muertos". No busca sofisticación tecnológica; adopta herramientas nuevas solo si son sumamente fáciles de entender y van directo al grano. 

Respecto a la adopción de una nueva plataforma de seguridad, valora altamente la automatización de alertas a contactos de confianza, pero rechaza funcionalidades que exijan esfuerzo adicional, como sacar el móvil en la calle para "calificar rutas" debido a la fatiga y el riesgo de robo. Es financieramente conservador y descarta pagar una suscripción mensual por simple acceso a una comunidad o mapas; solo invertiría si hay un retorno económico directo (descuentos o micro-seguros). Sus factores absolutos de abandono (churn) son dos: que la aplicación drene la poca batería que le queda al salir del trabajo, o que el sistema presente fallas y envíe falsas alarmas que generen pánico innecesario a su familia.


---
**Entrevista 3**
| Campo | Detalle                                                                                                                                                                                                                                                                                                                      |
| :--- |:-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Nombre** | Luis Mendoza Miranda|
| **Edad** | 32 años                                                                                                                                                                                                                                                                                                                      |
| **Distrito** | San Martín de Porres   |
| **Duración** | 5:36     |
| **Estado civil** | Soltero   |
| **Ocupación** | agente de seguridad privada |
| **Enlace** | https://upcedupe-my.sharepoint.com/:v:/g/personal/u202421065_upc_edu_pe/IQAoJA0AjDdKS7A-8S3BD1zeAQ49mq6jaTduIZbRZUYsQSM?e=9jxrdJ |

<div align="center">
<img src="resources/imgs/chapter_ii/entrevista3_segmento1.png" alt="Entrevista 3 - Segmento 1" width="600">
</div>

**Resumen**: Luis Mendoza Miranda es un hombre soltero de 32 años ,  que reside en el distrito de San Martín de Porres. Trabaja desde hace 2 años y medio como agente de seguridad privada en el turno nocturno de un centro corporativo en San Isidro. Su jornada implica traslados largos y pesados en transporte público, saliendo a las 5:20 p.m. para iniciar a las 7:00 p.m. y retornando a las 7:00 a.m. Su principal motivación es la estabilidad económica de su hogar, aprovechando el ingreso adicional del bono nocturno, pero su mayor preocupación es la inseguridad latente durante los traslados y el agotamiento físico crónico provocado por el cambio de ciclo de sueño.

El trayecto de retorno y la espera en paraderos representan una fricción crítica y un riesgo comprobado, habiendo vivido un intento de asalto por parte de delincuentes en moto mientras esperaba transporte de madrugada. Para mitigar esta vulnerabilidad, mantiene un protocolo de prevención activo: comparte su ubicación en tiempo real por WhatsApp con su pareja al finalizar su guardia y guarda el celular en un bolsillo interno con cierre mientras viaja en el transporte público.

De personalidad reservada, observadora y práctica, Luis es un usuario tecnológico funcional que utiliza un smartphone Android de gama media. Sus canales digitales principales son WhatsApp, herramienta clave para la coordinación laboral y la comunicación familiar, y redes como Facebook, TikTok y grupos vecinales para mantenerse informado sobre alertas locales. Tiene una adopción tecnológica pragmática: maneja sin problemas herramientas de uso diario, pero descarta interfaces engorrosas o aplicaciones que requieran pasos innecesarios.

Respecto a una nueva solución tecnológica de seguridad, considera sumamente valiosa la automatización de avisos a contactos de confianza ante eventualidades o falta de batería, así como el reporte de rutas para prevenir paraderos peligrosos. Muestra un claro interés por integrarse a una comunidad laboral para intercambiar alertas, aunque descarta por completo pagar una suscripción mensual debido a que prioriza los gastos básicos familiares, aceptando el servicio únicamente bajo un modelo gratuito. Sus factores determinantes de abandono (churn) son el consumo excesivo de batería o datos móviles durante el turno nocturno, y los errores de sistema que detonen falsas alarmas y generen angustia innecesaria en su familia. 


---

*Registro de entrevistas — Segmento 2*

**Entrevista 1**

| Campo | Detalle                |
| :--- |:-----------------------|
| **Nombre** | Juan Gutierrez         |
| **Edad** | 24 años                |
| **Distrito** | San Juan de Miraflores |
| **Duración** | 5:57 min               |
| **Enlace** |https://upcedupe-my.sharepoint.com/:v:/g/personal/u202423775_upc_edu_pe/IQBBwCDLDYdtSJDvTpf3VT-EAY3r4Ss02w-EYfW38XfSQ2E?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJPbmVEcml2ZUZvckJ1c2luZXNzIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXciLCJyZWZlcnJhbFZpZXciOiJNeUZpbGVzTGlua0NvcHkifX0&e=hDDVYf |

<div align="center">
<img src="resources/imgs/chapter_ii/entrevista1_segmento2.png" alt="Entrevista 1 - Segmento 2" width="600">
</div>

**Resumen**: En esta entrevista, Juan Gutiérrez, un estudiante universitario de 24 años, comparte su experiencia como contacto de confianza de su hermano menor, quien trabaja de madrugada en un Oxxo. Destaca que su mayor preocupación es el trayecto desolado que su hermano debe recorrer desde el trabajo hasta el paradero del bus a las 5:00 a.m. También menciona que actualmente dependen de mensajes de WhatsApp para confirmar que su hermano ha subido al transporte y ha llegado a casa, relatando un episodio de mucha angustia que vivió cuando el celular de su hermano se apagó en el trayecto. Explica que compartir la ubicación no genera ninguna incomodidad entre ellos, ya que la prioridad absoluta es la protección familiar. Finalmente, describe que confiaría en una aplicación de monitoreo pasivo si las notificaciones son precisas y llegan a tiempo, pero la descartaría inmediatamente si presenta errores técnicos, consume rápidamente la batería del celular o si lanza falsas alarmas de pánico que lo asusten de la nada.

---
**Entrevista 2**

| Campo | Detalle                |
| :--- |:-----------------------|
| **Nombre** | Roberto Carlos Fernández  |
| **Edad** | 42 años                |
| **Estado civil** | Casado                |
| **Ocupación** | Freelance             |
| **Distrito** | San Juan de Lurigancho |
| **Duración** | 6:46 min               |
| **Enlace** |https://upcedupe-my.sharepoint.com/:v:/g/personal/u20241i469_upc_edu_pe/IQAz-r_0LzsSQJUPbxKTl7oaAcTpRAyzqHmi6tNBz6vn7d0?e=qeV5bz&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D|

<div align="center">
<img src="resources/imgs/chapter_ii/entrevistaSegmento2-Roberto.png" alt="Entrevista 1 - Segmento 2" width="600">
</div>

**Resumen**: Roberto Carlos Fernández es un trabajador independiente de 42 años, casado y residente en el distrito de San Juan de Lurigancho, Lima. Su esposa se desempeña desde hace cuatro años como técnico de mantenimiento en turnos rotativos y nocturnos, cubriendo usualmente jornadas de diez de la noche a seis de la mañana. Aunque durante el día se considera una persona tranquila, experimenta constantes episodios de ansiedad y preocupación en torno a la seguridad de su cónyuge, atribuyendo su inquietud a la peligrosidad de la zona donde residen y a la desolación de las calles durante las madrugadas. Durante el turno de su esposa, su descanso suele ser intermitente, despertándose en varias oportunidades para escribirle y consultar cómo se encuentra.

El mayor temor del entrevistado se concentra en los trayectos de regreso a casa a tempranas horas de la mañana, debido al riesgo latente de accidentes o actos delictivos en avenidas poco transitadas. Relata como experiencia de angustia crítica un episodio en el que su esposa demoró cerca de dos horas en comunicarse tras finalizar su turno laboral. En una ocasión no se podia contactar con ella tras reiteradas llamadas fallidas, la situación se esclareció al confirmarse que el teléfono de ella se había quedado sin batería hasta que pudo recargarlo mediante una batería externa y se logro comunicar con el. Actualmente, el protocolo de verificación recae en el envío voluntario de mensajes por WhatsApp al momento de abordar el transporte y al llegar a destino, esperando un margen de tolerancia aproximado de 30 minutos antes de escalar a llamadas telefónicas directas o contactar a compañeras de trabajo.

Ante esta constante incertidumbre, Roberto considera fundamental contar con una herramienta tecnológica que emita alertas automáticas únicamente ante retrasos o anomalías en los trayectos, permitiéndole descansar sin revisar el celular compulsivamente. No obstante, condiciona el uso de este sistema a que el rastreo de ubicación opere de forma puntual y transparente durante los traslados hacia o desde el trabajo, resguardando la privacidad de su pareja para evitar conductas invasivas y garantizando la estricta protección de sus datos.

---
**Entrevista 3**


| Campo | Detalle                |
| :--- |:-----------------------|
| **Nombre** | Ronald Ramírez         |
| **Edad** | 51 años                |
| **Distrito** | Bellavista, Callao     |
| **Duración** | 5:00 min               |
| **Enlace** | https://upcedupe-my.sharepoint.com/:v:/g/personal/u202218235_upc_edu_pe/IQCHCDbrqzODRKhF84bxBViOAcXq2EV7CrAvOLCkhijcgb8?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D&e=cURYcK |

<div align="center">
<img src="resources/imgs/chapter_ii/entrevista3_segmento2.png" alt="Entrevista 2 - Segmento 2" width="600">
</div>

**Resumen**: En esta entrevista, Ronald Ramírez, un asistente administrativo de 51 años residente en Bellavista, Callao, comparte su experiencia como contacto de confianza de su esposa, quien labora como enfermera en el turno nocturno. Explica que se considera organizado y previsor, pero siente constante ansiedad por la seguridad de su esposa frente a la delincuencia y posibles accidentes de tránsito durante sus traslados. Menciona que en su rutina nocturna duerme con el celular a volumen alto para estar alerta ante cualquier emergencia y que siempre esperan un mensaje de confirmación al llegar a su destino, relatando un episodio de mucha angustia donde su esposa demoró más de 30 minutos sin responder porque se le había descargado el celular. Destaca que compartir la ubicación entre ambos es un acuerdo normal que no le genera ninguna incomodidad y que una aplicación de notificación automática de llegada le brindaría un gran alivio para conciliar el sueño. Finalmente, afirma que confiaría en una herramienta así si las alertas y la ubicación son precisas, pero la descartaría si genera falsas alarmas constantemente o consume la batería demasiado rápido.

---

### 2.2.3. Análisis de entrevistas. 

#### **Análisis del Segmento 1: Trabajadores Nocturnos (Usuarios Principales)**

A partir de las entrevistas realizadas a trabajadores de turno nocturno (cajeros de tiendas de conveniencia y agentes de seguridad), se identifican patrones claros en sus hábitos de traslado, nivel de exposición al riesgo, uso de tecnología y expectativas de seguridad:

* **Entorno laboral y nivel de riesgo:** El 100% de los entrevistados (3 de 3) labora en jornadas de madrugada (entre 5:00 p. m. y 7:00 a. m.) y señala que los trayectos a pie de regreso a casa y la espera en paraderos representan el momento de mayor vulnerabilidad y temor. Asimismo, el 100% (3 de 3) ha sido víctima directa de la delincuencia o ha enfrentado situaciones de riesgo alto en el transporte público o la vía pública (como ser perseguidos por vehículos sospechosos, intentos de asalto en moto o robos al quedarse dormidos por cansancio).
* **Protocolos actuales de prevención:** El 100% utiliza WhatsApp como herramienta principal para enviar mensajes a sus contactos de confianza al abordar o descender del transporte. Sin embargo, el 100% enfrenta una restricción crítica: la falta de batería (llegando al final del turno con carga crítica de 15% o totalmente descargados) y el temor a quedarse sin datos móviles, lo que limita el uso continuo del GPS en tiempo real.
* **Perfil tecnológico y usabilidad:** El 100% de los entrevistados es usuario de smartphones Android con un enfoque estrictamente *Mobile-First* y pragmático. Utilizan redes sociales (Facebook, TikTok) e interacción por WhatsApp, pero el 100% rechaza tajantemente aplicaciones con interfaces complejas o que exijan interactuar de forma activa con el teléfono en la calle (como calificar rutas manualmente), ya que el cansancio acumulado y el riesgo de exhibir el celular en la vía pública representan una fricción inaceptable.
* **Valoración de la propuesta de solución:** El 100% de los entrevistados valida positivamente la automatización de notificaciones a sus contactos de confianza ante eventualidades o falta de confirmación de llegada, así como la visualización de zonas de riesgo o paraderos peligrosos.
* **Disposición al pago (monetización):** Solo el 33% (1 de 3) estaría dispuesto a pagar una suscripción mensual si esta incluye beneficios tangibles (como seguros contra robos o descuentos), mientras que el 66% (2 de 3) prioriza los gastos básicos del hogar y descarta pagos recurrentes, aceptando el servicio únicamente bajo un modelo gratuito o con retorno económico directo.
* **Criterios de abandono (*churn*):** El 100% de los entrevistados afirma que desinstalaría la aplicación de manera inmediata si genera un consumo excesivo de batería o datos, si presenta errores técnicos (*bugs*) o si emite falsas alarmas que generen angustia o pánico innecesario en sus familias.

---

#### **Análisis del Segmento 2: Contactos de Confianza (Familiares y Parejas)**

A partir de las entrevistas realizadas a los contactos de confianza (familiares directos y cónyuges de trabajadores nocturnos), se identifican patrones comunes sobre el impacto emocional del turno nocturno, los hábitos de verificación y la aceptación de herramientas de monitoreo:

* **Impacto emocional y percepción del riesgo:** El 100% de los entrevistados (2 de 2) experimenta altos niveles de ansiedad, preocupación constante e interrupción de su descanso nocturno debido a la inseguridad ciudadana y al riesgo de accidentes durante los traslados de sus familiares. El 100% identifica los trayectos solitarios desde el centro de trabajo hacia el transporte público a tempranas horas de la mañana como la principal fuente de inquietud.
* **Gestión de comunicación y verificación:** El 100% depende del envío voluntario de mensajes de WhatsApp por parte del trabajador al iniciar el retorno o llegar a su destino, estableciendo un margen de tolerancia previo de entre 15 y 30 minutos antes de escalar a llamadas insistentes o contactar a terceros. Además, el 100% ha vivido episodios de angustia crítica provocados por la imposibilidad de comunicarse cuando el teléfono del trabajador se apaga por falta de batería durante el trayecto.
* **Privacidad y consentimiento:** El 100% de los entrevistados indica que compartir la ubicación en tiempo real no genera ninguna incomodidad entre las partes, siempre que se realice bajo un acuerdo mutuo enfocado en la protección familiar y resguardando la privacidad sin caer en conductas invasivas.
* **Validación de la propuesta tecnológica:** El 100% considera fundamental contar con un sistema de monitoreo pasivo que emita alertas automáticas únicamente ante retrasos desmedidos o anomalías en la ruta, permitiéndoles conciliar el sueño y descansar sin la necesidad de revisar compulsivamente el celular.
* **Factores de desconfianza y abandono:** El 100% de los entrevistados condiciona la adopción del sistema a la precisión y puntualidad del rastreo. Del mismo modo, el 100% dejaría de utilizar la herramienta si emite falsas alarmas de pánico de manera recurrente, si genera errores de sistema o si agota rápidamente la batería del dispositivo de su familiar.

---



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

### Epics:
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

### User Stories:
Requisitos definidos junto con el conjunto de User Stories y Epics para los requisitos identificados. Las User Stories incluyen Acceptance Criteria redactados en tiempo presente, tercera persona, sin hacer referencia a detalles de interfaz de usuario, siguiendo la estructura de Gherkin (Given-When-Then). Se incluyen además User Stories para el sitio web estático (Landing Page), tomando como rol base visitante.

| Epic / Story ID | Título | Descripción | Criterios de Aceptación | Relacionado con (Epic ID) |
| :--- | :--- | :--- | :--- | :--- |
| **US-01** | Registro de usuario | Como nuevo usuario, quiero registrarme indicando mi rol (trabajador de turno nocturno o contacto de confianza) para poder acceder a la plataforma y sus funcionalidades. | **Escenario 1: Registro exitoso**<br>Dado que el nuevo usuario ingresa todos los datos requeridos de forma correcta,<br>Cuando envía el formulario de registro,<br>Entonces su cuenta es creada correctamente y se le asigna el rol seleccionado.<br><br>**Escenario 2: Registro con correo ya existente**<br>Dado que el nuevo usuario intenta registrarse con un correo ya registrado en el sistema,<br>Cuando envía el formulario de registro,<br>Entonces el sistema muestra un mensaje indicando que el correo ya existe. | EP-01 |
| **US-02** | Inicio de sesión | Como usuario registrado, quiero iniciar sesión con mi correo y contraseña para acceder a mi cuenta y a las funcionalidades correspondientes a mi rol. | **Escenario 1: Inicio de sesión exitoso**<br>Dado que el usuario tiene una cuenta activa y credenciales correctas,<br>Cuando inicia sesión,<br>Entonces el sistema le concede acceso a su cuenta según su rol.<br><br>**Escenario 2: Credenciales incorrectas**<br>Dado que el usuario ingresa una contraseña incorrecta,<br>Cuando intenta iniciar sesión,<br>Entonces el sistema deniega el acceso y muestra un mensaje de error. | EP-01 |
| **US-03** | Recuperación de contraseña | Como usuario, quiero solicitar la recuperación de mi contraseña olvidada para poder restablecer el acceso a mi cuenta. | **Escenario 1: Solicitud de recuperación exitosa**<br>Dado que el usuario registra un correo asociado a una cuenta existente,<br>Cuando solicita la recuperación de contraseña,<br>Entonces el sistema envía un enlace de restablecimiento a dicho correo.<br><br>**Escenario 2: Correo no registrado**<br>Dado que el usuario ingresa un correo que no está registrado en el sistema,<br>Cuando solicita la recuperación de contraseña,<br>Entonces el sistema indica que no existe una cuenta asociada a ese correo. | EP-01 |
| **US-04** | Edición de perfil | Como usuario, quiero editar mis datos personales y de contacto para mantener mi información actualizada dentro de la plataforma. | **Escenario 1: Edición exitosa de perfil**<br>Dado que el usuario ha iniciado sesión y modifica alguno de sus datos personales,<br>Cuando guarda los cambios,<br>Entonces el sistema actualiza la información del perfil correctamente.<br><br>**Escenario 2: Edición con dato inválido**<br>Dado que el usuario ingresa un dato con un formato inválido en su perfil,<br>Cuando intenta guardar los cambios,<br>Entonces el sistema rechaza la actualización y señala el campo inválido. | EP-01 |
| **US-05** | Conocer la propuesta de valor | Como visitante del sitio web, quiero conocer la propuesta de valor y las funcionalidades principales de la plataforma en la landing page para decidir si deseo registrarme. | **Escenario 1: Visualización de la propuesta de valor**<br>Dado que el visitante ingresa a la landing page,<br>Cuando la página carga completamente,<br>Entonces se muestran la propuesta de valor, las funcionalidades principales y un llamado a la acción para registrarse.<br><br>**Escenario 2: Acceso desde la landing page al registro**<br>Dado que el visitante se encuentra en la landing page,<br>Cuando selecciona la opción de registro,<br>Entonces el sistema lo redirige al formulario de creación de cuenta. | EP-01 |
| **US-06** | Invitar contacto de confianza | Como trabajador nocturno, quiero invitar a un contacto de confianza mediante su correo o número de teléfono para que pueda recibir notificaciones sobre mis trayectos. | **Escenario 1: Invitación enviada correctamente**<br>Dado que el trabajador nocturno ingresa un correo o número válido,<br>Cuando envía la invitación,<br>Entonces el sistema notifica al contacto de confianza sobre la invitación recibida.<br><br>**Escenario 2: Invitación a contacto ya vinculado**<br>Dado que el trabajador nocturno intenta invitar a un contacto que ya está vinculado a su cuenta,<br>Cuando envía la invitación,<br>Entonces el sistema indica que el contacto ya se encuentra vinculado. | EP-02 |
| **US-07** | Aceptar o rechazar invitación | Como contacto de confianza, quiero aceptar o rechazar una invitación recibida para decidir si deseo vincularme a un trabajador nocturno. | **Escenario 1: Invitación aceptada**<br>Dado que el contacto de confianza recibe una invitación pendiente,<br>Cuando acepta la invitación,<br>Entonces el vínculo entre ambos usuarios queda establecido.<br><br>**Escenario 2: Invitación rechazada**<br>Dado que el contacto de confianza recibe una invitación pendiente,<br>Cuando rechaza la invitación,<br>Entonces el vínculo no se establece y el trabajador nocturno es notificado del rechazo. | EP-02 |
| **US-08** | Remover contacto de confianza | Como trabajador nocturno, quiero eliminar un contacto de confianza vinculado para dejar de compartir información sobre mis trayectos con él. | **Escenario 1: Eliminación exitosa**<br>Dado que el trabajador nocturno tiene un contacto de confianza vinculado,<br>Cuando elimina el vínculo,<br>Entonces el contacto deja de recibir notificaciones sobre sus trayectos.<br><br>**Escenario 2: Confirmación previa a la eliminación**<br>Dado que el trabajador nocturno solicita eliminar un contacto vinculado,<br>Cuando el sistema solicita confirmación,<br>Entonces la eliminación solo se ejecuta si el trabajador confirma la acción. | EP-02 |
| **US-09** | Iniciar check-in de trayecto seguro | Como trabajador nocturno, quiero iniciar un check-in de trayecto indicando mi destino y tiempo estimado de llegada para activar el acompañamiento pasivo del sistema. | **Escenario 1: Check-in iniciado correctamente**<br>Dado que el trabajador nocturno indica un destino y un tiempo estimado válido,<br>Cuando inicia el check-in,<br>Entonces el sistema activa el seguimiento del trayecto y notifica a sus contactos de confianza.<br><br>**Escenario 2: Intento de iniciar check-in con uno activo**<br>Dado que el trabajador nocturno ya tiene un check-in activo,<br>Cuando intenta iniciar un nuevo check-in,<br>Entonces el sistema le indica que primero debe finalizar o cancelar el trayecto en curso. | EP-03 |
| **US-10** | Confirmar llegada segura | Como trabajador nocturno, quiero confirmar mi llegada al finalizar el trayecto para cerrar el check-in y notificar a mis contactos de confianza que llegué bien. | **Escenario 1: Confirmación de llegada dentro del tiempo estimado**<br>Dado que el trabajador nocturno tiene un check-in activo,<br>Cuando confirma su llegada,<br>Entonces el sistema cierra el check-in y notifica a sus contactos de confianza que llegó de forma segura.<br><br>**Escenario 2: Confirmación de llegada fuera del margen de tolerancia**<br>Dado que el trabajador nocturno confirma su llegada después de haberse generado un posible incidente,<br>Cuando registra la confirmación,<br>Entonces el sistema cierra el incidente como falso positivo y notifica a los contactos de confianza. | EP-03 |
| **US-11** | Cancelar check-in activo | Como trabajador nocturno, quiero cancelar un check-in en curso en caso de un cambio de planes para evitar que se generen alertas innecesarias. | **Escenario 1: Cancelación exitosa**<br>Dado que el trabajador nocturno tiene un check-in activo,<br>Cuando cancela el check-in,<br>Entonces el sistema detiene el seguimiento del trayecto sin generar alertas.<br><br>**Escenario 2: Intento de cancelar un check-in ya cerrado**<br>Dado que el check-in del trabajador nocturno ya fue cerrado previamente,<br>Cuando intenta cancelarlo,<br>Entonces el sistema indica que no existe un check-in activo para cancelar. | EP-03 |
| **US-12** | Marcado automático de posible incidente | Como trabajador nocturno, quiero que el sistema marque automáticamente un posible incidente cuando no confirmo mi llegada dentro del margen de tolerancia, para que mis contactos de confianza sean alertados. | **Escenario 1: Generación automática de posible incidente**<br>Dado que un check-in activo supera el tiempo estimado más el margen de tolerancia sin confirmación de llegada,<br>Cuando el sistema evalúa el estado del trayecto,<br>Entonces se genera un posible incidente y se notifica a los contactos de confianza.<br><br>**Escenario 2: Sin generación de incidente dentro del margen de tolerancia**<br>Dado que un check-in activo aún se encuentra dentro del margen de tolerancia establecido,<br>Cuando el sistema evalúa el estado del trayecto,<br>Entonces no se genera ningún posible incidente. | EP-04 |
| **US-13** | Validar posible incidente | Como trabajador nocturno, quiero validar o descartar un posible incidente marcado por el sistema para confirmar mi estado real ante mis contactos de confianza. | **Escenario 1: Incidente descartado por el usuario**<br>Dado que existe un posible incidente activo asociado al trabajador nocturno,<br>Cuando el trabajador indica que se encuentra bien,<br>Entonces el sistema cierra el incidente como falso positivo y notifica a los contactos de confianza.<br><br>**Escenario 2: Incidente confirmado por el usuario**<br>Dado que existe un posible incidente activo asociado al trabajador nocturno,<br>Cuando el trabajador confirma que necesita ayuda,<br>Entonces el sistema mantiene el incidente como activo y escala la alerta a los contactos de confianza. | EP-04 |
| **US-14** | Recibir alerta de posible incidente | Como contacto de confianza, quiero recibir una alerta inmediata cuando se detecte un posible incidente en el trayecto de mi trabajador vinculado para poder actuar rápidamente. | **Escenario 1: Alerta recibida correctamente**<br>Dado que se genera un posible incidente para un trabajador vinculado,<br>Cuando el sistema procesa la alerta,<br>Entonces el contacto de confianza recibe la notificación de forma inmediata.<br><br>**Escenario 2: Actualización del estado del incidente**<br>Dado que un posible incidente previamente notificado es descartado por el trabajador nocturno,<br>Cuando el sistema actualiza el estado del incidente,<br>Entonces el contacto de confianza recibe una notificación indicando que el trabajador se encuentra bien. | EP-04 |
| **US-15** | Buscar servicios nocturnos cercanos | Como trabajador nocturno, quiero buscar en el mapa comunitario los servicios abiertos cerca de mi ubicación para encontrar rápidamente lo que necesito durante mi turno. | **Escenario 1: Búsqueda con resultados**<br>Dado que existen servicios nocturnos validados cerca de la ubicación del trabajador,<br>Cuando realiza la búsqueda,<br>Entonces el sistema muestra la lista de servicios disponibles ordenados por cercanía.<br><br>**Escenario 2: Búsqueda sin resultados**<br>Dado que no existen servicios nocturnos registrados cerca de la ubicación del trabajador,<br>Cuando realiza la búsqueda,<br>Entonces el sistema indica que no se encontraron servicios en la zona. | EP-05 |
| **US-16** | Reportar nuevo servicio nocturno | Como trabajador nocturno, quiero reportar un nuevo establecimiento abierto de madrugada para contribuir con información útil a la comunidad. | **Escenario 1: Reporte enviado correctamente**<br>Dado que el trabajador nocturno completa los datos requeridos de un nuevo servicio,<br>Cuando envía el reporte,<br>Entonces el sistema lo registra con estado pendiente de validación.<br><br>**Escenario 2: Reporte de un servicio ya existente**<br>Dado que el trabajador nocturno intenta reportar un servicio que ya se encuentra registrado en la misma ubicación,<br>Cuando envía el reporte,<br>Entonces el sistema le indica que el servicio ya existe en el mapa. | EP-05 |
| **US-17** | Calificar un servicio nocturno reportado | Como trabajador nocturno, quiero calificar la veracidad de un servicio reportado por otro usuario para ayudar a mantener el mapa comunitario actualizado y confiable. | **Escenario 1: Calificación registrada**<br>Dado que el trabajador nocturno visita un servicio previamente reportado,<br>Cuando envía su calificación sobre la veracidad del servicio,<br>Entonces el sistema actualiza el puntaje de confiabilidad del servicio.<br><br>**Escenario 2: Servicio con baja confiabilidad**<br>Dado que un servicio acumula un número de calificaciones negativas por encima del umbral definido,<br>Cuando el sistema recalcula el puntaje de confiabilidad,<br>Entonces el servicio es marcado para revisión de un moderador. | EP-05 |
| **US-18** | Calificar seguridad de ruta | Como trabajador nocturno, quiero calificar qué tan segura se sintió una ruta al finalizar mi trayecto para aportar información a la comunidad de trabajadores. | **Escenario 1: Calificación registrada al finalizar el trayecto**<br>Dado que el trabajador nocturno finaliza un check-in de trayecto,<br>Cuando registra una calificación de seguridad de la ruta,<br>Entonces el sistema almacena la calificación asociada a esa ruta.<br><br>**Escenario 2: Intento de calificar sin trayecto finalizado**<br>Dado que el trabajador nocturno no cuenta con un trayecto recientemente finalizado,<br>Cuando intenta registrar una calificación de ruta,<br>Entonces el sistema le indica que debe finalizar un trayecto antes de calificarlo. | EP-06 |
| **US-19** | Reportar punto de riesgo específico | Como trabajador nocturno, quiero marcar un punto específico de la ruta como sospechoso o peligroso para alertar a otros usuarios sobre esa zona. | **Escenario 1: Reporte de punto de riesgo exitoso**<br>Dado que el trabajador nocturno identifica un punto específico durante su trayecto,<br>Cuando reporta dicho punto como zona de riesgo,<br>Entonces el sistema registra la ubicación y la asocia al mapa comunitario de riesgo.<br><br>**Escenario 2: Reporte con descripción insuficiente**<br>Dado que el trabajador nocturno intenta reportar un punto de riesgo sin indicar el motivo,<br>Cuando envía el reporte,<br>Entonces el sistema rechaza el envío y solicita completar el motivo del reporte. | EP-06 |
| **US-20** | Visualizar mapa de zonas de riesgo | Como trabajador nocturno, quiero visualizar en el mapa las zonas calificadas como riesgosas por la comunidad para evitarlas antes de iniciar mi trayecto. | **Escenario 1: Visualización de zonas de riesgo**<br>Dado que existen zonas de riesgo reportadas y validadas en el área del trabajador,<br>Cuando consulta el mapa comunitario,<br>Entonces el sistema muestra dichas zonas señaladas junto con su nivel de riesgo.<br><br>**Escenario 2: Área sin reportes de riesgo**<br>Dado que no existen reportes de riesgo validados en el área consultada,<br>Cuando el trabajador consulta el mapa,<br>Entonces el sistema indica que no hay zonas de riesgo registradas en esa área. | EP-06 |
| **US-21** | Registrar horas de descanso | Como trabajador nocturno, quiero registrar mis horas de sueño diurno para llevar un control de mi descanso y bienestar físico. | **Escenario 1: Registro exitoso de descanso**<br>Dado que el trabajador nocturno ingresa la hora de inicio y fin de su descanso,<br>Cuando guarda el registro,<br>Entonces el sistema almacena la información en su bitácora de sueño.<br><br>**Escenario 2: Registro con datos inconsistentes**<br>Dado que el trabajador nocturno ingresa una hora de fin anterior a la hora de inicio,<br>Cuando intenta guardar el registro,<br>Entonces el sistema rechaza el registro y señala la inconsistencia. | EP-07 |
| **US-22** | Visualizar historial de descanso | Como trabajador nocturno, quiero visualizar el historial de mis registros de sueño para identificar patrones en mi descanso a lo largo del tiempo. | **Escenario 1: Historial disponible**<br>Dado que el trabajador nocturno cuenta con registros previos de descanso,<br>Cuando consulta su bitácora,<br>Entonces el sistema muestra el historial ordenado cronológicamente.<br><br>**Escenario 2: Historial vacío**<br>Dado que el trabajador nocturno no cuenta con registros previos de descanso,<br>Cuando consulta su bitácora,<br>Entonces el sistema indica que aún no existen registros disponibles. | EP-07 |
| **US-23** | Recibir sugerencia de higiene del sueño | Como trabajador nocturno, quiero recibir sugerencias cuando mi descanso ha sido insuficiente durante un periodo determinado para cuidar mi bienestar físico. | **Escenario 1: Sugerencia generada por descanso insuficiente**<br>Dado que el trabajador nocturno registra un promedio de horas de sueño por debajo del umbral recomendado,<br>Cuando el sistema evalúa su bitácora,<br>Entonces se genera una sugerencia de higiene del sueño para el trabajador.<br><br>**Escenario 2: Descanso dentro de parámetros saludables**<br>Dado que el trabajador nocturno mantiene un promedio de horas de sueño dentro del rango recomendado,<br>Cuando el sistema evalúa su bitácora,<br>Entonces no se genera ninguna sugerencia adicional. | EP-07 |
| **US-24** | Consultar planes de suscripción (Landing Page) | Como visitante del sitio web, quiero consultar los planes de suscripción disponibles y sus beneficios para decidir si deseo registrarme en la plataforma. | **Escenario 1: Visualización de planes**<br>Dado que el visitante accede a la sección de planes en la landing page,<br>Cuando la página carga,<br>Entonces se muestran los planes de suscripción disponibles con sus respectivos beneficios y precios.<br><br>**Escenario 2: Selección de un plan desde la landing page**<br>Dado que el visitante revisa los planes disponibles,<br>Cuando selecciona un plan específico,<br>Entonces el sistema lo redirige al formulario de registro con el plan preseleccionado. | EP-08 |
| **US-25** | Suscribirse al plan mensual | Como trabajador nocturno, quiero suscribirme al plan mensual de la plataforma para acceder a los beneficios colectivos negociados. | **Escenario 1: Suscripción exitosa**<br>Dado que el trabajador nocturno selecciona un plan y completa el pago correctamente,<br>Cuando confirma la suscripción,<br>Entonces el sistema activa su membresía y le otorga acceso a los beneficios correspondientes.<br><br>**Escenario 2: Pago rechazado**<br>Dado que el trabajador nocturno intenta suscribirse con un medio de pago rechazado,<br>Cuando el sistema procesa el pago,<br>Entonces la suscripción no se activa y se le notifica el motivo del rechazo. | EP-08 |
| **US-26** | Acceder a beneficios y descuentos | Como trabajador nocturno con suscripción activa, quiero visualizar y acceder a los descuentos y beneficios negociados colectivamente para aprovecharlos. | **Escenario 1: Acceso a beneficios con suscripción activa**<br>Dado que el trabajador nocturno cuenta con una suscripción activa,<br>Cuando consulta la sección de beneficios,<br>Entonces el sistema muestra los descuentos y coberturas disponibles para su membresía.<br><br>**Escenario 2: Intento de acceso sin suscripción activa**<br>Dado que el trabajador nocturno no cuenta con una suscripción activa,<br>Cuando intenta acceder a la sección de beneficios,<br>Entonces el sistema le indica que debe suscribirse para acceder a dicho contenido. | EP-08 |
| **US-27** | Referir a un contacto para obtener beneficio | Como trabajador nocturno, quiero invitar a otro trabajador mediante un código de referido para obtener un beneficio en mi suscripción cuando este se registre. | **Escenario 1: Referido registrado exitosamente**<br>Dado que un nuevo usuario se registra utilizando el código de referido de un trabajador nocturno,<br>Cuando el registro se completa,<br>Entonces el sistema otorga el beneficio correspondiente al trabajador que refirió.<br><br>**Escenario 2: Uso de código de referido inválido**<br>Dado que un nuevo usuario ingresa un código de referido inexistente,<br>Cuando intenta completar el registro,<br>Entonces el sistema le indica que el código ingresado no es válido, sin bloquear el registro. | EP-08 |
| **US-28** | Visualizar estado de trayecto en tiempo real | Como contacto de confianza, quiero visualizar el estado actual del trayecto de mi trabajador vinculado para tener tranquilidad sin necesidad de llamarlo. | **Escenario 1: Trayecto en curso**<br>Dado que el trabajador vinculado tiene un check-in activo,<br>Cuando el contacto de confianza consulta el panel de seguimiento,<br>Entonces el sistema muestra el estado actual del trayecto y el tiempo estimado de llegada.<br><br>**Escenario 2: Sin trayecto activo**<br>Dado que el trabajador vinculado no tiene ningún check-in activo,<br>Cuando el contacto de confianza consulta el panel de seguimiento,<br>Entonces el sistema indica que no hay un trayecto en curso. | EP-09 |
| **US-29** | Configurar preferencias de notificación | Como contacto de confianza, quiero configurar qué tipo de notificaciones deseo recibir (inicio de trayecto, llegada, posibles incidentes) para adaptar la app a mis necesidades. | **Escenario 1: Preferencias guardadas correctamente**<br>Dado que el contacto de confianza selecciona los tipos de notificación que desea recibir,<br>Cuando guarda su configuración,<br>Entonces el sistema aplica dichas preferencias a las futuras notificaciones.<br><br>**Escenario 2: Intento de deshabilitar notificaciones de incidentes**<br>Dado que el contacto de confianza intenta deshabilitar las notificaciones de posibles incidentes,<br>Cuando guarda la configuración,<br>Entonces el sistema le advierte que este tipo de notificación es obligatoria y no puede deshabilitarse. | EP-09 |
| **US-30** | Revisar y aprobar reportes de la comunidad | Como moderador de la comunidad, quiero revisar los reportes de nuevos servicios e incidentes enviados por los usuarios para aprobarlos o rechazarlos antes de que sean visibles públicamente. | **Escenario 1: Reporte aprobado**<br>Dado que existe un reporte pendiente de validación,<br>Cuando el moderador lo revisa y lo aprueba,<br>Entonces el reporte pasa a estar visible para toda la comunidad.<br><br>**Escenario 2: Reporte rechazado**<br>Dado que existe un reporte pendiente de validación que no cumple con los criterios de calidad,<br>Cuando el moderador lo rechaza,<br>Entonces el reporte no se publica y se notifica al usuario que lo envió. | EP-10 |
| **US-31** | Visualizar video de demostración y equipo en la Landing Page | Como visitante del sitio web, quiero reproducir el video explicativo sobre la plataforma y el equipo para comprender mejor el funcionamiento del servicio antes de crear una cuenta. | **Escenario 1: Reproducción del video demostrativo**<br>Dado que el visitante se ubica en la sección de demostración en video de la landing page,<br>Cuando interactúa con el reproductor interactivo,<br>Entonces el contenido audiovisual se reproduce sin interrupciones y con controles de reproducción funcionales.<br><br>**Escenario 2: Falla de carga del recurso multimedia**<br>Dado que el servicio de video no se encuentra disponible o presenta fallos de red,<br>Cuando la landing page carga la sección multimedia,<br>Entonces el sistema muestra un mensaje alternativo indicando la indisponibilidad temporal del video sin romper el diseño de la página. | EP-01 |
| **US-32** | Consultar testimonios y casos de éxito en la Landing Page | Como visitante del sitio web, quiero explorar las experiencias y testimonios de otros trabajadores nocturnos para verificar la credibilidad y efectividad de la plataforma. | **Escenario 1: Navegación entre testimonios**<br>Dado que el visitante visualiza el módulo de testimonios en la landing page,<br>Cuando selecciona un caso de éxito o avanza entre las opiniones disponibles,<br>Entonces el sistema actualiza la cita mostrada con el detalle del testimonio y la ocupación del usuario correspondiente.<br><br>**Escenario 2: Visualización estática en vista móvil**<br>Dado que el visitante accede desde una pantalla de formato reducido,<br>When consulta la sección de testimonios,<br>Then los testimonios se adaptan al espacio disponible permitiendo deslizar de forma accesible entre cada historia. | EP-01 |
| **US-33** | Desplegar preguntas frecuentes (FAQ) en la Landing Page | Como visitante del sitio web, quiero expandir y colapsar preguntas frecuentes para resolver dudas clave sobre el funcionamiento, privacidad y costos de la plataforma de manera inmediata. | **Escenario 1: Despliegue interactivo de respuesta**<br>Dado que el visitante se encuentra en la sección de preguntas frecuentes con todos los ítems colapsados,<br>Cuando selecciona una pregunta específica,<br>Entonces la sección correspondiente se expande revelando la respuesta detallada y contrayendo las demás si aplica.<br><br>**Escenario 2: Colapso de respuesta activa**<br>Dado que el visitante tiene una pregunta abierta,<br>Cuando hace clic nuevamente sobre el encabezado de dicha pregunta,<br>Entonces el contenido se repliega ocultando la respuesta. | EP-01 |
| **US-34** | Enviar formulario de contacto o soporte desde la Landing Page | Como visitante del sitio web, quiero enviar mis consultas a través del formulario de contacto para recibir asistencia o información personalizada por parte del equipo. | **Escenario 1: Envío exitoso de consulta**<br>Dado que el visitante completa su nombre, correo electrónico y mensaje válido en el formulario de pie de página,<br>Cuando hace clic en el botón de envío,<br>Entonces el sistema registra la consulta, muestra un mensaje de confirmación y restablece los campos del formulario.<br><br>**Escenario 2: Validación de campos obligatorios o formato erróneo**<br>Dado que el visitante omite un campo requerido o escribe una dirección de correo con formato inválido,<br>Cuando intenta enviar el formulario,<br>Entonces el sistema bloquea el envío y resalta los campos con error solicitando su corrección. | EP-01 |
| **US-35** | Cambiar idioma y tema visual en la Landing Page | Como visitante del sitio web, quiero alternar entre los idiomas disponibles (español e inglés) y ajustar el modo de visualización para adaptar la lectura a mis preferencias. | **Escenario 1: Alternancia de idioma**<br>Dado que la landing page se muestra en el idioma predeterminado,<br>Cuando el visitante acciona el selector de idioma (ES/EN),<br>Entonces todos los textos, títulos y llamados a la acción se traducen de forma coherente y dinámica.<br><br>**Escenario 2: Conmutación de tema claro y oscuro**<br>Dado que el visitante interactúa con el interruptor de modo visual en la barra de navegación,<br>Cuando activa el cambio de tema,<br>Entonces la paleta de colores de la interfaz se adapta inmediatamente al esquema seleccionado manteniendo los contrastes y legibilidad. | EP-01 |
---

### Technical Stories:
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

#### El estilo visual de la startup

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

#### Paleta de colores

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

#### Tipografía

Se seleccionan las tipografías Poppins y Roboto debido a su buena legibilidad en dispositivos digitales y a su apariencia moderna y accesible.

- **Poppins:** títulos, encabezados y elementos destacados.
- **Roboto:** textos, descripciones, formularios, mensajes y contenido informativo.

#### Jerarquía tipográfica

| Elemento | Tipografía | Uso | Tamaño |
|---|---|---|---|
| Encabezado 1 | Poppins | Títulos principales | 28-36 px |
| Encabezado 2 | Poppins | Títulos de sección | 22-30 px |
| Encabezado 3 | Poppins | Tarjetas y subsecciones | 18-24 px |
| Texto principal | Roboto | Información principal | 14-16 px |
| Texto secundario | Roboto | Información complementaria | 12-14 px |
| Botones | Roboto | Acciones | 14-16 px |

#### Espaciado

Se define un sistema de espaciado basado en múltiplos de 8 px, con el objetivo de mantener una distribución consistente:

- **8 px:** separación mínima entre elementos relacionados.
- **16 px:** separación estándar entre componentes.
- **24 px:** separación entre secciones.
- **32 px:** separación entre bloques principales.
- **40 px o más:** separación de áreas principales de la interfaz.

Este sistema permite mantener una estructura ordenada y facilita la adaptación de la interfaz a diferentes tamaños de pantalla.

#### Tono de comunicación

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
#### 1. Diseño y estructura

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

#### 2. Sistema de grillas

Se utiliza un sistema de diseño basado en una grilla de 12 columnas para escritorio y estructuras adaptativas para dispositivos móviles.

Las principales características son:

- Espaciado basado en múltiplos de 8 px.
- Contenedores responsivos.
- Distribución consistente de tarjetas.
- Márgenes adaptables.
- Componentes reutilizables.

**Justificación:** Permite mantener una estructura visual consistente y facilita la adaptación de la plataforma a diferentes dispositivos y resoluciones.

#### 3. Componentes UI principales

##### Tarjetas

Las tarjetas se utilizan para agrupar información relacionada, por ejemplo:

- Estado del trayecto.
- Contactos de confianza.
- Servicios abiertos.
- Reportes de seguridad.
- Estado del descanso.
- Beneficios disponibles.
- Publicaciones de la comunidad.

Cada tarjeta debe mostrar información concreta y permitir identificar rápidamente su función.

##### Botones

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

##### Insignias o Badges

Las insignias permiten identificar rápidamente los estados dentro del sistema.

Algunos ejemplos son:

- **Trayecto seguro**
- **En camino**
- **Precaución**
- **Posible incidente**
- **Emergencia**
- **Trayecto finalizado**

Los colores siempre estarán acompañados por texto o iconografía para no depender únicamente del color.

##### Formularios

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

##### Notificaciones

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

##### Feedback inmediato

El sistema debe proporcionar retroalimentación inmediata después de cada acción relevante.

Ejemplos:

- "Trayecto iniciado correctamente."
- "Llegada confirmada."
- "Tu contacto de confianza ha sido notificado."
- "Reporte enviado para revisión."

**Justificación:** La retroalimentación inmediata permite reducir la incertidumbre y aumenta la confianza del usuario en el funcionamiento de la plataforma.

##### Restricciones de acciones

El sistema debe evitar acciones que puedan generar información incorrecta o poner en riesgo al usuario.

Por ejemplo:

- No se puede confirmar una llegada si no existe un trayecto activo.
- No se puede finalizar un trayecto que ya fue cerrado.
- Un reporte de emergencia requiere una confirmación para evitar activaciones accidentales.
- La información de ubicación solo se comparte durante el periodo autorizado por el usuario.
- Un posible incidente puede requerir confirmación posterior por parte del trabajador.

##### Visualización del estado

Los estados del sistema se representan mediante una combinación de:

- Colores.
- Iconos.
- Texto.
- Indicadores de progreso.
- Líneas de tiempo.

Por ejemplo, un trayecto puede visualizarse como:

**Inicio → En camino → Cerca del destino → Llegada confirmada**

Esto permite que tanto el trabajador como su contacto de confianza comprendan rápidamente el estado actual del trayecto.

#### 5. Diseño adaptable

La startup está diseñada principalmente para dispositivos móviles, debido a que los trabajadores utilizarán la plataforma durante sus desplazamientos nocturnos.

También se contempla su uso en:

- Smartphone.
- Tablet.
- Escritorio.

##### Móvil

La versión móvil prioriza:

- Acciones principales accesibles con una mano.
- Botones grandes.
- Navegación simplificada.
- Acceso rápido a emergencia.
- Mapa y ubicación.
- Estado del trayecto.
- Notificaciones.
- Lectura clara en ambientes con poca iluminación.

##### Tablet y escritorio

Se aprovecha el espacio disponible para presentar:

- Mapas de mayor tamaño.
- Historial de trayectos.
- Información de comunidad.
- Estadísticas de bienestar.
- Administración de contactos.
- Beneficios y servicios disponibles.

#### 6. Navegación

La navegación debe ser simple y consistente.

##### Móvil

Se utiliza una barra de navegación inferior para acceder a las funciones principales:

**Inicio | Trayecto | Mapa | Comunidad | Perfil**

Las funciones de emergencia y seguridad deben permanecer fácilmente accesibles.

##### Escritorio

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

#### 7. Iconografía

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

#### 8. Componentes específicos de la solución

Debido a que la plataforma está orientada específicamente a trabajadores nocturnos, se establecen algunos componentes propios del sistema.

##### Registro de trayecto seguro

Permite iniciar un trayecto, seleccionar un destino y compartir el estado con los contactos de confianza.

##### Contactos de confianza

Permite registrar familiares, parejas o amigos que recibirán notificaciones relacionadas con el trayecto.

##### Mapa nocturno

Permite visualizar:

- Servicios abiertos durante la noche.
- Zonas reportadas como inseguras.
- Incidentes registrados.
- Información proporcionada por la comunidad.

##### Reporte de incidentes

Permite registrar situaciones como:

- Robo.
- Acoso.
- Zona peligrosa.
- Mala iluminación.
- Accidente.
- Situación sospechosa.

##### Registro de bienestar

Permite registrar información relacionada con:

- Horas de sueño.
- Descanso.
- Fatiga.
- Hábitos relacionados con el turno nocturno.

##### Comunidad

Permite a los trabajadores compartir información, experiencias y recomendaciones relacionadas con el trabajo nocturno.

##### Beneficios

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

#### Principios clave del sistema de etiquetado:

Las etiquetas evitarán tecnicismos innecesarios y ambigüedades. Se emplearán términos comunes que puedan ser comprendidos rápidamente por trabajadores, familiares y otros usuarios de la plataforma.

Un mismo concepto siempre se representará con la misma palabra en todos los entornos de la plataforma, incluyendo la aplicación móvil, aplicación web, notificaciones y comunicaciones.

Las etiquetas se limitarán preferentemente a 1-3 palabras, procurando que sean descriptivas, directas y fáciles de identificar.

Las etiquetas relacionadas con situaciones de seguridad tendrán un mayor peso visual y utilizarán colores e iconos de acuerdo con las directrices establecidas en la guía de estilo.

#### Etiquetas principales por área

**Navegación global:** Inicio, Trayecto, Mapa, Comunidad, Bienestar, Beneficios, Perfil.

**Página de inicio:** Mi estado, Mi trayecto, Alertas, Servicios cercanos, Actividad reciente.

**Seguridad y trayectos:** Iniciar trayecto, Finalizar trayecto, Confirmar llegada, Contactos de confianza, Compartir trayecto, Historial.

**Mapa nocturno:** Servicios abiertos, Zonas de riesgo, Incidentes, Rutas, Cerca de mí.

**Comunidad:** Publicaciones, Reportes, Recomendaciones, Experiencias, Comentarios.

**Bienestar:** Descanso, Sueño, Registro, Historial, Recomendaciones.

**Beneficios:** Beneficios disponibles, Descuentos, Seguro, Suscripción.

**Acciones del usuario:** Crear cuenta, Iniciar sesión, Iniciar trayecto, Confirmar llegada, Reportar incidente, Compartir ubicación, Añadir contacto, Registrar descanso, Ver beneficio, Cerrar sesión.

#### Asociaciones entre etiquetas

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
#### Página de inicio

**Título:** Seguridad y bienestar para trabajadores nocturnos.

**Meta Descripción:** Plataforma digital para trabajadores nocturnos que ofrece seguimiento de trayectos, contactos de confianza, información sobre servicios abiertos, reportes comunitarios y herramientas de bienestar.

**Meta Palabras clave:** trabajadores nocturnos, seguridad nocturna, bienestar laboral, seguridad personal, trayecto seguro, servicios nocturnos, comunidad nocturna, Lima.

**Autor de la metaetiqueta:** [Noctiva]

#### Aplicación web

**Título:** Seguridad y bienestar durante tu jornada nocturna.

**Meta Descripción:** Gestiona tus trayectos nocturnos, comparte tu estado con contactos de confianza, consulta zonas de riesgo y encuentra servicios disponibles durante la noche desde una sola plataforma.

**Meta Palabras clave:** seguridad para trabajadores nocturnos, seguimiento de trayectos, contactos de confianza, mapa nocturno, zonas de riesgo, servicios abiertos, bienestar nocturno.

**Autor de la metaetiqueta:** [Noctiva]

### 4.2.4. Searching Systems.
Las decisiones de búsqueda en Noxway están orientadas a garantizar que los usuarios encuentren rápidamente información relevante sobre servicios nocturnos, zonas de riesgo, rutas, reportes comunitarios y beneficios, evitando que tengan que revisar grandes cantidades de información.

#### Opciones de búsqueda

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

#### Filtros disponibles

**Por tipo de servicio:** Restaurantes, farmacias, tiendas, centros de salud, transporte y otros servicios disponibles durante la noche.

**Por distancia:** Cerca de mí, menos de 1 km, menos de 3 km, menos de 5 km.

**Por horario:** Abierto ahora, abierto toda la noche, apertura próxima.

**Por seguridad:** Ruta recomendada, zona segura, zona de precaución, zona de riesgo.

**Por valoración:** Mejor valorados, más recientes y más reportados.

**Por fecha:** Reportes recientes, últimos 7 días y últimos 30 días.

#### Apariencia de los datos después de la búsqueda

**Listados de resultados:** Incluyen nombre del lugar o reporte, ubicación, distancia, horario de atención y valoración cuando corresponda.

**Resumen y descripción:** Cada resultado presenta información relevante, como descripción del servicio, reportes recientes, nivel de seguridad o comentarios de la comunidad.

**Ordenación y filtros aplicados:** El usuario podrá ordenar los resultados por cercanía, relevancia, valoración o fecha. Los filtros activos se mostrarán claramente en la parte superior de los resultados.

**Información comunitaria:** Los resultados relacionados con seguridad podrán incluir reportes y valoraciones realizadas por otros trabajadores nocturnos, permitiendo conocer experiencias recientes de la zona.

**Ubicación:** Los resultados podrán visualizarse tanto en formato de lista como en el mapa, facilitando la identificación de servicios y zonas relevantes cercanas al usuario.

### 4.2.5. Navigation Systems.
La estructura de navegación de la startup está diseñada para ofrecer una experiencia de usuario fluida y sencilla, asegurando un acceso rápido a las funcionalidades relacionadas con seguridad, trayectos, comunidad y bienestar.

La navegación prioriza especialmente las funciones que pueden ser utilizadas durante un desplazamiento nocturno, reduciendo la cantidad de pasos necesarios para acceder a información importante.

#### Páginas principales

**Inicio:** Dashboard principal con el estado del usuario, trayecto activo, alertas importantes, servicios cercanos y accesos rápidos.

**Mi trayecto:** Permite iniciar, consultar y finalizar trayectos, además de gestionar la información compartida con los contactos de confianza.

**Mapa:** Permite visualizar servicios abiertos durante la noche, zonas de riesgo, incidentes reportados y otros puntos relevantes.

**Comunidad:** Espacio donde los trabajadores pueden consultar y compartir experiencias, reportes, recomendaciones e información relacionada con el trabajo nocturno.

**Bienestar:** Sección destinada al registro de descanso, sueño y otros indicadores relacionados con el bienestar del trabajador nocturno.

**Beneficios:** Permite consultar descuentos, servicios y beneficios disponibles para los usuarios suscritos.

**Perfil:** Permite administrar información personal, contactos de confianza, preferencias, privacidad y configuración de la cuenta.

#### Opciones de usuario

**Iniciar sesión:** Acceso para usuarios registrados.

**Registrarme:** Registro de nuevos trabajadores y contactos de confianza.

**Perfil:** Configuración y gestión de información personal.

**Contactos de confianza:** Administración de familiares, parejas o amigos autorizados para recibir información sobre los trayectos.

**Configuración:** Gestión de preferencias, privacidad, notificaciones y permisos de ubicación.

**Cerrar sesión:** Salida segura de la cuenta.

#### Búsqueda y navegación

**Barra de búsqueda:** Disponible en las secciones donde sea necesario localizar servicios, lugares, reportes o beneficios.

**Categorías:** Permiten filtrar rápidamente la información por tipo de servicio, incidente o contenido.

**Explorar:** Facilita el acceso a módulos principales como Mapa, Comunidad, Bienestar y Beneficios.

**Mapa:** Permite navegar visualmente por la ubicación del usuario y consultar información relevante del entorno nocturno.

#### Navegación de seguridad

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

#### Marca e identidad

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
<img src="resources/imgs/Identity & Network Management.png"
     alt="eventstorming"
     style="">
<br>
<br>
**Safe Commute Execution**
<br>
<br>
<img src="resources/imgs/safees.png"
     alt="eventstorming"
     style="">
<br>
<br>
**Incident & Alert Management**
<br>
<br>
<img src="resources/imgs/incident.png"
     alt="eventstorming"
     style="">
<br>
<br>
**Community Intelligence**
<br>
<br>
<img src="resources/imgs/comuni.png"
     alt="eventstorming"
     style="">
<br>
<br>
**Sleep Health & Wellness**
<br>
<br>
<img src="resources/imgs/sleep.png"
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
<img src="resources/imgs/governance.png"
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

### Landing Page Components

La Landing Page se descompone en Hero & Protocol Section, Ecosystem & Features, Subscription Plans View y Registration Funnel. Estas secciones exponen visualmente el flujo de cuatro pasos (Vincular, Iniciar, Monitorear, Confirmar) y las capacidades tecnológicas del sistema. El Registration Funnel permite captar datos iniciales y redirigir a los visitantes hacia la experiencia correspondiente (Worker o Contact) en la Web Application, comunicándose directamente con el RESTful API.

C4 Component Diagram - Landing Page.

<img src="resources/imgs/landingdiagram.png"
     alt="componentdiagram"
     style="">

### Web Application Components

La Web Application separa el Auth & Onboarding Module, Worker Portal, Companion Portal, Active Commute Tracker, 24h Community Map, Sleep & Wellness Log y Benefits & Subscriptions. Todas estas experiencias utilizan llamadas centralizadas y comparten componentes interactivos, manteniendo una única vía de comunicación con el RESTful API para garantizar la sincronización en tiempo real del estado de los trayectos.

C4 Component Diagram - Web Application.

<img src="resources/imgs/web.png"
     alt="componentdiagram"
     style="">

### RESTful API Components

El RESTful API organiza sus componentes principales de acuerdo con los Bounded Contexts identificados en el Design-Level EventStorming: Account & Auth Controller, Trust Network Controller, Commute & Check-In Controller, Incident & Alert Manager, Community Map Service, Sleep Wellness Service, Subscription Controller y Moderation Controller.

Account & Auth Controller y Trust Network API concentran el registro, autenticación y gestión de vínculos. Commute Controller y el Incident Manager en segundo plano gestionan la telemetría, evaluación de tolerancia y disparo de alertas. Community Map Service procesa consultas espaciales de locales y zonas de riesgo. Sleep Wellness Service administra los registros de descanso diurno y sugerencias de fatiga. Subscription Controller gestiona planes, pagos y convenios colectivos.

Persistence Layer concentra el acceso hacia PostgreSQL y External Integrations encapsula la comunicación con Payment Gateway, Email Service, SMS/Push Service y Map APIs.

C4 Component Diagram - RESTful API.

<img src="resources/imgs/api.png"
     alt="componentdiagram"
     style="">

### Relational Database Components

El container Relational Database se organiza mediante separación lógica de datos. Los esquemas `users_network_schema`, `commute_incident_schema`, `community_data_schema`, `wellness_schema`, `subscription_schema` y `moderation_schema` corresponden a los Bounded Contexts identificados. 

Esta organización permite conservar límites de responsabilidad a nivel de persistencia, separando datos transaccionales críticos (como la telemetría) de datos espaciales y de facturación, aun cuando PostgreSQL sea desplegado inicialmente como una única instancia.

C4 Component Diagram - Relational Database.

<img src="resources/imgs/database.png"
     alt="componentdiagram"
     style="">

## 4.7. Software Object-Oriented Design

El diseño orientado a objetos se organiza de acuerdo con los Bounded Contexts identificados en el Design-Level EventStorming y con los módulos de soporte necesarios para mantener trazabilidad con las User Stories del Capítulo III. Los nombres de clases, atributos, métodos e interfaces se mantienen en inglés y se especifican relaciones, multiplicidades y visibilidad de miembros.

## 4.7.1. Class Diagrams

### Identity & Network Management

El modelo concentra la abstracción `User`, de la cual heredan los roles específicos `NightWorker` y `TrustedContact`. `TrustLink` modela la clase de asociación que representa el vínculo de acompañamiento seguro entre un trabajador y su contacto de confianza, encapsulando su estado y vigencia.

Class Diagram - Identity & Network Management.

<img src="resources/imgs/identity&networkmanagement.png"
     style="">

### Safe Commute & Incident Management

`Commute` representa el núcleo del ciclo de vida del trayecto y se relaciona fuertemente con `TelemetryPing` mediante composición para registrar la ubicación y velocidad. `SafetyIncident` modela las situaciones de riesgo o demoras generadas durante el trayecto, interactuando con `NotificationPreference` para escalar las alertas a los canales correspondientes.

Class Diagram - Safe Commute Incident Management.

<img src="resources/imgs/safecommute.png"
     style="">

### Community Intelligence

`CommunityMap` actúa como la entidad agregadora para la consulta espacial. `NightServicePoint` representa los servicios verificados que operan en la madrugada y `RiskZone` modela los puntos de peligro reportados. `RouteRating` registra la calificación de seguridad asignada a las rutas una vez finalizado el desplazamiento.

Class Diagram - Community Intelligence.

<img src="resources/imgs/community intelligence.png"
     style="">

### Sleep Health & Wellness

`SleepLog` representa el registro agregado diario de metas y déficits de sueño, mientras que `RestSession` registra periodos individuales de descanso fragmentado. `HygieneSuggestion` modela las recomendaciones emitidas por el sistema en función del nivel de fatiga detectado en el trabajador nocturno.

Class Diagram - Sleep Health Wellness.

<img src="resources/imgs/sleephealth.png"
     style="">

### Subscriptions & Collective Benefits

`Subscription` representa el plan (Esencial, Centinela Pro, etc.) activo de un trabajador, el cual genera registros en `PaymentTransaction` por su facturación recurrente. `CollectiveBenefit` modela los seguros y convenios habilitados, mientras que `ReferralCode` administra la lógica del programa de crecimiento por referidos.

Class Diagram - Subscriptions Collective Benefits.

<img src="resources/imgs/subscriptions.png"
     style="">

### Moderation & Governance

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

#### Identity & Network Management

El modelo persiste las cuentas en `users` y su información demográfica en `user_profiles`. El control de acceso se maneja a través de `roles` y `user_roles`. Los dispositivos móviles se registran en `user_devices` para posibilitar el envío de notificaciones push. La creación de la red de acompañamiento utiliza `trust_invitations` para gestionar los tokens enviados externamente y `trust_links` para consolidar el vínculo aceptado.

Database Diagram - Identity & Network Management.

<img src="resources/imgs/iden.png"
     style="">

#### Safe Commute & Incident Management

El modelo persiste los trayectos en la tabla `commutes`, complementada por `commute_checkpoints` para trazar los hitos de la ruta. La telemetría de alto volumen se aísla en `telemetry_pings`. Las anomalías generan registros en `safety_incidents`, los cuales mantienen su ciclo de vida y disparan registros de auditoría de notificaciones en `incident_alerts`.

Database Diagram - Safe Commute Incident Management.

<img src="resources/imgs/comu.png"
     style="">

#### Community Intelligence

El modelo persiste ubicaciones geoespaciales como `night_services` y `risk_zones`. Para garantizar la confiabilidad comunitaria, se emplean las tablas transaccionales `service_validations` y `risk_zone_confirmations`, que evitan votos duplicados por parte del mismo trabajador. Las encuestas de los desplazamientos se almacenan en `route_ratings`.

Database Diagram - Community Intelligence.

<img src="resources/imgs/commu.png"
     style="">

#### Sleep Health & Wellness

El modelo organiza la higiene del sueño separando el consolidado diario (`daily_sleep_logs`) de los periodos de descanso fraccionado (`sleep_sessions`). El sistema almacena en `hygiene_suggestions` las alertas emitidas por déficit de horas, las cuales se vinculan lógicamente al usuario que las recibe.

Database Diagram - Sleep Health Wellness.

<img src="resources/imgs/health.png"
     style="">

#### Subscriptions & Collective Benefits

El modelo persiste el catálogo de servicios en `subscription_plans`. La tabla `subscriptions` mantiene el estado de membresía del usuario, apoyándose en `payment_transactions` para el historial de facturación. Los convenios de seguros y descuentos se guardan en `collective_benefits`. El esquema de fidelización emplea `referral_codes` y audita sus canjes mediante `referral_usages`.

Database Diagram - Subscriptions Payment Management.

<img src="resources/imgs/sub.png"
     style="">

#### Moderation & Governance

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

### 5.1.3. Source Code Style Guide & Conventions. 

### 5.1.4. Software Deployment Configuration. 

## 5.2. Landing Page, Services & Applications Implementation. 

### 5.2.1. Sprint 1

#### 5.2.1.1. Sprint Planning 1. 

#### 5.2.1.2. Aspect Leaders and Collaborators. 

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

[NoxWay Sprint Backlog](https://trello.com/invite/b/690c87e2eddd3d52ed83189d/ATTI96b986ca465d37e1b647b2fb1690fee5DC6EC0DE/noxway)

#### 5.2.1.4. Development Evidence for Sprint Review. 

#### 5.2.1.5. Execution Evidence for Sprint Review. 

#### 5.2.1.6. Services Documentation Evidence for Sprint Review. 

#### 5.2.1.7. Software Deployment Evidence for Sprint Review. 

#### 5.2.1.8. Team Collaboration Insights during Sprint. 


# Conclusiones 

# Bibliografía 

# Anexos