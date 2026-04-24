# **Chapter III: Requirements Specification**
## **3.1. User Stories**
## **3.2. Impact Mapping**
## **3.3. Product Backlog**


## **3.1 User Stories**

In this section, the system’s functional requirements are presented, defined through User Stories and grouped into Epics based on the analysis carried out in Chapter II.

#### Epics

<table>
  <tr>
    <th>Epic ID</th>
    <th>Title</th>
    <th>Description</th>
  </tr>

  <tr>
    <td>EP01</td>
    <td>Laboratory organization</td>
    <td>Manage laboratory structure including sites, storage areas and equipment to organize monitoring across locations</td>
  </tr>

  <tr>
    <td>EP02</td>
    <td>Real-time monitoring</td>
    <td>View temperature, humidity and equipment status automatically in real time without manual recording</td>
  </tr>

  <tr>
    <td>EP03</td>
    <td>Alerts and notifications</td>
    <td>Receive, view and manage alerts, including mobile notifications and team awareness of incidents</td>
  </tr>

  <tr>
    <td>EP04</td>
    <td>Reporting and data analysis</td>
    <td>Access historical data, compare periods and generate reports to analyze trends and support compliance</td>
  </tr>

  <tr>
    <td>EP05</td>
    <td>Equipment condition and maintenance</td>
    <td>Monitor equipment condition, reliability and maintenance history to prevent failures</td>
  </tr>

  <tr>
    <td>EP06</td>
    <td>Dashboard and system overview</td>
    <td>Provide a centralized view of system status, alerts and key indicators for quick decision making</td>
  </tr>

  <tr>
    <td>EP07</td>
    <td>User access and roles</td>
    <td>Allow users to securely access the system using login methods and manage roles for proper access control</td>
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

  <!-- EP01 -->
  <tr><td>US01</td><td>Register laboratory site</td><td>As a Supervisor, I want to register a site with name and location so I can organize monitoring</td><td>EP01</td></tr>
  <tr><td>US02</td><td>View laboratory sites</td><td>As a Supervisor, I want to see all registered sites so I can manage them</td><td>EP01</td></tr>
  <tr><td>US03</td><td>Create storage area</td><td>As a Supervisor, I want to create storage areas with name and type so I can organize equipment</td><td>EP01</td></tr>
  <tr><td>US04</td><td>View storage areas</td><td>As a Supervisor, I want to see storage areas so I understand organization</td><td>EP01</td></tr>
  <tr><td>US05</td><td>Register equipment</td><td>As a Supervisor, I want to register equipment with name, type and identifier so it can be monitored</td><td>EP01</td></tr>
  <tr><td>US06</td><td>View equipment list</td><td>As a Supervisor, I want to see all equipment so I can manage it easily</td><td>EP01</td></tr>
  <tr><td>US07</td><td>Assign equipment to area</td><td>As a Supervisor, I want to assign equipment to a storage area so I know its location</td><td>EP01</td></tr>
  <tr><td>US08</td><td>Search equipment by name</td><td>As a Supervisor, I want to search equipment by name so I find it quickly</td><td>EP01</td></tr>

  <!-- EP02 -->
  <tr><td>US09</td><td>View temperature values</td><td>As an Operator, I want to see temperature values so I monitor conditions</td><td>EP02</td></tr>
  <tr><td>US10</td><td>View humidity values</td><td>As an Operator, I want to see humidity values so I ensure proper storage</td><td>EP02</td></tr>
  <tr><td>US11</td><td>View equipment working status</td><td>As an Operator, I want to see if equipment is working so I detect issues</td><td>EP02</td></tr>
  <tr><td>US12</td><td>View equipment details</td><td>As an Operator, I want to open equipment details to see temperature, humidity and status</td><td>EP02</td></tr>
  <tr><td>US13</td><td>View equipment list with real-time data</td><td>As an Operator, I want to see equipment with current values so I monitor quickly</td><td>EP02</td></tr>
  <tr><td>US14</td><td>Filter equipment by storage area</td><td>As an Operator, I want to filter equipment by area so I focus on a location</td><td>EP02</td></tr>
  <tr><td>US15</td><td>Identify equipment without recent data</td><td>As an Operator, I want to detect equipment without recent data so I act quickly</td><td>EP02</td></tr>
  <tr><td>US16</td><td>Automatic data collection</td><td>As an Operator, I want data to be collected automatically so I don’t record it manually</td><td>EP02</td></tr>
  <tr><td>US17</td><td>View data on mobile</td><td>As an Operator, I want to view monitoring data on my phone so I can access it easily</td><td>EP02</td></tr>

  <!-- EP03 -->
  <tr><td>US18</td><td>Receive temperature alerts</td><td>As an Operator, I want alerts when temperature exceeds limits so I react fast</td><td>EP03</td></tr>
  <tr><td>US19</td><td>Receive humidity alerts</td><td>As an Operator, I want alerts when humidity exceeds limits so I act quickly</td><td>EP03</td></tr>
  <tr><td>US20</td><td>View alerts list</td><td>As an Operator, I want to see a list of alerts so I manage incidents</td><td>EP03</td></tr>
  <tr><td>US21</td><td>View alert details</td><td>As an Operator, I want to open an alert to see equipment, value and time</td><td>EP03</td></tr>
  <tr><td>US22</td><td>Acknowledge alert</td><td>As an Operator, I want to mark an alert as handled so I track actions</td><td>EP03</td></tr>
  <tr><td>US23</td><td>View alerts sorted by severity</td><td>As an Operator, I want to see alerts sorted by severity so I prioritize work</td><td>EP03</td></tr>
  <tr><td>US24</td><td>Receive alerts on mobile device</td><td>As an Operator, I want to receive alerts on my phone so I respond quickly</td><td>EP03</td></tr>
  <tr><td>US25</td><td>Set alert limits per equipment</td><td>As a Supervisor, I want to define limits so alerts trigger automatically</td><td>EP03</td></tr>
  <tr><td>US26</td><td>Share alerts with team</td><td>As an Operator, I want alerts to be visible to the team so we coordinate actions</td><td>EP03</td></tr>

  <!-- EP04 -->
  <tr><td>US27</td><td>View historical data</td><td>As a Supervisor, I want to see past data so I analyze trends</td><td>EP04</td></tr>
  <tr><td>US28</td><td>Select date range for data</td><td>As a Supervisor, I want to choose a date range so I filter data</td><td>EP04</td></tr>
  <tr><td>US29</td><td>Compare data between periods</td><td>As a Supervisor, I want to compare data so I detect changes</td><td>EP04</td></tr>
  <tr><td>US30</td><td>Generate report by equipment and date</td><td>As a Supervisor, I want to generate reports so I validate compliance</td><td>EP04</td></tr>
  <tr><td>US31</td><td>Download report file</td><td>As a Supervisor, I want to download reports so I share them</td><td>EP04</td></tr>
  <tr><td>US32</td><td>View incident history</td><td>As a Supervisor, I want to see past alerts so I evaluate performance</td><td>EP04</td></tr>
  <tr><td>US33</td><td>Export data file</td><td>As a Supervisor, I want to export data so I use it outside the system</td><td>EP04</td></tr>
  <tr><td>US34</td><td>Compare weekly and monthly data</td><td>As a Supervisor, I want to compare data between weeks and months so I detect variations</td><td>EP04</td></tr>

  <!-- EP05 -->
  <tr><td>US35</td><td>View equipment condition</td><td>As a Supervisor, I want to see if equipment is working correctly so I prevent failures</td><td>EP05</td></tr>
  <tr><td>US36</td><td>View abnormal values</td><td>As an Operator, I want to see values outside limits so I detect problems</td><td>EP05</td></tr>
  <tr><td>US37</td><td>Receive equipment warning alerts</td><td>As an Operator, I want to receive warnings so I prevent failures</td><td>EP05</td></tr>
  <tr><td>US38</td><td>View equipment performance data</td><td>As a Supervisor, I want to see performance over time so I improve operations</td><td>EP05</td></tr>
  <tr><td>US39</td><td>View equipment usage data</td><td>As a Supervisor, I want to see usage so I manage resources</td><td>EP05</td></tr>
  <tr><td>US40</td><td>Register maintenance record</td><td>As a Supervisor, I want to record maintenance so I track history</td><td>EP05</td></tr>
  <tr><td>US41</td><td>View maintenance history</td><td>As a Supervisor, I want to see maintenance records so I ensure reliability</td><td>EP05</td></tr>
  <tr><td>US42</td><td>View equipment reliability</td><td>As a Supervisor, I want to see stability over time so I prevent failures</td><td>EP05</td></tr>

  <!-- EP06 -->
  <tr><td>US43</td><td>View dashboard</td><td>As a Supervisor, I want to see key system information</td><td>EP06</td></tr>
  <tr><td>US44</td><td>View critical alerts</td><td>As a Supervisor, I want to see critical alerts so I act immediately</td><td>EP06</td></tr>
  <tr><td>US45</td><td>View summary with totals</td><td>As a Supervisor, I want an overview of equipment and alerts</td><td>EP06</td></tr>
  <tr><td>US46</td><td>View equipment with active alerts</td><td>As a Supervisor, I want to see equipment with issues</td><td>EP06</td></tr>
  <tr><td>US47</td><td>View equipment without recent data</td><td>As an Operator, I want to detect missing data</td><td>EP06</td></tr>
  <tr><td>US48</td><td>View alert trends</td><td>As a Supervisor, I want to analyze alert patterns</td><td>EP06</td></tr>
  <tr><td>US49</td><td>View temperature trends</td><td>As a Supervisor, I want to analyze temperature changes</td><td>EP06</td></tr>
  <tr><td>US50</td><td>View humidity trends</td><td>As a Supervisor, I want to analyze humidity changes</td><td>EP06</td></tr>

  <!-- EP07 -->
  <tr><td>US51</td><td>Login with Google account</td><td>As a user, I want to log in with Google so I access quickly</td><td>EP07</td></tr>
  <tr><td>US52</td><td>Login with email and password</td><td>As a user, I want to log in with email so I access my account</td><td>EP07</td></tr>
  <tr><td>US53</td><td>Recover password by email</td><td>As a user, I want to recover access via email</td><td>EP07</td></tr>
  <tr><td>US54</td><td>Logout from system</td><td>As a user, I want to log out to protect my account</td><td>EP07</td></tr>
  <tr><td>US55</td><td>Assign user role</td><td>As a Supervisor, I want to assign roles so users have proper access</td><td>EP07</td></tr>

</table>
---


### HU01 - Listar productos


<!-- ===================== HU01 ===================== -->
<table>
<tr>
<td><b>Number:</b></td>
<td>HU01</td>
<td><b>User:</b></td>
<td>Supervisor</td>
</tr>

<tr>
<td><b>Story Name:</b></td>
<td colspan="3">Register laboratory site</td>
</tr>

<tr>
<td><b>Business Priority:</b></td>
<td colspan="3">High</td>
</tr>

<tr>
<td><b>Developer:</b></td>
<td colspan="3">To be defined</td>
</tr>

<tr>
<td><b>Description:</b></td>
<td colspan="3">
As a Supervisor, I want to register a laboratory site with name and location so I can organize monitoring
</td>
</tr>

<tr>
<td><b>Acceptance Criteria:</b></td>
<td colspan="3">

<b>Scenario 1: Successful registration</b><br>
Given a site name and location<br>
When the user saves<br>
Then the system registers the site<br><br>

<b>Scenario 2: Missing data</b><br>
Given missing name or location<br>
When saving<br>
Then the system shows an error

</td>
</tr>
</table>

<!-- ===================== HU02 ===================== -->
<table>
<tr>
<td><b>Number:</b></td>
<td>HU02</td>
<td><b>User:</b></td>
<td>Supervisor</td>
</tr>

<tr>
<td><b>Story Name:</b></td>
<td colspan="3">View laboratory sites</td>
</tr>

<tr>
<td><b>Business Priority:</b></td>
<td colspan="3">High</td>
</tr>

<tr>
<td><b>Developer:</b></td>
<td colspan="3">To be defined</td>
</tr>

<tr>
<td><b>Description:</b></td>
<td colspan="3">
As a Supervisor, I want to view all registered sites so I can manage them
</td>
</tr>

<tr>
<td><b>Acceptance Criteria:</b></td>
<td colspan="3">

<b>Scenario 1: View list</b><br>
Given existing sites<br>
When accessing the list<br>
Then the system displays all sites<br><br>

<b>Scenario 2: Empty list</b><br>
Given no sites registered<br>
When accessing<br>
Then the system shows empty message

</td>
</tr>
</table>

<!-- ===================== HU03 ===================== -->
<table>
<tr>
<td><b>Number:</b></td>
<td>HU03</td>
<td><b>User:</b></td>
<td>Supervisor</td>
</tr>

<tr>
<td><b>Story Name:</b></td>
<td colspan="3">Create storage area</td>
</tr>

<tr>
<td><b>Business Priority:</b></td>
<td colspan="3">High</td>
</tr>

<tr>
<td><b>Developer:</b></td>
<td colspan="3">To be defined</td>
</tr>

<tr>
<td><b>Description:</b></td>
<td colspan="3">
As a Supervisor, I want to create a storage area with name and type so I can organize equipment
</td>
</tr>

<tr>
<td><b>Acceptance Criteria:</b></td>
<td colspan="3">

<b>Scenario 1: Successful creation</b><br>
Given name and type<br>
When saving<br>
Then the system creates the area<br><br>

<b>Scenario 2: Missing data</b><br>
Given missing fields<br>
When saving<br>
Then error is shown

</td>
</tr>
</table>

<!-- ===================== HU04 ===================== -->
<table>
<tr>
<td><b>Number:</b></td>
<td>HU04</td>
<td><b>User:</b></td>
<td>Supervisor</td>
</tr>

<tr>
<td><b>Story Name:</b></td>
<td colspan="3">View storage areas</td>
</tr>

<tr>
<td><b>Business Priority:</b></td>
<td colspan="3">Medium</td>
</tr>

<tr>
<td><b>Developer:</b></td>
<td colspan="3">To be defined</td>
</tr>

<tr>
<td><b>Description:</b></td>
<td colspan="3">
As a Supervisor, I want to see storage areas so I understand organization
</td>
</tr>

<tr>
<td><b>Acceptance Criteria:</b></td>
<td colspan="3">

<b>Scenario 1: Show areas</b><br>
Given areas exist<br>
When opening list<br>
Then system shows areas<br><br>

<b>Scenario 2: No areas</b><br>
Given no data<br>
When opening<br>
Then empty message appears

</td>
</tr>
</table>

<!-- ===================== HU05 ===================== -->
<table>
<tr>
<td><b>Number:</b></td>
<td>HU05</td>
<td><b>User:</b></td>
<td>Supervisor</td>
</tr>

<tr>
<td><b>Story Name:</b></td>
<td colspan="3">Register equipment</td>
</tr>

<tr>
<td><b>Business Priority:</b></td>
<td colspan="3">High</td>
</tr>

<tr>
<td><b>Developer:</b></td>
<td colspan="3">To be defined</td>
</tr>

<tr>
<td><b>Description:</b></td>
<td colspan="3">
As a Supervisor, I want to register equipment with name and type so it can be monitored
</td>
</tr>

<tr>
<td><b>Acceptance Criteria:</b></td>
<td colspan="3">

<b>Scenario 1: Register equipment</b><br>
Given valid data<br>
When saving<br>
Then equipment is created<br><br>

<b>Scenario 2: Missing data</b><br>
Given missing fields<br>
When saving<br>
Then error appears

</td>
</tr>
</table>

<!-- ===================== HU06 ===================== -->
<table>
<tr>
<td><b>Number:</b></td>
<td>HU06</td>
<td><b>User:</b></td>
<td>Supervisor</td>
</tr>

<tr>
<td><b>Story Name:</b></td>
<td colspan="3">View equipment list</td>
</tr>

<tr>
<td><b>Business Priority:</b></td>
<td colspan="3">High</td>
</tr>

<tr>
<td><b>Developer:</b></td>
<td colspan="3">To be defined</td>
</tr>

<tr>
<td><b>Description:</b></td>
<td colspan="3">
As a Supervisor, I want to see all equipment so I can manage it
</td>
</tr>

<tr>
<td><b>Acceptance Criteria:</b></td>
<td colspan="3">

<b>Scenario 1: Show list</b><br>
Given equipment exists<br>
When opening list<br>
Then system displays equipment<br><br>

<b>Scenario 2: Empty list</b><br>
Given no equipment<br>
When opening<br>
Then show empty message

</td>
</tr>
</table>

<!-- ===================== HU07 ===================== -->
<table>
<tr>
<td><b>Number:</b></td>
<td>HU07</td>
<td><b>User:</b></td>
<td>Supervisor</td>
</tr>

<tr>
<td><b>Story Name:</b></td>
<td colspan="3">Assign equipment to area</td>
</tr>

<tr>
<td><b>Business Priority:</b></td>
<td colspan="3">High</td>
</tr>

<tr>
<td><b>Developer:</b></td>
<td colspan="3">To be defined</td>
</tr>

<tr>
<td><b>Description:</b></td>
<td colspan="3">
As a Supervisor, I want to assign equipment to an area so I know its location
</td>
</tr>

<tr>
<td><b>Acceptance Criteria:</b></td>
<td colspan="3">

<b>Scenario 1: Assign equipment</b><br>
Given equipment and area<br>
When assigning<br>
Then system links them<br><br>

<b>Scenario 2: Missing selection</b><br>
Given missing data<br>
When assigning<br>
Then show error

</td>
</tr>
</table>

<!-- ===================== HU08 ===================== -->
<table>
<tr>
<td><b>Number:</b></td>
<td>HU08</td>
<td><b>User:</b></td>
<td>Supervisor</td>
</tr>

<tr>
<td><b>Story Name:</b></td>
<td colspan="3">Search equipment by name</td>
</tr>

<tr>
<td><b>Business Priority:</b></td>
<td colspan="3">Medium</td>
</tr>

<tr>
<td><b>Developer:</b></td>
<td colspan="3">To be defined</td>
</tr>

<tr>
<td><b>Description:</b></td>
<td colspan="3">
As a Supervisor, I want to search equipment by name so I find it quickly
</td>
</tr>

<tr>
<td><b>Acceptance Criteria:</b></td>
<td colspan="3">

<b>Scenario 1: Search result</b><br>
Given matching name<br>
When searching<br>
Then system shows results<br><br>

<b>Scenario 2: No result</b><br>
Given no match<br>
When searching<br>
Then show no results message

</td>
</tr>
</table>


<!-- ===================== HU09 ===================== -->
<table>
<tr>
<td><b>Number:</b></td>
<td>HU09</td>
<td><b>User:</b></td>
<td>Operator</td>
</tr>

<tr>
<td><b>Story Name:</b></td>
<td colspan="3">View temperature values</td>
</tr>

<tr>
<td><b>Business Priority:</b></td>
<td colspan="3">High</td>
</tr>

<tr>
<td><b>Developer:</b></td>
<td colspan="3">To be defined</td>
</tr>

<tr>
<td><b>Description:</b></td>
<td colspan="3">
As an Operator, I want to see temperature values so I monitor conditions
</td>
</tr>

<tr>
<td><b>Acceptance Criteria:</b></td>
<td colspan="3">

<b>Scenario 1: Show temperature</b><br>
Given equipment connected<br>
When viewing<br>
Then temperature is displayed<br><br>

<b>Scenario 2: No data</b><br>
Given no data<br>
When viewing<br>
Then system shows warning

</td>
</tr>
</table>

<!-- ===================== HU10 ===================== -->
<table>
<tr>
<td><b>Number:</b></td>
<td>HU10</td>
<td><b>User:</b></td>
<td>Operator</td>
</tr>

<tr>
<td><b>Story Name:</b></td>
<td colspan="3">View humidity values</td>
</tr>

<tr>
<td><b>Business Priority:</b></td>
<td colspan="3">High</td>
</tr>

<tr>
<td><b>Developer:</b></td>
<td colspan="3">To be defined</td>
</tr>

<tr>
<td><b>Description:</b></td>
<td colspan="3">
As an Operator, I want to see humidity values so I ensure proper storage
</td>
</tr>

<tr>
<td><b>Acceptance Criteria:</b></td>
<td colspan="3">

<b>Scenario 1: Show humidity</b><br>
Given equipment connected<br>
When viewing<br>
Then humidity is displayed<br><br>

<b>Scenario 2: No data</b><br>
Given no data<br>
When viewing<br>
Then system shows warning

</td>
</tr>
</table>

<!-- ===================== HU11 ===================== -->
<table>
<tr>
<td><b>Number:</b></td>
<td>HU11</td>
<td><b>User:</b></td>
<td>Operator</td>
</tr>

<tr>
<td><b>Story Name:</b></td>
<td colspan="3">View equipment working status</td>
</tr>

<tr>
<td><b>Business Priority:</b></td>
<td colspan="3">High</td>
</tr>

<tr>
<td><b>Developer:</b></td>
<td colspan="3">To be defined</td>
</tr>

<tr>
<td><b>Description:</b></td>
<td colspan="3">
As an Operator, I want to see if equipment is working or not so I detect issues
</td>
</tr>

<tr>
<td><b>Acceptance Criteria:</b></td>
<td colspan="3">

<b>Scenario 1: Working status</b><br>
Given equipment sending data<br>
When viewing status<br>
Then system shows "working"<br><br>

<b>Scenario 2: Not working</b><br>
Given no data received<br>
When viewing status<br>
Then system shows "not working"

</td>
</tr>
</table>

<!-- ===================== HU12 ===================== -->
<table>
<tr>
<td><b>Number:</b></td>
<td>HU12</td>
<td><b>User:</b></td>
<td>Operator</td>
</tr>

<tr>
<td><b>Story Name:</b></td>
<td colspan="3">View equipment details</td>
</tr>

<tr>
<td><b>Business Priority:</b></td>
<td colspan="3">High</td>
</tr>

<tr>
<td><b>Developer:</b></td>
<td colspan="3">To be defined</td>
</tr>

<tr>
<td><b>Description:</b></td>
<td colspan="3">
As an Operator, I want to view equipment details so I see temperature, humidity and status
</td>
</tr>

<tr>
<td><b>Acceptance Criteria:</b></td>
<td colspan="3">

<b>Scenario 1: View details</b><br>
Given existing equipment<br>
When opening details<br>
Then system shows temperature, humidity and status<br><br>

<b>Scenario 2: Equipment not found</b><br>
Given invalid selection<br>
When opening<br>
Then system shows error

</td>
</tr>
</table>

<!-- ===================== HU13 ===================== -->
<table>
<tr>
<td><b>Number:</b></td>
<td>HU13</td>
<td><b>User:</b></td>
<td>Operator</td>
</tr>

<tr>
<td><b>Story Name:</b></td>
<td colspan="3">View equipment list with real-time data</td>
</tr>

<tr>
<td><b>Business Priority:</b></td>
<td colspan="3">High</td>
</tr>

<tr>
<td><b>Developer:</b></td>
<td colspan="3">To be defined</td>
</tr>

<tr>
<td><b>Description:</b></td>
<td colspan="3">
As an Operator, I want to see equipment with current values so I monitor quickly
</td>
</tr>

<tr>
<td><b>Acceptance Criteria:</b></td>
<td colspan="3">

<b>Scenario 1: Show list with data</b><br>
Given equipment available<br>
When viewing list<br>
Then system shows temperature and humidity<br><br>

<b>Scenario 2: Missing data</b><br>
Given no data available<br>
When viewing list<br>
Then system shows warning

</td>
</tr>
</table>

<!-- ===================== HU14 ===================== -->
<table>
<tr>
<td><b>Number:</b></td>
<td>HU14</td>
<td><b>User:</b></td>
<td>Operator</td>
</tr>

<tr>
<td><b>Story Name:</b></td>
<td colspan="3">Filter equipment by storage area</td>
</tr>

<tr>
<td><b>Business Priority:</b></td>
<td colspan="3">Medium</td>
</tr>

<tr>
<td><b>Developer:</b></td>
<td colspan="3">To be defined</td>
</tr>

<tr>
<td><b>Description:</b></td>
<td colspan="3">
As an Operator, I want to filter equipment by area so I focus on a location
</td>
</tr>

<tr>
<td><b>Acceptance Criteria:</b></td>
<td colspan="3">

<b>Scenario 1: Filter results</b><br>
Given selected area<br>
When applying filter<br>
Then system shows only equipment in that area<br><br>

<b>Scenario 2: No results</b><br>
Given no equipment in area<br>
When filtering<br>
Then show empty message

</td>
</tr>
</table>

<!-- ===================== HU15 ===================== -->
<table>
<tr>
<td><b>Number:</b></td>
<td>HU15</td>
<td><b>User:</b></td>
<td>Operator</td>
</tr>

<tr>
<td><b>Story Name:</b></td>
<td colspan="3">Identify equipment without recent data</td>
</tr>

<tr>
<td><b>Business Priority:</b></td>
<td colspan="3">High</td>
</tr>

<tr>
<td><b>Developer:</b></td>
<td colspan="3">To be defined</td>
</tr>

<tr>
<td><b>Description:</b></td>
<td colspan="3">
As an Operator, I want to detect equipment without recent data so I act quickly
</td>
</tr>

<tr>
<td><b>Acceptance Criteria:</b></td>
<td colspan="3">

<b>Scenario 1: Detect no data</b><br>
Given no data received for a period<br>
When viewing equipment<br>
Then system highlights it<br><br>

<b>Scenario 2: Normal data</b><br>
Given data is available<br>
When viewing<br>
Then no warning is shown

</td>
</tr>
</table>

<!-- ===================== HU16 ===================== -->
<table>
<tr>
<td><b>Number:</b></td>
<td>HU16</td>
<td><b>User:</b></td>
<td>Operator</td>
</tr>

<tr>
<td><b>Story Name:</b></td>
<td colspan="3">Automatic data collection</td>
</tr>

<tr>
<td><b>Business Priority:</b></td>
<td colspan="3">High</td>
</tr>

<tr>
<td><b>Developer:</b></td>
<td colspan="3">To be defined</td>
</tr>

<tr>
<td><b>Description:</b></td>
<td colspan="3">
As an Operator, I want data to be collected automatically so I don’t record it manually
</td>
</tr>

<tr>
<td><b>Acceptance Criteria:</b></td>
<td colspan="3">

<b>Scenario 1: Automatic update</b><br>
Given connected equipment<br>
When system runs<br>
Then data updates automatically<br><br>

<b>Scenario 2: No connection</b><br>
Given no connection<br>
When collecting data<br>
Then system shows warning

</td>
</tr>
</table>

<!-- ===================== HU17 ===================== -->
<table>
<tr>
<td><b>Number:</b></td>
<td>HU17</td>
<td><b>User:</b></td>
<td>Operator</td>
</tr>

<tr>
<td><b>Story Name:</b></td>
<td colspan="3">View data on mobile</td>
</tr>

<tr>
<td><b>Business Priority:</b></td>
<td colspan="3">High</td>
</tr>

<tr>
<td><b>Developer:</b></td>
<td colspan="3">To be defined</td>
</tr>

<tr>
<td><b>Description:</b></td>
<td colspan="3">
As an Operator, I want to view monitoring data on my phone so I can access it easily
</td>
</tr>

<tr>
<td><b>Acceptance Criteria:</b></td>
<td colspan="3">

<b>Scenario 1: Mobile access</b><br>
Given logged in user<br>
When accessing from mobile<br>
Then system shows data correctly<br><br>

<b>Scenario 2: No access</b><br>
Given no connection<br>
When accessing<br>
Then system shows error

</td>
</tr>
</table>

<!-- ===================== HU18 ===================== -->
<table>
<tr>
<td><b>Number:</b></td>
<td>HU18</td>
<td><b>User:</b></td>
<td>Operator</td>
</tr>

<tr>
<td><b>Story Name:</b></td>
<td colspan="3">Receive temperature alerts</td>
</tr>

<tr>
<td><b>Business Priority:</b></td>
<td colspan="3">High</td>
</tr>

<tr>
<td><b>Developer:</b></td>
<td colspan="3">To be defined</td>
</tr>

<tr>
<td><b>Description:</b></td>
<td colspan="3">
As an Operator, I want alerts when temperature exceeds limits so I react fast
</td>
</tr>

<tr>
<td><b>Acceptance Criteria:</b></td>
<td colspan="3">

<b>Scenario 1: Alert triggered</b><br>
Given temperature exceeds limit<br>
When system detects it<br>
Then alert is generated<br><br>

<b>Scenario 2: Normal values</b><br>
Given temperature within limits<br>
When monitoring<br>
Then no alert is generated

</td>
</tr>
</table>

<!-- ===================== HU19 ===================== -->
<table>
<tr>
<td><b>Number:</b></td>
<td>HU19</td>
<td><b>User:</b></td>
<td>Operator</td>
</tr>

<tr>
<td><b>Story Name:</b></td>
<td colspan="3">Receive humidity alerts</td>
</tr>

<tr>
<td><b>Business Priority:</b></td>
<td colspan="3">High</td>
</tr>

<tr>
<td><b>Developer:</b></td>
<td colspan="3">To be defined</td>
</tr>

<tr>
<td><b>Description:</b></td>
<td colspan="3">
As an Operator, I want alerts when humidity exceeds limits so I act quickly
</td>
</tr>

<tr>
<td><b>Acceptance Criteria:</b></td>
<td colspan="3">

<b>Scenario 1: Alert triggered</b><br>
Given humidity exceeds limit<br>
When detected<br>
Then system generates alert<br><br>

<b>Scenario 2: Normal humidity</b><br>
Given normal values<br>
When monitoring<br>
Then no alert is generated

</td>
</tr>
</table>

<!-- ===================== HU20 ===================== -->
<table>
<tr>
<td><b>Number:</b></td>
<td>HU20</td>
<td><b>User:</b></td>
<td>Operator</td>
</tr>

<tr>
<td><b>Story Name:</b></td>
<td colspan="3">View alerts list</td>
</tr>

<tr>
<td><b>Business Priority:</b></td>
<td colspan="3">High</td>
</tr>

<tr>
<td><b>Developer:</b></td>
<td colspan="3">To be defined</td>
</tr>

<tr>
<td><b>Description:</b></td>
<td colspan="3">
As an Operator, I want to see a list of alerts so I manage incidents
</td>
</tr>

<tr>
<td><b>Acceptance Criteria:</b></td>
<td colspan="3">

<b>Scenario 1: Show alerts</b><br>
Given existing alerts<br>
When opening list<br>
Then system displays alerts<br><br>

<b>Scenario 2: No alerts</b><br>
Given no alerts<br>
When opening<br>
Then system shows empty message

</td>
</tr>
</table>

<!-- ===================== HU21 ===================== -->
<table>
<tr>
<td><b>Number:</b></td>
<td>HU21</td>
<td><b>User:</b></td>
<td>Operator</td>
</tr>

<tr>
<td><b>Story Name:</b></td>
<td colspan="3">View alert details</td>
</tr>

<tr>
<td><b>Business Priority:</b></td>
<td colspan="3">High</td>
</tr>

<tr>
<td><b>Developer:</b></td>
<td colspan="3">To be defined</td>
</tr>

<tr>
<td><b>Description:</b></td>
<td colspan="3">
As an Operator, I want to view alert details so I understand the issue
</td>
</tr>

<tr>
<td><b>Acceptance Criteria:</b></td>
<td colspan="3">

<b>Scenario 1: Show details</b><br>
Given an alert selected<br>
When opening it<br>
Then system shows equipment, value and time<br><br>

<b>Scenario 2: Invalid alert</b><br>
Given alert does not exist<br>
When opening<br>
Then system shows error

</td>
</tr>
</table>

<!-- ===================== HU22 ===================== -->
<table>
<tr>
<td><b>Number:</b></td>
<td>HU22</td>
<td><b>User:</b></td>
<td>Operator</td>
</tr>

<tr>
<td><b>Story Name:</b></td>
<td colspan="3">Acknowledge alert</td>
</tr>

<tr>
<td><b>Business Priority:</b></td>
<td colspan="3">High</td>
</tr>

<tr>
<td><b>Developer:</b></td>
<td colspan="3">To be defined</td>
</tr>

<tr>
<td><b>Description:</b></td>
<td colspan="3">
As an Operator, I want to mark an alert as handled so I track actions
</td>
</tr>

<tr>
<td><b>Acceptance Criteria:</b></td>
<td colspan="3">

<b>Scenario 1: Mark as handled</b><br>
Given an active alert<br>
When marking as handled<br>
Then system updates status<br><br>

<b>Scenario 2: Already handled</b><br>
Given alert already handled<br>
When updating<br>
Then system keeps status

</td>
</tr>
</table>

<!-- ===================== HU23 ===================== -->
<table>
<tr>
<td><b>Number:</b></td>
<td>HU23</td>
<td><b>User:</b></td>
<td>Operator</td>
</tr>

<tr>
<td><b>Story Name:</b></td>
<td colspan="3">View alerts sorted by severity</td>
</tr>

<tr>
<td><b>Business Priority:</b></td>
<td colspan="3">Medium</td>
</tr>

<tr>
<td><b>Developer:</b></td>
<td colspan="3">To be defined</td>
</tr>

<tr>
<td><b>Description:</b></td>
<td colspan="3">
As an Operator, I want to see alerts sorted by severity so I prioritize work
</td>
</tr>

<tr>
<td><b>Acceptance Criteria:</b></td>
<td colspan="3">

<b>Scenario 1: Sorted alerts</b><br>
Given multiple alerts<br>
When viewing list<br>
Then system orders by severity<br><br>

<b>Scenario 2: Same severity</b><br>
Given equal severity<br>
When viewing<br>
Then system keeps default order

</td>
</tr>
</table>

<!-- ===================== HU24 ===================== -->
<table>
<tr>
<td><b>Number:</b></td>
<td>HU24</td>
<td><b>User:</b></td>
<td>Operator</td>
</tr>

<tr>
<td><b>Story Name:</b></td>
<td colspan="3">Receive alerts on mobile device</td>
</tr>

<tr>
<td><b>Business Priority:</b></td>
<td colspan="3">High</td>
</tr>

<tr>
<td><b>Developer:</b></td>
<td colspan="3">To be defined</td>
</tr>

<tr>
<td><b>Description:</b></td>
<td colspan="3">
As an Operator, I want to receive alerts on my phone so I respond quickly
</td>
</tr>

<tr>
<td><b>Acceptance Criteria:</b></td>
<td colspan="3">

<b>Scenario 1: Alert notification</b><br>
Given alert triggered<br>
When system detects it<br>
Then notification is sent<br><br>

<b>Scenario 2: No connection</b><br>
Given no network<br>
When sending alert<br>
Then system retries later

</td>
</tr>
</table>

<!-- ===================== HU25 ===================== -->
<table>
<tr>
<td><b>Number:</b></td>
<td>HU25</td>
<td><b>User:</b></td>
<td>Supervisor</td>
</tr>

<tr>
<td><b>Story Name:</b></td>
<td colspan="3">Set alert limits per equipment</td>
</tr>

<tr>
<td><b>Business Priority:</b></td>
<td colspan="3">High</td>
</tr>

<tr>
<td><b>Developer:</b></td>
<td colspan="3">To be defined</td>
</tr>

<tr>
<td><b>Description:</b></td>
<td colspan="3">
As a Supervisor, I want to define temperature and humidity limits so alerts trigger automatically
</td>
</tr>

<tr>
<td><b>Acceptance Criteria:</b></td>
<td colspan="3">

<b>Scenario 1: Save limits</b><br>
Given valid limits<br>
When saving<br>
Then system stores values<br><br>

<b>Scenario 2: Invalid limits</b><br>
Given incorrect values<br>
When saving<br>
Then system shows error

</td>
</tr>
</table>

<!-- ===================== HU25 ===================== -->
<table>
<tr>
<td><b>Number:</b></td>
<td>HU25</td>
<td><b>User:</b></td>
<td>Supervisor</td>
</tr>

<tr>
<td><b>Story Name:</b></td>
<td colspan="3">Set alert limits per equipment</td>
</tr>

<tr>
<td><b>Business Priority:</b></td>
<td colspan="3">High</td>
</tr>

<tr>
<td><b>Developer:</b></td>
<td colspan="3">To be defined</td>
</tr>

<tr>
<td><b>Description:</b></td>
<td colspan="3">
As a Supervisor, I want to define temperature and humidity limits so alerts trigger automatically
</td>
</tr>

<tr>
<td><b>Acceptance Criteria:</b></td>
<td colspan="3">

<b>Scenario 1: Save limits</b><br>
Given valid limits<br>
When saving<br>
Then system stores values<br><br>

<b>Scenario 2: Invalid limits</b><br>
Given incorrect values<br>
When saving<br>
Then system shows error

</td>
</tr>
</table>

<!-- ===================== HU27 ===================== -->
<table>
<tr>
<td><b>Number:</b></td>
<td>HU27</td>
<td><b>User:</b></td>
<td>Supervisor</td>
</tr>

<tr>
<td><b>Story Name:</b></td>
<td colspan="3">View historical data</td>
</tr>

<tr>
<td><b>Business Priority:</b></td>
<td colspan="3">High</td>
</tr>

<tr>
<td><b>Developer:</b></td>
<td colspan="3">To be defined</td>
</tr>

<tr>
<td><b>Description:</b></td>
<td colspan="3">
As a Supervisor, I want to view historical data so I analyze trends
</td>
</tr>

<tr>
<td><b>Acceptance Criteria:</b></td>
<td colspan="3">

<b>Scenario 1: Show history</b><br>
Given stored data<br>
When selecting equipment<br>
Then system displays history<br><br>

<b>Scenario 2: No history</b><br>
Given no data<br>
When viewing<br>
Then system shows empty message

</td>
</tr>
</table>

<!-- ===================== HU28 ===================== -->
<table>
<tr>
<td><b>Number:</b></td>
<td>HU28</td>
<td><b>User:</b></td>
<td>Supervisor</td>
</tr>

<tr>
<td><b>Story Name:</b></td>
<td colspan="3">Select date range for data</td>
</tr>

<tr>
<td><b>Business Priority:</b></td>
<td colspan="3">Medium</td>
</tr>

<tr>
<td><b>Developer:</b></td>
<td colspan="3">To be defined</td>
</tr>

<tr>
<td><b>Description:</b></td>
<td colspan="3">
As a Supervisor, I want to select a date range so I filter data
</td>
</tr>

<tr>
<td><b>Acceptance Criteria:</b></td>
<td colspan="3">

<b>Scenario 1: Apply filter</b><br>
Given selected dates<br>
When applying filter<br>
Then system shows filtered data<br><br>

<b>Scenario 2: Invalid range</b><br>
Given wrong dates<br>
When applying<br>
Then system shows error

</td>
</tr>
</table>

<!-- ===================== HU29 ===================== -->
<table>
<tr>
<td><b>Number:</b></td>
<td>HU29</td>
<td><b>User:</b></td>
<td>Supervisor</td>
</tr>

<tr>
<td><b>Story Name:</b></td>
<td colspan="3">Compare data between periods</td>
</tr>

<tr>
<td><b>Business Priority:</b></td>
<td colspan="3">Medium</td>
</tr>

<tr>
<td><b>Developer:</b></td>
<td colspan="3">To be defined</td>
</tr>

<tr>
<td><b>Description:</b></td>
<td colspan="3">
As a Supervisor, I want to compare data between periods so I detect changes
</td>
</tr>

<tr>
<td><b>Acceptance Criteria:</b></td>
<td colspan="3">

<b>Scenario 1: Compare data</b><br>
Given two periods selected<br>
When comparing<br>
Then system shows both results<br><br>

<b>Scenario 2: Missing selection</b><br>
Given incomplete data<br>
When comparing<br>
Then system shows error

</td>
</tr>
</table>

<!-- ===================== HU30 ===================== -->
<table>
<tr>
<td><b>Number:</b></td>
<td>HU30</td>
<td><b>User:</b></td>
<td>Supervisor</td>
</tr>

<tr>
<td><b>Story Name:</b></td>
<td colspan="3">Generate report by equipment and date</td>
</tr>

<tr>
<td><b>Business Priority:</b></td>
<td colspan="3">High</td>
</tr>

<tr>
<td><b>Developer:</b></td>
<td colspan="3">To be defined</td>
</tr>

<tr>
<td><b>Description:</b></td>
<td colspan="3">
As a Supervisor, I want to generate reports so I validate compliance
</td>
</tr>

<tr>
<td><b>Acceptance Criteria:</b></td>
<td colspan="3">

<b>Scenario 1: Generate report</b><br>
Given selected equipment and date<br>
When generating<br>
Then system creates report<br><br>

<b>Scenario 2: Missing data</b><br>
Given incomplete fields<br>
When generating<br>
Then system shows error

</td>
</tr>
</table>

<!-- ===================== HU31 ===================== -->
<table>
<tr>
<td><b>Number:</b></td>
<td>HU31</td>
<td><b>User:</b></td>
<td>Supervisor</td>
</tr>

<tr>
<td><b>Story Name:</b></td>
<td colspan="3">Download report file</td>
</tr>

<tr>
<td><b>Business Priority:</b></td>
<td colspan="3">High</td>
</tr>

<tr>
<td><b>Developer:</b></td>
<td colspan="3">To be defined</td>
</tr>

<tr>
<td><b>Description:</b></td>
<td colspan="3">
As a Supervisor, I want to download generated reports so I can share them
</td>
</tr>

<tr>
<td><b>Acceptance Criteria:</b></td>
<td colspan="3">

<b>Scenario 1: Download report</b><br>
Given a generated report<br>
When downloading<br>
Then file is saved locally<br><br>

<b>Scenario 2: No report</b><br>
Given no report generated<br>
When downloading<br>
Then system shows error

</td>
</tr>
</table>

<!-- ===================== HU32 ===================== -->
<table>
<tr>
<td><b>Number:</b></td>
<td>HU32</td>
<td><b>User:</b></td>
<td>Supervisor</td>
</tr>

<tr>
<td><b>Story Name:</b></td>
<td colspan="3">View incident history</td>
</tr>

<tr>
<td><b>Business Priority:</b></td>
<td colspan="3">High</td>
</tr>

<tr>
<td><b>Developer:</b></td>
<td colspan="3">To be defined</td>
</tr>

<tr>
<td><b>Description:</b></td>
<td colspan="3">
As a Supervisor, I want to view past alerts so I evaluate performance
</td>
</tr>

<tr>
<td><b>Acceptance Criteria:</b></td>
<td colspan="3">

<b>Scenario 1: Show incidents</b><br>
Given stored alerts<br>
When viewing history<br>
Then system displays alerts<br><br>

<b>Scenario 2: No incidents</b><br>
Given no alerts<br>
When viewing<br>
Then system shows empty message

</td>
</tr>
</table>

<!-- ===================== HU33 ===================== -->
<table>
<tr>
<td><b>Number:</b></td>
<td>HU33</td>
<td><b>User:</b></td>
<td>Supervisor</td>
</tr>

<tr>
<td><b>Story Name:</b></td>
<td colspan="3">Export data file</td>
</tr>

<tr>
<td><b>Business Priority:</b></td>
<td colspan="3">Medium</td>
</tr>

<tr>
<td><b>Developer:</b></td>
<td colspan="3">To be defined</td>
</tr>

<tr>
<td><b>Description:</b></td>
<td colspan="3">
As a Supervisor, I want to export data so I can use it outside the system
</td>
</tr>

<tr>
<td><b>Acceptance Criteria:</b></td>
<td colspan="3">

<b>Scenario 1: Export data</b><br>
Given available data<br>
When exporting<br>
Then file is generated<br><br>

<b>Scenario 2: No data</b><br>
Given empty data<br>
When exporting<br>
Then system shows error

</td>
</tr>
</table>

<!-- ===================== HU34 ===================== -->
<table>
<tr>
<td><b>Number:</b></td>
<td>HU34</td>
<td><b>User:</b></td>
<td>Supervisor</td>
</tr>

<tr>
<td><b>Story Name:</b></td>
<td colspan="3">Compare weekly and monthly data</td>
</tr>

<tr>
<td><b>Business Priority:</b></td>
<td colspan="3">Medium</td>
</tr>

<tr>
<td><b>Developer:</b></td>
<td colspan="3">To be defined</td>
</tr>

<tr>
<td><b>Description:</b></td>
<td colspan="3">
As a Supervisor, I want to compare weekly and monthly data so I detect variations
</td>
</tr>

<tr>
<td><b>Acceptance Criteria:</b></td>
<td colspan="3">

<b>Scenario 1: Compare data</b><br>
Given selected week and month<br>
When comparing<br>
Then system shows both values<br><br>

<b>Scenario 2: Missing selection</b><br>
Given incomplete selection<br>
When comparing<br>
Then system shows error

</td>
</tr>
</table>

<!-- ===================== HU35 ===================== -->
<table>
<tr>
<td><b>Number:</b></td>
<td>HU35</td>
<td><b>User:</b></td>
<td>Supervisor</td>
</tr>

<tr>
<td><b>Story Name:</b></td>
<td colspan="3">View equipment condition</td>
</tr>

<tr>
<td><b>Business Priority:</b></td>
<td colspan="3">High</td>
</tr>

<tr>
<td><b>Developer:</b></td>
<td colspan="3">To be defined</td>
</tr>

<tr>
<td><b>Description:</b></td>
<td colspan="3">
As a Supervisor, I want to see if equipment is working correctly so I prevent failures
</td>
</tr>

<tr>
<td><b>Acceptance Criteria:</b></td>
<td colspan="3">

<b>Scenario 1: Working condition</b><br>
Given equipment functioning<br>
When viewing<br>
Then system shows normal status<br><br>

<b>Scenario 2: Issue detected</b><br>
Given abnormal condition<br>
When viewing<br>
Then system shows warning

</td>
</tr>
</table>

<!-- ===================== HU36 ===================== -->
<table>
<tr>
<td><b>Number:</b></td>
<td>HU36</td>
<td><b>User:</b></td>
<td>Operator</td>
</tr>

<tr>
<td><b>Story Name:</b></td>
<td colspan="3">View abnormal values</td>
</tr>

<tr>
<td><b>Business Priority:</b></td>
<td colspan="3">High</td>
</tr>

<tr>
<td><b>Developer:</b></td>
<td colspan="3">To be defined</td>
</tr>

<tr>
<td><b>Description:</b></td>
<td colspan="3">
As an Operator, I want to see values outside limits so I detect problems
</td>
</tr>

<tr>
<td><b>Acceptance Criteria:</b></td>
<td colspan="3">

<b>Scenario 1: Abnormal detected</b><br>
Given values exceed limits<br>
When viewing<br>
Then system highlights them<br><br>

<b>Scenario 2: Normal values</b><br>
Given normal values<br>
When viewing<br>
Then no warning appears

</td>
</tr>
</table>

<!-- ===================== HU37 ===================== -->
<table>
<tr>
<td><b>Number:</b></td>
<td>HU37</td>
<td><b>User:</b></td>
<td>Operator</td>
</tr>

<tr>
<td><b>Story Name:</b></td>
<td colspan="3">Receive equipment warning alerts</td>
</tr>

<tr>
<td><b>Business Priority:</b></td>
<td colspan="3">High</td>
</tr>

<tr>
<td><b>Developer:</b></td>
<td colspan="3">To be defined</td>
</tr>

<tr>
<td><b>Description:</b></td>
<td colspan="3">
As an Operator, I want to receive warnings so I prevent failures
</td>
</tr>

<tr>
<td><b>Acceptance Criteria:</b></td>
<td colspan="3">

<b>Scenario 1: Warning triggered</b><br>
Given abnormal condition<br>
When detected<br>
Then system sends warning<br><br>

<b>Scenario 2: Normal operation</b><br>
Given normal values<br>
When monitoring<br>
Then no warning is sent

</td>
</tr>
</table>

<!-- ===================== HU38 ===================== -->
<table>
<tr>
<td><b>Number:</b></td>
<td>HU38</td>
<td><b>User:</b></td>
<td>Supervisor</td>
</tr>

<tr>
<td><b>Story Name:</b></td>
<td colspan="3">View equipment performance data</td>
</tr>

<tr>
<td><b>Business Priority:</b></td>
<td colspan="3">Medium</td>
</tr>

<tr>
<td><b>Developer:</b></td>
<td colspan="3">To be defined</td>
</tr>

<tr>
<td><b>Description:</b></td>
<td colspan="3">
As a Supervisor, I want to see performance over time so I improve operations
</td>
</tr>

<tr>
<td><b>Acceptance Criteria:</b></td>
<td colspan="3">

<b>Scenario 1: Show performance</b><br>
Given stored data<br>
When viewing<br>
Then system displays performance trend<br><br>

<b>Scenario 2: No data</b><br>
Given no data<br>
When viewing<br>
Then system shows empty message

</td>
</tr>
</table>

<!-- ===================== HU39 ===================== -->
<table>
<tr>
<td><b>Number:</b></td>
<td>HU39</td>
<td><b>User:</b></td>
<td>Supervisor</td>
</tr>

<tr>
<td><b>Story Name:</b></td>
<td colspan="3">View equipment usage data</td>
</tr>

<tr>
<td><b>Business Priority:</b></td>
<td colspan="3">Medium</td>
</tr>

<tr>
<td><b>Developer:</b></td>
<td colspan="3">To be defined</td>
</tr>

<tr>
<td><b>Description:</b></td>
<td colspan="3">
As a Supervisor, I want to see usage data so I manage resources
</td>
</tr>

<tr>
<td><b>Acceptance Criteria:</b></td>
<td colspan="3">

<b>Scenario 1: Show usage</b><br>
Given usage data exists<br>
When viewing<br>
Then system displays usage<br><br>

<b>Scenario 2: No data</b><br>
Given no usage data<br>
When viewing<br>
Then system shows empty message

</td>
</tr>
</table>

<!-- ===================== HU40 ===================== -->
<table>
<tr>
<td><b>Number:</b></td>
<td>HU40</td>
<td><b>User:</b></td>
<td>Supervisor</td>
</tr>

<tr>
<td><b>Story Name:</b></td>
<td colspan="3">Register maintenance record</td>
</tr>

<tr>
<td><b>Business Priority:</b></td>
<td colspan="3">High</td>
</tr>

<tr>
<td><b>Developer:</b></td>
<td colspan="3">To be defined</td>
</tr>

<tr>
<td><b>Description:</b></td>
<td colspan="3">
As a Supervisor, I want to record maintenance so I track equipment history
</td>
</tr>

<tr>
<td><b>Acceptance Criteria:</b></td>
<td colspan="3">

<b>Scenario 1: Save record</b><br>
Given maintenance data<br>
When saving<br>
Then system stores record<br><br>

<b>Scenario 2: Missing data</b><br>
Given incomplete data<br>
When saving<br>
Then system shows error

</td>
</tr>
</table>

<!-- ===================== HU41 ===================== -->
<table>
<tr><td><b>Number:</b></td><td>HU41</td><td><b>User:</b></td><td>Supervisor</td></tr>
<tr><td><b>Story Name:</b></td><td colspan="3">View maintenance history</td></tr>
<tr><td><b>Business Priority:</b></td><td colspan="3">High</td></tr>
<tr><td><b>Developer:</b></td><td colspan="3">To be defined</td></tr>
<tr><td><b>Description:</b></td><td colspan="3">As a Supervisor, I want to view maintenance records so I ensure reliability</td></tr>
<tr><td><b>Acceptance Criteria:</b></td><td colspan="3">

<b>Scenario 1: Show history</b><br>
Given maintenance records exist<br>
When viewing history<br>
Then system displays records<br><br>

<b>Scenario 2: No records</b><br>
Given no records<br>
When viewing<br>
Then system shows empty message

</td></tr>
</table>

<!-- ===================== HU42 ===================== -->
<table>
<tr><td><b>Number:</b></td><td>HU42</td><td><b>User:</b></td><td>Supervisor</td></tr>
<tr><td><b>Story Name:</b></td><td colspan="3">View equipment reliability</td></tr>
<tr><td><b>Business Priority:</b></td><td colspan="3">High</td></tr>
<tr><td><b>Developer:</b></td><td colspan="3">To be defined</td></tr>
<tr><td><b>Description:</b></td><td colspan="3">As a Supervisor, I want to see equipment stability over time so I prevent failures</td></tr>
<tr><td><b>Acceptance Criteria:</b></td><td colspan="3">

<b>Scenario 1: Show reliability</b><br>
Given historical data exists<br>
When viewing<br>
Then system shows stability trend<br><br>

<b>Scenario 2: No data</b><br>
Given no data<br>
When viewing<br>
Then system shows empty message

</td></tr>
</table>

<!-- ===================== HU43 ===================== -->
<table>
<tr><td><b>Number:</b></td><td>HU43</td><td><b>User:</b></td><td>Supervisor</td></tr>
<tr><td><b>Story Name:</b></td><td colspan="3">View dashboard</td></tr>
<tr><td><b>Business Priority:</b></td><td colspan="3">High</td></tr>
<tr><td><b>Developer:</b></td><td colspan="3">To be defined</td></tr>
<tr><td><b>Description:</b></td><td colspan="3">As a Supervisor, I want to see key system information so I understand system status</td></tr>
<tr><td><b>Acceptance Criteria:</b></td><td colspan="3">

<b>Scenario 1: Show dashboard</b><br>
Given system data available<br>
When accessing dashboard<br>
Then system displays key metrics<br><br>

<b>Scenario 2: No data</b><br>
Given no data<br>
When accessing<br>
Then system shows empty state

</td></tr>
</table>

<!-- ===================== HU44 ===================== -->
<table>
<tr><td><b>Number:</b></td><td>HU44</td><td><b>User:</b></td><td>Supervisor</td></tr>
<tr><td><b>Story Name:</b></td><td colspan="3">View critical alerts</td></tr>
<tr><td><b>Business Priority:</b></td><td colspan="3">High</td></tr>
<tr><td><b>Developer:</b></td><td colspan="3">To be defined</td></tr>
<tr><td><b>Description:</b></td><td colspan="3">As a Supervisor, I want to see critical alerts so I act immediately</td></tr>
<tr><td><b>Acceptance Criteria:</b></td><td colspan="3">

<b>Scenario 1: Show critical alerts</b><br>
Given alerts exist<br>
When filtering by critical<br>
Then system shows critical alerts<br><br>

<b>Scenario 2: No critical alerts</b><br>
Given none exist<br>
When viewing<br>
Then system shows empty message

</td></tr>
</table>

<!-- ===================== HU44 ===================== -->
<table>
<tr><td><b>Number:</b></td><td>HU44</td><td><b>User:</b></td><td>Supervisor</td></tr>
<tr><td><b>Story Name:</b></td><td colspan="3">View critical alerts</td></tr>
<tr><td><b>Business Priority:</b></td><td colspan="3">High</td></tr>
<tr><td><b>Developer:</b></td><td colspan="3">To be defined</td></tr>
<tr><td><b>Description:</b></td><td colspan="3">As a Supervisor, I want to see critical alerts so I act immediately</td></tr>
<tr><td><b>Acceptance Criteria:</b></td><td colspan="3">

<b>Scenario 1: Show critical alerts</b><br>
Given alerts exist<br>
When filtering by critical<br>
Then system shows critical alerts<br><br>

<b>Scenario 2: No critical alerts</b><br>
Given none exist<br>
When viewing<br>
Then system shows empty message

</td></tr>
</table>

<!-- ===================== HU46 ===================== -->
<table>
<tr><td><b>Number:</b></td><td>HU46</td><td><b>User:</b></td><td>Supervisor</td></tr>
<tr><td><b>Story Name:</b></td><td colspan="3">View equipment with active alerts</td></tr>
<tr><td><b>Business Priority:</b></td><td colspan="3">High</td></tr>
<tr><td><b>Developer:</b></td><td colspan="3">To be defined</td></tr>
<tr><td><b>Description:</b></td><td colspan="3">As a Supervisor, I want to see equipment with active alerts so I focus on issues</td></tr>
<tr><td><b>Acceptance Criteria:</b></td><td colspan="3">

<b>Scenario 1: Show affected equipment</b><br>
Given alerts exist<br>
When filtering<br>
Then system shows affected equipment<br><br>

<b>Scenario 2: No alerts</b><br>
Given none exist<br>
When filtering<br>
Then system shows empty message

</td></tr>
</table>

<!-- ===================== HU47 ===================== -->
<table>
<tr><td><b>Number:</b></td><td>HU47</td><td><b>User:</b></td><td>Operator</td></tr>
<tr><td><b>Story Name:</b></td><td colspan="3">View equipment without recent data</td></tr>
<tr><td><b>Business Priority:</b></td><td colspan="3">High</td></tr>
<tr><td><b>Developer:</b></td><td colspan="3">To be defined</td></tr>
<tr><td><b>Description:</b></td><td colspan="3">As an Operator, I want to identify equipment without recent data so I act quickly</td></tr>
<tr><td><b>Acceptance Criteria:</b></td><td colspan="3">

<b>Scenario 1: Show missing data</b><br>
Given no recent data<br>
When viewing<br>
Then system highlights equipment<br><br>

<b>Scenario 2: Normal data</b><br>
Given data exists<br>
When viewing<br>
Then no warning is shown

</td></tr>
</table>

<!-- ===================== HU48 ===================== -->
<table>
<tr><td><b>Number:</b></td><td>HU48</td><td><b>User:</b></td><td>Supervisor</td></tr>
<tr><td><b>Story Name:</b></td><td colspan="3">View alert trends</td></tr>
<tr><td><b>Business Priority:</b></td><td colspan="3">Medium</td></tr>
<tr><td><b>Developer:</b></td><td colspan="3">To be defined</td></tr>
<tr><td><b>Description:</b></td><td colspan="3">As a Supervisor, I want to see alert trends so I improve processes</td></tr>
<tr><td><b>Acceptance Criteria:</b></td><td colspan="3">

<b>Scenario 1: Show trends</b><br>
Given alert history<br>
When viewing<br>
Then system shows trend data<br><br>

<b>Scenario 2: No data</b><br>
Given no alerts<br>
When viewing<br>
Then system shows empty message

</td></tr>
</table>

<!-- ===================== HU49 ===================== -->
<table>
<tr><td><b>Number:</b></td><td>HU49</td><td><b>User:</b></td><td>Supervisor</td></tr>
<tr><td><b>Story Name:</b></td><td colspan="3">View temperature trends</td></tr>
<tr><td><b>Business Priority:</b></td><td colspan="3">Medium</td></tr>
<tr><td><b>Developer:</b></td><td colspan="3">To be defined</td></tr>
<tr><td><b>Description:</b></td><td colspan="3">As a Supervisor, I want to see temperature trends so I detect risks</td></tr>
<tr><td><b>Acceptance Criteria:</b></td><td colspan="3">

<b>Scenario 1: Show temperature trends</b><br>
Given historical data<br>
When viewing<br>
Then system shows trend<br><br>

<b>Scenario 2: No data</b><br>
Given no data<br>
When viewing<br>
Then system shows empty message

</td></tr>
</table>

<!-- ===================== HU50 ===================== -->
<table>
<tr><td><b>Number:</b></td><td>HU50</td><td><b>User:</b></td><td>Supervisor</td></tr>
<tr><td><b>Story Name:</b></td><td colspan="3">View humidity trends</td></tr>
<tr><td><b>Business Priority:</b></td><td colspan="3">Medium</td></tr>
<tr><td><b>Developer:</b></td><td colspan="3">To be defined</td></tr>
<tr><td><b>Description:</b></td><td colspan="3">As a Supervisor, I want to see humidity trends so I maintain conditions</td></tr>
<tr><td><b>Acceptance Criteria:</b></td><td colspan="3">

<b>Scenario 1: Show humidity trends</b><br>
Given historical data<br>
When viewing<br>
Then system shows trend<br><br>

<b>Scenario 2: No data</b><br>
Given no data<br>
When viewing<br>
Then system shows empty message

</td></tr>
</table>

<!-- ===================== HU51 ===================== -->
<table>
<tr><td><b>Number:</b></td><td>HU51</td><td><b>User:</b></td><td>User</td></tr>
<tr><td><b>Story Name:</b></td><td colspan="3">Login with Google account</td></tr>
<tr><td><b>Business Priority:</b></td><td colspan="3">High</td></tr>
<tr><td><b>Developer:</b></td><td colspan="3">To be defined</td></tr>
<tr><td><b>Description:</b></td><td colspan="3">As a user, I want to log in using my Google account so I access quickly</td></tr>
<tr><td><b>Acceptance Criteria:</b></td><td colspan="3">

<b>Scenario 1: Successful login</b><br>
Given valid Google account<br>
When logging in<br>
Then access is granted<br><br>

<b>Scenario 2: Failed login</b><br>
Given invalid credentials<br>
When logging in<br>
Then system shows error

</td></tr>
</table>

<!-- ===================== HU52 ===================== -->
<table>
<tr><td><b>Number:</b></td><td>HU52</td><td><b>User:</b></td><td>User</td></tr>
<tr><td><b>Story Name:</b></td><td colspan="3">Login with email and password</td></tr>
<tr><td><b>Business Priority:</b></td><td colspan="3">High</td></tr>
<tr><td><b>Developer:</b></td><td colspan="3">To be defined</td></tr>
<tr><td><b>Description:</b></td><td colspan="3">As a user, I want to log in using my email so I access my account</td></tr>
<tr><td><b>Acceptance Criteria:</b></td><td colspan="3">

<b>Scenario 1: Successful login</b><br>
Given valid credentials<br>
When logging in<br>
Then access is granted<br><br>

<b>Scenario 2: Invalid credentials</b><br>
Given incorrect data<br>
When logging in<br>
Then system shows error

</td></tr>
</table>

<!-- ===================== HU53 ===================== -->
<table>
<tr><td><b>Number:</b></td><td>HU53</td><td><b>User:</b></td><td>User</td></tr>
<tr><td><b>Story Name:</b></td><td colspan="3">Recover password by email</td></tr>
<tr><td><b>Business Priority:</b></td><td colspan="3">Medium</td></tr>
<tr><td><b>Developer:</b></td><td colspan="3">To be defined</td></tr>
<tr><td><b>Description:</b></td><td colspan="3">As a user, I want to recover access via email</td></tr>
<tr><td><b>Acceptance Criteria:</b></td><td colspan="3">

<b>Scenario 1: Send reset link</b><br>
Given valid email<br>
When requesting reset<br>
Then system sends email<br><br>

<b>Scenario 2: Invalid email</b><br>
Given unregistered email<br>
When requesting<br>
Then system shows error

</td></tr>
</table>

<!-- ===================== HU54 ===================== -->
<table>
<tr><td><b>Number:</b></td><td>HU54</td><td><b>User:</b></td><td>User</td></tr>
<tr><td><b>Story Name:</b></td><td colspan="3">Logout from system</td></tr>
<tr><td><b>Business Priority:</b></td><td colspan="3">High</td></tr>
<tr><td><b>Developer:</b></td><td colspan="3">To be defined</td></tr>
<tr><td><b>Description:</b></td><td colspan="3">As a user, I want to log out to protect my account</td></tr>
<tr><td><b>Acceptance Criteria:</b></td><td colspan="3">

<b>Scenario 1: Logout</b><br>
Given user logged in<br>
When logging out<br>
Then session ends<br><br>

<b>Scenario 2: Session expired</b><br>
Given inactive session<br>
When accessing<br>
Then system redirects to login

</td></tr>
</table>

<!-- ===================== HU55 ===================== -->
<table>
<tr><td><b>Number:</b></td><td>HU55</td><td><b>User:</b></td><td>Supervisor</td></tr>
<tr><td><b>Story Name:</b></td><td colspan="3">Assign user role</td></tr>
<tr><td><b>Business Priority:</b></td><td colspan="3">High</td></tr>
<tr><td><b>Developer:</b></td><td colspan="3">To be defined</td></tr>
<tr><td><b>Description:</b></td><td colspan="3">As a Supervisor, I want to assign roles so users have proper access</td></tr>
<tr><td><b>Acceptance Criteria:</b></td><td colspan="3">

<b>Scenario 1: Assign role</b><br>
Given a user exists<br>
When assigning role<br>
Then system updates role<br><br>

<b>Scenario 2: Invalid user</b><br>
Given user not found<br>
When assigning<br>
Then system shows error

</td></tr>
</table>



## **3.2. Impact Mapping**

The Impact Mapping has been created using the Miro tool. You can access the board at the following link:

https://miro.com/app/board/uXjVGhw33Ew=/?share_link_id=265067473734


The following impact maps show how the system connects the main goal with the needs of both Supervisor and Operator users. They help explain how each feature and user story contributes to solving real problems, improving monitoring, and allowing faster response in the laboratory.

Operator:

<img src="../assets/chapter-3/impact-mapping/impact-mapping-operator.jpg" alt="Impact Mapping Operator" width="800">

Supervisor:

<img src="../assets/chapter-3/impact-mapping/impact-mapping-supervisor.jpg" alt="Impact Mapping Operator" width="800">





## **3.3. Product Backlog**

Product Backlog for the Meditrack system is shown below, where user stories are prioritized based on user needs and value, and estimated using the Fibonacci scale.

<table>
<thead>
<tr>
<th># Orden</th>
<th>User Story ID</th>
<th>Título</th>
<th>Descripción</th>
<th>Story Points</th>
</tr>
</thead>
<tbody>

<tr><td>1</td><td>US51</td><td>Login with Google</td><td>As a user, I want to log in using Google so I access quickly</td><td>3</td></tr>
<tr><td>2</td><td>US01</td><td>Register site</td><td>As a Supervisor, I want to register a site to organize monitoring</td><td>3</td></tr>
<tr><td>3</td><td>US03</td><td>Create storage area</td><td>As a Supervisor, I want to create areas to organize equipment</td><td>3</td></tr>
<tr><td>4</td><td>US05</td><td>Register equipment</td><td>As a Supervisor, I want to register equipment to monitor it</td><td>5</td></tr>
<tr><td>5</td><td>US07</td><td>Assign equipment</td><td>As a Supervisor, I want to assign equipment to areas</td><td>3</td></tr>

<tr><td>6</td><td>US16</td><td>Automatic data collection</td><td>As an Operator, I want automatic data so I don’t record manually</td><td>8</td></tr>
<tr><td>7</td><td>US09</td><td>View temperature</td><td>As an Operator, I want to monitor temperature</td><td>3</td></tr>
<tr><td>8</td><td>US10</td><td>View humidity</td><td>As an Operator, I want to monitor humidity</td><td>3</td></tr>
<tr><td>9</td><td>US11</td><td>View equipment status</td><td>As an Operator, I want to detect equipment issues</td><td>3</td></tr>

<tr><td>10</td><td>US18</td><td>Temperature alerts</td><td>As an Operator, I want alerts for temperature issues</td><td>5</td></tr>
<tr><td>11</td><td>US19</td><td>Humidity alerts</td><td>As an Operator, I want alerts for humidity issues</td><td>5</td></tr>
<tr><td>12</td><td>US20</td><td>View alerts</td><td>As an Operator, I want to see alerts list</td><td>3</td></tr>
<tr><td>13</td><td>US22</td><td>Acknowledge alert</td><td>As an Operator, I want to mark alerts as handled</td><td>2</td></tr>

<tr><td>14</td><td>US24</td><td>Mobile alerts</td><td>As an Operator, I want alerts on my phone</td><td>5</td></tr>
<tr><td>15</td><td>US17</td><td>View data on mobile</td><td>As an Operator, I want to access data on mobile</td><td>5</td></tr>

<tr><td>16</td><td>US43</td><td>View dashboard</td><td>As a Supervisor, I want to see system overview</td><td>5</td></tr>
<tr><td>17</td><td>US44</td><td>View critical alerts</td><td>As a Supervisor, I want to prioritize issues</td><td>3</td></tr>
<tr><td>18</td><td>US45</td><td>View summary</td><td>As a Supervisor, I want quick overview</td><td>3</td></tr>

<tr><td>19</td><td>US27</td><td>View historical data</td><td>As a Supervisor, I want to analyze past data</td><td>5</td></tr>
<tr><td>20</td><td>US30</td><td>Generate report</td><td>As a Supervisor, I want reports for compliance</td><td>5</td></tr>
<tr><td>21</td><td>US31</td><td>Download report</td><td>As a Supervisor, I want to download reports</td><td>3</td></tr>

<tr><td>22</td><td>US35</td><td>View equipment condition</td><td>As a Supervisor, I want to prevent failures</td><td>3</td></tr>
<tr><td>23</td><td>US42</td><td>Equipment reliability</td><td>As a Supervisor, I want to evaluate stability</td><td>5</td></tr>

<tr><td>24</td><td>US26</td><td>Share alerts</td><td>As an Operator, I want team coordination</td><td>3</td></tr>

<tr><td>25</td><td>US25</td><td>Set alert limits</td><td>As a Supervisor, I want to configure thresholds</td><td>5</td></tr>

<tr><td>26</td><td>US02</td><td>View sites</td><td>As a Supervisor, I want to manage sites</td><td>2</td></tr>
<tr><td>27</td><td>US04</td><td>View areas</td><td>As a Supervisor, I want to manage areas</td><td>2</td></tr>
<tr><td>28</td><td>US06</td><td>View equipment</td><td>As a Supervisor, I want to manage equipment</td><td>3</td></tr>

<tr><td>29</td><td>US13</td><td>Equipment list with data</td><td>As an Operator, I want quick monitoring</td><td>3</td></tr>
<tr><td>30</td><td>US12</td><td>Equipment details</td><td>As an Operator, I want full info</td><td>2</td></tr>

<tr><td>31</td><td>US14</td><td>Filter equipment</td><td>As an Operator, I want focused view</td><td>2</td></tr>
<tr><td>32</td><td>US08</td><td>Search equipment</td><td>As a Supervisor, I want quick search</td><td>2</td></tr>

<tr><td>33</td><td>US15</td><td>No data detection</td><td>As an Operator, I want to detect missing data</td><td>3</td></tr>

<tr><td>34</td><td>US21</td><td>Alert details</td><td>As an Operator, I want full alert info</td><td>2</td></tr>
<tr><td>35</td><td>US23</td><td>Sort alerts</td><td>As an Operator, I want prioritization</td><td>2</td></tr>

<tr><td>36</td><td>US28</td><td>Select date range</td><td>As a Supervisor, I want filtered data</td><td>2</td></tr>
<tr><td>37</td><td>US29</td><td>Compare data</td><td>As a Supervisor, I want analysis</td><td>3</td></tr>

<tr><td>38</td><td>US32</td><td>View incidents</td><td>As a Supervisor, I want to evaluate alerts</td><td>3</td></tr>
<tr><td>39</td><td>US33</td><td>Export data</td><td>As a Supervisor, I want external usage</td><td>3</td></tr>

<tr><td>40</td><td>US34</td><td>Compare weekly/monthly</td><td>As a Supervisor, I want deeper analysis</td><td>3</td></tr>

<tr><td>41</td><td>US36</td><td>Abnormal values</td><td>As an Operator, I want to detect issues</td><td>3</td></tr>
<tr><td>42</td><td>US37</td><td>Equipment warnings</td><td>As an Operator, I want early alerts</td><td>3</td></tr>

<tr><td>43</td><td>US38</td><td>Performance data</td><td>As a Supervisor, I want optimization</td><td>3</td></tr>
<tr><td>44</td><td>US39</td><td>Usage data</td><td>As a Supervisor, I want resource control</td><td>3</td></tr>

<tr><td>45</td><td>US40</td><td>Register maintenance</td><td>As a Supervisor, I want tracking</td><td>3</td></tr>
<tr><td>46</td><td>US41</td><td>Maintenance history</td><td>As a Supervisor, I want reliability</td><td>3</td></tr>

<tr><td>47</td><td>US46</td><td>Equipment with alerts</td><td>As a Supervisor, I want focus</td><td>2</td></tr>
<tr><td>48</td><td>US47</td><td>No data equipment</td><td>As an Operator, I want detection</td><td>2</td></tr>

<tr><td>49</td><td>US48</td><td>Alert trends</td><td>As a Supervisor, I want analysis</td><td>3</td></tr>
<tr><td>50</td><td>US49</td><td>Temperature trends</td><td>As a Supervisor, I want insights</td><td>3</td></tr>
<tr><td>51</td><td>US50</td><td>Humidity trends</td><td>As a Supervisor, I want insights</td><td>3</td></tr>

<tr><td>52</td><td>US52</td><td>Login email</td><td>As a user, I want to log in with email</td><td>3</td></tr>
<tr><td>53</td><td>US53</td><td>Recover password</td><td>As a user, I want to recover access</td><td>3</td></tr>
<tr><td>54</td><td>US54</td><td>Logout</td><td>As a user, I want to log out</td><td>1</td></tr>
<tr><td>55</td><td>US55</td><td>Assign role</td><td>As a Supervisor, I want role control</td><td>3</td></tr>

</tbody>
</table>