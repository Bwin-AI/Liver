# LiverQ&A Dataset (Anonymized Subset, n = 50)

This repository contains a representative, anonymized subset of the LiverQ&A dataset, used in the paper:

"HEAL: LLM-based Hybrid Evidenced Adaptive Learning Model for Liver Disease Diagnosis"

---

##  Overview

LiverQ&A is a real-world clinical dataset compiled from multiple tertiary hospitals. It contains structured medical records of patients diagnosed with various types of liver diseases.

Due to privacy regulations, only a subset of 50 anonymized cases is released here. This sample reflects the diversity of disease types, diagnostic complexity, and multimodal information used by our model.

---

##  File Structure

- `case.xlsx`  
   Contains 50 structured clinical cases. Each row represents a patient case.

---

##  Data Fields 

| main context            | Description |
|-------------------------|-------------|
| `chief_complaint`       | Main symptoms reported at admission |
| `present_illness`       | History of present illness  |
| `past_history`          | Past medical history (e.g., hypertension, hepatitis) |
| `family_history`        | Family history of liver-related diseases |
| `ultrasound_report`     | Key ultrasound findings |
| `mri_report`            | Key MRI findings |
...

##  Suggested Use

This dataset can be used to:
- Benchmark medical NLP models on structured diagnostic reasoning
- Evaluate case complexity classification algorithms
- Explore multi-agent or ensemble learning settings for diagnosis
- Reproduce ablation and robustness experiments in the original paper

---

##  Ethical and Legal Considerations

- All data has been **fully anonymized**.
- No personally identifiable information (PII) or hospital-specific references are present.
- This subset is released **strictly for academic and non-commercial research purposes**.
- Any use of the data should cite the associated paper.

---
