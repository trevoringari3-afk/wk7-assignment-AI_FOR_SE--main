# AI Ethics Assignment: Designing Responsible and Fair AI Systems 

## Overview

This repository contains the AI Ethics Assignment for the PLP Academy.  
The project focuses on analyzing, auditing, and reflecting on ethical considerations in AI systems.  
It includes theoretical analyses, case studies, practical fairness audits on the COMPAS dataset, and reflections on ethical AI design.


## Project Structure

AI_Ethics_Assignment/
│
├── part1_theory/
│ └── theory_answers.pdf # Short answers and ethical principles matching
│
├── part2_case_studies/
│ └── case_studies.pdf # Case study analyses (Biased Hiring, Facial Recognition)
│
├── part3_practical_audit/
│ ├── compas.csv # COMPAS dataset used for fairness audit
│ ├── audit.ipynb # Jupyter Notebook with fairness analysis
│ ├── audit_report.pdf # 300-word report summarizing audit findings
│ └── processed/ # Folder containing cleaned and prepared datasets
│ ├── compas_prepared.csv
│ ├── compas_features_encoded.csv
│ └── compas_labels.csv
│
├── part4_reflection/
│ └── reflection.pdf # Ethical reflection on personal AI project
│
├── bonus/
│ └── ethical_ai_healthcare.pdf # Bonus task: 1-page ethical AI guidelines for healthcare
│
└── README.md # This file

## Assignment Parts

### Part 1 — Theoretical Understanding
- Short answers on algorithmic bias, transparency, explainability, GDPR.
- Ethical principles matching exercise.

### Part 2 — Case Study Analysis
- Analysis of biased AI systems: Amazon hiring tool and facial recognition in policing.
- Identification of ethical risks, bias sources, and recommended fixes.

### Part 3 — Practical Audit
- Preprocessing of the COMPAS dataset.
- Logistic Regression model training.
- Fairness evaluation using metrics:
  - Disparate Impact (DI)
  - Equal Opportunity Difference (EOD)
  - False Positive Rate Difference (FPRD)
- Visualizations and audit report.

### Part 4 — Ethical Reflection
- Reflection on ethical considerations in a personal AI project.

### Bonus Task
- Drafted 1-page ethical AI guidelines for healthcare.

---

## How to Run the Practical Audit Notebook

1. Ensure Python 3.x is installed.
2. Install required packages:

```bash
pip install pandas matplotlib scikit-learn aif360
Open part3_practical_audit/audit.ipynb in Jupyter Notebook.

Run cells step by step to replicate the fairness audit.

Generated outputs include metrics, visualizations, and the cleaned dataset in processed/.

Notes
All PDFs are ready for submission.

The dataset compas.csv is sourced from publicly available COMPAS data.

The project demonstrates fairness auditing techniques, bias mitigation, and ethical reflection.

Author
Otieno Mohan
PLP Academy AI Ethics Assignment
November 2025