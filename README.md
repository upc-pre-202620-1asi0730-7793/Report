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
    <td> (producto) <br> <img src="resources/imgs/producto-logo.png"></img> </td>
    <td> bSafe <br> <img src="resources/imgs/bsafe-logo.png"></img> </td>
    <td> Noonlight <br> <img src="resources/imgs/noonlight-logo.png"></img> </td>
    <td> Safetipin <br> <img src="resources/imgs/safetipin-logo.png"></img> </td>
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