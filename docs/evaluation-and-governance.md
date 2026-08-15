# Evaluation and Governance

## Technical evaluation

The paper proposes assessing predictive discrimination and calibration, simulation fidelity, uncertainty estimation, robustness and subgroup performance. AUROC is discussed as an example of a discrimination measure for prediction tasks, while RMSE is discussed for comparing simulated physiological quantities with measured values.

The paper also proposes testing resilience to data-quality variation and streaming latency and evaluating performance across sex, age, ethnicity and comorbidity subgroups.

## Clinical evaluation

A real-world evaluation would need clinical evidence rather than model metrics alone. Suggested endpoints include 30-day readmission, mortality and NYHA class for heart failure, and ablation success, recurrence and stroke prevention for atrial fibrillation.

## Economic evaluation

The framework also considers cost-effectiveness and quality-adjusted life years. The purpose is to determine whether a digital-twin approach provides meaningful value in addition to clinical benefit.

## Governance and safety

The paper discusses:

- privacy-by-design and pseudonymisation
- role-based access and multifactor authentication
- encryption and auditability
- model drift and performance monitoring
- explainability and clinician oversight
- bias and equity assessment
- interoperability across NHS environments
- alignment with UK GDPR, MHRA SaMD/AIaMD guidance and the NICE Evidence Standards Framework

## Important distinction

The metrics and thresholds described in this document are **proposed evaluation requirements or examples from the paper**, not measured results from an NHS deployment. This repository contains no patient data and does not claim clinical validation.
