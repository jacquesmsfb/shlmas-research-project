# Review of Related Literature and Studies (RRL)

## Introduction

This chapter presents the literature and previous studies related to library management systems, workflow automation, QR code technology, embedded systems, and recommendation systems. These references provide the theoretical and technological foundation for the development of the Smart Hybrid Library Management and Automation System (SHLMAS).

The review demonstrates how previous research supports the use of automation in improving library services while identifying gaps that the proposed system intends to address.

---

# Library Management Systems

A Library Management System (LMS) is an information system designed to organize, monitor, and manage library resources and circulation activities. Traditional LMS platforms automate cataloging, borrowing, returning, inventory management, and report generation.

According to previous studies, implementing a digital library management system can:

- Improve inventory accuracy
- Reduce manual paperwork
- Increase transaction speed
- Improve record management
- Reduce librarian workload

However, many existing systems primarily replace paper records with digital databases while maintaining similar borrowing workflows.

The proposed SHLMAS extends this concept by redesigning the circulation workflow through automation using a self-service kiosk and smart return box.

---

# Workflow Automation

Workflow automation refers to the use of technology to automate repetitive operational tasks while minimizing human intervention.

Automation has been widely adopted in industries such as banking, healthcare, logistics, and education because it improves efficiency, consistency, and productivity.

In library operations, workflow automation can reduce:

- Manual encoding
- Human recording errors
- Processing time
- Administrative workload

SHLMAS applies workflow automation by automating book borrowing, returning, inventory updates, and report generation while allowing librarians to supervise exceptional cases.

---

# QR Code Technology

Quick Response (QR) Codes are two-dimensional barcodes capable of storing significantly more information than traditional one-dimensional barcodes.

QR codes are widely used because they are:

- Inexpensive
- Easy to generate
- Fast to scan
- Highly accurate
- Compatible with smartphones and commercial scanners

Compared with RFID systems, QR code technology offers a practical and affordable solution for schools with limited budgets.

For this reason, SHLMAS uses QR codes for:

- Student identification
- Book identification
- Borrowing transactions
- Returning transactions

RFID integration is proposed only as a future enhancement.

---

# Embedded Systems in Education

Embedded systems combine hardware and software to perform dedicated functions within larger systems.

Examples include:

- Attendance systems
- Smart classrooms
- Automated lockers
- Self-service kiosks
- Smart vending machines

Affordable microcontrollers such as the ESP32 have enabled schools to develop low-cost automation projects with internet connectivity and real-time communication.

In SHLMAS, the ESP32 serves as the controller for the borrowing kiosk and smart return box, demonstrating how embedded systems can support educational automation.

---

# Web-Based Information Systems

Web-based information systems allow users to access services through standard web browsers without installing dedicated software.

Advantages include:

- Platform independence
- Centralized database management
- Easier maintenance
- Remote accessibility
- Real-time synchronization

The Student Portal and Librarian Dashboard of SHLMAS are both implemented as web-based applications connected to a centralized database.

This architecture enables all modules to access updated information simultaneously.

---

# Recommendation Systems

Recommendation systems help users discover relevant items based on predefined rules or previous interactions.

Recommendation techniques generally include:

- Rule-based recommendations
- Content-based filtering
- Collaborative filtering
- Machine learning approaches

Because school libraries often have relatively small collections and predictable borrowing patterns, SHLMAS employs a rule-based recommendation engine rather than artificial intelligence.

Books may be recommended based on:

- Same subject
- Same author
- Frequently borrowed together
- Same grade level

This approach is computationally simple while remaining effective for educational environments.

---

# Related Studies

Previous studies have reported that automated library systems generally improve:

- Transaction efficiency
- Inventory management
- User satisfaction
- Information accessibility

Studies involving QR code technology have shown that QR-based identification provides reliable and cost-effective solutions for tracking books and users.

Research involving embedded automation devices also indicates that integrating hardware with centralized software systems can significantly reduce repetitive administrative work.

However, many existing studies evaluate only software-based library systems and do not integrate both hardware and software into one complete workflow.

---

# Research Gap

Although numerous digital library systems exist, relatively few studies combine multiple technologies into a single integrated ecosystem specifically designed for secondary school libraries.

Most existing systems focus on digital cataloging or record management rather than redesigning the complete borrowing and returning workflow.

In particular, few systems simultaneously integrate:

- A web-based student portal
- A self-service borrowing kiosk
- A smart return box
- Automated reporting
- Analytics dashboard
- Rule-based recommendation engine
- Centralized real-time database

This gap provides the opportunity for SHLMAS to contribute a practical and scalable hybrid solution tailored to the operational needs of school libraries.

---

# Conceptual Foundation

The proposed system is based on the principle that automation improves operational efficiency by reducing repetitive manual tasks while maintaining human supervision for critical decisions.

Instead of replacing librarians, SHLMAS supports librarians by automating routine circulation processes and providing real-time information for better decision-making.

The study therefore evaluates whether integrating affordable technologies into one modular ecosystem can significantly improve library circulation efficiency compared to traditional manual methods.

---

# Chapter Summary

The reviewed literature suggests that workflow automation, QR code technology, web-based systems, embedded devices, and centralized databases each contribute to improving operational efficiency.

However, previous studies rarely combine these technologies into a single modular ecosystem specifically designed for secondary school libraries.

This research addresses that gap by proposing the Smart Hybrid Library Management and Automation System (SHLMAS), which integrates software and hardware components into one unified platform for automating library circulation while maintaining librarian supervision.
