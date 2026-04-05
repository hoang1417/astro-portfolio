---
title: Automated Shipment Update
publishDate: 2025-08-01 00:00:00
img: /assets/primaplas/Automated Logistics Data Integration System.png
img_alt: Automated Logistics Data Integration System
description: |
  Automated shipment tracking across multiple ocean carriers by building an end-to-end data integration system, eliminating manual updates for a AU$300M revenue company with over 4,000 shipments every year and improving operational efficiency by 20% while achieving daily service-level updates.
tags:
  - System Integration
  - Automation & Optimisation
  - API and Software
---

> This project replaced a fragmented, manual shipment tracking process with a fully integrated, automated system that delivers reliable, daily shipment visibility at scale — demonstrating how automation and system integration can directly improve operational efficiency and service quality in logistics.

#### Overview

**Automated Shipment Update System**

Replaced a fully manual shipment tracking process with an automated, data-driven system that integrates directly with shipping lines and third-party providers, improving operational visibility and reducing workload for logistics teams across high-volume shipment operations (~4,000 shipments annually).

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

Designed and implemented a scalable, end-to-end shipment tracking and automation system to replace fragmented manual processes:

- Implemented a **hybrid integration approach (API + file-based ingestion)** to accommodate varying capabilities across major shipping lines (OOCL, Maersk) and third-party providers (SeaRates, ShipsGo)  
- Built automated data pipelines to retrieve, validate, and process high-volume shipment status updates in near real-time  
- Designed a centralised processing layer to standardise data and ensure consistency before updating the internal ERP system (SAP)  
- Automated ERP updates to eliminate manual data entry and reduce dependency on logistics staff  
- Developed monitoring and alerting mechanisms to detect key shipment events (e.g. delays) and trigger proactive notifications  

This architecture ensures reliable, scalable, and timely shipment updates across multiple external data sources while maintaining data integrity within internal systems.

---

#### Business Workflow

![Business Workflow Transformation](/assets/primaplas/Business-Workflow-Transformation.png)

---

#### Impact

**Operational Impact**
- ⏱ **20% efficiency gain** (~70 hours/week), removing repetitive manual tracking and data entry tasks  
- ⚡ Reduced update delays from **days/weeks to daily automated updates**  
- 🔁 Eliminated dependency on manual follow-ups with shipping lines  

**Business Impact**
- 📊 Enabled consistent, organisation-wide visibility of shipment status across all active orders  
- 🚚 Improved service reliability by ensuring customers receive timely and accurate updates  
- 🔔 Introduced proactive delay detection, allowing operations teams to respond earlier to potential disruptions  
- 😊 Improved staff experience by removing high-pressure, repetitive manual workloads 

---

#### Tools & Technologies

- **Data & Integration**: SQL, Python, Azure Function App (data pipelines, automation, orchestration)  
- **Storage & Processing**: Azure Blob Storage, MS SQL Server (data ingestion, transformation, storage)  
- **Systems**: SAP (ERP integration), External API integrations  
- **Automation & Communication**: Azure Logic App, Outlook, Microsoft Teams (notifications and reporting)

---

#### Technical Architecture

![Automated Shipment Update Architecture](/assets/primaplas/Automated-Shipment-Update-Architecture.png)

This architecture enables fully automated, daily shipment updates by integrating multiple external data sources into a centralised processing and ERP update pipeline.
