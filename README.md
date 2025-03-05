## Classification & Clustering

## Overview
This project focuses on **Classification & Clustering** tasks using machine learning techniques. The project is divided into two parts:
1. **Classification (Tasks 1–13):** Predicting diabetes risk using patient data.
2. **Clustering (Tasks 14–18):** Analyzing geographic distribution of weather monitoring stations.

---

## Dataset Information
- **Classification:** `diabetes.csv` (Patient data for diabetes prediction)
- **Clustering:** `pm25_2016_2020_v3.csv` (Weather monitoring station data)

---

## Task Breakdown

### **Classification Tasks (Tasks 1–13)**

1. **Load the Dataset:** Import `diabetes.csv` into a Pandas DataFrame and display its structure.
2. **Compute Median Blood Pressure:** Calculate the median blood pressure of diabetes-diagnosed individuals.
3. **Check Dataset Balance:** Identify the target variable and check if the dataset is balanced.
4. **Prepare Data for Modeling:** Split features (`X`) and target variable (`Y`).
5. **Understand Train-Test Split:** Explain how `stratify=y` affects data splitting.
6. **Modify Train-Test Split:** Adjust to a 3:1 split.
7. **Train a Decision Tree Classifier:** Fit the model and evaluate accuracy.
8. **Detect Overfitting:** Analyze potential overfitting in the model.
9. **Interpret Precision & Recall:** Explain the classification report’s precision and recall values.
10. **Confusion Matrix Analysis:** Compute and interpret false positives & sensitivity.
11. **Visualize Decision Tree:** Generate a plot of the trained Decision Tree.
12. **Identify Important Features:** Rank features based on their influence in the decision tree.
13. **Compare Models:** Train a K-Nearest Neighbors (KNN) model and compare its performance with the Decision Tree.

---

### **Clustering Tasks (Tasks 14–18)**

14. **Load Weather Data:** Import `pm25_2016_2020_v3.csv` into a Pandas DataFrame.
15. **Extract Geographic Features:** Create a new DataFrame (`X`) containing `latitude_x` and `longitude_x`.
16. **Apply K-Means Clustering:** Cluster data into 3 groups and understand the range of cluster values (`0, 1, 2`).
17. **Modify Clustering for 5 Groups:** Adjust the model to `n_clusters=5` and analyze cluster distribution.
18. **Visualize Clusters:** Generate a scatter plot with color-coded clusters to analyze geographic distribution.

---

## Dependencies
Ensure you have the following Python libraries installed:
```bash
pip install pandas numpy scikit-learn seaborn matplotlib
```

## Running the Code
1. Load the dataset in a Jupyter Notebook or Google Colab.
2. Execute the tasks step by step, following the provided instructions.
3. Compare classification models and analyze clustering results visually.

---

## Expected Outcomes
- A trained **Decision Tree model** to predict diabetes risk.
- A **K-Means clustering model** identifying geographical station groupings.
- Visualization of results using confusion matrices, decision trees, and cluster scatter plots.

---
