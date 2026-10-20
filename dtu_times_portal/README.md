# DTU Times — Edition Portal Presentation & Quickstart

## Overview
The internal collaboration platform designed for the **DTU Times Editorial Board**. It replaces the 20–25 fragmented WhatsApp groups previously used per edition with a clean, role-based workspace.

---

## 🏃 Running the Portal

### 1. Via Local Server:
```bash
node server.js
```
Then visit **`http://localhost:3000`** in your browser.

### 2. Direct File Launch:
Open `index.html` in Chrome, Edge, or Firefox.

---

## 🎯 Key Features Demonstrated

1. **Left Sidebar Workspace:**
   * **Pipeline (Board):** 5-stage kanban review (*Drafting &rarr; Associate Review &rarr; EIC Polish &rarr; Layout Pairing &rarr; Ready for Print*).
   * **Edition Sections:** 10 recurring standard sections auto-populated for each cycle.
   * **Draft Studio:** Simple writing workspace with word counter and submission buttons.
   * **Visual Assets:** Dedicated handoff between columnists, photographers, and illustrators.
   * **Team Contributions:** Clear, friendly member activity table.
   * **Drive Scaffolding:** Automated folder tree linking directly to Google Drive.
   * **User Flow Guide:** 5-step lifecycle walkthrough and before/after comparison.

2. **Light & Dark Theme Toggle:**
   * Default high-contrast light theme for comfortable daytime editing.
   * 1-click Moon/Sun toggle in the header for night mode.

3. **Active Role Switcher:**
   * Experience the portal as **Arjun Mehta (Council Head / EIC)**, **Kavya Verma (Associate Editor)**, **Rohan Das (Columnist)**, or **Ishaan Sharma (Designer / Layout)**.

- **v1.6 (Latest - Login Page & Authentication):** Added dedicated, bespoke Sign-In page (`login.html`) with university email authentication, password visibility toggle, 1-click persona quick-login cards, and persistent session role handoff with a header sign-out action.
- **v1.5:** Enhanced top navigation bar with generous vertical height (64px), larger brand badge, comfortable padding, and refined status pills.
- **v1.4:** Restored streamlined left sidebar with clean Light Theme by default and instant Dark Mode toggle.

---

## 📌 Maintenance Note
This README and the root README are automatically updated side-by-side with every GitHub commit to maintain complete synchronization.
