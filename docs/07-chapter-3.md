# **Chapter III: Requirements Specification**
## **3.1. User Stories**
## **3.2. Impact Mapping**
## **3.3. Product Backlog**

### Enlace al Impact Map

El Impact Mapping ha sido elaborado utilizando la herramienta Miro. Puede acceder al tablero en el siguiente enlace:

https://miro.com/app/board/uXjVGhw33Ew=/?share_link_id=417296329604



## **3.1 User Stories**



En esta sección se presentan los requisitos funcionales del sistema Meditrack definidos mediante User Stories y agrupados en Epics a partir del análisis realizado en el Capítulo II.

#### Epics

<table>
  <tr>
    <th>Epic ID</th>
    <th>Title</th>
    <th>Description</th>
  </tr>

  <tr>
    <td>EP01</td>
    <td>Laboratory Organization</td>
    <td>Structure sites, areas, and equipment to locate and manage resources.</td>
  </tr>

  <tr>
    <td>EP02</td>
    <td>Inventory Management</td>
    <td>Register products and control quantities and expiration dates.</td>
  </tr>

  <tr>
    <td>EP03</td>
    <td>Condition Monitoring</td>
    <td>Monitor temperature and environmental variables in real time.</td>
  </tr>

  <tr>
    <td>EP04</td>
    <td>Alerts and Tracking</td>
    <td>Notify issues and track actions taken.</td>
  </tr>

  <tr>
    <td>EP05</td>
    <td>History and Compliance</td>
    <td>Record activities and generate reports for audits.</td>
  </tr>

  <tr>
    <td>EP06</td>
    <td>Dashboard</td>
    <td>Provide an overview of laboratory status and key indicators.</td>
  </tr>

  <tr>
    <td>EP07</td>
    <td>User Access</td>
    <td>Secure login and account recovery.</td>
  </tr>

  <tr>
    <td>EP08</td>
    <td>User Management</td>
    <td>Manage users and permissions within the system.</td>
  </tr>

  <tr>
    <td>EP09</td>
    <td>System Configuration</td>
    <td>Adjust parameters such as ranges, rules, and data types.</td>
  </tr>

  <tr>
    <td>EP10</td>
    <td>Support and Maintenance</td>
    <td>Handle system errors and ensure operational continuity.</td>
  </tr>
</table>


---

#### User Stories

<table>
  <tr>
    <th>ID</th>
    <th>Title</th>
    <th>Description</th>
    <th>Epic</th>
  </tr>

  <tr>
    <td>US01</td>
    <td>Register laboratory site</td>
    <td>As a lab manager, I want to register a site so I can organize monitoring across locations</td>
    <td>EP01</td>
  </tr>

  <tr>
    <td>US02</td>
    <td>Create storage room</td>
    <td>As a lab manager, I want to create rooms so I can organize where samples and vaccines are stored</td>
    <td>EP01</td>
  </tr>

  <tr>
    <td>US03</td>
    <td>Register storage equipment</td>
    <td>As a lab manager, I want to register refrigerators and freezers so I can monitor where critical materials are stored</td>
    <td>EP01</td>
  </tr>

  <tr>
    <td>US04</td>
    <td>Assign equipment to room</td>
    <td>As a lab manager, I want to assign equipment to rooms so I always know their exact location</td>
    <td>EP01</td>
  </tr>

  <tr>
    <td>US05</td>
    <td>Find equipment quickly</td>
    <td>As a lab technician, I want to quickly find equipment so I can react faster during issues</td>
    <td>EP01</td>
  </tr>

  <tr>
    <td>US06</td>
    <td>Register product</td>
    <td>As a lab technician, I want to register products so I can track samples, vaccines, and reactives</td>
    <td>EP02</td>
  </tr>

  <tr>
    <td>US07</td>
    <td>Register batch with expiration</td>
    <td>As a lab technician, I want to add expiration dates so I can avoid using expired materials</td>
    <td>EP02</td>
  </tr>

  <tr>
    <td>US08</td>
    <td>View inventory levels</td>
    <td>As a lab manager, I want to see stock levels so I can avoid shortages or waste</td>
    <td>EP02</td>
  </tr>

  <tr>
    <td>US09</td>
    <td>Register incoming products</td>
    <td>As a lab technician, I want to register incoming items so inventory stays accurate</td>
    <td>EP02</td>
  </tr>

  <tr>
    <td>US10</td>
    <td>Register product usage</td>
    <td>As a lab technician, I want to register product usage so inventory reflects real consumption</td>
    <td>EP02</td>
  </tr>

  <tr>
    <td>US11</td>
    <td>View products close to expiration</td>
    <td>As a lab manager, I want to see products close to expiration so I can prevent losses</td>
    <td>EP02</td>
  </tr>

  <tr>
    <td>US12</td>
    <td>View equipment temperature</td>
    <td>As a lab technician, I want to see current temperature so I can ensure proper storage conditions</td>
    <td>EP03</td>
  </tr>

  <tr>
    <td>US13</td>
    <td>View temperature history</td>
    <td>As a lab manager, I want to review temperature history so I can confirm stability over time</td>
    <td>EP03</td>
  </tr>

  <tr>
    <td>US14</td>
    <td>Check monitoring status</td>
    <td>As a lab technician, I want to know if equipment is being monitored so I can trust the data</td>
    <td>EP03</td>
  </tr>

  <tr>
    <td>US15</td>
    <td>Detect abnormal conditions</td>
    <td>As a lab technician, I want to detect abnormal conditions so I can act before samples are damaged</td>
    <td>EP03</td>
  </tr>

  <tr>
    <td>US16</td>
    <td>View temperature trends</td>
    <td>As a lab manager, I want to see temperature trends so I can understand equipment behavior</td>
    <td>EP03</td>
  </tr>

  <tr>
    <td>US17</td>
    <td>Detect monitoring loss</td>
    <td>As a lab technician, I want to know when a device stops sending data so I can avoid blind spots</td>
    <td>EP03</td>
  </tr>

  <tr>
    <td>US18</td>
    <td>Receive temperature alerts</td>
    <td>As a lab technician, I want to receive alerts so I can react quickly to temperature issues</td>
    <td>EP04</td>
  </tr>

  <tr>
    <td>US19</td>
    <td>Receive email notifications</td>
    <td>As a lab manager, I want to receive alerts by email so I can stay informed even when offline</td>
    <td>EP04</td>
  </tr>

  <tr>
    <td>US20</td>
    <td>View active alerts</td>
    <td>As a lab technician, I want to see active alerts so I can prioritize actions</td>
    <td>EP04</td>
  </tr>

</table>

<table>
  <tr>
    <th>ID</th>
    <th>Title</th>
    <th>Description</th>
    <th>Epic</th>
  </tr>

  <tr>
    <td>US21</td>
    <td>Mark alert as handled</td>
    <td>As a lab technician, I want to mark alerts as handled so I can track resolved issues</td>
    <td>EP04</td>
  </tr>

  <tr>
    <td>US22</td>
    <td>Add notes to alerts</td>
    <td>As a lab technician, I want to add notes to alerts so I can document what happened</td>
    <td>EP04</td>
  </tr>

  <tr>
    <td>US23</td>
    <td>View alert history</td>
    <td>As a lab manager, I want to review past alerts so I can analyze incidents</td>
    <td>EP04</td>
  </tr>

  <tr>
    <td>US24</td>
    <td>Get alerts for monitoring failure</td>
    <td>As a lab technician, I want to be alerted when monitoring stops so I can avoid missing risks</td>
    <td>EP04</td>
  </tr>

  <tr>
    <td>US25</td>
    <td>View condition history</td>
    <td>As a lab manager, I want to see historical conditions so I can support audits</td>
    <td>EP05</td>
  </tr>

  <tr>
    <td>US26</td>
    <td>Track user actions</td>
    <td>As a lab manager, I want to see who made changes so I can maintain accountability</td>
    <td>EP05</td>
  </tr>

  <tr>
    <td>US27</td>
    <td>Generate reports</td>
    <td>As a lab manager, I want to generate reports so I can review operations and compliance</td>
    <td>EP05</td>
  </tr>

  <tr>
    <td>US28</td>
    <td>Download reports</td>
    <td>As a lab manager, I want to download reports so I can share them easily</td>
    <td>EP05</td>
  </tr>

  <tr>
    <td>US29</td>
    <td>Ensure data integrity</td>
    <td>As a lab manager, I want to trust that data cannot be altered so audits are reliable</td>
    <td>EP05</td>
  </tr>

  <tr>
    <td>US30</td>
    <td>View dashboard overview</td>
    <td>As a lab manager, I want to see a full overview so I understand the current situation quickly</td>
    <td>EP06</td>
  </tr>

  <tr>
    <td>US31</td>
    <td>Identify critical equipment</td>
    <td>As a lab technician, I want to see which equipment has issues so I can act fast</td>
    <td>EP06</td>
  </tr>

  <tr>
    <td>US32</td>
    <td>See alerts in dashboard</td>
    <td>As a lab technician, I want to see alerts in one place so I don’t miss anything</td>
    <td>EP06</td>
  </tr>

  <tr>
    <td>US33</td>
    <td>View key metrics</td>
    <td>As a lab manager, I want to see key indicators so I can make quick decisions</td>
    <td>EP06</td>
  </tr>

  <tr>
    <td>US34</td>
    <td>Detect unmonitored equipment</td>
    <td>As a lab technician, I want to identify equipment with no data so I can fix issues</td>
    <td>EP06</td>
  </tr>

  <tr>
    <td>US35</td>
    <td>Login to system</td>
    <td>As a user, I want to log in so I can access the platform securely</td>
    <td>EP07</td>
  </tr>

  <tr>
    <td>US36</td>
    <td>Recover password</td>
    <td>As a user, I want to recover my password so I can regain access</td>
    <td>EP07</td>
  </tr>

  <tr>
    <td>US37</td>
    <td>Logout from system</td>
    <td>As a user, I want to log out so I can protect my account</td>
    <td>EP07</td>
  </tr>

  <tr>
    <td>US38</td>
    <td>Receive recovery email</td>
    <td>As a user, I want to receive an email to reset my password so I can log back in</td>
    <td>EP07</td>
  </tr>

  <tr>
    <td>US39</td>
    <td>Create user account</td>
    <td>As an admin, I want to create users so the team can access the system</td>
    <td>EP08</td>
  </tr>

  <tr>
    <td>US40</td>
    <td>Assign user roles</td>
    <td>As an admin, I want to assign roles so I can control permissions</td>
    <td>EP08</td>
  </tr>

  <tr>
    <td>US41</td>
    <td>Edit user information</td>
    <td>As an admin, I want to update user data so information stays accurate</td>
    <td>EP08</td>
  </tr>

  <tr>
    <td>US42</td>
    <td>Deactivate users</td>
    <td>As an admin, I want to deactivate users so I can restrict access when needed</td>
    <td>EP08</td>
  </tr>

  <tr>
    <td>US43</td>
    <td>Set temperature conditions</td>
    <td>As a lab manager, I want to define safe temperature ranges so samples are protected</td>
    <td>EP09</td>
  </tr>

  <tr>
    <td>US44</td>
    <td>Define abnormal conditions</td>
    <td>As a lab manager, I want to define what is considered abnormal so alerts are meaningful</td>
    <td>EP09</td>
  </tr>

  <tr>
    <td>US45</td>
    <td>Apply rules by product</td>
    <td>As a lab manager, I want to apply different conditions depending on the product so storage is accurate</td>
    <td>EP09</td>
  </tr>

  <tr>
    <td>US46</td>
    <td>Configure alert recipients</td>
    <td>As a lab manager, I want to choose who receives alerts so response is faster</td>
    <td>EP09</td>
  </tr>

  <tr>
    <td>US47</td>
    <td>Search equipment</td>
    <td>As a lab technician, I want to search equipment so I can find it quickly</td>
    <td>EP09</td>
  </tr>

  <tr>
    <td>US48</td>
    <td>Filter equipment</td>
    <td>As a lab manager, I want to filter equipment by location so I can analyze specific areas</td>
    <td>EP09</td>
  </tr>

  <tr>
    <td>US49</td>
    <td>Filter alerts</td>
    <td>As a lab technician, I want to filter alerts so I can focus on what matters</td>
    <td>EP09</td>
  </tr>

  <tr>
    <td>US50</td>
    <td>Confirm normal conditions</td>
    <td>As a lab manager, I want to quickly confirm everything is normal so I can have peace of mind</td>
    <td>EP09</td>
  </tr>

</table>


---


### HU01 - Listar productos

<table>
<tr>
<td><b>Número:</b></td>
<td>HU01</td>
<td><b>Usuario:</b></td>
<td>Administrador</td>
</tr>

<tr>
<td><b>Nombre HU:</b></td>
<td colspan="3">Listar productos</td>
</tr>

<tr>
<td><b>Prioridad en el negocio:</b></td>
<td colspan="3">Alta</td>
</tr>

<tr>
<td><b>Programador responsable:</b></td>
<td colspan="3">Por definir</td>
</tr>

<tr>
<td><b>Descripción:</b></td>
<td colspan="3">
Como administrador, quiero listar los productos médicos para tener control del inventario
</td>
</tr>

<tr>
<td><b>Criterios de aceptación:</b></td>
<td colspan="3">

<b>Escenario 1: Visualización de productos registrados</b><br>
Dado que el administrador ha registrado uno o más productos<br>
Cuando accede a la sección de inventario<br>
Entonces el sistema muestra el listado de productos registrados<br><br>

<b>Escenario 2: Lista vacía</b><br>
Dado que no existen productos registrados<br>
Cuando accede al inventario<br>
Entonces el sistema muestra un mensaje indicando que no hay productos<br><br>

<b>Escenario 3: Acceso al detalle del producto</b><br>
Dado que existen productos registrados<br>
Cuando selecciona un producto<br>
Entonces el sistema muestra el detalle del producto

</td>
</tr>
</table>

<table> <tr> <td><b>Número:</b></td> <td>HU01</td> <td><b>Usuario:</b></td> <td>Administrador</td> </tr> <tr> <td><b>Nombre HU:</b></td> <td colspan="3">Registrar sede</td> </tr> <tr> <td><b>Prioridad en el negocio:</b></td> <td colspan="3">Alta</td> </tr> <tr> <td><b>Programador responsable:</b></td> <td colspan="3">Por definir</td> </tr> <tr> <td><b>Descripción:</b></td> <td colspan="3"> Como administrador, quiero registrar una sede del laboratorio para organizar las operaciones por ubicación </td> </tr> <tr> <td><b>Criterios de aceptación:</b></td> <td colspan="3">

<b>Escenario 1: Registro exitoso</b><br>
Dado datos válidos de una sede<br>
Cuando el administrador guarda<br>
Entonces el sistema registra la sede correctamente<br><br>

<b>Escenario 2: Datos incompletos</b><br>
Dado que faltan datos obligatorios<br>
Cuando intenta guardar<br>
Entonces el sistema muestra un mensaje de error<br><br>

<b>Escenario 3: Visualización</b><br>
Dado una sede registrada<br>
Cuando accede al listado<br>
Entonces la sede aparece en el sistema

</td> </tr> </table>

<table> <tr> <td><b>Número:</b></td> <td>HU02</td> <td><b>Usuario:</b></td> <td>Administrador</td> </tr> <tr> <td><b>Nombre HU:</b></td> <td colspan="3">Crear sala</td> </tr> <tr> <td><b>Prioridad en el negocio:</b></td> <td colspan="3">Alta</td> </tr> <tr> <td><b>Programador responsable:</b></td> <td colspan="3">Por definir</td> </tr> <tr> <td><b>Descripción:</b></td> <td colspan="3"> Como administrador, quiero crear salas dentro de una sede para ubicar los equipos de almacenamiento </td> </tr> <tr> <td><b>Criterios de aceptación:</b></td> <td colspan="3">

<b>Escenario 1: Creación exitosa</b><br>
Dado una sede existente<br>
Cuando crea la sala<br>
Entonces el sistema la registra correctamente<br><br>

<b>Escenario 2: Error de validación</b><br>
Dado datos incompletos<br>
Cuando guarda<br>
Entonces muestra error<br><br>

<b>Escenario 3: Visualización</b><br>
Dado salas registradas<br>
Cuando consulta<br>
Entonces se muestran en la sede

</td> </tr> </table>

<table> <tr> <td><b>Número:</b></td> <td>HU03</td> <td><b>Usuario:</b></td> <td>Administrador</td> </tr> <tr> <td><b>Nombre HU:</b></td> <td colspan="3">Registrar equipo de almacenamiento</td> </tr> <tr> <td><b>Prioridad en el negocio:</b></td> <td colspan="3">Alta</td> </tr> <tr> <td><b>Programador responsable:</b></td> <td colspan="3">Por definir</td> </tr> <tr> <td><b>Descripción:</b></td> <td colspan="3"> Como administrador, quiero registrar equipos de almacenamiento para gestionar dónde se conservan los productos </td> </tr> <tr> <td><b>Criterios de aceptación:</b></td> <td colspan="3">

<b>Escenario 1: Registro correcto</b><br>
Dado datos válidos<br>
Cuando guarda<br>
Entonces el equipo se registra<br><br>

<b>Escenario 2: Datos inválidos</b><br>
Dado información incompleta<br>
Cuando guarda<br>
Entonces muestra error<br><br>

<b>Escenario 3: Visualización</b><br>
Dado equipos registrados<br>
Cuando consulta<br>
Entonces se muestran en la lista

</td> </tr> </table>

<table> <tr> <td><b>Número:</b></td> <td>HU04</td> <td><b>Usuario:</b></td> <td>Administrador</td> </tr> <tr> <td><b>Nombre HU:</b></td> <td colspan="3">Asignar equipo a sala</td> </tr> <tr> <td><b>Prioridad en el negocio:</b></td> <td colspan="3">Alta</td> </tr> <tr> <td><b>Programador responsable:</b></td> <td colspan="3">Por definir</td> </tr> <tr> <td><b>Descripción:</b></td> <td colspan="3"> Como administrador, quiero asignar un equipo a una sala para conocer su ubicación exacta </td> </tr> <tr> <td><b>Criterios de aceptación:</b></td> <td colspan="3">

<b>Escenario 1: Asignación exitosa</b><br>
Dado equipo y sala existentes<br>
Cuando asigna<br>
Entonces queda vinculado<br><br>

<b>Escenario 2: Error de asignación</b><br>
Dado datos incorrectos<br>
Cuando asigna<br>
Entonces muestra error<br><br>

<b>Escenario 3: Visualización</b><br>
Dado equipo asignado<br>
Cuando consulta<br>
Entonces muestra su ubicación

</td> </tr> </table>


### 3.3 Product Backlog

Product Backlog para el sistema Meditrack...

<table>
    <thead>
        <tr>
            <th># Orden</th>
            <th>User Story ID</th>
            <th>Título</th>
            <th>Descripción</th>
            <th>Story Points (1/2/3/5/8)</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>1</td>
            <td>US01</td>
            <td>Registrar producto</td>
            <td>Como administrador, quiero registrar productos médicos para gestionar el inventario.</td>
            <td>3</td>
        </tr>
        <tr>
            <td>2</td>
            <td>US02</td>
            <td>Visualizar inventario</td>
            <td>Como administrador, quiero ver el listado de productos para tener control del stock disponible.</td>
            <td>3</td>
        </tr>
        <tr>
            <td>3</td>
            <td>US06</td>
            <td>Alertar stock bajo</td>
            <td>Como administrador, quiero recibir alertas de stock bajo para evitar desabastecimiento.</td>
            <td>5</td>
        </tr>
        <tr>
            <td>4</td>
            <td>US07</td>
            <td>Alertar productos por vencer</td>
            <td>Como administrador, quiero recibir alertas de productos próximos a vencer para evitar pérdidas.</td>
            <td>5</td>
        </tr>
        <tr>
            <td>5</td>
            <td>US08</td>
            <td>Visualizar dashboard</td>
            <td>Como administrador, quiero ver indicadores del inventario para tomar decisiones informadas.</td>
            <td>8</td>
        </tr>
    </tbody>
</table>
