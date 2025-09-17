# Informe del Trabajo Final

**Universidad Peruana de Ciencias Aplicadas**

<img src="https://upload.wikimedia.org/wikipedia/commons/f/fc/UPC_logo_transparente.png" alt="Logo UPC">

**Ingeniería de software**

**Aplicaciones Web**

**Sección:** 7420

**Profesor:** Alex Humberto Sanchez

**Nombre del StartUp:** SendiFi

**Nombre del Producto:** Horizon

| Nombre                            | Código     |
| --------------------------------- | ---------- |
| Aguirre Eneque, Joan Elias        | U202313655 |
| Esquirva León, Miguel Juan Diego      | U202019449 |
| Osores Marchese, Pietro     | U202312391 |
| Payesa Torres, Harrison Hubert | U202313397 |
| Cossar Sanchez, Eduardo Jose      | U202312109 |

**Ciclo 2025-02**

# Registro de Versiones del Informe

| Version | Fecha      | Autor                                          | Descripción de modificación                                                |
| ------- | ---------- | ---------------------------------------------- | -------------------------------------------------------------------------- |
| 1ra     | --/--/-- | --------------------- | TB1: Se realizo los capitulos 1, 2, 3, 4 y el primer sprint del capitulo 5 |

</div>


# Project Report Collaboration Insights

URL del repositorio para el proyecto:

**TB1**

Para el desarrollo del informe perteneciente a la entrega TB1, se dividió la implementación de secciones de la siguiente forma
para cada integrante del equipo:

| Integrantes            | Tareas Asignadas                                                                                                                                       |
| ---------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------ |
|Aguirre Eneque, Joan Elias              | 2.3.1 User Persona, 3.2 User Stories, 4.7.1 Class Diagram, Diagramas C4                                                                                |
| Esquirva León, Miguel Juan Diego          | 2.3.2 User persona, 2.3.3 User Journey mapping, 2.3.4 Empathy mapping, 2.3.2 User matrix, 2.3.5. AS-IS Scenario Mapping, 4.8 Diagrama de base de datos |
| Osores Marchese, Pietro         | 2.2 Entrevistas, 3.2 User Stories y Diagramas c4                                                                                                       |
| Payesa Torres, Harrison Hubert      | 2.2 Entrevistas, Capitulo V: Product Implementation, Validation & Deployment                                                                           |
| Cossar Sanchez, Eduardo Jose         | Capitulo I: Introducción, 2.1 Competidores, 4.3 Landing Page UI Desing, 4.4 Web Applications UX/UI Design, 4.7.2 Class Dictionary                      
                                     

**Github Collaboration Insights**

Github también presenta un timeline de las ramas principales y los procesos de merge a los que se han sometido. Todas las
ramas se crearon tomando en cuenta el diseño de GitFlow para una buena organización cuando se usa un software de control
de versiones.

Los integrantes son:

- Aguirre Eneque, Joan Elias
- Esquirva León, Miguel Juan Diego
- Osores Marchese, Pietro
- Payesa Torres, Harrison Hubert
- Cossar Sanchez, Eduardo Jose (coleeeee-dev)

Se explican las ramas más prominentes:

**main:** Es representada por el color negro. Se trata de la rama principal del proyecto y se actualiza para cada entregable.<br>
**develop:** Es representada por el color azul. Se trata de la rama principal para el proceso del desarrollo del proyecto.<br>
**feature/Nombre-del-integrante**: <br>

# Contenido

1. [Capítulo I: Introducción](#capítulo-i-introducción)<br>
   1.1. [Startup Profile](#11-startup-profile)<br>
   1.1.1. [Descripción de la Startup](#111-descripción-de-la-startup)<br>
   1.1.2. [Perfiles de integrantes del equipo](#112-perfiles-de-integrantes-del-equipo)<br>
   1.2. [Solution Profile](#12-solution-profile)<br>
   1.2.1 [Antecedentes y problemática](#121-antecedentes-y-problemática)<br>
   1.2.2 [Lean UX Process](#122-lean-ux-process)<br>
   1.2.2.1. [Lean UX Problem Statements](#1221-lean-ux-problem-statements)<br>
   1.2.2.2. [Lean UX Assumptions](#1222-lean-ux-assumptions)<br>
   1.2.2.3. [Lean UX Hypothesis Statements](#1223-lean-ux-hypothesis-statements)<br>
   1.2.2.4. [Lean UX Canvas](#1224-lean-ux-canvas)<br>
   1.3. [Segmentos objetivo](#13-segmentos-objetivo)<br>
2. [Capítulo II: Requirements Elicitation & Analysis](#capítulo-ii-requirements-elicitation--analysis)<br>
   2.1. [Competidores](#21-competidores)<br>
   2.1.1. [Análisis competitivo](#211-análisis-competitivo)<br>
   2.1.2. [Estrategias y tácticas frente a competidores](#212-estrategias-y-tácticas-frente-a-competidores)<br>
   2.2. [Entrevistas](#22-entrevistas)<br>
   2.2.1. [Diseño de entrevistas](#221-diseño-de-entrevistas)<br>
   2.2.2. [Registro de entrevistas](#222-registro-de-entrevistas)<br>
   2.2.3. [Análisis de entrevistas](#223-análisis-de-entrevistas)<br>
   2.3. [Needfinding](#23-needfinding)<br>
   2.3.1. [User Personas](#231-user-personas)<br>
   2.3.2. [User Task Matrix](#232-user-task-matrix)<br>
   2.3.3. [User Journey Mapping](#232-user-task-matrix)<br>
   2.3.4. [Empathy Mapping](#234-empathy-mapping)<br>
   2.3.5. [As-is Scenario Mapping](#235-as-is-scenario-mapping)<br>
   2.4. [Ubiquitous Language](#24-ubiquitous-language)<br>
3. [Capítulo III: Requirements Specification](#capítulo-iii-requirements-specification)<br>
   3.1. [To-Be Scenario Mapping](#31-to-be-scenario-mapping)<br>
   3.2. [User Stories](#32-user-stories)<br>
   3.3. [Impact Mapping](#33-impact-mapping)<br>
   3.4. [Product Backlog](#34-product-backlog)<br>
4. [Capítulo IV: Product Design](#capítulo-iv-product-design)<br>
   4.1. [Style Guidelines](#41-style-guidelines)<br>
   4.1.1. [General Style Guidelines](#411-general-style-guidelines)<br>
   4.1.2. [Web Style Guidelines](#412-web-style-guidelines)<br>
   4.2. [Information Architecture](#42-information-architecture)<br>
   4.2.1. [Organization Systems](#421-organization-systems)<br>
   4.2.2. [Labeling Systems](#422-labeling-systems)<br>
   4.2.3. [SEO Tags and Meta Tags](#423-seo-tags-and-meta-tags)<br>
   4.2.4. [Searching Systems](#424-searching-systems)<br>
   4.2.5. [Navigation Systems](#425-navigation-systems)<br>
   4.3. [Landing Page UI Design](#43-landing-page-ui-design)<br>
   4.3.1. [Landing Page Wireframe](#431-landing-page-wireframe)<br>
   4.3.2. [Landing Page Mock-up](#432-landing-page-mock-up)<br>
   4.4. [Web Applications UX/UI Design](#44-web-applications-uxui-design)<br>
   4.4.1. [Web Applications Wireframes](#441-web-applications-wireframes)<br>
   4.4.2. [Web Applications Wireflow Diagrams](#442-web-applications-wireflow-diagrams)<br>
   4.4.2. [Web Applications Mock-ups](#442-web-applications-mock-ups)<br>
   4.4.3. [Web Applications User Flow Diagrams](#443-web-applications-user-flow-diagrams)<br>
   4.5. [Web Applications Prototyping](#45-web-applications-prototyping)<br>
   4.6. [Domain-Driven Software Architecture](#46-domain-driven-software-architecture)<br>
   4.6.1. [Software Architecture Context Diagram](#461-software-architecture-context-diagram)<br>
   4.6.2. [Software Architecture Container Diagrams](#462-software-architecture-container-diagrams)<br>
   4.6.3. [Software Architecture Components Diagrams](#463-software-architecture-components-diagrams)<br>
   4.7. [Software Object-Oriented Design](#47-software-object-oriented-design)<br>
   4.7.1. [Class Diagrams](#471-class-diagrams)<br>
   4.7.2. [Class Dictionary](#472-class-dictionary)<br>
   4.8. [Database Design](#48-database-design)<br>
   4.8.1. [Database Diagram](#481-database-diagram)<br>
5. [Capítulo V: Product Implementation, Validation & Deployment](#capítulo-v-product-implementation-validation--deployment)<br>
   5.1. [Software Configuration Management](#51-software-configuration-management)<br>
   5.1.1. [Software Development Environment Configuration](#511-software-development-environment-configuration)<br>
   5.1.2. [Source Code Management](#512-source-code-management)<br>
   5.1.3. [Source Code Style Guide & Conventions](#513-source-code-style-guide--conventions)<br>
   5.1.4. [Software Deployment Configuration](#514-software-deployment-configuration)<br>
   5.2. [Landing Page, Services & Applications Implementation](#52-landing-page-services--applications-implementation)<br>
   5.2.1. [Sprint 1](#521-sprint-1)<br>
   5.2.1.1. [Sprint Planning 1](#5211-sprint-planning-1)<br>
   5.2.1.2. [Aspect Leaders and Collaborators](#5212-aspect-leaders-and-collaborators)<br>
   5.2.1.3. [Sprint Backlog 1](#5213-sprint-backlog-1)<br>
   5.2.1.4. [Development Evidence for Sprint Review](#5214-development-evidence-for-sprint-review)<br>
   5.2.1.5. [Execution Evidence for Sprint Review](#5215-execution-evidence-for-sprint-review)<br>
   5.2.1.6. [Services Documentation Evidence for Sprint Review](#5216-services-documentation-evidence-for-sprint-review)<br>
   5.2.1.7. [Software Deployment Evidence for Sprint Review](#5217-software-deployment-evidence-for-sprint-review)<br>
   5.2.1.8. [Team Collaboration Insights during Sprint](#5218-team-collaboration-insights-during-sprint)<br>

6. [Conclusiones](#conclusiones)<br>
   6.1 [Conclusiones y recomendaciones](#61-conclusiones-y-recomendaciones)<br>
7. [Bibliografía](#bibliografía)<br>
8. [Anexos](#anexos)<br>


# Student Outcomes

**Student Outcome 3**

| Criterio específico                                                    | Acciones realizadas                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    | Conclusiones                                                                                                                                                                                                                                                                                                                                                                            |
| ---------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Comunica oralmente con efectividad a diferentes rangos de audiencia.   | **TB1**<br><br>**Aguirre Eneque, Joan Elias:** Durante el desarrollo del TB1, participé activamente en las reuniones grupales, donde compartí mis ideas y opiniones de forma oral. Además, colaboré en la redacción del documento, asegurándome de que todas las decisiones acordadas fueran plasmadas de manera clara y precisa.<br><br>**Esquirva León, Miguel Juan Diego:** En el TB1, trabajé junto al equipo expresando mis propuestas durante las reuniones y escuchando las opiniones de los demás. También contribuí a la elaboración escrita del informe, donde dejamos constancia de las decisiones tomadas de manera colaborativa.<br><br>**Osores Marchese, Pietro:** Mi aporte en el TB1 se basó en mantener una comunicación fluida con el equipo, participando de manera activa en cada reunión. Posteriormente, ayudé en la redacción del documento, organizando las ideas de forma ordenada para una mejor comprensión de los acuerdos alcanzados.<br><br>**Cossar Sanchez, Eduardo Jose:** Para el TB1, intervine en las reuniones grupales proponiendo ideas y discutiendo alternativas con mis compañeros. Asimismo, participé en la redacción del documento final, reflejando correctamente el consenso logrado entre todos.<br><br>**Payesa Torres, Harrison Hubert:** Durante la preparación del TB1, contribuí expresando mis puntos de vista y escuchando las sugerencias de los demás en las reuniones orales. También colaboré en la comunicación escrita, detallando de forma clara las decisiones que se tomaron en equipo.  |**TB1**<br>Para la TB1, el equipo trabajó colaborativamente y se logró una participación activa de cada uno de los integrantes. Se realizaron reuniones grupales en la que cada miembro compartió sus ideas de manera oral o escrita y, a partir de ello, se logró una toma de decisiones en conjunto la cual benefició al equipo en la toma de decisiones y en la ejecución de tareas.  <br>|
|   |
| Comunica por escrito con efectividad a diferentes rangos de audiencia. | **TB1**<br><br>**Aguirre Eneque, Joan Elias:** En el TB1, aporté en la redacción del documento, plasmando de manera clara las ideas que fueron acordadas en las reuniones.<br><br>**Esquirva León, Miguel Juan Diego:** Durante el TB1, contribuí a la elaboración escrita del informe, explicando de forma precisa los acuerdos logrados en equipo.<br><br>**Osores Marchese, Pietro:** Mi participación en el TB1 incluyó el desarrollo de habilidades de comunicación escrita, dejando registradas las ideas consensuadas durante las reuniones.<br><br>**Cossar Sanchez, Eduardo Jose:** En el desarrollo del TB1, colaboré en redactar el documento final, explicando adecuadamente las ideas discutidas en las sesiones de grupo.<br><br>**Payesa Torres, Harrison Hubert:** Para el TB1, me enfoqué en la redacción de las ideas trabajadas en equipo, asegurando que estuvieran correctamente explicadas en el documento.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               | **TB1**<br>Para el TB1, el equipo comunicó las ideas tomadas en el documento de manera conjunta y equitativa, siendo todos parte y responsables del desarrollo del informe. |     









# Capítulo I: Introducción

## 1.1. Startup Profile

### 1.1.1. Descripción de la Startup

Sendifi es una plataforma innovadora que se dedica a transformar la gestión de envíos a través de la tecnología. Nuestra plataforma web centraliza y simplifica la logística —desde el registro y la asignación hasta el seguimiento en tiempo real y los reportes—, mejorando la eficiencia operativa, reduciendo costos y elevando la experiencia del cliente. Aunque es una iniciativa emergente, en Horizon estamos profundamente comprometidos con la excelencia operativa y el desarrollo de soluciones tecnológicas que aborden los desafíos actuales del sector logístico. En Horizon brindamos herramientas que permiten a personas y empresas gestionar sus envíos de forma más eficiente, transparente y escalable.<br><br>
**Misión:** Hacer que personas, emprendimientos y pequeñas empresas gestionen sus envíos de forma simple y centralizada: crear, seguir y analizar en un solo lugar, sin complejidad.<br><br>
**Visión:** Ser la opción de confianza en Perú para personas, emprendimientos y pequeñas empresas que necesitan claridad y control sobre sus envíos, sin complejidad.<br><br>


### 1.1.2. Perfiles de integrantes del equipo

| **Perfil**                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    | **Foto**                                                                        |
| --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------- |
| **Aguirre Eneque, Joan Elias**<br>Mi nombre es Jeremy, Tengo 22 años. En la actualidad estoy estudiando la carrera de ingeniería de software en la Universidad Peruana de Ciencias Aplicadas. Albergo conocimientos intermedios en algunos lenguajes de programación, tales como C++, JavaScript y Python. Me considero una persona responsable con disposición de apoyar al grupo, también me gustan mucho los retos y así mismo poder cumplirlos. | <img src="https://files.catbox.moe/vl4z7c.jpg" alt="Jeremy image" width="200"> |
| **Esquirva León, Miguel Juan Diego**<br>Mi nombre es Kevin Chi. Tengo 19 años y actualmente estoy cursando el 5° ciclo de ingeniería de software. Me considero una persona con capacidades de liderazgo y capaz de trabajar bajo presión. | <img src="https://files.catbox.moe/bacwjq.jpg" alt="kevin image" width="200"> |
| **Osores Marchese, Pietro**<br> Soy Pietro Osores Marchese, estudiante de Ingeniería de Sistemas con interés en el desarrollo de software y la innovación tecnológica. Mi perfil combina habilidades en programación frontend, diseño de interfaces y gestión de proyectos ágiles, con un enfoque en la creación de soluciones digitales funcionales y escalables. Me caracterizo por el trabajo en equipo, la adaptabilidad y la búsqueda constante de nuevas herramientas para optimizar procesos y experiencias de usuario. | <img width="900" height="1200" alt="Image" src="https://github.com/user-attachments/assets/3299f6b1-3924-4222-af63-bf12555d01b0" /> |
| **Payesa Torres, Harrison Hubert**<br>Mi nombre es Harrison Payesa. Soy estudiante de la carrera de Ingeniería de Software. Tengo conocimientos en lenguaje Python, C++ y JavaScript, ademas de haber hecho proyectos con FrontEnd usando HTML, CSS y JS. En mi tiempo libre suelo ver películas y escuchar música. | <img width="650" height="872" alt="Image" src="https://github.com/user-attachments/assets/9e0ab9d7-bce6-4c6d-9029-673fe04f8355" /> |
| **Cossar Sanchez, Eduardo Jose**<br>Mi nombre es Eduardo Cossar. Soy estudiante de la carrera de Ingeniería de Software, tengo 19 años y actualmente estoy cursando el quinto ciclo en la UPC. Me considero una persona responsable y comprometida con un gran interés por la tecnología. Como integrante de este equipo, me comprometo a brindar todo mi apoyo y participación activa para afrontar los desafíos que se presenten y dar lo mejor de mí para lograr el éxito de este proyecto. | <img src="https://files.catbox.moe/mw437z.png" alt="Eduardo image" width="200"> |

## 1.2. Solution Profile

Sendify es una plataforma web que centraliza la gestión de envíos para personas, emprendimientos y empresas pequeñas. Desde una interfaz simple, el usuario (un único rol con acceso total) puede crear órdenes (remitente, destinatario, direcciones, peso/costo), generar un código de seguimiento, ver una línea de tiempo con los hitos del envío (recibido, en tránsito, entregado), recibir alertas ante retrasos o devoluciones y obtener reportes de costos y desempeño para tomar mejores decisiones.

### 1.2.1 Antecedentes y problemática

En el Perú, muchas personas, emprendimientos y pequeñas empresas gestionan sus envíos usando múltiples portales de couriers y hojas de cálculo, lo que genera dispersión de información, poca visibilidad de estados/costos y decisiones reactivas. Esto eleva los tiempos operativos, incrementa errores y dificulta medir el desempeño logístico

**What (Qué)**

#### ¿Cuál es el problema?

No existe (para este público objetivo) una plataforma simple y centralizada que permita crear envíos, hacer seguimiento unificado y analizar costos/tiempos sin saltar entre portales y planillas.

#### ¿Cuál es la relación con la persona en cuestión?

Sendify resuelve esta brecha al unificar órdenes, tracking y reportes en una sola interfaz con un lenguaje de estados estandarizado, reduciendo fricción y errores.


**Who (Quién)**

#### ¿Quiénes están involucrados?

Personas corrientes, vendedores independientes, micro y pequeñas empresas (e‑commerce y retail), couriers y clientes finales que reciben los paquetes.

#### ¿A quiénes le sucede el problema?

 A quienes envían 5–500 envíos/mes y necesitan visibilidad en tiempo real y control de costos sin complejidad técnica.

**Where (Dónde)**

#### ¿En dónde ocurre el problema?

Principalmente en Lima Metropolitana y ciudades con alta actividad de e‑commerce; la fragmentación de herramientas complica la gestión diaria.

#### ¿En dónde nos enfocaremos?

Lima (fase inicial) con proyección a principales ciudades del país una vez validado el flujo.

**When (Cuándo)**

#### ¿Cuándo sucede el problema?

A diario, con picos en campañas y temporadas (Cyber, Black Friday, Navidad, quincenas).

#### ¿Cuándo utiliza el cliente el producto?

Al crear/etiquetar envíos, consultar el tracking y exportar reportes para decisiones operativas.

**Why (Por qué)**

#### ¿Cuál es la causa del problema?

Las principales causas del problema incluyen la fragmentación de herramientas (múltiples portales de courier y planillas sin una vista única), la baja madurez digital de micro y pequeñas empresas que mantienen procesos manuales, y la variabilidad del desempeño logístico entre transportistas, lo que exige contar con datos comparables para decidir por destino; además, la escasa analítica de tiempos y costos dificulta identificar mejoras y tomar decisiones oportunas.

**How (Cómo)**

##### ¿En qué condiciones los clientes usan nuestro producto?

Los clientes usarán Sendifi a través de una aplicación web ligera y fácil de usar desde dispositivos con conexión a internet. La plataforma permitirá crear órdenes con datos de remitente/destinatario y generar un código interno; consultar un timeline con estados normalizados y recibir alertas por retrasos o devoluciones; además, ofrecerá un cotizador de tarifas (peso/destino/servicio), gestión de clientes y direcciones frecuentes con autocompletar, y reportes de costos/tiempos con exportación a PDF/CSV.

**How much (Cuánto)**

##### Estadísticas que sustentan la problemática.

El e‑commerce peruano movió del orden de US$ 13 mil millones en 2023 y cerca de la mitad de peruanos compra en línea, lo que incrementa la presión sobre la última milla y la gestión de envíos para pequeños vendedores.<br><br>
El 74% de compradores online en Perú prioriza el tiempo de entrega como factor decisivo para repetir compra; la visibilidad y cumplimiento logístico es crítico para retención.<br><br>
Perú obtuvo en 2023 un LPI ≈ 3.0 (rank ~61), reflejando brechas de desempeño logístico frente a países líderes y oportunidades de mejora en timeliness y trazabilidad.<br><br>
La madurez digital de micro (48%) y pequeñas (51%) empresas es inferior a la de medianas/grandes, lo que refuerza la necesidad de herramientas simples y centralizadas.
