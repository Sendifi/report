# Capítulo V: Product Implementation, Validation & Deployment

## 5.1. Software Configuration Management

En esta sección se detallan todas las reglas y procesos que hemos seguido en el proyecto **Sendify** al momento de crear y desplegar la aplicación web. El objetivo es garantizar la integridad y consistencia del software desde el inicio hasta el despliegue y mantenimiento.  

### 5.1.1. Software Development Environment Configuration

**Project Management**  
- Centro de organización del trabajo: **GitHub**  
- Planificación de tareas: **Pivotal Tracker**  
- Reuniones con el equipo: **Google Meet**  
- Comunicación grupal: **WhatsApp**  

**Requirements Management**  
- Se utilizó **Pivotal Tracker** para organizar user stories y backlog del proyecto.  

| Herramienta | Descripción | Enlace |
|-------------|-------------|--------|
| Pivotal Tracker | Gestión de historias de usuario y backlog | https://www.pivotaltracker.com/ |

**Product UX/UI Design**  
- Se utilizó **Figma** para crear wireframes, mockups y prototipos interactivos.  

| Herramienta | Descripción | Enlace |
|-------------|-------------|--------|
| Figma | Diseño de prototipos y wireframes | https://www.figma.com/ |  

[Adjuntar capturas de Figma: wireframe y mockup de la landing]  

**Software Development**  
- **Frontend:** HTML, CSS y JavaScript para la Landing Page.  
- **Backend (futuro):** Node.js + Express.  

| Herramienta | Descripción | Enlace |
|-------------|-------------|--------|
| HTML | Estructura semántica de la página | https://www.w3schools.com/html/ |
| CSS | Estilos visuales y responsividad | https://www.w3schools.com/css/ |
| JavaScript | Interactividad básica | https://www.javascript.com/ |  

**Software Deployment**  
- La landing page fue desplegada en **GitHub Pages**.  

[Adjuntar captura de la configuración de GitHub Pages]  

---

### 5.1.2. Source Code Management

Repositorios creados:  

| Producto     | Repositorio        | URL |
|--------------|-------------------|-----|
| Reporte      | Sendify-Report     | https://github.com/Sendifi/report.git |
| Landing Page | Sendify-Landing    | https://github.com/Sendifi/LandingPage.git |  

[Adjuntar captura de la organización y repositorios en GitHub]  

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
- Configuración de GitHub Pages en rama `main`.  
- Despliegue activo en:  
🔗 https://sendifi.github.io/LandingPage/  

[Adjuntar captura del sitio en línea funcionando]  

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
| US001 | Ver secciones principales | Navbar | Navegación entre Home, Funcionalidades, Planes, Contacto | 3 | Done |
| US002 | Ver diseño atractivo | Estilizar landing | Colores corporativos y tipografía | 4 | Done |
| US003 | Explorar funcionalidades | Sección servicios | Mostrar Gestión de envíos, Tracking, Flota | 3 | Done |
| US004 | Comparar planes | Pricing | Tarjetas Starter, Pro, Enterprise | 3 | Done |
| US005 | Validar confianza | Testimonios | Sección de usuarios satisfechos | 3 | Done |
| US006 | Contactar equipo | Formulario | Nombre, correo, mensaje | 4 | Done |
| US007 | Información final | Footer | Redes sociales y contacto | 2 | Done |  

[Adjuntar captura de Sprint Backlog en Pivotal Tracker o GitHub Projects]  

---

#### 5.2.1.4. Development Evidence for Sprint Review

Commits y merges destacados en el repositorio **LandingPage**:  

| Branch | Commit/PR | Mensaje | Estado | Deploy | Responsable |
|--------|-----------|---------|--------|--------|-------------|
| feature → develop | PR #2 | Merge pull request #2 from Sendifi/feature | ✅ Deployed | GitHub Pages (#17) | Maximoff19 |
| feature → develop | PR #1 | Merge pull request #1 from Sendifi/feature | ✅ Deployed | GitHub Pages (#16) | Maximoff19 |
| main | commit | docs: Add the LandingPage link | ✅ Deployed | GitHub Pages (#15) | Maximoff19 |
| develop | commit | feat: add initial version of landing page | ✅ Deployed | GitHub Pages (#14) | Maximoff19 |
| main | commit | chore(assets): remove Logo header.png.png | ✅ Deployed | GitHub Pages (#13) | Maximoff19 |
| main | commit | chore(assets): remove LANDINGPAGE-SENDIFY.png | ❌ Failed | GitHub Pages (#12) | Maximoff19 |
| main | commit | chore(assets): remove IMAGEN HERO.png | ✅ Deployed | GitHub Pages (#11) | Maximoff19 |

[Adjuntar captura de historial de commits en GitHub]  

---

#### 5.2.1.5. Testing Suite Evidence for Sprint Review

Durante este primer sprint no se realizaron pruebas automatizadas, ya que el objetivo principal fue el desarrollo visual y despliegue de la landing.  

Se ejecutaron pruebas **manuales**:  
- Navegación entre secciones.  
- Visualización en distintos dispositivos (desktop, tablet, móvil).  
- Funcionamiento de enlaces y botones principales.  

📌 Las pruebas automáticas se implementarán en siguientes sprints junto al backend.  

---

#### 5.2.1.6. Execution Evidence for Sprint Review

La landing está desplegada en:  
🔗 https://sendifi.github.io/LandingPage/  

Incluye:  
1. Hero con slogan: “Tu logística, más simple y digital”.  
2. Sección de funcionalidades principales.  
3. Planes de suscripción (Starter, Pro, Enterprise).  
4. Testimonios de clientes.  
5. Formulario de contacto.  
6. Footer con redes sociales y contacto.  

[Adjuntar capturas de cada sección de la landing desplegada]  

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

[Adjuntar captura del deployment exitoso en GitHub Pages]  

---

#### 5.2.1.9. Team Collaboration Insights during Sprint

- 2 reuniones en Google Meet (inicio y cierre).  
- Comunicación continua en WhatsApp.  
- Uso de GitHub Projects para seguimiento.  
- Aprendizajes: registrar avances diarios con más frecuencia y documentar commits detallados.  

[Adjuntar captura de chat grupal o reunión de sprint review]  
