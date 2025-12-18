# Insurance Portfolio Performance Dashboard (Power BI)

An end-to-end insurance analytics project built in **Power BI**, designed to analyze premium flows, maturity outcomes, coverage efficiency, payment risk, and sales productivity through a professional, business-ready dashboard.

---

## 📌 Project Overview

This project simulates a real-world insurance analytics solution used by management to evaluate portfolio health, investment performance, coverage alignment, collection risk, and sales productivity across hierarchical roles.

The dashboard follows a **dark blue–purple theme**, uses rounded visuals, custom icons, and a left-side navigation panel to resemble a production-grade BI product rather than a default Power BI report.

---

## 🎯 Business Objectives

- Understand how invested premiums compare to expected maturity values  
- Identify high-profit and high-return insurance products  
- Evaluate whether premiums are aligned with coverage benefits  
- Assess near-term vs long-term collection risk  
- Monitor regional and agent-level sales productivity  
- Secure sensitive data using role-based access control (RLS)

---

## 📊 Dashboard Pages & Business Questions

### 1️⃣ Overview Page  
**Business Question:**  
**“What is the current health and composition of the insurance portfolio?”**

![Overview](<Dashboard Images/overview.PNG>) 

**Key KPIs**
- Total Number of Policies  
- Total Annual Premium  
- Total Premium Amount  
- Total Premium Paid  
- Total Premium Payable  
- Underwriting Cost  

**Visuals & Insights**
- Policy distribution by **Policy Type** and **Policy Name**
- Premium contribution by **Occupation**
- Portfolio trend over **Year**
- Geographic distribution by **State**
- Field parameter slicer to dynamically switch measures

**Purpose:**  
Gives executives a quick, reliable snapshot of portfolio scale, composition, and risk exposure.

---

### 2️⃣ Summary / Detail Page  
**Business Question:**  
**“Can we drill down to transaction-level details when needed?”**

![Summary](<Dashboard Images/summary.PNG>) 

**Features**
- Excel-style transaction table
- Fully filterable
- Toggle view using bookmarks and buttons

**Purpose:**  
Supports audits, investigations, and operational follow-ups without leaving Power BI.

---

### 3️⃣ Investment vs Maturity Page  
**Business Questions**
- **How do invested premiums compare with expected maturity values?**
- **Which policies generate the highest absolute profit?**
- **Which policies deliver better annualized returns?**

![Investment](<Dashboard Images/investment.PNG>)  

**Visuals**
- Clustered column chart: **Total Premium Paid vs Total Maturity Amount**
- Bar chart: **Profit / Gain by Policy**
- Ribbon chart: **Annualized ROI % ranking by policy**

**Purpose:**  
Evaluates investment efficiency and identifies products that truly create value over time.

---

### 4️⃣ Premium vs Coverage Page  
**Business Questions**
- **Are premiums aligned with coverage levels?**
- **Do higher premiums result in better returns?**
- **Which policy types generate higher profit per policy?**

![Coverage](<Dashboard Images/coverage.PNG>) 

**Visuals**
- Line & column chart: **Total Premium vs Coverage Multiple**
- Scatter plot: **Premium vs ROI %**
- Bar chart: **Profit per Policy Type**

**Purpose:**  
Ensures customers are not overpaying for underperforming coverage and helps insurers refine product pricing.

---

### 5️⃣ Payment Analysis Page  
**Business Questions**
- **What is the near-term vs long-term collection risk?**
- **How does collection progress over time?**
- **Which regions or states are most at risk?**

![Payments](<Dashboard Images/payments.PNG>) 

**Visuals**
- Stacked column chart: **Paid vs Payable by Payment Bucket**
- Line chart: **Premium Paid vs Payable over Year**
- Treemap: **Premium Payable by State**

**Purpose:**  
Highlights liquidity risk and supports proactive collection strategies.

---

### 6️⃣ Sales Productivity Page  
**Business Question:**  
**“How is insurance performance distributed across the sales hierarchy?”**

![Productivity Chart](<Dashboard Images/productivity-chart.PNG>)  
![Productivity Matrix](<Dashboard Images/productivity-matrix.PNG>)  

**Key Features**
- Button-controlled bookmarks (Chart View / Matrix View)
- Dynamic hierarchy using field parameters:
  - Zonal Manager  
  - Regional Manager  
  - Sales Agent  
- Measures:
  - Total Annual Premium  
  - Total Premium Amount  
  - Total Maturity Amount  

**Security**
- Role-Level Security (RLS) applied for Zonal and Regional Managers
- Email-based slicers ensure users see only authorized data

**Purpose:**  
Tracks performance fairly while protecting sensitive financial information.

---

## 🧮 Key Calculations Used

- **Total Annual Premium** (normalized from payment frequency)
- **Total Premium Amount** (full tenure)
- **Total Premium Paid**
- **Total Premium Payable**
- **Total Maturity Amount (rule-based return logic)**
- **Profit / Gain**
- **Coverage Multiple**
- **Annual ROI**
- **Annualized ROI %**
- **Portfolio CAGR %**

**Why these matter:**  
They mirror how insurers evaluate profitability, customer value, and long-term sustainability in real operations.

---

## 🧩 Problems Faced & Solutions

### Large PBIX File (>25 MB)
**Problem:** GitHub size limit  
**Solution:** Used **Git Large File Storage (Git LFS)** to track `.pbix` files

### Navigation Copy Issues
**Problem:** Only background copied, buttons missing  
**Solution:** Used **Selection Pane** to group and lock navigation elements

### Mixed Metric Interpretation
**Problem:** Coverage Multiple initially misleading  
**Solution:** Fixed aggregation logic and clarified scale usage

### Button Hover Distortion
**Problem:** Matrix button zooming on hover  
**Solution:** Rebuilt button states with consistent formatting

---

```

## 📂 Repository Structure

Insurance-Portfolio-Performance-Dashboard/
│
├── datasets/ # Source data used in the report
├── Dashboard Images/ # Dashboard screenshots
├── icons/ # Icons, logos, backgrounds
├── .gitattributes # Git LFS configuration
├── Insurance Portfolio & Performance Dashboard.pbix
├── LICENSE
└── README.md

```


---

## 🚀 How to Open the PBIX File

1. Download the repository  
2. Install **Power BI Desktop (latest version recommended)**  
3. Open `Insurance Portfolio & Performance Dashboard.pbix`

> Note: File is tracked using **Git LFS**, so ensure Git LFS is installed if cloning.

---

## 👤 About Me

Hi, I’m **Ayush Ranabhat**, an aspiring data analyst with a strong foundation in finance and hands-on experience building business-grade Power BI solutions.

This project reflects my focus on:
- Analytical thinking  
- Business-oriented KPIs  
- Clean visual design  
- Real-world problem solving  

I enjoy turning complex data into insights that decision-makers can trust.

---

## 🔗 Let’s Connect

[![Email](https://img.shields.io/badge/Email-Ayura833@gmail.com-blue?style=flat-square&logo=gmail&logoColor=white)](mailto:Ayura833@gmail.com)  
[![Email](https://img.shields.io/badge/Email-Ayurasen@outlook.com-blue?style=flat-square&logo=microsoft-outlook&logoColor=white)](mailto:Ayurasen@outlook.com)  
[![Facebook](https://img.shields.io/badge/Facebook-Profile-1877F2?style=flat-square&logo=facebook&logoColor=white)](https://www.facebook.com/Ayurasen123)  
[![Instagram](https://img.shields.io/badge/Instagram-Profile-E4405F?style=flat-square&logo=instagram&logoColor=white)](https://www.instagram.com/_uke_p/)  
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Profile-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/ayush-ranabhat-87b577262/)  
[![Tableau](https://img.shields.io/badge/Tableau-Visualizations-E97627?style=flat-square&logo=tableau&logoColor=white)](https://public.tableau.com/app/profile/ayush.ranabhat2075/vizzes)

---

⭐ If you found this project insightful, feel free to star the repository!
