# Phase 1 — Project Overview

> **Status:** Proposed System Overview

---

# Smart Hybrid Library Management and Automation System (SHLMAS)

## Project Title

**Smart Hybrid Library Management and Automation System (SHLMAS)**

---

# Project Description

The Smart Hybrid Library Management and Automation System (SHLMAS) is a low-cost library automation concept intended for public schools that replaces manual borrowing and returning procedures with an RFID-assisted approach using a hybrid RFID architecture.

Unlike traditional RFID library systems that require every physical book to have its own RFID tag, SHLMAS uses a hybrid RFID architecture consisting of:

- RFID cards representing student identification
- RFID Book Identifier Cards

This approach is intended to minimize hardware costs while still providing a foundation for digital library circulation in a future, expanded system.

The project focuses on supporting common library operations such as borrowing and returning, recording transactions, updating book availability, viewing borrowing history, and monitoring library records — described below as designed functionality rather than features already implemented in the prototype.

---

# Purpose of the Project

The project aims to modernize public school library operations by replacing manual record keeping with an RFID-assisted system concept. The system is intended to reduce paperwork, simplify borrowing procedures, improve record accuracy, and decrease the workload of library personnel when fully developed beyond the prototype stage.

---

# Target Users

The system is intended for:

- Students
- Library-in-Charge Personnel
- Teachers
- School Administrators

---

# Primary Goal

To develop an affordable RFID-assisted library system concept that improves circulation management while remaining practical for schools with limited financial resources.

---

# Core Concept

Instead of attaching an RFID tag to every physical book, SHLMAS uses a separate RFID Book Identifier Card together with an RFID Student ID Card.

A borrowing (or returning) transaction in the proposed system concept is completed by scanning:

1. Student RFID ID
2. RFID Book Identifier Card

At prototype stage, the focus is on validating RFID identification and USB communication between the microcontroller and a laptop; transaction processing and record-keeping remain part of the designed features (see sections below).

---

# Design Philosophy

The project focuses on:

- Low implementation cost
- Simplicity
- Practical deployment
- Ease of use
- Accessibility for public schools

---

# Project Classification

| Category | Value |
|-----------|-------|
| System Type | Library Management System (concept) |
| Automation Type | RFID-assisted |
| Platform | Desktop-assisted Prototype |
| Hardware | ESP32 + RC522 RFID |
| Prototype Communication | USB connection to laptop |
| Internet Requirement (Prototype) | None |
| Deployment Type (Prototype) | Offline |

---

# Prototype Summary

Status: Prototype Demonstration

For the prototype:

- An ESP32 microcontroller is used with an RC522 RFID reader to read RFID UIDs.
- RFID Student Identification Cards and RFID Book Identifier Cards are used as physical identifiers.
- The ESP32 is connected to a laptop over USB for serial communication; the laptop receives raw RFID UIDs for further processing in future development.
- The prototype operates completely offline and is intended to demonstrate the RFID identification and communication process required for transaction recording in future work.

The prototype does NOT include a full library management application, a database, cloud services, Wi‑Fi communication, online synchronization, or an automated borrowing/returning service. Those are designed features or proposed future implementations described in separate sections below.

---

# Key Characteristics

- RFID-assisted identification (prototype)
- Hybrid RFID architecture (concept)
- Offline prototype demonstration (current)

# Phase 2 — Problem Statement

> **Status:** Research Foundation

---

# Background

Many public school libraries still rely on manual processes for managing library circulation. Borrowing and returning books are commonly recorded using handwritten logbooks or paper-based records which slows operations and increases the workload for library personnel.

Manual methods require additional time for recording transactions, checking records, and updating book availability.

---

# Existing Problems

## Manual Borrowing Process

Borrowing books requires library personnel to manually record information such as:

- Student name
- Book title
- Borrowing date
- Return date

This process becomes slower as the number of library users increases.

---

## Manual Return Process

Returning books also requires manual updating of library records. Library personnel must locate previous borrowing records before confirming that a book has been returned.

---

## Time-Consuming Transactions

Because every transaction is recorded manually, borrowing and returning books may take longer than necessary, especially during busy periods.

---

## Human Error

Manual recording increases the possibility of errors such as:

- Incorrect student information
- Incorrect book records
- Missing entries
- Duplicate entries
- Incomplete records

---

## Record Management

Paper-based records become more difficult to manage as library transactions increase. Searching previous borrowing records may require manually checking multiple logbooks.

---

## Library Monitoring

Without digital records, monitoring library activities becomes more difficult. Examples include:

- Current borrowed books
- Returned books
- Borrowing history
- Book availability

---

# Why SHLMAS Was Proposed

SHLMAS was proposed to simplify library circulation by providing a low-cost hybrid RFID approach that can serve as the identification and communication foundation for future digital transaction recording and automation.

At prototype stage, the system demonstrates RFID UID capture and reliable USB serial communication to a laptop; transaction processing is part of the designed system behavior to be implemented later.

---

# Intended Improvement

Compared to manual recording, SHLMAS (when fully developed) intends to provide:

- Faster borrowing transactions (designed)
- Faster return transactions (designed)
- Digital transaction records (designed)
- Easier record management (designed)
- Improved monitoring of borrowed books (designed)
- Reduced manual paperwork (designed)

---

# Scope of the Problem Being Addressed

SHLMAS focuses specifically on improving:

- Library circulation (concept)
- Borrowing (designed)
- Returning (designed)
- Transaction recording (designed)
- Record management (designed)

The prototype does not attempt to solve every aspect of library management; its primary aim is to validate the RFID identification and communication foundation for a future hybrid library management system.

# Phase 3 — Objectives

> **Status:** Project Objectives (Research & Prototype Goals)

---

# General Objective

To develop the SHLMAS concept and a low-cost prototype that demonstrates RFID-assisted identification and USB communication between an ESP32 and a laptop as a basis for future library circulation automation.

---

# Specific Objectives

The project specifically aims to:

## 1. Demonstrate RFID Identification and Communication (Implemented Prototype)

- Show that the RC522 can read RFID UIDs and that the ESP32 can transmit those UIDs to a laptop over USB.

---

## 2. Define Designed Features (System Design)

The following items are part of the system design (intended behavior) but are not implemented in the prototype:

- Borrowing transaction processing
- Returning transaction processing
- Digital transaction records
- Book availability monitoring
- Borrowing history
- Library record management

Whenever these are described in this document they are presented as "designed to", "intended to", or "proposed functionality" rather than implemented features.

---

# Expected Outcome

Upon completion of the prototype phase, SHLMAS is expected to have successfully demonstrated the RFID identification and USB communication needed as the foundation for a future library circulation system.

Future development (proposed final implementation) would implement the designed features listed above.

---

# Project Focus

The objectives of SHLMAS are limited, for the prototype, to validating the hardware and communication chain for RFID-based identification. Designed features and proposed final implementation remain separate and clearly identified in this document.

# Phase 4 — Scope and Limitations

> **Status:** Project Scope (Prototype vs Design)

---

# Scope

The SHLMAS prototype focuses on validating the hybrid RFID approach and the offline USB communication between the ESP32 and a laptop. The prototype demonstrates identification of students and book identifier cards via RFID UIDs.

---

# Included Features (Prototype vs Designed)

## Implemented Prototype (Current)

Only include features that are actually implemented in the prototype:

- ESP32 microcontroller
- RC522 RFID reader
- RFID cards
- RFID Student Identification Cards (RFID cards representing student identification)
- RFID Book Identifier Cards
- USB connection between ESP32 and laptop
- Laptop receiving RFID data over serial
- Offline operation
- RFID scanning and UID reading


## Designed Features (Not Implemented — Described as intended or designed)

Wording for these features uses terms such as "designed to", "intended to", or "proposed functionality":

- Borrowing transaction processing (designed to)
- Returning transaction processing (designed to)
- Digital transaction records (designed to)
- Book availability monitoring (designed to)
- Borrowing history (designed to)
- Library record management (designed to)


## Excluded from the Prototype

The prototype does NOT include (do not claim these as implemented):

- Full library management software
- A database system
- An automated borrowing system
- An automated returning system
- Cloud services
- Wi‑Fi communication
- Online synchronization

---

# Prototype Scope

The prototype specifically consists of:

- ESP32 microcontroller
- RC522 RFID reader
- RFID Student ID Cards
- RFID Book Identifier Cards
- USB connection between ESP32 and laptop
- Completely offline operation
- Laptop receiving RFID UIDs for further processing in future work

---

# Limitations

The current prototype has the following limitations.

## Offline Operation

The prototype operates entirely offline. It does not require Internet, Wi‑Fi, or cloud services.

---

## Single Device Operation

The prototype uses a single ESP32 connected to a single laptop. It is not designed for multiple kiosks or multiple computers during prototype testing.

---

## USB Communication

Communication between the ESP32 and the laptop is performed through a USB cable. No wireless communication is implemented in the prototype.

---

## RFID Usage

RFID is used only for identifying:

- Student ID Cards (RFID cards representing student identification)
- Book Identifier Cards

The prototype does not attach RFID tags directly to physical books.

---

## Prototype Purpose

The prototype is intended to demonstrate the core RFID identification and communication functionality required by SHLMAS. It is not intended to represent the complete proposed implementation of the system.

# Phase 5 — Prototype Hardware

> **Status:** Current Prototype Implementation

---

# Overview

The SHLMAS prototype uses a simple hardware setup designed to demonstrate RFID-assisted identification and USB serial communication while operating completely offline. All processing beyond UID capture is part of the designed system behavior for later implementation.

---

# Hardware Components

## ESP32

### Purpose

The ESP32 serves as the primary microcontroller of the prototype. It is responsible for reading RFID data from the RC522 module and sending RFID UIDs to the laptop through USB serial.

---

## RC522 RFID Reader

### Purpose

The RC522 reads RFID cards used during prototype demonstrations. The reader scans RFID UIDs from both student ID cards and book identifier cards.

---

## RFID Student Identification Card

### Purpose

Each student is represented by an RFID card used as a student identifier. The card is scanned to capture its UID during prototype demonstrations.

---

## RFID Book Identifier Card

### Purpose

Instead of placing a tag on every book, the prototype uses separate RFID Book Identifier Cards to represent selected books during tests. The card is scanned to capture its UID.

---

## Laptop

### Purpose

The laptop serves as the device that receives RFID UIDs from the ESP32 and is the expected place for future prototype software to process those UIDs. At prototype stage the laptop is used to capture and log serial UID messages for validation and testing purposes.

---

## USB Cable

### Purpose

The USB cable provides communication between the ESP32 and the laptop and supplies power to the ESP32.

No wireless communication is used in the prototype.

---

# Hardware Communication

The prototype hardware communicates in the following sequence:

```
RFID Card
      │
      ▼
RC522 RFID Reader
      │
      ▼
ESP32
      │
   USB Cable
      │
      ▼
Laptop
```

This chain represents the implemented data flow for UID capture and serial transmission. It does not imply that transaction processing, database updates, or book status changes occur at the prototype stage.

---

# Hardware Workflow

1. The user taps an RFID card on the RC522 reader.
2. The RC522 reads the RFID UID.
3. The ESP32 receives the UID.
4. The ESP32 sends the UID to the laptop through the USB connection.
5. The laptop receives the UID for inspection, logging, or later processing in future software development.


---

# Prototype Characteristics

| Component | Purpose |
|-----------|---------|
| ESP32 | Reads RFID UIDs and sends them to the laptop |
| RC522 | Reads RFID cards |
| RFID Student ID Card | Represents the student (UID captured) |
| RFID Book Identifier Card | Identifies the selected book (UID captured) |
| Laptop | Receives UID data for validation and future processing |
| USB Cable | Communication and power |

---

# Current Prototype Architecture

```
Student
   │
   ▼
RFID Student ID
   │
   ▼
RC522 RFID Reader
   │
   ▼
ESP32
   │
 USB
   │
   ▼
Laptop
```

The same capture process applies when scanning a RFID Book Identifier Card. The prototype demonstrates UID capture and USB serial transmission only.

---

# Hardware Notes

- The prototype operates completely offline.
- No Wi‑Fi is used.
- No cloud services are used.
- No wireless communication is implemented.
- The ESP32 communicates with the laptop only through a USB connection.

- Low-cost implementation for RFID UID capture
- Demonstrates the communication foundation required for future transaction processing

# Phase 6 — Prototype Software

> **Status:** Prototype Software Design

---

# Overview

The SHLMAS prototype includes a software design for how a laptop-side application could receive RFID UIDs from the ESP32 and use those UIDs in borrowing/returning workflows. The current prototype demonstrates UID capture and serial communication; the full software implementation for processing transactions and storing records is part of the designed features and is not implemented in the prototype.

---

# Software Responsibilities (Design)

The proposed laptop-side software is described here as designed to handle the following when implemented in future development:

- Receive RFID UIDs from the ESP32 via USB serial
- Identify students (based on RFID UIDs)
- Identify books (based on RFID UIDs)
- Process borrowing transactions (designed to)
- Process return transactions (designed to)
- Update book status (designed to)
- Record library transactions (designed to)

When the document describes the software performing these actions it uses wording such as "designed to", "intended to", or "could" to indicate these are planned behaviors and not current prototype features.

---

# Communication Method (Implemented)

The prototype implements USB serial communication between the ESP32 and the laptop. The communication flow implemented in the prototype is:

```
ESP32
   │
USB Serial Connection
   │
Laptop (receives UIDs)
```

No wireless communication is used in the prototype.

---

# Transaction Processing (Designed)

The software design describes how borrowing and returning transactions could be processed after RFID identification. Example phrasing used throughout this document replaces any earlier definitive claims about processing with phrases such as:

- "designed to"
- "intended to"
- "proposed functionality"

Examples of revised phrasing applied in this repository's documentation:

- Replace strong claims like "The system automates borrowing and returning" with "The system is designed to support RFID-assisted borrowing and returning transactions."
- Replace "The prototype records transactions" with "The prototype is designed to demonstrate the RFID identification and communication process required for transaction recording."
- Replace "The software processes borrowing and returning transactions" with "The software design describes how borrowing and returning transactions could be processed after RFID identification."

---

# Transaction Records (Designed)

The prototype is not a full transaction-recording system. The design describes storing digital records for transactions in future development; the prototype demonstrates the RFID UID capture and serial messaging needed by such a system.

---

# Prototype Notes

- The software design exists to guide future implementation.
- The current prototype software component should be considered a UID receiver and logger rather than a complete library management application.

# Phase 7 — Prototype Workflow

> **Status:** Prototype Demonstration Workflow

---

# Overview

The SHLMAS prototype follows a simple RFID-assisted demonstration workflow for UID capture and serial transmission. Each physical scan sequence implemented in the prototype results in one or more RFID UIDs being sent from the ESP32 to the laptop via USB serial.

Only the UID capture and communication are implemented; transaction completion, database updates, or book status changes are designed features for future work.

---

# Prototype Workflow (Implemented)

1. Scan RFID Student Identification Card (UID captured by RC522)
2. ESP32 sends the Student UID to the laptop over USB serial
3. Scan RFID Book Identifier Card (UID captured by RC522)
4. ESP32 sends the Book Identifier UID to the laptop over USB serial
5. The laptop receives the UIDs for logging, inspection, or later processing in future software development


---

# Prototype Data Flow (Implemented)

```
RFID Card
     │
     ▼
RC522
     │
     ▼
ESP32
     │
 USB Serial
     │
     ▼
Laptop (receives UIDs)
```

This data flow represents the implemented prototype behavior and intentionally omits downstream transaction processing steps (such as database updates or book status changes), which are part of the Designed Features or Proposed Final Implementation.

---

# Phase 8 — Proposed Final Implementation

> **Status:** Future Development Concept

---

# Overview

This section describes a possible expansion and future deployment concept for SHLMAS. The items below are proposals for future development and are NOT implemented in the current prototype.

---

# Proposed Final Implementation (Future)

As a future expansion, the system could be developed into a full library management application that implements the Designed Features described earlier (borrowing/return processing, transaction records, book availability monitoring, borrowing history, and library record management). Such a final implementation would be considered a separate project stage and is included here only as a development concept.

---

# Closing Notes

This document has been revised to clearly separate implemented prototype features (current), designed features (planned behavior), and proposed final implementation (future development). The prototype demonstrates the RFID identification and USB serial communication foundation required by SHLMAS while leaving transaction processing and persistent record management to later development efforts.
