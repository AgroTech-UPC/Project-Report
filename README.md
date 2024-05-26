﻿<p align="center">
  <img src="img/image1.png" alt="Logo de UPC" width="100%">
</p>

<div align="center">

# <span style="color:red">**Universidad Peruana de Ciencias Aplicadas**</span>
## Carrera de Ingeniería de Software

Ciclo: 2024 - 1

Curso: Desarrollo de Aplicaciones Open Source

Sección: WX52

Profesor: Elio Jefferrson Navarrete Vilca

“Informe de Trabajo Final"

Startup: AgroTech

Producto: AgroConnect

Grupo: 1

|          Integrantes          |      Código      |
|:-----------------------------:|:-------------------:|
|   Delgado Corrales, Piero Gonzalo   |    U202210749    |
|  Lucas Coronel, Nadia Alessandra   |    U202120430    |
|   Paredes Puente, Sebastián Roberto  |    U202217239    |
|  Salinas Torres, Salvador Antonio   |    U20221B127    |
|   Valverde Mozo, Andre Gabriel   |    U202218899    |

Mayo 2024

</div>


# Registro de versiones

<table>
  <thead>
    <tr>
        <th>Versión</th>
        <th>Fecha</th>
        <th>Autor</th>
        <th>Descripción de modificación</th>
    </tr>
  </thead>
  <tbody>
  <tr>
      <td><strong>TB1</strong></td>
      <td>Sábado 13 de Abril</td>
      <td>
        <ul>
          <li>Delgado Corrales, Piero Gonzalo</li>
          <li>Lucas Coronel, Nadia Alessandra</li>
          <li>Paredes Puente, Sebastián Roberto</li>
          <li>Salinas Torres, Salvador Antonio</li>
          <li>Valverde Mozo, Andre Gabriel</li>
        </ul>
      </td>
      <td>
        Se han incluído los siguientes capítulos:
        <ul>
          <li>Capítulo I: Introducción</li>
          <li>Capítulo II: Requirements Elicitation & Analysis</li>
          <li>Capítulo III: Requirements Specification</li>
          <li>Capítulo IV: Product Design</li>
          <li>Avance del Capítulo V: Product Implementation, Validation & Deployment hasta el punto 5.2.1.8</li>
          <li>Avance de Conclusiones, Bibliografía y Anexos</li>
        </ul>
      </td>
  </tr>
  <tr>
  <td><strong>TP1</strong></td>
      <td>Viernes 3 de Mayo</td>
      <td>
        <ul>
          <li>Delgado Corrales, Piero Gonzalo</li>
          <li>Lucas Coronel, Nadia Alessandra</li>
          <li>Paredes Puente, Sebastián Roberto</li>
          <li>Salinas Torres, Salvador Antonio</li>
          <li>Valverde Mozo, Andre Gabriel</li>
        </ul>
      </td>
      <td>
        <li>Correcciones levantadas.</li>
        <li>Avance del punto 5.2.2. Sprint 2.</li>
      </td>
  </tr>
    <td><strong>TB2</strong></td>
      <td>Sabado 8 de Mayo</td>
      <td>
        <ul>
          <li>Delgado Corrales, Piero Gonzalo</li>
          <li>Lucas Coronel, Nadia Alessandra</li>
          <li>Paredes Puente, Sebastián Roberto</li>
          <li>Salinas Torres, Salvador Antonio</li>
          <li>Valverde Mozo, Andre Gabriel</li>
        </ul>
      </td>
      <td>
        <li>Correcciones levantadas.</li>
        <li>Desarrollo del Sprint 3.</li>
        <li>Creación del Video About-The-Product.</li>
        <li>Implementación de entrevistas de validación</li>
        <li>Desarrollo de evaluación por heurísticas</li>
        <li>Avance de Conclusiones y Anexos</li>
      </td>
  </tr>
  </tbody>
</table>

# **Project Report Collaboration Insights**
URL Project Report (Github): https://github.com/AgroTech-UPC/Project-Report

Commits en el project report de la TB1:

<img src="img/commits-tb1.png">

<img src="img/commits-tb1_detailed1.png">
<img src="img/commits-tb1_detailed2.png">
<img src="img/commits-tb1_detailed3.png">

Commits en el project report de la TP1:

<img src="img/team-collaboration-tp1.png">
<img src="img/commits-tp1-1.png">
<img src="img/commits-tp1-2.png">

# **Tabla de Contenido**

- [Registro de Versiones](#registro-de-versiones)
- [Student Outcome](#student-outcome)
- [Capítulo I: Introducción](#Capítulo-I-Introducción)
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
- [Capítulo II: Requirements Elicitation & Analysis](#Capítulo-II-Requirements-Elicitation--Analysis)
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
    - [2.3.5. As-is Scenario Mapping](#235-as-is-scenario-mapping)
  - [2.4. Ubiquitous Language](#24-ubiquitous-language)
- [Capítulo III: Requirements Specification](#Capítulo-III-Requirements-Specification)
  - [3.1. To-Be Scenario Mapping](#31-to-be-scenario-mapping)
  - [3.2. User Stories](#32-user-stories)
  - [3.3. Impact Mapping](#33-impact-mapping)
  - [3.4. Product Backlog](#34-product-backlog)
- [Capítulo IV: Product Design](#Capítulo-IV-Product-Design)
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
    - [4.4.3. Web Applications Mock-ups](#443-web-applications-mock-ups)
    - [4.4.4. Web Applications User Flow Diagrams](#444-web-applications-user-flow-diagrams)
  - [4.5. Web Applications Prototyping](#45-web-applications-prototyping)
  - [4.6. Domain-Driven Software Architecture](#46-domain-driven-software-architecture)
    - [4.6.1. Software Architecture Context Diagram](#461-software-architecture-context-diagram)
    - [4.6.2. Software Architecture Container Diagrams](#462-software-architecture-container-diagrams)
    - [4.6.3. Software Architecture Components Diagrams](#463-software-architecture-components-diagrams)
  - [4.7. Software Object-Oriented Design](#47-software-object-oriented-design)
    - [4.7.1. Class Diagrams](#471-class-diagrams)
    - [4.7.2. Class Dictionary](#472-class-dictionary)
  - [4.8. Database Design](#48-database-design)
    - [4.8.1. Database Diagram](#481-database-diagram)
- [Capítulo V: Product Implementation, Validation & Deployment](#Capítulo-V-Product-Implementation-Validation--Deployment)
  - [5.1. Software Configuration Management](#51-software-configuration-management)
    - [5.1.1. Software Development Environment Configuration](#511-software-development-environment-configuration)
    - [5.1.2. Source Code Management](#512-source-code-management)
    - [5.1.3. Source Code Style Guide & Conventions](#513-source-code-style-guide--conventions)
    - [5.1.4. Software Deployment Configuration](#514-software-deployment-configuration)
  - [5.2. Landing Page, Services & Applications Implementation](#52-landing-page-services--applications-implementation)
    - [5.2.1. Sprint 1](#521-sprint-1)
      - [5.2.1.1. Sprint Planning 1](#5211-sprint-planning-1)
      - [5.2.1.2. Sprint Backlog 1](#5212-sprint-backlog-1)
      - [5.2.1.3. Development Evidence for Sprint Review](#5213-development-evidence-for-sprint-review)
      - [5.2.1.4. Testing Suite Evidence for Sprint Review](#5214-testing-suite-evidence-for-sprint-review)
      - [5.2.1.5. Execution Evidence for Sprint Review](#5215-execution-evidence-for-sprint-review)
      - [5.2.1.6. Services Documentation Evidence for Sprint Review](#5216-services-documentation-evidence-for-sprint-review)
      - [5.2.1.7. Software Deployment Evidence for Sprint Review](#5217-software-deployment-evidence-for-sprint-review)
      - [5.2.1.8. Team Collaboration Insights during Sprint](#5218-team-collaboration-insights-during-sprint)
    - [5.2.2. Sprint 2](#522-sprint-2)
      - [5.2.2.1. Sprint Planning 2](#5221-sprint-planning-2)
      - [5.2.2.2. Sprint Backlog 2](#5222-sprint-backlog-2)
      - [5.2.2.3. Development Evidence for Sprint Review](#5223-development-evidence-for-sprint-review)
      - [5.2.2.4. Testing Suite Evidence for Sprint Review](#5224-testing-suite-evidence-for-sprint-review)
      - [5.2.2.5. Execution Evidence for Sprint Review](#5225-execution-evidence-for-sprint-review)
      - [5.2.2.6. Services Documentation Evidence for Sprint Review](#5226-services-documentation-evidence-for-sprint-review)
      - [5.2.2.7. Software Deployment Evidence for Sprint Review](#5227-software-deployment-evidence-for-sprint-review)
      - [5.2.2.8. Team Collaboration Insights during Sprint](#5228-team-collaboration-insights-during-sprint)
    - [5.2.3. Sprint 3](#523-sprint-3)
      - [5.2.3.1. Sprint Planning 3](#5231-sprint-planning-3)
      - [5.2.3.2. Sprint Backlog 3](#5232-sprint-backlog-3)
      - [5.2.3.3. Development Evidence for Sprint Review](#5233-development-evidence-for-sprint-review)
      - [5.2.3.4. Testing Suite Evidence for Sprint Review](#5234-testing-suite-evidence-for-sprint-review)
      - [5.2.3.5. Execution Evidence for Sprint Review](#5235-execution-evidence-for-sprint-review)
      - [5.2.3.6. Services Documentation Evidence for Sprint Review](#5236-services-documentation-evidence-for-sprint-review)
      - [5.2.3.7. Software Deployment Evidence for Sprint Review](#5237-software-deployment-evidence-for-sprint-review)
      - [5.2.3.8. Team Collaboration Insights during Sprint](#5238-team-collaboration-insights-during-sprint)
  - [5.3. Validation Interviews](#53-validation-interviews)
    - [5.3.1. Diseño de Entrevistas](#531-diseño-de-entrevistas)
    - [5.3.2. Registro de Entrevistas](#532-registro-de-entrevistas)
    - [5.3.3. Evaluaciones según heurísticas](#533-evaluaciones-según-heurísticas)
  - [5.4. Video About-the-Product](#54-video-about-the-product)
- [Conclusiones](#conclusiones)
  - [Conclusiones y recomendaciones](#conclusiones-y-recomendaciones)
- [Video About-the-Team](#video-about-the-team)
- [Bibliografía](#bibliografía)
- [Anexos](#anexos)



# Student Outcome

ABET – EAC - Student Outcome 3

Criterio: Capacidad de comunicarse efectivamente con un rango de audiencias

<table>
  <thead>
    <tr>
      <th><strong>Criterio específico</strong></th>
      <th><strong>Acciones realizadas</strong></th>
      <th><strong>Conclusiones</strong></th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Comunica oralmente sus ideas y/o resultados con objetividad a público de diferentes especialidades y niveles jerárquicos, en el marco del desarrollo de un proyecto en ingeniería.</td>
      <td>
        <p><strong>Delgado Corrales, Piero Gonzalo</strong></p>
        <p><strong>TB1:</strong></p>
        <p>En esta primera entrega, se desarrolló la idea de negocio. Para lograr esto, en lo personal tuve que realizar entrevista a un criador de cuyes para obtener mayores especificaciones sobre el problema a tratar. Del mismo modo, comunique oralmente las ideas del diseño de la aplicación web y de los diagramas de arquitectura de software mediante el proyecto.</p>
        <p><strong>TP1:</strong></p>
        <p>Para este entregable, se desarrolló el sprint 2 el cual se enfocó en el desarrollo del frontend. Dichos cambios se comunicaron oralmente mediante el video del proyecto. Además, realicé una entrevista a un asesor para tener una mayor información sobre el alcance de nuestro proyecto.</p>
        <p><strong>Lucas Coronel, Nadia Alessandra</strong></p>
        <p><strong>TB1:</strong></p>
        <p>Se enfocó principalmente en el diseño y desarrollo del producto, destacando el diseño de la landing page, guías de estilo, historias de usuario y la base de datos. Se priorizó que el diseño fuera intuitivo y atractivo para los usuarios, mientras cumplía con los requisitos. Esta labor fue fundamental para garantizar que el producto final satisficiera las necesidades de los usuarios y las demandas del mercado de manera efectiva.</p>
        <p><strong>TP1:</strong></p>
        <p>Durante este entregable, nuestro enfoque se centró en mejorar el diseño de la página de inicio (landing page) del proyecto. Con el objetivo de garantizar la eficacia y la coherencia visual, se implementaron cambios significativos que se alinean con las mejores prácticas de diseño web. Además, se completó con éxito las tareas asignadas durante el segundo sprint del proyecto. Estas incluyeron el desarrollo del front-end, la implementación de la API y la integración exitosa del front-end con el backend.</p>
        <p><strong>Paredes Puente, Sebastián Roberto</strong></p>
        <p><strong>TB1:</strong></p>
        <p>Se puso especial énfasis en el diseño y desarrollo del producto, concentrándose en la sección “Acerca de” de la landing page, user stories, user personas y scenario mapping. Esta labor fue esencial para asegurar que el producto final cumpliera efectivamente con las necesidades de los usuarios, al delimitar las user stories, y las exigencias del mercado. Además, se llevó a cabo una investigación inicial para conocer opiniones de algunos expertos en el tema, por ello se realizó entrevistas con personas clave de nuestros segmentos objetivo, lo que facilitó el trabajo en equipo y el avance del proyecto.</p>
        <p><strong>TP1:</strong></p>
        <p>Durante este entregable, nuestro enfoque se centró en mejorar el diseño de la landing page del proyecto, implementando ciertas mejoras como adicionar información y hacer que se vea visualmente más estético y llamativo. Además, se completaron con éxito las tareas asignadas durante el segundo sprint, que incluyeron el desarrollo del front-end y la implementación de la API. Para comunicar estos cambios, se realizaron un total de 9 entrevistas a nuestros segmentos objetivos, para obtener más información sobre el alcance del proyecto en una próxima entrega.</p>
        <p><strong>Salinas Torres, Salvador Antonio</strong></p>
        <p><strong>TB1:</strong></p>
        <p>En este primer avance, primero identificamos la problemática y realizamos la investigación necesaria para identificar los requisitos que nuestra aplicación final abarca. Para ello, realizamos entrevistas de forma oral con personas de nuestros segmentos objetivo para conocer sus principales necesidades y ponernos un poco mejor en su perspectiva. Gracias a estas, es que el desarrollo del trabajo fue fluido, ya que luego en grupo nos reunimos y fuimos avanzando, realizando recomendaciones y resolviendo dudas sobre nuestros objetivos como startup.</p>
        <p><strong>TP1:</strong></p>
        <p>Para este avance nos enfocamos en mejorar un poco más la investigación del mercado a partir de los comentarios brindados por el profesor. De este modo, realicé una entrevista más para obtener una perspectiva más a tomar en cuenta en el segmento objetivo. Igualmente, realizamos mejoras en el Landing Page, para lo cual realizamos una videoconferencia para conversar en grupo y compartir ideas sobre los siguientes pasos.</p>
        <p><strong>Valverde Mozo, Andre Gabriel</strong></p>
        <p><strong>TB1:</strong></p>
        <p>En la fase inicial, investigamos a fondo las necesidades de nuestros usuarios mediante entrevistas directas. Esto facilitó el progreso del trabajo en equipo al ofrecer recomendaciones y aclarar dudas. Luego, nos centramos en el diseño y desarrollo del producto, priorizando un diseño intuitivo y atractivo que cumpliera con los requisitos establecidos y satisficiera las demandas del mercado.</p>
        <p><strong>TP1:</strong></p>
        <p>En el segundo sprint, nos enfocamos en profundizar nuestro conocimiento de Angular y completar tareas clave para mejorar el front-end de nuestra aplicación. Paralelamente, ajustamos el diseño de la página principal y consideramos comentarios del profesor para una mejor comprensión del mercado y las preferencias de nuestros usuarios.</p>
      </td>
      <td>
        <p><strong>TB1:</strong></p>
        <p>En conclusión, a través de un enfoque meticuloso, nos aseguramos de definir claramente los requisitos del proyecto, crear un diseño robusto y funcional, llevar a cabo un desarrollo cuidadoso y exhaustivo, y realizar pruebas rigurosas para garantizar la calidad y fiabilidad del producto. Parte de este proceso de definición fueron las entrevistas en las cuales nos comunicamos con nuestros segmentos objetivo para definir mejor la problemática y las funcionalidades que ayudarán a solucionarla. Estos hallazgos se vieron reflejados en la exposición del primer avance donde explicamos a detalle todos los aspectos desarrollados durante la primera entrega.</p>
        <p><strong>TP1:</strong></p>
        <p>En resumen, durante esta etapa del proyecto, implementamos las mejoras sugeridas por el profesor, las cuales incluyeron la adición de más historias técnicas y la mejora del diseño de la landing page siguiendo buenas prácticas. Además, todos los integrantes del equipo completaron con éxito todas las actividades asignadas en el segundo sprint. Este progreso se refleja claramente en el tablero de Trello correspondiente al sprint.</p>
      </td>
    </tr>
    <tr>
      <td>Comunica en forma escrita ideas y/o resultados con objetividad a público de diferentes especialidades y niveles jerárquicos, en el marco del desarrollo de un proyecto en ingeniería.</td>
      <td>
        <p><strong>Delgado Corrales, Piero Gonzalo</strong></p>
        <p><strong>TB1:</strong></p>
        <p>Durante esta primera entrega, comunique de forma escrita mis ideas mediante la realización del informe del trabajo en Github con el lenguaje Markdown. Asimismo, mostré los resultados de las entrevistas mediante tablas y gráficos que mostraban con objetividad los hallazgos obtenidos.</p>
        <p><strong>TP1:</strong></p>
        <p>Para esta entrega, comunique de forma escrita las mejoras realizadas a los diagramas de domain driven design y del diseño de la base de datos en el informe del trabajo. Del mismo modo, con los cambios realizados al landing page se pudo expresar de mejor manera nuestras funcionalidades y alcances a los segmentos objetivos.</p>
        <p><strong>Lucas Coronel, Nadia Alessandra</strong></p>
        <p><strong>TB1:</strong></p>
        <p>Se facilitó una comunicación clara y precisa sobre el diseño y desarrollo del producto a través de diferentes áreas, incluyendo el diseño de las guías de estilo, las historias de usuario y el diseño de la base de datos. Esta comunicación efectiva fue esencial para mantener informados a todos los miembros del equipo, independientemente de su nivel de experiencia técnica, y promovió una colaboración exitosa.</p>
        <p><strong>TP1:</strong></p>
        <p>En este entregable, se enfocó en mejorar el diseño de la landing page,  lo cual implicó la revisión de la estructura y el contenido para optimizar la experiencia del usuario. Asimismo, se brindó apoyo en la gestión y organización del proyecto a través de la plataforma Trello, contribuyendo a la creación y actualización de tableros, asignación de tareas y seguimiento del progreso del equipo. Además, se culminó con éxito las tareas del segundo sprint, estas incluyen colaborar en el desarrollo del front-end, la implementación de la API y la integración del front-end con el backend.</p>
        <p><strong>Paredes Puente, Sebastián Roberto</strong></p>
        <p><strong>TB1:</strong></p>
        <p>Me concentré en comunicar mis ideas y avances a través de un informe escrito, lo cual resultó fundamental para transmitir claramente los detalles del diseño y desarrollo del producto. Durante esta etapa, me esforcé por documentar cuidadosamente cada paso del proceso utilizando lenguaje Markdown, asegurando así un informe completo y fácil de entender.</p>
        <p><strong>TP1:</strong></p>
        <p>Durante el desarrollo para esta entrega, se puso énfasis en abordar los puntos a mejorar en el feedback del trabajo anterior, como lo fueron el mejorar la redacción de algunas user stories, a su vez, agregar más user stories técnicas. Además, se desarrolló el Frontend de la aplicación web mediante el uso de Angular como framework y una API fake en formato JSON para simular la gestión de datos, la cuál se estuvo probando para su correcto funcionamiento.</p>
        <p><strong>Salinas Torres, Salvador Antonio</strong></p>
        <p><strong>TB1:</strong></p>
        <p>Durante el desarrollo de este primer sprint, realice la documentación de forma escrita con todos los puntos requeridos a lo largo del proyecto. Así como establecer las convenciones de estilo y configuración de sistema de software, los cuales son importantes ya que de estos es que se basará el desarrollo del proyecto hasta su fin.</p>
        <p><strong>TP1:</strong></p>
        <p>Este avance parcial se enfocó principalmente en subsanar los comentarios brindados por el profesor así como en la redacción de las historias de usuario, y en la realización del Frontend de la aplicación web utilizando como framework Angular y fake API en json para simular la gestión de datos.</p>
        <p><strong>Valverde Mozo, Andre Gabriel</strong></p>
        <p><strong>TB1:</strong></p>
        <p>Al inicio del proyecto, me concentré en comunicar mis ideas y avances a través del informe escrito. Este informe fue esencial para transmitir claramente los detalles del diseño y desarrollo del producto, asegurando que todos los miembros del equipo estuvieran al tanto de nuestros progresos y facilitando una colaboración efectiva. Durante esta etapa, me esforcé por documentar cuidadosamente cada paso del proceso, garantizando un registro completo y accesible para todos los involucrados en el proyecto.</p>
        <p><strong>TP1:</strong></p>
        <p>En este avance parcial, nos enfocamos en mejorar la redacción de user stories, subsanar comentarios del profesor, y desarrollar el Frontend de la aplicación web utilizando Angular y una API fake en JSON. Buscamos también entender mejor las necesidades de nuestros usuarios potenciales, asegurando una buena experiencia de usuario y mejorando la calidad del trabajo anterior.</p>
        <p><strong>Valverde Mozo, Andre Gabriel</strong></p>
      </td>
      <td>
        <p><strong>TB1:</strong></p>
        <p>En conclusión, para esta primera entrega nos comunicamos de forma escrita mediante nuestro informe en el cual desarrollamos nuestra idea de negocio utilizando convenciones para facilitar la comprensión del proceso. Asimismo, la comunicación directa entre los miembros del equipo fue clave para la resolución de problemas y planificación de plazos para alcanzar los objetivos planteados.</p>
        <p><strong>TP1:</strong></p>
        <p>En resumen, para esta entrega se enfatizó en mejorar mediante el feedback proporcionado por el profesor y un autoanálisis. Por lo tanto, nos comunicamos de forma escrita en el informe del proyecto, buscando mejorar tanto el formato como el contenido para mostrar nuestras ideas de manera más objetiva.</p>
      </td>
    </tr>
  </tbody>
</table>

<br>

# Capítulo I: Introducción

## 1.1. Startup Profile

### 1.1.1. Descripción de la Startup


En AgroTech, nos especializamos en abordar los desafíos de la crianza de cuyes a través de nuestra aplicación integral AgroConnect. Nuestro enfoque principal es proporcionar asesoramiento especializado y herramientas tecnológicas para mejorar la gestión de granjas de cuyes de manera inteligente y eficiente.

**Misión:**

Empoderar a los granjeros a través de soluciones tecnológicas de vanguardia para una gestión más eficiente de sus criaderos.

**Visión:**

Liderar la innovación tecnológica en la gestión de la crianza de cuyes, promoviendo el bienestar animal y la sostenibilidad en esta industria específica, con miras a expandirnos hacia otros tipos de animales en el futuro.

<p align="center">
  <img src="img/logo.png"
  alt="logo de AgroConnect"
  width="200">
</p>

_Imagen 1. Logo de la aplicación AgroConnect_

### 1.1.2. Perfiles de integrantes del equipo

<table>
  <tr>
    <th>
      <img src="img/piero_perfil.jpg" alt="Foto de perfil de Piero" width="800px">
    </th>
    <td valign="top">
      <p><b>Delgado Corrales, Piero Gonzalo</b></p>
      <p>
        Actualmente estoy en el quinto ciclo de Ingeniería de Software. Poseo destrezas en programación en C++, así como conocimientos en estructuras de datos y sus aplicaciones. Recientemente, he adquirido habilidades en diseño web utilizando HTML, CSS y herramientas como Figma. Soy una persona responsable y me esfuerzo por mantener una organización óptima para gestionar eficazmente las entregas de trabajos.
      </p>
    </td>
  </tr>
  <tr>
    <th>
      <img src="img/salvador_perfil.jpg" alt="Foto de perfil de Salvador" width="800px">
    </th>
    <td valign="top">
      <p><b>Salinas Torres, Salvador Antonio</b></p>
      <p>
        Soy estudiante de quinto ciclo de la carrera de Ingeniería de Software. Poseo conocimientos en programación orientada a objetos en C++ y Python, desarrollo web usando HTML, CSS y JavaScript, y gestión de base de datos en SQL Server. Considero que soy una persona responsable y siempre organizo el tiempo para hacerlos tranquilamente antes de la fecha de entrega.
      </p>
    </td>
  </tr>
  <tr>
    <th>
      <img src="img/nadia_perfil.png" alt="Foto de perfil de Nadia" width="800px">
    </th>
    <td valign="top">
      <p><b>Lucas Coronel, Nadia Alessandra</b></p>
      <p>
        Mi nombre es Nadia Alessandra Lucas Coronel y soy estudiante del sexto ciclo de la carrera de Ingeniería de Software. Me considero una persona entusiasta, perseverante y responsable. Cuento con conocimientos en SQL, C++, Python, HTML, CSS, JavaScript y metodologías ágiles. Me comprometo a aplicar mis conocimientos de manera efectiva para contribuir al desarrollo de soluciones de software de alta calidad.
      </p>
    </td>
  </tr>
  <tr>
    <th>
      <img src="img/sebastian_perfil.png" alt="Foto de perfil de Sebastian" width="800px">
    </th>
    <td valign="top">
      <p><b>Paredes Puente, Sebastian Roberto</b></p>
      <p>
        Soy estudiante de quinto ciclo de la carrera de Ingeniería de Software. Dentro de mi experiencia, destaco la capacidad de analizar información y programar en lenguaje C++. Además, he completado cursos en Python, SQL Server y HTML. En cuanto a mis habilidades interpersonales, cuento con adaptabilidad, pensamiento creativo, trabajo en equipo, gestión del tiempo y capacidad analítica para resolver problemas.
      </p>
    </td>
  </tr>
  <tr>
    <th>
      <img src="img/andre_perfil.png" alt="Foto de perfil de Andre" width="700px">
    </th>
    <td valign="top">
      <p><b>Valverde Mozo, Andre Gabriel</b></p>
      <p>
        Mi perfil se basa en ser alguien que busca soluciones creativas a todo problema. Considero que tengo una buena capacidad de análisis de problemas y un pensamiento rápido en dichos casos. Me encanta todo lo que es la programación ya que es una forma de arte para mí, solo que lo puedo hacer realidad frente a mis ojos.
      </p>
    </td>
  </tr>
</table>


<br>

## 1.2. Solution Profile

### 1.2.1 Antecedentes y problemática

- **What:** El sector de la crianza de cuyes enfrenta desafíos en la gestión eficiente de las granjas, la falta de acceso a tecnologías adecuadas y la necesidad de mejorar el bienestar animal y la sostenibilidad de las prácticas agrícolas. 
- **Where:** Nos enfocaremos en todo el territorio nacional del Perú, especialmente en los departamentos donde se concentra la mayor parte del comercio y la actividad económica del país, y donde la crianza de cuyes es más prevalente

- **When:** Actualmente, el sector agropecuario se enfrenta a estos desafíos en la gestión de la crianza de cuyes. Con el crecimiento de la población en el país y la demanda de alimentos en aumento, se requiere una mayor eficiencia en la producción agrícola. Además, las preocupaciones ambientales y de bienestar animal están impulsando la necesidad de adoptar prácticas agrícolas más sostenibles y éticas.
- **Who:** AgroTech, como empresa líder en tecnología aplicada a la agricultura, asume la responsabilidad de liderar la innovación en la gestión de la crianza de cuyes. En este proceso, trabajamos en estrecha colaboración con expertos y asesores en la crianza de cuyes, quienes aportan su conocimiento especializado para desarrollar soluciones tecnológicas específicas y efectivas. Además, involucramos activamente a los criadores de cuyes, quienes son los beneficiarios directos de estas soluciones, asegurando que se adapten a sus necesidades y realidades específicas.
- **Why:** Para abordar estos desafíos y mejorar la gestión y productividad en la crianza de cuyes, garantizando el bienestar animal y promoviendo prácticas sostenibles en la industria agropecuaria. Además, se busca mejorar la rentabilidad de los agricultores y contribuir a la seguridad alimentaria peruana.
- **How:** A través de la aplicación integral Agroconnect, que proporcionará asesoramiento especializado y herramientas tecnológicas para gestionar de manera inteligente y eficiente las granjas de cuyes. Esto incluirá sistemas de análisis predictivo para optimizar la alimentación y la salud de los animales, y la implementación de prácticas agrícolas más sostenibles.
- **How much:** Se espera que la aplicación tenga un impacto significativo en la mejora de la gestión de las granjas de cuyes, aumentando la productividad, mejorando el bienestar animal y promoviendo prácticas más sostenibles en la industria agropecuaria. Esta innovación busca mejorar la eficiencia en la crianza de los cuyes para de esta manera poder sumar a los esfuerzos del Ministerio de Desarrollo Agrario y Riego (Midagri) en este ámbito, el cuál ha informado que se logró un incremento del 20% en las crianzas de cuyes, lo que ha permitido un mayor consumo de carne de esta especie, evidenciando el impacto positivo de las tecnologías y prácticas innovadoras en la crianza de cuyes.
<br><br>Del mismo modo, hemos comprobado la necesidad del mercado gracias a las estadísticas brindadas por el Ministerio de Desarrollo Agrario y Riego (2023) ya que estas muestran que del año 2020 al 2021 hubo un aumento de 116 mil cuyes. Por lo que, se espera que siga aumentando. (Revisar [Anexo N°1: Gráfico de evolución de población de cuyes](#anexo-n1-gráfico-de-evolución-de-población-de-cuyes)).<br><br>Entonces, nuestra aplicación ayudará para  mejorar el cuidado de los cuyes, ya que suelen haber problemas como la mala nutrición o el déficit de control de enfermedades que perjudica directamente a las granjas. (Revisar [Anexo N°2: Diagrama de problemas en la crianza de cuyes](#anexo-n2-diagrama-de-problemas-en-la-crianza-de-cuyes))

### 1.2.2 Lean UX Process.

#### 1.2.2.1. Lean UX Problem Statements.

***Problem Statement 1***

|Nuestro producto tiene como objetivo mejorar la gestión de granjas de cuyes en el Perú.|
| - |
|Hemos observado que los criadores de cuyes en Perú enfrentan dificultades para gestionar eficientemente sus granjas, lo que afecta su productividad y rentabilidad.|
|¿Podría nuestra aplicación AgroConnect ayudar a los criadores de cuyes a mejorar la gestión de sus granjas y aumentar su productividad?|


***Problem Statement 2***

|Nuestro producto tiene como objetivo aumentar la rentabilidad de los criadores de cuyes en Perú.|
| - |
|Hemos observado que muchos criadores de cuyes en Perú enfrentan desafíos para lograr una rentabilidad adecuada debido a la falta de eficiencia en la gestión de sus granjas.|
|¿Podría Agroconnect ayudar a los criadores de cuyes en Perú a mejorar su rentabilidad mediante una gestión más eficiente de sus granjas?|


***Problem Statement 3***

|Nuestro producto tiene como objetivo facilitar el acceso a mercados y mejorar la comercialización de los productos de cuy en Perú.|
| - |
|Hemos observado que muchos criadores de cuyes en Perú enfrentan dificultades para acceder a mercados y comercializar sus productos de manera efectiva.|
|¿Podría Agroconnect ayudar a los criadores de cuyes en Perú a acceder a mercados y mejorar la comercialización de sus productos?|


#### 1.2.2.2. Lean UX Assumptions.

1. **¿Quién es el usuario?** 

   El usuario principal de nuestro producto es el criador de cuyes en Perú. También pueden incluirse otros actores involucrados en la cadena de producción y comercialización de productos cárnicos de cuy, como los trabajadores de las granjas, los compradores de cuyes y los consumidores finales.

1. **¿Dónde encaja nuestro producto en su trabajo o vida?**

   Nuestro producto encaja en la vida del criador de cuyes al proporcionarle herramientas tecnológicas y asesoramiento especializado para mejorar la gestión de sus granjas. Agroconnect se integra en su trabajo diario al ofrecer soluciones para la gestión eficiente de la crianza de cuyes, la mejora del bienestar animal, la adopción de prácticas sostenibles y la comercialización de sus productos.

1. **¿Qué problemas tiene nuestro producto? ¿Resolver?**

   Actualmente, nuestro producto presenta un inconveniente, ya que no está configurado para enfocarse en la crianza de animales distintos al cuy. Por otra parte, aborda varios problemas que enfrentan los criadores de cuyes en Perú, como la falta de acceso a tecnologías adecuadas, la gestión ineficiente de las granjas, la necesidad de mejorar el bienestar animal, la baja rentabilidad y el impacto ambiental negativo de las prácticas agrícolas. Agroconnect resuelve estos problemas al proporcionar herramientas y conocimientos para una gestión más eficiente, prácticas agrícolas sostenibles, mejoramiento del bienestar animal, aumento de la rentabilidad y reducción del impacto ambiental.

1. **¿Cuándo y cómo es nuestro producto? ¿Usado?** 

   Nuestro producto sería utilizado de manera continua por los criadores de cuyes en Perú, como una herramienta integral en la gestión diaria de sus granjas. Agroconnect se utilizará a través de dispositivos móviles o computadoras, con acceso a internet, permitiendo a los usuarios utilizar la plataforma en cualquier momento y desde cualquier lugar.

1. **¿Qué características son importantes?**

   Asesoramiento especializado: Ofrecer información y recomendaciones específicas para la gestión de granjas de cuyes.

   Análisis predictivo: Proporcionar predicciones y sugerencias para optimizar la alimentación, la salud y la reproducción de los cuyes.

   Herramientas de gestión: Facilitar la administración de inventarios, registros de salud y reproducción, y planificación de actividades.

   Conexión con mercados: Ayudar a los criadores a acceder a mercados y promocionar sus productos nutricionales (la carne del cuy) de manera efectiva.

1. **¿Cómo debe verse nuestro producto y cómo comportarse?**

   Nuestro producto debe tener una interfaz intuitiva y fácil de usar, con un diseño limpio y atractivo. Debe comportarse de manera rápida y eficiente, brindando información y recomendaciones de manera clara y precisa. Debe ser confiable y seguro, garantizando la protección de los datos de los usuarios y la integridad de la información proporcionada.

**Presentación de otros supuestos:** 

|Creo que mis clientes necesitan un servicio que les brinde soluciones integrales para la gestión eficiente de la crianza de cuyes, abordando aspectos como la salud animal, la nutrición, la reproducción y la comercialización.|Haré dinero a través de la venta de suscripciones a nuestra plataforma Agroconnect, así como mediante la prestación de servicios de consultoría especializada y la venta de productos complementarios.|
| - | - |
|Estas necesidades se pueden resolver con tecnologías avanzadas de monitoreo y análisis de datos, junto con el acceso a un equipo de expertos en crianza de cuyes que proporcionen orientación y recomendaciones personalizadas.|<p>Mi competencia principal en el mercado será: BestFarm  </p><p></p>|
|Mis clientes iniciales son los criadores de cuyes en Perú que buscan mejorar la eficiencia y la rentabilidad de sus operaciones.|Los venceremos gracias a nuestra combinación única de tecnología avanzada, conocimientos especializados y enfoque centrado en las necesidades específicas de la crianza de cuyes.|
|El valor número uno que un cliente quiere de mi servicio es mejorar la rentabilidad de su granja de cuyes mientras garantiza el bienestar de los animales y adoptar prácticas sostenibles.|Mi mayor riesgo con respecto al producto es la resistencia al cambio por parte de algunos criadores, que pueden ser reacios a adoptar nuevas tecnologías o modificar sus métodos de crianza.|
|El cliente también puede optar por no renovar su suscripción a nuestra plataforma si no percibe mejoras significativas en la gestión y rentabilidad de su granja de cuyes.|Resolveremos esto a través de una estrategia integral de educación y soporte continuo para nuestros clientes, demostrando el valor tangible de nuestra plataforma a través de casos de éxito y resultados demostrables.|
|Voy a adquirir a la mayoría de mis clientes a través de campañas de marketing dirigidas en línea, participación en eventos agrícolas locales y asociaciones con organizaciones de productores de cuyes.|Nuestro enfoque principal es proporcionar asesoramiento especializado y herramientas tecnológicas para mejorar la gestión de la crianza de cuyes de forma inteligente y eficiente.|


#### 1.2.2.3. Lean UX Hypothesis Statements.

**Hypothesis Statement 1**

|Creemos que al proporcionar a los criadores de cuyes en Perú acceso a tecnologías avanzadas y asesoramiento especializado a través de nuestra plataforma Agroconnect, mejorarán la eficiencia y la rentabilidad de sus granjas..|
| - |
|Sabremos que esto es cierto…|
|Cuando se aprecie un incremento del 20% en la cantidad de solicitudes de asesorías durante los primeros 6 meses de lanzamiento.|

**Hypothesis Statement 2**

|Creemos que al promover prácticas agrícolas sostenibles y éticas en la crianza de cuyes en Perú a través de Agroconnect, los criadores adoptarán un enfoque más responsable con el medio ambiente.|
| - |
|Sabremos que esto es cierto…|
|Cuando proporcionemos orientación y recursos específicos sobre prácticas sostenibles a través de AgroConnect y evaluemos la adopción de estas prácticas por parte de los criadores, viendo un aumento del 15% en el uso de prácticas sostenibles dentro de los primeros 6 meses de lanzamiento.|

**Hypothesis Statement 3**

|Creemos que al facilitar el acceso a mercados y mejorar la comercialización de los productos de cuy en Perú a través de Agroconnect, los criadores aumentarán sus ventas y expandirán sus negocios.|
| - |
|Sabremos que esto es cierto…|
|Cuando se establezcan conexiones con compradores y mercados a través de los asesores de AgroConnect, y evaluemos el impacto en las ventas de los criadores mediante un aumento del 25% en las ventas en los primeros 6 meses de uso de la aplicación.|

**Hypothesis Statement 4**

|Creemos que al facilitar el acceso a mercados y mejorar la comercialización de los productos de cuy en Perú a través de Agroconnect, los criadores aumentarán sus ventas y expandirán sus negocios.|
| - |
|Sabremos que esto es cierto…|
|Cuando se observe un aumento del 20% en el número de asesores activos en los primeros tres meses posteriores a la implementación de la nueva estructura de comisiones. Además, mediremos la retroalimentación de los asesores mediante encuestas regulares, y consideraremos que hemos tenido éxito si al menos el 70% de las respuestas son positivas en relación con la nueva estructura de comisiones.|



#### 1.2.2.4. Lean UX Canvas.

![Lean Ux Canvas](img/leanuxcanvas.png)

_Imagen 2. Lean UX Canvas_


## 1.3. Segmentos objetivo

Por el lado de los asesores, hemos considerado que estos tendrán experiencia en el campo y/o estudios universitarios en carreras como ingeniería agrónoma, medicina veterinaria, zootecnia, etc. De este modo, debido a que el plan de estudios de estas carreras es de mínimo 5 años a más, y necesitan cierto grado de experiencia para dar recomendaciones y planes de acción confiables, hemos decidido que el rango de edad será de 25 años hasta 65 años.


Según el Ministerio de Desarrollo Agrario y Riego (2023), la crianza de cuyes es una alternativa para la generación de ingresos monetarios para más de 800,000 familias agrarias en el Perú, las cuales se ubican en su mayoría en la sierra del país. El consumo de carne de cuy se ha mantenido en el tiempo e incluso ha trascendido al mercado externo. Esta información destaca la importancia de los asesores en la crianza de cuyes, ya que su conocimiento y orientación pueden ser fundamentales para el éxito y la sostenibilidad de los productores en este sector.


|**Segmento objetivo**|Asesores |
| :- | :- |
|**Edad**|25-65 años|
|**Ubicación**|Perú|
|**Sexo**|Masculino y Femenino|
|**Formación educativa**|Universitario o cualquier educación superior|
|**Poder adquisitivo**|Bajo, medio y alto|

Para delimitar el segmento objetivo de criadores de cuyes nos basamos en el diagnóstico situacional de la crianza de cuyes en Cajamarca realizado en julio de 2004. Dicho diagnóstico menciona que el 44.6% de los productores tenían más de 50 años, sus esposas que conducían la crianza de cuyes tenían entre 31 a 50 años. Además, los hijos que vivían con los padres tenían entre 6 a 17 años. Por lo tanto, para el rango de edad de los criadores decidimos seleccionar desde los 18 años de edad hasta los 60 años para abarcar tanto a los padres que manejan la crianza como a los hijos mayores de edad que la apoyan.

Por otro lado, el mismo diagnóstico señala que el grado de instrucción predominante en la familia es de educación primaría con un 65.6% que es el que consideraremos.


|**Segmento objetivo**|Criadores de cuyes|
| :- | :- |
|**Edad**|18-60 años|
|**Ubicación**|Perú|
|**Sexo**|Masculino y Femenino|
|**Formación educativa**|Educación primaria|
|**Poder adquisitivo**|Bajo y medio|


# Capítulo II Requirements Elicitation & Analysis

## 2.1. Competidores

### 2.1.1. Análisis competitivo
<table>
  <tr>
    <th colspan="6" valign="top">Competitive Analysis Landscape</th>
  </tr>
  <tr>
    <td colspan="2" valign="top">¿Por qué llevar a cabo este análisis?</td>
    <td colspan="4" valign="top">Objetivo 1: Adquirir conocimiento acerca de las propuestas ofrecidas por nuestros competidores y obtener enseñanzas a partir de las áreas en las que presentan limitaciones.<br>
    Objetivo 2: Identificar los puntos fuertes y las limitaciones de nuestros competidores con el fin de formular una estrategia competitiva sólida y efectiva.
    </td>
  </tr>
  <tr>
    <td colspan="2" rowspan="2" valign="top">Empresa/App</td>
    <td valign="top">AgroConnect </td>
    <td valign="top">BestFarm</td>
    <td valign="top">CattleMax</td>
    <td valign="top">BarnTools</td>
  </tr>
  <tr>
    <td valign="top"><img src="img/logo.png" alt="Logo AgroConnect" height="100px"></td>
    <td valign="top"><img src="img/bestfarm_logo.png" alt="Logo BestFarm" height="100px"></td>
    <td valign="top"><img src="img/cattlemax_logo.png" alt="Logo CattleMax" height="100px"></td>
    <td valign="top"><img src="img/barntool_logo.png" alt="Logo BarnTools" height="100px"></td>
  </tr>
  <tr>
    <td rowspan="2" valign="top">Perfil</td>
    <td valign="top">Overview</td>
    <td valign="top">Una aplicación integral desarrollada por AgroTech para mejorar la gestión de granjas de cuyes en el Perú. Ofrece asesoramiento especializado y herramientas tecnológicas para optimizar la alimentación, salud y sostenibilidad en la crianza de cuyes, empoderando a los granjeros a través de la innovación tecnológica.</td>
    <td valign="top">Plataforma integral de gestión agrícola que abarca una amplia gama de actividades agrícolas, incluyendo cultivos y ganadería.</td>
    <td valign="top">Aplicación especializada en la gestión de ganado. Está diseñada específicamente para ayudar a los ganaderos a llevar un registro detallado de su ganado, gestionar la salud y el seguimiento de la reproducción.</td>
    <td valign="top">BarnTools es una aplicación que se centra en la gestión de animales de granja en general, incluyendo ganado, aves de corral y otros animales. </td>
  </tr>
  <tr>
    <td valign="top">Ventaja competitiva ¿Qué valor ofrece a los clientes?</td>
    <td valign="top">La ventaja competitiva de AgroConnect es la integración completa de tecnología y asesoramiento especializado. Esto significa que no solo proporcionamos herramientas tecnológicas avanzadas a través de AgroConnect, sino que también ofrecemos orientación y asesoramiento específico para la crianza de cuyes.</td>
    <td valign="top">La ventaja competitiva de BestFarm radica en su enfoque de la gestión agrícola, que permite a los usuarios gestionar tanto cultivos como animales en una sola plataforma.</td>
    <td valign="top">La principal ventaja competitiva de CattleMax es que ofrece características y herramientas específicas para el ganado, lo que lo convierte en una opción sólida para ganaderos que buscan una solución dedicada.</td>
    <td valign="top">La ventaja competitiva de BarnTools radica en su capacidad para gestionar una variedad de animales de granja, lo que la hace adecuada para granjeros con múltiple variedad de ganado.</td>
  </tr>
  <tr>
    <td rowspan="2" valign="top">Perfil de Marketing</td>
    <td valign="top">Mercado objetivo</td>
    <td valign="top">El mercado objetivo de AgroConnect son los criadores de cuyes en Perú, así como otros actores involucrados en la cadena de producción y comercialización de productos cárnicos de cuy.</td>
    <td valign="top">El mercado objetivo de BestFarm incluye a agricultores y ganaderos que gestionan operaciones mixtas de cultivos y ganado.</td>
    <td valign="top">El mercado objetivo de CattleMax son los ganaderos y criadores de ganado de todas las escalas.</td>
    <td valign="top">El mercado objetivo de BarnTools son los granjeros y ganaderos que gestionan una variedad de animales</td>
  </tr>
  <tr>
    <td valign="top">Estrategias de marketing</td>
    <td valign="top">Campañas educativas en línea y fuera de línea para resaltar los beneficios de AgroConnet en términos de mejora de la productividad, bienestar animal y sostenibilidad en la crianza de cuyes.</td>
    <td valign="top">Promoción en ferias agrícolas y ganaderas para mostrar la versatilidad de la plataforma.</td>
    <td valign="top">Colaboración con asociaciones ganaderas y veterinarios especializados en ganado.</td>
    <td valign="top">Publicidad en revistas agrícolas y ganaderas</td>
  </tr>
  <tr>
    <td rowspan="3" valign="top">Perfil de Producto</td>
    <td valign="top">Productos & Servicios</td>
    <td valign="top">Plataforma integral de gestión para la crianza de cuyes. Ofreciendo una solución completa para la gestión eficiente de granjas de cuyes.</td>
    <td valign="top">Plataforma integral de gestión agrícola para cultivos y animales, planificación de cultivos, programación de tareas, seguimiento de salud, análisis de datos agrícolas</td>
    <td valign="top">Plataforma de gestión de ganado bovino, registro de animales, seguimiento de salud, programación de tareas, seguimiento de reproducción, gestión de gastos.</td>
    <td valign="top">Plataforma versátil para la gestión de animales de granja en general, registro de animales, seguimiento de salud, programación de tareas.</td>
  </tr>
  <tr>
    <td valign="top">Precios & Costos</td>
    <td valign="top">Modelo de suscripción mensual o anual. Los precios varían según la escala de la operación y las funcionalidades requeridas.</td>
    <td valign="top">BestFarm utiliza  precios basados en suscripción.</td>
    <td valign="top">CattleMax utiliza  precios basados en suscripción.</td>
    <td valign="top">BarnTools utiliza  precios basados en la suscripción.</td>
  </tr>
  <tr>
    <td valign="top">Canales de distribución (Web y/o Móvil)</td>
    <td valign="top">AgroConnect se distribuye principalmente a través de una plataforma web accesible desde cualquier navegador. También ofrece una aplicación móvil.</td>
    <td valign="top">BestFarm se distribuye a través de una plataforma web</td>
    <td valign="top">CattleMax se distribuye a través de una plataforma web y ofrece una aplicación móvil</td>
    <td valign="top">BarnTools se distribuye principalmente a través de una plataforma web accesible desde navegadores de computadoras de escritorio y dispositivos móviles.</td>
  </tr>
  <tr>
    <td rowspan="4" valign="top">Análisis SWOT</td>
    <td valign="top">Fortalezas</td>
    <td valign="top">- Integración completa de tecnología y asesoramiento especializado.<br>
    - Mejora del bienestar animal y la sostenibilidad en la crianza de cuyes.<br>
    - Plataforma integral que aborda múltiples aspectos de la gestión de granjas de cuyes.<br>
    - Potencial para expandirse hacia otros tipos de animales en el futuro.
    </td>
    <td valign="top">- Ofrece una plataforma integral para la gestión de cultivos y animales.<br>
    - Enfoque en la agricultura.<br>
    - Planificación y análisis de datos agrícolas.
    </td>
    <td valign="top">- Enfoque especializado en la gestión de ganado bovino.<br>
    - Herramientas específicas para ganado bovino.<br>
    - Plataforma web y aplicación móvil para mayor accesibilidad.
    </td>
    <td valign="top">- Versatilidad para gestionar una variedad de animales de granja.<br>
    - Registro de animales, seguimiento de salud y programación de tareas.<br>
    - Plataforma web y aplicación móvil para mayor accesibilidad.
    </td>
  </tr>
  <tr>
    <td valign="top">Debilidades</td>
    <td valign="top">– Posible resistencia al cambio por parte de algunos criadores de cuyes.<br>
    - Costos de implementación y acceso a tecnología en áreas rurales o remotas.<br>
    - Necesidad de una curva de aprendizaje para algunos usuarios menos familiarizados con la tecnología.<br>
    - Dependencia de la conectividad a internet para el funcionamiento óptimo de la plataforma.
    </td>
    <td valign="top">- Competencia en nichos de mercado más específicos.<br>
    - Puede ser percibido como demasiado complejo para usuarios con necesidades simples.
    </td>
    <td valign="top">- Limitado en términos de diversificación de servicios para otros tipos de animales.</td>
    <td valign="top">- Mayor competencia en el mercado de gestión de animales de granja.</td>
  </tr>
  <tr>
    <td valign="top">Oportunidades</td>
    <td valign="top">- Creciente demanda de soluciones tecnológicas en el sector agrícola.<br>
    - Aumento de la conciencia sobre el bienestar animal y la sostenibilidad.<br>
    - Posibilidad de colaboraciones con instituciones gubernamentales y organizaciones agrícolas para promover el uso de tecnología en la crianza de cuyes.<br>
    - Expansión a nuevos mercados regionales o internacionales.
    </td>
    <td valign="top">- Expansión hacia mercados agrícolas más amplios.<br>
    - Colaboración con proveedores de tecnología agrícola.
    </td>
    <td valign="top">- Expansión hacia otros nichos de mercado ganadero.</td>
    <td valign="top">- Colaboración con proveedores de tecnología agrícola.</td>
  </tr>
  <tr>
    <td valign="top">Amenazas</td>
    <td valign="top">- Competencia de otras soluciones tecnológicas en el mercado agrícola.<br>
    - Cambios en la regulación gubernamental que podrían afectar la industria de la crianza de cuyes.
    </td>
    <td valign="top">- Competidores especializados en áreas específicas de la agricultura</td>
    <td valign="top">- Cambios en las regulaciones ganaderas.</td>
    <td valign="top">- Competidores especializados en áreas específicas de la gestión de animales de granja.</td>
  </tr>
</table>

### 2.1.2. Estrategias y tácticas frente a competidores
**Estrategias:**

**Diferenciación del producto:** Destacaremos las características únicas de AgroConnect, como la integración completa de tecnología y asesoramiento especializado, para diferenciarnos claramente de otras soluciones en el mercado.

**Enfoque en el valor agregado:** Nos centraremos en comunicar y demostrar el valor agregado que AgroConnect ofrece a los criadores de cuyes, resaltando los beneficios tangibles como la mejora del bienestar animal, la eficiencia operativa y la sostenibilidad.


**Tácticas:**

**Marketing de contenido:** Crearemos contenido educativo y relevante sobre la crianza de cuyes, tecnología agrícola y prácticas sostenibles, para posicionarnos como líderes de pensamiento en el sector y atraer a clientes potenciales.

**Programas de prueba y demostraciones:** Ofreceremos programas de prueba gratuitos y demostraciones en granjas para permitir a los clientes experimentar directamente los beneficios de AgroConnect y generar confianza en nuestra solución.

**Desarrollo de alianzas estratégicas:** Buscaremos colaboraciones con instituciones agrícolas, asociaciones de criadores de cuyes y otras empresas del sector para ampliar nuestra red de clientes y aumentar la visibilidad de AgroConnect.

**Servicio al cliente excepcional:** Nos comprometemos a brindar un excelente servicio al cliente, proporcionando soporte técnico, capacitación y asistencia personalizada para garantizar la satisfacción y fidelidad de nuestros usuarios.


## 2.2. Entrevistas

### 2.2.1. Diseño de entrevistas

**Segmento: Asesor**
1. ¿Cuál es su experiencia en la granja y cuántos años lleva trabajando en este campo?
2. ¿Qué tipo de asesoramiento o servicios específicos ofrece a los criadores en su trabajo actual?
3. ¿Cuáles considera que son los desafíos más comunes que enfrentan los criadores de cuyes principiantes en la gestión de sus granjas?
4. ¿Qué herramientas o recursos utiliza actualmente para brindar asesoramiento a los criadores?
5. ¿Cuál ha sido su experiencia con estas herramientas o recursos? ¿Fue una experiencia positiva o negativa?
6. ¿Qué características o funcionalidades le gustaría ver en una plataforma como “AgroConnect” que facilite la prestación de sus servicios de asesoramiento?
7. ¿Qué temas específicos en la industria agropecuaria considera que son de mayor interés para los criadores principiantes y que deberían abordarse en la plataforma?
8. ¿Cómo cree que una plataforma como "AgroConnect" podría beneficiar a los criadores principiantes y a los propios asesores en la industria?

**Segmento: Criador de cuyes**
1. ¿Cuál es el tamaño de su operación agropecuaria y qué tipo de animales roedores cría?
2. ¿Cuáles son los mayores desafíos que enfrenta en la gestión diaria de su granja?
3. ¿Qué herramientas o métodos utiliza actualmente para llevar un registro de la salud y el estado de sus animales?
4. ¿Cómo planifica y programa las tareas diarias relacionadas con la alimentación, cuidado de los animales y mantenimiento de las instalaciones?
5. ¿Qué información de pronóstico suele utilizar para tomar decisiones en su granja?
6. ¿Ha utilizado aplicaciones o herramientas móviles relacionadas a la gestión de granjas? ¿Cuáles han sido sus experiencias?
7. ¿Qué tipo de información o recursos adicionales le gustaría tener acceso para mejorar la gestión de su granja?
8. ¿Cuál es su opinión sobre la posibilidad de recibir asesoramiento y orientación de criadores más experimentados a través de plataformas en línea o aplicaciones?

### 2.2.2. Registro de entrevistas

**Entrevista N 1 - Asesor:**

**Entrevistador:** Andre Valverde

**Entrevistado:** Rodrigo Guerra

**Link de la entrevista:** https://youtu.be/rXbdiB0spIQ 

<img src="img/entrevista1.png" width="100%">

_Imagen 3. Entrevista a Rodrigo_

**Resumen:** 

Rodrigo Guerra, es asesor de cría de cuyes que tiene un año de experiencia y ofrece asesoramiento técnico en alimentación, reproducción y gestión de granjas. Los desafíos comunes para los criadores principiantes incluyen la falta de conocimientos técnicos. Utiliza herramientas como manuales técnicos y capacitaciones, con una experiencia generalmente positiva. En una plataforma como "AgroConnect", busca funciones para facilitar el intercambio de conocimientos y abordar temas como manejo del estrés y prácticas sostenibles, lo que beneficiaría a criadores y asesores.


**Entrevista N 2 - Asesor:** 

**Entrevistador:** Salvador Salinas

**Entrevistado:** Tamara García

**Link de la entrevista:** https://youtu.be/xs9W9uG10z0

<img src="img/entrevista2.png" width="100%">

_Imagen 4. Entrevista a Tamara_

**Resumen:**

Tamara García es una potencial asesora en la cría de cuyes y está dispuesta a aconsejar a criadores principiantes en la granja de cuyes. Su principal recurso es la experiencia que ha ganado gracias a su familia, y cuenta cómo desde pequeña está familiarizada con la cría de cuyes y la gestión de granja de cuyes. Al comentarle un poco sobre la idea de la plataforma “AgroConnect”, menciona que le gustó mucho la idea ya que no ha visto algo parecido anteriormente, especialmente dirigido a la granja de cuyes. Asimismo, comenta que debería ser una aplicación fácil de usar y accesible para todos.


**Entrevista N 3 - Asesor:**

**Entrevistador:** Sebastian Paredes

**Entrevistado:** Belen Ramos

**Link de la entrevista:** https://youtu.be/xwnwEvw3LxI

<img src="img/entrevista3.jpg" width="100%">

_Imagen 5. Entrevista a Belen_

**Resumen:**

Belen Ramos, la entrevistada, tiene un año de experiencia en la crianza de cuyes y ofrece asesoramiento básico sobre aspectos como la alimentación y el control de enfermedades. Utiliza recursos en línea y su experiencia personal para brindar consejos prácticos a criadores principiantes. Considera que una plataforma como "AgroConnect" sería beneficiosa para conectar con criadores y abordar temas relevantes como la selección de razas y el manejo de enfermedades.

**Entrevista N 4 - Asesor:**

**Entrevistador:** Piero Delgado

**Entrevistado:** Adrián Espinoza

**Link de la entrevista:** https://youtu.be/ANKhs9e_x5E

<img src="img/entrevista4.png" width="100%">

_Imagen 6. Entrevista a Adrián_

**Resumen:**
Adrián ha estado involucrado en la crianza de cuyes desde joven por su familia y recientemente ha empezado a ofrecer asesoramiento a otras familias en alimentación, manejo sanitario y selección de razas de cuyes. Por ello, decidió estudiar Medicina Veterinaria en Arequipa para aprender más de la crianza de animales. Durante la entrevista, destacó los desafíos comunes que enfrentan los criadores principiantes, como el manejo de la alimentación y la prevención de enfermedades. Actualmente, utiliza principalmente su conocimiento personal y recursos en línea para brindar asesoramiento, pero está interesado en explorar nuevas herramientas como aplicaciones. Sugirió que AgroConnect debería permitir la programación de citas de asesoramiento de manera sencilla y abordar temas como la organización de criaderos y la gestión de recursos.


**Entrevista N 5 - Asesor:**

**Entrevistador:** Nadia Lucas

**Entrevistado:** Romina Arana

**Link de la entrevista:** https://www.youtube.com/watch?v=-s0YObYyF8c

<img src="img/entrevista5.png" width="100%">

_Imagen 7. Entrevista a Romina_

**Resumen:**
Romina, una egresada de la UNALM con más de 3 años de experiencia en trabajos de campo desde su sexto ciclo universitario, ofrece asesoramiento en diversos aspectos de la producción de cuyes, desde selección de razas hasta planificación de instalaciones. Su experiencia positiva en el trabajo actual, obtenido a través de una convocatoria en línea, resalta la utilidad de recursos digitales para el aprendizaje. En cuanto a "AgroConnect", Romina sugiere funciones que faciliten la interacción directa entre asesores y criadores, así como la inclusión de temas como reproducción, nutrición, manejo sanitario y comercialización. También considera que ambos, criadores principiantes y asesores, podrían beneficiarse de una plataforma que brinde información confiable y servicios eficientes.


**Entrevista N 6 - Criador:**

**Entrevistador:** Sebastian Paredes

**Entrevistado:** Alessandra Chaupis

**Link de la entrevista:** https://youtu.be/3UqveRZBafU

<img src="img/entrevista6.png" width="100%">

_Imagen 8. Entrevista a Alessandra_

**Resumen:** 

Alessandra Chaupis, una joven de 20 años que vive en San Juan de Lurigancho, se encuentra en sus inicios en el negocio de la crianza de cuyes, en la entrevista destaca que su operación agropecuaria es de tamaño mediano, gracias a esta escala puede gestionar todas las actividades de cuidado y producción de manera efectiva, manteniendo un equilibrio entre la rentabilidad y la atención individualizada que requieren los cuyes. Los principales desafíos que enfrenta en su granja son el control de enfermedades, la gestión de la alimentación adecuada y el mantenimiento de las condiciones sanitarias para garantizar la salud y el bienestar de los animales y la calidad de los productos. Utiliza un registro manual y aplicaciones móviles para el seguimiento de la salud de los cuyes, así como un calendario para planificar las tareas diarias. Además, utiliza información meteorológica y datos históricos de producción para tomar decisiones informadas. Además, tiene una experiencia positiva con aplicaciones móviles de gestión de granjas, que le han permitido mejorar la eficiencia de su operación. Busca acceso a información sobre nuevas técnicas de crianza y mejores prácticas de manejo, y considera que recibir asesoramiento de criadores más experimentados sería beneficioso para mejorar la eficiencia y productividad de su granja.



**Entrevista N 7 - Criador:** 

**Entrevistador:** Nadia Lucas

**Entrevistado:** Nayeli Chavez

**Link de la entrevista:** https://youtu.be/xM3fyi4a-To 

<img src="img/entrevista7.png" width="100%">

_Imagen 9. Entrevista a Nayeli_

**Resumen:**

Nayeli Chávez, una criadora de 24 años que reside en Puente Piedra, es relativamente nueva en el negocio que maneja junto a su madre, crían alrededor de 50 cuyes debido a su alta demanda. Sus desafíos incluyen mantener la salud y condiciones ambientales adecuadas para los animales, así como gestionar su alimentación y espacio. Actualmente lleva registros manuales de la salud de cada cuy y planifica sus tareas diarias para garantizar un cuidado constante. Utiliza información sobre madurez sexual y ciclos reproductivos para tomar decisiones en su granja y está abierta a explorar aplicaciones que faciliten la gestión. Busca acceso a recursos sobre prácticas de cría avanzadas y considera valiosa la orientación de criadores más experimentados a través de plataformas en línea o aplicaciones.


**Entrevista N 8 - Criador:**

**Entrevistador:** Piero Delgado

**Entrevistado:** Daniel Ruiz

**Link de la entrevista:** https://youtu.be/Lst4qVknGrk?si=2-f34iRuoXJ4amyC

<img src="img/entrevista8.jpg" width="100%">

_Imagen 10. Entrevista a Daniel_

**Resumen:**

Daniel viene de una familia que ha criado cuyes durante generaciones para generar un ingreso para su familia. Su familia maneja una operación mediana con alrededor de 30 cuyes. Uno de los desafíos más grandes para su criadero es mantener la salud y el bienestar de los cuyes, así como garantizar una alimentación adecuada y prevenir enfermedades. Para registrar la información de los cuyes, utiliza métodos manuales donde detalla la salud de cada animal y realiza revisiones periódicas para detectar problemas. Daniel no ha utilizado aplicaciones especializadas pero usa herramientas simples como calculadora y calendario. Está interesado en una herramienta intuitiva para gestionar la información de los cuyes y recibir asesoramiento en línea. Estaría dispuesto a pagar por una aplicación con estas funcionalidades si el precio es asequible.


**Entrevista N 9 - Criador:**

**Entrevistador:** Salvador Salinas

**Entrevistado:** Anderson Morales

**Link de la entrevista:** https://youtu.be/y0rkvGo_8nQ

<img src="img/entrevista9.png" width="100%">

_Imagen 11. Entrevista a Anderson_

**Resumen:**

Anderson Morales ha empezado junto a su padre a criar unos treinta cuyes aproximadamente. Comenta que a veces se le dificulta el mantener registro de los recursos y datos de los animales, ya que lo hace en un excel pero no suele ser muy eficiente. Al comentarle sobre la idea de la app para poder gestionar los datos de su granja y recibir asesorías, mencionó que le pareció una gran idea, ya que así podría tener una mejor manera para organizar sus datos y además poder tener gente de la cual apoyarse en caso tenga algún problema.

### 2.2.3. Análisis de entrevistas

**Formas de difusión de información de los asesores**
|Formas de difusión|Rodrigo|Tamara|Belen|
| - | - | - | - |
|Charlas|X| | |
|Grupos de discusion en línea|X| |X|
|Visita presencial| |X|X|
|Videos en línea| | |X|

<img src="img/piechart1.png" alt="% Asesores que apoyan nuestra idea">

_Imagen 12. Gráfico circular - Asesores_

Gracias a las entrevistas realizadas, comprendimos que los asesores suelen brindar apoyo a través de internet o a conocidos. Así, al comentarle sobre nuestra idea de aplicación web para poder brindar asesorías a criadores de cuyes, indicaron que les pareció muy buena idea ya que brinda mejor comunicación y confiabilidad.

**Desafíos que tienen los asesores con la crianza de cuyes**
|Desafíos de crianza|Alessandra|Nayeli|Daniel|
| - | - | - | - |
|Gestión de alimentación|X|X|X|
|Mantenimiento de galpones|X| | |
|Control de enfermedades|X|X|X|
|Gestión de espacio| |X| |

<img src="img/piechart2.png" alt="% Criadores que apoyan nuestra idea">

_Imagen 13. Gráfico circular - Criadores_

Asimismo, obtuvimos la conclusión de que los criadores de cuyes suelen tener dificultad para gestionar correctamente la alimentación y control de enfermedades, además de gestionar recursos de la granja en sí. De esta forma, al comentarle sobre nuestra idea de aplicación web para poder recibir asesorías de personas con experiencia y gestionar los recursos de su granja, indicaron que les pareció muy buena idea ya que sería un mejor recurso para obtener información confiable.

## 2.3. Needfinding

### 2.3.1. User Personas

Para la realización de las fichas de User Personas se han considerado los 2 segmentos objetivos: asesores y criadores de cuyes. Se elaborarán las fichas con la información recopilada de las entrevistas sobre su perfil.

**Segmento Asesor**

<img src="img/persona_asesor.png" alt="Persona Asesor">

_Imagen 14. User Persona - Asesor_

**Segmento Criador**

<img src="img/persona_criador.png" alt="Persona Criador">

_Imagen 15. User Persona - Criador_

### 2.3.2. User Task Matrix

<table>
  <tr>
    <th rowspan="2" valign="top"><b>Task Matrix</b></th>
    <th colspan="2" valign="top"><b>Asesores</b></th>
    <th colspan="2" valign="top"><b>Criadores</b></th>
  </tr>
  <tr>
    <td valign="top"><b>Frecuencia</b></td>
    <td valign="top"><b>Importancia</b></td>
    <td valign="top"><b>Frecuencia</b></td>
    <td valign="top"><b>Importancia</b></td>
  </tr>
  <tr>
    <td>Alimentar a los cuyes</td>
    <td>Nunca</td>
    <td>Ninguna</td>
    <td>Diaria</td>
    <td>Alta</td>
  </tr>
  <tr>
    <td>Proporcionar agua limpia</td>
    <td>Nunca</td>
    <td>Ninguna</td>
    <td>Diaria</td>
    <td>Alta</td>
  </tr>
  <tr>
    <td>Limpiar jaulas</td>
    <td>Nunca</td>
    <td>Ninguna</td>
    <td>Semanal</td>
    <td>Media</td>
  </tr>
  <tr>
    <td>Comprar suministros y alimentos</td>
    <td>Nunca</td>
    <td>Ninguna</td>
    <td>Mensual</td>
    <td>Media</td>
  </tr>
  <tr>
    <td>Vender cuyes</td>
    <td>Nunca</td>
    <td>Ninguna</td>
    <td>Mensual</td>
    <td>Alta</td>
  </tr>
  <tr>
    <td>Gestionar gastos y ganancias</td>
    <td>Mensual</td>
    <td>Media</td>
    <td>Mensual</td>
    <td>Alta</td>
  </tr>
  <tr>
    <td>Monitorear la salud y el bienestar de los cuyes</td>
    <td>Mensual</td>
    <td>Alta</td>
    <td>Siempre</td>
    <td>Alta</td>
  </tr>
  <tr>
    <td>Investigar sobre nuevas prácticas y tecnologías para la crianza de cuyes</td>
    <td>Mensual</td>
    <td>Media</td>
    <td>Casi Nunca</td>
    <td>Baja</td>
  </tr>
  <tr>
    <td>Realizar seguimiento y evaluación de progreso de granjas</td>
    <td>Semanal</td>
    <td>Alta</td>
    <td>Semanal</td>
    <td>Alta</td>
  </tr>
  <tr>
    <td>Participar de sesiones de asesoramiento para recibir información actualizada</td>
    <td>Mensual</td>
    <td>Media</td>
    <td>Mensual</td>
    <td>Media</td>
  </tr>
  <tr>
    <td>Resolver problemas específicos en las granjas</td>
    <td>Según necesidad</td>
    <td>Muy Alta</td>
    <td>Según necesidad</td>
    <td>Muy Alta</td>
  </tr>
  <tr>
    <td>Desarrollar y/o asistir a sesiones de capacitación sobre técnicas de crianza</td>
    <td>A veces</td>
    <td>Alta</td>
    <td>A veces</td>
    <td>Media</td>
  </tr>
  <tr>
    <td>Elaborar y/o leer informes de progreso con recomendaciones</td>
    <td>Trimestral</td>
    <td>Alta</td>
    <td>Trimestral</td>
    <td>Alta</td>
  </tr>
  <tr>
    <td>Evaluar las condiciones y necesidades de las granjas de forma presencial</td>
    <td>Casi nunca</td>
    <td>Alta</td>
    <td>Diaria</td>
    <td>Media</td>
  </tr>
</table>

<br>
A partir del User Task Matrix, resaltaremos las tareas de mayor trascendencia. Entre ellas tenemos ‘monitorear la salud y bienestar de los cuyes’ ya que los criadores están pendientes constantemente de la salud de los cuyes viendo comportamientos inusuales y posibles enfermedades para comunicárselo a los asesores quienes otorgarían consejos sobre el accionar ante una posible enfermedad o comportamiento inusual. Esta tarea es fundamental para que haya una producción exitosa y sin contratiempos.

Asimismo, la tarea de ‘realizar seguimiento y evaluación de progreso de granjas’ es fundamental por el mismo motivo porque permite una mejora continua en el rendimiento de las granjas.

Por otro lado, las principales diferencias entre ambos segmentos radican en las actividades diarias dentro del criadero ya que solo participan los criadores para asegurarse de la salud y crecimiento de los cuyes. Por lo tanto, los criadores están monitoreando constantemente las condiciones de sus granjas, mientras que los asesores tienen que separar una fecha para realizar esto de forma presencial.

Finalmente, la principal coincidencia encontrada es que tanto los asesores como los criadores deben estar preparados para solucionar problemas específicos cuando estos aparezcan.




### 2.3.3. User Journey Mapping

Para el segmento de los asesores especializados, se ha considerado desde el momento en que reciben una solicitud de servicio por parte de un criador de cuyes hasta el seguimiento de los avances con respecto a los cambios planteados.
Por otro lado, para el segmento de criadores de cuyes se tomó en cuenta desde la búsqueda inicial de información y contactos de asesores hasta la implementación de nuevos conocimientos y el análisis de resultados obtenidos.

**Segmento Asesor**

<img src="img/journeymap_asesor.png" alt="Journey Map Asesor">

_Imagen 16. User Journey Map - Asesor_

**Segmento Criador**

<img src="img/journeymap_criador.png" alt="Journey Map Criador">

_Imagen 17. User Journey Map - Criador_

### 2.3.4. Empathy Mapping

En esta sección, se desarrollaron los Empathy Maps de cada segmento objetivo. Se utilizó una plantilla de EXPressia que contiene los apartados que debe tener el Empathy Map junto a preguntas que se respondieron conforme a lo identificado de nuestro segmento objetivo para desarrollar este artefacto.

**Segmento Asesor**

<img src="img/empathymap_asesor.png" alt="Empathy Map Asesor">

_Imagen 18. Empathy Map - Asesor_

**Segmento Criador**

<img src="img/empathymap_criador.png" alt="Empathy Map Criador">

_Imagen 19. Empathy Map - Criador_

### 2.3.5. As-is Scenario Mapping
**Segmento: Asesor**

|**Phases**|**Búsqueda de de trabajo**|**Publicar su experiencia en el rubro** |**Comunicación con el ganadero**|**Asesorar al ganadero**|
| :- | :- | :- | :- | :- |
|**Doing**|- Busca la manera de llegar a más público, creándose  foros de difusión, cuentas de instagram,etc.Para que así más personas adquieran sus servicios.|- Habiendo creado su perfil, empieza a publicar información acerca de él, la experiencia que tiene en el campo, el rubro con el que se especializa, entre otros datos relevantes que ayuden a captar el interés del cliente.|-Se comunica con el ganadero mediante whatsapp, instagram o en llamadas cortas explicando los beneficios de su servicio.|- Mediante whatsapp y luego de haber llegado a un acuerdo se reúne con el ganador para poder asesorar en lo que necesita|
|**Thinking**|- "Necesito que me contraten para poder generar ingresos."|- "Espero que la información que publique interese a los clientes."|- "Es importante comunicarse con la persona, sin embargo no llegó a comprender que exactamente desea."|- "El asesoramiento que brinda al ganadero ha sido no tan eficiente pero sí eficaz."|
|**Feeling**|<p>-Estresado por no saber donde debo posicionarme para poder buscar trabajo. </p><p>- Decepcionado por no conocer una página o aplicación que me brinde la facilidad de conectar con mis clientes.</p>|<p>- Preocupado sobre qué dirán las personas al ver lo que ofrezco.</p><p>- Tímido al publicar mi información en mi feed.</p>|<p>- Satisfecho por haber conseguido un cliente dispuesto a contratarme.</p><p>- Confundido porque el cliente no detalla bien qué servicio  desea  de mí.</p>|<p>- Satisfecho de haber culminado mi asesoramiento continuo al cliente.</p><p></p><p>-Frustrado por el tiempo que me demore en asesorar debido a la gran cantidad de herramientas que he usado.</p>|

**Segmento: Criador**

|**Phases**|**Búsqueda de Información y Asesoramiento**|**Comunicación con el Asesor** |**Registro de Datos y Asesoramiento**|**Uso Continuo**|
| :- | :- | :- | :- | :- |
|**Doing**|- Busca información sobre la crianza de cuyes en línea y en libros especializados.|- Contacta a un asesor a través de la aplicación para obtener asesoramiento sobre la crianza de su ganado de cuyes.|<p>- Proporciona detalles sobre su ganado de cuyes, como la cantidad, la salud, la alimentación y otros aspectos relevantes, al asesor. </p><p>- Recibe asesoramiento y recomendaciones del asesor.</p>|- Mantiene una comunicación regular con el asesor para recibir orientación continua sobre la crianza de su ganado de cuyes.|
|**Thinking**|- "Necesito encontrar información precisa y útil para mejorar la crianza de mi ganado de cuyes."|- "Espero que el asesor tenga el conocimiento necesario para ayudarme."|- "Es importante proporcionar datos precisos para recibir un asesoramiento efectivo."|- "La relación continua con el asesor es clave para el éxito de mi ganado de cuyes."|
|**Feeling**|<p>- Motivado por mejorar la salud y la productividad de su ganado de cuyes.</p><p>`- Interesado en aprender más sobre la crianza de cuyes</p>|<p>- Optimista sobre la posibilidad de recibir asesoramiento valioso del asesor.</p><p>- Satisfecho al establecer una comunicación efectiva.</p>|<p>- Satisfecho por recibir recomendaciones que benefician a su ganado de cuyes. </p><p>- Responsable de seguir las recomendaciones del asesor.</p>|<p>- Satisfecho con la relación continua con el asesor. </p><p>- Comprometido con mejorar su ganadería de cuyes a largo plazo.</p>|


## 2.4. Ubiquitous Language

En esta sección, se definirán términos utilizados a lo largo del proyecto para que se pueda comprender para todos los miembros del equipo y agentes interesados. 

- **Guinea pig breeder** (Criador de cuyes): Persona dedicada a la crianza y producción de cuyes con el fin de obtener carne y otros productos derivados de estos animales.
- **Ganadero** (Rancher): Individuo dedicado a la crianza de animales. En este contexto, es otra forma de llamar a los criadores de cuyes, pero de forma más general. Los ganaderos son responsables del cuidado diario de los cuyes, incluida la alimentación, el manejo del hábitat y la reproducción.
- **Advisor** (Asesor): En el contexto del proyecto, es una persona con experiencia y conocimientos especializados en la crianza de cuyes y prácticas agrícolas relacionadas. Su papel es brindar apoyo personalizado para resolver desafíos específicos que enfrentan los criadores en el cuidado de los cuyes.
- **Guinea pig farm** (Granja de cuyes): Instalación destinada a la cría y manejo de cuyes, equipada con las infraestructuras necesarias para su cuidado y reproducción.
- **Animal welfare** (Bienestar animal): Estado de salud física y psicológica de los cuyes que garantiza su crecimiento óptimo, garantizado mediante prácticas de crianza adecuadas que respetan sus necesidades naturales.
- **Sustainable agricultural practices** (Prácticas agrícolas sostenibles): Técnicas y métodos de producción que preservan los recursos naturales y minimizan el impacto ambiental negativo, contribuyendo a la conservación a largo plazo del medio ambiente y los ecosistemas.

- **Self-sustainable** (Auto-sustentable): En el contexto de la crianza de cuyes, se refiere a la práctica de consumir los cuyes criados en la granja principalmente para satisfacer las necesidades alimenticias de los criadores y sus familias. En lugar de venderlos para generar ingresos adicionales.

- **Shed** (Galpón): Es el ambiente donde se construyen o colocan las pozas o jaulas para criar a los cuyes, lo que permite un mejor control de los animales.

- **Cage** (Jaula): Espacio donde vive un grupo de cuyes normalmente construidos de madera o mallas metálicas.

- **Resources** (Recursos): Elementos físicos necesarios para la crianza de cuyes como el alimento que consumen los cuyes, la medicina para los cuyes enfermos, o recursos de producción como pueden ser las pieles de los cuyes.

- **Expenses** (Gastos): Inversiones de dinero del criador para cubrir las necesidades de la crianza como puede ser la compra de los alimentos de los cuyes.

- **Review** (Reseña): Evaluación del desempeño de un asesor durante una cita. Consta de calificación (con rango de 0 a 5 estrellas) y de un comentario opcional.

- **Appointment** (Cita): Encuentro programado entre el criador y el asesor con el objetivo de recibir asistencia técnica en desafíos en la crianza, y con el objetivo de recibir recomendaciones.


# Capítulo III Requirements Specification
## 3.1. To-Be Scenario Mapping
**Segmento: Asesor**<br>

|**Phases**|**Búsqueda de de trabajo**|**Publicar su experiencia en el rubro** |**Comunicación con el ganadero**|**Asesorar al ganadero**|
| :- | :- | :- | :- | :- |
|**Doing**|- Ingreso a la aplicación “AgroConnect” y me registro como asesor.|- Habiendo creado mi cuenta, ingreso a mi perfil y lo diseñó a mi gusto sin límites para que el cliente sepa lo que ofrezco, además resalto mi calificación y las reseñas positivas que he tenido con el asesoramiento a otros clientes.|-Acepto la solicitud que me envió un cliente el cual resalta lo que necesita de manera detallada, luego me comunico con él mediante la misma aplicación y coordino algunos aspectos de la solicitud.|- Me reúno con el ganadero luego de coordinar mediante la aplicación,para luego asesorar usando todas las herramientas que me brinda la aplicación siendo rápido y eficiente.|
|**Thinking**|- "Que bueno que haya un sitio exclusivo para asesores en la ganadería "|- “Me encanta detallar toda mi información de manera concisa."|- "Me encanta lo rápido que es  entender al cliente, gracias a la solicitud detallada que me manda y que de igual manera podamos comunicarnos en la misma aplicación."|- "El asesoramiento que brinda al ganadero ha sido eficiente y rápido debido a las herramientas que me proporciona la aplicación."|
|**Feeling**|<p>-Tranquilo por lo fácil que fue para el registrase en la aplicación. </p><p>- Contento porque existe una aplicación que lo ayude a hacerse más reconocido.</p>|<p>- Entusiasmado en los nuevos clientes que llegare a tener por la información que les he brindado </p><p>` `- Feliz por poder resaltar mi empeño como asesor mediante reseñas y puntajes.</p>|<p>- Satisfecho por haber comprendido al cliente de manera rapido.</p><p>` `- Cómodo por la manera en la cual me he comunicado con el cliente.</p>|<p>- Satisfecho de haber culminado mi asesoramiento continuo al cliente.</p><p></p><p>-Encantado  por las herramientas que me brinda la aplicación para poder asesorar bien al ganadero.</p>|

**Segmento: Criadores**<br>

|**Phases**|**Búsqueda de Información y Asesoramiento**|**Comunicación con el Asesor** |**Registro de Datos y Asesoramiento**|**Uso Continuo**|
| :- | :- | :- | :- | :- |
|**Doing**|<p>- Navega por la aplicación en busca de información relevante sobre la crianza de ganado de cuyes</p><p></p><p></p>|- Inicia una conversación en la aplicación con el asesor para obtener detalles específicos sobre su ganado de cuyes.|<p>- Registra los datos de su ganado de cuyes, incluyendo su salud, alimentación y otros detalles relevantes en la aplicación. </p><p>- Recibe asesoramiento y recomendaciones del asesor.</p>|- Continúa interactuando con el asesor a lo largo del tiempo, el cual le va brindando asesoramiento y seguimiento regular.|
|**Thinking**|- "Necesito encontrar información precisa y útil que me ayude con mi ganado de cuyes"|- "Espero obtener información detallada del asesor para gestionar mi granja de cuyes de manera  adecuada."|- "Es importante proporcionar datos precisos para recibir un asesoramiento efectivo."|- "Mantener una comunicación continua con el asesor es esencial para el éxito de mi granja."|
|**Feeling**|- Interesado mucho más en aprender más sobre la ganadería de cuyes. |- Satisfecho al establecer una comunicación efectiva.|<p>- Satisfecho por contribuir al bienestar de su ganado de cuyes.</p><p> </p>|<p>- Satisfecho con la relación continua con el asesor. </p><p>- Comprometido con el cuidado de su granja.</p>|

## 3.2. User Stories

Se identificaron las siguientes épicas que se componen de las historias de usuario.

<table><tr><th valign="top"><b>Epic ID</b></th><th valign="top"><b>Epic</b></th><th valign="top"><b>User story ID</b></th><th valign="top"><b>User stories</b></th></tr>
<tr><td rowspan="9" valign="top"><b>E01</b></td><td rowspan="9" valign="top">Sistema de búsqueda y programación de citas con asesores y calificaciones</td><td valign="top">US01</td><td valign="top">Catálogo de asesores</td></tr>
<tr><td valign="top">US02</td><td valign="top">Información de un asesor</td></tr>
<tr><td valign="top">US03</td><td valign="top">Visualización de horarios de asesores</td></tr>
<tr><td valign="top">US04</td><td valign="top">Programación de citas con asesores</td></tr>
<tr><td valign="top">US05</td><td valign="top">Visualización de información del criador de cuyes</td></tr>
<tr><td valign="top">US06</td><td valign="top">Notificación de citas al asesor</td></tr>
<tr><td valign="top">US07</td><td valign="top">Notificación de citas al criador</td></tr>
<tr><td valign="top">US08</td><td valign="top">Calificación al asesor luego de una cita</td></tr>
<tr><td valign="top">US14</td><td valign="top">Separar fechas disponibles para asesoría</td></tr>
<tr><td rowspan="2" valign="top"><b>E02</b></td><td rowspan="2" valign="top">Publicaciones en la aplicación</td><td valign="top">US09</td><td valign="top">Gestión de una publicación</td></tr>
<tr><td valign="top">US10</td><td valign="top">Visualización de publicaciones de asesores</td></tr>
<tr><td rowspan="3" valign="top"><b>E03</b></td><td rowspan="3" valign="top">Sistema integral de registro y seguimiento animal</td><td valign="top">US11</td><td valign="top">Gestión de jaulas de cuyes</td></tr>
<tr><td valign="top">US12</td><td valign="top">Registro de información de animales</td></tr>
<tr><td valign="top">US13</td><td valign="top">Visualización y edición de información de animales</td></tr>
<tr><td rowspan="2" valign="top"><b>E04</b></td><td rowspan="2" valign="top">Gestión de granja</td><td valign="top">US15</td><td valign="top">Gestión de recursos de la granja</td></tr>
<tr><td valign="top">US16</td><td valign="top">Gestión de gastos realizados</td></tr>
<tr><td rowspan="2" valign="top"><b>E05</b></td><td rowspan="2" valign="top">Eficiencia y seguridad de aplicación</td><td valign="top">US17</td><td valign="top">Seguridad de información</td></tr>
<tr><td valign="top">US18</td><td valign="top">Disponibilidad y confiabilidad</td></tr>
<tr><td rowspan="3" valign="top"><b>E06</b></td><td rowspan="3" valign="top">Registro, acceso a la aplicación y datos personales</td><td valign="top">US19</td><td valign="top">Registro de un usuario nuevo</td></tr>
<tr><td valign="top">US20</td><td valign="top">Inicio de sesión</td></tr>
<tr><td valign="top">US21</td><td valign="top">Recuperación de contraseña</td></tr>
<tr><td rowspan="6" valign="top"><b>E07</b></td><td rowspan="6" valign="top">Visualización de una Landing Page estática</td><td valign="top">US22</td><td valign="top">Visualización de Navbar y Footer</td></tr>
<tr><td valign="top">US23</td><td valign="top">Visualización de sección de inicio</td></tr>
<tr><td valign="top">US24</td><td valign="top">Visualización de sección“Acerca De”</td></tr>
<tr><td valign="top">US25</td><td valign="top">Visualización de sección “Sobre Nosotros”</td></tr>
<tr><td valign="top">US26</td><td valign="top">Visualización de sección “Características”</td></tr>
<tr><td valign="top">US27</td><td valign="top">Visualización de sección “Contacto”</td></tr>
<tr><td rowspan="3" valign="top"><b>E08</b></td><td rowspan="3" valign="top">Funcionalidades de servicios externos</td><td valign="top">US28</td><td valign="top">Uso de un API para iniciar sesión</td></tr>
<tr><td valign="top">US29</td><td valign="top">Uso de un API para videollamadas</td></tr>
<tr><td valign="top">US30</td><td valign="top">Uso de un API para separar fechas</td></tr>
</table>



|**Epic / Story ID**|**Título**|**Descripción**|**Criterios de Aceptación**|**Relacionado con (Epic ID)**|
| :- | :- | :- | :- | :- |
|US01|Catálogo de asesores|**Como** criador de cuyes **quiero** explorar el catálogo de asesores **para** conocer quiénes me pueden apoyar con asesorías.|<p>**Escenario 1: Explorar el catálogo de asesores**</p><p>**Given** el criador quiere explorar asesores.</p><p>**And** se encuentra en el apartado de “Asesores”.</p><p>**When** seleccione el botón “Catálogo de asesores”.</p><p>**Then** el sistema le mostrará una lista de todos los asesores disponibles en la aplicación.</p><p></p><p>**Escenario 2: Filtrar búsqueda de asesores**</p><p>**Given** el criador quiere filtrar su búsqueda.</p><p>**And** se encuentra en el apartado "Asesores".</p><p>**When** seleccione el botón de filtros.</p><p>**Then** el sistema le permitirá filtrar asesores por ubicación, experiencia o reputación.</p><p></p><p>**Escenario 3: Ver mis asesores**</p><p>**Given** el criador desea ver los asesores a los que les solicitó un servicio para recibir una mentoría.</p><p>**And** se encuentra en el apartado de “Asesores”.</p><p>**When** haga clic en el botón “Mis Asesores”</p><p>**Then** el sistema le mostrará una lista de todos los asesores a los que ha solicitado una cita.</p><p></p>|E01|
|US02|Información de un asesor|**Como** criador de cuyes **quiero** tener acceso a la información de un asesor **para** tomar una decisión informada antes de separar una cita|<p>**Escenario 1: Ver información de un asesor** </p><p>**Given** el criador quiere ver información de un asesor.</p><p>**And se** encuentra en el apartado de “Asesores”.</p><p>**When** seleccione al cuadro de un asesor.</p><p>**Then** el sistema le mostrará la información del asesor como nombre, experiencia, calificación y reseñas.</p><p>**Escenario 2: Fallar al visualizar la información del asesor**</p><p>**Given** el criador quiere ver información de un asesor.</p><p>**And se** encuentra en el apartado de “Asesores”</p><p>**When** seleccione a un asesor.</p><p>**And** se encuentre con un error al cargar la información.</p><p>**Then** el sistema le mostrará un mensaje de error de carga.</p>|E01|
|US03|Visualización de horarios de asesores|**Como** criador de cuyes **quiero** ver los horarios disponibles de los asesores **para** seleccionar un horario que se ajuste a mi agenda|<p>**Escenario 1: Visualizar horarios disponibles**</p><p>**Given** el criador desea visualizar los horarios disponibles de un asesor elegido.</p><p>**And** se encuentra viendo la información del perfil de un asesor.</p><p>**When** haga clic en el botón “Reservar Cita”</p><p>**Then** el sistema le mostrará una interfaz con los horarios disponibles del asesor</p><p></p><p>**Escenario 2: Fallar al intentar visualizar horarios.**</p><p>**Given** el criador desea visualizar los horarios disponibles de un asesor elegido.</p><p>**And** se encuentra viendo la información del perfil de un asesor.</p><p>**When** haga clic en el botón “Reservar Cita”</p><p>**And** el asesor no tenga horarios disponibles</p><p>**Then** el sistema le mostrará un mensaje de error “El asesor no tiene horarios disponibles”.</p>|E01|
|US04|Programación de citas con asesores|**Como** criador de cuyes **quiero** programar una cita con un asesor **para** recibir orientación personalizada|<p>**Escenario 1: Programar una cita**</p><p>**Given** el criador desea programar una cita.</p><p>**And** se encuentra en el apartado de “Horarios Disponibles” del perfil de un asesor.</p><p>**When** seleccione un horario disponible</p><p>**And** complete los campos solicitados.</p><p>**And** haga clic en el botón “Reservar Cita”</p><p>**Then** el sistema le mostrará un mensaje de confirmación.</p><p>**Escenario 2: Fallar al programar una cita**</p><p>**Given** el criador desea programar una cita.</p><p>**And** se encuentra en el apartado de “Horarios Disponibles” del perfil de un asesor.</p><p>**When** seleccione un horario disponible</p><p>**And** se encuentra un error técnico o de conexión que impide completar la programación.</p><p>**Then** el sistema le mostrará un mensaje de error sugiriendo contactar con soporte.</p>|E01|
|US05|Visualización de información del criador de cuyes|**Como** asesor **quiero** tener tener información de la granja del criador de cuyes **para** planificar los temas de la asesoría.|<p>**Escenario 1: Ver información del criador**</p><p>**Given** el asesor desea ver información del criador de cuyes con el que tendrá una asesoría.</p><p>**And** se encuentra en la sección de “Mis Citas”.</p><p>**And** observa que tiene una cita programada con un criador.</p><p>**When** haga clic en la card de la cita.</p><p>**Then** el sistema le permitirá ver información de la granja del criador como número de jaulas y número de cuyes</p><p>**And** mostrará información del criador como nombre, edad y localización.</p><p>**Escenario 2: Fallar al acceder a la información del criador**</p><p>**Given** el asesor desea ver información del criador de cuyes con el que tendrá una asesoría</p><p>**And** se encuentra en la sección de “Mis Citas”.</p><p>**And** observa que tiene una cita programada con un criador</p><p>**When** haga clic en la card de la cita.</p><p>**And** se encuentre con un error al cargar la información</p><p>**Then** el sistema le mostrará un mensaje de error indicando que hubo un error de carga.</p>|E01|
|US06|Notificación de citas al asesor|**Como** asesor, **quiero** recibir notificaciones de citas programadas por los criadores **para** mantenerme al tanto de mis ofertas laborales.|<p>**Escenario 1: Ver notificaciones de cita programadas por criadores**</p><p>**Given** el asesor desea ver sus notificaciones de citas programadas.</p><p>**When** se encuentre en el apartado de “Notificaciones”</p><p>**Then** el sistema le mostrará un mensaje que describe brevemente la solicitud.</p><p></p><p>**Scenario 2: Aceptar notificación de cita programada con el criador**</p><p>**Given** que el asesor decide cerrar la notificación para liberar espacio y permitir la visualización de otras notificaciones.</p><p>**And** se encuentra en la sección de "Notificaciones" del sistema.</p><p>**When** haga clic en el botón "Aceptar" dentro de la notificación correspondiente a la cita programada con el criador.</p><p>**Then**  el sistema eliminará la notificación de la lista.</p>|E03|
|US07|Notificación de citas al criador de cuyes|**Como** criador de cuyes **quiero** recibir notificaciones referentes al estado de mis citas **para** mantenerme al tanto de mi solicitud.|<p>**Escenario 1: Ver notificaciones de cita programadas con los asesores**</p><p>**Given** el criador desea ver sus notificaciones de citas programadas.</p><p>**When** se encuentre en el apartado de “Notificaciones”.</p><p>**Then** el sistema le mostrará un mensaje que describe brevemente la solicitud.</p><p></p><p>**Escenario 2: Aceptar notificación de cita programada con el asesor**</p><p>**Given** que el criador decide cerrar la notificación para liberar espacio y permitir la visualización de otras notificaciones.</p><p>**And** se encuentra en la sección de "Notificaciones" del sistema.</p><p>**When** haga clic en el botón "Aceptar" dentro de la notificación correspondiente a la cita programada con el asesor.</p><p>**Then** el sistema eliminará la notificación de la lista de notificaciones.</p>|EO1|
|US08|Calificación al asesor luego de una asesoría|**Como** criador de cuyes **quiero** calificar al asesor luego de una consulta **para** ayudar a otros criadores a tomar una decisión informada antes de separar una cita.|<p>**Escenario 1: Calificar al asesor**</p><p>**Given** el criador desea hacer un feedback referente al servicio del asesor.</p><p>**And** se encuentra en la vista de calificación del servicio.</p><p>**When** haga clic en el botón “Calificar Servicio”</p><p>**Then** el sistema le permitirá asignarle un número de estrellas y reseñar el servicio del asesor.</p><p>**Escenario 2: Omitir Calificación**</p><p>**Given** el criador no desea dar feedback al asesor referente al servicio.</p><p>**And** se encuentra en la vista de calificación del servicio.</p><p>**When** haga clic en el botón “Omitir calificación”</p><p>**Then** el sistema le permitirá omitir la reseña.</p>|E01|
|US09|Gestión de una publicación|**Como** asesor **quiero** hacer publicaciones **para** tener un mayor alcance hacia los criadores dentro de la aplicación.|<p>**Escenario 1: Crear una nueva publicación**</p><p>**Given** el asesor desea crear una publicación.</p><p>**And** está en el apartado de "Mis Publicaciones".</p><p>**When** hace clic en el botón "Crear Publicación".</p><p>**Then** se le redirige a un formulario donde puede ingresar el contenido de su nueva publicación.</p><p>**And** después de completar el contenido, hace clic en el botón "Publicar".</p><p>**Then** el sistema le mostrará un mensaje de confirmación.</p><p></p><p>**Escenario 2: Eliminar una publicación existente**</p><p>**Given** el asesor desea eliminar una publicación existente.</p><p>**And** está en el apartado de "Mis Publicaciones" de la Sidebar.</p><p>**And** tiene una publicación previamente creada.</p><p>**When** selecciona la opción de eliminar en la publicación que desea borrar.</p><p>**Then** el sistema le mostrará un mensaje de confirmación solicitando la confirmación de la eliminación.</p><p>**And** después de confirmar, la publicación se elimina de su perfil y ya no está disponible para los criadores.</p>|E02|
|US10|Visualización de publicaciones de los asesores|**Como** criador de cuyes **quiero** poder ver las publicaciones de la comunidad de asesores **para** obtener información útil y, si es necesario, solicitar asesoramiento en base a esas publicaciones.|<p>**Escenario 1: Visualizar publicaciones de asesores**</p><p>**Given** el criador desea ver las publicaciones de la comunidad</p><p>**When** haga clic en el botón “Publicaciones” de la Sidebar.</p><p>**Then** el sistema le mostrará una lista de las últimas publicaciones de la comunidad de asesores.</p><p></p><p>**Escenario 2: Filtrar publicaciones de asesores por fecha**</p><p>**Given** el criador desea ver las publicaciones de la comunidad de un tiempo en específico como “esta semana”, “este mes” o ingresar una fecha en específico.</p><p>**And** se encuentra visualizando las publicaciones.</p><p>**When** haga clic en el ícono de filtro.</p><p>**Then** el sistema le permitirá filtrar las publicaciones por el parámetro elegido.</p>|E02|
|US11|Gestión de jaulas de cuyes|**Como** criador de cuyes **quiero** poder registrar una jaula en la plataforma **para** poder gestionar la información de mis cuyes de manera organizada.|<p>**Escenario 1: Registro de una jaula**</p><p>**Given** que el criador desea registrar una jaula.</p><p>**And** se encuentra en el apartado "Registro".</p><p>**When** haga clic en el botón "Registrar Jaula".</p><p>**And** completa el formulario con la información requerida de la jaula como nombre, tamaño y observaciones.</p><p>**And** hace clic en el botón "Registrar Jaula".</p><p>**Then** el sistema le mostrará un mensaje del registro exitoso de la jaula.</p><p>**Escenario 2: Eliminar jaula**</p><p>**Given** que el criador desea eliminar una jaula.</p><p>**And** se encuentra en una jaula del apartado "Mis Animales".</p><p>**When** haga clic en el botón "Borrar".</p><p>**Then** el sistema le mostrará un mensaje de confirmación solicitando la confirmación de la eliminación.</p><p>**And** después de confirmar, la jaula se elimina junto a la información de los cuyes asignados a esa jaula.</p>|E03|
|US12|Registro de información de un animal|**Como** criador de cuyes **quiero** contar con un sistema de registro de animales **para** almacenar información básica sobre cada animal, incluyendo su número de identificación, nombre, raza, género, peso y fecha de nacimiento.|<p>**Escenario 1: Registrar un nuevo animal**</p><p>**Given** el criador desea registrar un cuy en su jaula.</p><p>**And** se encuentra en el apartado de “Registro”.</p><p>**When** haga clic en el botón ”Nuevo cuy”</p><p>**And** ingresa la información básica del animal, incluyendo su número de identificación, número de jaula dónde se va a encontrar, raza, género, peso y fecha de nacimiento,</p><p>**And** haga clic “Registrar”</p><p>**Then** el sistema le mostrará una confirmación del registro.</p><p>**Escenario 2: Fallar en el registro de animal**</p><p>**Given** el criador desea registrar un cuy en su jaula.</p><p>**And** se encuentra en el apartado de “Registro”.</p><p>**When** haga clic en el botón ”Nuevo cuy”</p><p>**And** intenta ingresar la información del animal pero no completa todos los campos obligatorios para el registro.</p><p>**And** haga clic en “Registrar”.</p><p>**Then** el sistema le mostrará un mensaje de error.</p>|E03|
|US13|Visualización y edición de información de animales|**Como** criador de cuyes **quiero** acceder a la información de un animal **para** visualizar o actualizar su información registrada.|<p>**Escenario 1: Buscar y visualizar la información de un animal registrado**</p><p>**Given** el criador tiene varios cuyes registrados en la aplicación y desea editar la información de uno en específico.</p><p>**And** se encuentra en el apartado de “Mis Animales”</p><p>**When** haga clic en "Ver" de una jaula</p><p>**And** seleccione el card de un cuy específico.</p><p>**Then** el sistema le mostrará la información detallada del cuy.</p><p>**Escenario 2: Actualizar información de un animal registrado**</p><p></p><p>**Given** el criador tiene varios cuyes registrados en la aplicación y desea editar la información de uno en específico.</p><p>**And** se encuentra viendo la información detallada de un cuy. </p><p>**When** haga clic en el botón “Editar”.</p><p>**And** realiza cambios en la información del cuy.</p><p>**Then** el sistema actualizará la información detallada del cuy</p>|E03|
|US14|Separar fechas disponibles para asesoría|**Como** asesor **quiero** poder seleccionar y separar las fechas y horas en las que estoy disponible para ofrecer asesorías **para** que los usuarios interesados puedan ver mis horarios disponibles y agendar una cita en un momento conveniente.|<p>**Escenario 1: Registrar disponibilidad para asesorías**</p><p>**Given** el asesor desea registrar sus fechas y horas disponibles para asesorías.</p><p>**And** está visualizando la página de "Horario disponible"</p><p>**When** haga clic en el botón “Agregar”</p><p>**And** complete los datos del nuevo horario disponible que tiene el asesor</p><p>**Then** el sistema actualizará y guardará las fechas y horas seleccionadas como disponibles.</p><p></p><p>**Escenario 2: Cancelar intención de modificar disponibilidad**</p><p>**Given** el asesor se ha equivocado al seleccionar una fecha o intervalo de tiempo para modificar.</p><p>**And** se encuentra visualizando los cambios antes de guardar.</p><p>**When** haga clic en el botón “Cancelar”</p><p>**Then** el sistema lo redireccionará a la vista original de sus fechas y horas disponibles sin aplicar los cambios.</p><p></p>|E01|
|US15|Gestión de recursos de la granja|**Como** criador de cuyes **quiero** registrar los recursos de mi granja **para** tener un control sobre los recursos esenciales como alimentos y medicamentos.|<p>**Registrar de nuevo ingreso de recursos en el inventario**</p><p>**Given** eel criador ha recibido el pedido de recursos por parte del proveedor y desea registrar esto en su inventario.</p><p>**And** se encuentra en el apartado de “Registro” de la Sidebar.</p><p>**When** haga clic en el botón “Nuevo Recurso”</p><p>**And** ingresa los detalles de nombre y tipo de recurso, fecha, cantidad y observación.</p><p>**Then** el sistema mostrará una confirmación.</p><p></p><p>**Escenario 2: Ver recursos**</p><p>**Given** el criador desea ver los recursos que posee.</p><p>**And** se encuentra en el apartado de “Mi Granja” de la Sidebar.</p><p>**When** haga clic en el botón “Gestión de Recursos”.</p><p>**Then** el sistema le permitirá visualizar sus recursos que incluyen datos como el nombre del recurso, el tipo de recurso (alimento, medicina, cultivo u otro) y la fecha en el que fue registrado este recurso.</p>|E04|
|US16|Gestión de gastos realizados|**Como** criador de cuyes **quiero** registrar gastos relacionados con mi negocio **para** tener un control y poder tomar decisiones financieras que serán útiles para tener una mejor rentabilidad.|<p>**Escenario 1: Registrar gasto**</p><p>**Given** el criador desea registrar los gastos que ha realizado.</p><p>**And** se encuentra en el apartado de “Registro” de la Sidebar.</p><p>**When** haga clic en el botón “gastos”</p><p>**And** ingrese datos como el precio, tipo de gasto, fecha y demás campos.</p><p>**Then** el sistema registrará correctamente los detalles del gasto.</p><p></p><p>**Escenario 2: Ver gasto registrado**</p><p>**Given** el criador desea ver un gasto ya registrado.</p><p>**And** se encuentra en el apartado de “Mi Granja” de la Sidebar.</p><p>**When** haga clic en el botón “Gestión de gastos”.</p><p>**Then** el sistema le permitirá visualizar sus gastos.</p><p>**Escenario 3: Ver gasto registrado**</p><p>**Given** el creador desea ver un recurso de un tipo en específico.</p><p>**And** se encuentra en la sección de “Gestión de Gastos”del apartado de “Mi Granja”</p>p>**When**seleccione el tipo de gasto que desea filtrar (todos, salud, alimento, Mantenimiento de criadero)</p><p>**And**And haga clic en el botón “Filtrar”</p><p>**Then** el sistema le mostrará una lista de todos los recursos que pertenezcan a ese tipo.|E04|
|US17|Seguridad de información|**Como** criador/asesor **quiero** que la aplicación cumpla con los estándares de seguridad **para** proteger mi información registrada.|<p>**Escenario 1: Seguridad en la conexión web**</p><p>**Given** el usuario desea que la aplicación sea segura para su uso personal.</p><p>**When** ingrese a la aplicación para hacer uso de ella.</p><p>**Then** la aplicación usará conexión segura https para enviar datos.</p>|E05|
|US18|Disponibilidad y confiabilidad|**Como** criador/asesor **quiero** que la aplicación esté disponible siempre **para** acceder a ella en cualquier momento y sin interrupciones.|<p>**Escenario 1: Acceso a la aplicación en todo momento**</p><p>**Given** el usuario desea usar la aplicación en cualquier instante.</p><p>**When** ingrese a la aplicación.</p><p>**Then** la aplicación se encuentra disponible y funcional.</p><p></p><p>**Escenario 2: Acceso a la aplicación sin interrupciones**</p><p>**Given** el usuario desea usar la aplicación en cualquier instante.</p><p>**When** ingresa a la aplicación.</p><p>**Then** la aplicación carga rápidamente y controla el tráfico para que la experiencia sea fluida.</p>|E05|
|US19|Registro de un usuario nuevo|**Como** usuario **quiero** registrarme **para** acceder a las funciones de usuario.|<p>**Escenario 1: Registro de cuenta por formulario**</p><p>**Given** el usuario desea registrarse en la aplicación.</p><p>**And** se encuentra en el apartado de “Registrarse”.</p><p>**When** complete el formulario de registro con su información personal.</p><p>**And** seleccione su rol en la aplicación entre “Criador” o “Asesor”</p><p>**And** los datos** sean correctos según las validaciones establecidas.</p><p>**Then** la cuenta se creará.</p><p></p><p>**Escenario 2: Registro incorrecto de cuenta**</p><p>**Given** el criador/asesor se encuentra en el apartado de “Registrarse”.</p><p>**When** ingrese la información solicitada de manera errónea.</p><p>**Then** la cuenta no se creará.</p><p>**And** recibirá un mensaje indicando el error.</p>|E06|
|US20|Inicio de sesión|**Como** usuario **quiero** acceder a mi cuenta registrada **para** acceder a las funciones de usuario.|<p>**Escenario 1: Inicio de sesión exitoso**</p><p>**Given** el criador/asesor desea acceder a su cuenta registrada. </p><p>**And** se encuentra en el apartado de “Acceder”.</p><p>**When** introduzca sus credenciales correctamente.</p><p>**Then** recibirá un mensaje de bienvenida.</p><p>**And** será redireccionado a su vista de usuario.</p><p></p><p>**Escenario 2: Inicio de sesión fallido**</p><p>**Given** el criador/asesor desea acceder a su cuenta registrada. </p><p>**And** se encuentra en el apartado de “Acceder”.</p><p>**When** introduzca sus credenciales incorrectamente.</p><p>**Then** no se le permitirá acceso a su cuenta.</p><p>**And** recibirá un mensaje indicando el error.</p><p></p><p>**Escenario 3: Bloqueo de sesión por exceso de intentos**</p><p>**Given** el criador/asesor desea acceder a su cuenta registrada. </p><p>**And** se encuentra en el apartado de “Acceder”.</p><p>**When** introduzca sus credenciales incorrectamente.</p><p>**And** siga errando hasta alcanzar el número máximo de intentos permitidos (tres intentos).</p><p>**Then** recibirá un mensaje que le informe que ha excedido el número de intentos permitidos.</p><p>**And** su cuenta será bloqueada temporalmente.</p><p>**And** se le pedirá actualizar contraseña.</p>|E06|
|US21|Recuperación de contraseña|**Como** usuario **quiero** poder recuperar mi contraseña **para** acceder a mi cuenta.|<p>**Escenario 1: Recuperación de contraseña**</p><p>**Given** el usuario olvidó su contraseña</p><p>**When** se dirija a la sección de “Inicio de sesión”</p><p>**And** seleccione “olvidé mi contraseña”</p><p>**And** coloque su correo vinculado a la cuenta.</p>><p>**Then** se le enviará un correo para que cambie su contraseña.</p>|E06|
|US22|Visualización de Navbar y Footer|**Como** potencial usuario **quiero** navegar con facilidad **para** movilizarme a través de la página y conocer sobre la aplicación.|<p>**Escenario 1: Visualización de Navbar y Footer**</p><p>**Given** el usuario desea conocer sobre la aplicación.</p><p>**When** ingresa al Landing Page,</p><p>**Then** se mostrará el Navbar y Footer que permitirá al usuario navegar con facilidad.</p>|E07|
|US23|Visualización de sección de inicio|**Como** potencial usuario **quiero** acceder a una página de inicio **para** conocer la idea principal de la aplicación y ver un diseño agradable.|<p>**Escenario 1: Visualización de página de inicio**</p><p>**Given** el usuario desea conocer sobre la aplicación.</p><p>**When** ingresa al Landing Page.</p><p>**Then** se mostrará la página inicial sencilla que da a entender la idea principal.</p>|E07|
|US24|Visualización de sección “Acerca De”|**Como** potencial usuario **quiero** acceder a una página sobre el problema que resuelve **para** conocer el propósito de la aplicación.|<p>**Escenario 1: Visualización de página Acerca De**</p><p>**Given** el usuario desea conocer sobre el problema que resuelve la aplicación</p><p>**When** ingresa al Landing Page</p><p>**And** ingresa a la sección Acerca De</p><p>**Then** se mostrará la página Acerca De, en la que se detalla la problemática que resolverá la aplicación.</p>|E07|
|US25|Visualización de sección “Sobre Nosotros”|**Como** potencial usuario **quiero** acceder a una página sobre la startup **para** conocer el propósito de la empresa detrás de la aplicación.|<p>**Escenario 1: Visualización de página Sobre Nosotros**</p><p>**Given** el usuario desea conocer sobre la empresa detrás de la aplicación.</p><p>**When** ingresa al Landing Page</p><p>**And** ingresa a la sección Sobre Nosotros</p><p>**Then** se mostrará la página Sobre Nosotros, en la que detalla información sobre la startup, su misión y visión.</p>|E07|
|US26|Visualización de sección “Características”|**Como** potencial usuario **quiero** acceder a una página sobre las características **para** conocer las principales funcionalidades de la aplicación.|<p>**Escenario 1: Visualización de página Características**</p><p>**Given** el usuario desea conocer sobre las características de la aplicación</p><p>**When** ingresa al Landing Page</p><p>**And** ingresa a la sección Características</p><p>**Then** se mostrará la página Características en la que detalla información sobre las funcionalidades principales que ofrece la aplicación.</p>|E07|
|US27|Visualización de sección “Contacto”|**Como** potencial usuario **quiero** acceder a una página de contacto **para** poder contactar con la empresa en caso tenga algún problema, duda o sugerencia.|<p>**Escenario 1: Visualización de página Contacto**</p><p>**Given** el usuario desea contactar con el área de soporte de la empresa</p><p>**When** ingresa al Landing Page</p><p>**And** ingresa a la sección Contacto</p><p>**Then** se mostrará la página Contacto, en la que se muestra los medios de contacto que puede usar el usuario para hacer consultas.</p>|E07|
|US28|Uso de un API para iniciar sesión| **Como** desarrollador **quiero** integrar el inicio de sesión utilizando la API de Google **para** facilitar el acceso a la aplicación | <p>**Escenario 1: Inicio de sesión con cuenta de Google**</p><p>**Given** el usuario quiere acceder a la aplicación</p><p>**When**seleccione ingreso por cuenta de Google</p><p>**Then** el sistema verificará las credenciales de su cuenta de Google para permitir su acceso</p> | E08 |
|US29|Uso de un API para videollamadas| **Como** desarrollador **quiero** integrar la creación de videollamadas utilizando la API de Google Meet **para** facilitar las asesorías en la aplicación | <p>**Escenario 1: Creación de videollamada**</p><p>**Given** el usuario tiene una asesoría pendiente</p><p>**When**seleccione la opción de ingresar a la asesoría</p><p>**Then** el sistema genera el enlace a una videollamada de Google Meet para que el usuario acceda a su asesoría</p> | E08 |
|US30|Uso de un API para separar fechas| **Como** desarrollador **quiero** integrar la API del calendario de Google **para** que los usuarios puedan sincronizar sus citas entre nuestra plataforma y sus calendarios personales | <p>**Escenario 1: Sincronización de citas**</p><p>**Given** el usuario ha separado una asesoría</p><p>**When**seleccione la opción de sincronizar citas</p><p>**Then** el sistema utiliza la API del calendario de Google para agregar la cita</p> | E08 |

## 3.3. Impact Mapping
**Segmento: Asesor**

<img src="img/impactmap_1.png" alt="ImpactMap Asesor">
 
 _Imagen 20. impact map - asesor_

**Segmento: Criadores**

<img src="img/impactmap_2.png" alt="ImpactMap Criador">
 
 _Imagen 21. impact map - criador_
 
 ## 3.4. Product Backlog

 Para trabajar el Product Backlog, se utilizó la herramienta Pivotal Tracker, la cual se encuentra en el siguiente enlace: <https://www.pivotaltracker.com/n/projects/2699734>

 <img src="img/product_backlog.jpg" alt="Product backlog">

  _Imagen 22. Product backlog_

|**# Orden**|**User Story Id**|**Título**|**Descripción**|**Story Points (1/2/3/5/8)**|
| :- | :- | :- | :- | :- |
|1|US22|Visualización de Navbar y Footer|**Como** potencial usuario **quiero** navegar con facilidad **para** movilizarme a través de la página y conocer sobre la aplicación.|2|
|2|US23|Visualización de sección de inicio|**Como** potencial usuario **quiero** acceder a una página de inicio **para** conocer la idea principal de la aplicación y ver un diseño agradable.|1|
|3|US24|Visualización de sección de inicio “Acerca De”|**Como** potencial usuario **quiero** acceder a una página sobre el problema que resuelve **para** conocer el propósito de la aplicación.|2|
|4|US25|Visualización de sección de inicio “Sobre Nosotros”|**Como** potencial usuario **quiere** acceder a una página sobre la startup **para** conocer el propósito de la empresa detrás de la aplicación.|2|
|5|US26|Visualización de sección de inicio “Características”|**Como** potencial usuario **quiero** acceder a una página sobre las características **para** conocer las principales funcionalidades de la aplicación.|2|
|6|US27|Visualización de sección de inicio “Contacto”|**Como** potencial usuario **quiero** acceder a una página de contacto **para** poder contactar con la empresa en caso tenga algún problema, duda o sugerencia.|2|
|7|US01|Catálogo de asesores|**Como** criador de cuyes **quiero** explorar el catálogo de asesores **para** conocer quiénes me pueden apoyar con asesorías.|5|
|8|US02|Información de un asesor|**Como** criador de cuyes **quiero** tener acceso a la información de un asesor **para** tomar una decisión informada antes de separar una cita.|3|
|9|US03|Visualización de horarios de asesores|**Como** criador de cuyes **quiero** ver los horarios disponibles de los asesores **para** seleccionar un horario que se ajuste a mi agenda.|3|
|10|US04|Programación de citas con asesores|**Como** criador de cuyes **quiero** poder programar una cita con un asesor **para** recibir orientación personalizada|8|
|11|US05|Visualización de información del criador de cuyes|**Como** asesor **quiero** tener tener información de la granja del criador de cuyes **para** planificar los temas de la asesoría.|5|
|12|US06|Notificación de citas al asesor|**Como** asesor, **quiero** recibir notificaciones de citas programadas por los criadores **para** mantenerme al tanto de mis ofertas laborales.|3|
|13|US07|Notificación de citas al criador de cuyes|**Como** criador de cuyes **quiero** recibir notificaciones referentes al estado de mis citas **para** mantenerme al tanto de mi solicitud.|3|
|14|US08|Calificación al asesor luego de una asesoría|**Como** criador de cuyes **quiero** calificar al asesor luego de consulta **para** ayudar a otros criadores a tomar una decisión informada antes de separar una cita.|5|
|15|US09|Gestión de una publicación|**Como** asesor **quiero** hacer publicaciones **para** tener una mayor visibilidad.|5|
|16|US10|Visualización de publicaciones de los asesores|**Como** criador de cuyes **quiero** poder ver las publicaciones de la comunidad de asesores **para** obtener información útil y, si es necesario, solicitar asesoramiento en base a esas publicaciones.|5|
|17|US11|Gestión de jaulas de cuyes|**Como** criador de cuyes **quiero** poder registrar una jaula en la plataforma **para** poder gestionar la información de mis cuyes de manera organizada.|3|
|18|US12|Registro de información de un animal|**Como** criador de cuyes **quiero** contar con un sistema de registro de animales **para** almacenar información básica sobre cada animal, incluyendo su número de identificación, nombre, raza, género, peso y fecha de nacimiento.|3|
|19|US13|Visualización y edición de información de animales|**Como** criador de cuyes **quiero** acceder a la información de un animal **para** visualizar o actualizar su información registrada.|8|
|20|US14|Separar fechas disponibles para asesoría|**Como** asesor **quiero** poder seleccionar y separar las fechas y horas en las que estoy disponible para ofrecer asesorías **para** que los usuarios interesados puedan ver mis horarios disponibles y agendar una cita en un momento conveniente.|3|
|21|US15|Gestión de recursos de la granja|**Como** criador de cuyes **quiero** gestionar los recursos de mi granja **para** tener un control sobre los recursos esenciales como alimentos y medicamentos.|8|
|22|US16|Gestión de gastos realizados|**Como** criador de cuyes **quiero** gestionar los gastos relacionados con mi negocio **para** tener un control y poder tomar decisiones financieras que serán útiles para tener una mejor rentabilidad.|8|
|23|US28|Uso de un API para iniciar sesión|**Como** desarrollador **quiero** integrar el inicio de sesión utilizando la API de Google **para** facilitar el acceso a la aplicación.|3|
|24|US29|Uso de un API para videollamadas|**Como** desarrollador **quiero** integrar la creación de videollamadas utilizando la API de Google Meet **para** facilitar las asesorías en la aplicación.|5|
|25|US30|Uso de un API para separar fechas|**Como** desarrollador **quiero** integrar la API del calendario de Google **para** que los usuarios puedan sincronizar sus citas entre nuestra plataforma y sus calendarios personales.|5|
|26|US17|Seguridad de información|**Como** criador/asesor **quiero** que la aplicación cumpla con los estándares de seguridad **para** proteger mi información registrada.|5|
|27|US18|Disponibilidad y confiabilidad|**Como** criador/asesor **quiero** que la aplicación esté disponible siempre **para** acceder a ella en cualquier momento y sin interrupciones.|3|
|28|US19|Registro de un usuario nuevo|**Como** usuario **quiero** registrarme **para** acceder a las funciones de usuario.|3|
|29|US20|Inicio de sesión|**Como** usuario **quiero** acceder a mi cuenta registrada **para** acceder a las funciones de usuario.|3|
|30|US21|Recuperación de contraseña|**Como** usuario **quiero** poder recuperar mi contraseña **para** acceder a mi cuenta.|5|



# Capítulo IV: Product Design

## 4.1. Style Guidelines

La importancia del estilo de un producto radica en la creación de una experiencia visual armoniosa y atractiva para los usuarios. A continuación, se presentará una descripción detallada de las pautas de estilo de nuestro proyecto.

### 4.1.1. General Style Guidelines

**Consistencia Visual**

Garantizar una apariencia uniforme en todos los aspectos del producto, desde la disposición de la interfaz de usuario hasta los elementos visuales. Esto implica seleccionar colores coherentes, tipografía adecuada, estilos consistentes y una navegación web intuitiva.

<p align="center">
  <img src="img/consistencia-visual.webp" alt="Ejemplo de consistencia visual" width="600">
</p>

_Imagen 23. Ejemplo de consistencia visual_

**Simplicidad**

Enfatizar la simplicidad en el diseño para una experiencia de usuario intuitiva y evitar el uso excesivo de elementos que puedan hacer perder el foco de atención al usuario.

<p align="center">
  <img src="img/simplicidad.jpg" alt="Ejemplo de simplicidad" width="600">
</p>

_Imagen 24. Ejemplo de simplicidad_

**Branding**

El logotipo de AgroConnect se presenta en forma de un círculo, que simboliza la unidad y la conexión dentro de las comunidades agrícolas peruanas. En el centro del círculo se encuentra un cuy, animal característico de las granjas peruanas y un símbolo de la agricultura local. El cuy está representado de manera amigable y sonriente, transmitiendo la naturaleza acogedora y cercana de la plataforma. El cuy lleva un pequeño gorro de granjero como un guiño a la laboriosa comunidad agrícola.

<p align="center">
  <img src="img/logo.png" alt="logo de AgroConnect" width="200">
</p>

_Imagen 25. Logo de AgroConnect_

**Typography**

La tipografía elegida para AgroConnect es "Inter", una fuente sans-serif moderna y altamente legible. Este tipo de letra se destaca por su estilo limpio y contemporáneo, lo que comunica profesionalismo y actualización. La elección de Inter asegura que el texto en las interfaces de usuario sea fácilmente legible y tenga una apariencia moderna y uniforme. Además, Inter es una fuente versátil que ofrece una amplia variedad de pesos y estilos, lo que permite una adaptación flexible a diferentes contextos y tamaños de texto en la aplicación.

<p align="center">
  <img src="img/font1.png" alt="Fuentes" width="600">
</p>

_Imagen 26. Fuentes_

**Colors**

AgroConnect ha seleccionado una paleta de colores que comunica confiabilidad y eficiencia en la contratación de asesores especializados y en el uso de herramientas avanzadas. Los tonos predominantes, como los marrones, amarillos y anaranjados, transmiten una sensación cálida que evoca la calidez y la energía de la naturaleza presente en las granjas peruanas. Esta elección de colores no solo refleja la conexión con la tierra y las raíces agrícolas, sino que también sugiere un ambiente acogedor y estimulante para los usuarios de la plataforma.

**Spacing**

El spacing garantiza una distribución uniforme y un equilibrio visual en la interfaz. Se han establecido las siguientes medidas.

````
 - Botones: padding de 16px vertical y 32px horizontal 
 - Margin entre texto 16px 
 - Margin entre elementos 24px 
 - Margin entre secciones 72px
````

**Diseño Visual con Patrón Z**

 Vamos a incorporar el conocido Patrón Z en nuestro diseño visual, el cual dirige de manera intuitiva la atención del usuario a través de la interfaz. Este enfoque implica estratégicamente ubicar los elementos clave en las esquinas superior e inferior izquierdas, mientras que los elementos secundarios se colocan en las esquinas superior e inferior derechas. Este diseño genera un flujo visual eficaz y atractivo que mejora la experiencia del usuario.

<p align="center">
  <img src="img/patronZ.png" alt="Patron Z ejemplo" width="600">
</p>

_Imagen 27. Ejemplo de Patron Z_

### 4.1.2. Web Style Guidelines

**Colors**

AgroConnect ha seleccionado cuidadosamente una paleta de colores que refleja los valores y la identidad de la plataforma. Los tonos elegidos comunican confiabilidad y eficiencia en la contratación de asesores especializados y en el uso de herramientas avanzadas.

<p align="center">
  <img src="img/colors.png" alt="Colores de AgroConnect" width="600">
</p>

_Imagen 28. Colores de AgroConnect_

**Typography**

La tipografía desempeña un papel fundamental en la apariencia y la legibilidad de AgroConnect. Hemos seleccionado cuidadosamente la fuente "Inter", una fuente sans-serif moderna y altamente legible.

<p align="center">
  <img src="img/font2.png" alt="Tipografia de AgroConnect" width="600">
</p>

_Imagen 29. Tipografia de AgroConnect_

**Icons**

Los íconos desempeñan un papel importante en la experiencia del usuario al proporcionar una representación visual rápida y reconocible de diversas funciones y características dentro de AgroConnect. Hemos seleccionado una colección de íconos que son consistentes con la identidad visual de la plataforma y que refuerzan su propósito y temática agrícola.

<p align="center">
  <img src="img/icons.png" alt="Iconos de AgroConnect" width="600">
</p>

_Imagen 30. Iconos de AgroConnect_

**Spacing**

El espaciado adecuado entre elementos es esencial para lograr una apariencia equilibrada y una experiencia de usuario cómoda en AgroConnect. Hemos establecido pautas claras de espaciado que garantizan coherencia y claridad en toda la plataforma.

<p align="center">
  <img src="img/spacing.png" alt="Spacing de AgroConnect" width="600">
</p>

_Imagen 31. Spacing de AgroConnect_

**Grid System**

El grid system es una herramienta esencial en el diseño y la organización de la interfaz de usuario de AgroConnect. Proporciona una estructura visual que ayuda a distribuir y alinear los elementos de la página de manera consistente y armoniosa en diferentes tamaños de pantalla.

<p align="center">
  <img src="img/grid.png" alt="Grid System de AgroConnect" width="600">
</p>

_Imagen 32. Grid System de AgroConnect_

**Button**

Los botones son elementos importantes en la interfaz de usuario de AgroConnect, ya que proporcionan una forma clara y visualmente destacada para que los usuarios realicen acciones importantes. Hemos definido un estilo de botón consistente que refleja la identidad visual de la plataforma y promueve una experiencia de usuario intuitiva y coherente.

<p align="center">
  <img src="img/button.png" alt="Button de AgroConnect" width="600">
</p>

_Imagen 33. Button de AgroConnect_

**Input System**

El input system es fundamental en la experiencia del usuario en AgroConnect, ya que proporciona formas para que los usuarios ingresen datos y realicen acciones dentro de la plataforma. Hemos definido un sistema de entrada consistente que garantiza una experiencia de usuario intuitiva y coherente en toda la interfaz.

<p align="center">
  <img src="img/input-system.png" alt="Input Sys AgroConnect" width="600">
</p>

_Imagen 34. Input System de AgroConnect_

## 4.2. Information Architecture

La arquitectura de información desempeña un papel fundamental en la organización y estructuración del contenido para garantizar su accesibilidad y comprensión por parte de los usuarios. En este apartado, se detallarán los sistemas de organización, etiquetado, etiquetas SEO y metaetiquetas, sistema de búsqueda y sistemas de navegación que componen la arquitectura de la información de nuestro producto.

### 4.2.1. Organization Systems

En AgroConnect, aplicamos un sistema de jerarquía visual para resaltar la información esencial y relevante, garantizando que los usuarios encuentren fácilmente lo que necesitan. Utilizamos una organización secuencial para guiar intuitivamente a los usuarios a través del proceso de registro y búsqueda de asesores o asesoría. En lo que respecta a la categorización de contenido, está organizado según audiencia (Criadores y Asesores)

### 4.2.2. Labeling Systems

En el proyecto AgroConnect se eligió implementar un sistema de etiquetado breve y fácil de comprender para los usuarios. Las etiquetas que se utilizarán son las siguientes:


**Vista de Criador:**

<table>
  <tbody>
  <tr>
      <th>My Farm - Mi Granja</th>
      <td>Se implementará un botón que permitirá a los usuarios gestionar su inventario, que incluirá medicamentos, producción de carne, fertilizante y otros elementos relacionados.</td>
  </tr>
  <tr>
      <th>Advisors - Mis asesores</th>
      <td>Se implementará un botón que permitirá a los usuarios contactar con asesores.</td>
  </tr>
  <tr>
      <th>My animals - Mis animales</th>
      <td>Se implementará un botón que permitirá al usuario llevar un registro y seguimiento de los animales en la granja.</td>
  </tr>
  <tr>
      <th>Calendar - Calendario</th>
      <td>Se implementará un botón que permitirá visualizar un calendario con las tareas, eventos y actividades registradas.</td>
  </tr>
  <tr>
      <th>Registry - Registro</th>
      <td>Se implementará un botón que permitirá al usuario registrar información de nuevos animales, datos de la gastos y recursos.</td>
  </tr>
  <tr>
      <th>Notifications - Notificaciones</th>
      <td>Se implementará un botón que permitirá visualizar notificaciones respecto a las solicitudes de las ofertas de empleo.</td>
  </tr>
  <tr>
      <th>Logout</th>
      <td>Se implementará un botón que permitirá al usuario desvincularse de su cuenta.</td>
  </tr>
  </tbody>
</table>

<br></br>
**Vista de Asesor:**

<table>
  <tbody>
  <tr>
      <th>Home - Inicio</th>
      <td>Se implementará un botón que permitirá al usuario ver publicaciones de clientes y poder ofertar.</td>
  </tr>
  <tr>
      <th>My clients - Mis clientes</th>
      <td>Se implementará un botón que permitirá a los usuarios ver su clientes.</td>
  </tr>
  <tr>
      <th>My publications - Mis publicaciones</th>
      <td>Se implementará un botón que permitirá al usuario ver el historial de sus publicaciones de ofertas de trabajo.</td>
  </tr>
  <tr>
      <th>Notifications - Notificaciones</th>
      <td>Se implementará un botón que permitirá visualizar notificaciones respecto a las solicitudes de las ofertas de empleo y recordatorios de citas pendientes.</td>
  </tr>
  <tr>
      <th>Logout</th>
      <td>Se implementará un botón que permitirá al usuario desvincularse de su cuenta.</td>
  </tr>
</table>

### 4.2.3. SEO Tags and Meta Tags

Las Search Engine Optimization (Etiquetas SEO) y las Meta Tags (Meta Etiquetas) juegan un papel vital en la visibilidad y el posicionamiento del contenido en los motores de búsqueda. Existen varios tipos de etiquetas SEO y metaetiquetas, y a continuación se destacan algunas de las más relevantes para la empresa:

- **Metaetiqueta de Descripción (Meta Description Tag):** Esta etiqueta ofrece una breve   descripción del contenido de la página. Aunque no influye directamente en el ranking de búsqueda, una meta descripción bien redactada puede aumentar la tasa de clics (CTR) al proporcionar a los usuarios una visión clara del contenido de la página.

````
<meta name="description" content="AgroTech ofrece soluciones tecnológicas innovadoras para mejorar la gestión de granjas de cuyes. Nuestra misión es empoderar a los granjeros con herramientas inteligentes y eficientes.">
````

**Metaetiqueta de Autor (Meta Autor Tag):** Esta etiqueta especifica el autor del contenido de la página. Esto puede ser útil para atribuir la propiedad intelectual o identificar la fuente del contenido.

````
<meta name="author" content="AgroTech">
````

**Etiqueta de Título (Title Tag):** Esta etiqueta es esencial para el SEO, ya que define el título de una página web y aparece como el título principal en los resultados de búsqueda. 

````
<title>AgroConnect</title>
````

**Etiqueta de Idioma (Language Tag):** Esta etiqueta especifica el idioma principal del contenido de la página. Es útil para la clasificación en búsquedas locales y ayuda a los motores de búsqueda a comprender el idioma del contenido.

````
<html lang="en">
````

**Metaetiqueta de Robots (Meta Robots Tag):** Esta etiqueta indica a los motores de búsqueda cómo indexar y rastrear la página. Puede especificar si la página debe ser indexada, si deben seguirse los enlaces o si se deben seguir ciertas instrucciones específicas.

````
<meta name="robots" content="index, follow"> 
````

<p align="center">
  <img src="img/seotags.JPG" alt="SEO tags" width="600">
</p>

_Imagen 35. SEO tags de AgroConnect_

### 4.2.4. Searching Systems

La aplicación AgroConnect desarrollará un sistema de búsqueda intuitivo, diseñado para que los usuarios encuentren rápidamente la información que necesitan. Este sistema se basará en filtros inteligentes que simplificarán la búsqueda de asesores, evitando así que los usuarios se vean abrumados por la cantidad de información disponible. Con esta mejora, nuestra aplicación garantizará una experiencia de usuario más fluida y satisfactoria al buscar información relevante.

<table>
  <tbody>
  <tr>
      <th>Ubicación</th>
      <td>Permite al usuario buscar asesores o recibir solicitudes de asesoramiento basadas en su ubicación actual o en una ubicación específica.</td>
  </tr>
  <tr>
      <th>Tipo de Asesoría</th>
      <td>Permite al usuario buscar según el tipo de asesoría ofrecida.</td>
  </tr>
  <tr>
      <th>Presupuesto</th>
      <td>Permite al usuario buscar asesores que se ajusten a su presupuesto.</td>
  </tr>
  <tr>
      <th>Experiencia</th>
      <td>Permite al usuario buscar asesores con un nivel de experiencia específico.</td>
  </tr>
  <tr>
      <th>Reputación</th>
      <td>Permite al usuario buscar asesores según las calificaciones obtenidas.</td>
  </tr>
  <tr>
      <th>Idioma</th>
      <td>Permite al usuario buscar según el idioma.</td>
  </tr>
  <tr>
      <th>Palabras Clave</th>
      <td>Proporciona un cuadro de búsqueda donde los usuarios pueden ingresar palabras clave específicas relacionadas con el tipo de asesoría que necesitan.</td>
  </tr>
  </tbody>
</table>

### 4.2.5. Navigation Systems

La página de inicio de AgroConnect ha sido diseñada para una experiencia fácil y completa, ofreciendo las siguientes características:

 - ***Menús de Navegación:*** Los menús de navegación son una estructura estándar que se utiliza para organizar y presentar las diversas secciones y páginas de un producto. Estos menús pueden adoptar diferentes formas, como menús desplegables, ubicados en la parte superior o lateral de una página, e incluso enlaces de navegación en el pie de página.

 - ***Navegación por Pestañas:*** Es un sistema que emplea pestañas para organizar el contenido en secciones o categorías. Esto permite a los usuarios cambiar entre las distintas secciones de contenido simplemente haciendo clic en las pestañas correspondientes, sin necesidad de cargar nuevas páginas.

## 4.3. Landing Page UI Design

En este apartado, nos enfocaremos en el diseño de la interfaz de usuario (UI) de nuestra landing page. Es crucial que los usuarios que visiten nuestra página comprendan rápidamente de qué se trata nuestro producto y qué beneficios principales ofrecemos.

### 4.3.1. Landing Page Wireframe

**Wireframe - sección de ‘Inicio’ de AgroConnect:** la sección tendrá una imagen de fondo llamativa con un mensaje que refleja el objetivo de la startup para llamar la atención de posibles usuarios.

<p align="center">
  <img src="img/wireframe-landing-about-app.JPG" alt="Pagina Acerca de" width="600">
</p>

_Imagen 36. Pagina Acerca de_

**Wireframe - sección de ‘Sobre Nosotros’:** la sección tendrá una imagen de fondo y tendrá información sobre la startup Agrotech junto con nuestra misión y visión.

<p align="center">
  <img src="img/wireframe-landing-about-us.JPG" alt="Pagina Sobre Nosotros" width="600">
</p>

_Imagen 37. Pagina Sobre Nosotros_

**Wireframe - sección de ‘Características’:** la sección tendrá una imagen de fondo y tendrá información sobre los servicios que ofrecemos con nuestra aplicación AgroConnect.

<p align="center">
  <img src="img/wireframe-landing-features.JPG" alt="Pagina Características" width="600">
</p>

_Imagen 38. Pagina Características_

**Wireframe - sección de ‘Contacto’:** la sección tendrá una imagen de fondo y tendrá un formulario donde los usuarios potenciales puedan escribir consultas para que sean respondidas en un correo por un miembro de AgroTech.

<p align="center">
  <img src="img/wireframe-landing-contact.JPG" alt="Pagina Contacto" width="600">
</p>

_Imagen 39. Pagina Contacto_

### 4.3.2. Landing Page Mock-up
**Mockup - sección de ‘Inicio’ de AgroConnect:** la sección tiene una imagen de fondo llamativa con un mensaje que refleja el objetivo de la startup para llamar la atención de posibles usuarios.

<p align="center">
  <img src="img/mockup-landing-home.JPG" alt="Pagina de Inicio" width="600">
</p>

_Imagen 40. Mockup Pagina Inicio_

**Mockup - sección de ‘Acerca de’:** la sección tiene una imagen de fondo y tiene información sobre la problemática que queremos resolver.

<p align="center">
  <img src="img/mockup-landing-about-app.JPG" alt="Página Acerca de la problemática" width="600">
</p>

_Imagen 41. Mockup Pagina Acerca de_

**Mockup - sección de ‘Sobre Nosotros’:** la sección tiene una imagen de fondo y tiene información sobre la startup Agrotech junto con nuestra misión y visión.

<p align="center">
  <img src="img/mockup-landing-about-us.JPG" alt="Pagina Sobre Nosotros" width="600">
</p>

_Imagen 42. Mockup Pagina Sobre Nosotros_

**Mockup - sección de ‘Características’:** la sección tiene una imagen de fondo y tiene información sobre los servicios que ofrecemos con nuestra aplicación AgroConnect.

<p align="center">
  <img src="img/mockup-landing-features.JPG" alt="Pagina de Características" width="600">
</p>

_Imagen 43. Mockup Pagina de Características_

**Mockup - sección de ‘Contacto’:** la sección tiene una imagen de fondo y tiene un formulario donde los usuarios potenciales pueden escribir consultas para que sean respondidas en un correo por un miembro de AgroTech.

<p align="center">
  <img src="img/mockup-landing-contact.JPG" alt="Pagina de Contacto" width="600">
</p>

_Imagen 44. Mockup Pagina de Contacto_

## 4.4 Web Applications UX/UI Design

### 4.4.1 Web Applications Wireframes
En este apartado, se muestran todos los wireframes necesarios para cumplir las funcionalidades indicadas en las User Stories con sus escenarios relacionados con el Web Application.

**Wireframes de Inicio de sesión y Registro:** En estos wireframes se han colocado las vistas de registro las cuales tienen primero los mismos inputs para criador y asesor, siendo el correo y contraseña, para luego diferir en información específica como es el caso de asesor donde coloca su profesión, años de experiencia, foto de perfil, etc.

<img src="img/Wireframe1.png" alt = "Wireframes de Inicio de sesión y Registro">

_Imagen 45. Wireframes de Inicio de sesión y Registro_

**Wireframes de Mi Granja:** En estos wireframes se maneja las vistas del criador donde podrá gestionar tanto sus recursos como sus gastos, pudiendo ver toda la información con respecto a estos que ha ido registrando.

<img src="img/Wireframe2.png" alt = "Wireframes de Mi Granja">

_Imagen 46. Wireframes de sección Mi Granja_

**Wireframes de Mis Animales - Jaulas:** En estos wireframes se maneja las vistas de la sección Mis Animales en específico los que tratan del manejo de las jaulas donde están los cuyes pudiendo modificar su información y/o eliminarlas.

<img src="img/Wireframe3.png" alt = "Wireframes de Mis animales - Jaulas">

_Imagen 47. Wireframes de Mis animales - Jaulas_

**Wireframes de Mis Animales - Jaulas:** En estos wireframes se maneja las vistas de la sección Mis Animales en específico los que tratan de la visualización y edición de información de los cuyes.

<img src="img/Wireframe4.png" alt = "Wireframes de Mis animales - Cuyes">

_Imagen 48. Wireframes de Mis animales - Cuyes_

**Wireframes de Asesores - Citas:** En estos wireframes se maneja la visualización de los asesores que participan de la aplicación, incluyendo la funcionalidad de filtrar los asesores por palabras clave como su nombre. Además de poder comprobar los horarios disponibles de los asesores y reservar citas.

<img src="img/Wireframe5.png" alt = "Wireframes de Asesores - Citas">

_Imagen 49. Wireframes de Asesores - Citas_

**Wireframes de Asesores - Reseñas:** En estos wireframes se maneja la funcionalidad de reseñas de los asesores.

<img src="img/Wireframe6.png" alt = "Wireframes de Asesores - Reseñas">

_Imagen 50. Wireframes de Asesores - Reseñas_

**Wireframes de Registro - Jaulas:** En estos wireframes se maneja el registro de nuevas jaulas.

<img src="img/Wireframe7.png" alt = "Wireframes de Registro - Jaulas">

_Imagen 51. Wireframes de Registro - Jaulas_

**Wireframes de Registro - Cuyes:** En estos wireframes se maneja el registro de nuevos cuyes.

<img src="img/Wireframe8.png" alt = "Wireframes de Registro - Cuyes">

_Imagen 52. Wireframes de Registro - Cuyes_

**Wireframes de Registro - Recursos:** En estos wireframes se maneja el registro de nuevos recursos.

<img src="img/Wireframe9.png" alt = "Wireframes de Registro - Recursos">

_Imagen 53. Wireframes de Registro - Cuyes_

**Wireframes de Notificaciones:** En estos wireframes se maneja la vista de las notificaciones del criador que serían los recordatorios de citas programadas.

<img src="img/Wireframe10.png" alt = "Wireframes de Notificaciones">

_Imagen 54. Wireframes de Notificaciones_

**Wireframes de Clientes:** En estos wireframes se maneja la vista de los clientes del asesor.

<img src="img/Wireframe11.png" alt = "Wireframes de Clientes">

_Imagen 55. Wireframes de Clientes_

**Wireframes de Publicaciones:** En estos wireframes se maneja la vista de las publicaciones actuales del asesor y la creación de nuevas publicaciones.

<img src="img/Wireframe12.png" alt = "Wireframes de Publicaciones">

_Imagen 56. Wireframes de Publicaciones_

**Wireframes de Notificaciones:** En estos wireframes se maneja la vista de las notificaciones del asesor que serían los recordatorios de citas programadas y interés en sus publicaciones.

<img src="img/Wireframe13.png" alt = "Wireframes de Notificaciones">

_Imagen 57. Wireframes de Notificaciones_

### 4.4.2 Web Applications Wireflow Diagrams
Para usuario:
<img src="img/usuario-wireflow-1.png" alt="Usuario - Wireflow 1">

_Imagen 58. Wireflow - usuario - 1_

<img src="img/usuario-wireflow-2.png" alt="Usuario - Wireflow 2">

_Imagen 59. Wireflow - usuario - 2_

Para asesor:
<img src="img/asesor-wireflow-1.png" alt="Asesor - Wireflow 1">

_Imagen 60. Wireflow - asesor - 1_

<img src="img/asesor-wireflow-2.png" alt="Asesor - Wireflow 2">

_Imagen 61. Wireflow - asesor - 2_

<img src="img/asesor-wireflow-3.png" alt="Asesor - Wireflow 3">

_Imagen 62. Wireflow - asesor - 3_

<img src="img/asesor-wireflow-4.png" alt="Asesor - Wireflow 4">

_Imagen 63. Wireflow - asesor - 4_

Para criador:
<img src="img/criador-wireflow-1.png" alt="Criador - Wireflow 1">

_Imagen 64. Wireflow - criador - 1_

<img src="img/criador-wireflow-2.png" alt="Criador - Wireflow 2">

_Imagen 65. Wireflow - criador - 2_

<img src="img/criador-wireflow-3.png" alt="Criador - Wireflow 3">

_Imagen 66. Wireflow - criador - 3_

<img src="img/criador-wireflow-4.png" alt="Criador - Wireflow 4">

_Imagen 67. Wireflow - criador - 4_

<img src="img/criador-wireflow-5.png" alt="Criador - Wireflow 5">

_Imagen 68. Wireflow - criador - 5_

<img src="img/criador-wireflow-6.png" alt="Criador - Wireflow 6">

_Imagen 69. Wireflow - criador - 6_

<img src="img/criador-wireflow-7.png" alt="Criador - Wireflow 7">

_Imagen 70. Wireflow - criador - 7_

<img src="img/criador-wireflow-8.png" alt="Criador - Wireflow 8">

_Imagen 71. Wireflow - criador - 8_

<img src="img/criador-wireflow-9.png" alt="Criador - Wireflow 9">

_Imagen 72. Wireflow - criador - 9_

<img src="img/criador-wireflow-10.png" alt="Criador - Wireflow 10">

_Imagen 73. Wireflow - criador - 10_

<img src="img/criador-wireflow-11.png" alt="Criador - Wireflow 11">

_Imagen 74. Wireflow - criador - 11_

### 4.4.3 Web Applications Mock-ups

En este apartado, se muestran todos los mock-ups basados de los wireframes previamento mencionados. Añadiendo los colores del general style guidelines e imágenes para mejorar la visibilidad de la aplicación.

**Mock-ups de Inicio de sesión y Registro:** 
<img src="img/Mockup1.png" alt = "Mock-ups de Inicio de sesión y Registro">

_Imagen 75. Mock-ups de Inicio de sesión y Registro_

**Mock-ups de Mi Granja:**

<img src="img/Mockup2.png" alt = "Mock-ups de Mi Granja">

_Imagen 76. Mock-ups de sección Mi Granja_

**Mock-ups de Mis Animales - Jaulas:**

<img src="img/Mockup3.png" alt = "Mock-ups de Mis animales - Jaulas">

_Imagen 77. Mock-ups de Mis animales - Jaulas_

**Mock-ups de Mis Animales - Jaulas:**

<img src="img/Mockup4.png" alt = "Mock-ups de Mis animales - Cuyes">

_Imagen 78. Mock-ups de Mis animales - Cuyes_

**Mock-ups de Asesores - Citas:**

<img src="img/Mockup5.png" alt = "Mock-ups de Asesores - Citas">

_Imagen 79. Mock-ups de Asesores - Citas_

**Mock-ups de Asesores - Reseñas:**

<img src="img/Mockup6.png" alt = "Mock-ups de Asesores - Reseñas">

_Imagen 80. Mock-ups de Asesores - Reseñas_

**Mock-ups de Registro - Jaulas:**

<img src="img/Mockup7.png" alt = "Mock-ups de Registro - Jaulas">

_Imagen 81. Mock-ups de Registro - Jaulas_

**Mock-ups de Registro - Cuyes:**

<img src="img/Mockup8.png" alt = "Mock-ups de Registro - Cuyes">

_Imagen 82. Mock-ups de Registro - Cuyes_

**Mock-ups de Registro - Recursos:**

<img src="img/Mockup9.png" alt = "Mock-ups de Registro - Recursos">

_Imagen 83. Mock-ups de Registro - Cuyes_

**Mock-ups de Notificaciones:**

<img src="img/Mockup10.png" alt = "Mock-ups de Notificaciones">

_Imagen 84. Mock-ups de Notificaciones_

**Mock-ups de Clientes:**

<img src="img/Mockup11.png" alt = "Mock-ups de Clientes">

_Imagen 85. Mock-ups de Clientes_

**Mock-ups de Publicaciones:**

<img src="img/Mockup12.png" alt = "Mock-ups de Publicaciones">

_Imagen 86. Mock-ups de Publicaciones_

**Mock-ups de Notificaciones:**

<img src="img/Mockup13.png" alt = "Mock-ups de Notificaciones">

_Imagen 87. Mock-ups de Notificaciones_

### 4.4.4 Web Applications User Flow Diagrams

Cabe mencionar que los happy paths son representados por cuadros amarillos, mientras que los unhappy paths se identifican por los cuadros con tonalidad rojiza.

**Para usuario:**

<img src="img/userflow1.png" alt = "userflow 1">

_Imagen 88. usuario - inicio sesion_

<img src="img/userflow3.png" alt = "userflow 3">

_Imagen 89. usuario - recuperar contraseña_

**Para asesor:**

<img src="img/userflow2.png" alt = "userflow 2">

_Imagen 90. asesor - registro_

<img src="img/userflow4.png" alt = "userflow 4">

_Imagen 91. asesor - visualizar clientes_

<img src="img/userflow5.png" alt = "userflow 5">

_Imagen 92. asesor - crear publicaciones_

<img src="img/userflow6.png" alt = "userflow 6">

_Imagen 93. asesor - recibir notificaciones_

**Para criador:**

<img src="img/userflow7.png" alt = "userflow 7">

_Imagen 94. criador - registrar jaulas_

<img src="img/userflow8.png" alt = "userflow 8">

_Imagen 95. criador - registrar cuyes_

<img src="img/userflow9.png" alt = "userflow 9">

_Imagen 96. criador - registrar gastos_

<img src="img/userflow10.png" alt = "userflow 10">

_Imagen 97. criador - registrar recursos_

<img src="img/userflow11.png" alt = "userflow 11">

_Imagen 98. criador - modificar informacion jaulas_

<img src="img/userflow12.png" alt = "userflow 12">

_Imagen 99. criador - eliminar jaulas_

<img src="img/userflow13.png" alt = "userflow 13">

_Imagen 100. criador - ver en que jaulas pertencen cuyes_

<img src="img/userflow14.png" alt = "userflow 14">

_Imagen 101. criador - eliminar registro cuy_

<img src="img/userflow15.png" alt = "userflow 15">

_Imagen 102. criador - editar registro cuy_

<img src="img/userflow16.png" alt = "userflow 16">

_Imagen 103. criador - buscar asesores_

<img src="img/userflow17.png" alt = "userflow 17">

_Imagen 104. criador - calificar asesoria_
 

## 4.5 Web Applications Prototyping
A partir de los User Flows definidos en el punto anterior, se trabajó el prototipo funcional en Figma, el cual se explica en el siguiente video.

URL del video: [Video de explicación](https://www.youtube.com/watch?v=lTo_Pz0j2vc)

URL del prototipo: [Prototipo en figma](https://www.figma.com/proto/y65W2Fnk2IreDIFC3yPTAl/Open--Web-Style-Guidelines?type=design&node-id=296-1548&t=75RhDMIrAZo5uqGx-1&scaling=contain&page-id=112%3A67&starting-point-node-id=296%3A1548)

<img src="img/prototyping.png">

_Imagen 105. Explicación del prototipo_

## 4.6 Domain-Driven Software Architecture
### 4.6.1 Software Architecture Context Diagram
El diagrama de contexto representa la estructura y las principales interacciones de un sistema de software. Este sistema permite a los usuarios, ya sean los criadores novatos o asesores, explorar la plataforma y llevar a cabo las sesiones para apoyo, y para gestionar inventario de la granja. Además, el sistema establece conexiones con sistemas externos, como el sistema de calendario de Google para la programación de citas.

<img src="img/diagrama_contexto.png">

_Imagen 106. Diagrama de contexto_

### 4.6.2 Software Architecture Container Diagrams
El diagrama de contenedores representa la arquitectura del sistema de AgroConnect. Los criadores y asesores utilizan el contenedor de la aplicación web para interactuar con las funcionalidades del sistema mediante una conexión con la API REST. Asimismo, el contenedor del API REST se conecta con los sistemas externos.

<img src="img/diagrama_contenedor.png">

_Imagen 107. Diagrama de contenedores_

### 4.6.3 Software Architecture Components Diagrams
Los diagramas de componentes fueron creados en base a la API Rest y los bounded contexts que la componen: Gestión, Publicación, Usuario y Cita.

**API Rest Bounded Context Component Diagram**
<img src="img/API_Rest_Component_Diagram.png">

_Imagen 108. Diagrama de componentes - API REST_


**Management Bounded Context Component Diagram**
<img src="img/Management_Component_Diagram.png">

_Imagen 109. Diagrama de componentes - Gestión_


**Publication Bounded Context Component Diagram**
<img src="img/Publication_Component_Diagram.png">

_Imagen 110. Diagrama de componentes - Publicación_


**User Bounded Context Component Diagram**
<img src="img/User_Component_Diagram.png">

_Imagen 111. Diagrama de componentes - Usuario_

**Appointment Bounded Context Component Diagram**
<img src="img/Appointment_Component_Diagram.png">

_Imagen 112. Diagrama de componentes - Cita_

## 4.7 Software Object-Oriented Design
### 4.7.1 Class Diagrams

<img src="img/class_diagram_appointment.png">

_Imagen 113. Diagrama de Clases Apointment Bounded Context_

<img src="img/class_diagram_management.png">

_Imagen 114. Diagrama de Clases Management Bounded Context_

<img src="img/class_diagram_publication.png">

_Imagen 115. Diagrama de Clases Publication Bounded Context_

<img src="img/class_diagram_user.png">

_Imagen 116. Diagrama de Clases User Bounded Context_



### 4.7.2. Class Dictionary.

**User Bounded Context**

|User|
| - |
|Es la interfaz que representa a un usuario general dentro de la aplicación. Tiene relación de asociación con User Factory.|

|Advisor|
| - |
|Es la clase que representa un asesor dentro de la aplicación. Es una clase hija de User, por lo que tiene relación de herencia con User.|

|Breeder|
| - |
|Es la clase que representa un criador dentro de la aplicación. Es una clase hija de User, por lo que tiene relación de herencia con User.|

|UserFactory||
| - | :- |
|Es la clase que se encarga de la creación de los usuarios, es clase hija de UserManager. Tiene relación de asociación con User y relación de herencia con UserManager.||
|createUser()|Método que implementa la creación de un nuevo objeto.|

|UserManager||
| - | :- |
|Es la clase que se encarga de la gestión de los usuarios. Tiene relación de herencia con UserFactory.||
|createUser()|Método que implementa la creación de un nuevo objeto User.|
|getUser()|Método que obtiene información de un usuario específico.|
|updateUser()|Método que permite actualizar los atributos de un usuario específico.|
|deleteUser()|Método que permite eliminar a un usuario específico.|

|AdvisorFactory||
| - | :- |
|Es la clase que se encarga de la creación de los usuarios de tipo Advisor. Es clase hija de UserFactory. Tiene relación de herencia con UserManager.||
|createUser()|Método que implementa la creación de un nuevo objeto Advisor.|

|BreederFactory||
| - | :- |
|Es la clase que se encarga de la creación de los usuarios de tipo Breeder. Es clase hija de UserFactory. Tiene relación de herencia con UserManager.||
|createUser()|Método que implementa la creación de un nuevo objeto Breeder.|

**Management Bounded Context**

|Breeder|
| - |
|Es la clase que representa un criador dentro de la aplicación y tiene una relación de asociación con la clase Farm.|

|Farm|
| - |
|Es la clase que representa la colección de recursos, gastos y animales del criador. Por lo que, tiene una relación de agregación con dichas clases.|

|Cage||
| - | :- |
|Es la clase que representa las jaulas donde están los cuyes. Entonces, tiene una relación de composición con Animal. Además, actúa como Director en el patrón Builder para registrar un animal porque este invoca al Builder.||
|getAnimals()|Método para obtener el conjunto de cuyes de la jaula.|
|registerAnimal()|Método para registrar un cuy usando el patrón Builder.|

|Animal|
| - |
|Es la clase que representa a los cuyes que crían los criadores.|

|Builder||
| - | :- |
|Es la clase que define los métodos para crear un Animal por parte y declara los pasos para crear un objeto Animal. ||
|setName()|Método para ponerle el nombre a un cuy.|
|setBreed()|Método para señalar la raza de un cuy.|
|setGender()|Método para indicar el género de un cuy.|
|setBirthDate()|Método para señalar la fecha de nacimiento de un cuy.|
|setStatus()|Método para indicar el estado de un cuy.|
|setCage()|Método para indicar la jaula donde habita un cuy.|
|setWeight()|Método para señalar el peso de un cuy.|
|setObservation()|Método para indicar observaciones adicionales de un cuy.|

|AnimalBuilder||
| - | :- |
|Es una implementación específica del Builder que permite crear a un animal.||
|setName()|Método para ponerle el nombre a un cuy.|
|setBreed()|Método para señalar la raza de un cuy.|
|setGender()|Método para indicar el género de un cuy.|
|setBirthDate()|Método para señalar la fecha de nacimiento de un cuy.|
|setStatus()|Método para indicar el estado de un cuy.|
|setCage()|Método para indicar la jaula donde habita un cuy.|
|setWeight()|Método para señalar el peso de un cuy.|
|setObservation()|Método para indicar observaciones adicionales de un cuy.|
|getAnimal()|Método para obtener el objeto Animal.|

|Expense|
| - |
|Es una interfaz que representa un gasto del criador.|

|FoodExpense|
| - |
|Es una implementación de un gasto específicamente un gasto de comida para cuyes del criador.|


|HealthExpense|
| - |
|Es una implementación de un gasto específicamente un gasto realizado para mantener la salud de los cuyes del criador.|

|MaintenanceExpense|
| - |
|Es una implementación de un gasto específicamente un gasto realizado para mantener el galpón del criador, pueden ser productos de limpieza, nuevas jaulas, etc.|

|ExpenseFactory||
| - | :- |
|Es la clase que define la creación de gastos. ||
|createExpense()|Método para la creación de un nuevo gasto.|

|FoodExpenseFactory||
| - | :- |
|Es la clase que define la creación de gastos sobre comida. ||
|createExpense()|Método que sobreescribe la creación de un nuevo gasto para que sea un gasto de comida.|

|HealthExpenseFactory||
| - | :- |
|Es la clase que define la creación de gastos sobre salud de los cuyes. ||
|createExpense()|Método que sobreescribe la creación de un nuevo gasto para que sea un gasto relacionado con la salud de los cuyes.|

|MaintenanceExpenseFactory||
| - | :- |
|Es la clase que define la creación de gastos sobre mantenimiento del galpón. ||
|createExpense()|Método que sobreescribe la creación de un nuevo gasto para que sea un gasto relacionado con el mantenimiento del galpón.|

|Resource|
| - |
|Es una interfaz que representa un recurso que el criador posee.|


|FoodResource|
| - |
|Es una implementación de un recurso, en este caso el recurso sería comida para cuyes.|

|MedicineResource|
| - |
|Es una implementación de un recurso, en este caso el recurso sería medicina para cuyes.|

|EquipmentResource|
| - |
|Es una implementación de un recurso, en este caso el recurso sería equipamiento necesario para el mantenimiento del galpón puede ser por ejemplo nuevas jaulas.|

|ResourceFactory||
| - | :- |
|Es la clase que define la creación de recursos. ||
|createResource()|Método para la creación de un nuevo recurso.|

|FoodResourceFactory||
| - | :- |
|Es la clase que define la creación de recursos de comida. ||
|createResource()|Método que sobreescribe la creación de un nuevo recurso para que sea un recurso de tipo comida.|

|MedicineResourceFactory||
| - | :- |
|Es la clase que define la creación de recurso sobre medicina para los cuyes. ||
|createResource()|Método que sobreescribe la creación de un nuevo recurso para que sea un recurso relacionado con medicina para cuyes.|

|EquipmentResourceFactory||
| - | :- |
|Es la clase que define la creación de gastos de equipamiento. ||
|createResource()|Método que sobreescribe la creación de un nuevo recurso para que sea un gasto relacionado con equipamiento como nuevas jaulas.|

**Appointment Bounded Context**

|Breeder||
| - | :- |
|Es la clase que representa un criador dentro de la aplicación. Es la clase que representa un asesor dentro de la aplicación. Implementa la interfaz “Observer” y definen su propio método ‘update()’ para recibir notificaciones.||
|update()|Cuando la fecha de la cita se acerca o cambia, la clase Appointment puede invocar el método update() en “Breeder”. Por ejemplo, si la fecha actual es igual a la fecha de la cita menos un día, el Appointment podría notificar al “Breeder” de dicho cambio; o también, cuando ya es la fecha de la cita.|

|Advicer||
| - | :- |
|Es la clase que representa un asesor dentro de la aplicación. Implementa la interfaz “Observer” y definen su propio método ‘update()’ para recibir notificaciones.||
|update()|Cuando la fecha de la cita se acerca o cambia, la clase Appointment puede invocar el método update() en “Advicer”. Por ejemplo, si la fecha actual es igual a la fecha de la cita menos un día, el Appointment podría notificar al “Advicer” de dicho cambio; o también, cuando ya es la fecha de la cita.|

|Appointment||
| - | :- |
|Es la clase que representa una cita entre el asesor y el criador de cuyes.||
|getDate()|Método que obtiene la fecha de la cita y luego compararla con la fecha actual para determinar si se debe enviar una notificación.|
|setDate()|Se utiliza para establecer la fecha inicial de la cita|

|Observer||
| - | :- |
|La interfaz Observer establece un acuerdo para los objetos interesados en recibir avisos sobre modificaciones en un objeto que puede ser observado.||
|update()|Método que se llama cuando la fecha del “Appointment” cambia y/o ya es la fecha de la cita necesita notificar a sus observadores.|


Publication Bounded Context

|Advisor||
| - | :- |
|Es la clase que representa un asesor dentro de la aplicación en el contexto de sus publicaciones||
|createPublication()|Método que crea una publicación.|
|updatePublication()|Método que actualiza la información de una publicación|
|deletePublication()|Método para eliminar una publicación|

|Publications|
| - |
|Es una interfaz que representa las publicaciones de un asesor|

|Publication||
| - | :- |
|Es la clase que representa una publicación hecha por un asesor||
|title|Título de la publicación|
|description|Descripción de la publicación|
|photo|Imagen que va en la publicación|
|getTitle()|Método que obtiene el título de la publicación|
|getDescription()|Método que obtiene la descripción de la publicación|
|getPhoto()|Método que obtiene la imagen de la publicación|
|Publication(PublicationAdvisorBuilder)|Método constructor utilizado para construir instancias de “Publication” utilizando los valores configurados en el “PublicationAdvisorBuilder”|


|PublicationAdvisorBuilder||
| - | :- |
|Es la clase que facilita la construcción paso a paso de objetos “Publication”||
|title|Título de la publicación|
|description|Descripción de la publicación|
|photo|Imagen que va en la publicación|
|setTitle()|Método que establece el título de la publicación|
|setDescription()|Método que establece la descripción de la publicación|
|getPhoto()|Método que establece la imagen de la publicación|
|build()|Método responsable de finalizar el proceso de construcción del objeto “Publication” y devuelve la instancia completa del mismo|




## 4.8 Database Design
### 4.8.1 Database Diagram
Se hizo el diseño de la base de datos no relacional, considerando cumplir con las funcionalidades mencionadas en las User Stories.

<img src="img/database.png">

_Imagen 117. Diagrama de base de datos_


# Capítulo V Product Implementation, Validation & Deployment

## 5.1. Software Configuration Management.

### 5.1.1. Software Development Environment Configuration.

**Project Management:**

Para la gestión del proyecto, utilizamos como principal medio de comunicación WhatsApp, a través de un grupo en el cual compartimos nuestras ideas y opiniones sobre cada parte del trabajo. A esto se le suma el uso de la herramienta Google Meet, para realizar reuniones en videoconferencia y conversar de forma síncrona. Por otro lado, el proyecto también tiene que ser documentado con todos los puntos requeridos, por lo que utilizamos Google Drive para la creación de documentos compartidos y trabajar de forma colaborativa, permitiendo un mejor flujo de trabajo y tener un historial sobre lo que realizó cada uno. Asimismo, utilizamos GitHub para el manejo de repositorios a través de una comunidad conformada por todos los integrantes del equipo. En esta, también documentamos los reportes y la aplicación en sí.


**Requirements Management:**

Para el registro de los requisitos, o también llamadas historias de usuario, utilizamos la herramienta Pivotal Tracker, en la cual registramos cada una de ellas y ordenadas por prioridad según el Product Backlog. La realización de este fue grupal, todos los integrantes aportamos en las historias de usuario y discutimos sobre las principales funcionalidades que consideramos que debe tener la aplicación web.


**Product UX/UI Design:**

Se realizaron los productos de UX con la herramienta UXPressia, así como el User Persona, Empathy Mapping, Impact Mapping, entre otras. Gracias a esto pudimos modelar bien los diseños de la experiencia de usuario, lo cual nos sirve para poder ponernos en una mejor perspectiva para nuestros segmentos objetivo. Por otro lado, hicimos los prototipos de la aplicación web utilizando la herramienta Figma, la cual nos permitió crear los Wireframes y Mock-ups para tener un diseño previo al desarrollo de la aplicación.


**Software Development:**

Como principal IDE, utilizamos Visual Studio Code, el cual es el entorno de desarrollo con el que estamos más familiarizados, además que ofrece flexibilidad, facilidad de uso y una gran variedad de soporte de lenguajes de programación. Además, permite la conexión con repositorios en línea creados en GitHub, lo cual nos permite tener una mejor gestión del proyecto, así como el historial de todos los cambios realizados. En la otra mano, para el desarrollo usamos los lenguajes aprendidos previamente, como HTML, CSS y JavaScript, y nuevos conocimientos adquiridos este ciclo como el framework de AngularJS.


**Software Testing:**

Las pruebas de aceptación son importantes a realizar para comprobar que los criterios de aceptación planteados están favoreciendo a las necesidades del negocio y cumplir con los requerimientos, para lo cual utilizamos el lenguaje Gherkin. Este consiste en trabajar el escenario con Given When Then, y lograr identificar las variables de input y output, lo cual es sencillo de entender para todos ya que utiliza lenguaje natural. Gracias a este, es que se logra garantizar la calidad del software, por ello cumple un papel esencial en los proyectos de desarrollo.


### 5.1.2. Source Code Management.

Usuarios de GitHub
<table>
  <thead>
    <tr>
        <th>Integrante</th>
        <th>Usuario de GitHub</th>
    </tr>
  </thead>
  <tbody>
  <tr>
      <td>Delgado Corrales, Piero Gonzalo</td>
      <td>PieroD04</td>
  </tr>
  <tr>
      <td>Lucas Coronel, Nadia Alessandra</td>
      <td>nad21lc</td>
  </tr>
  <tr>
      <td>Paredes Puente, Sebastián Roberto</td>
      <td>sebastian123gonzalo</td>
  </tr>
  <tr>
      <td>Salinas Torres, Salvador Antonio</td>
      <td>salvadoorssalinas</td>
  </tr>
  <tr>
      <td>Valverde Mozo, Andre Gabriel</td>
      <td>AndreVMG</td>
  </tr>
  </tbody>
</table>


*URL de repositorio de Landing Page:* https://github.com/AgroTech-UPC/Landing-Page

*URL de repositorio de Web Services:* https://github.com/AgroTech-UPC/Web-Services

*URL de repositorio de Frontend Web Applications:* https://github.com/AgroTech-UPC/Frontend-Web-Applications

*URL de repositorio de Acceptance Tests*: https://github.com/AgroTech-UPC/Acceptance-Tests

Para el desarrollo del trabajo se hará uso de GitFlow, el cual es un modelo de flujo de trabajo para la gestión de control de versiones Git. Está compuesta por ramas y cada una cumple un propósito distinto. Las ramas que utilizamos son: Feature, Develop y Main. 

**Rama Feature**: En esta rama se desarrolla un feature específico, por ejemplo la implementación del registro de un usuario o del inicio de sesión. Las ramas Feature se trabajan y controlan por separado para tener un orden sobre el cual trabajar a partir del Product Backlog. Esto asegura que cualquier problema que surja durante el desarrollo de una característica no afecte al programa en su totalidad.

**Rama Develop**: En esta rama se fusionan las ramas feature desarrolladas. Esto permite verificar que todo funcione correctamente antes de integrarlo en la rama Main para su despliegue oficial.

**Rama Main**: Esta rama almacena las versiones finales del sprint y se utiliza para desplegar la aplicación web. Se espera que todas las versiones almacenadas aquí sean funcionales y estables para el usuario.

### 5.1.3. Source Code Style Guide & Conventions.
En el desarrollo de este trabajo, se utilizará una gran variedad de lenguajes para trabajar en el Landing Page, Web Services y Frontend Web Application. Para ello, se utilizará la siguiente guía de estilos y convenciones.


**HTML**

Es el lenguaje utilizado para estructurar el contenido de una página web, brindando una variedad de elementos posibles como texto, imágenes, formularios, etc.
https://www.w3schools.com/html/html5_syntax.asp

- Declarar el tipo de documento en la primera línea con \<!DOCTYPE html>.
- Respetar la estructura básica del HTML: \<html>, \<head>, \<body>.
- Declarar el título de la página para dar a conocer al usuario en qué página se encuentra. (Usar el elemento \<title> en \<head>)
- Se usará la indentación coherente para lograr una lectura sencilla del código, por lo que es importante tener la tabulación correcta para cada nivel de anidamiento.
- Siempre cerrar los elementos que lo requieran, ya sea una división, párrafo, título. (Si se declara una \<div>, siempre cerrarlo con \</div>)
- Declarar el atributo “alt” para las imágenes.


**CSS**

Es el lenguaje utilizado para definir el diseño de la página web, así como los estilos, fuentes, colores, contenedores, etc.
https://google.github.io/styleguide/htmlcssguide.html
- Usar indentación de forma correcta.
- Los nombres para elementos deben ser cortos y en minúsculas.
- Declarar los colores en código hexadecimal. (Ejemplo: #024A86)
- Dejar comentarios para conocer el propósito del estilo y su uso.
- El diseño debe ser responsive para que los usuarios lo puedan visualizar cómodamente desde el dispositivo en qué se encuentren.


**JavaScript**

Es el lenguaje de programación más utilizado para la programación web, ya que permite desarrollar páginas interactivas con animaciones agradables para los usuarios.
https://www.w3schools.com/js/js_conventions.asp
- Declarar nombres coherentes y cortos para las variables y funciones.
- Dejar comentarios para dar a conocer que hace cada parte del código sobre la página web.
- Siempre colocar un punto y coma al final de cada línea de código.
- Declarar las constantes cuando sea necesario en lugar de variables que nunca cambiarán su valor.
- Usar los operadores de comparación estricta en lugar de comparación regular cuando sea posible. (Ejemplo: Utilizar === en lugar de ==)


**TypeScript**

Es el superjunto de JavaScript que añade características como el tipado estático y funciones avanzadas.
https://www.typescriptlang.org/docs/handbook/intro.html
- Declarar nombres significativos y consistentes para las variables, al igual que en JavaScript.
- Declarar interfaces y tipos en PascalCase.
- Declarar variables y funciones en CamelCase.
- Dejar comentarios para explicar sobre lo que hace cada parte del código.
- Usar interfaces para la reutilización de código.


**Java**

Es un lenguaje de programación utilizado para la programación web, programación móvil, entre otros. Es capaz de adaptarse para funcionar en distintas plataformas.
https://google.github.io/styleguide/javaguide.html
- Nombrar las variables, funciones y clases con CamelCase, además de ser significativos y cortos.
- Utilizar HTTPS para establecer una conexión segura.
- Usar indentación correctamente para un código coherente y ordenado.
- Usar comillas dobles (“) para las cadenas de texto.
- Dejar comentarios en cada bloque de código para explicar su funcionalidad.
- Declarar constantes cuando sean variables que no cambiarán su valor a lo largo de todo el código.


**Gherkin**

Es el lenguaje para el diseño de casos de prueba en base a los requisitos establecidos por el negocio. Este se utiliza durante el proceso de testing.
https://specflow.org/gherkin/gherkin-conventions-for-readable-specifications/
- Separar en bloques cada parte de Given When Then, para una mejor lectura y subdividirse adecuadamente.
- Al mostrar las variables de input y output con sus ejemplos, se utilizan tablas para la representación de estos. Sin embargo, no es necesario utilizar tantas tablas para cada parte del código, sino una general al final del escenario.
- Si hay más de un escenario en un archivo, hacer la separación adecuada entre estas para diferenciarlas y dar a conocer que son más de uno. Para ello, se puede dejar dos líneas en blanco para saber dónde es que un escenario termina y el otro comienza.
- Agregar líneas en blanco dentro de cada Step para una mejor lectura y organización de la información.


### 5.1.4. Software Deployment Configuration.

Para la configuración del despliegue de la aplicación, utilizaremos Git, un sistema de control de versiones distribuido que es bastante utilizado en proyectos de desarrollo de software. Es una herramienta esencial para trabajar colaborativamente y poder hacer el seguimiento de los cambios realizados por los miembros del grupo. Una de sus mejores ventajas es su capacidad para rastrear los cambios en los archivos de un proyecto a lo largo del tiempo. Con Git, es posible crear ramas, realizar cambios en ellas y fusionarlos eficientemente, permitiendo que varios desarrolladores trabajen en diferentes aspectos del proyecto simultáneamente sin interferencias.


Por otro lado, tenemos a GitHub, el cual es la plataforma para poder alojar repositorios de Git. Es uno de los servicios más utilizados por desarrolladores de forma mundial, ya que permite manejar repositorios públicos y privados para almacenar el código en la nube. A parte de ello, maneja el historial de los repositorios, permitiendo a los usuarios acceder a todas las versiones trabajadas, permitiendo que puedan retornar a una versión anterior en caso lo deseen. Ofrece otras herramientas que son muy útiles como los pull requests, los cuales son solicitudes de revisiones de una rama y luego poder fusionarla con otra rama.


Así es como con este, que cada miembro podrá trabajar de forma remota desde su IDE, teniendo una copia del repositorio Git a través del repositorio en línea almacenado en GitHub, así poder hacer commits para empujar los cambios que hayan realizado.

## 5.2. Landing Page, Services & Applications Implementation.

### 5.2.1. Sprint 1

#### 5.2.1.1. Sprint Planning 1.

Se planeó el primer sprint a través de una reunión en Meet. Para ello, se hizo la siguiente tabla para registrar la información que se discutió.

|**Sprint #**|Sprint 1|
| :- | :- |
|**Sprint Planning Background**||
|Date|2024-04-01|
|Time|10: 00 PM|
|Location|Virtual (Google Meet)|
|Prepared by|Delgado Corrales, Piero Gonzalo|
|Attendees (to planning meeting)|<p>Delgado Corrales, Piero Gonzalo</p><p>Lucas Coronel, Nadia Alessandra</p><p>Paredes Puente, Sebastián Roberto</p><p>Salinas Torres, Salvador Antonio</p><p>Valverde Mozo, Andre Gabriel</p>|
|Sprint n - 1 Review Summary|No hubo sprint anterior|
|Sprint n - 1 Retrospective Summary|No hubo sprint anterior|
|**Sprint Goal & User Stories**||
|Sprint 1 Goal|Realizar el Landing Page|
|Sprint 1 Velocity|20|
|Sum of Story Points|20|


#### 5.2.1.2. Sprint Backlog 1.

El objetivo de este primer sprint es la implementación del Landing Page estático. Además, se trabajó con una tabla en Trello para manejar los Work-Items de forma adecuada.

<https://trello.com/b/AtaOZblV/sprint-backlog-1> 

<img src="img/sprintBacklog.jpg" width="100%"> 

_Imagen 118. Sprint Backlog 1 en Trello_

<table><tr><th valign="top">Sprint #</th><th colspan="7" valign="top">Sprint 1</th></tr>
<tr><td colspan="2" valign="top">User Story</td><td colspan="6" valign="top">Work-Item / Task</td></tr>
<tr><td valign="top">Id</td><td valign="top">Title</td><td valign="top">Id</td><td valign="top">Title</td><td valign="top">Description</td><td valign="top">Estimation (Hours)</td><td valign="top">Assigned To</td><td valign="top">Status (To-Do / In-Process / Review / Done)</td></tr>
<tr><td rowspan="2" valign="top">US22</td><td rowspan="2" valign="top">Visualización de Navbar y Footer</td><td valign="top">TS01</td><td valign="top">Implementación de Navbar</td><td valign="top">Se implementa el navbar de forma responsive.</td><td valign="top">3</td><td valign="top">Nadia Lucas</td><td valign="top">Done</td></tr>
<tr><td valign="top">TS02</td><td valign="top">Implementación de Footer</td><td valign="top">Se implementa el footer de forma responsive.</td><td valign="top">1</td><td valign="top">Nadia Lucas</td><td valign="top">Done</td></tr>
<tr><td valign="top">US23</td><td valign="top">Página de inicio</td><td valign="top">TS03</td><td valign="top">Implementación de página de inicio</td><td valign="top">Se implementa la página de inicio de forma responsive y con su archivo css correspondiente.</td><td valign="top">1</td><td valign="top">Nadia Lucas</td><td valign="top">Done</td></tr>
<tr><td valign="top">US24</td><td valign="top">Sección “Acerca De”</td><td valign="top">TS04</td><td valign="top">Implementación de sección Acerca De</td><td valign="top">Se implementa la página Acerca De, de forma responsive y con su archivo css correspondiente.</td><td valign="top">2</td><td valign="top">Sebastián Paredes</td><td valign="top">Done</td></tr>
<tr><td valign="top">US25</td><td valign="top">Sección “Sobre Nosotros”</td><td valign="top">TS05</td><td valign="top">Implementación de sección Sobre Nosotros</td><td valign="top">Se implementa la página Sobre Nosotros, de forma responsive y con su archivo css correspondiente.</td><td valign="top">2</td><td valign="top">Salvador Salinas</td><td valign="top">Done</td></tr>
<tr><td valign="top">US26</td><td valign="top">Sección “Características”</td><td valign="top">TS06</td><td valign="top">Implementación de sección Características</td><td valign="top">Se implementa la página Características, de forma responsive y con su archivo css correspondiente.</td><td valign="top">2</td><td valign="top">Andre Valverde</td><td valign="top">Done</td></tr>
<tr><td valign="top">US27</td><td valign="top">Sección “Contacto”</td><td valign="top">TS07</td><td valign="top">Implementación de sección Contacto</td><td valign="top">Se implementa la página Contacto, de forma responsive y con su archivo css correspondiente.</td><td valign="top">2</td><td valign="top">Piero Delgado</td><td valign="top">Done</td></tr>
</table>

#### 5.2.1.3. Development Evidence for Sprint Review.

Se realizaron los avances con los commits correspondiente en el repositorio de la siguiente forma.

|**Repository**|**Branch**|**Commit Id**|**Commit Message**|**Commited on (Date)**|
| :- | :- | :- | :- | :- |
|AgroTech-UPC/Landing-Page|feature/header-footer|ff5467f|feat: Preparing the workspace|02/04/2024|
|AgroTech-UPC/Landing-Page|feature/header-footer|965448b|feat: Complete header and footer|02/04/2024|
|AgroTech-UPC/Landing-Page|develop|f450025|Merge pull request #1 from AgroTech-UPC/header-footer|02/04/2024|
|AgroTech-UPC/Landing-Page|develop|bab8888|refactor: login button deleted & padding to main|02/04/2024|
|AgroTech-UPC/Landing-Page|feature/contact|1fdfcb2|feat: contact page completed|03/04/2024|
|AgroTech-UPC/Landing-Page|feature/contact|2a79c52|fix: fixed position of footer|03/04/2024|
|AgroTech-UPC/Landing-Page|develop|1c1cab7|Merge pull request #4 from AgroTech-UPC/feature/contact|03/04/2024|
|AgroTech-UPC/Landing-Page|feature/home|12c2b0b|feat: home page completed|03/04/2024|
|AgroTech-UPC/Landing-Page|develop|b348cf3|Merge pull request #5 from AgroTech-UPC/feature/home|03/04/2024|
|AgroTech-UPC/Landing-Page|feature/about-us|bcee2f1|feat: about us section added|03/04/2024|
|AgroTech-UPC/Landing-Page|develop|f0b57ab|Merge pull request #7 from AgroTech-UPC/feature/about-us|03/04/2024|
|AgroTech-UPC/Landing-Page|feature/about-app|a0f235c|Feat: Section about-app created|04/04/2024|
|AgroTech-UPC/Landing-Page|feature/characteristics|2c15c6d|feat: features section added|04/04/2024|
|AgroTech-UPC/Landing-Page|develop|961b6fe|Merge pull request #8 from AgroTech-UPC/feature/about-app|04/04/2024|
|AgroTech-UPC/Landing-Page|develop|bc8aa23|Merge pull request #10 from AgroTech-UPC/feature/characteristics|04/04/2024|
|AgroTech-UPC/Landing-Page|main|341ad78|Merge pull request #11 from AgroTech-UPC/develop|04/04/2024|

#### 5.2.1.4. Testing Suite Evidence for Sprint Review.

Se realizaron las pruebas de aceptación para las historias de usuario trabajadas utilizando el lenguaje Gherkin en archivos feature. De esta manera, se registraron en el repositorio.

|**Repository**|**Branch**|**Commit Id**|**Commit Message**|**Commited on (Date)**|
| :- | :- | :- | :- | :- |
|AgroTech-UPC/Acceptance-Tests|main|57f2c58|feat: added feature file for US29|05/04/2024|
|AgroTech-UPC/Acceptance-Tests|main|1b94680|feat: added feature file for US28|05/04/2024|
|AgroTech-UPC/Acceptance-Tests|main|9027b2b|Fix: fix typing error|05/04/2024|
|AgroTech-UPC/Acceptance-Tests|main|329c774|feat: added acceptance test for US31|05/04/2024|
|AgroTech-UPC/Acceptance-Tests|main|24c738a|feat: added acceptance test for US30|06/04/2024|
|AgroTech-UPC/Acceptance-Tests|main|802f736|feat: added acceptance test for US26|07/04/2024|
|AgroTech-UPC/Acceptance-Tests|main|29d85ed|feat: added acceptance test for US27|07/04/2024|



#### 5.2.1.5. Execution Evidence for Sprint Review.

En esta sección, se mostrará lo avanzado en el primer sprint, el cual se basa en la implementación del Landing Page estático. Para ello, se realizó el siguiente video con la explicación y las capturas que evidencia la página web.

**URL de video:**
[Execution Evidence](https://youtu.be/Yi3p53UjKF0)

<img src="img/evidence_landing_page_1.png" width="100%"> 

_Imagen 119. evidencia landing page 1_


Navbar: fue implementada para que sea responsive y las secciones pasen a un menú lateral en caso de ser necesario.

<img src="img/evidence_landing_page_2.png" width="100%"> 

_Imagen 120. navbar 1_

<img src="img/evidence_landing_page_3.png" width="100%"> 

_Imagen 121. navbar 2_

Footer: al igual que el navbar, se implementó para acomodarse acorde al tamaño de la ventana.

<img src="img/evidence_landing_page_4.png" width="100%"> 

_Imagen 122. footer 1_

<img src="img/evidence_landing_page_5.png" width="100%"> 

_Imagen 123. footer 2_

Página de inicio:

<img src="img/evidence_landing_page_6.png" width="100%"> 

_Imagen 124. pagina de inicio 1_

<img src="img/evidence_landing_page_7.png" width="100%"> 

_Imagen 125. pagina de inicio 2_

Sección “Acerca De”:

<img src="img/evidence_landing_page_8.png" width="100%"> 

_Imagen 126. seccion "Acerca de" 1_

<img src="img/evidence_landing_page_9.png" width="100%"> 

_Imagen 127. seccion "Acerca de" 2_

Sección “Sobre Nosotros”:

<img src="img/evidence_landing_page_10.png" width="100%"> 

_Imagen 128. seccion "Sobre Nosotros" 1_

<img src="img/evidence_landing_page_11.png" width="100%">

_Imagen 129. seccion "Sobre Nosotros" 2_

Sección “Características”: 

<img src="img/evidence_landing_page_12.png" width="100%"> 

_Imagen 130. seccion "Caracteristicas" 1_

<img src="img/evidence_landing_page_13.png" width="100%"> 

_Imagen 131. seccion "Caracteristicas" 2_

Sección “Contacto”:

<img src="img/evidence_landing_page_14.png" width="100%"> 

_Imagen 132. seccion "Contacto" 1_

<img src="img/evidence_landing_page_15.png" width="100%"> 

_Imagen 133. seccion "Contacto" 2_

#### 5.2.1.6. Services Documentation Evidence for Sprint Review.

En este primer sprint, no hemos trabajado con servicios web, ya que nos hemos concentrado exclusivamente en la creación del Landing Page estático. Es por ello que en esta ocasión, no se trabajó la documentación relacionada con el uso de servicios web.

#### 5.2.1.7. Software Deployment Evidence for Sprint Review.

Una vez acabamos de trabajar con todas las historias de usuario, realizamos el deployment del Landing Page utilizando GitHub Pages.

URL de deployment de Landing Page: <https://agrotech-upc.github.io/Landing-Page/home.html>

Para lograr hacer el deployment, entramos a la configuración del repositorio y a la sección de Pages. Luego, debemos seleccionar la rama sobre la cual se hará el deployment.

<img src="img/github-pages.jpg" width="100%"> 

_Imagen 134. github - pages - 1_

Escogimos la rama main, ya que es la rama principal sobre la cual se guarda la versión final para hacer el deployment. Una vez se escoge, se guardan los cambios.

<img src="img/github-pages-1.jpg" width="100%"> 

_Imagen 135. github - pages - 2_

Finalmente, solo se espera a que GitHub cree la página y nos brinde el enlace.

<img src="img/github-pages-2.jpg" width="100%"> 

_Imagen 136. github - pages - 3_

<img src="img/github-pages-3.jpg" width="100%"> 

_Imagen 137. github - pages - 4_

#### 5.2.1.8. Team Collaboration Insights during Sprint.

En la elaboración de la landing page, todos los integrantes realizaron commits referentes al branch feature que les tocó trabajar. 

<img src="img/commits-landing-page.jpg" width="100%"> 

_Imagen 138. commits - landing-page_

La división de trabajo para lograr la implementación fue por secciones en las cuales cada miembro realizó una sección de la landing page:

-Piero Delgado: sección ‘contacto’

-Sebastían Paredes: sección ‘acerca de’

-Nadia Lucas: sección ‘inicio’

-André Valverde: sección ‘características’

-Salvador Salinas: sección ‘sobre nosotros’

Cada sección tuvo su rama con el formato ‘feature/sección’

<img src="img/feature-seccion.jpg" width="100%">

_Imagen 139. feature-seccion_

### 5.2.2. Sprint 2

#### 5.2.2.1. Sprint Planning 2.

Se planeó el segundo sprint a través de una reunión en Meet. Para ello, se hizo la siguiente tabla para registrar la información que se discutió.

|**Sprint #**|Sprint 2|
| :- | :- |
|**Sprint Planning Background**||
|Date|2024-04-24|
|Time|11: 00 PM|
|Location|Virtual (Google Meet)|
|Prepared by|Delgado Corrales, Piero Gonzalo|
|Attendees (to planning meeting)|<p>Delgado Corrales, Piero Gonzalo</p><p>Lucas Coronel, Nadia Alessandra</p><p>Paredes Puente, Sebastián Roberto</p><p>Salinas Torres, Salvador Antonio</p><p>Valverde Mozo, Andre Gabriel</p>|
|Sprint 1 Review Summary|En el primer sprint, logramos realizar el deployment del landing page, pero igualmente no se llegó a una versión buena. Además, se necesita mejorar la base de datos y las historias de usuario.|
|Sprint 1 Retrospective Summary|En retrospectiva, se debe mejorar el landing page, la base de datos, mejorar algunas historias de usuario y añadir más.|
|**Sprint Goal & User Stories**||
|Sprint 2 Goal|Implementar el Frontend de nuestra aplicación web|
|Sprint 2 Velocity|72|
|Sum of Story Points|72|

#### 5.2.2.2. Sprint Backlog 2.

El objetivo de este segundo sprint es la implementación del Frontend de nuestra aplicación web. Además, se trabajó con una tabla en Trello para manejar los Work-Items de forma adecuada.

https://trello.com/b/lyM1zKbK/agrotech-sprint-backlog-2

<img src="img/sprintbacklog2.PNG" width="100%">

_Imagen 140. Sprint Backlog 2_

<table>
    <tr><th valign="top">Sprint #</th><th colspan="7" valign="top">Sprint 2</th></tr>
    <tr><td colspan="2" valign="top">User Story</td><td colspan="6" valign="top">Work-Item / Task</td></tr>
    <tr><td valign="top">Id</td><td valign="top">Title</td><td valign="top">Id</td><td valign="top">Title</td><td valign="top">Description</td><td valign="top">Estimation (Hours)</td><td valign="top">Assigned To</td><td valign="top">Status (To-Do / In-Process / Review / Done)</td></tr>
    <tr>
      <td valign="top">US01</td><td valign="top">Catálogo de asesores</td><td valign="top">TS01</td><td valign="top">Implementación de búsqueda de asesores</td><td valign="top">Se implementa el componente para la búsqueda de asesores para los criadores.</td><td valign="top">3</td>
      <td valign="top">Andre Valverde</td><td valign="top">Done</td>
    </tr>
    <tr>
      <td valign="top">US02</td><td valign="top">Información de un asesor</td><td valign="top">TS02</td><td valign="top">Implementación de vista de información de un asesor</td><td valign="top">Se implementa el componente con la vista de información de un asesor.</td><td valign="top">2</td><td valign="top">Andre Valverde</td>
      <td valign="top">Done</td>
    </tr>
    <tr>
      <td valign="top">US03</td><td valign="top">Visualización de horarios de asesores</td><td valign="top">TS03</td><td valign="top">Implementación de vista de horarios</td><td valign="top">Se implementa el componente con la vista de los horarios disponibles del asesor.</td><td valign="top">2</td>
      <td valign="top">Andre Valverde</td><td valign="top">Done</td>
    </tr>
    <tr>
      <td valign="top">US04</td><td valign="top">Programación de citas con asesores</td><td valign="top">TS04</td><td valign="top">Implementación de vista para programar cita</td><td valign="top">Se implementa la vista para programar una cita con un asesor.</td><td valign="top">6</td>
      <td valign="top">Andre Valverde</td><td valign="top">Done</td>
    </tr>
    <tr>
      <td valign="top">US05</td><td valign="top">Visualización de información del criador de cuyes</td><td valign="top">TS05</td><td valign="top">Implementación de detalles de cita</td><td valign="top">Se implementa la página para visualizar los datos del criador previa a la cita.</td><td valign="top">2</td>
      <td valign="top">Salvador Salinas</td><td valign="top">Done</td>
    </tr>
    <tr>
      <td valign="top" rowspan="2">US06</td><td valign="top" rowspan="2">Notificación de citas al asesor</td><td valign="top">TS06</td><td valign="top">Implementación de visualización de notificaciones al asesor</td><td valign="top">Se implementa el componente que muestra la vista de notificaciones para los asesores.</td><td valign="top">2</td>
      <td valign="top">Salvador Salinas</td><td valign="top">Done</td>
    </tr>
    <tr>
      <td valign="top">TS07</td><td valign="top">Implementación de eliminación de notificaciones al asesor</td><td valign="top">Se implementa la función que permite eliminar una notificación.</td><td valign="top">2</td><td valign="top">Salvador Salinas</td><td valign="top">Done</td>
    </tr>
    <tr>
      <td valign="top" rowspan="3">US07</td><td valign="top" rowspan="3">Notificación de citas al criador</td><td valign="top">TS08</td><td valign="top">Implementación de visualización de notificaciones al criador</td><td valign="top">Se implementa el componente que muestra la vista de notificaciones para los criadores.</td><td valign="top">2</td>
      <td valign="top">Nadia Lucas</td><td valign="top">Done</td>
    </tr>
    <tr>
      <td valign="top">TS09</td><td valign="top">Implementación de eliminación de notificaciones al criador</td><td valign="top">Se implementa la función que permite eliminar una notificación.</td><td valign="top">2</td><td valign="top">Nadia Lucas</td><td valign="top">Done</td>
    </tr>
    <tr>
      <td valign="top">TS10</td><td valign="top">Implementación de Pantalla de Resultados Vacíos</td><td valign="top">Se implementa un componente que recibe un mensaje como parámetro y permite mostrar una vista cuando no se encuentren datos disponibles.</td><td valign="top">2</td><td valign="top">Nadia Lucas</td><td valign="top">Done</td>
    </tr>
    <tr>
      <td valign="top">US08</td><td valign="top">Calificación al asesor luego de una cita</td><td valign="top">TS11</td><td valign="top">Implementación de registro de calificación del asesor</td><td valign="top">Se implementa la funcionalidad en el componente para registrar la calificación del asesor brindada por el criador.</td><td valign="top">1</td>
      <td valign="top">Andre Valverde</td><td valign="top">Done</td>
    </tr>
    <tr>
      <td valign="top" rowspan="2">US09</td>
      <td valign="top" rowspan="2">Gestión de una publicación</td>
      <td valign="top">TS12</td>
      <td valign="top">Implementación de creación de publicaciones</td>
      <td valign="top">Se implementa el componente para crear nuevas publicaciones</td>
      <td valign="top">2</td>
      <td valign="top">Salvador Salinas</td>
      <td valign="top">Done</td>
    </tr>
    <tr>
      <td valign="top">TS13</td>
      <td valign="top">Implementación de eliminación de publicaciones</td>
      <td valign="top">Se implementa la función dentro del componente de publicaciones para eliminar una publicación</td>
      <td valign="top">2</td>
      <td valign="top">Salvador Salinas</td>
      <td valign="top">Done</td>
    </tr>
    <tr>
      <td valign="top">US10</td><td valign="top">Visualización de publicaciones de asesores</td><td valign="top">TS14</td><td valign="top">Implementación de visualización de publicaciones</td><td valign="top">Se implementa el componente para visualizar publicaciones de asesores para el criador.</td><td valign="top">1</td>
      <td valign="top">Salvador Salinas</td><td valign="top">Done</td>
    </tr>
    <tr>
      <td valign="top" rowspan="3">US11</td><td valign="top" rowspan="3">Gestión de jaulas de cuyes</td><td valign="top">TS15</td><td valign="top">Implementación de registro de una jaula</td><td valign="top">Se implementa el componente para registrar una nueva jaula de cuyes.</td><td valign="top">2</td><td valign="top">Sebastián Paredes</td><td valign="top">Done</td>
    </tr>
    <tr>
        <td valign="top">TS16</td><td valign="top">Implementación de edición de una jaula</td><td valign="top">Se implementa la función que permite editar la información de una jaula.</td><td valign="top">2</td><td valign="top">Piero Delgado</td><td valign="top">Done</td>
    </tr>
    <tr>
        <td valign="top">TS17</td><td valign="top">Implementación de eliminación de una jaula</td><td valign="top">Se implementa la función que permite eliminar una jaula junto a la información de los cuyes que habitan en ella.</td><td valign="top">1</td><td valign="top">Piero Delgado</td><td valign="top">Done</td>
    </tr>
    <tr>
      <td valign="top">US12</td><td valign="top">Registro de información de animales</td><td valign="top">TS18</td><td valign="top">Implementación de registro de un cuy</td><td valign="top">Se implementa el componente para registrar un cuy en una jaula existente.</td><td valign="top">2</td><td valign="top">Sebastián Paredes</td><td valign="top">Done</td>
    </tr>
    <tr>
      <td rowspan="2" valign="top">US13</td>
      <td rowspan="2" valign="top">Visualización y edición de información de animales</td>
      <td valign="top">TS19</td>
      <td valign="top">Implementación de vista de información de animales</td>
      <td valign="top">Se implementa el componente para visualizar las jaulas y el componente para visualizar la información de los cuyes.</td>
      <td valign="top">2</td><td valign="top">Piero Delgado</td><td valign="top">Done</td>
    </tr>
    <tr>
      <td valign="top">TS20</td><td valign="top">Implementación de edición de información de animales</td><td valign="top">Se implementa la edición dentro de la componente de jaula, así como la edición para la componente de información de un cuy.</td><td valign="top">2</td><td valign="top">Piero Delgado</td><td valign="top">Done</td>
    </tr>
    <tr>
      <td valign="top">US14</td>
      <td valign="top">Registro de fallecimiento de un cuy</td>
      <td valign="top">TS21</td><td valign="top">Implementación de cambio de estado de un cuy</td>
      <td valign="top">Se implementa la función para cambiar el estado a fallecido dentro de la componente de información de cuy.</td>
      <td valign="top">1</td><td valign="top">Piero Delgado</td>
      <td valign="top">Done</td>
    </tr>
    <tr>
      <td rowspan="2" valign="top">US15</td>
      <td rowspan="2" valign="top">Gestión de recursos de la granja</td>
      <td valign="top">TS22</td>
      <td valign="top">Implementación de registro de recurso</td>
      <td valign="top">Se implementa el componente para registrar un recurso para el criador.</td>
      <td valign="top">2</td><td valign="top">Sebastián Paredes</td><td valign="top">Done</td>
    </tr>
    <tr>
      <td valign="top">TS23</td>
      <td valign="top">Implementación de vista de recursos</td>
      <td valign="top">Se implementa el componente para la vista de los recursos del criador</td>
      <td valign="top">2</td><td valign="top">Nadia Lucas</td>
      <td valign="top">Done</td>
    </tr>
    <tr>
      <td rowspan="2" valign="top">US16</td>
      <td rowspan="2" valign="top">Gestión de gastos realizados</td>
      <td valign="top">TS24</td>
      <td valign="top">Implementación de registro de gasto</td>
      <td valign="top">Se implementa el componente para registrar un gasto para el criador.</td>
      <td valign="top">1</td>
      <td valign="top">Sebastián Paredes</td>
      <td valign="top">Done</td>
    </tr>
    <tr>
      <td valign="top">TS25</td>
      <td valign="top">Implementación de vista de gastos</td>
      <td valign="top">Se implementa el componente para la vista de los recursos del criador.</td>
      <td valign="top">1</td><td valign="top">Nadia Lucas</td>
      <td valign="top">Done</td>
    </tr>
    <tr>
      <td valign="top">US24</td>
      <td valign="top">Visualización de la sección "Acerca De"</td>
      <td valign="top">TS26</td><td valign="top">Mejorar diseño y contenido de la sección "Acerca De"</td>
      <td valign="top">Se mejora el contenido de la página sobre la problemática, sobre nosotros, características y contacto.</td>
      <td valign="top">2</td><td valign="top">Nadia Lucas, Piero Delgado, Salvador Salinas, Sebastián Paredes</td>
      <td valign="top">Done</td>
    </tr>
    <tr>
      <td valign="top">US25</td>
      <td valign="top">Visualización de la sección "Sobre Nosotros"</td>
      <td valign="top">TS27</td>
      <td valign="top">Mejorar diseño y contenido de la sección "Sobre Nosotros"</td>
      <td valign="top">Se mejora el diseño y contenido de la sección "Sobre Nosotros" para proporcionar información clara y concisa sobre el equipo y la misión.</td>
      <td valign="top">2</td>
      <td valign="top">Nadia Lucas, Piero Delgado, Salvador Salinas, Sebastián Paredes</td>
      <td valign="top">Done</td>
    </tr>
    <tr>
      <td valign="top">US26</td>
      <td valign="top">Visualización de la sección "Características"</td>
      <td valign="top">TS28</td>
      <td valign="top">Mejorar diseño y contenido de la sección "Características"</td>
      <td valign="top">Se mejora el diseño y contenido de la sección "Características" para resaltar las funcionalidades clave de la plataforma.</td>
      <td valign="top">2</td>
      <td valign="top">Nadia Lucas, Piero Delgado, Salvador Salinas, Sebastián Paredes</td><td valign="top">Done</td>
    </tr>
    <tr>
      <td valign="top">US27</td>
      <td valign="top">Visualización de la sección "Contacto"</td>
      <td valign="top">TS29</td>
      <td valign="top">Mejorar diseño y contenido de la sección "Contacto"</td>
      <td valign="top">Se mejora el diseño y contenido de la sección "Contacto" para facilitar la comunicación entre usuarios y el equipo de soporte.</td>
      <td valign="top">1</td>
      <td valign="top">Nadia Lucas, Piero Delgado, Salvador Salinas, Sebastián Paredes</td><td valign="top">Done</td>
    </tr>
</table>

#### 5.2.2.3. Development Evidence for Sprint Review.

Se realizaron los avances con los commits correspondientes en los repositorios del Landing Page y Frontend Web Applications de la siguiente forma.

|**Repository**|**Branch**|**Commit Id**|**Commit Message**|**Commited on (Date)**|
| :- | :- | :- | :- | :- |
|AgroTech-UPC/Landing-Page|feature/about-us|b658932|feat: added develop team and fixed font size|25/04/2024|
|AgroTech-UPC/Landing-Page|feature/about-app|393d06a|fix: fixed font size|25/04/2024|
|AgroTech-UPC/Landing-Page|feature/about-us|5d05343|feat: Added improvements in about-us section|26/04/2024|
|AgroTech-UPC/Landing-Page|feature/about-app|ac57c51|feat: added more images and redesign problem section|01/05/2024|
|AgroTech-UPC/Landing-Page|feature/characteristics|74704dc|feat: added improvements in features section|02/05/2024|
|AgroTech-UPC/Landing-Page|feature/about-app|3bbb28b|feat: Added improvements in about-app section|02/05/2024|
|AgroTech-UPC/Landing-Page|main|35548e5|Merge pull request #24 from AgroTech-UPC/develop|02/05/2024|
|AgroTech-UPC/Frontend-Web-Applications|main|303c08c|chore: Setting up the work environment|23/04/2024|
|AgroTech-UPC/Frontend-Web-Applications|feature/header-sidenav|3217293|feat: Added header and sidenav|30/04/2024|
|AgroTech-UPC/Frontend-Web-Applications|feature/json-data|74089d5|chore: added json-server configuration files|30/04/2024|
|AgroTech-UPC/Frontend-Web-Applications|feature/json-data|5a83167|feat: Updated db.json includes users, advisors, resources and resource\_breed|30/04/2024|
|AgroTech-UPC/Frontend-Web-Applications|feature/json-data|c61773a|feat: added breeders, appointments, publications, notifications|30/04/2024|
|AgroTech-UPC/Frontend-Web-Applications|feature/my-farm-view|15298b8|feat: added my farm view component for breeder|30/04/2024|
|AgroTech-UPC/Frontend-Web-Applications|feature/header-sidenav|c29f9bb|fix: fixed sidenav visibility and added button|30/04/2024|
|AgroTech-UPC/Frontend-Web-Applications|feature/my-farm-resource-management|a856a03|feat: Create a my-farm-resource-management.component|30/04/2024|
|AgroTech-UPC/Frontend-Web-Applications|feature/header-sidenav|a853c26|fix: fixed padding on sidebar|30/04/2024|
|AgroTech-UPC/Frontend-Web-Applications|feature/my-farm-resource-management|711e7cb|feat: Resource management completed|01/05/2024|
|AgroTech-UPC/Frontend-Web-Applications|feature/my-farm-resource-management|a2546de|feat: added responsive version|01/05/2024|
|AgroTech-UPC/Frontend-Web-Applications|feature/register|0718256|feat: register-cage component added|01/05/2024|
|AgroTech-UPC/Frontend-Web-Applications|feature/register|38767f5|feat: register cage component and functionality added|01/05/2024|
|AgroTech-UPC/Frontend-Web-Applications|feature/my-farm-expenses-management|3a05500|feat: my-farm-expenses-management view completed|01/05/2024|
|AgroTech-UPC/Frontend-Web-Applications|feature/my-farm-expenses-management|a58148b|feat: added aria labels|01/05/2024|
|AgroTech-UPC/Frontend-Web-Applications|feature/register|0f32e71|fix: issue with confirmation of register solved with snackbar|01/05/2024|
|AgroTech-UPC/Frontend-Web-Applications|feature/register|f038f92|fix: method handleClick() fixed|01/05/2024|
|AgroTech-UPC/Frontend-Web-Applications|feature/register|ef8b3d6|feat: register-cuy section added|01/05/2024|
|AgroTech-UPC/Frontend-Web-Applications|feature/register|6684f5c|feat: section register-expense added|01/05/2024|
|AgroTech-UPC/Frontend-Web-Applications|feature/my-animals|c359b67|feat: added routes for my animals|01/05/2024|
|AgroTech-UPC/Frontend-Web-Applications|feature/my-animals|d0e2622|feat: added confirmation dialog component|01/05/2024|
|AgroTech-UPC/Frontend-Web-Applications|feature/my-animals|7a4191d|feat: added animal and cage models|01/05/2024|
|AgroTech-UPC/Frontend-Web-Applications|feature/my-animals|01007d4|feat: added http service|01/05/2024|
|AgroTech-UPC/Frontend-Web-Applications|feature/notifications-view|f7c7ee9|feat: added notification view|01/05/2024|
|AgroTech-UPC/Frontend-Web-Applications|feature/my-animals|603b0b4|feat: added table with cages|01/05/2024|
|AgroTech-UPC/Frontend-Web-Applications|feature/my-animals|10bbcc6|feat: added edit cage form|01/05/2024|
|AgroTech-UPC/Frontend-Web-Applications|feature/my-animals|a80172b|feat: added view for animals in a specific cage|01/05/2024|
|AgroTech-UPC/Frontend-Web-Applications|feature/my-animals|7841c9c|feat: added form for visualizing and editing animal information|01/05/2024|
|AgroTech-UPC/Frontend-Web-Applications|feature/clients|a9302f7|feat: clients appointments view for advisor|01/05/2024|
|AgroTech-UPC/Frontend-Web-Applications|feature/notifications-advisor|899e8d0|feat: added notifications view for advisor|01/05/2024|
|AgroTech-UPC/Frontend-Web-Applications|feature/publication|40b03dc|feat: added my publications view|01/05/2024|
|AgroTech-UPC/Frontend-Web-Applications|feature/notifications-view|e6511c1|feat: sorted folders with the ddd|01/05/2024|
|AgroTech-UPC/Frontend-Web-Applications|feature/publication|3d4b64a|feat: added publication detail view|01/05/2024|
|AgroTech-UPC/Frontend-Web-Applications|feature/publication|7dd310a|feat: added new publication feature for advisor|01/05/2024|
|AgroTech-UPC/Frontend-Web-Applications|feature/register|b442663|feat: register-resources section added|01/05/2024|
|AgroTech-UPC/Frontend-Web-Applications|feature/register|c62a0f8|fix: organization of components and services were fixed|01/05/2024|
|AgroTech-UPC/Frontend-Web-Applications|feature/notifications-advisor|12dcb5d|fix: fixed model for notification|01/05/2024|
|AgroTech-UPC/Frontend-Web-Applications|feature/notifications-view|7f0beb7|fix: conflict with header solved|01/05/2024|
|AgroTech-UPC/Frontend-Web-Applications|develop|60598bd|fix: fixed go back buttons and notifications for advisor|02/05/2024|
|AgroTech-UPC/Frontend-Web-Applications|feature/publication|6504622|feat: added feature to delete publications|02/05/2024|
|AgroTech-UPC/Frontend-Web-Applications|feature/appointment|f3de032|feat: Added Sections: Search advisors, more information about an advisor, view advisor reviews, view advisor schedules, and book an appointment|02/05/2024|
|AgroTech-UPC/Frontend-Web-Applications|feature/appointment|1429648|fix: fixed link that redirects the “back” button|02/05/2024|
|AgroTech-UPC/Frontend-Web-Applications|feature/appointment|b566228|feat: Added interface my advisors|02/05/2024|
|AgroTech-UPC/Frontend-Web-Applications|feature/appointment|9d1a9dd|feat: Functionality was added to the “My advisors” section|02/05/2024|
|AgroTech-UPC/Frontend-Web-Applications|feature/appointment|f2be04b|feat: The search bar was implemented|02/05/2024|
|AgroTech-UPC/Frontend-Web-Applications|feature/appointment|eb9e789|fix: Solution to redirect button|03/05/2024|
|AgroTech-UPC/Frontend-Web-Applications|feature/appointment|33f23e9|feat: Added Review section|03/05/2024|

#### 5.2.2.4. Testing Suite Evidence for Sprint Review.
Se realizaron las pruebas de aceptación para las historias de usuario trabajadas utilizando el lenguaje Gherkin en archivos feature. De esta manera, se registraron en el repositorio.

|**Repository**|**Branch**|**Commit Id**|**Commit Message**|**Commited on (Date)**|
| :- | :- | :- | :- | :- |
|AgroTech-UPC/Acceptance-Tests|main|b046326|feat: added acceptance test for US13|01/05/2024|
|AgroTech-UPC/Acceptance-Tests|main|964877f|feat: added acceptance test for US14|01/05/2024|
|AgroTech-UPC/Acceptance-Tests|main|c8e984d|feat: added acceptance test for US06|02/05/2024|
|AgroTech-UPC/Acceptance-Tests|main|950fb0b|feat: added acceptance test for US08, US09|02/05/2024|
|AgroTech-UPC/Acceptance-Tests|main|718cd68|feat: added acceptance test for US11, US12, US15|02/05/2024|
|AgroTech-UPC/Acceptance-Tests|main|209c8d5|feat: Updated features 06 and 15, and added features 07 and 16|03/05/2024|
|AgroTech-UPC/Acceptance-Tests|main|a16a719|feat: Added User Stories: 01, 02, 03, 04, 05|03/05/2024|

#### 5.2.2.5. Execution Evidence for Sprint Review.

En esta sección, se mostrará lo avanzado en el segundo sprint, el cual se basa en la nueva versión de la landing page y el despliegue del Frontend-Web-Application de AgroConnect.

**Evidencia de la landing page:**

- Se implementaron flip cards en la sección “Problemática” que contienen información relevante para nuestro segmento objetivo.

<img src="img/landing-page-1.jpg" width="100%">
  En este apartado, también se añadió información sobre los dos segmentos objetivos.

<img src="img/landing-page-2.jpg" width="100%">

- Se realizaron mejoras en el diseño de la sección “características”.

<img src="img/landing-page-3.jpg" width="100%">

- Se realizaron mejoras en el diseño de la sección “Sobre Nosotros”.

<img src="img/landing-page-4.jpg" width="100%">
En este apartado también se añadieron las fotos del equipo de desarrollo.

<img src="img/landing-page-5.jpg" width="100%">

- Se realizaron mejoras en el diseño de la sección “Contacto”.

<img src="img/landing-page-6.jpg" width="100%">

**Evidencia del Frontend-Web-Application:**

Se implementó todas las historias de usuario en el sprint backlog, a excepción de la primera que tiene que ver con el Landing Page, para el primer release del Frontend de nuestra aplicación web. Para ello, se grabó el siguiente video de explicación en el cual se muestran todos los procesos alcanzados.

URL de video:
[Execution Evidence](https://upcedupe-my.sharepoint.com/:v:/g/personal/u20221b127_upc_edu_pe/EYY0ErnjEsFBiUZXlO60wHQBnqjOJRxM13gjVWm8Gpbbzg?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJPbmVEcml2ZUZvckJ1c2luZXNzIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXciLCJyZWZlcnJhbFZpZXciOiJNeUZpbGVzTGlua0NvcHkifX0&e=Hd2T2Y)
<img src="img/front-web-evidence.png">

#### 5.2.2.6. Services Documentation Evidence for Sprint Review.

En el alcance de este sprint 2, se ha priorizado el desarrollo de la parte de Front-end de la aplicación web, por lo que en este caso no se evidencia el empleo de web services.

#### 5.2.2.7. Software Deployment Evidence for Sprint Review.

Para el caso del Landing Page, se hizo el deployment igualmente a través de GitHub Pages, y se accede a esta a través del siguiente enlace: https://agrotech-upc.github.io/Landing-Page/home.html


Para el Frontend Web Application, utilizamos la página https://my-json-server.typicode.com/ para alojar nuestros API creados a partir del db.json, solo creamos los repositorios en GitHub que alojan cada parte de nuestro API, el cual tuvimos que dividirlo en tres ya que hay un límite de 5 endpoints. Estos se pueden encontrar en los siguientes enlaces:
https://my-json-server.typicode.com/salvadoorssalinas/api-1
https://my-json-server.typicode.com/salvadoorssalinas/api-2
https://my-json-server.typicode.com/salvadoorssalinas/api-3

<img src="img/json-server-salvador.png" width="100%">

Por otro lado, para el deployment del Frontend Web Application Para ello, seguimos los siguientes pasos:

Primero, se utilizó el comando ng build para crear la carpeta dist, la cual sirve para realizar el deployment en Firebase.
<img src="img/deployment1.png" width="100%">
<img src="img/deployment2.png" width="100%">

Luego, se utilizó el comando de lite-server para comprobar el funcionamiento de la aplicación
<img src="img/deployment3.png" width="100%">

Se instaló firebase-tools dentro del proyecto, y luego se inició sesión.
<img src="img/deployment4.png" width="100%">
<img src="img/deployment5.png" width="100%">

Se crea el proyecto Firebase en el cual se guardará todos los archivos, el cual le pusimos como nombre agroconnect-demo.
<img src="img/deployment6.png" width="100%">

Se ejecuta el comando para instalar @angular/fire.
<img src="img/deployment7.png" width="100%">

Se selecciona la opción ng deploy -- hosting.
<img src="img/deployment8.png" width="100%">

Se selecciona el proyecto y se crea el enlace donde se aloja el proyecto
<img src="img/deployment9.png" width="100%">

Se modifica el archivo firebase.json de la siguiente forma:
<img src="img/deployment10.png" width="100%">

Se usa el comando ng deploy para deployear la aplicación
<img src="img/deployment11.png" width="100%">
<img src="img/deployment12.png" width="100%">

Finalmente, logramos acceder a nuestra aplicación deployada.
<img src="img/deployment13.png" width="100%">

URL de Frontend Web Application deployado: https://agroconnect-demo.web.app/home

#### 5.2.2.8. Team Collaboration Insights during Sprint.

Para la elaboración del Frontend, nos repartimos las tareas entre cada miembro, y cada uno trabajó en las ramas feature correspondientes, para luego ir realizando los merge con la rama develop. Asimismo, nos reunimos de forma virtual a través de Google Meet para revisar juntos los avances y los merges realizados para verificar que todo funciona acorde a lo esperado.

<img src="img/team-collaboration-1.jpg" width="100%">

<img src="img/team-collaboration-2.jpg" width="100%">

<img src="img/team-collaboration-3.jpg" width="100%">

<img src="img/team-collaboration-4.png" width="100%">

### 5.2.3. Sprint 3.

#### 5.2.3.1. Sprint Planning 3.

El tercer sprint se planeó a través de una reunión virtual en Google Meet. Para ello, se hizo la siguiente tabla para registrar la información que se discutió.


|**Sprint #**|Sprint 3|
| :- | :- |
|**Sprint Planning Background**||
|Date|2024-05-14|
|Time|09: 00 PM|
|Location|Virtual (Google Meet)|
|Prepared by|Delgado Corrales, Piero Gonzalo|
|Attendees (to planning meeting)|<p>Delgado Corrales, Piero Gonzalo</p><p>Lucas Coronel, Nadia Alessandra</p><p>Paredes Puente, Sebastián Roberto</p><p>Salinas Torres, Salvador Antonio</p><p>Valverde Mozo, Andre Gabriel</p>|
|Sprint 2 Review Summary|En el sprint 2, se realizó la implementación y deployment del Frontend de la aplicación web.|
|Sprint 2 Retrospective Summary|Este segundo sprint consistió principalmente en Frontend, aunque faltaron algunas partes a desarrollar y realizar algunas mejoras en las historias de usuario.|
|**Sprint Goal & User Stories**||
|Sprint 3 Goal|Desarrollar la parte faltante en Frontend y empezar con el desarrollo de Backend de la aplicación web.|
|Sprint 3 Velocity|-|
|Sum of Story Points|-|

#### 5.2.3.2. Sprint Backlog 3.

#### 5.2.3.3. Development Evidence for Sprint Review.

#### 5.2.3.4. Testing Suite Evidence for Sprint Review.

#### 5.2.3.5. Execution Evidence for Sprint Review.

#### 5.2.3.6. Services Documentation Evidence for Sprint Review.

#### 5.2.3.7. Software Deployment Evidence for Sprint Review.

#### 5.2.3.8. Team Collaboration Insights during Sprint.

## 5.3. Validation Interviews.

### 5.3.1. Diseño de entrevistas.

### 5.3.2. Registro de entrevistas.

### 5.3.3. Evaluaciones según heurísticas.

## 5.4. Video About-The-Product

# Conclusiones
## Conclusiones y recomendaciones
* La estructura realizada del proceso Lean UX ha permitido a nuestra startup AgroTech identificar los segmentos objetivos, competidores y necesidades del mercado, entre otros aspectos clave. Desde la formulación inicial de los problem statements hasta la elaboración de hypothesis statements y la creación del Lean UX canvas, cada paso ha contribuido a mejorar la eficiencia y la agilidad en el desarrollo de la aplicación AgroConnect.


* AgroTech ha realizado un análisis exhaustivo de sus competidores, así como entrevistas y actividades de needfinding para comprender las necesidades de sus usuarios. Lo anteriormente desarrollado se realizó en el capítulo II, dónde se realizó dicha investigación y análisis que aportaron con la creación de una solución como lo es AgroConnect, para que satisfaga las necesidades reales de sus usuarios.


* Plantear e identificar los requisitos del proyecto al inicial fue crucial, ya que establecieron las bases sólidas sobre las cuales se construirá la aplicación AgroConnect de AgroTech, estas se lograron identificar gracias a los empathy mappings, impact mappings y user personas ayudaron a empatizar y estar en el lugar de nuestro públic objetivo, As-is y To-Be Scenario Mappings que permiten visualizar el proceso en el que realiza una tarea sin y con AgroConnect respectivamente. Además, las user stories proporcionaron una descripción detallada de las interacciones que los usuarios tendrán con la aplicación, lo que es fundamental para brindar una experiencia de usuario satisfactoria. Finalmente, el product backlog estableció la lista priorizada de todas las funcionalidades y características que se implementarán en la aplicación y reducir los esfuerzos en el desarrollo de la aplicación.

# Video About-The-Team


# Bibliografía

Aguilar, G., Bustamante, J., Bazán, V. y Falcón, N. (2011). Diagnóstico situacional de la crianza de cuyes en una zona de Cajamarca. _Revista de Investigaciones Veterinarias del Perú, 22_(1), 09-14. http://www.scielo.org.pe/scielo.php?script=sci_arttext&pid=S1609-91172011000100002&lng=es&tlng=es

Guerra, C. (2009). _Manual técnico de crianza de cuyes_. Cedepas. https://www.cedepas.org.pe/sites/default/files/manual_tecnico_de_crianza_de_cuyes.pdf

Instituto Nacional de Innovación Agraria. (23 de enero de 2023). Razas de cuyes del INIA mejoran un 20% la productividad de la crianza familiar y consumo de carne. _El Peruano_. https://www.elperuano.pe/noticia/225260-razas-de-cuyes-del-inia-mejoran-un-20-la-productividad-de-la-crianza-familiar-y-consumo-de-carne


Luque, R. (2023). _Meta Tags | Las 7 más importantes en SEO_. SEOcrawl. https://seocrawl.com/meta-tags/

Ministerio de Desarrollo Agrario y Riego. (2023). _Cadena productiva de cuyes_. https://cdn.www.gob.pe/uploads/document/file/4061856/Cadena%20productiva%20de%20cuy.pdf

SENASA. (2019). _Cajamarca es el principal productor de cuy en el Perú_. https://www.senasa.gob.pe/senasacontigo/cajamarca-es-el-principal-productor-de-cuy-en-el-peru/


# Anexos

## Anexo N°1: Gráfico de evolución de población de cuyes

<img src="img/grafico-anexo.png">

_Imagen 141. Gráfico - poblacion de cuyes_

Recuperado de: https://cdn.www.gob.pe/uploads/document/file/4061856/Cadena%20productiva%20de%20cuy.pdf

## Anexo N°2: Diagrama de problemas en la crianza de cuyes

<img src="img/cuadro-anexo.png">

_Imagen 142. Cuadro - problemas de la crianza de cuyes_

## Anexo N°3: Web Style Guidelines

[https://www.figma.com/file/y65W2Fnk2IreDIFC3yPTAl/Open--Web-Style-Guidelines?type=design&node-id=0%3A1&mode=design&t=wpjgQEwVQwYdQHGP-1 ](https://www.figma.com/file/y65W2Fnk2IreDIFC3yPTAl/Open--Web-Style-Guidelines?type=design&node-id=0%3A1&mode=design&t=wpjgQEwVQwYdQHGP-1 )

## Anexo N°4: Video de exposiciones

Exposición del TB1: [upc-pre-202401-si729-wx52-agrotech-expo-tb1.mp4](https://upcedupe-my.sharepoint.com/:v:/g/personal/u202210749_upc_edu_pe/EZz3pjA0mJhDvymuSBI8WywBb2DCa7RrK25a5osiHJz_zw?e=aeuDy3)

Exposición del TP: [upc-pre-202401-si729-wx52-agrotech-expo-tp1.mp4](https://upcedupe-my.sharepoint.com/:v:/g/personal/u202210749_upc_edu_pe/EcuWnAtFFa5Aseqn8_glQZwBhxi1acBsSWeR7ko-zFCT3g?e=yVgPhv)


## Anexo N°5: Prototipo de la aplicación web
Enlace del prototipo en figma: [https://www.figma.com/proto/y65W2Fnk2IreDIFC3yPTAl/Open--Web-Style-Guidelines?type=design&node-id=296-1548&t=75RhDMIrAZo5uqGx-1&scaling=contain&page-id=112%3A67&starting-point-node-id=296%3A1548](https://www.figma.com/proto/y65W2Fnk2IreDIFC3yPTAl/Open--Web-Style-Guidelines?type=design&node-id=296-1548&t=75RhDMIrAZo5uqGx-1&scaling=contain&page-id=112%3A67&starting-point-node-id=296%3A1548)

## Anexo N°6: Explicación del prototipo
Enlace: [Explicación del prototipo](https://youtu.be/lTo_Pz0j2vc)
