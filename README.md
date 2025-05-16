# PUBG Placement Prediction

> A complete machine learning pipeline project for predicting player placement in PUBG matches using real-world game data and statistical modeling techniques.

## 🎯 Goal

To apply end-to-end data science processes — including data preprocessing, feature engineering, model training, and evaluation — to predict final player rankings in PUBG games based on match performance metrics.

---

## 🔍 Overview

This project explores the [PUBG Finish Placement Prediction](https://www.kaggle.com/competitions/pubg-finish-placement-prediction) Kaggle dataset to build a regression model capable of predicting a player's final rank percentage.

It demonstrates practical knowledge in:

* Exploratory data analysis (EDA)
* Feature selection & engineering
* Outlier handling
* Model evaluation and tuning

---

## 🚀 Features

* 📊 Exploratory Data Analysis with visualizations
* 🔧 Feature Engineering for improved model learning
* 🧹 Data Cleaning & Preprocessing pipelines
* 📈 Model training using Linear Regression, XGBoost, Random Forest
* 📉 Evaluation using metrics like RMSE and R² Score
* 🧪 Cross-validation and Hyperparameter tuning
* 📂 Modular and clean code structure

---

## 👷 Tech Stack

| Category         | Technology            |
| ---------------- | --------------------- |
| Language         | Python                |
| Data Analysis    | Pandas, NumPy         |
| Visualization    | Matplotlib, Seaborn   |
| Modeling         | Scikit-learn, XGBoost |
| Notebook Runtime | Jupyter Notebooks     |
| Version Control  | Git + GitHub          |

---

## 📁 Project Structure

```text
PubG_Placement_Prediction/
├── data/                # Raw and processed data files
├── notebooks/           # EDA and modeling notebooks
├── models/              # Saved models (optional)
├── pubg_predict.py      # Main Python script for training/predicting
├── utils.py             # Helper functions
├── requirements.txt     # Environment dependencies
└── README.md            # Project documentation
```

---

## 🧭 Process Overview

1. Loaded and inspected the Kaggle dataset
2. Performed univariate and multivariate EDA
3. Engineered relevant features from raw gameplay stats
4. Handled missing values and outliers
5. Trained multiple regression models
6. Evaluated and compared model performance
7. Finalized best-performing model for predictions

---

## 🔭 Future Enhancements

* Integrate Flask/Streamlit for model deployment as a web app
* Create interactive dashboards using Plotly or Dash
* Use more advanced algorithms like LightGBM or ensemble stacking
* Optimize preprocessing using pipelines and `sklearn.compose`
* Perform feature importance analysis for model explainability

---

## 🧑‍💼 Author

**Shashwat Patel**
Data Analyst | Aspiring ML Engineer | Tech Enthusiast
📍 Chicago, IL
🌐 [LinkedIn](https://www.linkedin.com/in/shashwatpatel107/)
💼 [Portfolio](https://shashwatpatel.netlify.app)

---

## 📜 License

This project is licensed under the [MIT License](LICENSE). You are free to use, modify, and distribute this project with attribution.

---

## 🤝 Contributions

Contributions, issues, and feature requests are welcome. Feel free to fork the repo and submit a pull request.

---

## 🔗 Resources

* [Kaggle Dataset - PUBG Finish Placement](https://www.kaggle.com/competitions/pubg-finish-placement-prediction)
* [Scikit-learn Documentation](https://scikit-learn.org/stable/)
* [XGBoost Documentation](https://xgboost.readthedocs.io/)

---

## ✅ Conclusion

This project combines core data science techniques with practical implementation to deliver accurate predictive insights using game telemetry.

> Built with curiosity, data, and caffeine ☕
> — *Shashwat Patel*
