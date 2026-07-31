# 📊 Vendor Performance Analysis  

**Presented By:** Nirmala Devi Suresh  
**Mentor:** Mr. Suresh  
**Institute:** Novitech R & D  
**Date:** 21-07-2026  

---

## 📝 Problem Statement  
The company purchases raw materials and products from multiple vendors. These vendors differ in pricing, delivery time, reliability, and product quality. Currently, vendor selection is based on past relationships rather than structured data analysis.  

This leads to challenges such as:  
- Higher procurement costs  
- Quality issues and delays  
- Lack of visibility into vendor performance  

The objective is to build a **data-driven vendor evaluation framework** to optimize procurement decisions and improve profitability.  

---

## 🎯 Objectives  
The analysis focuses on seven core dimensions:  
1. **Pricingwise Analysis** – Identify cost-efficient vendors  
2. **Deliverywise Analysis** – Assess delivery consistency  
3. **Qualitywise Analysis** – Measure defect/rejection rates  
4. **Procurementwise Analysis** – Evaluate overall spend and dependency  
5. **Negotiated Analysis** – Quantify negotiation effectiveness  
6. **Reliability Analysis** – Measure compliance and responsiveness  
7. **Yearlywise Analysis** – Track vendor trends over time  

---

## 📂 Dataset  
The dataset used for this project was sourced from Kaggle:  
**Procurement KPI Analysis Dataset**  
[Link to dataset](https://www.kaggle.com/datasets/shahriarkabir/procurement-kpi-analysis-dataset)  

It contains procurement records including:  
- Purchase orders  
- Supplier details  
- Item categories  
- Delivery timelines  
- Unit prices and negotiated prices  
- Compliance information  

This dataset served as the foundation for analyzing vendor performance across pricing, delivery, quality, reliability, and procurement history.  

---

## ⚙️ Methodology  
1. **Data Collection:** Kaggle Procurement KPI dataset  
2. **Data Understanding:** Mapping dataset fields to analysis categories  
3. **Data Cleaning:**  
   - Removed incomplete delivery records  
   - Imputed missing defect values using supplier averages  
4. **Data Modelling:** Derived metrics created:  
   - `Status_rate`  
   - `Total Spend`  
   - `Savings`  
   - `Defective_Rate`  
   - `Compliance_rate`  
   - `Negotiated_rate`  
5. **Dashboard Development:** Excel Pivot Tables for structured analysis  

---

## 📈 Findings  
- **Alpha Inc:** Strong quality & savings  
- **Beta Supplies:** Large delivery volumes but high defect rates  
- **Delta Logistics:** Weak compliance, high defects  
- **Gamma Co:** Moderate results, higher defect levels  
- **Epsilon Group:** Superior compliance (98%), strong reliability, low defects → *Best overall vendor despite higher pricing*  

---

## 🔮 Future Scope  
While the current analysis identifies **Epsilon Group** as the most suitable supplier overall, future work can extend this study by:  

- **Item‑wise Analysis:** Determining which vendor performs best in each product category (e.g., raw materials, office supplies, electronics).  
- **In‑depth Calculations:** Applying detailed cost–benefit and defect rate analysis for each category to uncover hidden strengths and weaknesses.  
- **Savings Analysis:** Evaluating negotiated savings across categories to identify which supplier provides the highest cost efficiency.  
- **Future Forecasting:** Leveraging advanced tools such as Power BI and Tableau to build interactive dashboards and predictive models for supplier performance.  
- **Delivery Time Analysis:** Evaluating which supplier consistently delivers in the shortest time period, adding speed as a key performance metric.  
- **Regional Vendor Analysis:** Calculating vendor regions (e.g., by state, zone, or country) to assess how location impacts delivery speed, logistics costs, and reliability. This will help identify whether proximity improves procurement efficiency and reduce risks associated with regional dependency.  

---

## 🚀 How to Reproduce  
1. **Clone this repository**  
   ```bash
  git clone https://github.com/nirm2812/vendor-performance-analysis.git
cd vendor-performance-analysis
