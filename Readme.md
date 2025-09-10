
# 🏦 AtliQO Bank Credit Card Analytics & A/B Testing

## 📌 Project Overview  
This project is divided into **two phases**:  
- **Phase 1:** Data extraction, cleaning, and exploratory analysis of customer, transaction, and credit profile data.  
- **Phase 2:** Business analysis and **A/B testing** for the launch of a new credit card targeting young customers (18–25 age group).  

The goal is to **analyze customer behavior, design an experiment, and evaluate campaign effectiveness** using statistical methods.  

---

## 🚀 Project Phases  

### 🔹 Phase 1: Data Analysis & Preparation  
- Connected to **MySQL database** and imported data (`customers`, `transactions`, `credit_profiles`).  
- Performed **data cleaning & preprocessing**:  
  - Handled missing/invalid values (e.g., zero annual income).  
  - Treated missing credit scores and incomplete profiles.  
- Conducted **Exploratory Data Analysis (EDA)**:  
  - Income distribution and demographics.  
  - Credit score & credit limit patterns.  
  - Transaction behavior by customer segments.  
- Output: A **clean dataset** ready for business analysis and campaign design.  

---

### 🔹 Phase 2: Business Analysis & A/B Testing  
- Targeted **age group 18–25** (~25% of customer base).  
  - Observed low income (<50k), limited credit history, and low credit card adoption.  
- Designed an **A/B testing campaign**:  
  - Test group: 100 customers (new credit card offer).  
  - Control group: 40 customers (no new offer).  
  - Duration: 2 months (Sept–Nov 2023).  
  - KPI: **Average transaction amount**.  
- Applied **Statistical Analysis**:  
  - Calculated sample size using **statistical power & effect size (0.4 SD → 100 customers)**.  
  - Conducted **Two-Sample Z-Test** to validate campaign effectiveness.  
- **Results**:  
  - ~40% conversion rate in test group.  
  - Statistically significant improvement in average transaction amounts compared to control.  

---

## 🛠️ Tech Stack  
- **Languages & Tools**: Python, MySQL, Jupyter Notebook  
- **Libraries**: Pandas, NumPy, Matplotlib, Statsmodels, Scipy  
- **Methods**: EDA, Data Cleaning, Hypothesis Testing, A/B Testing, Statistical Power Analysis  

---

## 📂 Project Structure  
```
├── phase_1_AtliqO.ipynb         # Phase 1: Data cleaning & EDA
├── phasse_2_AtliqO.ipynb        # Phase 2: Business analysis & A/B testing
├── README.md                    # Project documentation
```

---

## 📈 Key Insights  
- Customers aged **18–25 are underserved** and present an untapped market.  
- Launch of new credit card resulted in a **40% adoption rate** among test customers.  
- **A/B testing confirmed** that the new card significantly improved average transaction amounts.  
- Data-driven recommendations can guide **future product launches and targeted campaigns**.  

---

## 🎯 Learning Outcomes  
- Hands-on experience in **data preparation, EDA, and campaign analysis**.  
- Practical application of **A/B testing and hypothesis testing** in a business context.  
- Ability to connect **SQL databases** with Python for analytics.  
- Experience in **customer segmentation and KPI-driven decision-making**.  

---

## 📌 Author  
👤 **Owais Khan**  
📧 Email: trgxowais@gmail.com  
🔗 LinkedIn: your-linkedin: https://www.linkedin.com/in/owais-khan-008929265/ 

---

👉 This project demonstrates end-to-end **Data Analytics & Business Intelligence skills**: from **data cleaning and EDA** to **experiment design, hypothesis testing, and business insights**.  
