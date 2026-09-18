![Logo de la upc](../assets/imagenes-caratula/logo-upc.png)

# Univeridad Peruana de Ciencias Aplicadas

# Ingeniería de Software

### Periodo: UG-2do Sementre 2026 Pregrado

### Curso: Desarrollo de Aplicaciones Open Source

### NRC: 7800

### Docente: Robles Fernández, Ivan

## Informe del Trabajo Final

### Startup: Vantara

### Producto: Hatarium

### Integrantes:

| Codigo     | Apellidos y Nombres                |
|------------|------------------------------------|
| U20241B645 | Linares Rodríguez, Franco Orlando   |
| U20241A860 | Ayllon Pauccar, Juan David          | 
| u20241D483 | Taza Curay, Eduardo Miguel          | 
| u202416272 | Asmat Alminco, Martin              | 
| u202516291 | Meza Tataje, David                 | 

### Agosto 2026-20

---

# Registo de Versiones del Informe

| Versión | Fecha    | Autor                              | Descrición Modificada                        |
|---------|----------|------------------------------------|----------------------------------------------|
|  0.1   | 28/08/26  |      Meza Tataje David             | Creación del documento                       |

# Project Report Collaboration Insights

- Link del repositorio del informe: [https://github.com/upc-pre-202620-1asi0729-7800-vantara/vantara-report.git](https://github.com/upc-pre-202620-1asi0729-7800-vantara/vantara-report.git)
- Link del repositorio de la Landing Page: [https://github.com/upc-pre-202620-1asi0729-7800-vantara/vantara-website.git](https://github.com/upc-pre-202620-1asi0729-7800-vantara/vantara-website.git)
- Link del repositorio del BackEnd: 


A lo largo del proyecto, el equipo ha estado comprometido en la creación del informe en diferentes fases. Las tareas principales que se han abarcado
- La realización de una investigación del negocio y la problemática a resolver, recopilando información relevante de fuentes confiables que nos permitieron comprender mejor el sector y las necesidades de los usuarios.
- La redacción de los capítulos del informe, incluyendo la descripción de la startup, el perfil de la solución, los segmentos objetivo, los competidores, las entrevistas, el needfinding, la especificación de requerimientos y el diseño del producto.


# Contenido

## Tabla de contenidos

* [Capítulo I: Introducción](#capítulo-i-introducción)
    * [1.1. Startup Profile](#11-startup-profile)
        * [1.1.1. Descripción de la Startup](#111-descripción-de-la-startup)
        * [1.1.2. Perfiles de integrantes del equipo](#112-perfiles-de-integrantes-del-equipo)
    * [1.2. Solution Profile](#12-solution-profile)
        * [1.2.1. Antecedentes y problemática](#121-antecedentes-y-problemática)
        * [1.2.2. Lean UX Process](#122-lean-ux-process)
            * [1.2.2.1. Lean UX Problem Statements](#1221-lean-ux-problem-statements)
            * [1.2.2.2. Lean UX Assumptions](#1222-lean-ux-assumptions)
            * [1.2.2.3. Lean UX Hypothesis Statements](#1223-lean-ux-hypothesis-statements)
            * [1.2.2.4. Lean UX Canvas](#1224-lean-ux-canvas)
    * [1.3. Segmentos objetivo](#13-segmentos-objetivo)
* [Capítulo II: Requirements Elicitation & Analysis](#capítulo-ii-requirements-elicitation--analysis)
    * [2.1. Competidores](#21-competidores)
        * [2.1.1. Análisis competitivo](#211-análisis-competitivo)
        * [2.1.2. Estrategias y tácticas frente a competidores](#212-estrategias-y-tácticas-frente-a-competidores)
    * [2.2. Entrevistas](#22-entrevistas)
        * [2.2.1. Diseño de entrevistas](#221-diseño-de-entrevistas)
        * [2.2.2. Registro de entrevistas](#222-registro-de-entrevistas)
        * [2.2.3. Análisis de entrevistas](#223-análisis-de-entrevistas)
    * [2.3. Needfinding](#23-needfinding)
        * [2.3.1. User Personas](#231-user-personas)
        * [2.3.2. User Task Matrix](#232-user-task-matrix)
        * [2.3.3. User Journey Mapping](#233-user-journey-mapping)
        * [2.3.4. Empathy Mapping](#234-empathy-mapping)
    * [2.4. Big Picture Event Storming](#24-big-picture-event-storming)
    * [2.5. Ubiquitous Language](#25-ubiquitous-language)
* [Capítulo III: Requirements Specification](#capítulo-iii-requirements-specification)
    * [3.1. User Stories](#31-user-stories)
    * [3.2. Impact Mapping](#32-impact-mapping)
    * [3.3. Product Backlog](#33-product-backlog)
* [Capítulo IV: Product Design](#capítulo-iv-product-design)
    * [4.1. Style Guidelines](#41-style-guidelines)
        * [4.1.1. General Style Guidelines](#411-general-style-guidelines)
        * [4.1.2. Web Style Guidelines](#412-web-style-guidelines)
    * [4.2. Information Architecture](#42-information-architecture)
        * [4.2.1. Organization Systems](#421-organization-systems)
        * [4.2.2. Labeling Systems](#422-labeling-systems)
        * [4.2.3. SEO Tags and Meta Tags](#423-seo-tags-and-meta-tags)
        * [4.2.4. Searching Systems](#424-searching-systems)
        * [4.2.5. Navigation Systems](#425-navigation-systems)
    * [4.3. Landing Page UI Design](#43-landing-page-ui-design)
        * [4.3.1. Landing Page Wireframe](#431-landing-page-wireframe)
        * [4.3.2. Landing Page Mock-up](#432-landing-page-mock-up)
    * [4.4. Web Applications UX/UI Design](#44-web-applications-uxui-design)
        * [4.4.1. Web Applications Wireframes](#441-web-applications-wireframes)
        * [4.4.2. Web Applications Wireflow Diagrams](#442-web-applications-wireflow-diagrams)
        * [4.4.3. Web Applications Mock-ups](#443-web-applications-mock-ups)
        * [4.4.4. Web Applications User Flow Diagrams](#444-web-applications-user-flow-diagrams)
    * [4.5. Web Applications Prototyping](#45-web-applications-prototyping)
    * [4.6. Domain-Driven Software Architecture](#46-domain-driven-software-architecture)
        * [4.6.1. Design-Level Event Storming](#461-design-level-event-storming)
        * [4.6.2. Software Architecture Context Diagram](#462-software-architecture-context-diagram)
        * [4.6.3. Software Architecture Container Diagrams](#463-software-architecture-container-diagrams)
        * [4.6.4. Software Architecture Components Diagrams](#464-software-architecture-components-diagrams)
    * [4.7. Software Object-Oriented Design](#47-software-object-oriented-design)
        * [4.7.1. Class Diagrams](#471-class-diagrams)
    * [4.8. Database Design](#48-database-design)
        * [4.8.1. Database Diagrams](#481-database-diagrams)
* [Capítulo V: Product Implementation, Validation & Deployment](#capítulo-v-product-implementation-validation--deployment)
    * [5.1. Software Configuration Management](#51-software-configuration-management)
        * [5.1.1. Software Development Environment Configuration](#511-software-development-environment-configuration)
        * [5.1.2. Source Code Management](#512-source-code-management)
        * [5.1.3. Source Code Style Guide & Conventions](#513-source-code-style-guide--conventions)
        * [5.1.4. Software Deployment Configuration](#514-software-deployment-configuration)
    * [5.2. Landing Page, Services & Applications Implementation](#52-landing-page-services--applications-implementation)
        * [5.2.1. Sprint 1](#521-sprint-1)
            * [5.2.1.1. Sprint Planning 1](#5211-sprint-planning-1)
            * [5.2.1.2. Aspect Leaders and Collaborators](#5212-aspect-leaders-and-collaborators)
            * [5.2.1.3. Sprint Backlog 1](#5213-sprint-backlog-1)
            * [5.2.1.4. Development Evidence for Sprint Review](#5214-development-evidence-for-sprint-review)
            * [5.2.1.5. Execution Evidence for Sprint Review](#5215-execution-evidence-for-sprint-review)
            * [5.2.1.6. Services Documentation Evidence for Sprint Review](#5216-services-documentation-evidence-for-sprint-review)
            * [5.2.1.7. Software Deployment Evidence for Sprint Review](#5217-software-deployment-evidence-for-sprint-review)
            * [5.2.1.8. Team Collaboration Insights during Sprint](#5218-team-collaboration-insights-during-sprint)
    * [5.3. Validation Interviews](#53-validation-interviews)
        * [5.3.1. Diseño de Entrevistas](#531-diseño-de-entrevistas)
        * [5.3.2. Registro de Entrevistas](#532-registro-de-entrevistas)
        * [5.3.3. Evaluaciones según heurísticas](#533-evaluaciones-según-heurísticas)
    * [5.4. Video About-the-Product](#54-video-about-the-product)


# Student Outcome
**Criterio:** La capacidad de adquirir y aplicar nuevos conocimientos según sea
necesario, utilizando estrategias deaprendizaje apropiadas.

En el siguiente cuadro se describe las accionesrealizadas y enunciados de conclusiones
por parte del grupo, que permiten sustentar el haber alcanzado el logro del ABET –
EAC - Student Outcome 7.

## ABET – EAC – Student Outcome 7

**Criterio:** *La capacidad de adquirir y aplicar nuevos conocimientos según sea necesario, utilizando estrategias de aprendizaje apropiadas.*

En el siguiente cuadro se describe las acciones realizadas y enunciados de conclusiones por parte del grupo, que permiten sustentar el haber alcanzado el logro del ABET – EAC – Student Outcome 7.

| **Criterio específico** | **Acciones realizadas** | **Conclusiones** |
| :--- | :--- | :--- |
| **Actualiza conceptos y conocimientos necesarios para su desarrollo profesional y en especial para su proyecto en soluciones de software.** | **Meza Tataje, David**<br>- **AV1:** Investigué los patrones tácticos de Domain-Driven Design (DDD) y la diagramación UML para la especificación del dominio ganadero. Adquirí conocimientos en gestión ágil y control de versiones bajo Git Flow con Conventional Commits. Estudié la maquetación responsiva HTML5/CSS3 y la lógica de navegación dinámica en JavaScript para la construcción del Header y Navbar de la Landing Page de Hatarium.<br><br>**Linares Rodríguez, Franco Orlando**<br>- **AV1:** Investigué técnicas de investigación cualitativa (5W's y 2H's) para estructurar el análisis de antecedentes y la problemática del sector ganadero en el Capítulo I. Adquirí conocimientos en maquetación web responsiva para el desarrollo de las secciones Hero Banner y About Us de la Landing Page de Hatarium. Estudié la metodología BDD para la especificación de pruebas de aceptación en formato Gherkin.<br><br>**Ayllon Pauccar, Juan David**<br>- **AV1:** Adquirí conocimientos en prototipado de alta fidelidad y sistemas de diseño utilizando Figma. Investigué técnicas de maquetación CSS Grid y Flexbox para implementar la sección de Producto y Módulos de Servicios (Ganaderos y Veterinarios) en la Landing Page. Estudié metodologías de análisis de dominio (Needfinding, User Personas, Empathy Maps) para el Capítulo II.<br><br>**Taza Curay, Eduardo Miguel**<br>- **AV1:** Investigué sobre la metodología Event Storming (Domain Events, Commands, Actors) e Impact Mapping para estructurar el alcance funcional del proyecto en el Capítulo III. Adquirí conocimientos en desarrollo web para implementar la sección de Contacto y la configuración bilingüe en `index-en.html`. Estudié técnicas de validación de formularios web.<br><br>**Asmat Alminco, Martin**<br>- **AV1:** Investigué sobre el Modelo C4 (Nivel de Contexto) para la especificación de la arquitectura de software en el Capítulo IV. Adquirí conocimientos en prácticas DevOps para la configuración del repositorio central en GitHub bajo Git Flow. Estudié las estrategias de despliegue continuo en GitHub Pages y maqueté la sección de Equipo, Video y Footer responsivo. | **AV1:** El equipo Vantara incorporó un conjunto amplio y diverso de metodologías y herramientas para el desarrollo de la solución SaaS Hatarium, abarcando desde el análisis del dominio del problema (Lean UX, 5W's y 2H's, Needfinding, Event Storming) hasta el diseño arquitectónico de la solución (DDD estratégico y táctico, Modelo C4) y la maquetación web (HTML5, CSS3, JS, Git Flow, GitHub Pages). Cada integrante identificó proactivamente las brechas en su conocimiento y tomó acciones concretas para cubrirlas mediante el estudio de documentación técnica, bibliografía especializada y recursos en línea. |
| **Reconoce la necesidad del aprendizaje permanente para el desempeño profesional y el desarrollo de proyectos en soluciones de software.** | **Meza Tataje, David**<br>- **AV1:** Reconocí que el liderazgo técnico y el modelado táctico bajo DDD exigen una actualización continua para garantizar arquitecturas escalables y mantenibles en proyectos SaaS. Identifiqué que los estándares de diseño y maquetación web evolucionan rápidamente, lo que me motivó a profundizar en guías de estilos CSS y buenas prácticas de desarrollo frontend.<br><br>**Linares Rodríguez, Franco Orlando**<br>- **AV1:** Comprendí que la definición de propuestas de valor y la estructuración de criterios de aceptación Gherkin requieren un aprendizaje constante para traducir necesidades de negocio en especificaciones técnicas claras. Reconocí que el desarrollo frontend responsivo exige mantenerse al día en estándares de maquetación e inspección web.<br><br>**Ayllon Pauccar, Juan David**<br>- **AV1:** Identifiqué que el diseño de interfaces (UI/UX) para usuarios del sector agropecuario requiere comprender profundamente sus necesidades mediante el estudio constante de metodologías de investigación cualitativa. Valoré la importancia de actualizarme en herramientas de prototipado como Figma para acelerar la validación visual antes del desarrollo.<br><br>**Taza Curay, Eduardo Miguel**<br>- **AV1:** Reconocí que el modelado del dominio mediante Event Storming y la especificación de requerimientos requieren formación permanente para evitar ambigüedades en la arquitectura del software. Comprendí que la implementación de formularios web con validación en tiempo real demanda la adopción constante de buenas prácticas de usabilidad.<br><br>**Asmat Alminco, Martin**<br>- **AV1:** Acepté que las prácticas de integración y despliegue continuo (DevOps) evolucionan rápidamente, exigiendo un estudio ininterrumpido para mantener productos de software listos para producción. Reconocí que el diseño de arquitecturas con el Modelo C4 es un pilar profesional que debo seguir fortaleciendo a lo largo de mi carrera. | **AV1:** El equipo Vantara reconoce de manera colectiva que la construcción de una solución SaaS de calidad como Hatarium exige una actitud de aprendizaje permanente y proactivo. A lo largo de esta entrega, cada integrante identificó de forma autónoma las áreas de conocimiento que debía fortalecer —desde el análisis de usuarios e investigación de dominio hasta la especificación de arquitectura y despliegue cloud—, demostrando capacidad de adaptación continua frente a los estándares de la industria del software. |