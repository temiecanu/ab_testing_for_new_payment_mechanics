# A/B Testing for New Payment Mechanics

## Project Overview

This project explores whether introducing a new payment mechanism can significantly improve monetisation metrics in an online learning marketplace. By conducting an A/B test and performing statistical analysis, I evaluated the conversion rate uplift between control and test groups.

### Company Context: EduPro

EduPro is a fictional learning platform which offers paid learning services. Improving payment conversion is crucial for revenue growth. The product team implemented a new payment flow and randomly assigned users to control and test groups. The business expects a measurable increase in purchase conversion.

---

## Business Goal

Assess whether a newly designed payment mechanic improves key monetisation metrics in EduPro’s online learning platform. Specifically, the goal was to test if the share of paying users, ARPU (Average Revenue Per User), or ARPPU (Average Revenue Per Paying User) showed significant improvements, and whether this justified scaling the change.

---

## Repository Structure

```
ab_testing_for_new_payment_mechanics/
│
├── data/
│   ├── active_studs.csv                        # Users active during the experiment period
│   ├── checks.csv                              # Payment confirmation data
│   ├── groups.csv                              # Initial user group assignment
│   └── groups_add.csv                          # Additional user assignments
│
├── ab_testing_for_new_payment_mechanics.ipynb  # Full A/B test analysis
├── README.md
```

---

## Key Findings
- No significant increase in the **share of paying users**
- No significant increase in **average revenue per user (ARPU)**
- Statistically significant increase in **average revenue per paying user (ARPPU)**

This suggests that while the new mechanic does not attract more buyers, it may be effective in increasing revenue from users already likely to pay. The feature is best scaled in targeted segments.

---

## How to Use

1. Clone the repository:
```bash
git clone https://github.com/artemietu/ab_testing_for_new_payment_mechanics.git
```

2. Install required packages:
```bash
pip install pandas scipy matplotlib
```

3. Open and run the Jupyter notebook:
```bash
ab_testing_for_new_payment_mechanics.ipynb
```

---

## Author

Artemie Țurcanu — Data Analyst
