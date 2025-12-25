# Card Utility Toolkit (Client-Side Web Tools)

A modern, client-side web toolkit built with **pure HTML, CSS, and JavaScript** that provides two focused utilities for processing card-formatted data.
The interface is optimized for **RTL (Persian)** layouts and features a high-end neon/glassmorphism UI.

> ⚠️ **Important Notice**
> This project is intended **strictly for educational, testing, and UI/UX demonstration purposes**.
> It must **not** be used with real financial data or for any unauthorized activity.

---

## 📌 Project Overview

This repository contains **two independent web tools**, each designed for a specific data-processing task:

* **Card Checker** – Displays only cards reported as “live”
* **Card Extractor** – Cleans and normalizes card-formatted input

All logic runs **entirely in the browser**.
No server, database, or framework is required.

---

## 📂 Project Structure

```
/
├── index.html   # Live card checker
├── bin.html     # Card data extractor / formatter
└── README.md
```

---

## 🔹 index.html — Live Card Checker

### Description

Processes a list of card-formatted inputs and displays **only cards identified as live** based on responses from an external checking service.

### Features

* Bulk input (one card per line)
* Live-only result filtering
* Animated progress bar with percentage
* Interactive result cards
* Clickable modal with card details
* Copy-to-clipboard support
* Fully responsive design
* No backend or build step required

### Technical Highlights

* Uses `fetch()` with asynchronous processing
* Graceful handling of failed or invalid responses
* Dead or unknown cards are intentionally not displayed
* Clean separation of UI logic and processing logic

---

## 🔹 bin.html — Card Data Extractor

### Description

Extracts and normalizes the **core card format** from mixed or extended input lines.

### Output Format

```
card_number | month | year | cvv
```

### Features

* Accepts large multiline input
* Ignores extra fields automatically
* Converts 4-digit years to 2-digit format
* Visual processing indicator
* Output counter
* One-click “copy all” functionality
* Works fully offline

### Example

**Input**

```
5106986312001037|01|2030|279|USD|4900
```

**Output**

```
5106986312001037|01|30|279
```

---

## 🎨 UI & UX Design

* Persian (RTL) layout
* Neon gradient typography
* Glassmorphism panels
* Animated background particles
* Custom scrollbars
* Mobile-first responsiveness

No UI libraries or CSS frameworks are used.

---

## 🧠 Technologies Used

* HTML5
* CSS3 (animations, gradients, glassmorphism)
* Vanilla JavaScript (ES6+)
* Google Fonts (Vazirmatn)

---

## ⚖️ Legal & Ethical Disclaimer

This repository **does not encourage, support, or condone**:

* Fraud
* Unauthorized card testing
* Use of real financial or personal data
* Circumventing security systems

The code is provided **as-is** for:

* Educational purposes
* UI/UX experimentation
* Frontend logic demonstration

**You are solely responsible for how you use this software.**

---

## 👤 Author

**Shayan Ghadamian**
GitHub: [https://github.com/shayanghad0](https://github.com/shayanghad0)
Telegram: [https://t.me/shayanghad0](https://t.me/shayanghad0)

---

## 📄 License

This project is shared for **educational and personal use only**.
Commercial or malicious usage is strictly discouraged.

---
