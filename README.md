<p align="center">
  <img src="https://github.com/AbdoulGafarouZOUNGRANA/estate-agency-system/blob/main/uniloge%20logo.jpg" alt="Uniloge Maroc Logo" width="260">
</p>

<h1 align="center">🏢 UNILOGE MAROC – Real Estate Agency Management System</h1>
<p align="center">
  <strong>Academic Engineering Project – École Mohammadia d’Ingénieurs (EMI)</strong><br>
  <em>“Un clic, un logement, un avenir.”</em>
</p>

---

## 📌 Overview

UNILOGE MAROC is a **complete real estate management system** developed as part of an academic project at  
**École Mohammadia d’Ingénieurs (EMI – Rabat)**.

We simulated a real company that connects:

- 🧑‍🎓 **Students looking for housing**  
- 🏠 **Owners renting their properties**  
- 🧑‍💼 **Supervisors handling visits and coordination**  
- 🏢 **Administrative staff managing HR, contracts, and payments**

The system integrates **Odoo ERP**, **HubSpot CRM**, **AppliCEO**, and a **centralized Excel database**, offering a professional-grade workflow and automation similar to a real real estate agency.

---

## 🎯 Objectives

- Provide a seamless housing search process for students  
- Allow owners to easily register properties for rent  
- Automate data collection and contact creation  
- Centralize all operations: clients, owners, visits, contracts, HR  
- Offer advanced filtering & matching to connect the right tenant with the right property  
- Simulate a fully operational real estate company  

---

## 🧩 Architecture & Technologies

| Layer | Tools / Technologies |
|------|-----------------------|
| ERP & Core System | **Odoo** |
| CRM & Contact Management | **HubSpot CRM** |
|  finance management| **AppliCEO** |
| Data Storage | **Excel (shared online)** + **Local windows Server** |
| SMTP & Communication | Email automation integration |
| Matching & Opportunities | Odoo CRM + Custom filters |
| Project Team Roles | Dev, CRM admin, HR manager, finance manager |

---

## 🏗️ Functional Modules

### 1️⃣ **Client & Student Intake Forms**
Built via **HubSpot**, allowing students to submit:

- Preferred city  
- District  
- Budget  
- Type of house  
- Contact information  

🔄 Auto-created in CRM as **Contacts** + **Opportunities**.

---

### 2️⃣ **Owner Intake Form**
Owners can register:

- Property details  
- Rent price  
- Location  
- Availability  
- Photos & description  

🔄 Their submissions automatically generate **property records**.

---

### 3️⃣ **Odoo CRM – Property Matching System**
Using Odoo’s CRM module, we built a **matching engine** using filters:

- City  
- Budget  
- Type of property  
- Availability  
- Owner requirements  

🧠 This allows us to match **students ↔ owners** efficiently.

---

### 4️⃣ **Visits & Scheduling Workflow**
Using Odoo’s **Calendar**:

- Meetings created automatically  
- Participants:
  - Student  
  - Owner  
  - Supervisor  
- Visit supervision from UNILOGE staff  
- Integrated email notifications (via SMTP)

---

### 5️⃣ **Contracts, Payments & Invoicing**
A second team member handled:

- Contract generation  
- Payment tracking  
- Invoice management  
- Document workflow for finalized rentals  

---

### 6️⃣ **Human Resources Module**
Another team member managed:

- Staff roles & permissions  
- Supervisor scheduling  
- Leave management  
- Internal company structure  

---

## 👨‍💻 My Contributions

As the **Project Leader**, I was responsible for supervising the entire workflow of the team and ensuring coordination between all modules (CRM, HR, invoicing, automations, forms, and database management). My main contributions include:

- 🧭 **Project Management & Team Coordination**  
  I led the team of four members, assigned tasks, validated architectural decisions, and ensured coherence between all functional modules.

- 🎨 **Branding & Visual Identity**  
  I designed the **official logo of UNILOGE MAROC**, establishing the visual identity of the simulated company.

- 🏗️ **Odoo ERP Customization**  
  Customizing Odoo modules for CRM, opportunities, filtering, visit scheduling, and tenant–owner matching.

- 🖥️ **Local Server Setup (windows)**  
  Installation, configuration, and hosting of our local instance of Odoo for development and testing.

- 🗂️ **Database Structuring & Centralization**  
  I created a shared cloud-based Excel data system to allow remote collaboration and consistency across all data sources.

- ✉️ **SMTP Email Integration**  
  Configuration of email automation inside the system, enabling the sending of visit confirmations and internal notifications.

- 📅 **Visit Scheduling Workflow**  
  Using the Calendar module, I built the workflow connecting students, owners, and supervisors, with automated reminders.

- 🧪 **Testing, Validation & Final Documentation**  
  Debugging the full pipeline, writing the technical explanations, and contributing to the final academic report.



## 📘 Report

The full academic report is available in this repository


