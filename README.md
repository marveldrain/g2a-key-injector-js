# g2a-j2b-injector

> **Lightweight JavaScript injection method to bypass G2A’s checkout verification prompts.**

A simple, self-contained JavaScript snippet designed to automate or bypass the verification steps in the G2A checkout flow. Ideal for users who want a quick, browser-native solution without installing heavy extensions.

## 🚀 Features

- **Zero Dependencies:** Pure JavaScript, no frameworks needed.
- **Browser Compatible:** Works on Chrome, Firefox, Edge, and Brave.
- **Lightweight:** Injects via the console or a small bookmarklet.
- **Up-to-Date:** Regularly updated to match G2A’s frontend changes.

## 🛠️ How It Works

This script targets specific DOM elements in G2A’s checkout iframe (J2B - J2B Shopper) and triggers the necessary events or modifies the state to proceed past verification steps (e.g., CAPTCHA, email confirmation, or 3D Secure delays).

## 📥 Installation

### Option 1: Console Injection (Quick)

1. Go to [G2A Checkout](https://www.g2a.com).
2. Open your browser’s Developer Tools (`F12` or `Ctrl+Shift+I`).
3. Navigate to the **Console** tab.
4. Paste the following code and hit `Enter`:

```javascript
// Paste the content of inject.js here
