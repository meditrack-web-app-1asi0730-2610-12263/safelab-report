# **Chapter IV: Product Design**
## **4.1. Style Guidelines**
### **4.1.1. General Style Guidelines**
### **4.1.2. Web Style Guidelines**
## **4.2. Information Architecture**
### **4.2.1. Organization Systems**
### **4.2.2. Labeling Systems**
### **4.2.3. SEO Tags and Meta Tags**
### **4.2.4. Searching Systems**
### **4.2.5. Navigation Systems**
## **4.3. Landing Page UI Design**
### **4.3.1. Landing Page Wireframe**
### **4.3.2. Landing Page Mockup**
## **4.4. Web Applications UX/UI Design**
### **4.4.1. Web Applications Wireframes**

<p align="center">
  <img src="../assets/chapter-4/web-applications-design/wireframes/wireframeweb1.png" width="70%" alt="web application wireframes">
</p>
<p align="center">
  <img src="../assets/chapter-4/web-applications-design/wireframes/wireframeweb2.png" width="70%" alt="web application wireframes">
</p>
<p align="center">
  <img src="../assets/chapter-4/web-applications-design/wireframes/wireframeweb3.png" width="70%" alt="web application wireframes">
</p>
<p align="center">
  <img src="../assets/chapter-4/web-applications-design/wireframes/wireframeweb4.png" width="70%" alt="web application wireframes">
</p>

### **4.4.2. Web Applications Wireflow Diagrams**

<p align="center">
  <img src="../assets/chapter-4/web-applications-design/wireflow-diagrams/wireflow1.png" width="70%" alt="wireflow diagram">
</p>
<p align="center">
  <img src="../assets/chapter-4/web-applications-design/wireflow-diagrams/wireflow1.png" width="70%" alt="wireflow diagram">
</p>

### **4.4.3. Web Applications Mock-ups**

<p align="center">
  <img src="../assets/chapter-4/web-applications-design/mockups/mockupweb1.png" width="70%" alt="web application mockup>
</p>
<p align="center">
  <img src="../assets/chapter-4/web-applications-design/mockups/mockupweb2.png" width="70%" alt="web application mockup>
</p>
<p align="center">
  <img src="../assets/chapter-4/web-applications-design/mockups/mockupweb3.png" width="70%" alt="web application mockup>
</p>
<p align="center">
  <img src="../assets/chapter-4/web-applications-design/mockups/mockupweb4.png" width="70%" alt="web application mockup>
</p>

### **4.4.4. Web Applications User Flow Diagrams**

## **4.5. Web Applications Prototyping**

## **4.6. Domain-Driven Software Architecture**

<p style="text-align: justify;">
  
  This section presents the Domain-Driven Software Architecture of SafeLab, structured through strategic and tactical design principles to manage the complexity of a real-time laboratory monitoring platform. The system is organized into well-defined Bounded Contexts, each representing an independent business domain such as Identity & Access Management, Sensor Monitoring, Asset & Inventory Monitoring, Alerts & Notifications, Incident Management, Reports & Analytics, and Audit & Traceability. This architectural approach promotes modularity, scalability, maintainability, and clear ownership of responsibilities across the solution. Through the use of Context, Container, Component, and Class Diagrams, the architecture aligns business processes with technical implementation, ensuring that SafeLab can evolve efficiently while supporting secure operations, regulatory compliance, and reliable monitoring services for laboratories and pharmaceutical environments.
</P>

### **4.6.1. Design-Level EventStorming**

- Identity & Access Management Bounded Context:

<p align="center">
  <img src="../assets/chapter-4/software-architecture/event-storming/identity-access-bounded-context.png" width="70%" alt="identity-access-bounded-context">
</p>

- User Profiles Bounded Context:

<p align="center">
  <img src="../assets/chapter-4/software-architecture/event-storming/user-profiles-bounded-context.png" width="70%" alt="user-profiles-bounded-context">
</p>

- Subscription & Billing Bounded Context:

<p align="center">
  <img src="../assets/chapter-4/software-architecture/event-storming/subscription-billing-bounded-context.png" width="70%" alt="subscription-billing-bounded-context">
</p>

- Dashboard & Overview Bounded Context:

<p align="center">
  <img src="../assets/chapter-4/software-architecture/event-storming/dashboard-overview-bounded-context.png" width="70%" alt="dashboard-overview-bounded-context">
</p>

- Asset & Inventory Monitoring Bounded Context:

<p align="center">
  <img src="../assets/chapter-4/software-architecture/event-storming/asset-inventory-monitoring-bounded-context.png" width="70%" alt="asset-inventory-monitoring-bounded-context">
</p>

- Sensor Monitoring Bounded Context:

<p align="center">
  <img src="../assets/chapter-4/software-architecture/event-storming/sensor-monitoring-bounded-context.png" width="70%" alt="sensor-monitoring-bounded-context">
</p>

- Environmental Compliance Bounded Context:

<p align="center">
  <img src="../assets/chapter-4/software-architecture/event-storming/environmental-compliance-bounded-context.png" width="70%" alt="environmental-compliance-bounded-context">
</p>

- Alerts & Notifications Bounded Context:

<p align="center">
  <img src="../assets/chapter-4/software-architecture/event-storming/alerts-notifications-bounded-context.png" width="70%" alt="alerts-notifications-bounded-context">
</p>

- Remote Control & Actuation Bounded Context:

<p align="center">
  <img src="../assets/chapter-4/software-architecture/event-storming/remote-control-actuation-bounded-context.png" width="70%" alt="remote-control-actuation-bounded-context">
</p>

- Reports & Analytics Bounded Context:

<p align="center">
  <img src="../assets/chapter-4/software-architecture/event-storming/reports-analytics-bounded-context.png" width="70%" alt="reports-analytics-bounded-context">
</p>

- Incident Management Bounded Context:

<p align="center">
  <img src="../assets/chapter-4/software-architecture/event-storming/incident-management-bounded-context.png" width="70%" alt="incident-management-bounded-context">
</p>

- Audit & Traceability Bounded Context:

<p align="center">
  <img src="../assets/chapter-4/software-architecture/event-storming/audit-traceability-bounded-context.png" width="70%" alt="audit-traceability-bounded-context">
</p>

### **4.6.2. Software Architecture Context Diagram**

- SafeLab Contex Diagram:

<p align="center">
  <img src="../assets/chapter-4/software-architecture/context-diagram/context-diagram.png" width="70%" alt="context-diagram">
</p>

### **4.6.3. Software Architecture Container Diagrams**

- SafeLab Container Diagram:

<p align="center">
  <img src="../assets/chapter-4/software-architecture/container-diagram/container-diagram.png" width="70%" alt="container-diagram">
</p>

### **4.6.4. Software Architecture Components Diagrams**

- SafeLab Web Application Component Diagram:

<p align="center">
  <img src="../assets/chapter-4/software-architecture/components-diagram/web-application-component-diagram.png" width="70%" alt="web-application-component-diagram">
</p>

- Identity & Access Management Component Diagram:

<p align="center">
  <img src="../assets/chapter-4/software-architecture/components-diagram/identity-access-component-diagram.png" width="70%" alt="identity-access-component-diagram">
</p>

- User Profiles Component Diagram:

<p align="center">
  <img src="../assets/chapter-4/software-architecture/components-diagram/user-profiles-component-diagram.png" width="70%" alt="user-profiles-component-diagram">
</p>

- Subscription & Billing Component Diagram:

<p align="center">
  <img src="../assets/chapter-4/software-architecture/components-diagram/subscription-billing-component-diagram.png" width="70%" alt="subscription-billing-component-diagram">
</p>

- Dashboard & Overview Component Diagram:

<p align="center">
  <img src="../assets/chapter-4/software-architecture/components-diagram/dashboard-overview-component-diagram.png" width="70%" alt="dashboard-overview-component-diagram">
</p>

- Asset & Inventory Monitoring Component Diagram:

<p align="center">
  <img src="../assets/chapter-4/software-architecture/components-diagram/asset-inventory-monitoring-component-diagram.png" width="70%" alt="asset-inventory-monitoring-component-diagram">
</p>

- Sensor Monitoring Component Diagram:

<p align="center">
  <img src="../assets/chapter-4/software-architecture/components-diagram/sensor-monitoring-component-diagram.png" width="70%" alt="sensor-monitoring-component-diagram">
</p>

- Environmental Compliance Component Diagram:

<p align="center">
  <img src="../assets/chapter-4/software-architecture/components-diagram/environmental-compliance-component-diagram.png" width="70%" alt="environmental-compliance-component-diagram">
</p>

- Alerts & Notifications Component Diagram:

<p align="center">
  <img src="../assets/chapter-4/software-architecture/components-diagram/alerts-notifications-component-diagram.png" width="70%" alt="alerts-notifications-component-diagram">
</p>

- Remote Control & Actuation Component Diagram:

<p align="center">
  <img src="../assets/chapter-4/software-architecture/components-diagram/remote-control-actuation-component-diagram.png" width="70%" alt="remote-control-actuation-component-diagram">
</p>

- Reports & Analytics Component Diagram:

<p align="center">
  <img src="../assets/chapter-4/software-architecture/components-diagram/reports-analytics-component-diagram.png" width="70%" alt="reports-analytics-component-diagram">
</p>

- Incident Management Component Diagram:

<p align="center">
  <img src="../assets/chapter-4/software-architecture/components-diagram/incident-management-component-diagram.png" width="70%" alt="incident-management-component-diagram">
</p>

- Audit & Traceability Component Diagram:

<p align="center">
  <img src="../assets/chapter-4/software-architecture/components-diagram/audit-traceability-component-diagram.png" width="70%" alt="audit-traceability-component-diagram">
</p>

## **4.7. Object-Oriented Design Software**

<p style="text-align: justify;">
  This section presents the object-oriented design of the SafeLab platform through UML Class Diagrams that model the internal structure of the system. The diagrams define the main entities, attributes, methods, enumerations, and relationships required to support the business logic of each bounded context. Following Domain-Driven Design (DDD) principles, the software model is organized into twelve functional domains, including identity management, user profiles, subscriptions, dashboards, asset monitoring, sensor telemetry, environmental compliance, alerts, remote control, analytics, incident management, and audit traceability. These diagrams provide a clear blueprint for software implementation, promote maintainability, and ensure consistency between business requirements and the technical architecture.
</p>

### **4.7.1. Class Diagrams**

- Identity & Access Management Class Diagram:

<p align="center">
  <img src="../assets/chapter-4/design-software/class-diagrams/identity-access-management-class-diagram.png" width="70%" alt="identity-access-class-diagram">
</p>

- User Profiles Class Diagram:

<p align="center">
  <img src="../assets/chapter-4/design-software/class-diagrams/user-profiles-class-diagram.png" width="70%" alt="user-profiles-class-diagram">
</p>

- Subscription & Billing Class Diagram:

<p align="center">
  <img src="../assets/chapter-4/design-software/class-diagrams/subscription-billing-class-diagram.png" width="70%" alt="subscription-billing-class-diagram">
</p>

- Dashboard & Overview Class Diagram:

<p align="center">
  <img src="../assets/chapter-4/design-software/class-diagrams/dashboard-overview-class-diagram.png" width="70%" alt="dashboard-overview-class-diagram">
</p>

- Asset & Inventory Monitoring Class Diagram:

<p align="center">
  <img src="../assets/chapter-4/design-software/class-diagrams/asset-inventory-monitoring-class-diagram.png" width="70%" alt="asset-inventory-monitoring-class-diagram">
</p>

- Sensor Monitoring Class Diagram:

<p align="center">
  <img src="../assets/chapter-4/design-software/class-diagrams/sensor-monitoring-class-diagram.png" width="70%" alt="sensor-monitoring-class-diagram">
</p>

- Environmental Compliance Class Diagram:

<p align="center">
  <img src="../assets/chapter-4/design-software/class-diagrams/environmental-compliance-class-diagram.png" width="70%" alt="environmental-compliance-class-diagram">
</p>

- Alerts & Notifications Class Diagram:

<p align="center">
  <img src="../assets/chapter-4/design-software/class-diagrams/alerts-notifications-class-diagram.png" width="70%" alt="alerts-notifications-class-diagram">
</p>

- Remote Control & Actuation Class Diagram:

<p align="center">
  <img src="../assets/chapter-4/design-software/class-diagrams/remote-control-actuation-class-diagram.png" width="70%" alt="remote-control-actuation-class-diagram">
</p>

- Reports & Analytics Class Diagram:

<p align="center">
  <img src="../assets/chapter-4/design-software/class-diagrams/reports-analytics-class-diagram.png" width="70%" alt="reports-analytics-class-diagram">
</p>

- Incident Management Class Diagram:

<p align="center">
  <img src="../assets/chapter-4/design-software/class-diagrams/incident-management-class-diagram.png" width="70%" alt="incident-management-class-diagram">
</p>

- Audit & Traceability Class Diagram:

<p align="center">
  <img src="../assets/chapter-4/design-software/class-diagrams/audit-traceability-class-diagram.png" width="70%" alt="audit-traceability-class-diagram">
</p>

## **4.8. Database Design**

<p style="text-align: justify;">
  This section defines the database design of the SafeLab platform, focusing on the logical organization, persistence strategy, and data structure required to support the system functionalities. Based on the previously defined bounded contexts and object-oriented models, the database design ensures data integrity, scalability, traceability, and efficient access to operational information. It includes the identification of core entities, relationships, constraints, and storage considerations for modules such as users, subscriptions, assets, sensors, alerts, incidents, reports, and audit records. The detailed database diagrams and relational implementation are presented in the following subsection.
</p>

### **4.8.1. Database Diagrams**

- Identity & Access Management Database Diagram:

<p align="center">
  <img src="../assets/chapter-4/database-design/database-diagram/safelab-database-diagram.png" width="70%" alt="safelab-database-diagram">


- Identity & Access Management Database Diagram:

<p align="center">
  <img src="../assets/chapter-4/database-design/database-diagram/identity-access-management-database-diagram.png" width="70%" alt="identity-access-management-database-diagram">
</p>

- User Profiles Database Diagram:

<p align="center">
  <img src="../assets/chapter-4/database-design/database-diagram/user-profiles-database-diagram.png" width="70%" alt="user-profiles-database-diagram">
</p>

- Subscription & Billing Database Diagram:

<p align="center">
  <img src="../assets/chapter-4/database-design/database-diagram/subscription-billing-database-diagram.png" width="70%" alt="subscription-billing-database-diagram">
</p>

- Dashboard & Overview Database Diagram:

<p align="center">
  <img src="../assets/chapter-4/database-design/database-diagram/dashboard-overview-database-diagram.png" width="70%" alt="dashboard-overview-database-diagram">
</p>

- Asset & Inventory Monitoring Database Diagram:

<p align="center">
  <img src="../assets/chapter-4/database-design/database-diagram/asset-inventory-monitoring-database-diagram.png" width="70%" alt="asset-inventory-monitoring-database-diagram">
</p>

- Sensor Monitoring Database Diagram:

<p align="center">
  <img src="../assets/chapter-4/database-design/database-diagram/sensor-monitoring-database-diagram.png" width="70%" alt="sensor-monitoring-database-diagram">
</p>

- Environmental Compliance Database Diagram:

<p align="center">
  <img src="../assets/chapter-4/database-design/database-diagram/environmental-compliance-database-diagram.png" width="70%" alt="environmental-compliance-database-diagram">
</p>

- Alerts & Notifications Database Diagram:

<p align="center">
  <img src="../assets/chapter-4/database-design/database-diagram/alerts-notifications-database-diagram.png" width="70%" alt="alerts-notifications-database-diagram">
</p>

- Remote Control & Actuation Database Diagram:

<p align="center">
  <img src="../assets/chapter-4/database-design/database-diagram/remote-control-actuation-database-diagram.png" width="70%" alt="remote-control-actuation-database-diagram">
</p>

- Reports & Analytics Database Diagram:

<p align="center">
  <img src="../assets/chapter-4/database-design/database-diagram/reports-analytics-database-diagram.png" width="70%" alt="reports-analytics-database-diagram">
</p>

- Incident Management Database Diagram:

<p align="center">
  <img src="../assets/chapter-4/database-design/database-diagram/incident-management-database-diagram.png" width="70%" alt="incident-management-database-diagram">
</p>

- Audit & Traceability Database Diagram:

<p align="center">
  <img src="../assets/chapter-4/database-design/database-diagram/audit-traceability-database-diagram.png" width="70%" alt="audit-traceability-database-diagram">
</p>
