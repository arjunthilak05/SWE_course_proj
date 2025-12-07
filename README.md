# Crisis Management System
**For College Campus Emergency Response**

## Overview
The Crisis Management System (CMS) is a comprehensive solution designed to handle emergency situations on college campuses. It provides automated crisis detection, intelligent analysis, and coordinated alert distribution to ensure rapid response and campus safety.

**Version:** 4.0 (IEEE 830 Compliant)  
**Date:** December 5, 2025

## Team Members
- **Arjun Thilak**
- **Anish Sriram B**
- **Gunvant Rao**

## Key Features
- **User Management:** Role-based access for Students, Faculty, Staff, Emergency Operators, and Administrators.
- **Crisis Reporting:** Easy complaint submission with text descriptions, GPS location, and photo uploads.
- **Intelligent Analysis:**
    - **Spam Detection:** ML-based filtering to identify false or duplicate reports.
    - **Crisis Classification:** Automatic categorization (Fire, Medical, Security, Infrastructure, Natural Disaster) and severity assignment.
- **Alert Distribution:** Multi-channel notifications via SMS, automated phone calls, and push notifications based on crisis severity and location.
- **IoT Integration:** Real-time data ingestion from sensors (fire detectors, cameras) to auto-generate alerts.
- **Analytics Dashboard:** Real-time monitoring of active crises, response times, and historical trend analysis.

## System Architecture & Diagrams
The system design is documented through various UML diagrams available in this repository:

- **[Activity Diagram](Activity_Diagram.png):** Workflow of system activities and decision points.
- **[Class Diagram](Class_Diagram.png):** Main entities, attributes, and relationships.
- **[Component Diagram](Component_Diagram.png):** Runtime components and dependencies.
- **[Data Flow Diagram](Data_Flow_Diagram.png):** High-level data movement.
- **[Deployment Diagram](Deployment_Diagram.png):** Physical deployment across hardware nodes.
- **[Entity-Relationship Diagram](ER_Diagram.png):** Database structure.
- **[Package Diagram](Package_Diagram.png):** Modular structure of the application.
- **[Sequence Diagram](Sequence_Diagram_End_to_End.png):** Time-ordered interactions for complaint processing.
- **[State Chart Diagram](State_Chart_Diagram.png):** Lifecycle states of a complaint.
- **[Use Case Diagrams](Use_Case_Interface.png):** Actor interactions with system functions.

## Standards Compliance
- **IEEE 830-1998:** Software Requirements Specifications
- **ISO 22320:2018:** Security and Resilience - Emergency Management
- **WCAG 2.1 Level AA:** Web Content Accessibility
- **OWASP Top 10:** Web Application Security
