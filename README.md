# 🏡 Airbnb Listings Analysis with Logistic Regression

## 📌 Project Overview
This project analyzes Airbnb listings data to build logistic regression models that predict listing performance. It demonstrates data preprocessing, feature engineering, and model evaluation.

## 🎯 Objectives and Goals
- Explore and preprocess Airbnb listings dataset.
- Build and optimize logistic regression models.
- Evaluate performance with metrics including accuracy, precision, recall, and ROC-AUC.

## ⚙️ Methodology
- Preprocessing: handled missing values, feature scaling, and one-hot encoding.
- Modeling: implemented logistic regression with hyperparameter tuning.
- Evaluation: compared multiple models using cross-validation and ROC analysis.

## 📊 Results and Key Findings
- Identified significant features impacting listing performance.
- ROC-AUC values confirmed reliable model performance.
- Model interpretability offered insights for host decision-making.

## 📈 Visualizations
Visual results can be found in the `results/` directory.

## 🔜 Next Steps
- Test advanced models (Random Forest, Gradient Boosting).
- Deploy model as a dashboard for host recommendations.

## 📂 Dataset
- Airbnb Listings dataset: `data/airbnbListingsData.csv`

## 💻 Notebooks
- [`notebooks/ModelSelectionForLogisticRegression.ipynb`](notebooks/ModelSelectionForLogisticRegression.ipynb)

## 🛠️ Installation
```bash
git clone https://github.com/syderni/btt-airbnb-ML-project.git
cd airbnb-logistic-regression
pip install -r requirements.txt
```

Run Jupyter Notebook:
```bash
jupyter notebook notebooks/ModelSelectionForLogisticRegression.ipynb
```

## 📘 Documentation
Full methodology and evaluation details are available in the `docs/` folder.
