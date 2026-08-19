# 🩻 Chest X-Ray Multi-Condition Detection

**Team:** Asgardians
**Event:** Data ML — Technical Championship

---

## 1. Team Details

| Field | Details |
| --- | --- |
| Team Name | Asgardians |
| Team Lead | M Mukesh Reddy — mukeshmreddy@gmail.com / 8500635807 |
| Team Members (4) | 1. M Mukesh Reddy |
|  | 2. LNV Lochan CH |
|  | 3. S Tashvi |
|  | 4. K Dhanvine Reddy |
| GitHub Repository | https://github.com/Asgardians-Varchas/Asgardians-DataML |

---

## 2. Project Overview

This project is part of the Data ML Technical Championship. Our goal is to analyze chest X-ray images and predict the probability of five conditions:

- Atelectasis
- Effusion
- Infiltration
- Nodule
- Pneumothorax

Each X-ray may contain more than one condition, so our system will generate an **independent probability (0–1) for each condition**, per image.

---

## 3. Planned Approach

Our primary focus is on **feature engineering** rather than deep learning — deciding how to represent each X-ray before any modeling happens.

**Planned Pipeline**

```
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
```

### Features to Investigate
- Intensity-based features
- Texture features
- Edge and structural features
- Spatial features
- Other characteristics identified during EDA

The final feature set will be chosen based on experimentation and validation results.

### Machine Learning Models Under Consideration
- Logistic Regression
- Support Vector Machine (SVM)
- Random Forest
- Gradient Boosting

The final model will be selected based on validation performance and suitability for multi-label probability prediction.

### Evaluation Plan
Training data will be split into training and validation portions. Validation results will be used to compare feature sets and models before generating predictions on the held-out test set.

---

## 4. Repository Structure

```
├── code/           # ML code and notebooks
├── data/           # Dataset files (not committed — see Dataset Note below)
├── features/       # Feature extraction code/results
├── models/         # Trained classical ML models
├── predictions/    # Final predictions
├── results/        # Experiment results and visualizations
└── writeup/        # Final project write-up (README/PDF)
```

**Dataset Note:** The official dataset has not been released yet. Once available, dataset files will be kept out of version control (`data/` is git-ignored) unless organizers specify otherwise.

---

## 5. Results *(TBD)*

To be completed once feature engineering and modeling begin.

| Metric | Score | Notes |
| --- | --- | --- |
| — | — | — |

---

## 6. Key Insight *(TBD)*

To be completed after EDA and modeling — this will describe the most surprising or valuable finding from our analysis, for the Final Round pitch if selected.

---

## 7. Wildcard Challenges

Not yet committed — participation is optional. Currently under consideration:

| Challenge | Considering? | Notes |
| --- | --- | --- |
| Best Visualization | Maybe | — |
| Most Interpretable Model | Likely | Natural fit — our approach is built on hand-engineered, explainable features |
| Fastest Inference Time | Maybe | — |
| Best Handling of Messy/Incomplete Data | Maybe | — |

---

## 8. Declaration *(to be signed at final submission)*

We confirm that this submission will be original work completed by our team during the official event window, built solely on the officially released dataset, and will not reuse pre-existing projects or another team's code.

*Team Lead: M Mukesh Reddy — mukeshmreddy@gmail.com*

---

## 9. Current Status

📍 **Project setup / initial planning**

This repository has been created to confirm team participation and document our development process as it progresses. Feature engineering, EDA, model training, and evaluation will be added once the official dataset is released.
