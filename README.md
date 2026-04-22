<div align="center">

<br>

<img src="https://upload.wikimedia.org/wikipedia/commons/f/fc/UPC_logo_transparente.png" alt="UPC Logo" width="140"/>

# Universidad Peruana de Ciencias Aplicadas
### Facultad de Ingeniería · Ciclo 2026-10

<br>

# Informe de Proyecto - Avance 1

## Presentado por ´PetHealt Team´


<img src="./pawtient-report/assets/images/pawtient.png" alt="Pawtient Logo" width="320"/>

## Startup: Pawtient

*Sistema de gestión de clínicas veterinarias*

<br>

**Código del Curso:** 1ASI0730 &nbsp;|&nbsp; **Nombre del Curso:** Aplicaciones Web

**NRC:** `10203`

**Profesor:** Alex Humberto Sánchez Ponce

<br>

### Integrantes de ´PetHealt Team´

`U202410239` - `Salinas Guzmán, Brianna Cristina`

`U202315007` - `Quintanilla Pozo, Gonzalo Samuel`

`U202315171` - `Salazar Miranda, Mateo Paolo`

`U202311469` - `Arroyo Gonzales, Emily Juliette`

`U202314898` - `Acuache Lucas, Mathias Joaquin`

### **Abril 2026**

</div>

---

<br>
<div align="center">
  
## Registro de Versiones del Informe

| Versión | Fecha | Participantes | Descripción de modificación |
|:-------:|:-----:|:-----:|:---------------------------|
| AV1 | 2026-04-08 | Salinas Guzmán, Brianna Cristina <br> Quintanilla Pozo, Gonzalo Samuel <br> Salazar Miranda, Mateo Paolo <br> Arroyo Gonzales, Emily Juliette <br> Acuache Lucas, Mathias Joaquin | Avance 1 del reporte del proyecto y primera versión de la landing page |
| | | | |

</div>

---

<br>

## Project Report Collaboration Insights

**URL del Repositorio:** [`https://github.com/PetHealt/Pawtient-report.git`](https://github.com/PetHealt/Pawtient-report.git)

*(Esta sección se irá expandiendo con cada entrega)*

---

<br>

## Tabla de Contenidos
  #### [Contenido](#-tabla-de-contenidos)
  #### [Student Outcome](#-student-outcome)

  #### [Capítulo I: Introducción](#capítulo-i-introducción-1)
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
 
  #### [Capítulo II: Requirements Elicitation & Analysis](#capítulo-ii-requirements-elicitation--analysis-1)
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
  - [2.4. Big Picture Event Storming](#24-big-picture-event-storming)
  - [2.5. Ubiquitous Language](#25-ubiquitous-language)
    
  #### [Capítulo III: Requirements Specification](#capítulo-iii-requirements-specification-1)
  - [3.1. User Stories](#31-user-stories)
  - [3.2. Impact Mapping](#32-impact-mapping)
  - [3.3. Product Backlog](#33-product-backlog)
    
  #### [Capítulo IV: Product Design](#capítulo-iv-product-design-1)
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
    - [4.6.1. Design-Level Event Storming](#461-design-level-event-storming)
    - [4.6.2. Software Architecture Context Diagram](#462-software-architecture-context-diagram)
    - [4.6.3. Software Architecture Container Diagrams](#463-software-architecture-container-diagrams)
    - [4.6.4. Software Architecture Components Diagrams](#464-software-architecture-components-diagrams)
  - [4.7. Software Object-Oriented Design](#47-software-object-oriented-design)
    - [4.7.1. Class Diagrams](#471-class-diagrams)
  - [4.8. Database Design](#48-database-design)
    - [4.8.1. Database Diagrams](#481-database-diagrams)
      
  #### [Capítulo V: Product Implementation, Validation & Deployment](#capítulo-v-product-implementation-validation--deployment-1)
  - [5.1. Software Configuration Management](#51-software-configuration-management)
    - [5.1.1. Software Development Environment Configuration](#511-software-development-environment-configuration)
    - [5.1.2. Source Code Management](#512-source-code-management)
    - [5.1.3. Source Code Style Guide & Conventions](#513-source-code-style-guide--conventions)
    - [5.1.4. Software Deployment Configuration](#514-software-deployment-configuration)
  - [5.2. Landing Page, Services & Applications Implementation](#52-landing-page-services--applications-implementation)
    - [5.2.1. Sprint 1](#521-sprint-1)
  - [5.3. Validation Interviews](#53-validation-interviews)
  - [5.4. Video About-the-Product](#54-video-about-the-product)
    
  #### [Conclusiones](#conclusiones-1)
  
  #### [Recomendaciones](#recomendaciones-1)

  #### [Video About-the-Team](#video-about-the-team-1)
  
  #### [Bibliografía](#-bibliografía)
  
  #### [Anexos](#anexos-1)

---

<br>

## Student Outcome

En el siguiente cuadro se describen las acciones realizadas y enunciados de conclusiones que permiten sustentar el logro alcanzado.

| Criterio específico | Acciones realizadas | Conclusiones |
|:---|:---|:---|
| **5.c1. Trabaja en equipo para proporcionar liderazgo en forma conjunta.** | **Salinas Guzmán, Brianna** <br> AV1: (acción específica) <br><br> **Quintanilla Pozo, Gonzalo** <br> AV1: (acción específica) <br><br> **Salazar Miranda, Mateo** <br> AV1: (acción específica) <br><br> **Arroyo Gonzales, Emily** <br> AV1: (acción específica) <br><br> **Acuache Lucas, Mathias** <br> AV1: (acción específica) | (Completar de forma grupal en cada entrega) |
| **5.c2. Crea un entorno colaborativo e inclusivo, establece metas, planifica tareas y cumple objetivos** | **Salinas Guzmán, Brianna** <br> AV1: (acción específica) <br><br> **Quintanilla Pozo, Gonzalo** <br> AV1: (acción específica) <br><br> **Salazar Miranda, Mateo** <br> AV1: (acción específica) <br><br> **Arroyo Gonzales, Emily** <br> AV1: (acción específica) <br><br> **Acuache Lucas, Mathias** <br> AV1: (acción específica) | (Completar de forma grupal en cada entrega) |

---

<div align="center">

# Capítulo I: Introducción

</div>

---

## 1.1. Startup Profile

### 1.1.1. Descripción de la Startup


---

###   1.1.2. Perfiles de integrantes del equipo

<div align="center">
  
#### Integrante 1

<img src="../assets/team/integrante1.jpg" alt="Foto Integrante 1" width="120"/>

| Campo | Detalle |
|:------|:--------|
| **Nombres y Apellidos** | `Salinas Guzmán, Brianna` |
| **Código de estudiante** | `U202410239` |
| **Carrera** | Ingeniería de Software |

</div>
<br>

**Descripción:**
*Soy estudiante de Ingeniería de Software con conocimientos en desarrollo de aplicaciones, estructuras de datos y programación orientada a objetos. Tengo experiencia trabajando con lenguajes como C++, Pyhton, SQL para base de datos y en la gestión de proyectos utilizando Git y GitHub para el control de versiones. Además, cuento con formación complementaria en marketing digital, lo que me permite aportar una perspectiva orientada al usuario y al posicionamiento del producto. Me considero una persona responsable, con capacidad de aprendizaje autónomo y habilidades para trabajar en equipo y comunicar ideas de manera clara.*

---

<br>

<div align="center">
  
#### Integrante 2

<img src="../assets/team/integrante2.jpg" alt="Foto Integrante 2" width="120"/>

| Campo | Detalle |
|:------|:--------|
| **Nombres y Apellidos** | `Apellidos, Nombres` |
| **Código de estudiante** | `codigo` |
| **Carrera** | Ingeniería de Software |
</div>

**Descripción:**
*(Párrafo describiendo principales conocimientos técnicos y habilidades que puede aportar al equipo)*

---
<br>

<div align="center">
  
#### Integrante 3

<img src="../assets/team/integrante3.jpg" alt="Foto Integrante 3" width="120"/>

| Campo | Detalle |
|:------|:--------|
| **Nombres y Apellidos** | `Apellidos, Nombres` |
| **Código de estudiante** | `codigo` |
| **Carrera** | Ingeniería de Software |
</div>

**Descripción:**
*(Párrafo describiendo principales conocimientos técnicos y habilidades que puede aportar al equipo)*

---
<br>
<div align="center">

#### Integrante 4

<img src="../assets/team/integrante4.jpg" alt="Foto Integrante 4" width="120"/>

| Campo | Detalle |
|:------|:--------|
| **Nombres y Apellidos** | `Apellidos, Nombres` |
| **Código de estudiante** | `codigo` |
| **Carrera** | Ingeniería de Software |
</div>

**Descripción:**
*(Párrafo describiendo principales conocimientos técnicos y habilidades que puede aportar al equipo)*

---
<br>
<div align="center">
  
#### Integrante 5

<img src="../assets/team/integrante5.jpg" alt="Foto Integrante 5" width="120"/>

| Campo | Detalle |
|:------|:--------|
| **Nombres y Apellidos** | `Apellidos, Nombres` |
| **Código de estudiante** | `codigo` |
| **Carrera** | Ingeniería de Software |
</div>

**Descripción:**
*(Párrafo describiendo principales conocimientos técnicos y habilidades que puede aportar al equipo)*

---
<br>


## 1.2. Solution Profile

### 1.2.1. Antecedentes y problemática



---

### 1.2.2. Lean UX Process



#### 1.2.2.1. Lean UX Problem Statements



**Problem Statement 1:**



---

#### 1.2.2.2. Lean UX Assumptions

**Business Assumptions:**



**User Assumptions:**


---

#### 1.2.2.3. Lean UX Hypothesis Statements

> *(Estructura: "Creemos que [resultado] se logrará si [usuario] logra [beneficio] con [característica]")*

**Hypothesis 1:**
> Creemos que **[resultado de negocio]** se logrará si **[usuario/segmento]** logra **[beneficio esperado]** con **[característica o solución propuesta]**.

**Hypothesis 2:**
> Creemos que **[resultado de negocio]** se logrará si **[usuario/segmento]** logra **[beneficio esperado]** con **[característica o solución propuesta]**.

**Hypothesis 3:**
> Creemos que **[resultado de negocio]** se logrará si **[usuario/segmento]** logra **[beneficio esperado]** con **[característica o solución propuesta]**.

---

#### 1.2.2.4. Lean UX Canvas

*(Incluir captura de imagen del Lean UX Canvas elaborado en la herramienta indicada)*

![Lean UX Canvas](../assets/lean-ux/lean-ux-canvas.png)

*(Descripción y análisis del Lean UX Canvas)*

---

## 1.3. Segmentos objetivo

> *(Describir los segmentos asociados al dominio del problema, incluyendo características demográficas e información estadística de sustento)*

### Segmento objetivo 1: `[Nombre del segmento]`

*(Descripción del segmento: características demográficas, perfil, necesidades y estadísticas de respaldo)*

**Características demográficas:**
- **Edad:** `[rango de edad]`
- **Género:** `[distribución]`
- **Ubicación:** `[contexto geográfico]`
- **Ocupación:** `[tipo de ocupación]`
- **Nivel socioeconómico:** `[nivel]`

*(Estadísticas de sustento con fuentes referenciadas)*

---

### Segmento objetivo 2: `[Nombre del segmento]`

*(Descripción del segmento: características demográficas, perfil, necesidades y estadísticas de respaldo)*

**Características demográficas:**
- **Edad:** `[rango de edad]`
- **Género:** `[distribución]`
- **Ubicación:** `[contexto geográfico]`
- **Ocupación:** `[tipo de ocupación]`
- **Nivel socioeconómico:** `[nivel]`

*(Estadísticas de sustento con fuentes referenciadas)*

---

<div align="center">

# Capítulo II: Requirements Elicitation & Analysis

</div>

---

## 2.1. Competidores

> *(Identificar y describir mínimo 3 competidores directos o indirectos con modelos de negocio basados en productos digitales similares)*

### 2.1.1. Análisis competitivo

**¿Por qué llevar a cabo este análisis?**
*(Escribir la pregunta que busca responder o el objetivo de este análisis)*

#### Competitive Analysis Landscape

| | **BrandRadar** | **Competidor 1** | **Competidor 2** | **Competidor 3** |
|:--|:--:|:--:|:--:|:--:|
| **Logo** | *(logo)* | *(logo)* | *(logo)* | *(logo)* |
| **Overview** | | | | |
| **Ventaja competitiva** | | | | |
| **Mercado objetivo** | | | | |
| **Estrategias de marketing** | | | | |
| **Productos & Servicios** | | | | |
| **Precios & Costos** | | | | |
| **Canales de distribución** | | | | |
| **Fortalezas** | | | | |
| **Debilidades** | | | | |
| **Oportunidades** | | | | |
| **Amenazas** | | | | |

---

### 2.1.2. Estrategias y tácticas frente a competidores

*(Describir las estrategias y tácticas preliminares que aplicará el startup para afrontar las fortalezas y aprovechar las debilidades de los competidores, así como el contexto de oportunidades y amenazas)*

---

## 2.2. Entrevistas

> *(Investigación basada en recolección de información mediante entrevistas a representantes de los segmentos objetivo)*

### 2.2.1. Diseño de entrevistas

*(Incluir las preguntas principales y complementarias para entrevistas, dirigidas a cada segmento objetivo)*

**Segmento objetivo 1: `[Nombre del segmento]`**

*Preguntas principales:*
1. *(Pregunta 1)*
2. *(Pregunta 2)*
3. *(Pregunta 3)*

*Preguntas complementarias:*
1. *(Pregunta complementaria 1)*
2. *(Pregunta complementaria 2)*

---

**Segmento objetivo 2: `[Nombre del segmento]`**

*Preguntas principales:*
1. *(Pregunta 1)*
2. *(Pregunta 2)*
3. *(Pregunta 3)*

*Preguntas complementarias:*
1. *(Pregunta complementaria 1)*
2. *(Pregunta complementaria 2)*

---

### 2.2.2. Registro de entrevistas
<div align="center">
  
**Segmento objetivo 1: `nombre del segmento`**

<br>

#### Entrevista 1
*Imagen de la entrevista*

<img src="../assets/interviews/ss_entrevista_1.png" alt="Screenshot Entrevista 1" width="500"/>

<br>

| Campo | Detalle |
|:------|:--------|
| **Nombres y apellidos** | `[Nombre del entrevistado]` |
| **Edad** | `[Edad]` |
| **Ubicación** | `[Distrito]` |
| **Fecha de entrevista** | `YYYY-MM-DD` |
| **Duración** | `[HH:MM]` |
| **Enlace al video** | [Ver entrevista en Microsoft Stream](`URL`) — Inicia en `[MM:SS]` |

**Resumen:**

</div>

*(Redactar resumen de la entrevista)*

<br>
<div align="center">
  
#### Entrevista 2
*Imagen de la entrevista*

<img src="../assets/interviews/ss_entrevista_2.png" alt="Screenshot Entrevista 2" width="1000"/>

<br>

| Campo | Detalle |
|:------|:--------|
| **Nombres y apellidos** | `[Nombre del entrevistado]` |
| **Edad** | `[Edad]` |
| **Ubicación** | `[Distrito]` |
| **Fecha de entrevista** | `YYYY-MM-DD` |
| **Duración** | `[HH:MM]` |
| **Enlace al video** | [Ver entrevista en Microsoft Stream](`URL`) — Inicia en `[MM:SS]` |

**Resumen:**

</div>

*(Redactar resumen de la entrevista)*

<br>
<div align="center">
  
#### Entrevista 3

*Imagen de la entrevista*

<img src="../assets/interviews/ss_entrevista_3.png" alt="Screenshot Entrevista 3" width="500"/>

<br>

| Campo | Detalle |
|:------|:--------|
| **Nombres y apellidos** | `[Nombre del entrevistado]` |
| **Edad** | `[Edad]` |
| **Ubicación** | `[Distrito]` |
| **Fecha de entrevista** | `YYYY-MM-DD` |
| **Duración** | `[HH:MM]` |
| **Enlace al video** | [Ver entrevista en Microsoft Stream](`URL`) — Inicia en `[MM:SS]` |

**Resumen:**

</div>

*Redactar resumen de la entrevista*

---
<div align="center">
  
**Segmento objetivo 2: `nombre del segmento`**

<br>

#### Entrevista 1

*Imagen de la entrevista*

<img src="../assets/interviews/ss_entrevista_4.png" alt="Screenshot Entrevista 4" width="500"/>

<br>

| Campo | Detalle |
|:------|:--------|
| **Nombres y apellidos** | `[Nombre del entrevistado]` |
| **Edad** | `[Edad]` |
| **Ubicación** | `[Distrito]` |
| **Fecha de entrevista** | `YYYY-MM-DD` |
| **Duración** | `[HH:MM]` |
| **Enlace al video** | [Ver entrevista en Microsoft Stream](`URL`) — Inicia en `[MM:SS]` |

**Resumen:**

</div>

*(Redactar de forma descriptiva las respuestas del entrevistado a las preguntas realizadas. Incluir todas las características objetivas y subjetivas: personalidad, marcas e influencias, tecnología, canales de interacción, browser, dispositivos, etc.)*

<br>

<div align="center">
  
#### Entrevista 2

*Imagen de la entrevista*

<img src="../assets/interviews/ss_entrevista_5.png" alt="Screenshot Entrevista 5" width="500"/>

<br>

| Campo | Detalle |
|:------|:--------|
| **Nombres y apellidos** | `[Nombre del entrevistado]` |
| **Edad** | `[Edad]` |
| **Ubicación** | `[Distrito]` |
| **Fecha de entrevista** | `YYYY-MM-DD` |
| **Duración** | `[HH:MM]` |
| **Enlace al video** | [Ver entrevista en Microsoft Stream](`URL`) — Inicia en `[MM:SS]` |

**Resumen:**

</div>

*(Redactar resumen de la entrevista)*

<br>

<div align="center">

#### Entrevista 3

*Imagen de la entrevista*

<img src="../assets/interviews/ss_entrevista_6.png" alt="Screenshot Entrevista 6" width="500"/>

<br>

| Campo | Detalle |
|:------|:--------|
| **Nombres y apellidos** | `[Nombre del entrevistado]` |
| **Edad** | `[Edad]` |
| **Ubicación** | `[Distrito]` |
| **Fecha de entrevista** | `YYYY-MM-DD` |
| **Duración** | `[HH:MM]` |
| **Enlace al video** | [Ver entrevista en Microsoft Stream](`URL`) — Inicia en `[MM:SS]` |

**Resumen:**

</div>

*(Redactar resumen de la entrevista)*

---

### 2.2.3. Análisis de entrevistas

> *(Análisis por segmento objetivo con sustento estadístico — porcentajes)*

**Segmento objetivo 1: `[Nombre del segmento]`**

*(Identificar con sustento estadístico todas las características objetivas y subjetivas representativas del segmento, necesarias para la construcción de los arquetipos)*

**Segmento objetivo 2: `[Nombre del segmento]`**

*(Identificar con sustento estadístico todas las características objetivas y subjetivas representativas del segmento, necesarias para la construcción de los arquetipos)*

---

## 2.3. Needfinding

> *(Artefactos resultantes del proceso de análisis de la información recolectada)*

### 2.3.1. User Personas

*(Introducción explicando la relación entre los artefactos y las principales características tomadas del análisis de entrevistas y competencia)*

**User Persona — Segmento 1: `[Nombre del Persona]`**

*(Captura de la ficha elaborada en UXPressia)*

![User Persona Segmento 1](../assets/user-personas/user-persona-seg1.png)

---

**User Persona — Segmento 2: `[Nombre del Persona]`**

*(Captura de la ficha elaborada en UXPressia)*

![User Persona Segmento 2](../assets/user-personas/user-persona-seg2.png)

---

### 2.3.2. User Task Matrix

*(Introducción estableciendo los segmentos considerados)*

| Tarea (Task) | `[Persona 1]` Frecuencia | `[Persona 1]` Importancia | `[Persona 2]` Frecuencia | `[Persona 2]` Importancia |
|:-------------|:------------------------:|:-------------------------:|:------------------------:|:-------------------------:|
| *(Tarea 1)* | Alta / Media / Baja | Alta / Media / Baja | Alta / Media / Baja | Alta / Media / Baja |
| *(Tarea 2)* | | | | |
| *(Tarea 3)* | | | | |
| *(Tarea 4)* | | | | |
| *(Tarea 5)* | | | | |

*(Explicación resaltando las tareas con mayor frecuencia e importancia, principales diferencias y coincidencias entre los User Personas)*

---

### 2.3.3. User Journey Mapping

*(Introducción resumiendo el end-to-end journey que se pretende ilustrar — versión As-Is)*

**User Journey Map — `[Persona 1]`**

*(Captura del diagrama elaborado en UXPressia)*

![User Journey Map Persona 1](../assets/journey-maps/journey-map-persona1.png)

---

**User Journey Map — `[Persona 2]`**

*(Captura del diagrama elaborado en UXPressia)*

![User Journey Map Persona 2](../assets/journey-maps/journey-map-persona2.png)

---

### 2.3.4. Empathy Mapping

*(Resumen del proceso de elaboración y capturas de los Empathy Maps)*

**Empathy Map — `[Persona 1]`**

*(Captura elaborada en UXPressia)*

![Empathy Map Persona 1](../assets/empathy-maps/empathy-map-persona1.png)

---

**Empathy Map — `[Persona 2]`**

*(Captura elaborada en UXPressia)*

![Empathy Map Persona 2](../assets/empathy-maps/empathy-map-persona2.png)

---

## 2.4. Big Picture Event Storming

> *(Sesión colaborativa enfocada en entender el dominio del negocio en general. Referencia: https://bit.ly/bpes-guide)*

*(Introducción al proceso realizado y explicación de las etapas)*

*(Capturas del Big Picture Event Storming elaborado en LucidChart / Miro)*

![Big Picture Event Storming](../assets/event-storming/big-picture-event-storming.png)

*(Explicación de los eventos, actores y flujos identificados)*

---

## 2.5. Ubiquitous Language

>*A continuación se presenta el glosario de términos clave utilizados en el dominio del sistema **Pawtient**, orientado a la gestión de clínicas veterinarias. Este lenguaje común permite una comunicación clara y sin ambigüedades entre todos los stakeholders: veterinarios, administradores, dueños de mascotas y el equipo de desarrollo.*

<br>

## Actores del dominio

| Término (EN) | Término (ES) | Definición |
|:---|:---|:---|
| `Veterinarian / Admin` | Veterinario / Administrador | Usuario interno de la clínica con privilegios para gestionar citas, consultas, inventario y reportes. En el sistema se identifica como un único rol con acceso completo. |
| `Pet Owner` | Dueño de mascota | Persona externa responsable de una o más mascotas registradas. Puede iniciar sesión para consultar información, pero no tiene acceso administrativo. |
| `Supplier` | Proveedor | Entidad externa que abastece insumos médicos a la clínica. Puede ser registrado, editado o eliminado por el veterinario/admin. |

<br>

## Gestión de clínica y usuarios

| Término (EN) | Término (ES) | Definición |
|:---|:---|:---|
| `Clinic` | Clínica | Entidad principal del sistema que agrupa veterinarios, mascotas, citas e inventario bajo una misma organización. |
| `Subscription Plan` | Plan de suscripción | Plan comercial que determina las funcionalidades habilitadas para una clínica (ej. Paw Basic). Activado al registrar la clínica. |
| `User Account` | Cuenta de usuario | Credenciales de acceso al sistema, asociadas a un rol (veterinario/admin o dueño de mascota). |
| `Session` | Sesión | Período activo de uso del sistema tras autenticación exitosa. |
| `Access Data` | Datos de acceso | Información guardada localmente para facilitar el inicio de sesión recurrente. |

<br>

## Mascotas y pacientes

| Término (EN) | Término (ES) | Definición |
|:---|:---|:---|
| `Pet` | Mascota | Animal registrado en el sistema, asociado a un dueño de mascota. Es la unidad de atención clínica. |
| `Patient` | Paciente | Mascota en el contexto de una consulta médica activa. El término se usa cuando la mascota está siendo atendida. |
| `Triage` | Triaje | Proceso de valoración inicial del paciente al ingresar a consulta, donde se registran signos vitales básicos. |
| `Vital Signs` | Signos vitales | Mediciones fisiológicas registradas durante el triaje (temperatura, peso, frecuencia cardíaca, etc.). |

<br>

## Citas y agenda

| Término (EN) | Término (ES) | Definición |
|:---|:---|:---|
| `Appointment` | Cita | Reserva programada para la atención de un paciente en una fecha y hora específica. |
| `Availability` | Disponibilidad | Configuración de horarios en los que un veterinario puede recibir citas. |
| `Appointment Request` | Solicitud de cita | Acción del dueño de mascota de pedir una cita. Inicia el flujo de confirmación. |
| `Confirmed Appointment` | Cita confirmada | Cita que ha sido aceptada y agendada formalmente. |
| `Cancelled Appointment` | Cita cancelada | Cita que fue anulada antes de realizarse. Genera una pregunta de negocio: ¿se bloquea al usuario si cancela con poca anticipación? |
| `Rescheduled Appointment` | Cita reprogramada | Cita que fue modificada a una nueva fecha u hora. |
| `Appointment Reminder` | Recordatorio de cita | Notificación enviada automáticamente al dueño de mascota antes de la cita. |

<br>

## Consulta médica

| Término (EN) | Término (ES) | Definición |
|:---|:---|:---|
| `Medical Consultation` | Consulta médica | Atención clínica realizada durante una cita donde el veterinario evalúa al paciente. Comienza con el triaje y finaliza con el cierre de la consulta. |
| `Diagnosis` | Diagnóstico | Identificación de una enfermedad o condición médica, emitida por el veterinario tras la evaluación. |
| `Prescription` | Receta médica | Documento generado por el veterinario que especifica medicamentos, dosis y duración del tratamiento. |
| `Medical Exam` | Examen médico | Estudio complementario solicitado durante la consulta (ej. análisis de sangre, rayos X). Se adjunta como archivo al historial. |
| `Lab Result` | Resultado de laboratorio | Resultado de un examen médico. Puede cargarse como PDF o JPG al historial del paciente. |
| `Closed Consultation` | Consulta finalizada | Estado de la consulta una vez que el veterinario ha completado el diagnóstico, emitido receta y adjuntado exámenes si aplica. |
| `Medical History` | Historial médico | Registro acumulado de todas las consultas, diagnósticos, recetas y exámenes de un paciente a lo largo del tiempo. |
| `Shared Medical History` | Historial compartido | Historial médico enviado/entregado al dueño de mascota al finalizar la consulta. |

<br>

## Inventario y suministros

| Término (EN) | Término (ES) | Definición |
|:---|:---|:---|
| `Medical Supply` | Insumo médico | Producto utilizado en la clínica: medicamentos, materiales de uso clínico, etc. Registrado con un stock inicial. |
| `Initial Stock` | Stock inicial | Cantidad definida al registrar un insumo médico por primera vez en el sistema. |
| `Stock Adjustment` | Ajuste de inventario | Modificación manual del nivel de stock de un insumo, registrada por el veterinario/admin. |
| `Critical Stock Alert` | Alerta de stock crítico | Notificación generada automáticamente cuando el stock de un insumo cae por debajo del umbral mínimo. |
| `Discounted Medication` | Medicamento descontado | Medicamento dispensado al paciente durante una consulta, que descuenta unidades del inventario automáticamente. |
| `Supply Expense` | Gasto de insumos | Registro del costo asociado al uso o compra de insumos. Aparece en los reportes financieros. |

<br>

## Proveedores

| Término (EN) | Término (ES) | Definición |
|:---|:---|:---|
| `Added Supplier` | Proveedor agregado | Proveedor nuevo registrado en el sistema. |
| `Edited Supplier` | Proveedor editado | Proveedor cuya información fue actualizada. |
| `Deleted Supplier` | Proveedor eliminado | Proveedor removido del sistema. Acción irreversible. |

<br>

## Facturación y reportes

| Término (EN) | Término (ES) | Definición |
|:---|:---|:---|
| `Service Invoice` | Boleta de atención | Documento generado al finalizar una consulta que detalla los servicios prestados y su costo. |
| `Client Payment` | Pago de cliente | Registro del pago efectuado por el dueño de mascota, asociado a una boleta de atención. |
| `Cancelled Sale` | Venta cancelada | Registro de una transacción que fue anulada antes o después de la emisión de la boleta. |
| `Income Report` | Reporte de ingresos | Reporte generado que consolida los ingresos de la clínica en un período determinado. |
| `Supply Expense Report` | Reporte de gastos de insumos | Reporte que detalla el consumo y costo de los insumos utilizados en un período. |

<br>

## Eventos del dominio (Domain Events)

Los siguientes son los eventos significativos identificados en el Event Storming. Representan hechos ocurridos en el sistema que tienen impacto en el negocio:

| Evento (EN) | Evento (ES) | Bounded Context |
|:---|:---|:---|
| `ClinicRegistered` | Clínica registrada | Gestión de clínica |
| `SubscriptionPlanActivated` | Plan de suscripción activado | Gestión de clínica |
| `UserRegistered` | Usuario registrado | Gestión de usuarios |
| `SessionStarted` | Sesión iniciada | Gestión de usuarios |
| `AccessDataSaved` | Datos de acceso guardados | Gestión de usuarios |
| `PetOwnerAccountRegistered` | Cuenta de dueño registrada | Gestión de usuarios |
| `PetRegistered` | Mascota registrada | Mascotas |
| `AvailabilityConfigured` | Disponibilidad configurada | Agenda |
| `AppointmentRequested` | Cita solicitada | Agenda |
| `AppointmentConfirmed` | Cita confirmada | Agenda |
| `AppointmentCancelled` | Cita cancelada | Agenda |
| `AppointmentRescheduled` | Cita reprogramada | Agenda |
| `AppointmentReminderSent` | Recordatorio de cita enviado | Agenda |
| `PatientAdmittedToTriage` | Paciente ingresado a triaje | Consulta médica |
| `VitalSignsRegistered` | Signos vitales registrados | Consulta médica |
| `MedicalConsultationStarted` | Consulta médica iniciada | Consulta médica |
| `DiagnosisIssued` | Diagnóstico emitido | Consulta médica |
| `PrescriptionGenerated` | Receta médica generada | Consulta médica |
| `MedicalExamAttached` | Examen adjuntado | Consulta médica |
| `ConsultationClosed` | Consulta finalizada | Consulta médica |
| `MedicalHistoryShared` | Historial médico compartido | Consulta médica |
| `SupplierAdded` | Proveedor agregado | Inventario |
| `SupplierEdited` | Proveedor editado | Inventario |
| `SupplierDeleted` | Proveedor eliminado | Inventario |
| `MedicalSupplyRegistered` | Insumo médico registrado | Inventario |
| `InitialStockDefined` | Stock inicial definido | Inventario |
| `MedicationDispensed` | Medicamento descontado por venta | Inventario |
| `CriticalStockAlertGenerated` | Alerta de stock crítico generada | Inventario |
| `StockAdjustmentMade` | Ajuste de inventario realizado | Inventario |
| `ServiceInvoiceGenerated` | Boleta de atención generada | Facturación |
| `ClientPaymentRegistered` | Pago de cliente registrado | Facturación |
| `SaleCancelled` | Venta cancelada | Facturación |
| `IncomeReportGenerated` | Reporte de ingresos generado | Facturación |
| `SupplyExpenseRegistered` | Gasto de insumos registrado | Facturación |


<br>

---

<div align="center">

# Capítulo III: Requirements Specification

</div>

---

## 3.1. User Stories

>*Las User Stories fueron definidas a partir del análisis de entrevistas realizadas a los dos segmentos objetivo: personal clínico de centros veterinarios y dueños de mascotas. Se incluyen además User Stories para la Landing Page y Technical Stories para el RESTful API. Los criterios de aceptación siguen la estructura Gherkin (Given–When–Then) y están redactados en tiempo presente, tercera persona, sin referencias a detalles de interfaz de usuario.*

<br>


| Epic / Story ID | Título | Descripción | Criterios de Aceptación | Relacionado con (Epic ID) |
|---|---|---|---|---|
| **EP01** | **Autenticación y Gestión de Usuarios** | Proveer un sistema seguro de registro, inicio de sesión y gestión de roles para veterinarios, administradores de clínica y dueños de mascotas. | — | — |
| US01 | Registrar cuenta como veterinario | Como veterinario, quiero crear una cuenta en Pawtient con mis datos profesionales para acceder a las funcionalidades del sistema de gestión clínica. | **Escenario 1 – Registro exitoso:** Dado que el veterinario completa todos los campos obligatorios (nombre, apellido, correo, contraseña, número de colegiatura), cuando envía el formulario de registro, entonces el sistema crea la cuenta, envía un correo de verificación y redirige a la pantalla de confirmación. **Escenario 2 – Correo ya registrado:** Dado que el veterinario ingresa un correo electrónico que ya existe en el sistema, cuando envía el formulario, entonces el sistema muestra el mensaje "El correo ya está registrado" y no crea una cuenta duplicada. **Escenario 3 – Contraseña débil:** Dado que el veterinario ingresa una contraseña que no cumple con los requisitos mínimos de seguridad (menos de 8 caracteres o sin caracteres especiales), cuando intenta continuar, entonces el sistema indica los requisitos incumplidos y no permite avanzar. | EP01 |
| US02 | Iniciar sesión en la plataforma | Como usuario registrado (veterinario, administrador o dueño de mascota), quiero iniciar sesión con mis credenciales para acceder a las funcionalidades según mi rol. | **Escenario 1 – Inicio de sesión exitoso:** Dado que el usuario ingresa correo y contraseña correctos, cuando confirma el inicio de sesión, entonces el sistema autentica al usuario, genera un token de sesión y lo redirige al panel de inicio correspondiente a su rol. **Escenario 2 – Credenciales incorrectas:** Dado que el usuario ingresa una contraseña incorrecta, cuando intenta iniciar sesión, entonces el sistema muestra el mensaje "Credenciales inválidas" sin especificar cuál campo es incorrecto, y no permite el acceso. **Escenario 3 – Cuenta no verificada:** Dado que el usuario registrado no ha verificado su correo electrónico, cuando intenta iniciar sesión, entonces el sistema informa que la cuenta requiere verificación y ofrece reenviar el correo de confirmación. | EP01 |
| US03 | Recuperar contraseña olvidada | Como usuario registrado, quiero recuperar el acceso a mi cuenta en caso de olvidar mi contraseña para no perder el acceso a la plataforma. | **Escenario 1 – Correo de recuperación enviado:** Dado que el usuario ingresa su correo registrado en el formulario de recuperación, cuando confirma la solicitud, entonces el sistema envía un enlace de restablecimiento de contraseña válido por 30 minutos. **Escenario 2 – Correo no registrado:** Dado que el usuario ingresa un correo que no existe en el sistema, cuando confirma la solicitud, entonces el sistema muestra el mensaje genérico "Si el correo está registrado, recibirás un enlace" sin confirmar ni negar la existencia de la cuenta. **Escenario 3 – Enlace expirado:** Dado que el usuario intenta usar un enlace de recuperación después de los 30 minutos de validez, cuando accede al enlace, entonces el sistema indica que el enlace ha expirado y permite solicitar uno nuevo. | EP01 |
| **EP02** | **Gestión de Historiales Clínicos** | Centralizar los registros médicos de las mascotas en formato digital, eliminando el uso de historias en papel o Excel y permitiendo el acceso desde dispositivos móviles. | — | — |
| US04 | Registrar historia clínica de mascota | Como veterinario, quiero crear y guardar la historia clínica digital de una mascota para eliminar el uso de registros físicos y acceder a la información desde cualquier dispositivo. | **Escenario 1 – Registro exitoso:** Dado que el veterinario selecciona "Nueva historia clínica" y completa los campos obligatorios (nombre de mascota, especie, raza, peso, diagnóstico, tratamiento y fecha), cuando confirma el guardado, entonces el sistema almacena el registro y muestra un mensaje de confirmación. **Escenario 2 – Campos incompletos:** Dado que el veterinario intenta guardar una historia clínica con campos obligatorios vacíos, cuando confirma el guardado, entonces el sistema resalta los campos faltantes y no permite continuar hasta completarlos. **Escenario 3 – Acceso desde dispositivo móvil:** Dado que el veterinario accede al sistema desde un dispositivo móvil, cuando consulta o crea una historia clínica, entonces el sistema muestra el formulario completo y funcional sin pérdida de campos ni de funcionalidades. | EP02 |
| US05 | Consultar historial médico de una mascota | Como veterinario, quiero buscar y visualizar el historial completo de una mascota para tomar decisiones clínicas informadas durante la consulta. | **Escenario 1 – Búsqueda por nombre de mascota:** Dado que el veterinario ingresa el nombre de la mascota en el buscador del módulo de historiales, cuando el sistema procesa la búsqueda, entonces muestra los registros coincidentes ordenados cronológicamente de forma descendente. **Escenario 2 – Sin resultados:** Dado que el veterinario realiza una búsqueda, cuando no existe ningún registro con ese nombre, entonces el sistema muestra el mensaje "No se encontraron registros" y ofrece la opción de crear uno nuevo. **Escenario 3 – Visualización de vacunas aplicadas:** Dado que el veterinario abre el historial de una mascota, cuando navega a la sección de vacunación, entonces el sistema lista todas las vacunas aplicadas con fecha de aplicación, lote y fecha de próxima dosis. | EP02 |
| US06 | Editar y actualizar historia clínica | Como veterinario, quiero actualizar la historia clínica de una mascota después de cada consulta para mantener la información vigente y con trazabilidad de cambios. | **Escenario 1 – Actualización exitosa:** Dado que el veterinario abre una historia clínica y realiza modificaciones en el diagnóstico o tratamiento, cuando guarda los cambios, entonces el sistema registra la actualización incluyendo la fecha, hora y nombre del usuario que realizó el cambio. **Escenario 2 – Intento de edición sin permisos:** Dado que un usuario sin rol de veterinario intenta editar una historia clínica, cuando intenta acceder al modo de edición, entonces el sistema deniega la acción y muestra el mensaje "No tienes permisos para editar este registro". **Escenario 3 – Registro de historial de cambios:** Dado que el veterinario revisa una historia clínica, cuando accede a la sección de trazabilidad, entonces el sistema muestra un registro cronológico de todas las modificaciones realizadas con nombre del autor y fecha. | EP02 |
| US07 | Registrar vacunas aplicadas | Como veterinario, quiero registrar cada vacuna aplicada durante una consulta vinculándola al historial de la mascota para mantener un calendario de vacunación actualizado. | **Escenario 1 – Registro de vacuna exitoso:** Dado que el veterinario completa los campos de vacunación (nombre de vacuna, lote, fecha de aplicación y próxima dosis) y confirma, cuando el sistema procesa la solicitud, entonces guarda el registro y lo añade al historial de vacunación de la mascota. **Escenario 2 – Fecha de próxima dosis anterior a hoy:** Dado que el veterinario ingresa una fecha de próxima dosis menor a la fecha actual, cuando intenta guardar, entonces el sistema muestra una advertencia indicando que la fecha ingresada corresponde al pasado y solicita confirmación para continuar. **Escenario 3 – Programación automática de recordatorio:** Dado que se registra una vacuna con fecha de próxima dosis, cuando el sistema confirma el guardado, entonces genera automáticamente un recordatorio programado para notificar al dueño 7 días antes de la fecha indicada. | EP02 |
| **EP03** | **Programación y Gestión de Citas** | Digitalizar y automatizar la agenda de citas para reducir el estrés del personal clínico y mejorar la experiencia del dueño de mascota. | — | — |
| US08 | Agendar cita desde la clínica | Como veterinario, quiero registrar una nueva cita en el sistema para organizar la agenda diaria sin depender de llamadas manuales ni registros en papel. | **Escenario 1 – Cita registrada correctamente:** Dado que el veterinario selecciona fecha, hora, veterinario asignado y mascota del cliente, cuando confirma el registro, entonces el sistema añade la cita al calendario y envía una notificación automática al dueño. **Escenario 2 – Horario no disponible:** Dado que el veterinario selecciona un horario que ya está ocupado para el mismo profesional, cuando intenta confirmar, entonces el sistema indica la no disponibilidad y sugiere los próximos horarios libres disponibles. **Escenario 3 – Cita registrada fuera del horario de atención:** Dado que el veterinario intenta registrar una cita fuera del horario de atención configurado por la clínica, cuando intenta confirmar, entonces el sistema muestra una advertencia indicando que el horario está fuera del rango configurado. | EP03 |
| US09 | Agendar cita como dueño de mascota | Como dueño de mascota, quiero solicitar una cita veterinaria desde mi celular para evitar llamadas telefónicas y reducir el tiempo invertido en coordinar turnos. | **Escenario 1 – Solicitud enviada exitosamente:** Dado que el dueño selecciona una clínica, una mascota de su cuenta, una fecha y hora disponibles, cuando confirma la solicitud, entonces el sistema registra la cita y envía una confirmación mediante notificación push. **Escenario 2 – Sin horarios disponibles en la fecha seleccionada:** Dado que el dueño selecciona una fecha en la que todos los horarios están ocupados, cuando intenta avanzar, entonces el sistema muestra el mensaje "No hay horarios disponibles para esta fecha" y permite seleccionar otra. **Escenario 3 – Cancelación con anticipación:** Dado que el dueño tiene una cita confirmada y la cancela con al menos 2 horas de anticipación, cuando confirma la cancelación, entonces el sistema libera el horario, notifica a la clínica y elimina los recordatorios asociados. | EP03 |
| US10 | Visualizar agenda del día | Como veterinario, quiero ver un resumen de las citas programadas para el día en curso para organizar mi jornada de trabajo de forma eficiente. | **Escenario 1 – Visualización correcta de agenda:** Dado que el veterinario accede al panel principal, cuando selecciona la vista de agenda diaria, entonces el sistema lista todas las citas del día ordenadas por hora con nombre de mascota, dueño y motivo de consulta. **Escenario 2 – Agenda vacía:** Dado que no existen citas programadas para el día en curso, cuando el veterinario accede a la agenda, entonces el sistema muestra el mensaje "No hay citas programadas para hoy". **Escenario 3 – Filtro por veterinario:** Dado que la clínica tiene múltiples veterinarios, cuando el administrador aplica un filtro por profesional específico, entonces el sistema muestra únicamente las citas asignadas a ese veterinario. | EP03 |
| US11 | Recibir recordatorios de citas | Como dueño de mascota, quiero recibir recordatorios automáticos antes de las citas de mi mascota para no olvidar los turnos médicos. | **Escenario 1 – Recordatorio 24 horas antes:** Dado que existe una cita confirmada, cuando faltan 24 horas para la cita, entonces el sistema envía una notificación push al dueño con fecha, hora, nombre de la clínica y veterinario asignado. **Escenario 2 – Recordatorio 1 hora antes:** Dado que existe una cita confirmada, cuando falta 1 hora para la cita, entonces el sistema envía un segundo recordatorio de confirmación al dueño. **Escenario 3 – Recordatorios desactivados:** Dado que el dueño ha desactivado los recordatorios de citas en su configuración, cuando el sistema evalúa el envío de una alerta, entonces no envía la notificación para ese tipo de evento. | EP03 |
| **EP04** | **Trazabilidad de Suministros e Inventario** | Proveer control en tiempo real del inventario de medicamentos e insumos para evitar faltantes, vencimientos y errores operativos en la clínica. | — | — |
| US12 | Registrar ingreso de suministros | Como administrador de clínica, quiero registrar el ingreso de nuevos suministros al inventario para mantener el stock actualizado en tiempo real. | **Escenario 1 – Ingreso registrado exitosamente:** Dado que el administrador completa los campos de nombre del producto, cantidad, unidad, fecha de vencimiento y proveedor, cuando confirma el registro, entonces el sistema actualiza el stock y registra la transacción con fecha y usuario. **Escenario 2 – Producto ya existente en inventario:** Dado que el administrador registra un suministro con el mismo nombre que uno existente, cuando confirma, entonces el sistema suma la cantidad al stock existente sin generar un registro duplicado. **Escenario 3 – Alerta de producto próximo a vencer:** Dado que un producto tiene fecha de vencimiento dentro de los próximos 30 días, cuando el administrador lo registra, entonces el sistema genera una alerta visible en el panel principal indicando la proximidad de vencimiento. | EP04 |
| US13 | Consultar niveles de stock | Como veterinario, quiero consultar el nivel actual de un suministro para verificar disponibilidad antes de prescribir un tratamiento. | **Escenario 1 – Consulta exitosa:** Dado que el veterinario ingresa el nombre de un suministro en el buscador de inventario, cuando el producto existe, entonces el sistema muestra la cantidad disponible, la unidad de medida y la fecha de vencimiento más próxima. **Escenario 2 – Stock mínimo alcanzado:** Dado que el stock de un suministro cae por debajo del nivel mínimo definido, cuando el sistema realiza la verificación periódica, entonces genera una alerta y notifica al administrador de la clínica. **Escenario 3 – Producto sin existencia:** Dado que el veterinario busca un suministro cuyo stock es cero, cuando el sistema responde a la consulta, entonces muestra el mensaje "Sin stock disponible" junto con la fecha del último ingreso registrado. | EP04 |
| US14 | Registrar consumo de suministros por consulta | Como veterinario, quiero registrar los insumos utilizados durante una consulta para descontarlos automáticamente del inventario y mantener la trazabilidad de uso. | **Escenario 1 – Descuento automático exitoso:** Dado que el veterinario registra los insumos usados al cerrar una consulta, cuando guarda el registro, entonces el sistema descuenta las cantidades del inventario y vincula la transacción al historial clínico de la mascota. **Escenario 2 – Cantidad solicitada mayor al stock disponible:** Dado que el veterinario intenta registrar el uso de una cantidad que supera el stock, cuando intenta guardar, entonces el sistema muestra una alerta de stock insuficiente y no permite completar el registro hasta corregir la cantidad. **Escenario 3 – Reporte de consumo mensual:** Dado que el administrador accede al módulo de reportes, cuando selecciona el período mensual, entonces el sistema presenta un detalle de consumo por insumo con cantidad total utilizada y costo estimado. | EP04 |
| US15 | Generar alertas de reabastecimiento | Como administrador de clínica, quiero recibir alertas automáticas cuando el stock de un suministro sea bajo para solicitar reposición con anticipación y evitar faltantes. | **Escenario 1 – Alerta generada automáticamente:** Dado que el stock de un suministro desciende al nivel mínimo configurado, cuando el sistema procesa la transacción de descuento, entonces genera una alerta visible en el panel del administrador con el nombre del suministro y la cantidad actual. **Escenario 2 – Configuración de nivel mínimo:** Dado que el administrador edita la ficha de un suministro e ingresa un nivel mínimo de stock, cuando guarda la configuración, entonces el sistema utiliza ese valor como umbral para las alertas de reabastecimiento. **Escenario 3 – Alerta de vencimiento masivo:** Dado que varios suministros tienen fecha de vencimiento dentro de los próximos 15 días, cuando el sistema ejecuta la revisión diaria, entonces agrupa las alertas en una sola notificación que lista todos los productos afectados. | EP04 |
| **EP05** | **Perfiles y Gestión de Mascotas** | Permitir a los dueños gestionar el perfil digital de sus mascotas con historial, vacunas y documentos accesibles desde el celular. | — | — |
| US16 | Crear perfil digital de mascota | Como dueño de mascota, quiero registrar el perfil de mi mascota en la plataforma para centralizar su información médica y acceder a ella en cualquier momento. | **Escenario 1 – Perfil creado exitosamente:** Dado que el dueño completa los campos de nombre, especie, raza, fecha de nacimiento y foto, cuando confirma el registro, entonces el sistema crea el perfil y lo muestra en la sección "Mis mascotas" de la cuenta. **Escenario 2 – Registro de múltiples mascotas:** Dado que el dueño desea registrar una segunda mascota, cuando accede a "Agregar mascota" y completa los datos, entonces el sistema crea un perfil independiente y lo lista junto a las mascotas previamente registradas. **Escenario 3 – Visualización del historial desde el perfil:** Dado que el dueño abre el perfil de una mascota, cuando navega a la sección de historial, entonces el sistema muestra las consultas anteriores ordenadas por fecha con diagnóstico y nombre del veterinario tratante. | EP05 |
| US17 | Compartir historial médico con una clínica | Como dueño de mascota, quiero compartir el historial de mi mascota con una nueva clínica para evitar repetir estudios y que el veterinario cuente con información previa relevante. | **Escenario 1 – Compartir mediante código temporal:** Dado que el dueño genera un código de acceso temporal desde el perfil de su mascota, cuando el veterinario ingresa ese código en el sistema, entonces visualiza el historial completo durante el período de validez del código (24 horas). **Escenario 2 – Código expirado:** Dado que el veterinario intenta usar un código de acceso después de las 24 horas de validez, cuando el sistema valida el código, entonces muestra el mensaje "Código expirado" y solicita al dueño generar uno nuevo. **Escenario 3 – Revocar acceso compartido:** Dado que el dueño compartió el historial con una clínica, cuando revoca el acceso desde su configuración, entonces el sistema invalida el código de forma inmediata y la clínica ya no puede visualizar el historial. | EP05 |
| US18 | Buscar clínicas veterinarias cercanas | Como dueño de mascota, quiero buscar clínicas veterinarias cercanas a mi ubicación con sus reseñas y servicios para elegir el mejor lugar para atender a mi mascota. | **Escenario 1 – Búsqueda por ubicación exitosa:** Dado que el dueño activa la búsqueda de clínicas cercanas, cuando el sistema detecta su ubicación, entonces muestra un listado de clínicas ordenadas por distancia con nombre, dirección, calificación y servicios disponibles. **Escenario 2 – Sin clínicas en el área:** Dado que el sistema no encuentra clínicas en el radio de búsqueda predeterminado, cuando presenta los resultados, entonces muestra el mensaje "No se encontraron clínicas en tu área" y ofrece ampliar el radio de búsqueda. **Escenario 3 – Filtro por servicio:** Dado que el dueño aplica un filtro por tipo de servicio (ej. urgencias, vacunación, grooming), cuando el sistema procesa el filtro, entonces muestra únicamente las clínicas que ofrecen ese servicio específico. | EP05 |
| **EP06** | **Notificaciones y Recordatorios Automatizados** | Automatizar el envío de alertas para vacunas, citas y cuidados preventivos tanto al equipo clínico como a los dueños de mascotas. | — | — |
| US19 | Recibir recordatorios de vacunación | Como dueño de mascota, quiero recibir alertas cuando la vacuna de mi mascota esté próxima para no perder el calendario de vacunación. | **Escenario 1 – Alerta 7 días antes:** Dado que el calendario de vacunación tiene una dosis programada, cuando faltan 7 días para aplicarla, entonces el sistema envía una notificación push al dueño con el nombre de la vacuna y un enlace para agendar la cita. **Escenario 2 – Alerta el día de la vacuna:** Dado que es el día de aplicación de una vacuna programada, cuando el sistema ejecuta la revisión diaria, entonces envía un recordatorio urgente al dueño indicando que la vacuna corresponde a ese día. **Escenario 3 – Cancelación del recordatorio tras aplicación:** Dado que la clínica registra la vacuna como aplicada, cuando el sistema actualiza el historial, entonces cancela los recordatorios pendientes y programa el siguiente recordatorio según el esquema de dosis. | EP06 |
| US20 | Configurar preferencias de notificación | Como dueño de mascota, quiero personalizar el tipo y frecuencia de notificaciones que recibo para gestionar las alertas según mis necesidades. | **Escenario 1 – Configuración guardada exitosamente:** Dado que el dueño accede a la sección de ajustes de notificaciones y selecciona los tipos de alerta deseados, cuando guarda los cambios, entonces el sistema aplica las nuevas preferencias en los siguientes envíos. **Escenario 2 – Desactivar todas las notificaciones:** Dado que el dueño desactiva todas las notificaciones desde su configuración, cuando el sistema intenta enviar cualquier alerta, entonces no realiza el envío hasta que las preferencias sean reactivadas manualmente. **Escenario 3 – Restaurar configuración por defecto:** Dado que el dueño selecciona "Restaurar valores por defecto" en la configuración de notificaciones, cuando el sistema procesa la acción, entonces habilita todas las categorías de notificación con frecuencias estándar predefinidas. | EP06 |
| US21 | Recibir notificaciones de resultados y seguimiento | Como dueño de mascota, quiero recibir notificaciones cuando el veterinario actualice el estado de seguimiento de mi mascota para mantenerme informado después de cada consulta. | **Escenario 1 – Notificación de actualización de seguimiento:** Dado que el veterinario añade una nota de seguimiento al historial de una mascota, cuando el sistema confirma el guardado, entonces envía una notificación push al dueño indicando que hay una actualización disponible en el perfil de su mascota. **Escenario 2 – Notificación de resultados de examen:** Dado que el veterinario registra los resultados de un examen de laboratorio vinculado a una consulta, cuando confirma el registro, entonces el sistema notifica al dueño que los resultados están disponibles para su revisión. **Escenario 3 – Historial de notificaciones recibidas:** Dado que el dueño desea revisar notificaciones previas, cuando accede al centro de notificaciones, entonces el sistema muestra el historial de los últimos 30 días ordenado cronológicamente con estado de lectura. | EP06 |
| **EP07** | **Landing Page de Pawtient** | Presentar la propuesta de valor de Pawtient a los visitantes, diferenciando el mensaje por segmento y facilitando el registro o contacto con la plataforma. | — | — |
| US22 | Conocer la propuesta de valor como visitante de clínica veterinaria | Como visitante del segmento clínica veterinaria, quiero ver los beneficios del sistema en la landing page para evaluar si Pawtient se adapta a las necesidades de mi centro. | **Escenario 1 – Sección de beneficios visible:** Dado que el visitante accede a la landing page y navega a la sección dirigida a clínicas, cuando la sección carga, entonces visualiza al menos tres beneficios clave (gestión de historiales, agenda digital, control de inventario) con íconos y descripciones claras. **Escenario 2 – Llamada a la acción funcional:** Dado que el visitante revisa la sección de clínicas, cuando activa la opción "Solicitar demo" o "Registrar mi clínica", entonces el sistema lo lleva al formulario de registro sin recargar la página completa. **Escenario 3 – Visualización en dispositivos móviles:** Dado que el visitante accede a la landing page desde un smartphone, cuando navega por la sección de beneficios para clínicas, entonces el contenido se adapta correctamente a la pantalla sin desbordamientos ni pérdida de información. | EP07 |
| US23 | Conocer la propuesta de valor como visitante dueño de mascota | Como visitante del segmento dueño de mascota, quiero entender cómo Pawtient me ayuda a cuidar mejor a mi mascota para decidir si me registro en la plataforma. | **Escenario 1 – Sección para dueños visible:** Dado que el visitante llega a la landing page, cuando navega a la sección dirigida a dueños de mascotas, entonces visualiza los beneficios principales (recordatorios de vacunas, historial digital, búsqueda de clínicas) con lenguaje accesible y no técnico. **Escenario 2 – Testimonios de dueños visibles:** Dado que el visitante llega a la sección de testimonios, cuando la página carga, entonces se muestran al menos dos testimonios reales de dueños de mascotas con nombre, tipo de mascota y valoración. **Escenario 3 – Registro desde la landing page:** Dado que el visitante revisa la sección de dueños y decide registrarse, cuando activa el botón de registro o descarga, entonces el sistema lo redirige al formulario de creación de cuenta como dueño de mascota. | EP07 |
| US24 | Navegar entre secciones de la landing page | Como visitante de la landing page, quiero usar el menú de navegación para desplazarme rápidamente a cualquier sección y conocer todo el contenido disponible. | **Escenario 1 – Desplazamiento suave entre secciones:** Dado que el visitante selecciona un elemento del menú de navegación, cuando el enlace apunta a una sección de la misma página, entonces el sistema ejecuta un desplazamiento suave hasta esa sección sin recargar la página. **Escenario 2 – Menú visible durante el scroll:** Dado que el visitante hace scroll hacia abajo, cuando supera la altura del encabezado inicial, entonces el menú permanece fijo en la parte superior de la pantalla y mantiene la navegación accesible. **Escenario 3 – Sección activa resaltada en el menú:** Dado que el visitante se encuentra en una sección específica de la página, cuando el scroll posiciona esa sección como principal en pantalla, entonces el ítem correspondiente del menú se resalta visualmente para indicar la ubicación actual. | EP07 |
| US25 | Ver preguntas frecuentes en la landing page | Como visitante de la landing page, quiero consultar las preguntas frecuentes de la plataforma para resolver dudas antes de registrarme sin necesidad de contactar al equipo de soporte. | **Escenario 1 – Sección FAQ visible y accesible:** Dado que el visitante navega a la sección de preguntas frecuentes, cuando la sección carga, entonces el sistema muestra al menos 6 preguntas organizadas por categoría (clínicas y dueños de mascotas). **Escenario 2 – Expansión de respuesta:** Dado que el visitante selecciona una pregunta del listado, cuando activa la pregunta, entonces el sistema expande la respuesta correspondiente sin redirigir a otra página. **Escenario 3 – Enlace de contacto al final de la sección:** Dado que el visitante revisa las preguntas frecuentes y no encuentra respuesta a su duda, cuando llega al final de la sección, entonces el sistema muestra un enlace o formulario de contacto para consultas adicionales. | EP07 |
| **EP08** | **Technical Stories – RESTful API** | Proveer endpoints seguros, documentados y funcionales que soporten todas las operaciones del sistema Pawtient para su integración con el frontend web y la aplicación móvil. | — | — |
| TS01 | Endpoint de autenticación de usuarios | Como developer, quiero un endpoint POST /api/v1/auth/login que valide credenciales y devuelva un token JWT para que el frontend pueda gestionar sesiones de forma segura. | **Escenario 1 – Autenticación exitosa (200):** Dado que el developer envía una petición POST con email y password válidos, cuando el servidor valida las credenciales, entonces retorna HTTP 200 con un token JWT, el rol del usuario y el tiempo de expiración del token. **Escenario 2 – Credenciales inválidas (401):** Dado que el developer envía credenciales incorrectas, cuando el servidor valida el body, entonces retorna HTTP 401 con el mensaje "Invalid credentials" sin especificar cuál campo es incorrecto. **Escenario 3 – Body malformado (400):** Dado que el developer envía una petición sin los campos requeridos (email o password), cuando el servidor valida el body, entonces retorna HTTP 400 con el mensaje "Missing required fields" y la lista de campos faltantes. | EP08 |
| TS02 | Endpoint de creación de historia clínica | Como developer, quiero un endpoint POST /api/v1/records que permita crear una nueva historia clínica para que el frontend registre consultas desde cualquier cliente. | **Escenario 1 – Creación exitosa (201):** Dado que el developer envía una petición POST con body válido (petId, diagnosis, treatment, date, vetId) y token de autenticación vigente, cuando el servidor procesa la solicitud, entonces retorna HTTP 201 con el objeto creado incluyendo el id generado y la fecha de registro. **Escenario 2 – Campos obligatorios faltantes (400):** Dado que el developer envía una petición POST con campos obligatorios ausentes, cuando el servidor valida el body, entonces retorna HTTP 400 con el mensaje "Missing required fields" y la lista de campos faltantes. **Escenario 3 – Token inválido o ausente (401):** Dado que el developer envía la petición sin token de autenticación o con uno expirado, cuando el servidor valida la cabecera Authorization, entonces retorna HTTP 401 con el mensaje "Unauthorized". | EP08 |
| TS03 | Endpoint de programación de citas | Como developer, quiero un endpoint POST /api/v1/appointments que permita crear citas para que el frontend web y la app móvil puedan agendar turnos de forma unificada. | **Escenario 1 – Cita creada exitosamente (201):** Dado que el developer envía una petición POST con petId, vetId, clinicId, date y time válidos, cuando el servidor verifica la disponibilidad del horario y procesa la solicitud, entonces retorna HTTP 201 con el objeto de cita incluyendo el appointmentId y el estado "confirmed". **Escenario 2 – Conflicto de horario (409):** Dado que el developer envía una solicitud para un horario ya ocupado por el mismo veterinario, cuando el servidor valida la disponibilidad, entonces retorna HTTP 409 con el mensaje "Time slot not available" y los horarios alternativos próximos disponibles. **Escenario 3 – Fecha en el pasado (422):** Dado que el developer envía una fecha anterior a la fecha actual del servidor, cuando el servidor valida el campo date, entonces retorna HTTP 422 con el mensaje "Invalid or past date". | EP08 |
| TS04 | Endpoint de gestión de inventario | Como developer, quiero endpoints GET /api/v1/inventory y POST /api/v1/inventory para consultar y registrar suministros para que el módulo de trazabilidad opere correctamente. | **Escenario 1 – Listado de inventario exitoso (200):** Dado que el developer envía una petición GET con token válido y clinicId como parámetro de consulta, cuando el servidor procesa la solicitud, entonces retorna HTTP 200 con el listado de suministros incluyendo nombre, stock actual, unidad de medida y fecha de vencimiento. **Escenario 2 – Ingreso de suministro exitoso (201):** Dado que el developer envía una petición POST con name, quantity, unit, expirationDate y clinicId válidos, cuando el servidor procesa la solicitud, entonces retorna HTTP 201 con el registro actualizado; si el producto ya existe, retorna el stock acumulado. **Escenario 3 – Stock bajo incluido en respuesta (200 con flag):** Dado que el developer consulta el inventario y algún suministro tiene stock igual o menor al mínimo configurado, cuando el servidor retorna la lista, entonces incluye el campo lowStock: true en los objetos de suministros que cumplen esa condición. | EP08 |
| TS05 | Endpoint de notificaciones push | Como developer, quiero un endpoint POST /api/v1/notifications/send que dispare notificaciones push a usuarios para que el sistema automatice recordatorios de vacunas y citas. | **Escenario 1 – Notificación encolada exitosamente (200):** Dado que el developer envía una petición POST con userId, notificationType (appointment/vaccine/followup) y scheduledDate válidos, cuando el servidor procesa la solicitud, entonces retorna HTTP 200 con el campo status: "queued" y el notificationId generado. **Escenario 2 – Usuario sin dispositivo registrado (404):** Dado que el developer envía la solicitud para un userId sin token de dispositivo registrado, cuando el servidor consulta el registro del usuario, entonces retorna HTTP 404 con el mensaje "No device token found for user". **Escenario 3 – Tipo de notificación inválido (400):** Dado que el developer envía un notificationType no reconocido por el sistema, cuando el servidor valida el campo, entonces retorna HTTP 400 con el mensaje "Invalid notification type" y la lista de tipos permitidos por el sistema. | EP08 |

<br>

**8 Epics**, **22 User Stories funcionales** (incluyendo 4 para la Landing Page) y **5 Technical Stories para el API**, sumando un total de **30 historias**. La distribución cubre los pain points identificados en las entrevistas: historiales físicos dispersos (EP02), gestión manual de citas (EP03), falta de recordatorios (EP06), trazabilidad de suministros (EP04), búsqueda de clínicas (EP05), acceso seguro (EP01), visibilidad de la plataforma (EP07) y contratos técnicos del API (EP08).

<br>

---

## 3.2. Impact Mapping

*(Introducción y capturas del Impact Mapping elaborado en la herramienta indicada — UXPressia)*

*(Business Goals deben cumplir criterios SMART. Ejemplo: "Alcanzar los 600 usuarios suscritos al plan A en el lapso de 8 meses.")*

![Impact Map](../assets/impact-mapping/impact-map.png)

*(Explicación del Impact Map: Business Goals, Actors/Personas, Impacts, Deliverables y User Stories)*

---

## 3.3. Product Backlog

*(Introducción al Product Backlog)*

> **Herramienta utilizada:** `[Pivotal Tracker / JetBrains YouTrack / Jira / Trello]`
>
> **URL del Product Backlog:** [`[URL pública del Product Backlog]`](`[URL]`)

*(Captura del Product Backlog en la herramienta indicada)*

![Product Backlog](../assets/product-backlog/product-backlog.png)

| # Orden | User Story ID | Título | Descripción | Story Points |
|:-------:|:-------------:|:------:|:------------|:------------:|
| 1 | US01 | `[Título]` | Como `[rol]`, deseo `[acción]`, para `[beneficio]`. | `1 / 2 / 3 / 5 / 8` |
| 2 | US02 | `[Título]` | Como `[rol]`, deseo `[acción]`, para `[beneficio]`. | |
| 3 | US03 | `[Título]` | Como `[rol]`, deseo `[acción]`, para `[beneficio]`. | |
| 4 | US04 | `[Título]` | Como `[rol]`, deseo `[acción]`, para `[beneficio]`. | |
| 5 | US05 | `[Título]` | Como `[rol]`, deseo `[acción]`, para `[beneficio]`. | |
| n | TS01 | `[Technical Story]` | Como Developer, deseo `[endpoint]`, para `[propósito]`. | |

---

<div align="center">

# Capítulo IV: Product Design

</div>

---

## 4.1. Style Guidelines

### 4.1.1. General Style Guidelines

*(Explicar las decisiones y referencias visuales sobre conceptos generales: Branding, Typography, Colors, Spacing y tono de comunicación)*

**Branding**

*(Descripción del branding de BrandRadar: logo, isotipo, naming, y principios de identidad visual)*

**Typography**

| Tipo | Fuente | Uso |
|:-----|:------:|:----|
| Display / Heading | `[Fuente principal]` | Títulos y encabezados |
| Body | `[Fuente secundaria]` | Texto de contenido |
| Monospace | `[Fuente monoespaciada]` | Código y datos técnicos |

**Colors**

| Nombre | Hex | Uso |
|:-------|:---:|:----|
| Primary | `#XXXXXX` | Color principal de la marca |
| Secondary | `#XXXXXX` | Color de apoyo |
| Accent | `#XXXXXX` | Énfasis y llamados a la acción |
| Background | `#XXXXXX` | Fondo general |
| Text | `#XXXXXX` | Texto principal |
| Error | `#XXXXXX` | Estados de error |
| Success | `#XXXXXX` | Estados de éxito |

**Spacing**

*(Describir el sistema de espaciado y las unidades base utilizadas)*

**Tono de comunicación**

| Dimensión | Selección |
|:----------|:---------:|
| Divertido / Serio | *(indicar posición en la escala)* |
| Formal / Casual | *(indicar posición en la escala)* |
| Respetuoso / Irreverente | *(indicar posición en la escala)* |
| Entusiasta / Sereno | *(indicar posición en la escala)* |

---

### 4.1.2. Web Style Guidelines

*(Decisiones sobre los estándares visuales y de interacción para responsive web interfaces)*

*(Incluir capturas o especificaciones visuales del Design System basado en Material Design y Angular Material)*

---

## 4.2. Information Architecture

*(Decisiones que dirigen la organización del contenido en las experiencias web — Landing Page y Web Application)*

### 4.2.1. Organization Systems

*(Explicar en qué grupos de información se aplica cada sistema de organización: jerárquica, secuencial o matricial; y los esquemas de categorización: alfabético, cronológico, por tópicos, según audiencia)*

### 4.2.2. Labeling Systems

*(Especificar las etiquetas a utilizar con el mínimo número de palabras, para representar los conjuntos de información y sus asociaciones)*

| Etiqueta | Descripción del contenido que representa |
|:--------:|:-----------------------------------------|
| `[Etiqueta]` | *(Descripción)* |
| `[Etiqueta]` | *(Descripción)* |
| `[Etiqueta]` | *(Descripción)* |

### 4.2.3. SEO Tags and Meta Tags

**Landing Page**

```html
<title>[Título del Landing Page]</title>
<meta name="description" content="[Descripción del Landing Page]" />
<meta name="keywords" content="[keywords, separadas, por, comas]" />
<meta name="author" content="[Nombre del Startup]" />
```

**Web Application**

```html
<title>[Título de la Web Application]</title>
<meta name="description" content="[Descripción de la Web Application]" />
<meta name="keywords" content="[keywords, separadas, por, comas]" />
<meta name="author" content="[Nombre del Startup]" />
```

### 4.2.4. Searching Systems

*(Describir qué opciones de búsqueda ofrecen las aplicaciones, con qué filtros contará el usuario y cómo lucirán los datos después de la búsqueda)*

### 4.2.5. Navigation Systems

*(Explicar las acciones y técnicas que guiarán a los usuarios a través del Landing Page y las aplicaciones, describiendo cómo recorrerán el contenido)*

---

## 4.3. Landing Page UI Design

*(Introducción explicando cómo se traducen las decisiones de diseño y arquitectura de información)*

### 4.3.1. Landing Page Wireframe

*(Wireframes del Landing Page para Desktop Web Browser y Mobile Web Browser)*

**Desktop Web Browser**

![Landing Page Wireframe Desktop](../assets/landing-page/wireframe-desktop.png)

**Mobile Web Browser**

![Landing Page Wireframe Mobile](../assets/landing-page/wireframe-mobile.png)

### 4.3.2. Landing Page Mock-up

*(Mock-ups del Landing Page para Desktop y Mobile, con Design System aplicado)*

**Desktop Web Browser**

![Landing Page Mockup Desktop](../assets/landing-page/mockup-desktop.png)

**Mobile Web Browser**

![Landing Page Mockup Mobile](../assets/landing-page/mockup-mobile.png)

---

## 4.4. Web Applications UX/UI Design

*(Propuesta visual y de interacción para las aplicaciones web)*

### 4.4.1. Web Applications Wireframes

*(Wireframes de las aplicaciones web con principios de diseño inclusivo y arquitectura de información aplicados)*

![Web App Wireframes](../assets/web-app/wireframes.png)

### 4.4.2. Web Applications Wireflow Diagrams

*(Un Wireflow por cada User goal, considerando los User Personas definidos)*

**User goal: `[Nombre del User goal]`**

*(Descripción del flujo especificado)*

![Wireflow Diagrama 1](../assets/web-app/wireflow-1.png)

---

**User goal: `[Nombre del User goal]`**

*(Descripción del flujo especificado)*

![Wireflow Diagrama 2](../assets/web-app/wireflow-2.png)

### 4.4.3. Web Applications Mock-ups

*(Mock-ups de las aplicaciones web con Design System aplicado)*

![Web App Mockups](../assets/web-app/mockups.png)

### 4.4.4. Web Applications User Flow Diagrams

*(User Flows incluyendo Mock-ups de vistas, happy paths y unhappy paths)*

**User goal: `[Nombre del User goal]`**

*(Descripción de los flujos y condiciones especificadas)*

![User Flow Diagrama 1](../assets/web-app/user-flow-1.png)

---

## 4.5. Web Applications Prototyping

*(Introducción explicando los principales criterios para las decisiones de interacción)*

*(Prototipos de UI para Desktop y Mobile Web Browser con simulación de interacción y navegación)*

**Prototipo Desktop**

![Screenshot Prototipo Desktop](../assets/prototypes/prototype-desktop-screenshot.png)

[Ver video de prototipo Desktop en Microsoft Stream](`URL`)

**Prototipo Mobile**

![Screenshot Prototipo Mobile](../assets/prototypes/prototype-mobile-screenshot.png)

[Ver video de prototipo Mobile en Microsoft Stream](`URL`)

---

## 4.6. Domain-Driven Software Architecture

### 4.6.1. Design-Level Event Storming

*(Introducción y explicación del proceso de Design-Level EventStorming realizado. Referencia: https://bit.ly/dles-guide)*

*(Capturas del Event Storming elaborado en LucidChart / Miro)*

![Design Level Event Storming](../assets/event-storming/design-level-event-storming.png)

*(Identificación de Bounded Contexts, Aggregates, Events, Commands and Queries)*

### 4.6.2. Software Architecture Context Diagram

*(Introducción y explicación del Context Diagram — C4 Model elaborado en Structurizr)*

*(El sistema como recuadro central, rodeado por usuarios y sistemas externos con los que interactúa)*

![Software Architecture Context Diagram](../assets/architecture/context-diagram.png)

*(Explicación del diagrama)*

### 4.6.3. Software Architecture Container Diagrams

*(Introducción y explicación del Container Diagram — C4 Model)*

*(Elementos de alto nivel de la arquitectura, distribución de responsabilidades, tecnologías y comunicación entre containers)*

![Software Architecture Container Diagram](../assets/architecture/container-diagram.png)

*(Explicación del diagrama)*

### 4.6.4. Software Architecture Components Diagrams

*(Component Diagrams para cada Container identificado — C4 Model)*

**Bounded Context: `[Nombre del Bounded Context]`**

![Component Diagram BC1](../assets/architecture/component-diagram-bc1.png)

*(Explicación de los components, sus responsabilidades y detalles de implementación/tecnología)*

---

## 4.7. Software Object-Oriented Design

>*En esta sección se presenta el diseño orientado a objetos del sistema Pawtient mediante diagramas de clases UML, los cuales describen la estructura interna de sus componentes. Los diagramas están organizados por bounded contexts, como gestión de pacientes, citas y suministros, permitiendo una clara separación de responsabilidades. Cada diagrama incluye clases, atributos, métodos y niveles de visibilidad, así como las relaciones entre ellas, especificando asociaciones y multiplicidades. Esto proporciona una visión estructurada del sistema y sirve como base para su implementación.*

<br>

### 4.7.1. Class Diagrams

A continuación, se presentan los diagramas de clases UML para cada bounded context del sistema *Pawtient*, donde se describen las clases, atributos, métodos y sus niveles de visibilidad. Asimismo, se incluyen las relaciones entre clases, especificando su tipo y multiplicidad, lo que permite comprender la estructura y organización del sistema.

<br>

**Bounded Context: `Gestión de Pacientes`**

<br>

En este bounded context se modelan las entidades relacionadas con la gestión de mascotas y sus historiales clínicos dentro del sistema Pawtient. El diagrama de clases incluye las clases principales Mascota, Dueño y HistorialClinico, las cuales permiten registrar, actualizar y consultar la información de los pacientes.

La clase Mascota contiene atributos como identificador, nombre, especie, raza, edad y peso, además de métodos para la gestión de sus datos. La clase Dueño almacena la información del responsable de la mascota, mientras que HistorialClinico gestiona los registros médicos, incluyendo diagnóstico y tratamiento.

Se establece una relación de asociación entre Dueño y Mascota con multiplicidad uno a muchos, y una relación de composición entre Mascota y HistorialClinico, donde cada mascota posee un único historial clínico. Esto permite representar de forma clara la estructura y comportamiento del sistema en este contexto.

<br>
<div align="center">
  
*Imagen del Class Diagram*

![Class Diagram BC1](pawtient-report/assets/images/class-diagrams/bounded_1.png)

*Elaboración propia con LucidChart*

</div>

<br>

**Bounded Context: `Gestión de Citas`**

<br>

En este bounded context se modela la programación y administración de las citas dentro del sistema Pawtient. Este módulo permite agendar, reprogramar y cancelar citas médicas para las mascotas, asegurando una correcta coordinación entre los dueños y los veterinarios.

El diagrama de clases incluye entidades como Cita, Veterinario y la enumeración EstadoCita, las cuales permiten representar el estado, la asignación y la gestión de cada cita. Además, se definen los atributos, métodos y relaciones necesarias para controlar el flujo de atención médica.

Las relaciones entre clases permiten establecer la asignación de citas a veterinarios y la gestión de sus estados, garantizando una organización eficiente del calendario clínico del sistema.

<br>
<div align="center">
  
*Imagen del Class Diagram*

![Class Diagram BC1](pawtient-report/assets/images/class-diagrams/bounded_2.png)

*Elaboración propia con LucidChart*

</div>


<br>

**Bounded Context: `Trazabilidad de Suministros`**

<br>

En este bounded context se gestiona el control y seguimiento de los suministros utilizados dentro del sistema Pawtient. Su objetivo es registrar el ingreso, uso y salida de insumos médicos y veterinarios, permitiendo mantener un control adecuado del inventario.

El diagrama de clases incluye entidades como Suministro y MovimientoSuministro, las cuales permiten representar la disponibilidad, el consumo y la trazabilidad de cada insumo dentro de la clínica. Además, se definen atributos y métodos que facilitan la actualización del stock y el registro de movimientos.

Las relaciones entre clases permiten llevar un control detallado del inventario, asegurando la correcta gestión de los recursos utilizados en la atención veterinaria.

<br>
<div align="center">
  
*Imagen del Class Diagram*

![Class Diagram BC1](pawtient-report/assets/images/class-diagrams/bounded_3.png)

*Elaboración propia con LucidChart*

</div>


<br>

**Bounded Context: `Gestión de Usuarios`**

<br>

En este bounded context se gestionan los usuarios del sistema Pawtient, incluyendo veterinarios y administradores que interactúan con la plataforma. Este módulo se encarga del control de acceso, la administración de perfiles y la asignación de roles dentro del sistema.

El diagrama de clases incluye entidades como Usuario, Veterinario y Administrador, permitiendo modelar las credenciales, datos personales y permisos de cada tipo de usuario. Además, se definen atributos y métodos que facilitan la autenticación, gestión de información y control de funciones dentro del sistema.

Las relaciones entre clases permiten establecer una jerarquía de usuarios mediante herencia, garantizando una estructura organizada y escalable para la gestión de accesos en la aplicación.

<br>
<div align="center">
  
*Imagen del Class Diagram*

![Class Diagram BC1](pawtient-report/assets/images/class-diagrams/bounded_4.png)

*Elaboración propia con LucidChart*

</div>

<br>

---

## 4.8. Database Design

>*En esta sección se presenta el diseño de la base de datos del sistema Pawtient, la cual está estructurada en base a los bounded contexts definidos previamente. Se modelan diagramas de base de datos relacionales que permiten la persistencia de la información del sistema. Cada diagrama incluye tablas, columnas, claves primarias y foráneas, así como las relaciones entre entidades. Este diseño garantiza la integridad de los datos y la correcta organización de la información según los módulos del sistema.*

<br>

### 4.8.1. Database Diagrams

*En esta sección se presentan los diagramas de base de datos para cada bounded context del sistema Pawtient. Estos diagramas describen la estructura de las tablas, sus columnas, claves primarias y foráneas, así como las relaciones entre ellas, permitiendo definir la persistencia de la información del sistema. Los diagramas han sido elaborados en Visual Studio Code utilizando la extensión **ERD Editor**, la cual permite generar modelos entidad-relación a partir de archivos en formato JSON.*

<br>

<div align="center">
  
**Bounded Context: `Gestión de Pacientes (Database Diagram)`**

<br>

![Database Diagram BC1](pawtient-report/assets/images/database/db_1.png)

</div>

<br>

*En este bounded context se modela la persistencia de datos de mascotas, dueños, historiales clínicos y consultas en el sistema Pawtient. El diagrama incluye las tablas Dueno, Mascota, HistorialClinico y Consulta, relacionadas mediante claves primarias y foráneas.*

*Se establece una relación uno a muchos entre Dueno y Mascota, una relación uno a uno entre Mascota y HistorialClinico, y una relación uno a muchos entre HistorialClinico y Consulta. Esto permite organizar y gestionar de forma eficiente la información clínica de los pacientes.*

<br>

<div align="center">
  
**Bounded Context: `Gestión de Citas (Database Diagram)`**

<br>

![Database Diagram BC2](pawtient-report/assets/images/database/db_2.png)

</div>

<br>

*En este bounded context se modela la persistencia de datos relacionados con la programación de citas en el sistema Pawtient. El diagrama incluye las tablas Cita, Veterinario y Mascota, las cuales permiten gestionar la asignación y organización de las atenciones médicas.*

*Se establecen relaciones uno a muchos entre Veterinario y Cita, así como entre Mascota y Cita, mediante claves foráneas. Esto permite registrar múltiples citas por veterinario y por mascota, asegurando una correcta gestión del calendario clínico.*

<br>

<div align="center">
  
**Bounded Context: `Trazabilidad de Suministros (Database Diagram)`**

<br>

![Database Diagram BC3](pawtient-report/assets/images/database/db_3.png)

</div>

<br>

*En este bounded context se modela la persistencia de datos relacionados con el control y seguimiento de los suministros en el sistema Pawtient. El diagrama incluye las tablas Suministro, MovimientoSuministro y AlertaInventario, que permiten gestionar el inventario y registrar los cambios en el stock.*

*Se establece una relación uno a muchos entre Suministro y MovimientoSuministro, así como entre Suministro y AlertaInventario, mediante claves foráneas. Esto permite llevar un control detallado de los movimientos y alertas asociadas a cada insumo.*


<br>


<div align="center">
  
**Bounded Context: `Gestión de Usuarios (Database Diagram)`**

<br>

![Database Diagram BC4](pawtient-report/assets/images/database/db_4.png)

</div>

<br>

*En este bounded context se modela la persistencia de datos relacionados con los usuarios del sistema Pawtient, incluyendo veterinarios y administradores. El diagrama está compuesto por las tablas Usuario, Veterinario y Administrador, que permiten gestionar la información, roles y acceso al sistema.*

*Se establece una relación de herencia entre Usuario y sus especializaciones, implementada mediante claves foráneas que vinculan a Veterinario y Administrador con la tabla principal. Esto permite mantener una estructura organizada y flexible para la gestión de usuarios.*


<br>

---


<div align="center">

# Capítulo V: Product Implementation, Validation & Deployment

</div>

---

## 5.1. Software Configuration Management

### 5.1.1. Software Development Environment Configuration

*(Especificar los productos de software que deben utilizar los miembros del equipo para colaborar en el ciclo de vida del producto digital)*

| Categoría | Producto | Propósito | Ruta / URL |
|:----------|:--------:|:---------:|:-----------|
| Project Management | `[Producto]` | `[Descripción del propósito]` | `[URL]` |
| Requirements Management | `[Producto]` | `[Descripción del propósito]` | `[URL]` |
| Product UX/UI Design | Figma | Wireframes, Mockups y Prototipos | https://figma.com |
| Product UX/UI Design | UXPressia | User Personas, Journey Maps, Empathy Maps | https://uxpressia.com |
| Software Development | IntelliJ IDEA / VS Code | Desarrollo de Web Services y Frontend | `[URL de descarga]` |
| Software Development | Angular CLI | Frontend Web Application | https://angular.io |
| Software Development | Spring Boot | RESTful Web Services | https://spring.io |
| Software Deployment | `[Plataforma cloud]` | Despliegue de productos | `[URL]` |
| Software Documentation | Swagger / OpenAPI | Documentación de Web Services | `[URL]` |
| Version Control | Git + GitHub | Control de versiones | https://github.com |

---

### 5.1.2. Source Code Management

*(Medios y esquema de organización para el seguimiento de modificaciones)*

**Organización de GitHub:** [`[URL de la organización]`](`[URL]`)

| Producto | Repositorio | URL |
|:--------:|:-----------:|:----|
| Landing Page | `[nombre-repo]` | `[URL]` |
| Frontend Web Application | `[nombre-repo]` | `[URL]` |
| Web Services (RESTful API) | `[nombre-repo]` | `[URL]` |
| Project Report | `[nombre-repo]` | `[URL]` |

**GitFlow Workflow:**

Se implementará GitFlow con las siguientes ramas:

| Rama | Propósito | Convención de nombre |
|:-----|:---------:|:---------------------|
| `main` | Código en producción | `main` |
| `develop` | Integración de features | `develop` |
| `feature/*` | Desarrollo de características | `feature/[descripción-corta]` |
| `release/*` | Preparación de releases | `release/[versión]` (ej: `release/1.0.0`) |
| `hotfix/*` | Correcciones urgentes en producción | `hotfix/[descripción-corta]` |

**Semantic Versioning:** Se aplica [Semantic Versioning 2.0.0](https://semver.org/) para nombrar los releases (`MAJOR.MINOR.PATCH`).

**Conventional Commits:** Se aplican [Conventional Commits](https://www.conventionalcommits.org/) para los mensajes de commits:

```
<tipo>[ámbito opcional]: <descripción>

Tipos: feat | fix | docs | style | refactor | test | chore
```

---

### 5.1.3. Source Code Style Guide & Conventions

*(Convenciones de nombrado y programación para cada lenguaje utilizado en la solución)*

| Lenguaje / Framework | Convención adoptada | Referencia |
|:--------------------:|:-------------------:|:-----------|
| HTML | HTML Style Guide | https://www.w3schools.com/html/html5_syntax.asp |
| CSS | Google HTML/CSS Style Guide | https://google.github.io/styleguide/htmlcssguide.html |
| JavaScript / TypeScript | Google TypeScript Style Guide | https://google.github.io/styleguide/tsguide.html |
| Angular | Angular coding style guide | https://angular.io/guide/styleguide |
| Java | Google Java Style Guide | https://google.github.io/styleguide/javaguide.html |
| Spring Boot | Spring Boot Features | https://docs.spring.io/spring-boot/docs/current/reference/html/features.html |
| Gherkin (Acceptance Criteria) | Gherkin Conventions | https://specflow.org/gherkin/gherkin-conventions-for-readable-specifications/ |

> **Nota:** Para todos los lenguajes se aplica la nomenclatura en **inglés**.

---

### 5.1.4. Software Deployment Configuration

*(Configuración del despliegue de la solución — pasos necesarios para lograr el despliegue de cada producto)*

**Landing Page:**
*(Describir pasos de despliegue del Landing Page — plataforma, configuración, automatización)*

**Frontend Web Application:**
*(Describir pasos de despliegue de la Web Application — plataforma, configuración, automatización)*

**Web Services (RESTful API):**
*(Describir pasos de despliegue del API — plataforma, configuración, automatización)*

---

## 5.2. Landing Page, Services & Applications Implementation

### 5.2.1. Sprint 1

#### 5.2.1.1. Sprint Planning 1

*(Introducción al Sprint Planning 1)*

| Campo | Detalle |
|:------|:--------|
| **Sprint #** | Sprint 1 |
| **Date** | `YYYY-MM-DD` |
| **Time** | `HH:MM AM/PM` |
| **Location** | `[Descripción de la ubicación — física o virtual]` |
| **Prepared By** | `[Apellido, Nombre — Team Leader]` |
| **Attendees** | `[Apellido1, Nombre1]` / `[Apellido2, Nombre2]` / ... |
| **Sprint 0 Review Summary** | *(Para el primer sprint, describir el estado inicial del proyecto)* |
| **Sprint 0 Retrospective Summary** | *(Para el primer sprint, describir las expectativas del equipo)* |
| **Sprint 1 Goal** | *(Definir el Goal siguiendo la estructura: Our focus is on... We believe it delivers... This will be confirmed when...)* |
| **Sprint 1 Velocity** | `[Story Points que puede aceptar el equipo]` |
| **Sum of Story Points** | `[Suma de Story Points del Sprint]` |

---

#### 5.2.1.2. Aspect Leaders and Collaborators

*(Introducción explicando los principales aspectos del Sprint)*

| Team Member (Last Name, First Name) | GitHub Username | `[Aspecto 1]` | `[Aspecto 2]` | `[Aspecto 3]` | `[Aspecto n]` |
|:-----------------------------------:|:---------------:|:-------------:|:-------------:|:-------------:|:-------------:|
| `[Apellido, Nombre]` | `[username]` | L | C | C | L |
| `[Apellido, Nombre]` | `[username]` | C | L | C | C |
| `[Apellido, Nombre]` | `[username]` | C | C | L | C |
| `[Apellido, Nombre]` | `[username]` | C | C | C | L |
| `[Apellido, Nombre]` | `[username]` | L | C | C | C |

> **L** = Leader &nbsp;|&nbsp; **C** = Collaborator

---

#### 5.2.1.3. Sprint Backlog 1

*(Introducción que resume el objetivo principal del Sprint 1)*

**URL del Board en herramienta de control:** [`[URL pública del Board]`](`[URL]`)

*(Screenshot del Board del Sprint 1)*

![Sprint 1 Board](../assets/sprints/sprint1-board.png)

| Sprint # | | | | | | | |
|:--------:|---|---|---|---|---|---|---|
| **Sprint 1** | **User Story** | | **Work-Item / Task** | | | | |
| | **ID** | **Título** | **ID** | **Título** | **Descripción** | **Estimación (h)** | **Asignado a** | **Estado** |
| | US01 | `[Título]` | T01 | `[Título del task]` | `[Descripción]` | `[n]` | `[Nombre]` | To-do / In-Process / To-Review / Done |
| | US01 | | T02 | `[Título del task]` | `[Descripción]` | `[n]` | `[Nombre]` | |
| | US02 | `[Título]` | T03 | `[Título del task]` | `[Descripción]` | `[n]` | `[Nombre]` | |

---

#### 5.2.1.4. Development Evidence for Sprint Review

*(Introducción resumiendo los principales avances en implementación del Sprint 1)*

| Repository | Branch | Commit ID | Commit Message | Commit Message Body | Committed on (Date) |
|:----------:|:------:|:---------:|:--------------:|:-------------------:|:-------------------:|
| `[user/repo]` | `[branch]` | `[commit-id]` | `[mensaje]` | `[cuerpo]` | `YYYY-MM-DD` |
| | | | | | |

---

#### 5.2.1.5. Execution Evidence for Sprint Review

*(Resumen de lo alcanzado en el Sprint 1 — screenshots de vistas implementadas)*

*(Descripción de las vistas implementadas)*

![Execution Evidence 1](../assets/sprints/sprint1-execution-1.png)

[Ver video de ejecución Sprint 1](`URL`)

---

#### 5.2.1.6. Services Documentation Evidence for Sprint Review

*(Introducción resumiendo los logros de Documentación de Web Services para el Sprint 1)*

> *(Para el Sprint 1, enfocado en Landing Page, puede no aplicar. Documentar si se implementaron endpoints)*

| Endpoint | Acción | Verbo HTTP | Sintaxis | Parámetros | Response ejemplo | URL documentación |
|:--------:|:------:|:----------:|:--------:|:----------:|:----------------:|:-----------------:|
| `[endpoint]` | `[acción]` | `GET/POST/PUT/DELETE` | `[sintaxis]` | `[params]` | `[JSON]` | `[URL]` |

---

#### 5.2.1.7. Software Deployment Evidence for Sprint Review

*(Introducción explicando las actividades de despliegue realizadas durante el Sprint 1)*

*(Capturas e instrucciones de los pasos realizados durante el Sprint: creación de cuentas, configuración de recursos en cloud, configuración de proyectos)*

![Deployment Evidence 1](../assets/sprints/sprint1-deployment-1.png)

---

#### 5.2.1.8. Team Collaboration Insights during Sprint

*(Descripción de las actividades de implementación y capturas de analíticos de colaboración en GitHub)*

*(Capturas de analíticos de commits por miembro del equipo en GitHub)*

![Team Collaboration Sprint 1](../assets/sprints/sprint1-collaboration.png)

---

## 5.3. Validation Interviews

### 5.3.1. Diseño de Entrevistas

*(Elementos a incluir en la sesión de validación por segmento objetivo — Landing Page y aplicaciones)*

**Segmento objetivo 1:**
*(Especificar user flows que formarán parte del proceso de validación)*

**Segmento objetivo 2:**
*(Especificar user flows que formarán parte del proceso de validación)*

### 5.3.2. Registro de Entrevistas

*(Para cada segmento se requiere de 3 a 5 entrevistas de validación)*

**Segmento objetivo 1:**

| Campo | Detalle |
|:------|:--------|
| **Nombres y apellidos** | `[Nombre]` |
| **Edad** | `[Edad]` |
| **Distrito** | `[Distrito]` |
| **Enlace al video** | [Ver en Microsoft Stream](`URL`) — Inicia en `[MM:SS]` |

*(Screenshot del video de validación)*

![Validation Interview Screenshot](../assets/validation/validation-seg1-1.png)

**Resumen:** *(Descripción de las principales apreciaciones del entrevistado)*

### 5.3.3. Evaluaciones según heurísticas

*(Ver formato completo en el Anexo D del enunciado del proyecto)*

**UX Heuristics & Principles Evaluation**
*Usability – Inclusive Design – Information Architecture*

**Site o App a evaluar:** BrandRadar

**Tareas a evaluar:**
1. *(Tarea 1)*
2. *(Tarea 2)*
3. *(Tarea 3)*

**Escala de Severidad:**

| Nivel | Descripción |
|:-----:|:------------|
| 1 | Problema superficial — puede superarse fácilmente o rara vez ocurre |
| 2 | Problema menor — ocurre con más frecuencia o es algo difícil de superar |
| 3 | Problema mayor — ocurre frecuentemente o los usuarios no pueden resolverlo |
| 4 | Problema muy grave — impide al usuario continuar usando la herramienta |

**Tabla Resumen:**

| # | Problema | Severidad | Heurística / Principio violado |
|:-:|:---------|:---------:|:-------------------------------|
| 1 | *(Descripción del problema)* | `[1-4]` | `[Heurística]` |
| 2 | *(Descripción del problema)* | `[1-4]` | `[Heurística]` |

---

## 5.4. Video About-the-Product

*(Introducción y descripción del Video About-the-Product)*

- **Público objetivo:** Visitantes del Landing Page y usuarios de las aplicaciones
- **Duración:** 1 a 3 minutos
- **URL Microsoft Stream:** [`[Nombre del video]`](`URL`)
- **URL YouTube (para incrustar en Landing Page):** [`[Nombre del video]`](`URL`)

*(Screenshot del video)*

![About the Product Video Screenshot](../assets/videos/about-the-product-screenshot.png)

---
<br>

## Conclusiones

*(Esta sección se desarrolla progresivamente en cada entrega)*

## Recomendaciones

*(Esta sección se desarrolla progresivamente en cada entrega)*

## Video About-The-Team

*(Incluir screenshot, URL de Microsoft Stream y YouTube, y timing del video)*

---

<br>

##  Bibliografía

*(Listar referencias en formato APA)*


---

<br>

## Anexos


### Anexo A: Participant Performance Report

*(Adjuntar como documento Word y PDF por separado)*

### Anexo B: Videos de Exposiciones

| Entrega | Título | Enlace |
|:-------:|:------:|:------:|
| AV1 | `upc-pre-202610-1asi0729-[10203]-[pethealt]-expo-av1` | `[URL Microsoft Stream]` |


---

<div align="center">

<br>

*PetHealt · Aplicaciones Web · UPC 2026-10*

</div>
