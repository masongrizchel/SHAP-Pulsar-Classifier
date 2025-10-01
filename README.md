# SHAP-Pulsar-Classifier
Pulsar Star Classification with Explainable AI (SHAP)

Pulsar Star Classification with Explainable AI (SHAP) 🚀
This repository contains a Python script that trains a machine learning model to classify pulsar star candidates and uses the SHAP library to make the model's predictions interpretable.

Description
The goal of this project is to build a reliable classifier for identifying pulsars from the HTRU2 dataset. While achieving high accuracy is important, understanding why a model makes a certain prediction is crucial for scientific applications. This script demonstrates how to train a RandomForestClassifier and then apply SHAP (SHapley Additive exPlanations) to explain its internal logic, turning a "black box" model into a transparent one.

Key Features
Data Handling: Loads and prepares the HTRU2 dataset directly from the UCI repository.

Model Training: Trains a RandomForestClassifier to distinguish between pulsars and non-pulsars.

Model Interpretation: Uses the SHAP library to calculate feature contributions for the model's predictions.

Visualization: Generates several key SHAP plots to understand the model's behavior:

Beeswarm Plot: For visualizing global feature importance and impact.

Bar Plot: A simplified view of the mean absolute impact of each feature.

Waterfall Plot: To break down the prediction for a single, specific candidate.

Dataset
This project uses the HTRU2 Dataset from the UCI Machine Learning Repository. The script loads the data directly from the source.

Link: https://archive.ics.uci.edu/ml/datasets/HTRU2

Requirements
