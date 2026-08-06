# 4. Theoretical Framework
## Overview of Theoretical Foundation
The development, implementation, and evaluation of the **Smart Hybrid Library Management and Automation System (SHLMAS)** are anchored on established technology adoption theories. Introducing an automated hardware-software system into a traditional school library environment requires understanding both human behavioral factors and organizational dynamics. Users must accept the interface, while educational institutions must be willing to integrate the system into their daily operations.
To address these requirements, the theoretical framework of SHLMAS combines two complementary models: the **Technology Acceptance Model (TAM)** formulated by Davis (1989) and the **Diffusion of Innovations Theory** developed by Rogers (2003).
The Technology Acceptance Model provides a framework for evaluating individual user acceptance among students and library personnel, while the Diffusion of Innovations Theory explains how the system's innovative characteristics support institutional adoption within public basic education schools.
---
# Technology Acceptance Model (TAM)
## Introduction
The **Technology Acceptance Model (TAM)**, introduced by Fred D. Davis in 1989, is an information systems theory designed to explain how users accept and utilize new technologies. TAM proposes that an individual's intention to use a system is primarily influenced by two core factors:
1. **Perceived Usefulness (PU)**  
2. **Perceived Ease of Use (PEOU)**  
(Davis, 1989)

+———————————————————————————–+
|                        TECHNOLOGY ACCEPTANCE MODEL (TAM)                          |
|                               (Davis, 1989)                                       |
|                                                                                   |
|  +—————————+              +–––––––––––––––––+  |
|  | Perceived Usefulness (PU) |              |   Perceived Ease of Use (PEOU)   |  |
|  |                           |              |                                  |  |
|  | • Faster borrowing        |              | • Tap-and-go RFID workflow      |  |
|  | • Automated records       |              | • Zero manual handwriting       |  |
|  | • Real-time book status   |              | • Minimal user training         |  |
|  +———––+———––+              +––––––––+—————–+  |
|                |                                             |                    |
|                +———————+———————–+                    |
|                                      |                                            |
|                                      v                                            |
|                     +–––––––––––––––––+                          |
|                     | System Acceptance & Usage        |                          |
|                     | (Students & Library Personnel)   |                          |
|                     +–––––––––––––––––+                          |
+———————————————————————————–+

---
## Perceived Usefulness (PU)
Davis (1989) defines **Perceived Usefulness** as the degree to which a person believes that using a specific system improves their performance or efficiency.
Within SHLMAS, perceived usefulness applies to both students and library personnel.
### Students
For students, SHLMAS improves usefulness by reducing the time required for borrowing and returning books. Replacing manual logbook writing with RFID scanning eliminates long waiting periods at circulation counters and allows students to complete transactions more efficiently.
### Library Personnel
For library personnel, SHLMAS provides operational benefits by automating transaction recording, updating book availability in real time, and removing repetitive manual ledger maintenance. This reduces administrative workload and minimizes recording errors.
When users recognize that SHLMAS directly solves the inefficiencies of traditional circulation methods, their perception of system usefulness increases, encouraging acceptance and continued use.
---
## Perceived Ease of Use (PEOU)
**Perceived Ease of Use** refers to the degree to which a person believes that operating a system requires minimal effort (Davis, 1989).
Complex or difficult technologies may discourage adoption even when they provide significant benefits. Therefore, SHLMAS prioritizes simplicity through its physical RFID interaction workflow.
The borrowing and returning process follows a straightforward sequence:

Tap Student RFID Card
↓
Tap Book RFID Identifier Card
↓
Automatic Transaction Recording

Users do not need to navigate complicated software interfaces, manually enter accession numbers, or write information in physical logbooks. This simple interaction reduces technical barriers and allows students and library staff to operate the system with minimal training.
---
## TAM Relationship to SHLMAS
According to Davis (1989), Perceived Ease of Use influences Perceived Usefulness because systems that require less effort allow users to achieve tasks more effectively.
In SHLMAS, maximizing both usefulness and ease of use promotes positive user attitudes, increasing acceptance and reducing resistance toward automated library technology.
---
# Diffusion of Innovations Theory
## Introduction
The **Diffusion of Innovations Theory**, developed by Everett M. Rogers (2003), explains how new technologies and ideas spread within social systems and organizations.
Rogers proposed that adoption depends on how potential users perceive specific characteristics of an innovation.

+———————————————————————————–+
|                        DIFFUSION OF INNOVATIONS THEORY                            |
|                               (Rogers, 2003)                                      |
|                                                                                   |
|  Innovation Attributes Influencing Adoption:                                      |
|                                                                                   |
|  1. Relative Advantage                                                            |
|     → Faster and more accurate than manual logging.                               |
|                                                                                   |
|  2. Compatibility                                                                 |
|     → Works with existing student RFID identification systems.                    |
|                                                                                   |
|  3. Complexity                                                                    |
|     → Simple tap-based workflow reduces technical barriers.                       |
|                                                                                   |
|  4. Trialability and Observability                                                |
|     → Prototype allows testing and visible evaluation of results.                  |
|                                                                                   |
+———————————————————————————–+

---
# Innovation Characteristics Applied to SHLMAS
Rogers (2003) identifies several innovation characteristics that influence adoption. The following attributes directly apply to SHLMAS.
---
## Relative Advantage
Relative advantage refers to the degree to which an innovation is perceived as better than the existing method (Rogers, 2003).
SHLMAS provides advantages over manual circulation systems by offering:
- Faster RFID-based transactions
- Automatic digital record creation
- Real-time book availability updates
- Reduced administrative workload
Additionally, the hybrid RFID model provides financial advantages compared to traditional item-level RFID systems because it avoids placing RFID tags on every physical book.
---
## Compatibility
Compatibility refers to how well an innovation fits existing practices, values, and operational requirements (Rogers, 2003).
SHLMAS is designed to integrate with existing school environments by utilizing RFID-based student identification cards. This reduces adoption barriers because schools do not need to completely replace existing identification systems.
---
## Complexity
Complexity refers to how difficult an innovation is perceived to understand and operate (Rogers, 2003).
Public schools often have limited technical support, making highly complex systems difficult to maintain. SHLMAS reduces complexity through:
- ESP32-based embedded hardware
- Simple RFID card interaction
- Automated transaction processing
The tap-based workflow allows both students and staff to operate the system without advanced technical knowledge.
---
## Trialability and Observability
Trialability refers to the ability to test an innovation before full adoption, while observability refers to how visible the results of the innovation are to users and decision-makers (Rogers, 2003).
SHLMAS supports trialability through a standalone prototype that can be tested within a school library environment without requiring complete infrastructure replacement.
The system's improvements—such as faster transactions, reduced errors, and improved record accuracy—can be directly observed by administrators and library personnel, encouraging wider adoption.
---
# Relationship Between Theories and SHLMAS
The Technology Acceptance Model and Diffusion of Innovations Theory provide complementary perspectives for evaluating SHLMAS.

+———————————————————————————–+
|                        INTEGRATED THEORETICAL FRAMEWORK                           |
+———————————————————————————–+
|                                                                                   |
|     INDIVIDUAL ACCEPTANCE                         INSTITUTIONAL ADOPTION           |
|     (Technology Acceptance Model)                 (Diffusion of Innovations)       |
|                                                                                   |
|     • Perceived Usefulness (PU)                   • Relative Advantage             |
|     • Perceived Ease of Use (PEOU)                • Compatibility                  |
|                                                    • Low Complexity                |
|                                                    • Trialability & Observability  |
|                                                                                   |
+—————————————–+—————————————–+
|
v
+———————————————————————————–+
|                         SUCCESSFUL SHLMAS IMPLEMENTATION                          |
|                                                                                   |
| • Increased user acceptance among students and staff                              |
| • Practical adoption within public basic education schools                        |
| • Sustainable library automation solution                                          |
+———————————————————————————–+

TAM focuses on the **individual level**, explaining how students and library personnel accept SHLMAS based on usefulness and ease of operation.
Meanwhile, the Diffusion of Innovations Theory focuses on the **institutional level**, explaining why schools may adopt SHLMAS based on its advantages, compatibility, simplicity, and feasibility.
Together, these theories allow SHLMAS to be evaluated not only as a functional technological system but also as a practical, user-friendly, and sustainable solution for public school library automation.
---
## References Used
- Davis, F. D. (1989). *Perceived usefulness, perceived ease of use, and user acceptance of information technology*. MIS Quarterly, 13(3), 319–340.
- Rogers, E. M. (2003). *Diffusion of Innovations* (5th ed.). Free Press.
