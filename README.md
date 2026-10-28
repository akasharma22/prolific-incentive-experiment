# Performance-Based Pay & Worker Output — A Prolific Field Experiment

**ResEcon 428 · University of Massachusetts Amherst · November 2024**

**Team:** Abha Dewal, Anjalika Arora, Akanksha Sharma

## Question
Does a performance-linked bonus get more and better work from online workers than a higher guaranteed payment?

## Design
A natural field experiment on Prolific.com (n = 44). Workers wrote a 150–200 word review of the Massachusetts voter registration website under one of two pay schemes:

| Condition | Pay | Time limit |
|---|---|---|
| Baseline | $2.00 guaranteed | 30 min |
| Treatment | $1.50 base + $0.50 bonus for meeting stated quality criteria | 35 min |

Responses were scored on word count, a quality score, and typos per 10 words. Effects were estimated with OLS, with and without controls for gender, ethnicity, English as a first language, and perceived website clarity.

## Results

| Outcome | Treatment effect | p-value | R² |
|---|---|---|---|
| Word count | +103 words | < 0.001 | 0.68 |
| Word count (with controls) | +98 words | < 0.001 | 0.74 |
| Quality score | +3.01 points | 0.0002 | 0.28 |
| Quality score (with controls) | +2.55 points | 0.0013 | 0.41 |
| Typos per 10 words | −0.034 | 0.0076 | 0.16 |

## Takeaway
A lower guaranteed wage paired with a clear, criteria-based bonus outperformed a higher flat payment on both quantity and quality. Explicit evaluation criteria appear to matter as much as the money.

## Files
- `428_Final_Project.pdf` — full report with regression output and source responses

**Methods & tools:** Experimental design · OLS regression · T-tests · Qualtrics · Prolific · Excel
