# Furniture Workshop Management System (FWMS)

**Student:** Nkurunziza Aimable
**Student ID:** 29692
**Course:** INSY 8311 - Database Development with PL/SQL
**Instructor:** Eric Maniraguha

## Problem Statement
Currently, Kwizera Decor manages all custom furniture orders, material purchases, and worker assignments from memory. This manual process leads to materials being bought twice, customer orders being delayed, and a lack of proper tracking for showroom inventory and finances. As the business grows, this memory-based system is causing financial losses and damaging customer trust.

## Objectives
To design and implement a working Oracle database with PL/SQL that will:
1. Track custom furniture orders from initial request to final delivery.
2. Manage showroom inventory and material procurement to prevent duplicate purchases.
3. Replace the "memory-based" tracking system with reliable, data-driven records.

## Data Source
Primary data collected from real-world business records of Kwizera Decor. 
Website: [https://www.kwizerdecor.com/](https://www.kwizerdecor.com/)

## Innovation
**Option:** Interactive User Interface
**Tool:** Oracle APEX
I will build a web-based dashboard connected directly to the Oracle database. This will allow the showroom attendant to check stock instantly and the boss to view a live dashboard of active orders, production stages, and pending balances, moving the business from memory-based tracking to real-time digital management.

## Planned Tables
- Customers
- Orders (Custom & Showroom)
- Designs
- Materials & Inventory
- Workers (Carpenters/Installers)
- Payments
- Deliveries

## Planned PL/SQL Features
- **Procedures:** To calculate total material costs and process customer deposits.
- **Functions:** To calculate the remaining balance for a customer order.
- **Triggers:** To automatically update inventory levels when materials are used, and an audit log to track order status changes.
- **Packages:** A package to group all order management and inventory functions together.

## Phase I – Business Process Modeling
- **Selected Business Process:** Custom Furniture Order Fulfillment
- **Modeling Tool Used:** draw.io (diagrams.net)
- **Published Diagram Link:** [Click here to view the interactive BPMN [Diagram]()](https://viewer.diagrams.net/?tags=%7B%7D&lightbox=1&highlight=0000ff&edit=_blank&layers=1&nav=1&title=FWMS_Phase1_Diagram.drawio&dark=auto#Uhttps%3A%2F%2Fdrive.google.com%2Fuc%3Fid%3D1NL4AE8yduhPjADR7pBrkKO7Vv9YzBC9U%26export%3Ddownload#%7B%22pageId%22%3A%22wss21I-tk3a3jg7dK66v%22%7D)
- **Supporting Explanation:** [Click here to view the PDF](./docs/business_process/business_process_explanation.pdf)

## References
1. Kwizera Decor. (2026). *Interior Design & Home Decoration in Rwanda*. Retrieved from https://www.kwizerdecor.com/
2. Oracle. (2024). *Oracle Database PL/SQL Language Reference*. 
3. Laudon, K. C., & Laudon, J. P. (2020). *Management Information Systems: Managing the Digital Firm* (16th ed.). Pearson.
4. Elmasri, R., & Navathe, S. B. (2015). *Fundamentals of Database Systems* (7th ed.). Pearson.
