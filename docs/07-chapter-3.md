# **Chapter III: Requirements Specification**
## **3.1 User Stories**

<p style="text-align: justify;">
  In this section, the system’s functional requirements are presented, defined through User Stories and grouped into Epics based on the analysis carried out in Chapter II.
</p>

<table style="margin: auto;">
  <thead>
    <tr>
      <th style="text-align: center;" colspan="3">
        EPICS
      </th>
    </tr>
    <tr>
      <th style="text-align: center;">
        ID
      </th>
      <th style="text-align: center;">
        Title
      </th>
      <th style="text-align: center;">
        Description
      </th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td style="text-align: center;">
        EP01
      </td>
      <td style="text-align: center;">
        Laboratory organization
      </td>
      <td style="text-align: justify;">
        Manage laboratory structure including sites, storage areas and  equipment to organize monitoring across locations
      </td>
    </tr>
    <tr>
      <td style="text-align: center;">
        EP02
      </td>
      <td style="text-align: center;">
        Real-time monitoring
      </td>
      <td style="text-align: justify;">
        View temperature, humidity and equipment status automatically in  real time without manual recording
      </td>
    </tr>
    <tr>
      <td style="text-align: center;">
        EP03
      </td>
      <td style="text-align: center;">
        Alerts and notifications
      </td>
      <td style="text-align: justify;">
        Receive, view and manage alerts, including mobile notifications   and team awareness of incidents
      </td>
    </tr>
    <tr>
      <td style="text-align: center;">
        EP04
      </td>
      <td style="text-align: center;">
        Reporting and data analysis
      </td>
      <td style="text-align: justify;">
        Access historical data, compare periods and generate reports to   analyze trends and support compliance
      </td>
    </tr>
    <tr>
      <td style="text-align: center;">
        EP05
      </td>
      <td style="text-align: center;">
        Equipment condition and maintenance
      </td>
      <td style="text-align: justify;">
        Monitor equipment condition, reliability and maintenance history  to prevent failures
      </td>
    </tr>
    <tr>
      <td style="text-align: center;">
        EP06
      </td>
      <td style="text-align: center;">
        Dashboard and system overview
      </td>
      <td style="text-align: justify;">
        Provide a centralized view of system status, alerts and key   indicators for quick decision making
      </td>
    </tr>
    <tr>
      <td style="text-align: center;">
        EP07
      </td>
      <td style="text-align: center;">
        User access and roles
      </td>
      <td style="text-align: justify;">
        Allow users to securely access the system using login methods and   manage roles for proper access control
      </td>
    </tr>
  </tbody>
</table>

<div style="page-break-after: always;"></div>

<table style="margin: auto;">
  <thead>
    <tr>
      <th style="text-align: center;" colspan="4">
        USER STORIES
      </th>
    </tr>
    <tr>
      <th style="text-align: center;">
        ID
      </th>
      <th style="text-align: center;">
        Title
      </th>
      <th style="text-align: center;">
        Description
      </th>
      <th style="text-align: center;">
        Epic
      </th>
    </tr>
  </thead>
  <tbody>
    <!-- EP01 -->
    <tr>
      <td style="text-align: center;">
        US01
      </td>
      <td style="text-align: center;">
        Register laboratory site
      </td>
      <td style="text-align: justify;">
        As a Supervisor, I want to register a site with name and location so I can organize monitoring
      </td>
      <td style="text-align: center;">
        EP01
      </td>
    </tr>
    <tr>
      <td style="text-align: center;">
        US02
      </td>
      <td style="text-align: center;">
        View laboratory sites
      </td>
      <td style="text-align: justify;">
        As a Supervisor, I want to see all registered sites so I can manage them
      </td>
      <td style="text-align: center;">
        EP01
      </td>
    </tr>
    <tr>
      <td style="text-align: center;">
        US03
      </td>
      <td style="text-align: center;">
        Create storage area
      </td>
      <td style="text-align: justify;">
        As a Supervisor, I want to create storage areas with name and type so I can organize equipment
      </td>
      <td style="text-align: center;">
        EP01
      </td>
    </tr>
    <tr>
      <td style="text-align: center;">
        US04
      </td>
      <td style="text-align: center;">
        View storage areas
      </td>
      <td style="text-align: justify;">
        As a Supervisor, I want to see storage areas so I understand organization
      </td>
      <td style="text-align: center;">
        EP01
      </td>
    </tr>
    <tr>
      <td style="text-align: center;">
        US05
      </td>
      <td style="text-align: center;">
        Register equipment
      </td>
      <td style="text-align: justify;">
        As a Supervisor, I want to register equipment with name, type and identifier so it can be monitored
      </td>
      <td style="text-align: center;">
        EP01
      </td>
    </tr>
    <tr>
      <td style="text-align: center;">
        US06
      </td>
      <td style="text-align: center;">
        View equipment list
      </td>
      <td style="text-align: justify;">
        As a Supervisor, I want to see all equipment so I can manage it easily
      </td>
      <td style="text-align: center;">
        EP01
      </td>
    </tr>
    <tr>
      <td style="text-align: center;">
        US07
      </td>
      <td style="text-align: center;">
        Assign equipment to area
      </td>
      <td style="text-align: justify;">
        As a Supervisor, I want to assign equipment to a storage area so I know its location
      </td>
      <td style="text-align: center;">
        EP01
      </td>
    </tr>
    <tr>
      <td style="text-align: center;">
        US08
      </td>
      <td style="text-align: center;">
        Search equipment by name
      </td>
      <td style="text-align: justify;">
        As a Supervisor, I want to search equipment by name so I find it quickly
      </td>
      <td style="text-align: center;">
        EP01
      </td>
    </tr>
    <!-- EP02 -->
    <tr>
      <td style="text-align: center;">
        US09
      </td>
      <td style="text-align: center;">
        View temperature values
      </td>
      <td style="text-align: justify;">
        As an Operator, I want to see temperature values so I monitor conditions
      </td>
      <td style="text-align: center;">
        EP02
      </td>
    </tr>
    <tr>
      <td style="text-align: center;">
        US10
      </td>
      <td style="text-align: center;">
        View humidity values
      </td>
      <td style="text-align: justify;">
        As an Operator, I want to see humidity values so I ensure proper storage
      </td>
      <td style="text-align: center;">
        EP02
      </td>
    </tr>
    <tr>
      <td style="text-align: center;">
        US11
      </td>
      <td style="text-align: center;">
        View equipment working status
      </td>
      <td style="text-align: justify;">
        As an Operator, I want to see if equipment is working so I detect issues
      </td>
      <td style="text-align: center;">
        EP02
      </td>
    </tr>
    <tr>
      <td style="text-align: center;">
        US12
      </td>
      <td style="text-align: center;">
        View equipment details
      </td>
      <td style="text-align: justify;">
        As an Operator, I want to open equipment details to see temperature, humidity and status
      </td>
      <td style="text-align: center;">
        EP02
      </td>
    </tr>
    <tr>
      <td style="text-align: center;">
        US13
      </td>
      <td style="text-align: center;">
        View equipment list with real-time data
      </td>
      <td style="text-align: justify;">
        As an Operator, I want to see equipment with current values so I monitor quickly
      </td>
      <td style="text-align: center;">
        EP02
      </td>
    </tr>
    <tr>
      <td style="text-align: center;">
        US14
      </td>
      <td style="text-align: center;">
        Filter equipment by storage area
      </td>
      <td style="text-align: justify;">
        As an Operator, I want to filter equipment by area so I focus on a location
      </td>
      <td style="text-align: center;">
        EP02
      </td>
    </tr>
    <tr>
      <td style="text-align: center;">
        US15
      </td>
      <td style="text-align: center;">
        Identify equipment without recent data
      </td>
      <td style="text-align: justify;">
        As an Operator, I want to detect equipment without recent data so I act quickly
      </td>
      <td style="text-align: center;">
        EP02
      </td>
    </tr>
    <tr>
      <td style="text-align: center;">
        US16
      </td>
      <td style="text-align: center;">
        Automatic data collection
      </td>
      <td style="text-align: justify;">
        As an Operator, I want data to be collected automatically so I don’t record it manually
      </td>
      <td style="text-align: center;">
        EP02
      </td>
    </tr>
    <tr>
      <td style="text-align: center;">
        US17
      </td>
      <td style="text-align: center;">
        View data on mobile
      </td>
      <td style="text-align: justify;">
        As an Operator, I want to view monitoring data on my phone so I can access it easily
      </td>
      <td style="text-align: center;">
        EP02
      </td>
    </tr>
    <!-- EP03 -->
    <tr>
      <td style="text-align: center;">
        US18
      </td>
      <td style="text-align: center;">
        Receive temperature alerts
      </td>
      <td style="text-align: justify;">
        As an Operator, I want alerts when temperature exceeds limits so I react fast
      </td>
      <td style="text-align: center;">
        EP03
      </td>
    </tr>
    <tr>
      <td style="text-align: center;">
        US19
      </td>
      <td style="text-align: center;">
        Receive humidity alerts
      </td>
      <td style="text-align: justify;">
        As an Operator, I want alerts when humidity exceeds limits so I act quickly
      </td>
      <td style="text-align: center;">
        EP03
      </td>
    </tr>
    <tr>
      <td style="text-align: center;">
        US20
      </td>
      <td style="text-align: center;">
        View alerts list
      </td>
      <td style="text-align: justify;">
        As an Operator, I want to see a list of alerts so I manage incidents
      </td>
      <td style="text-align: center;">
        EP03
      </td>
    </tr>
    <tr>
      <td style="text-align: center;">
        US21
      </td>
      <td style="text-align: center;">
        View alert details
      </td>
      <td style="text-align: justify;">
      As an Operator, I want to open an alert to see equipment, value and time
      </td>
      <td style="text-align: center;">
        EP03
      </td>
    </tr>
    <tr>
      <td style="text-align: center;">
        US22
      </td>
      <td style="text-align: center;">
        Acknowledge alert
      </td>
      <td style="text-align: justify;">
        As an Operator, I want to mark an alert as handled so I track actions
      </td>
      <td style="text-align: center;">
        EP03
      </td>
    </tr>
    <tr>
      <td style="text-align: center;">
        US23
      </td>
      <td style="text-align: center;">
        View alerts sorted by severity
      </td>
      <td style="text-align: justify;">
        As an Operator, I want to see alerts sorted by severity so I prioritize work
      </td>
      <td style="text-align: center;">
        EP03
      </td>
    </tr>
    <tr>
      <td style="text-align: center;">
        US24
      </td>
      <td style="text-align: center;">
        Receive alerts on mobile device
      </td>
      <td style="text-align: justify;">
        As an Operator, I want to receive alerts on my phone so I respond quickly
      </td>
      <td style="text-align: center;">
        EP03
      </td>
    </tr>
    <tr>
      <td style="text-align: center;">
        US25
      </td>
      <td style="text-align: center;">
        Set alert limits per equipment
      </td>
      <td style="text-align: justify;">
        As a Supervisor, I want to define limits so alerts trigger automatically
      </td>
      <td style="text-align: center;">
        EP03
      </td>
    </tr>
    <tr>
      <td style="text-align: center;">
        US26
      </td>
      <td style="text-align: center;">
        Share alerts with team
      </td>
      <td style="text-align: justify;">
        As an Operator, I want alerts to be visible to the team so we coordinate actions
      </td>
      <td style="text-align: center;">
        EP03
      </td>
    </tr>
    <!-- EP04 -->
    <tr>
      <td style="text-align: center;">
        US27
      </td>
      <td style="text-align: center;">
        View historical data
      </td>
      <td style="text-align: justify;">
        As a Supervisor, I want to see past data so I analyze trends
      </td>
      <td style="text-align: center;">
        EP04
      </td>
    </tr>
    <tr>
      <td style="text-align: center;">
        US28
      </td>
      <td style="text-align: center;">
        Select date range for data
      </td>
      <td style="text-align: justify;">
        As a Supervisor, I want to choose a date range so I filter data
      </td>
      <td style="text-align: center;">
        EP04
      </td>
    </tr>
    <tr>
      <td style="text-align: center;">
        US29
      </td>
      <td style="text-align: center;">
        Compare data between periods
      </td>
      <td style="text-align: justify;">
        As a Supervisor, I want to compare data so I detect changes
      </td>
      <td style="text-align: center;">
        EP04
      </td>
    </tr>
    <tr>
      <td style="text-align: center;">
        US30
      </td>
      <td style="text-align: center;">
        Generate report by equipment and date
      </td>
      <td style="text-align: justify;">
        As a Supervisor, I want to generate reports so I validate compliance
      </td>
      <td style="text-align: center;">
        EP04
      </td>
    </tr>
    <tr>
      <td style="text-align: center;">
        US31
      </td>
      <td style="text-align: center;">
        Download report file
      </td>
      <td style="text-align: justify;">
        As a Supervisor, I want to download reports so I share them
      </td>
      <td style="text-align: center;">
        EP04
      </td>
    </tr>
    <tr>
      <td style="text-align: center;">
        US32
      </td>
      <td style="text-align: center;">
        View incident history
      </td>
      <td style="text-align: justify;">
        As a Supervisor, I want to see past alerts so I evaluate performance
      </td>
      <td style="text-align: center;">
        EP04
      </td>
    </tr>
    <tr>
      <td style="text-align: center;">
        US33
      </td>
      <td style="text-align: center;">
        Export data file
      </td>
      <td style="text-align: justify;">
        As a Supervisor, I want to export data so I use it outside the system
      </td>
      <td style="text-align: center;">
        EP04
      </td>
    </tr>
    <tr>
      <td style="text-align: center;">
        US34
      </td>
      <td style="text-align: center;">
        Compare weekly and monthly data
      </td>
      <td style="text-align: justify;">
        As a Supervisor, I want to compare data between weeks and months so I detect variations
      </td>
      <td style="text-align: center;">
        EP04
      </td>
    </tr>
    <!-- EP05 -->
    <tr>
      <td style="text-align: center;">
        US35
      </td>
      <td style="text-align: center;">
        View equipment condition
      </td>
      <td style="text-align: justify;">
        As a Supervisor, I want to see if equipment is working correctly so I prevent failures
      </td>
      <td style="text-align: center;">
        EP05
      </td>
    </tr>
    <tr>
      <td style="text-align: center;">
        US36
      </td>
      <td style="text-align: center;">
        View abnormal values
      </td>
      <td style="text-align: justify;">
        As an Operator, I want to see values outside limits so I detect problems
      </td>
      <td style="text-align: center;">
        EP05
      </td>
    </tr>
    <tr>
      <td style="text-align: center;">
        US37
      </td>
      <td style="text-align: center;">
        Receive equipment warning alerts
      </td>
      <td style="text-align: justify;">
        As an Operator, I want to receive warnings so I prevent failures
      </td>
      <td style="text-align: center;">
        EP05
      </td>
    </tr>
    <tr>
      <td style="text-align: center;">
        US38
      </td>
      <td style="text-align: center;">
        View equipment performance data
      </td>
      <td style="text-align: justify;">
        As a Supervisor, I want to see performance over time so I improve operations
      </td>
      <td style="text-align: center;">
        EP05
      </td>
    </tr>
    <tr>
      <td style="text-align: center;">
        US39
      </td>
      <td style="text-align: center;">
        View equipment usage data
      </td>
      <td style="text-align: justify;">
        As a Supervisor, I want to see usage so I manage resources
      </td>
      <td style="text-align: center;">
        EP05
      </td>
    </tr>
    <tr>
      <td style="text-align: center;">
        US40
      </td>
      <td style="text-align: center;">
        Register maintenance record
      </td>
      <td style="text-align: justify;">
        As a Supervisor, I want to record maintenance so I track history
      </td>
      <td style="text-align: center;">
        EP05
      </td>
    </tr>
    <tr>
      <td style="text-align: center;">
        US41
      </td>
      <td style="text-align: center;">
        View maintenance history
      </td>
      <td style="text-align: justify;">
        As a Supervisor, I want to see maintenance records so I ensure reliability
      </td>
      <td style="text-align: center;">
        EP05
      </td>
    </tr>
    <tr>
      <td style="text-align: center;">
        US42
      </td>
      <td style="text-align: center;">
        View equipment reliability
      </td>
      <td style="text-align: justify;">
        As a Supervisor, I want to see stability over time so I prevent failures
      </td>
      <td style="text-align: center;">
        EP05
      </td>
    </tr>
    <!-- EP06 -->
    <tr>
      <td style="text-align: center;">
        US43
      </td>
      <td style="text-align: center;">
        View dashboard
      </td>
      <td style="text-align: justify;">
        As a Supervisor, I want to see key system information
      </td>
      <td style="text-align: center;">
        EP06
      </td>
    </tr>
    <tr>
      <td style="text-align: center;">
        US44
      </td>
      <td style="text-align: center;">
        View critical alerts
      </td>
      <td style="text-align: justify;">
        As a Supervisor, I want to see critical alerts so I act immediately
      </td>
      <td style="text-align: center;">
        EP06
      </td>
    </tr>
    <tr>
      <td style="text-align: center;">
        US45
      </td>
      <td style="text-align: center;">
        View summary with totals
      </td>
      <td style="text-align: justify;">
        As a Supervisor, I want an overview of equipment and alerts
      </td>
      <td style="text-align: center;">
        EP06
      </td>
    </tr>
    <tr>
      <td style="text-align: center;">
        US46
      </td>
      <td style="text-align: center;">
        View equipment with active alerts
      </td>
      <td style="text-align: justify;">
        As a Supervisor, I want to see equipment with issues
      </td>
      <td style="text-align: center;">
        EP06
      </td>
    </tr>
    <tr>
      <td style="text-align: center;">
        US47
      </td>
      <td style="text-align: center;">
        View equipment without recent data
      </td>
      <td style="text-align: justify;">
        As an Operator, I want to detect missing data
      </td>
      <td style="text-align: center;">
        EP06
      </td>
    </tr>
    <tr>
      <td style="text-align: center;">
        US48
      </td>
      <td style="text-align: center;">
        View alert trends
      </td>
      <td style="text-align: justify;">
        As a Supervisor, I want to analyze alert patterns
      </td>
      <td style="text-align: center;">
        EP06
      </td>
    </tr>
    <tr>
      <td style="text-align: center;">
        US49
      </td>
      <td style="text-align: center;">
        View temperature trends
      </td>
      <td style="text-align: justify;">
        As a Supervisor, I want to analyze temperature changes
      </td>
      <td style="text-align: center;">
        EP06
      </td>
    </tr>
    <tr>
      <td style="text-align: center;">
        US50
      </td>
      <td style="text-align: center;">
        View humidity trends
      </td>
      <td style="text-align: justify;">
        As a Supervisor, I want to analyze humidity changes
      </td>
      <td style="text-align: center;">
        EP06
      </td>
    </tr>
    <!-- EP07 -->
    <tr>
      <td style="text-align: center;">
        US51
      </td>
      <td style="text-align: center;">
        Login with Google account
      </td>
      <td style="text-align: justify;">
        As a user, I want to log in with Google so I access quickly
      </td>
      <td style="text-align: center;">
        EP07
      </td>
    </tr>
    <tr>
      <td style="text-align: center;">
        US52
      </td>
      <td style="text-align: center;">
        Login with email and password
      </td>
      <td style="text-align: justify;">
        As a user, I want to log in with email so I access my account
      </td>
      <td style="text-align: center;">
        EP07
      </td>
    </tr>
    <tr>
      <td style="text-align: center;">
        US53
      </td>
      <td style="text-align: center;">
        Recover password by email
      </td>
      <td style="text-align: justify;">
        As a user, I want to recover access via email
      </td>
      <td style="text-align: center;">
        EP07
      </td>
    </tr>
    <tr>
      <td style="text-align: center;">
        US54
      </td>
      <td style="text-align: center;">
        Logout from system
      </td>
      <td style="text-align: justify;">
        As a user, I want to log out to protect my account
      </td>
      <td style="text-align: center;">
        EP07
      </td>
    </tr>
    <tr>
      <td style="text-align: center;">
        US55
      </td>
      <td style="text-align: center;">
        Assign user role
      </td>
      <td style="text-align: justify;">
        As a Supervisor, I want to assign roles so users have proper access
      </td>
      <td style="text-align: center;">
        EP07
      </td>
    </tr>
 </tbody>
</table>

<div style="page-break-after: always;"></div>

<!-- ===================== HU01 ===================== -->
<table style="margin: auto; table-layout: fixed; width: 80%;">
  <tr style="background-color: #d9d9d9;">
    <td>
      <b>Number:</b>
    </td>
    <td style="text-align: center;">
      HU01
    </td>
    <td>
      <b>User:</b>
    </td>
    <td style="text-align: center;">
      Supervisor
    </td>
  </tr>
  <tr>
    <td>
      <b>Story Name:</b>
    </td>
    <td style="text-align: center;" colspan="3">
      Register laboratory site
    </td>
  </tr>
  <tr>
    <td>
      <b>Business Priority:</b>
    </td>
    <td colspan="3">
      High
    </td>
  </tr>
  <tr>
    <td>
      <b>Developer:</b>
    </td>
    <td colspan="3">
      To be defined
    </td>
  </tr>
  <tr>
    <td>
      <b>Description:</b>
    </td>
    <td  style="text-align: justify;" colspan="3">
      <i>As a</i> Supervisor, <i>I want to</i> register a laboratory site with name and location <i>so</i> I can organize monitoring
    </td>
  </tr>
  <tr>
    <td>
      <b>Acceptance Criteria:</b>
    </td>
    <td style="text-align: justify;" colspan="3">
      <div style="text-align: center;">
        <b>Scenario 1: Successful registration</b>
      </div>
              <i>Given</i> a site name and location
      <br><i>When</i> the user saves
      <br><i>Then</i> the system registers the site      <br><br>
      <div style="text-align: center;">
        <b>Scenario 2: Missing data</b>
      </div>
              <i>Given</i> missing name or location
      <br><i>When</i> saving
      <br><i>Then</i> the system shows an error
    </td>
  </tr>
</table>

<br><br>

<!-- ===================== HU02 ===================== -->
<table style="margin: auto; table-layout: fixed; width: 80%;">
  <tr style="background-color: #d9d9d9;">
    <td>
      <b>Number:</b>
    </td>
    <td style="text-align: center;">
      HU02
    </td>
    <td>
      <b>User:</b>
    </td>
    <td style="text-align: center;">
      Supervisor
    </td>
  </tr>
  <tr>
    <td>
      <b>Story Name:</b>
    </td>
    <td style="text-align: center;" colspan="3">
      View laboratory sites
    </td>
  </tr>
  <tr>
    <td>
      <b>Business Priority:</b>
    </td>
    <td colspan="3">
      High
    </td>
  </tr>
  <tr>
    <td>
      <b>Developer:</b>
    </td>
    <td colspan="3">
      To be defined
    </td>
  </tr>
  <tr>
    <td>
      <b>Description:</b>
    </td>
    <td style="text-align: justify;" colspan="3">
      <i>As a</i> Supervisor, <i>I want to</i> view all registered sites <i>so</i> I can manage themg
    </td>
  </tr>
  <tr>
    <td>
      <b>Acceptance Criteria:</b>
    </td>
    <td style="text-align: justify;" colspan="3">
      <div style="text-align: center;">
        <b>Scenario 1: View list</b>
      </div>
              <i>Given</i> existing sites
      <br><i>When</i> accessing the list
      <br><i>Then</i> the system displays all sites      <br><br>
      <div style="text-align: center;">
        <b>Scenario 2: Empty list</b>
      </div>
              <i>Given</i> no sites registered
      <br><i>When</i> accessing
      <br><i>Then</i> the system shows empty message
    </td>
  </tr>
</table>

<div style="page-break-after: always;"></div>

<!-- ===================== HU03 ===================== -->
<table style="margin: auto; table-layout: fixed; width: 80%;">
  <tr style="background-color: #d9d9d9;">
    <td>
      <b>Number:</b>
    </td>
    <td style="text-align: center;">
      HU03
    </td>
    <td>
      <b>User:</b>
    </td>
    <td style="text-align: center;">
      Supervisor
    </td>
  </tr>
  <tr>
    <td>
      <b>Story Name:</b>
    </td>
    <td style="text-align: center;" colspan="3">
      Create storage area
    </td>
  </tr>
  <tr>
    <td>
      <b>Business Priority:</b>
    </td>
    <td colspan="3">
      High
    </td>
  </tr>
  <tr>
    <td>
      <b>Developer:</b>
    </td>
    <td colspan="3">
      To be defined
    </td>
  </tr>
  <tr>
    <td>
      <b>Description:</b>
    </td>
    <td style="text-align: justify;" colspan="3">
      <i>As a</i> Supervisor, <i>I want to</i> create a storage area with name and type <i>so</i> I can organize equipment
    </td>
  </tr>
  <tr>
    <td>
      <b>Acceptance Criteria:</b>
    </td>
    <td style="text-align: justify;" colspan="3">
      <div style="text-align: center;">
        <b>Scenario 1: Successful creation</b>
      </div>
              <i>Given</i> name and type
      <br><i>When</i> saving
      <br><i>Then</i> the system creates the area      <br><br>
      <div style="text-align: center;">
        <b>Scenario 2: Missing data</b>
      </div>
              <i>Given</i> missing fields
      <br><i>When</i> saving
      <br><i>Then</i> error is shown
    </td>
  </tr>
</table>

<br><br>

<!-- ===================== HU04 ===================== -->
<table style="margin: auto; table-layout: fixed; width: 80%;">
  <tr style="background-color: #d9d9d9;">
    <td>
      <b>Number:</b>
    </td>
    <td style="text-align: center;">
      HU04
    </td>
    <td>
      <b>User:</b>
    </td>
    <td style="text-align: center;">
      Supervisor
    </td>
  </tr>
  <tr>
    <td>
      <b>Story Name:</b>
    </td>
    <td style="text-align: center;" colspan="3">
      View storage areas
    </td>
  </tr>
  <tr>
    <td>
      <b>Business Priority:</b>
    </td>
    <td colspan="3">
      Medium
    </td>
  </tr>
  <tr>
    <td>
      <b>Developer:</b>
    </td>
    <td colspan="3">
      To be defined
    </td>
  </tr>
  <tr>
    <td>
      <b>Description:</b>
    </td>
    <td style="text-align: justify;" colspan="3">
      <i>As a</i> Supervisor, <i>I want to</i> see storage areas <i>so</i> I understand organization
    </td>
  </tr>
  <tr>
    <td>
      <b>Acceptance Criteria:</b>
    </td>
    <td style="text-align: justify;" colspan="3">
      <div style="text-align: center;">
        <b>Scenario 1: Show areas</b>
      </div>
              <i>Given</i> areas exist
      <br><i>When</i> opening list
      <br><i>Then</i> system shows areas      <br><br>
      <div style="text-align: center;">
        <b>Scenario 2: No areas</b>
      </div>
              <i>Given</i> no data
      <br><i>When</i> opening
      <br><i>Then</i> empty message appears
    </td>
  </tr>
</table>

<div style="page-break-after: always;"></div>

<!-- ===================== HU05 ===================== -->
<table style="margin: auto; table-layout: fixed; width: 80%;">
  <tr style="background-color: #d9d9d9;">
    <td>
      <b>Number:</b>
    </td>
    <td style="text-align: center;">
      HU05
    </td>
    <td>
      <b>User:</b>
    </td>
    <td style="text-align: center;">
      Supervisor
    </td>
  </tr>
  <tr>
    <td>
      <b>Story Name:</b>
    </td>
    <td style="text-align: center;" colspan="3">
      Register equipment
    </td>
  </tr>
  <tr>
    <td>
      <b>Business Priority:</b>
    </td>
    <td colspan="3">
      High
    </td>
  </tr>
  <tr>
    <td>
      <b>Developer:</b>
    </td>
    <td colspan="3">
      To be defined
    </td>
  </tr>
  <tr>
    <td>
      <b>Description:</b>
    </td>
    <td style="text-align: justify;" colspan="3">
      <i>As a</i> Supervisor, <i>I want to</i> register equipment with name and type <i>so</i> it can be monitored
    </td>
  </tr>
  <tr>
    <td>
      <b>Acceptance Criteria:</b>
    </td>
    <td style="text-align: justify;" colspan="3">
      <div style="text-align: center;">
        <b>Scenario 1: Register equipment</b>
      </div>
              <i>Given</i> valid data
      <br><i>When</i> saving
      <br><i>Then</i> equipment is created      <br><br>
      <div style="text-align: center;">
        <b>Scenario 2: Missing data</b>
      </div>
              <i>Given</i> missing fields
      <br><i>When</i> saving
      <br><i>Then</i> error appears
    </td>
  </tr>
</table>

<br><br>

<!-- ===================== HU06 ===================== -->
<table style="margin: auto; table-layout: fixed; width: 80%;">
  <tr style="background-color: #d9d9d9;">
    <td>
      <b>Number:</b>
    </td>
    <td style="text-align: center;">
      HU06
    </td>
    <td>
      <b>User:</b>
    </td>
    <td style="text-align: center;">
      Supervisor
    </td>
  </tr>
  <tr>
    <td>
      <b>Story Name:</b>
    </td>
    <td style="text-align: center;" colspan="3">
      View equipment list
    </td>
  </tr>
  <tr>
    <td>
      <b>Business Priority:</b>
    </td>
    <td colspan="3">
      High
    </td>
  </tr>
  <tr>
    <td>
      <b>Developer:</b>
    </td>
    <td colspan="3">
      To be defined
    </td>
  </tr>
  <tr>
    <td>
      <b>Description:</b>
    </td>
    <td style="text-align: justify;" colspan="3">
      <i>As a</i> Supervisor, <i>I want to</i> see all equipment <i>so</i> I can manage it
    </td>
  </tr>
  <tr>
    <td>
      <b>Acceptance Criteria:</b>
    </td>
    <td style="text-align: justify;" colspan="3">
      <div style="text-align: center;">
        <b>Scenario 1: Show list</b>
      </div>
              <i>Given</i> equipment exists
      <br><i>When</i> opening list
      <br><i>Then</i> system displays equipment      <br><br>
      <div style="text-align: center;">
        <b>Scenario 2: Empty list</b>
      </div>
              <i>Given</i> no equipment
      <br><i>When</i> opening
      <br><i>Then</i> show empty message
    </td>
  </tr>
</table>

<div style="page-break-after: always;"></div>

<!-- ===================== HU07 ===================== -->
<table style="margin: auto; table-layout: fixed; width: 80%;">
  <tr style="background-color: #d9d9d9;">
    <td>
      <b>Number:</b>
    </td>
    <td style="text-align: center;">
      HU07
    </td>
    <td>
      <b>User:</b>
    </td>
    <td style="text-align: center;">
      Supervisor
    </td>
  </tr>
  <tr>
    <td>
      <b>Story Name:</b>
    </td>
    <td style="text-align: center;" colspan="3">
      Assign equipment to area
    </td>
  </tr>
  <tr>
    <td>
      <b>Business Priority:</b>
    </td>
    <td colspan="3">
      High
    </td>
  </tr>
  <tr>
    <td>
      <b>Developer:</b>
    </td>
    <td colspan="3">
      To be defined
    </td>
  </tr>
  <tr>
    <td>
      <b>Description:</b>
    </td>
    <td style="text-align: justify;" colspan="3">
      <i>As a</i> Supervisor, <i>I want to</i> assign equipment to an area <i>so</i> I know its location
    </td>
  </tr>
  <tr>
    <td>
      <b>Acceptance Criteria:</b>
    </td>
    <td style="text-align: justify;" colspan="3">
      <div style="text-align: center;">
        <b>Scenario 1: Assign equipment</b>
      </div>
              <i>Given</i> equipment and area
      <br><i>When</i> assigning
      <br><i>Then</i> system links them      <br><br>
      <div style="text-align: center;">
        <b>Scenario 2: Missing selection</b>
      </div>
              <i>Given</i> missing data
      <br><i>When</i> assigning
      <br><i>Then</i> show error
    </td>
  </tr>
</table>

<br><br>

<!-- ===================== HU08 ===================== -->
<table style="margin: auto; table-layout: fixed; width: 80%;">
  <tr style="background-color: #d9d9d9;">
    <td>
      <b>Number:</b>
    </td>
    <td style="text-align: center;">
      HU08
    </td>
    <td>
      <b>User:</b>
    </td>
    <td style="text-align: center;">
      Supervisor
    </td>
  </tr>
  <tr>
    <td>
      <b>Story Name:</b>
    </td>
    <td style="text-align: center;" colspan="3">
      Search equipment by name
    </td>
  </tr>
  <tr>
    <td>
      <b>Business Priority:</b>
    </td>
    <td colspan="3">
      Medium
    </td>
  </tr>
  <tr>
    <td>
      <b>Developer:</b>
    </td>
    <td colspan="3">
      To be defined
    </td>
  </tr>
  <tr>
    <td>
      <b>Description:</b>
    </td>
    <td style="text-align: justify;" colspan="3">
      <i>As a</i> Supervisor, <i>I want to</i> search equipment by name <i>so</i> I find it quickly
    </td>
  </tr>
  <tr>
    <td>
      <b>Acceptance Criteria:</b>
    </td>
    <td style="text-align: justify;" colspan="3">
      <div style="text-align: center;">
        <b>Scenario 1: Search result</b>
      </div>
              <i>Given</i> matching name
      <br><i>When</i> searching
      <br><i>Then</i> system shows results      <br><br>
      <div style="text-align: center;">
        <b>Scenario 2: No result</b>
      </div>
              <i>Given</i> no match
      <br><i>When</i> searching
      <br><i>Then</i> show no results message
    </td>
  </tr>
</table>

<div style="page-break-after: always;"></div>

<!-- ===================== HU09 ===================== -->
<table style="margin: auto; table-layout: fixed; width: 80%;">
  <tr style="background-color: #d9d9d9;">
    <td>
      <b>Number:</b>
    </td>
    <td style="text-align: center;">
      HU09
    </td>
    <td>
      <b>User:</b>
    </td>
    <td style="text-align: center;">
      Operator
    </td>
  </tr>
  <tr>
    <td>
      <b>Story Name:</b>
    </td>
    <td style="text-align: center;" colspan="3">
      View temperature values
    </td>
  </tr>
  <tr>
    <td>
      <b>Business Priority:</b>
    </td>
    <td colspan="3">
      High
    </td>
  </tr>
  <tr>
    <td>
      <b>Developer:</b>
    </td>
    <td colspan="3">
      To be defined
    </td>
  </tr>
  <tr>
    <td>
      <b>Description:</b>
    </td>
    <td style="text-align: justify;" colspan="3">
      <i>As a</i> Operator, <i>I want to</i> see temperature values <i>so</i> I monitor conditions
    </td>
  </tr>
  <tr>
    <td>
      <b>Acceptance Criteria:</b>
    </td>
    <td style="text-align: justify;" colspan="3">
      <div style="text-align: center;">
        <b>Scenario 1: Show temperature</b>
      </div>
              <i>Given</i> equipment connected
      <br><i>When</i> viewing
      <br><i>Then</i> temperature is displayed      <br><br>
      <div style="text-align: center;">
        <b>Scenario 2: No data</b>
      </div>
              <i>Given</i> no data
      <br><i>When</i> viewing
      <br><i>Then</i> system shows warning
    </td>
  </tr>
</table>

<br><br>

<!-- ===================== HU10 ===================== -->
<table style="margin: auto; table-layout: fixed; width: 80%;">
  <tr style="background-color: #d9d9d9;">
    <td>
      <b>Number:</b>
    </td>
    <td style="text-align: center;">
      HU10
    </td>
    <td>
      <b>User:</b>
    </td>
    <td style="text-align: center;">
      Operator
    </td>
  </tr>
  <tr>
    <td>
      <b>Story Name:</b>
    </td>
    <td style="text-align: center;" colspan="3">
      View humidity values
    </td>
  </tr>
  <tr>
    <td>
      <b>Business Priority:</b>
    </td>
    <td colspan="3">
      High
    </td>
  </tr>
  <tr>
    <td>
      <b>Developer:</b>
    </td>
    <td colspan="3">
      To be defined
    </td>
  </tr>
  <tr>
    <td>
      <b>Description:</b>
    </td>
    <td style="text-align: justify;" colspan="3">
      <i>As a</i> Operator, <i>I want to</i> see humidity values <i>so</i> I ensure proper storage
    </td>
  </tr>
  <tr>
    <td>
      <b>Acceptance Criteria:</b>
    </td>
    <td style="text-align: justify;" colspan="3">
      <div style="text-align: center;">
        <b>Scenario 1: Show humidity</b>
      </div>
              <i>Given</i> equipment connected
      <br><i>When</i> viewing
      <br><i>Then</i> humidity is displayed      <br><br>
      <div style="text-align: center;">
        <b>Scenario 2: No data</b>
      </div>
              <i>Given</i> no data
      <br><i>When</i> viewing
      <br><i>Then</i> system shows warning
    </td>
  </tr>
</table>

<div style="page-break-after: always;"></div>

<!-- ===================== HU11 ===================== -->
<table style="margin: auto; table-layout: fixed; width: 80%;">
  <tr style="background-color: #d9d9d9;">
    <td>
      <b>Number:</b>
    </td>
    <td style="text-align: center;">
      HU11
    </td>
    <td>
      <b>User:</b>
    </td>
    <td style="text-align: center;">
      Operator
    </td>
  </tr>
  <tr>
    <td>
      <b>Story Name:</b>
    </td>
    <td style="text-align: center;" colspan="3">
      View equipment working status
    </td>
  </tr>
  <tr>
    <td>
      <b>Business Priority:</b>
    </td>
    <td colspan="3">
      High
    </td>
  </tr>
  <tr>
    <td>
      <b>Developer:</b>
    </td>
    <td colspan="3">
      To be defined
    </td>
  </tr>
  <tr>
    <td>
      <b>Description:</b>
    </td>
    <td style="text-align: justify;" colspan="3">
      <i>As a</i> Operator, <i>I want to</i> see if equipment is working or not <i>so</i> I detect issues
    </td>
  </tr>
  <tr>
    <td>
      <b>Acceptance Criteria:</b>
    </td>
    <td style="text-align: justify;" colspan="3">
      <div style="text-align: center;">
        <b>Scenario 1: Working status</b>
      </div>
              <i>Given</i> equipment sending data
      <br><i>When</i> viewing status
      <br><i>Then</i> system shows "working"      <br><br>
      <div style="text-align: center;">
        <b>Scenario 2: Not working</b>
      </div>
              <i>Given</i> no data received
      <br><i>When</i> viewing status
      <br><i>Then</i> system shows "not working"
    </td>
  </tr>
</table>

<br><br>

<!-- ===================== HU12 ===================== -->
<table style="margin: auto; table-layout: fixed; width: 80%;">
  <tr style="background-color: #d9d9d9;">
    <td>
      <b>Number:</b>
    </td>
    <td style="text-align: center;">
      HU12
    </td>
    <td>
      <b>User:</b>
    </td>
    <td style="text-align: center;">
      Operator
    </td>
  </tr>
  <tr>
    <td>
      <b>Story Name:</b>
    </td>
    <td style="text-align: center;" colspan="3">
      View equipment details
    </td>
  </tr>
  <tr>
    <td>
      <b>Business Priority:</b>
    </td>
    <td colspan="3">
      High
    </td>
  </tr>
  <tr>
    <td>
      <b>Developer:</b>
    </td>
    <td colspan="3">
      To be defined
    </td>
  </tr>
  <tr>
    <td>
      <b>Description:</b>
    </td>
    <td style="text-align: justify;" colspan="3">
      <i>As a</i> Operator, <i>I want to</i> view equipment details <i>so</i> I see temperature, humidity and status
    </td>
  </tr>
  <tr>
    <td>
      <b>Acceptance Criteria:</b>
    </td>
    <td style="text-align: justify;" colspan="3">
      <div style="text-align: center;">
        <b>Scenario 1: View details</b>
      </div>
              <i>Given</i> existing equipment
      <br><i>When</i> opening details
      <br><i>Then</i> system shows temperature, humidity and status      <br><br>
      <div style="text-align: center;">
        <b>Scenario 2: Equipment not found</b>
      </div>
              <i>Given</i> invalid selection
      <br><i>When</i> opening
      <br><i>Then</i> system shows error
    </td>
  </tr>
</table>

<div style="page-break-after: always;"></div>

<!-- ===================== HU13 ===================== -->
<table style="margin: auto; table-layout: fixed; width: 80%;">
  <tr style="background-color: #d9d9d9;">
    <td>
      <b>Number:</b>
    </td>
    <td style="text-align: center;">
      HU13
    </td>
    <td>
      <b>User:</b>
    </td>
    <td style="text-align: center;">
      Operator
    </td>
  </tr>
  <tr>
    <td>
      <b>Story Name:</b>
    </td>
    <td style="text-align: center;" colspan="3">
      View equipment list with real-time data
    </td>
  </tr>
  <tr>
    <td>
      <b>Business Priority:</b>
    </td>
    <td colspan="3">
      High
    </td>
  </tr>
  <tr>
    <td>
      <b>Developer:</b>
    </td>
    <td colspan="3">
      To be defined
    </td>
  </tr>
  <tr>
    <td>
      <b>Description:</b>
    </td>
    <td style="text-align: justify;" colspan="3">
      <i>As a</i> Operator, <i>I want to</i> see equipment with current values <i>so</i> I monitor quickly
    </td>
  </tr>
  <tr>
    <td>
      <b>Acceptance Criteria:</b>
    </td>
    <td style="text-align: justify;" colspan="3">
      <div style="text-align: center;">
        <b>Scenario 1: Show list with data</b>
      </div>
              <i>Given</i> equipment available
      <br><i>When</i> viewing list
      <br><i>Then</i> system shows temperature and humidity      <br><br>
      <div style="text-align: center;">
        <b>Scenario 2: Missing data</b>
      </div>
              <i>Given</i> no data available
      <br><i>When</i> viewing list
      <br><i>Then</i> system shows warning
    </td>
  </tr>
</table>

<br><br>

<!-- ===================== HU14 ===================== -->
<table style="margin: auto; table-layout: fixed; width: 80%;">
  <tr style="background-color: #d9d9d9;">
    <td>
      <b>Number:</b>
    </td>
    <td style="text-align: center;">
      HU14
    </td>
    <td>
      <b>User:</b>
    </td>
    <td style="text-align: center;">
      Operator
    </td>
  </tr>
  <tr>
    <td>
      <b>Story Name:</b>
    </td>
    <td style="text-align: center;" colspan="3">
      Filter equipment by storage area
    </td>
  </tr>
  <tr>
    <td>
      <b>Business Priority:</b>
    </td>
    <td colspan="3">
      Medium
    </td>
  </tr>
  <tr>
    <td>
      <b>Developer:</b>
    </td>
    <td colspan="3">
      To be defined
    </td>
  </tr>
  <tr>
    <td>
      <b>Description:</b>
    </td>
    <td style="text-align: justify;" colspan="3">
      <i>As a</i> Operator, <i>I want to</i> filter equipment by area <i>so</i> I focus on a location
    </td>
  </tr>
  <tr>
    <td>
      <b>Acceptance Criteria:</b>
    </td>
    <td style="text-align: justify;" colspan="3">
      <div style="text-align: center;">
        <b>Scenario 1: Filter results</b>
      </div>
              <i>Given</i> selected area
      <br><i>When</i> applying filter
      <br><i>Then</i> system shows only equipment in that area      <br><br>
      <div style="text-align: center;">
        <b>Scenario 2: No results</b>
      </div>
              <i>Given</i> no equipment in area
      <br><i>When</i> filtering
      <br><i>Then</i> show empty message
    </td>
  </tr>
</table>

<div style="page-break-after: always;"></div>

<!-- ===================== HU15 ===================== -->
<table style="margin: auto; table-layout: fixed; width: 80%;">
  <tr style="background-color: #d9d9d9;">
    <td>
      <b>Number:</b>
    </td>
    <td style="text-align: center;">
      HU15
    </td>
    <td>
      <b>User:</b>
    </td>
    <td style="text-align: center;">
      Operator
    </td>
  </tr>
  <tr>
    <td>
      <b>Story Name:</b>
    </td>
    <td style="text-align: center;" colspan="3">
      Identify equipment without recent data
    </td>
  </tr>
  <tr>
    <td>
      <b>Business Priority:</b>
    </td>
    <td colspan="3">
      High
    </td>
  </tr>
  <tr>
    <td>
      <b>Developer:</b>
    </td>
    <td colspan="3">
      To be defined
    </td>
  </tr>
  <tr>
    <td>
      <b>Description:</b>
    </td>
    <td style="text-align: justify;" colspan="3">
      <i>As a</i> Operator, <i>I want to</i> detect equipment without recent data <i>so</i> I act quickly
    </td>
  </tr>
  <tr>
    <td>
      <b>Acceptance Criteria:</b>
    </td>
    <td style="text-align: justify;" colspan="3">
      <div style="text-align: center;">
        <b>Scenario 1: Detect no data</b>
      </div>
              <i>Given</i> no data received for a period
      <br><i>When</i> viewing equipment
      <br><i>Then</i> system highlights it      <br><br>
      <div style="text-align: center;">
        <b>Scenario 2: Normal data</b>
      </div>
              <i>Given</i> data is available
      <br><i>When</i> viewing
      <br><i>Then</i> no warning is shown
    </td>
  </tr>
</table>

<br><br>

<!-- ===================== HU16 ===================== -->
<table style="margin: auto; table-layout: fixed; width: 80%;">
  <tr style="background-color: #d9d9d9;">
    <td>
      <b>Number:</b>
    </td>
    <td style="text-align: center;">
      HU16
    </td>
    <td>
      <b>User:</b>
    </td>
    <td style="text-align: center;">
      Operator
    </td>
  </tr>
  <tr>
    <td>
      <b>Story Name:</b>
    </td>
    <td style="text-align: center;" colspan="3">
      Automatic data collection
    </td>
  </tr>
  <tr>
    <td>
      <b>Business Priority:</b>
    </td>
    <td colspan="3">
      High
    </td>
  </tr>
  <tr>
    <td>
      <b>Developer:</b>
    </td>
    <td colspan="3">
      To be defined
    </td>
  </tr>
  <tr>
    <td>
      <b>Description:</b>
    </td>
    <td style="text-align: justify;" colspan="3">
      <i>As a</i> Operator, I want data to be collected automatically <i>so</i> I don’t record it manually
    </td>
  </tr>
  <tr>
    <td>
      <b>Acceptance Criteria:</b>
    </td>
    <td style="text-align: justify;" colspan="3">
      <div style="text-align: center;">
        <b>Scenario 1: Automatic update</b>
      </div>
              <i>Given</i> connected equipment
      <br><i>When</i> system runs
      <br><i>Then</i> data updates automatically      <br><br>
      <div style="text-align: center;">
        <b>Scenario 2: No connection</b>
      </div>
              <i>Given</i> no connection
      <br><i>When</i> collecting data
      <br><i>Then</i> system shows warning
    </td>
  </tr>
</table>

<div style="page-break-after: always;"></div>

<!-- ===================== HU17 ===================== -->
<table style="margin: auto; table-layout: fixed; width: 80%;">
  <tr style="background-color: #d9d9d9;">
    <td>
      <b>Number:</b>
    </td>
    <td style="text-align: center;">
      HU17
    </td>
    <td>
      <b>User:</b>
    </td>
    <td style="text-align: center;">
      Operator
    </td>
  </tr>
  <tr>
    <td>
      <b>Story Name:</b>
    </td>
    <td style="text-align: center;" colspan="3">
      View data on mobile
    </td>
  </tr>
  <tr>
    <td>
      <b>Business Priority:</b>
    </td>
    <td colspan="3">
      High
    </td>
  </tr>
  <tr>
    <td>
      <b>Developer:</b>
    </td>
    <td colspan="3">
      To be defined
    </td>
  </tr>
  <tr>
    <td>
      <b>Description:</b>
    </td>
    <td style="text-align: justify;" colspan="3">
      <i>As a</i> Operator, <i>I want to</i> view monitoring data on my phone <i>so</i> I can access it easily
    </td>
  </tr>
  <tr>
    <td>
      <b>Acceptance Criteria:</b>
    </td>
    <td style="text-align: justify;" colspan="3">
      <div style="text-align: center;">
        <b>Scenario 1: Mobile access</b>
      </div>
          <i>Given</i> logged in user
      <br><i>When</i> accessing from mobile
      <br><i>Then</i> system shows data correctly
      <br><br>
      <div style="text-align: center;">
        <b>Scenario 2: No access</b>
      </div>
          <i>Given</i> no connection
      <br><i>When</i> accessing
      <br><i>Then</i> system shows error
    </td>
  </tr>
</table>

<br><br>

<!-- ===================== HU18 ===================== -->
<table style="margin: auto; table-layout: fixed; width: 80%;">
  <tr style="background-color: #d9d9d9;">
    <td>
      <b>Number:</b>
    </td>
    <td style="text-align: center;">
      HU18
    </td>
    <td>
      <b>User:</b>
    </td>
    <td style="text-align: center;">
      Operator
    </td>
  </tr>
  <tr>
    <td>
      <b>Story Name:</b>
    </td>
    <td style="text-align: center;" colspan="3">
      Receive temperature alerts
    </td>
  </tr>
  <tr>
    <td>
      <b>Business Priority:</b>
    </td>
    <td colspan="3">
      High
    </td>
  </tr>
  <tr>
    <td>
      <b>Developer:</b>
    </td>
    <td colspan="3">
      To be defined
    </td>
  </tr>
  <tr>
    <td>
      <b>Description:</b>
    </td>
    <td style="text-align: justify;" colspan="3">
      <i>As a</i> Operator, I want alerts when temperature exceeds limits <i>so</i> I react fast
    </td>
  </tr>
  <tr>
    <td>
      <b>Acceptance Criteria:</b>
    </td>
    <td style="text-align: justify;" colspan="3">
      <div style="text-align: center;">
        <b>Scenario 1: Alert triggered</b>
      </div>
          <i>Given</i> temperature exceeds limit
      <br><i>When</i> system detects it
      <br><i>Then</i> alert is generated
      <br><br>
      <div style="text-align: center;">
        <b>Scenario 2: Normal values</b>
      </div>
          <i>Given</i> temperature within limits
      <br><i>When</i> monitoring
      <br><i>Then</i> no alert is generated
    </td>
  </tr>
</table>

<div style="page-break-after: always;"></div>

<!-- ===================== HU19 ===================== -->
<table style="margin: auto; table-layout: fixed; width: 80%;">
  <tr style="background-color: #d9d9d9;">
    <td>
      <b>Number:</b>
    </td>
    <td style="text-align: center;">
      HU19
    </td>
    <td>
      <b>User:</b>
    </td>
    <td style="text-align: center;">
      Operator
    </td>
  </tr>
  <tr>
    <td>
      <b>Story Name:</b>
    </td>
    <td style="text-align: center;" colspan="3">
      Receive humidity alerts
    </td>
  </tr>
  <tr>
    <td>
      <b>Business Priority:</b>
    </td>
    <td colspan="3">
      High
    </td>
  </tr>
  <tr>
    <td>
      <b>Developer:</b>
    </td>
    <td colspan="3">
      To be defined
    </td>
  </tr>
  <tr>
    <td>
      <b>Description:</b>
    </td>
    <td style="text-align: justify;" colspan="3">
      <i>As a</i> Operator, I want alerts when humidity exceeds limits <i>so</i> I act quickly
    </td>
  </tr>
  <tr>
    <td>
      <b>Acceptance Criteria:</b>
    </td>
    <td style="text-align: justify;" colspan="3">
      <div style="text-align: center;">
        <b>Scenario 1: Alert triggered</b>
      </div>
          <i>Given</i> humidity exceeds limit
      <br><i>When</i> detected
      <br><i>Then</i> system generates alert
      <br><br>
      <div style="text-align: center;">
        <b>Scenario 2: Normal humidity</b>
      </div>
          <i>Given</i> normal values
      <br><i>When</i> monitoring
      <br><i>Then</i> no alert is generated
    </td>
  </tr>
</table>

<br><br>

<!-- ===================== HU20 ===================== -->
<table style="margin: auto; table-layout: fixed; width: 80%;">
  <tr style="background-color: #d9d9d9;">
    <td>
      <b>Number:</b>
    </td>
    <td style="text-align: center;">
      HU20
    </td>
    <td>
      <b>User:</b>
    </td>
    <td style="text-align: center;">
      Operator
    </td>
  </tr>
  <tr>
    <td>
      <b>Story Name:</b>
    </td>
    <td style="text-align: center;" colspan="3">
      View alerts list
    </td>
  </tr>
  <tr>
    <td>
      <b>Business Priority:</b>
    </td>
    <td colspan="3">
      High
    </td>
  </tr>
  <tr>
    <td>
      <b>Developer:</b>
    </td>
    <td colspan="3">
      To be defined
    </td>
  </tr>
  <tr>
    <td>
      <b>Description:</b>
    </td>
    <td style="text-align: justify;" colspan="3">
      <i>As a</i> Operator, <i>I want to</i> see a list of alerts <i>so</i> I manage incidents
    </td>
  </tr>
  <tr>
    <td>
      <b>Acceptance Criteria:</b>
    </td>
    <td style="text-align: justify;" colspan="3">
      <div style="text-align: center;">
        <b>Scenario 1: Show alerts</b>
      </div>
          <i>Given</i> existing alerts
      <br><i>When</i> opening list
      <br><i>Then</i> system displays alerts
      <br><br>
      <div style="text-align: center;">
        <b>Scenario 2: No alerts</b>
      </div>
          <i>Given</i> no alerts
      <br><i>When</i> opening
      <br><i>Then</i> system shows empty message
    </td>
  </tr>
</table>

<div style="page-break-after: always;"></div>

<!-- ===================== HU21 ===================== -->
<table style="margin: auto; table-layout: fixed; width: 80%;">
  <tr style="background-color: #d9d9d9;">
    <td>
      <b>Number:</b>
    </td>
    <td style="text-align: center;">
      HU21
    </td>
    <td>
      <b>User:</b>
    </td>
    <td style="text-align: center;">
      Operator
    </td>
  </tr>
  <tr>
    <td>
      <b>Story Name:</b>
    </td>
    <td style="text-align: center;" colspan="3">
      View alert details
    </td>
  </tr>
  <tr>
    <td>
      <b>Business Priority:</b>
    </td>
    <td colspan="3">
      High
    </td>
  </tr>
  <tr>
    <td>
      <b>Developer:</b>
    </td>
    <td colspan="3">
      To be defined
    </td>
  </tr>
  <tr>
    <td>
      <b>Description:</b>
    </td>
    <td style="text-align: justify;" colspan="3">
      <i>As a</i> Operator, <i>I want to</i> view alert details <i>so</i> I understand the issue
    </td>
  </tr>
  <tr>
    <td>
      <b>Acceptance Criteria:</b>
    </td>
    <td style="text-align: justify;" colspan="3">
      <div style="text-align: center;">
        <b>Scenario 1: Show details</b>
      </div>
          <i>Given</i> an alert selected
      <br><i>When</i> opening it
      <br><i>Then</i> system shows equipment, value and time
      <br><br>
      <div style="text-align: center;">
        <b>Scenario 2: Invalid alert</b>
      </div>
          <i>Given</i> alert does not exist
      <br><i>When</i> opening
      <br><i>Then</i> system shows error
    </td>
  </tr>
</table>

<br><br>

<!-- ===================== HU22 ===================== -->
<table style="margin: auto; table-layout: fixed; width: 80%;">
  <tr style="background-color: #d9d9d9;">
    <td>
      <b>Number:</b>
    </td>
    <td style="text-align: center;">
      HU22
    </td>
    <td>
      <b>User:</b>
    </td>
    <td style="text-align: center;">
      Operator
    </td>
  </tr>
  <tr>
    <td>
      <b>Story Name:</b>
    </td>
    <td style="text-align: center;" colspan="3">
      Acknowledge alert
    </td>
  </tr>
  <tr>
    <td>
      <b>Business Priority:</b>
    </td>
    <td colspan="3">
      High
    </td>
  </tr>
  <tr>
    <td>
      <b>Developer:</b>
    </td>
    <td colspan="3">
      To be defined
    </td>
  </tr>
  <tr>
    <td>
      <b>Description:</b>
    </td>
    <td style="text-align: justify;" colspan="3">
      <i>As a</i> Operator, <i>I want to</i> mark an alert as handled <i>so</i> I track actions
    </td>
  </tr>
  <tr>
    <td>
      <b>Acceptance Criteria:</b>
    </td>
    <td style="text-align: justify;" colspan="3">
      <div style="text-align: center;">
        <b>Scenario 1: Mark as handled</b>
      </div>
          <i>Given</i> an active alert
      <br><i>When</i> marking as handled
      <br><i>Then</i> system updates status
      <br><br>
      <div style="text-align: center;">
        <b>Scenario 2: Already handled</b>
      </div>
          <i>Given</i> alert already handled
      <br><i>When</i> updating
      <br><i>Then</i> system keeps status
    </td>
  </tr>
</table>

<div style="page-break-after: always;"></div>

<!-- ===================== HU23 ===================== -->
<table style="margin: auto; table-layout: fixed; width: 80%;">
  <tr style="background-color: #d9d9d9;">
    <td>
      <b>Number:</b>
    </td>
    <td style="text-align: center;">
      HU23
    </td>
    <td>
      <b>User:</b>
    </td>
    <td style="text-align: center;">
      Operator
    </td>
  </tr>
  <tr>
    <td>
      <b>Story Name:</b>
    </td>
    <td style="text-align: center;" colspan="3">
      View alerts sorted by severity
    </td>
  </tr>
  <tr>
    <td>
      <b>Business Priority:</b>
    </td>
    <td colspan="3">
      Medium
    </td>
  </tr>
  <tr>
    <td>
      <b>Developer:</b>
    </td>
    <td colspan="3">
      To be defined
    </td>
  </tr>
  <tr>
    <td>
      <b>Description:</b>
    </td>
    <td style="text-align: justify;" colspan="3">
      <i>As a</i> Operator, <i>I want to</i> see alerts sorted by severity <i>so</i> I prioritize work
    </td>
  </tr>
  <tr>
    <td>
      <b>Acceptance Criteria:</b>
    </td>
    <td style="text-align: justify;" colspan="3">
      <div style="text-align: center;">
        <b>Scenario 1: Sorted alerts</b>
      </div>
          <i>Given</i> multiple alerts
      <br><i>When</i> viewing list
      <br><i>Then</i> system orders by severity
      <br><br>
      <div style="text-align: center;">
        <b>Scenario 2: Same severity</b>
      </div>
          <i>Given</i> equal severity
      <br><i>When</i> viewing
      <br><i>Then</i> system keeps default order
    </td>
  </tr>
</table>

<br><br>

<!-- ===================== HU24 ===================== -->
<table style="margin: auto; table-layout: fixed; width: 80%;">
  <tr style="background-color: #d9d9d9;">
    <td>
      <b>Number:</b>
    </td>
    <td style="text-align: center;">
      HU24
    </td>
    <td>
      <b>User:</b>
    </td>
    <td style="text-align: center;">
      Operator
    </td>
  </tr>
  <tr>
    <td>
      <b>Story Name:</b>
    </td>
    <td style="text-align: center;" colspan="3">
      Receive alerts on mobile device
    </td>
  </tr>
  <tr>
    <td>
      <b>Business Priority:</b>
    </td>
    <td colspan="3">
      High
    </td>
  </tr>
  <tr>
    <td>
      <b>Developer:</b>
    </td>
    <td colspan="3">
      To be defined
    </td>
  </tr>
  <tr>
    <td>
      <b>Description:</b>
    </td>
    <td style="text-align: justify;" colspan="3">
      <i>As a</i> Operator, <i>I want to</i> receive alerts on my phone <i>so</i> I respond quickly
    </td>
  </tr>
  <tr>
    <td>
      <b>Acceptance Criteria:</b>
    </td>
    <td style="text-align: justify;" colspan="3">
      <div style="text-align: center;">
        <b>Scenario 1: Alert notification</b>
      </div>
          <i>Given</i> alert triggered
      <br><i>When</i> system detects it
      <br><i>Then</i> notification is sent
      <br><br>
      <div style="text-align: center;">
        <b>Scenario 2: No connection</b>
      </div>
          <i>Given</i> no network
      <br><i>When</i> sending alert
      <br><i>Then</i> system retries later
    </td>
  </tr>
</table>

<div style="page-break-after: always;"></div>

<!-- ===================== HU25 ===================== -->
<table style="margin: auto; table-layout: fixed; width: 80%;">
  <tr style="background-color: #d9d9d9;">
    <td>
      <b>Number:</b>
    </td>
    <td style="text-align: center;">
      HU25
    </td>
    <td>
      <b>User:</b>
    </td>
    <td style="text-align: center;">
      Supervisor
    </td>
  </tr>
  <tr>
    <td>
      <b>Story Name:</b>
    </td>
    <td style="text-align: center;" colspan="3">
      Set alert limits per equipment
    </td>
  </tr>
  <tr>
    <td>
      <b>Business Priority:</b>
    </td>
    <td colspan="3">
      High
    </td>
  </tr>
  <tr>
    <td>
      <b>Developer:</b>
    </td>
    <td colspan="3">
      To be defined
    </td>
  </tr>
  <tr>
    <td>
      <b>Description:</b>
    </td>
    <td style="text-align: justify;" colspan="3">
      <i>As a</i> Supervisor, <i>I want to</i> define temperature and humidity limits <i>so</i> alerts trigger automatically
    </td>
  </tr>
  <tr>
    <td>
      <b>Acceptance Criteria:</b>
    </td>
    <td style="text-align: justify;" colspan="3">
      <div style="text-align: center;">
        <b>Scenario 1: Save limits</b>
      </div>
          <i>Given</i> valid limits
      <br><i>When</i> saving
      <br><i>Then</i> system stores values
      <br><br>
      <div style="text-align: center;">
        <b>Scenario 2: Invalid limits</b>
      </div>
          <i>Given</i> incorrect values
      <br><i>When</i> saving
      <br><i>Then</i> system shows error
    </td>
  </tr>
</table>

<br><br>

<!-- ===================== HU26 ===================== -->
<table style="margin: auto; table-layout: fixed; width: 80%;">
  <tr style="background-color: #d9d9d9;">
    <td>
      <b>Number:</b>
    </td>
    <td style="text-align: center;">
      HU25
    </td>
    <td>
      <b>User:</b>
    </td>
    <td style="text-align: center;">
      Supervisor
    </td>
  </tr>
  <tr>
    <td>
      <b>Story Name:</b>
    </td>
    <td style="text-align: center;" colspan="3">
      Set alert limits per equipment
    </td>
  </tr>
  <tr>
    <td>
      <b>Business Priority:</b>
    </td>
    <td colspan="3">
      High
    </td>
  </tr>
  <tr>
    <td>
      <b>Developer:</b>
    </td>
    <td colspan="3">
      To be defined
    </td>
  </tr>
  <tr>
    <td>
      <b>Description:</b>
    </td>
    <td style="text-align: justify;" colspan="3">
      <i>As a</i> Supervisor, <i>I want to</i> define temperature and humidity limits <i>so</i> alerts trigger automatically
    </td>
  </tr>
  <tr>
    <td>
      <b>Acceptance Criteria:</b>
    </td>
    <td style="text-align: justify;" colspan="3">
      <div style="text-align: center;">
        <b>Scenario 1: Save limits</b>
      </div>
          <i>Given</i> valid limits
      <br><i>When</i> saving
      <br><i>Then</i> system stores values
      <br><br>
      <div style="text-align: center;">
        <b>Scenario 2: Invalid limits</b>
      </div>
          <i>Given</i> incorrect values
      <br><i>When</i> saving
      <br><i>Then</i> system shows error
    </td>
  </tr>
</table>

<div style="page-break-after: always;"></div>

<!-- ===================== HU27 ===================== -->
<table style="margin: auto; table-layout: fixed; width: 80%;">
  <tr style="background-color: #d9d9d9;">
    <td>
      <b>Number:</b>
    </td>
    <td style="text-align: center;">
      HU27
    </td>
    <td>
      <b>User:</b>
    </td>
    <td style="text-align: center;">
      Supervisor
    </td>
  </tr>
  <tr>
    <td>
      <b>Story Name:</b>
    </td>
    <td style="text-align: center;" colspan="3">
      View historical data
    </td>
  </tr>
  <tr>
    <td>
      <b>Business Priority:</b>
    </td>
    <td colspan="3">
      High
    </td>
  </tr>
  <tr>
    <td>
      <b>Developer:</b>
    </td>
    <td colspan="3">
      To be defined
    </td>
  </tr>
  <tr>
    <td>
      <b>Description:</b>
    </td>
    <td style="text-align: justify;" colspan="3">
      <i>As a</i> Supervisor, <i>I want to</i> view historical data <i>so</i> I analyze trends
    </td>
  </tr>
  <tr>
    <td>
      <b>Acceptance Criteria:</b>
    </td>
    <td style="text-align: justify;" colspan="3">
      <div style="text-align: center;">
        <b>Scenario 1: Show history</b>
      </div>
              <i>Given</i> stored data
      <br><i>When</i> selecting equipment
      <br><i>Then</i> system displays history      <br><br>
      <div style="text-align: center;">
        <b>Scenario 2: No history</b>
      </div>
              <i>Given</i> no data
      <br><i>When</i> viewing
      <br><i>Then</i> system shows empty message
    </td>
  </tr>
</table>

<br><br>

<!-- ===================== HU28 ===================== -->
<table style="margin: auto; table-layout: fixed; width: 80%;">
  <tr style="background-color: #d9d9d9;">
    <td>
      <b>Number:</b>
    </td>
    <td style="text-align: center;">
      HU28
    </td>
    <td>
      <b>User:</b>
    </td>
    <td style="text-align: center;">
      Supervisor
    </td>
  </tr>
  <tr>
    <td>
      <b>Story Name:</b>
    </td>
    <td style="text-align: center;" colspan="3">
      Select date range for data
    </td>
  </tr>
  <tr>
    <td>
      <b>Business Priority:</b>
    </td>
    <td colspan="3">
      Medium
    </td>
  </tr>
  <tr>
    <td>
      <b>Developer:</b>
    </td>
    <td colspan="3">
      To be defined
    </td>
  </tr>
  <tr>
    <td>
      <b>Description:</b>
    </td>
    <td style="text-align: justify;" colspan="3">
      <i>As a</i> Supervisor, <i>I want to</i> select a date range <i>so</i> I filter data
    </td>
  </tr>
  <tr>
    <td>
      <b>Acceptance Criteria:</b>
    </td>
    <td style="text-align: justify;" colspan="3">
      <div style="text-align: center;">
        <b>Scenario 1: Apply filter</b>
      </div>
          <i>Given</i> selected dates
      <br><i>When</i> applying filter
      <br><i>Then</i> system shows filtered data
      <br><br>
      <div style="text-align: center;">
        <b>Scenario 2: Invalid range</b>
      </div>
          <i>Given</i> wrong dates
      <br><i>When</i> applying
      <br><i>Then</i> system shows error
    </td>
  </tr>
</table>

<div style="page-break-after: always;"></div>

<!-- ===================== HU29 ===================== -->
<table style="margin: auto; table-layout: fixed; width: 80%;">
  <tr style="background-color: #d9d9d9;">
    <td>
      <b>Number:</b>
    </td>
    <td style="text-align: center;">
      HU29
    </td>
    <td>
      <b>User:</b>
    </td>
    <td style="text-align: center;">
      Supervisor
    </td>
  </tr>
  <tr>
    <td>
      <b>Story Name:</b>
    </td>
    <td style="text-align: center;" colspan="3">
      Compare data between periods
    </td>
  </tr>
  <tr>
    <td>
      <b>Business Priority:</b>
    </td>
    <td colspan="3">
      Medium
    </td>
  </tr>
  <tr>
    <td>
      <b>Developer:</b>
    </td>
    <td colspan="3">
      To be defined
    </td>
  </tr>
  <tr>
    <td>
      <b>Description:</b>
    </td>
    <td style="text-align: justify;" colspan="3">
      <i>As a</i> Supervisor, <i>I want to</i> compare data between periods <i>so</i> I detect changes
    </td>
  </tr>
  <tr>
    <td>
      <b>Acceptance Criteria:</b>
    </td>
    <td style="text-align: justify;" colspan="3">
      <div style="text-align: center;">
        <b>Scenario 1: Compare data</b>
      </div>
          <i>Given</i> two periods selected
      <br><i>When</i> comparing
      <br><i>Then</i> system shows both results
      <br><br>
      <div style="text-align: center;">
        <b>Scenario 2: Missing selection</b>
      </div>
          <i>Given</i> incomplete data
      <br><i>When</i> comparing
      <br><i>Then</i> system shows error
    </td>
  </tr>
</table>

<br><br>

<!-- ===================== HU30 ===================== -->
<table style="margin: auto; table-layout: fixed; width: 80%;">
  <tr style="background-color: #d9d9d9;">
    <td>
      <b>Number:</b>
    </td>
    <td style="text-align: center;">
      HU30
    </td>
    <td>
      <b>User:</b>
    </td>
    <td style="text-align: center;">
      Supervisor
    </td>
  </tr>
  <tr>
    <td>
      <b>Story Name:</b>
    </td>
    <td style="text-align: center;" colspan="3">
      Generate report by equipment and date
    </td>
  </tr>
  <tr>
    <td>
      <b>Business Priority:</b>
    </td>
    <td colspan="3">
      High
    </td>
  </tr>
  <tr>
    <td>
      <b>Developer:</b>
    </td>
    <td colspan="3">
      To be defined
    </td>
  </tr>
  <tr>
    <td>
      <b>Description:</b>
    </td>
    <td style="text-align: justify;" colspan="3">
      <i>As a</i> Supervisor, <i>I want to</i> generate reports <i>so</i> I validate compliance
    </td>
  </tr>
  <tr>
    <td>
      <b>Acceptance Criteria:</b>
    </td>
    <td style="text-align: justify;" colspan="3">
      <div style="text-align: center;">
        <b>Scenario 1: Generate report</b>
      </div>
          <i>Given</i> selected equipment and date
      <br><i>When</i> generating
      <br><i>Then</i> system creates report
      <br><br>
      <div style="text-align: center;">
        <b>Scenario 2: Missing data</b>
      </div>
          <i>Given</i> incomplete fields
      <br><i>When</i> generating
      <br><i>Then</i> system shows error
    </td>
  </tr>
</table>

<div style="page-break-after: always;"></div>

<!-- ===================== HU31 ===================== -->
<table style="margin: auto; table-layout: fixed; width: 80%;">
  <tr style="background-color: #d9d9d9;">
    <td>
      <b>Number:</b>
    </td>
    <td style="text-align: center;">
      HU31
    </td>
    <td>
      <b>User:</b>
    </td>
    <td style="text-align: center;">
      Supervisor
    </td>
  </tr>
  <tr>
    <td>
      <b>Story Name:</b>
    </td>
    <td style="text-align: center;" colspan="3">
      Download report file
    </td>
  </tr>
  <tr>
    <td>
      <b>Business Priority:</b>
    </td>
    <td colspan="3">
      High
    </td>
  </tr>
  <tr>
    <td>
      <b>Developer:</b>
    </td>
    <td colspan="3">
      To be defined
    </td>
  </tr>
  <tr>
    <td>
      <b>Description:</b>
    </td>
    <td style="text-align: justify;" colspan="3">
      <i>As a</i> Supervisor, <i>I want to</i> download generated reports <i>so</i> I can share them
    </td>
  </tr>
  <tr>
    <td>
      <b>Acceptance Criteria:</b>
    </td>
    <td style="text-align: justify;" colspan="3">
      <div style="text-align: center;">
        <b>Scenario 1: Download report</b>
      </div>
          <i>Given</i> a generated report
      <br><i>When</i> downloading
      <br><i>Then</i> file is saved locally
      <br><br>
      <div style="text-align: center;">
        <b>Scenario 2: No report</b>
      </div>
          <i>Given</i> no report generated
      <br><i>When</i> downloading
      <br><i>Then</i> system shows error
    </td>
  </tr>
</table>

<br><br>

<!-- ===================== HU32 ===================== -->
<table style="margin: auto; table-layout: fixed; width: 80%;">
  <tr style="background-color: #d9d9d9;">
    <td>
      <b>Number:</b>
    </td>
    <td style="text-align: center;">
      HU32
    </td>
    <td>
      <b>User:</b>
    </td>
    <td style="text-align: center;">
      Supervisor
    </td>
  </tr>
  <tr>
    <td>
      <b>Story Name:</b>
    </td>
    <td style="text-align: center;" colspan="3">
      View incident history
    </td>
  </tr>
  <tr>
    <td>
      <b>Business Priority:</b>
    </td>
    <td colspan="3">
      High
    </td>
  </tr>
  <tr>
    <td>
      <b>Developer:</b>
    </td>
    <td colspan="3">
      To be defined
    </td>
  </tr>
  <tr>
    <td>
      <b>Description:</b>
    </td>
    <td style="text-align: justify;" colspan="3">
      <i>As a</i> Supervisor, <i>I want to</i> view past alerts <i>so</i> I evaluate performance
    </td>
  </tr>
  <tr>
    <td>
      <b>Acceptance Criteria:</b>
    </td>
    <td style="text-align: justify;" colspan="3">
      <div style="text-align: center;">
        <b>Scenario 1: Show incidents</b>
      </div>
          <i>Given</i> stored alerts
      <br><i>When</i> viewing history
      <br><i>Then</i> system displays alerts
      <br><br>
      <div style="text-align: center;">
        <b>Scenario 2: No incidents</b>
      </div>
          <i>Given</i> no alerts
      <br><i>When</i> viewing
      <br><i>Then</i> system shows empty message
    </td>
  </tr>
</table>

<div style="page-break-after: always;"></div>

<!-- ===================== HU33 ===================== -->
<table style="margin: auto; table-layout: fixed; width: 80%;">
  <tr style="background-color: #d9d9d9;">
    <td>
      <b>Number:</b>
    </td>
    <td style="text-align: center;">
      HU33
    </td>
    <td>
      <b>User:</b>
    </td>
    <td style="text-align: center;">
      Supervisor
    </td>
  </tr>
  <tr>
    <td>
      <b>Story Name:</b>
    </td>
    <td style="text-align: center;" colspan="3">
      Export data file
    </td>
  </tr>
  <tr>
    <td>
      <b>Business Priority:</b>
    </td>
    <td colspan="3">
      Medium
    </td>
  </tr>
  <tr>
    <td>
      <b>Developer:</b>
    </td>
    <td colspan="3">
      To be defined
    </td>
  </tr>
  <tr>
    <td>
      <b>Description:</b>
    </td>
    <td style="text-align: justify;" colspan="3">
      <i>As a</i> Supervisor, <i>I want to</i> export data <i>so</i> I can use it outside the system
    </td>
  </tr>
  <tr>
    <td>
      <b>Acceptance Criteria:</b>
    </td>
    <td style="text-align: justify;" colspan="3">
      <div style="text-align: center;">
        <b>Scenario 1: Export data</b>
      </div>
          <i>Given</i> available data
      <br><i>When</i> exporting
      <br><i>Then</i> file is generated
      <br><br>
      <div style="text-align: center;">
        <b>Scenario 2: No data</b>
      </div>
          <i>Given</i> empty data
      <br><i>When</i> exporting
      <br><i>Then</i> system shows error
    </td>
  </tr>
</table>

<br><br>

<!-- ===================== HU34 ===================== -->
<table style="margin: auto; table-layout: fixed; width: 80%;">
  <tr style="background-color: #d9d9d9;">
    <td>
      <b>Number:</b>
    </td>
    <td style="text-align: center;">
      HU34
    </td>
    <td>
      <b>User:</b>
    </td>
    <td style="text-align: center;">
      Supervisor
    </td>
  </tr>
  <tr>
    <td>
      <b>Story Name:</b>
    </td>
    <td style="text-align: center;" colspan="3">
      Compare weekly and monthly data
    </td>
  </tr>
  <tr>
    <td>
      <b>Business Priority:</b>
    </td>
    <td colspan="3">
      Medium
    </td>
  </tr>
  <tr>
    <td>
      <b>Developer:</b>
    </td>
    <td colspan="3">
      To be defined
    </td>
  </tr>
  <tr>
    <td>
      <b>Description:</b>
    </td>
    <td style="text-align: justify;" colspan="3">
      <i>As a</i> Supervisor, <i>I want to</i> compare weekly and monthly data <i>so</i> I detect variations
    </td>
  </tr>
  <tr>
    <td>
      <b>Acceptance Criteria:</b>
    </td>
    <td style="text-align: justify;" colspan="3">
      <div style="text-align: center;">
        <b>Scenario 1: Compare data</b>
      </div>
          <i>Given</i> selected week and month
      <br><i>When</i> comparing
      <br><i>Then</i> system shows both values
      <br><br>
      <div style="text-align: center;">
        <b>Scenario 2: Missing selection</b>
      </div>
          <i>Given</i> incomplete selection
      <br><i>When</i> comparing
      <br><i>Then</i> system shows error
    </td>
  </tr>
</table>

<div style="page-break-after: always;"></div>

<!-- ===================== HU35 ===================== -->
<table style="margin: auto; table-layout: fixed; width: 80%;">
  <tr style="background-color: #d9d9d9;">
    <td>
      <b>Number:</b>
    </td>
    <td style="text-align: center;">
      HU35
    </td>
    <td>
      <b>User:</b>
    </td>
    <td style="text-align: center;">
      Supervisor
    </td>
  </tr>
  <tr>
    <td>
      <b>Story Name:</b>
    </td>
    <td style="text-align: center;" colspan="3">
      View equipment condition
    </td>
  </tr>
  <tr>
    <td>
      <b>Business Priority:</b>
    </td>
    <td colspan="3">
      High
    </td>
  </tr>
  <tr>
    <td>
      <b>Developer:</b>
    </td>
    <td colspan="3">
      To be defined
    </td>
  </tr>
  <tr>
    <td>
      <b>Description:</b>
    </td>
    <td style="text-align: justify;" colspan="3">
      <i>As a</i> Supervisor, <i>I want to</i> see if equipment is working correctly <i>so</i> I prevent failures
    </td>
  </tr>
  <tr>
    <td>
      <b>Acceptance Criteria:</b>
    </td>
    <td style="text-align: justify;" colspan="3">
      <div style="text-align: center;">
        <b>Scenario 1: Working condition</b>
      </div>
          <i>Given</i> equipment functioning
      <br><i>When</i> viewing
      <br><i>Then</i> system shows normal status
      <br><br>
      <div style="text-align: center;">
        <b>Scenario 2: Issue detected</b>
      </div>
          <i>Given</i> abnormal condition
      <br><i>When</i> viewing
      <br><i>Then</i> system shows warning
    </td>
  </tr>
</table>

<br><br>

<!-- ===================== HU36 ===================== -->
<table style="margin: auto; table-layout: fixed; width: 80%;">
  <tr style="background-color: #d9d9d9;">
    <td>
      <b>Number:</b>
    </td>
    <td style="text-align: center;">
      HU36
    </td>
    <td>
      <b>User:</b>
    </td>
    <td style="text-align: center;">
      Operator
    </td>
  </tr>
  <tr>
    <td>
      <b>Story Name:</b>
    </td>
    <td style="text-align: center;" colspan="3">
      View abnormal values
    </td>
  </tr>
  <tr>
    <td>
      <b>Business Priority:</b>
    </td>
    <td colspan="3">
      High
    </td>
  </tr>
  <tr>
    <td>
      <b>Developer:</b>
    </td>
    <td colspan="3">
      To be defined
    </td>
  </tr>
  <tr>
    <td>
      <b>Description:</b>
    </td>
    <td style="text-align: justify;" colspan="3">
      <i>As a</i> Operator, <i>I want to</i> see values outside limits <i>so</i> I detect problems
    </td>
  </tr>
  <tr>
    <td>
      <b>Acceptance Criteria:</b>
    </td>
    <td style="text-align: justify;" colspan="3">
      <div style="text-align: center;">
        <b>Scenario 1: Abnormal detected</b>
      </div>
          <i>Given</i> values exceed limits
      <br><i>When</i> viewing
      <br><i>Then</i> system highlights them
      <br><br>
      <div style="text-align: center;">
        <b>Scenario 2: Normal values</b>
      </div>
          <i>Given</i> normal values
      <br><i>When</i> viewing
      <br><i>Then</i> no warning appears
    </td>
  </tr>
</table>

<div style="page-break-after: always;"></div>

<!-- ===================== HU37 ===================== -->
<table style="margin: auto; table-layout: fixed; width: 80%;">
  <tr style="background-color: #d9d9d9;">
    <td>
      <b>Number:</b>
    </td>
    <td style="text-align: center;">
      HU37
    </td>
    <td>
      <b>User:</b>
    </td>
    <td style="text-align: center;">
      Operator
    </td>
  </tr>
  <tr>
    <td>
      <b>Story Name:</b>
    </td>
    <td style="text-align: center;" colspan="3">
      Receive equipment warning alerts
    </td>
  </tr>
  <tr>
    <td>
      <b>Business Priority:</b>
    </td>
    <td colspan="3">
      High
    </td>
  </tr>
  <tr>
    <td>
      <b>Developer:</b>
    </td>
    <td colspan="3">
      To be defined
    </td>
  </tr>
  <tr>
    <td>
      <b>Description:</b>
    </td>
    <td style="text-align: justify;" colspan="3">
      <i>As a</i> Operator, <i>I want to</i> receive warnings <i>so</i> I prevent failures
    </td>
  </tr>
  <tr>
    <td>
      <b>Acceptance Criteria:</b>
    </td>
    <td style="text-align: justify;" colspan="3">
      <div style="text-align: center;">
        <b>Scenario 1: Warning triggered</b>
      </div>
          <i>Given</i> abnormal condition
      <br><i>When</i> detected
      <br><i>Then</i> system sends warning
      <br><br>
      <div style="text-align: center;">
        <b>Scenario 2: Normal operation</b>
      </div>
          <i>Given</i> normal values
      <br><i>When</i> monitoring
      <br><i>Then</i> no warning is sent
    </td>
  </tr>
</table>

<br><br>

<!-- ===================== HU38 ===================== -->
<table style="margin: auto; table-layout: fixed; width: 80%;">
  <tr style="background-color: #d9d9d9;">
    <td>
      <b>Number:</b>
    </td>
    <td style="text-align: center;">
      HU38
    </td>
    <td>
      <b>User:</b>
    </td>
    <td style="text-align: center;">
      Supervisor
    </td>
  </tr>
  <tr>
    <td>
      <b>Story Name:</b>
    </td>
    <td style="text-align: center;" colspan="3">
      View equipment performance data
    </td>
  </tr>
  <tr>
    <td>
      <b>Business Priority:</b>
    </td>
    <td colspan="3">
      Medium
    </td>
  </tr>
  <tr>
    <td>
      <b>Developer:</b>
    </td>
    <td colspan="3">
      To be defined
    </td>
  </tr>
  <tr>
    <td>
      <b>Description:</b>
    </td>
    <td style="text-align: justify;" colspan="3">
      <i>As a</i> Supervisor, <i>I want to</i> see performance over time <i>so</i> I improve operations
    </td>
  </tr>
  <tr>
    <td>
      <b>Acceptance Criteria:</b>
    </td>
    <td style="text-align: justify;" colspan="3">
      <div style="text-align: center;">
        <b>Scenario 1: Show performance</b>
      </div>
          <i>Given</i> stored data
      <br><i>When</i> viewing
      <br><i>Then</i> system displays performance trend
      <br><br>
      <div style="text-align: center;">
        <b>Scenario 2: No data</b>
      </div>
          <i>Given</i> no data
      <br><i>When</i> viewing
      <br><i>Then</i> system shows empty message
    </td>
  </tr>
</table>

<div style="page-break-after: always;"></div>

<!-- ===================== HU39 ===================== -->
<table style="margin: auto; table-layout: fixed; width: 80%;">
  <tr style="background-color: #d9d9d9;">
    <td>
      <b>Number:</b>
    </td>
    <td style="text-align: center;">
      HU39
    </td>
    <td>
      <b>User:</b>
    </td>
    <td style="text-align: center;">
      Supervisor
    </td>
  </tr>
  <tr>
    <td>
      <b>Story Name:</b>
    </td>
    <td style="text-align: center;" colspan="3">
      View equipment usage data
    </td>
  </tr>
  <tr>
    <td>
      <b>Business Priority:</b>
    </td>
    <td colspan="3">
      Medium
    </td>
  </tr>
  <tr>
    <td>
      <b>Developer:</b>
    </td>
    <td colspan="3">
      To be defined
    </td>
  </tr>
  <tr>
    <td>
      <b>Description:</b>
    </td>
    <td style="text-align: justify;" colspan="3">
      <i>As a</i> Supervisor, <i>I want to</i> see usage data <i>so</i> I manage resources
    </td>
  </tr>
  <tr>
    <td>
      <b>Acceptance Criteria:</b>
    </td>
    <td style="text-align: justify;" colspan="3">
      <div style="text-align: center;">
        <b>Scenario 1: Show usage</b>
      </div>
          <i>Given</i> usage data exists
      <br><i>When</i> viewing
      <br><i>Then</i> system displays usage
      <br><br>
      <div style="text-align: center;">
        <b>Scenario 2: No data</b>
      </div>
          <i>Given</i> no usage data
      <br><i>When</i> viewing
      <br><i>Then</i> system shows empty message
    </td>
  </tr>
</table>

<br><br>

<!-- ===================== HU40 ===================== -->
<table style="margin: auto; table-layout: fixed; width: 80%;">
  <tr style="background-color: #d9d9d9;">
    <td>
      <b>Number:</b>
    </td>
    <td style="text-align: center;">
      HU40
    </td>
    <td>
      <b>User:</b>
    </td>
    <td style="text-align: center;">
      Supervisor
    </td>
  </tr>
  <tr>
    <td>
      <b>Story Name:</b>
    </td>
    <td style="text-align: center;" colspan="3">
      Register maintenance record
    </td>
  </tr>
  <tr>
    <td>
      <b>Business Priority:</b>
    </td>
    <td colspan="3">
      High
    </td>
  </tr>
  <tr>
    <td>
      <b>Developer:</b>
    </td>
    <td colspan="3">
      To be defined
    </td>
  </tr>
  <tr>
    <td>
      <b>Description:</b>
    </td>
    <td style="text-align: justify;" colspan="3">
      <i>As a</i> Supervisor, <i>I want to</i> record maintenance <i>so</i> I track equipment history
    </td>
  </tr>
  <tr>
    <td>
      <b>Acceptance Criteria:</b>
    </td>
    <td style="text-align: justify;" colspan="3">
      <div style="text-align: center;">
        <b>Scenario 1: Save record</b>
      </div>
          <i>Given</i> maintenance data
      <br><i>When</i> saving
      <br><i>Then</i> system stores record
      <br><br>
      <div style="text-align: center;">
        <b>Scenario 2: Missing data</b>
      </div>
          <i>Given</i> incomplete data
      <br><i>When</i> saving
      <br><i>Then</i> system shows error
    </td>
  </tr>
</table>

<div style="page-break-after: always;"></div>

<!-- ===================== HU41 ===================== -->
<table style="margin: auto; table-layout: fixed; width: 80%;">
  <tr style="background-color: #d9d9d9;">
    <td>
      <b>Number:</b>
    </td>
    <td style="text-align: center;">
      HU41
    </td>
    <td>
      <b>User:</b>
    </td>
    <td style="text-align: center;">
      Supervisor
    </td>
  </tr>
  <tr>
    <td>
      <b>Story Name:</b>
    </td>
    <td style="text-align: center;" colspan="3">
      View maintenance history
    </td>
  </tr>
  <tr>
    <td>
      <b>Business Priority:</b>
    </td>
    <td colspan="3">
      High
    </td>
  </tr>
  <tr>
    <td>
      <b>Developer:</b>
    </td>
    <td colspan="3">
      To be defined
    </td>
  </tr>
  <tr>
    <td>
      <b>Description:</b>
    </td>
    <td style="text-align: justify;" colspan="3">
      <i>As a</i> Supervisor, <i>I want to</i> view maintenance records <i>so</i> I ensure reliability
    </td>
  </tr>
  <tr>
    <td>
      <b>Acceptance Criteria:</b>
    </td>
    <td style="text-align: justify;" colspan="3">
      <div style="text-align: center;">
        <b>Scenario 1: Show history</b>
      </div>
          <i>Given</i> maintenance records exist
      <br><i>When</i> viewing history
      <br><i>Then</i> system displays records
      <br><br>
      <div style="text-align: center;">
        <b>Scenario 2: No records</b>
      </div>
          <i>Given</i> no records
      <br><i>When</i> viewing
      <br><i>Then</i> system shows empty message
    </td>
  </tr>
</table>

<br><br>

<!-- ===================== HU42 ===================== -->
<table style="margin: auto; table-layout: fixed; width: 80%;">
  <tr style="background-color: #d9d9d9;">
    <td>
      <b>Number:</b>
    </td>
    <td style="text-align: center;">
      HU42
    </td>
    <td>
      <b>User:</b>
    </td>
    <td style="text-align: center;">
      Supervisor
    </td>
  </tr>
  <tr>
    <td>
      <b>Story Name:</b>
    </td>
    <td style="text-align: center;" colspan="3">
      View equipment reliability
    </td>
  </tr>
  <tr>
    <td>
      <b>Business Priority:</b>
    </td>
    <td colspan="3">
      High
    </td>
  </tr>
  <tr>
    <td>
      <b>Developer:</b>
    </td>
    <td colspan="3">
      To be defined
    </td>
  </tr>
  <tr>
    <td>
      <b>Description:</b>
    </td>
    <td style="text-align: justify;" colspan="3">
      <i>As a</i> Supervisor, <i>I want to</i> see equipment stability over time <i>so</i> I prevent failures
    </td>
  </tr>
  <tr>
    <td>
      <b>Acceptance Criteria:</b>
    </td>
    <td style="text-align: justify;" colspan="3">
      <div style="text-align: center;">
        <b>Scenario 1: Show reliability</b>
      </div>
          <i>Given</i> historical data exists
      <br><i>When</i> viewing
      <br><i>Then</i> system shows stability trend
      <br><br>
      <div style="text-align: center;">
        <b>Scenario 2: No data</b>
      </div>
          <i>Given</i> no data
      <br><i>When</i> viewing
      <br><i>Then</i> system shows empty message
    </td>
  </tr>
</table>

<div style="page-break-after: always;"></div>

<!-- ===================== HU43 ===================== -->
<table style="margin: auto; table-layout: fixed; width: 80%;">
  <tr style="background-color: #d9d9d9;">
    <td>
      <b>Number:</b>
    </td>
    <td style="text-align: center;">
      HU43
    </td>
    <td>
      <b>User:</b>
    </td>
    <td style="text-align: center;">
      Supervisor
    </td>
  </tr>
  <tr>
    <td>
      <b>Story Name:</b>
    </td>
    <td style="text-align: center;" colspan="3">
      View dashboard
    </td>
  </tr>
  <tr>
    <td>
      <b>Business Priority:</b>
    </td>
    <td colspan="3">
      High
    </td>
  </tr>
  <tr>
    <td>
      <b>Developer:</b>
    </td>
    <td colspan="3">
      To be defined
    </td>
  </tr>
  <tr>
    <td>
      <b>Description:</b>
    </td>
    <td style="text-align: justify;" colspan="3">
      <i>As a</i> Supervisor, <i>I want to</i> see key system information <i>so</i> I understand system status
    </td>
  </tr>
  <tr>
    <td>
      <b>Acceptance Criteria:</b>
    </td>
    <td style="text-align: justify;" colspan="3">
      <div style="text-align: center;">
        <b>Scenario 1: Show dashboard</b>
      </div>
          <i>Given</i> system data available
      <br><i>When</i> accessing dashboard
      <br><i>Then</i> system displays key metrics
      <br><br>
      <div style="text-align: center;">
        <b>Scenario 2: No data</b>
      </div>
          <i>Given</i> no data
      <br><i>When</i> accessing
      <br><i>Then</i> system shows empty state
    </td>
  </tr>
</table>

<br><br>

<!-- ===================== HU44 ===================== -->
<table style="margin: auto; table-layout: fixed; width: 80%;">
  <tr style="background-color: #d9d9d9;">
    <td>
      <b>Number:</b>
    </td>
    <td style="text-align: center;">
      HU44
    </td>
    <td>
      <b>User:</b>
    </td>
    <td style="text-align: center;">
      Supervisor
    </td>
  </tr>
  <tr>
    <td>
      <b>Story Name:</b>
    </td>
    <td style="text-align: center;" colspan="3">
      View critical alerts
    </td>
  </tr>
  <tr>
    <td>
      <b>Business Priority:</b>
    </td>
    <td colspan="3">
      High
    </td>
  </tr>
  <tr>
    <td>
      <b>Developer:</b>
    </td>
    <td colspan="3">
      To be defined
    </td>
  </tr>
  <tr>
    <td>
      <b>Description:</b>
    </td>
    <td style="text-align: justify;" colspan="3">
      <i>As a</i> Supervisor, <i>I want to</i> see critical alerts <i>so</i> I act immediately
    </td>
  </tr>
  <tr>
    <td>
      <b>Acceptance Criteria:</b>
    </td>
    <td style="text-align: justify;" colspan="3">
      <div style="text-align: center;">
        <b>Scenario 1: Show critical alerts</b>
      </div>
          <i>Given</i> alerts exist
      <br><i>When</i> filtering by critical
      <br><i>Then</i> system shows critical alerts
      <br><br>
      <div style="text-align: center;">
        <b>Scenario 2: No critical alerts</b>
      </div>
          <i>Given</i> none exist
      <br><i>When</i> viewing
      <br><i>Then</i> system shows empty message
    </td>
  </tr>
</table>

<div style="page-break-after: always;"></div>

<!-- ===================== HU45 ===================== -->
<table style="margin: auto; table-layout: fixed; width: 80%;">
  <tr style="background-color: #d9d9d9;">
    <td>
      <b>Number:</b>
    </td>
    <td style="text-align: center;">
      HU45
    </td>
    <td>
      <b>User:</b>
    </td>
    <td style="text-align: center;">
      Supervisor
    </td>
  </tr>
  <tr>
    <td>
      <b>Story Name:</b>
    </td>
    <td style="text-align: center;" colspan="3">
      View critical alerts
    </td>
  </tr>
  <tr>
    <td>
      <b>Business Priority:</b>
    </td>
    <td colspan="3">
      High
    </td>
  </tr>
  <tr>
    <td>
      <b>Developer:</b>
    </td>
    <td colspan="3">
      To be defined
    </td>
  </tr>
  <tr>
    <td>
      <b>Description:</b>
    </td>
    <td style="text-align: justify;" colspan="3">
      <i>As a</i> Supervisor, <i>I want to</i> see critical alerts <i>so</i> I act immediately
    </td>
  </tr>
  <tr>
    <td>
      <b>Acceptance Criteria:</b>
    </td>
    <td style="text-align: justify;" colspan="3">
      <div style="text-align: center;">
        <b>Scenario 1: Show critical alerts</b>
      </div>
          <i>Given</i> alerts exist
      <br><i>When</i> filtering by critical
      <br><i>Then</i> system shows critical alerts
      <br><br>
      <div style="text-align: center;">
        <b>Scenario 2: No critical alerts</b>
      </div>
          <i>Given</i> none exist
      <br><i>When</i> viewing
      <br><i>Then</i> system shows empty message
    </td>
  </tr>
</table>

<br><br>

<!-- ===================== HU46 ===================== -->
<table style="margin: auto; table-layout: fixed; width: 80%;">
  <tr style="background-color: #d9d9d9;">
    <td>
      <b>Number:</b>
    </td>
    <td style="text-align: center;">
      HU46
    </td>
    <td>
      <b>User:</b>
    </td>
    <td style="text-align: center;">
      Supervisor
    </td>
  </tr>
  <tr>
    <td>
      <b>Story Name:</b>
    </td>
    <td style="text-align: center;" colspan="3">
      View equipment with active alerts
    </td>
  </tr>
  <tr>
    <td>
      <b>Business Priority:</b>
    </td>
    <td colspan="3">
      High
    </td>
  </tr>
  <tr>
    <td>
      <b>Developer:</b>
    </td>
    <td colspan="3">
      To be defined
    </td>
  </tr>
  <tr>
    <td>
      <b>Description:</b>
    </td>
    <td style="text-align: justify;" colspan="3">
      <i>As a</i> Supervisor, <i>I want to</i> see equipment with active alerts <i>so</i> I focus on issues
    </td>
  </tr>
  <tr>
    <td>
      <b>Acceptance Criteria:</b>
    </td>
    <td style="text-align: justify;" colspan="3">
      <div style="text-align: center;">
        <b>Scenario 1: Show affected equipment</b>
      </div>
          <i>Given</i> alerts exist
      <br><i>When</i> filtering
      <br><i>Then</i> system shows affected equipment
      <br><br>
      <div style="text-align: center;">
        <b>Scenario 2: No alerts</b>
      </div>
          <i>Given</i> none exist
      <br><i>When</i> filtering
      <br><i>Then</i> system shows empty message
    </td>
  </tr>
</table>

<div style="page-break-after: always;"></div>

<!-- ===================== HU47 ===================== -->
<table style="margin: auto; table-layout: fixed; width: 80%;">
  <tr style="background-color: #d9d9d9;">
    <td>
      <b>Number:</b>
    </td>
    <td style="text-align: center;">
      HU47
    </td>
    <td>
      <b>User:</b>
    </td>
    <td style="text-align: center;">
      Operator
    </td>
  </tr>
  <tr>
    <td>
      <b>Story Name:</b>
    </td>
    <td style="text-align: center;" colspan="3">
      View equipment without recent data
    </td>
  </tr>
  <tr>
    <td>
      <b>Business Priority:</b>
    </td>
    <td colspan="3">
      High
    </td>
  </tr>
  <tr>
    <td>
      <b>Developer:</b>
    </td>
    <td colspan="3">
      To be defined
    </td>
  </tr>
  <tr>
    <td>
      <b>Description:</b>
    </td>
    <td style="text-align: justify;" colspan="3">
      <i>As a</i> Operator, <i>I want to</i> identify equipment without recent data <i>so</i> I act quickly
    </td>
  </tr>
  <tr>
    <td>
      <b>Acceptance Criteria:</b>
    </td>
    <td style="text-align: justify;" colspan="3">
      <div style="text-align: center;">
        <b>Scenario 1: Show missing data</b>
      </div>
          <i>Given</i> no recent data
      <br><i>When</i> viewing
      <br><i>Then</i> system highlights equipment
      <br><br>
      <div style="text-align: center;">
        <b>Scenario 2: Normal data</b>
      </div>
          <i>Given</i> data exists
      <br><i>When</i> viewing
      <br><i>Then</i> no warning is shown
    </td>
  </tr>
</table>

<br><br>

<!-- ===================== HU48 ===================== -->
<table style="margin: auto; table-layout: fixed; width: 80%;">
  <tr style="background-color: #d9d9d9;">
    <td>
      <b>Number:</b>
    </td>
    <td style="text-align: center;">
      HU48
    </td>
    <td>
      <b>User:</b>
    </td>
    <td style="text-align: center;">
      Supervisor
    </td>
  </tr>
  <tr>
    <td>
      <b>Story Name:</b>
    </td>
    <td style="text-align: center;" colspan="3">
      View alert trends
    </td>
  </tr>
  <tr>
    <td>
      <b>Business Priority:</b>
    </td>
    <td colspan="3">
      Medium
    </td>
  </tr>
  <tr>
    <td>
      <b>Developer:</b>
    </td>
    <td colspan="3">
      To be defined
    </td>
  </tr>
  <tr>
    <td>
      <b>Description:</b>
    </td>
    <td style="text-align: justify;" colspan="3">
      <i>As a</i> Supervisor, <i>I want to</i> see alert trends <i>so</i> I improve processes
    </td>
  </tr>
  <tr>
    <td>
      <b>Acceptance Criteria:</b>
    </td>
    <td style="text-align: justify;" colspan="3">
      <div style="text-align: center;">
        <b>Scenario 1: Show trends</b>
      </div>
          <i>Given</i> alert history
      <br><i>When</i> viewing
      <br><i>Then</i> system shows trend data
      <br><br>
      <div style="text-align: center;">
        <b>Scenario 2: No data</b>
      </div>
          <i>Given</i> no alerts
      <br><i>When</i> viewing
      <br><i>Then</i> system shows empty message
    </td>
  </tr>
</table>

<div style="page-break-after: always;"></div>

<!-- ===================== HU49 ===================== -->
<table style="margin: auto; table-layout: fixed; width: 80%;">
  <tr style="background-color: #d9d9d9;">
    <td>
      <b>Number:</b>
    </td>
    <td style="text-align: center;">
      HU49
    </td>
    <td>
      <b>User:</b>
    </td>
    <td style="text-align: center;">
      Supervisor
    </td>
  </tr>
  <tr>
    <td>
      <b>Story Name:</b>
    </td>
    <td style="text-align: center;" colspan="3">
      View temperature trends
    </td>
  </tr>
  <tr>
    <td>
      <b>Business Priority:</b>
    </td>
    <td colspan="3">
      Medium
    </td>
  </tr>
  <tr>
    <td>
      <b>Developer:</b>
    </td>
    <td colspan="3">
      To be defined
    </td>
  </tr>
  <tr>
    <td>
      <b>Description:</b>
    </td>
    <td style="text-align: justify;" colspan="3">
      <i>As a</i> Supervisor, <i>I want to</i> see temperature trends <i>so</i> I detect risks
    </td>
  </tr>
  <tr>
    <td>
      <b>Acceptance Criteria:</b>
    </td>
    <td style="text-align: justify;" colspan="3">
      <div style="text-align: center;">
        <b>Scenario 1: Show temperature trends</b>
      </div>
          <i>Given</i> historical data
      <br><i>When</i> viewing
      <br><i>Then</i> system shows trend
      <br><br>
      <div style="text-align: center;">
        <b>Scenario 2: No data</b>
      </div>
          <i>Given</i> no data
      <br><i>When</i> viewing
      <br><i>Then</i> system shows empty message
    </td>
  </tr>
</table>

<br><br>

<!-- ===================== HU50 ===================== -->
<table style="margin: auto; table-layout: fixed; width: 80%;">
  <tr style="background-color: #d9d9d9;">
    <td>
      <b>Number:</b>
    </td>
    <td style="text-align: center;">
      HU50
    </td>
    <td>
      <b>User:</b>
    </td>
    <td style="text-align: center;">
      Supervisor
    </td>
  </tr>
  <tr>
    <td>
      <b>Story Name:</b>
    </td>
    <td style="text-align: center;" colspan="3">
      View humidity trends
    </td>
  </tr>
  <tr>
    <td>
      <b>Business Priority:</b>
    </td>
    <td colspan="3">
      Medium
    </td>
  </tr>
  <tr>
    <td>
      <b>Developer:</b>
    </td>
    <td colspan="3">
      To be defined
    </td>
  </tr>
  <tr>
    <td>
      <b>Description:</b>
    </td>
    <td style="text-align: justify;" colspan="3">
      <i>As a</i> Supervisor, <i>I want to</i> see humidity trends <i>so</i> I maintain conditions
    </td>
  </tr>
  <tr>
    <td>
      <b>Acceptance Criteria:</b>
    </td>
    <td style="text-align: justify;" colspan="3">
      <div style="text-align: center;">
        <b>Scenario 1: Show humidity trends</b>
      </div>
          <i>Given</i> historical data
      <br><i>When</i> viewing
      <br><i>Then</i> system shows trend
      <br><br>
      <div style="text-align: center;">
        <b>Scenario 2: No data</b>
      </div>
          <i>Given</i> no data
      <br><i>When</i> viewing
      <br><i>Then</i> system shows empty message
    </td>
  </tr>
</table>

<div style="page-break-after: always;"></div>

<!-- ===================== HU51 ===================== -->
<table style="margin: auto; table-layout: fixed; width: 80%;">
  <tr style="background-color: #d9d9d9;">
    <td>
      <b>Number:</b>
    </td>
    <td style="text-align: center;">
      HU51
    </td>
    <td>
      <b>User:</b>
    </td>
    <td style="text-align: center;">
      User
    </td>
  </tr>
  <tr>
    <td>
      <b>Story Name:</b>
    </td>
    <td style="text-align: center;" colspan="3">
      Login with Google account
    </td>
  </tr>
  <tr>
    <td>
      <b>Business Priority:</b>
    </td>
    <td colspan="3">
      High
    </td>
  </tr>
  <tr>
    <td>
      <b>Developer:</b>
    </td>
    <td colspan="3">
      To be defined
    </td>
  </tr>
  <tr>
    <td>
      <b>Description:</b>
    </td>
    <td style="text-align: justify;" colspan="3">
      <i>As a</i> user, <i>I want to</i> log in using my Google account <i>so</i> I access quickly
    </td>
  </tr>
  <tr>
    <td>
      <b>Acceptance Criteria:</b>
    </td>
    <td style="text-align: justify;" colspan="3">
      <div style="text-align: center;">
        <b>Scenario 1: Successful login</b>
      </div>
          <i>Given</i> valid Google account
      <br><i>When</i> logging in
      <br><i>Then</i> access is granted
      <br><br>
      <div style="text-align: center;">
        <b>Scenario 2: Failed login</b>
      </div>
          <i>Given</i> invalid credentials
      <br><i>When</i> logging in
      <br><i>Then</i> system shows error
    </td>
  </tr>
</table>

<br><br>

<!-- ===================== HU52 ===================== -->
<table style="margin: auto; table-layout: fixed; width: 80%;">
  <tr style="background-color: #d9d9d9;">
    <td>
      <b>Number:</b>
    </td>
    <td style="text-align: center;">
      HU52
    </td>
    <td>
      <b>User:</b>
    </td>
    <td style="text-align: center;">
      User
    </td>
  </tr>
  <tr>
    <td>
      <b>Story Name:</b>
    </td>
    <td style="text-align: center;" colspan="3">
      Login with email and password
    </td>
  </tr>
  <tr>
    <td>
      <b>Business Priority:</b>
    </td>
    <td colspan="3">
      High
    </td>
  </tr>
  <tr>
    <td>
      <b>Developer:</b>
    </td>
    <td colspan="3">
      To be defined
    </td>
  </tr>
  <tr>
    <td>
      <b>Description:</b>
    </td>
    <td style="text-align: justify;" colspan="3">
      <i>As a</i> user, <i>I want to</i> log in using my email <i>so</i> I access my account
    </td>
  </tr>
  <tr>
    <td>
      <b>Acceptance Criteria:</b>
    </td>
    <td style="text-align: justify;" colspan="3">
      <div style="text-align: center;">
        <b>Scenario 1: Successful login</b>
      </div>
          <i>Given</i> valid credentials
      <br><i>When</i> logging in
      <br><i>Then</i> access is granted
      <br><br>
      <div style="text-align: center;">
        <b>Scenario 2: Invalid credentials</b>
      </div>
          <i>Given</i> incorrect data
      <br><i>When</i> logging in
      <br><i>Then</i> system shows error
    </td>
  </tr>
</table>

<div style="page-break-after: always;"></div>

<!-- ===================== HU53 ===================== -->
<table style="margin: auto; table-layout: fixed; width: 80%;">
  <tr style="background-color: #d9d9d9;">
    <td>
      <b>Number:</b>
    </td>
    <td style="text-align: center;">
      HU53
    </td>
    <td>
      <b>User:</b>
    </td>
    <td style="text-align: center;">
      User
    </td>
  </tr>
  <tr>
    <td>
      <b>Story Name:</b>
    </td>
    <td style="text-align: center;" colspan="3">
      Recover password by email
    </td>
  </tr>
  <tr>
    <td>
      <b>Business Priority:</b>
    </td>
    <td colspan="3">
      Medium
    </td>
  </tr>
  <tr>
    <td>
      <b>Developer:</b>
    </td>
    <td colspan="3">
      To be defined
    </td>
  </tr>
  <tr>
    <td>
      <b>Description:</b>
    </td>
    <td style="text-align: justify;" colspan="3">
      <i>As a</i> user, <i>I want to</i> recover access via email
    </td>
  </tr>
  <tr>
    <td>
      <b>Acceptance Criteria:</b>
    </td>
    <td style="text-align: justify;" colspan="3">
      <div style="text-align: center;">
        <b>Scenario 1: Send reset link</b>
      </div>
          <i>Given</i> valid email
      <br><i>When</i> requesting reset
      <br><i>Then</i> system sends email
      <br><br>
      <div style="text-align: center;">
        <b>Scenario 2: Invalid email</b>
      </div>
          <i>Given</i> unregistered email
      <br><i>When</i> requesting
      <br><i>Then</i> system shows error
    </td>
  </tr>
</table>

<br><br>

<!-- ===================== HU54 ===================== -->
<table style="margin: auto; table-layout: fixed; width: 80%;">
  <tr style="background-color: #d9d9d9;">
    <td>
      <b>Number:</b>
    </td>
    <td style="text-align: center;">
      HU54
    </td>
    <td>
      <b>User:</b>
    </td>
    <td style="text-align: center;">
      User
    </td>
  </tr>
  <tr>
    <td>
      <b>Story Name:</b>
    </td>
    <td style="text-align: center;" colspan="3">
      Logout from system
    </td>
  </tr>
  <tr>
    <td>
      <b>Business Priority:</b>
    </td>
    <td colspan="3">
      High
    </td>
  </tr>
  <tr>
    <td>
      <b>Developer:</b>
    </td>
    <td colspan="3">
      To be defined
    </td>
  </tr>
  <tr>
    <td>
      <b>Description:</b>
    </td>
    <td style="text-align: justify;" colspan="3">
      <i>As a</i> user, <i>I want to</i> log out to protect my account
    </td>
  </tr>
  <tr>
    <td>
      <b>Acceptance Criteria:</b>
    </td>
    <td style="text-align: justify;" colspan="3">
      <div style="text-align: center;">
        <b>Scenario 1: Logout</b>
      </div>
          <i>Given</i> user logged in
      <br><i>When</i> logging out
      <br><i>Then</i> session ends
      <br><br>
      <div style="text-align: center;">
        <b>Scenario 2: Session expired</b>
      </div>
          <i>Given</i> inactive session
      <br><i>When</i> accessing
      <br><i>Then</i> system redirects to login
    </td>
  </tr>
</table>

<div style="page-break-after: always;"></div>

<!-- ===================== HU55 ===================== -->
<table style="margin: auto; table-layout: fixed; width: 80%;">
  <tr style="background-color: #d9d9d9;">
    <td>
      <b>Number:</b>
    </td>
    <td style="text-align: center;">
      HU55
    </td>
    <td>
      <b>User:</b>
    </td>
    <td style="text-align: center;">
      Supervisor
    </td>
  </tr>
  <tr>
    <td>
      <b>Story Name:</b>
    </td>
    <td style="text-align: center;" colspan="3">
      Assign user role
    </td>
  </tr>
  <tr>
    <td>
      <b>Business Priority:</b>
    </td>
    <td colspan="3">
      High
    </td>
  </tr>
  <tr>
    <td>
      <b>Developer:</b>
    </td>
    <td colspan="3">
      To be defined
    </td>
  </tr>
  <tr>
    <td>
      <b>Description:</b>
    </td>
    <td style="text-align: justify;" colspan="3">
      <i>As a</i> Supervisor, <i>I want to</i> assign roles <i>so</i> users have proper access
    </td>
  </tr>
  <tr>
    <td>
      <b>Acceptance Criteria:</b>
    </td>
    <td style="text-align: justify;" colspan="3">
      <div style="text-align: center;">
        <b>Scenario 1: Assign role</b>
      </div>
          <i>Given</i> a user exists
      <br><i>When</i> assigning role
      <br><i>Then</i> system updates role
      <br><br>
      <div style="text-align: center;">
        <b>Scenario 2: Invalid user</b>
      </div>
          <i>Given</i> user not found
      <br><i>When</i> assigning
      <br><i>Then</i> system shows error
    </td>
  </tr>
</table>

<div style="page-break-after: always;"></div>

## **3.2. Impact Mapping**

<p style="text-align: justify;">
  The Impact Mapping has been created using the Miro tool. You can access the board at the following link:
</p>

> **Link:** [Impact Mapping Board](https://miro.com/app/board/uXjVGhw33Ew=/?share_link_id=265067473734)

<p style="text-align: justify;">
  The following impact maps show how the system connects the main goal with the needs of both Supervisor and Operator users. They help explain how each feature and user story contributes to solving real problems, improving monitoring, and allowing faster response in the laboratory.
</p>


- **Operator:**
  <div style="text-align: center;">
    <img src="../assets/chapter-3/impact-mapping/operator.jpg" alt="impact-mapping-operator" width="70%">
  </div>

<br>

- **Supervisor:**
  <div style="text-align: center;">
    <img src="../assets/chapter-3/impact-mapping/supervisor.jpg" alt="impact-mapping-operator" width="70%">
  </div>

<div style="page-break-after: always;"></div>

## **3.3. Product Backlog**

<p style="text-align: justify;">
  Product Backlog for the Meditrack system is shown below, where user stories are prioritized based on user needs and value, and estimated using the Fibonacci scale.
</p>

<table style="margin: auto;">
  <thead>
    <tr>
      <th style="text-align: center;">
        # Orden
      </th>
      <th style="text-align: center;">
        User Story ID
      </th>
      <th style="text-align: center;">
        Título
      </th>
      <th style="text-align: center;">
        Descripción
      </th>
      <th style="text-align: center;">
        Story Points
      </th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td style="text-align: center;">
        01
      </td>
      <td style="text-align: center;">
        US51
      </td>
      <td style="text-align: center;">
        Login with Google
      </td>
      <td style="text-align: justify;">
        As a user, I want to log in using Google so I access quickly
      </td>
      <td style="text-align: center;">
        3
      </td>
    </tr>
    <tr>
      <td style="text-align: center;">
        02
      </td>
      <td style="text-align: center;">
        US01
      </td>
      <td style="text-align: center;">
        Register site
      </td>
      <td style="text-align: justify;">
        As a Supervisor, I want to register a site to organize monitoring
      </td>
      <td style="text-align: center;">
        3
      </td>
    </tr>
    <tr>
      <td style="text-align: center;">
        03
      </td>
      <td style="text-align: center;">
        US03
      </td>
      <td style="text-align: center;">
        Create storage area
      </td>
      <td style="text-align: justify;">
        As a Supervisor, I want to create areas to organize equipment
      </td>
      <td style="text-align: center;">
        3
      </td>
    </tr>
    <tr>
      <td style="text-align: center;">
        04
      </td>
      <td style="text-align: center;">
        US05
      </td>
      <td style="text-align: center;">
        Register equipment
      </td>
      <td style="text-align: justify;">
        As a Supervisor, I want to register equipment to monitor it
      </td>
      <td style="text-align: center;">
        5
      </td>
    </tr>
    <tr>
      <td style="text-align: center;">
        05
      </td>
      <td style="text-align: center;">
        US07
      </td>
      <td style="text-align: center;">
        Assign equipment
      </td>
      <td style="text-align: justify;">
        As a Supervisor, I want to assign equipment to areas
      </td>
      <td style="text-align: center;">
        3
      </td>
    </tr>
    <tr>
      <td style="text-align: center;">
        06
      </td>
      <td style="text-align: center;">
        US16
      </td>
      <td style="text-align: center;">
        Automatic data collection
      </td>
      <td style="text-align: justify;">
        As an Operator, I want automatic data so I don’t record manually
      </td>
      <td style="text-align: center;">
        8
      </td>
    </tr>
    <tr>
      <td style="text-align: center;">
        07
      </td>
      <td style="text-align: center;">
        US09
      </td>
      <td style="text-align: center;">
        View temperature
      </td>
      <td style="text-align: justify;">
        As an Operator, I want to monitor temperature
      </td>
      <td style="text-align: center;">
        3
      </td>
    </tr>
    <tr>
      <td style="text-align: center;">
        08
      </td>
      <td style="text-align: center;">
        US10
      </td>
      <td style="text-align: center;">
        View humidity
      </td>
      <td style="text-align: justify;">
        As an Operator, I want to monitor humidity
      </td>
      <td style="text-align: center;">
        3
      </td>
    </tr>
    <tr>
      <td style="text-align: center;">
        09
      </td>
      <td style="text-align: center;">
        US11
      </td>
      <td style="text-align: center;">
        View equipment status
      </td>
      <td style="text-align: justify;">
        As an Operator, I want to detect equipment issues
      </td>
      <td style="text-align: center;">
        3
      </td>
    </tr>
    <tr>
      <td style="text-align: center;">
        10
      </td>
      <td style="text-align: center;">
        US18
      </td>
      <td style="text-align: center;">
        Temperature alerts
      </td>
      <td style="text-align: justify;">
        As an Operator, I want alerts for temperature issues
      </td>
      <td style="text-align: center;">
        5
      </td>
    </tr>
    <tr>
      <td style="text-align: center;">
        11
      </td>
      <td style="text-align: center;">
        US19
      </td>
      <td style="text-align: center;">
        Humidity alerts
      </td>
      <td style="text-align: justify;">
        As an Operator, I want alerts for humidity issues
      </td>
      <td style="text-align: center;">
        5
      </td>
    </tr>
    <tr>
      <td style="text-align: center;">
        12
      </td>
      <td style="text-align: center;">
        US20
      </td>
      <td style="text-align: center;">
        View alerts
      </td>
      <td style="text-align: justify;">
        As an Operator, I want to see alerts list
      </td>
      <td style="text-align: center;">
        3
      </td>
    </tr>
    <tr>
      <td style="text-align: center;">
        13
      </td>
      <td style="text-align: center;">
        US22
      </td>
      <td style="text-align: center;">
        Acknowledge alert
      </td>
      <td style="text-align: justify;">
        As an Operator, I want to mark alerts as handled
      </td>
      <td style="text-align: center;">
        2
      </td>
    </tr>
    <tr>
      <td style="text-align: center;">
        14
      </td>
      <td style="text-align: center;">
        US24
      </td>
      <td style="text-align: center;">
        Mobile alerts
      </td>
      <td style="text-align: justify;">
        As an Operator, I want alerts on my phone
      </td>
      <td style="text-align: center;">
        5
      </td>
    </tr>
    <tr>
      <td style="text-align: center;">
        15
      </td>
      <td style="text-align: center;">
        US17
      </td>
      <td style="text-align: center;">
        View data on mobile
      </td>
      <td style="text-align: justify;">
        As an Operator, I want to access data on mobile
      </td>
      <td style="text-align: center;">
        5
      </td>
    </tr>
    <tr>
      <td style="text-align: center;">
        16
      </td>
      <td style="text-align: center;">
        US43
      </td>
      <td style="text-align: center;">
        View dashboard
      </td>
      <td style="text-align: justify;">
        As a Supervisor, I want to see system overview
      </td>
      <td style="text-align: center;">
        5
      </td>
    </tr>
    <tr>
      <td style="text-align: center;">
        17
      </td>
      <td style="text-align: center;">
        US44
      </td>
      <td style="text-align: center;">
        View critical alerts
      </td>
      <td style="text-align: justify;">
        As a Supervisor, I want to prioritize issues
      </td>
      <td style="text-align: center;">
        3
      </td>
    </tr>
    <tr>
      <td style="text-align: center;">
        18
      </td>
      <td style="text-align: center;">
        US45
      </td>
      <td style="text-align: center;">
        View summary
      </td>
      <td style="text-align: justify;">
        As a Supervisor, I want quick overview
      </td>
      <td style="text-align: center;">
        3
      </td>
    </tr>
    <tr>
      <td style="text-align: center;">
        19
      </td>
      <td style="text-align: center;">
        US27
      </td>
      <td style="text-align: center;">
        View historical data
      </td>
      <td style="text-align: justify;">
        As a Supervisor, I want to analyze past data
      </td>
      <td style="text-align: center;">
        5
      </td>
    </tr>
    <tr>
      <td style="text-align: center;">
        20
      </td>
      <td style="text-align: center;">
        US30
      </td>
      <td style="text-align: center;">
        Generate report
      </td>
      <td style="text-align: justify;">
        As a Supervisor, I want reports for compliance
      </td>
      <td style="text-align: center;">
        5
      </td>
    </tr>
    <tr>
      <td style="text-align: center;">
        21
      </td>
      <td style="text-align: center;">
        US31
      </td>
      <td style="text-align: center;">
        Download report
      </td>
      <td style="text-align: justify;">
        As a Supervisor, I want to download reports
      </td>
      <td style="text-align: center;">
        3
      </td>
    </tr>
    <tr>
      <td style="text-align: center;">
        22
      </td>
      <td style="text-align: center;">
        US35
      </td>
      <td style="text-align: center;">
        View equipment condition
      </td>
      <td style="text-align: justify;">
        As a Supervisor, I want to prevent failures
      </td>
      <td style="text-align: center;">
        3
      </td>
    </tr>
    <tr>
      <td style="text-align: center;">
        23
      </td>
      <td style="text-align: center;">
        US42
      </td>
      <td style="text-align: center;">
        Equipment reliability
      </td>
      <td style="text-align: justify;">
        As a Supervisor, I want to evaluate stability
      </td>
      <td style="text-align: center;">
        5
      </td>
    </tr>
    <tr>
      <td style="text-align: center;">
        24
      </td>
      <td style="text-align: center;">
        US26
      </td>
      <td style="text-align: center;">
        Share alerts
      </td>
      <td style="text-align: justify;">
        As an Operator, I want team coordination
      </td>
      <td style="text-align: center;">
        3
      </td>
    </tr>
    <tr>
      <td style="text-align: center;">
        25
      </td>
      <td style="text-align: center;">
        US25
      </td>
      <td style="text-align: center;">
        Set alert limits
      </td>
      <td style="text-align: justify;">
        As a Supervisor, I want to configure thresholds
      </td>
      <td style="text-align: center;">
        5
      </td>
    </tr>
    <tr>
      <td style="text-align: center;">
        26
      </td>
      <td style="text-align: center;">
        US02
      </td>
      <td style="text-align: center;">
        View sites
      </td>
      <td style="text-align: justify;">
        As a Supervisor, I want to manage sites
      </td>
      <td style="text-align: center;">
        2
      </td>
    </tr>
    <tr>
      <td style="text-align: center;">
        27
      </td>
      <td style="text-align: center;">
        US04
      </td>
      <td style="text-align: center;">
        View areas
      </td>
      <td style="text-align: justify;">
        As a Supervisor, I want to manage areas
      </td>
      <td style="text-align: center;">
        2
      </td>
    </tr>
    <tr>
      <td style="text-align: center;">
        28
      </td>
      <td style="text-align: center;">
        US06
      </td>
      <td style="text-align: center;">
        View equipment
      </td>
      <td style="text-align: justify;">
        As a Supervisor, I want to manage equipment
      </td>
      <td style="text-align: center;">
        3
      </td>
    </tr>
    <tr>
      <td style="text-align: center;">
        29
      </td>
      <td style="text-align: center;">
        US13
      </td>
      <td style="text-align: center;">
        Equipment list with data
      </td>
      <td style="text-align: justify;">
        As an Operator, I want quick monitoring
      </td>
      <td style="text-align: center;">
        3
      </td>
    </tr>
    <tr>
      <td style="text-align: center;">
        30
      </td>
      <td style="text-align: center;">
        US12
      </td>
      <td style="text-align: center;">
        Equipment details
      </td>
      <td style="text-align: justify;">
        As an Operator, I want full info
      </td>
      <td style="text-align: center;">
        2
      </td>
    </tr>
    <tr>
      <td style="text-align: center;">
        31
      </td>
      <td style="text-align: center;">
        US14
      </td>
      <td style="text-align: center;">
        Filter equipment
      </td>
      <td style="text-align: justify;">
        As an Operator, I want focused view
      </td>
      <td style="text-align: center;">
        2
      </td>
    </tr>
    <tr>
      <td style="text-align: center;">
        32
      </td>
      <td style="text-align: center;">
        US08
      </td>
      <td style="text-align: center;">
        Search equipment
      </td>
      <td style="text-align: justify;">
        As a Supervisor, I want quick search
      </td>
      <td style="text-align: center;">
        2
      </td>
    </tr>
    <tr>
      <td style="text-align: center;">
        33
      </td>
      <td style="text-align: center;">
        US15
      </td>
      <td style="text-align: center;">
        No data detection
      </td>
      <td style="text-align: justify;">
        As an Operator, I want to detect missing data
      </td>
      <td style="text-align: center;">
        3
      </td>
    </tr>
    <tr>
      <td style="text-align: center;">
        34
      </td>
      <td style="text-align: center;">
        US21
      </td>
      <td style="text-align: center;">
        Alert details
      </td>
      <td style="text-align: justify;">
        As an Operator, I want full alert info
      </td>
      <td style="text-align: center;">
        2
      </td>
    </tr>
    <tr>
      <td style="text-align: center;">
        35
      </td>
      <td style="text-align: center;">
        US23
      </td>
      <td style="text-align: center;">
        Sort alerts
      </td>
      <td style="text-align: justify;">
        As an Operator, I want prioritization
      </td>
      <td style="text-align: center;">
        2
      </td>
    </tr>
    <tr>
      <td style="text-align: center;">
        36
      </td>
      <td style="text-align: center;">
        US28
      </td>
      <td style="text-align: center;">
        Select date range
      </td>
      <td style="text-align: justify;">
        As a Supervisor, I want filtered data
      </td>
      <td style="text-align: center;">
        2
      </td>
    </tr>
    <tr>
      <td style="text-align: center;">
        37
      </td>
      <td style="text-align: center;">
        US29
      </td>
      <td style="text-align: center;">
        Compare data
      </td>
      <td style="text-align: justify;">
        As a Supervisor, I want analysis
      </td>
      <td style="text-align: center;">
        3
      </td>
    </tr>
    <tr>
      <td style="text-align: center;">
        38
      </td>
      <td style="text-align: center;">
        US32
      </td>
      <td style="text-align: center;">
        View incidents
      </td>
      <td style="text-align: justify;">
        As a Supervisor, I want to evaluate alerts
      </td>
      <td style="text-align: center;">
        3
      </td>
    </tr>
    <tr>
      <td style="text-align: center;">
        39
      </td>
      <td style="text-align: center;">
        US33
      </td>
      <td style="text-align: center;">
        Export data
      </td>
      <td style="text-align: justify;">
        As a Supervisor, I want external usage
      </td>
      <td style="text-align: center;">
        3
      </td>
    </tr>
    <tr>
      <td style="text-align: center;">
        40
      </td>
      <td style="text-align: center;">
        US34
      </td>
      <td style="text-align: center;">
        Compare weekly/monthly
      </td>
      <td style="text-align: justify;">
        As a Supervisor, I want deeper analysis
      </td>
      <td style="text-align: center;">
        3
      </td>
    </tr>
    <tr>
      <td style="text-align: center;">
        41
      </td>
      <td style="text-align: center;">
        US36
      </td>
      <td style="text-align: center;">
        Abnormal values
      </td>
      <td style="text-align: justify;">
        As an Operator, I want to detect issues
      </td>
      <td style="text-align: center;">
        3
      </td>
    </tr>
    <tr>
      <td style="text-align: center;">
        42
      </td>
      <td style="text-align: center;">
        US37
      </td>
      <td style="text-align: center;">
        Equipment warnings
      </td>
      <td style="text-align: justify;">
        As an Operator, I want early alerts
      </td>
      <td style="text-align: center;">
        3
      </td>
    </tr>
    <tr>
      <td style="text-align: center;">
        43
      </td>
      <td style="text-align: center;">
        US38
      </td>
      <td style="text-align: center;">
        Performance data
      </td>
      <td style="text-align: justify;">
        As a Supervisor, I want optimization
      </td>
      <td style="text-align: center;">
        3
      </td>
    </tr>
    <tr>
      <td style="text-align: center;">
        44
      </td>
      <td style="text-align: center;">
        US39
      </td>
      <td style="text-align: center;">
        Usage data
      </td>
      <td style="text-align: justify;">
        As a Supervisor, I want resource control
      </td>
      <td style="text-align: center;">
        3
      </td>
    </tr>
    <tr>
      <td style="text-align: center;">
        45
      </td>
      <td style="text-align: center;">
        US40
      </td>
      <td style="text-align: center;">
        Register maintenance
      </td>
      <td style="text-align: justify;">
        As a Supervisor, I want tracking
      </td>
      <td style="text-align: center;">
        3
      </td>
    </tr>
    <tr>
      <td style="text-align: center;">
        46
      </td>
      <td style="text-align: center;">
        US41
      </td>
      <td style="text-align: center;">
        Maintenance history
      </td>
      <td style="text-align: justify;">
        As a Supervisor, I want reliability
      </td>
      <td style="text-align: center;">
        3
      </td>
    </tr>
    <tr>
      <td style="text-align: center;">
        47
      </td>
      <td style="text-align: center;">
        US46
      </td>
      <td style="text-align: center;">
        Equipment with alerts
      </td>
      <td style="text-align: justify;">
        As a Supervisor, I want focus
      </td>
      <td style="text-align: center;">
        2
      </td>
    </tr>
    <tr>
      <td style="text-align: center;">
        48
      </td>
      <td style="text-align: center;">
        US47
      </td>
      <td style="text-align: center;">
        No data equipment
      </td>
      <td style="text-align: justify;">
        As an Operator, I want detection
      </td>
      <td style="text-align: center;">
        2
      </td>
    </tr>
    <tr>
      <td style="text-align: center;">
        49
      </td>
      <td style="text-align: center;">
        US48
      </td>
      <td style="text-align: center;">
        Alert trends
      </td>
      <td style="text-align: justify;">
        As a Supervisor, I want analysis
      </td>
      <td style="text-align: center;">
        3
      </td>
    </tr>
    <tr>
      <td style="text-align: center;">
        50
      </td>
      <td style="text-align: center;">
        US49
      </td>
      <td style="text-align: center;">
        Temperature trends
      </td>
      <td style="text-align: justify;">
        As a Supervisor, I want insights
      </td>
      <td style="text-align: center;">
        3
      </td>
    </tr>
    <tr>
      <td style="text-align: center;">
        51
      </td>
      <td style="text-align: center;">
        US50
      </td>
      <td style="text-align: center;">
        Humidity trends
      </td>
      <td style="text-align: justify;">
        As a Supervisor, I want insights
      </td>
      <td style="text-align: center;">
        3
      </td>
    </tr>
    <tr>
      <td style="text-align: center;">
        52
      </td>
      <td style="text-align: center;">
        US52
      </td>
      <td style="text-align: center;">
        Login email
      </td>
      <td style="text-align: justify;">
        As a user, I want to log in with email
      </td>
      <td style="text-align: center;">
        3
      </td>
    </tr>
    <tr>
      <td style="text-align: center;">
        53
      </td>
      <td style="text-align: center;">
        US53
      </td>
      <td style="text-align: center;">
        Recover password
      </td>
      <td style="text-align: justify;">
        As a user, I want to recover access
      </td>
      <td style="text-align: center;">
        3
      </td>
    </tr>
    <tr>
      <td style="text-align: center;">
        54
      </td>
      <td style="text-align: center;">
        US54
      </td>
      <td style="text-align: center;">
        Logout
      </td>
      <td style="text-align: justify;">
        As a user, I want to log out
      </td>
      <td style="text-align: center;">
        1
      </td>
    </tr>
    <tr>
      <td style="text-align: center;">
        55
      </td>
      <td style="text-align: center;">
        US55
      </td>
      <td style="text-align: center;">
        Assign role
      </td>
      <td style="text-align: justify;">
        As a Supervisor, I want role control
      </td>
      <td style="text-align: center;">
        3
      </td>
    </tr>
  </tbody>
</table>

<div style="page-break-after: always;"></div>
