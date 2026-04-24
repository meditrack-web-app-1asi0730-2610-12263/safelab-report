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


</section>

<section id="software-deployment-configuration">
  <h3>5.1.4. Software Deployment Configuration</h3>
</section>
  </section>

  <section id="landing-page-services-applications-implementation">
    <h2>5.2. Landing Page, Services &amp; Applications Implementation</h2>

<section id="sprint-n">
  <h3>5.2.X. Sprint n</h3>

  <section id="sprint-planning-n">
    <h4>5.2.X.1. Sprint Planning n</h4>
  </section>

  <section id="aspect-leaders-and-collaborators">
    <h4>5.2.X.2. Aspect Leaders and Collaborators</h4>
  </section>

  <section id="sprint-backlog-n">
    <h4>5.2.X.3. Sprint Backlog n</h4>
  </section>

  <section id="development-evidence-for-sprint-review">
    <h4>5.2.X.4. Development Evidence for Sprint Review</h4>
  </section>

  <section id="execution-evidence-for-sprint-review">
    <h4>5.2.X.5. Execution Evidence for Sprint Review</h4>
  </section>

  <section id="services-documentation-evidence-for-sprint-review">
    <h4>5.2.X.6. Services Documentation Evidence for Sprint Review</h4>
  </section>

  <section id="software-deployment-evidence-for-sprint-review">
    <h4>5.2.X.7. Software Deployment Evidence for Sprint Review</h4>
  </section>

  <section id="team-collaboration-insights-during-sprint">
    <h4>5.2.X.8. Team Collaboration Insights during Sprint</h4>
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