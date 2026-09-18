<div style="page-break-before: always;"></div>

# Capítulo IV: Product Design

## 4.1. Style Guidelines

### 4.1.1. General Style Guidelines

**Branding** 

El branding de Hatarium está orientado a transmitir confianza, tecnología y compromiso con la gestión ganadera moderna. La identidad visual busca representar la conexión entre la tecnología y el cuidado del ganado mediante una propuesta limpia, profesional y accesible para ganaderos y veterinarios.

La marca utiliza tonalidades verdes como elemento principal para reforzar conceptos relacionados con la naturaleza, bienestar animal, sostenibilidad, salud y productividad. Estos elementos se complementan con una interfaz minimalista que facilita la consulta y gestión de información.

El logotipo de Hatarium incorpora una representación gráfica relacionada con el ganado y la naturaleza, reforzando visualmente la finalidad de la plataforma. Su uso debe mantenerse consistente en las diferentes pantallas para favorecer el reconocimiento de la marca.

El objetivo principal de la identidad de Hatarium es proyectar una plataforma confiable y moderna que permita gestionar el ganado, realizar seguimiento sanitario, controlar la alimentación y consultar información productiva desde un mismo entorno digital.

**Typography**

La tipografía de Hatarium prioriza la legibilidad, claridad y jerarquía visual para facilitar la lectura tanto en dispositivos web como móviles.

Para los títulos, encabezados y elementos principales se utilizará la fuente Poppins, debido a su estilo moderno, geométrico y profesional. Esta tipografía permitirá diferenciar claramente títulos, secciones y elementos importantes dentro de la interfaz.

Para el contenido, textos descriptivos, formularios, etiquetas y elementos secundarios se utilizará la fuente Inter, debido a su alta legibilidad en diferentes tamaños de pantalla.

El uso combinado de Poppins e Inter permite mantener una identidad visual moderna y profesional, al mismo tiempo que facilita la lectura de información relacionada con el ganado, registros sanitarios, alimentación y reportes.

**Jerarquía tipográfica**
- H1: Poppins Bold — títulos principales.
- H2: Poppins SemiBold — títulos de módulos y secciones.
- H3: Poppins SemiBold — títulos de tarjetas y componentes.
- Body: Inter Regular — contenido general.
- Labels: Inter Medium — etiquetas, filtros y formularios.

**Colors**

La paleta de colores de Hatarium fue diseñada para representar naturaleza, bienestar animal, confianza y tecnología aplicada a la gestión ganadera.

Los colores principales utilizan diferentes tonalidades de verde para representar la identidad de la marca y mantener una relación visual con el entorno natural y ganadero.

Los colores semánticos se utilizan para comunicar estados específicos como animales saludables, situaciones que requieren seguimiento, tratamientos activos, alertas y acciones importantes.

<img src="../assets/Colores principales.png">

El verde oscuro será el color principal de Hatarium y se utilizará principalmente en elementos que requieran mayor jerarquía visual, como botones principales, navegación seleccionada y elementos de identidad.

El verde claro será utilizado principalmente como color de apoyo para tarjetas, fondos, badges y componentes relacionados con estados saludables.

<img src="../assets/Secundarios.png">

Los colores semánticos deberán utilizarse de manera consistente. Por ejemplo, el color verde representará estados positivos, mientras que amarillo y rojo indicarán situaciones que requieren atención.

**Spacing**

La interfaz de Hatarium utilizará un sistema de espaciado consistente para mantener una estructura visual ordenada y facilitar la navegación.

Se utilizarán espacios diferenciados entre:

- Secciones principales.
- Tarjetas.
- Formularios.
- Botones.
- Elementos de navegación.
- Tablas y listas.
- Información secundaria.

Se priorizará un sistema basado en múltiplos de 4 px, utilizando principalmente valores de:

4 px · 8 px · 12 px · 16 px · 24 px · 32 px · 40 px

Los espacios de 16 px y 24 px serán los más utilizados dentro de tarjetas y componentes, mientras que valores mayores serán utilizados para separar secciones principales.

Este sistema permitirá mantener consistencia entre las versiones Web y Mobile.

### 4.1.2. Web Style Guidelines

La versión Web de Hatarium está orientada a proporcionar una plataforma completa para la gestión y monitoreo de una ganadería.

La interfaz utiliza una estructura basada en sidebar + header + área de contenido, permitiendo acceder rápidamente a los diferentes módulos.

Las principales secciones de la plataforma son:

Inicio → Ganado → Salud → Alimentación → Lotes → Reportes → Citas → Alertas

Los diferentes módulos mantendrán los componentes compartidos de la interfaz, como el sidebar, header, buscador, selector de ganadería y perfil de usuario.

La versión Web priorizará la visualización de información mediante dashboards, tablas, tarjetas y gráficos, permitiendo gestionar grandes cantidades de información de manera organizada.

**Imágenes**

Las imágenes utilizadas en Hatarium estarán relacionadas principalmente con:

- Ganado bovino.
- Entornos ganaderos.
- Veterinaria.
- Tecnología aplicada al ganado.
- Monitoreo animal.

Las imágenes deberán mantener una estética limpia y coherente con la identidad visual de la plataforma.

En las pantallas principales se podrán utilizar ilustraciones o representaciones visuales del ganado como elemento complementario, evitando que las imágenes interfieran con la lectura de la información.

**Botones**

Los botones de Hatarium seguirán una línea visual consistente con la identidad de la plataforma.

Los botones principales utilizarán el verde oscuro de la marca para representar acciones principales como:

- Registrar animal.
- Generar reporte.
- Crear plan.
- Registrar vacunación.
- Guardar información.
- Iniciar sesión.

Los botones secundarios utilizarán fondos claros o blancos con bordes sutiles para acciones complementarias.

Las acciones de advertencia o críticas utilizarán colores semánticos como amarillo o rojo cuando sea necesario comunicar un riesgo o una acción que requiere atención.

Todos los botones tendrán bordes redondeados, buen contraste y una jerarquía visual clara.

**Navegation**

La navegación de la versión Web utilizará un sidebar lateral fijo como elemento principal de navegación.

El sidebar incluirá las secciones:

- Inicio
- Ganado
- Salud
- Alimentación
- Lotes
- Reportes
- Citas
- Alertas
- Configuración

La sección activa deberá identificarse mediante un fondo verde claro y el color verde principal de Hatarium.

El sidebar también mostrará la información básica del usuario en la parte inferior.

Esta estructura deberá mantenerse consistente en todas las secciones de la plataforma.

## 4.2. Information Architecture

### 4.2.1. Organization Systems

La organización del contenido en Vantara se estructurará según el tipo de información, la funcionalidad y el perfil del usuario, con el objetivo de facilitar la navegación dentro de la plataforma web.

#### Organización Jerárquica

Se aplicará principalmente en la Landing Page y en el Dashboard principal de la Web Application, priorizando el acceso a las funcionalidades más importantes del sistema, tales como:

- Gestión de ganado
- Historial sanitario
- Reproducción
- Alimentación
- Reportes
- Gestión veterinaria


#### Organización Secuencial

Se utilizará en procesos que requieran una serie de pasos definidos para completar una tarea, como:

- Registro de un nuevo animal
- Registro de tratamientos veterinarios
- Registro de eventos reproductivos
- Actualización de información del ganado
- Configuración del perfil del usuario

Este sistema permitirá guiar al usuario durante procesos que requieran ingresar información en un orden determinado.

#### Organización por Tópicos

La información se agrupará de acuerdo con categorías relacionadas con las principales actividades de gestión ganadera:

- Ganado
- Salud
- Alimentación
- Reproducción
- Reportes
- Veterinaria
- Perfil y configuración

Esta organización permitirá al usuario identificar rápidamente la sección correspondiente a la información que desea consultar o gestionar.

#### Organización según Audiencia

Vantara organizará determinadas funcionalidades según el tipo de usuario que acceda a la plataforma web.

Los principales perfiles serán:

- **Ganadero:** tendrá acceso a la gestión de animales, alimentación, reproducción, información sanitaria y reportes.
- **Médico veterinario:** tendrá acceso principalmente a historiales clínicos, diagnósticos, tratamientos y seguimiento sanitario.

Cada perfil tendrá acceso a las funcionalidades necesarias para realizar sus actividades dentro de la plataforma.

### 4.2.2. Labeling Systems

El sistema de etiquetado de Vantara busca mantener simplicidad, claridad y coherencia visual. Se utilizarán palabras simples y directas, evitando términos técnicos innecesarios y manteniendo consistencia entre las diferentes secciones de la plataforma.

#### Etiquetas principales

- Inicio
- Ganado
- Salud
- Alimentación
- Reproducción
- Veterinaria
- Reportes
- Perfil
- Configuración

#### Etiquetas de acciones

También se utilizarán verbos claros para representar las principales acciones dentro de la plataforma:

- Registrar
- Consultar
- Editar
- Actualizar
- Eliminar
- Buscar
- Filtrar
- Guardar
- Cancelar

### 4.2.3. SEO Tags and Meta Tags

Vantara utilizará SEO Tags y Meta Tags para describir correctamente el contenido de sus principales páginas y facilitar su identificación por navegadores y motores de búsqueda.

#### Landing Page

**Title:**  
Vantara – Gestión Ganadera Inteligente

**Meta Description:**  
Vantara es una plataforma web orientada a la gestión ganadera, permitiendo organizar información del ganado, salud animal, reproducción, alimentación y atención veterinaria.

**Keywords:**  
ganadería, gestión ganadera, ganado, salud animal, veterinaria, reproducción, alimentación, Vantara

**Author:**  
Equipo de Desarrollo Vantara

#### Web Application

**Title:**  
Vantara – Plataforma de Gestión Ganadera

**Meta Description:**  
Plataforma web para la gestión y seguimiento de información ganadera, sanitaria, reproductiva y veterinaria.

**Keywords:**  
gestión de ganado, salud animal, veterinaria, ganado, reportes ganaderos, Vantara

**Author:**  
Equipo de Desarrollo Vantara

### 4.2.4. Searching Systems

Vantara contará con sistemas de búsqueda orientados a facilitar la localización rápida de información dentro de la plataforma web.

#### Búsqueda de ganado

Los usuarios podrán buscar animales registrados utilizando diferentes criterios, tales como:

- Nombre del animal
- Código o identificador
- Estado sanitario
- Tipo de ganado

#### Filtros de búsqueda

Para mejorar la localización de información, se podrán aplicar filtros según:

- Estado de salud
- Fechas
- Tratamientos
- Eventos reproductivos
- Tipo de ganado

#### Búsqueda de información veterinaria

Los médicos veterinarios podrán localizar información relacionada con:

- Animales atendidos
- Historiales clínicos
- Diagnósticos
- Tratamientos registrados

#### Presentación de resultados

Los resultados se mostrarán de manera clara y ordenada, mostrando la información principal del elemento encontrado y permitiendo acceder a su detalle correspondiente.

### 4.2.5. Navigation Systems

Vantara utilizará un sistema de navegación simple y consistente que permita a los usuarios desplazarse fácilmente entre las principales secciones de la Landing Page y la Web Application.

#### Navegación en la Landing Page

La Landing Page utilizará una barra de navegación principal ubicada en la parte superior, permitiendo acceder rápidamente a las secciones más importantes del sitio.

Las principales opciones de navegación serán:

- Inicio
- Nosotros
- Funcionalidades
- Beneficios
- Planes
- Contacto
- Iniciar sesión
- Empezar

La navegación permitirá al visitante desplazarse entre las diferentes secciones de forma clara y directa.

#### Navegación en la Web Application

La Web Application utilizará un menú principal que permitirá acceder a las funcionalidades más importantes de Vantara.

Las principales secciones serán:

- Inicio
- Ganado
- Salud
- Alimentación
- Reproducción
- Veterinaria
- Reportes
- Perfil
- Configuración

El usuario podrá acceder a estas opciones desde cualquier vista principal de la plataforma, manteniendo una estructura de navegación consistente.

#### Navegación jerárquica

En secciones que contienen información detallada, se utilizará una navegación jerárquica que permita pasar de información general a información específica.

Por ejemplo:

Ganado → Animal seleccionado → Historial sanitario

Esto permitirá al usuario comprender en qué sección se encuentra y regresar fácilmente a niveles anteriores.

#### Navegación según el tipo de usuario

Las opciones disponibles podrán variar según el perfil del usuario.

- El ganadero tendrá acceso a funcionalidades relacionadas con la gestión del ganado, salud, reproducción, alimentación y reportes.
- El médico veterinario tendrá acceso principalmente a historiales clínicos, diagnósticos, tratamientos y seguimiento sanitario.

De esta manera, cada usuario visualizará las opciones relevantes para las actividades que realiza dentro de Vantara.

## 4.3. Landing Page UI Design

### 4.3.1. Landing Page Wireframe

Los wireframes de la landing page priorizan la experiencia del usuario y la facilidad de uso. Gracias a una estructura intuitiva y una jerarquía visual bien definida, garantizamos que la navegación sea fluida, permitiendo que los visitantes localicen información clave y realicen conversiones sin fricciones. 

- Es la interfaz principal de nuestra landing page

<img src="../assets/landing-page-wireframe-1.jpeg">

- La sección "About Us" contará con la siguiente interfaz donde se describe quienes somos, que hacemos, y nuestra visión y misión.

<img src="../assets/landing-page-wireframe-2.jpeg">

- La sección "Product" contará con las siguientes interface donde se describe hacia quienes va dirigido nuestro producto y las funcionalidades que ofrece.

<img src="../assets/landing-page-wireframe-3.jpeg">
<img src="../assets/landing-page-wireframe-4.jpeg">
<img src="../assets/landing-page-wireframe-5.jpeg">

- La sección "About the team" contará con la siguiente interfaz donde muestra la información de quienes conforman el equipo de Vantara

<img src="../assets/landing-page-wireframe-6.jpeg">

- La sección "Contact" contará con la siguiente interfaz donde muestra la información de los canales de contacto disponibles.

<img src="../assets/landing-page-wireframe-7.jpeg">

### 4.3.2. Landing Page Mock-up

- Sección de "Home"

<img src="../assets/landing-page-mockup-1.png">

- Sección de "About Us"

<img src="../assets/landing-page-mockup-2.png">

- Sección de "Product"

<img src="../assets/landing-page-mockup-3.png">
<img src="../assets/landing-page-mockup-4.png">
<img src="../assets/landing-page-mockup-5.png">

- Sección de "About The Team"

<img src="../assets/landing-page-mockup-6.png">

- Sección de "Contact"

<img src="../assets/landing-page-mockup-7.png">

## 4.4. Web Applications UX/UI Design

### 4.4.1. Web Applications Wireframes

- Sección de "Iniciar Sesión"

<img src="../assets/web-application-wireframe-1.png">

- Sección de "Inicio"

<img src="../assets/web-application-wireframe-2.png">

- Sección de "Ganado"

<img src="../assets/web-application-wireframe-3.png">
<img src="../assets/web-application-wireframe-8.png">
<img src="../assets/web-application-wireframe-9.png">

- Sección de "Salud"

<img src="../assets/web-application-wireframe-4.png">

- Sección de "Alimentación"

<img src="../assets/web-application-wireframe-5.png">

- Sección de "Reportes"

<img src="../assets/web-application-wireframe-6.png">

- Sección de "Visualizar Reporte"

<img src="../assets/web-application-wireframe-7.png">


### 4.4.2. Web Applications Wireflow Diagrams

A continuación se presenta el diagrama de Wireflow de la aplicación web Hatarium, que combina los wireframes
de las pantallas con los flujos de navegación entre ellas. Este artefacto permite visualizar de forma integrada
tanto la estructura visual de cada pantalla como las rutas que el usuario sigue para completar las principales
tareas dentro de la aplicación

<img src="../assets/web-application-wireflow.png">

### 4.4.3. Web Applications Mock-ups

Se presenta el diseño a alto nivel de detalle de la aplicación web, considerando una versión para el segmento objetivo productores ganaderos y veterinarios.

- Sección de "Iniciar Sesión"

<img src="../assets/web-application-mockup-1.jpg">

- Sección de "Registrarse"

<img src="../assets/web-application-mockup-2.jpg">

- Sección de "Inicio"

<img src="../assets/web-application-mockup-3.jpg">

- Sección de "Ganado"

<img src="../assets/web-application-mockup-4.jpg">
<img src="../assets/web-application-mockup-9.jpg">
<img src="../assets/web-application-mockup-10.jpg">


- Sección de "Salud"

<img src="../assets/web-application-mockup-5.jpg">

- Sección de "Alimentación"

<img src="../assets/web-application-mockup-6.jpg">

- Sección de "Reportes"

<img src="../assets/web-application-mockup-7.jpg">

- Sección de "Visualizar Reporte"

<img src="../assets/web-application-mockup-8.jpg">

### 4.4.4. Web Applications User Flow Diagrams

A continuación se presenta el User Flow Diagram del Sprint 1 de la aplicación web Hatarium. Este diagrama representa las rutas de navegación que sigue el usuario desde el ingreso a la aplicación hasta la ejecución de las funcionalidades principales implementadas en este sprint, permitiendo identificar los puntos de decisión y los posibles caminos alternativos dentro del flujo de uso.

<img src="../assets/web-application-userflow.png">

## 4.5. Web Applications Prototyping

En este primer sprint, se desarrollaron principalmente las funcionalidades core de la aplicación front end para el segmento objetivo de productores ganaderos, con pestaña de inicio, ganado, salud y alimento.

Video Exposición del Prototipo: ([Link](https://upcedupe-my.sharepoint.com/:v:/g/personal/u20241b645_upc_edu_pe/IQCDQjed5qhyR6kXCKI0k-1vAVzHmNJGotmTSCgda-dBNMc?e=jaCitc&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D))

<img src="../assets/screenshot-prototype.png">

## 4.6. Domain-Driven Software Architecture

### 4.6.1. Design-Level Event Storming

### 4.6.2. Software Architecture Context Diagram

El diagrama de contexto presenta al sistema Vantara y las principales entidades que interactúan con él. El productor ganadero utiliza la plataforma para gestionar el inventario de animales, lotes, planes de alimentación, citas y pagos. El médico veterinario consulta y administra información clínica, diagnósticos, tratamientos, vacunas y certificados de trazabilidad. Además, Vantara se integra mediante HTTPS con un proveedor externo de autenticación, una pasarela de pagos y un servicio de notificaciones push.

<img src="../assets/c4/c4context-diagram.png">

La plataforma centraliza la información operativa y clínica, valida la identidad de los usuarios, procesa las transacciones y envía alertas sobre citas y eventos relevantes del sistema.

### 4.6.3. Software Architecture Container Diagrams

### 4.6.4. Software Architecture Components Diagrams

## 4.7. Software Object-Oriented Design

### 4.7.1. Class Diagrams

A continuación se presentan los diagramas de clases correspondientes a cada Bounded Context identificado en la arquitectura de la solución. Cada diagrama detalla las entidades principales, sus atributos, métodos y las relaciones entre ellas.

#### 1. IAM (Identity and Access Management) Bounded Context
Este Bounded Context se encarga de gestionar la seguridad, autenticación y autorización de los usuarios en la plataforma. Sus clases representan las credenciales, roles (como Ganadero o Veterinario) y sesiones de los usuarios.
<img src="../assets/class-diagrams/1-iam-classes.png">

#### 2. Profile Bounded Context
Gestiona la información personal y la configuración de los perfiles de usuario dentro del sistema, así como la información general de la ganadería. Contiene clases que modelan los datos de contacto y preferencias.
<img src="../assets/class-diagrams/2-profile-classes.png">

#### 3. Livestock Bounded Context
Este Bounded Context abarca la gestión del inventario animal. Sus clases principales modelan a los animales individuales, sus características físicas, estado, raza y su agrupación en lotes para una gestión más eficiente.
<img src="../assets/class-diagrams/3-livestock-classes.png">

#### 4. Veterinary Bounded Context
Se enfoca en la gestión de la salud y el historial clínico del ganado. Contiene clases que representan diagnósticos, tratamientos, vacunaciones y citas veterinarias, permitiendo un control sanitario riguroso.
<img src="../assets/class-diagrams/4-veterinary-classes.png">

#### 5. Reproductive Bounded Context
Encargado de registrar el ciclo reproductivo del ganado. Incluye clases para modelar eventos como celos, inseminaciones, gestaciones y partos, facilitando la planificación y el seguimiento reproductivo.
<img src="../assets/class-diagrams/5-reproductive-classes.png">

#### 6. Payments Bounded Context
Maneja la lógica de facturación, transacciones y suscripciones de la plataforma. Sus clases modelan los pagos realizados, los planes de suscripción y el historial de facturación de los usuarios.
<img src="../assets/class-diagrams/6-payments-classes.png">

#### 7. Reports Bounded Context
Responsable de la recopilación y consolidación de datos. Sus clases estructuran la generación de reportes estadísticos, resúmenes de productividad y exportación de datos operativos y sanitarios para la toma de decisiones.
<img src="../assets/class-diagrams/7-reports-classes.png">

#### 8. Notifications Bounded Context
Administra las comunicaciones con el usuario. Sus clases estructuran la configuración y el envío de alertas, recordatorios y notificaciones sobre eventos críticos (como tratamientos pendientes o citas).
<img src="../assets/class-diagrams/8-notifications-classes.png">

## 4.8. Database Design

### 4.8.1. Database Diagrams

A continuación, se presentan los Database Diagrams para cada Bounded Context de la solución. Estos diagramas detallan las tablas, columnas, restricciones (como llaves primarias `PK` y foráneas `FK`) y las relaciones que permitirán la persistencia de los objetos del dominio en una base de datos relacional. 

Adicionalmente, al final de la sección se incluye una **vista general de la base de datos** utilizando diagrama UML, que integra todos los Bounded Contexts, dado que representan un esquema consolidado para la plataforma.

#### 1. Identity and Access Management (IAM)
Este esquema gestiona las credenciales de acceso, cuentas y roles. Las tablas principales incluyen la definición de roles y las cuentas de usuario, asegurando que la autenticación sea consistente y segura.
<img src="../assets/database-diagrams/bd-identity-access-management.png">

#### 2. Profile Management
Se enfoca en almacenar los perfiles de los usuarios y su asociación con una cuenta del sistema. Permite guardar la información demográfica, de contacto y los datos de las ganaderías.
<img src="../assets/database-diagrams/bd-profile-management.png">

#### 3. Livestock Management
Este esquema persiste toda la información relacionada con los animales, sus lotes, movimientos y planes de alimentación. Incluye tablas robustas que relacionan a los animales con sus padres (trazabilidad genealógica), su ubicación (lotes) y su dieta.
<img src="../assets/database-diagrams/bd-livestock-management.png">

#### 4. Veterinary Health
Contiene las tablas necesarias para registrar las citas veterinarias, los historiales médicos, los diagnósticos y los tratamientos aplicados a los animales, incluyendo el catálogo de medicamentos.
<img src="../assets/database-diagrams/bd-veterinary-health.png">

#### 5. Reproductive Management
Almacena la información del ciclo reproductivo de los animales, incluyendo las gestaciones, fechas estimadas de parto y las crías resultantes, enlazándose directamente con el registro de inventario de animales.
<img src="../assets/database-diagrams/bd-reproductive-management.png">

#### 6. Payments
Gestiona el almacenamiento de las transacciones financieras. Sus tablas incluyen los pagos generados, transacciones asociadas a métodos de pago y los recibos de cobro por suscripciones o servicios veterinarios.
<img src="../assets/database-diagrams/bd-payments.png">

#### 7. Reports and Analytics
Estructura la información para generar y compartir reportes. Relaciona quién generó el reporte, sobre qué animales o ganadería trata y con qué usuarios del sistema se han compartido los resultados.
<img src="../assets/database-diagrams/bd-reports-analytics.png">

#### 8. Notifications
Persiste las notificaciones y alertas dirigidas a los usuarios. Su tabla principal registra el mensaje, el estado de lectura y el usuario destinatario.
<img src="../assets/database-diagrams/bd-notifications.png">

#### Vista General de Base de Datos (Entity-Relationship)

Para integrar las relaciones consolidadas de todos los Bounded Contexts y comprender la estructura completa del sistema Vantara, presentamos el siguiente diagrama unificado modelado en UML (PlantUML).

<img src="../assets/database-diagrams/db-general.png">