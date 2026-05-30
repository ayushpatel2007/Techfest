# IIT Bombay Techfest 2026 | Landing Page

This repository contains a responsive, highly interactive landing page developed for the **IIT Bombay Techfest** task. The design revolves around a brutalist, "Toxic Bio-Hack" cyberpunk theme, merging modern UI/UX design with advanced front-end micro-interactions.

## 🔗 Live Links
* **Live Preview:**
* [https://ayushpatel2007.github.io/Techfest/#competitions]
* **Video Demo:**
* []

## 🚀 Technical Features & Micro-Interactions

Unlike standard static templates, this landing page features several custom-built interactive elements:

* **Interactive Toxic Rain (HTML5 Canvas):** A custom-coded, optimized matrix-style background using `requestAnimationFrame` to simulate a falling data stream of hazard symbols and binary.
* **3D Dual-State Glitch Cards:** Event cards utilize `transform-style: preserve-3d` and mouse-tracking mathematics to physically tilt towards the user's cursor. Hovering reveals a hidden, glitch-animated background image underneath the frosted glass.
* **Ambient Audio Controller:** A custom retro-tech pill UI that toggles an immersive cyberpunk synth soundtrack to elevate the user experience.
* **Root Access Easter Egg:** A hidden keylogger listens for a specific sequence (`c-y-b-o-r-g`). Upon activation, the DOM locks down and triggers an amber "Critical Error" hacker terminal overlay with a typewriter animation effect.

## 💻 Tech Stack
* **HTML5:** Semantic structure aligning with Techfest's official event nodes (Competitions, Exhibitions, Technoholix).
* **CSS3:** Advanced styling utilizing CSS Grid/Flexbox, CSS Variables, `clip-path` for aggressive brutalist geometry, CSS Animations (`@keyframes`), and backdrop-filters for frosted glass.
* **Vanilla JavaScript (ES6):** No external libraries (like Three.js or Particles.js) were used. All 3D tilt mathematics, canvas rendering, and event listeners were built from scratch.

## 🛠️ Installation / Usage
To run this project locally:
1. Clone the repository.
2. Ensure both `index.html` and `soundtrack.mp3` are in the same root directory.
3. Open `index.html` in any modern web browser. 
*(Note: To activate the easter egg, simply type `cyborg` on your keyboard while viewing the page).*
