# 💻 Turn the Terminal | Portfolio OS v2.0

> An interactive, cyberpunk-inspired, command-line interface portfolio built for the web.

Welcome to **Turn the Terminal**, a fully functional browser-based OS environment designed to showcase my skills, experience, and projects in Cybersecurity and Adversarial Emulation. Instead of scrolling through a standard webpage, visitors are invited to "hack" their way through my portfolio using standard Unix-like commands.

---

## ✨ Key Features

* **Interactive CLI Environment:** A custom-built command parser that handles inputs, arguments, and command history (using Up/Down arrow keys).
* **Virtual File System:** Navigate through directories (`cd`), list contents (`ls`, `tree`), analyze directory stats (`dir`), and read files (`cat`).
* **Gamification & CTF Elements:** Hidden secrets, XP tracking, and playful error handling (try running `sudo`!).
* **Dynamic Theming:** Built-in theme switching (e.g., executing `theme matrix` overrides the global CSS).
* **"Secure Comms" Webhook Integration:** A custom UI modal for visitors to leave messages, wired directly to a Google Apps Script backend that logs payloads into a secure Google Sheet.
* **Live System Telemetry:** Persistent, real-time fake logs and session uptime tracking.

---

## 🛠️ Tech Stack

* **Frontend:** HTML5, Vanilla JavaScript (ES6+), Tailwind CSS (via CDN)
* **Backend (Logging/Comms):** Google Apps Script (Serverless Webhook)
* **Database:** Google Sheets
* **Typography:** JetBrains Mono, Inter, Manrope (Google Fonts)

---

## 🚀 Quick Start (Local Deployment)

Because this project relies entirely on client-side JavaScript, setting it up locally is incredibly simple:

1. Clone the repository:
   ```bash
   git clone [https://github.com/Aayan01/TurnTheTerminal.git](https://github.com/Aayan01/TurnTheTerminal.git)
