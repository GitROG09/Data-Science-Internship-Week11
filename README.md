# Customer Segmentation & Prediction Using Machine Learning

## Project Overview
This project applies advanced machine learning techniques to segment customers and build predictive models for each segment. The goal is to generate actionable business insights that improve customer retention and revenue.

---

## Objectives
- Segment customers using clustering algorithms
- Build separate prediction models for each segment
- Apply hyperparameter tuning
- Evaluate models using multiple performance metrics
- Translate technical findings into business strategies

---

## Technologies Used
- Python
- Scikit-learn
- Pandas, NumPy
- Matplotlib, Seaborn
- Google Colab

---

## Dataset
**customer_churn.csv**
- Rows: 500
- Target Variable: Churn
- Contains customer behavioral data

---

## Methodology

### 1. Data Preprocessing
- Missing value handling
- Encoding categorical variables
- Feature scaling using StandardScaler

### 2. Customer Segmentation
- K-Means Clustering (Elbow Method)
- Hierarchical Clustering
- DBSCAN (noise detection)

### 3. Segment Analysis
- Cluster profiling
- Customer behavior interpretation
- Segment naming

### 4. Prediction Models
- Random Forest Classifier per segment
- Separate train-test splits
- Feature importance analysis

### 5. Model Evaluation
Metrics used:
- Accuracy
- Precision
- Recall
- F1-score
- ROC-AUC

### 6. Hyperparameter Tuning
- GridSearchCV for Random Forest optimization

---

## Project Structure
