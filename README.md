# OJT-Task-1
Exploratory Data Analysis on a school dataset of 5,200 institutions to identify key factors affecting student performance. Includes data cleaning, visualization, feature engineering, and a baseline Linear Regression model showing the impact of infrastructure, parental literacy, and socio-economic conditions on Math scores.


# 📊 School Performance Analysis (EDA Project)

## 📌 Project Overview

This project performs **Exploratory Data Analysis (EDA)** on a dataset of **5,200 schools** to understand the factors influencing student academic performance, especially **Math scores**.

The analysis focuses on the impact of:

* Infrastructure facilities 🏫
* Socio-economic conditions 🌍
* Teacher-related factors 👨‍🏫

## 📁 Dataset Information

* Total Schools: **5,200**
* Features: **17**
* Key Variables:

  * Math, Language, Science Scores
  * Teacher-Student Ratio
  * Internet Availability
  * Parent Literacy Rate
  * Infrastructure Facilities

🎯 **Target Variable:** `%_Math_Score`

## 🧹 Data Preprocessing

* Handled missing values (~5%) using **median imputation**
* Removed inconsistencies:

  * Scores limited to **0–100**
  * Negative values corrected
* No duplicate records found


## 📊 Exploratory Data Analysis

### 📈 Distribution Analysis

* Scores follow an **approximately normal distribution**
* Average scores range between **60–63%**

### 🏙️ Urban vs Rural Analysis

* Urban schools show **better performance** compared to rural schools

### 🔗 Correlation Insights

* Positive impact:

  * Parent Literacy
  * Internet Access
  * Library Availability
* Negative impact:

  * High Teacher-Student Ratio
  * Higher Marginalized Population

### 🏗️ Infrastructure Impact

* Schools with better infrastructure score **significantly higher**


## 💡 Key Insights

* 📚 Parent literacy strongly affects student performance
* ⚡ Basic facilities like electricity improve learning outcomes
* 🌐 Internet access supports self-learning
* 🏫 Infrastructure is a major performance driver
* 👨‍🏫 Teacher experience alone is not sufficient

## ⚙️ Feature Engineering

Created new features:

* `Avg_Score`
* `Infra_Index`
* `Is_Urban`
* `Teacher_Quality_Score`


## 🤖 Machine Learning Model

* Model Used: **Linear Regression**
* Train-Test Split: **80/20**
* Scaling: **StandardScaler**

📊 Results:

* **R² Score:** 0.35
* **RMSE:** 12

## ✅ Conclusion

Infrastructure, parental literacy, and location are the **most important factors** affecting student performance. Improving rural facilities and digital access can significantly enhance outcomes.


## 🛠️ Technologies Used

* Python 🐍
* Pandas
* NumPy
* Matplotlib / Seaborn
* Scikit-learn


