# **Chapter V: Product Implementation, Validation &amp; Deployment**
## **5.1. Configuration Management Software**

<p style="text-align: justify;">
  This section describes the configuration management decisions adopted during the development of the Meditrack product, developed by the SafeLab startup. These decisions cover the development environment, version control, coding conventions, and deployment strategies, with the goal of ensuring consistency, maintainability, and traceability throughout the entire project lifecycle.
</p>

### **5.1.1. Software Development Environment Configuration**
<p style="text-align: justify;">
  For the project development environment, tools oriented toward modern web development were considered. The team configured the necessary resources to work on the landing page and prepare the future implementation of the main application.
</p>

<p style="text-align: justify;">
  The development environment includes the use of Visual Studio Code as the code editor, Git for version control, GitHub as the remote repository, and web technologies such as HTML, CSS, and JavaScript for the landing page. Additionally, the future use of frontend and backend technologies for the main application is considered, although at this initial stage, their implementation has not yet begun.
</p>

<p style="text-align: justify;">
  Trello was also used as a task management tool, allowing work to be divided into lists such as Backlog, Sprint Backlog, To Do, In Process, and Done. Team communication was carried out through Discord for general coordination and WhatsApp for quick messages, alerts, and immediate follow-up.
</p>

<div style="page-break-after: always;"></div>

### **5.1.2. Source Code Management**
<p style="text-align: justify;">
  The source code management of the Meditrack project was carried out using Git as the version control system and GitHub as the remote repository. These tools allowed maintaining traceability of changes, distributed version control, and collaboration among team members.
</p>

<p style="text-align: justify;">
  The project has multiple repositories organized according to the type of deliverable. On one hand, there is a repository dedicated to the technical report, where project documentation is stored. On the other hand, there is an independent repository for the landing page, where the source code of the deployed web application is managed.
</p>

<ul>
  <li>
    <a href="https://github.com/meditrack-web-app-1asi0730-2610-12263" target="_blank">
      General Project Repository
    </a>
  </li>
  <li>
    <a href="https://github.com/meditrack-web-app-1asi0730-2610-12263/safelab-report.git" target="_blank">
      Report Repository:
    </a>
  </li>
  <li>
    <a href="https://github.com/meditrack-web-app-1asi0730-2610-12263/safelab-business-website.git" target="_blank">
      Landing page Repository
    </a>
  </li>
</ul>

<p style="text-align: justify;">
  During development, a basic commit strategy focused on documenting project progress was used. Commits were structured using prefixes such as <b>docs</b>, <b>feat</b>, <b>chore</b>, and <b>deploy</b>, allowing identification of the type of change made in each repository update.
</p>

<p style="text-align: justify;">
  At this stage of the project, commits mainly focused on repository creation, initial environment setup, landing page development, and progress on report documentation. There are still no commits related to frontend or backend development of the main application, as these phases will be addressed in later sprints.
</p>

<p style="text-align: justify;">
  This organization allowed maintaining a clear separation between the different components of the project, facilitating code management, change review, and future system scalability.
</p>

### **5.1.3. Source Code Style Guide & Conventions**

<p style="text-align: justify;">
  In order to ensure consistency, maintainability, and quality in the development of the Meditrack project, coding conventions were established for all technologies used, including HTML, CSS, JavaScript, Vue.js, C#, and Gherkin. All naming conventions follow the English language and recognized industry standards.
</p>

<ul>
  <li>
    <b>HTML and CSS</b>
    <ul>
      <li>
        <b>Standards:</b>
        <ul>
          <li>
            Based on W3C recommendations and Google Style Guide
          </li>
          <li>
            Indentation: 2 spaces
          </li>
          <li>
            Use of double quotes for HTML attributes
          </li>
          <li>
            Descriptive comments in English
          </li>
        </ul>
      </li>
      <li>
        <b>Methodology:</b>
        <ul>
          <li>
            Use of BEM (Block-Element-Modifier) for CSS classes
          </li>
          <li>
            Use of semantic HTML tags such as &lt;header&gt;, &lt;section&gt;, &lt;article&gt;
          </li>
        </ul>
      </li>
    </ul>
  </li>
  <li>
    <b>JavaScript</b>
    <ul>
      <li>
        <b>Guidelines:</b>
        <ul>
          <li>
            Based on MDN and Google JavaScript Style Guide
          </li>
          <li>
            Variables and functions in camelCase (e.g., calculateTotal)
          </li>
          <li>
            Use of const or let (avoiding var)
          </li>
          <li>
            Use of single quotes for strings ('text')
          </li>
          <li>
            Preference for arrow functions
          </li>
        </ul>
      </li>
    </ul>
  </li>
  <div style="page-break-after: always;"></div>
  <li>
    <b>Vue.js</b>
    <ul>
      <li>
        <b>Conventions:</b>
        <ul>
          <li>
            Components in PascalCase (e.g., UserProfile.vue)
          </li>
          <li>
            Props and methods in camelCase
          </li>
          <li>
            Use of shorthand directives (@ for v-on, : for v-bind)
          </li>
          <li>
            Component organization by feature folders
          </li>
          <li>
            Lifecycle order (created(), mounted(), etc.)
          </li>
        </ul>
      </li>
    </ul>
  </li>
  <li>
    <b>C# (ASP.NET Core)</b>
    <ul>
      <li>
        <b>Microsoft Style:</b>
        <ul>
          <li>
            Classes and methods in PascalCase (e.g., UserService)
          </li>
          <li>
            Variables and parameters in camelCase
          </li>
          <li>
            Use of XML comments (/// &lt;summary&gt;)
          </li>
        </ul>
      </li>
      <li>
        <b>ASP.NET Core:</b>
        <ul>
          <li>
            Dependency Injection implementation
          </li>
          <li>
            Layered architecture (MVC)
          </li>
          <li>
            Use of ViewModels for data transfer
          </li>
        </ul>
      </li>
    </ul>
  </li>
  <li>
    <b>Gherkin (.feature)</b>
    <ul>
      <li>
        Use of Given – When – Then
      </li>
      <li>
        Clear, descriptive, non-technical language
      </li>
      <li>
        Reusable scenarios
      </li>
    </ul>
  </li>
  <li>
    <b>General Best Practices</b>
    <ul>
      <li>
        Code modularity and reuse
      </li>
      <li>
        Readable naming conventions
      </li>
      <li>
        Consistent indentation
      </li>
      <li>
        Performance optimization
      </li>
      <li>
        Security by design
      </li>
    </ul>
  </li>
</ul>

<p style="text-align: justify;">
  These conventions ensure a consistent, scalable, and maintainable codebase aligned with professional standards.
</p>

<div style="page-break-after: always;"></div>

### **5.1.4. Software Deployment Configuration**

<p style="text-align: justify;">
  The steps for deploying the components currently implemented in the Meditrack solution are detailed below, which correspond to the Landing Page and the project report.
</p>

Deployment Steps

<ul>
  <li>
    <b>Landing Page:</b>
    <ul>
      <li>
        Clone or download the repository from GitHub.
      </li>
      <li>
        Install the necessary project dependencies (if applicable).
      </li>
      <li>
        Build the project if build tools are used.
      </li>
      <li>
        Publish the static files (HTML, CSS, and JavaScript) on a web server or hosting service.
      </li>
      <li>
        Verify that the page displays correctly in the browser.
      </li>
    </ul>
  </li>
</ul>

> [**Landing Page Repository**](https://github.com/meditrack-web-app-1asi0730-2610-12263/safelab-business-website.git)

> [**Deployed Landing Page**](https://meditrack-web-app-1asi0730-2610-12263.github.io/safelab-business-website/)

<ul>
  <li>
    <b>Project Report:</b>
    <ul>
      <li>
        Access the report repository on GitHub.
      </li>
      <li>
        Update the content corresponding to each chapter of the project.
      </li>
      <li>
        Verify the HTML structure and document formatting.
      </li>
      <li>
        Upload changes to the repository through commits.
      </li>
      <li>
        Validate the correct visualization of the report in the corresponding environment or viewer.
      </li>
    </ul>
  </li>
</ul>

> [**Report Repository**](https://github.com/meditrack-web-app-1asi0730-2610-12263/safelab-report.git)

<p style="text-align: justify;">
  Currently, the project deployment is limited to the Landing Page and the report documentation. The frontend and backend applications of Meditrack have not yet been implemented or deployed at this stage, and their configuration will be addressed in future sprints.
</p>

## **5.2. Landing Page, Services &amp; Applications Implementation**
### **5.2.1. Sprint 1**

<p style="text-align: justify;">
  Sprint 1 of the Meditrack project focused on the initial organization of the project, consolidation of report documentation, task management through Trello, and the development and deployment of the Landing Page. During this sprint, the team prioritized planning, coordination, and delivery of initial evidence, leaving frontend and backend development for future iterations.
</p>

#### **5.2.1.1. Sprint Planning 1**

<p style="text-align: justify;">
  During Sprint 1 planning, the team defined the main objective as establishing the organizational and technical foundations of the Meditrack project. Tasks related to repository configuration, collaborative tools, report progress, and Landing Page implementation were prioritized.
</p>

<p style="text-align: justify;">
  In this sprint, the focus was on project organization, report progress, and Landing Page development. Tasks were distributed among SafeLab team members, assigning specific responsibilities. In this context, Reyes Menacho, Camila Asuncion was responsible for developing Chapter V.
</p>

<div style="page-break-after: always;"></div>

<table style="margin: auto; table-layout: fixed; width: 80%;">
  <tr style="background-color: #d9d9d9;">
    <td>
      <b>Sprint #</b>
    </th>
    <td style="text-align: center;">
      1
    </th>
  </tr>
  <tr>
    <td style="text-align: center;" colspan="2">
      <b>Sprint Planning Background</b>
    </td>
  </tr>
  <tr>
    <td>
      <b>Date</b>
    </td>
    <td>
      April 2026
    </td>
  </tr>
  <tr>
    <td>
      <b>Time</b>
    </td>
    <td>
      8:30 PM
    </td>
  </tr>
  <tr>
    <td>
      <b>Location</b>
    </td>
    <td>
      Via Discord
    </td>
  </tr>
  <tr>
    <td>
      <b>Prepared By</b>
    </td>
    <td>
      SafeLab Team
    </td>
  </tr>
  <tr>
    <td>
      <b>Attendees (to planning meeting)</b>
    </td>
    <td>
      Carlos Lavado, Augusto Montes, Jean Arizabal, Camila Reyes, Juan Orosco
    </td>
  </tr>
  <tr>
    <td>
      <b>Sprint 1 Review Summary</b>
    </td>
    <td style="text-align: justify;">
      This sprint focused on project organization, report development, and Landing Page implementation as the first deliverable.
    </td>
  </tr>
  <tr>
    <td>
      <b>Sprint 1 Retrospective Summary</b>
    </td>
    <td style="text-align: justify;">
      The team identified progress in organization and documentation, as well as improvement opportunities in planning the technical development of the main application.
    </td>
  </tr>
  <tr>
    <td style="text-align: center;" colspan="2">
      <b>Sprint Goal &amp; User Stories</b>
    </td>
  </tr>
  <tr>
    <td>
      <b>Sprint 1 Goal</b>
    </td>
    <td style="text-align: justify;">
      Develop and deploy a Landing Page that presents Meditrack product information, while significantly advancing the project report documentation.
    </td>
  </tr>
  <tr>
    <td>
      <b>Sprint 1 Velocity</b>
    </td>
    <td>
      7 story points
    </td>
  </tr>
  <tr>
    <td>
      <b>Sum of Story Points</b>
    </td>
    <td>
      7 Story Points
    </td>
  </tr>
</table>

#### **5.2.1.2. Aspect Leaders and Collaborators**

<table>
  <thead>
    <tr>
      <th style="text-align: center;">
        Team Member
      </th>
      <th style="text-align: center;">
        Code
      </th>
      <th style="text-align: center;">
        Aspect 1: Landing Page
      </th>
      <th style="text-align: center;">
        Aspect 2: Report
      </th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td style="text-align: center;">
        Carlos Lavado, Ever Giusephi
      </td>
      <td style="text-align: center;">
        U202224867
      </td>
      <td style="text-align: center;">
        C
      </td>
      <td style="text-align: center;">
        L
      </td>
    </tr>
    <tr>
      <td style="text-align: center;">
        Montes Maza, Augusto Sebastian
      </td>
      <td style="text-align: center;">
        U202218645
      </td>
      <td style="text-align: center;">
        C
      </td>
      <td style="text-align: center;">
        L
      </td>
    </tr>
    <tr>
      <td style="text-align: center;">
        Arizabal Condori, Jean Niels
      </td>
      <td style="text-align: center;">
        U201919096
      </td>
      <td style="text-align: center;">
        C
      </td>
      <td style="text-align: center;">
        L
      </td>
    </tr>
    <tr>
      <td style="text-align: center;">
        Reyes Menacho, Camila Asuncion
      </td>
      <td style="text-align: center;">
        U201921442
      </td>
      <td style="text-align: center;">
        L
      </td>
      <td style="text-align: center;">
        L (Chapter V)
      </td>
    </tr>
    <tr>
      <td style="text-align: center;">
        Orosco Ttamiña, Juan Carlos
      </td>
      <td style="text-align: center;">
        U202414840
      </td>
      <td style="text-align: center;">
        C
      </td>
      <td style="text-align: center;">
        L
      </td>
    </tr>
  </tbody>
</table>

<div style="page-break-after: always;"></div>

#### **5.2.1.3. Sprint Backlog 1**

<p style="text-align: justify;">
  Sprint Backlog 1 consisted of tasks related to project organization, team communication, report progress, Landing Page development, and its deployment. These tasks were organized in Trello to track their progress status.
</p>

<table style="margin: auto;">
  <thead>
    <tr>
      <th style="text-align: center;">
        User Story ID
      </th>
      <th style="text-align: center;">
        Title
      </th>
      <th style="text-align: center;">
        Task ID
      </th>
      <th style="text-align: center;">
        Task
      </th>
      <th style="text-align: center;">
        Description
      </th>
      <th style="text-align: center;">
        Assigned
      </th>
      <th style="text-align: center;">
        Status
      </th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td style="text-align: center;">
        US01
      </td>
      <td style="text-align: center;">
        Organize project
      </td>
      <td style="text-align: center;">
        UT01
      </td>
      <td style="text-align: center;">
        Configure Trello
      </td>
      <td style="text-align: justify;">
        Create lists and workflow
      </td>
      <td style="text-align: center;">
        Camila
      </td>
      <td style="text-align: center;">
        Done
      </td>
    </tr>
    <tr>
      <td style="text-align: center;">
        US02
      </td>
      <td style="text-align: center;">
        Team communication
      </td>
      <td style="text-align: center;">
        UT02
      </td>
      <td style="text-align: center;">
        Define channels
      </td>
      <td style="text-align: justify;">
        Use of Discord and WhatsApp
      </td>
      <td style="text-align: center;">
        Team
      </td>
      <td style="text-align: center;">
        Done
      </td>
    </tr>
    <tr>
      <td style="text-align: center;">
        US03
      </td>
      <td style="text-align: center;">
        Report
      </td>
      <td style="text-align: center;">
        UT03
      </td>
      <td style="text-align: center;">
        Develop Chapter I
      </td>
      <td style="text-align: justify;">
        Report writing
      </td>
      <td style="text-align: center;">
        Jean
      </td>
      <td style="text-align: center;">
        In Process
      </td>
    </tr>
    <tr>
      <td style="text-align: center;">
        US03
      </td>
      <td style="text-align: center;">
        Report
      </td>
      <td style="text-align: center;">
        UT04
      </td>
      <td style="text-align: center;">
        Develop Chapter II
      </td>
      <td style="text-align: justify;">
        Report writing
      </td>
      <td style="text-align: center;">
        Jean
      </td>
      <td style="text-align: center;">
        In Process
      </td>
    </tr>
    <tr>
      <td style="text-align: center;">
        US03
      </td>
      <td style="text-align: center;">
        Report
      </td>
      <td style="text-align: center;">
        UT05
      </td>
      <td style="text-align: center;">
        Develop Chapter III
      </td>
      <td style="text-align: justify;">
        Report writing
      </td>
      <td style="text-align: center;">
        Juan
      </td>
      <td style="text-align: center;">
        In Process
      </td>
    </tr>
    <tr>
      <td style="text-align: center;">
        US03
      </td>
      <td style="text-align: center;">
        Report
      </td>
      <td style="text-align: center;">
        UT06
      </td>
      <td style="text-align: center;">
        Develop Chapter IV
      </td>
      <td style="text-align: justify;">
        Report writing
      </td>
      <td style="text-align: center;">
        Giusephi and Sebastian
      </td>
      <td style="text-align: center;">
        In Process
      </td>
    </tr>
    <tr>
      <td style="text-align: center;">
        US04
      </td>
      <td style="text-align: center;">
        Report
      </td>
      <td style="text-align: center;">
        UT07
      </td>
      <td style="text-align: center;">
        Develop Chapter V
      </td>
      <td style="text-align: justify;">
        Configuration, deployment, and evidence
      </td>
      <td style="text-align: center;">
        Camila
      </td>
      <td style="text-align: center;">
        In Process
      </td>
    </tr>
    <tr>
      <td style="text-align: center;">
        US05
      </td>
      <td style="text-align: center;">
        Landing Page
      </td>
      <td style="text-align: center;">
        UT08
      </td>
      <td style="text-align: center;">
        Develop landing
      </td>
      <td style="text-align: justify;">
        Visual implementation of the product
      </td>
      <td style="text-align: center;">
        Team
      </td>
      <td style="text-align: center;">
        Done
      </td>
    </tr>
    <tr>
      <td style="text-align: center;">
        US06
      </td>
      <td style="text-align: center;">
        Deploy
      </td>
      <td style="text-align: center;">
        UT09
      </td>
      <td style="text-align: center;">
        Deploy landing
      </td>
      <td style="text-align: justify;">
        Web publication
      </td>
      <td style="text-align: center;">
        Giusephi
      </td>
      <td style="text-align: center;">
        Done
      </td>
    </tr>
  </tbody>
</table>

<div style="page-break-after: always;"></div>

#### **5.2.1.4. Development Evidence for Sprint Review**

<p style="text-align: justify;">
  This section presents the commits that provide evidence of the Landing Page development of the Meditrack project, including integration, content fixes, styling, and deployment.
</p>

> [**Landing Page Repository**](https://github.com/meditrack-web-app-1asi0730-2610-12263/safelab-business-website.git)

<table style="margin: auto;">
  <tr>
    <th style="text-align: center;">
      Repository
    </th>
    <th style="text-align: center;">
      Branch
    </th>
    <th style="text-align: center;">
      Commit Id
    </th>
    <th style="text-align: center;">
      Commit Message
    </th>
    <th style="text-align: center;">
      Committed on
    </th>
  </tr>
  <tr>
    <td style="text-align: center;">
      safelab-business-website
    </td>
    <td style="text-align: center;">
      main
    </td>
    <td style="text-align: center;">
      6144d89
    </td>
    <td style="text-align: justify;">
      hotfix(release): merge landing content fixes into main
    </td>
    <td style="text-align: center;">
      2026-04-23
    </td>
  </tr>
  <tr>
    <td style="text-align: center;">
      safelab-business-website
    </td>
    <td style="text-align: center;">
      main
    </td>
    <td style="text-align: center;">
      99070d
    </td>
    <td style="text-align: justify;">
      release(v1): merge develop into main with initial SafeLab landing page
    </td>
    <td style="text-align: center;">
      2026-04-23
    </td>
  </tr>
  <tr>
    <td style="text-align: center;">
      safelab-business-website
    </td>
    <td style="text-align: center;">
      develop
    </td>
    <td style="text-align: center;">
      4b6dd01
    </td>
    <td style="text-align: justify;">
      merge(safelab-landing): integrate initial landing page, styles
    </td>
    <td style="text-align: center;">
      2026-04-23
    </td>
  </tr>
    <tr>
    <td style="text-align: center;">
      safelab-business-website
    </td>
    <td style="text-align: center;">
      hotfix/landing-content
    </td>
    <td style="text-align: center;">
      190222a
    </td>
    <td style="text-align: justify;">
      fix(styles): enhance team section with updated avatar styles
    </td>
    <td style="text-align: center;">
      2026-04-24
    </td>
  </tr>
  <tr>
    <td style="text-align: center;">
      safelab-business-website
    </td>
    <td style="text-align: center;">
      hotfix/landing-content
    </td>
    <td style="text-align: center;">
      ec8e452
    </td>
    <td style="text-align: justify;">
      fix(content): update image paths and team section content
    </td>
    <td style="text-align: center;">
      2026-04-24
    </td>
  </tr>
  <tr>
    <td style="text-align: center;">
      safelab-business-website
    </td>
    <td style="text-align: center;">
      hotfix/landing-content
    </td>
    <td style="text-align: center;">
      6f44d89
    </td>
    <td style="text-align: justify;">
      fix(assets): update SafeLab branding logos and images
    </td>
    <td style="text-align: center;">
      2026-04-24
    </td>
  </tr>
  <tr>
    <td style="text-align: center;">
      safelab-business-website
    </td>
    <td style="text-align: center;">
      develop
    </td>
    <td style="text-align: center;">
      2c37fd7
    </td>
    <td style="text-align: justify;">
      chore(merge): sync develop with main
    </td>
    <td style="text-align: center;">
      2026-04-24
    </td>
  </tr>
  <tr>
    <td style="text-align: center;">
      safelab-business-website
    </td>
    <td style="text-align: center;">
      feature/i18n-language-switcher
    </td>
    <td style="text-align: center;">
      a3efc69
    </td>
    <td style="text-align: justify;">
      feat: implement language switcher feature
    </td>
    <td style="text-align: center;">
      2026-04-24
    </td>
  </tr>
</table>

<div style="page-break-after: always;"></div>

#### **5.2.1.5. Execution Evidence for Sprint Review**

<p style="text-align: justify;">
  During the sprint, the Landing Page functionalities were completed. The execution evidence is shown through access to the deployed system.
</p>

<div style="text-align: center;">
  <img src="../assets/chapter-5/implementation/sprint-1/execution-evidence/landing-page.png" width="70%" alt="meditrack-landing-page">
</div>

> [**View Landing Page**](https://meditrack-web-app-1asi0730-2610-12263.github.io/safelab-business-website/)

#### **5.2.1.6. Services Documentation Evidence for Sprint Review**

<p style="text-align: justify;">
  As defined in sprint planning, this sprint focused only on the Landing Page development and report progress.
</p>

<p style="text-align: justify;">
  No backend services or OpenAPI-documented endpoints were implemented, since the main application development is planned for future sprints.
</p>

#### **5.2.1.7. Software Deployment Evidence for Sprint Review**

<p style="text-align: justify;">
  During this sprint, the Landing Page was deployed as the first evidence of the Meditrack product. The goal was to provide an online accessible version for initial validation.
</p>

<p style="text-align: justify;">
</p>
<ul>
  <li>
    <b>Activities performed:</b>
    <ul>
      <li>
        Creation of the GitHub repository
      </li>
      <li>
        Upload of Landing Page source code
      </li>
      <li>
        Deployment environment configuration
      </li>
      <li>
        Public access verification
      </li>
    </ul>
  </li>
</ul>

> [**Deployed Landing Page**](https://meditrack-web-app-1asi0730-2610-12263.github.io/safelab-business-website/)

> [**Report repository**](https://github.com/meditrack-web-app-1asi0730-2610-12263/safelab-report.git)


<div style="text-align: center;">
  <img src="../assets/chapter-5/implementation/sprint-1/deployment-evidence/deployment.png"  width="70%" alt="deployment-evidence">
  
  <p>
    Figure X. Landing Page deployment evidence
  </p>
</div>

#### **5.2.1.8. Team Collaboration Insights during Sprint**

<p style="text-align: justify;">
  During Sprint 1, the SafeLab team worked collaboratively through task and report chapter distribution.
</p>

<p style="text-align: justify;">
  Task management was carried out using Trello, allowing visualization of progress through lists such as Backlog, Sprint Backlog, To Do, In Process, and Done.
</p>

<p style="text-align: justify;">
  Team communication was conducted via Discord for meetings and general coordination, and WhatsApp for quick communication and follow-up.
</p>

<p style="text-align: justify;">
  Reyes Menacho, Camila Asuncion was responsible for developing Chapter V, consolidating implementation, deployment, and sprint evidence documentation.
</p>

<div style="text-align: center;">
  <img src="../assets/chapter-5/implementation/sprint-1/team-collaboration-insights/trello-board.png" width="70%" alt="trello-board">

  <p>
    Figure 5.1. Trello board evidence used in Sprint 1
  </p>
</div>

> [**Trello Board**](https://trello.com/b/rTOXeOxY/trabajo-final-de-aplicaciones-web)

<div style="page-break-after: always;"></div>

## **5.3. Validation Interviews**
### **5.3.1. Interview Design**
### **5.3.2. Interview Recording**
### **5.3.3. Evaluations Based on Heuristics**
## **5.4. About-the-Product Video**

<div style="page-break-after: always;"></div>
