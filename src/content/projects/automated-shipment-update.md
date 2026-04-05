---
title: Automated Shipment Update
publishDate: 2025-08-01 00:00:00
img: /assets/primaplas/Automated Logistics Data Integration System.png
img_alt: Automated Logistics Data Integration System
description: |
  Automated shipment tracking across multiple ocean carriers by building an end-to-end data integration system, eliminating manual updates for a AU$300M revenue company and improving operational efficiency by 20% while achieving daily service-level updates.
tags:
  - System Integration
  - Automation & Optimisation
  - API and Software
---

#### Overview

**Automated Shipment Update System**

Replaced a fully manual shipment tracking process with an automated, data-driven system that integrates directly with shipping lines and third-party providers, improving operational visibility and reducing workload for logistics teams.

---

#### Problem

Shipment updates were previously handled manually by the logistics team:

- Manual data entry accounted for ~20% of daily workload  
- Updates were often delayed by days or even weeks  
- High dependency on staff to track and follow up shipment statuses  
- Limited visibility for both internal teams and customers  

This created operational inefficiencies and made it difficult to maintain a consistent service level.

---

#### Before vs After

- **Before:** Manual shipment updates consuming ~20% of logistics workload, with frequent delays  
- **After:** Fully automated daily updates and notifications, reducing manual workload and improving efficiency by 20%  

---

#### Solution

Designed and implemented an automated shipment tracking and update system:

- Integrated directly with major shipping lines (OOCL, Maersk) and third-party data providers (SeaRate, Shipsgo) via APIs  
- Built data pipelines to retrieve and process shipment updates in near real-time  
- Automated updates into the internal ERP system (SAP)  
- Implemented monitoring and alerting for key shipment events (e.g. delays)  

The solution replaces manual tracking with a scalable, automated workflow that ensures data consistency and timeliness.

---

#### Outcomes

- Fully eliminated manual shipment update processes  
- Achieved **daily update service level** (maximum frequency supported by shipping lines)  
- Provided up-to-date shipment visibility for both operations and customer service teams  
- Enabled proactive monitoring of delayed shipments  

---

#### Impact & Relevance

- ⏱ **20% efficiency gain** by removing manual workload from logistics staff  
- 📉 Reduced delays and improved reliability of shipment information  
- 📊 Enhanced operational visibility with automated reporting and alerts  
- 😊 Improved staff experience by eliminating repetitive, high-pressure manual updates  

This project demonstrates the application of automation and system integration to modernise logistics operations, replacing manual processes with scalable, data-driven workflows.

---

#### Tools & Technologies

- **Data & Integration**: SQL, Python, Azure Function App
- **Storage & Processing**: Azure Blob Storage, MS SQL Server  
- **Systems**: SAP (ERP integration), API integration
- **Automation & Communication**: Azure Logic App, Outlook Emails, Teams Notifications

---

#### Business Workflow

![Business Workflow Transformation](/assets/primaplas/Business-Workflow-Transformation.png)

---

#### Technical Architecture

![Automated Shipment Update Architecture](/assets/primaplas/Automated-Shipment-Update-Architecture.png)

This architecture enables fully automated, daily shipment updates by integrating multiple external data sources into a centralised processing and ERP update pipeline.