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

**Tipografía:**

La tipografía de Sendify debe garantizar **claridad, modernidad y
legibilidad**, especialmente en dispositivos móviles y dashboards web.

  -----------------------------------------------------------------------
  Elemento UI             Tipografía elegida      Tamaño
  ----------------------- ----------------------- -----------------------
  Nombre de la app        Montserrat Bold         23 px

  Título principal                                29 px

  Subtítulo                                       17 px

  Cuerpo de texto         Montserrat Bold         15 px

  Menú                                            15 px

  Botones                                         15 px
  -----------------------------------------------------------------------

Cada tipo y tamaño de tipografía se ajustó de acuerdo a lo señalado por
el Gobierno del Perú (2021a) en sus indicaciones de tamaño de letra para
apps de escritorio y móviles

**Figura 7**

*Colours**. PALETA FOTO***

*Nota*. Elaboración propia. agrego link

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

**Header**

El header utiliza fondo **#111111** con tipografía en blanco y botones
resaltados en naranja. En versiones móviles debe ser compacto, mientras
que en pantallas grandes incluye menú expandido y barra de búsqueda de
envíos.

  -----------------------------------------------------------------------
  Dispositivo                         Resolución
  ----------------------------------- -----------------------------------
  Teléfonos Android / iOS modernos    **720 x 1280 px**

  Apple Watch                         **396 x 484 px**

  Google Nest Hub                     **1024 x 600 px**

  Android TV                          **1920 × 1080 px**

  Laptops pequeñas                    **1366 × 768 px**

  Monitores estándar                  **1920 × 1080 px**
  -----------------------------------------------------------------------

.

Estas resoluciones fueron establecidas por los datos proporcionado por
el Gobierno del Perú (2021c) para resoluciones en dispositivos
inteligentes

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

### ***4.2.2. Labeling Systems***

  ------------------------------------------------------------------------------
  **Tópico**            **Definición**
  --------------------- --------------------------------------------------------
  **Home**              Página principal de Sendify, donde se presenta el valor
                        de la plataforma, con botones de acción como *Probar
                        Demo* y *Registrarse Gratis*.

  **Funcionalidades**   Sección que explica los módulos principales: Gestión de
                        Envíos, Tracking Unificado, Cotización de Tarifas y
                        Notificaciones Inteligentes.

  **Beneficios**        Espacio donde se detallan las ventajas de usar Sendify:
                        reducción de costos, ahorro de tiempo, mayor control y
                        mejor experiencia para los clientes.

  **Testimonios**       Apartado con comentarios y reseñas de usuarios que ya
                        utilizan la plataforma.

  **Equipo**            Sección que muestra a los integrantes detrás de Sendify,
                        destacando su rol en el desarrollo y soporte de la
                        aplicación.

  **Precios**           Aquí se presentan los planes de suscripción,
                        diferenciando la versión gratuita y los planes Pro,
                        junto con sus beneficios.

  **Contacto**          Sección destinada a brindar al usuario los canales de
                        comunicación disponibles, como correo, WhatsApp o
                        formulario directo.

  **Dashboard**         Acceso directo al panel principal, donde los usuarios
                        registrados gestionan envíos, consultan tracking y
                        visualizan reportes.
  ------------------------------------------------------------------------------

4.3.Landing Page UI Design.

El diseño de la interfaz de usuario de nuestra landing page jugará un
papel fundamental en el proyecto, pues representará el primer contacto
de los usuarios con nuestro producto. Será la oportunidad de ofrecer una
experiencia atractiva y práctica, capaz de captar la atención de los
visitantes y motivarlos a seguir explorando.

4.3.1.Landing Page Wireframe

.![](media/image6.png){width="6.267716535433071in"
height="3.638888888888889in"}

![](media/image1.png){width="6.267716535433071in"
height="3.5277777777777777in"}

![](media/image5.png){width="6.267716535433071in"
height="4.527777777777778in"}

![](media/image11.png){width="6.267716535433071in"
height="3.236111111111111in"}

![](media/image4.png){width="6.267716535433071in"
height="6.222222222222222in"}

![](media/image2.png){width="6.267716535433071in"
height="1.8333333333333333in"}

4.3.2.Landing Page Mock-up.

![](media/image7.png){width="3.1875in"
height="1.5625in"}![](media/image9.png){width="3.1875in"
height="1.5416666666666667in"}![](media/image12.png){width="3.375in"
height="1.4895833333333333in"}![](media/image14.png){width="3.375in"
height="1.5416666666666667in"}![](media/image8.png){width="3.1875in"
height="1.484375546806649in"}![](media/image10.png){width="3.375in"
height="1.570754593175853in"}

4.4.Web Applications UX/UI Design.

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

4.4.1.Web Applications Wireframes.

![](media/image13.png){width="6.267716535433071in"
height="4.152777777777778in"}

4.4.2.Web Applications Wireflow Diagrams.

4.4.2.

Web Applications Mock-ups.

4.4.3.

Web Applications User Flow Diagrams.


