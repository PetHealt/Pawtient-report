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
| **5.c1. Trabaja en equipo para proporcionar liderazgo en forma conjunta.** | **Salinas Guzmán, Brianna** <br> AV1: Demostré liderazgo colaborativo al guiar la estructuración del sistema mediante la elaboración del Ubiquitous Language, User Stories, Impact Mapping y Product Backlog, facilitando la alineación del equipo en torno al dominio del problema. <br><br> **Quintanilla Pozo, Gonzalo** <br> AV1: Ejercí el liderazgo técnico al establecer el flujo de trabajo con GitFlow, supervisando la creación de ramas y resolviendo conflictos de integración. Coordiné el Sprint Planning para alinear los objetivos del equipo con el despliegue de la Landing Page y proporcioné dirección en la arquitectura de estilos base. <br><br> **Salazar Miranda, Mateo** <br> AV1: Contribuí al liderazgo técnico mediante el análisis y diseño de la sección de Servicios y Estadísticas. Participé activamente en la toma de decisiones sobre la arquitectura C4 y el diseño de clases, aportando una visión crítica para optimizar la estructura y escalabilidad del sistema. <br><br> **Arroyo Gonzales, Emily** <br> AV1: Demostré liderazgo colaborativo al liderar el modelado del Design Level Event Storming, facilitando la identificación de Bounded Contexts esenciales como Clinic y Appointment. Aseguré la consistencia estética y funcional mediante el diseño de componentes visuales clave. <br><br> **Acuache Lucas, Mathias** <br> AV1: Colaboré en la dirección conjunta del equipo mediante la estructuración de secciones críticas como IoT, Roles y Pricing. Mi participación en el diseño de la base de datos y diagramas de arquitectura permitió tener una visión clara de la lógica de negocio del sistema. | El equipo PetHealt logró establecer una base sólida de trabajo mediante metodologías ágiles y GitFlow, permitiendo una integración sin fricciones. La combinación de liderazgo técnico y comunicación clara resultó en un despliegue exitoso, cumpliendo con el 100% de los objetivos planteados para esta entrega. |
| **5.c2. Crea un entorno colaborativo e inclusivo, establece metas, planifica tareas y cumple objetivos** | **Salinas Guzmán, Brianna** <br> AV1: Contribuí a la creación de un entorno colaborativo mediante la organización y priorización del Product Backlog, estableciendo metas claras para el desarrollo del sistema Pawtient. Aseguré la coherencia entre requerimientos y diseño técnico. <br><br> **Quintanilla Pozo, Gonzalo** <br> AV1: Fomenté un entorno colaborativo al configurar el entorno de despliegue continuo en Netlify y gestionar las versiones mediante la rama v1.0.0. Planifiqué y ejecuté tareas de integración técnica, cumpliendo con el objetivo de publicar la Landing Page en los tiempos establecidos. <br><br> **Salazar Miranda, Mateo** <br> AV1: Participé en la planificación de tareas mediante la estimación de tiempos para la implementación de secciones responsivas del frontend. Cumplí con los objetivos asignados al desarrollar componentes CSS modulares para las funcionalidades de estadísticas de la plataforma. <br><br> **Arroyo Gonzales, Emily** <br> AV1: Contribuí a un entorno inclusivo al documentar los procesos de diseño y asegurar que las necesidades de los veterinarios se reflejaran en el Event Storming. Planifiqué y cumplí con la entrega de recursos visuales para la sección Hero y de Contacto. <br><br> **Acuache Lucas, Mathias** <br> AV1: Demostré compromiso con las metas del Sprint al planificar e implementar la lógica de navegación y los componentes de precios. Mi proactividad en la resolución de tareas del Sprint Backlog permitió cumplir con el despliegue de una plataforma funcional y preparada para futuras integraciones. | El cumplimiento riguroso del Sprint Backlog y la distribución equitativa de tareas garantizaron un entorno de trabajo productivo. La planificación estratégica permitió que todas las historias de usuario del primer sprint pasaran a estado "Done", validando la capacidad de entrega técnica del equipo bajo presión académica. |
---

<div align="center">

# Capítulo I: Introducción

</div>

---

## 1.1. Startup Profile

### 1.1.1. Descripción de la Startup

**PetHealth** es una startup tecnológica enfocada en la modernización del sector veterinario mediante soluciones digitales orientadas a la gestión clínica. Su producto principal, Pawtient, es una plataforma web SaaS diseñada para ayudar a clínicas veterinarias y veterinarios independientes a optimizar la administración de historiales clínicos, citas, tratamientos e inventarios médicos.

- **Misión:** Desarrollar soluciones digitales que optimicen la gestión de clínicas veterinarias y veterinarios independientes, facilitando el control de la información clínica, la organización de procesos y la eficiencia operativa para mejorar la calidad del servicio veterinario.


- **Visión:** Posicionarnos como una startup líder en soluciones tecnológicas para la gestión veterinaria en Latinoamérica, impulsando la digitalización y modernización de los servicios veterinarios mediante herramientas accesibles, eficientes e innovadoras.

---

###   1.1.2. Perfiles de integrantes del equipo

|                                         Miembro                                         |                                                                                                                                                                                                                                                                                                                                                Descripción                                                                                                                                                                                                                                                                                                                                                |
|:---------------------------------------------------------------------------------------:|:---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------:|
| <img src="pawtient-report/assets/images/Capítulo1/members/Gonzalo.png " width="3000"/>  |                                                                                                                                                                                            **Gonzalo Samuel Quintanilla Pozo \- U202315007** <br>  Soy estudiante de la carrera de Ingeniería de Software en la UPC y tengo 20 años, como compañero me gusta apoyar y tomar iniciativa en trabajos grupales. Me especializo en los lenguajes CSS, Java y Python. Tengo experiencia desarrollando páginas web.                                                                                                                                                                                             |
| <img src="pawtient-report/assets/images/Capítulo1/members/Mathias.jpeg " width="3000"/> |                                                                                                                                                   **Mathias Joaquin Acuache Lucas \- U202314898** <br> Soy Mathias Joaquin Acuache Lucas, me encuentro en el sexto ciclo de la carrera de ingeniería de software, mi código de alumno es u202314898. Tengo experiencia en C++, SQL, MongoDB, además de utilizar GitHub de manera correcta . Me considero una persona que trata de apoyar en los diversos trabajos en equipo e investigar cosas nuevas.                                                                                                                                                    |
| <img src="pawtient-report/assets/images/Capítulo1/members/Brianna.png " width="3000"/>  | **Brianna Cristina Salinas Guzman \- U202410239** <br> Soy estudiante de Ingeniería de Software con conocimientos en desarrollo de aplicaciones, estructuras de datos y programación orientada a objetos. Tengo experiencia trabajando con lenguajes como C++, Pyhton, SQL para base de datos y en la gestión de proyectos utilizando Git y GitHub para el control de versiones. Además, cuento con formación complementaria en marketing digital, lo que me permite aportar una perspectiva orientada al usuario y al posicionamiento del producto. Me considero una persona responsable, con capacidad de aprendizaje autónomo y habilidades para trabajar en equipo y comunicar ideas de manera clara. | 
|  <img src="pawtient-report/assets/images/Capítulo1/members/Mateo.jpg " width="3000"/>   |                                                                                                                                                                                                                 **Mateo Paolo Salazar Miranda \- U202315171**   <br>  Soy un estudiante responsable y comprometido, con interés en el desarrollo de soluciones tecnológicas innovadoras. Tengo habilidades en trabajo en equipo, pensamiento analítico y resolución de problemas                                                                                                                                                                                                                          | 
|  <img src="pawtient-report/assets/images/Capítulo1/members/Emily.png " width="3000"/>   |                                                                                                                                                                                                            **Emily Juliette Arroyo Gonzales \- U202311469**  <br> Soy estudiante de la carrera de Ingeniería de Software, tengo 20 años, tengo experiencia en lenguajes como C++, MongoDB, en trabajos grupales me gusta aportar ideas que contribuyan a mi grupo y avanzar según lo asignado.                                                                                                                                                                                                            | 

---

## 1.2. Solution Profile

### 1.2.1. Antecedentes y problemática

#### What? (¿Qué?)


#### ¿Cuál es el problema?


Muchos centros veterinarios aún gestionan la información clínica y administrativa de forma manual o mediante herramientas poco integradas, lo que genera desorganización en historiales clínicos, citas e inventarios médicos. Esto dificulta la gestión operativa y reduce la eficiencia en la atención veterinaria.

#### When? (¿Cuándo?)


#### ¿Cuándo ocurre el problema?


El problema ocurre principalmente durante el registro de consultas, la programación de citas, el seguimiento de tratamientos y el control de insumos médicos, especialmente cuando la información no se actualiza en tiempo real o se maneja manualmente.

#### Where? (¿Dónde?)


#### ¿Dónde surge el problema?


La problemática surge en los procesos operativos y administrativos dentro de clínicas veterinarias y consultorios independientes.

#### ¿En qué tipo de centros o contextos ocurre esta problemática?


Se presenta principalmente en clínicas veterinarias pequeñas y medianas, así como en veterinarios independientes que aún utilizan registros manuales, archivos físicos o herramientas no especializadas para gestionar su información.

#### Who? (¿Quién?)


#### ¿Quiénes son los principales afectados por esta problemática?


Los principales afectados son los dueños y administradores y veterinarios independientes, quienes enfrentan dificultades para organizar información clínica, gestionar citas, controlar inventarios y optimizar sus procesos operativos.

#### ¿Quién lo utilizará?


La plataforma será utilizada por clínicas veterinarias y veterinarios independientes para registrar historiales clínicos, gestionar citas, controlar tratamientos e inventarios médicos y optimizar la administración de sus servicios.

#### Why? (¿Por qué?)


#### ¿Cuál es la causa del problema?


La principal causa es la falta de digitalización e integración de los procesos veterinarios, lo que provoca desorganización, duplicidad de información, errores en los registros y dificultades en la gestión operativa y administrativa.


#### How? (¿Cómo?)


#### ¿En qué condiciones los usuarios usarán nuestro producto?


Los usuarios utilizarán la plataforma durante sus actividades diarias para registrar consultas, gestionar citas, supervisar tratamientos, controlar inventarios y acceder a información clínica en tiempo real.

#### ¿Cómo les gustaría a los usuarios acceder a la plataforma?


Los usuarios prefieren acceder mediante computadoras y dispositivos móviles, ya que esto les permite gestionar la información clínica y administrativa de forma rápida, flexible y desde cualquier lugar.

#### How much? (¿Cuánto?)


#### ¿Cómo impacta la gestión ineficiente de la información clínica y de los insumos médicos en la calidad de atención en las clínicas veterinarias?


Esto impacta de manera significativa en la calidad de atención en las clínicas o centros veterinarios, ya que el manejo manual y no centralizado de los datos puede generar pérdida, duplicidad y dificultad en el acceso a los registros clínicos, afectando el seguimiento adecuado de los pacientes.


De acuerdo con Cedeno Ochoa et al. (2021), en muchos centros veterinarios la información aún se gestiona de forma manual, lo que dificulta la organización de los expedientes y puede ocasionar errores en los registros. Asimismo, la implementación de herramientas digitales permite reducir el tiempo de atención y mejorar la eficiencia en los procesos administrativos.


En el contexto peruano, Lolimsa (2024) señala que una inadecuada gestión en centros veterinarios, especialmente en el manejo de información e insumos, puede generar retrasos de atención, desorganización y una disminución en la calidad del servicio. En este sentido, la falta de digitalización impacta negativamente, mientras que soluciones como Pawtient permiten optimizar procesos, reducir errores y ofrecer una atención más eficiente y confiable.

---

### 1.2.2. Lean UX Process

El proceso de Lean UX es una metodología de diseño enfocada en el usuario que busca mejorar continuamente el producto a partir de la prueba de ideas, la evaluación y la retroalimentación constante. En el caso de Pawtient, se aplicará para entender mejor las necesidades de los dueños y administradores de clínicas veterinarias, así como de los veterinarios independientes, permitiendo ajustar la plataforma en función de su uso real y mejorar su experiencia de manera progresiva.

#### 1.2.2.1. Lean UX Problem Statements

Nuestro sistema busca mejorar la forma en que las clínicas veterinarias y los veterinarios independientes gestionan su información clínica, facilitando el acceso a datos y el control de sus procesos operativos.

Hemos observado que en muchos centros veterinarios y servicios independientes la información aún se maneja de forma manual o mediante herramientas no integradas, lo que dificulta el acceso a datos actualizados, el seguimiento de historiales clínicos y la correcta gestión de citas e insumos médicos.

**¿Cómo podemos lograr que las clínicas veterinarias y los veterinarios independientes gestionen su información clínica y sus procesos de manera más organizada, accesible y confiable?**

Nuestro sistema también busca optimizar la gestión administrativa y operativa dentro de las clínicas veterinarias, facilitando el control de recursos y mejorando la eficiencia en la atención.

Actualmente, muchos centros veterinarios presentan dificultades para controlar sus inventarios, organizar citas y centralizar la información clínica, lo que genera desorganización y afecta la eficiencia de sus operaciones.

**¿Cómo podemos mejorar la gestión operativa y administrativa de las clínicas veterinarias para optimizar sus procesos y reducir errores en el manejo de la información?**

Nuestro sistema busca optimizar la gestión de los recursos e insumos dentro de las clínicas veterinarias, mejorando la eficiencia de sus procesos operativos.

Hemos identificado que la gestión de insumos suele realizarse de forma manual o con herramientas poco integradas, lo que genera desorganización, errores en el control de stock y dificultades en la toma de decisiones.

**¿Cómo podemos mejorar el control y la gestión de los recursos e insumos en las clínicas veterinarias para optimizar sus procesos ?**

---

#### 1.2.2.2. Lean UX Assumptions

**Business Assumptions:**

1. **Considero que** las clínicas veterinarias y los veterinarios independientes requieren una forma más ordenada, eficiente y segura de gestionar la información clínica y administrativa de sus servicios.
2. **Estas necesidades pueden resolverse con** una plataforma web que centralice historiales clínicos, control de insumos, gestión de citas y seguimiento de tratamientos.
3. **Nuestros primeros usuarios serán** los dueños y administradores de clínicas veterinarias, así como los veterinarios independientes que buscan optimizar sus procesos operativos y mejorar la organización de la información clínica.
4. **El principal beneficio que buscan los usuarios es** mejorar la eficiencia de sus operaciones, reducir errores administrativos y tomar decisiones basadas en información actualizada.
5. **El sistema también ofrece** control de inventario, gestión de citas, seguimiento de tratamientos y acceso rápido a información clínica en tiempo real.
6. **La captación de nuestros usuarios será a través de** marketing digital, alianzas con on clínicas veterinarias y recomendaciones dentro del sector veterinario.
7. **Generaré ingresos mediante** un modelo de suscripción mensual con diferentes niveles: Paw Basic(5 USD), Paw Care(15 USD), Paw Pro(30 USD).
8. **Mi competencia estará conformada** por otros sistemas de gestión veterinaria y soluciones digitales similares.
9. **Nos diferenciamos por** ofrecer una plataforma accesible, fácil de usar y enfocada en centralizar la gestión clínica y operativa en un solo sistema.
10. **Mi principal riesgo** será la baja adopción del sistema debido a la resistencia al cambio o poca familiaridad con herramientas digitales.
11. **Abordaremos este riesgo mediante** una interfaz simple, guías de uso dentro de la plataforma y un proceso de adopción progresivo que facilite el uso desde el primer momento.

**User Assumptions:**

**¿Quiénes son nuestros usuarios?**


Los usuarios de Pawtient son dueños y administradores de clínicas veterinarias, así como veterinarios independientes que buscan optimizar la gestión de historiales clínicos, citas, tratamientos e inventarios médicos mediante herramientas digitales.

**¿Qué problemas busca resolver nuestro producto?**


Pawtient busca resolver la desorganización de la información clínica, la falta de integración de procesos y el control limitado de citas e insumos médicos dentro de clínicas veterinarias y servicios independientes.

**¿En qué momentos y de qué forma se utiliza el producto?**


La plataforma se utiliza durante consultas, gestión de citas, seguimiento de tratamientos y control de inventarios. Puede ser accedida desde computadoras o dispositivos móviles, permitiendo trabajar con información actualizada en tiempo real.

**¿Cómo se integra la solución en la rutina del usuario?**


El sistema forma parte de las actividades diarias de clínicas veterinarias y veterinarios independientes, facilitando el registro de consultas, la gestión de pacientes, el control de insumos y la organización de procesos operativos.

**¿Qué tan sencilla es la adopción de la plataforma?**


La incorporación de la plataforma será progresiva, ya que reemplaza procesos manuales por una solución más organizada. Su diseño simple y fácil de usar permite que los usuarios se adapten rápidamente sin afectar sus actividades habituales.


**¿Qué esperan ver los usuarios en la plataforma?**


La plataforma debe contar con un diseño claro y ordenado, con iconos fáciles de reconocer, colores adecuados y una estructura que facilite la navegación. Esto permite que los usuarios comprendan rápidamente las funciones y puedan interactuar de forma ágil y sencilla.


---

#### 1.2.2.3. Lean UX Hypothesis Statements

- **Hypothesis 01:**

  <br>**Creemos que** los dueños y administradores de clínicas veterinarias mejorarán la organización de la información si centralizan los historiales clínicos en una sola plataforma.

  <br>**Sabremos que** hemos tenido éxito.

  <br>**Cuando** encuentren la información más rápido y disminuyan los errores al momento de registrar o consultar datos.


- **Hypothesis 02:**

  <br>**Creemos que** los veterinarios independientes optimizarán la gestión de sus consultas si cuentan con acceso rápido y centralizado a la información clínica de sus pacientes.

  <br>**Sabremos que** hemos tenido éxito.

  <br>**Cuando** reduzcan el tiempo de búsqueda de información y mejoren el seguimiento de tratamientos y consultas.


- **Hypothesis 03:**

  <br>**Creemos que** las notificaciones sobre citas y tratamientos ayudarán a los dueños y administradores de clínicas veterinarias, así como a los veterinarios independientes, a gestionar mejor sus actividades diarias.

  <br>**Sabremos que** hemos tenido éxito.

  <br>**Cuando** disminuyan las citas perdidas y se mejore el seguimiento de los tratamientos registrados.


- **Hypothesis 04:**

  <br>**Creemos que** los dueños y administradores de clínicas veterinarias registrarán la información más rápido si utilizan formularios digitales dentro de la plataforma.

  <br>**Sabremos que** hemos tenido éxito.

  <br>**Cuando** los registros se completen en menos tiempo y sin repetir información.


- **Hypothesis 05:**

  <br>**Creemos que** centralizar el estado clínico y los tratamientos de los pacientes ayudará a los dueños y administradores de clínicas veterinarias a mejorar el seguimiento y control de la atención médica.

  <br>**Sabremos que** hemos tenido éxito.

  <br>**Cuando** los usuarios consulten frecuentemente la información clínica y mejoren el seguimiento de los pacientes.


- **Hypothesis 06:**

  <br>**Creemos que** una plataforma organizada y accesible mejorará la confianza de los dueños y administradores de clínicas veterinarias, así como de los veterinarios independientes, en la gestión de su información operativa y clínica.

  <br>**Sabremos que** hemos tenido éxito.

  <br>**Cuando** los usuarios utilicen constantemente la plataforma y reduzcan el uso de registros manuales o herramientas no integradas.

---

#### 1.2.2.4. Lean UX Canvas

El Lean UX Canvas es una herramienta visual que permite organizar y comprender los elementos clave de un producto, enfocándose en el problema, los usuarios y el valor que se busca ofrecer.

En el caso de Pawtient, se utiliza para identificar las necesidades de los dueños y administradores de clínicas veterinarias, así como de los veterinarios independientes, y definir cómo la plataforma aporta valor dentro de la gestión veterinaria.

A continuación, se presenta el Lean UX Canvas de Pawtient:

![Lean UX Canvas](pawtient-report/assets/images/Capítulo1/Lean-UX-Canvas.png)

**Enlace al Lean UX Canvas:** [*Ver en Miro*](https://miro.com/welcomeonboard/QVN1VzZ1RmhoWEhGUm9heXpldFAyenkxK1hWQ1hiQ1dLTUlNN2twU1ArL0o2TzY2ZzdlMjc2dkJ0SEhvdy9PQTZGejBEeFNJWFQ5VUh2V1NNb3hKNlcxUnNrTWZNWmh3MitiSXhvQVdHeUtxSFhvTWN2OTNLNTk5LzZSa0lWUklzVXVvMm53MW9OWFg5bkJoVXZxdFhRPT0hdjE=?share_link_id=400022156481)

---

## 1.3. Segmentos objetivo

En el análisis del segmento objetivo para Pawtient, se ha identificado que nuestros principales usuarios serán los dueños y administradores de clínicas veterinarias, así como los veterinarios independientes.

### Dueños y administradores de clínicas veterinarias

Incluye responsables de la gestión operativa y administrativa de clínicas veterinarias, quienes necesitan organizar la información clínica, gestionar citas, controlar inventarios y optimizar los procesos del centro de forma eficiente.

- **Factores demográficos:**

  - Hombres y mujeres entre 30 y 55 años.
  - Propietarios o administradores de clínicas veterinarias urbanas.
  - Residentes principalmente en Santiago de Surco, Lima, Perú.
  - Nivel socioeconómico B y C.
  - Experiencia previa en gestión veterinaria o administración de negocios.


- **Factores psicográficos:**
   - Buscan optimizar la gestión operativa de sus clínicas.
   - Priorizan el orden, la eficiencia y el control de procesos.
   - Están interesados en modernizar y digitalizar sus servicios.
   - Buscan mejorar la organización y reducir errores administrativos.


- **Necesidades clave:**
  
   - Centralizar historiales clínicos y citas. 
   - Mejorar el control de inventarios e insumos médicos. 
   - Optimizar la gestión operativa y administrativa. 
   - Acceder rápidamente a información clínica actualizada.

### Veterinarios independientes


Incluye profesionales veterinarios que realizan consultas independientes y requieren herramientas digitales para gestionar pacientes, historiales clínicos y tratamientos de manera rápida y organizada.

- **Factores demográficos:**

    - Hombres y mujeres entre 25 y 45 años. 
    - Médicos veterinarios que trabajan de manera independiente. 
    - Residentes principalmente en Santiago de Surco, Lima, Perú.
    - Nivel socioeconómico B y C. 
    - Profesionales con experiencia en atención clínica veterinaria.


- **Factores psicográficos:**
    - Buscan herramientas digitales prácticas y accesibles. 
    - Priorizan la rapidez y movilidad en su trabajo diario. 
    - Desean reducir tareas manuales y mejorar la organización de consultas. 
    - Están interesados en gestionar información clínica desde cualquier lugar.


- **Necesidades clave:**

    - Gestionar pacientes e historiales clínicos de forma digital. 
    - Organizar citas y tratamientos veterinarios. 
    - Acceder a información clínica desde dispositivos móviles. 
    - Mejorar la eficiencia y organización de sus consultas.

---

<div align="center">

# Capítulo II: Requirements Elicitation & Analysis

</div>

---

## 2.1. Competidores

### 2.1.1. Análisis competitivo

Ahora veremos un análisis competitivo para identificar a los principales actores del mercado de software veterinario (vet-tech) en el Perú y Latinoamérica,
y evaluar sus fortalezas y debilidades. Esto nos permite definir la propuesta de valor de PetHealth y crear estrategias que nos ayuden a diferenciarnos y capturar la atención de nuestros usuarios, tanto clínicas veterinarias como dueños de mascotas.

#### Competitive Analysis Landscape
<table>
  <thead>
    <tr>
      <th colspan="7"><b>Competitive Analysis Landscape</b></th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td colspan="2" align="center">¿Por qué llevar a cabo este análisis?</td>
      <td colspan="5" align="center">El objetivo de este análisis es identificar las características de los competidores, evaluar sus fortalezas y debilidades, y encontrar maneras de diferenciarnos para obtener una ventaja competitiva en el mercado de software veterinario.</td>
    </tr>
      <tr>
    <td colspan="2" rowspan="2" valign="top">Startup y Competidores</td>
        <td valign="top" align="center">Nuestra Startup</td>
        <td valign="top" align="center"></td>
        <td valign="top" align="center"></td>
        <td valign="top" align="center"></td>
  </tr>
  <tr>
    <td valign="top" align="center"><img src="pawtient-report/assets/images/pawtient.png" alt="Pawtient" height="80" /></td>
    <td valign="top" align="center"><img src="pawtient-report/assets/images/Competidores-logo/SmartVet.png" alt="SmartVet" height="80" /></td>
    <td valign="top" align="center"><img src="pawtient-report/assets/images/Competidores-logo/Qvet.jpg" alt="Qvet" height="80" /></td>
    <td valign="top" align="center"><img src="pawtient-report/assets/images/Competidores-logo/Provet-cloud.jpeg" alt="Provet Cloud" height="80" /></td>
   </tr>
  <tr>
    <td rowspan="2" valign="top">Perfil</td>
    <td valign="top">Overview</td>
    <td valign="top">Es una plataforma web SaaS orientada a la gestión integral de clínicas veterinarias. Permite gestionar historiales clínicos, citas e inventarios, además de conectar directamente al veterinario con el dueño de la mascota a través de un portal de seguimiento en tiempo real.</td>
    <td valign="top">Software en la nube para la gestión de clínicas veterinarias, enfocado en simplificar la facturación, los registros médicos y la agenda para consultorios pequeños y medianos en Latinoamérica.</td>
    <td valign="top">Software de gestión veterinaria muy completo y consolidado. Centraliza desde la historia clínica hasta la facturación y cuenta con un ecosistema de herramientas empresariales muy robusto para el sector hispanohablante.</td>
    <td valign="top">Es una plataforma veterinaria avanzada basada en la nube que tiene incluido diversas herramientas de IA para dictado de notas médicas para las mascotas. Tiene un sistema “limpio”, esto permite tener una propiedad de los datos para la organización.</td>
  </tr>
  <tr>
    <td valign="top">Ventaja competitiva ¿Qué valor ofrece a los clientes?</td>
    <td valign="top">Ofrecemos una herramienta simple, accesible y centralizada. Nuestro mayor valor es la visibilidad total que le damos al dueño de la mascota sobre los tratamientos y credenciales de su veterinario, generando confianza y fidelización, todo en un entorno web fácil de usar.</td>
    <td valign="top">Destaca por su facilidad de uso inicial y su bajo costo para clínicas que recién empiezan a digitalizarse. Su soporte técnico en español es muy valorado en la región.</td>
    <td valign="top">Destaca por su extrema robustez, capacidad para administrar grupos de clínicas interconectadas, e innovación tecnológica (como el uso de IA para recomendar productos y servicios médicos al cliente).</td>
    <td valign="top">La principal diferencia es la innovación mediante IA navita. Ofrece un asistente que redacta notas médicas, además de tener un resumen del historial y automatiza la captura de cargos omitidos,etc.</td>
  </tr>
  <tr>
    <td rowspan="2" valign="top">Perfil de Marketing</td>
    <td valign="top">Mercado objetivo</td>
    <td valign="top">Clínicas veterinarias de tamaño pequeño a mediano en Perú y Latinoamérica, y dueños de mascotas que exigen transparencia y seguimiento digital de la salud de sus animales.</td>
    <td valign="top">Consultorios independientes y pequeñas clínicas en Latinoamérica que buscan salir del papel y usar su primer software de gestión.</td>
    <td valign="top">Clínicas veterinarias de tamaño medio, grandes hospitales y grupos corporativos veterinarios que buscan un control empresarial, clínico y financiero total a gran escala.</td>
    <td valign="top">Clínicas veterinarias de alta complejidad, además de clínicas con múltiples sedes y servicios especialidades o medicina móvil.</td>
  </tr>
  <tr>
    <td valign="top">Estrategias de marketing</td>
    <td valign="top">Marketing digital en redes sociales, demostraciones gratuitas a dueños de clínicas, y estrategias de referidos (dueños de mascotas que recomiendan la plataforma a su veterinario de confianza).</td>
    <td valign="top">Campañas en Google Ads, presencia en grupos de Facebook de veterinarios y un fuerte enfoque en el marketing de contenidos (blogs y webinars sobre gestión).</td>
    <td valign="top">Fuerte presencia institucional en congresos veterinarios internacionales, alianzas con colegios veterinarios, y una fuerza de ventas consultiva (B2B) para grandes cuentas.</td>
    <td valign="top">Herramientas integradas para enviar campañas, promociones y recordatorios automáticos sin esfuerzo manual. Utilizan anuncios diversos de Google Ads.</td>
  </tr>
  <tr>
    <td rowspan="3" valign="top">Perfil de Producto</td>
    <td valign="top">Productos & Servicios</td>
    <td valign="top">Historial clínico digital, agenda de citas, gestión de insumos médicos, portal web para el dueño de la mascota y registro de credenciales del personal médico.</td>
    <td valign="top">Historias clínicas, agenda, recordatorios automáticos por WhatsApp/Email, control de caja e inventario básico.</td>
    <td valign="top">Historias clínicas avanzadas, integración directa con equipos de laboratorio, módulo de hospitalización, planes de salud, compras/stock inteligente y gestión de salas de espera.</td>
    <td valign="top">Gestión de turnos, historias clínicas electrónicas, telemedicina, recetas electrónicas, informes personalizados y gestión de salud de rebaños en un solo click.</td>
  </tr>
  <tr>
    <td valign="top">Precios & Costos</td>
    <td valign="top">Anual: Desde $60 USD hasta $360 USD. Mensual: plan escalonado de $5, $15, $30 USD.</td>
    <td valign="top">Anual: Desde $240 USD hasta $480 USD. Mensual: Desde $20 a $40 USD dependiendo del país y funciones.</td>
    <td valign="top">Anual: Desde $600 USD hasta cotizaciones personalizadas elevadas para grupos de clínicas. Mensual: Desde $50 USD a $100+ USD mensuales, dependiendo fuertemente de los módulos adicionales contratados.</td>
    <td valign="top">Plan Core: Desde $249/mes incluye 1 veterinarios; personal de apoyo ilimitado gratuito. Plan Pro Desde $299/mes para clínicas con múltiples sedes.</td>
  </tr>
  <tr>
    <td valign="top">Canales de distribución (Web y/o Móvil)</td>
    <td valign="top">Plataforma web responsiva (SaaS) accesible desde navegadores en PC o móvil, sin necesidad de instalación.</td>
    <td valign="top">100% Software como Servicio (SaaS) accesible vía navegador web</td>
    <td valign="top">Despliegue en la nube (SaaS Cloud) o en servidor local, distribuido a través de asesores de ventas corporativos con procesos de implementación guiada.</td>
    <td valign="top">100% Web (SaaS) accesible desde cualquier navegador (PC, Mac, tablets) y App móvil para dueños de mascotas.</td>
  </tr>
  <tr>
    <td rowspan="4" valign="top">Análisis SWOT</td>
    <td valign="top">Fortalezas</td>
    <td valign="top">Enfoque dual que empodera al dueño de la mascota. Precios altamente accesibles. Interfaz moderna y sin curva de aprendizaje pronunciada.</td>
    <td valign="top">Muy posicionado en el mercado hispanohablante. Simple y directo al grano para tareas diarias.</td>
    <td valign="top">Altamente funcional y personalizable. Cuenta con control exhaustivo de inventario e integraciones con casi cualquier equipo médico de laboratorio.</td>
    <td valign="top">Alta capacidad de integración (+150 herramientas) y API abierta. Seguridad de datos con 5 capas de producción. Asistente de IA nativo para reducir la carga administrativa del médico.</td>
  </tr>
  <tr>
    <td valign="top">Debilidades</td>
    <td valign="top">Al ser una startup nueva, la notoriedad de marca es baja inicialmente. Dependencia de que ambos usuarios (clínica y dueño) adopten la plataforma para generar el valor completo.</td>
    <td valign="top">Interfaz un poco anticuada. Carece de funciones avanzadas para clínicas que crecen rápidamente y abren nuevas sedes.</td>
    <td valign="top">Al tener tantas opciones y módulos, la interfaz puede resultar abrumadora y la curva de aprendizaje es larga para el personal nuevo.</td>
    <td valign="top">Costo inicial más elevado que las soluciones locales básicas.</td>
  </tr>
  <tr>
    <td valign="top">Oportunidades</td>
    <td valign="top">La nueva generación de dueños de mascotas exige transparencia digital. Oportunidad de crear alianzas con proveedores de alimentos y medicinas.</td>
    <td valign="top">Expansión de sus integraciones con métodos de pago locales en diferentes países de Latinoamérica.</td>
    <td valign="top">Aprovechar su inmensa base de datos clínica para ofrecer analíticas predictivas y expandir versiones "Lite" a consultorios más pequeños.</td>
    <td valign="top">Creciente demanda en telemedicina y comunicación “mobile-first” en dueños de mascotas jóvenes.</td>
  </tr>
  <tr>
    <td valign="top">Amenazas</td>
    <td valign="top">Resistencia al cambio tecnológico por parte de veterinarios. Que los sistemas consolidados (como SmartVet) bajen sus precios.</td>
    <td valign="top">La aparición de startups más ágiles con mejores diseños y modelos de precios más agresivos (como PetHealth).</td>
    <td valign="top">Startups modernas con interfaces más limpias y amigables que resulten más atractivas para las nuevas generaciones de veterinarios.</td>
    <td valign="top">Inestabilidad de conexiones a internet en zonas rurales, lo que afecta a sistemas 100% nube. Surgimiento de startups locales con precios más bajos y soporte presencial en la región.</td>
  </tr>
  <tr>
</table>

---

### 2.1.2. Estrategias y tácticas frente a competidores

#### Estrategias:

- Posicionar a PetHealth como una solución moderna, accesible e intuitiva, diseñada específicamente para las clínicas veterinarias pequeñas y medianas en Perú, a diferencia de los sistemas ERP corporativos complejos y costosos (como Qvet) o plataformas con interfaces anticuadas (como SmartVet).
- Enfocarse en la funcionalidad única del modelo dual (B2B2C) que conecta al veterinario directamente con el dueño de la mascota a través de una "Libreta Sanitaria Digital", transformando el software de una simple herramienta administrativa a un canal de fidelización y marketing para la clínica.
- Ofrecer un modelo de suscripción SaaS escalonado con un plan básico de muy bajo costo ($5 USD), lo cual elimina el riesgo financiero para los emprendedores que buscan dejar el papel, haciéndolo mucho más atractivo que los competidores premium.
- Posicionar a PetHealth como una alternativa "Lite" y veloz frente a la complejidad de otras aplicaciones (como Provet Cloud). Mientras que otros requieren una curva de aprendizaje alta debido a sus múltiples módulos hospitalarios y de IA, PetHealth elimina la fricción operativa ofreciendo una interfaz web 100% responsive, optimizada para procesos de consulta rápida en clínicas medianas, garantizando que el personal médico no pierda tiempo en menús complejos.

#### Tácticas:

- Desarrollar un proceso de onboarding (registro inicial) autogestionable de menos de 10 minutos y tutoriales interactivos dentro de la plataforma para facilitar la rápida adopción por parte del personal veterinario con baja familiaridad tecnológica.
- Implementar campañas de educación y marketing en redes sociales (Instagram, TikTok, Facebook) dirigidas a los dueños de mascotas ("Pet Parents") para que sean ellos quienes exijan historiales clínicos transparentes y recomienden PetHealth a sus veterinarios.
- Establecer alianzas estratégicas con proveedores de insumos médicos, marcas de alimentos para mascotas y colegios veterinarios para llegar a un gran número de clínicas de manera directa y generar confianza institucional.
- Crear una calculadora interactiva (ROI) dentro de la Landing Page que le muestre a los dueños de las clínicas el ahorro de tiempo, la reducción de inasistencias (gracias a los recordatorios) y el aumento de ganancias que obtendrán al usar PetHealth versus sus métodos manuales actuales


---

## 2.2. Entrevistas

Esta sección expone la investigación basada en entrevistas realizadas a médicos veterinarios (incluyendo administradores de clínicas) y dueños de mascotas, segmentos clave del proyecto. A través de sus testimonios se buscó identificar las principales dificultades en la gestión clínica, administrativa y en el seguimiento de la salud animal, para explorar cómo una solución digital integral podría responder de manera efectiva a sus necesidades

### 2.2.1. Diseño de entrevistas

Las entrevistas fueron diseñadas aplicando buenas prácticas de investigación cualitativa, estructurando las preguntas de lo general a lo específico. El objetivo principal es recolectar información demográfica, psicográfica, conductual y tecnológica de los entrevistados. Estos datos son fundamentales para construir posteriormente nuestros arquetipos (User Personas), identificando su biografía, dispositivos de preferencia, influencias, metas y puntos de dolor respecto a la gestión de salud veterinaria.

**Segmento 1: Médicos Veterinarios y Administradores de Clínicas**

**A. Información Demográfica y Antecedentes**

- ¿Podría indicarnos su edad, en qué distrito reside y cuál es su estado civil o composición familiar actual?

- ¿Cuál es su cargo exacto en la clínica y cuántos años de experiencia tiene en el rubro veterinario?

- ¿Cómo describiría su personalidad en su entorno de trabajo? (Ej. metódico, tradicional, innovador, acelerado).

**B. Objetivos y Frustraciones**

- ¿Cuáles son sus objetivos profesionales principales para su clínica este año y qué es lo que más le impide lograrlos actualmente?

- Pensando en la gestión diaria (citas, historias clínicas, inventario), ¿cuál es la tarea que considera más tediosa, desordenada o propensa a errores?

- ¿Cómo le afecta a nivel personal (estrés, falta de tiempo libre) el no tener la información de sus pacientes o el stock de insumos centralizados?

**C. Tecnología y Canales de Interacción**

- ¿Qué dispositivos utiliza con mayor frecuencia en su día a día (Smartphone, Laptop) tanto para su vida personal como para la clínica?

- ¿Qué tan hábil se considera aprendiendo a usar nuevos programas y cuáles son sus redes sociales favoritas para informarse o interactuar con colegas?

- ¿Hay alguna marca, empresa o figura pública dentro del rubro veterinario o tecnológico que considere un referente o influencia?

**D. Comportamiento frente a la solución**

Si existiera una herramienta integral que le permitiera gestionar la clínica y fidelizar a sus clientes, ¿qué funciones serían indispensables para que usted decida implementarla?

---

**Segmento 2: Dueños de Mascotas (Pet Parents)**

**A. Información Demográfica y Antecedentes**

- ¿Podría indicarnos su edad, ocupación actual, en qué distrito reside y con quiénes vive actualmente?

- Hábleme de su mascota: ¿Qué especie es, cuántos años tiene y cómo llegó a su vida?

- ¿Cómo describiría su personalidad como dueño de mascota? (Ej. sobreprotector, relajado, muy organizado con sus cosas).

**B. Objetivos y Frustraciones**

- ¿Cuál es su objetivo principal respecto a la salud de su mascota y qué es lo que más le genera estrés cuando tiene que llevarla al veterinario?

- ¿Cómo se organiza para recordar sus vacunas, citas o encontrar su historial médico si tiene que ir a una clínica nueva?

- ¿Alguna vez ha olvidado una indicación médica importante o ha perdido una receta física? ¿Cómo resolvió esa situación?

**C. Tecnología y Canales de Interacción**

- ¿Qué dispositivos tecnológicos utiliza principalmente en su rutina y cuáles son las aplicaciones o redes sociales donde pasa más tiempo?

- Cuando compra productos para su mascota (comida, accesorios), ¿qué marcas suele preferir y por qué confía en ellas?

- ¿Sigue a algún influencer de mascotas, veterinario en redes sociales o blog que influya en la manera en que cuida a su animal?

**D. Comportamiento frente a la solución**

- Si existiera una plataforma web donde pudiera ver todo el historial de su mascota, recibir recordatorios y agendar citas desde su celular, ¿qué características harían que la use constantemente?

---

### 2.2.2. Registro de entrevistas
<div align="center">
  
**Segmento objetivo 1: `Personal de clínico de centros veterinarios`**

<br>

#### Entrevista 1
*Imagen de la entrevista*

<img src="pawtient-report/assets/images/Entrevista/valeria.png" alt="Screenshot Entrevista 1" width="500"/>

<br>

| Campo | Detalle                                                                                                                                                                                                                                                                                                                                                       |
|:------|:--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Nombres y apellidos** | Valeria Nomberto                                                                                                                                                                                                                                                                                                                                              |
| **Edad** | 23                                                                                                                                                                                                                                                                                                                                                            |
| **Ubicación** | Lince                                                                                                                                                                                                                                                                                                                                                         |
| **Fecha de entrevista** | 21-04-2026                                                                                                                                                                                                                                                                                                                                                    |
| **Duración** | 05:59 min                                                                                                                                                                                                                                                                                                                                                     |
| **Enlace al video** | [Ver entrevista en Microsoft Stream](https://upcedupe-my.sharepoint.com/:v:/g/personal/u202315007_upc_edu_pe/IQAz3Em-fhe6R7-5goCWq0-YAWzVewgdUXIBFNEKZiFuhOE?e=kimAI5&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D) |

**Resumen:**

</div>

Valeria es una médica veterinaria de 23 años que trabaja en el distrito de Lince, Lima. Se define como una profesional responsable, empática y muy organizada, con aproximadamente dos años de experiencia en el sector. Su principal meta para este año es digitalizar los procesos de su clínica para mejorar la fidelización de los clientes y optimizar la gestión interna. Actualmente, su mayor dificultad es el desorden y la dispersión de las historias clínicas físicas, lo que le genera estrés y le resta tiempo libre. Por ello, busca una herramienta que centralice la gestión de citas, inventarios e historiales médicos en una plataforma accesible desde el celular.

<br>
<div align="center">
  
#### Entrevista 2
*Imagen de la entrevista*

<img src="pawtient-report/assets/images/Entrevista/Adrian.png" alt="Screenshot Entrevista 1" width="500"/>

<br>

| Campo | Detalle                                                     |
|:------|:------------------------------------------------------------|
| **Nombres y apellidos** | Adrian                                                      |
| **Edad** | 35                                                          |
| **Ubicación** | Miraflores                                                  |
| **Fecha de entrevista** | 22-04-2026                                                  |
| **Duración** | 05:44 min                                                   |
| **Enlace al video** | [Ver entrevista en Microsoft Stream](https://upcedupe-my.sharepoint.com/:v:/g/personal/u202315007_upc_edu_pe/IQBBtDDT9R0bQpGUDj6Uw9XeAbjQ6oExcvphcoKBd82sQ7o?e=80gFgA&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D) |

**Resumen:**

</div>

Adrián es un médico veterinario de 35 años residente en Miraflores con una década de experiencia profesional, quien se define como una persona metódica y responsable que busca optimizar la gestión interna y la fidelización de clientes en su clínica. Su mayor desafío es el estrés provocado por la gestión manual de citas y el uso de historias clínicas en papel o Excel, lo que le genera errores y le impide desconectarse totalmente del trabajo, por lo cual considera fundamental implementar una agenda digital automatizada y un control de inventarios en tiempo real que facilite su labor diaria y mejore la comunicación con los dueños de las mascotas.

<br>
<div align="center">
  
#### Entrevista 3

*Imagen de la entrevista*

<img src="pawtient-report/assets/images/Entrevista/Luciana.png" alt="Screenshot Entrevista 1" width="500"/>

<br>

| Campo | Detalle                                                      |
|:------|:-------------------------------------------------------------|
| **Nombres y apellidos** | Luciana Quintana                                             |
| **Edad** | 28                                                           |
| **Ubicación** | Surco                                                        |
| **Fecha de entrevista** | 22-04-2026                                                   |
| **Duración** | 05:18 min                                                     |
| **Enlace al video** | [Ver entrevista en Microsoft Stream](https://upcedupe-my.sharepoint.com/:v:/g/personal/u202315007_upc_edu_pe/IQCMlNh3l3N6TZPQPy1mHg6RAVOCx3wuJoNC11qLxFvlMrY?e=4XiPy9&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D) |

**Resumen:**

</div>

Luciana es una veterinaria y administradora de 28 años que reside en Surco y cuenta con tres años de experiencia, desempeñando un rol multifuncional donde su perfil organizado choca frecuentemente con la falta de tiempo y el desorden en los procesos internos. Para ella, el manejo de información no centralizada y la necesidad de resolver temas administrativos fuera del horario laboral representan su principal fuente de estrés, por lo que aspira a que la clínica crezca mediante una herramienta integral que digitalice las historias médicas y automatice los recordatorios mediante dispositivos móviles, permitiéndole ser más práctica y elevar la calidad del servicio.

---
<div align="center">
  
**Segmento objetivo 2: `Dueños de mascotas`**

<br>

#### Entrevista 1

*Imagen de la entrevista*

<img src="pawtient-report/assets/images/Entrevista/Pierina.png" alt="Screenshot Entrevista 1" width="500"/>

<br>

| Campo | Detalle                                                     |
|:------|:------------------------------------------------------------|
| **Nombres y apellidos** | Pierina                                                     |
| **Edad** | 29                                                          |
| **Ubicación** | Surco                                                       |
| **Fecha de entrevista** | 20-04-2026                                                  |
| **Duración** | 07:57 min                                                   |
| **Enlace al video** | [Ver entrevista en Microsoft Stream](https://upcedupe-my.sharepoint.com/:v:/g/personal/u202315007_upc_edu_pe/IQAFfPb10NeoRrgpyDAsrwO9AV0mvrXDNFWqMpHT4T8IZZ4?e=LIlQpN&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D) |

**Resumen:**

</div>

Pierina es una estudiante de Ingeniería de Software de 19 años que vive en San Juan de Lurigancho y tiene dos perros de raza pequeña de cuatro años, adoptados de la camada de un familiar. Se considera una dueña sobreprotectora y su principal objetivo es mantener a sus mascotas saludables y libres de parásitos, especialmente por la presencia de perros callejeros en su zona. Le genera preocupación llevarlos al veterinario por posibles malos tratos y tiene dificultades para organizar el historial médico y las vacunas, ya que utiliza una cartilla física que puede perderse o no siempre está disponible. Utiliza TikTok e Instagram para buscar recomendaciones y sigue a veterinarios en redes sociales. Además, señala que usaría una plataforma digital si le permitiera organizar el historial médico, recibir recordatorios de vacunas, agendar citas y ver reseñas de veterinarias.
<br>

<div align="center">
  
#### Entrevista 2

*Imagen de la entrevista*

<img src="pawtient-report/assets/images/Entrevista/Mauricio.png" alt="Screenshot Entrevista 1" width="500"/>

<br>

| Campo | Detalle                                                     |
|:------|:------------------------------------------------------------|
| **Nombres y apellidos** | Mauricio Canchis                                            |
| **Edad** | 29                                                          |
| **Ubicación** | Surco                                                       |
| **Fecha de entrevista** | 18-04-2026                                                  |
| **Duración** | 08:42 min                                                   |
| **Enlace al video** | [Ver entrevista en Microsoft Stream](https://upcedupe-my.sharepoint.com/:v:/g/personal/u202315007_upc_edu_pe/IQDpOEyAXDKrSabjI835Bo8_AaRMpQ-XQfXEVC77FQGQYfo?e=vnulnX&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D) |

**Resumen:**

</div>

Mauricio es un estudiante universitario de 29 años que reside en Surco y es dueño de un perro pequeño. Debido a su pesada carga académica y a que posee una memoria que él mismo describe como "frágil", le resulta complicado mantenerse al día con los cuidados de su mascota. Su principal frustración es el tiempo que consume ir al veterinario y la dificultad para recordar las fechas de vacunación o citas médicas. Es un usuario intensivo de smartphone y WhatsApp, y admite que no recuerda nombres de marcas, sino que compra productos guiándose por el reconocimiento visual de los colores del empaque. Para él, lo más valioso de una plataforma digital sería recibir notificaciones y recordatorios automáticos que le quiten la preocupación de olvidar los eventos de salud de su perro.

<br>

<div align="center">

#### Entrevista 3

*Imagen de la entrevista*

<img src="pawtient-report/assets/images/Entrevista/Jorge.png" alt="Screenshot Entrevista 1" width="500"/>

<br>

| Campo | Detalle                                                      |
|:------|:-------------------------------------------------------------|
| **Nombres y apellidos** | Jorge                                                        |
| **Edad** | 20                                                           |
| **Ubicación** | La Victoria                                                  |
| **Fecha de entrevista** | 21-04-2026                                                   |
| **Duración** | 06:16 min                                                    |
| **Enlace al video** | [Ver entrevista en Microsoft Stream](https://upcedupe-my.sharepoint.com/:v:/g/personal/u202315007_upc_edu_pe/IQACXesV91lmRpPN6yBDOZ3EAa3Z8Y0G0-DjIC18S1qX8jk?e=1VGFIk&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D) |

**Resumen:**

</div>

Jorge es un estudiante universitario de 20 años que vive en La Victoria junto a su hermano y tiene un perro Golden Retriever de 6 años que llegó como regalo. Se considera un dueño equilibrado entre relajado y sobreprotector, y su principal objetivo es brindarle calidad de vida a su mascota. Le genera estrés llevarlo al veterinario porque su perro le tiene miedo y porque a veces detecta problemas tarde, lo que aumenta los costos. Ha perdido indicaciones médicas anteriormente y ha tenido que volver al veterinario. Utiliza principalmente su celular y computadora, y aplicaciones como Instagram, WhatsApp y Google Calendar. Prefiere marcas de comida recomendadas como Pro Plan y sigue consejos de veterinarios en redes sociales. Además, usaría una plataforma digital si incluyera historial médico, recordatorios y recomendaciones para el cuidado de su mascota.

---

### 2.2.3. Análisis de entrevistas

**Segmento objetivo 1: `Personal de clínico de centros veterinarios`**

Tras analizar las entrevistas realizadas a los profesionales del sector veterinario, se han identificado las siguientes características objetivas y subjetivas, las cuales servirán de base para la construcción de nuestro User Persona:


* **Perfil Demográfico (Características objetivas):** El 100% de los entrevistados son profesionales activos (médicos veterinarios y administradores) con edades comprendidas entre los 23 y 35 años, operando en diversos distritos de Lima Metropolitana. El 100% cuenta con experiencia laboral previa en el rubro, variando entre 2 y 10 años.


* **Perfil Psicológico y Conductual (Características subjetivas):** El 100% de la muestra se autodefine con rasgos de personalidad orientados al orden (organizados, metódicos y responsables). A nivel de metas profesionales, el 100% tiene como objetivo principal optimizar la gestión interna de sus clínicas para mejorar la calidad del servicio y fidelizar a sus clientes.


* **Puntos de Dolor (Pain Points):** Existe una coincidencia absoluta; el 100% de los profesionales reporta altos niveles de estrés derivados de la gestión manual y desordenada de la información (uso de historias clínicas en papel o Excel y agendas manuales). Asimismo, el 100% manifiesta que esta ineficiencia operativa invade su vida personal, obligándolos a realizar labores administrativas fuera de su horario y dificultando su desconexión del trabajo.


* **Necesidades y Soluciones Esperadas:** El 100% de los entrevistados expresa la necesidad urgente de una transformación digital. Buscan una herramienta tecnológica integral, con accesibilidad móvil (mencionada explícitamente), que les permita centralizar tres pilares fundamentales: historias clínicas, agendamiento de citas y control de inventarios en tiempo real.


**Segmento objetivo 2: `Dueños de mascotas`**

El análisis de las entrevistas a los dueños de mascotas revela patrones de comportamiento muy marcados respecto a la responsabilidad y la gestión del tiempo, delineando el siguiente perfil para el arquetipo:


* **Perfil Demográfico (Características objetivas):** El 100% de los entrevistados son jóvenes adultos y estudiantes universitarios (rango de 19 a 29 años) residentes en Lima. El 100% son dueños de perros y son usuarios intensivos de dispositivos móviles (smartphones) y plataformas digitales (Instagram, WhatsApp, TikTok).


* **Perfil Psicológico y Conductual (Características subjetivas):** El 100% tiene como prioridad fundamental garantizar la salud, prevención (libre de parásitos) y calidad de vida de sus mascotas. A nivel de personalidad frente a su mascota, el 66.7% (2 de 3) se autodenomina con tendencias "sobreprotectoras". Además, el 100% lleva un ritmo de vida acelerado y con alta carga de responsabilidades académicas.


* **Puntos de Dolor (Pain Points):** El 100% de la muestra experimenta frustración y dificultades severas para organizar la información médica de sus mascotas. Manifiestan problemas de "memoria frágil", pérdida de indicaciones médicas y extravío de cartillas físicas de vacunación. Adicionalmente, el 66.7% asocia la visita al veterinario con experiencias de estrés, ya sea por el tiempo que consume o por el miedo que experimentan sus mascotas.


* **Necesidades y Soluciones Esperadas:** El 100% de los dueños afirma que utilizaría activamente una plataforma digital si esta resuelve su problema de memoria y organización. Su necesidad principal, exigida por el 100% de la muestra, es un sistema que envíe notificaciones y recordatorios automáticos (vacunas, citas) y que digitalice el historial médico para tenerlo siempre disponible en el celular.

---

## 2.3. Needfinding

### 2.3.1. User Personas

Los siguientes User Personas se elaboraron a partir de las entrevistas realizadas a dueños y administradores de clínicas veterinarias, así como a veterinarios independientes. Cada uno representa características, comportamientos y necesidades clave que permiten orientar el diseño y la propuesta de valor de la plataforma Pawtient.

User Persona 1: Dueños y administradores de clínicas veterinarias

Camila Ramírez de 32 años es dueña y administradora de una clínica veterinaria en Santiago de Surco. En su día a día debe coordinar citas, controlar inventarios y supervisar la información clínica de sus pacientes, por lo que busca soluciones digitales que le permitan mantener una gestión más organizada, rápida y eficiente.

![User Persona 1](pawtient-report/assets/images/user-personas/user-persona-1.png)

User Persona 2: Veterinarios independientes

Diego Torres es un médico veterinario independiente que atiende consultas y realiza seguimiento de pacientes en distintos puntos de Santiago de Surco. Su principal desafío es mantener organizada la información clínica y gestionar sus citas de manera eficiente, por lo que busca herramientas digitales prácticas que le permitan optimizar su trabajo diario y enfocarse más en la atención de sus pacientes.

![User Persona 1](pawtient-report/assets/images/user-personas/user-persona-2.png)

---

### 2.3.2. User Task Matrix

##### User Task Matrix - Dueños y administradores de clínicas veterinarias

| **Tareas / Tasks**                   | **Frecuencia** | **Importancia** |
|--------------------------------------|----------------|-----------------|
| Gestionar historiales clínicos         | Alta           | Muy alta        |
| Organizar citas veterinarias   | Alta           | Muy alta        |
| Controlar inventario de insumos                     | Alta           | Alta            |
| Supervisar procesos operativos     | Alta           | Muy alta        |
| Consultar información de pacientes     | Alta           | Muy alta        |
| Coordinar atención del personal         | Media          | Alta            |
| Revisar reportes y registros       | Media          | Alta            |
| Gestionar información administrativa | Alta           | Muy alta        |
| Dar seguimiento a tratamientos  | Media          | Alta            |

Los dueños y administradores de clínicas veterinarias realizan tareas enfocadas en la organización operativa, control de información clínica y supervisión de procesos internos. Esto evidencia la necesidad de una plataforma que centralice datos y optimice la gestión diaria del centro veterinario.

##### User Task Matrix - Veterinarios independientes

| **Tareas / Tasks**                          | **Frecuencia** | **Importancia** |
|---------------------------------------------|----------------|-----------------|
| Registrar consultas veterinarias         | Alta           | Muy alta        |
| Consultar historiales clínicos           | Alta           | Muy alta        |
| Gestionar citas y tratamientos | Alta           | Alta            |
| Realizar seguimiento de pacientes              | Media          | Alta            |
| Acceder a información clínica móvil  | Alta           | Muy alta        |
| Organizar registros médicos    | Alta           | Alta            |
| Comunicar indicaciones médicas          | Alta           | Alta            |
| Gestionar tiempos de atención           | Media          | Alta            |
| Revisar información de pacientes      | Alta           | Muy alta        |

Los veterinarios independientes desarrollan tareas relacionadas con la atención clínica, el seguimiento de pacientes y la gestión de información médica en distintos entornos de trabajo. Esto refleja la necesidad de herramientas digitales accesibles que faciliten la organización y agilicen sus actividades diarias.

---

### 2.3.3. User Journey Mapping

En el desarrollo de Pawtient, se elaboró un User Journey Mapping con el objetivo de comprender cómo interactúan los dueños y administradores de clínicas veterinarias, así como los veterinarios independientes, dentro de sus procesos de atención y gestión diaria. Se analizaron las distintas etapas relacionadas con la organización de consultas, manejo de historiales clínicos, control de insumos y seguimiento de pacientes, identificando problemas y oportunidades de mejora. Este análisis permitió proponer una solución que se integra de manera práctica en sus actividades diarias, optimizando la gestión de la información y mejorando la eficiencia de los procesos veterinarios.

**User Journey Map — Dueños y administradores de clínicas veterinarias**

<img alt= "User Journey Mapping Dueños y administradores de clínicas veterinarias" src="https://raw.githubusercontent.com/PetHealt/Pawtient-report/refs/heads/feature/sprint2-emily/pawtient-report/assets/images/Journey%20Mapping/Journey-mapping-1.png">

[Ver Imagen](https://raw.githubusercontent.com/PetHealt/Pawtient-report/refs/heads/feature/sprint2-emily/pawtient-report/assets/images/Journey%20Mapping/Journey-mapping-1.png)

---

**User Journey Map — Veterinarios independientes**

<img alt= "User Journey Mapping Veterinarios independientes" src="https://raw.githubusercontent.com/PetHealt/Pawtient-report/refs/heads/feature/sprint2-emily/pawtient-report/assets/images/Journey%20Mapping/Journey-mapping-2.png">

[Ver Imagen](https://raw.githubusercontent.com/PetHealt/Pawtient-report/refs/heads/feature/sprint2-emily/pawtient-report/assets/images/Journey%20Mapping/Journey-mapping-2.png)

---

### 2.3.4. Empathy Mapping

En esta sección se presentarán los Empathy Maps de cada segmento objetivo, construidos a partir de los User Persona previamente definidos. Esta herramienta permite analizar de forma integral lo que los usuarios piensan, sienten, dicen y hacen, facilitando la identificación de sus necesidades, frustraciones y motivaciones. De esta manera, se obtienen insights clave que orientan el diseño de la solución propuesta.

**Empathy Map — Dueños y administradores de clínicas veterinarias**

<img alt= "Empathy mapping Dueños y administradores de clínicas veterinarias" src="">

[Ver Imagen]()

---

**Empathy Map — Veterinarios independientes**

<img alt= "Empathy mapping veterinarios independientes" src="">

[Ver Imagen]()

---

## 2.4. Big Picture Event Storming

En esta sección se introduce y resume el proceso realizado por el equipo para el Big Picture Event Storming, que fue realizado mediante una llamada en discord y plasmado con la ayuda de la herramienta Miro. A continuación, se explica el proceso:

**1. OPEN**

En esta etapa el equipo se concentró en generar la mayor cantidad de eventos de dominio posibles (cosas que suceden en el negocio) escribiendo en los post-its naranjas.

![Open](pawtient-report/assets/images/Big-Picture-Event-Storming/open.png)

**2. Explore**

Después de la anterior etapa, en esta se concentró en ordenar cronológicamente los eventos, eliminar los eventos repetidos, identificar sus actores y posibles sistemas externos, y finalmente algunos puntos de dolor en post-its morados.

![Explore](pawtient-report/assets/images/Big-Picture-Event-Storming/Explore.png)

**3. Close**

En esta última etapa, se documentaron en post-its rosados los problemas más relevantes detectados, junto con aspectos que debíamos investigar más a fondo o descartar según el alcance definido.

![Close](pawtient-report/assets/images/Big-Picture-Event-Storming/Close.png)

Luego de conversar un poco, el equipo descartó algunos eventos y identificó mejor un sistema externo:

![Big Picture Final](pawtient-report/assets/images/Big-Picture-Event-Storming/Big-picture-event-storming.png)

[Ver en miro](https://miro.com/welcomeonboard/TUM0Kzk0ajRxOXdpd1EzRXpwQjU1ckx6c3JPV2trSUxpQ2dLc0p6RFZjUEFwaXYvcHpOMTZGWHExOFpibXpLRHNURWF6Zko2b1NaM2FxTEJieCsvUElhMFUwdXIwNThuaWpBa3F4dzlXUklLaXA4dFFvZUY1VjRHVXhGcklxT3BNakdSWkpBejJWRjJhRnhhb1UwcS9BPT0hdjE=?share_link_id=798329479919)


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
| US01 | Registrar cuenta como veterinario | Como veterinario, quiero crear una cuenta en Pawtient con mis datos profesionales para acceder a las funcionalidades del sistema de gestión clínica. | **Escenario 1 – Registro exitoso:** <br> **Given** que el veterinario completa todos los campos obligatorios (nombre, apellido, correo, contraseña y número de colegiatura), <br> **When** envía el formulario de registro, <br> **Then** el sistema crea la cuenta, envía un correo de verificación y muestra un mensaje de confirmación. <br><br> **Escenario 2 – Correo ya registrado:** <br> **Given** que el veterinario ingresa un correo electrónico que ya existe en el sistema, <br> **When** envía el formulario, <br> **Then** el sistema muestra el mensaje "El correo ya está registrado" y no crea una cuenta duplicada. <br><br> **Escenario 3 – Contraseña débil:** <br> **Given** que el veterinario ingresa una contraseña que no cumple los requisitos mínimos de seguridad, <br> **When** envía el formulario, <br> **Then** el sistema resalta los requisitos incumplidos y no permite que el registro continúe. | EP01 |
| US02 | Iniciar sesión en la plataforma | Como usuario registrado (veterinario, administrador o dueño de mascota), quiero iniciar sesión con mis credenciales para acceder a las funcionalidades según mi rol. | **Escenario 1 – Inicio de sesión exitoso:** <br> **Given** que el usuario ingresa un correo y contraseña válidos, <br> **When** confirma el inicio de sesión, <br> **Then** el sistema autentica al usuario, genera un token de sesión y lo redirige al panel correspondiente a su rol. <br><br> **Escenario 2 – Credenciales incorrectas:** <br> **Given** que el usuario ingresa una contraseña incorrecta, <br> **When** intenta iniciar sesión, <br> **Then** el sistema muestra el mensaje "Credenciales inválidas" sin especificar cuál campo es incorrecto y deniega el acceso. <br><br> **Escenario 3 – Cuenta no verificada:** <br> **Given** que el usuario registrado no ha verificado su correo electrónico, <br> **When** intenta iniciar sesión, <br> **Then** el sistema informa que la cuenta requiere verificación y ofrece reenviar el correo de confirmación. | EP01 |
| US03 | Recuperar contraseña olvidada | Como usuario registrado, quiero recuperar el acceso a mi cuenta en caso de olvidar mi contraseña para no perder el acceso a la plataforma. | **Escenario 1 – Correo de recuperación enviado:** <br> **Given** que el usuario ingresa su correo registrado en el formulario de recuperación, <br> **When** confirma la solicitud, <br> **Then** el sistema envía un enlace de restablecimiento de contraseña válido por 30 minutos. <br><br> **Escenario 2 – Correo no registrado:** <br> **Given** que el usuario ingresa un correo que no existe en el sistema, <br> **When** confirma la solicitud, <br> **Then** el sistema muestra el mensaje genérico "Si el correo está registrado, recibirás un enlace" sin confirmar ni negar la existencia de la cuenta. <br><br> **Escenario 3 – Enlace expirado:** <br> **Given** que el usuario intenta usar un enlace de recuperación después de los 30 minutos de validez, <br> **When** accede al enlace, <br> **Then** el sistema indica que el enlace ha expirado y permite solicitar uno nuevo. | EP01 |
| **EP02** | **Gestión de Historiales Clínicos** | Centralizar los registros médicos de las mascotas en formato digital, eliminando el uso de historias en papel o Excel y permitiendo el acceso desde dispositivos móviles. | — | — |
| US04 | Registrar historia clínica de mascota | Como veterinario, quiero crear y guardar la historia clínica digital de una mascota para eliminar el uso de registros físicos y acceder a la información desde cualquier dispositivo. | **Escenario 1 – Registro exitoso:** <br> **Given** que el veterinario completa todos los campos obligatorios (nombre de mascota, especie, raza, peso, diagnóstico, tratamiento y fecha), <br> **When** confirma el guardado, <br> **Then** el sistema almacena el registro y muestra un mensaje de confirmación. <br><br> **Escenario 2 – Campos incompletos:** <br> **Given** que el veterinario intenta guardar una historia clínica con campos obligatorios vacíos, <br> **When** confirma el guardado, <br> **Then** el sistema resalta los campos faltantes y no permite continuar hasta completarlos. <br><br> **Escenario 3 – Acceso desde dispositivo móvil:** <br> **Given** que el veterinario accede al sistema desde un dispositivo móvil, <br> **When** crea o consulta una historia clínica, <br> **Then** el sistema muestra el formulario completo y funcional sin pérdida de campos ni funcionalidades. | EP02 |
| US05 | Consultar historial médico de una mascota | Como veterinario, quiero buscar y visualizar el historial completo de una mascota para tomar decisiones clínicas informadas durante la consulta. | **Escenario 1 – Búsqueda por nombre de mascota:** <br> **Given** que el veterinario ingresa el nombre de la mascota en el buscador del módulo de historiales, <br> **When** el sistema procesa la búsqueda, <br> **Then** muestra los registros coincidentes ordenados cronológicamente de forma descendente. <br><br> **Escenario 2 – Sin resultados:** <br> **Given** que el veterinario realiza una búsqueda, <br> **When** no existe ningún registro con ese nombre, <br> **Then** el sistema muestra el mensaje "No se encontraron registros" y ofrece la opción de crear uno nuevo. <br><br> **Escenario 3 – Visualización de vacunas aplicadas:** <br> **Given** que el veterinario abre el historial de una mascota, <br> **When** navega a la sección de vacunación, <br> **Then** el sistema lista todas las vacunas aplicadas con fecha de aplicación, número de lote y fecha de próxima dosis. | EP02 |
| US06 | Editar y actualizar historia clínica | Como veterinario, quiero actualizar la historia clínica de una mascota después de cada consulta para mantener la información vigente y con trazabilidad de cambios. | **Escenario 1 – Actualización exitosa:** <br> **Given** que el veterinario abre un registro existente y modifica el diagnóstico o tratamiento, <br> **When** guarda los cambios, <br> **Then** el sistema registra la actualización incluyendo la fecha, hora y nombre del usuario que realizó el cambio. <br><br> **Escenario 2 – Edición sin permisos:** <br> **Given** que un usuario sin rol de veterinario intenta editar una historia clínica, <br> **When** intenta acceder al modo de edición, <br> **Then** el sistema deniega la acción y muestra el mensaje "No tienes permisos para editar este registro". <br><br> **Escenario 3 – Historial de cambios visible:** <br> **Given** que el veterinario revisa una historia clínica, <br> **When** accede a la sección de trazabilidad, <br> **Then** el sistema muestra un registro cronológico de todas las modificaciones realizadas con nombre del autor y fecha. | EP02 |
| US07 | Registrar vacunas aplicadas | Como veterinario, quiero registrar cada vacuna aplicada durante una consulta vinculándola al historial de la mascota para mantener un calendario de vacunación actualizado. | **Escenario 1 – Registro de vacuna exitoso:** <br> **Given** que el veterinario completa los campos de vacunación (nombre de vacuna, lote, fecha de aplicación y próxima dosis), <br> **When** confirma el registro, <br> **Then** el sistema guarda la entrada y la añade al historial de vacunación de la mascota. <br><br> **Escenario 2 – Fecha de próxima dosis en el pasado:** <br> **Given** que el veterinario ingresa una fecha de próxima dosis anterior a la fecha actual, <br> **When** intenta guardar, <br> **Then** el sistema muestra una advertencia indicando que la fecha corresponde al pasado y solicita confirmación para continuar. <br><br> **Escenario 3 – Programación automática de recordatorio:** <br> **Given** que se registra una vacuna con fecha de próxima dosis, <br> **When** el sistema confirma el guardado, <br> **Then** programa automáticamente un recordatorio para notificar al dueño 7 días antes de la fecha indicada. | EP02 |
| **EP03** | **Programación y Gestión de Citas** | Digitalizar y automatizar la agenda de citas para reducir el estrés del personal clínico y mejorar la experiencia del dueño de mascota. | — | — |
| US08 | Agendar cita desde la clínica | Como veterinario, quiero registrar una nueva cita en el sistema para organizar la agenda diaria sin depender de llamadas manuales ni registros en papel. | **Escenario 1 – Cita registrada correctamente:** <br> **Given** que el veterinario selecciona fecha, hora, veterinario asignado y mascota del cliente, <br> **When** confirma el registro, <br> **Then** el sistema añade la cita al calendario y envía automáticamente una notificación al dueño de la mascota. <br><br> **Escenario 2 – Horario no disponible:** <br> **Given** que el veterinario selecciona un horario ya ocupado por el mismo profesional, <br> **When** intenta confirmar, <br> **Then** el sistema indica la no disponibilidad y sugiere los próximos horarios libres. <br><br> **Escenario 3 – Cita fuera del horario de atención:** <br> **Given** que el veterinario intenta registrar una cita fuera del horario configurado por la clínica, <br> **When** intenta confirmar, <br> **Then** el sistema muestra una advertencia indicando que el horario seleccionado está fuera del rango configurado. | EP03 |
| US09 | Agendar cita como dueño de mascota | Como dueño de mascota, quiero solicitar una cita veterinaria desde mi celular para evitar llamadas telefónicas y reducir el tiempo invertido en coordinar turnos. | **Escenario 1 – Solicitud enviada exitosamente:** <br> **Given** que el dueño selecciona una clínica, una de sus mascotas registradas y una fecha y hora disponibles, <br> **When** confirma la solicitud, <br> **Then** el sistema registra la cita y envía una confirmación mediante notificación push. <br><br> **Escenario 2 – Sin horarios disponibles en la fecha seleccionada:** <br> **Given** que el dueño selecciona una fecha en la que todos los horarios están ocupados, <br> **When** intenta avanzar, <br> **Then** el sistema muestra el mensaje "No hay horarios disponibles para esta fecha" y permite seleccionar otra. <br><br> **Escenario 3 – Cancelación con anticipación:** <br> **Given** que el dueño tiene una cita confirmada y la cancela con al menos 2 horas de anticipación, <br> **When** confirma la cancelación, <br> **Then** el sistema libera el horario, notifica a la clínica y elimina los recordatorios asociados. | EP03 |
| US10 | Visualizar agenda del día | Como veterinario, quiero ver un resumen de las citas programadas para el día en curso para organizar mi jornada de trabajo de forma eficiente. | **Escenario 1 – Visualización correcta de la agenda:** <br> **Given** que el veterinario accede al panel principal, <br> **When** selecciona la vista de agenda diaria, <br> **Then** el sistema lista todas las citas del día ordenadas por hora con nombre de mascota, dueño y motivo de consulta. <br><br> **Escenario 2 – Agenda vacía:** <br> **Given** que no existen citas programadas para el día en curso, <br> **When** el veterinario accede a la agenda, <br> **Then** el sistema muestra el mensaje "No hay citas programadas para hoy". <br><br> **Escenario 3 – Filtro por veterinario:** <br> **Given** que la clínica tiene múltiples veterinarios, <br> **When** el administrador aplica un filtro por un profesional específico, <br> **Then** el sistema muestra únicamente las citas asignadas a ese veterinario. | EP03 |
| US11 | Recibir recordatorios de citas | Como dueño de mascota, quiero recibir recordatorios automáticos antes de las citas de mi mascota para no olvidar los turnos médicos. | **Escenario 1 – Recordatorio 24 horas antes:** <br> **Given** que existe una cita confirmada, <br> **When** faltan 24 horas para la cita, <br> **Then** el sistema envía una notificación push al dueño con la fecha, hora, nombre de la clínica y veterinario asignado. <br><br> **Escenario 2 – Recordatorio 1 hora antes:** <br> **Given** que existe una cita confirmada, <br> **When** falta 1 hora para la cita, <br> **Then** el sistema envía un segundo recordatorio de confirmación al dueño. <br><br> **Escenario 3 – Recordatorios desactivados por el usuario:** <br> **Given** que el dueño ha desactivado los recordatorios de citas en su configuración, <br> **When** el sistema evalúa el envío de una alerta, <br> **Then** no envía ninguna notificación para ese tipo de evento. | EP03 |
| **EP04** | **Trazabilidad de Suministros e Inventario** | Proveer control en tiempo real del inventario de medicamentos e insumos para evitar faltantes, vencimientos y errores operativos en la clínica. | — | — |
| US12 | Registrar ingreso de suministros | Como administrador de clínica, quiero registrar el ingreso de nuevos suministros al inventario para mantener el stock actualizado en tiempo real. | **Escenario 1 – Ingreso registrado exitosamente:** <br> **Given** que el administrador completa los campos de nombre del producto, cantidad, unidad, fecha de vencimiento y proveedor, <br> **When** confirma el registro, <br> **Then** el sistema actualiza el stock y registra la transacción con fecha y usuario responsable. <br><br> **Escenario 2 – Producto ya existente en inventario:** <br> **Given** que el administrador registra un suministro con el mismo nombre que uno existente, <br> **When** confirma el ingreso, <br> **Then** el sistema suma la cantidad al stock existente sin crear un registro duplicado. <br><br> **Escenario 3 – Alerta de producto próximo a vencer:** <br> **Given** que un producto tiene fecha de vencimiento dentro de los próximos 30 días, <br> **When** el administrador lo registra, <br> **Then** el sistema genera una alerta visible en el panel principal indicando la proximidad del vencimiento. | EP04 |
| US13 | Consultar niveles de stock | Como veterinario, quiero consultar el nivel actual de un suministro para verificar disponibilidad antes de prescribir un tratamiento. | **Escenario 1 – Consulta exitosa:** <br> **Given** que el veterinario busca un suministro por nombre en el módulo de inventario, <br> **When** el producto existe, <br> **Then** el sistema muestra la cantidad disponible, la unidad de medida y la fecha de vencimiento más próxima. <br><br> **Escenario 2 – Stock mínimo alcanzado:** <br> **Given** que el stock de un suministro cae por debajo del nivel mínimo definido, <br> **When** el sistema realiza la verificación periódica, <br> **Then** genera una alerta y notifica al administrador de la clínica. <br><br> **Escenario 3 – Producto sin existencia:** <br> **Given** que el veterinario busca un suministro cuyo stock es cero, <br> **When** el sistema responde a la consulta, <br> **Then** muestra el mensaje "Sin stock disponible" junto con la fecha del último ingreso registrado. | EP04 |
| US14 | Registrar consumo de suministros por consulta | Como veterinario, quiero registrar los insumos utilizados durante una consulta para descontarlos automáticamente del inventario y mantener la trazabilidad de uso. | **Escenario 1 – Descuento automático de inventario:** <br> **Given** que el veterinario registra los insumos usados al cerrar una consulta, <br> **When** guarda el registro, <br> **Then** el sistema descuenta las cantidades del inventario y vincula la transacción al historial clínico de la mascota. <br><br> **Escenario 2 – Cantidad solicitada supera el stock disponible:** <br> **Given** que el veterinario intenta registrar una cantidad que supera el stock actual, <br> **When** intenta guardar, <br> **Then** el sistema muestra una alerta de stock insuficiente y no permite completar el registro hasta corregir la cantidad. <br><br> **Escenario 3 – Reporte de consumo mensual:** <br> **Given** que el administrador accede al módulo de reportes y selecciona el período mensual, <br> **When** genera el reporte, <br> **Then** el sistema presenta un detalle de consumo por insumo con cantidad total utilizada y costo estimado. | EP04 |
| US15 | Generar alertas de reabastecimiento | Como administrador de clínica, quiero recibir alertas automáticas cuando el stock de un suministro sea bajo para solicitar reposición con anticipación y evitar faltantes. | **Escenario 1 – Alerta generada automáticamente:** <br> **Given** que el stock de un suministro desciende al nivel mínimo configurado, <br> **When** el sistema procesa la transacción de descuento, <br> **Then** genera una alerta visible en el panel del administrador con el nombre del suministro y la cantidad actual. <br><br> **Escenario 2 – Configuración del nivel mínimo:** <br> **Given** que el administrador edita la ficha de un suministro e ingresa un nivel mínimo de stock, <br> **When** guarda la configuración, <br> **Then** el sistema utiliza ese valor como umbral para las futuras alertas de reabastecimiento. <br><br> **Escenario 3 – Alerta de vencimiento masivo:** <br> **Given** que varios suministros tienen fecha de vencimiento dentro de los próximos 15 días, <br> **When** el sistema ejecuta la revisión diaria, <br> **Then** agrupa las alertas en una sola notificación que lista todos los productos afectados. | EP04 |
| **EP05** | **Perfiles y Gestión de Mascotas** | Permitir a los dueños gestionar el perfil digital de sus mascotas con historial, vacunas y documentos accesibles desde el celular. | — | — |
| US16 | Crear perfil digital de mascota | Como dueño de mascota, quiero registrar el perfil de mi mascota en la plataforma para centralizar su información médica y acceder a ella en cualquier momento. | **Escenario 1 – Perfil creado exitosamente:** <br> **Given** que el dueño completa los campos de nombre, especie, raza, fecha de nacimiento y foto, <br> **When** confirma el registro, <br> **Then** el sistema crea el perfil y lo muestra en la sección "Mis mascotas" de la cuenta. <br><br> **Escenario 2 – Registro de múltiples mascotas:** <br> **Given** que el dueño desea registrar una segunda mascota, <br> **When** selecciona "Agregar mascota" y completa los datos, <br> **Then** el sistema crea un perfil independiente y lo lista junto a las mascotas previamente registradas. <br><br> **Escenario 3 – Historial visible desde el perfil:** <br> **Given** que el dueño abre el perfil de una mascota, <br> **When** navega a la sección de historial, <br> **Then** el sistema muestra todas las consultas anteriores ordenadas por fecha con diagnóstico y nombre del veterinario tratante. | EP05 |
| US17 | Compartir historial médico con una clínica | Como dueño de mascota, quiero compartir el historial de mi mascota con una nueva clínica para que el veterinario cuente con información previa relevante. | **Escenario 1 – Compartir mediante código temporal:** <br> **Given** que el dueño genera un código de acceso temporal desde el perfil de su mascota, <br> **When** el veterinario ingresa ese código en el sistema, <br> **Then** el sistema muestra el historial clínico completo durante el período de validez del código de 24 horas. <br><br> **Escenario 2 – Código expirado:** <br> **Given** que el veterinario intenta usar un código de acceso después de las 24 horas de validez, <br> **When** el sistema valida el código, <br> **Then** muestra el mensaje "Código expirado" y solicita al dueño generar uno nuevo. <br><br> **Escenario 3 – Acceso revocado por el dueño:** <br> **Given** que el dueño compartió el historial con una clínica, <br> **When** revoca el acceso desde su configuración, <br> **Then** el sistema invalida el código de forma inmediata y la clínica ya no puede visualizar el historial. | EP05 |
| US18 | Buscar clínicas veterinarias cercanas | Como dueño de mascota, quiero buscar clínicas veterinarias cercanas con sus reseñas y servicios para elegir el mejor lugar para atender a mi mascota. | **Escenario 1 – Búsqueda por ubicación exitosa:** <br> **Given** que el dueño activa la búsqueda de clínicas cercanas, <br> **When** el sistema detecta su ubicación, <br> **Then** muestra un listado de clínicas ordenadas por distancia con nombre, dirección, calificación y servicios disponibles. <br><br> **Escenario 2 – Sin clínicas en el área:** <br> **Given** que el sistema no encuentra clínicas dentro del radio de búsqueda predeterminado, <br> **When** presenta los resultados, <br> **Then** muestra el mensaje "No se encontraron clínicas en tu área" y ofrece ampliar el radio de búsqueda. <br><br> **Escenario 3 – Filtro por tipo de servicio:** <br> **Given** que el dueño aplica un filtro por tipo de servicio (ej. urgencias, vacunación, grooming), <br> **When** el sistema procesa el filtro, <br> **Then** muestra únicamente las clínicas que ofrecen ese servicio específico. | EP05 |
| **EP06** | **Notificaciones y Recordatorios Automatizados** | Automatizar el envío de alertas para vacunas, citas y cuidados preventivos tanto al equipo clínico como a los dueños de mascotas. | — | — |
| US19 | Recibir recordatorios de vacunación | Como dueño de mascota, quiero recibir alertas cuando la vacuna de mi mascota esté próxima para no perder el calendario de vacunación. | **Escenario 1 – Alerta 7 días antes de la fecha:** <br> **Given** que el calendario de vacunación tiene una dosis programada, <br> **When** faltan 7 días para la fecha de aplicación, <br> **Then** el sistema envía una notificación push al dueño con el nombre de la vacuna y un enlace para agendar la cita. <br><br> **Escenario 2 – Alerta el día de la vacuna:** <br> **Given** que es el día en que corresponde aplicar una vacuna programada, <br> **When** el sistema ejecuta la revisión diaria, <br> **Then** envía un recordatorio urgente al dueño indicando que la vacuna corresponde a ese día. <br><br> **Escenario 3 – Recordatorio cancelado tras aplicación:** <br> **Given** que la clínica registra la vacuna como aplicada, <br> **When** el sistema actualiza el historial clínico, <br> **Then** cancela todos los recordatorios pendientes de esa dosis y programa el siguiente según el esquema de dosis. | EP06 |
| US20 | Configurar preferencias de notificación | Como dueño de mascota, quiero personalizar el tipo y frecuencia de notificaciones que recibo para gestionar las alertas según mis necesidades. | **Escenario 1 – Configuración guardada exitosamente:** <br> **Given** que el dueño accede a los ajustes de notificaciones y selecciona los tipos de alerta deseados, <br> **When** guarda los cambios, <br> **Then** el sistema aplica las nuevas preferencias en todos los envíos posteriores. <br><br> **Escenario 2 – Todas las notificaciones desactivadas:** <br> **Given** que el dueño desactiva todas las notificaciones desde su configuración, <br> **When** el sistema intenta enviar cualquier alerta, <br> **Then** no realiza ningún envío hasta que las preferencias sean reactivadas manualmente. <br><br> **Escenario 3 – Configuración por defecto restaurada:** <br> **Given** que el dueño selecciona "Restaurar valores por defecto" en la configuración de notificaciones, <br> **When** el sistema procesa la acción, <br> **Then** habilita todas las categorías de notificación con las frecuencias estándar predefinidas. | EP06 |
| US21 | Recibir notificaciones de resultados y seguimiento | Como dueño de mascota, quiero recibir notificaciones cuando el veterinario actualice el estado de seguimiento de mi mascota para mantenerme informado después de cada consulta. | **Escenario 1 – Notificación de actualización de seguimiento:** <br> **Given** que el veterinario añade una nota de seguimiento al historial de una mascota, <br> **When** el sistema confirma el guardado, <br> **Then** envía una notificación push al dueño indicando que hay una actualización disponible en el perfil de su mascota. <br><br> **Escenario 2 – Notificación de resultados de examen:** <br> **Given** que el veterinario registra los resultados de un examen de laboratorio vinculado a una consulta, <br> **When** confirma el registro, <br> **Then** el sistema notifica al dueño que los resultados están disponibles para su revisión. <br><br> **Escenario 3 – Historial de notificaciones accesible:** <br> **Given** que el dueño desea revisar notificaciones previas, <br> **When** accede al centro de notificaciones, <br> **Then** el sistema muestra el historial de los últimos 30 días ordenado cronológicamente con estado de lectura. | EP06 |
| **EP07** | **Landing Page de Pawtient** | Presentar la propuesta de valor de Pawtient a los visitantes, diferenciando el mensaje por segmento y facilitando el registro o contacto con la plataforma. | — | — |
| US22 | Conocer la propuesta de valor como visitante de clínica veterinaria | Como visitante del segmento clínica veterinaria, quiero ver los beneficios del sistema en la landing page para evaluar si Pawtient se adapta a las necesidades de mi centro. | **Escenario 1 – Sección de beneficios visible:** <br> **Given** que el visitante accede a la landing page y navega a la sección dirigida a clínicas, <br> **When** la sección carga, <br> **Then** se visualizan al menos tres beneficios clave (gestión de historiales, agenda digital, control de inventario) con íconos y descripciones claras. <br><br> **Escenario 2 – Llamada a la acción funcional:** <br> **Given** que el visitante revisa la sección de clínicas, <br> **When** activa la opción "Solicitar demo" o "Registrar mi clínica", <br> **Then** el sistema lo lleva al formulario de registro sin recargar la página completa. <br><br> **Escenario 3 – Visualización en dispositivos móviles:** <br> **Given** que el visitante accede a la landing page desde un smartphone, <br> **When** navega por la sección de beneficios para clínicas, <br> **Then** el contenido se adapta correctamente a la pantalla sin desbordamientos ni pérdida de información. | EP07 |
| US23 | Conocer la propuesta de valor como visitante dueño de mascota | Como visitante del segmento dueño de mascota, quiero entender cómo Pawtient me ayuda a cuidar mejor a mi mascota para decidir si me registro en la plataforma. | **Escenario 1 – Sección para dueños visible:** <br> **Given** que el visitante llega a la landing page, <br> **When** navega hasta la sección dirigida a dueños de mascotas, <br> **Then** visualiza los beneficios principales (recordatorios de vacunas, historial digital, búsqueda de clínicas) con lenguaje accesible y no técnico. <br><br> **Escenario 2 – Testimonios visibles:** <br> **Given** que el visitante llega a la sección de testimonios, <br> **When** la página carga completamente, <br> **Then** se muestran al menos dos testimonios de dueños de mascotas con nombre, tipo de mascota y valoración. <br><br> **Escenario 3 – Registro desde la landing page:** <br> **Given** que el visitante revisa la sección de dueños y decide registrarse, <br> **When** activa el botón de registro, <br> **Then** el sistema lo redirige al formulario de creación de cuenta como dueño de mascota. | EP07 |
| US24 | Navegar entre secciones de la landing page | Como visitante de la landing page, quiero usar el menú de navegación para desplazarme rápidamente a cualquier sección y conocer todo el contenido disponible. | **Escenario 1 – Desplazamiento suave entre secciones:** <br> **Given** que el visitante selecciona un elemento del menú de navegación, <br> **When** el enlace apunta a una sección dentro de la misma página, <br> **Then** el sistema ejecuta un desplazamiento suave hasta esa sección sin recargar la página. <br><br> **Escenario 2 – Menú visible durante el scroll:** <br> **Given** que el visitante hace scroll hacia abajo, <br> **When** supera la altura del encabezado inicial, <br> **Then** el menú permanece fijo en la parte superior de la pantalla y se mantiene accesible durante la navegación. <br><br> **Escenario 3 – Sección activa resaltada en el menú:** <br> **Given** que el visitante se encuentra en una sección específica de la página, <br> **When** el scroll posiciona esa sección como la principal visible en pantalla, <br> **Then** el ítem correspondiente del menú se resalta visualmente para indicar la ubicación actual. | EP07 |
| US25 | Ver preguntas frecuentes en la landing page | Como visitante de la landing page, quiero consultar las preguntas frecuentes de la plataforma para resolver dudas antes de registrarme sin necesidad de contactar al equipo de soporte. | **Escenario 1 – Sección FAQ visible y accesible:** <br> **Given** que el visitante navega a la sección de preguntas frecuentes, <br> **When** la sección carga, <br> **Then** el sistema muestra al menos 6 preguntas organizadas por categoría (clínicas y dueños de mascotas). <br><br> **Escenario 2 – Expansión de respuesta:** <br> **Given** que el visitante selecciona una pregunta del listado, <br> **When** la activa, <br> **Then** el sistema expande la respuesta correspondiente sin redirigir a otra página. <br><br> **Escenario 3 – Enlace de contacto al final de la sección:** <br> **Given** que el visitante revisa las preguntas frecuentes y no encuentra respuesta a su duda, <br> **When** llega al final de la sección, <br> **Then** el sistema muestra un enlace o formulario de contacto para consultas adicionales. | EP07 |
| **EP08** | **Technical Stories – RESTful API** | Proveer endpoints seguros, documentados y funcionales que soporten todas las operaciones del sistema Pawtient para su integración con el frontend web y la aplicación móvil. | — | — |
| TS01 | Endpoint de autenticación de usuarios | Como developer, quiero un endpoint POST /api/v1/auth/login que valide credenciales y devuelva un token JWT para que el frontend pueda gestionar sesiones de forma segura. | **Escenario 1 – Autenticación exitosa (200):** <br> **Given** que el developer envía una petición POST con email y password válidos, <br> **When** el servidor valida las credenciales, <br> **Then** retorna HTTP 200 con un token JWT, el rol del usuario y el tiempo de expiración del token. <br><br> **Escenario 2 – Credenciales inválidas (401):** <br> **Given** que el developer envía credenciales incorrectas, <br> **When** el servidor valida el body de la petición, <br> **Then** retorna HTTP 401 con el mensaje "Invalid credentials" sin especificar cuál campo es incorrecto. <br><br> **Escenario 3 – Body malformado (400):** <br> **Given** que el developer envía una petición sin los campos requeridos (email o password), <br> **When** el servidor valida el body, <br> **Then** retorna HTTP 400 con el mensaje "Missing required fields" y la lista de campos faltantes. | EP08 |
| TS02 | Endpoint de creación de historia clínica | Como developer, quiero un endpoint POST /api/v1/records que permita crear una nueva historia clínica para que el frontend registre consultas desde cualquier cliente. | **Escenario 1 – Creación exitosa (201):** <br> **Given** que el developer envía una petición POST con body válido (petId, diagnosis, treatment, date, vetId) y token de autenticación vigente, <br> **When** el servidor procesa la solicitud, <br> **Then** retorna HTTP 201 con el objeto creado incluyendo el id generado y la marca de tiempo del registro. <br><br> **Escenario 2 – Campos obligatorios faltantes (400):** <br> **Given** que el developer envía una petición POST con campos obligatorios ausentes, <br> **When** el servidor valida el body, <br> **Then** retorna HTTP 400 con el mensaje "Missing required fields" y la lista de campos faltantes. <br><br> **Escenario 3 – Token inválido o ausente (401):** <br> **Given** que el developer envía la petición sin token de autenticación o con uno expirado, <br> **When** el servidor valida la cabecera Authorization, <br> **Then** retorna HTTP 401 con el mensaje "Unauthorized". | EP08 |
| TS03 | Endpoint de programación de citas | Como developer, quiero un endpoint POST /api/v1/appointments que permita crear citas para que el frontend web y la app móvil puedan agendar turnos de forma unificada. | **Escenario 1 – Cita creada exitosamente (201):** <br> **Given** que el developer envía una petición POST con petId, vetId, clinicId, date y time válidos, <br> **When** el servidor verifica la disponibilidad y procesa la solicitud, <br> **Then** retorna HTTP 201 con el objeto de cita incluyendo el appointmentId y el estado "confirmed". <br><br> **Escenario 2 – Conflicto de horario (409):** <br> **Given** que el developer envía una solicitud para un horario ya ocupado por el mismo veterinario, <br> **When** el servidor valida la disponibilidad, <br> **Then** retorna HTTP 409 con el mensaje "Time slot not available" y la lista de los próximos horarios disponibles. <br><br> **Escenario 3 – Fecha en el pasado (422):** <br> **Given** que el developer envía una fecha anterior a la fecha actual del servidor, <br> **When** el servidor valida el campo date, <br> **Then** retorna HTTP 422 con el mensaje "Invalid or past date". | EP08 |
| TS04 | Endpoint de gestión de inventario | Como developer, quiero endpoints GET /api/v1/inventory y POST /api/v1/inventory para consultar y registrar suministros para que el módulo de trazabilidad opere correctamente. | **Escenario 1 – Listado de inventario exitoso (200):** <br> **Given** que el developer envía una petición GET con token válido y clinicId como parámetro de consulta, <br> **When** el servidor procesa la solicitud, <br> **Then** retorna HTTP 200 con el listado de suministros incluyendo nombre, stock actual, unidad de medida y fecha de vencimiento. <br><br> **Escenario 2 – Ingreso de suministro exitoso (201):** <br> **Given** que el developer envía una petición POST con name, quantity, unit, expirationDate y clinicId válidos, <br> **When** el servidor procesa la solicitud, <br> **Then** retorna HTTP 201 con el registro actualizado; si el producto ya existe, retorna el stock acumulado. <br><br> **Escenario 3 – Flag de stock bajo en la respuesta (200):** <br> **Given** que el developer consulta el inventario y algún suministro tiene stock igual o menor al mínimo configurado, <br> **When** el servidor retorna la lista, <br> **Then** incluye el campo lowStock: true en los objetos de suministros que cumplen esa condición. | EP08 |
| TS05 | Endpoint de notificaciones push | Como developer, quiero un endpoint POST /api/v1/notifications/send que dispare notificaciones push a usuarios para que el sistema automatice recordatorios de vacunas y citas. | **Escenario 1 – Notificación encolada exitosamente (200):** <br> **Given** que el developer envía una petición POST con userId, notificationType (appointment / vaccine / followup) y scheduledDate válidos, <br> **When** el servidor procesa la solicitud, <br> **Then** retorna HTTP 200 con el campo status: "queued" y el notificationId generado. <br><br> **Escenario 2 – Usuario sin dispositivo registrado (404):** <br> **Given** que el developer envía la solicitud para un userId sin token de dispositivo registrado, <br> **When** el servidor consulta el registro del usuario, <br> **Then** retorna HTTP 404 con el mensaje "No device token found for user". <br><br> **Escenario 3 – Tipo de notificación inválido (400):** <br> **Given** que el developer envía un notificationType no reconocido por el sistema, <br> **When** el servidor valida el campo, <br> **Then** retorna HTTP 400 con el mensaje "Invalid notification type" y la lista de tipos aceptados por el sistema. | EP08 |


<br>

**8 Epics**, **22 User Stories funcionales** (incluyendo 4 para la Landing Page) y **5 Technical Stories para el API**, sumando un total de **30 historias**. La distribución cubre los pain points identificados en las entrevistas: historiales físicos dispersos (EP02), gestión manual de citas (EP03), falta de recordatorios (EP06), trazabilidad de suministros (EP04), búsqueda de clínicas (EP05), acceso seguro (EP01), visibilidad de la plataforma (EP07) y contratos técnicos del API (EP08).

<br>

---

## 3.2. Impact Mapping

>*El Impact Mapping de Pawtient permite alinear los objetivos del negocio con las necesidades de los usuarios, asegurando que cada funcionalidad desarrollada genere valor real. A partir de los User Personas identificados: Sebastián Navarro (veterinario) y Camila Rodríguez (dueña de mascota), se definieron los objetivos de negocio (Business Goals), los actores involucrados, los impactos esperados en su comportamiento y los entregables que permiten alcanzarlos.
Los Business Goals han sido formulados bajo el criterio SMART, asegurando que sean específicos, medibles, alcanzables, relevantes y definidos en el tiempo.*

<br>

<div align="center">
  
**Herramienta utilizada:** `UXPressia`

![Impact Map](pawtient-report/assets/images/impact-mapping/impact-map.png)

</div>

<br>

El Impact Mapping nos permitió conectar los objetivos de negocio con el comportamiento esperado de los usuarios. A partir de los User Personas, identificamos qué acciones deben realizar para lograr los objetivos, y definimos funcionalidades concretas que luego se traducen en User Stories dentro del Product Backlog.

<br>

---

## 3.3. Product Backlog

>*El Product Backlog de Pawtient representa el conjunto ordenado de todas las User Stories y Technical Stories que guían el desarrollo del producto. El orden de priorización está determinado por el valor que cada historia aporta al negocio, considerando los Business Goals definidos en el Impact Map. Las historias relacionadas con la Landing Page se ubican al inicio dado que deben estar disponibles desde el primer sprint. Las Technical Stories se ubican al final por tratarse de soporte técnico al desarrollo. La estimación de esfuerzo se realizó utilizando la escala de Story Points de Fibonacci (1, 2, 3, 5, 8).*

<br>


| Orden | User Story ID | Título | Descripción | Story Points |
|---|---|---|---|---|
| 1 | US22 | Propuesta de valor para clínicas | Como visitante del segmento clínica, deseo ver los beneficios del sistema en la landing page para evaluar si Pawtient se adapta a las necesidades de mi centro. | 3 |
| 2 | US23 | Propuesta de valor para dueños | Como visitante del segmento dueño de mascota, deseo entender cómo Pawtient me ayuda a cuidar mejor a mi mascota para decidir si me registro en la plataforma. | 3 |
| 3 | US24 | Navegación en landing page | Como visitante de la landing page, deseo usar el menú de navegación para desplazarme rápidamente a cualquier sección y conocer todo el contenido disponible. | 2 |
| 4 | US25 | Preguntas frecuentes | Como visitante de la landing page, deseo consultar las preguntas frecuentes para resolver dudas antes de registrarme sin necesidad de contactar al equipo de soporte. | 2 |
| 5 | US04 | Registrar historia clínica | Como veterinario, deseo crear y guardar la historia clínica digital de una mascota para eliminar el uso de registros físicos y acceder a la información desde cualquier dispositivo. | 8 |
| 6 | US05 | Consultar historial clínico | Como veterinario, deseo buscar y visualizar el historial completo de una mascota para tomar decisiones clínicas informadas durante la consulta. | 5 |
| 7 | US08 | Agendar cita desde la clínica | Como veterinario, deseo registrar una nueva cita en el sistema para organizar la agenda diaria sin depender de llamadas manuales ni registros en papel. | 5 |
| 8 | US10 | Visualizar agenda diaria | Como veterinario, deseo ver un resumen de las citas programadas para el día en curso para organizar mi jornada de trabajo de forma eficiente. | 3 |
| 9 | US16 | Crear perfil de mascota | Como dueño de mascota, deseo registrar el perfil de mi mascota en la plataforma para centralizar su información médica y acceder a ella en cualquier momento. | 5 |
| 10 | US09 | Agendar cita como dueño | Como dueño de mascota, deseo solicitar una cita veterinaria desde mi celular para evitar llamadas telefónicas y reducir el tiempo invertido en coordinar turnos. | 5 |
| 11 | US11 | Recordatorios de citas | Como dueño de mascota, deseo recibir recordatorios automáticos antes de las citas de mi mascota para no olvidar los turnos médicos. | 3 |
| 12 | US07 | Registrar vacunas | Como veterinario, deseo registrar cada vacuna aplicada durante una consulta vinculándola al historial de la mascota para mantener un calendario de vacunación actualizado. | 5 |
| 13 | US19 | Recordatorios de vacunación | Como dueño de mascota, deseo recibir alertas cuando la vacuna de mi mascota esté próxima para no perder el calendario de vacunación. | 3 |
| 14 | US12 | Registrar suministros | Como administrador de clínica, deseo registrar el ingreso de nuevos suministros al inventario para mantener el stock actualizado en tiempo real. | 5 |
| 15 | US13 | Consultar stock | Como veterinario, deseo consultar el nivel actual de un suministro para verificar disponibilidad antes de prescribir un tratamiento. | 3 |
| 16 | US14 | Registrar consumo de suministros | Como veterinario, deseo registrar los insumos utilizados durante una consulta para descontarlos automáticamente del inventario y mantener la trazabilidad de uso. | 5 |
| 17 | US15 | Alertas de reabastecimiento | Como administrador de clínica, deseo recibir alertas automáticas cuando el stock de un suministro sea bajo para solicitar reposición con anticipación y evitar faltantes. | 3 |
| 18 | US06 | Editar historia clínica | Como veterinario, deseo actualizar la historia clínica de una mascota después de cada consulta para mantener la información vigente y con trazabilidad de cambios. | 5 |
| 19 | US20 | Configurar notificaciones | Como dueño de mascota, deseo personalizar el tipo y frecuencia de notificaciones que recibo para gestionar las alertas según mis necesidades. | 2 |
| 20 | US21 | Notificaciones de seguimiento | Como dueño de mascota, deseo recibir notificaciones cuando el veterinario actualice el estado de seguimiento de mi mascota para mantenerme informado después de cada consulta. | 3 |
| 21 | US17 | Compartir historial con clínica | Como dueño de mascota, deseo compartir el historial de mi mascota con una nueva clínica para que el veterinario cuente con información previa relevante. | 5 |
| 22 | US18 | Buscar clínicas cercanas | Como dueño de mascota, deseo buscar clínicas veterinarias cercanas con sus reseñas y servicios para elegir el mejor lugar para atender a mi mascota. | 5 |
| 23 | US01 | Registro de veterinario | Como veterinario, deseo crear una cuenta en Pawtient con mis datos profesionales para acceder a las funcionalidades del sistema de gestión clínica. | 5 |
| 24 | US02 | Inicio de sesión | Como usuario registrado, deseo iniciar sesión con mis credenciales para acceder a las funcionalidades según mi rol. | 3 |
| 25 | US03 | Recuperar contraseña | Como usuario registrado, deseo recuperar el acceso a mi cuenta en caso de olvidar mi contraseña para no perder el acceso a la plataforma. | 3 |
| 26 | TS01 | API – Autenticación | Como developer, deseo un endpoint POST /api/v1/auth/login que valide credenciales y devuelva un token JWT para que el frontend pueda gestionar sesiones de forma segura. | 5 |
| 27 | TS02 | API – Historial clínico | Como developer, deseo un endpoint POST /api/v1/records que permita crear una nueva historia clínica para que el frontend registre consultas desde cualquier cliente. | 5 |
| 28 | TS03 | API – Citas | Como developer, deseo un endpoint POST /api/v1/appointments que permita crear citas para que el frontend web y la app móvil puedan agendar turnos de forma unificada. | 5 |
| 29 | TS04 | API – Inventario | Como developer, deseo endpoints GET y POST /api/v1/inventory para consultar y registrar suministros para que el módulo de trazabilidad opere correctamente. | 5 |
| 30 | TS05 | API – Notificaciones | Como developer, deseo un endpoint POST /api/v1/notifications/send que dispare notificaciones push para que el sistema automatice recordatorios de vacunas y citas. | 5 |

<br>

<div align="center">
  
**Herramienta utilizada:** `Jira`

**URL del Product Backlog:** [Ver Product Backlog en Jira](https://briupalace.atlassian.net/jira/software/projects/PAW/boards/2/backlog?atlOrigin=eyJpIjoiMTE0ZjJmNThkNjBhNDQyNzkwMzI2YTJiMzJkNjRiN2MiLCJwIjoiaiJ9)

<br>

*Captura del Product Backlog en herramienta*

![Product Backlog](pawtient-report/assets/images/product-backlog/product-backlog.png)

</div>

<br>

### Criterios de priorización aplicados

<br>

El orden del backlog responde a los siguientes criterios en cascada:

1. **Visibilidad inmediata (Sprint 1):** Las User Stories de Landing Page (US22–US25) se priorizan primero porque deben estar disponibles desde el inicio para la adquisición de usuarios, tal como indica el enunciado.

2. **Core del negocio:** Las historias del módulo de historiales clínicos (US04, US05, US06) y citas (US08, US09, US10) se priorizan a continuación por ser el diferencial central de Pawtient y las que directamente impactan el Business Goal 1.

3. **Engagement del dueño:** Las historias de perfil de mascota (US16), recordatorios (US11, US19) y vacunación (US07) se ubican en posición media-alta por su impacto directo en el Business Goal 2.

4. **Inventario y trazabilidad:** Las historias del módulo de suministros (US12–US15) se ubican en posición media por ser críticas para el Business Goal 4 pero de menor urgencia que los módulos core.

5. **Funcionalidades complementarias:** Las historias de configuración (US20), seguimiento (US21), compartir historial (US17) y búsqueda de clínicas (US18) se ubican en posición baja-media por ser mejoras sobre funcionalidad ya establecida.

6. **Autenticación:** Las historias de registro e inicio de sesión (US01–US03) se ubican al final de las User Stories funcionales porque, si bien son necesarias técnicamente, no representan valor directo de negocio para el usuario final y el enunciado indica explícitamente que iniciar el backlog con autenticación es incorrecto.

7. **Technical Stories:** Las TS01–TS05 cierran el backlog por ser soporte técnico del API REST, sin valor de negocio directo perceptible por el usuario.

<br>

---

<div align="center">

# Capítulo IV: Product Design

</div>

---

## 4.1. Style Guidelines

### 4.1.1. General Style Guidelines

Las decisiones de estilo de Pawtient se basan en la necesidad de transmitir confianza, cercanía y profesionalismo en el contexto del cuidado de mascotas y la gestión de clínicas veterinarias. Se busca una interfaz clara, accesible y consistente, que facilite la interacción tanto de veterinarios como del personal administrativo.

**Branding**

El branding de Pawtient está orientado a representar el cuidado y bienestar de las mascotas a través de una identidad visual moderna y amigable.

El nombre Pawtient surge de la combinación de “Paw” (pata) y “Patient” (paciente), haciendo referencia directa a las mascotas como los pacientes principales del sistema.

El logotipo de *Pawtient* está compuesto por una tipografía sans-serif moderna y amigable, que transmite claridad, accesibilidad y confianza, valores fundamentales en el contexto de la gestión clínica veterinaria.

El elemento distintivo del logotipo es la integración de una huella de mascota dentro de la letra inicial “P”, la cual funciona como isotipo. Este recurso visual refuerza de manera directa el enfoque del sistema en el cuidado de animales, permitiendo una identificación inmediata por parte del usuario.

En cuanto a la paleta de colores, el logotipo utiliza una combinación de azul y verde. El azul (#3A86FF) representa confianza, profesionalismo y seguridad en el manejo de la información, mientras que el verde (#2ECC71) evoca salud, bienestar y conexión con el cuidado de las mascotas. Esta combinación cromática genera un equilibrio visual que comunica tanto el aspecto clínico como el humano del producto.

El diseño del logotipo ha sido concebido para ser versátil y escalable, asegurando su correcta visualización en diferentes contextos, como interfaces web, aplicaciones móviles, iconos y material gráfico. Asimismo, el isotipo puede utilizarse de forma independiente en espacios reducidos, como favicon o elementos de navegación.

![Logo Pawtient](pawtient-report/assets/images/pawtient2.png)

Los principios de identidad visual se centran en:
- Cercanía con el usuario
- Claridad en la comunicación
- Profesionalismo en el entorno clínico
- Confianza en el manejo de información

---

**Typography**

| Tipo |   Fuente    | Uso |
|:-----|:-----------:|:----|
| Display / Heading |   Poppins   | Títulos y encabezados |
| Body |    Inter    | Texto de contenido |
| Monospace | Roboto Mono | Código y datos técnicos |

![roboto](pawtient-report/assets/images/roboto.png)

![poppins](pawtient-report/assets/images/poppins.png)

![inter](pawtient-report/assets/images/inter.png)

Estas tipografías fueron seleccionadas por su alta legibilidad en entornos digitales y su compatibilidad con interfaces modernas.

**Colors**

| Nombre | Hex | Uso                                |
|:-------|:---:|:-----------------------------------|
| Primary | #3A86FF | Color principal de la marca        |
| Secondary | #2ECC71 | Color de apoyo (salud y bienestar) |
| Accent | #FF9F1C | Énfasis y llamados a la acción     |
| Background | #F5F5F5 | Fondo general                      |
| Text | #2E2E2E | Texto principal                    |
| Error | #E63946 | Estados de error                   |
| Success | #2ECC71 | Estados de éxito                   |

![paletacolores](pawtient-report/assets/images/paletacolores.png)

La paleta busca generar una experiencia visual equilibrada, transmitiendo seguridad, limpieza y accesibilidad.

**Spacing**

El sistema de espaciado de *Pawtient* se basa en una unidad base de **8px**, siguiendo buenas prácticas de diseño UI modernas.

Se utilizan múltiplos de esta unidad para mantener consistencia:
- 8px → separación mínima
- 16px → separación estándar
- 24px / 32px → separación entre secciones
- 48px+ → separación de bloques principales

Esto permite una interfaz ordenada, clara y fácil de escanear visualmente.

---
**Tono de comunicación**

| Dimensión |             Selección             |
|:----------|:---------------------------------:|
| Divertido / Serio |  Equilibrado (ligeramente serio)  |
| Formal / Casual |            Semi-formal            |
| Respetuoso / Irreverente |            Respetuoso             |
| Entusiasta / Sereno | Sereno con toques positivos |

El tono busca generar confianza en un entorno clínico, sin perder cercanía con los usuarios.

---

### 4.1.2. Web Style Guidelines

Las Web Style Guidelines de Pawtient definen los estándares visuales y de interacción para garantizar una experiencia consistente en la aplicación web.

---

#### Diseño Responsive 

La aplicación se adapta a distintos dispositivos:
- Desktop
- Tablet
- Mobile

Se prioriza la usabilidad en pantallas pequeñas, asegurando navegación fluida y contenido legible.

---
#### Componentes del sistema

Los componentes del sistema de *Pawtient* han sido diseñados siguiendo principios de simplicidad, consistencia y reutilización, tomando como referencia Material Design y adaptándose a la identidad visual del producto.

- **Navbar (Barra de navegación):**  
  Ubicada en la parte superior, permite el acceso a secciones principales como Inicio, Servicios, Nosotros y Contacto. Mantiene una estructura limpia y fija para facilitar la navegación.

- **Buttons (Botones):**  
  Botones con bordes ligeramente redondeados y estilos definidos (primary, secondary).
    - Primary: color azul (#3A86FF) para acciones principales
    - Secondary: verde (#2ECC71) para acciones complementarias  
      Incluyen estados: hover, active y disabled.

- **Hero Section:**  
  Sección principal de bienvenida con título destacado, subtítulo y call-to-action (CTA), diseñada para captar la atención del usuario y comunicar el valor del sistema.

- **Cards:**  
  Utilizadas para mostrar información estructurada como servicios, mascotas o funcionalidades. Incluyen imagen, título y descripción breve.

- **Forms (Formularios):**  
  Inputs claros con etiquetas visibles y validaciones en tiempo real. Se utilizan para registro, inicio de sesión y gestión de datos.

- **Icons (Iconos):**  
  Basados en representaciones simples y reconocibles (usuario, menú, mascota), alineados con el estilo minimalista del sistema.
---

#### Interacciones

Las interacciones en Pawtient están diseñadas para ser intuitivas, fluidas y consistentes, mejorando la experiencia del usuario sin sobrecargar la interfaz.

- **Hover states:**  
  Los elementos interactivos (botones, links, cards) cambian sutilmente de color o elevación al pasar el cursor.

- **Feedback visual:**  
  El sistema muestra respuestas inmediatas a las acciones del usuario, como mensajes de éxito, error o carga.

- **Transiciones suaves:**  
  Se utilizan animaciones ligeras para cambios de estado, navegación o aparición de componentes.

- **Responsive interactions:**  
  En dispositivos móviles, se priorizan interacciones táctiles claras, como botones grandes y menús desplegables.

- **Call To Action (CTA):**  
  Botones destacados como “Comenzar gratis” guían al usuario hacia las acciones principales del sistema.

---
#### Design System

El diseño de *Pawtient* se basa en un sistema de diseño modular que garantiza consistencia visual y escalabilidad en toda la aplicación.

Se toman como referencia los principios de **Material Design**, adaptados a la identidad del producto.

- **Grid system:**  
  Uso de grillas flexibles para organizar el contenido en diferentes resoluciones (desktop, tablet y mobile).

- **Spacing system:**  
  Basado en una unidad de 8px para mantener consistencia en márgenes y paddings.

- **Color system:**  
  Aplicación coherente de la paleta definida (primary, secondary, accent, neutrals) en todos los componentes.

- **Typography system:**  
  Uso consistente de jerarquías tipográficas (heading, subheading, body) para mejorar la legibilidad.

- **Component-based design:**  
  Todos los elementos UI (botones, cards, forms) son reutilizables, permitiendo mantener coherencia y facilitar el desarrollo en Angular.

![Landing Pawtient](pawtient-report\assets\images\pcpet.PNG)

---
## 4.2. Information Architecture

En nuestra aplicación Pawtient nos basamos en un enfoque centrado en el usuario, diferenciando claramanete la experiencia de captación en la Landing Page de la experiencia operativa en la Web Application.

Para la Landing Page, se ha optado por una estructura narrativa que guía al usuario a traves de toda la aplicación para guiarlo de una buena manera, centrandonos en el objetivo
de ayudar a estos usuarios como una guía de lo que ofrecemos en los planes de membresia, en esta App priorizamos la claridad visual y la confianza hacia el usuario.
Para esta Web Application, la organización es funcional y modular, permitiendo a veterinarios y administradores acceder a las herramientas de regirstro e inventario con la menor cantidad de clics
posibles, optimizando asi los procesos diarios.

### 4.2.1. Organization Systems

Se utiliza un sistema de organización jerárquica para la Landing Page, permitiendo que el usuario entienda primero la propuesta de valor y luego baje
hacia los detalles de servicios y planes. Para la Web Application, se aplica un sistema orientado a tareas, facilitando que el veterinario acceda directamente a las funciones
de registro clínico e inventario.

### 4.2.2. Labeling Systems


|  Etiqueta   | Descripción del contenido que representa                 |
|:-----------:|:---------------------------------------------------------|
|  `Inicio`   | Página principal con la propuesta de valor de Pawtient.  |
| `Servicios` | Detalle de las funcionalidades (Historial, Insumo, IoT). |
| `Membresía` | Planes de Suscripción (Basic, Mid, Pro) y beneficios     |
| `Contacto`  | Formulario para soporte y consultas de nuevos centros    |

### 4.2.3. SEO Tags and Meta Tags

**Landing Page**

```html
<title>Pawtient - Gestión Veterinaria Inteligente e Integral</title>
<meta name="description" content="Plataforma para digitalizar centros veterinarios, gestionar historiales clínicos" />
<meta name="keywords" content="veterinaria, gestión clínica, historiales médicos,control de insumos, software veterinario" />
<meta name="author" content="PetHealth" />
```

**Web Application**

```html
<title>[Título de la Web Application]</title>
<meta name="description" content="Panel de administración para veterinarios: registro clínico, control de inventario de insumos" />
<meta name="keywords" content="gestión veterinaria, dashboard, historial clínico digital" />
<meta name="author" content="PetHealth" />
```

### 4.2.4. Searching Systems


El sistema de búsqueda en Pawtient está diseñado para ser reactivo y eficiente. Se implementará una barra de búsqueda global en el DashBoard que permitirá a los veterianos encontrar
pacientes por nombre de la mascota, nombre del dueño o DNI del usuario. Ademas, se incluirán filtros avanzados en la sección de inventario para categorizar insumos por tipo. 

### 4.2.5. Navigation Systems


Se han definido tres sistemas de navegación principales para garantizar la usabilidad:

* Navegación Estructural (Menús):La Landing Page utiliza un menú superior fijo con enlaces ancla a las secciones de beneficios y precios. La Web Application utiliza una barra lateral con iconos reconocibles para el acceso rápido.
* Navegación Asociativa: Se incluyen botones de 'Llamada a la Acción' (CTA) estratégicos como 'Comenzar gratis' para convertir visitantes en usuarios.
* Navegación de Utilidad: Un menú de perfil de usuario en la esquina superior derecha para gestionar la configuración de la cuenta y el cierre de sesión, manteniendo la consistencia visual mediante el uso de avatars."

---

## 4.3. Landing Page UI Design



### 4.3.1. Landing Page Wireframe

En esta sección se presenta los wireframes de la versión Desktop de la Landing page, donde se observa la estructura
que tiene esta landing, como diversos apartados en donde el usuario pueda interacturar de manera autonoma y con una interfaz fácil de usar.


**Desktop Web Browser**

![Page-Wireframe1](pawtient-report/assets/images/landing-page/Page-Wireframe1.png)
![Page-Wireframe2](pawtient-report/assets/images/landing-page/Page-Wireframe2.png)
![Page-Wireframe3](pawtient-report/assets/images/landing-page/Page-Wireframe3.png)
![Page-Wireframe5](pawtient-report/assets/images/landing-page/Page-Wireframe5.png)
![Page-Wireframe6](pawtient-report/assets/images/landing-page/Page-Wireframe6.png)
![Page-Wireframe7](pawtient-report/assets/images/landing-page/Page-Wireframe7.png)

**Mobile Web Browser**

![Mobile-Wireframe1](pawtient-report/assets/images/mobile-app/Mobile-Wireframe1.png)
![Mobile-Wireframe2](pawtient-report/assets/images/mobile-app/Mobile-Wireframe2.png)
![Mobile-Wireframe3](pawtient-report/assets/images/mobile-app/Mobile-Wireframe3.png)
![Mobile-Wireframe4](pawtient-report/assets/images/mobile-app/Mobile-Wireframe4.png)
![Mobile-Wireframe5](pawtient-report/assets/images/mobile-app/Mobile-Wireframe5.png)
![Mobile-Wireframe6](pawtient-report/assets/images/mobile-app/Mobile-Wireframe6.png)
![Mobile-Wireframe7](pawtient-report/assets/images/mobile-app/Mobile-Wireframe7.png)
![Mobile-Wireframe8](pawtient-report/assets/images/mobile-app/Mobile-Wireframe8.png)

### 4.3.2. Landing Page Mock-up


En este apartado se muestra todos los Mocku-ups de nuestra App web, tanto desktop como mobile tienen una interfaz la cual es agradable para el usuario,
además de ser fácil de poder utilizar, cumple con el objetivo que nosotros queremos ofrecer, asimismo sigue un lineamiento usando
diversos tipos de colores, tipografías, etc.

**Desktop Web Browser**

![Desktop-Mockup1](pawtient-report/assets/images/landing-page/Page-Mockup1.png)
![Desktop-Mockup2](pawtient-report/assets/images/landing-page/Page-Mockup2.png)
![Desktop-Mockup3](pawtient-report/assets/images/landing-page/Page-Mockup3.png)
![Desktop-Mockup5](pawtient-report/assets/images/landing-page/Page-Mockup5.png)
![Desktop-Mockup7](pawtient-report/assets/images/landing-page/Page-Mockup7.png)
**Mobile Web Browser**

![Mobile-Mockup1](pawtient-report/assets/images/mobile-app/Mobile-Mockup1.png)
![Mobile-Mockup2](pawtient-report/assets/images/mobile-app/Mobile-Mockup2.png)
![Mobile-Mockup3](pawtient-report/assets/images/mobile-app/Mobile-Mockup3.png)
![Mobile-Mockup4](pawtient-report/assets/images/mobile-app/Mobile-Mockup4.png)
![Mobile-Mockup5](pawtient-report/assets/images/mobile-app/Mobile-Mockup5.png)
![Mobile-Mockup6](pawtient-report/assets/images/mobile-app/Mobile-Mockup6.png)
![Mobile-Mockup7](pawtient-report/assets/images/mobile-app/Mobile-Mockup7.png)
![Mobile-Mockup8](pawtient-report/assets/images/mobile-app/Mobile-Mockup8.png)
![Mobile-Mockup9](pawtient-report/assets/images/mobile-app/Mobile-Mockup9.png)
---

## 4.4. Web Applications UX/UI Design


### 4.4.1. Web Applications Wireframes

**Panorama Completo de los WireFrames Desktop and Mobile**

![Web App Wireframes](pawtient-report/assets/images/landing-page/AllWireframes.png)

### 4.4.2. Web Applications Wireflow Diagrams

En esta sección usamos los Wireframes. El objetivos es mostrar la lógica que queremos transmitir para nuestros usuarios

---

**User goal: `[Usuario y selección de Perfil]`**

El Wireflow describe la transición jerárquica desde el punto de entrada público hacia la función de la aplicación. 
En este apartado se aplica un diseño de navegación lineal, el cual va a garantizar que el usuarios defina su rol
antes de poder acceder al sistema y realizar los debido servicios. 

![Wireflow Diagrama 4](pawtient-report/assets/images/landing-page/Page-Wireframe4.png)
![Wireflow Diagrama 4](pawtient-report/assets/images/mobile-app/Mobile-Wireframe4.png)

---
### 4.4.3. Web Applications Mock-ups

**Panorama Completo de los Mock-ups Desktop and Mobile, teniendo en cuenta los diversos styles anteriormente puesto**

![Web App Mockups](pawtient-report/assets/images/landing-page/AllMockUps.png)

### 4.4.4. Web Applications User Flow Diagrams

**User goal: `[Usuario y selección de Perfil/ Elección de Membresia]`**

Los diagramas de User Flow presentados ilustran la lógica de navegación y la experiencia del usuario dentro de nuestro sistema
Pawtient, centrándose en el proceso crítico de elección de rol y la elección de membresia. Esta estructura de flujos asegura 
que la aplicación web mantenga la integridad de la base de datos y ofrezca una navegación intuitiva y segura en todo momento.

![User Flow Diagrama 1](pawtient-report/assets/images/landing-page/Page-Mockup4.png)
![User Flow Diagrama 2](pawtient-report/assets/images/mobile-app/Mobile-Mockup4.png)
![User Flow Diagrama 2](pawtient-report/assets/images/landing-page/Page-Mockup6.png)

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

En esta sección se explica y evidencia el proceso de Design-Level EventStorming, que sirvió para plantear una aproximación revisada y mejorada al modelado de nivel general para el dominio del problema.


**IAM Bounded Context**
![IAM](pawtient-report/assets/images/Design-Level-Event-Storming/IAM.png)

**Profile Bounded Context**
![Profile](pawtient-report/assets/images/Design-Level-Event-Storming/Profile.png)

**Clinic Bounded Context**
![Clinic](pawtient-report/assets/images/Design-Level-Event-Storming/Clinic.png)

**Appointment Bounded Context**
![Appointment](pawtient-report/assets/images/Design-Level-Event-Storming/Appoiments.png)

**Report Bounded Context**
![Report](pawtient-report/assets/images/Design-Level-Event-Storming/Reports.png)

**Store Bounded Context**
![Store](pawtient-report/assets/images/Design-Level-Event-Storming/Store.png)

**Bounded Contexts y sus relaciones**
![Bounded Contexts](pawtient-report/assets/images/Design-Level-Event-Storming/Bounded-Context.png)
En este último paso, el equipo buscó agregados que estén relacionados entre sí mediante policies para luego identificar bounded contexts y finalmente marco los eventos de dominio que fueron implementados.

[Ver en miro](https://miro.com/welcomeonboard/TUM0Kzk0ajRxOXdpd1EzRXpwQjU1ckx6c3JPV2trSUxpQ2dLc0p6RFZjUEFwaXYvcHpOMTZGWHExOFpibXpLRHNURWF6Zko2b1NaM2FxTEJieCsvUElhMFUwdXIwNThuaWpBa3F4dzlXUklLaXA4dFFvZUY1VjRHVXhGcklxT3BNakdSWkpBejJWRjJhRnhhb1UwcS9BPT0hdjE=?share_link_id=798329479919)

### 4.6.2. Software Architecture Context Diagram

El diagrama de contexto del sistema Pawtient presenta una vista general del sistema dentro de su entorno, identificando los actores principales que interactúan con la plataforma y los sistemas externos con los que se integra.

![System Context View](pawtient-report/assets/images/systemcontextview.png)

### 4.6.3. Software Architecture Container Diagrams

El diagrama de contenedores del sistema Pawtient presenta una vista de alto nivel de la arquitectura, mostrando los principales bloques tecnológicos y la forma en que interactúan entre sí.

El sistema está compuesto por una aplicación web (frontend), que permite la interacción de los usuarios mediante una interfaz intuitiva; un backend implementado como una API REST, encargado de procesar la lógica de negocio y gestionar las solicitudes; y una base de datos, donde se almacena la información del sistema, como usuarios, mascotas, citas e historiales médicos.

Asimismo, el sistema se integra con servicios externos para el envío de notificaciones y el procesamiento de pagos. La comunicación entre los contenedores se realiza mediante protocolos estándar, garantizando una arquitectura organizada, escalable y mantenible.

![Container View](pawtient-report/assets/images/containerview.png)

### 4.6.4. Software Architecture Components Diagrams

Los diagramas de componentes del sistema Pawtient representan la estructura interna del backend siguiendo el enfoque de Domain-Driven Design (DDD). La arquitectura se organiza en distintos Bounded Contexts, cada uno enfocado en una responsabilidad específica del sistema: IAM, Profile, Organization, Monitoring and Control, y Reports.

Dentro de cada Bounded Context, los componentes se estructuran en cuatro capas principales: Interfaces, Application, Domain e Infrastructure. La capa de Interfaces gestiona la interacción con los usuarios a través de endpoints REST; la capa de Application coordina la lógica de negocio y los casos de uso; la capa de Domain contiene las entidades y reglas de negocio; y la capa de Infrastructure se encarga de la persistencia de datos mediante repositorios. 

La interacción entre estas capas sigue un flujo definido donde la capa de Interfaces invoca los servicios de Application, los cuales utilizan el Domain para ejecutar la lógica de negocio y la Infrastructure para acceder a la base de datos. Este enfoque permite una clara separación de responsabilidades, facilitando la escalabilidad, mantenibilidad y evolución del sistema.

- Organization Bounded Context
  ![Organization](pawtient-report/assets/images/organization.png)
- Monitoring and Control Bounded Context
  ![Monitoring](pawtient-report/assets/images/monitoring.png)
- Reports Bounded Context
  ![Reports](pawtient-report/assets/images/reports.png)
- Profile Bounded Context
  ![Profile](pawtient-report/assets/images/profile.png)
- IAM Bounded Context
  ![IAM](pawtient-report/assets/images/IAM.png)
---

## 4.7. Software Object-Oriented Design

>*En esta sección se presenta el diseño orientado a objetos del sistema Pawtient mediante diagramas de clases UML, los cuales describen la estructura interna de sus componentes. El diseño se basa en los enfoques Domain-Driven Design (DDD) y el modelo C4, organizando el sistema en distintos bounded contexts como IAM, Appointments, Clinical Management, Store, Reports y Profile.
Cada bounded context se estructura en capas (domain, application, infrastructure y presentation), lo que permite una adecuada separación de responsabilidades. Los diagramas incluyen clases con atributos, métodos y niveles de visibilidad, así como sus relaciones y multiplicidades. En conjunto, proporcionan una visión clara y estructurada del sistema, sirviendo como base para su implementación.*

<br>

### 4.7.1. Class Diagrams

A continuación, se presentan los diagramas de clases UML para cada bounded context del sistema Pawtient. Estos diagramas describen las clases, sus atributos, métodos y relaciones, diferenciando además los componentes de frontend y backend.

Esta representación permite comprender la organización modular del sistema y la distribución de responsabilidades entre la interfaz de usuario y la lógica de negocio, asegurando coherencia con la arquitectura definida.

<br>

**1. Bounded Context: `IAM (Identity & Access)`**

<br>

Este diagrama corresponde al Identity & Access Bounded Context, encargado de gestionar la autenticación y autorización de los usuarios dentro del sistema Pawtient. El agregado principal User administra la información esencial del usuario, incluyendo su identificador, correo electrónico, contraseña cifrada, rol y fecha de registro. Este contexto permite controlar el acceso al sistema mediante operaciones como registro, inicio de sesión y validación de credenciales. Además, el modelo considera diferentes roles (administrador, veterinario y dueño de mascota), los cuales determinan los permisos y funcionalidades disponibles dentro de la plataforma. En conjunto, este contexto garantiza la seguridad del sistema y el control adecuado de acceso a los recursos.

<br>
<div align="center">

**Frontend Components Diagrams**

![Frontend Diagram BC1](pawtient-report/assets/images/class-diagrams/frontend/front-diagram-1.png)

</div>
<br>

El módulo IAM permite a los usuarios registrarse, iniciar sesión y gestionar su sesión activa. Incluye vistas como LoginView, RegisterView y ProfileView, junto con un AuthStore que maneja el estado de autenticación y la comunicación con la API mediante Observables.

<br>
<div align="center">

**Backend Components Diagrams**

![Backend Diagram BC1](pawtient-report/assets/images/class-diagrams/backend/back-diagram-1.png)

</div>
<br>

El módulo IAM gestiona la lógica de negocio relacionada con autenticación y control de acceso. Implementa comandos como registro e inicio de sesión, handlers para procesar dichas operaciones, repositorios para persistencia de usuarios y servicios de seguridad como generación de tokens JWT.

<br>

**2. Bounded Context: `Appointment Management`**

<br>

Este diagrama corresponde al contexto de gestión de citas, responsable de administrar la programación, modificación y cancelación de citas médicas para las mascotas. El agregado principal Appointment contiene información clave como la mascota asociada, el veterinario asignado, la fecha y el estado de la cita. Este contexto permite organizar la agenda de atención, asegurando un flujo ordenado de consultas dentro de la clínica. Además, el sistema contempla distintos estados de la cita (programada, cancelada, completada), lo que permite llevar un control preciso del ciclo de vida de cada atención.


<br>
<div align="center">

**Frontend Components Diagrams**

![Frontend Diagram BC2](pawtient-report/assets/images/class-diagrams/frontend/front-diagram-2.png)

</div>
<br>

El módulo Appointments permite a los usuarios visualizar el calendario de citas, registrar nuevas citas y gestionar las existentes. Incluye componentes como AppointmentDashboard, AppointmentForm y AppointmentCard, junto con un AppointmentStore que gestiona el estado y sincroniza los datos con el backend.

<br>
<div align="center">

**Backend Components Diagrams**

![Backend Diagram BC2](pawtient-report/assets/images/class-diagrams/backend/back-diagram-2.png)

</div>
<br>

El módulo Appointments gestiona la lógica de negocio relacionada con la programación de citas. Implementa comandos como creación y cancelación de citas, handlers para procesar estas acciones y repositorios para la persistencia de la información.

<br>

**2. Bounded Context: `Clinical Management`**

<br>

Este diagrama corresponde al contexto principal del sistema Pawtient, encargado de la gestión clínica de las mascotas. El agregado principal Pet representa al paciente veterinario, incluyendo información como nombre, especie, raza, fecha de nacimiento y su propietario. Este contexto incluye las entidades Consultation, que registra cada atención médica con diagnóstico y tratamiento, y MedicalRecord, que almacena el historial clínico completo de la mascota, incluyendo antecedentes, alergias y observaciones. En conjunto, este contexto permite centralizar toda la información médica del paciente, facilitando el seguimiento continuo de su estado de salud y la toma de decisiones clínicas.

<br>
<div align="center">

**Frontend Components Diagrams**

![Frontend Diagram BC3](pawtient-report/assets/images/class-diagrams/frontend/front-diagram-3.png)

</div>
<br>

El módulo Clinical Management permite a los usuarios gestionar mascotas, consultas y registros médicos. Incluye vistas como PetDashboardView, ConsultationView y MedicalRecordView, junto con componentes especializados como formularios y tarjetas. El estado es gestionado por ClinicStore, que coordina la comunicación con la API y mantiene sincronizados los datos clínicos.

<br>
<div align="center">

**Backend Components Diagrams**

![Backend Diagram BC3](pawtient-report/assets/images/class-diagrams/backend/back-diagram-3.png)

</div>
<br>

El módulo Clinical Management gestiona la lógica de negocio relacionada con pacientes, consultas y registros médicos. Implementa comandos como creación de consultas y actualización de historiales médicos, handlers para su procesamiento, servicios de consulta para recuperación de datos y repositorios para la persistencia de la información clínica.

<br>

**4. Bounded Context: `Store (Inventory)`**

<br>

Este diagrama corresponde al contexto de gestión de inventario, encargado de administrar los productos, proveedores y movimientos de stock dentro de la clínica veterinaria. El agregado principal Product contiene información como nombre, descripción, precio y stock disponible. Además, el modelo incluye la entidad Supplier, que representa a los proveedores de insumos, y StockMovement, que registra las entradas y salidas de productos. Este contexto permite mantener un control preciso del inventario, evitando desabastecimientos y facilitando la gestión de recursos médicos.

<br>
<div align="center">

**Frontend Components Diagrams**

![Frontend Diagram BC4](pawtient-report/assets/images/class-diagrams/frontend/front-diagram-4.png)

</div>
<br>

El módulo Store permite a los usuarios visualizar productos, registrar nuevos insumos y gestionar movimientos de inventario. Incluye vistas como InventoryDashboardView, ProductFormView y StockMovementView, junto con componentes reutilizables y un InventoryStore que maneja el estado de los productos y movimientos.

<br>
<div align="center">

**Backend Components Diagrams**

![Backend Diagram BC4](pawtient-report/assets/images/class-diagrams/backend/back-diagram-4.png)

</div>
<br>

El módulo Store gestiona la lógica de negocio relacionada con productos y control de inventario. Implementa comandos como creación de productos y registro de movimientos, handlers correspondientes y repositorios para la persistencia de datos.

<br>

**5. Bounded Context: `Reports & Billing`**

<br>

Este diagrama corresponde al contexto de reportes y gestión financiera, encargado de generar informes y controlar la facturación dentro del sistema. El agregado principal Report permite generar distintos tipos de reportes sobre el funcionamiento de la clínica, mientras que la entidad Billing gestiona la información financiera, incluyendo montos, fechas y transacciones. Este contexto permite obtener una visión global del rendimiento del negocio, facilitando la toma de decisiones estratégicas y el control económico.

<br>
<div align="center">

**Frontend Components Diagrams**

![Frontend Diagram BC5](pawtient-report/assets/images/class-diagrams/frontend/front-diagram-5.png)

</div>
<br>

El módulo Reports permite a los usuarios generar reportes y visualizar información financiera. Incluye vistas como ReportView y BillingView, junto con un ReportStore que gestiona los datos y coordina la comunicación con el backend.

<br>
<div align="center">

**Backend Components Diagrams**

![Backend Diagram BC5](pawtient-report/assets/images/class-diagrams/backend/back-diagram-5.png)

</div>
<br>

El módulo Reports gestiona la lógica de negocio relacionada con la generación de reportes y facturación. Implementa comandos para la generación de reportes, handlers para su procesamiento y repositorios para el almacenamiento de la información.

<br>

**6. Bounded Context: `Profile`**

<br>

Este diagrama corresponde al contexto de gestión de perfil de usuario, encargado de administrar la información personal de los usuarios dentro del sistema. El agregado principal Profile contiene datos como nombre, correo electrónico y la relación con el usuario del sistema. Este contexto permite a los usuarios actualizar su información personal y mantener sus datos actualizados dentro de la plataforma.

<br>
<div align="center">

**Frontend Components Diagrams**

![Frontend Diagram BC6](pawtient-report/assets/images/class-diagrams/frontend/front-diagram-6.png)

</div>
<br>

El módulo Profile permite a los usuarios visualizar y actualizar su información personal. Incluye la vista ProfileView y un ProfileStore que gestiona el estado del perfil y la comunicación con la API.

<br>
<div align="center">

**Backend Components Diagrams**

![Backend Diagram BC6](pawtient-report/assets/images/class-diagrams/backend/back-diagram-6.png)

</div>
<br>

El módulo Profile gestiona la lógica de negocio relacionada con la actualización de perfiles de usuario. Implementa comandos de actualización, handlers y repositorios para la persistencia de datos.

<br>

---

## 4.8. Database Design

>*En esta sección se presenta el diseño de la base de datos del sistema Pawtient, estructurado en función de los bounded contexts definidos previamente en el modelo de dominio. El diseño sigue un enfoque relacional que permite la persistencia eficiente y consistente de la información del sistema.
El modelo incluye tablas con atributos definidos bajo una nomenclatura uniforme, así como claves primarias y foráneas que establecen relaciones entre entidades. Estas relaciones garantizan la integridad referencial y permiten mantener la coherencia de los datos entre los distintos módulos del sistema. Asimismo, la organización por bounded contexts facilita la separación de responsabilidades y la escalabilidad del sistema.*

<br>

### 4.8.1. Database Diagrams

>*El diagrama de base de datos de Pawtient refleja una arquitectura orientada al dominio, organizada en múltiples bounded contexts, cada uno responsable de un conjunto cohesivo de entidades. Para su elaboración se utilizó MySQL Workbench, herramienta que permitió diseñar, visualizar y estructurar las tablas, columnas y relaciones del sistema de manera clara.
Aunque el modelo es único a nivel físico, en el diagrama las tablas se agrupan visualmente según el bounded context al que pertenecen, lo que facilita la comprensión de la estructura del sistema sin generar duplicación de datos.*

<br>

<div align="center">
  

**`Database Diagram`**

<br>

![Database Diagram](pawtient-report/assets/images/database/database-diagram.png)

</div>

<br>

*Explicación:*

<br>

**IAM (Identity & Access)**

Este contexto gestiona la identidad y el acceso al sistema. La tabla Users centraliza la autenticación, roles y estado de los usuarios. A partir de ella se derivan Pet_owners y Veterinarians, que extienden la información según el tipo de usuario. Estas entidades permiten diferenciar claramente entre los dueños de mascotas y los profesionales veterinarios dentro del sistema.

<br>

**Appointment Management** 

Este contexto administra la programación de citas. La tabla Schedules define la disponibilidad de los veterinarios mediante bloques de tiempo, mientras que Appointments vincula mascotas, veterinarios y horarios, incluyendo el estado y motivo de la cita. La tabla Reminders permite registrar notificaciones asociadas a cada cita, facilitando la comunicación con los usuarios.

<br>

**Clinical Management** 

Este es el núcleo funcional del sistema. La tabla Medical_records actúa como raíz del historial clínico de cada mascota. A partir de ella, Consultations registra cada atención médica realizada por un veterinario. De cada consulta se derivan múltiples entidades relacionadas:

- Vital_signs, que almacena los signos vitales,
- Diagnoses, que contiene el diagnóstico,
- Prescriptions, que define el tratamiento,
- Exams, que permite registrar múltiples estudios complementarios.

Este contexto permite gestionar de forma integral la información médica de cada paciente.

<br>

**Store (Inventory)** 

Este contexto gestiona los recursos e insumos de la clínica. Suppliers almacena la información de proveedores, mientras que Products representa los insumos disponibles, incluyendo stock actual y mínimo. Inventory_movements registra cada movimiento de inventario (entrada, salida o ajuste), y Stock_alerts permite identificar situaciones de bajo stock.

La tabla Prescription_items conecta este contexto con el clínico, permitiendo la trazabilidad de los productos utilizados en cada tratamiento.

**Reports** 

Este contexto se encarga de la generación de reportes y análisis del sistema. No posee tablas propias en el modelo actual, ya que consume información proveniente de otros contextos como Appointments, Consultations e Inventory_movements.

Su función es consolidar y procesar estos datos para obtener indicadores y reportes, manteniendo una única fuente de verdad sin duplicar información.

**Profile** 

Este contexto gestiona la información del perfil de usuario. Se basa en la tabla Users, reutilizando sus atributos para evitar redundancia. Su responsabilidad principal es permitir la visualización y actualización de los datos personales del usuario dentro del sistema.

<br>

---


<div align="center">

# Capítulo V: Product Implementation, Validation & Deployment

</div>

---

## 5.1. Software Configuration Management

### 5.1.1. Software Development Environment Configuration

Para el desarrollo de Pawtient, el equipo ha estandarizado un entorno de desarrollo y un conjunto de tecnologías que aseguran la compatibilidad y fluidez del trabajo conjunto en todo el ciclo de vida del producto:

| Categoría | Producto |                                  Propósito                                  | Ruta / URL                     |
|:----------|:--------:|:---------------------------------------------------------------------------:|:-------------------------------|
| Project Management | Jira |              Gestión ágil de Sprints, tareas y Product Backlog              | https://jira.it.tuwien.ac.at/  |
| Requirements Management | UXPressia |                 Elaboración de Impact Maps y User Personas                  | https://uxpressia.com          |
| Product UX/UI Design | Figma |                     Wireframes, Mockups y Prototipos UI                     | https://figma.com              |
| Software Development | Visual Studio Code |            Editor principal para desarrollo web (HTML, CSS, JS)             | https://code.visualstudio.com/ |
| Software Development | Angular CLI |            Framework principal para el Frontend Web Application             | https://angular.io             |
| Software Development | Spring Boot |              Framework principal para los RESTful Web Services              | https://spring.io              |
| Software Deployment | GitHub Pages |                   Despliegue estático de la Landing Page                    | https://pages.github.com/      |
| Software Documentation | Swagger / OpenAPI |                Documentación interactiva de los Web Services                | https://swagger.io/            |
| Version Control | Git + GitHub |                 Control de versiones y trabajo colaborativo                 | https://github.com             |
|Miro   |Diseño| Diseño colaborativo en tiempo real de mapas de experiencia (As-Is y To-Be). |https://miro.com   |
---

### 5.1.2. Source Code Management

El código fuente de Pawtient se gestiona bajo una arquitectura de repositorios separados para garantizar modularidad.

**Organización de GitHub:** [PetHealt](https://github.com/PetHealt)

|      Producto       |       Repositorio       | URL                                             |
|:-------------------:|:-----------------------:|:------------------------------------------------|
| Organización Flowey |       `Pawtient`        | https://github.com/FloweyTech     |
|    Landing Page     | `Pawtient-landing-page` | https://github.com/PetHealt/Pawtient-landing-page     |
|       Report        |    `Pawtient-report`    | https://github.com/PetHealt/Pawtient-report    |

**GitFlow Workflow:**

Se implementará GitFlow con las siguientes ramas:

| Rama | Propósito | Convención de nombre |
|:-----|:---------:|:---------------------|
| `main` | Código en producción | `main` |
| `develop` | Integración de features | `develop` |
| `feature/*` | Desarrollo de características | `feature/<nombre-descriptivo>` |
| `release/*` | Preparación de releases | `release/vX.Y.Z` (ej: `release/1.0.0`) |
| `hotfix/*` | Correcciones urgentes en producción | `hotfix/<problema>` |

**Semantic Versioning:** Se aplica [Semantic Versioning 2.0.0](https://semver.org/) para nombrar los releases (`MAJOR.MINOR.PATCH`).

**Conventional Commits:** Se aplican [Conventional Commits](https://www.conventionalcommits.org/) para los mensajes de commits:


---

### 5.1.3. Source Code Style Guide & Conventions

| Lenguaje / Framework | Convención adoptada | Referencia |
|:--------------------:|:-------------------:|:-----------|
| HTML | HTML Style Guide | https://www.w3schools.com/html/html5_syntax.asp |
| CSS | BEM & Custom Properties | Guía de estilo interna (Uso estricto de variables en `:root`) |
| JavaScript / TypeScript | Google TypeScript Style Guide | https://google.github.io/styleguide/tsguide.html |
| Angular | Angular coding style guide | https://angular.io/guide/styleguide |
| Java | Google Java Style Guide | https://google.github.io/styleguide/javaguide.html |
| Spring Boot | Spring Boot Features | https://docs.spring.io/spring-boot/docs/current/reference/html/features.html |
| Gherkin (Acceptance Criteria) | Gherkin Conventions | https://specflow.org/gherkin/gherkin-conventions-for-readable-specifications/ |

> **Nota:** Para todos los lenguajes se aplica la nomenclatura en **inglés**.

---

### 5.1.4. Software Deployment Configuration

1. **Ingresar a Netlify**<br>
   Accedemos a la plataforma mediante nuestras credenciales de Github en "Log in with GitHub".
   ![Screenshot 1 del Deployment](pawtient-report/assets/images/Software-Deployment-Configuration/deployment-1.png)

2. **Autorizar a Netlify**<br>
   Damos permisos a Netlify de acceder a nuestra cuenta de GitHub para luego ir a la sección "Sites" y presionar "Add new site". Entonces, le damos a "Import an existing project".
    ![Screenshot 2 del Deployment](pawtient-report/assets/images/Software-Deployment-Configuration/deployment-2.jpeg)
3. **Escoger tu deploy**<br>
   En la parte de "Let's deploy your project with..." seleccionamos GitHub.
    ![Screenshot 3 del Deployment](pawtient-report/assets/images/Software-Deployment-Configuration/deployment-3.png)

4. **Escoger tu repositorio**<br>
    Dado que nuestro repositorio está bajo una organización, la seleccionamos.
    ![Screenshot 4 del Deployment](pawtient-report/assets/images/Software-Deployment-Configuration/deployment-4.png)
5. **Configurar el despliegue**<br>
   Ahora procedemos a configurar el despliegue, colocando el Site Name y seleccionando el Team, también debemos escoger una rama que en este caso será la Main.
    ![Screenshot 5 del Deployment](pawtient-report/assets/images/Software-Deployment-Configuration/deployment-5.png)

6. **Seguir configurando**<br>
   Seguimos configurando, pero esta vez seleccionando el "Publish directory" colocamos public, para finalmente darle a "Deploy demy-academy".
    ![Screenshot 6 del Deployment](pawtient-report/assets/images/Software-Deployment-Configuration/deployment-6.png)

7. **Despliegue listo**<br>
   Ahora podemos observar que el deploy está listo y podremos ver el enlace de la web a la landing page recién desplegada.
    ![Screenshot 7 del Deployment](pawtient-report/assets/images/Software-Deployment-Configuration/deployment-7.png)

Ahora con la Landing Page desplegada, cada vez que se realize un push en la rama correspondiente, se actualizara automáticamente, de esta manera evitamos repetir los pasos.

[Ver Landing Page desplegada](`https://pethealt.netlify.app/`)

---



## 5.2. Landing Page, Services & Applications Implementation
### 5.2.1. Sprint 1
#### 5.2.1.1. Sprint Planning 1

A continuación se presentará el sprint planning para esta primera entrega, donde definimos qué trabajo se va a realizar para el próximo sprint y cómo se va a lograr.

| Sprint #                             | Sprint 1                                                                                                                                                                                                                                                                                          |
|--------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Sprint planning <br> background      |                                                                                                                                                                                                                                                                                                   |
| Date                                 | 2026/04/10                                                                                                                                                                                                                                                                                        |
| Time                                 | 8:00 PM                                                                                                                                                                                                                                                                                           |
| Location                             | Llamada grupal en la plataforma Discord                                                                                                                                                                                                                                                           |
| Prepared By                          | Gonzalo Quintanilla                                                                                                                                                                                                                                                                               |
| Attendees <br> (to planning meeting) | Brianna Salinas, Emily Arroyo, Mateo Salazar, Mathias Acuache y Gonzalo Quintanilla                                                                                                                                                                                                               |
| **Sprint Goal & User Stories** |                                                                                                                                                                                                                                                                                                   |
| Sprint 1 Goal                        | Nuestro enfoque está en presentar una landing page que muestre todas las <br> funcionalidades y características de Pawtient a los visitantes. <br> Creemos que esto generará una sólida primera impresión sobre el valor de la plataforma para clínicas y dueños de mascotas. <br> Esto se confirmará cuando la página esté desplegada, sea responsiva y sus enlaces funcionen correctamente. |
| Sprint 1 Velocity                    | 15                                                                                                                                                                                                                                                                                                |
| Sum of story points                  | 10                                                                                                                                                                                                                                                                                                |
---

#### 5.2.1.2. Aspect Leaders and Collaborators

Ahora presentaremos nuestro LACX (Leadership-and-Collaboration Matrix) que nos ayudará a saber quién lidera y quién colabora en cada aspecto de este primer sprint.<br>
Los aspectos que tomamos en cuenta para este primer sprint fueron los features de nuestra Landing Page desarrollados por el equipo de Pawtient.

<div style="font-size:70%;">

| **Team Member** <br> Last Name, First Name |      **GitHub Username**       | **Hero & Global** <br> L/C | **Nav & About us** <br> L/C | **Services & Stats** <br> L/C | **IoT & Roles** <br> L/C | **Pricing & Contact** <br> L/C |
|:------------------------------------------:|:------------------------------:|:-----------------:|:---------------------:|:---------------------:|:-------------------------:|:--------------------:|
|         **Quintanilla, Gonzalo** |             GoldQP             |         L         |           C           |           C           |             C             |          C           |
|         **Salinas, Brianna** |        brianna-salinas         |         C         |           L           |           C           |             C             |          C           |
|         **Salazar, Mateo** |  Mateo Paolo Salazar Miranda   |         C         |           C           |           L           |             C             |          C           |
|         **Arroyo, Emily** |             Em2920             |         C         |           C           |           C           |             L             |          C           |
|         **Acuache, Mathias** |           mathiasA25           |         C         |           C           |           C           |             C             |          L           |

</div>

<div style="text-align: center; font-size:85%; margin-top: 0.5rem;">

**Nota.** L = *Leader* (responsable principal del aspecto).  
C = *Collaborator* (apoya el desarrollo del aspecto).

</div>
---

#### 5.2.1.3. Sprint Backlog 1

El objetivo principal de este Sprint es **diseñar, implementar y desplegar la Landing Page** de la plataforma Pawtient, de modo que los usuarios (tanto personal clínico como dueños de mascotas) puedan conocer la propuesta de valor, características de la arquitectura, planes de suscripción y medios de contacto. Esto permitirá la primera validación con usuarios reales y sentará las bases para la adquisición B2B y B2C.

<table>
  <tr>
    <td><b>Sprint #</b></td>
    <td colspan="7">Sprint 1</td>
  </tr>
  <tr>
    <td colspan="2"><b>User Story</b></td>
    <td colspan="2"><b>Work-Item / Task</b></td>
    <td><b>Description</b></td>
    <td><b>Estimation (Hours)</b></td>
    <td><b>Assigned To</b></td>
    <td><b>Status (To-do / In-Process / To-Review / Done)</b></td>
  </tr>
  <tr>
    <td><b>Id</b></td>
    <td><b>Title</b></td>
    <td><b>Id</b></td>
    <td><b>Title</b></td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
  </tr>
  <tr>
    <td>US22</td>
    <td>Propuesta de valor para clínicas</td>
    <td>T01</td>
    <td>Implementar Hero y Global CSS</td>
    <td>Estructurar base HTML, variables CSS nativas y vista principal de captación.</td>
    <td>5</td>
    <td>Gonzalo Q.</td>
    <td>Done</td>
  </tr>
  <tr>
    <td>US22</td>
    <td>Propuesta de valor para clínicas</td>
    <td>T02</td>
    <td>Implementar sección IoT y Roles</td>
    <td>Maquetar tarjetas dinámicas de roles y sección de visualización de equipos IoT.</td>
    <td>4</td>
    <td>Emily A.</td>
    <td>Done</td>
  </tr>
  <tr>
    <td>US23</td>
    <td>Propuesta de valor para dueños</td>
    <td>T03</td>
    <td>Implementar Navbar y About Us</td>
    <td>Crear encabezado interactivo, menús de navegación y sección "Nosotros".</td>
    <td>4</td>
    <td>Brianna S.</td>
    <td>Done</td>
  </tr>
  <tr>
    <td>US24</td>
    <td>Navegación en landing page</td>
    <td>T04</td>
    <td>Implementar Servicios y Estadísticas</td>
    <td>Estilos CSS responsive en Grid/Flexbox para los beneficios y estadísticas.</td>
    <td>4</td>
    <td>Mateo S.</td>
    <td>Done</td>
  </tr>
  <tr>
    <td>US25</td>
    <td>Preguntas frecuentes y Contacto</td>
    <td>T05</td>
    <td>Implementar Pricing y Contacto</td>
    <td>Formularios de contacto e interruptor interactivo para la tabla de precios.</td>
    <td>4</td>
    <td>Mathias A.</td>
    <td>Done</td>
  </tr>
  <tr>
    <td>-</td>
    <td>-</td>
    <td>T06</td>
    <td>Configuración de entorno de trabajo (Git)</td>
    <td>Crear repositorios, estructurar ramas (GitFlow) y resolver conflictos de fusión.</td>
    <td>3</td>
    <td>Gonzalo Q.</td>
    <td>Done</td>
  </tr>
  <tr>
    <td>-</td>
    <td>-</td>
    <td>T07</td>
    <td>Despliegue del Frontend (CI/CD)</td>
    <td>Configurar entorno en Netlify conectado a la rama main de GitHub.</td>
    <td>2</td>
    <td>Gonzalo Q.</td>
    <td>Done</td>
  </tr>
</table>
</div>

---

#### 5.2.1.4. Development Evidence for Sprint Review

Durante el Sprint 1 se implementó la Landing Page de la solución Pawtient, la cual incluyó la creación de las secciones principales: Hero, Nosotros, Servicios, IoT & Roles, Precios y Contacto. El desarrollo se realizó en el repositorio público https://github.com/PetHealt/Pawtient-landing-page, utilizando un flujo de ramas basado en feature branches (GitFlow).

**Development Evidence – Sprint 1**

| Repository | Branch | Commit Id | Commit Message | Commit Message Body | Committed on (Date) |
| :--- | :--- | :--- | :--- | :--- | :--- |
| PetHealt/Pawtient-landing-page | main | 8ea012a | release: integra todos los componentes de la landing page en main | Integración final de todos los módulos unificados en la rama principal lista para producción. | 25/04/2026 |
| PetHealt/Pawtient-landing-page | develop | 9f54109 | fix:Bug fixes when joining branches | Corrección de errores de código generados durante la fusión de ramas del equipo. | 25/04/2026 |
| PetHealt/Pawtient-landing-page | develop | d2ebdb9 | fix: integra a gonzalo | Integración de los componentes de la rama feat/gonzalo a develop. | 25/04/2026 |
| PetHealt/Pawtient-landing-page | develop | 872d972 | fix: integra a mathias | Integración de los componentes de la rama feat/mathias a develop. | 25/04/2026 |
| PetHealt/Pawtient-landing-page | develop | fafe731 | fix: integra a mateo | Integración de los componentes de la rama feat/mateo a develop. | 25/04/2026 |
| PetHealt/Pawtient-landing-page | develop | 682dca8 | fix:resolves conflict by keeping Emilys CSS files | Resolución manual de conflictos de fusión priorizando los estilos CSS de Emily. | 25/04/2026 |
| PetHealt/Pawtient-landing-page | develop | 02a7120 | Merge pull request #1 from PetHealt/feat/brianna | Aprobación e integración del Pull Request de Brianna hacia develop. | 25/04/2026 |
| PetHealt/Pawtient-landing-page | feat/emily | 2564363 | feat: add hero.css file | Implementación de estilos visuales específicos para la sección Hero. | 25/04/2026 |
| PetHealt/Pawtient-landing-page | feat/emily | a2e3058 | feat: add contact.css file | Implementación de estilos visuales para la sección y formulario de contacto. | 25/04/2026 |
| PetHealt/Pawtient-landing-page | feat/mathias | 62c19f0 | feat: implement navigation bar styles | Desarrollo de estilos responsivos para la barra de navegación interactiva. | 25/04/2026 |
| PetHealt/Pawtient-landing-page | feat/mathias | 4c2fa8c | feat: implement iot section styles and logic | Implementación visual y de lógica para el módulo de equipos IoT. | 25/04/2026 |
| PetHealt/Pawtient-landing-page | feat/mateo | d9f1939 | feat: implement stats section | Desarrollo de la sección de estadísticas clave de la plataforma. | 24/04/2026 |
| PetHealt/Pawtient-landing-page | feat/mateo | 4861df8 | feat: implement services section | Implementación de la sección descriptiva de servicios ofrecidos. | 24/04/2026 |
| PetHealt/Pawtient-landing-page | feat/brianna | a8efe10 | feat: update pricing responsive styles | Ajuste de estilos móviles y responsivos para la tabla de planes de suscripción. | 24/04/2026 |
| PetHealt/Pawtient-landing-page | feat/brianna | 7db2f60 | feat: update script behavior and refine styles | Refinamiento de la lógica de JavaScript y estilos generales del componente. | 24/04/2026 |
| PetHealt/Pawtient-landing-page | feat/brianna | edfe80e | feat: refactor styles structure | Refactorización de la estructura de archivos de estilos modulares. | 24/04/2026 |
| PetHealt/Pawtient-landing-page | feat/gonzalo | 3b3cffb | feat: add index, script, global and about code | Código base HTML, configuración global de CSS Variables y script principal. | 23/04/2026 |
| PetHealt/Pawtient-landing-page | develop | b38d1d8 | chore: creates an empty folder and file structure | Creación del "molde" inicial con carpetas y archivos CSS vacíos para el equipo. | 23/04/2026 |
| PetHealt/Pawtient-landing-page | main | df95928 | landing page files | Primer commit con los recursos estáticos iniciales de la Landing Page. | 13/04/2026 |

---

#### 5.2.1.5. Execution Evidence for Sprint Review

Durante el **Sprint 1** se implementó la **Landing Page** de la plataforma Pawtient, cumpliendo satisfactoriamente con los objetivos definidos en el Sprint Backlog.  
La Landing Page constituye el primer punto de interacción con los usuarios, mostrando de forma clara la propuesta de valor dual de la plataforma: herramientas de gestión clínica e inventario para centros veterinarios (B2B) y seguimiento médico para dueños de mascotas (B2C).

El desarrollo tecnológico se centró en:
- Diseño responsive (Mobile-First) y navegación estructurada mediante anclas.
- Secciones implementadas: *Hero, Nosotros, Servicios, Estadísticas, IoT & Roles, Precios y Contacto*.
- Implementación de **Modo Oscuro (Dark Mode)** nativo e interactivo.
- Tarjetas desplegables e interruptores dinámicos en la tabla de planes de suscripción.

A continuación, se presentan las capturas de las principales vistas desarrolladas y desplegadas en producción:

*(Nota: Reemplaza las siguientes líneas con las imágenes/capturas reales de tu Landing Page)*
![Vista del Hero Section y Navbar](pawtient-report/assets/images/Evidence-for-sprint-review/evidencia-1.png)
![Vista de la sección Nosotros y Servicios](pawtient-report/assets/images/Evidence-for-sprint-review/evidencia-2.png)
![Vista de la sección IoT y Roles](pawtient-report/assets/images/Evidence-for-sprint-review/evidencia-3.png)
![Vista de Tabla de Precios y Contacto en Modo Oscuro](pawtient-report/assets/images/Evidence-for-sprint-review/evidencia-4.png)
![Vista de la Landing Page adaptada a formato Móvil](pawtient-report/assets/images/Evidence-for-sprint-review/evidencia-5.png)
![Vista de la Landing Page adaptada a formato Móvil](pawtient-report/assets/images/Evidence-for-sprint-review/evidencia-6.png)


Asimismo, se elaboró un **video demostrativo** que muestra la navegación fluida de la Landing Page, comprobando su responsividad, el cambio de temas (claro/oscuro) y explicando cada una de las secciones implementadas por el equipo:  
[Ver video demostrativo de Pawtient]([https://upcedupe-my.sharepoint.com/:v:/g/personal/u202315007_upc_edu_pe/IQCmFsBAO3FvTpMOpMAylR0gAUDFExNbahk7ihbfPEj4jSI?e=BnRltz&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D])

---

#### 5.2.1.6. Services Documentation Evidence for Sprint Review

Durante el Sprint 1, el esfuerzo técnico y el alcance principal se centraron exclusivamente en el diseño, implementación y despliegue de la Landing Page de captación. Por este motivo, en esta fase iterativa no se desarrollaron servicios de backend (RESTful API) asociados a la lógica de negocio profunda.

Sin embargo, a partir de las *Technical Stories* definidas en el Product Backlog, se ha establecido la arquitectura inicial de los Web Services y se ha previsto la integración con OpenAPI/Swagger. Esto permitirá, en los sprints posteriores, documentar formalmente los contratos de los endpoints que darán soporte a las funcionalidades *Core* de la plataforma, tales como la autenticación de roles (IAM), la programación de citas médicas, la gestión de historiales clínicos y el control de inventario de suministros veterinarios.

---

#### 5.2.1.7. Software Deployment Evidence for Sprint Review

## Software Deployment Evidence for Sprint Review

Durante el **Sprint 1** se realizó el despliegue exitoso de la **Landing Page** en la plataforma **Netlify**, utilizando el repositorio [PetHealt/Pawtient-landing-page](https://github.com/PetHealt/Pawtient-landing-page).  
Se optó por Netlify debido a su facilidad para implementar **Continuous Deployment (CD)** desde GitHub. Esto asegura que cualquier cambio aprobado y subido a la rama `main` se publique automáticamente en el servidor de producción sin intervención manual adicional.

### 🔹 Proceso seguido
1. **Conexión de cuenta:** Se vinculó la cuenta de GitHub de la organización **PetHealt** con la plataforma Netlify.
2. **Selección de repositorio:** Se seleccionó el proyecto `Pawtient-landing-page` para la creación del nuevo sitio.
3. **Configuración de Build:** Se definió la rama `main` como la rama de producción. Dado que es un sitio estático, no se requirieron comandos de compilación (Build commands) complejos.
4. **Despliegue inicial:** Se ejecutó el *Deploy* inicial, donde Netlify procesó los archivos HTML, CSS y JavaScript del repositorio.
5. **Generación de URL:** Una vez finalizado el proceso de *Provisioning* y *Deploy*, la plataforma generó una URL pública segura (HTTPS).

**URL del despliegue:** [https://pawtient.netlify.app/](https://pethealt.netlify.app/)

### 🔹 Evidencias
A continuación, se presentan las capturas de pantalla que documentan el estado "Published" en el panel de Netlify y la correcta visualización del sitio en el navegador:

1. **Captura del Panel de Netlify:** Donde se vea el estado "Site is live" y la conexión con el repo de GitHub.
2. **Captura de Deploys Log:** Mostrando el historial de despliegues exitosos.
3. **Captura del Sitio Web:** La Landing Page cargada en el navegador con el candado de seguridad HTTPS activo.

![Configuración de despliegue en Netlify](pawtient-report/assets/images/Software-Deployment-Configuration/deployment-3.png)
![Configuración de despliegue en Netlify](pawtient-report/assets/images/Software-Deployment-Configuration/deployment-7.png)
![Configuración de despliegue en Netlify](pawtient-report/assets/images/Evidence-for-sprint-review/evidencia-1.png)
---

#### 5.2.1.8. Team Collaboration Insights during Sprint

Durante el Sprint 1, el equipo trabajó siguiendo la estrategia de ramificación estandarizada **GitFlow**, creando ramas específicas por cada desarrollador y característica asignada (ejemplo: `feat/gonzalo`, `feat/brianna`, `feat/mateo`, `feat/emily`, `feat/mathias`).

El trabajo asíncrono se gestionó de manera eficiente: cada integrante empujó (*push*) sus cambios a su respectiva rama remota. Posteriormente, el Líder Técnico se encargó de realizar la integración progresiva (*merge*) de todas las ramas hacia `develop`, resolviendo los conflictos de fusión de estilos CSS que surgieron al unir los componentes. Tras la validación en el entorno de desarrollo, el código unificado se consolidó en la rama principal `main` para su despliegue a producción.

A continuación, se presentan los **analíticos de GitHub (Insights & Network Graph)**, que evidencian la participación del equipo en *commits*, gestión de ramas y *merges* durante el Sprint. Estas evidencias confirman la colaboración activa, equilibrada y estructurada de todos los miembros del equipo:

*(Nota: Reemplaza las siguientes líneas con tus capturas de GitHub Insights / Network)*
![Gráfico de Red (Network Graph) mostrando las ramas y merges](pawtient-report/assets/images/Team-Collaboration/network-graph.png)
![Analíticas de Contribución (Contributors) del equipo](pawtient-report/assets/images/Team-Collaboration/contributors.png)


## Conclusiones

1. **Integración y Despliegue Continuo (CI/CD) Exitoso:** La adopción estricta de la metodología de control de versiones *GitFlow* permitió al equipo gestionar de manera asíncrona y eficiente el código fuente de la *Landing Page*. La resolución efectiva de conflictos de fusión (merge conflicts) en la rama `develop` y la posterior automatización del despliegue en Netlify desde la rama `main` demuestran la madurez técnica del equipo en la gestión de la configuración del software.
2. **Validación Efectiva de la Propuesta de Valor:** El uso de herramientas de diseño UX (Impact Mapping, Wireframes, Mockups) y el desarrollo de una interfaz responsiva con *Dark Mode* nativo garantizaron que la *Landing Page* comunique eficazmente la propuesta de valor dual (B2B2C) de Pawtient. Esto establece un canal de adquisición sólido tanto para el personal clínico como para los dueños de mascotas.
3. **Arquitectura Escalable basada en DDD:** La aplicación del *Domain-Driven Design* a través del *Event Storming*, sumado al diseño de la base de datos relacional y los diagramas de arquitectura C4, proporciona una base técnica robusta, modular y altamente cohesiva. Esta estructuración mitiga riesgos técnicos tempranos y prepara el terreno para el desarrollo de los módulos de Gestión Clínica e Inventario en los próximos Sprints.

## Bibliografía

1. Cedeño Ochoa, A., Catuto Murillo, A., & Rodas-Silva, J. (31 de agosto de 2020). *Use of Web applications for the management of veterinary clinics and their impact on the improvement of administrative processes*. Portal AmeliCA. https://portal.amelica.org/ameli/jatsRepo/606/6062739010/index.html
2. Chacon, S., & Straub, B. (2014). *Pro Git* (2nd ed.). Apress. https://git-scm.com/book/en/v2
3. Evans, E. (2004). *Domain-Driven Design: Tackling Complexity in the Heart of Software*. Addison-Wesley Professional.
4. Gutiérrez Lerma, R. A. (5 de octubre de 2024). *Los principales problemas con clientes y motivos de insatisfacción en clínicas veterinarias*. VetStrategies Consulting. https://www.vetstrategiesconsulting.com/blog/los-principales-problemas-con-clientes-y-motivos-de-insatisfaccion-en-clinicas-veterinarias
5. Lolimsa. (12 de marzo de 2024). *Problemas comunes en clínicas veterinarias y cómo prevenirlos*. Lolimsa Blog. https://www.lolimsa.com.pe/blog/problemas-comunes-en-clinicas-veterinarias-y-como-prevenirlos/
6. Schwaber, K., & Sutherland, J. (2020). *The Scrum Guide*. Scrum.org. https://scrumguides.org/scrum-guide.html
7. W3C. (2023). *HTML5 Semantic Elements*. World Wide Web Consortium. https://www.w3.org/TR/html52/
---


## Anexos
- Landing page: desplegada en Netlify [https://pethealt.netlify.app/](https://pethealt.netlify.app/)
- video de exposición [Click Aqui](https://upcedupe-my.sharepoint.com/:v:/g/personal/u202315007_upc_edu_pe/IQDjBMv1FAbeT7vu70wgG-jjAUtpp41LDZw-REsa8JLOJ3U?e=mhXlkB&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D)
- prototipo web [Click Aqui](https://upcedupe-my.sharepoint.com/:v:/g/personal/u202315007_upc_edu_pe/IQCmFsBAO3FvTpMOpMAylR0gAUDFExNbahk7ihbfPEj4jSI?e=BnRltz&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D)