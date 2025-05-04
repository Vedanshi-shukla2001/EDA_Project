# 📊 Telco Customer Churn - EDA Project

This project performs **Exploratory Data Analysis (EDA)** on the [Telco Customer Churn dataset](https://raw.githubusercontent.com/IBM/telco-customer-churn-on-icp4d/master/data/Telco-Customer-Churn.csv), a popular dataset provided by IBM. The goal is to uncover patterns related to customer attrition and churn using Python's data analysis libraries.

---

## 🗂️ Project Structure

EDA_Project/
├── Python_EDA_Project.ipynb
├── README.md
└── requirements.txt 


---

## 📌 Key Objectives

- Clean and preprocess the Telco Customer Churn data
- Handle missing values and datatype issues
- Explore categorical and numerical features
- Visualize relationships and distributions
- Identify factors influencing customer churn

---

## 📥 Dataset

- **Source:** [IBM Sample Data](https://raw.githubusercontent.com/IBM/telco-customer-churn-on-icp4d/master/data/Telco-Customer-Churn.csv)
- **Records:** ~7,000 customers
- **Features:**
  - Demographics (e.g., gender, senior citizen)
  - Services signed up (e.g., internet, phone, streaming)
  - Tenure, charges, and contract types
  - Target variable: `Churn`

---

## 🔍 Analysis Performed

1. **Data Cleaning**
   - Convert `TotalCharges` to numeric
   - Handle missing values
   - Drop irrelevant columns (`customerID`)

2. **Univariate Analysis**
   - Distribution of tenure, charges
   - Bar plots for contract, gender, churn, etc.

3. **Categorical Breakdown**
   - Churn rate by internet service, payment method, and more

4. **Correlation Heatmap**
   - Visualize relationships between numerical features

5. **Pairwise Plot**
   - Explore feature interactions with respect to churn

6. **Feature Engineering**
   - Derive new features (if any were added)

7. **Observations & Insights**
   - Key takeaways about what influences customer churn

---

## 🛠️ Libraries Used

- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`

Install dependencies:
```bash
pip install -r requirements.txt

📌 **Sample Visualizations**
Missing value heatmap

Bar plots for churn distribution

Correlation matrix

Pairplots for key features

🤔 **Key Insights**
Customers with month-to-month contracts are more likely to churn.

Fiber optic internet service users have higher churn rates.

Longer tenure usually indicates more loyal customers.

Customers with electronic check payments are more likely to churn.

**How to Run**
git clone https://github.com/your-username/EDA_Project.git
cd EDA_Project

jupyter notebook Python_EDA_Project.ipynb

📃 **License**
This project is licensed under the MIT License.

✍️ **Author**
Vedanshi Shukla
GitHub https://github.com/Vedanshi-shukla2001/EDA_Project 
