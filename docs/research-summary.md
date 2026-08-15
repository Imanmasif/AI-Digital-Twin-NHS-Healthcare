# Research Summary

## Paper

**AI-Powered Digital Twin for Personalised Healthcare in the NHS**

Fawaz Ahmed Dar, Iman Muhammad Asif, Irfan Ahmed. 2026 20th International Conference on Ubiquitous Information Management and Communication (IMCOM), IEEE, 2026.

DOI: https://doi.org/10.1109/IMCOM69009.2026.11360793

## Research problem

The paper addresses the limitations of reactive and population-focused care pathways for chronic cardiovascular conditions. It proposes an AI-powered patient digital twin that can combine multimodal health information into an evolving computational representation of a patient.

## Main contribution

The paper proposes and discusses a framework for designing and assessing an AI-powered digital twin for personalised cardiovascular care within the NHS. The contribution is organised around three dimensions:

1. system architecture
2. cardiovascular clinical application
3. evaluation and governance

## Data sources considered by the framework

The proposed architecture considers electronic health records, laboratory results, medical imaging, wearable and implantable device signals, medication information, and contextual public-health or social-determinant information. The paper discusses FHIR-based interoperability together with standards such as SNOMED CT, LOINC and ICD-10.

The paper does **not** provide a public patient dataset or claim to have deployed the proposed digital twin in the NHS.

## Clinical use cases

Two cardiovascular examples are used:

- **Heart failure:** personalised risk prediction, trajectory modelling and what-if assessment of treatment changes.
- **Atrial fibrillation:** patient-specific modelling and planning of ablation strategies using imaging and electrophysiological information.

## Evaluation concept

The proposed evaluation goes beyond predictive accuracy. It covers technical performance, simulation fidelity, clinical outcomes, economic value, robustness across patient subgroups, uncertainty, privacy, security, explainability, bias, interoperability and scalability.

## Status

This repository is a research companion to the published paper. The work presents a proposed framework and evaluation approach; it is not presented here as a deployed NHS clinical system or as a validated medical device.
