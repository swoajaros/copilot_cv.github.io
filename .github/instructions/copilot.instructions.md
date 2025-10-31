---
applyTo: "**"
---

Provide project context and coding guidelines that AI should follow when generating code, answering questions, or reviewing changes.

# 🌐 Project Context – One-Pager CV Generator

---

## 🧭 Business Goals

- Create a lightweight, responsive one-pager website showcasing a user's professional profile.
- Provide a modern, concise online CV format suitable for sharing.
- Enable easy deployment via GitHub Pages.

---

## ⚙️ Technical Stack

- **Frontend**: Vanilla JavaScript (no frameworks)
- **Styling**: CSS3 (preferably using Flexbox/Grid)
- **Markup**: HTML5
- **Deployment**: GitHub Pages
- **Optional**: JSON as a data source for dynamic section rendering

---

## 🧩 Architecture & Structure

- Project structure:
  - `/index.html` – main page
  - `/style.css` – styling
  - `/script.js` – JavaScript logic
  - `/data.json` (optional) – user data
- Modular JS functions for rendering sections (e.g., experience, skills, contact)

---

## 🔒 Project Assumptions

- GitHub Copilot acts as a **pair programming assistant**, not a full code generator.
- Developer leads the implementation; Copilot supports by:
  - Suggesting code snippets
  - Completing repetitive code
  - Refactoring and debugging
- No external JS libraries or frameworks will be used.

---

## 🧠 Scope

- Build HTML structure and CSS styling
- Add interactivity using Vanilla JS
- Support dynamic data loading from JSON
- Ensure mobile responsiveness

---

## ⚖️ Out of Scope

- Use of JS frameworks (e.g., React, Vue)
- Backend development (e.g., Node.js, PHP)
- User authentication
- CMS or visual editors
