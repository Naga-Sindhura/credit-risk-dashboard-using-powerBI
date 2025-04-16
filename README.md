# 📊 Credit Risk Dashboard | Power BI, DAX, Data Visualization

An interactive dashboard built using Power BI to analyze loan performance and assess credit risk. This project uses a real-world dataset from Kaggle and applies data modeling, DAX measures, and insightful visuals to help uncover loan default patterns and borrower risk segments.

---

## 🔍 Project Overview

This dashboard offers a multi-page view into credit risk analytics:

- Tracks loan performance, borrower behavior, and risk levels
- Computes and visualizes key metrics like **default rate**, **loan-to-income ratio**, and **interest rate by risk**
- Applies **risk segmentation logic using DAX**
- Enables dynamic filtering through slicers (e.g., home ownership)

---

## 🧩 Pages & Insights

### 📄 **Page 1: Loan Summary**
A high-level overview of loan activity and default patterns.
- **KPI Cards**: Average loan amount, interest rate, loan-to-income ratio, and overall default rate
- **Pie Chart**: Loan status distribution (default vs. non-default)
- **Bar Charts**: Default rate and loan-to-income ratio by **loan intent**
- **Slicer**: Home ownership for borrower-based filtering

---

### 📄 **Page 2: Risk Analysis**
Breakdown of loans by risk level and loan grade.
- **Line Chart**: Average interest rate vs default rate by **loan grade**
- **Pie Chart**: Loan distribution by **High Risk** / **Low Risk**
- **Bar Charts**: Interest rate and loan amount by **risk level**
- **KPI Cards**: Total loans, total defaults, and risk-based metrics

---

### 📄 **Page 3: Risk Drivers**
Analyzes borrower characteristics affecting loan risk.
- **Matrix**: Default rate and risk level by **loan intent and grade**
- **Bar Charts**: 
  - Default rate by **employment length**
  - Default rate by **historical default status**
  - Default rate across **age groups**
- **Chart**: Loan status compared with historical default

---

## 🧠 Key Features & Techniques

- ✅ **DAX Measures** for custom calculations:
  - `Default Rate`
  - `Loan-to-Income Ratio`
  - `Risk_Level` column based on default rate thresholds
- ✅ **Data Modeling** with categorical & numerical attributes
- ✅ **Slicers** for interactivity
- ✅ **Clear segmentation** for risk insight

---

## 📁 Project Files

- `Credit_Risk_Dashboard.pbix` – Power BI Dashboard
- `page1.jpg`, `page2.jpg`, `page3.jpg` – Visual screenshots
- `README.md` – Project documentation (this file)
- 'credit_risk_dataset' - Dataset

---

## 🧰 Tools & Dataset

- **Power BI Desktop**
- **DAX** for calculated columns and measures
- **Dataset Source**: [Kaggle - Give Me Some Credit](https://www.kaggle.com/)
- **Visualization Style**: KPI cards, line/bar charts, pie, matrix visuals

---

## 📸 Screenshots

### 🔹 Page 1: Loan Summary  
![Page 1](dashboard-page1.png)

### 🔹 Page 2: Risk Analysis  
![Page 2](page2.png)

### 🔹 Page 3: Risk Drivers  
![Page 3](page3.png)

---

## 🙌 Credits

Created by Naga Sindhura Padala as part of a Power BI portfolio project.

---

## 🔗 Connect

If you found this project helpful or interesting, feel free to connect:

- [LinkedIn](https://www.linkedin.com/in/naga-sindhura-padala-59095825b//)
- [GitHub](https://github.com/Naga-Sindhura)

