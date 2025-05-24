# Predicting Drug Prescriptions Based on Patient’s Health Metrics: A Machine Learning Approach

## 📌 Aim

The objective of this project is to develop and evaluate machine learning models that can accurately classify which type of drug should be prescribed to a patient based on their medical attributes.

## 📊 Dataset

We used the **drug200.csv** dataset, which contains 200 records. This dataset is publicly available on [Kaggle](https://www.kaggle.com/datasets/prathamtripathi/drug-classification/data) and includes the following patient features:

* **Age**
* **Sex**
* **Blood Pressure (BP)**
* **Cholesterol**
* **Na\_to\_K (Sodium to Potassium ratio)**
* **Drug (Target variable)**

## 🛠️ Technologies Used

* **Python**
* **Pandas**: For data preprocessing and manipulation.
* **Scikit-learn (sklearn)**: For implementing machine learning models and performance evaluation.
* **Matplotlib / Seaborn** *(optional)*: For visualizations.

## 🤖 Machine Learning Models Implemented

* **Decision Tree**
* **K-Nearest Neighbors (KNN)**
* **Random Forest**
* **Support Vector Machine (SVM)**

Each model was evaluated based on:

* Accuracy
* Precision (Weighted & Macro)
* Recall (Weighted & Macro)
* F1 Score (Weighted & Macro)

## 🧠 Summary of Results

Decision Tree and Random Forest achieved perfect classification on this dataset, while KNN and SVM showed good performance but were slightly less accurate.

## 📌 How to Run

1. Clone the repository.
2. Install the required libraries:

   ```bash
   pip install -r requirements.txt
   ```
3. Open the `.ipynb` file and run all cells sequentially.

## 📁 Files

* `drug200.csv`: The dataset.
* `ML.ipynb`: The notebook containing preprocessing, model training, and evaluation code.
* `README.md`: Project documentation.

## 🔗 Dataset Source

[Drug Classification Dataset on Kaggle](https://www.kaggle.com/datasets/prathamtripathi/drug-classification/data)

## 📌 License

This project is for educational and research purposes only.
