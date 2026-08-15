# System Architecture

The paper proposes five interconnected layers for an AI-powered cardiovascular digital twin in the NHS.

## 1. Data acquisition and ingestion

The framework considers multimodal inputs including electronic health records, medical imaging, laboratory results, wearable and implantable devices, medication information, and contextual public-health or social-determinant information. Real-time streams and less frequently updated sources may be ingested through different pipelines.

## 2. Data harmonisation and integration

Heterogeneous information is standardised before modelling. The paper discusses FHIR as the common resource structure and terminology mapping using SNOMED CT, LOINC and ICD-10. Data-quality checks and temporal alignment are also proposed.

## 3. Digital twin core

The central layer combines AI/ML prediction with biophysical and computational modelling. The paper discusses supervised models such as neural networks or gradient boosting, time-series models such as LSTMs and transformers, generative approaches for counterfactual prediction, and physics-informed neural networks as possible components.

The twin is intended to be updated as new patient information becomes available so that the computational representation remains aligned with the patient's changing state.

## 4. Personalisation and clinical decision support

Outputs are described as personalised risk forecasts, treatment comparisons, uncertainty-aware visualisations and clinician-facing decision support. The paper gives examples involving readmission risk, arrhythmia recurrence and therapy optimisation.

## 5. Governance, security and deployment

The proposed framework includes privacy-by-design, pseudonymisation, role-based access, multifactor authentication, encryption, audit trails, model monitoring, explainability, bias assessment and clinician override. The paper discusses alignment with NHS and UK regulatory expectations.

## Conceptual flow

```text
Multimodal NHS data
        ↓
Data ingestion and harmonisation
        ↓
Digital twin core
(AI/ML + computational modelling)
        ↓
Personalised predictions and simulations
        ↓
Clinical decision support
        ↓
Governance, monitoring and human oversight
```

This is the architecture proposed and discussed in the paper. It is not a claim that these layers have been implemented as a production NHS system in this repository.
