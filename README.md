# Route Choice Analysis: Machine Learning & Deep Learning Frameworks

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Python 3.8+](https://img.shields.io/badge/python-3.8+-blue.svg)](https://www.python.org/downloads/release/python-380/)
[![Status](https://img.shields.io/badge/Status-Research%20Prototype-orange)]()

## 📌 Overview

This repository contains the implementation of **Hybrid Choice Architectures** designed to predict traveler route and mode selection behavior. It accompanies the research on bridging the gap between traditional **Econometric Theory** (Discrete Choice Models) and **Data-Driven Approaches** (Machine Learning & Deep Learning).

The framework focuses on capturing non-linear behavioral heterogeneity that traditional Logit models often miss, leveraging datasets on urban commuter behavior (specifically calibrated for Indian mixed-traffic conditions).

### Key Features
* **Comparative Analysis:** Benchmarking traditional Discrete Choice Models (MNL) against ML/DL classifiers.
* **Deep Learning Models:** Implementation of **Long Short-Term Memory (LSTM)** networks for sequential route choice data.
* **Machine Learning Models:** **Random Forest (RF)** and Gradient Boosting implementations for feature importance and non-linear pattern recognition.
* **Hybrid Frameworks:** Architectures that combine utility theory with the predictive power of neural networks.

---

## 📂 Repository Structure

```text
├── data/                  # Sample datasets (anonymized)
├── notebooks/             # Jupyter Notebooks for exploration & visualization
├── models/
│   ├── econometrics/      # Biogeme/PyLogit scripts for MNL models
│   ├── machine_learning/  # Scikit-Learn implementations (RF, SVM, GBM)
│   └── deep_learning/     # TensorFlow/Keras models (LSTM, DNN)
├── src/                   # Helper functions for data preprocessing & evaluation
├── results/               # Model performance metrics and plots
└── README.md
