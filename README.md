# SHAP-Pulsar-Classifier: Pulsar Star Classification with Explainable AI (SHAP)

This repository contains a Python script that trains a machine learning model to classify pulsar star candidates and uses the SHAP library to make the model's predictions interpretable.

### Description
The goal of this project is to build a reliable classifier for identifying pulsars from the HTRU2 dataset. While achieving high accuracy is important, understanding why a model makes a certain prediction is crucial for scientific applications. This script demonstrates how to train a RandomForestClassifier and then apply SHAP (SHapley Additive exPlanations) to explain its internal logic, turning a "black box" model into a transparent one.

### Key Features
1. Data Handling: Loads and prepares the HTRU2 dataset directly from the UCI repository.
2. Model Training: Trains a RandomForestClassifier to distinguish between pulsars and non-pulsars.
3. Model Interpretation: Uses the SHAP library to calculate feature contributions for the model's predictions.
4. Visualization: Generates several key SHAP plots to understand the model's behavior:
5. Beeswarm Plot: For visualizing global feature importance and impact.
6. Bar Plot: A simplified view of the mean absolute impact of each feature.
7. Waterfall Plot: To break down the prediction for a single, specific candidate.

### Dataset
This project uses the HTRU2 Dataset from the UCI Machine Learning Repository. The script loads the data directly from the source.

Link: https://archive.ics.uci.edu/ml/datasets/HTRU2

### Usage
Run the Jupyter Notebook (.ipynb) or the Python script (.py) in your environment. The script will automatically download the data, train the model, and generate the SHAP visualizations.
