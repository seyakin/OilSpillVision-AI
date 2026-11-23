## Deep Learning for Oil Spill Detection and Segmentation in SAR Imagery

### Overview

Oil spills in marine and aquatic environments present significant environmental, ecological and economic risks. Rapid identification and spatial delineation of oil slicks can support environmental monitoring, incident assessment and response planning.

OilSpillVision-AI is a research portfolio project exploring the application of computer vision and deep learning to oil spill detection and segmentation in Synthetic Aperture Radar (SAR) imagery.

The project aims to investigate the identification of potential oil slicks, the differentiation of oil slicks from look-alike phenomena, and the segmentation of spill-affected areas using image-based machine learning techniques.

### Research Objectives

1. Explore suitable SAR imagery datasets for oil spill detection research.
2. Develop an image preprocessing and data preparation workflow.
3. Establish a baseline deep learning model for oil spill detection.
4. Investigate image segmentation approaches for delineating potential oil slicks.
5. Evaluate model performance, generalisation and limitations.
6. Document a reproducible experimental workflow.

### Proposed Methodology

- Dataset acquisition and exploratory data analysis.
- Image preprocessing and dataset preparation.
- Baseline machine learning and deep learning experiments.
- Image segmentation experiments.
- Model evaluation using appropriate classification and segmentation metrics.
- Reproducibility, documentation and error analysis.

### Planned Evaluation

Classification metrics may include:

- Precision
- Recall
- F1-score
- Accuracy, where appropriate
- ROC-AUC, where appropriate

Segmentation metrics may include:

- Intersection over Union (IoU)
- Dice coefficient
- Precision and recall

The final evaluation metrics will depend on the dataset, task definition and experimental design.

### Project Status

**Status: Initial setup and research planning.**

No model performance claims are made at this stage.

### Planned Project Structure

```text
OilSpillVision-AI/
├── README.md
├── requirements.txt
├── notebooks/
├── src/
├── data/
├── results/
├── docs/
└── references/
```

### Research Scope and Limitations

This project is an experimental research initiative. The identification of SAR dark spots alone does not establish the presence of petroleum contamination. Wind conditions, biogenic slicks, natural surfactants and other environmental phenomena may produce similar image signatures.

The models developed in this project will therefore be treated as research and decision-support tools rather than definitive spill confirmation systems.

### Researcher

Oluseye Akinmuda

Environmental Scientist | Applied Machine Learning Researcher

GitHub: https://github.com/seyakin
