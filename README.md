# Olympics Data Analysis

Welcome to the **Olympics Data Analysis** project! This project leverages **Streamlit** to explore, analyze, and visualize Olympics data interactively, using powerful Python libraries and Machine Learning techniques to extract meaningful insights.

---

## 🏆 Project Overview

This project aims to analyze Olympics data and uncover trends, patterns, and key insights using advanced visualization and predictive modeling. The interactive **Streamlit dashboard** provides tools for users to explore:

- **Trends in Olympic Data**: Historical medal counts, country performance, and more.
- **Athlete Insights**: Analysis of athlete demographics, age distribution, and performance.
- **Medal Prediction**: Machine Learning models to predict medal outcomes based on past data.

---

## 🚀 Features

- **Streamlit Dashboard**: A clean and intuitive interface for exploring data and predictions.
- **Dynamic Filters**: Interactive filtering by country, year, sport, and athlete.
- **Advanced Visualizations**: Charts and graphs powered by Matplotlib, Seaborn, and Plotly.
- **Predictive Modeling**: Machine Learning algorithms to analyze and predict outcomes.

---

## 🛠️ Key Python Libraries Used

- **Data Manipulation and Analysis**: `pandas`, `numpy`
- **Data Visualization**: `matplotlib`, `seaborn`, `plotly`, `streamlit`
- **Machine Learning**: `scikit-learn`, `xgboost`
- **Statistical Analysis**: `scipy`, `statsmodels`

---

## 🤖 Machine Learning Algorithms Implemented

- **Linear Regression**: For trend analysis and medal prediction.
- **Random Forest**: For classification and feature importance.
- **K-Means Clustering**: To group countries or athletes by similar characteristics.
- **XGBoost**: To improve predictive accuracy in medal predictions.
- **Decision Trees**: For simple and interpretable classification tasks.

---

## 📥 Installation

To run the project locally, follow these steps:

```bash
git clone https://github.com/pchhonkar/Olympics-Data-Analysis.git
cd Olympics-Data-Analysis
python3 -m venv myenv
source myenv/bin/activate
pip install -r requirements.txt
streamlit run app.py
