# uk-hta-model
Interactive healthcare finance and pharmacoeconomic simulator modeling UK market access, NICE drug reimbursement, and QALY cost-effectiveness for new medicines.
# UK Market Access & NICE Health Technology Assessment (HTA) Model

An interactive healthcare finance and pharmacoeconomic simulator modeling **UK market access**, **NICE drug reimbursement pathways**, and **QALY cost-effectiveness** for innovative medicines in England and Wales.

🔗 **Live Interactive Simulator:** [Launch Web App](https://github.io)

---

## Overview

In the UK, the **National Institute for Health and Care Excellence (NICE)** evaluates whether new medicines provide sufficient clinical benefit to justify their cost to the National Health Service (NHS). 

This web-based simulator allows users to explore the commercial and clinical trade-offs behind pharmaceutical pricing, Patient Access Schemes (PAS), and cost-effectiveness thresholds.

---

## Key Features

* **Interactive QALY Sensitivity Curve:** Visualizes how net drug pricing and commercial discounts shift the Incremental Cost-Effectiveness Ratio (ICER) relative to NICE willingness-to-pay thresholds.
* **Therapeutic Area Presets:** Includes three pre-configured clinical scenarios reflecting real-world UK market access pathways:
  * **CAR-T Oncology Therapy:** Models high upfront cell therapy costs and substantial survival gains.
  * **Cardiometabolic Biologic:** Models chronic biologic therapy pricing across larger patient populations.
  * **Paediatric Gene Therapy:** Models ultra-rare one-off curative therapies evaluated under NICE's **Highly Specialised Technology (HST)** pathway (£100,000 per QALY ceiling).
* **Dynamic Parameter Controls:** Adjust pricing discounts and model inputs in real time to see where a therapy crosses into cost-effective reimbursement territory.

---

## Health Economics & Finance Concepts Modeled

* **QALY (Quality-Adjusted Life Year):** Combines length of life and health-related quality of life (on a 0 to 1 scale) into a single metric to compare value across different medical conditions.
* **NICE Willingness-to-Pay Thresholds:**
  * **Standard Technology Appraisal:** Typically **£20,000 – £30,000 per QALY** gained.
  * **Highly Specialised Technologies (HST):** Up to **£100,000 per QALY** (and higher with QALY weighting) for ultra-rare conditions with low overall NHS budget impact.
* **Commercial Discounts (PAS):** Demonstrates how confidential list-price discounts reduce the net cost per QALY to achieve positive NICE guidance.

---

## Technology Stack

* **HTML5 / CSS3** with **Tailwind CSS** for responsive UI layout
* **JavaScript (ES6)** for real-time pharmacoeconomic calculations
* **Chart.js** for interactive cost-effectiveness curve rendering

---

## Disclaimer

*This simulator is built for educational, analytical, and portfolio demonstration purposes. All preset figures and scenarios are illustrative models of UK HTA principles and do not represent confidential commercial agreements or official NICE clinical guidance.*
