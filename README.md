## Key Features
- ROI-based MRI analysis
- Simulation of PET-like biomarker
- Machine learning prediction (Random Forest)
- Multimodal imaging concept (MRI → PET)# multimodal-mri-pet-project
MRI-based prediction of PET-like biomarkers using machine learning
![Prediction](images/prediction_plot.png)
# MRI-based Prediction of PET-like Biomarker

## Overview
This project demonstrates a simplified multimodal imaging workflow inspired by PET-MRI studies. The aim is to investigate whether MRI-derived features can predict PET-like signals associated with tumour biology.

## Methodology
- A real MRI image was used as input
- A Region of Interest (ROI) was extracted
- A PET-like signal was simulated from MRI intensity
- A machine learning model (Random Forest) was trained to predict PET-like values from MRI

## Results
The model demonstrated a positive correlation between MRI-derived features and simulated PET signals.

![Prediction](images/prediction_plot.png)

## Clinical Relevance
This project reflects ongoing research in multimodal imaging, where MRI-based biomarkers are explored as potential alternatives to PET for assessing tumour hypoxia and biological activity.

## Future Work
- Use real PET-MRI datasets
- Apply radiomics features
- Extend to voxel-level modelling
