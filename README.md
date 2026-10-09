# 🛡️ Grassroots Cyber-Immunity: Interactive Phishing & Scam Awareness Platform

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](http://makeapullrequest.com)
[![MY Bharat](https://img.shields.io/badge/Hackathon-MY%20Bharat%20%2F%20HSC-blue)](https://mybharat.gov.in)
[![UN SDG Alignment](https://img.shields.io/badge/UN%20SDG-4%20%7C%209-orange)](https://sdgs.un.org/goals)

> **Grassroots Cyber-Immunity** is an open-source, mobile-first, and multilingual interactive simulation tool engineered to empower rural and semi-urban Indian citizens with experiential cyber-defense instincts.

---

## 📌 Problem Statement & Context
As millions of first-time digital citizens across Tier-2, Tier-3, and rural India adopt digital payments (UPI, DBT benefits, net banking), cyber fraud has skyrocketed:
* **Prevalent Scam Vectors:** Fake electricity disconnection notices, fraudulent KYC suspension threats, spoofed UPI "Collect/Cashback" requests, and advance-fee lottery letters.
* **The Core Gap:** Traditional awareness campaigns rely on static PDF advisories, banners, and lectures that fail to build practical, real-time threat detection reflexes.

---

## 💡 The Solution: Experiential Simulation
Instead of passive reading, **Grassroots Cyber-Immunity** puts citizens into safe, interactive sandbox scenarios directly on their smartphones:
1. **Realistic Scenario Simulation:** Emulates exact WhatsApp messages, SMS alerts, and UPI payment requests.
2. **Interactive Red-Flag Spotter:** Highlights deception cues (urgency triggers, spoofed shortlinks, non-official sender IDs).
3. **Multilingual & Zero-Friction:** Full Indic language support (Hindi, Tamil, English, and more) with zero mandatory registration.
4. **Direct 1930 Integration:** Educates citizens on the **National Cyber Helpline 1930** and golden-hour recovery protocol.

---

## 🚀 Live Demo & Quick Start

### 1. View Directly in Browser
You can run this project with zero build dependencies! Simply open `index.html` in any modern web browser or budget mobile device:
```bash
# Clone the repository
git clone https://github.com/your-username/grassroots-cyber-immunity.git

# Navigate into the project folder
cd grassroots-cyber-immunity

# Open index.html directly or serve locally
# Using Python:
python -m http.server 8080

# Using Node (npx):
npx serve .
```

Visit: `http://localhost:8080`

---

## 🏗️ Architecture & Tech Stack

```text
┌────────────────────────────────────────────────────────┐
│             Citizen Smartphone / Browser               │
└──────────────────────────┬─────────────────────────────┘
                           │
             ┌─────────────▼─────────────┐
             │ Lightweight Frontend PWA  │
             │ (HTML5 / Tailwind / JS)   │
             └─────────────┬─────────────┘
                           │
       ┌───────────────────┼───────────────────┐
       ▼                   ▼                   ▼
┌──────────────┐   ┌──────────────┐   ┌────────────────┐
│ Multilingual │   │ Interactive  │   │  Helpline 1930 │
│ Scenario DB  │   │ Sandbox & XP │   │ Reporting Flow │
│ (Hindi/Tamil)│   │  Evaluator   │   │ & Golden Hour  │
└──────────────┘   └──────────────┘   └────────────────┘
```

* **Frontend:** Modern, responsive HTML5 + Tailwind CSS (zero heavy bundle overhead, <3MB footprint).
* **Architecture:** Mobile-first, Progressive Web App (PWA) ready, designed for low-bandwidth 2G/3G connectivity.
* **Internationalization (i18n):** Client-side instant language toggle (English, हिन्दी, தமிழ்).
* **Security & Privacy:** 100% client-side simulation. No user credentials, phone numbers, or telemetry stored.

---

## 📱 Supported Scam Scenarios in Prototype
| Scenario | Category | Attack Vector Explored |
|---|---|---|
| **Electricity Cut-off SMS** | Utility Scam | Psychological urgency, fake 10-digit customer care number, malicious APK link. |
| **UPI PIN Collect Fraud** | Financial Scam | "Enter PIN to receive cashback" deception (Golden Rule: PIN is only for sending money). |
| **Bank KYC Suspension** | Phishing | Unofficial domain cloning (`sbi-kyc-verify-portal.in`), fake account block threat. |
| **KBC SIM Lucky Draw** | Advance-Fee | Foreign country code (+92), advance processing fee demand. |

---

## 🎯 Alignment with UN SDGs & Viksit Bharat
* **UN SDG 4 (Quality Education):** Democratizes digital literacy and practical cyber education.
* **UN SDG 9 (Industry, Innovation & Infrastructure):** Builds a secure, trusted digital financial public infrastructure.
* **Viksit Bharat 2047:** Protects grassroots capital and rural digital adoption from organized cybercrime syndicates.

---

## 📂 Project Structure
```text
grassroots-cyber-immunity/
├── index.html        # Main interactive simulation web application
├── README.md         # Comprehensive documentation & setup instructions
├── LICENSE           # Open-source MIT License
└── scenarios.json    # Modular scam vector scenario dataset (extensible)
```

---

## 🤝 Contributing
Contributions are welcome! If you want to add new regional scam vectors or translate scenarios into more Indian languages (Telugu, Bengali, Marathi, Gujarati):
1. Fork the repo.
2. Add your scenario to the dataset.
3. Submit a Pull Request.

---

## 📜 License
Distributed under the MIT License. See `LICENSE` for more information.
