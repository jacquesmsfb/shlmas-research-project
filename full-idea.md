# Phase 1 — Project Overview

> **Status:** Proposed System Overview

---

# Smart Hybrid Library Management and Automation System (SHLMAS)

## Project Title

**Smart Hybrid Library Management and Automation System (SHLMAS)**

---

# Project Description

The **Smart Hybrid Library Management and Automation System (SHLMAS)** is a low-cost library automation system designed for public schools that replaces manual borrowing and returning procedures with a hybrid RFID approach intended to reduce paperwork and simplify record keeping.

Unlike traditional RFID library systems that require every physical book to have its own RFID tag, SHLMAS uses a **hybrid RFID architecture** consisting of:

- RFID cards representing student identification
- RFID Book Identifier Cards

This approach minimizes hardware costs while still providing digital library circulation.

The system is designed to automate common library operations such as:

- Borrowing books
- Returning books
- Recording transactions
- Updating book availability
- Viewing borrowing history
- Monitoring library records

while remaining significantly more affordable than commercial RFID library systems.

---

# Purpose of the Project

The project aims to modernize public school library operations by replacing manual record keeping with an RFID-assisted digital circulation system.

The system is intended to reduce paperwork, simplify borrowing procedures, improve record accuracy, and decrease the workload of library personnel.

---

# Target Users

The system is intended for:

- Students
- Library-in-Charge Personnel
- Teachers
- School Administrators

---

# Primary Goal

To develop an affordable RFID-assisted library automation system that improves circulation management while remaining practical for schools with limited financial resources.

---

# Core Concept

Instead of attaching an RFID tag to every physical book, SHLMAS uses a separate RFID Book Identifier Card together with an RFID Student ID Card.

A borrowing transaction is completed by scanning:

1. Student RFID ID
2. RFID Book Identifier Card

The system is designed to record the borrowing transaction digitally.

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
| System Type | Library Management System |
| Automation Type | RFID-assisted |
| Platform | Desktop-assisted Prototype |
| Hardware | ESP32 + RC522 RFID |
| Prototype Communication | USB connection to laptop |
| Internet Requirement (Prototype) | None |
| Deployment Type (Prototype) | Offline |

---

# Prototype Summary

For the prototype:

- ESP32 connects directly to a laptop using USB.
- The laptop performs processing and stores the records (prototype design).
- The prototype operates completely offline.
- RFID is used only for identifying students and book identifier cards.

No Wi-Fi or cloud communication is used in the prototype.

---

# Key Characteristics

- RFID-assisted circulation
- Hybrid RFID architecture
- Offline prototype

# Phase 2 — Problem Statement

> **Status:** Research Foundation

---

# Background

Many public school libraries still rely on manual processes for managing library circulation. Borrowing and returning books are commonly recorded using handwritten logbooks or paper-based records which increases workload and the chance of human error.

These manual methods require library personnel to spend additional time recording transactions, checking records, and updating book availability.

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

Returning books also requires manual updating of library records.

Library personnel must locate previous borrowing records before confirming that a book has been returned.

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

Paper-based records become more difficult to manage as library transactions increase.

Searching previous borrowing records may require manually checking multiple logbooks.

---

## Library Monitoring

Without digital records, monitoring library activities becomes more difficult.

Examples include:

- Current borrowed books
- Returned books
- Borrowing history
- Book availability

---

# Why SHLMAS Was Proposed

The Smart Hybrid Library Management and Automation System (SHLMAS) was proposed to simplify library circulation by digitally recording transactions using RFID technology.

Instead of manually writing borrowing records, the system is designed to record transactions after scanning:

- RFID Student ID
- RFID Book Identifier Card

This reduces the amount of manual recording required during library operations.

---

# Intended Improvement

Compared to manual recording, SHLMAS aims to provide:

- Faster borrowing transactions
- Faster return transactions
- Digital transaction records
- Easier record management
- Improved monitoring of borrowed books
- Reduced manual paperwork

---

# Scope of the Problem Being Addressed

SHLMAS focuses specifically on improving:

- Library circulation
- Borrowing
- Returning
- Transaction recording
- Record management

The project does not attempt to solve every aspect of library management. Its primary focus is the automation of circulation using a low-cost hybrid RFID approach.

# Phase 3 — Objectives

> **Status:** Project Objectives

---

# General Objective

To develop the **Smart Hybrid Library Management and Automation System (SHLMAS)** that automates library circulation through a low-cost hybrid RFID approach, replacing manual borrowing and returning record-keeping.

---

# Specific Objectives

The project specifically aims to:

## 1. Automate Borrowing Transactions

Develop a borrowing process that digitally records library transactions after scanning:

- RFID Student ID Card
- RFID Book Identifier Card

instead of requiring manual logbook entries.

---

## 2. Automate Returning Transactions

Develop a returning process that updates the transaction record digitally when a borrowed book is returned.

---

## 3. Digitally Record Library Transactions

Create a digital transaction record for every borrowing and returning activity performed within the system.

---

## 4. Monitor Book Availability

Allow the system to keep track of whether a book is currently:

- Available
- Borrowed

based on recorded transactions.

---

## 5. Maintain Borrowing Records

Store digital records of library transactions.

---

## 6. Reduce Manual Recording

Minimize the need for manual paperwork during library circulation by replacing handwritten recording with RFID-assisted digital logging.

---

## 7. Utilize a Hybrid RFID Approach

Implement a hybrid RFID architecture that uses:

- RFID Student Identification Cards
- RFID Book Identifier Cards

instead of attaching RFID tags directly to every physical book.

This approach is intended to reduce implementation cost while maintaining digital transaction recording.

---

# Expected Outcome

Upon completion, SHLMAS is expected to provide a functional RFID-assisted library circulation system capable of:

- Recording borrowing transactions digitally
- Recording return transactions digitally
- Updating book availability (designed)
- Maintaining borrowing records
- Reducing manual recording during library circulation

---

# Project Focus

The objectives of SHLMAS are limited to improving the library circulation process through RFID-assisted automation.

The project focuses on:

- Borrowing
- Returning
- Transaction recording
- Book status monitoring
- Digital record management

within the scope of the proposed library management system.

# Phase 4 — Scope and Limitations

> **Status:** Project Scope

---

# Scope

The Smart Hybrid Library Management and Automation System (SHLMAS) focuses on automating the library circulation process using a hybrid RFID approach.

The system is designed to manage borrowing and returning transactions by identifying both the student and the selected book through RFID cards.

For the prototype, the system operates completely offline using an ESP32 connected directly to a laptop through USB.

---

# Included Features

The project includes the following functions:

## Library Circulation

- Borrow books
- Return books
- Record borrowing transactions (designed)
- Record return transactions (designed)

---

## RFID Identification

The system identifies:

- Students using RFID cards representing student identification
- Books using RFID Book Identifier Cards

Both RFID cards are scanned during library transactions.

---

## Transaction Recording

The system is designed to record transaction information digitally instead of requiring handwritten logbooks.

Recorded transactions are stored on the laptop during the prototype.

---

## Book Status

The system is designed to update book status based on recorded transactions.

Book status includes:

- Available
- Borrowed

---

## Borrowing Records

The system is designed to maintain digital borrowing records for library transactions completed through the RFID system.

---

# Prototype Scope

The prototype specifically consists of:

- ESP32 microcontroller
- RC522 RFID reader
- RFID Student ID Cards (RFID cards representing student identification)
- RFID Book Identifier Cards
- USB connection between ESP32 and laptop
- Completely offline operation

The laptop performs the processing and stores the transaction records during prototype testing.

---

# Intended Users

The prototype is intended to be used by:

- Students
- Library-in-Charge Personnel

---

# Limitations

The current prototype has the following limitations.

## Offline Operation

The prototype operates entirely offline.

It does not require:

- Internet connection
- Wi-Fi
- Cloud services

---

## Single Device Operation

The prototype uses a single ESP32 connected to a single laptop.

It is not designed for multiple kiosks or multiple computers during prototype testing.

---

## USB Communication

Communication between the ESP32 and the laptop is performed through a USB cable.

No wireless communication is implemented in the prototype.

---

## RFID Usage

RFID is used only for identifying:

- Student ID Cards (RFID cards representing student identification)
- Book Identifier Cards

The prototype does not attach RFID tags directly to physical books.

---

## Prototype Purpose

The prototype is intended to demonstrate the core functionality of SHLMAS, specifically:

- RFID-based identification
- Digital borrowing (designed)
- Digital returning (designed)
- Offline transaction recording

It is not intended to represent the complete proposed implementation of the system.

# Phase 5 — Prototype Hardware

> **Status:** Prototype (Current Implementation)

---

# Overview

The SHLMAS prototype uses a simple hardware setup designed to demonstrate RFID-assisted library circulation while operating completely offline.

All processing is performed through a laptop connected directly to the ESP32 using a USB cable.

---

# Hardware Components

## ESP32

### Purpose

The ESP32 serves as the primary microcontroller of the prototype.

It is responsible for:

- Reading RFID data from the RC522 module
- Sending RFID data to the laptop through USB

---

## RC522 RFID Reader

### Purpose

The RC522 reads RFID cards used during borrowing and returning transactions.

The reader scans:

- RFID cards representing student identification
- RFID Book Identifier Cards

---

## RFID Student Identification Card

### Purpose

Each student is represented by an RFID card used as a student identifier.

The card is scanned before completing a borrowing or returning transaction.

---

## RFID Book Identifier Card

### Purpose

Instead of placing an RFID tag directly on every book, the prototype uses a separate RFID Book Identifier Card.

The card represents the selected book during a transaction.

It is scanned after the Student ID Card.

---

## Laptop

### Purpose

The laptop serves as the processing device for the prototype.

It is responsible for:

- Receiving RFID data from the ESP32
- Processing transactions (prototype software)
- Storing transaction records (prototype testing)
- Running the prototype software

---

## USB Cable

### Purpose

The USB cable provides:

- Communication between the ESP32 and the laptop
- Power to the ESP32

No wireless communication is used in the prototype.

---

# Hardware Communication

The prototype hardware communicates in the following sequence:

```text
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

---

# Hardware Workflow

1. The user taps an RFID card on the RC522 reader.
2. The RC522 reads the RFID UID.
3. The ESP32 receives the UID.
4. The ESP32 sends the UID to the laptop through the USB connection.
5. The laptop processes the transaction (prototype software).

---

# Prototype Characteristics

| Component | Purpose |
|-----------|---------|
| ESP32 | Reads RFID data and sends it to the laptop |
| RC522 | Reads RFID cards |
| RFID Student ID Card | Represents the student (RFID card) |
| RFID Book Identifier Card | Identifies the selected book |
| Laptop | Processes transactions and stores records (prototype) |
| USB Cable | Communication and power |

---

# Current Prototype Architecture

```text
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

The same process is used when scanning the RFID Book Identifier Card.

---

# Hardware Notes

- The prototype operates completely offline.
- No Wi-Fi is used.
- No cloud services are used.
- No wireless communication is implemented.
- The ESP32 communicates with the laptop only through a USB connection.

- Low-cost implementation
- Digital transaction recording (designed)
- Designed for public school libraries

# Phase 6 — Prototype Software

> **Status:** Prototype (Current Implementation)

---

# Overview

The SHLMAS prototype uses software running on a laptop to process RFID data received from the ESP32 through a USB connection.

The prototype software is designed to process RFID data and to store transaction-related information while operating completely offline.

---

# Software Responsibilities

The prototype software is designed to:

- Receive RFID data from the ESP32
- Identify students (based on RFID UIDs)
- Identify books (based on RFID UIDs)
- Process borrowing transactions (designed)
- Process return transactions (designed)
- Update book status (designed)
- Record library transactions (designed)

---

# Communication Method

The prototype software communicates with the ESP32 through a USB connection.

Communication flow:

```text
ESP32
   │
USB Serial Connection
   │
Laptop Software
```

No wireless communication is used.

---

# Transaction Processing

After receiving RFID data from the ESP32, the software determines whether the scanned card belongs to:

- A student
- A book identifier

The software then processes the appropriate library transaction according to the prototype design.

---

# Borrowing Process

For a borrowing transaction, the software is designed to perform the following tasks:

1. Receive the Student RFID UID.
2. Receive the Book Identifier RFID UID.
3. Match both records.
4. Record the borrowing transaction (designed).
5. Update the book status to **Borrowed** (designed).

---

# Returning Process

For a return transaction, the software is designed to perform the following tasks:

1. Receive the Student RFID UID.
2. Receive the Book Identifier RFID UID.
3. Locate the active borrowing record (designed).
4. Record the return transaction (designed).
5. Update the book status to **Available** (designed).

---

# Transaction Records

The software is designed to store digital records for each processed transaction.

Each transaction represents either:

- Borrowing
- Returning

---

# Book Status

The software is designed to maintain the current status of registered books.

Possible states include:

- Available
- Borrowed

The status is intended to change based on processed transactions.

---

# Prototype Characteristics

| Feature | Prototype |
|----------|-----------|
| Offline Operation | ✔ |
| USB Communication | ✔ |
| Student Identification | ✔ |
| Book Identification | ✔ |
| Borrowing Transactions | Designed |
| Returning Transactions | Designed |
| Digital Transaction Records | Designed |
| Automatic Book Status Updates | Designed |
| Wi-Fi | ✘ |
| Cloud Database | ✘ |
| Online Synchronization | ✘ |

---

# Software Workflow

```text
RFID Card
     │
     ▼
RC522 Reader
     │
     ▼
ESP32
     │
 USB Serial
     │
     ▼
Laptop Software
     │
     ├── Identify Student
     ├── Identify Book
     ├── Process Transaction
     ├── Update Book Status
     └── Save Transaction Record
```

---

# Prototype Notes

- The software operates entirely offline.
- All processing is performed on the laptop.
- The ESP32 functions only as the RFID-reading microcontroller.
- No internet connection is required during prototype operation.

# Phase 7 — Prototype Workflow

> **Status:** Prototype (Current Implementation)

---

# Overview

The SHLMAS prototype follows a simple RFID-assisted workflow for library circulation.

Each transaction is completed by scanning:

1. RFID Student Identification Card
2. RFID Book Identifier Card

The laptop then processes the transaction after receiving the RFID data from the ESP32 through USB.

---

# Overall Workflow

```text
Student
    │
    ▼
Scan RFID Student ID
    │
    ▼
ESP32 receives Student UID
    │
    ▼
Send UID to Laptop (USB)
    │
    ▼
Scan RFID Book Identifier Card
    │
    ▼
ESP32 receives Book UID
    │
    ▼
Send UID to Laptop (USB)
    │
    ▼
Laptop Processes Transaction (prototype software)
    │
    ▼
Update Book Status (designed)
    │
    ▼
Save Transaction Record (designed)
```

---

# Borrowing Workflow

## Step 1

The student scans their RFID Student Identification Card.

---

## Step 2

The RC522 reads the RFID UID.

---

## Step 3

The ESP32 receives the UID.

---

## Step 4

The ESP32 sends the UID to the laptop through USB.

---

## Step 5

The student scans the RFID Book Identifier Card.

---

## Step 6

The RC522 reads the Book Identifier UID.

---

## Step 7

The ESP32 sends the Book Identifier UID to the laptop.

---

## Step 8

The laptop processes the borrowing transaction (prototype software).

---

## Step 9

The system records the transaction after processing.

---

## Step 10

The selected book is intended to be marked as:

**Borrowed**

---

# Return Workflow

The return process follows the same sequence.

## Step 1

Scan RFID Student Identification Card.

---

## Step 2

ESP32 sends the Student UID to the laptop.

---

## Step 3

Scan RFID Book Identifier Card.

---

## Step 4

ESP32 sends the Book Identifier UID to the laptop.

---

## Step 5

The laptop locates the active borrowing record (designed).

---

## Step 6

The system records the transaction as returned after processing.

---

## Step 7

The book status is intended to be set to:

**Available**

---

# Prototype Data Flow

```text
Student
      │
      ▼
RFID Student ID
      │
      ▼
RC522
      │
      ▼
ESP32
      │
 USB
      │
      ▼
Laptop
      │
      ├── Student Identification
      ├── Book Identification
      ├── Borrow / Return Processing (designed)
      ├── Book Status Update (designed)
      └── Transaction Recording (designed)
```

---
