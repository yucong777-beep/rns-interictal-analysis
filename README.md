# RNS Interictal Epilepsy Analysis

This repository contains the planned analysis pipeline for investigating interictal-period brain activity as an intrinsic signature of epilepsy, using RNS intracranial EEG datasets.

## Hypothesis
The interictal period carries intrinsic neural signatures that reflect epilepsy state and seizure vulnerability. This project aims to characterize interictal epileptic patterns and their relationship with seizure occurrence.

## Data Access
This study requests access to de-identified RNS iEEG data from:
- Baud et al., 2018 cohort
- Proix et al., 2021 multi-center cohort
- Zarei & Parvin, *Cycles in Epilepsy* dataset (`All_counts.mat`)

We will apply the same interictal analysis pipeline across these datasets to replicate and validate our hypothesis. Only secondary analysis of de-identified data will be performed.

## Planned Analysis
1. Preprocess long-term RNS iEEG recordings
2. Quantify interictal epileptiform activity and brain rhythms
3. Relate interictal features to seizure timestamps
4. Test statistical associations between interictal biomarkers and seizure occurrence

## Environment
- Python >= 3.9
- NumPy, SciPy
- Pandas
- MNE-Python
- scikit-learn
- Matplotlib

## Outputs
- Open-source Python analysis pipeline
- Reproducible statistical analysis scripts
- Academic manuscript

## Data Use Commitments
- No redistribution of raw data
- No re-identification of participants
- Compliance with all data-use requirements and DUA
- All analysis will be conducted exclusively for this academic project. No commercial use.
