# **Chapter IV: Product Design**

## **4.1. Style Guidelines**

### **4.1.1. General Style Guidelines**

**Brand Overview**

SafeLab is a biotech monitoring platform designed to ensure pharmaceutical and clinical cold chain compliance through real-time sensor monitoring and alert management. The brand identity reflects professionalism, reliability, and technological innovation in the healthcare sector.

**Color Palette**

Our primary color palette emphasizes trust, safety, and precision:

- **Primary Colors:**
  - Indigo 600 (`#4F46E5`) - Main brand color, used for primary actions and navigation
  - Indigo 700 (`#4338CA`) - Darker variant for hover states and emphasis
  - Indigo 50 (`#EEF2FF`) - Light backgrounds and subtle highlights

- **Secondary Colors:**
  - Slate 900 (`#0F172A`) - Primary text and headings
  - Slate 700 (`#334155`) - Secondary text
  - Slate 600 (`#475569`) - Tertiary text and labels
  - Slate 100 (`#F1F5F9`) - Background surfaces
  - Slate 50 (`#F8FAFC`) - Page backgrounds

- **Semantic Colors:**
  - Emerald 600 (`#059669`) - Success states, active sensors, normal operations
  - Amber 500 (`#F59E0B`) - Warning states, threshold approaching
  - Red 600 (`#DC2626`) - Critical alerts, errors, out-of-compliance
  - Blue 600 (`#2563EB`) - Information, neutral notifications

**Typography**

- **Font Family:** System font stack prioritizing readability and performance
  - Primary: `-apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, "Helvetica Neue", Arial, sans-serif`
  
- **Hierarchy:**
  - **H1 (Page Titles):** 2rem (32px), Bold (700), Slate 900
  - **H2 (Section Headers):** 1.5rem (24px), Bold (700), Slate 900
  - **H3 (Subsections):** 1.25rem (20px), Semibold (600), Slate 800
  - **Body Text:** 1rem (16px), Regular (400), Slate 700
  - **Small Text:** 0.875rem (14px), Regular (400), Slate 600
  - **Caption:** 0.75rem (12px), Medium (500), Slate 600

**Spacing & Layout**

- **Base Unit:** 0.25rem (4px)
- **Common Spacing:**
  - xs: 0.5rem (8px)
  - sm: 0.75rem (12px)
  - md: 1rem (16px)
  - lg: 1.5rem (24px)
  - xl: 2rem (32px)
  - 2xl: 3rem (48px)

- **Container Max-Width:** 1280px (desktop), 100% (mobile)
- **Grid System:** 12-column responsive grid with 16px gutters

**Iconography**

- **Icon Library:** Lucide React
- **Icon Sizes:**
  - Small: 16px (informational icons)
  - Medium: 20px (navigation, buttons)
  - Large: 24px (feature highlights)
  - Extra Large: 32px+ (hero sections, empty states)

- **Icon Style:** Minimalist line icons with 2px stroke width, consistent with modern medical/scientific interfaces

**Visual Elements**

- **Border Radius:**
  - Small components (buttons, badges): 0.375rem (6px)
  - Cards and containers: 0.5rem (8px)
  - Large surfaces: 0.75rem (12px)
  - Circular elements (avatars): 50%

- **Shadows:**
  - Subtle: `0 1px 2px rgba(0, 0, 0, 0.05)`
  - Medium: `0 4px 6px rgba(0, 0, 0, 0.1)`
  - Large: `0 10px 15px rgba(0, 0, 0, 0.1)`

- **Gradients:**
  - Primary: `linear-gradient(135deg, #4F46E5 0%, #4338CA 100%)`
  - Background: `linear-gradient(to bottom right, #F8FAFC 0%, #F1F5F9 100%)`

**Tone & Voice**

- **Professional:** Clear, concise, technical when necessary
- **Reassuring:** Emphasize safety, reliability, and compliance
- **Actionable:** Direct users with clear calls-to-action
- **Accessible:** Avoid jargon when communicating with non-technical users

### **4.1.2. Web Style Guidelines**

**Responsive Design Principles**

SafeLab follows a mobile-first responsive approach with three primary breakpoints:

- **Mobile:** 320px - 767px (single column, stacked navigation)
- **Tablet:** 768px - 1023px (adaptive layouts, collapsible sidebar)
- **Desktop:** 1024px+ (full multi-column layouts, persistent navigation)

**Component Design Standards**

**Navigation:**
- **Desktop:** Persistent left sidebar (240px width) with icon + label navigation
- **Mobile:** Bottom tab bar with icon-only navigation (56px height)
- **Header:** Fixed top bar (64px height) with breadcrumbs, search, and user profile

**Buttons:**
- **Primary Button:** Indigo 600 background, white text, rounded-md, medium padding (px-4 py-2)
  - Hover: Indigo 700 background
  - Active: Indigo 800 background with subtle shadow
  - Disabled: Slate 300 background, Slate 500 text, no pointer events

- **Secondary Button:** White background, Slate 700 text, Slate 300 border
  - Hover: Slate 50 background
  
- **Danger Button:** Red 600 background, white text (for critical actions like "Delete", "Deactivate")

**Forms:**
- **Input Fields:** White background, Slate 300 border, rounded-md, 40px height
  - Focus: Indigo 600 border (2px), subtle shadow
  - Error: Red 500 border, Red 600 error message below
  - Success: Emerald 500 border

- **Labels:** Slate 700, 14px, semibold (600), 8px margin-bottom
- **Placeholders:** Slate 400, italic
- **Helper Text:** Slate 600, 12px, regular

**Cards:**
- **Standard Card:** White background, subtle shadow, 8px border-radius, 16px padding
- **Elevated Card:** Medium shadow on hover for interactive cards
- **Sensor Card:** Includes status indicator (colored left border: 4px), icon, title, metrics, and timestamp

**Tables:**
- **Header:** Slate 100 background, Slate 700 bold text, 12px uppercase
- **Rows:** White background, Slate 800 border-bottom (1px)
  - Hover: Slate 50 background
  - Striped (optional): Alternating Slate 50 backgrounds
- **Responsive:** Horizontal scroll on mobile, card-based layout for narrow screens

**Alerts & Notifications:**
- **Critical Alert:** Red 50 background, Red 700 border-left (4px), Red 800 text, AlertTriangle icon
- **Warning:** Amber 50 background, Amber 600 border, Amber 900 text, AlertCircle icon
- **Success:** Emerald 50 background, Emerald 600 border, Emerald 900 text, CheckCircle icon
- **Info:** Blue 50 background, Blue 600 border, Blue 900 text, Info icon

**Charts & Data Visualization:**
- **Library:** Recharts
- **Color Scheme:** Indigo gradient for primary metrics, semantic colors for status indicators
- **Accessibility:** All charts include text alternatives and ARIA labels

**Loading States:**
- **Skeleton Screens:** Animated pulse effect on placeholder elements
- **Spinners:** Indigo 600 spinner for content loading
- **Progress Bars:** Indigo 600 fill with Slate 200 background

**Accessibility Standards:**
- **WCAG 2.1 Level AA Compliance**
- **Minimum contrast ratio:** 4.5:1 for normal text, 3:1 for large text
- **Focus indicators:** 2px Indigo 600 outline with 2px offset
- **Keyboard navigation:** Full support for tab, arrow keys, enter, escape
- **Screen reader support:** Proper ARIA labels, roles, and live regions for dynamic content
- **Touch targets:** Minimum 44x44px for all interactive elements on mobile

**Animation & Transitions:**
- **Duration:** 150ms for micro-interactions, 300ms for page transitions
- **Easing:** `ease-in-out` for most transitions
- **Hover Effects:** Subtle scale (1.02) or shadow increase
- **Page Transitions:** Fade in/out with slight vertical movement
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
  <img src="../assets/chapter-4/web-applications-design/wireflow-diagrams/wireflow2.png" width="70%" alt="wireflow diagram">
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

<p align="center">
  <img src="../assets/chapter-4/web-applications-design/user-flow-diagrams/userflow1.png" width="70%" alt="user flow diagram">
</p>
<p align="center">
  <img src="../assets/chapter-4/web-applications-design/user-flow-diagrams/userflow2.png" width="70%" alt="user flow diagram">
</p>
<p align="center">
  <img src="../assets/chapter-4/web-applications-design/user-flow-diagrams/userflow3.png" width="70%" alt="user flow diagram">
</p>
<p align="center">
  <img src="../assets/chapter-4/web-applications-design/user-flow-diagrams/userflow4.png" width="70%" alt="user flow diagram">
</p>

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
