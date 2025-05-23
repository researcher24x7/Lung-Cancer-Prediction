# Enhanced Lung Cancer Prediction via Gradient Boosting: A Comparative Machine Learning Analysis

## 📌 Project Overview

This project aims to develop a predictive model to determine the likelihood of lung cancer in patients using machine learning techniques. It combines tabular clinical data (like age, smoking history, etc.) and can be extended to use medical images with CNNs for multimodal learning. The goal is to assist in early detection of lung cancer, improving diagnosis accuracy and healthcare outcomes.

## 🧠 Technologies Used

- Python 🐍
- Jupyter Notebook📓
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn
- XGBoost / RandomForestClassifier (baseline models)

## 🗃️ Dataset

### 1. Clinical Dataset (Tabular)
- Features: 14 clinical parameters (e.g., age, gender, smoking history, etc.)
- Target: Binary (1 = Lung cancer, 0 = No lung cancer)


## 🏗️ Project Structure

```
lung-cancer-prediction/
│
├── project(lung_cancer_disease_prediction_using_ML).ipynb  # Main notebook
├── README.md                                               # Project documentation
├── requirements.txt                                        # Dependencies
├── data/                                                   # Datasets
│   ├── tabular/                                            # Tabular data (CSV)
├── models/                                                 # Saved models                                                                  # visualizations
└── results/                                                # Metrics and plots
```

## ✅ Key Features

- 📊 **Exploratory Data Analysis (EDA)** for feature distribution and correlation.
- 🧪 **Model Building**: Trained multiple ML models (e.g., Logistic Regression, Random Forest, XGBoost).
- 📈 **Evaluation Metrics**: Accuracy, Precision, Recall, F1-score, ROC-AUC.


## 📊 Results Summary
| Model Name             | Precision | Recall | F1   | Accuracy |
| ---------------------- | --------- | ------ | ---- | -------- |
| Logistic Regression    | 0.97      | 0.97   | 0.95 | 94.3%    |
| Decision Tree          | 0.96      | 0.97   | 0.95 | 94.9%    |
| KNN                    | 0.95      | 0.95   | 0.92 | 92.7%    |
| Gaussian Naïve Bayes   | 0.95      | 0.95   | 0.92 | 92.4%    |
| MNB                    | 0.89      | 0.89   | 0.81 | 81.3%    |
| SVC                    | 0.89      | 0.89   | 0.81 | 98%      |
| RF (Random Forest)     | 0.89      | 0.89   | 0.89 | 97.9%    |
| XGB (XGBoost)          | 0.98      | 0.98   | 0.98 | 97%      |
| Multi-layer Perceptron | 0.98      | 0.98   | 0.98 | 97.8%    |
| Gradient Boosting      | 0.98      | 0.98   | 0.98 | 98.2%    |
| ---------------------- | --------- | ------ | ---- | -------- |


## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/lung-cancer-prediction.git
   cd lung-cancer-prediction
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Launch Jupyter Notebook:
   ```bash
   jupyter notebook
   ```

4. Open the notebook `project(lung_cancer_disease_prediction_using_ML).ipynb`.

## 📄 Requirements

Create a `requirements.txt` with:

```txt
pandas
numpy
scikit-learn
matplotlib
seaborn
xgboost
```

## 📚 References

- Schiller et al. (2019) – Lung cell reference map  
- Duma et al. (2019) – NSCLC review  
- Qureshi et al. (2020) – Multimodal ML-based prediction  
- Hussein et al. (2019) – 3D CNN for lung nodule classification  
- Rajpurkar et al. – CheXNeXt for chest radiographs  
*(Full citation list included in the research paper)*

## 🧾 License

This project is licensed under the MIT License.

## 🙌 Acknowledgments

Thanks to the open-source medical datasets (LIDC-IDRI, LC25000), and the authors of SHAP, LIME, and scikit-learn for providing amazing tools.
