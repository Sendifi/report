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

<img src="https://files.catbox.moe/x7ekav.png" alt="Eduardo image" width="200">

<img src="https://files.catbox.moe/b236wz.png" alt="Eduardo image" width="200">

<img src="https://files.catbox.moe/6rkjea.png" alt="Eduardo image" width="200">

<img src="https://files.catbox.moe/62zu6b.png" alt="Eduardo image" width="200">


#### 5.2.2.6. Services Documentation Evidence for Sprint Review

A continuación, se presentan tres fragmentos de código que evidencian el uso e implementación de los servicios en el aplicación, abarcando desde la configuración de rutas hasta la lógica de negocio y la presentación de datos al usuario:

Archivo de Rutas (Vue.js Routing) 
Archivo: router/index.js 

Función: Define la estructura de navegación de toda la aplicación

Importancia: -Permite acceder a las páginas donde se usan servicios
 -Es el punto de entrada para mostrar componentes que a su vez usan servicios para obtener, actualizar o eliminar datos.

<img src="https://files.catbox.moe/28j09f.png" alt="Eduardo image" width="200">


httpService (Implementation Service Class) Archivo: http.service.ts Función: Es una clase utilitaria que centraliza operaciones comunes de los servicios (GET, PUT, PATCH).

Importancia:

Estandariza el consumo de APIs REST.

Evita duplicar código al implementar métodos reutilizables para manejar recursos.

Permite manejar errores con catchError y hacer reintentos con retry.



<img src="https://files.catbox.moe/zj0o2g.png" alt="Eduardo image" width="200">

#### 5.2.2.7. Software Deployment Evidence for Sprint Review
El sistema fue desplegado de manera distribuida:

Link del Frontend desplegado: https://proyecto-sendify.vercel.app


#### 5.2.2.8. Team Collaboration Insights during Sprint
Durante este segundo sprint se observó una mejor coordinación en GitHub mediante ramas dedicadas por feature (feature/shipment, feature/tracking, feature/rates).
Se establecieron reuniones de daily scrums breves para monitorear el progreso y resolver bloqueos técnicos.
Además, el uso de Trello permitió una visualización clara del avance y priorización de tareas, lo que facilitó el cumplimiento de los objetivos planificados.

<img src="https://files.catbox.moe/rcukfb.png" alt="Eduardo image" width="200">


### 5.2.3. Sprint 3

#### 5.2.3.1.Sprint Planning 3

Dentro del marco de trabajo Scrum, cada Sprint constituye un periodo de tiempo fijo y breve en el que el equipo de desarrollo trabaja de manera enfocada para alcanzar un objetivo específico que contribuya al cumplimiento del Product Goal (Schwaber, K. & Sutherland, J., 2020). En el contexto del desarrollo de la plataforma sendify, el Sprint #3 dio inicio el 29/05/2025, y su meta consiste en completar la aplicación web del lado frontend y comenzar con el backend . Durante este Sprint, se desarrollaron las funcionalidades esenciales para ambos segmentos objetivo - trabajadores técnicos independientes y usuarios que requieren servicios técnicos: los clientes pueden explorar perfiles de diferentes trabajadores técnicos y solicitar sus servicios de manera intuitiva, mientras que los trabajadores técnicos tienen acceso a herramientas de gestión que les permiten configurar sus tarifas, administrar sus servicios ofrecidos y visualizar las solicitudes de trabajo asignadas.

<table>
   <tr>
      <td colspan="1" align="center"><b>Sprint #</b></td>
      <td colspan="1" align="center">Sprint 3</td>
   </tr>
   <tr>
      <td colspan="2" align="center"><b>Sprint Planning Background</b></td>
   </tr>
   <tr>
      <td colspan="1" align="center"><b>Date</b></td>
      <td colspan="1">2025-11-05</td>
   </tr>
   <tr>
      <td colspan="1" align="center"><b>Time</b></td>
      <td colspan="1">09:00 PM</td>
   </tr>
   <tr>
      <td colspan="1" align="center"><b>Location</b></td>
      <td colspan="1">Reunión virtual mediante la aplicación Discord</td>
   </tr>
   <tr>
      <td colspan="1" align="center"><b>Prepare By</b></td>
      <td colspan="1">Joan Aguirre</td>
   </tr>
   <tr>
      <td colspan="1" align="center"><b>Attendees (to planning meeting)</b></td>
      <td colspan="1">Joan Aguirre, Miguel Esquirva, Pietro Osores, Harrison Payesa, Eduardo Cossar</td>
   </tr>
   <tr>
      <td colspan="1" align="center"><b>Sprint n - 3 Review Summary</b></td>
      <td colspan="1">Durante este sprint se mejoro el frontend de la aplicación web utilizando Vue.js y PrimeVue, tambien se realizo el backend utilizando C#</td>
   </tr>
   <tr>
      <td colspan="1" align="center"><b>Sprint n - 3 Retrospective Summary</b></td>
      <td colspan="1">Se identificó la necesidad de mejorar la planificación de tareas y la integración temprana de pruebas para evitar retrabajos. También se destacó una mayor fluidez en la comunicación del equipo respecto al sprint anterior, lo que permitió avanzar con mayor claridad en los entregables.</td>
   </tr>
   <tr>
      <td colspan="2" align="center"><b>Sprint Goal & User Stories</b></td>
   </tr>
   <tr>
      <td colspan="1" align="center"><b>Sprint 3 Goal</b></td>
      <td colspan="1"><b>Our focus in on</b> developing the full web application frontend using Vue.js and PrimeVue, also we are developing the backend for this app<br><b>We believe it delivers</b> a functional and responsive interface that supports key actions.<br><b>This will be confirmed when</b> customers can find a good deal for their shipments.</td>
   </tr>
   <tr>
      <td colspan="1" align="center"><b>Sprint 3 Velocity</b></td>
      <td colspan="1">5</td>
   </tr>
   <tr>
      <td colspan="1" align="center"><b>Sum of Story Points</b></td>
      <td colspan="1">18</td>
   </tr>

   <tr>
</tr>
</table>


#### 5.2.2.2. Aspect Leaders and Collaborators.

Para este Sprint, se han identificado los principales aspectos del backend application de Sendiy. Con el fin de mejorar la organización y la comunicación del equipo, se ha elaborado la matriz Leadership and Collaboration Matrix (LACX), donde se define quién asume el rol de Líder (L) y quiénes participan como Colaboradores (C) en cada uno de estos aspectos clave. Esta distribución facilita una ejecución más clara y eficiente de las tareas asignadas.

| **Miembro del Equipo** | **GitHub Username**                             | **Rol Principal**                    | **Shipping** | **Delivery** | **User** | **Tracking** | **Deployment / DevOps** | **Courier** |
| ---------------------- | ----------------------------------------------- | ------------------------------------ | ------------ | ---------------------- | ----------------- | ---------------- | ----------------------- | ----------------- |
| **Joan Aguirre**       | [JoanAguirre]  | Líder de Delivery API                     | Apoyo     | Líder               | Colabora       | Apoyo         | Apoyo                | Colabora       |
| **Harrison Payesa**    | [Harrison1024] | Líder de Tracking API                | Apoyo     | Apoyo               | Apoyo          | Líder         | Colabora             | Apoyo          |
| **Juandy Off**         | [juandyoff]       | Líder de Shipping API                    | Líder     | Apoyo               | Apoyo          | Colabora      | Apoyo                | Colabora       |
| **Eduardo Cossar**     | [coleeeee-dev] | Líder de Courier API               | Apoyo     | Colabora            | Colabora       | Colabora      | Apoyo                | Líder          |
| **Pietro Osores**      | [Maximoff19]     | Líder de User API | Colabora  | Colabora            | Líder          | Apoyo         | Colabora             | Apoyo          |


#### 5.2.3.3.Sprint Backlog 3.

En el tercer sprint backlog, el equipo tuvo la intención de avanzar de manera significativa en el desarrollo del backend de Sendify, consolidando la arquitectura del sistema e implementando los servicios principales relacionados con la gestión de envíos, el tracking y la cotización de tarifas. En este periodo se trabajó en la definición de las entidades, endpoints y la lógica de negocio necesaria para soportar las operaciones básicas de la plataforma, dejando preparado el backend para su posterior integración con el frontend.



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
| US-07.1           | Como desarrollador, quiero crear endpoints REST para envíos.                        | T9          | Desarrollo del endpoint POST `/api/shipments` | Validar los datos de entrada y registrar nuevos envíos en la base de datos.                  | 5                    | Maximoff19             | Done       |
| US-07.2           | Como desarrollador, quiero crear el endpoint de tracking.                           | T10         | Endpoint GET `/api/tracking/:id`              | Retornar la información del envío y sus estados asociados.                                   | 4                    | Harrison1024            | Done       |



Enlace para acceder al Trello: [Trello Sprint Backlog 3](https://trello.com/invite/b/683a3962930000c3d5ef87f0/ATTI302ef236cfd65c123fb226b68a19bffeF566BB88/jobconnect-sprint-3)

#### 5.2.2.4.Development Evidence for Sprint Review.


#### 5.2.3.5.Execution Evidence for Sprint Review.




#### 5.2.3.6.Services Documentation Evidence for Sprint Review.

Se contempla los servicios de Mysql, con Swagger y OpenAPI para la creación de la documentación interactiva y además de la conección con BD.




#### 5.2.3.7.Software Deployment Evidence for Sprint Review.

No se logró el despligue de la aplicación backend.  


#### 5.2.3.8.Team Collaboration Insights during Sprint.

<img src="https://files.catbox.moe/rcukfb.png" alt="Eduardo image" width="400">


