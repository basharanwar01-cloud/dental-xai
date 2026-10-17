# Explainable AI for Dental Disease Classification from Panoramic Radiographs

CSC621 Master's project, Qassim University (Department of Cybersecurity).
Author: Bashar Anwar. Supervisor: Dr. Haifa Al-Hassoun.

## Goal
Train CNN classifiers on panoramic dental radiographs and compare several
explanation methods (Grad-CAM, Grad-CAM++, LIME, SHAP) using standard
classification metrics plus explanation-faithfulness metrics.

## Status
- [ ] Week 1-2: dataset chosen, preprocessing, baseline classifier, first results
- [ ] Week 3-4: remaining backbones compared
- [ ] Week 5-6: explainability methods + faithfulness metrics
- [ ] Week 7-8: clinical-alignment review, final report

## Structure
- `data/`       dataset instructions (raw data is NOT committed)
- `src/`        dataset loading, training, explanation, evaluation code
- `notebooks/`  Kaggle/Colab experiments
- `results/`    metrics tables and figures
- `configs/`    hyperparameters

## Setup
```
pip install -r requirements.txt
```

## Dataset
See `data/README.md`.

## Results
To be filled in from real experiment runs.
