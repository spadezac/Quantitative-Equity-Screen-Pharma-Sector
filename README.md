# Quantitative Equity Screen: Indian Pharmaceutical Sector

### Project by Simran Gupta | July 2025

---

## 1. Project Overview

This repository contains a data-driven analysis project designed to systematically screen the Indian Pharmaceutical sector. A Python script was developed to programmatically analyze over 200 publicly listed companies and identify a shortlist of high-quality investment opportunities based on a rigorous set of fundamental financial metrics.

The goal of this project is to showcase a practical, real-world application of combining technical programming skills with financial analysis, mirroring the initial research process conducted by financial analysts in an investment banking or research setting.

---

## 2. Key Outputs

This repository contains three primary files:

1.  **`pharma_screener.py`**: The core Python script that uses the Pandas library to perform data loading, cleaning, filtering, and analysis.
2.  **`Investment_Memo.pdf`**: A professional one-page memo summarizing the project's objective, methodology, results, and recommended next steps. This is the final deliverable of the analysis.
3.  **`pharma_data.csv`**: The raw data file containing the financial metrics for 200+ companies in the Indian Pharmaceutical sector, as sourced from Screener.in.

---

## 3. Screening Methodology

To ensure an objective and efficient analysis, a multi-factor screening model was applied. A company was required to pass **all five** of the following criteria to be included in the final shortlist:

| Metric | Criteria | Rationale |
| :--- | :--- | :--- |
| **Scale (Market Cap)** | `> ₹20,000 Cr` | To focus on large, established companies with significant market presence. |
| **Growth (3-Yr Sales)** | `> 15%` | To identify companies with a proven track record of sustained top-line growth. |
| **Profitability (ROCE)** | `> 15%` | To select for businesses that generate high returns on their total capital base. |
| **Solvency (D/E Ratio)** | `< 0.5` | To ensure financial prudence and a low-risk balance sheet. |
| **Valuation (P/E Ratio)** | `< 50` | To screen for companies trading at reasonable valuations and avoid speculative hype. |

---

## 4. Final Results

The screening process successfully identified the following two companies that met every established criterion:

| Company Name | Market Cap (Cr) | P/E Ratio | Debt to Equity | 3-Yr Sales Growth (%) | ROCE (%) |
| :--- | :--- | :--- | :--- | :--- | :--- |
| **Zydus Lifesci.** | 100,192.08 | 21.58 | 0.13 | 15.43 | 24.31 |
| **J B Chemicals &** | 28,188.60 | 44.08 | 0.01 | 17.35 | 25.79 |

---

## 5. Skills Demonstrated

* **Financial Analysis:** Understanding and application of key financial ratios (P/E, ROCE, D/E) and stock screening methodologies.
* **Python for Data Analysis:** Proficient use of the **Pandas** library for data ingestion, cleaning, manipulation, and analysis.
* **Problem-Solving:** Developing a logical workflow to translate a financial concept into a functional program.
* **Communication & Synthesis:** Clearly summarizing a complex quantitative analysis into a concise and professional investment memo.
