
## Experiment Overview
This experiment focuses on building and evaluating a classification model using **Logistic Regression**. The goal is to simulate a real-world machine learning workflow—from data preprocessing to model training, cross-validation, and performance analysis.

## Dataset
- **Name:** Breast Cancer Wisconsin Dataset
- **Source:** Built-in dataset from `scikit-learn`
- **Type:** Binary classification (Malignant vs Benign)
- **Features:** 30 numeric features related to cell nuclei measurements
- **Target:** Diagnosis label (0 = malignant, 1 = benign)

## Model and Evaluation
- **Model Used:** Logistic Regression
- **Evaluation Metrics:**
  - Accuracy
  - Precision
  - Recall
  - F1 Score
  - Confusion Matrix
  - 5-Fold Cross Validation
  - Learning Curve

## How to Run
1. Open `logistic_regression.ipynb` in **Google Colab** or **Jupyter Notebook**
2. Run all cells sequentially
3. The following files will be generated automatically:
   - `confusion_matrix.png`
   - `learning_curve.png`
   - `cross_validation.txt`
4. Review `report.docx` or `report.pdf` for interpretation and insights

## Notes
- All preprocessing steps (scaling, encoding, splitting) are included in the notebook
- The model is evaluated for consistency and generalization
- Optional comparison with other classifiers (e.g., KNN) can be added for bonus points

## Author
Keanne Rosario
Laguna State Polytechnic University  
Academic Year 2025–2026
