# Aarki Analytics Challenge: Optimizing Lead Quality & ROI

## Project Overview
This project analyzes a dataset of 3,021 debt consolidation leads to identify drivers of lead quality and conversion. The primary objective is to reach a 9.6% conversion threshold (Closed Rate) to unlock a 20% CPL increase from the advertiser.

## Business Objectives
* **Trend Analysis:** Determine if monthly lead quality changes are statistically significant.
* **Segment Identification:** Isolate high-performing demographics and "toxic" segments draining the budget.
* **Optimization Strategy:** Implement a negative-targeting framework to lift the aggregate conversion rate from 8.11% to the target 9.6%.

## Key Insights
* [cite_start]**Systemic Decay:** Statistical testing (Chi-Square) confirmed a significant downward trend in lead quality (p-value = 0.0006)[cite: 30].
* [cite_start]**High-Intent Segments:** "Stop Collections" and "Holding Tank" ad groups convert at ~15%, double the baseline average[cite: 58].
* [cite_start]**Target Profile:** The "Sweet Spot" for conversion is leads with $10k–$50k in declared debt[cite: 59].
* [cite_start]**Efficiency Gap:** The "Student Debt" segment accounted for 12% of volume but only a 1.1% conversion rate[cite: 60].

## Optimization Results
[cite_start]By suppressing the Student Debt segment and filtering extreme debt outliers (<$10k or >$100k), the overall conversion rate was successfully lifted to **10.06%**, exceeding the advertiser's target and securing the higher CPL payout[cite: 7, 74].

## Technical Stack
* **Language:** Python
* **Libraries:** Pandas (Data Cleaning), Matplotlib/Seaborn (Visualization), Scipy (Statistical Testing)

## Repository Structure
* `Aarki_Lead_Analysis.ipynb`: Complete technical analysis and statistical proofs.
* `Ad_Tech_Case_Study_Deck.pdf`: Executive-level business presentation.