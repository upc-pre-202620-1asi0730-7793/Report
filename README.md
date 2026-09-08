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