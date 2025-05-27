# Online-shoppers-intention-prediction
A machine learning project to analyze and predict e-commerce user purchasing behavior using classification models and KMeans clustering on the UCI Online Shoppers dataset.

## 📂 Project Structure

online-shoppers-intention/
├── data/ # Raw and cleaned data files
├── notebooks/ # Jupyter notebooks with EDA, modeling, and results
├── results/ # Graphs, charts, reports, accuracy results
├── requirements.txt # Project dependencies
├── README.md # Project description and usage
└── .gitignore



---

## 📊 Dataset

- **Source**: [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Online+Shoppers+Purchasing+Intention+Dataset)
- **Target**: `Revenue` — indicates whether a purchase was made or not.

---

## ✅ Objectives

- Perform **EDA** (Exploratory Data Analysis)
- Apply and evaluate **classification models**:
  - Logistic Regression
  - K-Nearest Neighbors
  - Decision Tree
  - Random Forest
  - Gradient Boosting
  - LightGBM
- Perform **K-Means Clustering**
- Visualize results and save performance metrics

---

## 🧠 Models and Accuracy

| Model                | Accuracy Score |
|----------------------|----------------|
| Random Forest        | 0.9081         |
| LightGBM             | 0.9067         |
| GRadient Boosting    | 0.9035         |
| Logistic Regression  | 0.8924         |
| K-Nearest Neighbors  | 0.8872         |
| Decision Tree        | 0.8559         |
| KMeans Clustering    | 0.7300         |

---

## 📈 Evaluation Metrics

- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix
- Accuracy Score (for clustering)

---
## Install dependencies
pip install -r requirements.txt

---
## Open and run notebook
jupyter notebook notebooks/analysis.ipynb

## 📤 Outputs
Accuracy scores and evaluation results saved in results/



Visualizations and charts generated using matplotlib and seaborn

---
## 📚 References
UCI Machine Learning Repository

scikit-learn, LightGBM, matplotlib, pandas
