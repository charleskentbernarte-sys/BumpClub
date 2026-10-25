# ⚡ BumpClub - LVCC Campus Network & Club Portal

A responsive web application designed for **La Verdad Christian College (LVCC)** students, club officers, and faculty advisers. BumpClub provides an interactive 2D campus map with wayfinding, a club directory, an AI-powered questionnaire matcher, an interactive AI Chat Assistant, and a hidden "Wizard of Oz" back-stage control room for prototype operators.

---

## 🌟 Key Features

### 🎓 For Students
- **🗺️ Interactive 2D Campus Map:** Walk an avatar around campus using on-screen direction controls and draw wayfinding path lines directly to any club room (Academic Bldg, Media Center, AVR Center, Gymnasium, etc.).
- **🏛️ Full Clubs Directory:** Browse all active campus organizations without taking recommendations. Filter by categories (*Tech & Engineering*, *Media & Arts*, *Spiritual & Outreach*, *Sports & Fitness*) or search via keyword.
- **🤖 AI Club Recommendation Survey:** Take an interactive survey to calculate personalized club compatibility percentages.
- **💬 AI Chatbot Assistant:** Ask natural language questions regarding meeting schedules, room numbers, club officers, or membership application steps.
- **📝 Online Registration:** Submit direct membership applications for any club with automated student identity mapping.

### 🛡️ For Club Officers & Faculty Advisers
- **📋 Member Approvals Dashboard:** Review incoming student and teacher application requests, view applicant details, and approve or decline memberships in real-time.

### ⚙️ Secret Wizard of Oz Back-Stage Control Room
- **🔑 Secret Operator Trigger:** Triple-tap the header navbar / top status bar to open the passcode prompt.
- **🔓 Access Passcode:** Enter `1010` (or `1234`) to unlock the hidden operator control room.
- **🕵️ Manual Fulfillment:** Operators can manually manage application queues, observe live system audit event logs, and fulfill student requests behind the scenes.

---

## 💻 Tech Stack & Requirements

- **HTML5 & CSS3**
- **Tailwind CSS v3** (Utility-first styling & dark mode design)
- **React v18 & ReactDOM v18** (Standalone UMD bundle)
- **Babel Standalone** (In-browser JSX compilation)
- **JavaScript (ES6+)**

*No Node.js build pipeline or server setup is required. The web app runs directly in any modern browser on PC, tablet, or mobile devices.*

---

## 🚀 How to Run the Web App

1. Download or extract the project files (`index.html`).
2. Double-click `index.html` to open it in any browser (Chrome, Edge, Safari, Firefox, or mobile web browsers).
3. Select a role on the login screen or click any of the **Quick Demo Sign In** buttons:
   - **Student:** `student@laverdad.edu.ph`
   - **Club Officer:** `officer@laverdad.edu.ph`
   - **Teacher / Adviser:** `teacher@laverdad.edu.ph`

---

## 📱 PC & Mobile Compatibility

The app includes an in-app view frame switcher located on the top header bar:
- **`🖥️ PC Web Mode`**: Full widescreen responsive web layout with a left navigation sidebar, multi-column club grids, and sticky header controls.
- **`📱 Mobile View`**: Simulated mobile device frame preview ideal for mobile screen demonstrations on desktop displays.