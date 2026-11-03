# Movie Ticket Booking Management System

<p align="center">
  <img src="https://img.shields.io/badge/Platform-Pega-002D72?style=for-the-badge&logo=pega&logoColor=white" alt="Pega Platform"/>
  <img src="https://img.shields.io/badge/App_Studio-Used-0078D4?style=for-the-badge" alt="App Studio"/>
  <img src="https://img.shields.io/badge/Dev_Studio-Used-00BCF2?style=for-the-badge" alt="Dev Studio"/>
  <img src="https://img.shields.io/badge/Case_Management-Enabled-28A745?style=for-the-badge" alt="Case Management"/>
  <img src="https://img.shields.io/badge/Internship-Pega_NIP-FF6F00?style=for-the-badge" alt="Pega NIP"/>
</p>

<p align="center">
  <strong>A Pega-Based Low-Code Solution for End-to-End Movie Ticket Booking Automation</strong>
</p>

<p align="center">
  <a href="#overview">Overview</a> •
  <a href="#features">Features</a> •
  <a href="#case-lifecycle">Case Lifecycle</a> •
  <a href="#platform--tools">Platform & Tools</a> •
  <a href="#application-details">Application Details</a> •
  <a href="#screenshots">Screenshots</a> •
  <a href="#documentation">Documentation</a> •
  <a href="#acknowledgement">Acknowledgement</a> •
  <a href="#author">Author</a>
</p>

---

## Overview

The **Movie Ticket Booking Management System** is a Pega-based case management application developed as part of the **Pega National Internship Program (NIP)**. It automates and streamlines the complete movie ticket booking process — from customer request submission to booking confirmation, ticket processing, and customer notification.

This application leverages Pega's powerful low-code capabilities to demonstrate real-world business process automation, including rule-based decision making, data modeling, service-level agreements (SLAs), and intelligent workflow orchestration.

---

## Features

- **End-to-End Booking Automation** – Seamlessly handles the entire ticket booking lifecycle with minimal manual intervention.
- **Case-Centric Workflow** – Built using Pega's Case Management framework to ensure structured and trackable processes.
- **Real-Time Availability Check** – Validates movie show availability before proceeding to booking.
- **Automated Cost Calculation** – Dynamically calculates ticket prices based on show details and seat selection.
- **Smart Decisioning** – Implements Decision Tables and Business Rules for accurate, rule-driven logic.
- **SLA Tracking** – Monitors each stage of the case lifecycle to ensure timely processing.
- **Automated Notifications** – Keeps customers informed through timely updates at key booking milestones.
- **User-Friendly Interface** – Designed using Pega App Studio for an intuitive and responsive user experience.
- **Data-Driven Design** – Utilizes Pega Data Objects for efficient storage and retrieval of booking-related data.

---

## Case Lifecycle

The `Movie Ticket Request` case follows a well-defined, stage-based lifecycle to ensure a smooth and consistent booking experience:

| Stage | Description |
| --- | --- |
| **1. Request Submission** | Customer initiates a movie ticket request by providing movie, theatre, showtime, and seat preferences. |
| **2. Availability Check** | The system verifies seat availability for the selected show in real-time. |
| **3. Cost Calculation** | Ticket cost is automatically calculated based on show type, number of seats, and applicable charges. |
| **4. Booking Confirmation** | The customer reviews the booking details and confirms the request before final processing. |
| **5. Process Booking** | The system finalizes the booking, allocates seats, and updates availability records. |
| **6. Ticket Issuance & Notification** | A confirmation is generated, and the customer is notified of successful booking details. |

---

## Platform & Tools

| Tool/Platform | Purpose |
| --- | --- |
| **[Pega Platform](https://www.pega.com/)** | Core low-code platform used to build and deploy the application |
| **[Pega App Studio](https://docs.pega.com/)** | Used for designing the user interface, case types, and workflows |
| **[Pega Dev Studio](https://docs.pega.com/)** | Used for advanced configurations, rules, data models, and integrations |
| **[Pega Blueprint](https://www.pega.com/products/pega-blueprint)** | Used for application design, planning, and requirement mapping |
| **[Pega Academy](https://academy.pega.com/)** | Learning resource used to build, test, and validate Pega concepts |

---

## Application Details

| Field | Value |
| --- | --- |
| **Application Name** | Movie Ticket Booking Management |
| **Case Type** | Movie Ticket Request |
| **Project Title** | Movie Ticket Booking Management System |
| **Program** | Pega National Internship Program (NIP) |
| **Developer** | Femina |
| **Platform** | Pega Infinity / Pega Platform |

---

## Screenshots

A glimpse of the application interface and workflow designed during development:

<p align="center">
  <img src="Screenshot%20(860).png" width="800" alt="Movie Ticket Booking Screenshot 1"/>
</p>

<p align="center">
  <img src="Screenshot%20(861).png" width="800" alt="Movie Ticket Booking Screenshot 2"/>
</p>

<p align="center">
  <img src="Screenshot%20(866).png" width="800" alt="Movie Ticket Booking Screenshot 3"/>
</p>

<p align="center">
  <img src="Screenshot%20(867).png" width="800" alt="Movie Ticket Booking Screenshot 4"/>
</p>

<p align="center">
  <img src="Screenshot%20(870).png" width="800" alt="Movie Ticket Booking Screenshot 5"/>
</p>

<p align="center">
  <img src="Screenshot%20(872).png" width="800" alt="Movie Ticket Booking Screenshot 6"/>
</p>

<p align="center">
  <img src="Screenshot%20(879).png" width="800" alt="Movie Ticket Booking Screenshot 7"/>
</p>

<p align="center">
  <img src="Screenshot%20(880).png" width="800" alt="Movie Ticket Booking Screenshot 8"/>
</p>

<p align="center">
  <img src="Screenshot%20(882).png" width="800" alt="Movie Ticket Booking Screenshot 9"/>
</p>

<p align="center">
  <img src="Screenshot%20(883).png" width="800" alt="Movie Ticket Booking Screenshot 10"/>
</p>

<p align="center">
  <img src="Screenshot%20(884).png" width="800" alt="Movie Ticket Booking Screenshot 11"/>
</p>

<p align="center">
  <img src="Screenshot%20(885).png" width="800" alt="Movie Ticket Booking Screenshot 12"/>
</p>

---

## Documentation

The detailed project report is included in this repository:  

[`1_MovieTicketBooking_N_Femina.docx`](1_MovieTicketBooking_N_Femina.docx)

It covers the complete project analysis, case design, rules, workflows, SLAs, and implementation details as per the Pega National Internship Program requirements.

---

## Key Learnings

- Gained hands-on experience with **Pega Case Management** and stage-based workflows
- Implemented **Business Rules**, **Decision Tables**, and **Data Transforms**
- Configured **SLAs** to track case progress and deadlines
- Designed and modeled **Data Objects** for structured data handling
- Applied **UI design principles** using Pega App Studio
- Understood end-to-end **low-code application development** in Pega

---

## Acknowledgement

I would like to express my sincere gratitude to the **Pega Team** and the **National Internship Program (NIP)** coordinators for providing this opportunity to learn, build, and showcase my skills. A special thanks to all mentors who guided me throughout the development of this project.

---

## Author

**Femina**  

[![GitHub](https://img.shields.io/badge/GitHub-Femina23-181717?style=for-the-badge&logo=github)](https://github.com/Femina23)

---

<p align="center">
  <i>Built with Pega Low-Code Platform | Developed as part of Pega National Internship Program</i>
</p>
