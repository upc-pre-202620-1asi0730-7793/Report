<div align="center" style="margin-top: -5px;">

<img src="resources/imgs/UPC_logo_transparente.png"
     alt="UPC_logo_transparente"
     style="width: 18%; height: auto; margin-bottom: -40px;">
  
## Universidad Peruana de Ciencias Aplicadas

**Facultad:** Ingeniería

**Carrera:** Ingeniería de Software

**Periodo:** 2026-20

**Código del Curso**: 1ASI0730

**Curso:** Desarrollo de Aplicaciones Open Source

**NRC:** 8093

**Profesor:** Ivan Robles Fernández

### Informe de Trabajo Final

**Startup:** Nombre

**Nombre del producto:** Nombre


#### Relación de integrantes

| Integrante                       | Código     |
|----------------------------------|------------|
| Patricio Farias, Ana Camila      | U20241I469 |
| Cano Gomez, Yam Antony           | U202423775 |
| Dextre Flores, Leonardo Felix    | U202421823 |
| Ramirez Rodriguez, Mauricio Joao | U202218235 |  
| Salcedo Correa, Carlos Matthew   | U202421065 |

<div align="center"><h3>Setiembre 2026</h3></div><br>

</div>

---
# Registro de Versiones del Informe 

|Versión|Fecha|Autor|Fecha de modificación|
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
| **Descripción** |                            |
| **Foto** |                            |
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
| :--- |:---------------------------------|
| **Código del Estudiante** | U202218235                       |
| **Carrera** | Ingeniería de Software           |
| **Descripción** |                                  |
| **Foto** |                                  |
---------------------

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
Lean UX Canvas — SkyCrop
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

### 2.1.1. Análisis competitivo. 

### 2.1.2. Estrategias y tácticas frente a competidores. 

## 2.2. Entrevistas. 

### 2.2.1. Diseño de entrevistas. 

### 2.2.2. Registro de entrevistas. 

### 2.2.3. Análisis de entrevistas. 

## 2.3. Needfinding. 

### 2.3.1. User Personas. 

### 2.3.2. User Task Matrix. 

### 2.3.3. User Journey Mapping. 

### 2.3.4. Empathy Mapping. 

## 2.4. Big Picture EventStorming. 

## 2.5. Ubiquitous Language. 



# Capítulo III: Requirements Specification 

## 3.1. User Stories. 

|Epic / Story ID|Título|Descripción|Criterios de aceptación|Relacionado con|
|:--------------|:-----|:----------|:----------------------|:--------------|
||||||

## 3.2. Impact Mapping. 


## 3.3. Product Backlog. 

|# Orden|User Story ID|Título|Descripción|Story Points|
|:--------------|:-----|:----------|:----------------------|:--------------|
||||||

# Capítulo IV: Product Design 

## 4.1. Style Guidelines. 

### 4.1.1. General Style Guidelines. 

### 4.1.2. Web Style Guidelines. 

## 4.2. Information Architecture. 

### 4.2.1. Organization Systems. 

### 4.2.2. Labeling Systems. 

### 4.2.3. SEO Tags and Meta Tags 

### 4.2.4. Searching Systems. 

### 4.2.5. Navigation Systems. 

## 4.3. Landing Page UI Design. 

### 4.3.1. Landing Page Wireframe. 

### 4.3.2. Landing Page Mock-up. 

## 4.4. Web Applications UX/UI Design. 

### 4.4.1. Web Applications Wireframes. 

### 4.4.2. Web Applications Wireflow Diagrams. 

### 4.4.2. Web Applications Mock-ups. 

### 4.4.3. Web Applications User Flow Diagrams. 

## 4.5. Web Applications Prototyping. 

## 4.6. Domain-Driven Software Architecture. 

### 4.6.1. Design-Level EventStorming. 

### 4.6.2. Software Architecture Context Diagram. 

### 4.6.3. Software Architecture Container Diagrams. 

### 4.6.4. Software Architecture Components Diagrams. 

## 4.7. Software Object-Oriented Design. 

### 4.7.1. Class Diagrams. 

## 4.8. Database Design. 

### 4.8.1. Database Diagrams. 


# Capítulo V: Product Implementation, Validation & Deployment  


## 5.1. Software Configuration Management. 

### 5.1.1. Software Development Environment Configuration. 

### 5.1.2. Source Code Management. 

### 5.1.3. Source Code Style Guide & Conventions. 

### 5.1.4. Software Deployment Configuration. 

## 5.2. Landing Page, Services & Applications Implementation. 

### 5.2.X. Sprint n 

#### 5.2.X.1. Sprint Planning n. 

#### 5.2.X.2. Aspect Leaders and Collaborators. 

#### 5.2.X.3. Sprint Backlog n. 

#### 5.2.X.4. Development Evidence for Sprint Review. 

#### 5.2.X.5. Execution Evidence for Sprint Review. 

#### 5.2.X.6. Services Documentation Evidence for Sprint Review. 

#### 5.2.X.7. Software Deployment Evidence for Sprint Review. 

#### 5.2.X.8. Team Collaboration Insights during Sprint. 


# Conclusiones 

# Bibliografía 

# Anexos