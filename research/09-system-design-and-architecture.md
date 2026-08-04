# System Design and Architecture

## Chapter Overview

This chapter presents the overall design of the Smart Hybrid Library Management and Automation System (SHLMAS). It describes the system architecture, software and hardware components, database structure, workflow, and interaction between users and the system.

The objective of this chapter is to demonstrate how the proposed solution transforms the traditional manual library circulation process into an integrated and automated workflow.

---

# System Overview

SHLMAS is a hybrid library management ecosystem composed of software and hardware modules connected through a centralized database.

Unlike conventional Library Management Systems that focus only on digital record keeping, SHLMAS automates both borrowing and returning workflows while keeping librarians in control of administrative tasks.

The system consists of:

- Student Portal
- Borrowing Kiosk
- Smart Return Box
- Librarian Dashboard
- Central Database
- Analytics & Reporting Module

---

# Overall System Architecture

```
                    Smart Hybrid Library Management System

                             +----------------------+
                             |    Student Portal    |
                             +----------+-----------+
                                        |
                                        |
                             +----------v-----------+
                             |   Central Database   |
                             +----------+-----------+
                                        |
              +-------------------------+-------------------------+
              |                         |                         |
              |                         |                         |
      +-------v------+         +--------v-------+        +--------v--------+
      | Borrow Kiosk |         | Librarian Dash |        | Smart Return Box|
      +--------------+         +----------------+        +-----------------+

```

---

# System Modules

## Student Portal

Purpose

Provide students with online access to library services.

Functions

- Search books
- Check availability
- Reserve books
- Borrow history
- Recommendations

---

## Borrowing Kiosk

Purpose

Allow students to borrow books independently.

Functions

- Authenticate student
- Scan book QR code
- Record borrowing
- Generate due date

---

## Smart Return Box

Purpose

Automatically process returned books.

Functions

- Detect returned book
- Identify borrower
- Update database
- Mark book as available

---

## Librarian Dashboard

Purpose

Provide administrative control.

Functions

- Manage books
- Manage students
- Approve requests
- Generate reports
- View analytics

---

# User Roles

## Student

Permissions

- Search books
- Borrow books
- Reserve books
- View history

---

## Librarian

Permissions

- Full system access
- Inventory management
- Reports
- User management

---

## Teacher

Permissions

- View overdue reports
- Approve restricted borrowing (optional)

---

## SSLG Representative

Permissions

- Receive overdue lists
- Announce reminders to students

---

# System Workflow

## Borrowing Process

```
Student Login

↓

Search Book

↓

Book Available?

↓

Yes

↓

Proceed to Borrowing Kiosk

↓

Authenticate Student

↓

Scan Book QR

↓

Borrow Recorded

↓

Due Date Generated

↓

Book Status Updated
```

---

## Returning Process

```
Insert Book

↓

QR Scanner Detects Book

↓

Borrow Record Located

↓

Return Recorded

↓

Inventory Updated

↓

Book Available Again
```

---

# Database Design

The system uses a centralized relational database.

## Books Table

- Book ID
- QR Code
- Title
- Author
- Subject
- Grade Level
- Shelf
- Status

---

## Students Table

- Student ID
- LRN
- Name
- Grade
- Section

---

## Borrow Records

- Borrow ID
- Student ID
- Book ID
- Borrow Date
- Due Date
- Return Date
- Status

---

## Reservations Table

- Reservation ID
- Student ID
- Book ID
- Queue Position
- Reservation Date
- Status

---

# Hardware Architecture

Prototype Components

- ESP32
- Tablet
- USB QR Scanner
- Smart Return Box
- Local Wi-Fi Network

Future Upgrades

- RFID Reader
- RFID Cards
- RFID Return Bin

---

# Software Architecture

Frontend

- React
- TypeScript
- Tailwind CSS

Backend

- Node.js
- Express.js

Database

- PostgreSQL

Authentication

- JWT Authentication

Deployment

- Docker
- Local School Server

---

# Security Design

The system implements role-based access control.

Students can only access their own borrowing records.

Only librarians may:

- Add books
- Delete books
- Modify inventory
- Generate reports

Passwords are never entered on the public borrowing kiosk.

Authentication is performed through QR code identification.

---

# Recommendation Engine

The recommendation system is rule-based.

Books are recommended according to:

- Same subject
- Same author
- Same grade level
- Frequently borrowed together

This approach minimizes computational requirements while providing useful suggestions.

---

# Analytics Dashboard

The dashboard displays:

- Books borrowed today
- Books returned today
- Active borrowers
- Overdue books
- Lost books
- Popular books
- Subject popularity
- Monthly borrowing trends

---

# Design Principles

The proposed system follows these design principles:

- Simplicity
- Reliability
- Scalability
- Modularity
- Ease of maintenance
- Cost-effectiveness

These principles ensure that SHLMAS remains practical for implementation in secondary schools with limited resources.

---

# Chapter Summary

The Smart Hybrid Library Management and Automation System adopts a modular architecture that integrates software and hardware into a unified ecosystem. Through centralized data management, self-service borrowing, automated book returns, and real-time analytics, the proposed design aims to improve the efficiency and accuracy of library circulation while maintaining librarian supervision.
