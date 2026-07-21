# Revenue Assurance & Reconciliation Analysis

#### Revenue Leakage Analysis | Payment Reconciliation | Power BI | DAX

## Project Overview

This project presents an interactive **Revenue Assurance & Reconciliation Dashboard** built to help a business monitor revenue leakage, payment settlement performance, and sales representative accountability across regions, channels, and payment methods. The dashboard consolidates transaction-level data into an executive reporting solution that enables stakeholders to identify where expected revenue is being lost and take corrective action.

---

# Business Problem

Businesses processing high transaction volumes often struggle to detect where revenue is being lost between what's expected and what's actually collected. Without a consolidated view, leakage from failed payments, partial settlements, and delayed reconciliations can go unnoticed until it materially affects profitability.

This dashboard addresses that gap by tracking expected vs. actual revenue, breaking down leakage by region, sales rep, and payment channel, and surfacing which transactions are fully reconciled versus at risk — enabling faster, more targeted intervention.

---

# Dashboard Pages

##  Executive Financial Overview

Provides a high-level summary of revenue performance, leakage, and settlement efficiency

<p align="center">
  <img src="https://github.com/Estee200/POWERBI-PROJECTS/blob/main/Revenue%20Assurance%20%20&%20Reconciliation%20Analysis/Images/Executive%20Overview.png?raw=true" alt="Revenue Leakage Executive Dashboard" width="800">
</p>


### Business Insights

- Out of ₦13M in expected revenue, only ₦9M was actually received — a revenue leakage of ₦4M, signaling a material gap between billed and collected amounts that warrants urgent investigation.
- Monthly revenue shows a consistent dip around June across both expected and actual figures, suggesting a seasonal or operational pattern worth planning around.
- Lagos generates the highest revenue among all regions, reinforcing it as the business's core market and a priority for retention and support.
- Card Payment and Mobile Banking show the highest volumes of settlement delays compared to POS, Bank Transfer, and USSD — pointing to these channels as key areas for process improvement.
- Online transactions drive more revenue than Retail, highlighting the growing importance of digital channels to the business.

---

##  Representatives Performance
Provides a breakdown of sales rep performance, revenue generation, and leakage exposure

<p align="center">
  <img src="https://github.com/Estee200/POWERBI-PROJECTS/blob/main/Revenue%20Assurance%20%20&%20Reconciliation%20Analysis/Images/Representatives%20Performance.png?raw=true" alt="Representative Performance Dashboard" width="800">
</p>

### Business Insights

- Tunde Adebayo is the top-performing rep by revenue (₦1.84M), but also carries the highest revenue leakage (₦931K) — indicating that higher sales volume is coming with proportionally higher collection risk.
- All five sales reps show a leakage rate close to 0.5% of expected revenue, suggesting the issue is systemic across the team rather than tied to individual rep performance.
- Order volume is fairly evenly distributed across reps (ranging from 949 to 1,056 orders), showing a balanced workload rather than one rep being overloaded.
- With ₦4.39M in total leakage against ₦13.1M expected across all reps, closing even a fraction of this gap could meaningfully improve overall revenue realization.

---

##  Revenue Assurance & Reconciliation
Provides detailed analysis of revenue leakage sources and payment reconciliation status

<p align="center">
  <img src="https://github.com/Estee200/POWERBI-PROJECTS/blob/main/Revenue%20Assurance%20%20&%20Reconciliation%20Analysis/Images/Revenue%20Assurance.png?raw=true" alt="Revenue Assurance Dashboard" width="800">
</p>

### Business Insights

- Only 46.28% of transactions are fully reconciled, meaning more than half of all transactions have some form of payment gap — a significant operational red flag.
- Failed payments (32.64%) and partial payments (20.18%) together account for over half of all transaction outcomes, suggesting the payment collection process itself may need re-evaluation.
- Lagos leads in revenue leakage (₦530K), followed by Kaduna and Owerri — showing leakage is concentrated in a handful of regions rather than spread evenly.
- Several high-value orders show 100% leakage (₦0 received against amounts near ₦5,000), indicating these may be failed or abandoned transactions that need direct follow-up rather than partial recovery efforts.

---

# Recommendations

- Investigate the ₦4M revenue leakage gap as a priority, starting with the highest-leakage regions (Lagos, Kaduna, Owerri) and payment channels (Card, Mobile Banking).
- Review reconciliation processes given that only 46.28% of transactions are fully settled — target reducing failed and partial payments through improved payment retry logic or customer follow-up.
- Investigate orders with 100% leakage individually, as these likely represent failed transactions requiring direct recovery action rather than systemic fixes.
- Since leakage is consistent across reps (~0.5%), address it at the process/payment-infrastructure level rather than through individual rep performance management.
- Monitor the recurring June revenue dip to determine whether it's seasonal and plan resourcing/collections activity accordingly.

---

# Tools & Technologies

- Microsoft Power BI
- Power Query
- DAX
- Data Modelling

---

# Dataset

The dashboard was developed using a **transaction-level payment dataset** capturing order, revenue, and settlement details across regions, sales reps, and payment channels.

The dataset includes:

- Order ID and Transaction Date
- Expected Amount and Amount Received
- Payment Status (Failed, Partial, Successful)
- Payment Channel (Card, Mobile Banking, POS, Bank Transfer, USSD)
- Sales Representative
- Region/State
- Settlement Date
- Sales Channel (Online/Retail)

> **Note:** This project uses a synthetic dataset created solely for educational and portfolio purposes.
