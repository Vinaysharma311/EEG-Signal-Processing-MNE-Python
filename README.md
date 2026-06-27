# EEG Signal Processing and Spectral Analysis using MNE-Python

## Overview

This project demonstrates a complete EEG signal processing workflow using **MNE-Python**. It covers EEG data loading, preprocessing, visualization, spectral analysis, and spatial visualization of brain-wave activity.

The project was developed to build practical experience in biomedical signal processing and neuroimaging using Python.

---

## Objectives

* Load and inspect EEG recordings
* Visualize raw EEG signals
* Apply band-pass filtering (1–40 Hz)
* Compute Power Spectral Density (PSD)
* Analyze Delta, Theta, Alpha, and Beta frequency bands
* Generate EEG topographic maps

---

## Dataset

The analysis uses the **MNE Sample Dataset**, which contains simultaneous MEG and EEG recordings. Only the EEG channels are used in this project.

---

## Technologies Used

* Python
* MNE-Python
* NumPy
* SciPy
* Pandas
* Matplotlib

---

## Workflow

1. Load EEG data
2. Explore recording metadata
3. Visualize raw EEG signals
4. Apply band-pass filtering
5. Compute Power Spectral Density
6. Estimate EEG band power
7. Visualize scalp topographic maps

---

## Results

The analysis demonstrates:

* Successful EEG preprocessing
* Spectral analysis using PSD
* Quantitative comparison of brain-wave bands
* Spatial visualization of EEG activity using topographic maps

---

## Repository Structure

```text
EEG-Signal-Processing-MNE-Python/
│
├── figures/
├── 01_EEG_Signal_Processing_and_Spectral_Analysis.ipynb
├── requirements.txt
├── .gitignore
└── README.md
```

---

## Future Improvements

* Artifact removal using ICA
* Epoching and Event-Related Potentials (ERP)
* Functional connectivity analysis
* EEG feature extraction
* Machine learning for EEG classification

---

## Author

**Vinay Sharma**

Electronics Instrumentation and Control Engineering

Interested in Biomedical Signal Processing, Embedded Systems, FPGA Development, and AI.
