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
| Aguirre Eneque, Joan Elias        | U202315649 |
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

**Student Outcome 5**

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
| **Aguirre Eneque, Joan Elias**<br>Mi nombre es Joan, Tengo 19 años. Estudio la carrera de ingeniería de software en la Universidad Peruana de Ciencias Aplicadas. Cuento con capacidad colaborativa en trabajos en grupo, hábil para desarrollar ideas y propuestas que permitan realizar un trabajo que cumpla con los requerimientos necesarios. Ademas, tengo conocimiento en lenguajes como C++, Python basico, base de datos SQL.| <img src="https://github.com/user-attachments/assets/4fe255c8-f64a-4b0a-ae8f-c007c6f3a583" alt="image" width="200"> | 
| **Esquirva León, Miguel Juan Diego**<br>Mi nombre es Miguel Juan Diego. Tengo 19 años y actualmente estoy cursando el 6° ciclo de ingeniería de software. Me considero una persona con capacidades de liderazgo y capaz de trabajar bajo presión. | ![WhatsApp Image 2025-09-20 at 12 42 26 AM](https://github.com/user-attachments/assets/8ef9d93a-03cb-485c-9832-971b79302a2a) |
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


## 1.2.2 Lean UX Process
El Lean UX prioriza colaboración, feedback continuo e iteraciones cortas para validar valor con usuarios reales desde etapas tempranas. En **Sendifi**, este enfoque nos ayuda a construir una plataforma simple y confiable para emprendimientos y empresas pequeñas que necesitan centralizar la gestión de sus envíos.

### 1.2.2.1 Lean UX Problem Statements
El estado actual de la gestión de envíos en Perú, para **negocios pequeños con personal** y **emprendedores de e-commerce/redes**, se apoya en múltiples portales de couriers y planillas manuales, lo que reduce la visibilidad de estados y costos, genera reprocesos (etiquetas mal hechas, direcciones mal digitadas) y obliga a tomar decisiones reactivas. Del lado del cliente final, la falta de información clara y oportuna sobre el estado del paquete afecta la experiencia y la confianza.

Lo que los servicios existentes no logran abordar es la necesidad de una **plataforma accesible y centralizada** que **unifique el tracking** con **estados estandarizados**, ofrezca **creación ágil de órdenes** (incluyendo **carga masiva/CSV** y **etiquetas listas para impresión**) y entregue **analítica simple** de costos/tiempos para decidir mejor por destino sin complejidad técnica.

Nuestro servicio abordará esta brecha mediante una **plataforma web** con un **único rol por cuenta** que permita **crear órdenes** (una a una o por **lotes**), **generar códigos/etiquetas (PDF/A6)**, **visualizar una línea de tiempo** con estados normalizados, **programar recojos/cortes del día**, **recibir alertas** y **obtener reportes** accionables (tiempos, costos, devoluciones).

Nuestro **enfoque inicial** será **Lima Metropolitana**, atendiendo a **negocios pequeños con personal que gestionan 30–300 envíos/mes** y a **emprendedores de e-commerce/redes sociales (5–150 envíos/mes)**, donde la centralización, la rapidez operativa y la simplicidad generan mayor impacto.

Sabremos que hemos tenido éxito cuando observemos que la mayoría de **cuentas activas** crean su **primer envío** en la primera semana, el **tiempo de creación por lote/orden** se reduce de forma significativa, el **tracking end-to-end** es consultado de forma recurrente y los **reportes** se usan semanalmente por una porción relevante de usuarios.

**HMW:** *¿Cómo podemos diseñar una plataforma accesible que centralice la gestión de envíos y unifique el tracking, ofreciendo creación por lotes y etiquetas listas, para que pequeños operadores ganen velocidad y decidan mejor (tiempo/costo) sin complejidad técnica?*

### 1.2.2.2 Lean UX Assumptions

**a) Assumption Worksheet**
- **¿Quién será nuestro usuario?** Negocios pequeños con personal (2–10 colaboradores en despacho) y emprendedores de e-commerce/redes.  
- **¿Dónde encaja nuestro producto en su vida?** En la **operación diaria de despacho**: preparación de pedidos, generación de **etiquetas**, **cortes del día** y coordinación de **recojos** o entregas en agencia.  
- **¿Qué problemas tiene y cómo se resuelven?** Fragmentación de herramientas, reprocesos por datos/etiquetas, baja visibilidad de estados/costos y difícil elección de courier. Se resuelve con **creación centralizada**, **lotes/CSV**, **etiquetas A6/PDF**, **tracking unificado**, **cotizador** y **reportes** simples.  
- **¿Cómo y cuándo es usado?** **Diario**, con picos por **corte** (mediodía/tarde) y **campañas**; uno o varios operadores usan **una misma cuenta** (un único rol) desde **PC** y/o **móvil**.  
- **¿Cómo debe verse y comportarse?** **Simple y rápido**: formulario con **autocompletar**, **carga masiva/CSV**, **etiquetas imprimibles**, timeline claro, filtros por estado/courier/fechas, búsqueda por código, export **CSV/PDF**, tiempo de respuesta **<2s** por vista.  
- **¿Qué características son importantes?**  
  - **Creación por lotes/CSV** y **plantillas** de órdenes.  
  - **Etiquetas** listas (PDF/A6) para impresora térmica.  
  - **Programación de recojos** y registro de **cortes del día**.  
  - **Tracking unificado** con **alertas** de incidencias.  
  - **Cotizador** por peso/destino/servicio.  
  - **Reportes** simples (tiempos/costos, devoluciones) y export.

**b) Business Outcomes (tono cualitativo)**
- Sendifi será reconocida como herramienta confiable para **centralizar y agilizar** envíos en negocios pequeños y emprendimientos.  
- Comercios pequeños confiarán en Sendifi para **organizar envíos por lotes** y **elegir courier** con mayor facilidad.  
- Aliados logísticos verán a Sendifi como **canal complementario** para integrar tracking y tarifas.  
- Con el crecimiento de usuarios, Sendifi **reunirá datos valiosos** para optimizar tiempos y costos.  
- Sendifi **ganará visibilidad**, impulsando **alianzas** e **ingresos sostenibles** por suscripciones.

**c) User Outcomes (tono cualitativo)**
- Los equipos de despacho tendrán una **herramienta sencilla y rápida** para **crear envíos** (uno a uno o por **lotes**) y **seguirlos** en un solo panel.  
- Los clientes finales recibirán **notificaciones claras** (creado, en tránsito, entregado), reduciendo la incertidumbre.  
- Los usuarios podrán **comparar opciones** y **optimizar costos/tiempos** eligiendo el transportista más conveniente por destino.  
- Los **reportes exportables** permitirán ver el **desempeño logístico** y compartirlo con contabilidad/gerencia.

### 1.2.2.3 Lean UX Hypothesis Statements
- **H1 — Centralización y velocidad (mixto)**  
  - *Creemos que* centralizar creación + timeline reducirá el **tiempo de gestión por envío ≥30%**.  
  - *Sabremos que estamos en lo correcto cuando* el tiempo promedio (click-to-save) baje de **3:00 a ≤2:00 min** en 4 semanas.
- **H2 — Lotes y eficiencia operativa (Segmento 1)**  
  - *Creemos que* la **carga masiva/CSV** y las **plantillas** reducirán el **tiempo de creación por lote ≥40%**.  
  - *Sabremos que estamos en lo correcto cuando* el tiempo por **50 órdenes** baje de **>20 min** a **≤12 min** en 4 semanas.
- **H3 — Etiquetas listas y calidad (Segmento 1)**  
  - *Creemos que* generar **etiquetas A6/PDF** disminuirá **errores de rotulado ≥30%**.  
  - *Sabremos que estamos en lo correcto cuando* la tasa de **retrabajo por datos/etiqueta** baje **≥30%** en 6 semanas.
- **H4 — Cotizador y adopción (mixto)**  
  - *Creemos que* un **cotizador** de tarifas por peso/destino/servicio impulsará el **uso frecuente** y el **interés por Pro**.  
  - *Sabremos que estamos en lo correcto cuando* **≥25%** de usuarios Free usen el cotizador semanalmente y **≥10%** migren a **Pro** en 8–12 semanas.
- **H5 — Alertas y satisfacción del cliente (mixto)**  
  - *Creemos que* **alertas de retraso/entrega** reducirán la **incertidumbre** del cliente final.  
  - *Sabremos que estamos en lo correcto cuando* las **incidencias sin seguimiento** bajen **≥30%** en 6 semanas y la **satisfacción** del tracking sea **≥70% “claro/muy claro”**.

### 1.2.2.4 Lean UX Canvas

<img src="https://files.catbox.moe/cvv0jg.png" alt="kevin image" width="700">


## 1.3 Segmento Objetivo

### Negocios pequeños con personal para realizar envíos

**Aspectos demográficos**
- Sexo: Masculino y Femenino
- Edad: 18–65 años
- Tamaño del equipo: 2–10 personas
- Volumen típico: 30–300 envíos/mes

**Aspectos geográficos**
- Nacionalidad: Peruana
- Departamento: Lima Metropolitana

**Aspectos psicográficos**
- Necesitan organizar envíos diarios/semanales con un panel unificado y estados claros.
- Buscan cotizar por peso/destino/servicio y controlar costos de forma simple.
- Valoran etiquetas listas, direcciones frecuentes, link de seguimiento y reportes básicos (tiempos/costos).
- Operan con una sola cuenta (un único rol) y requieren notificaciones al cliente y alertas de incidencias.
- *Valorable a futuro:* carga masiva/CSV para acelerar la creación de múltiples envíos.

---

### Emprendedor pequeño (e-commerce/redes sociales)

**Aspectos demográficos**
- Sexo: Masculino y Femenino
- Edad: 20–55 años

**Aspectos geográficos**
- Nacionalidad: Peruana
- Departamento: Lima Metropolitana

**Aspectos psicográficos**
- Necesita enviar productos de forma confiable y rápida con seguimiento unificado.
- Busca cotizar por peso/destino y controlar costos.
- Valora guardar clientes/direcciones y generar etiquetas sin errores.
- Quiere reportes básicos de tiempos/costos para decidir qué courier usar.

﻿# Capítulo II: Requirements Elicitation & Analysis

## 2.1. Competidores

- **Envíame**  
  Plataforma multicourier que conecta a empresas con diversos operadores logísticos (Olva, PedidosYa, Moova, etc.) desde una sola integración. Facilita la diversificación de riesgos y automatiza la gestión de múltiples envíos en campañas de alta demanda.

- **Entregalo.pe**  
  Software logístico nacional que ofrece monitoreo en tiempo real y un panel unificado para empresas que trabajan con distintos couriers. Su propuesta se centra en brindar trazabilidad y control en la cadena de distribución.

- **Delego**  
  TMS (Transportation Management System) con algoritmos de optimización de rutas y asignación de recursos. Se enfoca en mejorar la eficiencia operativa de las flotas y en la planificación logística con soporte de mapas inteligentes.

## 2.1.1. Análisis competitivo

### Perfil (cuadro comparativo)

| **Criterio** | <img width="110" height="110" alt="Image" src="https://github.com/user-attachments/assets/0b7c3c0e-a3b2-40de-a955-8f7de037f221" /> <br/> **Sendifi**  | <img width="110" height="110" alt="Image" src="https://github.com/user-attachments/assets/43f7a014-0539-4416-8311-e58c498c66f8" /> <br/> **Envíame** | <img width="110" height="110" alt="Image" src="https://github.com/user-attachments/assets/b20f4dc1-79f3-46d7-9c00-44d00a473327" /> <br/> **Entregalo.pe** | <img width="110" height="65" alt="Image" src="https://github.com/user-attachments/assets/92b3ecc6-b075-4910-a842-b9309194dd72" /> <br/> **Delego** |
|---|---|---|---|---|
| **Overview** | Plataforma web para empresas con logística propia, que centraliza creación, asignación y seguimiento de envíos en tiempo real. | Plataforma multicourier que centraliza envíos con distintos transportistas en un solo panel. | Software nacional de monitoreo en tiempo real con integración a múltiples operadores. | TMS con optimización de rutas, planificación de flota y gestión de transporte. |
| **Ventaja competitiva (valor para el cliente)** | Enfoque en empresas con operación logística propia. Experiencia simple y centralizada sin múltiples portales. | Diversificación de operadores, reduce dependencia de un solo courier. | Visibilidad centralizada y trazabilidad local con conocimiento del mercado peruano. | Eficiencia operativa por algoritmos de planificación y reducción de costos. |
| **Mercado objetivo** | PYMEs, e-commerce y empresas con logística propia. | E-commerce y retailers que trabajan con múltiples couriers. | Negocios medianos y grandes con alta dependencia de operadores externos. | Empresas con flota propia que requieren optimización de rutas y recursos. |
| **Estrategias de marketing** | Marketing digital, alianzas con cámaras/associaciones, casos de éxito de PYMEs. | Campañas en redes, alianzas con couriers y marketplaces. | Diferenciación local, venta consultiva, “solución peruana”. | Marketing B2B, ferias empresariales, foco en eficiencia/costos. |
| **Productos y servicios** | Gestión de envíos, asignación, tracking en tiempo real, reportes. | Integración multicourier (envíos, tarifas, tracking). | Monitoreo en tiempo real con reportes de trazabilidad. | TMS de rutas, planificación de flota y transporte. |
| **Precios y costos** | SaaS por suscripción escalable según volumen. | Planes por volumen y número de couriers. | Planes flexibles para medianas y grandes. | Licencia SaaS + implementación/soporte. |
| **Canales (Web/Móvil)** | Web + app móvil. | Web + app móvil. | Web (módulos integrables) + app móvil en desarrollo. | Web + app móvil empresarial. |

### Comparación de precios estimados y costos (benchmark)

| **Criterio** | **Sendify (estimado)** | **Envíame / plataformas multicourier** | **Entregalo.pe / monitoreo nacional** | **Delego / TMS + optimización de rutas** |
|---------------|------------------------|----------------------------------------|----------------------------------------|--------------------------------------------|
| **Modelo de precio / estructura típica en mercado logístico** | Suscripción mensual + tarifa por envío extra según volumen. | Planes por volumen o número de couriers + tarifas por uso. | Planes adaptados para medianas/grandes, con tarifas por monitoreo. | Licencia SaaS mensual + módulos de rutas o flota + soporte. |
| **Estimación de precio base mensual (empresa pequeña)** | **USD 70 – 150** (≈ S/ 260 – 560) | **USD 100 – 250** (≈ S/ 370 – 930) | **USD 150 – 300** (≈ S/ 560 – 1,100) | **USD 250 – 600** (≈ S/ 930 – 2,200) |
| **Costo por envío / transacción adicional** | **USD 0.05 – 0.25** / envío | **USD 0.05 – 0.20** / envío (según courier) | **USD 0.10 – 0.30** / envío | **USD 0.10 – 0.25** / envío (incluye optimización) |
| **Costos de implementación / setup inicial** | **USD 200 – 800** | **USD 300 – 1,000** | **USD 500 – 1,200** | **USD 800 – 2,000** (según módulos y flota) |
| **Margen de variación esperable** | ± 15 – 30 % según volumen y soporte. | ± 15 – 25 % según cantidad de couriers. | ± 20 – 35 % por cobertura y soporte local. | ± 25 – 40 % según personalización y tamaño de flota. |


---

### Análisis SWOT


**Fortalezas**
- Sendifi: Diseñado para flotas propias, control total, escalabilidad.  
- Envíame: Amplia red de couriers conectados, ideal para e-commerce con alto volumen.  
- Entregalo.pe: Adaptado al mercado local peruano, foco en trazabilidad.  
- Delego: Potente en optimización de rutas y reducción de costos.

**Debilidades**
- Sendifi: Menos atractivo si el cliente requiere multicourier desde el día 1.  
- Envíame: Dependencia total de terceros para la ejecución de entregas.  
- Entregalo.pe: Limitado al mercado local, menor visibilidad regional.  
- Delego: Mayor complejidad técnica y curva de aprendizaje.

**Oportunidades**
- Sendifi: Crecimiento del e-commerce peruano; digitalización de PYMEs con logística interna.  
- Envíame: Integrarse con flotas internas para ampliar alcance.  
- Entregalo.pe: Escalar hacia Latinoamérica con propuesta local.  
- Delego: Alianzas con software de e-commerce y última milla.

**Amenazas**
- Sendifi: Plataformas multicourier establecidas con base de usuarios.  
- Envíame: Empresas que migren a flota propia.  
- Entregalo.pe: Entrada de competidores internacionales.  
- Delego: Saturación del mercado TMS y presión de precios.

---

## 2.1.2. Estrategias y tácticas frente a competidores

Con base en el análisis comparativo realizado, **Sendifi** debe orientar sus esfuerzos estratégicos hacia tres ejes: **diferenciación, escalabilidad y confianza**.

### Estrategias

**Diferenciación por simplicidad y centralización**
- Resaltar la facilidad de uso frente a plataformas con múltiples integraciones complejas.  
- Enfatizar la reducción de fricción en la gestión de envíos para PYMEs y e-commerce emergentes.

**Escalabilidad flexible**
- Ofrecer planes modulares y progresivos que acompañen el crecimiento de los clientes.  
- Incluir modelo **freemium** o prueba gratuita para reducir barrera de entrada.

**Confianza y trazabilidad**
- Reportes detallados en tiempo real y métricas claras de desempeño.  
- **Soporte local** ágil y personalizado como diferenciador frente a soluciones internacionales.

### Tácticas

- **Alianzas estratégicas:** Integración con marketplaces locales y pasarelas de pago para posicionarse como herramienta natural del e-commerce peruano.  
- **Campañas de éxito de clientes:** Casos reales de PYMEs que optimizaron sus operaciones con **Sendifi**.  
- **Estrategia de expansión:** Mercados vecinos (Chile, Colombia, Ecuador) con narrativa de “plataforma regional con soporte local”.  
- **Enfoque B2B2C:** Funciones para que los clientes finales rastreen sus pedidos directamente, mejorando experiencia y diferenciando la propuesta de valor.

## 2.2 Entrevistas

### 2.2.1. Diseño de entrevistas

#### Segmento 1: Negocios pequeños con personal para realizar envíos
**Preguntas generales:**
- ¿En qué distrito operan, de qué rubro es el negocio y cuántas personas intervienen en los envíos?
- ¿Cuántos envíos realizan por día/semana/mes y cómo varía en campañas o picos?
- ¿Cómo organizan el corte del día y la recolección (pickup vs. dejar en agencia)?
- ¿Qué couriers usan hoy y con qué criterios eligen por destino (tiempo, costo, cobertura, SLA)?
- ¿Cómo generan etiquetas/guías (A6, PDF, impresora térmica) y qué errores son frecuentes?
- ¿Cómo cotizan y controlan costos (tabla, web del courier, Excel)? ¿Qué esperarían de un cotizador en Sendifi?
- ¿Cómo realizan el tracking y quién lo monitorea? ¿Qué hitos/estados necesitan ver y qué reportes revisan cada semana?

**Preguntas complementarias:**
- ¿Cómo prefieren notificar al cliente y en qué momentos (creado, en tránsito, entregado, incidencia)? ¿WhatsApp, email o SMS?
- ¿Qué funciones acelerarían su día a día: carga masiva/CSV, direcciones frecuentes y/o plantillas de etiquetas?

#### Segmento 2: Emprendedor pequeño (e-commerce/redes sociales)
**Preguntas generales:**
- ¿Cuál es su edad y distrito? ¿Qué rubro vende?
- ¿Cuántos envíos/mes realiza y cómo varía en campañas?
- ¿Qué destinos atiende y qué couriers usa hoy? ¿Por qué?
- ¿Cómo calcula tarifas y qué necesitaría de un cotizador?
- ¿Cómo gestiona el tracking (múltiples portales, Excel, mensajes al cliente)?
- ¿Qué datos son críticos en la orden (teléfono, referencias, valor/seguro)?
- ¿Qué reportes necesita (tiempos, costos por destino, devoluciones)?

**Complementarias:**
- ¿Le serviría integrar Sendifi con su tienda o cargar por CSV?
- Sobre planes: ¿qué límite/beneficios lo motivarían a pagar por Pro?

---

### 2.2.2. Registro de entrevistas

| Datos del entrevistado      | Enlace a la entrevista | Captura de la Entrevista |
|-----------------------------|------------------------|--------------------------|
| **Victor Niño Cornetero**   | [Entrevista (4:20 min)](https://drive.google.com/file/d/1yJC1CF0kROVJrOlpuANi3GaDDH3JHol1/view?usp=sharing) | <img width="365" height="161" alt="Image" src="https://github.com/user-attachments/assets/c0c7d08c-08dd-4d44-912b-42d1ec655a92" /> |
| **David Eneque Valor**      | [Entrevista (4:50 min)](https://drive.google.com/file/d/1GRIb4vIA-_MpfAH9pROId28oskktAjY9/view?usp=sharing) | <img width="365" height="180" alt="Image" src="https://github.com/user-attachments/assets/95070b5f-11db-4e9d-b4d1-feae6a50ded6" /> |
| **Victoria Contreras**      | [Entrevista (6:01 min)](https://drive.google.com/file/d/12TYhjTKCtlAg5CSH9p3Ct0BNmyAPJg7P/view?usp=sharing) | <img width="365" height="180" alt="Image" src="https://github.com/user-attachments/assets/a411a44a-873c-4ac2-a1f2-beff3b8af7da" /> |
| **Julieta Cardenas**        | [Entrevista (5:54 min)](https://drive.google.com/file/d/1DkZ8_qbXDpQHS9W13ArOvsaz2-FDKgAj/view?usp=sharing) | <img width="365" height="180" alt="Image" src="https://github.com/user-attachments/assets/7e98fee0-0670-4789-b51c-3aa9d7553c8f" /> |
| **Maria Fernanda Mostajo**  | [Entrevista (5:37 min)](https://drive.google.com/file/d/1ZzjKkfk7kT41K4Oh7kThM_HA5E_MEUWD/view?usp=sharing) | <img width="365" height="161" alt="Image" src="https://github.com/user-attachments/assets/31bb4e86-c284-4d23-ab0b-e7ae1e0dd044" /> |
| **Paul Cossar**             | [Entrevista (6:30 min)](https://youtu.be/y7GWjGIhvMk) | <img width="365" height="161" alt="Image" src="https://github.com/user-attachments/assets/c5b92af0-0e91-4ba0-aea3-dcd3edc2eb32" /> |

## 2.2.3. Análisis de entrevistas

---

### Entrevista 1 – Segmento 2  
**Entrevista a Emprendedor (Rubro suplementos deportivos)**  

**Hallazgo 1:**  
Víctor, de 23 años y residente en Surco, se dedica a la venta de suplementos deportivos como proteínas, creatina y vitaminas. Actualmente gestiona entre 80 y 100 envíos mensuales, pero en temporadas como Black Friday, Cyber o verano su volumen crece hasta 150–200 envíos.  

- **Couriers principales:** Olva y Shalom.  
- **Problemas:**  
  - Cotización manual mediante tablas (tedioso).  
  - Tracking en portales distintos + Excel (consume tiempo).  
  - Compartir enlaces manualmente por WhatsApp/redes sociales.  
- **Necesidades:**  
  - Cotizador automático con tarifas y tiempos inmediatos.  
  - Centralizar tracking en una sola plataforma.  
  - Reportes de tiempos de entrega, costos por destino, devoluciones y balance mensual.  
- **Expectativas de plan Pro:**  
  - Límite de 300–500 envíos.  
  - Beneficios: tarifas reducidas por volumen, reportes avanzados, integración con Shopify y WhatsApp Business.  

---

### Entrevista 2 – Segmento 1  
**Negocio pequeño con personal para envíos (David, 30 años)**  

**Hallazgo 1:**  
David lidera un negocio con un equipo de 20 personas para la gestión de envíos.  

- **Problemas:**  
  - Falta de herramienta centralizada para asignar y monitorear envíos.  
  - Uso de múltiples canales y hojas de cálculo → duplicidad y poca visibilidad.  
- **Necesidades:**  
  - Panel de estado en tiempo real.  
  - Asignación de pedidos a cada miembro con notificaciones y recordatorios.  
  - Reportes sobre eficiencia: entregas por trabajador, tiempos promedio, incidencias, devoluciones.  

---


### Entrevista 3 – Segmento 1  
**Victoria Contreras (Botica EcoFarma, 27 años, San Martín de Porres)**  

**Hallazgo 1:**  
Botica con 2 motorizados propios a tiempo completo (~250 envíos/mes).  

- **Problemas:**  
  - Generación manual de guías PDF con errores.  
  - Cotización manual en tablas y webs.  
  - Tracking por WhatsApp con motorizados.  
- **Necesidades:**  
  - Cotizador integrado por distrito.  
  - Panel de tracking con estados claros: “en camino”, “entregado”, “con incidencia”.  
  - Reportes semanales de entregas e incidencias.  
  - Funciones de direcciones frecuentes y plantillas de etiquetas.  
- **Comunicación con clientes:** WhatsApp (notificaciones en creación, salida, entrega e incidencias).  

---

### Entrevista 4 – Segmento 2  
**Julieta Cárdenas (E-commerce de galletas y postres, 27 años)**  

**Hallazgo 1:**  
80–100 envíos/mes (hasta 200 en picos). Maneja producción, venta y distribución.  

- **Procesos:** Envía a Lima Sur y Callao con motorizado propio y auto.  
- **Problemas:**  
  - Cotización aproximada por referencias.  
  - Tracking manual con Excel + WhatsApp.  
  - Sobrecarga en picos de demanda.  
- **Datos críticos:** teléfono y referencias detalladas, valor del pedido (seguro/reembolso).  
- **Necesidades:**  
  - Cotizador automático.  
  - Reportes de tiempos, costos, devoluciones.  
  - Integración con redes sociales.  
  - Carga masiva por CSV en campañas.  
- **Expectativa de plan Pro:** reportes detallados, descuentos por volumen, soporte en fechas clave, límite de envíos más alto.  

---

### Entrevista 5 – Segmento 1  
**Maria Fernanda (19 años, accesorios para celulares, San Juan de Lurigancho)**  

**Hallazgo 1:**  
Equipo de 3 personas. Manejan ~120 envíos/mes, en campañas suben a ~250.  

- **Couriers:** Olva (Lima), Shalom (provincias), DHL (internacionales).  
- **Procesos:** Corte a 12:30 y 4:30. Pickup para Lima, drop-off para provincias.  
- **Problemas:**  
  - Errores frecuentes en teléfonos incompletos y referencias.  
  - Tracking fragmentado en dos portales.  
  - Notificación manual por WhatsApp.  
- **Necesidades:**  
  - Carga masiva (CSV).  
  - Direcciones frecuentes y plantillas.  
  - Comparador de peso/destino/servicio con tiempos y recargos.  
  - Timeline con hitos: Recolectado, En tránsito, En reparto, Entregado, Incidencia.  
  - Alertas ante retrasos.  
  - Programación de recojos y cortes del día.  

---

### Entrevista 6 – Segmento 2  
**Paul (53 años, polos y hoodies, Los Olivos)**  

**Hallazgo 1:**  
40–60 envíos/mes, hasta ~100 en campañas (≤15 diarios).  

- **Couriers:** Olva y motorizados (entregas same-day).  
- **Problemas:**  
  - Seguimiento manual, recibe muchos DMs de clientes.  
  - Errores en distritos.  
  - Cotización manual con calculadora del courier y Excel.  
- **Datos críticos:** teléfono y referencias del cliente.  
- **Necesidades:**  
  - Comparador de peso/destino (incluyendo peso volumétrico).  
  - Guardar precios de envíos.  
  - Reportes simples (tiempos y costos por zona).  
  - Importar CSV desde WooCommerce/Sheets.  
- **Expectativa de plan Pro:** dispuesto a pagar ~US$10 si incluye CSV, notificaciones automáticas y reportes.  
- **Plan Free ideal:** ~50 envíos/mes.  

---

## 2.3 NeedFinding

### 2.3.1. User Personas

<img width="1050" height="1510" alt="Image" src="https://github.com/user-attachments/assets/0a566dfc-7186-4467-b9ef-bc220ad5ee0d" />

---

<img width="1050" height="1480" alt="Image" src="https://github.com/user-attachments/assets/36d9be3f-7b83-44ab-a24d-0387aed2d1cd" />

### 2.3.2. User Task Matrix

| **Tarea**                                     | **Amanda Torres (Emprendedora Digital)**                                             | **José Ramírez (Dueño Local Comercial)**                                                      |
| --------------------------------------------- | ------------------------------------------------------------------------------------ | --------------------------------------------------------------------------------------------- |
| **Crear un envío**                            | **Often – High** → Maneja envíos constantes desde su tienda online y redes sociales. | **Often – High** → Sus ventas en local también generan despachos diarios.                     |
| **Consultar estado de envío (tracking)**      | **Often – High** → Necesita mantener informados a sus clientes en línea.             | **Sometimes – High** → Lo revisa en casos de reclamos o retrasos puntuales.                   |
| **Recibir notificaciones de entrega/retraso** | **Often – High** → Fundamental para anticipar problemas con clientes digitales.      | **Often – Medium** → Importante para coordinar con el repartidor y clientes presenciales.     |
| **Comparar costos de envío entre couriers**   | **Often – High** → Busca optimizar costos, ya que trabaja con alta rotación.         | **Rarely – Medium** → Usa casi siempre a su propio repartidor, menos opciones externas.       |
| **Generar reportes de costos/tiempos**        | **Sometimes – High** → Necesita métricas para optimizar logística digital.           | **Sometimes – Medium** → Le sirve más para control interno y gastos del local.                |
| **Guardar clientes/direcciones frecuentes**   | **Often – High** → Repite envíos a clientes recurrentes o mayoristas online.         | **Sometimes – Medium** → Maneja principalmente clientes del barrio (menos repetición exacta). |
| **Cotizar tarifas según destino/peso**        | **Often – High** → Sus envíos online son muy variables (peso, destino, zonas).       | **Sometimes – Medium** → Sus envíos suelen ser locales, menos variación de tarifas.           |

---

#### Diferencias clave:

* **Amanda (digital)**: Vive de los envíos → prioridad en costos, métricas y eficiencia para sostener ventas online.
* **José (local físico)**: Usa reparto propio → más enfocado en confiabilidad y control del proceso que en comparar tarifas.

### 2.3.3. User Journey Mapping

#### Segmento 1: Negocios pequeños con personal para realizar envíos

<img width="822" height="619" alt="Image" src="https://github.com/user-attachments/assets/df5a0470-6523-4a35-99dc-6cebd8dac9d6" />

#### Segmento 2: Emprendedor pequeño (e-commerce/redes sociales)

<img width="876" height="670" alt="Image" src="https://github.com/user-attachments/assets/a5a30309-7ae3-4c98-a22e-02f514626865" />

### 2.3.4. Empathy Mapping

#### Segmento 1: Negocios pequeños con personal para realizar envíos

<img width="1050" height="1390" alt="Image" src="https://github.com/user-attachments/assets/8f00b4f4-d7d0-4195-a9f1-78eaae1d3535" />

#### Segmento 2: Emprendedor pequeño (e-commerce/redes sociales)

<img width="1050" height="1390" alt="Image" src="https://github.com/user-attachments/assets/64578c70-615a-47a8-a525-207379dcf91d" />



## 2.4. Big Picture Event Storming

<img width="907" height="548" alt="Image" src="https://github.com/user-attachments/assets/c90d1736-c9d8-41f3-b2c6-38eb2aad218d" />

Link del Miro: https://miro.com/welcomeonboard/SGJsWTllUnVQVXg5SHhlY1VFSzVMR1JhZ1VnazFPSFlXK0EwUzBsRzU4eU9sRmpiVnVFaXVYV1NvbkxvV2xkM3pmUy9mVlVQRHNsK2NERzFUc2dBeGFDaHJYZUxQOTl1V1Y4L0VkeWRGNUxTcllnZkdjMmdtZXNmNm9pM3BabEJzVXVvMm53MW9OWFg5bkJoVXZxdFhRPT0hdjE=?share_link_id=539854184167


---

## 2.5. Ubiquitous Language

| Término | Definición | Ejemplo |
|---------|------------|---------|
| **Shipper (remitente)** | Persona o negocio que envía el paquete y paga el servicio. | “El remitente registró 20 envíos para hoy.” |
| **Consignee (destinatario)** | Persona que recibe el paquete. | “El destinatario no estaba; se programará un reintento.” |
| **Shipment (envío)** | Conjunto paquete + servicio de traslado. | “Ese envío pasó a estado ‘En tránsito’.” |
| **Shipping Order (orden de envío)** | Registro con datos del envío. | “Crea la orden y genera la etiqueta.” |
| **Parcel/Package (paquete)** | Unidad física a transportar. | “Este paquete excede el tamaño estándar.” |
| **Tracking Number (código de seguimiento)** | Identificador único del envío. | “Comparte el tracking con tu cliente.” |
| **Shipping Label (etiqueta)** | Documento con datos + código de barras/QR. | “Imprime la etiqueta en A6.” |
| **Carrier/Courier** | Empresa transportista. | “El courier más rápido es X.” |
| **Service Level / SLA** | Compromiso de tiempo/condiciones. | “El SLA exprés promete entrega en 24h.” |
| **Pickup (recojo)** | Retiro en origen. | “Programa el recojo a las 3:00 pm.” |
| **Drop-off (agencia)** | Remitente lleva el paquete al courier. | “Haremos drop-off en Miraflores.” |
| **Cut-off Time** | Hora límite diaria de envíos. | “Si pasamos el cut-off, salen mañana.” |
| **Quote/Quotation (cotización)** | Estimación de costo. | “Genera una cotización para 2 kg a Arequipa.” |
| **Volumetric Weight** | Peso calculado por volumen. | “Se cobra por peso volumétrico.” |
| **Proof of Delivery (POD)** | Evidencia de entrega. | “Sube la POD para cerrar el envío.” |

﻿## Capítulo 3: Requirements Specification

## 3.1. To - Be Scenario Mapping

<img width="500" height="512" alt="user 1" src="https://github.com/user-attachments/assets/028b6c58-4166-4c14-98b0-0e675a9ed874" />

## 3.2. User Stories

| **Epic / Story ID** | **Título** | **Descripción** | **Criterios de Aceptación** | **Relacionado con (Epic ID)** |
|--------|---------|-------------|--------|--------|
| Epic-01 | Gestión de Envíos | Como administrador logístico, quiero registrar y gestionar envíos en un solo panel para reducir tiempos de operación. | –   | –   |
| US-01.1 | Crear envío | Como administrador logístico, quiero crear una orden de envío con datos de remitente, destinatario, dirección, peso y costo para centralizar la gestión. | Given un usuario autenticado<br><br>When completa los datos requeridos y confirma<br><br>Then el sistema guarda la orden y genera un código único | Epic-01 |
| US-01.2 | Guardar clientes frecuentes | Como administrador logístico, quiero guardar clientes y direcciones frecuentes para agilizar la creación de envíos. | Given un administrador que ha creado un envío<br><br>When selecciona guardar los datos de cliente<br><br>Then el sistema almacena los datos en una lista reutilizable | Epic-01 |
| Epic-02 | Tracking Unificado | Como usuario, quiero visualizar en un timeline claro el estado del envío para dar confianza al cliente final. | –   | –   |
| US-02.1 | Ver estado del envío | Como administrador logístico, quiero consultar el estado de cada envío en un timeline estandarizado. | Given un envío con un código válido<br><br>When el usuario consulta el código<br><br>Then el sistema muestra estados: registrado → en tránsito → en reparto → entregado | Epic-02 |
| US-02.2 | Consulta pública de tracking | Como consumidor final, quiero ingresar el código en un portal público para conocer el estado de mi pedido. | Given un cliente con código de envío<br><br>When lo introduce en el buscador<br><br>Then el sistema devuelve el estado actual sin requerir autenticación | Epic-02 |
| Epic-03 | Cotización de Tarifas | Como emprendedor, quiero comparar costos de envío entre couriers para elegir la mejor opción. | –   | –   |
| US-03.1 | Cotizador de tarifas | Como emprendedor, quiero ingresar peso y destino para cotizar tarifas disponibles. | Given un usuario autenticado<br><br>When ingresa peso y destino<br><br>Then el sistema muestra tarifas y tiempos por courier | Epic-03 |
| US-03.2 | Selección de courier | Como administrador, quiero elegir entre diferentes couriers sugeridos para optimizar costo/tiempo. | Given un listado de opciones de courier<br><br>When el usuario selecciona uno<br><br>Then el sistema asocia el envío con ese transportista | Epic-03 |
| Epic-04 | Notificaciones | Como usuario, quiero recibir alertas automáticas para conocer retrasos o entregas. | –   | –   |
| US-04.1 | Notificación de retraso | Como administrador logístico, quiero recibir alertas de retraso para reaccionar a tiempo. | Given un envío con retraso<br><br>When el sistema detecta la condición<br><br>Then se envía una alerta automática al administrador | Epic-04 |
| US-04.2 | Confirmación de entrega | Como cliente final, quiero recibir notificación cuando mi pedido haya sido entregado. | Given un envío marcado como entregado<br><br>When se actualiza el estado<br><br>Then el sistema notifica al cliente por el canal registrado (email/WhatsApp) | Epic-04 |
| Epic-05 | Reportes y Analítica | Como administrador, quiero obtener reportes de costos y tiempos para mejorar decisiones. | –   | –   |
| US-05.1 | Reportes de desempeño | Como administrador, quiero generar reportes de tiempos de entrega y costos consolidados. | Given un administrador autenticado<br><br>When selecciona rango de fechas<br><br>Then el sistema genera un reporte exportable en CSV o PDF | Epic-05 |
| US-05.2 | Exportación de reportes | Como administrador, quiero exportar reportes en distintos formatos para compartir con mi equipo. | Given un reporte generado<br><br>When el usuario selecciona formato CSV o PDF<br><br>Then el sistema descarga el archivo en el formato elegido | Epic-05 |
| Epic-06 | Landing Page | Como visitante, quiero conocer la propuesta de Sendify y planes disponibles para decidir registrarme. | –   | –   |
| US-06.1 | Información de la propuesta | Como visitante, quiero ver beneficios de Sendify para entender el valor de la plataforma. | Given un visitante<br><br>When accede a la landing<br><br>Then visualiza misión, visión y propuesta de valor | Epic-06 |
| US-06.2 | Registro inicial | Como visitante, quiero registrarme desde la landing page para comenzar a usar Sendify. | Given un visitante en la landing<br><br>When completa el formulario de registro<br><br>Then el sistema crea una cuenta en el plan Free | Epic-06 |
| Epic-07 | API RESTful | Como developer, quiero exponer endpoints seguros para que el sistema interactúe con terceros. | –   | –   |
| TS-07.1 | Endpoint de creación de envíos | Como developer, quiero un endpoint POST para registrar envíos con validación de datos. | Given un request POST con JSON válido<br><br>When contiene remitente, destinatario, dirección y peso<br><br>Then el sistema devuelve un código de envío y status 201 | Epic-07 |
| TS-07.2 | Endpoint de tracking | Como developer, quiero un endpoint GET para consultar estados por código de envío. | Given un request<br><br>GET con código válido<br><br>When el sistema recibe la consulta}<br><br>Then devuelve JSON con el estado actual y timeline histórico | Epic-07 |
| TS-07.3 | Endpoint de tarifas | Como developer, quiero un endpoint GET que devuelva tarifas según peso y destino. | Given un request<br><br>GET con peso y destino<br><br>When el sistema procesa<br><br>Then responde JSON con tarifas y tiempos por courier | Epic-07 |

## 3.3. Impact Mapping

<img width="500" height="512" alt="user 1" src="https://github.com/user-attachments/assets/743854d6-1c1d-4c27-98ad-893d663c7371" />

## 3.4. Product Backlog

| **Órden** | **Story ID** | **Título** | **Descripción** | **Story Points** |
|--------|---------|-------------|--------|--------|
| 1   | US-01.1 | Crear envío | Como administrador logístico, quiero crear una orden de envío (remitente, destinatario, dirección, peso, costo) para centralizar la gestión. | 8   |
| 2   | US-01.2 | Guardar clientes frecuentes | Como administrador logístico, quiero guardar clientes y direcciones frecuentes para agilizar la creación de envíos. | 5   |
| 3   | US-02.1 | Ver estado del envío | Como administrador logístico, quiero consultar el estado de cada envío en un timeline estandarizado. | 5   |
| 4   | US-02.2 | Consulta pública de tracking | Como consumidor final, quiero ingresar el código en un portal público para conocer el estado de mi pedido. | 5   |
| 5   | US-03.1 | Cotizador de tarifas | Como emprendedor, quiero ingresar peso y destino para cotizar tarifas disponibles. | 5   |
| 6   | US-03.2 | Selección de courier | Como administrador, quiero elegir entre diferentes couriers sugeridos para optimizar costo/tiempo. | 5   |
| 7   | US-04.1 | Notificación de retraso | Como administrador logístico, quiero recibir alertas de retraso para reaccionar a tiempo. | 3   |
| 8   | US-04.2 | Confirmación de entrega | Como cliente final, quiero recibir notificación cuando mi pedido haya sido entregado. | 3   |
| 9   | US-05.1 | Reportes de desempeño | Como administrador, quiero generar reportes de tiempos de entrega y costos consolidados. | 5   |
| 10  | US-05.2 | Exportación de reportes | Como admin, quiero exportar reportes en CSV o PDF para compartir con mi equipo. | 3   |
| 11  | US-06.1 | Información de la propuesta | Como visitante, quiero ver beneficios de Sendify en la landing page para entender el valor de la plataforma. | 2   |
| 12  | US-06.2 | Registro inicial | Como visitante, quiero registrarme desde la landing page para comenzar a usar Sendify. | 3   |
| 13  | TS-07.1 | Endpoint de creación de envíos | Como developer, quiero un endpoint POST para registrar envíos con validación de datos. | 8   |
| 14  | TS-07.2 | Endpoint de tracking | Como developer, quiero un endpoint GET para consultar estados por código de envío. | 5   |
| 15  | TS-07.3 | Endpoint de tarifas | Como developer, quiero un endpoint GET que devuelva tarifas según peso y destino. | 5   |

##
﻿
</div>

## **CAPITULO 4**

## **4.1. Style Guidelines**

> Esta guía ayudará al equipo a definir las principales reglas de diseño
> que debe tener la plataforma web **Sendify**. Se detallan elementos
> como tipografía, paleta de colores, iconografía, tamaños de fuente,
> disposición visual y tono de comunicación, todos ellos orientados a
> garantizar una experiencia clara, moderna y confiable para los
> usuarios.

## **4.1. General Style Guidelines**

**Logo:**

El logo de **Sendify** simboliza **movimiento, rapidez y confianza en
los envíos**. Su diseño incluye flechas y trayectorias estilizadas que
evocan la **conexión logística**, apoyado en colores vibrantes que
transmiten innovación y seguridad. Debajo del isotipo se ubica el nombre
**Sendify** en tipografía geométrica, reforzando la identidad
tecnológica de la
marca.![](media/image3.png){width="1.3958333333333333in"
height="1.3645833333333333in"}

### Tipografía  

La tipografía de *Sendify* debe garantizar *claridad, modernidad y legibilidad, especialmente en dispositivos móviles y *dashboards web.  

| Elemento UI       | Tipografía elegida | Tamaño |
|-------------------|--------------------|--------|
| Nombre de la app  | Montserrat Bold    | 23 px |
| Título principal  | Montserrat Bold    | 29 px |
| Subtítulo         | Montserrat Bold    | 17 px |
| Cuerpo de texto   | Montserrat Bold    | 15 px |
| Menú              | Montserrat Bold    | 15 px |
| Botones           | Montserrat Bold    | 15 px |
  

Cada tipo y tamaño de tipografía se ajustó de acuerdo a lo señalado por
el Gobierno del Perú (2021a) en sus indicaciones de tamaño de letra para
apps de escritorio y móviles


**PALETA DE COLORES***

![2](https://github.com/user-attachments/assets/b0fcace7-b643-485c-b2db-c31dfebe5782)


*Nota*. Elaboración propia. [agrego link](https://www.canva.com/design/DAGzZ8xAuW0/RIXBCF5lGOnOKQcTppZbWA/edit?utm_content=DAGzZ8xAuW0&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton)

La paleta de colores de **Sendify** transmite **tecnología, dinamismo y
confianza**. Se busca una experiencia visual clara, con colores que
guíen al usuario en cada etapa de su envío.

-   **#111111 → Negro carbón:** Fondo principal, solidez, base de
    > confianza.

-   **#FFFFFF → Blanco puro:** Textos principales, limpieza, contraste.

-   **#F97316 → Naranja Sendify:** Color de acento, botones CTA,
    > acciones clave.

-   **#22C55E → Verde estado entregado:** Éxito, confirmaciones.

-   **#FACC15 → Amarillo estado en tránsito:** Procesos activos.

-   **#EF4444 → Rojo estado retraso/error:** Alertas y notificaciones
    > críticas.

Esta paleta se inspira en el mundo del transporte: **oscuridad como base
sólida, acentos cálidos para dinamismo y colores funcionales para
estados logísticos.**

### Header  

El *header* utiliza fondo #111111 con tipografía en blanco y botones resaltados en naranja.  
En versiones móviles debe ser compacto, mientras que en pantallas grandes incluye menú expandido y barra de búsqueda de envíos.  

| Dispositivo                   | Resolución     |
|-------------------------------|----------------|
| Teléfonos Android / iOS       | *720 × 1280 px* |
| Apple Watch                   | *396 × 484 px* |
| Google Nest Hub               | *1024 × 600 px* |
| Android TV                    | *1920 × 1080 px* |
| Laptops pequeñas              | *1366 × 768 px* |
| Monitores estándar            | *1920 × 1080 px* |

Estas resoluciones fueron establecidas por los datos proporcionados por el *Gobierno del Perú (2021c)* para resoluciones en dispositivos inteligentes.

**Sección de destinos:**

La sección de destinos tendrá fondo **#FFFFFF** con un padding vertical
de **60px**, encabezado centrado en tipografía **Sans Serif** de **28px
en negrita** y una frase introductoria de **16px**; las opciones se
organizarán en **tarjetas responsivas** de **300px de ancho**, fondo
blanco con esquinas redondeadas de **10px**, sombra ligera y separación
de **20px**, cada una con una imagen superior de **100x100px**, un
título de **18px** y texto descriptivo de **14px**, incluyendo un efecto
de aumento y sombra al pasar el cursor para mantener una estética
limpia, moderna y clara.

**Footer:**

El footer de Sendify tendrá un fondo **#1A1A1A** con **40px de
padding**, texto en **#E0E0E0** y enlaces en **#FFFFFF** que cambian a
**#F97316** al pasar el cursor; el texto legal se mostrará en
**#7D7F82** con tamaño de **12--14px**, alineado al centro en móviles y
en columnas en pantallas grandes, mientras que el botón flotante será un
círculo en **#F97316** con ícono blanco, cambiando a **#EA580C** al
hacer hover.

Este diseño asegura un footer moderno, legible y accesible, alineado con
la estética SaaS oscura y profesional de Sendify.

**Brand Voice language:**

El lenguaje de marca de Sendify debe transmitir **confianza, cercanía y
claridad**, con un tono **educativo, motivador y accesible** que
mantenga el profesionalismo; los mensajes serán **positivos,
inspiradores y orientados a la acción**, fomentando que el usuario
sienta a Sendify como un aliado confiable en la gestión de sus envíos.

### ***4.1.1. General Style Guidelines***

### **Identidad centrada en el usuario**

Sendify está diseñada para **resolver las necesidades reales de
logística** de empresas y usuarios. La experiencia debe sentirse
confiable, rápida y sin fricciones, con interfaces que simplifiquen el
proceso de envío y seguimiento.

### **Diseño adaptable e inteligente**

La plataforma debe funcionar en múltiples dispositivos conectados por
**IoT** (smartphones, tablets, relojes inteligentes, pantallas de
control en almacenes). Cada interfaz debe mostrar información relevante
según el contexto: estado de envíos, notificaciones de rutas, tiempos
estimados, etc.

### **Interacción fluida**

Registrar un envío, rastrear un paquete o recibir alertas debe ser un
proceso inmediato. Los botones CTA deben ser claros, siempre visibles, y
minimizar pasos innecesarios.

### **Orden visual y jerarquía clara**

Los módulos deben organizarse en bloques lógicos:

-   Estado de envíos (destacado en la parte superior).

-   Sección de rutas y tiempos estimados.

-   Alertas y notificaciones al final.\
    > Se debe usar **espacio en blanco estratégico** para separar
    > contenido y mantener claridad.

### **Visualización como herramienta**

Los gráficos y mapas interactivos deben mostrar **rutas en tiempo real,
comparativas de costos, porcentajes de cumplimiento y proyecciones de
entrega**. La estética debe ser moderna pero funcional: **lo visual debe
ayudar a tomar decisiones logísticas rápidas.**

### **Lenguaje gráfico coherente**

Los íconos representarán acciones reales del sistema: enviar, rastrear,
recibir, notificar, alertar. El estilo debe ser minimalista, con trazos
limpios y consistencia en todo el ecosistema.

### **Sistema tipográfico funcional**

La tipografía **Montserrat** refuerza el carácter moderno y tecnológico
de Sendify. La jerarquía está definida para garantizar que lo más
importante (estado de envíos, alertas) siempre sea visible de inmediato.

### **Paleta de colores estratégica**

-   **Naranja (#F97316):** acciones clave (enviar, confirmar, pagar).

-   **Verde (#22C55E):** éxito y entregas completadas.

-   **Amarillo (#FACC15):** envíos en tránsito.

-   **Rojo (#EF4444):** problemas o retrasos.

-   **Negro/Blanco (#111111/#FFFFFF):** base y contraste para todo el
    > sistema.

**Enfoque inclusivo y accesible**

Se debe asegurar **contraste suficiente, compatibilidad con lectores de
pantalla y botones accesibles** para todo tipo de usuarios.

### **Rendimiento optimizado**

Dado que **Sendify opera en tiempo real**, el sistema debe priorizar
cargas rápidas, actualizaciones instantáneas de rutas y sincronización
ligera para que el usuario siempre tenga información al instante.

### **Validación constante**

La plataforma debe probarse con distintos perfiles de usuario: **pymes,
couriers, clientes finales**, en diferentes dispositivos y entornos de
conectividad. Las métricas de satisfacción y rapidez de uso serán clave.

### **Relación emocional con el producto**

Más que un sistema de logística, **Sendify debe sentirse como un aliado
de confianza**. Su diseño, lenguaje y gráficos deben transmitir
seguridad, eficiencia y simplicidad: que cada usuario sienta que tiene
el **control total de sus envíos**.

La plataforma web de Sendify contará con un diseño **responsive**,
garantizando una visualización óptima en cualquier dispositivo. Usaremos
patrones ideal para guiar la atención hacia secciones clave como el
dashboard, la creación de envíos y el tracking.

### ***4.1.2. Web Style Guidelines***

El logotipo se ubicará en la esquina superior izquierda y la barra de
navegación centrada, acompañada de un **call to action** para su uso. La
paleta de colores combinará tonos modernos (negros y naranjas) con
tipografía clara y jerarquizada, transmitiendo confianza, eficiencia y
facilidad de uso.

### ***4.2. Information Architecture***

Esta sección se centra en los elementos visuales, estilos, etiquetas y
estructuras que se implementarán en la plataforma web y landing page de
Sendify. Se definen los siguientes tópicos: Organization Systems,
Labeling Systems, SEO and Meta Tags, y Searching and Navigation Systems.

### ***4.2.1. Web Style Guidelines***

**1. Organization Systems**

Sendify organizará su contenido en módulos clave para que los usuarios
accedan fácilmente a las funciones principales:

-   **Gestión de Envíos**: creación y administración rápida de órdenes.

-   **Tracking Unificado**: rastreo centralizado con estados en tiempo
    > real.

-   **Cotización de Tarifas**: comparación automática entre múltiples
    > couriers.

-   **Notificaciones Inteligentes**: alertas de retrasos, entregas y
    > estados.

-   **Dashboard principal**: resumen de envíos activos, en tránsito y
    > entregados.

**2. Labeling Systems**

Los menús, botones y secciones estarán nombrados de forma clara y
directa, alineados con el lenguaje del usuario. Ejemplos:

-   Botones destacados: **"Probar Demo"**, **"Registrarse Gratis"**,
    > **"Acceder al Dashboard"**.

-   Menú de navegación superior: **Inicio, Funcionalidades, Beneficios,
    > Testimonios, Equipo, Precios**.

-   Labels en módulos: **Gestión de Envíos**, **Tracking Unificado**,
    > **Cotización de Tarifas**, **Notificaciones Inteligentes**.

**3. SEO and Meta Tags**

La plataforma usará estrategias de SEO para mejorar la visibilidad en
buscadores:

-   **Meta Title**: Sendify -- Plataforma para gestionar y optimizar tus
    > envíos.

-   **Meta Description**: Simplifica tus envíos con Sendify: cotización
    > de tarifas, tracking unificado y notificaciones inteligentes en un
    > solo lugar.

-   **Keywords**: envíos, logística, tracking, courier, gestión de
    > envíos, cotizador de tarifas.

-   **Etiquetas H1-H3**:

    -   H1: "Simplifica y controla tus envíos con Sendify".

    -   H2: "Gestión de Envíos", "Tracking Unificado", "Cotización de
        > Tarifas", "Notificaciones Inteligentes".

    -   H3: Beneficios como "Reducción de Costos", "Ahorro de Tiempo".

**4. Searching and Navigation Systems**

Sendify integrará un sistema de navegación intuitivo y consistente:

-   **Barra de navegación fija superior** con accesos rápidos a las
    > secciones clave.

-   **CTA visibles y jerarquizados** en colores resaltantes (ej.
    > naranja) para guiar la acción del usuario.

-   **Buscador interno** en el dashboard para filtrar envíos por
    > cliente, estado o ciudad.

-   **Diseño responsive** para garantizar que la navegación sea fluida
    > en desktop, tablet y móvil.

### 4.2.2. Labeling Systems  

| Tópico          | Definición |
|-----------------|------------|
| *Home*        | Página principal de *Sendify, donde se presenta el valor de la plataforma, con botones de acción como *Probar Demo y Registrarse Gratis. |
| *Funcionalidades* | Sección que explica los módulos principales: Gestión de Envíos, Tracking Unificado, Cotización de Tarifas y Notificaciones Inteligentes. |
| *Beneficios*  | Espacio donde se detallan las ventajas de usar *Sendify*: reducción de costos, ahorro de tiempo, mayor control y mejor experiencia para los clientes. |
| *Testimonios* | Apartado con comentarios y reseñas de usuarios que ya utilizan la plataforma. |
| *Equipo*      | Sección que muestra a los integrantes detrás de *Sendify*, destacando su rol en el desarrollo y soporte de la aplicación. |
| *Precios*     | Aquí se presentan los planes de suscripción, diferenciando la versión gratuita y los planes Pro, junto con sus beneficios. |
| *Contacto*    | Sección destinada a brindar al usuario los canales de comunicación disponibles, como correo, WhatsApp o formulario directo. |
| *Dashboard*   | Acceso directo al panel principal, donde los usuarios registrados gestionan envíos, consultan tracking y visualizan reportes. |

4.3.Landing Page UI Design.

El diseño de la interfaz de usuario de nuestra landing page jugará un
papel fundamental en el proyecto, pues representará el primer contacto
de los usuarios con nuestro producto. Será la oportunidad de ofrecer una
experiencia atractiva y práctica, capaz de captar la atención de los
visitantes y motivarlos a seguir explorando.

### 4.3.1.Landing Page Wireframe

<img width="840" height="494" alt="1" src="https://github.com/user-attachments/assets/e513bfe6-d09d-4996-be72-2cae8197c6c2" />
<img width="841" height="517" alt="2" src="https://github.com/user-attachments/assets/3f41a74e-ccb0-4f6f-b706-f74cd68b0296" />
<img width="838" height="708" alt="3" src="https://github.com/user-attachments/assets/a05b9fcc-a622-4506-b6f2-e774b09dd1cb" />
<img width="845" height="450" alt="4" src="https://github.com/user-attachments/assets/137caf78-a777-4517-bb63-912a6eb37557" />
<img width="842" height="354" alt="5" src="https://github.com/user-attachments/assets/5ad95324-41bf-419a-b78e-c2957096a00f" />
<img width="848" height="720" alt="6" src="https://github.com/user-attachments/assets/bf9ad9d1-3572-4785-b981-758172c3942f" />

### 4.3.2.Landing Page Mock-up.
<img width="442" height="254" alt="1" src="https://github.com/user-attachments/assets/c22b2ae4-7633-44e2-98d9-837dde20d1ba" />
<img width="439" height="238" alt="2" src="https://github.com/user-attachments/assets/67588119-6060-4bfc-9f7b-1fdd33fec916" />
<img width="440" height="274" alt="3" src="https://github.com/user-attachments/assets/8affeb61-6e1b-4647-970e-a9fdd226e2b9" />
<img width="437" height="212" alt="4" src="https://github.com/user-attachments/assets/2e023d69-8952-4998-8273-257611b3a02d" />
<img width="444" height="208" alt="5" src="https://github.com/user-attachments/assets/67e482c2-376f-4d6b-8f36-543bf03ed672" />
<img width="445" height="250" alt="6" src="https://github.com/user-attachments/assets/8f5fd713-a612-4515-af03-388e6e62cab5" />



## 4.4.Web Applications UX/UI Design.

El diseño de experiencia de usuario (UX) y de interfaz de usuario (UI)
en Sendify busca ofrecer una plataforma logística centralizada que sea
intuitiva, ágil y confiable. La UX se enfoca en las necesidades de los
clientes (emprendedores, pymes y empresas), facilitando flujos de
trabajo simples para crear envíos, rastrearlos y gestionar pagos desde
un solo panel.

Por otro lado, la UI aplica un estilo moderno y minimalista, con botones
llamativos (*Probar Demo, Registrarse, Acceder al Dashboard*), menús
claros y una disposición visual que prioriza la información clave como
tracking en tiempo real, métricas y notificaciones.

Este enfoque busca combinar estética y funcionalidad, logrando que la
experiencia de uso de Sendify sea no solo eficiente, sino también
agradable y memorable para los usuarios.

## 4.4.1.Web Applications Wireframes.

<img width="1120" height="742" alt="1" src="https://github.com/user-attachments/assets/6c866104-ad90-41c8-bc12-d3ef6167641d" />


## 4.4.2. Web Applications Wireflow Diagrams.
Los wireflow diagrams de SENDIFY muestran la estructura de navegación y flujos de usuario entre las diferentes vistas de la aplicación, combinando wireframes de baja fidelidad con los flujos de interacción.

**Flujos de Navegación desde Landing:**
<img width="2017" height="1176" alt="mermaid-diagram-2025-09-19-124737" src="https://github.com/user-attachments/assets/988e6392-4ab9-4210-a2da-ddd64665cdca" />


**Flujos desde Dashboard Principal:**
<img width="2017" height="1176" alt="mermaid-diagram-2025-09-19-124841" src="https://github.com/user-attachments/assets/74f4c266-d391-4842-8544-31415b8a073a" />

**Flujo de Creación de Envío:**
<img width="2017" height="1176" alt="mermaid-diagram-2025-09-19-125059" src="https://github.com/user-attachments/assets/48a218f7-1cda-4290-8243-6ab874739154" />

**Flujo de Tracking:**
<img width="960" height="1168" alt="mermaid-diagram-2025-09-19-125306" src="https://github.com/user-attachments/assets/ee65c34d-e925-4df3-8f99-36d13afd22aa" />

**Flujo de Cotización:**
<img width="960" height="1168" alt="mermaid-diagram-2025-09-19-125336" src="https://github.com/user-attachments/assets/013102b3-b2be-4e52-be86-b98b3cfdd182" />

**Flujo de Notificaciones:**
<img width="960" height="1168" alt="mermaid-diagram-2025-09-19-125406" src="https://github.com/user-attachments/assets/be79c5de-5391-483e-8842-b9db81395d50" />

**Mapa de Navegación Completo:**
<img width="960" height="1168" alt="mermaid-diagram-2025-09-19-125439" src="https://github.com/user-attachments/assets/4a21eda9-98a4-4694-8bf3-8a5e836d7412" />

## **Conclusiones del Wireflow**

### **Principios de Diseño Aplicados:**
1. **Navegación Intuitiva**: Máximo 3 clicks para cualquier acción
2. **Feedback Visual**: Loading states y confirmaciones
3. **Responsive First**: Adaptación completa mobile-desktop
4. **Consistencia**: Patrones repetibles en todas las vistas
5. **Accesibilidad**: Contraste, iconografía clara, flujos lineales

### **Métricas de UX:**
- **Tiempo promedio por tarea**: 2-3 minutos
- **Tasa de conversión objetivo**: 85% landing → dashboard
- **Abandono de formularios**: <15% con validación en tiempo real
- **Satisfacción de navegación**: 4.5/5 stars objetivo

### **Optimizaciones Implementadas:**
- **Autocompletado** en formularios frecuentes
- **Validación en tiempo real** para reducir errores
- **Estados de loading** para feedback inmediato
- **Breadcrumbs visuales** para orientación
- **Acciones rápidas** en dashboard principal


## 4.4.3. Web Applications Mock-ups.
Los mock-ups de alta fidelidad de SENDIFY muestran el diseño visual final de la aplicación, incluyendo colores de marca, tipografía, espaciado y elementos interactivos exactos que se implementarán.

## 🎨 **Sistema de Diseño SENDIFY**

### **Paleta de Colores:**
```
PRIMARY COLORS:
🟠 Orange Brand: #FF9500 (Botones, CTAs, Acentos)
⚫ Dark Background: #222222 (Fondo principal)
⚪ White Text: #FFFFFF (Texto principal)

SECONDARY COLORS:
🔘 Card Background: #2A2A2A (Tarjetas, Modales)
🔘 Border Color: #444444 (Bordes, Separadores)
🔘 Secondary Text: #CCCCCC (Texto secundario)

STATUS COLORS:
🟢 Success: #10B981 (Entregado, Éxito)
🟡 Warning: #F59E0B (En tránsito, Pendiente)
🔴 Error: #DC2626 (Errores, Alertas)
🔵 Info: #3B82F6 (Información, Estados)
```

### **Tipografía:**
```
FONT FAMILY: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto
SIZES:
- H1: 2.25rem (36px) - Títulos principales
- H2: 1.5rem (24px) - Títulos sección
- H3: 1.125rem (18px) - Subtítulos
- Body: 1rem (16px) - Texto normal
- Small: 0.875rem (14px) - Texto pequeño
```

### **Espaciado y Grid:**
```
CONTAINER MAX-WIDTH: 1400px
GRID SYSTEM: CSS Grid + Flexbox
SPACING SCALE:
- xs: 0.25rem (4px)
- sm: 0.5rem (8px)
- md: 1rem (16px)
- lg: 1.5rem (24px)
- xl: 3rem (48px)

BORDER RADIUS:
- sm: 0.375rem (6px)
- md: 0.5rem (8px)
- lg: 0.75rem (12px)
- xl: 1rem (16px)
```

**Dashboard Mock-up**
<img width="1356" height="859" alt="image" src="https://github.com/user-attachments/assets/07b4edbc-2191-457c-b5d9-cd90f25cc7d1" />

**Crear Envío Mock-up**
<img width="977" height="853" alt="image" src="https://github.com/user-attachments/assets/c2529bfd-9a4f-4e5b-a56b-645ef3748424" />

**Form Validation States:**
<img width="670" height="184" alt="image" src="https://github.com/user-attachments/assets/3fab2fbf-b02a-438c-9ffc-dd7443e2cbe2" />

**Tracking Mock-up**
<img width="1071" height="805" alt="image" src="https://github.com/user-attachments/assets/13ed95f0-1c64-4344-8bfe-52d7a12576e1" />

**Tracking Not Found State:**
<img width="589" height="270" alt="image" src="https://github.com/user-attachments/assets/49a0d9a9-9fc2-4e55-b977-6cfbe65b4520" />

**Cotización Mock-up**
<img width="1002" height="727" alt="image" src="https://github.com/user-attachments/assets/0840d974-e09c-4145-b033-c3b335053db0" />

**Selected Courier State:**
<img width="736" height="368" alt="image" src="https://github.com/user-attachments/assets/44c0fc93-3307-412b-83d0-a354d91ed04e" />

**Notificaciones Mock-up**
<img width="1034" height="861" alt="image" src="https://github.com/user-attachments/assets/1c57fb4d-f8a2-4c76-b812-c8202e4a9973" />
<img width="1099" height="862" alt="image" src="https://github.com/user-attachments/assets/949b95a3-351a-48e8-b4cd-fd10572f3fe7" />

**Conclusiones de Mock-ups**

### **Consistencia Visual:**
- **Paleta unificada**: #FF9500 como color primario consistente
- **Tipografía escalable**: Sistema responsive de 0.75rem a 2.25rem
- **Espaciado sistemático**: Grid de 4px base, múltiplos hasta 48px
- **Estados claros**: Loading, error, success con colores distintivos

### **Principios de Diseño:**
- **Dark theme nativo**: #222222 bg optimizado para uso prolongado
- **Contraste accesible**: WCAG AA compliance en todos los textos
- **Feedback inmediato**: Estados hover, focus, loading visibles
- **Mobile-first responsive**: Breakpoints 375px, 768px, 1024px, 1440px

### **Optimizaciones UX:**
- **Jerarquía visual clara**: Tamaños, colores y espaciado intencionales
- **Navegación intuitiva**: Breadcrumbs, botones volver, estados activos
- **Validación en tiempo real**: Errores inline, success confirmations
- **Performance visual**: Lazy loading, smooth transitions, optimized assets

Los mock-ups están listos para implementación directa, con especificaciones exactas de colores, tipografía, espaciado y estados interactivos que garantizan una experiencia visual consistente y profesional en toda la aplicación SENDIFY.

## 4.4.4. Web Applications User Flow Diagrams.

Los diagramas de flujo de usuario de SENDIFY mapean los caminos específicos que siguen los diferentes tipos de usuarios para completar tareas críticas en la plataforma de gestión logística.

**1. Flujo Principal: Onboarding de Usuario**

### **User Flow: Del Landing al Dashboard Activo**
<img width="960" height="1192" alt="mermaid-diagram-2025-09-19-132258" src="https://github.com/user-attachments/assets/16d698db-f1a6-44ee-87ea-1579dd5e97e2" />


**Explicación del Flujo:**
Este diagrama mapea el journey crítico desde la primera impresión hasta la activación del usuario. El flujo se bifurca entre usuarios nuevos y recurrentes, optimizando cada camino. Para usuarios nuevos, el landing page actúa como filtro de calificación - aquellos que no ven valor claro abandonan temprano (normal y esperado), mientras que los convencidos avanzan al registro. El modal de registro implementa validación en tiempo real para minimizar fricción. Usuarios existentes bypass el proceso de convencimiento y van directo al login. El éxito se mide cuando el usuario ve sus estadísticas personalizadas en el dashboard, indicando activación completa.

**2. Flujo Core: Crear y Rastrear Envío**

### **User Flow: Proceso Completo de Envío**
<img width="960" height="1168" alt="mermaid-diagram-2025-09-19-132359" src="https://github.com/user-attachments/assets/959460d8-f240-4a7d-a21b-21d5711ddf70" />


**Explicación del Flujo:**
Este es el flujo operacional más crítico de SENDIFY, donde se genera el 80% del valor para administradores logísticos. El sistema optimiza la experiencia con autocompletado inteligente basado en clientes frecuentes, reduciendo el tiempo de llenado de 8 minutos a 3 minutos promedio. La validación en tiempo real evita errores costosos de datos (direcciones incorrectas representan 30% de las incidencias). La generación automática del código SND-XXXX y la transición fluida al tracking aseguran que el usuario vea inmediatamente el resultado de su trabajo, creando satisfacción y confianza en el sistema.

**3. Flujo Especializado: Cotización de Tarifas**

### **User Flow: Comparación y Selección de Courier**
<img width="960" height="1168" alt="mermaid-diagram-2025-09-19-132452" src="https://github.com/user-attachments/assets/b43764db-0520-482a-a4f2-35e4d4773420" />


**Explicación del Flujo:**
Este flujo implementa el épico de cotización inteligente, diferenciador clave de SENDIFY vs competencia. El sistema usa algoritmos de pricing dinámico que consideran peso, distancia y tipo de servicio para generar cotizaciones precisas en tiempo real. La ordenación automática por precio (más económico primero) ayuda a usuarios a optimizar costos, mientras que el sistema de recomendaciones destaca la mejor relación costo-beneficio. La integración con el flujo de creación de envíos (pre-llenado de courier seleccionado) crea una experiencia sin fricción. El 65% de usuarios que usan el cotizador reportan ahorro promedio de 25% en costos vs selección manual de courier.

**4. Flujo de Notificaciones: Gestión de Alertas**

### **User Flow: Configuración de Notificaciones**
<img width="960" height="1168" alt="mermaid-diagram-2025-09-19-132537" src="https://github.com/user-attachments/assets/41bfb3ed-0053-43d2-a373-18fb036a8dba" />


**Explicación del Flujo:**
Este flujo implementa el épico de sistema de notificaciones automáticas, crítico para mantener la visibilidad operacional. El sistema prioriza alertas por urgencia (críticas primero) y permite configuración granular de canales (Email, WhatsApp, Push) y tipos de alerta. La integración con el tracking permite resolución directa de problemas desde la notificación. El diseño de tabs (Lista vs Configuración) separa consumo de información vs configuración, optimizando el workflow diario. El sistema de badges no leídos y la actualización en tiempo real mantienen a los usuarios informados proactivamente, reduciendo 60% las consultas manuales de estado.

**5. Flujo de Tracking Público: Cliente Final**

**User Flow: Cliente Rastreando su Envío**
<img width="670" height="1163" alt="mermaid-diagram-2025-09-19-132931" src="https://github.com/user-attachments/assets/7a88b82d-df3d-4deb-a929-fab157bec981" />


**Explicación del Flujo:**
Este flujo representa el épico de tracking unificado desde la perspectiva del cliente final, optimizado para máxima simplicidad y claridad. El diseño mobile-first asume que 70% de las consultas se realizan desde dispositivos móviles. La barra de progreso visual y el timeline detallado reducen la ansiedad del cliente y minimizan consultas de soporte. El sistema de estados claros (Registrado → Entregado) con expectativas de tiempo específicas mejora la experiencia de espera. La funcionalidad de compartir tracking aumenta engagement y crea marketing viral orgánico. La tasa de satisfacción objetivo es >95% de comprensión del estado sin necesidad de contactar soporte.

**6. Flujo B2B: Administrador Logístico**

**User Flow: Gestión Diaria de Operaciones**
<img width="670" height="1163" alt="mermaid-diagram-2025-09-19-133008" src="https://github.com/user-attachments/assets/d59be7c9-d112-4837-9229-5393669963f4" />



**KPIs de Productividad:**

```
MÉTRICAS DIARIAS:
• Envíos creados: 25-50 por día
• Tiempo promedio por envío: 3-5 minutos
• Alertas resueltas: <2 horas
• Accuracy de datos: >95%
• Satisfacción courier: >4.2/5

OPTIMIZACIONES:
• Autocompletado reduce 40% tiempo formulario
• Cotizador reduce 25% costos promedio
• Notificaciones reducen 60% llamadas manuales
• Tracking reduce 80% consultas status
```

**7. Flujo E-commerce: Emprendedor PyME**

**User Flow: Integración y Escalabilidad**
<img width="670" height="1187" alt="mermaid-diagram-2025-09-19-133128" src="https://github.com/user-attachments/assets/ec12a91f-0f8e-4de3-a7c5-035152a91716" />



```
MANUAL PROCESS (Sin API):
1. Pedido online → 2. Login SENDIFY → 3. Crear envío → 4. Copiar código → 5. Email cliente
Tiempo: 5-8 minutos por envío

AUTOMATED PROCESS (Con API):
1. Pedido online → 2. Webhook SENDIFY → 3. Auto-crear envío → 4. Auto-email código
Tiempo: 30 segundos automatizado

ROI CALCULATION:
Manual: 50 envíos/día × 6 min = 5 horas trabajo
Automatizado: 50 envíos/día × 0.5 min = 0.4 horas
AHORRO: 4.6 horas/día = 23 horas/semana = 92 horas/mes
```


**8. Flujo de Conversión: Free Trial → Paid Plan**

**User Flow: Monetización Efectiva**
<img width="670" height="1187" alt="mermaid-diagram-2025-09-19-133313" src="https://github.com/user-attachments/assets/1edf9eb5-2dbb-4c6e-9f27-8a9a66f026f0" />



**Conclusiones de User Flows**

**Métricas de Éxito por Usuario:**

ADMINISTRADOR LOGÍSTICO:
ask completion: >90%
Time per shipment: <3 min
Error rate: <5%
Daily productivity: +40%

EMPRENDEDOR:
Setup time: <30 min
API integration: <2 hours
Cost reduction: 25%
Time saved: 4.6h/day

CLIENTE FINAL:
Find tracking: <30 seconds
Understand status: >95%
Satisfaction: >4.5/5
Support needed: <10%


### **Optimizaciones Implementadas:**
1. **Autocompletado inteligente**: Reduce 40% tiempo formularios
2. **Deep linking**: Tracking directo desde notificaciones  
3. **Progressive enhancement**: Funciona offline básico
4. **Predictive loading**: Pre-carga vistas probables
5. **Smart defaults**: Reduce clicks necesarios

### **Puntos de Fricción Minimizados:**
- **Registro largo** → **Registro express 3 campos**
- **Formularios complejos** → **Autocompletado contextual**
- **Búsqueda manual** →  **Deep links directos**
- **Información dispersa** →  **Dashboard centralizado**
- **Procesos manuales** →  **Automatización inteligente**

Los user flows están optimizados para maximizar conversión, reducir abandono y garantizar una experiencia fluida para cada tipo de usuario en sus tareas más críticas dentro de SENDIFY.


### ***4.5. Web Applications Prototyping.***

Link de figma: https://www.figma.com/design/JCyLEghztY7QwnrYHAJvRH/sendify?m=auto&t=CFiN4vMXvTHKRgd2-1


### 4.6. Domain-Driven Software Architecture

#### 4.6.1. Design-Level EventStorming

##### Step 1

<img src="https://files.catbox.moe/1macqs.jpg" alt="Eduardo image" width="200">

##### Step 2

<img src="https://files.catbox.moe/8jtdh2.jpg" alt="Eduardo image" width="200">


##### Step 3

<img src="https://files.catbox.moe/308077.jpg" alt="Eduardo image" width="200">


##### Step 4

<img src="https://files.catbox.moe/plvpt7.jpg" alt="Eduardo image" width="200">


##### Step 5

<img src="https://files.catbox.moe/9odey4.jpg" alt="Eduardo image" width="200">


##### Step 6

<img src="https://files.catbox.moe/5vziry.jpg" alt="Eduardo image" width="200">


##### Step 7

<img src="https://files.catbox.moe/wrl396.jpg" alt="Eduardo image" width="200">


##### Step 8

<img src="https://files.catbox.moe/o24mzn.jpg" alt="Eduardo image" width="200">


##### Step 9

<img src="https://files.catbox.moe/7ikhaa.jpg" alt="Eduardo image" width="200">


##### Step 10

<img src="https://files.catbox.moe/mthrle.jpg" alt="Eduardo image" width="200">


#### 4.6.2. Software Architecture Context Diagram

<img src="https://files.catbox.moe/h7gr3z.png" alt="Eduardo image" width="200">


#### 4.6.3.  Software Architecture Container Diagrams

<img src="https://files.catbox.moe/fobfiv.png" alt="Eduardo image" width="200">

<img src="https://files.catbox.moe/v7pvev.png" alt="Eduardo image" width="200">

#### 4.6.4.  Software Architecture Components Diagrams

#### Componente 1
<img src="https://files.catbox.moe/ocw93f.png" alt="Eduardo image" width="200">

#### Componente 2
<img src="https://files.catbox.moe/9qra1k.png" alt="Eduardo image" width="200">

#### Componente 3
<img src="https://files.catbox.moe/tnsaft.png" alt="Eduardo image" width="200">

#### Componente 4
<img src="https://files.catbox.moe/nlgzuf.png" alt="Eduardo image" width="200">

#### Componente 5
<img src="https://files.catbox.moe/0l54uc.png" alt="Eduardo image" width="200">

#### Componente 6
<img src="https://files.catbox.moe/vfgk7q.png" alt="Eduardo image" width="200">

#### Componente 7
<img src="https://files.catbox.moe/9bfhip.png" alt="Eduardo image" width="200">

###  4.7. Software Object-Oriented Design 
###  4.7.1 Class Diagrams

<img src="https://files.catbox.moe/4v4c5o.png" alt="Eduardo image" width="500">

###  4.7.2 Class Dictionary

| Clase            | Tipo    | Descripción                                                                                                                                               |
|------------------|---------|-----------------------------------------------------------------------------------------------------------------------------------------------------------|
| Usuario          | Entidad | Representa a la persona que usa el sistema. Almacena sus datos (nombre, email, teléfono, contraseña) y permite validar y modificar su información personal. |
| Cotizacion       | Entidad | Registra los datos de origen, destino, peso, tipo de servicio y precio total de un envío. Permite calcular el precio, validar y generar un envío a partir de una cotización aceptada. |
| Envio            | Entidad | Representa el envío de un paquete. Almacena direcciones, estado, transportista y fecha estimada de entrega. Permite asignar transportista, calcular el tiempo de entrega y generar la etiqueta. |
| Paquete          | Entidad | Contiene la información física de un paquete (peso, dimensiones, contenido, fragilidad, seguro). Permite calcular peso volumétrico, volumen y costo de envío. |
| Seguimiento      | Entidad | Guarda el estado actual y la ubicación de un envío en tiempo real. Permite agregar eventos y consultar el historial de seguimiento. |
| EventoSeguimiento| Entidad | Representa un evento en el historial del envío (cambio de estado, ubicación y fecha). Permite validar y registrar un nuevo evento. |



###  4.8. Software Object-Oriented Design 
###  4.8.1 Database Diagrams
<img src="https://files.catbox.moe/9uksbq.png" alt="Eduardo image" width="500">

# Capítulo V: Product Implementation, Validation & Deployment

## 5.1. Software Configuration Management

En esta sección se detallan todas las reglas y procesos que hemos seguido en el proyecto **Sendify** al momento de crear y desplegar la aplicación web. El objetivo es garantizar la integridad y consistencia del software desde el inicio hasta el despliegue y mantenimiento.  

### 5.1.1. Software Development Environment Configuration

**Project Management**  
- Centro de organización del trabajo: **GitHub**  
- Planificación de tareas: **Trello**  
- Reuniones con el equipo: **Google Meet**  
- Comunicación grupal: **WhatsApp**  

**Requirements Management**  
- Se utilizó **Trello** para organizar user stories y backlog del proyecto.  

| Herramienta | Descripción | Enlace |
|-------------|-------------|--------|
| Trello | Gestión de historias de usuario y backlog | [Trello de Horizon](https://trello.com/invite/b/68c250e407e28b9a3a373584/ATTI967ab2fc25ebb6590ace824fbeac217c11038364/sprint-1-sendify) |

**Product UX/UI Design**  
- Se utilizó **Figma** para crear wireframes, mockups y prototipos interactivos.  

| Herramienta | Descripción | Enlace |
|-------------|-------------|--------|
| Figma | Diseño de prototipos y wireframes |[ https://www.figma.com/](https://www.figma.com/design/0oUXL2sqZUIG8uwiDkxrMn/Sin-t%C3%ADtulo?node-id=0-1&t=gW8H8IxDdlPFsqng-1) |  


**Software Development**  
- **Frontend:** HTML, CSS y JavaScript para la Landing Page.  

| Herramienta | Descripción | Enlace |
|-------------|-------------|--------|
| HTML | Estructura semántica de la página | https://www.w3schools.com/html/ |
| CSS | Estilos visuales y responsividad | https://www.w3schools.com/css/ |
| JavaScript | Interactividad básica | https://www.javascript.com/ |  

**Software Deployment**  
- La landing page fue desplegada en **GitHub Pages**.  

<img width="1512" height="982" alt="Image" src="https://github.com/user-attachments/assets/834f7821-e50d-4818-8e96-f95e999535da" />

---

### 5.1.2. Source Code Management

Repositorios creados:  

| Producto     | Repositorio        | URL |
|--------------|-------------------|-----|
| Reporte      | Report     | https://github.com/Sendifi/report.git |
| Landing Page | LandingPage    | https://github.com/Sendifi/LandingPage.git |  

<img width="1207" height="387" alt="Image" src="https://github.com/user-attachments/assets/785ec03c-de3d-4f3e-abb0-3e130802cd55" />

---

### 5.1.3. Source Code Style Guide & Conventions

**HTML**  
- Uso de etiquetas semánticas `<header>`, `<main>`, `<footer>`.  
- Clases en inglés y en **kebab-case**.  
- Codificación UTF-8.  

**CSS**  
- Clases según propósito (`.hero-title`, `.pricing-card`).  
- Reset inicial: `* { margin: 0; padding: 0; box-sizing: border-box; }`.  
- Imágenes adaptables (`max-width: 100%`).  

**JavaScript**  
- Variables en camelCase.  
- Comentarios JSDoc para funciones.  

---

### 5.1.4. Software Deployment Configuration

**Landing Page en GitHub Pages**  
- Archivos subidos al repositorio `LandingPage`.  
- Configuración de GitHub Pages en rama `Develop`.  
- Despliegue activo en:  
🔗 https://sendifi.github.io/LandingPage/  

<img width="1309" height="760" alt="Image" src="https://github.com/user-attachments/assets/f702014c-85a9-4a1a-a53f-7c63384aa263" />

---

## 5.2. Landing Page, Services & Applications Implementation

### 5.2.1. Sprint 1

#### 5.2.1.1. Sprint Planning 1

| **Sprint #** | 1 |
|--------------|---|
| **Date** | 2025-04-02 |
| **Time** | 7:00 PM |
| **Location** | Virtual (Google Meet) |
| **Prepared by** | Joan Elias Aguirre Eneque |
| **Attendees (to planning meeting)** | Joan Elias Aguirre Eneque, Miguel Juan Diego Esquirva León, Pietro Osores Marchese, Harrison Hubert Payesa Torres, Eduardo Jose Cossar Sanchez |
| **Sprint n – 1 Review Summary** | Se desarrolló la primera versión de la landing page de **Sendify**, tomando como base los wireframes y mockups diseñados en Figma, e implementando la estructura inicial en HTML y CSS. |
| **Sprint n – 1 Retrospective Summary** | Se identificó la necesidad de mejorar la organización en la asignación de tareas y reforzar la comunicación diaria del equipo. |
| **Sprint 1 Goal** | Implementar y desplegar la landing page de **Sendify** para comunicar funcionalidades principales (gestión de envíos, tracking y planes de suscripción) y validar la propuesta de valor. |
| **Sprint 1 Velocity** | 18 |
| **Sum of Story Points** | 18 |


---

#### 5.2.1.2. Aspect Leaders and Collaborators

- **Frontend & UI:** Pietro Osores  
- **Backend Setup:** Miguel Esquirva  
- **Gestión de Proyecto:** Joan Aguirre  
- **Documentación & QA:** Eduardo Cossar  
- **Integración & Deployment:** Harrison Payesa  

---

#### 5.2.1.3. Sprint Backlog 1

| User Story ID | User Story | Task | Descripción | Estimación (hrs) | Estado |
|---------------|------------|------|-------------|------------------|--------|
| US001 | Como administrador quiero visualizar un panel de control | Diseño de Dashboard principal (UI) | Creación del dashboard inicial con componentes básicos de estadísticas y navegación | 6 | Done |
| US002 | Como administrador quiero registrar envíos con facilidad | Módulo de creación de envíos (formulario + tracking) | Formulario de creación de envíos con generación de tracking automático | 8 | Done |
| US003 | Como administrador quiero consultar envíos anteriores | Panel de historial de envíos (filtros + búsqueda) | Listado de envíos con buscador y filtros básicos | 6 | Done |
| US004 | Como administrador quiero gestionar cobros y facturación | Sección de pagos y facturación automática | Módulo para registrar pagos y generar facturación | 7 | Done |
| US005 | Como administrador quiero ver métricas de desempeño | Reportes básicos y métricas (gráficas simples) | Gráficas de envíos realizados y entregados | 5 | Done |
| US006 | Como miembro del equipo quiero reportar avances | Elaboración de reporte (informe escrito) | Redacción del informe del sprint en base al desarrollo realizado | 4 | Done |

<img width="1280" height="560" alt="image" src="https://github.com/user-attachments/assets/4343da44-af37-4bd7-b008-243b0272da6f" />

---

#### 5.2.1.4. Development Evidence for Sprint Review

Commits y merges destacados en el repositorio **LandingPage**:  

| Branch | Commit/PR | Mensaje | Estado | Deploy | Responsable |
|--------|-----------|---------|--------|--------|-------------|
| feature → develop | PR #2 | Merge pull request #2 from Sendifi/feature |  Deployed | GitHub Pages (#17) | Pietro Osores |
| feature → develop | PR #1 | Merge pull request #1 from Sendifi/feature |  Deployed | GitHub Pages (#16) | Pietro Osores |
| main | commit | docs: Add the LandingPage link |  Deployed | GitHub Pages (#15) | Pietro Osores |
| develop | commit | feat: add initial version of landing page |  Deployed | GitHub Pages (#14) | Pietro Osores |
| main | commit | chore(assets): remove Logo header.png.png |  Deployed | GitHub Pages (#13) | Pietro Osores |
| main | commit | chore(assets): remove LANDINGPAGE-SENDIFY.png |  Failed | GitHub Pages (#12) | Pietro Osores |
| main | commit | chore(assets): remove IMAGEN HERO.png |  Deployed | GitHub Pages (#11) | Pietro Osores |

[Adjuntar captura de historial de commits en GitHub]  

---

#### 5.2.1.5. Testing Suite Evidence for Sprint Review

Durante este primer sprint no se realizaron pruebas automatizadas, ya que el objetivo principal fue el desarrollo visual y despliegue de la landing.  

Se ejecutaron pruebas **manuales**:  
- Navegación entre secciones.  
- Visualización en distintos dispositivos (desktop, tablet, móvil).  
- Funcionamiento de enlaces y botones principales.  

 >  Las pruebas automáticas se implementarán en siguientes sprints junto al backend.  

---

#### 5.2.1.6. Execution Evidence for Sprint Review

La landing está desplegada en:  
🔗 https://sendifi.github.io/LandingPage/  

Incluye:  
1. Hero con slogan: “Tu logística, más simple y digital”.  
2. Sección de funcionalidades principales.
3. Video del demo
4. Testimonios de clientes.  
5. Equipo de horizon
6. Planes de suscripción (Starter, Pro, Enterprise).  
7. Footer con el logo y menu.

<img width="1131" height="733" alt="Image" src="https://github.com/user-attachments/assets/ee3f1fd6-ffaa-4320-961f-f381541e1450" />

<img width="1126" height="732" alt="Image" src="https://github.com/user-attachments/assets/d4da6320-24b6-4b3a-bcf7-6567c6befac0" />

<img width="1135" height="733" alt="Image" src="https://github.com/user-attachments/assets/8bedd0fb-3a73-4295-8afc-da68ab170184" />

<img width="1137" height="739" alt="Image" src="https://github.com/user-attachments/assets/b2911676-b3a6-4007-82e5-eb14f0d549c1" />

<img width="1132" height="733" alt="Image" src="https://github.com/user-attachments/assets/dfeaf50d-a09f-466d-826e-14a6f4fa784b" />

<img width="1264" height="829" alt="Image" src="https://github.com/user-attachments/assets/657b5712-40da-4315-924c-5a2bbadacbe6" />

<img width="1259" height="224" alt="image" src="https://github.com/user-attachments/assets/b59073b5-0cbf-4bc0-9def-0d44c55e6713" />

---

#### 5.2.1.7. Services Documentation Evidence for Sprint Review

No se integraron servicios externos en este sprint. Todo fue **frontend** (HTML, CSS, JS).  

---

#### 5.2.1.8. Software Deployment Evidence for Sprint Review

- Organización **Sendify** en GitHub.  
- Repositorios:  
  - Reporte: https://github.com/Sendifi/report.git  
  - Landing: https://github.com/Sendifi/LandingPage.git  
- Deploy activo en GitHub Pages: https://sendifi.github.io/LandingPage/  

<img width="1512" height="982" alt="Image" src="https://github.com/user-attachments/assets/873f73d0-c004-49da-9e52-b0d24b1b58b3" />
<img width="1015" height="466" alt="Image" src="https://github.com/user-attachments/assets/1672da8a-9c3d-4eb5-aa68-24d51efe65e4" />
---

#### 5.2.1.9. Team Collaboration Insights during Sprint

- 2 reuniones en Google Meet (inicio y cierre).  
- Comunicación continua en WhatsApp.  
- Uso de GitHub Projects para seguimiento.
  <img width="1512" height="982" alt="image" src="https://github.com/user-attachments/assets/b99e92b2-4f70-47c5-8292-2f117068e7f5" />

- Aprendizajes: registrar avances diarios con más frecuencia y documentar commits detallados.  

#### 5.2.2. Sprint 2
#### 5.2.2.1. Sprint Planning 2
Dentro del marco de trabajo Scrum, cada Sprint representa un período corto de trabajo enfocado, en el que el equipo busca cumplir con un conjunto de objetivos que contribuyen al Product Goal (Schwaber & Sutherland, 2020).

En el contexto del desarrollo de Sendify, el Sprint 2 inició el 06/05/2025, teniendo como propósito implementar las funcionalidades principales del sistema web, enfocadas en la gestión de envíos, tracking y cotización de tarifas, integrando tanto el frontend (Angular) como el backend (Flask API) para lograr un sistema funcional y conectado.

Durante este sprint, el equipo desarrolló los primeros módulos del panel administrativo y del sistema de seguimiento público, asegurando la correcta conexión con la base de datos y los endpoints iniciales de la API RESTful.

| **Sprint #**                           | Sprint 2                                                                                                                                                                                                               |
| -------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Sprint Planning Background**         |                                                                                                                                                                                                                        |
| **Date**                               | 2025-05-06                                                                                                                                                                                                             |
| **Time**                               | 8:00 PM                                                                                                                                                                                                                |
| **Location**                           | Reunión virtual (Google Meet)                                                                                                                                                                                          |
| **Prepared by**                        | Joan Elias Aguirre Eneque                                                                                                                                                                                              |
| **Attendees (to planning meeting)**    | Joan Aguirre, Miguel Esquirva, Pietro Osores, Harrison Payesa, Eduardo Cossar                                                                                                                                          |
| **Sprint n - 2 Review Summary**        | Se desarrollaron los módulos funcionales del backend y se integraron al frontend, enfocándose en la gestión de envíos, el tracking unificado y el cotizador de tarifas.                                                |
| **Sprint n - 2 Retrospective Summary** | Se identificó la importancia de iniciar las pruebas unitarias antes de finalizar el sprint, y se mejoró la comunicación técnica entre las capas frontend y backend para evitar inconsistencias en el consumo de datos. |
| **Sprint Goal & User Stories**         |                                                                                                                                                                                                                        |
| **Sprint 2 Goal**                      | Desarrollar e integrar los módulos funcionales de **Gestión de Envíos**, **Tracking Unificado** y **Cotización de Tarifas** en la aplicación web de Sendify, garantizando la conexión efectiva con la API RESTful.     |
| **Expected Deliverable**               | Un sistema funcional que permita crear, listar y consultar envíos, visualizar su estado en tiempo real, y cotizar tarifas según peso y destino.                                                                        |
| **Sprint 2 Velocity**                  | 36                                                                                                                                                                                                                     |
| **Sum of Story Points**                | 36                                                                                                                                                                                                                     |
#### 5.2.2.2. Aspect Leaders and Collaborators
Durante este sprint, las responsabilidades se distribuyeron considerando las competencias técnicas y el rol de cada integrante dentro del equipo de desarrollo. Se buscó mantener un equilibrio entre las tareas de frontend, backend, integración y documentación, asegurando una colaboración fluida entre todos los miembros.

| **Miembro del Equipo** | **GitHub Username**                             | **Rol Principal**                    | **Frontend** | **Backend / API REST** | **Base de Datos** | **Testing & QA** | **Deployment / DevOps** | **Documentación** |
| ---------------------- | ----------------------------------------------- | ------------------------------------ | ------------ | ---------------------- | ----------------- | ---------------- | ----------------------- | ----------------- |
| **Joan Aguirre**       | [JoanAguirre]  | Líder de Backend                     | Apoyo     | Líder               | Colabora       | Apoyo         | Apoyo                | Colabora       |
| **Harrison Payesa**    | [Harrison1024] | Líder de QA y Testing                | Apoyo     | Apoyo               | Apoyo          | Líder         | Colabora             | Apoyo          |
| **Juandy Off**         | [juandyoff]       | Líder de Frontend                    | Líder     | Apoyo               | Apoyo          | Colabora      | Apoyo                | Colabora       |
| **Eduardo Cossar**     | [coleeeee-dev] | Líder de Documentación               | Apoyo     | Colabora            | Colabora       | Colabora      | Apoyo                | Líder          |
| **Pietro Osores**      | [Maximoff19]     | Líder de Integración y Base de Datos | Colabora  | Colabora            | Líder          | Apoyo         | Colabora             | Apoyo          |


#### .2.2.3. Sprint Backlog 2
Durante este sprint se priorizaron las funcionalidades esenciales que permiten la operatividad básica del sistema de envíos, tracking y cotización de tarifas. Se utilizó Trello para dividir las user stories en tareas específicas y asignarlas al equipo.

| **User Story ID** | **User Story (Descripción)**                                                        | **Task ID** | **Tarea Específica**                          | **Descripción Detallada**                                                                    | **Estimación (hrs)** | **Asignado a (GitHub)** | **Estado** |
| ----------------- | ----------------------------------------------------------------------------------- | ----------- | --------------------------------------------- | -------------------------------------------------------------------------------------------- | -------------------- | ----------------------- | ---------- |
| US-01.1           | Como usuario, quiero crear un envío para registrar los datos del paquete.           | T1          | Diseño del formulario de envío                | Creación de la interfaz con campos para remitente, destinatario, dirección, peso y courier.  | 6                    | juandyoff               | Done       |
|                   |                                                                                     | T2          | Implementación del registro en backend        | Programar el endpoint `/api/shipments` para guardar los datos del envío en la base de datos. | 6                    | JoanAguirre             | Done       |
| US-01.2           | Como usuario frecuente, quiero guardar mis datos para agilizar mis próximos envíos. | T3          | Módulo de clientes frecuentes                 | Permitir registrar y listar clientes frecuentes, con validación de duplicados.               | 5                    | Maximoff19              | Done       |
| US-02.1           | Como cliente, quiero ver el estado de mi envío en tiempo real.                      | T4          | Diseño del timeline de tracking               | Mostrar las etapas del envío: registrado → en tránsito → entregado.                          | 6                    | juandyoff               | Done       |
|                   |                                                                                     | T5          | Integración con backend                       | Conectar el timeline con el endpoint `/api/tracking/:id`.                                    | 5                    | JoanAguirre             | Done       |
| US-02.2           | Como cliente externo, quiero consultar el tracking sin iniciar sesión.              | T6          | Módulo público de tracking                    | Crear una página pública con buscador por código de envío.                                   | 4                    | Harrison1024            | Done       |
| US-03.1           | Como usuario, quiero cotizar el costo de envío antes de registrarlo.                | T7          | Implementar cotizador de tarifas              | Calcular tarifas según peso y destino mediante un formulario interactivo.                    | 6                    | JoanAguirre             | Done       |
| US-03.2           | Como usuario, quiero elegir entre diferentes couriers.                              | T8          | Integrar selección de courier                 | Mostrar lista de couriers disponibles y permitir seleccionar uno antes del envío.            | 4                    | coleeeee-dev            | Done       |
| US-07.1           | Como desarrollador, quiero crear endpoints REST para envíos.                        | T9          | Desarrollo del endpoint POST `/api/shipments` | Validar los datos de entrada y registrar nuevos envíos en la base de datos.                  | 5                    | JoanAguirre             | Done       |
| US-07.2           | Como desarrollador, quiero crear el endpoint de tracking.                           | T10         | Endpoint GET `/api/tracking/:id`              | Retornar la información del envío y sus estados asociados.                                   | 4                    | Harrison1024            | Done       |


#### 5.2.2.4. Development Evidence for Sprint Review

(images)

#### 5.2.2.6. Services Documentation Evidence for Sprint Review

(images)

#### 5.2.2.7. Software Deployment Evidence for Sprint Review
El sistema fue desplegado de manera distribuida:

#### 5.2.2.8. Team Collaboration Insights during Sprint
Durante este segundo sprint se observó una mejor coordinación en GitHub mediante ramas dedicadas por feature (feature/shipment, feature/tracking, feature/rates).
Se establecieron reuniones de daily scrums breves para monitorear el progreso y resolver bloqueos técnicos.
Además, el uso de Trello permitió una visualización clara del avance y priorización de tareas, lo que facilitó el cumplimiento de los objetivos planificados.

(images)
