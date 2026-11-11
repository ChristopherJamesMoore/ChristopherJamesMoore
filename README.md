<div align="center">

# Christopher Moore
**Computer Science Graduate | Hardware & Software | Somerset, UK**

*Five years of component-level electronics diagnostics at **Apuljack Electronics**, now moving into silicon and post-silicon validation.*

</div>

---

## About

My background sits in the gap between hardware and software. I combine hands-on fault-finding on electronic assemblies with a BSc in Computer Science, and I'm especially interested in high-performance desktop and server processors, from CPU architecture and memory subsystems to the validation that proves they are stable and correct.

I enjoy the methodical side of debugging: reproducing a fault, narrowing it down and finding the root cause.

* **Hardware:** Component-level fault diagnosis, multimeter and oscilloscope measurement, PCB track repair, SMD and through-hole soldering, Bluetooth Low Energy integration on custom PCBs.
* **Software:** Python and C++, with TypeScript for production web tooling. Git and Linux day to day.
* **Testing:** Automated testing and validation in my own projects (unit, schema and end-to-end tests), and test procedure tooling used for repair work.
* **Currently learning:** Bare-metal C, Arm architecture, computer architecture, and debugging with GDB and SWD.

---

## Tech Stack

<img src="https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white" />
<img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" />
<img src="https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black" />
<img src="https://img.shields.io/badge/Bluetooth_LE-0082FC?style=for-the-badge&logo=bluetooth&logoColor=white" />
<img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white" />
<img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" />
<img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white" />

---

## Featured Projects

<!--
UNCOMMENT AND FILL IN ONCE THE PROJECT IS BUILT AND PUBLISHED:

### Bare-Metal Validation Framework (Raspberry Pi Pico)
Bare-metal C tests running on an Arm Cortex-M33 microcontroller, with a Python and pytest framework that flashes the board, runs the test suite and reports regressions. Debugged with GDB over SWD and a logic analyser.
Repo: [link]
-->

### LedgRx: Blockchain Pharmaceutical Supply Chain Tracking
**BSc Computer Science Dissertation (81%), University of Plymouth**

A permissioned ledger that tracks pharmaceutical supply chain integrity across multiple parties.

* Built on **Hyperledger Fabric**, enforcing controlled state transitions so records can't move into an invalid state.
* Implemented FIDO2/WebAuthn passkey authentication and zero-trust API security, including single-use challenges, JWT blacklisting and TLS-enforced database transport.
* Designed audit trails that make every change traceable.

### Axiom: Guided Test Procedure Platform
A test procedure platform for repair and test work at Apuljack Electronics, with a rich-text editor, image annotation, auto-saving and shared fix libraries, plus strict access controls and audit logging.

### Atlas: Operations & Repair Platform
A platform covering repair workflows, WooCommerce sync, Xero invoicing and SLA analytics, with an automated CI pipeline (Vitest, Zod, Playwright) reaching 66% unit test coverage.
