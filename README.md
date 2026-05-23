# Retail overview: chips
its a virtual internship with hands on experience project ,here we are finding the chips sales analysis
Here's a detailed README based on your actual PowerPoint presentation:

---

# 🛒 Retail Overview: Chips Sales Analysis

**Quantium Virtual Internship | Retail Analytics | June 2020**

A hands-on virtual internship project analyzing chip category sales data to uncover customer purchasing behavior and evaluate the impact of a store trial intervention.

---

## 📌 Project Overview

This project is part of the **Quantium Virtual Experience Program**, structured into two tasks:

| Task | Focus |
|------|-------|
| Task 1 | Data Preparation & Customer Analytics |
| Task 2 | Experimentation & Uplift Testing |

---

## 📁 Repository Structure

| File | Description |
|------|-------------|
| `QVI_transaction_data.xlsx` | Raw chip purchase transaction data |
| `QVI_purchase_behaviour.csv.xlsx` | Customer segmentation & behavior data |
| `QVI_data.csv` | Cleaned and merged dataset |
| `basic_questions.ipynb` | Exploratory data analysis |
| `intermediante_Q.ipynb` | Intermediate-level analysis & insights |
| `def_function.ipynb` | Reusable helper functions |
| `note_loop.ipynb` | Loop-based analysis examples |
| `quantium_task2.docx` | Task 2 trial analysis report |

---

## 🎯 Task 1 — Data Preparation & Customer Analytics

**Objective:** Understand customer purchasing behavior by cleaning and analyzing transaction data.

### Steps Performed
- Created high-level summaries of the data
- Identified and removed outliers
- Corrected data formats
- Derived extra features: **pack size** and **brand name**
- Defined key metrics to understand who spends on chips and what drives spend per segment

### Key Findings

**Transaction Trends**
- Chip transactions remained relatively consistent week-over-week
- A notable spike occurred **the week before Christmas**
- Christmas week itself saw a sharp drop due to **public holiday store closures**

**Customer Segmentation (by Life Stage & Premium Tier)**
- **Older Families** and **Young Families** purchase the highest average units per transaction (~9 units)
- **Mainstream Young Singles & Couples** form the **largest proportion** of chip shoppers
- **Mainstream Retirees** also hold a significant customer share
- Affluence (Budget / Mainstream / Premium) is relatively consistent within each life stage

---

## 🧪 Task 2 — Experimentation & Uplift Testing

**Objective:** Evaluate the performance of a store trial conducted in stores **77, 86, and 88** during **Feb–Apr 2019**.

### Methodology
- Selected **control stores** as "lookalikes" of trial stores for a fair, meaningful comparison
- Compared total sales and customer counts during the trial period
- Applied **statistical significance testing** (95% confidence intervals)

### Trial Results

| Store | Sales Uplift | Customer Uplift | Verdict |
|-------|-------------|-----------------|---------|
| **77** | Significant in March (+36.7%) & April (+62.3%) | Significant in March & April | ✅ Successful |
| **86** | Only significant in March (+31.6%) | Significant across all 3 months | ⚠️ Mixed |
| **88** | Significant in March & April | Strong pre-trial alignment + clear uplift | ✅ Successful |

### Overall Conclusion
- **2 out of 3** trial stores (77 & 88) showed clear, statistically significant increases in both sales and customers
- Store 86 showed customer growth but limited sales uplift — possibly due to differences in implementation
- **The intervention was successful overall**, demonstrating measurable uplift in customer traffic and chip sales

---

## 🛠️ Tools & Technologies

- **Python** (Jupyter Notebook)
- **Pandas** — data cleaning & manipulation
- **Matplotlib / Seaborn** — data visualization
- **NumPy** — numerical operations

---

## 🚀 How to Run

```bash
git clone https://github.com/anugrahars87-design/Retail-overview-Chips.git
cd Retail-overview-Chips
jupyter notebook
```

Run notebooks in this order:
1. `basic_questions.ipynb`
2. `def_function.ipynb`
3. `intermediante_Q.ipynb`

---

## 🏢 About

This is a **Quantium Virtual Experience Program** project. All data is de-identified and used strictly for analytical learning purposes under Quantium's data privacy and security guidelines (ISO 27001 certified).

---

*⭐ Star the repo if you found it useful!*

---

This README is built directly from your presentation slides. You can copy-paste it straight into your GitHub `README.md`. Want me to export this as a `.md` file for download?
