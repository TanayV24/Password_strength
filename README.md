
# 🔐 Password Strength Checker

### Real-time Password Strength Validation & Feedback Tool

![JavaScript](https://img.shields.io/badge/JavaScript-ES6-yellow?style=for-the-badge&logo=javascript&logoColor=black)
![React](https://img.shields.io/badge/React-18.x-61DAFB?style=for-the-badge&logo=react&logoColor=white)
![CSS](https://img.shields.io/badge/Styling-CSS-blue?style=for-the-badge)

**A lightweight web tool that validates password strength in real time, providing visual feedback and suggestions — ideal for signup forms and authentication flows.**

[🐛 Report Bug](https://github.com/TanayV24/Password_strength/issues) | [💡 Request Feature](https://github.com/TanayV24/Password_strength/issues)

</div>

---

## ✨ Features

### 🔐 Password Validation & Feedback
- ✅ **Real-time Strength Assessment** — Checks password strength as user types  
- 🧪 **Multiple Validation Rules** — Minimum length, lowercase, uppercase, number, special character  
- 📊 **Visual Strength Indicator** — Progress bar or meter showing strength level  
- 💡 **Requirements Checklist** — Shows which criteria are met/unmet (e.g. “Has number”, “Has special char”)  
- 🔁 **Instant Feedback** — Encourages users to improve weak passwords before submission  
- 🛠️ **Easy to Embed** — Can be integrated into signup/login forms  

### 📐 UI / UX Features
- 📱 **Responsive Design** — Works well on desktop and mobile screens  
- 🎨 **Clean, Minimal UI** — Simple input + feedback bar + requirement list  
- ⚡ **Fast and Lightweight** — No heavy dependencies required  

---

## 🛠 Tech Stack

| Layer | Technology |
|-------|------------|
| Frontend | HTML, CSS, JavaScript (or React if implemented) |
| Validation Logic | JavaScript (regex or string analysis) |
| Optional UI Library | React / Tailwind / plain CSS |
| Deployment | Static hosting (GitHub Pages / Netlify / Vercel) |

---

## 📋 Prerequisites

| Tool | Version | Link |
|------|---------|------|
| 🟢 Node.js & npm (if using React) | 16.x or higher | https://nodejs.org |
| 💻 Git | Latest | https://git-scm.com |

If using plain HTML/CSS/JS — no build tools needed: just open `index.html` in browser.

---

## ⚙️ Installation & Setup  

### 🚀 Quick Start (Plain JS / Static Deployment)

1. Clone the repo  
```bash
git clone https://github.com/TanayV24/Password_strength.git  
cd Password_strength  
````

2. Open `index.html` in your browser — no build needed

---

### 🛠 (If using React / build setup)

```bash
git clone https://github.com/TanayV24/Password_strength.git  
cd Password_strength  
npm install  
npm run dev  # or npm start  
```

---

## 🎮 How to Use

* Open the web page / run the React app
* Enter or paste a password in the input field
* Watch the strength indicator / meter update in real time
* Review the checklist for unmet password requirements
* Use the feedback to create a strong password

---

## 📁 Detailed Project Structure

```
Password_strength/
│
├── src/ (or root if plain JS)
│   ├── index.html               # Main HTML file (if static)  
│   ├── style.css                # CSS styles for input, meter, feedback  
│   ├── script.js                # JavaScript logic for strength checking & feedback  
│   └── (Optional) React files:
│       ├── App.jsx              # Main component  
│       ├── components/          # UI components (PasswordInput, StrengthBar, RequirementsList)  
│       └── utils/               # Helper functions (validation logic, regex patterns)  
│
├── README.md                    # Documentation (this file)  
└── (Optional) package.json      # If using React / build tools  
```

**Explanation of key parts:**

* `index.html` — The main page containing the password input field and container for the strength meter / feedback.
* `style.css` — Styles for the input, meter bar, color indicators, requirement checklist, responsiveness.
* `script.js` — Core logic: listens to input change, runs validation rules (length, uppercase, number, special char), computes strength, updates UI accordingly.
* (If using React) `App.jsx`, `components/`, `utils/` — Modular component-based structure for UI, logic separation, easier maintenance and scalability.

---

## 🐛 Troubleshooting & Common Issues

<details>
<summary>Password strength indicator not working / no feedback</summary>

* Ensure your browser’s console has no JS errors
* If using React, confirm dependencies are installed and app compiled
* For regex-based validation: verify patterns are correct and not overly strict

</details>

<details>
<summary>Styling / responsiveness broken on mobile</summary>

* Check CSS media queries or flex settings
* Ensure viewport meta tag is present in HTML:
  `<meta name="viewport" content="width=device-width, initial-scale=1">`

</details>

<details>
<summary>Password accepted but actually weak</summary>

Remember: this tool gives a heuristic — always encourage users to use passphrases, mix of unrelated words, and avoid common patterns for maximum security. For stronger checking, consider using libraries such as zxcvbn. ([GitHub][1])

</details>

---

