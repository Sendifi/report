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
- Se utilizó **Pivotal Tracker** para organizar user stories y backlog del proyecto.  

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

[Adjuntar captura de reunión de planning en Google Meet o Pivotal Tracker con historias de usuario]  

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
- Aprendizajes: registrar avances diarios con más frecuencia y documentar commits detallados.  

[Adjuntar captura de chat grupal o reunión de sprint review]  
