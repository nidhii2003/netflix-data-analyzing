# 🎬 Netflix India User Retention Command Deck
### *Real-Time Telemetry Event Stream & Algorithmic Churn Mitigation Pipeline*

An enterprise-grade behavioral analytics application built to simulate real-time user engagement tracking, identify subscriber anomalies across domestic Indian tier matrices (₹149 - ₹649), and execute automated automated mitigation strategies before user subscription churn occurs.

---

## 🚀 Live Operational Demo
👉 **[Click Here to Launch the Live Interactive Dashboard](https://nidhii2003.github.io/netflix-data-analyzing/)**

---

## 💡 Project Purpose: Why is this Architecture Necessary?
In modern SaaS architectures (like Netflix, Hotstar, or Spotify), customer acquisition costs are exponentially higher than retention costs. If a user completely drops their activity window, it is often too late to prevent a cancellation. 

**This system solves that enterprise vulnerability by:**
1. **Ingesting Event Telemetry Early:** Processing streaming user signals (pausing indefinitely, running empty searches, multi-skipping content) directly in-memory.
2. **Quantifying Financial Impact Instantly:** Translating behavioral drops into clear financial visibility (Total Monthly Revenue at Risk in INR) so business leaders know exactly how much capital is vulnerable at any given second.
3. **Automating Dynamic Marketing Interventions:** Running real-time thresholds via user controls to trigger precision micro-actions (e.g., custom discount delivery, immediate high-priority support flags).

---

## 🛠️ The Technology Stack & System Components

- **Frontend Interface Architecture:** Structured exclusively with utility-first responsive **Tailwind CSS** styles to mimic modern production SaaS admin systems.
- **Dynamic Render & State Processing:** Engineered using vanilla **JavaScript (ES6+)** runtime loops to handle simulated data packet streams without framework overhead.
- **Analytical Vector Graphics:** Powered by **Chart.js** to render automated categorical data charts mapped to multi-tier profile counts in real time.
- **Data Serialization Structure:** Explicit JSON-formatted payloads visible in a real-time debugging view component to mirror REST API data transfers.

---

## 🧠 The Business Logic & Scoring Rules Model
The system processes simulated continuous transactions through a state-machine loop that calculates an **Engagement Health Index** score ($0\%$ to $100\%$):

* **Safe State ($\ge 50\%$ Health):** User behavior shows normal engagement velocity. The pipeline flags the account state as `No Intervention Required`.
* **Decay State ($25\%$ to $50\%$ Health):** User behavior signals disinterest (e.g., *Empty Search Outcomes*). If the score drops below your chosen slider threshold, it automatically triggers a `Queue Plan Renewal Discount`.
* **Critical Outlier State ($< 25\%$ Health):** High-risk actions (e.g., *Profile Deletion Screen Viewed*). The application immediately forces a `Dispatch High Priority Support Call` routine to prevent total subscription loss.

---

## 📋 Daily Operational Usage Guide

This tool acts as a command deck for three distinct business teams:

### 1. Data Analysts / Retention Managers
- Use the **Offer Trigger Sensitivity Slider** to run real-time stress testing simulations on vulnerable customer clusters.
- Toggle the **Plan Profile Filters** to isolate exactly which tier segments (Premium vs Mobile) are currently experiencing high attrition.

### 2. Marketing Operations
- Monitor the **Automated System Actions** log rows to see what kind of retention messaging payloads (discounts, text alerts) are being generated dynamically.

### 3. Software & Data Engineers
- Track the **Developer JSON Payload Stream** box at the bottom right. This component lets engineers inspect the exact data structure formatting that would be transferred via an API endpoint connection to back-end services.
