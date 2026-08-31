# 🎬 Movie Ticket Booking Management

## 📌 Project Overview

Movie Ticket Booking Management is a Pega-based application developed as part of the National Internship Program (NIP).

The application manages the complete movie ticket booking lifecycle, starting from customer request submission and continuing through show availability verification, cost calculation, booking confirmation, ticket processing, and customer notification.

The project demonstrates the use of Pega case management, data objects, business rules, decision tables, SLA configuration, and automated workflow processing.

---

## 🛠️ Platform & Tools

- Pega Platform
- Pega App Studio
- Pega Dev Studio
- Pega Academy
- Pega Blueprint

---

## 📋 Application Details

- **Application Name:** Movie Ticket Booking Management
- **Case Type:** Movie Ticket Request
- **Project:** Movie Ticket Booking
- **Program:** Pega National Internship Program (NIP)

---

## 🔄 Case Lifecycle

The **Movie Ticket Request** case is designed with the following primary stages:

1. Request Submission
2. Availability Check
3. Cost Calculation
4. Booking Confirmation
5. Process Booking
6. Notify Customer

The application also contains alternate stages for handling exceptional booking scenarios.

---

## 🔁 Application Workflow

The overall booking workflow is:

**Customer Request**
⬇️  
**Request Submission**
⬇️  
**Availability Check**
⬇️  
**Cost Calculation**
⬇️  
**Booking Confirmation**
⬇️  
**Process Booking**
⬇️  
**Notify Customer**
⬇️  
**Case Resolution**

### 1️⃣ Request Submission

The booking process begins when the customer submits a Movie Ticket Request.

The application captures booking information such as:

- Attendee
- Movie Name
- Show Date
- Show Time
- Ticket Quantity
- Show Type
- Discount Code

Required-field validation is applied before the case proceeds to the next stage.

### 2️⃣ Availability Check

The application checks the selected show's availability before continuing with the booking.

This stage handles:

- Fetching show information
- Evaluating seat availability
- Checking available seat count
- Updating Seat Availability Status

The booking proceeds when seats are available.

### 3️⃣ Cost Calculation

The application calculates the booking amount automatically based on the ticket price and requested ticket quantity.

**Formula:**

`Total Cost = Ticket Price × Ticket Quantity`

Example:

`$150 × 2 Tickets = $300`

This reduces manual calculation and ensures that the booking amount is generated consistently.

### 4️⃣ Booking Confirmation

The booking details are presented to the customer for review.

The summary includes:

- Movie Name
- Show Date
- Show Time
- Show Type
- Ticket Quantity
- Ticket Price
- Total Cost
- Payment Method
- Booking Status

The application also contains alternate stages such as **Rejected Request** for handling bookings that do not proceed through the normal confirmation flow.

### 5️⃣ Process Booking

After confirmation, the application processes the ticket booking.

This stage performs activities such as:

- Lock Seats
- Generate Booking ID / Ticket ID
- Update booking information
- Assign Seat Numbers
- Update Booking Confirmation Status
- Route the booking based on Show Type

A Decision Table is used to support show-type-based routing.

### 6️⃣ Notify Customer

After the booking is processed, the application executes the customer notification stage.

The notification contains relevant booking information such as:

- Case ID
- Movie Name
- Show details
- Booking confirmation information

The case then reaches completion.

---

## 🧠 Business Rules & Automation

The application uses Pega business rules and workflow automation to reduce manual processing.

### Automatic Cost Calculation

The **Compute Booking Total** step calculates:

`Total Cost = Ticket Price × Ticket Quantity`

### Show Availability

Seat availability information is evaluated before the booking continues.

The application maintains:

- Seat Availability Status
- Available Seats Count

### Show-Type Routing

The **RouteBookingRequestByShowType** Decision Table is used for routing booking requests.

- Premium → Premium Show Queue
- Special → Premium Show Queue
- Other Show Types → Standard Show Queue

### Service Level Agreement (SLA)

A Custom SLA is configured for the Booking Confirmation stage.

- **Goal:** 1 Day
- **Deadline:** 2 Days
- **Urgency Increase:** +10

This helps prioritize booking requests that are approaching their processing deadline.

---

## 🗃️ Data Management

A reusable **Movie** data object is used to maintain movie-related information.

It includes properties such as:

- Movie Title
- Genre
- Director
- Duration
- Release Date
- Country of Origin
- Certification
- Language
- Cast
- Production Company
- Synopsis
- Trailer URL
- Movie Poster
- Average Rating
- Show List

The data object is linked with the Movie Ticket Request case for reusable movie and show information.

---

## ✨ Key Features

- Movie ticket request submission
- Required-field validation
- Movie and show information management
- Show availability checking
- Seat availability verification
- Automatic ticket cost calculation
- Booking summary and confirmation
- Seat assignment
- Ticket ID generation
- Booking processing
- Decision Table based routing
- Customer notification
- Custom SLA configuration
- Alternate-stage handling

---

## 🎟️ Sample Booking

| Field | Sample Value |
|---|---|
| Movie Name | Cosmic Adventure |
| Show Type | IMAX |
| Show Date | 15 September 2026 |
| Show Time | 3:00 PM |
| Seat Numbers | A1, A2 |
| Ticket Price | $150 |
| Ticket Quantity | 2 |
| Total Cost | $300 |
| Seat Availability | Available |
| Booking Status | Confirmed |
| Payment Method | Credit Card |

---

## 🏆 Project Result

The primary **Movie Ticket Request** workflow was successfully configured and tested in Pega.

The application demonstrates an end-to-end booking process covering request submission, availability verification, automated cost calculation, booking confirmation, ticket processing, routing, and customer notification.

The project also demonstrates practical implementation of Pega concepts including:

- Case Types
- Stages and Steps
- Data Objects
- Business Rules
- Decision Tables
- SLA Configuration
- Workflow Automation
- Alternate Stages

---

## 🎓 National Internship Program

This project was developed as part of the **Pega National Internship Program (NIP)** to demonstrate practical knowledge of application development and case management using the Pega Platform.

---

## 👩‍💻 Author

**N Femina**
