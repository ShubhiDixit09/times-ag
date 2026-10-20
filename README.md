# DTU Times — Edition Management & Collaboration Portal (`times-ag`)

The official internal collaboration portal and edition management platform for **DTU Times**, the student publication and media platform of **Delhi Technological University (DTU)**.

---

## 🌟 The Core Problem Solved
Producing each quarterly edition previously required coordinating **20 to 25 distinct WhatsApp groups** across columnists, illustrators, photographers, designers, and associate editors. This led to:
- **Associate Burnout:** 9 associate editors manually monitoring scores of individual chats and chasing deadlines.
- **Asset Degradation & Lost Files:** WhatsApp compression destroying print-resolution photos and vector art.
- **Version Confusion:** Designers guessing which copy iteration is the approved final text.
- **Subjective Annual Appraisals:** End-of-year leadership selections relying on unverified Google Forms.

---

## 🚀 Key Portal Features

### 1. Streamlined Left Sidebar Navigation
A clean, accessible navigation rail organized into three intuitive areas:
- **Editorial Workspace:**
  - **Pipeline (Board):** 5-stage editorial review kanban (*Drafting* &rarr; *Associate Review* &rarr; *EIC Polish* &rarr; *Layout Pairing* &rarr; *Ready for Print*).
  - **Edition Sections:** 10 recurring standard sections auto-populated for each cycle (*VC Address*, *Campus News*, *Student Accolades*, *Faculty News*, *Alumni Spotlight*, *Society Coverage*, *Interviews*, *Creative Columns*, *The Pulse*).
  - **Draft Studio:** Distraction-free writing environment with live word count and submission actions.
  - **Visual Art & Photos:** Dedicated pairing board matching written manuscripts with camera RAWs and vector art.
- **Team & Management:**
  - **Team Contributions:** Clean, friendly tracker showing each member's vertical, completed tasks, and activity level.
  - **Drive Scaffolding:** Automated Google Drive directory hierarchy preventing database storage strain.
- **Documentation:**
  - **User Flow Guide:** Interactive 5-phase editorial lifecycle walkthrough and before/after comparison.

### 2. Dual Light & Dark Theme
- **Crisp Light Theme (Default):** Soft slate background, pure white cards, high-contrast typography, and clean status indicators.
- **Instant Dark Mode Switch:** One-click toggle in the top-right header for seamless switching.

### 3. Role-Based Permissions & Simulation
Switch effortlessly between roles in the top bar to preview the workflow from different perspectives:
- **Arjun Mehta (Council Head / EIC):** Full edition oversight, milestone tracking, and print sign-off.
- **Kavya Verma (Associate Editor):** Section management, columnist assignment, and inline reviews.
- **Rohan Das (Columnist / Contributor):** Focused writing studio, word counts, and draft submission.
- **Ishaan Sharma (Designer / Layout):** Access to locked manuscripts and full-resolution linked visual assets.

---

## 💻 Quick Start: Running Locally

### Option 1: Built-in Node.js Server (Recommended)
Open PowerShell or Command Prompt:
```bash
cd dtu_times_portal
node server.js
```
Open **[http://localhost:3000](http://localhost:3000)** in any modern browser.

### Option 2: 1-Click Direct Browser Launch (No server needed)
Double-click `dtu_times_portal/index.html` in Windows Explorer or execute:
```powershell
Start-Process "c:\Users\Shubhi Dixit\Downloads\times_ag\dtu_times_portal\index.html"
```

---

## 📁 Repository Structure
```
times-ag/
├── dtu_times_portal/
│   ├── index.html            # Standalone interactive portal & user flow visualizer
│   ├── server.js             # Lightweight zero-dependency Node.js HTTP server
│   └── README.md             # Walkthrough guide for presenting to editorial board
├── ARCHITECTURE_AND_USER_FLOW.md # Full technical specification & multi-persona user journeys
├── extracted_meeting_notes.txt # Parsed meeting discussion with seniors (19 Oct 2026)
├── Meeting started 2026_10_19 22_08 IST - Notes by Gemini.pdf
└── README.md                 # Project overview & latest update changelog
```

---

## 🔄 Recent Changelog & Update History

- **v1.6 (Latest - 10x UI Overhaul):** Redesigned with bespoke editorial craftsmanship: Plus Jakarta Sans & Newsreader typography, Linear-inspired elevated cards with page allocations and author badges, interactive ⌘K search bar, and refined warm paper/obsidian theme palettes.
- **v1.5:** Enhanced top navigation bar with generous vertical height (64px), larger brand badge, comfortable padding, and refined status pills.
- **v1.4:** Restored streamlined left sidebar with clean Light Theme by default and instant Dark Mode toggle.
- **v1.3:** Ultra-accessible layout redesign; simplified team contribution tracker and streamlined submission workflow.
- **v1.2:** De-cluttered top navigation bar; removed heavy corporate metrics and simplified card typography.
- **v1.1:** Complete personal anonymization; replaced all specific team names across the app and docs with custom student personas.
- **v1.0:** Initial MVP architecture blueprint, multi-persona user flows, Google Drive scaffolding rules, and interactive prototype.
