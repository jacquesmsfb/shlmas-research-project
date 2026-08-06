# 4. Theoretical Framework

## Overview of Theoretical Foundation

The development, implementation, and evaluation of the **Smart Hybrid Library Management and Automation System (SHLMAS)** are anchored on established technology adoption theories. Introducing an automated hardware-software system into a traditional school library environment requires an understanding of both human behavioral factors and organizational dynamics. Individuals must accept the interface, and the educational institution must be willing to integrate the system into daily routines.

To address these dual requirements, the theoretical framework for SHLMAS combines two complementary models: the **Technology Acceptance Model (TAM)** formulated by Davis (1989) and the **Diffusion of Innovations Theory** developed by Rogers (2003). While TAM provides a framework for evaluating individual user acceptance among students and library personnel, the Diffusion of Innovations Theory offers an analytical perspective on how the system's innovative design characteristics facilitate institutional adoption within public basic education schools.

---

# Technology Acceptance Model (TAM)

## Introduction

The **Technology Acceptance Model (TAM)**, introduced by Fred D. Davis in 1989, is an information systems theory designed to explain how users accept and utilize new technologies. TAM proposes that an individual's behavioral intention to use a system is primarily influenced by two major cognitive factors:

1. **Perceived Usefulness (PU)**
2. **Perceived Ease of Use (PEOU)**

(Davis, 1989)

## TAM Framework Applied to SHLMAS

| TAM Construct | Application in SHLMAS |
|---|---|
| **Perceived Usefulness (PU)** | The belief that SHLMAS improves library operations and increases efficiency. |
| Faster borrowing | RFID scanning reduces transaction time compared to manual logbooks. |
| Automated records | Transactions are digitally stored without handwritten entries. |
| Real-time book status | Availability records are updated immediately after transactions. |
| **Perceived Ease of Use (PEOU)** | The belief that SHLMAS requires minimal effort to operate. |
| Tap-and-go RFID workflow | Users only scan their student card and book identifier card. |
| Zero manual handwriting | Eliminates physical circulation logs. |
| Minimal user training | Simple interaction allows students and staff to quickly understand the system. |
| **System Acceptance and Usage** | Increased usefulness and ease of use encourage successful adoption of SHLMAS. |

---

## Perceived Usefulness (PU)

Davis (1989) defines **Perceived Usefulness** as the degree to which an individual believes that using a specific system enhances their performance or productivity.

Within SHLMAS, Perceived Usefulness applies to both students and library personnel.

### Students

SHLMAS increases usefulness by improving the speed and convenience of borrowing and returning library materials. Replacing manual logbook writing with RFID scanning minimizes waiting time, reduces circulation delays, and allows students to complete transactions efficiently during limited school breaks and study periods.

### Library Personnel

For librarians and teacher-librarians, SHLMAS provides operational benefits by automatically recording transactions, updating book availability, and maintaining digital borrowing histories. This reduces repetitive administrative tasks, minimizes human recording errors, and allows personnel to focus more on student support and library management.

When users recognize that SHLMAS directly solves existing circulation problems, their perception of system usefulness increases, encouraging technology acceptance (Davis, 1989).

---

## Perceived Ease of Use (PEOU)

**Perceived Ease of Use** refers to the degree to which an individual believes that operating a system requires minimal physical and mental effort (Davis, 1989).

SHLMAS incorporates ease of use through a simplified RFID-based workflow. The borrowing and returning process follows a straightforward interaction:

1. Scan student RFID identification card.
2. Scan RFID book identifier card.
3. Automatically record the transaction.

Users do not need to manually write information, type accession numbers, or navigate complex interfaces. This reduces technical barriers and allows students and library personnel with limited technological experience to operate the system effectively.

---

## TAM Relationship to SHLMAS

According to Davis (1989), Perceived Ease of Use contributes to Perceived Usefulness because systems that require less effort allow users to accomplish tasks more efficiently.

In SHLMAS, combining usefulness and simplicity creates a positive user experience. Faster transactions, reduced workload, and simplified interaction increase user acceptance and reduce resistance toward adopting automated library systems.

---

# Diffusion of Innovations Theory

## Introduction

The **Diffusion of Innovations Theory**, developed by Everett M. Rogers (2003), explains how new technologies and ideas spread within organizations and communities. Rogers proposed that adoption depends on how potential users perceive specific characteristics of an innovation.

## Innovation Characteristics Applied to SHLMAS

| Innovation Attribute | Application in SHLMAS |
|---|---|
| **Relative Advantage** | SHLMAS improves upon manual logbooks by providing faster transactions, accurate digital records, and automated tracking. |
| **Compatibility** | SHLMAS integrates with existing school workflows and RFID-based student identification systems. |
| **Complexity** | The simple tap-based RFID process minimizes difficulty for students and staff. |
| **Trialability** | Schools can test the prototype before committing to full implementation. |
| **Observability** | Improvements such as reduced transaction time and accurate records can be directly measured and observed. |

---

## Relative Advantage

Relative advantage refers to the degree to which an innovation is perceived as better than the system it replaces (Rogers, 2003).

SHLMAS provides advantages over traditional manual circulation systems by offering:

- Faster RFID-based transactions.
- Automated digital record keeping.
- Improved borrowing accuracy.
- Reduced workload for library personnel.

Additionally, the hybrid RFID model provides a financial advantage compared with conventional RFID systems because it eliminates the need to attach individual RFID tags to every physical book.

---

## Compatibility

Compatibility refers to how well an innovation aligns with existing values, experiences, and operational requirements of potential adopters (Rogers, 2003).

SHLMAS is designed specifically for public basic education environments. The system can integrate with existing student identification processes and requires minimal changes to current library procedures.

By maintaining a familiar borrowing workflow while replacing manual recording with automation, SHLMAS improves compatibility with existing school operations.

---

## Complexity

Complexity describes how difficult an innovation is perceived to understand and use (Rogers, 2003).

SHLMAS reduces complexity through:

- A simple RFID scanning process.
- A dedicated hardware interface.
- Minimal user interaction requirements.
- Automated database processing.

The ESP32-based kiosk architecture allows the system to function as a self-contained solution that does not require advanced technical knowledge from daily users.

---

## Trialability and Observability

Trialability refers to the ability to test an innovation before full adoption, while observability refers to how visible its benefits are to potential adopters (Rogers, 2003).

SHLMAS supports trialability because schools can deploy the prototype within a controlled library environment before expanding implementation.

The system also provides observable improvements, including:

- Faster borrowing and returning transactions.
- Reduced manual workload.
- More accurate circulation records.
- Improved monitoring of library resources.

These visible benefits help administrators evaluate the effectiveness of SHLMAS before wider adoption.

---

# Relationship Between Theories and SHLMAS

The Technology Acceptance Model and Diffusion of Innovations Theory provide complementary perspectives for evaluating SHLMAS.

| Evaluation Level | Theory | Factors Applied to SHLMAS |
|---|---|---|
| **Individual User Acceptance** | Technology Acceptance Model (TAM) | Perceived Usefulness and Perceived Ease of Use |
| **Institutional Adoption** | Diffusion of Innovations Theory | Relative Advantage, Compatibility, Complexity, Trialability, and Observability |
| **Expected Outcome** | SHLMAS Implementation Success | Increased user acceptance, practical adoption, and sustainable library automation |

---

TAM focuses on the **individual level**, explaining how students and library personnel accept SHLMAS based on its usefulness and ease of operation.

Meanwhile, Diffusion of Innovations Theory focuses on the **institutional level**, explaining why schools may adopt SHLMAS based on its advantages, compatibility, simplicity, and feasibility.

By combining these theoretical perspectives, SHLMAS is evaluated not only as a functional technological solution but also as a practical and sustainable innovation suitable for public basic education libraries.
