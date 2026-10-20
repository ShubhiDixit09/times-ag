# DTU Times — Edition Management & Collaboration Portal (`times-ag`)

The official internal collaboration portal and edition management system for **DTU Times**, the media platform and quarterly publication of **Delhi Technological University (DTU)**.

---

## 🌟 The Core Problem Solved
Producing each 60–80+ page quarterly edition previously required coordinating **20 to 25 distinct WhatsApp groups** across columnists, illustrators, photographers, designers, and associate editors. This led to:
- **Severe Associate Burnout:** 9 associate editors tracking hundreds of daily chat messages and chasing deadlines.
- **Asset Degradation & Lost Files:** WhatsApp compression destroying print-resolution photos and vector art.
- **Version Confusion:** Designers guessing which copy iteration is the approved final text.
- **Subjective Annual Appraisals:** End-of-year leadership selections relying on unverified Google Forms.

## 🚀 The Solution
The **DTU Times Edition Portal** replaces chaotic chat groups with a unified, role-based workspace inspired by Microsoft Teams / Linear:
1. **Autonomous Edition Scaffolding:** Pre-populates 8 standard recurring sections (VC Message, Campus News, Student/Faculty Awards, Alumni Spotlight, Society Coverage, Columns, The Pulse) and provisions Google Drive API folders automatically.
2. **5-Stage Editorial Gatekeeper:** Strict state machine from Draft &rarr; Associate Review &rarr; EIC Polish &rarr; Design Pairing &rarr; Print Ready.
3. **Google Drive Cloud Storage:** High-res RAW photos and vector `.ai` art stream directly to Google Drive without loading the database.
4. **Member Activity & Telemetry Tracker:** Concrete logs of submissions, on-time rate, quality score, and turnaround time to power end-of-year promotions.

---

## 📁 Repository Structure
```
times-ag/
├── dtu_times_portal/
│   ├── index.html            # Standalone interactive prototype & user flow visualizer
│   ├── server.js             # Lightweight zero-dependency Node.js preview server
│   └── README.md             # Walkthrough guide for presenting to seniors
├── ARCHITECTURE_AND_USER_FLOW.md # Full technical specification & multi-persona user journeys
├── extracted_meeting_notes.txt # Parsed meeting discussion with Arjun Mehta (19 Oct 2026)
├── Meeting started 2026_10_19 22_08 IST - Notes by Gemini.pdf
└── README.md                 # This overview file
```

---

## 💻 Quick Start & Live Preview

### Running the Prototype Locally:
```bash
cd dtu_times_portal
node server.js
```
Open **[http://localhost:3000](http://localhost:3000)** in your browser.

Or simply double-click `dtu_times_portal/index.html` to open it in any modern browser without installing any dependencies!

---

## 👥 Personas Supported in Portal
- **Editor-in-Chief / Council Head (Arjun Mehta):** Full edition oversight, milestone tracking, and print sign-off.
- **Associate Editor (Vertical Leads):** Section management, columnist assignment, inline reviews, and quality ratings.
- **Core Contributor (Rohan Das):** Distraction-free writing studio, live word counts, and direct asset linking.
- **Designer & Layout Artist (Ishaan Sharma):** Access to locked manuscripts and full-res vector/photo asset bundles.
