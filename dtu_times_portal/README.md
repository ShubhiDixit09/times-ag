# DTU Times Edition Management & Collaboration Portal (Prototype)

## Overview
Designed and developed for **Arjun Mehta (Council Head & Senior)** and the **DTU Times Editorial Board** by **Editorial Team**.

This prototype replaces the **20–25 fragmented WhatsApp groups** used in every publication cycle with a unified, role-based edition workspace. It automates Google Drive directory scaffolding, pre-populates standard sections, enforces a 5-stage editorial review pipeline, and records objective member activity telemetry for annual performance appraisals.

---

## Quick Launch Instructions

### Method 1: Local HTTP Server (Recommended)
Open a terminal in this directory and run:
```bash
node server.js
```
Then navigate to: **[http://localhost:3000](http://localhost:3000)** in any modern browser.

### Method 2: Direct Browser Launch
Simply double-click `index.html` in Windows Explorer or open it in Google Chrome, Microsoft Edge, or Firefox.

---

## Recommended Presentation Walkthrough for "Bhaiya"

1. **Start on "Presentation Mode (Interactive Walkthrough)"**:
   - Click the top banner button or the left sidebar link: **`Inspect User Flow`**.
   - Show the **"Before vs. After"** contrast card: 25 WhatsApp groups vs. 1 unified portal.
   - Click through the **5-Step Interactive Editorial Lifecycle**:
     - *Phase 01:* Edition Initialization & Google Drive Scaffolding
     - *Phase 02:* Section Task Allocation (Word count & visual tagging)
     - *Phase 03:* Drafting & High-Res Drive Uploads (No WhatsApp compression)
     - *Phase 04:* Editorial Review Gatekeeper (Associate feedback & EIC polish)
     - *Phase 05:* Design & InDesign Spread Pairing

2. **Demonstrate Role Switching**:
   - Use the **Active Role** dropdown in the top-right header:
     - **Arjun Mehta / EIC (Council Head):** Full oversight, edition progress, lock for design.
     - **Associate Editor (Content Lead):** Managing columnists, inline reviewing, quality scoring.
     - **Rohan Das (Columnist, 2nd Yr CHE):** Drafting studio, live word count, Drive asset linking.
     - **Ishaan Sharma (Designer / Layout):** Accessing locked manuscripts and high-res vector art.

3. **Walk through the Editorial Pipeline (Kanban Board)**:
   - Click on `Editorial Pipeline` in the left sidebar.
   - Click any card (e.g. *Orientation-cum-Induction Program at Raj Soin Hall*).
   - Show the **Editorial Review Drawer**: manuscript preview, attached Google Drive files, reviewer remarks, and one-click stage advancement.

4. **Showcase the Autonomous Scaffolding**:
   - Click on the Edition selector at the top &rarr; **`Initialize New Edition (Auto-Scaffold)`**.
   - Click **`Initialize & Scaffold Drive`** to demonstrate how the portal automatically provisions 8 recurring sections and 5 Google Drive subdirectories via API.

5. **Highlight the Member Activity & Annual Appraisal Tracker**:
   - Click on **`Member Activity Tracker`** in the left sidebar.
   - Explain how this solves the annual dilemma of unverified Google Forms.
   - Review metrics: *Submissions*, *On-Time %*, *Avg Quality Rating*, *Review Turnaround SLA*, and *Objective Merit Index (OMI)*.
   - Click **`Export Appraisal Report (PDF/CSV)`** to preview the end-of-year executive summary.

---

## Technical Specifications
- **Layout Philosophy:** Microsoft Teams / Linear dual-column workspace.
- **Styling:** Tailwind CSS with official DTU Times visual palette (DTU Crimson `#8B0000`, Deep Gold, Midnight Slate `#090D16`).
- **Typography:** Newsreader & Cinzel for authentic editorial publication aesthetics; Inter for UI crispness.
- **Data Integration:** Standalone reactive state engine with zero external dependencies.
