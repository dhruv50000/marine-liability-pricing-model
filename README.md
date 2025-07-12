
# Marine Liability Insurance Pricing Model

This project simulates the experience-based pricing of Marine Third-Party Liability insurance, modeled as part of AIG’s Virtual Actuarial Internship (Forage). It includes historical claims analysis, risk adjustment, pure premium computation, and final rate recommendations.

---

## 🎯 Objectives

- Derive missing claim data from raw datasets (gross, adjusted, capped claims)
- Analyze trends in claim severity and frequency using exploratory data analysis (EDA)
- Apply actuarial pricing techniques (frequency × severity, risk margin)
- Adjust for inflation, deductibles, and capped limits
- Recommend final premium with sensitivity analysis

---

## 📊 Features

- 🧮 **Claims Data Derivation**:
  - Computed gross claim, gross adjusted claim, net adjusted claim, and capped net loss
- 📈 **EDA Dashboard**:
  - Claims by type, year, and severity distributions (histograms, bar charts)
- 💡 **Pricing Model**:
  - Pure Premium = Frequency × Severity  
  - Final Premium = Pure + Risk Margin + Expense Load
- 🔁 **Sensitivity Analysis**:
  - Impact of 10–30% increase in severity/frequency  
  - Added 1-in-20-year large-loss layer to simulate catastrophic events

---

## 🧠 Actuarial Concepts Used

- Experience Rating (based on historical loss data)
- Trend & Inflation Adjustments
- Deductible Impact Modeling
- Loss Capping with Policy Limits
- Sensitivity Testing with Scenario Manager
- Pure Premium → Loaded Premium Conversion

---

## 🛠️ Tools Used

- Microsoft Excel (Data Cleaning, Formulas, PivotTables, Graphs)
- Manual Actuarial Calculations (Loss Ratio, Risk Load)
- Scenario Testing using Excel's Data Table / What-If Analysis

---

## 📎 Files Included

| File | Description |
|------|-------------|
| `Claims Data` | Cleaned claim-level dataset with derived columns |
| `EDA` | Frequency/Severity visualizations & tables |
| `Pricing_Model` | Pure premium + loaded premium with risk margin |
| `Sensitivity_Analysis` | Premium impact under loss trend scenarios |
| `Report` | Commentary on pricing model, risk exposure, and recommendations

---

## 📌 Key Outcome

> Final premium recommendation was based on frequency × severity with 15–25% risk/expense loading.  
> Sensitivity analysis revealed highest premium sensitivity to large-loss scenarios and inflation assumptions.

---

## 📑 Developed As Part Of

**AIG Forage Virtual Actuarial Internship – Marine Liability Module**  
Prepared by: Dhruv Goel (B.Sc. Statistics, Kirori Mal College | IFoA Student)

---
