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

### 1.1.1. Descripción de la Startup 

### 1.1.2. Perfiles de integrantes del equipo 

## 1.2. Solution Profile 

### 1.2.1 Antecedentes y problemática 

### 1.2.2 Lean UX Process. 

#### 1.2.2.1. Lean UX Problem Statements. 

#### 1.2.2.2. Lean UX Assumptions. 

#### 1.2.2.3. Lean UX Hypothesis Statements. 

#### 1.2.2.4. Lean UX Canvas. 

## 1.3. Segmentos objetivo. 



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

La navegación mantendrá una estructura consistente en todas las vistas para que los usuarios puedan identificar rápidamente dónde se encuentran y cómo regresar a las funciones principales.
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