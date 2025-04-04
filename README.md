
# Freelance Team Churn Prediction Project

This project uses **synthetic data** to simulate and predict **churn in freelance teams** based on factors such as team size, client ratings, average project value, communication score, and more.

## 📁 Files Included

- `freelance_churn_data.csv` – Synthetic dataset of 1000 freelance teams
- `Freelance_Team_Churn_Prediction_Notebook.ipynb` – Jupyter notebook with model training and evaluation
- `xgboost_feature_importance.png` – Feature importance visualization (optional)
- `streamlit_freelance_churn_app.py` – Interactive Streamlit web app for live churn prediction

## 📊 Features in Dataset

- `team_size`
- `avg_monthly_projects`
- `avg_project_value`
- `client_rating`
- `deadline_meeting_rate`
- `communication_score`
- `dispute_count`
- `contract_extension_rate`
- `is_churned` (Target variable: 0 = Retained, 1 = Churned)

## 📦 Requirements

```bash
pip install pandas numpy scikit-learn xgboost matplotlib seaborn streamlit
```

## 🧪 To Run the Jupyter Notebook

```bash
jupyter notebook Freelance_Team_Churn_Prediction_Notebook.ipynb
```

## 🖥️ To Run the Streamlit App

```bash
streamlit run streamlit_freelance_churn_app.py
```

---

Created by **Agbozu Ebingiye Nelvin**
