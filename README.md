# Requirement Analysis in Software Development

This repository provides a detailed exploration of Requirement Analysis within the Software Development Life Cycle (SDLC). It outlines key activities, the importance of analyzing requirements, types of requirements, and use case diagrams, using a booking management system as a case study.


## What is Requirement Analysis?

Requirement Analysis is the process of identifying, analyzing, documenting, and managing the needs and requirements of stakeholders for a software system. It forms the foundation of software development by ensuring that the final product meets user expectations and business goals.

Requirement Analysis bridges the gap between stakeholders' needs and the technical team's implementation efforts. It involves gathering information, validating requirements, and converting them into detailed documentation for development.

In the SDLC, it plays a vital role by:
- Reducing project risks and misunderstandings
- Ensuring alignment between the software and business goals
- Enabling better design, development, and testing

## Why is Requirement Analysis Important?

1. **Minimizes Costly Mistakes**  
   Clear requirements help avoid rework by ensuring the development team builds the right system from the start.

2. **Enhances Communication**  
   It facilitates communication between stakeholders and developers by creating a common understanding of expectations.

3. **Supports Project Planning**  
   Accurate requirements help define project scope, resources, timelines, and risk mitigation strategies.

## Key Activities in Requirement Analysis

- **Requirement Gathering**  
  Collecting initial information from stakeholders to understand the needs of the system.

- **Requirement Elicitation**  
  Using interviews, questionnaires, observations, and brainstorming to extract detailed requirements.

- **Requirement Documentation**  
  Recording all gathered and elicited requirements in structured formats like SRS (Software Requirements Specification).

- **Requirement Analysis and Modeling**  
  Organizing, analyzing, and creating models (e.g., data flow diagrams, use case diagrams) to represent requirements clearly.

- **Requirement Validation**  
  Ensuring that the documented requirements are complete, accurate, and agreed upon by stakeholders.

## Types of Requirements

### Functional Requirements
These define what the system should do.

**Examples (Booking Management System):**
- Users can create a new booking.
- Admins can add, edit, or delete rooms.
- Users can cancel bookings.
- System sends email confirmation after booking.

### Non-functional Requirements
These define how the system should perform.

**Examples (Booking Management System):**
- The system should respond within 2 seconds under normal load.
- User data must be encrypted and comply with GDPR.
- The website must be available 99.9% of the time.
- The system should support 500 concurrent users.

## Use Case Diagrams

Use Case Diagrams visually represent user interactions with the system and help identify requirements.

They help:
- Understand system functionality
- Clarify user roles and responsibilities
- Serve as a communication tool between developers and stakeholders

![Booking System Use Case Diagram]
<img width="961" height="151" alt="alx-booking-uc drawio" src="https://github.com/user-attachments/assets/cc17267a-121a-4764-9a1d-5901762ffbbc" />


## Acceptance Criteria

Acceptance Criteria are specific, measurable conditions that a software product must meet to be accepted by stakeholders or the product owner. They ensure that requirements are testable, unambiguous, and clearly understood by all parties.

### Example: Checkout Feature Acceptance Criteria

- User must be logged in to access checkout.
- System must display total cost, taxes, and summary of selected booking.
- Payment options must include debit card and bank transfer.
- Confirmation email must be sent after successful payment.
- Booking data must be stored in the database.
