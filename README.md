# 🖥️ ServiceNow IT Help Desk Analytics Project

**Built on:** ServiceNow Developer Instance (Zurich Release)  
**Author:** Meghana Lakshminarayana Swamy  
**Skills Demonstrated:** IT Service Management (ITSM), Platform Analytics, Flow Designer, Service Catalog, Incident Management

---

## 📌 Project Overview

This project simulates a real-world IT Help Desk management system built entirely on ServiceNow. It covers three core components that are commonly required in ServiceNow Administrator and Business Analyst roles:

1. **Real-Time Analytics Dashboard** — monitoring open incidents across categories, priorities, states, and assignment groups
2. **Automated Workflow** — a Flow Designer automation that triggers email alerts for Critical priority incidents
3. **Service Catalog Item** — a self-service employee request form for laptop provisioning

---

## 1️⃣ IT Help Desk Analytics Dashboard

Built using ServiceNow Platform Analytics with 4 interactive visualizations and a Category filter (slicer).

**Charts included:**
- Incidents by Category (Bar Chart)
- Incidents by Priority (Bar Chart)
- Incidents by State (Donut Chart)
- Incidents by Assignment Group (Bar Chart)

**Data:** 50+ mock IT incidents generated via background script covering categories: Network, Hardware, Software, Database, Security

<img width="1526" height="782" alt="8 - dashboard" src="https://github.com/user-attachments/assets/f40533cb-4baf-4073-afae-a97db780a2d5" />

---

## 2️⃣ Critical Incident Alert — Automated Workflow

Built using ServiceNow **Flow Designer**.

**Logic:**
- **Trigger:** When a new Incident is created
- **Condition:** Priority = 1 - Critical
- **Action:** Automatically sends an email alert to the IT manager

This eliminates manual monitoring of Critical incidents and ensures immediate response.

<img width="498" height="438" alt="9 - automation workflow" src="https://github.com/user-attachments/assets/3ff1424a-ddbb-4113-a621-4c60fad0f457" />

---

## 3️⃣ New Employee Laptop Request — Service Catalog Item

Built using ServiceNow **Service Catalog**.

A self-service request form employees can use to request a laptop. Includes:
- Employee full name (mandatory text field)
- Laptop type required (multiple choice)
- Date needed by (date picker)
- 2-day delivery SLA

<img width="1919" height="427" alt="10 2" src="https://github.com/user-attachments/assets/d12fe974-137e-420e-a8b7-11be60a382e6" />

---

## 🛠️ Tools & Features Used

| Feature | Purpose |
|---|---|
| Background Script (JavaScript) | Generated 50 mock incidents for realistic data |
| Platform Analytics | Built interactive dashboard with filters |
| Flow Designer | Automated Critical incident email alerts |
| Service Catalog | Created self-service employee request form |
| Incident Management | Configured categories, priorities, states |

---

## 💡 Key Takeaways

- Hands-on experience configuring and administering a ServiceNow developer instance
- Built end-to-end ITSM workflows without any prior ServiceNow experience
- Combined data analytics background with ServiceNow platform capabilities
- Demonstrated ability to translate business requirements into platform solutions
