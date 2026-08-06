# Synthesis of Literature and Studies

## Common Findings from Existing Literature and Studies

The reviewed literature and empirical studies consistently demonstrate that digitizing and automating library operations provide significant improvements over traditional manual record-keeping practices. Research across different educational environments shows that replacing paper-based logbooks with digital database systems improves record accuracy, simplifies resource tracking, and reduces administrative workload among library personnel (Adewole et al., 2020; Asemi et al., 2010; Velasco, 2019).

Studies focusing on Radio Frequency Identification (RFID) technology further establish its effectiveness in improving library circulation processes. RFID enables contactless identification, faster authentication, and more reliable transaction recording compared with traditional handwriting and barcode-based systems (Ayre, 2005; Finkenzeller, 2010). Previous research indicates that RFID-assisted circulation reduces transaction processing time, minimizes human recording errors, and improves inventory management efficiency (Engel, 2017; Shahid, 2005).

In addition, engineering studies on embedded systems demonstrate that affordable microcontrollers, such as the ESP32, combined with modular components like the RC522 RFID reader, are capable of supporting localized automation applications. These technologies provide sufficient processing capability, reliability, and affordability for educational technology projects (Kumar & Sharma, 2021; Suryana et al., 2020).

Research regarding technology implementation in Philippine public basic education further emphasizes that successful digital transformation requires solutions that are affordable, maintainable, and suitable for environments with limited infrastructure and resources (DepEd, 2019; NEDA, 2021; Velasco, 2019). Therefore, effective school-based automation systems must balance technological capability with practical implementation requirements.

---

## Limitations of Existing Approaches

Although existing studies demonstrate the benefits of library automation and RFID technology, several limitations remain across current approaches.

### Traditional Manual Systems

Manual paper-based circulation systems remain common in many school libraries due to their low initial cost and simple implementation. However, these systems are limited by slow transaction processing, human recording errors, poor handwriting legibility, and the physical deterioration of records over time (Bansode & Periera, 2008; Velasco, 2019).

Additionally, retrieving historical borrowing records or determining book availability requires manually searching through physical documents, creating delays and increasing administrative workload for library personnel (Asemi et al., 2010). These limitations reduce the efficiency of library services and restrict the ability of schools to maintain accurate circulation data.

### Existing RFID Library Systems

Existing RFID-based library systems successfully improve circulation speed and inventory management through automated identification. However, most commercial RFID implementations use an item-level tagging approach, where every physical book copy requires an individual RFID tag (Ayre, 2005; Engel, 2017).

While effective in universities and large institutions with sufficient financial resources, the cost of purchasing and maintaining thousands of RFID tags, specialized readers, and supporting infrastructure creates a significant barrier for public basic education schools (Engel, 2017; Shahid, 2005). Furthermore, some enterprise RFID systems require complex server environments and reliable network connectivity, which may not be practical for schools with limited technological infrastructure.

### Software-Based Library Systems

Software-based library management systems successfully address problems associated with paper documentation by providing centralized databases, organized records, and easier information retrieval (Adewole et al., 2020).

However, software-only solutions often continue to depend on manual encoding during transactions. Library personnel may still need to enter student information and book identification details manually, which can introduce delays and potential data-entry errors during high-volume borrowing periods (Velasco, 2019).

### Embedded Automation Systems

Previous embedded system studies demonstrate the potential of low-cost microcontrollers for automation applications. Systems using ESP32 and RFID modules have successfully supported applications such as attendance monitoring, identification systems, and localized transaction logging (Kumar & Sharma, 2021; Suryana et al., 2020).

However, existing embedded automation projects are primarily designed for general tracking or authentication purposes rather than complete library circulation workflows. Limited research has explored the integration of embedded hardware, RFID identification, and database management specifically for public school library environments.

---

## Synthesis of Existing Approaches

| System Category | Solved Capabilities | Remaining Limitations |
|---|---|---|
| Manual Logbooks | Low implementation cost and simple operation without technological requirements. | Slow processing, high error rate, difficult record retrieval, and physical document degradation. |
| Item-Level RFID Systems | Fast contactless identification and improved inventory tracking. | Expensive implementation due to requiring RFID tags for every book and supporting infrastructure. |
| Software-Only Library Management Systems | Centralized digital records and improved data organization. | Continued dependence on manual data entry during transactions. |
| Basic Embedded Automation Systems | Affordable hardware processing and localized automation capabilities. | Limited application in specialized library circulation workflows. |
| SHLMAS (Proposed System) | Combines RFID automation, embedded hardware, digital records, and low-cost implementation. | Designed to address cost, infrastructure, and usability limitations through hybrid RFID architecture. |

---

## Contribution of SHLMAS

The Smart Hybrid Library Management and Automation System (SHLMAS) addresses the limitations identified in previous research by integrating RFID technology, embedded hardware, and digital record management into a low-cost automation framework specifically designed for public basic education schools.

### Hybrid RFID Approach

SHLMAS introduces a hybrid RFID identification model to reduce the implementation cost associated with traditional item-level RFID systems. Instead of attaching RFID tags to every physical book, the system utilizes RFID Student Identification Cards for borrower authentication and reusable RFID Book Identifier Cards associated with cataloged books.

This approach maintains the advantages of RFID technology, including fast contactless identification and reduced manual input, while significantly lowering the number of RFID components required for deployment.

### Embedded Low-Cost Architecture

SHLMAS utilizes an ESP32 microcontroller combined with an RC522 RFID reader module to provide an affordable automation platform. The embedded system processes RFID identification data, manages transaction logic, and communicates with the database system without requiring expensive industrial hardware.

The use of modular and accessible components makes the system more suitable for public schools with limited technology budgets and technical resources.

### Offline-Capable Operation

To address connectivity limitations in public school environments, SHLMAS incorporates offline transaction buffering capabilities. Transactions can be temporarily stored locally during internet interruptions and synchronized with the central database once connectivity is restored.

This design improves system reliability by allowing library operations to continue despite unstable network conditions.

### Integrated Hardware and Software Workflow

Unlike software-only library systems that require manual encoding, SHLMAS integrates physical RFID interactions directly with digital database records. By scanning student and book identifiers, the system automatically records borrowing and returning transactions, updates book availability, and reduces manual data entry requirements.

Through this integrated approach, SHLMAS combines the efficiency of RFID technology, the affordability of embedded systems, and the organizational advantages of digital databases into a practical library automation solution for public basic education institutions.
