# Requirement Analysis in Software Development

This repository documents the Requirement Analysis phase for a **Booking Management System**.  
The project simulates a real-world scenario, focusing on clarity, precision, and structure in defining requirements to ensure successful software development.

---

## What is Requirement Analysis?

Requirement Analysis is the process of identifying, documenting, and analyzing the needs and expectations of stakeholders for a software system. It ensures that the final product aligns with business goals and user needs.  

In the **Software Development Lifecycle (SDLC)**, Requirement Analysis is a critical early phase that reduces misunderstandings, prevents costly rework, and establishes a solid foundation for design and development.

---

## Why is Requirement Analysis Important?

- **Prevents Scope Creep:** Clearly defined requirements help avoid uncontrolled changes during development.  
- **Improves Communication:** Serves as a common reference between stakeholders, developers, and testers.  
- **Ensures Quality:** Well-defined requirements allow accurate testing and validation of the system.  

---

## Key Activities in Requirement Analysis

- **Requirement Gathering** – Collecting needs from stakeholders through interviews, surveys, and observations.  
- **Requirement Elicitation** – Refining requirements using techniques like brainstorming, workshops, and prototyping.  
- **Requirement Documentation** – Creating formal documents like SRS (Software Requirement Specification).  
- **Requirement Analysis & Modeling** – Structuring and analyzing requirements using diagrams and models.  
- **Requirement Validation** – Ensuring requirements are accurate, complete, and aligned with business goals.  

---

## Types of Requirements

### Functional Requirements
These define **what the system should do**.  
Example for Booking Management System:
- Users can create, update, and cancel bookings.
- Admins can manage available rooms/resources.
- System sends email confirmations upon booking.

### Non-Functional Requirements
These define **how the system performs**.  
Example for Booking Management System:
- System must handle 500 concurrent users.
- Response time for booking confirmation < 2 seconds.
- System uptime should be 99.9%.

---

## Use Case Diagrams

A **Use Case Diagram** visually represents the interactions between users (actors) and the system.  
It helps stakeholders easily understand the scope and functionality of the system.  

![Booking Management Use Case](./alx-booking-uc.png)

**Actors:**
- Customer  
- Admin  
- Payment Gateway  

**Use Cases:**
- Book Room  
- Cancel Booking  
- Update Booking  
- Make Payment  
- Receive Confirmation  

---

## Acceptance Criteria

Acceptance Criteria are specific, measurable conditions that a feature must satisfy to be accepted by stakeholders.  

### Importance:
- Provides clarity on what “done” means.  
- Helps testers validate functionality.  
- Aligns developers and stakeholders on expectations.  

### Example (Checkout Feature):
- User can view a summary of their booking.  
- User must enter valid payment details.  
- System should process payment securely via gateway.  
- Confirmation message and email must be sent after successful payment.  

---
