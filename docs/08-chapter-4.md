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
### **4.4.2. Web Applications Wireflow Diagrams**
### **4.4.3. Web Applications Mock-ups**
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
### **4.6.4. Software Architecture Components Diagrams**
## **4.7. Object-Oriented Design Software**
### **4.7.1. Class Diagrams**
## **4.8. Database Design**
### **4.8.1. Database Diagrams**