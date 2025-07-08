# 🌿 Machine Learning-Based Drug Discovery using Phytochemical Data

This project proposes a machine learning-based framework to identify potential drug candidates by analyzing phytochemical data derived from medicinal plants. The focus is on predicting drug efficacy (e.g., for Alzheimer’s treatment) using models like Logistic Regression, Random Forest, and Gradient Boosting.

---

## 📌 Features

- Integrates traditional medicinal plant data with modern ML techniques
- Predicts drug efficacy based on pharmacological and biological parameters
- Enables personalized recommendations by incorporating patient-specific input
- Includes model evaluation using Accuracy, F1 Score, Precision, and Recall

---

## 🧠 Methodology

### 🔹 Data Collection
- Sources: Curated datasets on medicinal plants and phytochemicals
- Features: 
  - Plant part (e.g., root, leaf)
  - Dosage (adult/child)
  - Delivery method
  - Side effects
  - Drug efficacy (in vivo)

### 🔹 Feature Engineering
- Encoding: One-hot and label encoding
- Normalization: Min-max or Z-score
- Interaction features (e.g., dosage × delivery method)

### 🔹 Models Used
- Logistic Regression
- Random Forest
- Gradient Boosting Classifier

### 🔹 Evaluation Metrics
- Accuracy
- F1 Score
- Precision
- Recall
- k-Fold Cross Validation

---

## 🧰 Tools & Libraries

- Python 3.x
- Pandas, NumPy
- Scikit-learn
- Plotly (for visualizations)
- Graphviz / NetworkX (for flow diagrams)

---

## 📊 Results

| Model               | Accuracy | F1 Score | Precision | Recall |
|---------------------|----------|----------|-----------|--------|
| Logistic Regression | 0.78     | 0.74     | 0.76      | 0.71   |
| Random Forest       | 0.86     | 0.84     | 0.85      | 0.82   |
| Gradient Boosting   | 0.89     | 0.87     | 0.88      | 0.86   |

---

## 🧪 Visual Analytics

- Feature importance analysis
- Interactive model performance plots
- System architecture visualization

---

## 📈 System Architecture

```text
Plant Data Input
       ↓
Feature Engineering
       ↓
Model Selection (Logistic Regression / RF / GB)
       ↓
Prediction Output (Drug Efficacy / Personalized Recommendation)
