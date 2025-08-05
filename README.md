# Power System Fault Detection and Classification

## Problem Statement

Design a machine learning model to detect and classify different types of faults in a power 
distribution system. Using electrical measurement data (e.g., voltage and current 
phasors), the model should be able to distinguish between normal operating conditions 
and various fault conditions (such as line-to-ground, line-to-line, or three-phase faults). 
The objective is to enable rapid and accurate fault identification, which is crucial for 
maintaining power grid stability and reliability.

## Dataset

The dataset contains time-series or tabular records of voltage and current phasors, labeled according to the type of fault or normal condition.
https://www.kaggle.com/datasets/ziya07/power-system-faults-dataset

Note: Dataset used in this project is either synthetic/simulated or obtained from a public source.

## Technologies Used

- Python
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn (for visualization)
- Flask or Streamlit (for deployment)
- IBM Cloud or Localhost (for hosting)

## ML Model

The model follows these steps:

1. Preprocessing – Handling missing values, normalization.
2. Feature Engineering – Extract statistical features from phasors.
3. Model Training – Using Decision Tree / Random Forest / SVM.
4. Evaluation – Accuracy, Confusion Matrix, Precision-Recall.

Achieved an accuracy of approximately X% in fault classification.


