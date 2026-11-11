```markdown
# #️⃣ TagVault System Architecture & Business Model Documentation

## 1. Executive Summary
TagVault bridges the physical and digital gap on university campuses. Misplacing high-value items like scientific calculators, laptops, and dorm keys is a universal student pain point. TagVault provides indestructible NFC tags and dynamic QR stickers mapped to a secure cloud database.

---

## 2. Technical Architecture

[NFC Tag / Dynamic QR] ---> ( Tap / Scan ) ---> [Secure Cloud Relay API] ---> [Owner Notification (SMS/Email/Push)]
|
[Encrypted Anonymous Chat]


### Stack Components:
* **Frontend:** HTML5, Tailwind CSS, Vanilla JavaScript with custom cursor physics and fluid glassmorphism UI.
* **Hardware Interfacing:** NTAG215 NFC chips (13.56 MHz ISO/IEC 14443A) + Dynamic URL redirection engine.
* **Backend & Database:** Node.js / Express microservices paired with PostgreSQL for encrypted asset mapping.

---

## 3. Financial & Tokenomics Model

* **Starter Bundle:** **KSh 50** for a pack of 5 high-durability NFC/QR stickers (covers manufacturing and initial 4-year database synchronization).
* **Extended Storage Renewal:** After the initial 4-year undergraduate lifecycle, users can renew data cloud storage for **KSh 100/year** per bundle.
* **Institutional Revenue Share:** Partnering with Baraton University security and student welfare offices for bulk campus distribution.
