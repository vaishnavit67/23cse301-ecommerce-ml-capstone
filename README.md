# Machine Learning Capstone Project

## 23CSE301 — Machine Learning

## Team - 17

This repository contains our Machine Learning Capstone Project, covering
three problem tracks: Regression, Classification, and Clustering.

The project follows the complete machine learning workflow:

**Data Loading → Exploratory Data Analysis → Data Cleaning → Feature Engineering → Preprocessing → Model Training → Hyperparameter Tuning → Evaluation → Result Comparison**

---

## 📌 Project Overview

| Track | Status | Problem |
|---|---|---|
| Regression | To be completed | To be added |
| Classification | Part A Completed | INN Hotels Group Booking Cancellation Prediction |
| Clustering | Planned | To be added |

---

## 1. Regression Track

**To be added**

---

## 2. Classification Track

## Hotel Booking Cancellation Prediction

### Problem Statement

The objective of this classification task is to predict whether a
hotel booking will be **Cancelled** or **Not_Canceled** based on
booking-related information.

### Dataset

- **Rows:** 36,275
- **Original features:** 19
- **Target:** `booking_status`
- **Classes:**
  - `Not_Canceled`
  - `Canceled`

### Exploratory Data Analysis

The dataset was examined through:

- Dataset shape and data types
- Missing-value analysis
- Duplicate detection
- Target-class distribution
- Numerical feature distributions
- Categorical feature distributions
- Correlation heatmap
- Feature-target scatter plots
- Boxplots and outlier analysis

### Data Preprocessing

The preprocessing pipeline included:

- Missing-value checking
- Duplicate checking
- IQR-based outlier treatment
- Feature engineering
- Categorical feature encoding
- Numerical feature scaling where required
- Stratified 80:20 train-test split
- Training-only fitting of preprocessing transformations

### Engineered Features

- `total_nights`
- `total_guests`
- `total_previous_bookings`
- `is_family`
- `price_per_guest`
- `arrival_month_sin`
- `arrival_month_cos`

---

## Classification — Part A

Five classification algorithms were implemented:

1. Logistic Regression
2. K-Nearest Neighbors (KNN)
3. Gaussian Naive Bayes
4. Decision Tree Classifier
5. Support Vector Classifier (SVC)

### Results

| Model | Accuracy | Precision | Recall | Weighted F1 | ROC-AUC |
|---|---:|---:|---:|---:|---:|
| Logistic Regression | 81.28% | 75.19% | 63.99% | 80.86% | 87.16% |
| KNN | 85.20% | 79.87% | 73.29% | 85.02% | 91.00% |
| Gaussian Naive Bayes | 40.83% | 35.22% | 96.05% | 33.04% | 78.81% |
| Decision Tree | 88.04% | 82.17% | 81.07% | 88.01% | 91.54% |
| SVC | 86.38% | 81.53% | 75.56% | 86.24% | 92.43% |

> **Note:** These results represent Classification **Part A**.
> Classification Part B will be added during the next stage.

---

## 3. Clustering Track

To be completed.

---

## 4. Repository Structure

```text
Project/
│
├── README.md
├── requirements.txt
│
├── Data/
│   └── INNHotelsGroup.csv
│
├── Notebooks/
│   └── Classification.ipynb
│
└── anaconda_projects/
  └── db/
```

## 5. Technologies Used

- Python
- Jupyter Notebook
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn

---

## 6. Installation

Clone the repository and install the required dependencies:

```bash
pip install -r requirements.txt
```

## 7. Project Status

| Component | Status |
|---|---|
| Regression Track | To be completed |
| Classification Part A | Completed |
| Classification Part B | To be completed |
| Clustering Track | Planned |

## 8. Academic Integrity & AI Assistance

Generative AI tools were used as a supporting resource during the
development of this project, primarily for code scaffolding,
debugging assistance, and understanding implementation approaches.

However, the data analysis, exploratory observations, feature
engineering decisions, model evaluation, interpretation of results,
and conclusions were carried out and validated by our team.

We did not rely on AI-generated interpretations without verification.
We examined the data, evaluated the models using the required metrics,
interpreted the visualizations and results, and made the final
analytical decisions independently.

AI was therefore used as a development aid, while the analytical
reasoning, interpretation, and conclusions represent our team's work
and understanding.

## Done By
### Team Members

| S.No. | Name | Register Number |
|---|---|---|
| 1 | Himakesh Puthumbaku | CB.SC.U4CSE24741 |
| 2 | Vaishnavi Tallada | CB.SC.U4CSE24757 |
| 3 | Vuyyala Manesh | CB.SC.U4CSE24759 |

