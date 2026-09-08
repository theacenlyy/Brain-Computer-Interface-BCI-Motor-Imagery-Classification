# Brain-Computer-Interface-BCI-Motor-Imagery-Classification                                                                                                             # Brain-Computer Interface (BCI): Motor Imagery EEG Data Processing & Feature Extraction Pipeline

An end-to-end Machine Learning and Signal Processing pipeline designed to process electroencephalography (EEG) data for Motor Imagery classification in Brain-Computer Interface (BCI) applications.

## 📌 Project Overview
This repository contains a structured data processing pipeline that takes raw EEG signal data, applies spatial and temporal filtering, extracts key time-frequency features, and formats the data for downstream Machine Learning classifiers.

## 🛠️ Features & Methodology
- **Signal Preprocessing:** Bandpass filtering, artifact reduction, and signal normalization for EEG channels.
- **Feature Extraction:** Extraction of power spectral density (PSD), band-power features (Mu & Beta rhythms), and spatial filtering.
- **Dataset Management:** Large EEG feature matrix tracking and storage via Git LFS.
- **Pipeline Architecture:** Modular Python and Jupyter Notebook scripts designed for reproducibility and easy model integration.

## 📁 Repository Structure
```text
.
├── dataset.csv                  # Extracted EEG feature matrix (Managed via Git LFS)
├── last_taskG.ipynb             # EEG processing & analysis notebook
├── .gitattributes              # Git LFS tracking configurations
└── README.md                    # Project documentation
