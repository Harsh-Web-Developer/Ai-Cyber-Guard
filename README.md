# 🛡️ AI CyberGuard

> **Real-Time Screen Threat Vision & Floating Emergency System**  
> Built by **Team Syntax Squad** for Hackathon 2026.

AI CyberGuard is a **100% Zero-API local client-side security scanner** designed to protect digital users, elderly individuals, and financial traders from phishing links, typo-squatted domains, and SMS scam patterns in real time. By leveraging high-contrast browser-native OCR (`Tesseract.js`), continuous canvas pre-processing, an Always-on-Top Document Picture-in-Picture (PiP) window, and a Dual Siren & TTS Audio Warning Engine, AI CyberGuard ensures critical security threats are never overlooked.

---

## 🚀 Key Features

* ** Zero-API Local Operation:** Runs 100% inside your browser using client-side pattern heuristics and local OCR engines. No external AI keys or cloud backends required.
* ** Real-Time High-Res Screen OCR:** Scans live screen frames (captured via `getDisplayMedia()`) every 2.5 seconds using grayscale high-contrast canvas enhancement to reliably detect tiny text across WhatsApp Desktop, Microsoft Edge, Telegram, and Notepad.
* ** Always-on-Top Floating PiP Overlay:** Utilizes the Chrome/Edge `Document Picture-in-Picture API` to float a dedicated security widget ON TOP of all active desktop apps. When a threat is detected, the floating window turns flashing red and displays the intercepted malicious link directly inside the widget.
* ** Dual Emergency Audio System (TTS + Siren):** Combines a Web Audio API sawtooth siren with instant Text-to-Speech (`window.speechSynthesis`) to broadcast audible voice alerts (e.g., *"Warning! Critical security threat detected on your screen!"*).
* ** Smart Phishing & Financial SMS Detection:** Built-in regex detection rules for:
  * URL Shorteners (`bit.ly`, `tinyurl.com`, `cutt.ly`, `t.me`)
  * Typo-squatted domains & raw IP addresses (`g00gle.com`, `http://192.168.x.x`)
  * Financial SMS Scams (`CREDITED to your A/C`, `DEBITED from A/C`, `urgent KYC update`, `electricity bill unpaid`)
* ** Cross-Platform Smart Fallback:** Native full-desktop screen scanning on PC/Mac, with a responsive 1-tap demo mode and test scratchpad for mobile web viewports.

---

## 🛠️ Tech Stack

* **Frontend:** HTML5, Tailwind CSS (Custom Dark/Neon Cyberpunk Theme), JavaScript (ES6+)
* **Vision & OCR Engine:** Tesseract.js (Offline Client-side OCR)
* **Overlay Architecture:** Document Picture-in-Picture API & Browser Native Notifications API
* **Audio System:** Web Audio API (Oscillator Siren) & Web Speech API (Text-To-Speech)
* **Build System:** Vite / Standalone HTML

---

