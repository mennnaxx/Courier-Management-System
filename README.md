# Courier Management System (CMS)

* [Overview](#overview)
* [Project Structure](#project-structure)
* [Core Features by Role](#core-features-by-role)
* [Technical Specifications](#technical-specifications)
* [Project Lifecycle](#project-lifecycle)
* [Requirement Gathering](#requirement-gathering)
* [Project Objectives](#project-objectives)
  * [Why — Purpose of the System](#1-why--purpose-of-the-system)
  * [Who — Target Users](#2-who--target-users)
  * [When — When the System is Used](#3-when--when-the-system-is-used)


## Overview
The Courier Management System (CMS) automates and streamlines logistics and delivery operations[cite: 276]. [cite_start]It connects customers, courier staff, delivery personnel, and super admins into a single, cohesive platform for end-to-end parcel management.

## Project Structure

```text
│   README.md
├───1. Context
│       context.png
│       context.svg
├───2. DFD
│       dfd level 0.png
│       dfd level 0.svg
├───3. Use-case
│   │   Use-case diagram.png
│   │   Use-case diagram.svg
│   └───Use-case analysis
│       ├───courir admin
│       │       courir admin.png
│       │       courir admin.svg
│       │       Generate Documents.pdf
│       │       login.pdf
│       │       Search Shipment.pdf
│       │       Update Delivery.pdf
│       ├───customer
│       │       Book Shipment.pdf
│       │       customer.png
│       │       customer.svg
│       │       login.pdf
│       │       Pay Shipping Bills.pdf
│       │       Track Parcel.pdf
│       ├───delivery
│       │       COD.pdf
│       │       delivery.png
│       │       delivery.svg
│       │       login.pdf
│       │       POD.pdf
│       │       Update Delivery.pdf
│       │       View Shipments.pdf
│       └───super admin
│               login.pdf
│               Manage Staff.pdf
│               Reports.pdf
│               super admin.png
│               super admin.svg
│               Update Rates.pdf
├───4. Activity
│       Activity.png
│       Activity.svg
├───5. SSD
│   │   SSD diagram.png
│   │   SSD diagram.svg
│   ├───SSD diagram 1
│   │       SSD diagram 1.png
│   │       SSD diagram 1.svg
│   ├───SSD diagram 2
│   │       SSD diagram 2.png
│   │       SSD diagram 2.svg
│   ├───SSD diagram 3
│   │       SSD diagram 3.png
│   │       SSD diagram 3.svg
│   └───SSD diagram 4
│           SSD diagram 4.png
│           SSD diagram 4.svg
├───6. SD
│   │   Master_Courier_Management.png
│   ├───SD diagram 1 - Login Sequence
│   │       SD diagram 1 - Login Sequence.png
│   │       SD diagram 1 - Login Sequence.svg
│   ├───SD diagram3 - Super Admin
│   │       SD diagram3 - Super Admin.png
│   │       SD diagram3 - Super Admin.svg
│   └───SD diagrams 2 - Courier Admin - Search & Update
│           SD diagrams 2 - Courier Admin - Search & Update .png
│           SD diagrams 2 - Courier Admin - Search & Update .svg
└───7. Class
        Class Diagram.png
        Class Diagram.svg
```
## Core Features by Role

* **Customers:** Book shipments, calculate rates, make secure payments, and track parcels in real-time via GPS.
* **Courier Admin:** Search shipments, update transit statuses/locations, and generate official shipping manifests.
* **Delivery Personnel:** View assigned tasks, update live delivery statuses, collect Cash on Delivery (COD), and capture Proof of Delivery (POD).
* **Super Admin:** Oversee global operations, manage staff and branches, configure service rates, and generate analytical reports.

## Technical Specifications

Built using PHP & MySQL with authentication mechanisms, role-based system operations, and a structured modular design.

## Project Lifecycle

The system was developed through four key phases:
1. **Requirement Gathering:** Defined logistical scope and user needs across all roles.
2. **System Design:** Created UI mockups, logic flows, and database schemas.
3. **Implementation:** Coded frontend interfaces and backend automation for rates and GPS.
4. **Documentation:** Compiled comprehensive records detailing the system's technical implementation and use cases.

# Requirement Gathering

The team gathered both functional and non-functional requirements to define the scope of the **Courier Management System**.  
This phase focused on understanding the logistical needs of all users, including customers, courier admins, delivery personnel, and super admins, ensuring that all shipment tracking and management processes were clearly identified.

---

# Project Objectives

## 1. Why — Purpose of the System

The **Courier Management System** aims to automate and streamline logistics and delivery operations by:

- Reducing manual effort
- Improving operational efficiency
- Ensuring accurate shipment tracking
- Enhancing customer experience
- Providing better administrative control and reporting

### Key Features

- Real-time parcel tracking
- Secure online payments
- Shipment and delivery management
- Automated billing and manifests
- Reporting and analytics tools

---

## 2. Who — Target Users

The system is designed for multiple types of users:

### Customers
- Book shipments
- Track parcels in real time
- Make payments securely
- Manage shipment history

### Courier Admins (Staff / Managers)
- Manage shipment data
- Update parcel status and location
- Generate manifests and bills
- Handle delivery operations

### Super Admins
- Manage branches and staff
- Update pricing and configurations
- Monitor overall system performance
- Analyze reports and statistics

### Delivery Personnel
- Handle parcel deliveries
- Update shipment status using GPS
- Confirm deliveries
- Manage cash-on-delivery operations

---

## 3. When — When the System is Used

The system is utilized throughout the complete shipment lifecycle:

1. **Shipment Booking**
   - Customers create shipment requests and make payments.

2. **Shipment Processing**
   - Staff update shipment details and parcel statuses.

3. **Parcel Transit**
   - Real-time GPS tracking is provided during delivery.

4. **Delivery Confirmation**
   - Delivery personnel confirm successful deliveries and proof of receipt.

5. **Administrative Operations**
   - Reports, analytics, monitoring, and performance management are handled by administrators.

---
