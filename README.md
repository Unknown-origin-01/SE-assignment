# SOFTWARE ENGINEERING ASSIGNMENT
## SDLC Model Selection for ATM Software System

| Course | Software Engineering |
| :--- | :--- |
| **Topic** | SDLC Model Selection |
| **Selected Project** | ATM Software System |
| **SDLC Model** | Waterfall Model |
| **Assignment Type** | Individual Assignment |

---

## 1. Introduction
[cite_start]An **ATM (Automated Teller Machine) Software System** is a critical financial application that enables bank customers to perform self-service banking transactions without the assistance of a human teller[cite: 5]. [cite_start]These transactions include cash withdrawals, balance inquiries, fund transfers, PIN changes, and mini-statement generation[cite: 6]. 

[cite_start]The ATM software interfaces directly with the bank's core banking infrastructure, card processing networks (such as VISA and Mastercard), and physical hardware components including the cash dispenser, card reader, PIN pad, and receipt printer[cite: 7].

### Key Characteristics:
* [cite_start]**Security-Critical:** Handles highly sensitive financial transactions requiring absolute accuracy[cite: 9].
* [cite_start]**High Availability:** Operates 24/7 with strict uptime requirements (99.9%+ availability)[cite: 10].
* [cite_start]**High Volume:** Processes hundreds to thousands of transactions per day[cite: 11].
* [cite_start]**Regulated Domain:** Interfaces with banking regulatory frameworks and compliance standards (PCI-DSS, RBI norms)[cite: 12].
* [cite_start]**Fixed Requirements:** Requirements are defined precisely by banking standards before development begins[cite: 13].

---

## 2. Selected SDLC Model: Waterfall Model
[cite_start]The **Waterfall Model** is a linear-sequential software development approach in which each phase must be completed before the next phase begins, with no overlapping or iterative cycles[cite: 17]. [cite_start]It is the most appropriate model for the ATM Software System[cite: 16].

### Sequential Phases:
| Phase | Name | Description |
| :--- | :--- | :--- |
| Phase 1 | Requirements Gathering & Analysis | [cite_start]All functional and non-functional requirements are collected and documented comprehensively[cite: 19]. |
| Phase 2 | System Design | [cite_start]High-level and low-level designs are created — including database schema, hardware interfaces, and security protocols[cite: 19]. |
| Phase 3 | Implementation (Coding) | Developers write code according to design documents. [cite_start]Modules like authentication and hardware interfaces are coded independently[cite: 19]. |
| Phase 4 | Testing | [cite_start]Rigorous unit, integration, security, and User Acceptance Testing (UAT) are performed[cite: 19]. |
| Phase 5 | Deployment | [cite_start]The system is deployed across ATM machines, followed by pilot testing[cite: 19]. |
| Phase 6 | Maintenance | [cite_start]Post-deployment bug fixes, security patches, and minor enhancements are handled[cite: 19]. |

---

## 3. Justification for Selecting Waterfall Model
[cite_start]The selection is strongly justified by the following points[cite: 21]:

* [cite_start]**Well-Defined and Stable Requirements:** All requirements, including security protocols (PCI-DSS), are defined clearly by regulatory bodies before development begins[cite: 23]. [cite_start]Since requirements do not change during development, a sequential approach is ideal[cite: 24].
* [cite_start]**Low Risk of Requirement Changes:** Core ATM functionality (cash dispensing, PIN verification) follows strict industry standards that have remained essentially unchanged for decades[cite: 27, 29].
* [cite_start]**High Security and Accuracy:** A single bug can lead to massive financial losses[cite: 33]. [cite_start]Waterfall’s emphasis on a verified design before coding and a dedicated exhaustive testing phase ensures zero-defect tolerance[cite: 35, 36, 38].
* [cite_start]**Extensive Documentation Required:** Audit trails and regulatory certifications (PCI-DSS) are legal requirements for financial software[cite: 41, 43]. [cite_start]Waterfall inherently produces the thorough documentation needed for compliance[cite: 42, 44].
* [cite_start]**Hardware-Software Integration Complexity:** Software must integrate with physical hardware on a fixed timeline[cite: 46, 47]. [cite_start]Waterfall ensures hardware interface specifications are finalized upfront, preventing costly mismatches after deployment[cite: 48, 49].

---

## 4. Comparison with Other Models
[cite_start]Other popular models are less suitable for the ATM Software System[cite: 51]:

### 4.1 Agile Model — Why Not Suitable
| Criteria | Agile Model | Why Not for ATM |
| :--- | :--- | :--- |
| **Requirements** | Evolving, sprint-based | [cite_start]ATM requirements are fixed & regulatory [cite: 53] |
| **Documentation** | Minimal | [cite_start]Compliance demands full documentation [cite: 53] |
| **Testing** | Continuous, informal cycles | [cite_start]ATM needs exhaustive formal testing [cite: 53] |
| **User Involvement** | Constant collaboration | [cite_start]End-users can't influence bank standards [cite: 53] |

[cite_start]**Verdict:** Agile's iterative sprints are counterproductive where all requirements must be fully validated before hardware installation and regulatory certification[cite: 54].

### 4.2 Spiral Model — Why Not Suitable
* [cite_start]**Excessive Risk Iterations:** ATM requirements are well-understood; extensive risk analysis cycles add unnecessary cost[cite: 58].
* [cite_start]**Mismatched Context:** Spiral is suited for high-uncertainty projects (military/aerospace), whereas ATMs require high precision with known requirements[cite: 59, 60].
* [cite_start]**Higher Cost:** Prototyping phases make it significantly more expensive without proportional benefit[cite: 61].

---

## 5. Diagram of the Waterfall Model
The diagram below illustrates the Waterfall Model as applied to the ATM Software System. [cite_start]Each phase flows sequentially downward, with feedback loops only for defect detection[cite: 64].

![ATM SDLC Waterfall Diagram](atm.png)

---

## 6. Conclusion
[cite_start]Based on the ATM Software System's characteristics, the **Waterfall Model** is the most suitable approach[cite: 84]. [cite_start]Its structured nature ensures every transaction is backed by software that has been rigorously designed, thoroughly tested, and fully compliant with banking standards[cite: 91, 92]. [cite_start]While other models have their place in dynamic projects, the ATM system’s stability and regulatory constraints make Waterfall the definitive choice[cite: 93].