# Chipmunks-ErgoGuard
ErgoGuard is an on-device, privacy first Chrome extension (Manifest V3) that automates the 20-20-20 rule for developers and students. Features non-intrusive optical canvas overlays to protect your eyes and maintain your deep-focus workflow without cloud tracking or webcams. Built by Team Chipmunks.
# 🛡️ ErgoGuard

*Eye care that never breaks your flow.*

ErgoGuard is an on-device, browser-native wellness co-pilot built for Chrome that automates the 20-20-20 rule without disrupting your workflow. Built by **Team Chipmunks** for hackathon innovation.

---

## 🚀 Problem Statement
Screen fatigue is a silent productivity killer for developers and students. During deep focus (coding, debugging, reading), blinking drops by **40–70%**, leading to dry eyes, strain, headaches, and burnout. Traditional timer apps fail because intrusive pop-ups break concentration, forcing users to disable them entirely.

---

## 💡 The Solution: How ErgoGuard Works
* **Non-Intrusive Overlay:** A calm 20-second optical canvas animation appears only when needed, preserving your flow state.
* **Flow-Aware Timing:** Intelligent background checks hold breaks during active typing bursts, fullscreen modes, or calls.
* **Privacy by Design:** 100% local-first architecture using Chrome storage. Optional camera tracking (MediaPipe) runs strictly on-device with zero video storage or cloud uploads.

---

## 🛠️ Tech Stack
* **Extension Core:** Manifest V3, JavaScript, HTML, CSS.
* **Chrome APIs:** `chrome.alarms`, `chrome.tabs`, `chrome.idle`, `chrome.storage.local`.
* **UI & Animation:** HTML5 Canvas, CSS Keyframes for smooth optical pulse.
* **Future Roadmap:** MediaPipe Face Mesh & Eye Aspect Ratio (EAR) via WebAssembly (WASM).

---

## 👥 Team Chipmunks
* **Arsh** – Screen Overlay & Visual Architecture (`content.js` & `content.css`)
* **Angel & Khushi** – Core Extension Logic & Background Timers (`background.js`)
* **Saksham** – Popup UI & Dashboard Controls (`popup.html` & `popup.js`)

---
