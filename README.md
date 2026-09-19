<p align="center">
COURSE PROJECT

<p align="center">
    <img src="https://upload.wikimedia.org/wikipedia/commons/f/fc/UPC_logo_transparente.png"></img><br>
    <strong>Universidad Peruana de Ciencias Aplicadas</strong><br>
    <br>
    <strong>Facultad de Ingeniería</strong><br>
    <strong>Carrera de Ingeniería de Software</strong><br>
    <strong>Ciclo 2026-2</strong>
</p>

<p align="center">
  <strong>Código del curso: </strong>1ACC0238<br>
  <strong>Curso: </strong>Aplicaciones para Dispositivos Móviles
</p>

<p align="center">
  <strong>NRC: 4945</strong>
</p>

<p align="center">
    <strong>Profesor: </strong>Mayta Guillermo, Jorge Luis
</p>

<p align="center">
    <strong>Informe de la TB1</strong>
</p>

<p align="center">
    <strong>Nombre del startup: </strong> NexoraPe
</p>

<p align="center">
    <strong>Nombre del producto:</strong> SafeWork
</p>

<div>
    <h3 align="center">Integrantes del equipo:</h3>
    </div>
<div>
     <table align="center">
        <tr>
            <th style="text-align:center;">Nombre</th>
            <th style="text-align:center;">Código</th>
        </tr>
        <tr>
            <td>Ruiz Huisa, Daniel Elias </td>
            <td>u202210764</td>
        </tr>
        <tr>
            <td>Apellido, Nombre </td>
            <td>Codigo</td>
        </tr>
        <tr>
            <td>Apellido, Nombre </td>
            <td>Codigo</td>
        </tr>
    </table>
</div>

<p align="center">
    <strong>Septiembre, 2026</strong>
</p>

---

# Registro de Versiones del Informe

| **Versión** | **Fecha** | **Autor** | **Descripción de modificación** |
|     ---     |     ---   |     ---   |             ---                 |
| 1.0 | 18/09/2026 | R. Daniel| Se adapto el proyecto utilizado anteriormente a la nueva plantilla de contenidos |




---

# Project Report Collaboration Insights
**URL del repositorio para el Project Report:** [Reporte](https://github.com/NexoraPe-1ACC0238-2620-4945/report.git) 


**TB1**

---

<div style="page-break-after: always;">

# Contenido

- [Registro de Versiones del Informe](#registro-de-versiones-del-informe)
- [Project Report Collaboration Insights](#project-report-collaboration-insights)
- [Contenido](#contenido)
- [Student Outcome](#student-outcome)
- [Objetivos SMART](#objetivos-smart)
- [Capítulo I: Presentación](#capítulo-i-presentación)
  - [1.1. Startup Profile](#11-startup-profile)
    - [1.1.1. Descripción de la Startup](#111-descripción-de-la-startup)
    - [1.1.2. Perfiles de integrantes del equipo](#112-perfiles-de-integrantes-del-equipo)
  - [1.2. Solution Profile](#12-solution-profile)
    - [1.2.1. Antecedentes y problemática](#121-antecedentes-y-problemática)
        - [**¿Cuál es el problema? (What)**](#cuál-es-el-problema-what)
    - [1.2.2. Lean UX Process](#122-lean-ux-process)
      - [1.2.2.1. Lean UX Problem Statements](#1221-lean-ux-problem-statements)
      - [1.2.2.2. Lean UX Assumptions](#1222-lean-ux-assumptions)
      - [1.2.2.3. Lean UX Hypothesis Statements](#1223-lean-ux-hypothesis-statements)
      - [1.2.2.4. Lean UX Canvas](#1224-lean-ux-canvas)
  - [1.3. Segmentos objetivo](#13-segmentos-objetivo)
- [Capítulo II: Requirements Development and Software Solution Design](#capítulo-ii-requirements-development-and-software-solution-design)
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
    - [2.3.5. Big Picture EventStorming](#235-big-picture-eventstorming)
    - [2.3.6. Ubiquitous Language](#236-ubiquitous-language)
  - [2.4. Requirements specification](#24-requirements-specification)
    - [2.4.1. User Stories](#241-user-stories)
    - [2.4.2. Impact Mapping](#242-impact-mapping)
    - [2.4.3. Product Backlog](#243-product-backlog)
  - [2.5. Strategic-Level Domain-Driven Design](#25-strategic-level-domain-driven-design)
    - [2.5.1. EventStorming](#251-eventstorming)
      - [2.5.1.1. Candidate Context Discovery](#2511-candidate-context-discovery)
      - [2.5.1.2. Domain Message Flows Modeling](#2512-domain-message-flows-modeling)
      - [2.5.1.3. Bounded Context Canvases](#2513-bounded-context-canvases)
    - [2.5.2. Context Mapping](#252-context-mapping)
    - [2.5.3. Software Architecture](#253-software-architecture)
      - [2.5.3.1. Software Architecture Context Level Diagrams](#2531-software-architecture-context-level-diagrams)
      - [2.5.3.2. Software Architecture Container Level Diagrams](#2532-software-architecture-container-level-diagrams)
      - [2.5.3.3. Software Architecture Deployment Diagrams](#2533-software-architecture-deployment-diagrams)
  - [2.6. Tactical-Level Domain-Driven Design](#26-tactical-level-domain-driven-design)
    - [2.6.x. Bounded Context: ](#26x-bounded-context-)
      - [2.6.x.1. Domain Layer](#26x1-domain-layer)
      - [2.6.x.2. Interface Layer](#26x2-interface-layer)
      - [2.6.x.3. Application Layer](#26x3-application-layer)
      - [2.6.x.4. Infrastructure Layer](#26x4-infrastructure-layer)
      - [2.6.x.5. Bounded Context Software Architecture Component Level Diagrams](#26x5-bounded-context-software-architecture-component-level-diagrams)
      - [2.6.x.6. Bounded Context Software Architecture Code Level Diagrams](#26x6-bounded-context-software-architecture-code-level-diagrams)
        - [2.6.x.6.1. Bounded Context Domain Layer Class Diagrams](#26x61-bounded-context-domain-layer-class-diagrams)
        - [2.6.x.6.2. Bounded Context Database Design Diagram](#26x62-bounded-context-database-design-diagram)
- [Capítulo III: Solution UI/UX Design](#capítulo-iii-solution-uiux-design)
  - [3.1. Product design](#31-product-design)
    - [3.1.1. Style Guidelines](#311-style-guidelines)
      - [3.1.1.1. General Style Guidelines](#3111-general-style-guidelines)
    - [3.1.2. Information Architecture](#312-information-architecture)
      - [3.1.2.1. Organization Systems](#3121-organization-systems)
      - [3.1.2.2. Labelling Systems](#3122-labelling-systems)
      - [3.1.2.3. SEO Tags and Meta Tags](#3123-seo-tags-and-meta-tags)
      - [3.1.2.4. Searching Systems](#3124-searching-systems)
      - [3.1.2.5. Navigation Systems](#3125-navigation-systems)
    - [3.1.3. Landing Page UI Design](#313-landing-page-ui-design)
      - [3.1.3.1. Landing Page Wireframe](#3131-landing-page-wireframe)
      - [3.1.3.2. Landing Page Mock-up](#3132-landing-page-mock-up)
    - [3.1.4. Mobile Applications UX/UI Design](#314-mobile-applications-uxui-design)
      - [3.1.4.1. Mobile Applications Wireframes](#3141-mobile-applications-wireframes)
      - [3.1.4.2. Mobile Applications Wireflow Diagrams](#3142-mobile-applications-wireflow-diagrams)
      - [3.1.4.3. Mobile Applications Mock-ups](#3143-mobile-applications-mock-ups)
      - [3.1.4.4. Mobile Applications User Flow Diagrams](#3144-mobile-applications-user-flow-diagrams)
      - [3.1.4.5. Mobile Applications Prototyping](#3145-mobile-applications-prototyping)
- [Capítulo IV: Product Implementation \& Validation](#capítulo-iv-product-implementation--validation)
  - [4.1. Software Configuration Management](#41-software-configuration-management)
    - [4.1.1. Software Development Environment Configuration](#411-software-development-environment-configuration)
    - [4.1.2. Source Code Management](#412-source-code-management)
    - [4.1.3. Source Code Style Guide \& Conventions](#413-source-code-style-guide--conventions)
    - [4.1.4. Software Deployment Configuration](#414-software-deployment-configuration)
  - [4.2. Landing Page \& Mobile Application Implementation](#42-landing-page--mobile-application-implementation)
    - [4.2.1. Sprint n](#421-sprint-n)
      - [4.2.1.1. Sprint Planning n](#4211-sprint-planning-n)
      - [4.2.1.2. Aspect Leaders and Collaborators](#4212-aspect-leaders-and-collaborators)
      - [4.2.1.3. Sprint Backlog n](#4213-sprint-backlog-n)
      - [4.2.1.4. Development Evidence for Sprint Review](#4214-development-evidence-for-sprint-review)
      - [4.2.1.5. Testing Suite Evidence for Sprint Review](#4215-testing-suite-evidence-for-sprint-review)
      - [4.2.1.6. Execution Evidence for Sprint Review](#4216-execution-evidence-for-sprint-review)
      - [4.2.1.7. Services Documentation Evidence for Sprint Review](#4217-services-documentation-evidence-for-sprint-review)
      - [4.2.1.8. Software Deployment Evidence for Sprint Review](#4218-software-deployment-evidence-for-sprint-review)
      - [4.2.1.9. Team Collaboration Insights during Sprint](#4219-team-collaboration-insights-during-sprint)
  - [4.3. Validation Interviews](#43-validation-interviews)
    - [4.3.1. Diseño de Entrevistas](#431-diseño-de-entrevistas)
    - [4.3.2. Registro de Entrevistas](#432-registro-de-entrevistas)
    - [4.3.3. Evaluaciones según heurísticas](#433-evaluaciones-según-heurísticas)
- [Conclusiones](#conclusiones)
  - [Conclusiones y recomendaciones](#conclusiones-y-recomendaciones)
- [Video App Validation](#video-app-validation)
  - [Video About the product](#video-about-the-product)
  - [Video About the team](#video-about-the-team)
- [Glosario](#glosario)
- [Bibliografía](#bibliografía)
- [Anexos](#anexos)

</div>

---

# Student Outcome

<div style="page-break-after: always;">

El curso contribuye al cumplimiento del Student Outcome ABET:<br>
**ABET - EAC - Student Outcome 7**

**Criterio:** La capacidad de adquirir y aplicar nuevos
conocimientos según sea necesario, utilizando estrategias de aprendizaje apropiadas.

En elsiguiente cuadro se describe las accionesrealizadas y enunciados de conclusiones
por parte del grupo, que permiten sustentar el haber alcanzado el logro del ABET –
EAC - Student Outcome 7.

<table>
  <thead>
    <tr>
      <th width="25%">Criterio específico</th>
      <th width="50%">Aportes Individuales</th>
      <th width="25%">Acciones realizadas (Equipo)</th>
    </tr>
  </thead>
  <tbody>
    <!-- FILA 1 -->
    <tr>
      <td><b>Actualiza conceptos y conocimientos necesarios para su desarrollo profesional y en especial para su proyecto en soluciones de software.</b></td>
      <td>
        <p><b>[Nombre de integrante 1]</b></p>
        <ul>
          <li><b>TB1:</b> [Aporte correspondiente a TB1 sobre actualización de conceptos y conocimientos]</li>
          <li><b>TP:</b> [Aporte correspondiente a TP sobre actualización de conceptos y conocimientos]</li>
          <li><b>TB2:</b> [Aporte correspondiente a TB2 sobre actualización de conceptos y conocimientos]</li>
          <li><b>TF:</b> [Aporte correspondiente a TF sobre actualización de conceptos y conocimientos]</li>
        </ul>
        <p><b>[Nombre de integrante 2]</b></p>
        <ul>
          <li><b>TB1:</b> [Aporte correspondiente a TB1 sobre actualización de conceptos y conocimientos]</li>
          <li><b>TP:</b> [Aporte correspondiente a TP sobre actualización de conceptos y conocimientos]</li>
          <li><b>TB2:</b> [Aporte correspondiente a TB2 sobre actualización de conceptos y conocimientos]</li>
          <li><b>TF:</b> [Aporte correspondiente a TF sobre actualización de conceptos y conocimientos]</li>
        </ul>
        <p><b>Ruiz Huisa, Daniel Elias</b></p>
        <ul>
          <li><b>TB1:</b> [Aporte correspondiente a TB1 sobre actualización de conceptos y conocimientos]</li>
          <li><b>TP:</b> [Aporte correspondiente a TP sobre actualización de conceptos y conocimientos]</li>
          <li><b>TB2:</b> [Aporte correspondiente a TB2 sobre actualización de conceptos y conocimientos]</li>
          <li><b>TF:</b> [Aporte correspondiente a TF sobre actualización de conceptos y conocimientos]</li>
        </ul>
        <p><b>[Nombre de integrante 3]</b></p>
        <ul>
          <li><b>TB1:</b> [Aporte correspondiente a TB1 sobre actualización de conceptos y conocimientos]</li>
          <li><b>TP:</b> [Aporte correspondiente a TP sobre actualización de conceptos y conocimientos]</li>
          <li><b>TB2:</b> [Aporte correspondiente a TB2 sobre actualización de conceptos y conocimientos]</li>
          <li><b>TF:</b> [Aporte correspondiente a TF sobre actualización de conceptos y conocimientos]</li>
        </ul>
      </td>
      <td>
        <ul>
          <li><b>TB1:</b> [Acción realizada por el equipo en TB1 para la actualización de conceptos]</li>
          <li><b>TP:</b> [Acción realizada por el equipo en TP para la actualización de conceptos]</li>
          <li><b>TB2:</b> [Acción realizada por el equipo en TB2 para la actualización de conceptos]</li>
          <li><b>TF:</b> [Acción realizada por el equipo en TF para la actualización de conceptos]</li>
        </ul>
      </td>
    </tr>
    <!-- FILA 2 -->
    <tr>
      <td><b>Reconoce la necesidad del aprendizaje permanente para el desempeño profesional y el desarrollo de proyectos en soluciones de software.</b></td>
      <td>
        <p><b>[Nombre de integrante 1]</b></p>
        <ul>
          <li><b>TB1:</b> [Aporte correspondiente a TB1 sobre aprendizaje permanente]</li>
          <li><b>TP:</b> [Aporte correspondiente a TP sobre aprendizaje permanente]</li>
          <li><b>TB2:</b> [Aporte correspondiente a TB2 sobre aprendizaje permanente]</li>
          <li><b>TF:</b> [Aporte correspondiente a TF sobre aprendizaje permanente]</li>
        </ul>
        <p><b>[Nombre de integrante 2]</b></p>
        <ul>
          <li><b>TB1:</b> [Aporte correspondiente a TB1 sobre aprendizaje permanente]</li>
          <li><b>TP:</b> [Aporte correspondiente a TP sobre aprendizaje permanente]</li>
          <li><b>TB2:</b> [Aporte correspondiente a TB2 sobre aprendizaje permanente]</li>
          <li><b>TF:</b> [Aporte correspondiente a TF sobre aprendizaje permanente]</li>
        </ul>
        <p><b>Ruiz Huisa, Daniel Elias</b></p>
        <ul>
          <li><b>TB1:</b> [Aporte correspondiente a TB1 sobre aprendizaje permanente]</li>
          <li><b>TP:</b> [Aporte correspondiente a TP sobre aprendizaje permanente]</li>
          <li><b>TB2:</b> [Aporte correspondiente a TB2 sobre aprendizaje permanente]</li>
          <li><b>TF:</b> [Aporte correspondiente a TF sobre aprendizaje permanente]</li>
        </ul>
        <p><b>[Nombre de integrante 3]</b></p>
        <ul>
          <li><b>TB1:</b> [Aporte correspondiente a TB1 sobre aprendizaje permanente]</li>
          <li><b>TP:</b> [Aporte correspondiente a TP sobre aprendizaje permanente]</li>
          <li><b>TB2:</b> [Aporte correspondiente a TB2 sobre aprendizaje permanente]</li>
          <li><b>TF:</b> [Aporte correspondiente a TF sobre aprendizaje permanente]</li>
        </ul>
      </td>
      <td>
        <ul>
          <li><b>TB1:</b> [Acción realizada por el equipo en TB1 para fomentar el aprendizaje permanente]</li>
          <li><b>TP:</b> [Acción realizada por el equipo en TP para fomentar el aprendizaje permanente]</li>
          <li><b>TB2:</b> [Acción realizada por el equipo en TB2 para fomentar el aprendizaje permanente]</li>
          <li><b>TF:</b> [Acción realizada por el equipo en TF para fomentar el aprendizaje permanente]</li>
        </ul>
      </td>
    </tr>
  </tbody>
</table>

<div style="page-break-after: always;">

# Objetivos SMART


<table>
  <thead>
    <tr>
      <th width="20%">Integrante</th>
      <th width="35%">Objetivo SMART 1 (Desarrollo Profesional)</th>
      <th width="35%">Objetivo SMART 2 (Desarrollo Profesional)</th>
      <th width="10%">Plan de Medición</th>
    </tr>
  </thead>
  <tbody>
    <!-- INTEGRANTE 1: TÚ -->
    <tr>
      <td><b>Ruiz Huisa, Daniel Elias</b></td>
      <td>
        <p><b>[Título breve del Objetivo 1]</b></p>
        <ul>
          <li><b>S (Específico):</b> [Qué habilidad, certificación o rol laboral específico planeas conseguir tras graduarte]</li>
          <li><b>M (Medible):</b> [Métrica clara, p. ej. obtener la certificación X, aprobar con puntaje Y, conseguir puesto Z]</li>
          <li><b>A (Alcanzable):</b> [Pasos previos o recursos que te permitirán lograrlo]</li>
          <li><b>R (Relevante):</b> [Cómo impacta este objetivo en tu carrera profesional a largo plazo]</li>
          <li><b>T (Temporal):</b> [Fecha límite o plazo exacto posterior a la graduación, p. ej., 6 meses post-graduación]</li>
        </ul>
      </td>
      <td>
        <p><b>[Título breve del Objetivo 2]</b></p>
        <ul>
          <li><b>S (Específico):</b> [Qué especialización o logro profesional buscas alcanzar]</li>
          <li><b>M (Medible):</b> [Métrica o entregable concreto que confirme su logro]</li>
          <li><b>A (Alcanzable):</b> [Estrategia o formación requerida]</li>
          <li><b>R (Relevante):</b> [Aporte al crecimiento profesional continuo]</li>
          <li><b>T (Temporal):</b> [Plazo de ejecución, p. ej., primer año posgrado/laboral]</li>
        </ul>
      </td>
      <td>
        <ul>
          <li><b>Revisión:</b> Semestral</li>
          <li><b>Evidencia:</b> Certificado / Contrato / Portafolio</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td><b>[Nombre de Integrante 2]</b></td>
      <td>
        <p><b>[Título breve del Objetivo 1]</b></p>
        <ul>
          <li><b>S (Específico):</b> [Descripción del objetivo profesional 1]</li>
          <li><b>M (Medible):</b> [Indicador de éxito]</li>
          <li><b>A (Alcanzable):</b> [Plan de acción inicial]</li>
          <li><b>R (Relevante):</b> [Importancia en su perfil laboral]</li>
          <li><b>T (Temporal):</b> [Tiempo de cumplimiento]</li>
        </ul>
      </td>
      <td>
        <p><b>[Título breve del Objetivo 2]</b></p>
        <ul>
          <li><b>S (Específico):</b> [Descripción del objetivo profesional 2]</li>
          <li><b>M (Medible):</b> [Indicador de éxito]</li>
          <li><b>A (Alcanzable):</b> [Plan de acción inicial]</li>
          <li><b>R (Relevante):</b> [Importancia en su perfil laboral]</li>
          <li><b>T (Temporal):</b> [Tiempo de cumplimiento]</li>
        </ul>
      </td>
      <td>
        <ul>
          <li><b>Revisión:</b> Anual</li>
          <li><b>Evidencia:</b> Documentación acreditada</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td><b>[Nombre de Integrante 3]</b></td>
      <td>
        <p><b>[Título breve del Objetivo 1]</b></p>
        <ul>
          <li><b>S (Específico):</b> [Descripción del objetivo profesional 1]</li>
          <li><b>M (Medible):</b> [Indicador de éxito]</li>
          <li><b>A (Alcanzable):</b> [Plan de acción inicial]</li>
          <li><b>R (Relevante):</b> [Importancia en su perfil laboral]</li>
          <li><b>T (Temporal):</b> [Tiempo de cumplimiento]</li>
        </ul>
      </td>
      <td>
        <p><b>[Título breve del Objetivo 2]</b></p>
        <ul>
          <li><b>S (Específico):</b> [Descripción del objetivo profesional 2]</li>
          <li><b>M (Medible):</b> [Indicador de éxito]</li>
          <li><b>A (Alcanzable):</b> [Plan de acción inicial]</li>
          <li><b>R (Relevante):</b> [Importancia en su perfil laboral]</li>
          <li><b>T (Temporal):</b> [Tiempo de cumplimiento]</li>
        </ul>
      </td>
      <td>
        <ul>
          <li><b>Revisión:</b> Anual</li>
          <li><b>Evidencia:</b> Documentación acreditada</li>
        </ul>
      </td>
    </tr>
  </tbody>
</table>

<div style="page-break-after: always;">

# Capítulo I: Presentación

## 1.1. Startup Profile
### 1.1.1. Descripción de la Startup
Retornamos con NexoraPE, un equipo de estudiantes de la Universidad Peruana de Ciencias Aplicadas comprometidos con el desarrollo de soluciones tecnológicas que mejoren la seguridad laboral en el Perú.
Nuestra misión es ofrecer una plataforma digital que facilite el reporte y seguimiento de incidentes laborales en tiempo real, permitiendo a trabajadores y responsables de seguridad actuar de manera rápida y eficiente para prevenir accidentes y garantizar entornos de trabajo más seguros.
Nuestra visión es convertirnos en la herramienta líder en gestión de seguridad laboral en Latinoamérica, ayudando a las empresas a reducir riesgos, cumplir con normativas y proteger la integridad de sus trabajadores mediante el uso de tecnología accesible, intuitiva y confiable.
### 1.1.2. Perfiles de integrantes del equipo
| Foto | Nombre y Apellidos | Código | Carrera | Resumen de Conocimientos y Habilidades |
| :---: | :--- | :---: | :---: | :--- |
| ![Daniel](assets/Cap-1//Daniel.jpeg) | **Daniel Elias Ruiz Huisa** | u202210764 | Estudiante de Ingeniería de Software. Me intereso por el desarrollo web y la evolucion de tecnologias como los nuevos agentes AI. Tengo conocimientos en Frameworks orientados a node.js como Astro, Vue y Angular. Domino lenguajes como python, C++ y typescript. Soy una persona responsable que busca siempre generar un ambiente sano y agradable para todos.     |
| ![Carlos](imgs/FotoLiam.png) | **Estudiante** | Codigo | Descripcion |
| ![Francisco](imgs/FotoLiam.png) | **Estudiante** | Codigo | Descripcion |
## 1.2. Solution Profile
SafeWork empezo como una aplicación web diseñada para mejorar la gestión de la seguridad laboral en fábricas, almacenes y construcciones. Ahora cambiamos a un enfoque movil, mucho mas versatil e inmediato. El aplicativo debe permitir que los trabajadores reporten incidentes con su telefono, evitando retrasos o la pérdida de información en papeleo. La plataforma asigna responsables de seguimiento, envía notificaciones inmediatas y facilita el monitoreo de cada caso hasta su resolución. Con esto, se garantiza mayor transparencia, rapidez y trazabilidad en los procesos de seguridad. SafeWork contribuye a reducir riesgos, fomentar una cultura de prevención y brindar a las empresas una base de datos útil para analizar y prevenir futuros incidentes.
### 1.2.1. Antecedentes y problemática

##### **¿Cuál es el problema? (What)**

En muchas empresas del sector industrial, logístico y de construcción, los incidentes laborales (accidentes, riesgos o fallas de seguridad) no se reportan de manera inmediata o se pierden en trámites burocráticos. Este retraso impide que se tomen acciones correctivas rápidas y expone a los trabajadores a mayores riesgos. Según la Superintendencia Nacional de Fiscalización Laboral **(SUNAFIL, 2024)**, en el Perú se registraron más de 2,800 inspecciones relacionadas a accidentes de trabajo entre el 2023 y 2024, siendo 381 de ellos mortales. 

 **¿Cuándo ocurre el problema? (When)**

El problema ocurre en el día a día de las operaciones de fábricas, almacenes y obras de construcción, especialmente en actividades de alto riesgo (uso de maquinaria, manipulación de materiales, transporte interno). Los incidentes suelen suceder en horarios de alta carga laboral o en turnos nocturnos, cuando la supervisión es limitada y los procedimientos de reporte se vuelven más lentos o poco efectivos.

 **¿Dónde ocurre el problema? (Where)**

Esta problemática se presenta en empresas medianas y grandes del sector industrial, logístico y de construcción en el Perú, donde la alta rotación de personal y la falta de digitalización dificultan el seguimiento de incidentes. También es frecuente en organizaciones donde la gestión de la seguridad depende de reportes en papel o sistemas fragmentados, lo que genera pérdida de información y baja trazabilidad.

 **¿A quién afecta el problema? (Who)**

El problema impacta directamente a los trabajadores, quienes enfrentan riesgos de salud y seguridad sin un sistema eficiente para reportarlos. También afecta al personal de seguridad y salud ocupacional, que debe gestionar incidentes sin herramientas modernas de control, y a las empresas, que se ven expuestas a sanciones legales, pérdida de productividad y altos costos asociados a accidentes laborales.

 **¿Por qué sucede el problema? (Why)**

La causa principal es la dependencia de procesos manuales (formularios físicos, llamadas telefónicas o correos informales) que retrasan la comunicación. Además, existe una cultura de poca prevención, donde los reportes de incidentes menores no siempre se registran, lo que impide detectar patrones de riesgo a tiempo. A esto se suma la falta de plataformas digitales especializadas en seguridad laboral que integren reporte, seguimiento y análisis en un mismo sistema.

 **¿Cómo sucede el problema? (How)**

Cuando ocurre un incidente, el trabajador debe llenar formularios en papel o informar verbalmente a un supervisor. Esta información tarda en llegar al área de seguridad, se puede extraviar o se registra de manera incompleta. El seguimiento depende de llamadas o correos aislados, sin trazabilidad clara ni métricas de control. Como resultado, los incidentes se resuelven tarde o se repiten por falta de medidas preventivas oportunas.

**¿Cuán grande es el impacto de este problema? (How much)**

El impacto es significativo en términos humanos, legales y económicos. Según el Ministerio de Trabajo y Promoción del Empleo **(MTPE)**, en el año 2022 se registraron 16,458 accidentes laborales, siendo los sectores más afectados la construcción, manufactura y minería. A nivel social, la falta de sistemas efectivos de gestión de incidentes perpetúa entornos de trabajo inseguros y afecta la calidad de vida de miles de trabajadores y sus familias.

### 1.2.2. Lean UX Process
#### 1.2.2.1. Lean UX Problem Statements

En el sector industrial, logístico y de construcción en el Perú, los trabajadores y responsables de seguridad enfrentan grandes dificultades para gestionar de manera eficiente los incidentes laborales que ocurren en el día a día. La mayoría de reportes se realizan en papel, llamadas o mensajes informales, lo cual retrasa la atención y genera pérdida de información importante.

Hemos observado que no existen herramientas digitales simples y accesibles que permitan a los trabajadores reportar incidentes en tiempo real y a las empresas darles seguimiento estructurado hasta su resolución. Esta falta de digitalización limita la prevención de riesgos y perpetúa entornos de trabajo inseguros.

¿Cómo podemos ayudar a las empresas y trabajadores en el Perú a reportar y gestionar incidentes laborales de forma rápida, organizada y transparente, promoviendo la prevención de accidentes, reduciendo riesgos y garantizando la seguridad en sus entornos de trabajo?

#### 1.2.2.2. Lean UX Assumptions

**¿Quién es el usuario?**

Trabajadores de fábricas, almacenes y obras de construcción en el Perú, así como personal de seguridad y salud ocupacional que necesitan gestionar incidentes laborales de manera organizada y en tiempo real.

**¿Dónde encaja nuestro producto en su vida?**

SafeWork se integra como una herramienta esencial en la rutina laboral, permitiendo a los trabajadores reportar riesgos o accidentes de forma inmediata desde su celular, y al personal de seguridad darles seguimiento estructurado, reduciendo papeleo y asegurando que los incidentes no pasen desapercibidos.

**¿Qué problemas tiene nuestro producto y cómo se pueden resolver?**

* Posible resistencia al uso de tecnología por parte de algunos trabajadores.  
  → Solución: interfaz intuitiva, capacitaciones breves y soporte en campo.  
* Temor a represalias por reportar incidentes.  
  → Solución: opción de reportes anónimos y protocolos de confidencialidad.  
* Baja frecuencia de uso en ambientes donde no siempre ocurren incidentes.  
  → Solución: agregar funciones de checklist preventivo y recordatorios de seguridad.

**¿Cómo y cuándo es usado nuestro producto?**

El producto se utiliza en el momento exacto en que ocurre un incidente o cuando un trabajador detecta un riesgo. Además, es empleado diariamente por el personal de seguridad para monitorear reportes, asignar responsables y cerrar incidentes. También se puede usar en reuniones de seguridad para revisar métricas e historial de casos.

**¿Qué características son importantes?**

* Reporte de incidentes en tiempo real con foto, ubicación y descripción.  
* Panel de control para responsables de seguridad.  
* Historial de incidentes y estadísticas exportables.  
* Sistema de asignación de responsables y seguimiento de casos.  
* Opción de reportes anónimos.  
* Dashboard de indicadores de seguridad.  
* Multiplataforma: acceso desde web.

**¿Cómo debe verse nuestro producto y cómo comportarse?**

Debe tener un diseño claro, simple y profesional, con íconos fáciles de reconocer y colores asociados a seguridad **(verde, amarillo, rojo)**. Su comportamiento debe ser rápido y confiable, con notificaciones inmediatas y flujos de interacción que requieran pocos pasos para registrar un reporte. Debe comportarse de manera que transmita confianza, facilidad y utilidad real en el entorno laboral.

#### 1.2.2.3. Lean UX Hypothesis Statements

* **Creemos que** al permitir a los trabajadores reportar incidentes laborales de manera inmediata y digital desde la web, lograremos que los responsables de seguridad los atiendan más rápido y se reduzca el tiempo de respuesta ante riesgos. **Sabremos que** hemos tenido éxito cuando al menos el 60% de los incidentes sean registrados en la plataforma dentro de las primeras 24 horas de ocurridos.

* **Creemos que** al implementar un panel web de seguimiento con asignación de responsables y estado de incidentes, lograremos mayor control y trazabilidad en la gestión de la seguridad laboral. **Sabremos que** hemos tenido éxito cuando más del 70% de los reportes registrados tengan un responsable asignado y un estado actualizado dentro de los primeros 3 días.

* **Creemos que** ofrecer un historial accesible de incidentes con estadísticas y reportes ayudará a las empresas a tomar decisiones preventivas más efectivas. **Sabremos que** hemos tenido éxito cuando al menos el 80% de los usuarios responsables de seguridad accedan al módulo de reportes y estadísticas al menos una vez por semana.

#### 1.2.2.4. Lean UX Canvas

| 1. Businesses Problem | 5. Solutions | 2. Businesses Outcomes |
|-----------------------|--------------|-------------------------|
| Actualmente, muchas empresas en Perú gestionan incidentes laborales de forma manual y desorganizada, lo que dificulta la prevención de accidentes y el cumplimiento normativo. No existen muchas soluciones que sean digital accesible y estandarizada que permitan reportar, organizar y dar seguimiento a estos incidentes de forma eficiente. Esta falta de herramientas genera riesgos operativos, pérdida de información y baja transparencia en los entornos laborales. | SafeWork es una aplicación web que permite a los trabajadores reportar incidentes, riesgos y fallas de seguridad de forma inmediata desde sus dispositivos móviles. El personal de seguridad recibe estos reportes, asigna responsables, da seguimiento y cierra los casos una vez resueltos. La plataforma también almacena un historial de incidentes para generar reportes y estadísticas que faciliten la toma de decisiones preventivas. <br><br>Características clave:<br>- Reporte de incidentes en tiempo real con foto, ubicación y descripción<br>- Panel de control para responsables de seguridad<br>- Historial de incidentes y estadísticas exportables<br>- Sistema de asignación de responsables y seguimiento de casos<br>- Opción de reportes anónimos<br>- Panel visual con indicadores clave de seguridad | Sabremos que estamos resolviendo el problema cuando las empresas comiencen a reportar incidentes laborales a través de la plataforma de forma consistente, reduciendo el tiempo de hacer un reporte en al menos un 40%. Esperamos ver un aumento en la trazabilidad de los casos, una mejora en el cumplimiento normativo, y una adopción de la app sostenida por parte de empresas medianas, con una tasa de retención superior al 70% en los primeros seis meses. |

| 3. Users |
|----------|
| Nos enfocaremos inicialmente en tres tipos de usuarios: (1) trabajadores operativos en fábricas, almacenes y obras de construcción que necesitan reportar incidentes de forma rápida y sencilla; (2) personal de seguridad y salud ocupacional que gestiona y da seguimiento a los reportes; y (3) gerentes o jefes de área que aprueban la adopción del sistema y supervisan su uso. Estos perfiles son clave para garantizar la adopción, configuración y uso efectivo de la aplicación. |

| 4. User Outcomes & Benefits |
|-----------------------------|
| Los usuarios buscan nuestra solución para reducir el tiempo y la complejidad al reportar incidentes laborales, lo que les permite enfocarse en tareas más importantes y disminuir el estrés. El personal de seguridad obtiene una herramienta organizada para clasificar y gestionar incidentes, mejorando la trazabilidad y la respuesta. Los gerentes logran mayor visibilidad y control sobre los riesgos, lo que se traduce en decisiones más efectivas y ahorro económico. Observamos como cambio de comportamiento una mayor frecuencia en los reportes, tiempos de respuesta más cortos y una disminución en incidentes repetitivos. |

| 6. Hypotheses |
|----------------|
| - Creemos que se logrará una reducción del tiempo de hacer un reporte en al menos 40% si los trabajadores operativos pueden reportar incidentes rápidamente mediante la función de reporte en tiempo real con foto, ubicación y descripción.<br>- Creemos que se mejorará la trazabilidad de los casos si el personal de seguridad y salud ocupacional obtiene mayor control mediante el panel de gestión de incidentes.<br>- Creemos que se logrará un mejor cumplimiento normativo de riesgos si los gerentes pueden visualizar métricas clave mediante el panel de indicadores de seguridad.<br>- Creemos que se alcanzará una adopción sostenida por parte de empresas medianas en al menos 70% de los casos si los usuarios pueden acceder fácilmente a la plataforma mediante la versión web. |

| 7. What's the most important thing we need to learn first? | 8. What's the least amount of work we need to do to learn the next most important thing? |
|------------------------------------------------------------|--------------------------------------------------------------------------------------------|
| ¿Realmente los trabajadores usarán la función de reporte en tiempo real en el momento del incidente? | Validar si los trabajadores están dispuestos y son capaces de reportar incidentes en tiempo real, sin necesidad de construir el sistema completo:<br><br>- Prototipo interactivo (sin backend): Simulación de la función de reporte en una app o mockup clickable<br>- Video demo + encuesta: Mostrar cómo funciona la aplicación y recolectar feedback |

## 1.3. Segmentos objetivo

**Personal encargado de la tramitación de accidentes e incidentes laborales**

Profesionales y responsables dentro de las áreas de seguridad ocupacional, recursos humanos o jefaturas inmediatas, que tienen como función reportar, registrar y dar seguimiento a accidentes o incidentes en el centro laboral.

**Características:**

* Buscan herramientas digitales que simplifiquen el proceso de reporte y documentación.  
* Necesitan reducir errores y duplicidad en la información al gestionar casos.  
* Valoran contar con un sistema centralizado que facilite la comunicación con las entidades competentes.

**Trabajadores afectados por accidentes o incidentes laborales**

Colaboradores que han sufrido un accidente o incidente en su centro de trabajo y requieren un seguimiento adecuado de su caso.

**Características:**

* Necesitan acceso rápido y claro a la información sobre el estado de su reporte.  
* Buscan confianza y transparencia en el proceso de registro y resolución de incidentes.  
* Valoran plataformas que les permitan sentirse acompañados y respaldados durante la gestión de su caso.


---

# Capítulo II: Requirements Development and Software Solution Design

## 2.1. Competidores
### 2.1.1. Análisis competitivo
### 2.1.2. Estrategias y tácticas frente a competidores

## 2.2. Entrevistas
### 2.2.1. Diseño de entrevistas
### 2.2.2. Registro de entrevistas
### 2.2.3. Análisis de entrevistas

## 2.3. Needfinding
### 2.3.1. User Personas
### 2.3.2. User Task Matrix
### 2.3.3. User Journey Mapping
### 2.3.4. Empathy Mapping
### 2.3.5. Big Picture EventStorming
### 2.3.6. Ubiquitous Language

## 2.4. Requirements specification
### 2.4.1. User Stories
### 2.4.2. Impact Mapping
### 2.4.3. Product Backlog

## 2.5. Strategic-Level Domain-Driven Design
### 2.5.1. EventStorming
#### 2.5.1.1. Candidate Context Discovery
#### 2.5.1.2. Domain Message Flows Modeling
#### 2.5.1.3. Bounded Context Canvases
### 2.5.2. Context Mapping
### 2.5.3. Software Architecture
#### 2.5.3.1. Software Architecture Context Level Diagrams
#### 2.5.3.2. Software Architecture Container Level Diagrams
#### 2.5.3.3. Software Architecture Deployment Diagrams

## 2.6. Tactical-Level Domain-Driven Design
### 2.6.x. Bounded Context: <Bounded Context Name>
#### 2.6.x.1. Domain Layer
#### 2.6.x.2. Interface Layer
#### 2.6.x.3. Application Layer
#### 2.6.x.4. Infrastructure Layer
#### 2.6.x.5. Bounded Context Software Architecture Component Level Diagrams
#### 2.6.x.6. Bounded Context Software Architecture Code Level Diagrams
##### 2.6.x.6.1. Bounded Context Domain Layer Class Diagrams
##### 2.6.x.6.2. Bounded Context Database Design Diagram

---

# Capítulo III: Solution UI/UX Design

## 3.1. Product design
### 3.1.1. Style Guidelines
#### 3.1.1.1. General Style Guidelines
### 3.1.2. Information Architecture
#### 3.1.2.1. Organization Systems
#### 3.1.2.2. Labelling Systems
#### 3.1.2.3. SEO Tags and Meta Tags
#### 3.1.2.4. Searching Systems
#### 3.1.2.5. Navigation Systems
### 3.1.3. Landing Page UI Design
#### 3.1.3.1. Landing Page Wireframe
#### 3.1.3.2. Landing Page Mock-up
### 3.1.4. Mobile Applications UX/UI Design
#### 3.1.4.1. Mobile Applications Wireframes
#### 3.1.4.2. Mobile Applications Wireflow Diagrams
#### 3.1.4.3. Mobile Applications Mock-ups
#### 3.1.4.4. Mobile Applications User Flow Diagrams
#### 3.1.4.5. Mobile Applications Prototyping

---

# Capítulo IV: Product Implementation & Validation

## 4.1. Software Configuration Management
### 4.1.1. Software Development Environment Configuration
### 4.1.2. Source Code Management
### 4.1.3. Source Code Style Guide & Conventions
### 4.1.4. Software Deployment Configuration

## 4.2. Landing Page & Mobile Application Implementation
### 4.2.1. Sprint n
#### 4.2.1.1. Sprint Planning n
#### 4.2.1.2. Aspect Leaders and Collaborators
#### 4.2.1.3. Sprint Backlog n
#### 4.2.1.4. Development Evidence for Sprint Review
#### 4.2.1.5. Testing Suite Evidence for Sprint Review
#### 4.2.1.6. Execution Evidence for Sprint Review
#### 4.2.1.7. Services Documentation Evidence for Sprint Review
#### 4.2.1.8. Software Deployment Evidence for Sprint Review
#### 4.2.1.9. Team Collaboration Insights during Sprint

## 4.3. Validation Interviews
### 4.3.1. Diseño de Entrevistas
### 4.3.2. Registro de Entrevistas
### 4.3.3. Evaluaciones según heurísticas

---

# Conclusiones
## Conclusiones y recomendaciones

# Video App Validation
## Video About the product
## Video About the team

# Glosario

# Bibliografía

# Anexos
