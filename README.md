# 📊 Regression Analysis: Workload vs Mental Health in University Students  

<!--Implemented an end-to-end heart disease prediction system using Logistic Regression with automated data loading, EDA, and hyperparameter optimization. Achieved 85% accuracy on test data with strong F1-scores (~0.87), confirming chest pain type and maximum heart rate as dominant clinical indicators.
-->

## 📌 Introduction  
In this project, we collected data from over **200+ university students** and prepared both **simple linear** and **multiple linear regression models**.  
Our goal was to identify relationships between the features of our survey and visualize them effectively.  

Key highlights of the project:  
- Built **Simple and Multiple Linear Regression Models** based on feature correlations (using heatmaps).  
- Conducted **4 types of Hypothesis Testing**:  
  1. Independent t-test  
  2. One-way ANOVA  
  3. Correlation test  
  4. Proportion test (Chi-square)  
- Designed an interactive dashboard to visualize key findings.  

---

## 📊 Dataset  
- Collected through a **survey among university students in Bangladesh** using Google Forms.  
- Responses came from students across **multiple institutions**.  
- **Data integrity** was prioritized — ensuring unique and diverse participants.  
- Final dataset reflects **dynamic real-world data** on workload and mental health.  

---

## 🔍 Methodology  
1. **Survey Design & Data Collection**  
   - Google Form questionnaire covering workload, stress, anxiety, sleep, extracurriculars, demographics.  
   - Gathered >200 responses.  

2. **Data Preprocessing**  
   - Missing value handling  
   - Categorical encoding (Yes/No, Year of Study, Gender)  
   - Outlier detection  

3. **Exploratory Data Analysis (EDA)**  
   - Summary statistics & visualizations  
   - Correlation heatmap to identify significant relationships  
   - Boxplots, scatterplots  

4. **Hypothesis Testing**  
   - Tested relationships between workload and mental health indicators.  
   - Applied appropriate tests with assumptions and interpretations.  

5. **Regression Analysis**  
   - Simple Linear Regression (e.g., Stress ~ Study Hours)  
   - Multiple Linear Regression (e.g., Stress ~ Study Hours + Sleep Quality + Credits + Activities)  
   - Model evaluation: coefficients, R², p-values, residuals  

---

## 📈 Key Insights  
- Workload indicators (study hours, credits) show a **positive relationship** with stress and anxiety.  
- Sleep hours and sleep quality are **negatively correlated** with stress and anxiety.  
- Extracurricular activities have a **moderating effect** on mental health outcomes.  
- Hypothesis testing validated several significant relationships across groups.  

---

## 🖥️ Interactive Dashboard  
We developed a **Streamlit/Dash dashboard** to present findings:  
- Correlation heatmap (interactive)  
- Scatter plots with regression lines  
- Boxplots by year, gender, or job status  
- Regression model summary (equation, coefficients, R²)  
- Textual interpretation panel  

---


---

## ⚙️ Technologies Used  
- **Python**: pandas, numpy, statsmodels, scipy, scikit-learn  
- **Visualization**: matplotlib, seaborn, plotly  
- **Dashboard**: Streamlit / Dash  
- **Survey Tool**: Google Forms  

---

## 📢 Conclusion  
This project demonstrates how **statistical modeling** and **regression analysis** can be applied to real-world survey data.  
It highlights the relationship between **workload** and **mental health** in university students, providing evidence-based insights to improve student well-being.  

---

