# 📊 Telecom Customers Churn Analysis

![Dashboard Page 1](/Churn%20Overview%20Page.png)


## 📌 Project Overview
Customer churn is one of the most critical challenges faced by telecom companies. Losing existing customers directly impacts revenue, increases acquisition costs, and reduces long-term customer lifetime value.

This project focuses on **analyzing customer churn patterns**, identifying **key drivers behind churn**, and proposing **actionable business strategies** to improve customer retention using data-driven insights.

---

![Dashboard Page 2](/Risk%20Drivers%20Page.png )

## 🎯 Business Objective
The primary objectives of this analysis were:
- Identify **which customers are churning**
- Understand **why customers are leaving**
- Provide **practical recommendations** to reduce churn

---

## 🧠 Problem Statement
The telecom company observed a **consistently increasing churn rate** but lacked clarity on:
- What factors contribute most to churn
- Which customer segments are at highest risk
- How to intervene before customers leave

The goal was to transform raw customer data into **clear, actionable insights**.

---

## 🗂️ Dataset Description
The dataset contains customer-level information including:
  
- **Account Information**: Tenure, contract type, payment method  
- **Service Usage**: Internet service, phone service, add-ons  
- **Financial Metrics**: Monthly charges, total charges  
- **Target Variable**: Churned, stayed or joined

Each row represents **one customer**.

---

## 🔍 Approach & Methodology (What I Did & How I Did It)

### Step 1: Data Understanding
- Reviewed all columns to understand business meaning
- Identified categorical and numerical variables
- Understood how churn is represented in the dataset

---

### Step 2: Data Cleaning & Preparation
- Checked for missing and inconsistent values
- Ensured correct data types for numerical columns
- Validated total charges against tenure × monthly charges
- Prepared clean data for analysis and visualization

**Tools used:**
- SQL for data validation and transformation  
- Excel for sanity checks and quick verification  

---

### Step 3: Exploratory Data Analysis (EDA)
The goal of EDA was to uncover **patterns, relationships, and anomalies** related to churn.

**Analysis performed:**
- Churn rate by contract type
- Churn rate by tenure groups
- Monthly charges vs churn
- Service usage vs churn

**Visualization focus:**
- Segment comparison
- Trend identification
- Risk group isolation

**Tool used:**  
- Power BI for interactive visual analysis

---

## ❓ Key Business Questions Answered
- Does contract duration affect churn?
- Are new customers more likely to churn?
- Do pricing and monthly charges influence churn?
- Which customer segments require immediate attention?
- How does Add on services affect the overall churn rate?

---

## 📈 Key Insights (The “Why”, Not Just the “What”)

### 🔹 Insight 1: Contract Type Is the Strongest Churn Driver
Customers on **month-to-month contracts** churn significantly more than those on annual or two-year contracts.

**Why this happens:**  
Lower commitment and easier switching increase churn likelihood.

---

### 🔹 Insight 2: New Customers Are the Most Vulnerable
Customers with **low tenure (first few months)** show the highest churn rate.

**Why this happens:**  
Poor onboarding experience, unmet expectations, or lack of early engagement.

---

### 🔹 Insight 3: High Monthly Charges Increase Churn Risk
Customers paying **higher monthly charges** churn more, especially when combined with short-term contracts.

**Why this happens:**  
Customers perceive lower value-for-money when commitment is low.

---

## 💡 Business Recommendations (Actionable & Practical)

### 🎯 Promote Long-Term Contracts
- Offer discounts or bundled services for 1-year and 2-year plans
- Clearly communicate long-term cost benefits

### 🎯 Strengthen Early Customer Onboarding
- Engage customers during the first 3–6 months
- Provide proactive support and follow-ups

### 🎯 Introduce Targeted Loyalty Pricing
- Identify high-risk, high-value customers
- Offer personalized retention incentives


---

## 📊 Expected Business Impact
If these strategies are implemented, the company can expect:
- Reduced churn among new and high-risk customers
- Increased customer lifetime value (CLV)
- Lower acquisition and marketing costs
- More stable revenue streams

---

## 🛠️ Tools & Technologies Used
- **SQL** – Data extraction, transformation, and validation  
- **Power BI** – Dashboarding and visual storytelling  
- **Excel** – Data validation and calculations  

---

## 📂 Project Assets
- Power BI Dashboard  
- SQL Queries  
- Dataset (if public)

---

## 🧠 Author Notes
This project prioritizes **business reasoning over tool complexity**.  
The objective was to understand **why churn occurs** and **how it can be reduced**, not just to visualize data.

---