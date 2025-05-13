# <center>COURSE PROJECT</center>

<p align="center">
    <strong>Universidad Peruana de Ciencias Aplicadas</strong><br>
    <img src="https://upload.wikimedia.org/wikipedia/commons/f/fc/UPC_logo_transparente.png"></img><br>
    <strong>Ingeniería de Software</strong><br>
    <strong>Aplicaciones Web - 4395</strong><br>
    <strong>Profesor: Angel Augusto Velasquez Nuñez </strong><br>
    <br>INFORME TRABAJO FINAL
</p>

<center>

#### Startup: **SoftCore**
#### Product: **CustomHost**

</center>

### <center>Team  Members:</center>
<center>

| Member                           | Code       |
|----------------------------------|------------|
| Ordoñez Ricaldi, Axel Randall    | U202216827 |
| Panta Castro, Fabrizio Martin    | U20231A810 |
| Ccarita Cruz, Brayan Roberto     | U20221C218 |
| Arrieta Quispe, Alison Jimena    | U202312031 |
| Santiago Peña, Andreow Jomark    | U202317362 |

<br> ABRIL 2025
</center>  

# Registro de Versiones del Informe
<center>

| Version | Fecha | Autor | Descripcion de Modificacion |
| ----------- | ----------- | ----------- | ----------- |
| TB1 | 23/04/2025 | Axel Randall Ordoñez Ricaldi | - Product baclog<br> - Imapct Mapping<br> - Domain Driver Software Architecture |  
| TB1 | 23/04/2025 | Fabrizio Martin Panta Castro | - To-be Scenario Mapping<br> - User Stories<br> - Style Guidelines<br> - Information Architecture |  
| TB1 | 23/04/2025 | Brayan Roberto Ccarita Cruz | - Startup Profile<br> - Solution Profile<br> - Segmentos objetivos<br> - Software Object-Priented Design |  
| TB1 | 23/04/2025 | Alison Jimena Arrieta Quispe | - Competidores<br> - Entrevistas<br> - Landing Page UI Design<br> -  Landing Page|  
| TB1 | 23/04/2025 | Andreow Jomark Santiago Peña | - Needfinding<br> - Ubiquitous Language<br> - Web Application UX/UI Design |

</center>

# Project Report Collaboration Insights
URL del repositorio: https://github.com/SoftCore-App-Web-1ASI0730-2510-4395/CustomHost

(Imagenes de los commits cada entrega)


# Contenido



[Registro de Versiones del Informe](#registro-de-versiones-del-informe)

[Project Report Collaboration Insights](#project-report-collaboration-insights)

[Student Outcome](#student-outcome)

[Capítulo I: Introducción](#capítulo-i-introducción)

[1.1 Startup Profile](#11-startup-profile)  
[1.1.1. Descripción de la Startup](#111-descripción-de-la-startup)  
[1.1.2. Perfiles de integrantes del equipo](#112-perfiles-de-integrantes-del-equipo)  

[1.2. Solution Profile](#12-solution-profile)  
[1.2.1 Antecedentes y problemática](#121-antecedentes-y-problemática)  
[1.2.2 Lean UX Process.](#122-lean-ux-process)  
[1.2.2.1. Lean UX Problem Statements.](#1221-lean-ux-problem-statements)  
[1.2.2.2. Lean UX Assumptions.](#1222-lean-ux-assumptions)  
[1.2.2.3. Lean UX Hypothesis Statements.](#1223-lean-ux-hypothesis-statements)  
[1.2.2.4. Lean UX Canvas.](#1224-lean-ux-canvas)  

[1.3. Segmentos objetivo.](#13-segmentos-objetivo)  

[Capítulo II: Requirements Elicitation & Analysi](#capítulo-ii-requirements-elicitation--analysis)  

[2.1. Competidores](#21-competidores)  
[2.1.1. Análisis competitivo](#211-análisis-competitivo)  
[2.1.2. Estrategias y tácticas frente a competidores](#211-análisis-competitivo)  

[2.2. Entrevistas](#22-entrevistas)  
[2.2.1. Diseño de entrevistas](#221-diseño-de-entrevistas)  
[2.2.2. Registro de entrevistas](#222-registro-de-entrevistas)  
[2.2.3. Análisis de entrevistas](#223-análisis-de-entrevistas)  

[2.3. Needfinding](#23-needfinding)  
[2.3.1. User Personas](#231-user-personas)  
[2.3.2. User Task Matrix](#232-user-task-matrix)  
[2.3.3. User Journey Mapping](#233-user-journey-mapping)  
[2.3.4. Empathy Mapping](#234-empathy-mapping)  
[2.3.5. As-is Scenario Mapping](#235-as-is-scenario-mapping) 

[2.4. Ubiquitous Language](#24-ubiquitous-language)  

[Capítulo III: Requirements Specificatio](#capítulo-iii-requirements-specification)  

[3.1. To-Be Scenario Mapping](#31-to-be-scenario-mapping)    
[3.2. User Stories](#32-user-stories)  
[3.3. Impact Mapping](#33-impact-mapping)  
[3.4. Product Backlog](#34-product-backlog)  

[Capítulo IV: Product Desig](#capítulo-iv-product-design)  

[4.1. Style Guidelines](#41-style-guidelines)  
[4.1.1. General Style Guidelines](#411-general-style-guidelines)  
[4.1.2. Web Style Guidelines](#412-web-style-guidelines)  

[4.2. Information Architecture](#42-information-architecture)  
[4.2.1. Organization Systems](#421-organization-systems)  
[4.2.2. Labeling Systems](#422-labeling-systems)  
[4.2.3. SEO Tags and Meta Tag](#423-seo-tags-and-meta-tags)  
[4.2.4. Searching Systems](#424-searching-systems)   
[4.2.5. Navigation Systems](#425-navigation-systems)  

[4.3. Landing Page UI Design](#43-landing-page-ui-design)   
[4.3.1. Landing Page Wireframe](#431-landing-page-wireframe)  
[4.3.2. Landing Page Mock-up](#432-landing-page-mock-up) 

[4.4. Web Applications UX/UI Design](#44-web-applications-uxui-design)  
[4.4.1. Web Applications Wireframes](#441-web-applications-wireframes)  
[4.4.2. Web Applications Wireflow Diagrams](#442-web-applications-wireflow-diagrams)  
[4.4.2. Web Applications Mock-ups](#442-web-applications-mock-ups)   
[4.4.3. Web Applications User Flow Diagrams](#443-web-applications-user-flow-diagrams)  

[4.5. Web Applications Prototyping](#45-web-applications-prototyping)  

[4.6. Domain-Driven Software Architecture](#46-domain-driven-software-architecture)  
[4.6.1. Software Architecture Context Diagram](#461-software-architecture-context-diagram)  
[4.6.2. Software Architecture Container Diagrams](#462-software-architecture-container-diagrams)  
[4.6.3. Software Architecture Components Diagrams](#463-software-architecture-components-diagrams)  

[4.7. Software Object-Oriented Design](#47-software-object-oriented-design)  
[4.7.1. Class Diagrams](#471-class-diagrams)  
[4.7.2. Class Dictionary](#472-class-dictionary)  

[4.8. Database Design](#48-database-design)  
[4.8.1. Database Diagram](#481-database-diagram)  

[Capítulo V: Product Implementation, Validation & Deploymen](#capítulo-v-product-implementation-validation--deployment)  

[5.1. Software Configuration Management](#51-software-configuration-management)  
[5.1.1. Software Development Environment Configuration](#511-software-development-environment-configuration)  
[5.1.2. Source Code Management](#512-source-code-management)  
[5.1.3. Source Code Style Guide & Conventions](#513-source-code-style-guide--conventions)  
[5.1.4. Software Deployment Configuration](#514-software-deployment-configuration)  

[5.2. Landing Page, Services & Applications Implementation](#52-landing-page-services--applications-implementation)  
[5.2.X. Sprint ](#52x-sprint-n)  
[5.2.X.1. Sprint Planning n](#52x1-sprint-planning-n)  
[5.2.X.2. Sprint Backlog n](#52x2-sprint-backlog-n)  
[5.2.X.3. Development Evidence for Sprint Review](#52x3-development-evidence-for-sprint-review)  
[5.2.X.4. Testing Suite Evidence for Sprint Review](#52x4-testing-suite-evidence-for-sprint-review)  
[5.2.X.5. Execution Evidence for Sprint Review](#52x5-execution-evidence-for-sprint-review)  
[5.2.X.6. Services Documentation Evidence for Sprint Review](#52x6-services-documentation-evidence-for-sprint-review)  
[5.2.X.7. Software Deployment Evidence for Sprint Review](#52x7-software-deployment-evidence-for-sprint-review)  
[5.2.X.8. Team Collaboration Insights during Sprint](#52x8-team-collaboration-insights-during-sprint)  

[5.3. Validation Interviews](#53-validation-interviews)  
[5.3.1. Diseño de Entrevistas](#531-diseño-de-entrevistas)  
[5.3.2. Registro de Entrevistas](#532-registro-de-entrevistas)  
[5.3.3. Evaluaciones según heurísticas](#533-evaluaciones-según-heurísticas)  

[5.4. Video About-the-Product](#54-video-about-the-product)  

[Conclusiones](#conclusiones)  
[Conclusiones y recomendaciones](#conclusiones-y-recomendaciones)  
[Video About-the-Team](#video-about-the-team)  
[Bibliografía](#bibliografía)  
[Anexos](#anexos)  

# Student Outcome
|Criterio Especifico|Acciones Realizadas|Conclusiones|
|-|-|-|
|Participa en equipos multidisciplinarios con eficacia, eficiencia y objetividad, en el marco de un proyecto en soluciones de ingeniería de software.|- Axel Ordoñez: <br> **TB1:** Durante el TB1, participé de manera activa en las reuniones del equipo y en el cumplimiento de los objetivos propuestos, asegurando eficiencia y eficacia en cada etapa para mejorar la calidad de la solución desarrollada. Además, asumí la responsabilidad de elaborar el Product Backlog, el Impact Mapping y la arquitectura basada en el dominio (Domain-Driven Software Architecture). <br><br> - Fabrizio Panta: <br> **TB1:** En este entregable, tomé parte activa en las reuniones y cumplí puntualmente con las tareas asignadas. Mis contribuciones incluyeron la elaboración del To-be Scenario Mapping, las User Stories, las Style Guidelines y la Information Architecture. <br><br> - Bryan Ccarita: <br> **TB1:** Mi participación en el TB1 se centró en el desarrollo del Startup Profile, el Solution Profile, la identificación de segmentos objetivo y el diseño orientado a objetos del software (Software Object-Oriented Design). <br><br> - Alison Arrieta: <br> **TB1:** Contribuí en diversos artefactos y requisitos del proyecto, como el análisis de competidores, la realización de entrevistas, el diseño de la interfaz de la Landing Page y su respectiva implementación. <br><br> - Andreow Santiago: <br> **TB1:** Aporté activamente en la construcción de artefactos esenciales para el proyecto, tales como la actividad de Needfinding, el desarrollo del Lenguaje Ubicuo (Ubiquitous Language) y el diseño de la experiencia e interfaz de usuario de la aplicación web (Web Application UX/UI Design). |Todos los integrantes demostraron una participación activa y comprometida dentro del equipo multidisciplinario, cumpliendo con eficacia y eficiencia las tareas asignadas. Se evidenció una adecuada distribución de responsabilidades, así como la capacidad de trabajar de manera colaborativa en diversos artefactos fundamentales del proyecto. Esta sinergia permitió avanzar con objetividad hacia los objetivos planteados, consolidando habilidades clave en el trabajo en equipo y la gestión de proyectos de software.|
|Conoce al menos un sector empresarial o dominio de aplicación de soluciones de software.|- Axel Ordoñez: <br> **TB1:** En este entregable, profundicé mis conocimientos en el uso de herramientas como GitHub y exploré más a fondo el sector hotelero, ampliando así mi comprensión del dominio de aplicación. <br><br> - Fabrizio Panta: <br> **TB1:** En este entregable, profundicé mis conocimientos en el uso de herramientas como GitHub y exploré más a fondo el sector hotelero, ampliando así mi comprensión del dominio de aplicación. <br><br> - Bryan Ccarita: <br> **TB1:** Aporté al equipo compartiendo mis conocimientos sobre los requisitos del proyecto, basados en distintos sectores empresariales y su relación con soluciones de software. <br><br> - Alison Arrieta: <br> **TB1:** En este entregable, he aportado mis ideas sobre sectores empresariales y los conocimientos que poseo en ciertos temas. Como resultado, hemos intercambiado saberes que enriquecen el desarrollo del proyecto. <br><br> - Andreow Santiago: <br> **TB1:** Colaboré compartiendo conocimientos relacionados con los requisitos del software y el uso de herramientas, apoyando así el análisis de diferentes dominios de aplicación. |El equipo evidenció un conocimiento progresivo y aplicado sobre diferentes sectores empresariales y dominios de aplicación de software. A través del intercambio de ideas, el análisis de casos y la exploración de herramientas específicas, se fortaleció la comprensión del contexto en el que se desarrollan las soluciones tecnológicas. Este criterio fue cumplido al vincular de forma efectiva el conocimiento técnico con las necesidades reales de distintos sectores, lo cual enriquece la propuesta del proyecto.|
# Capítulo I: Introducción
## 1.1. Startup Profile
### 1.1.1. Descripción de la Startup

SoftCore es una prometedora startup conformada por estudiantes de la Universidad Peruana de Ciencia Aplicadas (UPC) en Lima, Perú, unidos por la visión de transformar la experiencia hotelera a través de la tecnología. Este equipo combina su conocimiento en desarrollo de software, diseño de interfaces y gran interes en la industria hotelera para crear una innovadora aplicación de gestión. Su objetivo principal es empoderar a los huéspedes, permitiéndoles personalizar su estadía y convertir cada habitación en un espacio inteligente y adaptado a sus preferencias individuales.

La propuesta de SoftCore se centra en la integración de tecnologías emergentes como el Internet de las Cosas (IoT), la biometría y la domótica. A través de su aplicación, los usuarios podrán definir sus preferencias antes o durante su llegada al hotel, lo que se traducirá en un entorno de habitación que responda automáticamente a sus necesidades. Esta solución no solo busca mejorar la comodidad y satisfacción del huésped, sino también proporcionar al personal administrativo herramientas eficientes para gestionar estas preferencias y optimizar las operaciones del hotel.

Con un enfoque inicial en el mercado hotelero de Lima, SoftCore aspira a convertirse en un referente de la innovación en el sector. La mentalidad disruptiva forma parte de nuestra filosofía y gracias a esto es posible abordar los desafíos de la industria con soluciones creativas y centradas en el usuario. La startup busca demostrar cómo la tecnología puede elevar la experiencia del cliente y generar valor tanto para los huéspedes como para los establecimientos hoteleros, marcando el camino hacia una nueva era de "hoteles inteligentes" en la capital peruana.

#### 1.1.2. Perfiles de integrantes del equipo
|Miembros del equipo | Codigo Estudiante | Carrera | Conocimientos / Habilidades |
|-|-|-|-|
|Ordoñez Ricaldi, Axel Randall 	![Imagen del compañero](Assets/img/chapter-1/Axel-photo.jpg)|U202216827|Ingenieria de software|C++, SQL, MongoDB, Python. Paciencia y buen trabajo en equipo|
|Panta Castro, Fabrizio Martin 	![Imagen del compañero](Assets/img/chapter-1/Fabrizio%20Martin%20Panta%20Castro.jpg)|U20231A810|Ingenieria de software|SQL, Pyhton, C++. Compañerismo y responsable con las entregas.|
|Ccarita Cruz, Brayan Roberto 	![Imagen del compañero](Assets/img/chapter-1/Roberto-photo.jpg)|U20221C218|Ingenieria de software|Astro.js, Svelte, Golang, Design Sprint. Perseverante y puntual|
| Arrieta Quispe, Alison Jimena  ![Imagen del compañero](Assets/img/chapter-1/Alison-photo.png)| U202312031 |  Ingeniería de Software |  MySql, C++, C#, Docker, Java, JavaScript. Responsable y Trabajadora. |
| Santiago Peña, Andrew Joamrk ![Imagen del compañero](/Assets/img/chapter-1/Andrew-photo.jpg)| U202317362 |Ingenieria de software | MySql, C++, C#, Docker, Perseverante y buen trabajo en equipo. |


## 1.2. Solution Profile
### 1.2.1 Antecedentes y problemática

La industria hotelera ha experimentado una notable evolución tecnológica, donde la implementación de soluciones digitales se ha vuelto crucial para mejorar tanto la eficiencia operativa como la experiencia del cliente. Inicialmente, los sistemas eran manuales, progresando hacia los Sistemas de Gestión de Propiedades (PMS) y, más tarde, a soluciones en la nube. Hoy en día, la inteligencia artificial (IA) está transformando el sector, optimizando procesos y personalizando la interacción con los huéspedes. Sin embargo, la adopción de estas tecnologías, especialmente en lugares como Lima, enfrenta desafíos relacionados con la inversión y la infraestructura (Analysis of Eco-Innovations in Peruvian Accommodation Establishments, 2023).

La personalización se ha convertido en una expectativa fundamental para los viajeros, quienes buscan experiencias adaptadas a sus preferencias. El Internet de las Cosas (IoT) juega un papel esencial al permitir la adaptación de las habitaciones a las necesidades individuales y al agilizar procesos como el check-in y el servicio en la habitación. A pesar de los beneficios, la implementación de IoT presenta retos como los costos iniciales y las preocupaciones de seguridad (Analysis of Eco-Innovations in Peruvian Accommodation Establishments, 2023).

La pandemia de COVID-19 generó una drástica caída en el turismo peruano, evidenciada en el desplome de las llegadas de huéspedes tanto nacionales como extranjeros en el año 2020. Los datos del MINCETUR muestran que los arribos de turistas nacionales se redujeron significativamente de 54.9 millones en 2019 a tan solo 34.6 millones en 2020, mientras que el turismo extranjero experimentó un descenso aún más alarmante, pasando de 8.3 millones a un mínimo histórico de 1.8 millones en el mismo periodo (MINCETUR, 2024). Si bien en los años posteriores se observa una tendencia de recuperación gradual en ambos segmentos, con un aumento constante en las cifras de arribos, aún no se alcanzan los niveles prepandemia, especialmente en el caso del turismo internacional. Esta situación resalta la necesidad de revitalizar el sector a través de la innovación, donde la Inteligencia Artificial (IA) y la domótica emergen como herramientas clave. La IA puede personalizar la experiencia del viajero, optimizar la gestión de recursos y predecir tendencias, mientras que la domótica puede mejorar la eficiencia y el confort en los alojamientos, ofreciendo experiencias más seguras, personalizadas y atractivas para los visitantes en la nueva normalidad.

Por lo tanto, existe una necesidad continua de que los hoteles en Lima adopten e integren tecnologías avanzadas para personalizar la experiencia del huésped y mejorar la eficiencia. A pesar de los desafíos económicos y de infraestructura, la transformación digital y la adopción de IoT son fundamentales para satisfacer las expectativas de los turistas y mantener la competitividad en el mercado hotelero.

### 1.2.2 Lean UX Process.
#### 1.2.2.1. Lean UX Problem Statements.
Nuestro contexto demanda soluciones tecnológicas innovadoras para optimizar la experiencia hotelera de los huéspedes, permitiéndoles personalizar su entorno y disfrutar de una estadía adaptada a sus necesidades individuales. A través de nuestra aplicación de gestión hotelera, buscamos brindar una plataforma integral que permita a los usuarios ingresar sus preferencias y que estas se traduzcan en una habitación inteligente y personalizada desde el momento en que reciben la llave.

Hemos observado un factor importante que afecta la satisfacción de los huéspedes, el cual se manifiesta en la falta de personalización y adaptación de las habitaciones a sus gustos y requerimientos específicos, limitando la sensación de confort y exclusividad durante su estadía.

¿Cómo podemos desarrollar una aplicación de gestión hotelera que se adapte a las necesidades individuales de cada huésped, integrando tecnologías como IoT, biometría y domótica para ofrecer una experiencia personalizada y optimizada en hoteles inteligentes de Lima?
#### 1.2.2.2. Lean UX Assumptions.
##### Business Assumptions

|Assumption|Description|
|-|-|
| Aumento de satisfacción      | La aplicación incrementará la satisfacción del cliente, promoviendo su fidelización y recomendaciones.        |
| Rentabilidad de IoT          | La inversión en domótica e IoT será rentable a mediano plazo por la diferenciación y optimización de recursos.|
| Adaptación del personal      | El personal administrativo podrá adaptarse fácilmente al dashboard y usarlo en su rutina diaria.              | 
| Colaboración con proveedores | Habrá una cooperación fluida con proveedores de domótica para integración y mantenimiento.                    |
| Diferenciación competitiva   | La idea de un "hotel inteligente" destacará frente a otros hoteles en Lima.                                   |
| Versión móvil eficiente      | La versión móvil facilitará la interacción del huésped en todas las etapas de su experiencia.                 |


##### User Assumptions
|Assumption|Description|
|-|-|
| Interés en personalización | Los turistas estarán interesados en la propuesta de personalización vía app.           |
| Valoración del control     | Los huéspedes valorarán poder manejar aspectos como luz o temperatura desde su celular.|
| Facilidad de uso           | Los usuarios verán la app como intuitiva y fácil de usar.                              |
| Confianza en biometría     | Habrá confianza en el uso de tecnología biométrica para acceso y personalización.      |
| Tiempo para configurar     | Los turistas estarán dispuestos a configurar preferencias antes o al llegar.           |
| Percepción de valor        | Los huéspedes verán el hotel inteligente como un valor agregado significativo.         |
#### 1.2.2.3. Lean UX Hypothesis Statements.
1. Creemos que ofrecer a los huéspedes la capacidad de personalizar su habitación a través de una aplicación móvil antes de su llegada aumentará su satisfacción general con la estadía.
Sabremos que hemos tenido éxito cuando observemos un aumento del 15% en las puntuaciones de satisfacción del cliente relacionadas con la comodidad y personalización de la habitación en las encuestas post-estancia.

2. Creemos que la implementación de un dashboard intuitivo para el personal administrativo que centralice las preferencias de los huéspedes optimizará la gestión del hotel y reducirá el tiempo dedicado a tareas relacionadas con la personalización de habitaciones.
Sabremos que hemos tenido éxito cuando el personal administrativo reporte una reducción del 10% en el tiempo promedio dedicado a la preparación y ajuste de las habitaciones según las preferencias de los huéspedes.

3. Creemos que la integración de tecnología biométrica para el acceso a la habitación y la personalización del entorno aumentará la percepción de seguridad y exclusividad entre los huéspedes.
Sabremos que hemos tenido éxito cuando al menos el 80% de los huéspedes que utilicen la función biométrica la califiquen positivamente en términos de seguridad y conveniencia en las encuestas post-estancia.

4. Creemos que ofrecer control domótico de la habitación a través de la aplicación (iluminación, temperatura, etc.) mejorará la comodidad y la experiencia general de los huéspedes durante su estadía.
Sabremos que hemos tenido éxito cuando observemos un aumento del 20% en el uso de las funciones de control domótico dentro de la aplicación por parte de los huéspedes activos.

5. Creemos que al proporcionar una plataforma que permite a los proveedores de domótica monitorear el funcionamiento de sus dispositivos en tiempo real, se facilitará el mantenimiento preventivo y se minimizarán los problemas técnicos en las habitaciones.
Sabremos que hemos tenido éxito cuando se registre una disminución del 5% en el número de reportes de fallas de los dispositivos de domótica en las habitaciones inteligentes.

6. Creemos que la disponibilidad de una versión móvil de la aplicación aumentará la interacción de los huéspedes con la plataforma antes, durante y después de su estadía, fomentando la exploración de los servicios del hotel y posibles reservas futuras.
Sabremos que hemos tenido éxito cuando observemos un aumento del 10% en el número de usuarios activos en la versión móvil de la aplicación y un incremento del 5% en las consultas o reservas realizadas a través de la misma.
#### 1.2.2.4. Lean UX Canvas.

![Lean ux canvas img](assets/chapter-one/lean-ux-canvas.jpg)

## 1.3. Segmentos objetivo.
##### Segmento 1: Huéspedes que desean hospedarse en un hotel

Este segmento incluye a individuos de diversos perfiles demográficos y socioeconómicos que tienen la necesidad o el deseo de alojarse en un hotel en Lima, ya sea por motivos de turismo, negocios u otros.

**Características demográficas:**

- **Rango de edad:** Amplio, desde jóvenes adultos hasta personas mayores.
- **Geografía:** Principalmente turistas nacionales e internacionales que visitan Lima, así como residentes locales que buscan una experiencia diferente.
- **Intereses:** Búsqueda de comodidad, conveniencia, experiencias personalizadas y, específicamente para nuestro caso, interés en la innovación tecnológica y la domótica en hoteles.

**Problema:** Estos huéspedes buscan una experiencia hotelera que vaya más allá de la simple pernoctación, deseando un entorno que se adapte a sus preferencias individuales para una estadía más confortable y memorable.

##### Segmento 2: Personal administrativo del hotel

Este segmento comprende a los empleados del hotel encargados de la gestión operativa, la atención al cliente y el mantenimiento de las instalaciones.

**Características demográficas:**

- **Roles:** Gerentes, recepcionistas, personal de mantenimiento, personal de limpieza, etc.
- **Necesidades:** Herramientas eficientes para la gestión de reservas, la atención a los huéspedes, la organización de las habitaciones y el seguimiento del estado de los dispositivos.
- **Objetivos:** Optimizar la eficiencia operativa, mejorar la satisfacción del cliente y reducir la carga de trabajo manual.

**Problema:** El personal del hotel tiene problemas para saber qué le gusta a cada huésped y asegurarse de que su estadía sea tal como la prefieren. Esto es difícil porque no tienen un sistema fácil y único para guardar y usar esa información.

##### Segmento 3: Proveedores de dispositivos de domótica

Este segmento incluye a las empresas que desarrollan, fabrican y distribuyen dispositivos y sistemas de domótica (iluminación inteligente, control de temperatura, cerraduras electrónicas, etc.).

**Características demográficas:**

- **Tipo de empresas:** Desde startups tecnológicas hasta grandes corporaciones especializadas en IoT y automatización del hogar/edificios.
- **Intereses:** Expandir su mercado, integrar sus productos en nuevos entornos (como hoteles), obtener datos sobre el rendimiento de sus dispositivos en un contexto de uso real y establecer alianzas estratégicas.

**Problema:** Estos proveedores buscan canales efectivos para introducir sus tecnologías en el sector hotelero y necesitan plataformas que faciliten la integración y el monitoreo de sus dispositivos en las instalaciones de sus clientes.

---

# Capítulo II: Requirements Elicitation & Analysis
## 2.1. Competidores.
### 2.1.1. Análisis competitivo.

| Competitive Analysis Landscape                          |  |
| ------------------------------------------------------- | -|
| ¿Por qué llevar a cabo este análisis?                   | Para identificar cómo Custom Host puede diferenciarse en el mercado de hotelería inteligente en Lima, aprovechando su enfoque único en personalización con IoT/biométrica - algo que competidores como INTELITY (solo software) y Cloudbeds (gestión genérica) no ofrecen. El análisis revela oportunidades clave: dominar el nicho de hoteles boutique tecnológicos y crear alianzas estratégicas con proveedores de domótica, mientras se evitan los altos costos de competir directamente con soluciones masivas ya establecidas. |


| |  | Custom Host (Nosotros) | INTELITY | ALICE Platform |Cloudbeds |
|-|-|-|-|-|-|
| PERFIL| Overview | Custom Host es una plataforma innovadora que utiliza IoT y biométrica para personalizar la experiencia hotelera, ajustando automáticamente las habitaciones según las preferencias del huésped. | INTELITY es una plataforma de gestión hotelera enfocada en mejorar el engagement con los huéspedes a través de una app móvil y automatización de servicios.	 | ALICE es un software diseñado para optimizar las operaciones hoteleras, desde reservas hasta mantenimiento, mejorando la eficiencia del personal.	 | Cloudbeds es una solución de gestión hotelera en la nube que combina administración de propiedades, reservas y distribución en una sola plataforma.|
|| Ventaja competitiva ¿Qué valor ofrece a los clientes? | Ofrece adaptación en tiempo real mediante domótica, creando un entorno único que mejora la satisfacción del cliente y simplifica la gestión para los hoteles.| Su integración con sistemas PMS líderes la hace ideal para cadenas hoteleras que buscan una solución tecnológica robusta y escalable.|Su fortaleza radica en la gestión interna, ayudando a hoteles a organizar tareas y comunicarse mejor con empleados y huéspedes.|Destaca por su interfaz intuitiva y su capacidad para integrarse con más de 500 canales de distribución, como Booking y Expedia.|
|| Mercado Objetivo                                        |Se dirige a hoteles boutique y de lujo en Lima, especialmente aquellos que atraen a huéspedes interesados en tecnología y experiencias personalizadas.| Cadenas hoteleras internacionales que necesitan herramientas para gestionar múltiples propiedades de manera eficiente.| Hoteles medianos y grandes, principalmente en EE.UU. y Europa, que buscan simplificar sus procesos operativos. | Hoteles boutique y propiedades independientes que necesitan una herramienta completa y fácil de usar.|
| Perfil de marketing                                     | Estrategia de Marketing | Se centra en alianzas con proveedores de IoT y en destacar su propuesta de "experiencia única" a través de redes sociales y demostraciones interactivas. | Enfoque B2B, con ventas directas a grandes hoteles y participación en ferias del sector. |Webinars y casos de éxito para demostrar su impacto en la productividad hotelera. | Marketing digital y presencia en eventos de la industria para promover sus soluciones. |
| Perfil del producto| Productos y servicios | Incluye una app móvil para huéspedes, un dashboard administrativo y dispositivos IoT para habitaciones inteligentes. | App para huéspedes, API para integraciones personalizadas y herramientas de gestión operativa. | Software para staff, app de huésped y herramientas de coordinación de equipos. |Gestión de reservas, distribución multicanal, informes de desempeño y herramientas de revenue management.|
|| Precios y costos                                        |  Modelo freemium con opciones de suscripción basadas en el número de habitaciones adaptadas. | Licencia anual por hotel, con costos que varían según el tamaño y necesidades de la propiedad. | Basado en el número de habitaciones, con planes adaptables a diferentes tamaños de propiedades. | Tarifa dinámica con planes "Pro" y "360", ajustables según las necesidades del hotel. |
|| Canales de distribución (Web y/o Móvil)                 | Disponible en web y móvil (iOS/Android), facilitando el acceso tanto para huéspedes como para el personal del hotel. | App propia y compatibilidad con sistemas PMS existentes. | Plataforma web y app móvil para acceso remoto. | Plataforma web y móvil, accesible desde cualquier dispositivo.|
### 2.1.2. Estrategias y tácticas frente a competidores.


|Competidores ->|  | Custom Host (Nosotros) | INTELITY| ALICE Platform| Cloudbeds |
|-|-|-|-|-|-|
| Análisis SWOT | Fortalezas | Custom Host destaca por su uso de IoT y biométrica para personalizar automáticamente las habitaciones, junto con un dashboard que simplifica la gestión hotelera, ofreciendo una ventaja competitiva en el mercado de hotelería personalizada | INTELITY es líder en soluciones de guest engagement, con una app móvil robusta y alta integración con sistemas de gestión hotelera (PMS). Su presencia global lo hace atractivo para cadenas internacionales. | ALICE se especializa en optimizar operaciones hoteleras, ayudando al personal con gestión de tareas, mantenimiento y comunicación interna. Es una solución eficiente para hoteles medianos y grandes. | Cloudbeds destaca por su interfaz intuitiva y su capacidad de integración con múltiples canales de distribución (Booking, Expedia). Es ideal para hoteles boutique que buscan una solución todo-en-uno. |
|| Debilidades   | El alto costo de implementación de dispositivos IoT puede ser una barrera para hoteles pequeños. Además, al ser un modelo nuevo, requiere convencer a los hoteles de adoptar tecnología avanzada, lo que puede ralentizar su expansión inicial. | No ofrece personalización física de habitaciones (domótica avanzada), y sus precios pueden ser prohibitivos para hoteles pequeños o independientes. | No se enfoca en la experiencia directa del huésped, lo que limita su atractivo frente a competidores como Custom Host. | No incluye personalización física (IoT), y su modelo de tarifas dinámicas puede ser menos accesible para propiedades pequeñas. | 
|| Oportunidades | El creciente interés en hoteles inteligentes en Lima y la demanda de experiencias personalizadas representan una ventana clave para posicionarse. Alianzas con proveedores de domótica y cadenas boutique podrían acelerar su adopción. | Podría expandirse en mercados emergentes como Latinoamérica, donde la hotelería de lujo busca innovación tecnológica. | La automatización con IA y la expansión en hoteles corporativos podrían fortalecer su propuesta. | El mercado de hoteles independientes sigue creciendo, y su flexibilidad le permite adaptarse a nuevas demandas, como herramientas de revenue management. | 
|| Amenazas      | Competidores establecidos como INTELITY y Cloudbeds ya tienen presencia en el mercado, y la resistencia al cambio en hoteles tradicionales podría limitar su crecimiento. | La creciente competencia en software hotelero y el avance de soluciones basadas en voz (como Volara) podrían reducir su ventaja. | La saturación de PMS genéricos y el surgimiento de plataformas más especializadas representan riesgos para su crecimiento. | Las grandes OTAs (como Booking.com) están desarrollando sus propios sistemas de gestión, lo que podría reducir su participación en el mercado. |

## 2.2. Entrevistas.
### 2.2.1. Diseño de entrevistas.
**Preguntas generales:**
En esta sección realizamos preguntas simples para obtener datos demográficos e información de comportamientos clave, como el navegador y dispositivos que utilizan los entrevistados.

1. ¿Cuál es su nombre? 
2. ¿Qué edad tiene? 
3. ¿A qué se dedica? 
4. ¿Qué navegador y dispositivos utiliza con mayor frecuencia? 

Las siguientes preguntas buscan responder nuestra hipótesis central, mencionada en el capítulo anterior:
"¿Los usuarios estarán interesados en nuestra propuesta innovadora, considerando que existen alternativas similares y que realmente la necesitan?"
(Previo a las entrevistas, se recopiló información básica como el distrito de residencia o procedencia de los usuarios para facilitar el contacto).

**Entrevistas usuario segmento (Huéspedes de hoteles)**
Esta sección de preguntas se enfoca en el punto de vista de los usuarios del segmento huéspedes que desean hospedarse en un hotel.

1. ¿Con qué frecuencia se hospeda en hoteles?
2. ¿Qué aspectos valora más al elegir un hotel?
3. ¿Ha utilizado hoteles con sistemas innovadores?
4. ¿Qué frustraciones ha tenido en sus estadías?
5. ¿Cómo preferiría interactuar con los servicios del hotel?
6. ¿Estaría dispuesto a pagar más por una experiencia adaptada a sus preferencias?  

**Entrevistas usuario segmento (Personal administrativo del hotel)**
Esta sección de preguntas se enfoca en el punto de vista de los usuarios del segmento personal administrativo del hotel.

1. ¿Qué rol desempeña en el hotel?  
2. ¿Cómo registran actualmente las preferencias de los huéspedes?
3. ¿Qué dificultades enfrentan para ofrecer una experiencia personalizada?
4. ¿Cómo gestionan la comunicación entre áreas?
5. ¿Qué tecnologías les gustaría implementar para optimizar procesos?
6. ¿Qué obstáculos ven para adoptar soluciones innovadoras? 
7. ¿Creen que los huéspedes demandan más personalización?

### 2.2.2. Registro de entrevistas.
**Segmento 1**  
Nombre: Fernando San José Zamora Solís 
Edad: 24 años 
Ocupación: Practicante de ingenieria de software
Browser: GoogleChrome y OperaGX
Device: Celular y computadora
Distrito: Jesus Maria
Timing:    
![Imagen de entrevista](/Assets/img/chapter-1/Entrevista%201%20segmento%201.png)

**[Entrevista a Uri (Anexo 2.2.1.1)](https://upcedupe-my.sharepoint.com/:v:/g/personal/u202317362_upc_edu_pe/ETQAkMt6M7VHppn0V_2yowMB4lImpb1OLwaovBnNoPKKhg?e=qYLctj&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D)**  
 minuto [00:00]

Fernando San José, estudiante de ingeniería de software, valora en los hoteles la comodidad y buena relación calidad-precio. Aunque no ha usado hoteles con tecnología avanzada, critica los sistemas anticuados de comunicación, como cuando el teléfono de su habitación no funcionó y tuvieron que enviar personal.

Prefiere interactuar con el hotel mediante una app móvil y le interesaría probar pantallas táctiles en la habitación. Estaría dispuesto a pagar más por personalización (clima, iluminación) y sería cliente recurrente si un hotel ofreciera estas innovaciones.

---
Nombre: Alessandra Becerra
Edad: 18 años 
Ocupación: estudiante de ingenieria de software
Browser: Safari y windows
Device: Celular Iphone y laptop
Distrito: San miguel
Timing:   
![Imagen de entrevista](/Assets/img/chapter-1/entrevista%202%20segmento%201.png)

[Uri entrevista [Anexo 2.2.1.2]](https://upcedupe-my.sharepoint.com/:v:/g/personal/u202317362_upc_edu_pe/EW8bbyowHHNGvrGNiIjfFlwB-Q3bTBRaSvZlTXGKRC2L7w?e=R9zBK3&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D) minuto [00:01]

Alessandra Becerra busca hoteles limpios, con buen WiFi y que acepten mascotas. Critica los sistemas anticuados, especialmente las demoras en check-in y la mala señal de internet. Preferiría usar una app para servicios básicos, pero manteniendo atención humana cuando sea necesario. Le interesaría probar tecnologías como tablets en las habitaciones y pagaría más por servicios que ahorren tiempo y ofrezcan mayor comodidad. Sus experiencias reflejan problemas comunes en hoteles tradicionales que podrían solucionarse con mejor tecnología.

---
Nombre: Luis Cordova
Edad: 25 años 
Ocupación: Data Science 
Browser: Google chrome
Device: computadora y celular
Distrito: San Borja
Timing:   
![Imagen de entrevista](/Assets/img/chapter-1/entrevista%203%20segmento%201.png)

[Uri entrevista [Anexo 2.2.1.2]](https://upcedupe-my.sharepoint.com/personal/u202317362_upc_edu_pe/_layouts/15/stream.aspx?id=%2Fpersonal%2Fu202317362%5Fupc%5Fedu%5Fpe%2FDocuments%2FSegmento%201%20%2D%20Luis%20Cordova%2Emp4&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0&ga=1&referrer=StreamWebApp%2EWeb&referrerScenario=AddressBarCopied%2Eview%2Ee82cd9e2%2D078e%2D4cb0%2D80cf%2D3200ebfdab04) minuto [00:03]

Luis, profesional de Data Science de 25 años, busca hoteles con comodidad y precios razonables para sus viajes de trabajo. Critica los sistemas obsoletos que usan cuadernos físicos y WhatsApp para gestiones, y relata problemas con reservas no cumplidas. Preferiría controlar los servicios mediante asistentes de voz o pantallas táctiles en lugar de los métodos tradicionales. Estaría dispuesto a pagar más por una verdadera personalización que optimice su experiencia como viajero frecuente. Sus experiencias destacan la necesidad urgente de modernizar los sistemas hoteleros con tecnología práctica.

---
**Segmento 2**  
Nombre: David Gallo
Edad: 22 años 
Ocupación: Administracion hotelera
Browser: Safari
Device: Macbook y Iphone
Distrito: San Isidro
Timing:     
![Imagen de entrevista](/Assets/img/chapter-1/entrevista%201%20segmento%202.png)

[Uri entrevista [Anexo 2.2.1.2]](https://upcedupe-my.sharepoint.com/:v:/g/personal/u202317362_upc_edu_pe/ETgSUSNEantAraWk1atoAa4BjISZsufjnztzz_iJVxGXAg?e=oxnXyR&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D) minuto [00:04]

David trabaja en front desk y atención al cliente, usando principalmente Safari en sus dispositivos Apple. Actualmente, registran las preferencias de los huéspedes (como vista al mar o tipo de cama) de forma manual, memorizando datos o anotando en libretas, lo que genera errores en temporadas altas. La comunicación entre áreas se gestiona mediante grupos de WhatsApp, un sistema que considera limitado.

Reconoce que los huéspedes demandan más personalización y que un sistema digitalizado agilizaría las reservas y preferencias. Le gustaría implementar una plataforma centralizada, pero identifica el costo como principal obstáculo. Aún así, confía en que su equipo (mayormente joven) podría adaptarse fácilmente a nuevas tecnologías que mejoren la experiencia del cliente y optimicen sus procesos internos.

---
Nombre: Alex Avila
Edad: 20 años 
Ocupación: Administrador hotelero
Browser: Opera gx y windows
Device: laptop y telefono android
Distrito: Jesus Maria
Timing:  
![Imagen de entrevista](/Assets/img/chapter-1/entrevista%202%20segmento%202.png)

[Uri entrevista [Anexo 2.2.1.2]](https://upcedupe-my.sharepoint.com/:v:/g/personal/u202317362_upc_edu_pe/EU9qNutqfIdAlN0FVSU5avIBOmL9Y3mwIx2kCBAuGyURhw?e=Vb6lwq&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D) minuto [00:02]

Alex trabaja en la administración de un hotel donde actualmente no existe un sistema para registrar preferencias de huéspedes, solo asignan habitaciones básicas (como vista a la calle) sin personalización. La comunicación entre áreas se maneja de forma tradicional, con asignación verbal de tareas y llamadas directas, sin plataformas digitales.

Reconoce que los huéspedes demandan más personalización, pero enfrentan dos obstáculos principales: sistemas anticuados y resistencia al cambio por parte del personal. Le gustaría implementar mejor control de empleados y actualizar su webcam, pero señala que la adaptación a nuevas tecnologías es lenta. Aunque algunos clientes frecuentes reciben trato personalizado (por memoria del staff), nuevos huéspedes no acceden a estos beneficios por falta de sistemas digitales.

---

Nombre: Claudia Sifuentes
Edad: 28 años 
Ocupación: Gerente de operaciones hotelera  
Browser: Firefox
Device: Laptop
Distrito: Lince
Timing:  
![Imagen de entrevista](/Assets/img/chapter-1/entrevista%203%20segmento%202.png)

[Uri entrevista [Anexo 2.2.1.2]](https://upcedupe-my.sharepoint.com/:v:/g/personal/u202317362_upc_edu_pe/EY3QHbePejVFhy4Lxa49_84BAwjrm9Pk8aQZWCyGwuz63Q?e=BSpEnp&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D) minuto [00:02]

Claudia Cifuentes, supervisora de operaciones en hotelería, revela los desafíos tecnológicos de su establecimiento. Aunque utilizan un CRM básico para registrar preferencias de huéspedes, admite que su implementación es irregular y que el personal carece de capacitación adecuada para aprovecharlo. La comunicación interna sigue siendo arcaica, dependiendo principalmente de correos electrónicos y reuniones presenciales.

Claudia identifica dos soluciones clave: implementar un sistema de gestión de habitaciones más robusto y adoptar herramientas de predictibilidad. Sin embargo, señala que los altos costos iniciales y la resistencia al cambio entre el personal son obstáculos significativos. Un dato revelador: los huéspedes, acostumbrados a experiencias personalizadas como las de Airbnb, están demandando cada vez más este tipo de servicios, lo que presiona al hotel a modernizarse a pesar de las dificultades internas. 


---


### 2.2.3. Análisis de entrevistas.
**Segmento 1:** : (Huéspedes):
Estadisticas y Aspectos comunes: En las entrevistas realizadas encontramos que 67% del segmento utiliza el browser de google, asimismo se
muestra que todos los entrevistados usan WhatsApp para su comunicacion, adicionalmente el 100% de los entrevistados mencionan almenos una
discomformidad con la comunicacion que se mantiene con sus superiores. Observamos que piensan en sus demas colegas del area laboral.
Caracteristicas Objetivas: Se requiere un sistema de comunicacion para este segmento, hay una necesidad en saber que hacer solicitando una
entrega de tareas o avisos si es que estas cambian, discomformidad con sistemas lentos. Hacer más, con menos. todos utilizan dispositivos moviles.
Caracteristicas Subjetivas: Todos los entrevistados tienen una fuerte opinion respecto a la comunicacion como un problema comun, seguido de la
falta de servicios actualizados o la falta total de estos que afecta su eficiencia. Todos estan de acuerdo con un cambio parecido al que estaremos
desarollando satisfaciendo nuestro supuesto mas importante por el lado del segmento 1.

**Segmento 2:** (Personal Administrativo):
Estadísticas y Aspectos comunes: El 100% usa WhatsApp o métodos manuales (libretas/Excel) para registrar preferencias, solo el 40% tiene sistemas integrados, y el 90% identifica la comunicación interna como barrera principal. El 80% señala que la falta de capacitación limita la innovación. Características Objetivas: Necesitan un dashboard centralizado para gestionar reservas, preferencias y comunicación entre áreas, con herramientas que reduzcan carga operativa. Características Subjetivas: Coinciden en que la digitalización mejoraría eficiencia, pero preocupan costos iniciales y resistencia al cambio. Reconocen que los huéspedes exigen más personalización (ej. influencia de Airbnb), lo que valida la urgencia de implementar sistemas como Custom Host.

Con esta informacion estamos sustentando los supuestos por el lado del segmento 2 y segmento 1

## 2.3. Needfinding.
### 2.3.1. User Personas.
**Segmento 1:**  

![Imagen User Persona](Assets/img/chapter-1/persona1.png)

**Segmento 2:**

![Imagen User Persona](Assets/img/chapter-1/persona2.png)


### 2.3.2. User Task Matrix.
| --- | ------ | Segmento 1  | Huespedes | Segmento 2  | ---------- |
| --- | ------ | ----------- | ------------ | ----------- | ---------- |
| ID  | Titulo | Importancia | Frecuencia   | Importancia | Frecuencia |
| U01|Personalizar ambiente de la habitación| Alta | Media| Alta  | Alta |
| U02|Realizar check-in/check-out digital| Alta | Baja | Alta  | Alta  |  
| U03| Controlar dispositivos IoT (luz, clima, TV) | Alta| Alta| Media | Alta  | 
| U04|Solicitar servicios adicionales | Media | Media | Alta  | Alta  |
| U05|   Reportar problemas técnicos  | Alta | Baja | Alta  | Media |  
| U06|  Gestionar reservas y modificaciones | Alta   |Baja | Alta  | Alta | 
| U07|  Coordinar limpieza de habitaciones | -| - | Alta | Alta  |
| U08|  Actualizar inventario de amenidades| - | - | Alta | Alta  |  
| U09|  Gestionar comunicación entre áreas  | -  | -  | Alta| Alta  | 
| U10| Registrar preferencias recurrentes | Media  | Baja  | Alta | Media  |

### 2.3.3. User Journey Mapping.
**Registration:**
Why would they trust us?
- Diseño profesional y consistente en la interfaz.
- Integración con cuentas existentes (Google, Apple ID) para registro rápido y confiable.
- Incluir testimonios reales de usuarios verificados
  
**Onboarding and first use:**
How can they feel successful?
- Diseñar un tutorial interactivo guiado paso a paso
- Confirmaciones visuales (animaciones, notificaciones) al realizar acciones.
- Soporte rápido (chat en vivo o bot inteligente para preguntas frecuentes).  
  
**Sharing:**
Why would they invite others?
- Integración con redes sociales para compartir experiencias fácilmente (ej: "Comparte tu habitación personalizada").
- Funciones exclusivas para grupos (ej: "Planifica un viaje con amigos y obtén descuento").
- Sistema de referidos con recompensas para ambos (ej: "Invita a un amigo y ambos ganan 20% de descuento").

**Segmento 1:**  

![Journey 1](Assets/img/chapter-1/journey%201.png)

**Segmento 2:**

![Journey 2](Assets/img/chapter-1/journey%202.png)

### 2.3.4. Empathy Mapping.

**Segmento 1:**

![Emphaty 1](Assets/img/chapter-1/empathy%201.png)


**Segmento 2:**

![Emphaty 2](Assets/img/chapter-1/emphaty%202.png)

### 2.3.5. As-is Scenario Mapping.

**Segmento 1**  
Escenario: Huésped llega a hotel sin sistema de personalización automática

As Is:
| Fases| Fase 1: Check-in | Fase 2: Ajuste manual| Fase 3: Solicitud de servicios| Fase 4: Habitación compartida|
| -------- | --------- | --------- | ------- | --------- |
| Doing | Llenar formularios físicos| Configurar termostato | Llamar a recepción para pedir toallas| Negociar temperatura con acompañante|
| Thinking | "¿Por qué no recuerdan mis preferencias?"| "¿Cómo funciona este control?" | "¿Cuánto tardarán?"| "Nunca logramos estar cómodos los dos"|
| Feeling  | Frustrado por repetir datos| Confundido con tecnología | Impaciente por demoras| Molesto por incomodidad constante|

**Segmento 2**  
Escenario: Personal hotelero gestiona preferencias manualmente

As Is:
| Fases| Fase 1: Recepción | Fase 2: Coordinación| Fase 3: Ejecución| Fase 4: Seguimiento|
| -------- | --------- | --------- | ------- | --------- |
| Doing | Anotar preferencias en papel| Hacer llamadas internas | Corregir errores de habitación| Registrar quejas de huéspedes|
| Thinking | "Seguro se pierde esta nota"| "¿Que decia el mensaje?" | "Otra vez olvidaron las almohadas"| "Nos van a poner mala evaluación"|
| Feeling  | Estresado por desorganización| Ansioso por comunicación fallida | Frustrado por errores repetidos| Preocupado por reputación del hotel
|
## 2.4. Ubiquitous Language.
```
Vacant (Disponible): Estado de una habitación que se encuentra libre y lista para ser ocupada por un nuevo huésped.

InService (En Servicio): Estado en el que una habitación se encuentra en proceso de limpieza, mantenimiento o reposición de productos. Durante este estado, la habitación no está disponible para huéspedes.

Occupied (Ocupada): Estado de una habitación que actualmente está siendo utilizada por un huésped registrado.

Manager (Gerente): Persona encargada de supervisar y coordinar las tareas, el personal (empleados) y la gestión de habitaciones e inventario del hotel.

Employees (Empleados): Personal operativo del hotel cuya función puede variar entre limpieza, atención a la habitación (room service) o reposición de insumos (restocking). Reciben y ejecutan tareas asignadas por el gerente.

Tasks (Tareas): Actividades operativas asignadas a los empleados, como la limpieza de habitaciones, el restocking de productos consumibles, o el mantenimiento de instalaciones.

Items (Ítems o Productos): Bienes consumibles utilizados en las habitaciones, como jabones, toallas, champú, entre otros. Cada ítem debe estar registrado en el inventario con su respectivo nivel de stock para facilitar su control y reposición.

Provider (Proveedor): Entidad que suministra los ítems al hotel. Cada ítem está asociado a un proveedor, lo cual permite realizar filtros y gestiones según el origen del producto.

```

---

# Capítulo III: Requirements Specification
## 3.1. To-Be Scenario Mapping.

![To-Be Scenario Mapping](/Assets/img/Chapter-3/To-Be-Segmento1.png)
![To-Be Scenario Mapping](/Assets/img/Chapter-3/To-Be-Segmento2.png)

## 3.2. User Stories.

| HUX  |    Historia de Usuario / Epica    | Descripción  | Criterios de Aceptación | Relacionado con (Epic ID) |
|------|-----------------------------------|--------------|-------------------------|---------------------------|
| EP01 |Crear cuenta|Como huésped o personal administrativo, quiero crear una cuenta para acceder a las funcionalidades de la aplicación|  **Escenario 1:**<br> Given que el usuario aún no tiene una cuenta, <br> When completa el formulario de registro con sus datos válidos <br>And pulsa el botón "Registrarse",<br>Then debe crearse su cuenta y redirigirse a la pantalla principal de su perfil. <br><br>**Escenario 2:** <br> Given que el usuario ya está registrado, <br> When ingresa su correo y contraseña correctamente en la pantalla de inicio de sesión, <br> Then debe acceder a la plataforma con su sesión iniciada según su rol (huésped o personal)                       |                           |
| EP02 |Configuración de Preferencias del Huésped|Como huésped, quiero establecer mis preferencias de iluminación y temperatura, para que mi habitación se adapte automáticamente.|**Escenario 1:** <br> Given que el huésped accede a la sección de preferencias en su perfil, <br> When selecciona su temperatura, tipo de luz y guarda los cambios, <br> Then la plataforma debe almacenar estas preferencias de forma personalizada. <br><br> **Escenario 2:** <br> Given que el huésped ingresa a su habitación con sesión activa, <br> When se detecta su presencia en la habitación, <br> Then los dispositivos deben ajustarse automáticamente según las preferencias registradas.|                           |
| EP03 |Gestión de Solicitudes de Servicios|Como huésped, quiero poder solicitar servicios desde la aplicación para tener una atención personalizada a mis gustos.|**Escenario 1:** <br>Given que el huésped desea solicitar un servicio,<br>When accede a la sección de "Solicitudes" y selecciona el tipo de servicio requerido,<br>Then debe enviarse la solicitud <br> And mostrar una confirmación con el estado "Pendiente".<br><br>**Escenario 2:** <br>Given que el huésped quiere revisar el estado de su solicitud, <br>When abre la sección de solicitudes activas en la aplicación,<br>Then debe poder visualizar el estado actualizado (pendiente, en proceso, completado) de cada solicitud.|                           |
| EP04 |Panel de control|Como personal administrativo, quiero tener un dashboard con información en tiempo real sobre las solicitudes de los huéspedes, para  poder gestionarlos mejor.|**Escenario 1:** <br>Given que el personal administrativo está en el panel de control, <br>When accede a la sección de solicitudes de los huéspedes <br>Then debe visualizar en tiempo real las nuevas solicitudes recibidas y su estado actual. <br><br>**Escenario 2:** <br>Given que el personal está gestionando una solicitud, <br>When cambia el estado de una solicitud a “En proceso” o “Completado”,<br>Then el huésped debe recibir una notificación con el nuevo estado actualizado.|                           |
| EP05 |Notificaciones en tiempo real|Como huésped o personal del hotel, quiero recibir notificaciones en tiempo real, para poder saber sobre eventos importantes o problemas técnicos.|**Escenario 1:**<br>Given que el huésped está conectado a la aplicación móvil,<br>When se genera un evento importante (como una promoción o evento del hotel),<br>Then debe recibir una notificación en tiempo real con el contenido del evento.|                           |
| EP06 |Seguimiento de Historial de Preferencias|Como developer, quiero tener acceso al historial de preferencia de los huéspedes, para mejorar la aplicación en base a las preferencias de los usuarios.| **Escenario 1:** <br> Given que un huésped modifica sus preferencias,<br>When guarda los cambios,<br>Then el sistema debe registrar los cambios<br><br>**Escenario 2:**<br>Given que el desarrollador accede al panel de administración,<br>When selecciona el perfil de un huésped,<br>Then debe visualizar el historial de preferencias registradas y fechas de modificación.|                           |
| EP07 |Gestión de habitaciones|Como developer, quiero implementar un sistema de gestión de habitaciones, para que permita modificar y asignar habitaciones disponibles.|**Escenario 1:**<br>Given que el administrador accede al sistema de gestión de habitaciones,<br>When selecciona una habitación ocupada,<br>Then debe visualizar sus datos, estado actual y tener la opción de reasignar a otro huésped.<br><br>**Escenario 2:** <br>Given que hay habitaciones nuevas disponibles,<br>When el personal técnico o administrativo actualiza su estado en el sistema,<br>Then estas deben mostrarse como disponibles para nuevas reservas|                           |
| EP08 |Implementacion de la landing page informativa|Como huésped, quiero tener acceso a una plataforma web, para conocer los servicios que brindan en el hotel.|**Escenario 1:** <br>Given que el visitante se encuentra en la página principal de la plataforma, <br>When accede a la sección inferior del sitio, <br>Then debe visualizar la información de contacto, incluyendo dirección, teléfono, correo y enlaces a redes sociales. <br><br>**Escenario 2:** <br>Given que el visitante necesita hacer una consulta, <br>When accede al icono de contacto disponible en la interfaz, <br>Then se debe mostrar un formulario emergente para que pueda enviar su mensaje directamente desde la landing.|                           |
| EP09 |Gestión de Reservas|Como developer, quiero desarrollar un sistema de gestión de reservas, para que los huéspedes puedan realizar, modificar o cancelar la reserva de sus habitaciones.|**Escenario 1:** <br>Given que el huésped desea reservar una habitación, <br>When selecciona una fecha y habitación disponible y confirma la reserva, <br>Then el sistema debe registrar la reserva y mostrar un resumen con los detalles. <br><br>**Escenario 2:** <br>Given que el huésped ya tiene una reserva confirmada, <br>When accede a la sección de “Mis reservas” y selecciona la opción de modificar o cancelar, <br>Then debe poder editar la información o anular la reserva según disponibilidad.|                           |
| EP10 |Evaluación de la Experiencia del Huésped|Como huésped, quiero poder calificar mi experiencia, para compartir mis opiniones sobre el servicio recibido.|**Escenario 1:** <br>Given que el huésped ha finalizado su estadía, <br>When recibe la notificación para calificar el servicio, <br>Then debe poder acceder a un formulario con estrellas y comentarios para evaluar su experiencia. <br><br>**Escenario 2:** <br>Given que el huésped ya completó una evaluación, <br>When accede a su historial de reservas, <br>Then debe poder visualizar sus calificaciones anteriores y los comentarios registrados.|                           |
| EP11 |Sistema de Recompensas y Fidelización|Como huésped, quiero recibir puntos o beneficios por mis visitas, para sentirme valorado y motivado a volver.|**Escenario 1:** <br>Given que el huésped ha realizado una nueva reserva, <br>When completa su estadía sin cancelaciones, <br>Then debe acumular puntos de fidelidad visibles en su perfil. <br><br>**Escenario 2:** <br>Given que el huésped ha acumulado puntos suficientes, <br>When accede a la sección de recompensas, <br>Then debe poder canjear sus puntos por beneficios o descuentos disponibles.|                           |
| EP12 |Gestión Multilingüe de la Plataforma|Como huésped quiero que la plataforma esté disponible en más de un idioma para poder usar el idioma de mi preferencia.|**Escenario 1:** <br>Given que el huésped está en la pantalla principal, <br>When accede al selector de idioma y elige otro idioma disponible, <br>Then toda la interfaz debe traducirse automáticamente al idioma seleccionado. <br><br>**Escenario 2:** <br>Given que el huésped configura su idioma preferido en el perfil, <br>When inicia sesión en una nueva ocasión, <br>Then la plataforma debe cargar automáticamente en su idioma predeterminado.|                           |
| EP13 |Seguridad y Privacidad de Datos|Como developer, quiero implementar, mecanismos de seguridad y privacidad de datos, para proteger la información de los usuarios.|**Escenario 1:** <br>Given que el usuario está ingresando sus datos personales, <br>When completa el formulario de registro, <br>Then el sistema debe asegurar la transmisión cifrada de los datos mediante protocolo HTTPS. <br><br>**Escenario 2:** <br>Given que un usuario desea eliminar su cuenta, <br>When confirma la eliminación desde la configuración, <br>Then todos sus datos personales deben eliminarse según la política de privacidad.|                           |
| EP14 |Soporte en Línea para el Usuario|Como huésped quiero tener un soporte personalizado y que responda inmediatamente para poder resolver mis problemas o mis consultas.|**Escenario 1:** <br>Given que el huésped tiene una consulta relacionada con su experiencia en el hotel, <br>When accede a la funcionalidad de soporte, <br>Then debe iniciarse una conversación en tiempo real con un agente disponible. <br><br>**Escenario 2:** <br>Given que no hay agentes disponibles, <br>When el huésped solicita asistencia fuera del horario de atención, <br>Then debe visualizarse un formulario para dejar su consulta y recibir una respuesta por correo electrónico.|                           |
| EP15 |Gestión de perfiles|Como developer, quiero implementar un sistema de gestión de perfiles de usuario que permita editar la información y preferencias, para que cada tipo de usuario tenga una experiencia personalizada.|**Escenario 1:** <br>Given que el usuario desea actualizar su información, <br>When accede a su perfil y edita su nombre, correo o preferencias, <br>Then los cambios deben guardarse y reflejarse inmediatamente en su cuenta. <br><br>**Escenario 2:** <br>Given que el sistema tiene diferentes tipos de usuarios, <br>When un administrador crea un nuevo perfil, <br>Then debe poder asignar el rol (huésped, técnico, administrativo) para determinar su acceso y permisos.|                           |
| HU01 |Visualización de Información de Servicios.|Como visitante del sitio, quiero visualizar los servicios que ofrece el hotel, para saber lo que ofrece antes de hacer una reserva.|**Escenario 1:** <br>Given que el visitante ha accedido a la landing page del sitio web, <br>When navega hacia la sección de servicios en la página, <br>Then el sistema debe mostrar un listado claro de los principales servicios.| EP08 |
| HU02 |Acceso a Información de Contacto.|Como visitante del sitio, quiero acceder fácilmente a los datos de contacto del hotel, para poder comunicarme si tengo dudas o necesito ayuda.|**Escenario 1:** <br>Given que el visitante visualiza la plataforma del hotel, <br>When revisa la parte inferior del sitio, <br>Then debe encontrar la información de contacto completa del hotel. <br><br>**Escenario 2:** <br>Given que el visitante necesita realizar una consulta rápida, <br>When utiliza la opción de contacto en la interfaz, <br>Then debe mostrarse un formulario emergente para enviar su mensaje.| EP08 |
| HU03 |Acceso a Testimonios de Huéspedes.|Como visitante del sitio, quiero leer opiniones de otros huéspedes, para tener mayor confianza al momento de decidir si reservar.|**Escenario 1:** <br>Given que el visitante está explorando la página de inicio, <br>When visualiza la sección de testimonios, <br>Then debe encontrar opiniones ordenadas cronológicamente, con nombre, fecha de estadía y contenido. <br><br>**Escenario 2:** <br>Given que hay múltiples testimonios disponibles, <br>When el visitante solicita ver más opiniones, <br>Then el sistema debe cargar contenido adicional dinámicamente, sin recargar la página.| EP08 |
| HU04 |Acceso Rápido al Formulario de Reserva.|Como visitante del sitio, quiero encontrar fácilmente un botón para reservar una habitación, para iniciar rápidamente el proceso si me interesa.|**Escenario 1:** <br>Given que el visitante se encuentra en la landing page del sitio web, <br>When llega a la sección de servicios o al final de la página, <br>Then debe ver un botón fijo "Reservar ahora" que redirige al formulario de reservas.| EP08 |
| HU05 |Sección "Sobre Nosotros".|Como visitante del sitio, quiero conocer la historia y valores del hotel, para tener mayor conexión y confianza con la empresa.|**Escenario 1:** <br>Given que el visitante está explorando la landing page, <br>When llega a la sección “Sobre Nosotros”, <br>Then debe visualizar una descripción breve de la historia del hotel, su equipo y valores, acompañada de imágenes. <br><br>**Escenario 2:** <br>Given que hay contenido multimedia sobre la historia del hotel, <br>When el visitante interactúa con el video informativo, <br>Then el video debe reproducirse en el mismo entorno visual, sin redirigir a otras páginas.| EP08 |
| HU06 |Visualización del Formulario de Registro.|Como huésped, quiero ver un formulario de registro bien estructurado, para poder registrarme en el sistema.|**Escenario 1:** <br>Given que el huésped nuevo accede a la plataforma web, <br>When decide registrarse como nuevo usuario, <br>Then el sistema debe mostrar un formulario de registro claro, accesible y fácil de completar. <br><br>**Escenario 2:** <br>Given que el huésped ha accedido al formulario de registro, <br>When intenta enviar los datos sin completar todos los campos obligatorios, <br>Then el sistema debe mostrar un mensaje que indique qué campos deben completarse.| EP01 |
| HU07 |Validación de Datos de Registro.|Como huésped, quiero que el sistema valide mis datos al registrarme, para evitar errores en mi cuenta.|**Escenario 1:** <br>Given que el huésped ha completado correctamente todos los campos del formulario de registro, <br>When envía los datos para su registro, <br>Then el sistema debe validar la información y redirigirlo a la página de confirmación de cuenta. <br><br>**Escenario 2:** <br>Given que el huésped ha ingresado un correo electrónico ya registrado, <br>When intenta registrar su cuenta, <br>Then el sistema debe notificar que el correo electrónico ya está en uso y sugerir opciones para recuperar la cuenta o cambiar el correo.| EP01 |
| HU08 |Configuración de Preferencias de habitación.|Como huésped, quiero seleccionar mis preferencias de habitación desde la plataforma web, para personalizar mi estadía.|**Escenario 1:** <br>Given que el huésped accede a la sección de configuración personal, <br>When define sus preferencias de temperatura y luz, <br>Then el sistema debe guardar las configuraciones y reflejarlas en su perfil de usuario. <br><br>**Escenario 2:** <br>Given que el huésped accede a la configuración de preferencias, <br>When elige restablecer los valores personalizados, <br>Then el sistema debe restablecer todas las opciones a sus valores predeterminados.| EP02 |
| HU09 |Personalización de Horarios de Servicio.|Como huésped, quiero establecer mis horarios de preferencia para servicios como limpieza o desayuno.|**Escenario 1:** <br>Given que el huésped accede a la sección de "Preferencias", <br>When selecciona el horario de limpieza para la mañana, <br>Then el sistema debe actualizar sus preferencias con el nuevo horario. <br><br>**Escenario 2:** <br>Given que el huésped selecciona un horario para el servicio de desayuno, <br>When guarda los cambios, <br>Then el sistema debe confirmar la actualización.| EP02 |
| HU10 |Solicitud de Servicios de Limpieza.|Como huésped, quiero solicitar un servicio de limpieza directamente desde la plataforma web, para mantener mi habitación limpia.|**Escenario 1:** <br>Given que el huésped accede a la sección de "Servicios", <br>When selecciona "Solicitar limpieza", <br>Then el sistema debe enviar una solicitud de limpieza y confirmar la solicitud con un mensaje.<br><br>**Escenario 2:** <br>Given que el huésped intenta solicitar un servicio fuera de horario, <br>When seleccione "Solicitar limpieza", <br>Then el sistema debe mostrar un mensaje informando sobre los horarios.| EP03 |
| HU11 |Solicitud de Desayuno en la Habitación.|Como huésped, quiero poder solicitar un desayuno en mi habitación a través de la plataforma web.|**Escenario 1:** <br>Given que el huésped entra a la sección "Solicitar desayuno", <br>When elige "Desayuno en la habitación" y selecciona el horario, <br>Then el sistema debe procesar la solicitud y confirmar el envío. <br><br>**Escenario 2:** <br>Given que el huésped selecciona "Desayuno en la habitación", <br>When selecciona un horario fuera de los disponibles, <br>Then el sistema debe mostrar un mensaje de error.| EP03 |
| HU12 |Gestión de Solicitudes Pendientes.|Como personal administrativo, quiero poder ver las solicitudes pendientes para atenderlas rápidamente.|**Escenario 1:** <br>Given que el miembro del personal administrativo accede a la sección de "Solicitudes", <br>When ve una lista de solicitudes, <br>Then el sistema debe mostrar las solicitudes ordenadas por urgencia y fecha. <br><br>**Escenario 2:** <br>Given que el miembro del personal administrativo tiene una solicitud nueva, <br>When selecciona "Ver detalles", <br>Then el sistema debe mostrar la información completa de la solicitud.| EP04 |
| HU13 |Modificación de Estado de la Solicitud.|Como personal administrativo, quiero poder cambiar el estado de una solicitud, para gestionarla mejor.|**Escenario 1:** <br>Given que el miembro del personal accede a la solicitud de un huésped, <br>When selecciona "Marcar como atendida", <br>Then el sistema debe cambiar el estado de la solicitud y mostrar el mensaje de confirmación. <br><br>**Escenario 2:** <br>Given que el miembro del personal ve que una solicitud está pendiente, <br>When selecciona "Marcar como pendiente", <br>Then el sistema debe confirmar el cambio de estado.| EP04 |
| HU14 |Notificación de solicitud atendida.|Como huésped, quiero recibir alertas cuando mi solicitud se atienda, para estar informado.|**Escenario 1:** <br>Given que el personal completa una solicitud, <br>When el estado cambia es atendido, <br>Then el huésped recibe una notificación inmediata. <br><br>**Escenario 2:** <br>Given que el sistema tiene un error, <br>When el estado cambia, <br>Then el huésped no recibe ninguna notificación.| EP05 |
| HU15 |Alerta de emergencia en el hotel.|Como personal, quiero recibir alertas inmediatas sobre emergencias, para reaccionar rápido.|**Escenario 1:** <br>Given que se activa una alerta de emergencia como un incendio, <br>When se emite desde el sistema, <br>Then todo el personal recibe una notificación urgente. <br><br>**Escenario 2:** <br>Given que se realiza una prueba del sistema, <br>When se lanza la alerta, <br>Then el mensaje indica claramente "Simulación de emergencia".| EP05 |
| HU16 |Enviar evaluación de estadía.|Como huésped, quiero calificar mi experiencia al final de la estadía, para dar retroalimentación al hotel.|**Escenario 1:** <br>Given que el huésped ha finalizado su estadía, <br>When completa el formulario de evaluación y lo envía, <br>Then el sistema registra la evaluación y muestra "Gracias por tu opinión". <br><br>**Escenario 2:** <br>Given que el huésped no llena todos los campos, <br>When intenta enviar, <br>Then el sistema muestra un mensaje indicando que debe completar todos los campos obligatorios.| EP10 |
| HU17 |Ver historial de evaluaciones.|Como personal administrativo, quiero consultar las evaluaciones recibidas, para mejorar la calidad del servicio.|**Escenario 1:** <br>Given que el personal accede a la sección de evaluaciones, <br>When selecciona un rango de fechas, <br>Then se muestran las evaluaciones correspondientes. <br><br>**Escenario 2:** <br>Given que no existen evaluaciones en ese periodo, <br>When consulta, <br>Then el sistema muestra "No se encontraron evaluaciones en este periodo".| EP10 |
| HU18 |Visualizar puntos acumulados.|Como huésped, quiero ver cuántos puntos de fidelidad tengo, para saber qué recompensas puedo obtener.|**Escenario 1:** <br>Given que el huésped accede a su cuenta, <br>When navega a la sección de recompensas, <br>Then puede visualizar su total de puntos acumulados. <br><br>**Escenario 2:** <br>Given que el huésped aún no ha generado puntos, <br>When accede a la sección, <br>Then el sistema muestra "Todavía no tienes puntos acumulados".| EP11 |
| HU19 |Canjear puntos por recompensa.|Como huésped, quiero canjear mis puntos por beneficios, para aprovechar el programa de fidelidad.|**Escenario 1:** <br>Given que el huésped tiene suficientes puntos, <br>When selecciona una recompensa y confirma el canje, <br>Then el sistema descuenta los puntos y entrega el beneficio. <br><br>**Escenario 2:** <br>Given que el huésped no tiene los puntos requeridos, <br>When intenta realizar el canje, <br>Then el sistema muestra "No tienes suficientes puntos para esta recompensa".| EP11 |
| HU20 |Cambiar el idioma de la interfaz.|Como huésped internacional, quiero cambiar el idioma de la interfaz, para comprender mejor la plataforma web.|**Escenario 1:** <br>Given que el huésped se encuentra en la configuración de idioma, <br>When selecciona “inglés”, <br>Then toda la interfaz se traduce automáticamente. <br><br>**Escenario 2:** <br>Given que el huésped intenta seleccionar un idioma no disponible, <br>When realiza el cambio, <br>Then el sistema muestra "Idioma no disponible actualmente".| EP12 |
| HU21 |Recordar el idioma seleccionado.|Como huésped, quiero que la plataforma recuerde mi idioma preferido, para no tener que cambiarlo cada vez.|**Escenario 1:** <br>Given que el huésped ha seleccionado un idioma, <br>When vuelve a iniciar sesión, <br>Then la plataforma carga directamente en ese idioma. <br><br>**Escenario 2:** <br>Given un problema técnico, <br>When el huésped cambia el idioma, <br>Then la plataforma vuelve a aparecer con el idioma predeterminado.| EP12 |
| HU22 |Iniciar chat con soporte.|Como huésped, quiero iniciar un chat con soporte, para resolver dudas rápidamente.|**Escenario 1:** <br>Given que el huésped accede a la sección de ayuda, <br>When presiona el botón de chat, <br>Then se abre una ventana con un agente disponible. <br><br>**Escenario 2:** <br>Given que no hay agentes en línea, <br>When intenta iniciar el chat, <br>Then el sistema muestra "No hay agentes disponibles, por favor inténtelo más tarde".| EP14 |
| HU23 |Consultar preguntas frecuentes.|Como huésped, quiero revisar preguntas frecuentes, para resolver dudas sin contactar soporte.|**Escenario 1:** <br>Given que el huésped accede al FAQ, <br>When busca “cómo solicitar limpieza”, <br>Then el sistema muestra artículos relacionados. <br><br>**Escenario 2:** <br>Given que busca una pregunta no registrada, <br>When realiza la búsqueda, <br>Then el sistema le mostrará preguntas similares a la realizada.| EP14 |
| TS01 |Modificar preferencias|Como desarrollador, quiero que el sistema guarde los cambios de preferencias de los huéspedes en una base de datos, para tener un registro de sus elecciones.|**Escenario 1:** <br>Given que un huésped modifica su preferencia ,<br> When el sistema recibe la solicitud de actualización  <br>And el sistema valida los datos modificados <br>And verifica que el huesped esta registrado<br>Then el sistema guarda los datos modificados en la tabla preferencias <br>And devuelve el mensaje: "Preferencias actualizadas correctamente" <br><br>**Escenario 2:** <br>Given que un huesped deja un campo vacio,<br>When el sistema recibe la sulicitud de guardar,<br>And detecta que algún campo es vacio o null<br>Then el sistema no guarda los cambios en la base de datos <br>And envia un mensaje de error: "Completar todos los campos"|EP06|
|TS02|Consultar historial de preferencias|Como desarrollador, quiero que el sistema muestre el historial cambios de preferencias de un huésped, para mejorar la experiencia de usuario basado en sus elecciones pasadas|**Escenario 1:** <br> Given que un administrador accede al perfil de un huésped registrado,<br>When el sistema recibe la solicitud para mostrar el historial de un usuario <br> Then el sistema devuelve la información de preferencias del usuario seleccionado <br>And tambien muestra la fecha en la que se modifico por ultima vez <br><br>**Escenario 2:**<br>Given que el huésped aun no ha realizado una modificación en sus preferencias,<br> When el sistema solicita su historial, <br> Then el sistema devuelve el mensaje: "Aun no se han registrado modificaciones" |EP06|
|TS03|Eliminar preferencias obsoletas|Como desarrollador, quiero que el sistema permita eliminar preferencias antiguas o incorrectas de un huésped, para mantener la base de datos limpia y actualizada.|**Escenario 1:**<br>Given que un administrador identifica una preferencia que no es valida <br>When el sistema recibe una solicitud de eliminar preferencia <br>And el sistema verifica que el id le pertenece a un huesped <br>Then elimina el registro de las preferencias del usuario <br> And registra las acciones realizadas en una tabla auditoria <br> And devuelve un mensaje: "Preferencia eliminada correctamente"<br><br>**Escenario 2:** <br>Given que un usuario que no tiene rol de administrador intenta eliminar una preferencia,<br>When el sistema valida sus permisos,<br>Then el sistema rechaza la acción con: "Acceso no autorizado".|EP06|
|TS04|Actualización de estado de habitaciones|Como desarrollador, quiero que el sistema permita actualizar el estado de las habitaciones (disponible / ocupado / en mantenimiento), para reflejar la disponibilidad de las reservar.|**Escenario 1:** <br>Given que el administrador selecciona una habitación, <br>When modifica su estado a "en mantenimiento" <br>And confirma la acción, <br>Then el sistema actualiza el estado en la base de datos, <br> And el sistema notifica: "Actualizado correctamente". <br><br> **Escenario 2:**<br>Given que se ingresa una habitación que no existe en la,<br>When el sistema busca el registro, <br>And no encuentra la habitación, <br>Then muestra el error: "Habitación no registrada".|EP07|
|TS05|Reasignación de habitaciones|Como desarrollador, quiero que el sistema permita reasignar una habitación ocupada a otro huésped, para optimizar el uso de espacios según necesidades cambiantes.|**Escenario 1:**<br>Given que el administrador selecciona una habitación ocupada,<br>When se asigna la habitación a un nuevo huésped y confirma, <br> Then el sistema libera la habitación del huésped previo, <br>And se registra al nuevo huésped, <br> And el sistema actualiza el historial de cambios. <br><br>**Escenario 2:** <br>Given que se ingresa un ID de huésped no registrado,<br>When el sistema valida si el huesped esta registrado en la base de datos, <br>Then se cancela la acción y notifica el error: "Huesped no encontrado".|EP07|
|TS06|Consulta de disponibilidad de habitaciones|Como desarrollador, quiero implementar un sistema de consulta de habitaciones disponibles con filtros, para que el personal pueda encontrar rápidamente espacios según filtros específicos.|**Escenario 1:** <br>Given que el administrador ingresa filtros de busqueda <br> When el sistema recibe los filtros de busqueda, <br> Then devuelve una lista de habitaciones disponibles que coincidan con los filtros,<br>And muestra las caracteristicas de la habitación.<br><br>**Escenario 2:**<br>Given que no hay habitaciones disponibles para los filtros aplicados,<br>When el sistema completa la búsqueda,<br>And no encuentra los filtros aplicados<br>Then devuelve un mensaje: "No se encontraron habitaciones con esos criterios".|EP07|
|TS07|Sistema de Registro de Reservas en Base de Datos|Como desarrollador, quiero una funcionalidad para almacenar nuevas reservas en la base de datos, para que el sistema pueda gestionar las reservas de los huéspedes.|**Escenario 1:** <br>Given que un huésped selecciona una habitación disponible y completa el formulario de reserva, <br>When el sistema valida que las fechas están disponibles, <br>And todos llos campos fueron completados, <br>And el huesped existe en el sistema,<br> Then el sistema guarda la reserva en la base de datos, <br>And actualiza el estado de la habitación, <br>And muestra al huésped un mensaje de confirmación con su número de reserva. <br><br> **Escenario 2:** <br> Given que un huésped intenta reservar una habitación ya ocupada para las fechas seleccionadas, <br> When el sistema verifica la disponibilidad de la habitación, <br>Then el sistema no guarda la reserva, <br>And muestra el mensaje: "Habitación no disponible", <br>And sugiere otras habitaciones disponibles|EP09|
|TS08|Módulo de Modificación de Reservas|Como desarrollador, quiero modificar las reservas existentes, para permitir a los huéspedes ajustar sus reservas según cambios en sus planes.|**Escenario 1:** <br> Given que un huésped solicita modificar una reserva confirmada, <br>When el sistema verifica que la nueva habitación está disponible,<br>And las nuevas fechas están disponibles,<br> And la reserva no ha sido cancelada previamente,<br>Then el sistema actualiza los datos de la reserva, <br>Envía un correo de confirmación con los nuevos detalles. <br><br> **Escenario 2:**<br>Given que un huésped intenta modificar una reserva pero no hay disponibilidad,<br>When el sistema valida los nuevos datos y no encuentra alguna coincidencia,<br>Then se mostrara el siguiente mensaje: "No hay disponibilidad para los cambios solicitados",<br>And ofrece opciones alternativas.|EP09|
|TS09|Consulta de reservas activas|Como desarrollador, quiero implementar la funcionalidad para consultar reservas activas, para que los huéspedes y administradores puedan ver el estado de las reservas.|**Escenario 1:** <br> Given que huésped o administrador accede al sistema, <br>When solicita ver las reservas que se encuntran activas, <br> Then el sistema muestra los detalles de la habitación junto al número de la reserva <br>And muestra el estado de la reserva ("Confirmada","Cancelada")<br><br>**Escenario 2:** <br> Given que un huésped no tiene reservas activas, <br>When xonsulta el historial de reservas, <br>Then el sistema muestra el mensaje: "No tiene reservas activas actualmente"|EP09|
|TS10|Eliminación Segura de Datos de Usuarios|Como desarrollador, quiero implementar una opción para eliminar todos los datos personales de un usuario, para cumplir con políticas de privacidad|**Escenario 1:** <br>Given que un usuario solicita eliminar su cuenta, <br>When se confirma el envio de la acción, <br>Then el sistema borra los datos de la tabla, <br>And conserva los registros en estado anónimo. <br><br>**Escenario 2:** <br>Given que un administrador intenta eliminar manualmente una cuenta, <br> When el sistema detecta que tiene datos de reserva asociados, <br>Then se solicita una confirmación adicional antes de eliminar la cuenta.|EP13|
|TS11|Registro de Actividades Sospechosas|Como desarrollador, quiero registrar intentos de acceso fallidos y actividades inusuales, para detectar y responder a posibles brechas de seguridad.|**Escenario 1:** <br>Given que un usuario falla al ingresar su contraseña 3 veces, <br>When el sistema registra el evento, <br>Then bloquea temporalmente la cuenta y notifica al administrador.|EP13|
|TS12|Implementación de Políticas de Cookies y Consentimiento|Como desarrollador, quiero implementar un sistema de gestión de cookies, para informar a los usuarios y obtener su consentimiento antes de almacenar datos.|**Escenario 1:** <br> Given que un usuario visita el sitio por primera vez, <br> When el sistema detecta que no hay preferencias guardadas, <br>Then muestra un banner preguntando al usuario para usar sus cookies,<br>And le muestra opciones para aceptar/rechazar.|EP13|
|TS13|Encriptación de Datos Sensibles en Base de Datos|Como desarrollador, quiero encriptrar información sensible del usuario, para mantener la información segura de los usuarios.|**Escenario 1:** <br>Given que un usuario ingresa su número de tarjeta en un formulario,<br>When el sistema guarda los datos,<br>Then almacena los datos y los encripta en la base de datos. <br><br> **Escenario 2:** <br> Given que un administrador consulta la base de datos directamente, <br>When revisa los campos encriptados,<br>Then ve valores cifrados en lugar de datos originales. |EP13|
|TS14| Actualización de Perfiles de Usuario|Como desarrollador,<br>quiero implementar un sistema seguro para actualizar información de perfiles,<br>para que los usuarios puedan modificar sus datos personales y preferencias.|**Escenario 1:**<br>Given que un usuario autenticado envía una solicitud para actualizar los datos perfil,<br>When el sistema valida los nuevos datos, <br>Then actualiza la información en la base de datos,<br>And devuelve una confirmación al frontend. <br><br>**Escenario 2:** <br>Given que un usuario intenta actualizar su perfil con un correo ya registrado, <br>When el sistema detecta el duplicado, <br>Then el sistema rechaza la actualización y notifica con el mensaje: "El correo ya está en uso". |EP15|
|TS15|Gestión de Roles y Permisos|Como desarrollador, quiero crear un sistema de asignación de roles, para controlar accesos y funcionalidades según el tipo de usuario.|**Escenario 1:** <br>Given que un administrador asigna un rol a un nuevo usuario, <br>When el sistema procesa la solicitud,<br>Then guarda el rol en la base de datos, <br>And aplica automáticamente los permisos asociados. <br><br>**Escenario 2:** <br>Given que un usuario sin privilegios intenta asignar roles,<br>When el sistema verifica sus permisos,<br>Then bloquea la acción y registra el intento en logs. |EP15|
|TS16|Visualización Condicional de Interfaces|Como desarrollador, quiero adaptar la interfaz según el rol del usuario, para mostrar solo las opciones relevantes a cada perfil.|**Escenario 1:** <br> Given que un huésped inicia sesión,<br>When el sistema carga su perfil,<br>Then muestra solo secciones como "Mis reservas" y "Preferencias". <br><br>**Escenario 2:** <br>Given que un administrador accede al sistema, <br>When se renderiza la interfaz, <br>Then incluye pestañas como "Gestión de usuarios" y "Reportes". |EP15|

## 3.3. Impact Mapping.

![Impact Mapping](/Assets/img/Chapter-3/Impact-map-Administrador-de-hotel.png)
![Impact Mapping](/Assets/img/Chapter-3/Impact-map-huésped.png)

## 3.4. Product Backlog.

Link Trello: https://trello.com/invite/b/6807e09feff6aab74b684127/ATTI98b87d9f903a3b4af1efa73604221d6aE9912258/customhost-product-backlog

| #Orden | User Story ID | Titulo| Descripción| Story Points (1/2/3/5/8) |
| ------ | ------------- | ----- | ---------- | ------------------------ |
|1|US01|Visualización de servicios del hotel|Como visitante del sitio, quiero visualizar los servicios que ofrece el hotel, para saber lo que ofrece antes de hacer una reserva.|2|
|2|US02|Acceso a información de contacto|	Como visitante del sitio, quiero acceder fácilmente a los datos de contacto del hotel, para poder comunicarme si tengo dudas o necesito ayuda.|1|
|3|US03|Acceso a Testimonios de Huéspedes|	Como visitante del sitio, quiero leer opiniones de otros huéspedes, para tener mayor confianza al momento de decidir si reservar.|3|
|4|US04|Acceso Rápido al Formulario de Reserva|Como visitante del sitio, quiero encontrar fácilmente un botón para reservar una habitación, para iniciar rápidamente el proceso si me interesa.|2|
|5|US05|Sección "Sobre Nosotros"|	Como visitante del sitio, quiero conocer la historia y valores del hotel, para tener mayor conexión y confianza con la empresa.|2|
|6|US06|Visualización del Formulario de Registro|Como huésped, quiero ver un formulario de registro bien estructurado, para poder registrarme en el sistema.|2|
|7|US07|Validación de Datos de Registro|Como huésped, quiero que el sistema valide mis datos al registrarme, para evitar errores en mi cuenta.|3|
|8|US08|Configuración de Preferencias de habitación|Como huésped, quiero seleccionar mis preferencias de habitación desde la plataforma web, para personalizar mi estadía.|5|
|9|US09|Personalización de Horarios de Servicio|Como huésped, quiero establecer mis horarios de preferencia para servicios como limpieza o desayuno.|5|
|10|US10|Solicitud de Servicios de Limpieza|Como huésped, quiero solicitar un servicio de limpieza directamente desde la plataforma web, para mantener mi habitación limpia.|3|
|11|US11|Solicitud de Desayuno en la Habitación|Como huésped, quiero poder solicitar un desayuno en mi habitación a través de la plataforma web.|3|
|12|US14|Notificación de solicitud atendida|Como huésped, quiero recibir alertas cuando mi solicitud se atienda, para estar informado.|5|
|13|US16|Enviar evaluación de estadía|Como huésped, quiero calificar mi experiencia al final de la estadía, para dar retroalimentación al hotel.|2|
|14|US18|Visualizar puntos acumulados|Como huésped, quiero ver cuántos puntos de fidelidad tengo, para saber qué recompensas puedo obtener.|3|
|15|US19|Canjear puntos por recompensa|Como huésped, quiero canjear mis puntos por beneficios, para aprovechar el programa de fidelidad.|5|
|16|US20|Cambiar el idioma de la interfaz|Como huésped internacional, quiero cambiar el idioma de la interfaz, para comprender mejor la plataforma web.|2|
|17|US21|Recordar el idioma seleccionado|Como huésped, quiero que la plataforma recuerde mi idioma preferido, para no tener que cambiarlo cada vez.|2|
|18|US22|Iniciar chat con soporte|Como huésped, quiero iniciar un chat con soporte, para resolver dudas rápidamente.|5|
|19|US23|Consultar preguntas frecuentes|Como huésped, quiero revisar preguntas frecuentes, para resolver dudas sin contactar soporte.|2|
|20|US12|Gestión de Solicitudes Pendientes|Como personal administrativo, quiero poder ver las solicitudes pendientes para atenderlas rápidamente.|3|
|21|US13|Modificación de Estado de la Solicitud|	Como personal administrativo, quiero poder cambiar el estado de una solicitud, para gestionarla mejor.|2|
|22|US15|Alerta de emergencia en el hotel|Como personal, quiero recibir alertas inmediatas sobre emergencias, para reaccionar rápido.|5|
|23|US17|Ver historial de evaluaciones|Como personal administrativo, quiero consultar las evaluaciones recibidas, para mejorar la calidad del servicio.|3|
|24|TS01|Modificar preferencias|Como desarrollador, quiero que el sistema guarde los cambios de preferencias de los huéspedes en una base de datos, para tener un registro de sus elecciones.|3|
|25|TS02|Consultar historial de preferencias|Como desarrollador, quiero que el sistema muestre el historial de cambios de preferencias de un huésped, para mejorar la experiencia de usuario basado en sus elecciones pasadas.|3|
|26|TS03|Eliminar preferencias obsoletas|Como desarrollador, quiero que el sistema permita eliminar preferencias antiguas o incorrectas de un huésped, para mantener la base de datos limpia y actualizada.|2|
|27|TS04|Actualización de estado de habitaciones|Como desarrollador, quiero que el sistema permita actualizar el estado de las habitaciones (disponible / ocupado / en mantenimiento), para reflejar la disponibilidad de las reservas.|5|
|28|TS05|Reasignación de habitaciones|Como desarrollador, quiero que el sistema permita reasignar una habitación ocupada a otro huésped, para optimizar el uso de espacios según necesidades cambiantes.|5|
|29|TS06|Consulta de disponibilidad de habitaciones|Como desarrollador, quiero implementar un sistema de consulta de habitaciones disponibles con filtros, para que el personal pueda encontrar rápidamente espacios según filtros específicos.|5|
|30|TS07|Sistema de Registro de Reservas|Como desarrollador, quiero una funcionalidad para almacenar nuevas reservas en la base de datos, para que el sistema pueda gestionar las reservas de los huéspedes.|5|
|31|TS08|Módulo de Modificación de Reservas|Como desarrollador, quiero modificar las reservas existentes, para permitir a los huéspedes ajustar sus reservas según cambios en sus planes.|5|
|32|TS09|Consulta de reservas activas|Como desarrollador, quiero implementar la funcionalidad para consultar reservas activas, para que los huéspedes y administradores puedan ver el estado de las reservas.|3|
|33|TS10|Eliminación Segura de Datos de Usuarios|Como desarrollador, quiero implementar una opción para eliminar todos los datos personales de un usuario, para cumplir con políticas de privacidad.|5|
|34|TS11|Registro de Actividades Sospechosas|Como desarrollador, quiero registrar intentos de acceso fallidos y actividades inusuales, para detectar y responder a posibles brechas de seguridad.|3|
|35|TS12|Implementación de Políticas de Cookies y Consentimiento|Como desarrollador, quiero implementar un sistema de gestión de cookies, para informar a los usuarios y obtener su consentimiento antes de almacenar datos.|3|
|36|TS13|Encriptación de Datos Sensibles en Base de Datos|Como desarrollador, quiero encriptar información sensible del usuario, para mantener la información segura de los usuarios.|5|
|37|TS14|Actualización de Perfiles de Usuario|Como desarrollador, quiero implementar un sistema seguro para actualizar información de perfiles, para que los usuarios puedan modificar sus datos personales y preferencias.|3|
|38|TS15|Gestión de Roles y Permisos|Como desarrollador, quiero crear un sistema de asignación de roles, para controlar accesos y funcionalidades según el tipo de usuario.|5|
|39|TS16|Visualización Condicional de Interfaces|Como desarrollador, quiero adaptar la interfaz según el rol del usuario, para mostrar solo las opciones relevantes a cada perfil.|5|

# Capítulo IV: Product Design
### 4.1.1. General Style Guidelines.

#### **Tipografía (Inter)**
La tipografía elegida para nuestra marca es Inter, por su estilo moderno, funcional y altamente legible. Su diseño limpio se adapta a distintos formatos, tanto digitales como impresos, garantizando una comunicación clara y profesional.

Gracias a su versatilidad, Inter funciona bien en títulos y textos extensos, reflejando los valores de innovación y accesibilidad de nuestra marca. Al ser de código abierto, también refuerza nuestro compromiso con soluciones sostenibles y colaborativas en un entorno digital dinámico.

#### **Colores**
La selección de nuestra paleta de colores para nuestro proyecto responde a una estrategia visual cuidadosamente diseñada para transmitir tecnología, confianza y sofisticación, elementos esenciales en la propuesta de valor de SoftCore.

![Imagen de la paleta de colores del landing page](Assets/img/Chapter%204/Paleta-de-Colores.png)

El color primario, un azul petróleo **(#37474F)**, establece la base visual del sitio y representa atributos como tecnología, profesionalismo y solidez. Este tono transmite autoridad, siendo ideal para productos tecnológicos dirigidos a usuarios que buscan eficiencia y modernidad en sus experiencias digitales.

Como color de acento, se emplea un verde petróleo oscuro **(#00796B)** que comunica estabilidad, frescura y eficiencia. Este tono complementa perfectamente al color primario, añadiendo un contraste equilibrado que dinamiza la interfaz y aporta un toque distintivo a la identidad visual de la aplicación. Su variante más oscura **(#00695C)** se aplica en estados hover, creando una interacción suave y coherente, reforzando la sensación de fluidez y respuesta inmediata en la navegación.

Los fondos claros como el gris azulado **(#ECEFF1)** y el degradado de gris medio a gris claro **(#CFD8DC --> #B0BEC5)** ofrecen una superficie limpia y luminosa, diseñada para mejorar la legibilidad, reducir la fatiga visual y mantener una atmósfera clara y ordenada. Estos colores funcionan como base sobre la cual los componentes interactivos y los bloques de contenido pueden destacar de manera natural, manteniendo siempre una estética elegante y balanceada.

En las secciones inferiores, como el footer, se utiliza un tono grafito elegante **(#263238)** que proporciona un contraste fuerte y ayuda a separar visualmente los contenidos. Este fondo oscuro refuerza la jerarquía visual y da un cierre sólido a la estructura de la página.

El texto principal está diseñado con un gris oscuro neutral **(#2E3C43)**, que garantiza una lectura cómoda, clara y accesible, especialmente en pantallas digitales. Además, se aplican sombras sutiles **(rgba(0, 0, 0, 0.1))** para generar profundidad y separación entre elementos, brindando una interfaz visualmente dinámica sin caer en la saturación.

Finalmente, para situaciones que requieren llamar la atención del usuario, como advertencias o notificaciones importantes, se utiliza un naranja vibrante **(#FB8C00)**. Este color aporta energía y urgencia, destacando eficazmente en contraste con el resto de la paleta, sin comprometer la coherencia estética general.

#### **Lenguaje**
En SoftCore, utilizaremos un lenguaje que refleje nuestra visión y dedicación para transformar la experiencia hotelera mediante tecnología inteligente. Buscamos conectar tanto con huéspedes como con profesionales del sector, manteniendo una comunicación clara, cercana y profesional. La combinación de tonos que emplearemos es la siguiente:

1. **Profesional pero accesible:** Queremos transmitir seriedad y conocimiento en el desarrollo de soluciones tecnológicas aplicadas a la hotelería, sin dejar de ser comprensibles para todos los usuarios. Nuestra comunicación mostrará dominio técnico, pero con un lenguaje claro y cercano que invite a explorar nuestra propuesta sin barreras.
2. **Formal pero cálido:** Aunque mantenemos un tono formal que refleje el compromiso y la confiabilidad de nuestra marca, también nos dirigimos a nuestros usuarios con cercanía. Nuestra intención es establecer una conexión humana y auténtica, transmitiendo confianza y empatía desde el primer contacto.
3. **Respetuoso y empático:** Nos comunicamos con respeto hacia todos nuestros usuarios, reconociendo la diversidad de necesidades de huéspedes, administradores y personal hotelero. Nuestro lenguaje será inclusivo y considerado, promoviendo una relación de colaboración y apoyo constante.
4. **Inspirador y optimista:** En SoftCore creemos que la tecnología puede mejorar profundamente la experiencia de hospedaje. Por ello, hablaremos con entusiasmo y convicción, motivando a nuestros usuarios a imaginar y vivir una nueva forma de hospedarse: más cómoda, personalizada e inteligente.

#### **Branding**
Nuestro logotipo representa de forma clara y minimalista la esencia de CustomHost. En él se aprecia la silueta de un hotel, acompañado por un ícono de señal inalámbrica en la parte superior, simbolizando la conectividad inteligente y el uso de tecnologías dentro de las habitaciones. Este diseño busca transmitir desde el primer vistazo el enfoque tecnológico de nuestro producto, que transforma la experiencia tradicional de hospedaje en una experiencia personalizada y digital.

![Imagen del logo de nuestra startup](Assets/img/Chapter%204/CustomHost-Logo.jpg)

### 4.1.2. Web Style Guidelines.

#### **Descripción General**
Este diseño corresponde a la aplicación web de CustomHost, una plataforma inteligente que permite a los huéspedes personalizar su estadía y a los hoteles optimizar su gestión mediante tecnologías como domótica y biometría. El diseño incluye la pantalla de inicio, la cual mantiene un estilo visual coherente utilizando una paleta de colores sobrios y tecnológicos como el azul petróleo y el verde oscuro. Además, se aplica una tipografía definida que refuerza la imagen moderna y profesional de la marca.
<br>

#### **1. Pantalla de Inicio**
**Header:**
- Logo (esquina superior izquierda).
- Menú de navegación con opciones: Home, SmartStay, About Us y Contact Us.
- Botones "Log In" y "Sign Up".
- Número y correo de contacto.

![Imagen del Header del landing page](Assets/img/Chapter%204/Header.png)
<br>

**Home:**
- Texto de bienvedida a nuestra aplicación web.
- Descripción acerca de lo que se puede hacer en nuestro hotel.

![Imagen de la sección Home del landing page](Assets/img/Chapter%204/Home.png)
<br>

**SmartStay:**
En esta sección se le presenta a los usuarios una introducción visual e informativa de los principales beneficios de usar CustomHost durante su estadía en un hotel inteligente.

![Imagen de la sección SmartStay del landing page](Assets/img/Chapter%204/SmartStay.png)
<br>

**About Us:**
En esta sección se presenta una introducción a la startup SoftCore. Los usuarios conocen quiénes están detrás del proyecto, cuál es su propósito y qué los motiva.

![Imagen de la sección About Us del landing page](Assets/img/Chapter%204/About_Us.png)
<br>

**Contact Us**
En esta sección se presenta un formulario solicitando los datos al usuario como su nombre, su correo y el mensaje que desea enviarnos para poder contactarse con nosotros.

![Imagen de la sección Contact Us del landing page](Assets/img/Chapter%204/Contact_Us.png)
<br>

**Footer**
- El logo junto con correo y numero de contacto.
- Secciones de partes de CustomHost como "Home", “SmartStay”, "About Us" y "Contact Us”.
- Ayuda el usuario como “Preguntas frecuentes”, “Términos de servicio”, Reportar un problema” y “Política de privacidad”.
- Algunos contactos y las redes sociales.

![Imagen del Footer del landing page](Assets/img/Chapter%204/Footer.png)
<br>

## 4.2. Information Architecture.
La arquitectura de información que se emplea en CustomHost está diseñada para ofrecer una navegación fluida y lógica tanto para huéspedes como para personal administrativo de hoteles. Esta estructura permitirá a los usuarios personalizar su experiencia de hospedaje, controlar su entorno y al personal del hotel gestionar de manera eficiente las preferencias y el estado de cada habitación, todo desde una plataforma centralizada.

La arquitectura de información que se emplea en CustomHost está diseñada para ofrecer una navegación fluida y lógica tanto para huéspedes como para personal administrativo de hoteles. Esta estructura permitirá a los usuarios personalizar su experiencia de hospedaje, controlar su entorno y al personal del hotel gestionar de manera eficiente las preferencias y el estado de cada habitación, todo desde una plataforma centralizada.

### 4.2.1. Organization Systems.
*Organización visual del contenido*
Se empleará una estructura jerárquica visual clara en la Landing Page y en cada sección de la plataformaweb. Se priorizará la presentación de información clave como el panel de preferencias del huésped, el estado de las habitaciones, y accesos rápidos a funciones como check-in, control domótico o comunicación con el personal.

### 4.2.2. Labeling Systems.
Estos son los principios de etiquetado aplicados en la plataforma:

*Claridad y simplicidad*
Se emplea un lenguaje accesible para los usuarios, evitando tecnicismos innecesarios en la interfaz del huésped. En el caso del personal técnico y administrativo, se mantienen ciertos términos específicos, especialmente en la gestión de dispositivos inteligentes y mantenimiento.

*Brevedad*
Las etiquetas de botones, menús y opciones se mantienen breves y directas, facilitando la navegación ágil desde cualquier dispositivo.

### 4.2.3. SEO Tags and Meta Tags
- Título: <title> CustomHost | Personaliza tu estadía con tecnología inteligente </title>
- Descripción: <meta name = "description" content = "Plataforma que permite a huéspedes y hoteles personalizar habitaciones con domótica, IoT y acceso biométrico. Vive una experiencia única e inteligente."/>
- Palabras Clave: <meta name = "keyword" content = "Hoteles inteligentes, domótica hotelera, IoT en hoteles, personalización de estadía, check-in digital, habitaciones automatizadas"/>

### 4.2.4. Searching Systems.
Al ingresar, el usuario será recibido con una pantalla de bienvenida donde se encontrará con dos botones en la parte superior derecha, uno para registrarse y otro para inicar sesión. Una vez iniciada la sesión, la navegación dentro de la aplicación estará organizada para facilitar una experiencia fluida e intuitiva.

Los usuarios contarán con una barra de navegación superior que les permitirá acceder fácilmente a las principales funciones. Desde allí podrán personalizar su estadía, controlar su entorno, solicitar ayuda o gestionar su salida del hotel.

La navegación estará reforzada con íconos, etiquetas breves y estados activos visuales, para garantizar que los usuarios siempre sepan dónde están y cómo volver o avanzar en sus acciones.
Al ingresar, el usuario será recibido con una pantalla de bienvenida donde se encontrará con dos botones en la parte superior derecha, uno para registrarse y otro para inicar sesión. Una vez iniciada la sesión, la navegación dentro de la aplicación estará organizada para facilitar una experiencia fluida e intuitiva.

Los usuarios contarán con una barra de navegación superior que les permitirá acceder fácilmente a las principales funciones. Desde allí podrán personalizar su estadía, controlar su entorno, solicitar ayuda o gestionar su salida del hotel.

La navegación estará reforzada con íconos, etiquetas breves y estados activos visuales, para garantizar que los usuarios siempre sepan dónde están y cómo volver o avanzar en sus acciones.

### 4.2.5. Navigation Systems.
Al ingresar al sitio web de CustomHost, el usuario visualizará una barra de navegación fija en la parte superior de la pantalla, la cual facilitará el acceso directo a las secciones más importantes del sitio.

![Imagen del Header del landing page](Assets/img/chapter%204/Header.png)

Esta barra permanecerá visible durante toda la navegación, sin importar la sección visitada, asegurando así un acceso ágil y constante a todos los servicios y recursos que ofrece CustomHost.

## 4.3. Landing Page UI Design.
En esta sección se presentan los diseños correspondientes a nuestra Landing Page, los cuales se encuentran divididos en dos partes: por un lado, los wireframes que muestran una estructura simplificada de la interfaz, y por otro, el mock-up visual que servirá como referencia estética y funcional para el desarrollo final de la página.

### 4.3.1. Landing Page Wireframe.
[Link en Figma]https://www.figma.com/design/3laD7dXkyOejl98KTsmxjj/Aplicaciones-Web?node-id=0-1&t=H1oZeP90awe925yF-1

![Imagen del Wireframe 1](Assets/img/Chapter%204/Wireframe_1.png)
![Imagen del Wireframe 2](Assets/img/Chapter%204/Wireframe_2.png)
![Imagen del Wireframe 3](Assets/img/Chapter%204/Wireframe_3.png)

### 4.3.2. Landing Page Mock-up.
[Link en Figma]https://www.figma.com/design/3laD7dXkyOejl98KTsmxjj/Aplicaciones-Web?node-id=0-1&t=H1oZeP90awe925yF-1

![Imagen del Mock-Up 1](Assets/img/Chapter%204/Mock-Up_1.png)
![Imagen del Mock-Up 2](Assets/img/Chapter%204/Mock-Up_2.png)
![Imagen del Mock-Up 3](Assets/img/Chapter%204/Mock-Up_3.png)


## 4.4. Web Applications UX/UI Design.
### 4.4.1. Web Applications Wireframes.
![Web Aplication Wireframe](/Assets/img/Chapter%204/wireflow-1.jpg)
![Web Aplication Wireframe](/Assets/img/Chapter%204/wireflow-2.jpg)
![Web Aplication Wireframe](/Assets/img/Chapter%204/wireflow-3.jpg)
![Web Aplication Wireframe](/Assets/img/Chapter%204/wireflow-4.jpg)
![Web Aplication Wireframe](/Assets/img/Chapter%204/wireflow-5.jpg)
![Web Aplication Wireframe](/Assets/img/Chapter%204/wireflow-6.jpg)
![Web Aplication Wireframe](/Assets/img/Chapter%204/wireflow-7.jpg)
![Web Aplication Wireframe](/Assets/img/Chapter%204/wireflow-8.jpg)
![Web Aplication Wireframe](/Assets/img/Chapter%204/wireflow-9.jpg)
![Web Aplication Wireframe](/Assets/img/Chapter%204/wireflow-10.jpg)


### 4.4.2. Web Applications Wireflow Diagrams.

![Web Aplication Wireflow](/Assets/img/Chapter%204/wflow1.jpg)
![Web Aplication Wireflow](/Assets/img/Chapter%204/wflow2.jpg)

### 4.4.2. Web Applications Mock-ups.

![Web Aplication Mockup](/Assets/img/Chapter%204/web-application-1.jpg)
![Web Aplication Mockup](/Assets/img/Chapter%204/web-application-2.jpg)
![Web Aplication Mockup](/Assets/img/Chapter%204/web-application-3.jpg)
![Web Aplication Mockup](/Assets/img/Chapter%204/web-application-4.jpg)
![Web Aplication Mockup](/Assets/img/Chapter%204/web-application-5.jpg)
![Web Aplication Mockup](/Assets/img/Chapter%204/web-application-6.jpg)
![Web Aplication Mockup](/Assets/img/Chapter%204/web-application-7.jpg)
![Web Aplication Mockup](/Assets/img/Chapter%204/web-application-8.jpg)
![Web Aplication Mockup](/Assets/img/Chapter%204/web-application-9.jpg)
![Web Aplication Mockup](/Assets/img/Chapter%204/web-application-10.jpg)

### 4.4.3. Web Applications User Flow Diagrams.

![Web Aplication User Flow Diagram](/Assets/img/Chapter%204/USER-FLOW-1.jpg)
![Web Aplication User Flow Diagram](/Assets/img/Chapter%204/USER-FLOW-2.jpg)


## 4.5. Web Applications Prototyping.
[URL del Prototipo (Hecho en figma)](https://https://www.figma.com/design/Rti8LYhQHMeIjsfMIQYIdr/Open-Source?node-id=0-1&p=f&t=XYETOEAUmnls4kjW-0)

## 4.6. Domain-Driven Software Architecture.
### 4.6.1. Software Architecture Context Diagram.
![Context Diagram](Assets/img/Chapter%204/structurizr-101614-SystemContext-001-fixed.png)

   
### 4.6.2. Software Architecture Container Diagrams.
![Container Diagram](Assets/img/Chapter%204/structurizr-101614-Container-001.png)


### 4.6.3. Software Architecture Components Diagrams.
![Components Diagram](Assets/img/Chapter%204/structurizr-101614-Component-001.png)
![Components Diagram](Assets/img/Chapter%204/structurizr-101614-Component-002.png)
![Components Diagram](Assets/img/Chapter%204/structurizr-101614-Component-003.png)
![Components Diagram](Assets/img/Chapter%204/structurizr-101614-Component-004.png)
![Components Diagram](Assets/img/Chapter%204/structurizr-101614-Component-005.png)
![Components Diagram](Assets/img/Chapter%204/structurizr-101614-Component-006.png)

## 4.7. Software Object-Oriented Design.
### 4.7.1. Class Diagrams.

![Class diagram img](Assets/img/chapter-4/class-diagram.png)

[> Click aquí para acceder al diagrama <](https://lucid.app/lucidchart/0b48881b-37af-4d3f-81f0-5c48f44eff2d/edit?invitationId=inv_e14a7c8d-7849-467d-99ab-528f2398e183&page=0_0#)

### 4.7.2. Class Dictionary.

# Class Dictionary

## 1. GuestAggregate
- **Type**: Aggregate Root
- **Description**: Raíz del agregado relacionado con los huéspedes.
- **Relationships**:
  - Contiene `Guest` (1:1).
  - Contiene `Card` (0..1).
  - Contiene `Preference` (0..*).
  - Contiene `ServiceRequest` (0..*).

---

## 2. Guest
- **Type**: Entity
- **Attributes**:
  - `GuestId`: Identity (Identificador único del huésped).
  - `Name`: string (Nombre del huésped).
  - `Email`: string (Correo electrónico del huésped).
  - `CheckInDate`: DateTime (Fecha de entrada).
  - `CheckOutDate`: DateTime (Fecha de salida).
- **Methods**:
  - `CreatePreference(preferenceType, value)`: Crea una nueva preferencia para el huésped.
  - `RequestService(type)`: Solicita un servicio para el huésped.
- **Relationships**:
  - Pertenece a `GuestAggregate`.
  - Tiene `Reservation` (0..*).
  - Tiene `ServiceRequest` (0..*).
  - Tiene `Preference` (0..*).

---

## 3. Card
- **Type**: Entity
- **Attributes**:
  - `CardId`: Identity (Identificador único de la tarjeta).
  - `IsActive`: boolean (Indica si la tarjeta está activa).
- **Methods**:
  - `Activate()`: Activa la tarjeta.
  - `Deactivate()`: Desactiva la tarjeta.
- **Relationships**:
  - Pertenece a `GuestAggregate`.

---

## 4. RoomAggregate
- **Type**: Aggregate Root
- **Description**: Raíz del agregado relacionado con las habitaciones.
- **Relationships**:
  - Contiene `Room` (1:1).
  - Contiene `Reservation` (0..*).

---

## 5. Room
- **Type**: Entity
- **Attributes**:
  - `RoomId`: Identity (Identificador único de la habitación).
  - `Number`: string (Número de la habitación).
- **Methods**:
  - `AssignDevice(device)`: Asigna un dispositivo a la habitación.
- **Relationships**:
  - Pertenece a `RoomAggregate`.
  - Tiene `Reservation` (0..*).
  - Tiene `Device` (0..*).

---

## 6. Reservation
- **Type**: Entity
- **Attributes**:
  - `ReservationId`: Identity (Identificador único de la reserva).
  - `PaymentStatus`: PaymentStatusEnum (Estado de pago de la reserva).
- **Methods**:
  - `UpdatePaymentStatus(status)`: Actualiza el estado de pago de la reserva.
- **Relationships**:
  - Pertenece a `RoomAggregate`.
  - Está relacionada con `Guest` (1:0..*).
  - Está relacionada con `Room` (1:0..*).

---

## 7. StaffAggregate
- **Type**: Aggregate Root
- **Description**: Raíz del agregado relacionado con el personal.
- **Relationships**:
  - Contiene `Staff` (1:1).
  - Contiene `MaintenanceLog` (0..*).

---

## 8. Staff
- **Type**: Entity
- **Attributes**:
  - `StaffId`: Identity (Identificador único del miembro del personal).
  - `Name`: string (Nombre del miembro del personal).
  - `Role`: string (Rol del miembro del personal).
  - `AccessLevel`: AccessLevelEnum (Nivel de acceso del miembro del personal).
- **Methods**:
  - `HandleServiceRequest(request)`: Maneja una solicitud de servicio.
  - `PerformDeviceMaintenance(device, action)`: Realiza mantenimiento en un dispositivo.
- **Relationships**:
  - Pertenece a `StaffAggregate`.
  - Tiene `MaintenanceLog` (0..*).
  - Maneja `ServiceRequest` (0..*).

---

## 9. DeviceAggregate
- **Type**: Aggregate Root
- **Description**: Raíz del agregado relacionado con los dispositivos.
- **Relationships**:
  - Contiene `Device` (1:1).
  - Contiene `StatusLog` (0..*).

---

## 10. Device
- **Type**: Entity
- **Attributes**:
  - `DeviceId`: Identity (Identificador único del dispositivo).
  - `CurrentSetting`: DeviceSetting (Configuración actual del dispositivo).
- **Methods**:
  - `UpdateSetting(setting)`: Actualiza la configuración del dispositivo.
  - `LogStatus(status)`: Registra el estado del dispositivo.
- **Relationships**:
  - Pertenece a `DeviceAggregate`.
  - Está instalado en `Room` (1:0..*).
  - Tiene `DeviceType` (1:1).
  - Tiene `MaintenanceLog` (0..*).
  - Tiene `StatusLog` (0..*).

---

## 11. ServiceRequest
- **Type**: Entity
- **Attributes**:
  - `RequestId`: Identity (Identificador único de la solicitud de servicio).
  - `Type`: string (Tipo de solicitud de servicio).
  - `Status`: RequestStatusEnum (Estado de la solicitud de servicio).
  - `Timestamp`: DateTime (Marca de tiempo de la solicitud).
- **Methods**:
  - `AssignStaff(staff)`: Asigna un miembro del personal a la solicitud.
  - `UpdateStatus(status)`: Actualiza el estado de la solicitud.
- **Relationships**:
  - Pertenece a `GuestAggregate`.
  - Es manejada por `Staff` (0..1).

---

## 12. DeviceType
- **Type**: Value Object
- **Attributes**:
  - `DeviceTypeId`: Identity (Identificador único del tipo de dispositivo).
  - `Name`: string (Nombre del tipo de dispositivo).
- **Relationships**:
  - Está relacionado con `Device` (1:0..*).
  - Aplica a `PreferenceType` (0..*).

---

## 13. PreferenceType
- **Type**: Value Object
- **Attributes**:
  - `PreferenceTypeId`: Identity (Identificador único del tipo de preferencia).
  - `Name`: string (Nombre del tipo de preferencia).
- **Relationships**:
  - Está relacionado con `Preference` (1:0..*).
  - Se aplica a `DeviceType` (0..*).

---

## 14. Preference
- **Type**: Value Object
- **Attributes**:
  - `PreferenceId`: Identity (Identificador único de la preferencia).
  - `Value`: string (Valor de la preferencia).
- **Relationships**:
  - Pertenece a `Guest` (1:0..*).
  - Está relacionado con `PreferenceType` (1:1).

---

## 15. DeviceSetting
- **Type**: Value Object
- **Attributes**:
  - `SettingData`: Map<string, string> (Datos de configuración del dispositivo).
- **Relationships**:
  - Es utilizado por `Device` (1:1).

---

## 16. MaintenanceLog
- **Type**: Value Object
- **Attributes**:
  - `LogId`: Identity (Identificador único del registro de mantenimiento).
  - `Action`: string (Acción realizada durante el mantenimiento).
  - `Timestamp`: DateTime (Marca de tiempo del registro).
- **Relationships**:
  - Es realizado por `Staff` (1:0..*).
  - Es recibido por `Device` (1:0..*).

---

## 17. StatusLog
- **Type**: Value Object
- **Attributes**:
  - `StatusLogId`: Identity (Identificador único del registro de estado).
  - `Status`: string (Estado registrado).
  - `Timestamp`: DateTime (Marca de tiempo del registro).
- **Relationships**:
  - Es registrado por `Device` (1:0..*).

---

## 18. AccessLevelEnum
- **Type**: Enumeration
- **Values**:
  - `BASIC = 1`
  - `INTERMEDIATE = 2`
  - `ADMIN = 3`

---

## 19. RequestStatusEnum
- **Type**: Enumeration
- **Values**:
  - `PENDING`
  - `IN_PROGRESS`
  - `COMPLETED`
  - `CANCELLED`

---

## 20. PaymentStatusEnum
- **Type**: Enumeration
- **Values**:
  - `PENDING`
  - `PAID`
  - `REFUNDED`
  - `CANCELLED`

## 4.8. Database Design.
### 4.8.1. Database Diagram.

![Database diagram img](Assets/img/chapter-4/database-diagram.png)

[> Click aquí para acceder al diagrama <](https://my.vertabelo.com/public-model-view/n0NImX9sR1voJyd33Hr1iawsHgx7swpzz7jOBxA2VjOTE3i8WLuZf64ZQlNCyCLB?x=2736&y=2923&zoom=0.4375)
# Capítulo V: Product Implementation, Validation & Deployment
En este último capítulo, nos centraremos en la implementación, validación y despliegue de nuestro proyecto. Al igual que explicar los puntos y pasos necesarios que hemos tomado para lograr su realización.
## 5.1. Software Configuration Management.
Durante el desarrollo del proyecto utilizaremos las siguientes convenciones o reglas para mantener consistencia en todo momento:
|Contexto|Convención|
|-|-|
|Nombre de archivos|Todos los archivos tendrán nombres en minúscula, sin espacios, usando kebab-case.|
|Convenciones de nomenclatura| Variables y funciones: lowerCamelCase; clases y componentes: PascalCase; constantes: UPPER_SNAKE_CASE; archivos: kebab-case.|
|Estructura del código|Usar estructura modular siguiendo el patrón feature/module, con carpetas como components/, assets/, pages/, services/, etc. Separar por responsabilidades.|
|Estilo de codificación|Seguir las reglas de ESLint y Prettier: Sangría de 2 espacios; comillas simples; punto y coma obligatorio; y orden alfabético en CSS.|
|Documentación|Comentar solo en funciones complejas o integraciones externas. Usar formato descripción y mantener el README.md claro y actualizado.|
|Control de versiones|GitHub Flow: ramas por feature, uso de Pull Requests, revisiones antes de merge. Formato de commits: feat, fix, chore, etc.|
|Gestión de dependencias|	Usar npm. Mantener package.json ordenado y actualizado. Preferir dependencias estables y con comunidad activa. Ejecutar npm audit regularmente.|
|Convenciones de prueba|Tests en archivos .spec.js si aplica. Enfoque en pruebas visuales/manuales en componentes clave como BookingForm, RoomCard, ServiceRequest.|
|Convenciones de seguridad|Validación de entradas en frontend. Autenticación vía tokens (JWT). No incluir secretos en el código. Usar sanitización para evitar XSS.|
|Convenciones de colaboración| Comunicación por Discord o Teams. Gestión en Trello o GitHub Projects. Documentar avances, pedir feedback constante y promover buenas prácticas. |
### 5.1.1. Software Development Environment Configuration.
|Producto|Descripción|Próposito de Uso
|-|-|-|
|Rider (JetBrains)|Entorno de desarrollo especializado en .NET, ideal para construir aplicaciones robustas de escritorio, móviles y servicios web.|Se emplea para el desarrollo de WebServices en C# y tecnología .NET, aprovechando su rendimiento, seguridad y compatibilidad multiplataforma.|
|MySQL|Sistema de gestión de bases de datos relacional, de código abierto y ampliamente soportado.|Brinda una base de datos confiable para manejar reservas, huéspedes, dispositivos y servicios del hotel, con capacidad de gestión local o en la nube.|
|Postman	|Plataforma de colaboración para pruebas de APIs REST. Permite simular, probar y documentar endpoints rápidamente.|Ideal para probar servicios de la web como reservas, preferencias de usuario, solicitudes de habitación y más.|
|Git|Sistema de control de versiones distribuido, esencial para llevar un historial organizado del desarrollo del software.|Administra cambios en el código, facilita el trabajo colaborativo y permite restaurar versiones anteriores si se requiere.|
### 5.1.2. Source Code Management.
El gitjab donde tengamos el proyecto
### 5.1.3. Source Code Style Guide & Conventions.
Que usamos con css (en caso usemos software para SASS)
supongo q tmbn cositas de como hacemo el code capas algun tipo de codigo para comunicarse entre comments
### 5.1.4. Software Deployment Configuration.
Configuraciones de donde y como deployeamos el proyecto
## 5.2. Landing Page, Services & Applications Implementation.
### 5.2.1. Sprint 1
#### 5.2.1.1. Sprint Planning 1.
A continuación, se presentará el sprint planning 1 donde se mostrarán las evidencias de planificación e implementación
del landing page.

**Sprint Backlog 1**
<table>
    <thead>
        <tr>
            <th> Sprint #</th>
            <th> Sprint 1</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td style="font-weight: bold; text-align: center" colspan="2"> Sprint Planing Background</td>
        </tr>
        <tr>
            <td style="font-weight: bold;"> Date</td>
            <td> 15/04/2024 </td>
        </tr>
        <tr>
            <td style="font-weight: bold;"> Time</td>
            <td> 17:00 horas (GMT-5)</td>
        </tr>
        <tr>
            <td style="font-weight: bold;"> Location</td>
            <td> Modalidad remota por Discord.
            <td>
        </tr>
        <tr>
            <td style="font-weight: bold;"> Prepared By</td>
            <td> Softcore team
            <td>
        </tr>
        <tr>
            <td style="font-weight: bold;"> Attendees (to planning meeting)</td>
            <td> Todos los miembros del equipo Softcore.
            <td>
        </tr>
        <tr>
            <td style="font-weight: bold;"> Sprint n – 0 Review Summary</td>
            <td> Debido a que es el primer sprint que se ha hecho, no existen sprints pasados a este.
            <td>
        </tr>
        <tr>
            <td style="font-weight: bold;"> Sprint n – 1 Retrospective Summary</td>
            <td>
        Durante este sprint, se creó el landing page empleando HTML, CSS y JavaScript. También se abordaron las conversaciones sobre el contenido textual que se integró en el landing page, así como el diseño previamente establecido en Figma. Al finalizar este sprint, el landing page se subió a GitHub Pages , permitiendo que cualquier usuario pueda acceder y visualizar la página a través del enlace proporcionado. Además, se realizaron pruebas exhaustivas para asegurar que el sitio esté completamente funcional y se vea correctamente en cualquier dispositivo, garantizando una experiencia óptima tanto en computadoras de escritorio como en tablets y teléfonos móviles.
            <td>
        </tr>
        <tr>
            <td style="font-weight: bold; text-align: center" colspan="2"> Sprint Goal & User Stories</td>
        </tr>
        <tr>
            <td style="font-weight: bold;"> Sprint 1 Velocity</td>
            <td> 14
            <td>
        </tr>
        <tr>
            <td style="font-weight: bold;"> Sum of Story Points</td>
            <td> 14
            <td>
        </tr>
    </tbody>
</table>

#### 5.2.1.2. Sprint Backlog 1.

![SprintBacklog n](/Assets/img/Chapter-5/sprint-backlog.jpg)

#### 5.2.1.3. Development Evidence for Sprint Review.

#### 5.2.1.4. Testing Suite Evidence for Sprint Review.
Al ser un landing page, no se requiere de una suite de pruebas para su desarrollo.
#### 5.2.1.5. Execution Evidence for Sprint Review.
Sprint 1: En este entregable, hemos logrado desarrollar la Landing Page para nuestra StartUp Sweet Manager. El link de la Landing Page es el siguiente: https://softcore-app-web-1asi0730-2510-4395.github.io/CustomHost/.
#### 5.2.1.6. Services Documentation Evidence for Sprint Review.
En este sprint se cumplió el objetivo de desarrollar la Landing Page; sin embargo, al ser Landing Page no requiere de documentación relacionada a Web Services
#### 5.2.1.7. Software Deployment Evidence for Sprint Review.
En este sprint, se completó el desarrollo del landing page y se utilizó un conjunto de herramientas para su despliegue:

- Git: Utilizado como sistema de control de versiones para facilitar el trabajo en equipo durante el desarrollo del landing page.
- GitFlow: Implementado como flujo de trabajo para gestionar el progreso individual de cada miembro del equipo en el desarrollo del landing page.
- GitHub: Empleado como plataforma colaborativa para almacenar las versiones del proyecto y facilitar el desarrollo conjunto del equipo.
- Github pages: Utilizado como plataforma para automatizar la hospedaje y despliegue del landing page, especialmente diseñada para sitios web estáticos.

#### 5.2.1.8. Team Collaboration Insights during Sprint.
El equipo desarrolló el sistema de gestión hotelera utilizando una estrategia basada en ramas para cada componente o funcionalidad. Esta metodología permitió que cada miembro del equipo trabajara de forma independiente en elementos como la página de inicio, el selector de idioma, la gestión de peticiones y el panel de administración, sin interferir con el trabajo de los demás. Una vez finalizada cada funcionalidad, se verificó que no existieran conflictos con la rama principal (main) y se generó una pull request para integrar los cambios de forma controlada. A continuación, se adjunta una imagen que evidencia la colaboración del equipo en GitHub.
![Sprint review Team Collaboration Insights](/Assets/img/Chapter-5/collabInsight.png) 


# Bibliografía
qoomon. (2021, 11 enero). Conventional Commit Messages. Gist.
Recuperado 20 de junio de 2022, de [LINK](https://gist.github.com/qoomon/5dfcdf8eec66a051ecd85625518cfd13)

LeaseIN. (2018). Importancia de contar con un equipo de soporte
técnico. [Entrada en blog]. Recuperado de:
[LINK](https://leasein.pe/blog/branding-empresarial-importanciasoporte-tecnico/)
``` 
formato

"Apellido", Ini.Ciales. & "otroAutor", O.A. (año). titulo del articulo.
        "nombre del articulo o lo q sea, Volumen(si es que tiene), numero  de pagina"#-#. https//link.org/eeeseneko

```
# Anexos

video 1: [https://upcedupe-my.sharepoint.com/:v:/g/personal/u202317362_upc_edu_pe/ETQAkMt6M7VHppn0V_2yowMB4lImpb1OLwaovBnNoPKKhg?e=qYLctj&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D](https://upcedupe-my.sharepoint.com/:v:/g/personal/u202317362_upc_edu_pe/ETQAkMt6M7VHppn0V_2yowMB4lImpb1OLwaovBnNoPKKhg?e=qYLctj&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D)

video 2: [https://upcedupe-my.sharepoint.com/:v:/g/personal/u202317362_upc_edu_pe/EW8bbyowHHNGvrGNiIjfFlwB-Q3bTBRaSvZlTXGKRC2L7w?e=R9zBK3&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D](https://upcedupe-my.sharepoint.com/:v:/g/personal/u202317362_upc_edu_pe/EW8bbyowHHNGvrGNiIjfFlwB-Q3bTBRaSvZlTXGKRC2L7w?e=R9zBK3&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D)

video 3: [https://upcedupe-my.sharepoint.com/:v:/g/personal/u202317362_upc_edu_pe/EdDQjdiPjQ9JlAtkH5yDuhgBZcXkH52f6WubG0DGugxiYw?e=RGPOHp&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D](https://upcedupe-my.sharepoint.com/:v:/g/personal/u202317362_upc_edu_pe/EdDQjdiPjQ9JlAtkH5yDuhgBZcXkH52f6WubG0DGugxiYw?e=RGPOHp&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D)

video 4: [https://upcedupe-my.sharepoint.com/:v:/g/personal/u202317362_upc_edu_pe/ETgSUSNEantAraWk1atoAa4BjISZsufjnztzz_iJVxGXAg?e=oxnXyR&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D](https://upcedupe-my.sharepoint.com/:v:/g/personal/u202317362_upc_edu_pe/ETgSUSNEantAraWk1atoAa4BjISZsufjnztzz_iJVxGXAg?e=oxnXyR&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D)

video 5: [https://upcedupe-my.sharepoint.com/personal/u202317362_upc_edu_pe/_layouts/15/stream.aspx?id=%2Fpersonal%2Fu202317362%5Fupc%5Fedu%5Fpe%2FDocuments%2FSegmento%201%20%2D%20Luis%20Cordova%2Emp4&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0&ga=1&referrer=StreamWebApp%2EWeb&referrerScenario=AddressBarCopied%2Eview%2Ee82cd9e2%2D078e%2D4cb0%2D80cf%2D3200ebfdab04](https://upcedupe-my.sharepoint.com/personal/u202317362_upc_edu_pe/_layouts/15/stream.aspx?id=%2Fpersonal%2Fu202317362%5Fupc%5Fedu%5Fpe%2FDocuments%2FSegmento%201%20%2D%20Luis%20Cordova%2Emp4&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0&ga=1&referrer=StreamWebApp%2EWeb&referrerScenario=AddressBarCopied%2Eview%2Ee82cd9e2%2D078e%2D4cb0%2D80cf%2D3200ebfdab04)

video 6: [https://upcedupe-my.sharepoint.com/:v:/g/personal/u202317362_upc_edu_pe/EU9qNutqfIdAlN0FVSU5avIBOmL9Y3mwIx2kCBAuGyURhw?e=Vb6lwq&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D](https://upcedupe-my.sharepoint.com/:v:/g/personal/u202317362_upc_edu_pe/EU9qNutqfIdAlN0FVSU5avIBOmL9Y3mwIx2kCBAuGyURhw?e=Vb6lwq&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D)

video 7: [https://upcedupe-my.sharepoint.com/:v:/g/personal/u202317362_upc_edu_pe/EY3QHbePejVFhy4Lxa49_84BAwjrm9Pk8aQZWCyGwuz63Q?e=BSpEnp&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D](https://upcedupe-my.sharepoint.com/:v:/g/personal/u202317362_upc_edu_pe/EY3QHbePejVFhy4Lxa49_84BAwjrm9Pk8aQZWCyGwuz63Q?e=BSpEnp&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D)






