# 🧬 Cancer Prediction with XGBoost

This project demonstrates how **machine learning** can assist in early cancer detection by predicting whether tumors are **benign** or **malignant**. Using the **XGBoost algorithm**, we build a high-performance classification model that leverages tumor feature data to support clinical decision-making.

## 📊 Dataset

The dataset contains tumor characteristics such as radius, texture, smoothness, compactness, and other cell features. Each entry is labeled as:

* **0 = Benign**
* **1 = Malignant**

> Commonly sourced from the [Cancer Dataset](https://github.com/YBIFoundation/Dataset/raw/main/Cancer.csv).

## 🚀 Workflow

1. **Data Preprocessing** – Handling missing values, encoding, and scaling.
2. **Exploratory Data Analysis (EDA)** – Visualizing distributions, correlations, and class balance.
3. **Model Training** – Implementing XGBoost with tuned hyperparameters.
4. **Evaluation** – Metrics include accuracy, precision, recall, F1-score, and ROC-AUC.
5. **Feature Importance** – Identifying the most predictive tumor features.

## ✅ Results

* **Accuracy:** ~96%
* XGBoost outperforms baseline models like logistic regression and decision trees.

## 🛠️ Installation

Clone the repo and install dependencies:

```bash
git clone https://github.com/yourusername/xgboost-cancer-prediction.git
cd xgboost-cancer-prediction
pip install -r requirements.txt
```

## 📌 Usage

Run the notebook for training and evaluation:

```bash
jupyter notebook XGBoost.ipynb
```

## 🔮 Future Improvements

* Hyperparameter optimization with Optuna/Random Search
* Deployment with Flask/Streamlit for interactive predictions
* Testing on larger, real-world medical datasets

## 🤝 Contributing

Contributions are welcome! Feel free to fork, submit pull requests, or open issues.

## 📜 License

This project is licensed under the MIT License.
