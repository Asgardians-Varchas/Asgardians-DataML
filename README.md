# Asgardians-DataML
🩻 Chest X-Ray Multi-Condition Detection

Team: Asgardians

📌 Project Overview

This project is part of the Data ML Technical Championship. Our goal is to analyze chest X-ray images and predict the probability of five conditions:

- Atelectasis
- Effusion
- Infiltration
- Nodule
- Pneumothorax

Each X-ray may contain more than one condition, so our system will generate an independent probability for each condition.

🎯 Planned Approach

Our primary focus will be on feature engineering rather than deep learning.

Planned Pipeline

X-Ray Images
↓
Image Preprocessing
↓
Handcrafted Feature Extraction
↓
Feature Selection
↓
Classical Machine Learning
↓
Five Condition Probabilities
↓
Final Predictions

🔍 Features to Investigate

We plan to investigate different hand-designed image features, including:

- Intensity-based features
- Texture features
- Edge and structural features
- Spatial features
- Other image characteristics identified during EDA

The final feature set will be selected based on experimentation and validation results.

🤖 Machine Learning

We will evaluate classical machine learning approaches such as:

- Logistic Regression
- Support Vector Machine (SVM)
- Random Forest
- Gradient Boosting

The final model will be selected based on validation performance and suitability for probability prediction.

📊 Evaluation

We will first divide the provided training data into training and validation portions. The validation results will be used to compare feature sets and classical ML models before generating predictions for the held-out test images.

📁 Planned Repository Structure

├── code/           # ML code and notebooks
├── data/           # Dataset files (not committed if restricted)
├── features/       # Feature extraction code/results
├── models/         # Trained classical ML models
├── predictions/    # Final predictions
├── results/        # Experiment results and visualizations
└── writeup/        # Final project write-up

🚧 Current Status

Project setup / initial planning

The repository has been created to document our development process. Feature engineering, exploratory data analysis, model training, and evaluation will be added as the official dataset becomes available.

👥 Team

Asgardians

1) M Mukesh Reddy
2) LNV Lochan CH
3) S Tashvi
4) K Dhanvine Reddy

---

«This project follows the competition requirement of using classical machine learning and hand-designed image representations for the chest X-ray task.»
