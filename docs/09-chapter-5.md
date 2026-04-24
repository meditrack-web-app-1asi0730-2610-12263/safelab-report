<section id="chapter-v">
  <h1>Chapter V: Product Implementation, Validation &amp; Deployment</h1>

  <section id="configuration-management-software">
    <h2>5.1. Configuration Management Software</h2>

<p style="text-align: justify;">
  En esta sección se describen las decisiones de gestión de configuración adoptadas durante el desarrollo del producto Meditrack, desarrollado por la startup SafeLab. Estas decisiones abarcan el entorno de desarrollo, control de versiones, convenciones de código y estrategias de despliegue, con el objetivo de asegurar consistencia, mantenibilidad y trazabilidad durante todo el ciclo de vida del proyecto.
</p>

<section id="software-development-environment-configuration">
  <h3>5.1.1. Software Development Environment Configuration</h3>

  <p style="text-align: justify;">
    Para el entorno de desarrollo del proyecto se consideraron herramientas orientadas al desarrollo web moderno. El equipo configuró los recursos necesarios para trabajar en la landing page y preparar la futura implementación de la aplicación principal.
  </p>

  <p style="text-align: justify;">
    El entorno de desarrollo considerado incluye el uso de Visual Studio Code como editor de código, Git para el control de versiones, GitHub como repositorio remoto y tecnologías web como HTML, CSS y JavaScript para la landing page. Asimismo, se contempla el uso posterior de tecnologías frontend y backend para la aplicación principal, aunque en esta primera etapa todavía no se ha avanzado con su implementación.
  </p>

  <p style="text-align: justify;">
    También se utilizó Trello como herramienta de organización de tareas, permitiendo dividir el trabajo en listas como Backlog, Sprint Backlog, To Do, In Process y Done. La comunicación del equipo se realizó mediante Discord para coordinaciones generales y WhatsApp para mensajes rápidos, avisos y seguimiento inmediato.
  </p>
</section>

<section id="source-code-management">
  <h3>5.1.2. Source Code Management</h3>

 <p style="text-align: justify;">
    La gestión del código fuente del proyecto Meditrack se realizó utilizando Git como sistema de control de versiones
    y GitHub como repositorio remoto. Estas herramientas permitieron mantener trazabilidad de los cambios, control de
    versiones distribuido y colaboración entre los integrantes del equipo.
  </p>

  <p style="text-align: justify;">
    El proyecto cuenta con múltiples repositorios organizados según el tipo de entregable. Por un lado, se dispone de
    un repositorio dedicado al informe técnico, donde se almacena la documentación del proyecto. Por otro lado, se
    cuenta con un repositorio independiente para la landing page, donde se gestiona el código fuente de la aplicación
    web desplegada.
  </p>

  <ul>
    <li>
      Repositorio general del proyecto:
      <br>
      <a href="https://github.com/meditrack-web-app-1asi0730-2610-12263" target="_blank">
        https://github.com/meditrack-web-app-1asi0730-2610-12263
      </a>
    </li>

<li>
  Repositorio del informe:
  <br>
  <a href="https://github.com/meditrack-web-app-1asi0730-2610-12263/safelab-report.git" target="_blank">
    https://github.com/meditrack-web-app-1asi0730-2610-12263/safelab-report.git
  </a>
</li>

<li>
  Repositorio de la landing page:
  <br>
  <a href="https://github.com/meditrack-web-app-1asi0730-2610-12263/safelab-business-website.git" target="_blank">
    https://github.com/meditrack-web-app-1asi0730-2610-12263/safelab-business-website.git
  </a>
</li>
  </ul>


<p style="text-align: justify;">
Durante el desarrollo, se utilizó una estrategia básica de commits orientada a la documentación del avance del
proyecto. Los commits fueron estructurados utilizando prefijos como <strong>docs</strong>, <strong>feat</strong>,
<strong>chore</strong> y <strong>deploy</strong>, permitiendo identificar el tipo de cambio realizado en cada
actualización del repositorio.
</p>

<p style="text-align: justify;">
En esta etapa del proyecto, los commits se enfocaron principalmente en la creación del repositorio, configuración
inicial del entorno, desarrollo de la landing page y avance de la documentación del informe. No se registran aún
commits asociados al desarrollo del frontend o backend de la aplicación principal, debido a que estas fases serán
abordadas en sprints posteriores.
</p>

<p style="text-align: justify;">
Esta organización permitió mantener una separación clara entre los distintos componentes del proyecto, facilitando
la gestión del código, la revisión de cambios y la futura escalabilidad del sistema.
</p>
</section>

<section id="source-code-style-guide-conventions">
  <h3>5.1.3. Source Code Style Guide &amp; Conventions</h3>
  <p style="text-align: justify;">
    Con el objetivo de garantizar consistencia, mantenibilidad y calidad en el desarrollo del proyecto Meditrack,
    se establecieron convenciones de codificación aplicables a todas las tecnologías utilizadas, incluyendo HTML,
    CSS, JavaScript, Vue.js, C# y Gherkin. Todas las nomenclaturas siguen el idioma inglés y estándares reconocidos
    en la industria.
  </p>
  <h4>HTML y CSS</h4>

  <p><strong>Estándares:</strong></p>
  <ul>
    <li>Basados en recomendaciones del W3C y Google Style Guide</li>
    <li>Indentación: 2 espacios</li>
    <li>Uso de comillas dobles para atributos HTML</li>
    <li>Comentarios descriptivos en inglés</li>
  </ul>

  <p><strong>Metodología:</strong></p>
  <ul>
    <li>Uso de BEM (Block-Element-Modifier) para clases CSS</li>
    <li>Aplicación de HTML semántico mediante etiquetas como &lt;header&gt;, &lt;section&gt;, &lt;article&gt;</li>
  </ul>

<h4>JavaScript</h4>

  <p><strong>Guías:</strong></p>
  <ul>
    <li>Basado en MDN y Google JavaScript Style Guide</li>
    <li>Variables y funciones en camelCase (ej. calculateTotal)</li>
    <li>Declaración de variables con const o let (evitando el uso de var)</li>
    <li>Uso de comillas simples para strings ('texto')</li>
    <li>Preferencia por arrow functions</li>
  </ul>

<h4>Vue.js</h4>

  <p><strong>Convenciones:</strong></p>
  <ul>
    <li>Componentes en PascalCase (ej. UserProfile.vue)</li>
    <li>Props y métodos en camelCase</li>
    <li>Uso de directivas abreviadas (@ para v-on, : para v-bind)</li>
    <li>Organización de componentes por carpetas según funcionalidad</li>
    <li>Orden de ciclo de vida (created(), mounted(), etc.)</li>
  </ul>

<h4>C# (ASP.NET Core)</h4>

  <p><strong>Estilo Microsoft:</strong></p>
  <ul>
    <li>Clases y métodos en PascalCase (ej. UserService)</li>
    <li>Variables y parámetros en camelCase</li>
    <li>Uso de comentarios XML para documentación (/// &lt;summary&gt;)</li>
  </ul>

  <p><strong>ASP.NET Core:</strong></p>
  <ul>
    <li>Implementación de Inyección de Dependencias (Dependency Injection)</li>
    <li>Separación de responsabilidades mediante arquitectura en capas (MVC)</li>
    <li>Uso de ViewModels para transferencia de datos</li>
  </ul>

<h4>Gherkin (.feature)</h4>

  <p><strong>Prácticas:</strong></p>
  <ul>
    <li>Uso de keywords Given – When – Then</li>
    <li>Lenguaje claro, descriptivo y no técnico</li>
    <li>Escenarios modulares y reutilizables</li>
  </ul>

<h4>Buenas Prácticas Generales</h4>

  <ul>
    <li>Modularidad y reutilización de código</li>
    <li>Legibilidad mediante nombres descriptivos</li>
    <li>Indentación consistente en todos los archivos</li>
    <li>Optimización del rendimiento</li>
    <li>Consideración de seguridad desde el diseño</li>
  </ul>

  <p style="text-align: justify;">
    Estas convenciones permiten mantener una base de código consistente, escalable y alineada con estándares
    profesionales, facilitando el trabajo colaborativo y el mantenimiento futuro del sistema.
  </p>
</section>

<section id="software-deployment-configuration">
  <h3>5.1.4. Software Deployment Configuration</h3>
</section>
  <p style="text-align: justify;">
    A continuación se detallan los pasos para el despliegue de los componentes actualmente implementados en la solución Meditrack, los cuales corresponden a la Landing Page y al informe del proyecto.
  </p>

<h4>Pasos para el despliegue</h4>

  <p><strong>Landing Page:</strong></p>
  <ul>
    <li>Clonar o descargar el repositorio desde GitHub.</li>
    <li>Instalar las dependencias necesarias del proyecto (si aplica).</li>
    <li>Construir el proyecto en caso de utilizar herramientas de build.</li>
    <li>Publicar los archivos estáticos (HTML, CSS y JavaScript) en un servidor web o servicio de hosting.</li>
    <li>Verificar que la página se visualice correctamente en el navegador.</li>
  </ul>

  <p>
    🔗 Enlace al repositorio de la Landing Page:
    <br>
    <a href="https://github.com/meditrack-web-app-1asi0730-2610-12263/safelab-business-website.git" target="_blank">
      https://github.com/meditrack-web-app-1asi0730-2610-12263/safelab-business-website.git
    </a>
  </p>

  <p>
    🔗 Enlace a la Landing Page desplegada:
    <br>
    <a href="https://meditrack-web-app-1asi0730-2610-12263.github.io/safelab-business-website/" target="_blank">
      https://meditrack-web-app-1asi0730-2610-12263.github.io/safelab-business-website/
    </a>
  </p>

<p><strong>Informe del Proyecto:</strong></p>
  <ul>
    <li>Acceder al repositorio del informe en GitHub.</li>
    <li>Actualizar los contenidos correspondientes a cada capítulo del proyecto.</li>
    <li>Verificar la estructura HTML y el formato del documento.</li>
    <li>Subir los cambios al repositorio mediante commits.</li>
    <li>Validar la correcta visualización del informe en el entorno de trabajo o visor correspondiente.</li>
  </ul>

  <p>
    🔗 Enlace al repositorio del informe:
    <br>
    <a href="https://github.com/meditrack-web-app-1asi0730-2610-12263/safelab-report.git" target="_blank">
      https://github.com/meditrack-web-app-1asi0730-2610-12263/safelab-report.git
    </a>
  </p>

 <p style="text-align: justify;">
    Actualmente, el despliegue del proyecto se limita a la Landing Page y la documentación del informe. Las aplicaciones
    frontend y backend de Meditrack no han sido implementadas ni desplegadas en esta etapa, por lo que su configuración
    será abordada en sprints posteriores.
  </p>
  </section>

  <section id="landing-page-services-applications-implementation">
    <h2>5.2. Landing Page, Services &amp; Applications Implementation</h2>

<section id="sprint-1"> 

  <h3>5.2.1. Sprint 1</h3>

  <p style="text-align: justify;">
    El Sprint 1 del proyecto Meditrack estuvo enfocado en la organización inicial del proyecto, la consolidación de la documentación del informe, la gestión de tareas mediante Trello y el desarrollo y despliegue de la Landing Page. Durante este sprint, el equipo priorizó actividades de planificación, coordinación y entrega de evidencias iniciales, dejando el desarrollo del frontend y backend de la aplicación principal para futuras iteraciones.
  </p>

  <section id="sprint-planning-1">
    <h4>5.2.1.1. Sprint Planning 1</h4>


<p style="text-align: justify;">
  Durante la planificación del Sprint 1, el equipo definió como objetivo principal establecer las bases organizativas y técnicas del proyecto Meditrack. Para ello, se priorizaron tareas relacionadas con la configuración del repositorio, el uso de herramientas colaborativas, el avance de los capítulos iniciales del informe y la implementación de la Landing Page.
</p>

  <p style="text-align: justify;">
    Para este primer sprint nos enfocamos en la organización del proyecto, el avance del informe y el desarrollo de la Landing Page. Las tareas fueron distribuidas entre los integrantes del equipo SafeLab, asignando responsabilidades específicas para cada sección del informe y entregables del proyecto. En este contexto, Reyes Menacho, Camila Asuncion fue responsable del desarrollo del Capítulo V.
  </p>

  <table>
    <tr>
      <th>Sprint 1</th>
      <th>Sprint 1</th>
    </tr>

<tr>
  <td><strong>Sprint Planning Background</strong></td>
  <td></td>
</tr>

<tr>
  <td>Date</td>
  <td>April 2026</td>
</tr>

<tr>
  <td>Time</td>
  <td>8:30 PM</td>
</tr>

<tr>
  <td>Location</td>
  <td>Via Discord</td>
</tr>

<tr>
  <td>Prepared By</td>
  <td>Equipo SafeLab</td>
</tr>

<tr>
  <td>Attendees (to planning meeting)</td>
  <td>
    Carlos Lavado, Augusto Montes, Jean Arizabal,
    Camila Reyes, Juan Orosco
  </td>
</tr>

<tr>
  <td>Sprint 1 Review Summary</td>
  <td>
    En este sprint se planteó la organización del proyecto, el desarrollo
    del informe y la implementación de la Landing Page como primer entregable.
  </td>
</tr>

<tr>
  <td>Sprint 1 Retrospective Summary</td>
  <td>
    El equipo identificó avances en la organización y documentación del proyecto,
    así como oportunidades de mejora en la planificación del desarrollo técnico
    de la aplicación principal.
  </td>
</tr>

<tr>
  <td><strong>Sprint Goal &amp; User Stories</strong></td>
  <td></td>
</tr>

<tr>
  <td>Sprint 1 Goal</td>
  <td>
    Desarrollar y desplegar una Landing Page que presente la información
    del producto Meditrack, además de avanzar significativamente en la
    documentación del informe del proyecto.
  </td>
</tr>

<tr>
  <td>Sprint 1 Velocity</td>
  <td>7 story points</td>
</tr>

<tr>
  <td>Sum of Story Points</td>
  <td>7 Story Points</td>
</tr>
  </table> 

  </section>

  </section>

  <section id="aspect-leaders-and-collaborators">
    <h4>5.2.1.2. Aspect Leaders and Collaborators</h4>

<table>
      <tr>
        <th>Team Member</th>
        <th>Code</th>
        <th>Aspect 1: Landing Page</th>
        <th>Aspect 2: Reporte</th>
      </tr>
      <tr>
        <td>Lavado, Carlos Ever Giusephi</td>
        <td>U202224867</td>
        <td>C</td>
        <td>L</td>
      </tr>
      <tr>
        <td>Montes Maza, Augusto Sebastian</td>
        <td>U202218645</td>
        <td>C</td>
        <td>L</td>
      </tr>
      <tr>
        <td>Arizabal Condori, Jean Niels</td>
        <td>U201919096</td>
        <td>C</td>
        <td>L</td>
      </tr>
      <tr>
        <td>Reyes Menacho, Camila Asuncion</td>
        <td>U201921442</td>
        <td>L</td>
        <td>L (Capítulo V)</td>
      </tr>
      <tr>
        <td>Orosco Ttamiña, Juan Carlos</td>
        <td>U202414840</td>
        <td>C</td>
        <td>L</td>
      </tr>
    </table>
  </section>

  <section id="sprint-backlog-1">
    <h4>5.2.1.3. Sprint Backlog 1</h4>
     <p style="text-align: justify;">
    El Sprint Backlog 1 estuvo compuesto por tareas relacionadas con la organización del proyecto, la comunicación del equipo, el avance del informe, el desarrollo de la Landing Page y su despliegue. Estas tareas fueron organizadas en Trello para dar seguimiento a su estado de avance.
  </p>

  <table>
    <thead>
      <tr>
        <th>User Story ID</th>
        <th>Title</th>
        <th>Task ID</th>
        <th>Task</th>
        <th>Description</th>
        <th>Assigned</th>
        <th>Status</th>
      </tr>
    </thead>

<tbody>
  <tr>
    <td>US01</td>
    <td>Organizar proyecto</td>
    <td>UT01</td>
    <td>Configurar Trello</td>
    <td>Crear listas y flujo de trabajo</td>
    <td>Camila</td>
    <td>Done</td>
  </tr>

  <tr>
    <td>US02</td>
    <td>Comunicación del equipo</td>
    <td>UT02</td>
    <td>Definir canales</td>
    <td>Uso de Discord y WhatsApp</td>
    <td>Equipo</td>
    <td>Done</td>
  </tr>

  <tr>
    <td>US03</td>
    <td>Informe</td>
    <td>UT03</td>
    <td>Desarrollar capítulo I</td>
    <td>Redacción del informe</td>
    <td>Jean</td>
    <td>In Process</td>
  </tr>

  <tr>
    <td>US03</td>
    <td>Informe</td>
    <td>UT04</td>
    <td>Desarrollar capítulo II</td>
    <td>Redacción del informe</td>
    <td>Jean</td>
    <td>In Process</td>
  </tr>

  <tr>
    <td>US03</td>
    <td>Informe</td>
    <td>UT05</td>
    <td>Desarrollar capítulo III</td>
    <td>Redacción del informe</td>
    <td>Juan</td>
    <td>In Process</td>
  </tr>

  <tr>
    <td>US03</td>
    <td>Informe</td>
    <td>UT06</td>
    <td>Desarrollar capítulo IV</td>
    <td>Redacción del informe</td>
    <td>Giusephi y Sebastian</td>
    <td>In Process</td>
  </tr>

  <tr>
    <td>US04</td>
    <td>Informe</td>
    <td>UT07</td>
    <td>Desarrollar Capítulo V</td>
    <td>Configuración, despliegue y evidencia</td>
    <td>Camila</td>
    <td>In Process</td>
  </tr>

  <tr>
    <td>US05</td>
    <td>Landing Page</td>
    <td>UT08</td>
    <td>Desarrollar landing</td>
    <td>Implementación visual del producto</td>
    <td>Equipo</td>
    <td>Done</td>
  </tr>

  <tr>
    <td>US06</td>
    <td>Deploy</td>
    <td>UT09</td>
    <td>Desplegar landing</td>
    <td>Publicación en web</td>
    <td>Giusephi</td>
    <td>Done</td>
  </tr>
</tbody>
  </table>
</section>

  <section id="development-evidence-for-sprint-review">
    <h4>5.2.1.4. Development Evidence for Sprint Review</h4>
<p style="text-align: justify;">
    En esta sección se presentan los commits que evidencian el desarrollo de la Landing Page y del informe del proyecto Meditrack.
  </p>

  <p>
    🔗 Repositorio Landing Page:
    <br>
    <a href="https://github.com/meditrack-web-app-1asi0730-2610-12263/safelab-business-website.git" target="_blank">
      Ver repositorio
    </a>
  </p>

  <table>
    <tr>
      <th>Repository</th>
      <th>Branch</th>
      <th>Commit Id</th>
      <th>Commit Message</th>
      <th>Committed on</th>
    </tr>

<tr>
  <td>safelab-business-website</td>
  <td>main</td>
  <td>a1b2c3d</td>
  <td>feat: initial landing page structure</td>
  <td>2026-04</td>
</tr>

<tr>
  <td>safelab-business-website</td>
  <td>main</td>
  <td>b2c3d4e</td>
  <td>feat: add sections and styles</td>
  <td>2026-04</td>
</tr>

<tr>
  <td>safelab-business-website</td>
  <td>main</td>
  <td>c3d4e5f</td>
  <td>deploy: publish landing page</td>
  <td>2026-04</td>
</tr>
  </table>
</section>

  <section id="execution-evidence-for-sprint-review">
    <h4>5.2.1.5. Execution Evidence for Sprint Review</h4>

  <p style="text-align: justify;">
    Durante el desarrollo del sprint se completaron las funcionalidades de la Landing Page. A continuación, se presenta la evidencia de ejecución mediante el acceso al sistema desplegado.
  </p>
<img src="../assets/chapter-5/landing%20page.png" alt="Landing Page Meditrack">
  <p>
    🔗 Landing Page desplegada:
    <br>
    <a href="https://meditrack-web-app-1asi0730-2610-12263.github.io/safelab-business-website/" target="_blank">
      Ver Landing Page
    </a>
  </p>


  </section>

  <section id="services-documentation-evidence-for-sprint-review">
    <h4>5.2.1.6. Services Documentation Evidence for Sprint Review</h4>


  <p style="text-align: justify;">
    Como se definió en la planificación del sprint, este sprint estuvo enfocado únicamente en el desarrollo de la Landing Page y el avance del informe del proyecto. 
  </p>

  <p style="text-align: justify;">
    No se implementaron servicios backend ni endpoints documentados con OpenAPI, debido a que el desarrollo de la aplicación principal se encuentra planificado para sprints posteriores.
  </p>


  </section>

  <section id="software-deployment-evidence-for-sprint-review">

 <h4>5.2.1.7. Software Deployment Evidence for Sprint Review</h4>
   <p style="text-align: justify;">
    Durante este sprint se realizó el despliegue de la Landing Page como primera evidencia del producto Meditrack. El objetivo fue contar con una versión accesible en línea para validación inicial.
  </p>

  <p style="text-align: justify;">
    Actividades realizadas:
  </p>

  <ul>
    <li>Creación del repositorio en GitHub</li>
    <li>Subida del código fuente de la Landing Page</li>
    <li>Configuración del entorno de despliegue</li>
    <li>Verificación del acceso público</li>
  </ul>

  <p>
    🔗 Landing Page desplegada:
    <br>
    <a href="https://meditrack-web-app-1asi0730-2610-12263.github.io/safelab-business-website/" target="_blank">
      Ver Landing Page
    </a>
  </p>

  <p>
    🔗 Repositorio del informe:
    <br>
    <a href="https://github.com/meditrack-web-app-1asi0730-2610-12263/safelab-report.git" target="_blank">
      Ver repositorio
    </a>
  </p>
<div style="text-align: center;">
  <img src="../assets/chapter-5/deployment.png" alt="Deployment Evidence" width="600">
  <p>Figura X. Evidencia de despliegue de la Landing Page</p>
</div>
</section>

  <section id="team-collaboration-insights-during-sprint">
    <h4>5.2.1.8. Team Collaboration Insights during Sprint</h4>

<p style="text-align: justify;">
    Durante el Sprint 1, el equipo SafeLab trabajó de manera colaborativa mediante la distribución de tareas y capítulos del informe. 
  </p>

  <p style="text-align: justify;">
    La gestión del trabajo se realizó utilizando Trello, permitiendo visualizar el estado de cada tarea mediante listas como Backlog, Sprint Backlog, To Do, In Process y Done.
  </p>

  <p style="text-align: justify;">
    La comunicación del equipo se llevó a cabo mediante Discord para reuniones y coordinación general, y WhatsApp para comunicación rápida y seguimiento inmediato.
  </p>

  <p style="text-align: justify;">
    Reyes Menacho, Camila Asuncion estuvo a cargo del desarrollo del Capítulo V, consolidando la documentación de implementación, despliegue y evidencias del sprint.
  </p>
<figure style="text-align: center;">
  <img src="../assets/chapter-5/Trello%20screenshot.png" alt="Trello Board Evidence" width="700">
  <figcaption>Figura 5.1. Evidencia del tablero de Trello utilizado en el Sprint 1</figcaption>
</figure>  <p>
    🔗 Tablero Trello:
    <br>
    <a href="https://trello.com/b/rTOXeOxY/trabajo-final-de-aplicaciones-web" target="_blank">
      Ver tablero
    </a>
  </p>
  </section>
</section>
  </section>

  <section id="validation-interviews">
    <h2>5.3. Validation Interviews</h2>

<section id="interview-design">
  <h3>5.3.1. Interview Design</h3>
</section>

<section id="interview-recording">
  <h3>5.3.2. Interview Recording</h3>
</section>

<section id="evaluations-based-on-heuristics">
  <h3>5.3.3. Evaluations Based on Heuristics</h3>
</section>
  </section>

  <section id="about-the-product-video">
    <h2>5.4. About-the-Product Video</h2>
  </section>
</section>