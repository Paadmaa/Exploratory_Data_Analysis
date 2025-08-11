# 💼 Thera Bank Personal Loan Campaign – EDA Project

![Thumbnail](https://github.com/Paadmaa/Exploratory_Data_Analysis/blob/master/Bank%20Personal%20Loan%20Modelling/business-loan-273540282-16x9_0.avif)

## 📌 Project Overview
This project performs **Exploratory Data Analysis (EDA)** on customer data from **Thera Bank**, aiming to uncover patterns that influence personal loan acceptance. Using Python and essential data analysis libraries, we analyze customer demographics, banking relationships, and campaign responses to help the bank improve future marketing strategies.

---

## 🧠 Business Context
Thera Bank wants to **convert liability customers into personal loan customers** without losing them as depositors. A previous campaign achieved a **9.6% conversion rate**, with 480 out of 5000 customers accepting the offer. The goal now is to identify key traits of responsive customers and **optimize future campaigns** for better targeting and cost-efficiency.

---

## 📊 Dataset Description

The dataset (`Bank.xls`) contains **5000 customer records** with the following features:

| Feature               | Description |
|----------------------|-------------|
| `Age`                | Customer's age |
| `Experience`         | Years of professional experience |
| `Income`             | Annual income (in $000) |
| `Family`             | Number of family members |
| `CCAvg`              | Avg. monthly credit card spending |
| `Education`          | Education level (1: Undergrad, 2: Graduate, 3: Advanced) |
| `Mortgage`           | Mortgage amount |
| `Securities Account`| Whether the customer has a securities account |
| `CD Account`         | Whether the customer has a certificate of deposit account |
| `Online`             | Whether the customer uses online banking |
| `CreditCard`         | Whether the customer has a credit card |
| `Personal Loan`      | Target variable (1: Accepted, 0: Not accepted) |

---

## 🛠️ Tools & Libraries
- **Python 3.x**
- **Pandas** – Data manipulation  
- **NumPy** – Numerical operations  
- **Matplotlib & Seaborn** – Visualization  
- **OpenPyXL / xlrd** – Excel file handling  

---

## 🔍 EDA Workflow

### 1. 📦 Data Loading & Cleaning
- Imported Excel file using `pandas.read_excel()`  
- Checked for missing values and data types  
- Verified class imbalance in `Personal Loan` column  

### 2. 📈 Univariate Analysis
- Distribution plots for `Age`, `Income`, `CCAvg`, and `Mortgage`  
- Count plots for categorical features like `Education`, `Family`, and `Online`  

### 3. 📊 Bivariate Analysis
- Compared loan acceptance across education levels, income brackets, and account types  
- Used boxplots and bar charts to highlight differences in spending and income  

### 4. 🔥 Correlation Analysis
- Generated a heatmap to identify relationships between numerical features  
- Found strong correlations between `Income`, `CCAvg`, and loan acceptance  

---

## 💡 Key Insights

| Insight | Summary |
|--------|---------|
| 🎓 Education | Customers with higher education levels are more likely to accept loans |
| 💰 Income | Higher income correlates with higher loan acceptance |
| 🏦 Account Types | CD and securities account holders show higher conversion rates |
| 📱 Online Banking | Online users are more engaged and responsive to campaigns |
| 💳 Credit Card Usage | High credit card spenders are more likely to accept loans |

---

## 🚀 How to Run

```bash
# Clone the repository
git clone https://github.com/Paadmaa/Finance-Loan-EDA.git

# Install dependencies
pip install pandas numpy matplotlib seaborn openpyxl

# Launch the notebook
jupyter notebook finance_loan_eda.ipynb
```

---

## 📈 Recommendations

### For Marketing Teams:
- Target **graduate and advanced degree holders**  
- Focus on **high-income customers** with active banking relationships  
- Prioritize customers with **CD accounts, securities accounts**, and **online banking usage**

### For Future Campaigns:
- Use **predictive modeling** to score leads before outreach  
- Personalize offers based on **spending behavior and account activity**

---

## 🔮 Future Work
- Build a **classification model** to predict loan acceptance  
- Apply **feature engineering** to improve model accuracy  
- Create a **dashboard** for campaign performance tracking  

---

## ✅ Conclusion
This EDA project helps Thera Bank understand customer behavior and improve personal loan targeting. By analyzing key features, we’ve identified actionable strategies to boost campaign success while minimizing costs.

---

## 📄 License
This project is licensed under the [MIT License](https://opensource.org/licenses/MIT). Feel free to use, modify, and share.

---

## 📬 Contact
- GitHub: [Paadmaa](https://github.com/Paadmaa)  
- LinkedIn: [Padma Ch. Behera](https://www.linkedin.com/in/padmach-behera/)  

---

Let me know if you'd like help turning this into a LinkedIn post or adding visuals to the notebook!
