# 🩺 Insurance Charges EDA & Linear Regression Analysis

This project presents an in-depth **Exploratory Data Analysis (EDA)** on an insurance dataset followed by a **Linear Regression** model to predict medical charges. It aims to identify the key drivers behind insurance costs and provide a foundation for building predictive models.

---

## 📊 Dataset Overview

The dataset includes information about insurance policyholders:
- `age` – Age of the primary beneficiary
- `sex` – Gender of the individual (female, male)
- `bmi` – Body mass index
- `children` – Number of dependents
- `smoker` – Smoking status
- `region` – Residential area in the US
- `charges` – Individual medical costs billed by health insurance

---

## 🎯 Objectives

- Perform comprehensive EDA to identify trends, patterns, and anomalies
- Understand how features like age, BMI, and smoking status affect medical charges
- Visualize key relationships and correlations
- Build a Linear Regression model to predict insurance charges

---

## 🔍 Key Insights

- **Smokers** are charged significantly more than non-smokers.
- **BMI** and **age** show strong correlation with medical costs.
- **Outliers** were found in high charges for certain BMI and smoker combinations.
- Region-wise distribution of charges is relatively uniform.

---

## 📈 Techniques & Tools

- **EDA** using `pandas`, `seaborn`, and `matplotlib`
- **Data Preprocessing** using `scikit-learn`
- **Linear Regression** modeling
- Visualizations: Box plots, pairplots, heatmaps, regression plots

---

## 🧪 Results

- Built a simple linear regression model with a good baseline performance
- Demonstrated which features have the most impact on prediction
- Discussed feature importance and possible improvements

---

## 📂 Files Included

- `insurance_eda.ipynb`: Jupyter Notebook with full EDA and modeling
- `charts/`: Contains visuals used for analysis
- `data/`: Original dataset (optional to include)
- `README.md`: Project documentation

---

## 📎 Resources

- 📌 [Colab Notebook Link]https://colab.research.google.com/drive/1nB_spYwtZD3XLroOly9LtyCumpyBv0vw?usp=sharing

---

## 📌 Author

**Your Name**  
[LinkedIn](https://linkedin.com/in/yourprofile) | [Portfolio](https://yourportfolio.com)

---

## ✅ Future Enhancements

- Try advanced regression models (Ridge, Lasso, etc.)
- Deploy the model using Flask or Streamlit
- Add interactive Power BI dashboard for business users

