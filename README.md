# Imbalanced Text Classification - Disaster Tweets

## Overview 

This project implements and compares multiple machine learning models for binary text classification on an imbalanced dataset (Disaster Tweets). It also evaluates the impact of imbalance handling techniques such as SMOTE and class weighting.

---

##  Structure

```
AI PROJECT/
│
├── project.ipynb
├── dataset/
│     └── tweets.csv
├── requirements.txt
├── README.md
└── venv/ (optional, not submitted)
```

---

## Setup Instructions 

### 1. Clone or Download Project

Download the project files and place them in a folder.

---

### 2. Create Virtual Environment (Recommended)

```bash
python -m venv venv
```

Activate it:

**Windows:**

```bash
venv\Scripts\activate
```

---

### 3. Install Dependencies

```bash
pip install -r requirements.txt
```

---

### 4. Run Jupyter Notebook

```bash
jupyter notebook
```

Open:

```
project.ipynb
```

---

## Execution Steps

Run the notebook cells **in order from top to bottom**:

1. Import libraries
2. Load dataset
3. Data preprocessing
4. TF-IDF vectorization
5. Train-test split
6. Train models (Part A)
7. Apply SMOTE and class weights (Part B)
8. Evaluate results

---

## Models Used

* Logistic Regression
* Random Forest
* Neural Network (Fixed Architecture)

---

## Imbalance Handling 

* SMOTE
* Class Weighting

---

## Evaluation Metrics

* Accuracy
* Precision
* Recall
* F1-score
* Confusion Matrix
* ROC-AUC
* Precision-Recall Curve

---

##  Notes

* Ensure dataset file is correctly placed in the folder 
* Run all cells sequentially after restarting kernel
* GPU is not required; CPU execution is sufficient

