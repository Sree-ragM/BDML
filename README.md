# Predicting Drug Prescriptions Based on Patient’s Health Metrics: A Machine Learning Approach

## 📌 Aim

The objective of this project is to develop and evaluate machine learning models that can accurately classify which type of drug should be prescribed to a patient based on their medical attributes.

## 📊 Dataset

We used the **drug200.csv** dataset, containing 200 patient records. This dataset is publicly available on [Kaggle](https://www.kaggle.com/datasets/prathamtripathi/drug-classification/data). The dataset features include:

* **Age**
* **Sex**
* **Blood Pressure (BP)**
* **Cholesterol**
* **Na\_to\_K (Sodium to Potassium ratio)**
* **Drug** (Target variable)

## 🛠️ Technologies Used

* **Python**
* **Pandas**: For data preprocessing and manipulation
* **Scikit-learn (sklearn)**: For implementing machine learning models and performance evaluation
* **Matplotlib / Seaborn** *(optional)*: For visualizations

## 🤖 Machine Learning Models Implemented

* Decision Tree
* K-Nearest Neighbors (KNN)
* Random Forest
* Support Vector Machine (SVM)

### 📈 Evaluation Metrics

* Accuracy
* Precision (Weighted & Macro)
* Recall (Weighted & Macro)
* F1 Score (Weighted & Macro)

## 🧠 Summary of Results

* **Decision Tree** and **Random Forest** models achieved perfect classification.
* **KNN** and **SVM** showed good performance, with slightly lower accuracy than tree-based models.

## 🚀 How to Run

1. Clone the repository:

   ```bash
   git clone https://github.com/Sree-ragM/BDML.git
   ```
2. Install required libraries:

   ```bash
   pip install -r requirements.txt
   ```
3. Open the `ML.ipynb` Jupyter notebook and run all cells sequentially.

## 📁 Project Files

* `drug200.csv`: Dataset
* `ML.ipynb`: Main notebook for preprocessing, training, and evaluation
* `README.md`: Project documentation

## 🔗 Dataset Source

[Drug Classification Dataset on Kaggle](https://www.kaggle.com/datasets/prathamtripathi/drug-classification/data)

## 📌 License

This project is for **educational and research** purposes only.

---

## 👥 Contributors

* [Sreerag M](https://github.com/Sree-ragM)
* [Neeraj Krishna](https://github.com/theneerajkrishna)

---

