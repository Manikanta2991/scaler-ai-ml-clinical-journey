# Resources: Datasets, Papers & References

## Overview

Curated collection of datasets, research papers, and clinical resources.

---

## Folders

### 1. Clinical Datasets
Open-source healthcare datasets
- MIMIC-III / MIMIC-IV
- eICU Collaborative Research Database
- PhysioNet datasets
- Medical Imaging datasets (CheXpert, ImageNet)

### 2. Research Papers
Seminal papers in AI/ML for healthcare
- Deep Learning
- NLP for Clinical Text
- Medical Imaging AI
- Clinical Prediction Models
- Fairness & Interpretability

### 3. Clinical Guidelines
Standard protocols and guidelines
- FDA guidance documents
- HIPAA compliance
- Clinical trial protocols
- Treatment guidelines

### 4. Benchmarks & Competitions
Datasets from Kaggle & competitions
- Medical image segmentation
- Clinical outcome prediction
- Drug discovery

---

## Key Resources

### Datasets
- **MIMIC-IV**: Free access to EHR data (PhysioNet)
- **CheXpert**: Chest X-ray interpretation
- **HAM10000**: Skin lesion classification
- **Alzheimer's**: MRI brain imaging

### Papers (Add to `papers/`)
- Key ML papers
- Healthcare AI research
- Clinical applications

### Tools & Libraries
- pandas, NumPy, scikit-learn
- PyTorch, TensorFlow
- Hugging Face, LangChain
- FastAPI, Streamlit

---

## Accessing Resources

```bash
# Example: Download MIMIC-IV
git clone https://github.com/MIT-LCP/mimic-code.git

# Example: Load dataset in Python
import pandas as pd
df = pd.read_csv('resources/datasets/mimic_sample.csv')
```

**See individual folders for detailed documentation.**