# cancer-detection-ml
A machine learning project to predict cancer diagnosis using Random Forest, SVM, and XGBoost with performance evaluation and model tuning.
# Cancer Detection using Machine Learning

This project uses machine learning models to predict whether a tumor is malignant or benign based on diagnostic features from a dataset.

## 📊 Dataset
- Source: Local dataset `cancer.det.csv`
- Features: Tumor measurements
- Target: Diagnosis (Benign = 0, Malignant = 1)

## 🧠 Models Used
- Support Vector Machine (SVM)
- Random Forest Classifier
- XGBoost Classifier

## 🛠 Features
- Data preprocessing and encoding
- Feature scaling using `StandardScaler`
- Model evaluation with:
  - Accuracy Score
  - Confusion Matrix
  - Classification Report
- Hyperparameter tuning using `GridSearchCV`
- Model saving/loading using `pickle`

## 📁 Project Structure
├── cancer pred.ipynb # Main Jupyter Notebook
├── cancer.det.csv # Dataset file (not included for privacy)
├── models/
│ ├── svm_model.pkl
│ ├── rf_model.pkl
│ └── xgb_model.pkl
