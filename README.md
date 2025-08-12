# 🌍 Analysis and Optimization of Global Energy Sustainability

## Project Overview
This project explores global energy sustainability using a rich dataset spanning from **2000 to 2020**, with the goal of identifying key drivers of **CO₂ emissions per capita**. Through data exploration and machine learning, we uncover actionable insights that can inform policy, support ESG strategies, and advance the energy transition.

---

## Dataset Description
The dataset includes over 20 years of data across countries, with indicators such as:
- CO₂ emissions per capita  
- GDP per capita  
- Energy intensity  
- Renewable energy share  
- Population density  
- Electricity access, and more

Source: [**Global Data on Sustainable Energy**](https://www.kaggle.com/datasets/anshtanwar/global-data-on-sustainable-energy)  

---

## Key Objectives
1. Clean, explore, and visualise global energy and emission indicators  
2. Use machine learning to **predict CO₂ emissions per capita**  
3. Identify the most impactful variables  
4. Provide **recommendations for sustainability strategies**

---

## Tools & Techniques
- **Language:** Python  
- **Libraries:** pandas, matplotlib, seaborn, scikit-learn  
- **ML Model:** Random Forest Regressor  
- **Evaluation:** R², RMSE, MAE, Feature Importance  
- **Tuning:** RandomizedSearchCV with cross-validation

---

## Exploratory Data Analysis (EDA)
We examined:
- Regional disparities in energy use and emissions  
- Correlation between economic development and emissions  
- Renewable adoption trends and outliers  
- Data cleaning and scaling to prep for modelling

---

## Predictive Modelling
- **Target:** CO₂ emissions (metric tons per capita)
- **Features Used:**
  - GDP per capita
  - Renewable energy share
  - Population density
  - Energy intensity (MJ per $GDP)
- **Final Model:** Random Forest with tuning
- **Best Cross-Validated R²:** **0.8530**

---

## Key Results & Insights
### Feature Importance
1. Population density  
2. Renewable energy share  
3. Energy intensity  
4. GDP per capita

### Model Performance
- R² = 0.85 (CV tuned)  
- Accurate for most countries; slight underestimation for outliers  
- Scatter plot shows strong predictive alignment with actual values

---

## Recommendations
- **Improve urban infrastructure** to reduce emissions in dense regions  
- **Expand renewable energy capacity** to accelerate decarbonisation  
- **Enhance energy efficiency** across sectors to reduce energy intensity

---

## Why This Matters
This project reflects real-world challenges in climate data analysis and shows your ability to:
- Work with complex sustainability datasets
- Build and validate predictive models
- Extract insights that matter to policy, ESG reporting, and sustainability strategy

---

## Next Steps
- Integrate time-series forecasting
- Build a dashboard using Tableau/Power BI
- Align indicators with ESG frameworks (e.g., SDGs, TCFD, GRI)

---

## About Me
I'm a Master of Business Analytics student passionate about using data to solve sustainability and environmental challenges.  
Let’s connect on **LinkedIn** ([https://linkedin.com/](https://www.linkedin.com/in/pashaarrighi/))
