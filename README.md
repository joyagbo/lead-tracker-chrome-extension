# Leads Tracker - Chrome Extension

A clean and functional browser extension designed for marketers and researchers to save web leads instantly. This project was built as part of my journey in the **Scrimba Full-Stack Developer Career Path**, focusing on DOM manipulation and browser APIs.

![Leads Tracker Preview](screenshot.png)

## Features
* **Save Current Tab:** Instantly capture the URL of the active browser tab using the Chrome API.
* **Manual Input:** Type or paste leads directly into the input field for manual tracking.
* **Persistent Storage:** Data is saved to `localStorage`, so your leads remain safe even if you close the popup or restart Chrome.
* **Quick Clear:** A double-click feature on the "Delete All" button to clear your list and storage.

## Tech Stack
* **HTML5:** Structured the extension's popup interface.
* **CSS3:** Styled the UI with a focus on clean typography and layout.
* **JavaScript (ES6):** Implemented the logic for event listeners, array manipulation, and storage.
* **Chrome Extension API (Manifest V3):** Utilized `chrome.tabs` to interact with the browser's active window.

## Installation & Setup
To run this extension locally on your Chrome browser:

1.  **Download/Clone** this repository to your computer.
2.  Open Chrome and go to the Extensions page by typing `chrome://extensions/` in the address bar.
3.  Enable **Developer mode** using the toggle in the top-right corner.
4.  Click the **Load unpacked** button.
5.  Select the folder containing the project files (where your `manifest.json` is located).
6.  Pin the "Leads Tracker" to your toolbar for easy access!

## What I Learned
During this Scrimba project, I mastered several key concepts:
* **Manifest Permissions:** Understanding how to request `permissions` in `manifest.json` to access browser data.
* **LocalStorage:** How to turn JavaScript arrays into strings using `JSON.stringify()` and back into objects using `JSON.parse()`.
* **Function Parameters:** Creating a reusable `render()` function to update the UI dynamically.
* **The Tab API:** Learning how to query the current active window to grab URLs.

---

### Author
**Joy Agbo**
*Aspiring Full-Stack Developer*

---
*Built with ❤️ while learning on Scrimba.*