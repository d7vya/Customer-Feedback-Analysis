# 📝 Customer Feedback Analysis Dashboard Project

This project is a comprehensive analysis of customer feedback data using Microsoft Excel. It involves cleaning and transforming raw data, creating meaningful age groups and rating categories, generating pivot tables, and designing visual dashboards with various charts for clear insights.

---

## 📊 Dataset Columns (Original)

- `CustomerID`
- `Age`
- `Gender`
- `Country`
- `Income`
- `ProductQuality` (scale: 1–10)
- `ServiceQuality` (scale: 1–10)
- `PurchaseFrequency`
- `FeedbackScore` (e.g., Low, Medium, High)
- `LoyaltyLevel` (e.g., Bronze, Silver, Gold)
- `SatisfactionScore` (scale: 1–10)

---

## 🔄 Transformed Columns

The dataset was enhanced by:

- `Age Group`: Categorized from Age into Teen/Young Adult, Adult, Early Adult, Mid-Age Adult, Older Adult, Elder
- `Rating of ProductQuality`: Categorized into Terrible, Not Satisfied, Average, Good, Satisfied (based on numeric ranges)
- `Rating of ServiceQuality`: Same rating scale applied
- `Rating of SatisfactionScore`: Same rating scale applied

---

## 📈 Pivot Tables & Charts

Several pivot tables were created to explore relationships between variables, and corresponding charts were used to visualize key insights:

### ✅ Charts in Dashboard

1. **Customer Satisfaction by Gender (Clustered Column Chart)**
   - Displays how males and females rated their satisfaction (Terrible → Satisfied).

2. **Customer Satisfaction by Age Group (Clustered Column Chart)**
   - Highlights satisfaction levels across different age categories.

3. **Loyalty Level vs Satisfaction (3D Clustered Column Chart)**
   - Checks whether Gold/Silver/Bronze members are satisfied.

4. **Feedback Score Levels (Horizontal Bar Chart)**
   - Visualizes how many customers rated feedback as Low, Medium, High.

5. **Customer Loyalty Distribution (Donut Pie Chart)**
   - Percentage distribution of customers across loyalty levels.

6. **Age Group Distribution (Pie Chart)**
   - Visual overview of customer count in each age category.

---

## 🎯 Key Goals

- Understand how customer satisfaction varies by age and gender.
- Identify if high-loyalty customers are actually satisfied.
- Correlate product and service quality with satisfaction and feedback.
- Present a visually clear and professional dashboard for business insights.

---

## 💼 Why This Is Interview-Ready

- **Multiple insights**: Gender-wise, Age-wise, Loyalty-level breakdowns.
- **Clean transformation logic**: Rating conversions, age grouping.
- **Visual clarity**: Pie charts, column charts, and bar charts used effectively.
- **Business focus**: Answers real business questions like loyalty vs. satisfaction.

---

## 📁 Tabs Overview

- `customer_feedback_satisfaction`: Cleaned raw dataset with transformations.
- `Gender Review`, `Age Wise Review`, `Product Satisfaction`, `Feedback`: Pivot tables and raw charts.
- `Dashboard`: Final visuals combined in a polished view.

---

## 🙌 Tools Used

- Microsoft Excel (Pivot Tables, Charts, Formulas)
- Logical formulas (IF statements for categorization)

---

Feel free to clone or reference this project for any analytics or dashboarding demonstration in interviews or personal portfolios!
