## Project Overview
This project focuses on predicting outcomes for children undergoing Bone Marrow Transplantation (BMT) using machine learning techniques. The primary goal is to enhance treatment strategies by developing predictive models that assess patient survival and relapse risks based on clinical attributes. The project involves two key approaches:

**- Comprehensive Process Analysis:**  Utilizes both pre- and post-transplant features for a holistic evaluation of the BMT process.

**- Predictive Modeling:** Focuses solely on pre-transplant features to predict survival, providing a tool for early decision-making.

The project demonstrates the potential of machine learning in predicting BMT outcomes, with Random Forests identified as the most effective model for comprehensive analysis. The pre-transplant model, while less accurate, is valuable for early interventions.

## Dataset
The dataset used in this project is sourced from the UCI Machine Learning Repository and contains 187 entries with 37 clinical attributes. These include demographic information, genetic markers, treatment specifics, recovery metrics, and outcomes. The target variable is the patient's survival status.

## Machine Learning Models
The project implements several machine learning algorithms, including:

- Decision Trees
- Random Forests
- K-Nearest Neighbors (KNN)
- Naive Bayes
- Support Vector Machines (SVM)
- Artificial Neural Networks (ANN)
  
Hyperparameter tuning was conducted using methods like Randomized Search CV and Grid Search to enhance model performance.

# How to Run the Code
## 1. Setup Environment:
Ensure Python and necessary libraries (e.g., pandas, scikit-learn) are installed.
## 2. Run the Notebook:
Open the provided Jupyter notebook (BONE_MARROW.ipynb).
Execute the cells in sequence to preprocess the data, train models, and evaluate results.
## 3. Evaluate Results:
Review model performance metrics and learning curves to assess the effectiveness of each approach.
