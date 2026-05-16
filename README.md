# Leukemia Detection Using GraphML

## Overview
This repository provides an implementation of Leukemia detection using Graph Machine Learning (GraphML) techniques. The project utilizes Graph Neural Networks (GNNs), specifically **GraphSAGE**, to classify biomedical data and predict the presence of Leukemia.

## Features
- **Graph Neural Networks:** Implements GraphSAGE with global mean/max pooling for graph classification.
- **Data Preprocessing:** Uses SimpleImputer and StandardScaler for robust data preparation.
- **Evaluation:** Comprehensive evaluation metrics including confusion matrices, accuracy scores, and classification reports.
- **Integration:** Includes Google Colab drive integration for easy cloud execution and dataset loading.

## Technologies Used
- PyTorch & PyTorch Geometric (Graph Neural Networks)
- Scikit-Learn (Metrics & Imputation)
- TQDM (Progress Tracking)

## How to Use
1. Clone the repository.
2. Install the required dependencies: `pip install torch torchvision torch-geometric scikit-learn tqdm`.
3. Run the notebook `Lukemia_Detection_Using_GraphML.ipynb`.
