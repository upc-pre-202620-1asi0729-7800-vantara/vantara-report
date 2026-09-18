<div style="page-break-before: always;"></div>

# Capítulo V: Product Implementation, Validation & Deployment

## 5.1. Software Configuration Management

### 5.1.1. Software Development Environment Configuration

#### Gestión del Proyecto
Para la coordinación del proyecto y el seguimiento del trabajo colaborativo se utilizaron plataformas de comunicación, almacenamiento y gestión ágil. El código fuente de la Landing Page y del informe se centralizó en una organización de GitHub. Las reuniones virtuales del equipo y coordinaciones diarias se realizaron mediante Discord y WhatsApp, mientras que la planificación y asignación de tareas se gestionó a través de Zoho Sprints.

* **Coordinación de código y repositorios:** GitHub
* **Reuniones virtuales y syncs:** Discord
* **Comunicación diaria:** WhatsApp
* **Organización y seguimiento de tareas (Agile):** Zoho Sprints

#### Gestión de Requerimientos
Durante la fase de análisis y estructuración de requerimientos, se empleó UXPressia para diseñar las User Personas, Mapas de Empatía e Impact Maps. Se utilizó Miro para la construcción de escenarios As-Is / To-Be y los tableros de Event Storming.

* **Diseño UX y Mapas de Impacto:** UXPressia
* **Event Storming y Escenarios:** Miro
* **Gestión de User Stories:** Zoho Sprints / GitHub Projects

#### Diseño de Experiencia e Interfaz del Producto
Para la concepción visual de la Landing Page y la maquetación preliminar de las interfaces de la plataforma, el equipo empleó Figma. Se elaboraron wireframes y maquetas de alta fidelidad para validar la estructura visual, paleta de colores y la disposición de las secciones informativas antes de su codificación.

* **Diseño de Interfaz y Prototipado:** Figma

#### Desarrollo de Software
El desarrollo de la Landing Page responsiva se realizó utilizando tecnologías web estándar (HTML5, CSS3, JavaScript / Frameworks Web). El informe del proyecto se redactó en formato Markdown (.md). Para el desarrollo del código y del informe se emplearon editores e IDEs como Visual Studio Code, WebStorm e IntelliJ IDEA, administrados mediante JetBrains ToolBox para mantener la homogeneidad del entorno.

* **IDEs y Editores:** Visual Studio Code, WebStorm, IntelliJ IDEA
* **Gestor de IDEs:** JetBrains ToolBox

#### Documentación de Software
La documentación técnica del informe se gestionó en archivos Markdown (.md) sincronizados con el repositorio central del grupo en GitHub mediante la metodología Git Flow, asegurando un trabajo colaborativo ordenado.

#### Despliegue de Software
Para la publicación de la Landing Page como primer entregable accesible al público, se utilizó GitHub Pages, plataforma que permite el alojamiento continuo desde la rama principal del repositorio.

* **Landing Page:** GitHub Pages / Vercel

---

### 5.1.2. Source Code Management

#### Estructura de Ramas Git Flow
Para mantener un historial de cambios limpio y organizado en el repositorio de la Landing Page e Informe, el equipo aplicó el modelo Git Flow:

* `main`: Mantiene el código estable y listo para publicación final.
* `develop`: Rama de integración donde se unen las características desarrolladas antes de pasar a la versión final.
* `feature/*`: Ramas individuales creadas para desarrollar secciones específicas (ej. `feature/US001-landing-hero`, `feature/capitulo-5`).
* `hotfix/*`: Ramas de corrección rápida para solucionar observaciones de formato o visualización.

#### Versionado Semántico (Semantic Versioning)
Se aplica la nomenclatura **Semantic Versioning 2.0.0** (`MAJOR.MINOR.PATCH`):
* `1.0.0` $\rightarrow$ Release inicial completado para la Entrega 1 (Landing Page publicada e Informe finalizado).

#### Estándar de Commit (Conventional Commits)
El equipo adoptó el estándar Conventional Commits para registrar los avances:
* `feat:` Nueva sección o funcionalidad en la Landing Page (ej. `feat(landing): add contact form section`).
* `docs:` Cambios o avances en la documentación del informe (ej. `docs(cap5): add configuration management section`).
* `style:` Ajustes estéticos, CSS o formato Markdown.
* `fix:` Correcciones de errores visuales o enlaces rotos.

---

### 5.1.3. Source Code Style Guide & Conventions

Se estableció el uso del idioma inglés para las clases CSS, identificadores y nombres de archivos de la Landing Page a fin de preservar estándares de desarrollo profesional.

#### Convenciones de Código Web (HTML5 / CSS3)
* **Nombres de etiquetas y atributos:** Siempre en minúsculas.
* **Archivos y carpetas:** Formato `kebab-case` (ej. `landing-style.css`, `hero-banner.png`).
* **Clases e Identificadores CSS:** Formato `kebab-case` descriptivo (ej. `.navbar-container`, `#contact-form`).
* **Atributos accesibles:** Inclusión obligatoria de atributos `alt` en imágenes y sintaxis semántica (`<header>`, `<section>`, `<footer>`).

---

### 5.1.4. Software Deployment Configuration

#### Despliegue de la Landing Page
1. Verificación de maquetación responsiva en navegador mediante herramientas de inspección web.
2. Fusión de los cambios validados en la rama `develop` hacia la rama `main` mediante Pull Request.
3. Activación de GitHub Pages desde la configuración del repositorio (`Settings > Pages`), estableciendo la rama `main` como origen de despliegue.
4. Generación automática del enlace público por parte de GitHub Pages y verificación de navegación activa.

---

## 5.2. Landing Page, Services & Applications Implementation

### 5.2.1. Sprint 1

#### 5.2.1.1. Sprint Planning 1

| Campo | Detalle |
| :--- | :--- |
| **Sprint #** | Sprint 1 |
| **Date** | 2026-05-05 |
| **Time** | 07:00 PM |
| **Location** | Reunión virtual mediante Discord |
| **Prepared By** | Meza Tataje, David |
| **Attendees** | Linares Rodríguez, Franco Orlando / Ayllon Pauccar, Juan David / Taza Curay, Eduardo Miguel / Asmat Alminco, Martin / Meza Tataje, David |
| **Sprint 0 Review Summary** | No aplica. Corresponde al primer Sprint del proyecto, por lo que no existe un sprint anterior del cual reportar resultados. |
| **Sprint 0 Retrospective Summary** | No aplica. Al ser el Sprint inicial, el equipo realizó una reunión de Kickoff donde se definieron los acuerdos de trabajo, herramientas de comunicación, convenciones de código (Git Flow y Conventional Commits) y la distribución inicial de responsabilidades entre los integrantes. |
| **Sprint 1 Goal** | Diseñar, desarrollar, verificar y desplegar la Landing Page completa y responsiva de Hatarium, e implementar la documentación técnica de los Capítulos I al V del informe para el primer entregable (TB1). |
| **Sprint 1 Velocity** | 12 Story Points |
| **Sum of Story Points** | 12 |

---

#### 5.2.1.2. Aspect Leaders and Collaborators

| Integrante | Rol / Aspecto Líder | Responsabilidades Principales en Sprint 1 |
| :--- | :--- | :--- |
| **Meza Tataje, David** | Team Lead / Frontend Developer | Coordinación del Sprint 1, maquetación CSS/HTML responsiva del Header y Navbar de la Landing Page, y redacción de los Capítulos III y V del informe. |
| **Linares Rodríguez, Franco Orlando** | Frontend Developer / QA | Desarrollo de las secciones Hero y About Us de la Landing Page, elaboración de pruebas Gherkin y redacción del Capítulo I del informe. |
| **Ayllon Pauccar, Juan David** | UX/UI Lead / Frontend Developer | Prototipado en Figma, maquetación de la sección de Funcionalidades y Servicios en la Landing Page, y redacción del Capítulo II del informe. |
| **Taza Curay, Eduardo Miguel** | Frontend Developer / Requirements | Desarrollo de la sección de Contacto, formulario web con validaciones UI, y estructuración de Historias de Usuario y Event Storming. |
| **Asmat Alminco, Martin** | DevOps / Software Architect | Implementación del Footer, configuración del repositorio GitHub (Git Flow), despliegue en GitHub Pages y redacción del Capítulo IV del informe. |

---

#### 5.2.1.3. Sprint Backlog 1

En este primer Sprint, el trabajo del equipo se dividió de manera equitativa entre la maquetación responsiva de la Landing Page de Hatarium y la elaboración técnica de la documentación del informe (Capítulos I al V):

| US / TS / Task ID | Título | Descripción de Tarea | Estimación (Horas) | Integrante Asignado | Estado |
| :--- | :--- | :--- | :---: | :--- | :---: |
| **US001 / CC01** | Header y Navbar Responsivos | Maquetación y estilos responsive del encabezado y menú de navegación. | 4 | Meza Tataje, David | Done |
| **US001 / CC02** | Sección Hero & About Us | Maquetación visual de la sección principal y presentación de la empresa. | 4 | Linares Rodríguez, Franco Orlando | Done |
| **US002 / CC03** | Sección de Servicios y Producto | Maquetación de tarjetas informativas con las funcionalidades del SaaS. | 3 | Ayllon Pauccar, Juan David | Done |
| **US003 / CC04** | Sección de Contacto | Maquetación de la sección informativa de canales de comunicación. | 2 | Taza Curay, Eduardo Miguel | Done |
| **US004 / CC05** | Formulario de Contacto UI | Desarrollo de la interfaz del formulario y validaciones en tiempo real. | 3 | Taza Curay, Eduardo Miguel | Done |
| **TS001 / CC06** | Footer & Enlaces Sociales | Maquetación del pie de página y enlaces a redes de la plataforma. | 2 | Asmat Alminco, Martin | Done |
| **TS001 / CC07** | Despliegue en GitHub Pages | Configuración del pipeline de despliegue continuo desde la rama `main`. | 2 | Asmat Alminco, Martin | Done |
| **DOC01** | Informe Capítulo I | Introducción, problema, objetivos, justificación y restricciones. | 5 | Linares Rodríguez, Franco Orlando | Done |
| **DOC02** | Informe Capítulo II | Análisis del dominio, entrevistas, User Personas, Empathy Maps. | 6 | Ayllon Pauccar, Juan David | Done |
| **DOC03** | Informe Capítulo III | Impact Mapping, Event Storming, 40 US + 12 TS y Product Backlog. | 8 | Meza Tataje, David / Taza Curay, Eduardo M. | Done |
| **DOC04** | Informe Capítulo IV | Arquitectura de Software, Estilo de Arquitectura y Vista de Contexto C4. | 6 | Asmat Alminco, Martin | Done |
| **DOC05** | Informe Capítulo V | Configuration Management, Sprint Planning 1 y Evidencias de Sprint. | 5 | Meza Tataje, David | Done |

---

#### 5.2.1.4. Development Evidence for Sprint Review

Durante el Sprint 1 se establecieron los repositorios centrales del proyecto en GitHub:
* **Repositorio del Informe:** `https://github.com/upc-pre-202620-1asi0729-7800-vantara/vantara-report`
* **Repositorio de la Landing Page:** `https://github.com/upc-pre-202620-1asi0729-7800-vantara/vantara-website`

---

#### 5.2.1.5. Execution Evidence for Sprint Review

Durante el Sprint 1 se implementaron y ejecutaron satisfactoriamente las evidencias de software correspondientes a la **Landing Page de Hatarium**, abarcando la maquetación interactiva, la navegabilidad y la validación de interfaz:

* **Landing Page de Hatarium (US001, US002, US003):**
  Se desarrolló la landing page completa incorporando las secciones principales: *Hero / Inicio*, *About Us / Nosotros*, *Services & Product / Funcionalidades*, *About the Team / Equipo* y *Contact / Contacto*. La plataforma es totalmente responsiva y permite la navegación fluida entre secciones mediante desplazamiento suave (*scroll suave*), facilitando que los visitantes, ganaderos y médicos veterinarios conozcan la propuesta de valor del SaaS antes del lanzamiento del panel web.

* **Formulario de Contacto (US004):**
  Se implementó la interfaz del formulario de contacto con validaciones en tiempo real en el frontend. El sistema detecta automáticamente campos obligatorios vacíos (nombre, correo electrónico, mensaje) y formatos de correo inválidos, desplegando mensajes de alerta descriptivos. Al completar el envío correctamente, la interfaz muestra una notificación de confirmación para el usuario.

  <td><p align="center"><img src="../Assets/imagenes-caratula/img-landing.png" alt="deploy-landing" width="70%"></p></td>




---

#### 5.2.1.6. Services Documentation Evidence for Sprint Review

#### 5.2.1.7. Software Deployment Evidence for Sprint Review

Durante el Sprint 1 se realizó el despliegue de la **Landing Page de Hatarium** como el primer entregable público de la plataforma SaaS.

* **Plataforma utilizada:** GitHub Pages
* **Pasos realizados para el despliegue:**
  1. Se desarrolló la landing page en el repositorio central de la organización `upc-pre-202620-1asi0729-7800-vantara`.
  2. Se configuró GitHub Pages desde la sección `Settings > Pages` del repositorio, seleccionando la rama `main` como fuente de publicación.
  3. GitHub Pages procesó los archivos estáticos y generó automáticamente la URL pública del sitio.
  4. Se realizó la verificación funcional accediendo a la URL generada desde distintos navegadores y dispositivos móviles para validar el diseño responsivo y la navegación.

* **URL de la Landing Page:** `https://upc-pre-202620-1asi0729-7800-vantara.github.io/vantara-website/`

#### 5.2.1.8. Team Collaboration Insights during Sprint

Durante el Sprint 1, el equipo mantuvo una comunicación fluida y organizada para asegurar el cumplimiento simultáneo del desarrollo de la Landing Page y la consolidación del informe del proyecto:

##### Project Management
* **Discord:** Canal principal para reuniones diarias (Daily Standups), sesiones de pair-programming para la Landing Page y resolución de dudas sobre la documentación.
* **Google Meet:** Plataforma utilizada para las reuniones formales de Sprint Planning 1, revisión del avance y retrospectiva del primer hito (TB1).
* **WhatsApp:** Medio de comunicación rápida para alertas y coordinación inmediata entre integrantes.
* **Zoho Sprints:** Herramienta utilizada para la gestión ágil del tablero Kanban del Sprint 1, control de estados (*To Do*, *In Process*, *Done*) y asignación de tareas por integrante.

##### Source Code Management
Se utilizó **GitHub** como repositorio centralizado bajo la organización del equipo. Se siguió el modelo **Git Flow**, creando ramas de trabajo de tipo `feature/` vinculadas a cada sección del informe o componente de la Landing Page, aplicando estrictamente el estándar de **Conventional Commits** (`feat:`, `docs:`, `style:`, `fix:`).

##### Distribución del trabajo por integrante:

| Integrante | Tareas Principales en Sprint 1 |
| :--- | :--- |
| **Linares Rodríguez, Franco Orlando** | Maquetación de la sección Hero y About Us de la Landing Page; redacción del Capítulo I del informe y diseño de criterios de aceptación Gherkin. |
| **Ayllon Pauccar, Juan David** | Maquetación de la sección de Funcionalidades y Servicios; diseño del prototipo interactivo en Figma y redacción del Capítulo II (Análisis de Dominio). |
| **Taza Curay, Eduardo Miguel** | Implementación de la sección de Contacto y formulario web con validaciones UI; apoyo en el diseño del Event Storming y Product Backlog (Capítulo III). |
| **Asmat Alminco, Martin** | Maquetación del Footer y componentes de pie de página; configuración del repositorio central, Git Flow, despliegue en GitHub Pages y redacción del Capítulo IV (Arquitectura). |
| **Meza Tataje, David** | Coordinación del Sprint 1; maquetación y estilos CSS responsivos del Header y Navbar de la Landing Page; redacción y estructuración técnica del Capítulo III y Capítulo V del informe. |

## 5.3. Validation Interviews

### 5.3.1. Diseño de Entrevistas

### 5.3.2. Registro de Entrevistas

### 5.3.3. Evaluaciones según heurísticas

## 5.4. Video About-the-Product