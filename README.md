# Bank Loan Analysis (Python / Colab)

Analyze a loan portfolio using Python, Pandas, and Plotly.  
This project computes portfolio KPIs, Good vs Bad loan metrics, and interactive visuals for monthly trends, regions, term, employment length, purpose, and home ownership.


## 📌 Problem Statement (BRD)

### BRD 1: Summary — KPIs
- **Total Loan Applications** 
- **Total Funded Amount** 
- **Total Amount Received** 
- **Average Interest Rate**
- **Average Debt-to-Income Ratio (DTI)**

### BRD 1: Summary — Good vs Bad Loan KPIs
**Good Loan**
- Good Loan Application Percentage  
- Good Loan Applications  
- Good Loan Funded Amount  
- Good Loan Total Received Amount  

**Bad Loan**
- Bad Loan Application Percentage  
- Bad Loan Applications  
- Bad Loan Funded Amount  
- Bad Loan Total Received Amount  

### Charts
- **Monthly Trends by Issue Date** (Line/Area): seasonality and long-term trends  
- **Regional Analysis by State** (Bar): regional disparities and activity  
- **Loan Term Analysis** (Donut): distribution across term lengths  
- **Employment Length Analysis** (Bar): how metrics vary by employment history  
- **Loan Purpose Breakdown** (Bar): primary reasons for financing  
- **Home Ownership Analysis** (Tree/Heat Map): impact of home ownership  
  - *Metrics shown: Total Loan Applications, Total Funded Amount, Total Amount Received*

---

## 🧠 Definitions & Assumptions
- **MTD (Month-to-Date):** by default uses the **latest month present** in the dataset’s `issue_date`. (You can switch to “today” if desired.)
- **Good Loans:** `Fully Paid`, `Current`
- **Bad Loans:** `Charged Off`, `Default` *(adjust if your statuses differ)*

---

## 📂 Dataset 
financial_loan.xlsx



