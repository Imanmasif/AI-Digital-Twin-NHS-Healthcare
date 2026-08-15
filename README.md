# AI-Powered Digital Twin for Personalised Healthcare in the NHS

**IEEE IMCOM 2026 | Research paper companion repository**

[![DOI](https://img.shields.io/badge/DOI-10.1109%2Fimcom69009.2026.11360793-blue)](https://doi.org/10.1109/imcom69009.2026.11360793)

## Overview

This repository accompanies the paper **AI-Powered Digital Twin for Personalised Healthcare in the NHS**, published at the 2026 20th International Conference on Ubiquitous Information Management and Communication (IMCOM).

The paper proposes a framework for using AI-powered digital twins to support personalised cardiovascular care within the NHS. The work brings together multimodal health data, interoperability standards, AI and machine learning, clinical decision support, and healthcare governance in a single architecture.

The repository is intended as a research companion to the published paper. It documents the proposed framework and its technical and clinical considerations; it is not presented as a deployed NHS clinical system or as a completed production implementation.

## Research focus

The work focuses on three connected areas:

- **System architecture** for an AI-powered patient digital twin
- **Cardiovascular personalisation**, with use cases covering heart failure and atrial fibrillation
- **Evaluation and governance**, including technical performance, clinical effectiveness, economic value, privacy, equity, and regulatory considerations

## Proposed architecture

The paper organises the digital twin into five interconnected layers:

1. **Data acquisition and ingestion** — EHRs, laboratory results, medical imaging, wearable and device data, and other relevant health information.
2. **Data harmonisation and integration** — standards and processes for interoperable and consistent data, including FHIR, SNOMED CT, LOINC, and ICD-10.
3. **Digital twin core** — AI/ML prediction models combined with biophysical and computational modelling to represent patient state and explore possible trajectories.
4. **Personalisation and clinical decision support** — risk forecasts, treatment comparisons, visualisation, and clinician-facing decision support.
5. **Governance, security, and deployment** — privacy, access control, auditability, monitoring, explainability, bias assessment, and alignment with NHS and UK regulatory expectations.

## Cardiovascular use cases

The paper uses cardiovascular care to illustrate how the framework could support personalised decision-making.

### Heart failure

The proposed twin can combine clinical records, imaging, laboratory results, and wearable measurements to maintain an evolving patient model. It can then support risk prediction and what-if analysis around treatment changes, such as medication titration, while presenting the resulting estimates to clinicians.

### Atrial fibrillation

The paper also considers personalised planning for atrial fibrillation ablation. Cardiac imaging, electrophysiological information, and patient-specific modelling can be combined to explore possible intervention strategies and recurrence risks.

## Data and implementation scope

The paper describes how an NHS-oriented system could ingest and harmonise multimodal health data, but it does **not** provide a public patient dataset or claim to have deployed the proposed digital twin in the NHS.

Accordingly, this repository does not contain patient records, clinical datasets, or a production clinical implementation. The architecture and implementation considerations should be read together with the published paper.

## Evaluation approach

The proposed evaluation framework considers more than model accuracy. It includes:

- predictive discrimination and calibration
- simulation fidelity and uncertainty estimation
- robustness and subgroup evaluation
- clinical outcomes such as readmission, mortality, and treatment outcomes
- economic value and cost-effectiveness
- privacy, security, explainability, bias, and clinician oversight
- operational interoperability and scalability across NHS environments

The paper discusses metrics such as AUROC and RMSE as examples of technical evaluation measures and emphasises the need for real-world clinical evidence before deployment.

## Documentation

- [Research summary](docs/research-summary.md)
- [System architecture](docs/architecture.md)
- [Cardiovascular use cases](docs/use-cases.md)
- [Evaluation and governance](docs/evaluation-and-governance.md)
- [Limitations and future work](docs/limitations-and-future-work.md)

## Governance and responsible use

Healthcare digital twins involve highly sensitive information and require strong governance. The paper discusses privacy-by-design, pseudonymisation, access controls, audit trails, encryption, model monitoring, explainability, bias assessment, and clinician override mechanisms. It also considers relevant NHS and UK frameworks, including FHIR interoperability, UK GDPR, MHRA SaMD/AIaMD guidance, and the NICE Evidence Standards Framework.

This repository is for **research and educational purposes**. Nothing here should be interpreted as medical advice, a validated clinical decision system, or evidence that the proposed framework is ready for clinical deployment.

## Publication

**AI-Powered Digital Twin for Personalised Healthcare in the NHS**  
Fawaz Ahmed Dar, Iman Muhammad Asif, Irfan Ahmed  
2026 20th International Conference on Ubiquitous Information Management and Communication (IMCOM), IEEE, 2026.  
DOI: https://doi.org/10.1109/imcom69009.2026.11360793

## Citation

```bibtex
@inproceedings{dar2026digitaltwin,
  title={AI-Powered Digital Twin for Personalised Healthcare in the NHS},
  author={Dar, Fawaz Ahmed and Asif, Iman Muhammad and Ahmed, Irfan},
  booktitle={2026 20th International Conference on Ubiquitous Information Management and Communication (IMCOM)},
  publisher={IEEE},
  year={2026},
  doi={10.1109/imcom69009.2026.11360793}
}
```

## Repository note

This repository is maintained as a concise research companion to the publication. The published paper remains the primary source for the complete methodology, references, architecture, use cases, evaluation framework, and discussion of limitations.
