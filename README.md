# 🚗 Automobile Price Prediction with XGBoost

This project applies machine learning techniques to predict automobile prices using a dataset sourced from [Kaggle]([https://www.kaggle.com/](https://www.kaggle.com/datasets/sumaya23abdul/automobile-database)). After thorough preprocessing and feature engineering, an XGBoost regression model was trained and achieved an **R² score of 0.94**, indicating strong predictive performance.

---

## 📂 Project Structure

├── data/                  # [Kaggle dataset](https://www.kaggle.com/datasets/sumaya23abdul/automobile-database)
├── notebooks/             # Jupyter notebooks
├── README.md              # Project overview and documentation
├── LICENSE                # MIT License for code
└── requirements.txt       # Python dependencies

---


## 📊 Dataset Overview

- **Source**: [Kaggle - Automobile Dataset](https://www.kaggle.com/datasets/sumaya23abdul/automobile-database)
- **Features**: Technical specifications, categorical attributes, and price
- **Target**: `price` (continuous variable)

> ⚠️ *Note: The dataset is not redistributed in this repository. Please download it directly from Kaggle and place it in the `data/` folder.*

---

## 🧼 Preprocessing Highlights

- Handled missing values using mean/mode imputation
- Converted object columns to appropriate numeric types
- Normalized and encoded categorical features
- Verified data types and cleaned inconsistencies

---

## 🧠 Model & Performance

- **Model Used**: XGBoost Regressor
- **Evaluation Metric**: R² Score
- **Result**: **0.94** on test set

---

## 📈 Visualization

- Scatter plots comparing actual vs. predicted values
- Feature importance chart from XGBoost
- Correlation heatmap for feature selection

---

## 🛠️ Installation

To run this project locally:

```bash
git clone https://github.com/ArianJr/Automobile-Data-Visualization-and-ML-Price-Prediction-R2-94.git
cd Automobile-Data-Visualization-and-ML-Price-Prediction-R2-94
pip install -r requirements.txt
```

---

## 👤 Author: Arian Jafar
Computer Engineering Student | Data Science and AI Enthusiast
📧 [arianjafar59@gmail.com]

---

## 📜 License
This project is licensed under the MIT License.
Please refer to the Kaggle dataset page for dataset usage terms.

---

## 🙌 Acknowledgments
- Kaggle for providing the dataset
- Scikit-learn and XGBoost for modeling tools
- Matplotlib and Seaborn for visualization

---

#### Thanks for checking out my project!
If you found it helpful or interesting, consider giving it a ⭐ on GitHub.
