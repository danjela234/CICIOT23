# Attack-Disjoint Feature Attribution for Improving Transparency in ML-Based Intrusion Detection Systems

This repository contains the implementation code for my master's thesis focused on detecting previously unseen attacks in IoT network traffic using machine learning and explainable AI techniques under an attack-disjoint evaluation methodology.

## Overview
This project implements a comprehensive multi-model intrusion detection framework evaluated under attack-disjoint conditions, where models are trained on one subset of attack categories and tested on entirely different, withheld attack types. Five models are compared: Random Forest, XGBoost, Isolation Forest, One-Class SVM, and Autoencoder. Explainability is analysed using SHAP and LIME.

## Features
- Multi-model intrusion detection (Random Forest, XGBoost, Isolation Forest, One-Class SVM, Autoencoder)
- Attack-disjoint evaluation methodology
- SHAP and LIME explainability comparison
- Decision threshold tuning and cost-sensitive learning
- PCA and t-SNE embedding visualisation
- Per-attack-type analysis and difficulty ranking
- Cross-dataset evaluation on UNSW-NB15
- Ablation study and real-time feasibility analysis

## Technologies
- Python 3.12
- Scikit-learn
- XGBoost
- TensorFlow/Keras
- SHAP
- LIME
- Pandas
- Matplotlib

## Dataset
- Primary: CIC-IoT2023
- Cross-dataset: UNSW-NB15
