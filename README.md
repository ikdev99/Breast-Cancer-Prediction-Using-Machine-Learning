# 🩺 Breast Cancer Prediction Using Machine Learning

## 📌 Project Overview

Breast cancer is one of the most common cancers worldwide. Early diagnosis can significantly improve treatment outcomes and survival rates.

This project develops and compares multiple Machine Learning models to predict whether a breast tumor is **Benign** or **Malignant** using the **Wisconsin Breast Cancer Diagnostic Dataset**. The project includes data preprocessing, model training, evaluation, and performance comparison using various metrics.

---

## 🎯 Objectives

* Predict breast cancer diagnosis using Machine Learning techniques.
* Compare the performance of multiple classification algorithms.
* Evaluate models using Accuracy, F1-Score, ROC-AUC, and Confusion Matrix.
* Identify the best-performing model for breast cancer prediction.

---

## 📂 Project Structure

```text
Breast-Cancer-Prediction-Using-Machine-Learning/
│
├── dataset/
│   └── data.csv
│
├── notebooks/
│   └── ML_1.ipynb
│
├── images/
│   ├── model_comparison.png
│   ├── confusion_matrix_lr.png
│   ├── confusion_matrix_rf.png
│   ├── confusion_matrix_svm.png
│   ├── confusion_matrix_xgb.png
│   └── confusion_matrix_mlp.png
│
├── results/
│   └── model_results.txt
│
├── requirements.txt
├── README.md
└── LICENSE
```

---

## 📊 Dataset Information

**Dataset:** Wisconsin Breast Cancer Diagnostic Dataset

### Features

The dataset contains diagnostic measurements computed from digitized images of breast mass cell nuclei.

Examples of features include:

* Radius
* Texture
* Perimeter
* Area
* Smoothness
* Compactness
* Concavity
* Symmetry
* Fractal Dimension

### Target Classes

| Label | Description |
| ----- | ----------- |
| M     | Malignant   |
| B     | Benign      |

---

## 🛠️ Technologies Used

* Python
* NumPy
* Pandas
* Matplotlib
* Seaborn
* Scikit-Learn
* XGBoost
* Jupyter Notebook

---

## 🤖 Machine Learning Models

The following classification algorithms were implemented and compared:

1. Logistic Regression
2. Random Forest
3. Support Vector Machine (SVM)
4. XGBoost
5. Multi-Layer Perceptron (MLP)

---

## ⚙️ Methodology

### 1. Data Preprocessing

* Removed unnecessary columns
* Encoded target labels
* Checked for missing values
* Feature scaling using StandardScaler

### 2. Train-Test Split

* Training Set: 70%
* Validation Set: 15%
* Test Set: 15%

### 3. Model Training

Each model was trained on the processed dataset and evaluated using the test set.

### 4. Performance Evaluation

Metrics used:

* Accuracy
* F1 Score
* ROC-AUC Score
* Confusion Matrix

---

## 📈 Model Performance

| Model               | Accuracy   | F1 Score   | ROC-AUC    |
| ------------------- | ---------- | ---------- | ---------- |
| Logistic Regression | 97.67%     | 96.88%     | 99.83%     |
| Random Forest       | 96.51%     | 95.24%     | 99.54%     |
| SVM                 | 97.67%     | 96.77%     | 99.94%     |
| XGBoost             | 97.67%     | 96.88%     | 99.71%     |
| MLP                 | **98.84%** | **98.41%** | **99.94%** |

---

## 🏆 Best Model

### Multi-Layer Perceptron (MLP)

Performance:

* Accuracy: 98.84%
* F1 Score: 98.41%
* ROC-AUC: 99.94%

The MLP model achieved the highest overall performance and demonstrated excellent classification capability for breast cancer diagnosis.

---

## 📷 Visualizations

### Model Performance Comparison

The project includes a graphical comparison of:

* Accuracy
* F1 Score
* ROC-AUC

across all machine learning models.

### Confusion Matrices

Confusion matrices are provided for:

* Logistic Regression
* Random Forest
* SVM
* XGBoost
* MLP

These visualizations help evaluate model prediction performance and classification errors.

---

## 🚀 How to Run the Project

### Clone Repository

```bash
git clone https://github.com/ikdev99/Breast-Cancer-Prediction-Using-Machine-Learning.git
```

### Navigate to Project

```bash
cd Breast-Cancer-Prediction-Using-Machine-Learning
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

### Run Jupyter Notebook

```bash
jupyter notebook
```

Open:

```text
notebooks/ML_1.ipynb
```

and execute all cells.

---

## 📌 Future Improvements

* Hyperparameter Optimization
* Deep Learning-Based Classification
* Explainable AI (XAI)
* Web-Based Prediction Interface
* Real-Time Clinical Decision Support System

---

## 👨‍💻 Author

**Md. Ibrahim Khalil**

* B.Sc. in Computer Science & Engineering
* American International University-Bangladesh (AIUB)
* GitHub: https://github.com/ikdev99

---

## ⭐ If you found this project useful, please consider giving it a star on GitHub.

