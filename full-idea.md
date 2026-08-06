# Phase 1 — Project Overview

> **Status:** Proposed System Overview

---

# Smart Hybrid Library Management and Automation System (SHLMAS)

## Project Title

**Smart Hybrid Library Management and Automation System (SHLMAS)**

---

# Project Description

The **Smart Hybrid Library Management and Automation System (SHLMAS)** is a low-cost library automation system designed for public schools that replaces manual borrowing and returning procedures with RFID-based digital transactions.

Unlike traditional RFID library systems that require every physical book to have its own RFID tag, SHLMAS uses a **hybrid RFID architecture** consisting of:

- RFID-enabled Student Identification Cards
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

The system then records the borrowing transaction digitally.

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
- The laptop performs processing and stores the records.
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

Many public school libraries still rely on manual processes for managing library circulation. Borrowing and returning books are commonly recorded using handwritten logbooks or paper-based records.

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

Instead of manually writing borrowing records, the system automatically records transactions after scanning:

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

To develop the **Smart Hybrid Library Management and Automation System (SHLMAS)** that automates library circulation through a low-cost hybrid RFID approach, replacing manual borrowing and returning records with digital transactions.

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

Provide digital records of borrowing transactions that can be viewed by authorized users instead of relying on handwritten logs.

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
- Updating book availability
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
- Record borrowing transactions
- Record return transactions

---

## RFID Identification

The system identifies:

- Students using RFID Student Identification Cards
- Books using RFID Book Identifier Cards

Both RFID cards are scanned during library transactions.

---

## Transaction Recording

The system records transaction information digitally instead of requiring handwritten logbooks.

Recorded transactions are stored on the laptop during the prototype.

---

## Book Status

The system updates the status of books based on completed transactions.

Book status includes:

- Available
- Borrowed

---

## Borrowing Records

The system maintains digital borrowing records for library transactions completed through the RFID system.

---

# Prototype Scope

The prototype specifically consists of:

- ESP32 microcontroller
- RC522 RFID reader
- RFID Student ID Cards
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

- Student ID Cards
- Book Identifier Cards

The prototype does not attach RFID tags directly to physical books.

---

## Prototype Purpose

The prototype is intended to demonstrate the core functionality of SHLMAS, specifically:

- RFID-based identification
- Digital borrowing
- Digital returning
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

- RFID Student Identification Cards
- RFID Book Identifier Cards

---

## RFID Student Identification Card

### Purpose

Each student is identified using an RFID-enabled Student ID Card.

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
- Processing transactions
- Storing transaction records
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
5. The laptop processes the transaction.

---

# Prototype Characteristics

| Component | Purpose |
|-----------|---------|
| ESP32 | Reads RFID data and sends it to the laptop |
| RC522 | Reads RFID cards |
| RFID Student ID Card | Identifies the student |
| RFID Book Identifier Card | Identifies the selected book |
| Laptop | Processes transactions and stores records |
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
- Digital transaction recording
- Designed for public school libraries

# Phase 6 — Prototype Software

> **Status:** Prototype (Current Implementation)

---

# Overview

The SHLMAS prototype uses software running on a laptop to process RFID data received from the ESP32 through a USB connection.

The software handles library transactions and stores digital records while operating completely offline.

---

# Software Responsibilities

The prototype software is responsible for:

- Receiving RFID data from the ESP32
- Identifying students
- Identifying books
- Processing borrowing transactions
- Processing return transactions
- Updating book status
- Recording library transactions

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

The software then processes the appropriate library transaction.

---

# Borrowing Process

For a borrowing transaction, the software performs the following tasks:

1. Receive the Student RFID UID.
2. Receive the Book Identifier RFID UID.
3. Match both records.
4. Record the borrowing transaction.
5. Update the book status to **Borrowed**.

---

# Returning Process

For a return transaction, the software performs the following tasks:

1. Receive the Student RFID UID.
2. Receive the Book Identifier RFID UID.
3. Locate the active borrowing record.
4. Record the return transaction.
5. Update the book status to **Available**.

---

# Transaction Records

The software stores digital records for each completed transaction.

Each transaction represents either:

- Borrowing
- Returning

---

# Book Status

The software maintains the current status of every registered book.

Possible states include:

- Available
- Borrowed

The status changes automatically after each completed transaction.

---

# Prototype Characteristics

| Feature | Prototype |
|----------|-----------|
| Offline Operation | ✔ |
| USB Communication | ✔ |
| Student Identification | ✔ |
| Book Identification | ✔ |
| Borrowing Transactions | ✔ |
| Returning Transactions | ✔ |
| Digital Transaction Records | ✔ |
| Automatic Book Status Updates | ✔ |
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
Laptop Processes Transaction
    │
    ▼
Update Book Status
    │
    ▼
Save Transaction Record
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

The laptop processes the borrowing transaction.

---

## Step 9

The transaction is recorded digitally.

---

## Step 10

The selected book is marked as:

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

The laptop locates the active borrowing record.

---

## Step 6

The transaction is recorded as returned.

---

## Step 7

The book status becomes:

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
      ├── Borrow / Return Processing
      ├── Book Status Update
      └── Transaction Recording
```

---

# Transaction Sequence

```text
Student ID
      │
      ▼
Book Identifier Card
      │
      ▼
Transaction Processing
      │
      ▼
Record Saved
      │
      ▼
Book Status Updated
```

---

# Prototype Characteristics

- RFID-assisted identification
- USB communication only
- Offline processing
- Digital transaction recording
- Automatic book status updates
- No Wi-Fi
- No cloud services
- Single laptop operation

# Phase 8 — Proposed Final Implementation

> **Status:** Proposed Final Implementation (Future Development)

---

# Overview

The proposed final implementation of SHLMAS expands the prototype into a more complete library automation system.

Unlike the prototype, which uses an ESP32 connected directly to a laptop through USB and operates completely offline, the final implementation introduces a more scalable system architecture.

The prototype demonstrates the core RFID transaction process, while the final implementation focuses on improving deployment for actual school library environments.

---

# Proposed System Architecture

The final implementation is designed around three main components:

1. RFID-based self-service kiosk
2. Library management system
3. Digital database system

---

# Proposed Hardware Components

## ESP32-Based RFID Kiosk

The final implementation uses the ESP32 as the main controller of the RFID kiosk.

The kiosk handles:

- RFID card reading
- Transaction processing
- Communication with the management system

---

## RFID Student Identification Card

Students continue to use RFID-enabled identification cards for authentication.

The card identifies the student during library transactions.

---

## RFID Book Identifier Card

Books continue to use RFID Book Identifier Cards instead of individual RFID tags attached directly to each physical book.

The card represents the book information stored in the system.

---

# Proposed Software System

The final implementation expands the prototype software into a complete library management platform.

The system would manage:

- Student records
- Book records
- Borrowing records
- Returning records
- Book availability

---

# Proposed Database System

The final implementation uses a database to store library information.

The database would contain:

- Student information
- Book information
- Transaction records
- Borrowing status

---

# Proposed Communication

Unlike the prototype's USB communication, the final implementation proposes communication between the ESP32 kiosk and the management system.

The system is intended to allow:

- Automatic transaction transfer
- Centralized record management
- Easier monitoring of library activity

---

# Proposed User Workflow

```text
Student
    │
    ▼
Tap RFID Student ID
    │
    ▼
Tap RFID Book Identifier Card
    │
    ▼
ESP32 RFID Kiosk
    │
    ▼
Library Management System
    │
    ▼
Database Update
    │
    ▼
Transaction Completed
```

---

# Improvements Compared to Prototype

| Feature | Prototype | Proposed Final Implementation |
|---|---|---|
| Processing Device | Laptop | Dedicated system architecture |
| Communication | USB | System communication |
| Operation | Offline prototype | Expanded deployment system |
| Database | Local prototype storage | Centralized database |
| Deployment | Testing environment | School library environment |

---

# Purpose of Final Implementation

The proposed final implementation aims to transform SHLMAS from a working prototype into a deployable school library automation system.

The prototype validates the RFID transaction concept, while the final implementation focuses on scalability, easier management, and practical use in school libraries.

# Phase 9 — System Architecture

> **Status:** Prototype and Proposed Final Implementation Separation

---

# Overview

The SHLMAS architecture is divided into two versions:

1. Prototype Architecture
2. Proposed Final Implementation Architecture

The prototype focuses on validating the RFID-based library transaction process, while the proposed final implementation expands the system for a more complete library environment.

---

# A. Prototype Architecture

> **Current Implementation**

The prototype architecture uses a direct connection between the RFID hardware and a laptop.

```text
RFID Student ID Card
          │
          ▼
RC522 RFID Reader
          │
          ▼
ESP32 Microcontroller
          │
       USB Cable
          │
          ▼
Laptop
          │
          ▼
Transaction Processing
          │
          ▼
Record Storage
```

---

# Prototype Component Roles

## RFID Student ID Card

Purpose:

- Provides student identification
- Sends RFID UID when scanned

---

## RFID Book Identifier Card

Purpose:

- Represents the selected book
- Provides book identification through RFID scanning

---

## RC522 RFID Reader

Purpose:

- Reads RFID card information
- Transfers RFID data to the ESP32

---

## ESP32

Purpose:

- Receives RFID data from RC522
- Sends RFID information to the laptop through USB

---

## Laptop

Purpose:

- Processes transactions
- Stores records
- Runs the prototype software

---

# Prototype Data Flow

```text
Card Scan
    │
    ▼
RFID UID Reading
    │
    ▼
ESP32 Processing
    │
    ▼
USB Transfer
    │
    ▼
Laptop Processing
    │
    ▼
Transaction Record
```

---

# B. Proposed Final Implementation Architecture

> **Future Development**

The proposed final implementation expands the system by separating the RFID kiosk, management system, and database.

```text
RFID Student ID Card
          │
          ▼
RFID Reader

RFID Book Identifier Card
          │
          ▼

ESP32 RFID Kiosk
          │
          ▼

Library Management System
          │
          ▼

Database
          │
          ▼

Library Records
```

---

# Proposed Final Component Roles

## RFID Kiosk

Purpose:

- Handles RFID scanning
- Provides the transaction interface
- Acts as the connection between users and the library system

---

## Library Management System

Purpose:

- Processes library transactions
- Manages book and student records
- Handles borrowing and returning operations

---

## Database

Purpose:

- Stores library information
- Maintains transaction history
- Stores book availability records

---

# Architecture Difference

| Component | Prototype | Proposed Final Implementation |
|---|---|---|
| RFID Reading | RC522 + ESP32 | RC522 + ESP32 kiosk |
| Processing | Laptop | Library management system |
| Communication | USB | System communication |
| Storage | Local prototype storage | Database system |
| Purpose | Testing functionality | Deployment concept |

---

# Main Architectural Idea

The main concept of SHLMAS remains the same in both versions:

```text
Student RFID Identification
            +
Book RFID Identification
            │
            ▼
Digital Library Transaction
```

The difference is the scale and deployment method.

# Phase 10 — RFID Identification System

> **Status:** Prototype (Current Implementation) + Proposed Final Implementation

---

# Overview

The Smart Hybrid Library Management and Automation System (SHLMAS) uses a hybrid RFID identification method.

Instead of placing an RFID tag directly on every physical book, the system separates identification into two RFID components:

1. RFID Student Identification Card
2. RFID Book Identifier Card

This approach allows the system to identify users and books while reducing the number of RFID tags required.

---

# RFID Components

## 1. RFID Student Identification Card

### Purpose

The RFID Student Identification Card identifies the student performing a library transaction.

---

### Usage

The student scans their RFID card before borrowing or returning a book.

The system uses the RFID information to determine:

- Who is performing the transaction
- Which student account should be updated

---

### Transaction Role

```text
Student
   │
   ▼
RFID Student ID Card
   │
   ▼
Student Identification
```

---

# 2. RFID Book Identifier Card

### Purpose

The RFID Book Identifier Card represents the book being borrowed or returned.

---

### Usage

Instead of attaching RFID tags directly to every physical book, each book is represented by an RFID card.

The card contains the identifier used by the system to locate the corresponding book record.

---

### Transaction Role

```text
Book
   │
   ▼
RFID Book Identifier Card
   │
   ▼
Book Identification
```

---

# Hybrid RFID Concept

The SHLMAS hybrid approach works by combining:

```text
Student RFID Card
        +
Book Identifier RFID Card
        │
        ▼
Library Transaction
```

Both identifiers are required to complete a borrowing or returning transaction.

---

# Borrowing Identification Flow

```text
Step 1:
Student scans RFID Student ID

        ▼

Step 2:
System identifies student

        ▼

Step 3:
Student scans RFID Book Identifier Card

        ▼

Step 4:
System identifies selected book

        ▼

Step 5:
Transaction is recorded
```

---

# Returning Identification Flow

```text
Step 1:
Student scans RFID Student ID

        ▼

Step 2:
Student scans RFID Book Identifier Card

        ▼

Step 3:
System finds borrowing record

        ▼

Step 4:
Return transaction is recorded
```

---

# Why Hybrid RFID Is Used

The system uses a hybrid RFID design to avoid attaching an individual RFID tag to every physical book.

Traditional item-level RFID requires:

```text
Book 1 → RFID Tag
Book 2 → RFID Tag
Book 3 → RFID Tag
...
```

SHLMAS uses:

```text
Student → RFID Student ID

Book Collection → RFID Book Identifier Cards
```

---

# Prototype RFID Implementation

The prototype uses:

- RC522 RFID Reader
- ESP32 Microcontroller
- RFID Student ID Cards
- RFID Book Identifier Cards

The RFID reader sends scanned card information to the ESP32, which transfers the data to the laptop through USB.

---

# Final Implementation RFID Concept

The proposed final implementation maintains the same RFID identification concept but integrates it into a larger library management system.

The core transaction remains:

```text
Identify Student
        +
Identify Book
        │
        ▼
Complete Library Transaction
```

---

# RFID System Summary

| Component | Purpose |
|---|---|
| RFID Student ID Card | Identifies the borrower |
| RFID Book Identifier Card | Identifies the selected book |
| RC522 Reader | Reads RFID information |
| ESP32 | Processes RFID input |
| Laptop/System | Handles transaction processing |

# Phase 11 — Library Transaction System

> **Status:** Prototype (Current Implementation)

---

# Overview

The SHLMAS prototype focuses on automating the basic library circulation process through RFID-based identification.

The transaction system manages two primary operations:

1. Borrowing
2. Returning

Each operation requires identifying both the student and the book involved in the transaction.

---

# Transaction Requirements

A library transaction requires:

## Student Identification

The system must identify the student using:

- RFID Student Identification Card

---

## Book Identification

The system must identify the selected book using:

- RFID Book Identifier Card

---

# Borrowing Transaction

## Purpose

The borrowing transaction records when a student takes a book from the library.

---

# Borrowing Process

```text
Student RFID Scan
        │
        ▼
Student Identified
        │
        ▼
Book Identifier Card Scan
        │
        ▼
Book Identified
        │
        ▼
Borrowing Record Created
        │
        ▼
Book Status Updated
```

---

# Borrowing Data Flow

```text
RFID Student ID
        │
        ▼
Student Record Lookup

RFID Book Identifier Card
        │
        ▼
Book Record Lookup

        │

        ▼

Transaction Saved
```

---

# Borrowing Result

After a successful borrowing transaction:

- The student is recorded as the borrower.
- The selected book is recorded as borrowed.
- A transaction record is created.

---

# Returning Transaction

## Purpose

The returning transaction records when a student returns a borrowed book.

---

# Returning Process

```text
Student RFID Scan
        │
        ▼
Student Identified
        │
        ▼
Book Identifier Card Scan
        │
        ▼
Book Identified
        │
        ▼
Existing Borrow Record Located
        │
        ▼
Return Record Created
        │
        ▼
Book Status Updated
```

---

# Returning Data Flow

```text
RFID Student ID
        │
        ▼
Student Record Lookup

RFID Book Identifier Card
        │
        ▼
Book Record Lookup

        │

        ▼

Borrow Record Found

        │

        ▼

Return Transaction Saved
```

---

# Book Status Management

The system tracks the availability of books based on transactions.

Possible book states:

```text
Available
    │
    │ Borrow Transaction
    ▼
Borrowed
    │
    │ Return Transaction
    ▼
Available
```

---

# Transaction Records

Each completed transaction creates a digital record.

Transaction records contain information related to:

- Student involved
- Book involved
- Transaction type
- Transaction status

---

# Prototype Transaction Flow

```text
User
 │
 ▼
Scan RFID Student ID
 │
 ▼
Scan RFID Book Identifier Card
 │
 ▼
ESP32 Receives RFID Data
 │
 ▼
USB Transfer to Laptop
 │
 ▼
Software Processes Transaction
 │
 ▼
Record Stored
```

---

# Transaction System Characteristics

| Feature | Status |
|---|---|
| RFID Student Identification | Implemented |
| RFID Book Identification | Implemented |
| Borrowing Process | Implemented Concept |
| Returning Process | Implemented Concept |
| Digital Records | Implemented Concept |
| Offline Operation | Implemented |
| USB Communication | Implemented |

---

# Purpose of the Transaction System

The transaction system is the core functionality of SHLMAS.

It demonstrates that RFID technology can replace manual library recording by allowing students and books to be digitally identified during circulation.

# Phase 12 — Data Management System

> **Status:** Prototype (Current Implementation) + Proposed Final Implementation

---

# Overview

The SHLMAS data management system handles the storage and organization of information generated during library transactions.

The prototype focuses on storing transaction information locally through the laptop, while the proposed final implementation expands this into a complete library database system.

---

# Prototype Data Management

> **Current Implementation**

The prototype uses the laptop as the main processing and storage device.

The laptop is responsible for:

- Receiving RFID data from the ESP32
- Processing student identification
- Processing book identification
- Recording transactions
- Managing book status

---

# Prototype Data Flow

```text
RFID Scan
    │
    ▼
ESP32
    │
 USB Connection
    │
    ▼
Laptop Software
    │
    ├── Identify Student
    ├── Identify Book
    ├── Process Transaction
    └── Save Record
```

---

# Prototype Stored Information

The system records information related to:

## Student Records

Used to identify the student performing the transaction.

Example information:

- Student RFID identifier
- Student account information

---

## Book Records

Used to identify the selected book.

Example information:

- Book RFID identifier
- Book information
- Current availability status

---

## Transaction Records

Used to store completed library activities.

Example information:

- Borrow transaction
- Return transaction
- Student involved
- Book involved

---

# Proposed Final Data Management

> **Future Development**

The proposed final implementation expands the storage system into a structured database.

The database manages:

- Student information
- Book information
- Borrowing records
- Returning records
- Book availability

---

# Proposed Database Structure

## Student Table

Purpose:

Stores information about registered users.

```text
Student
│
├── Student ID
├── RFID Identifier
└── Student Information
```

---

## Book Table

Purpose:

Stores information about library books.

```text
Book
│
├── Book ID
├── Book Identifier RFID
├── Book Information
└── Availability Status
```

---

## Transaction Table

Purpose:

Stores library activity records.

```text
Transaction
│
├── Transaction ID
├── Student ID
├── Book ID
├── Transaction Type
└── Transaction Record
```

---

# Relationship Between Data

```text
Student
    │
    │ performs
    ▼

Transaction

    ▲
    │ involves

Book
```

---

# Data Management Workflow

```text
Student RFID Scan
        │
        ▼
Student Record Search

Book RFID Scan
        │
        ▼
Book Record Search

        │

        ▼

Transaction Created

        │

        ▼

Book Status Updated
```

---

# Purpose of Data Management

The data management system allows SHLMAS to:

- Replace manual library records
- Maintain organized transaction history
- Track borrowed books
- Monitor book availability
- Provide digital records of library activity

---

# Data Management Summary

| Component | Prototype | Proposed Final Implementation |
|---|---|---|
| Storage Device | Laptop | Database System |
| Operation | Offline | Expanded System |
| Student Records | Local Processing | Structured Records |
| Book Records | Local Processing | Structured Records |
| Transaction Records | Local Storage | Database Storage |

# Phase 13 — System Operation Flow

> **Status:** Prototype (Current Implementation)

---

# Overview

The SHLMAS prototype operation flow describes how users interact with the hardware and software components during library transactions.

The process begins when a student presents an RFID card and ends when the transaction is recorded by the laptop system.

---

# Complete System Flow

```text
Student
   │
   ▼
RFID Card Presentation
   │
   ▼
RC522 RFID Reader
   │
   ▼
ESP32 Microcontroller
   │
   ▼
USB Communication
   │
   ▼
Laptop Processing System
   │
   ▼
Transaction Verification
   │
   ▼
Record Storage
   │
   ▼
Transaction Completed
```

---

# Borrowing Operation Flow

## 1. Student Identification

The student begins the transaction by scanning the RFID Student Identification Card.

```text
Student
   │
   ▼
RFID Student ID Card
```

The RFID reader captures the card identifier.

---

## 2. RFID Data Transfer

The RC522 RFID reader sends the scanned information to the ESP32.

```text
RC522
   │
   ▼
ESP32
```

---

## 3. USB Communication

The ESP32 transfers the RFID information to the laptop.

```text
ESP32
   │
 USB
   │
   ▼
Laptop
```

---

## 4. Book Identification

The student scans the RFID Book Identifier Card.

```text
Book Identifier Card
   │
   ▼
RC522
   │
   ▼
ESP32
```

---

## 5. Transaction Processing

The laptop software receives both identifiers:

```text
Student Identifier
        +
Book Identifier
```

The system processes the borrowing request.

---

## 6. Record Creation

The borrowing transaction is saved.

The book status changes:

```text
Available
     │
     ▼
Borrowed
```

---

# Returning Operation Flow

## 1. Student Identification

The student scans the RFID Student Identification Card.

---

## 2. Book Identification

The student scans the RFID Book Identifier Card.

---

## 3. Transaction Matching

The system searches for the existing borrowing record.

---

## 4. Return Processing

The system records the return transaction.

---

## 5. Status Update

The book status changes:

```text
Borrowed
     │
     ▼
Available
```

---

# System Interaction Diagram

```text
              Student

                 │

                 ▼

        RFID Student ID Card

                 │

                 ▼

          RFID Reader (RC522)

                 │

                 ▼

              ESP32

                 │

             USB Serial

                 │

                 ▼

              Laptop

                 │

                 ▼

       Library Transaction System

                 │

                 ▼

          Stored Record
```

---

# Operation Characteristics

| Operation | Method |
|---|---|
| Student Identification | RFID Card Scan |
| Book Identification | RFID Book Identifier Card Scan |
| Hardware Processing | ESP32 |
| Communication | USB |
| Transaction Processing | Laptop |
| Storage | Local Prototype Storage |
| Internet Requirement | None |

---

# Purpose of the Operation Flow

The operation flow demonstrates the main function of SHLMAS:

> Using RFID identification to replace manual library circulation recording with a faster digital transaction process.
