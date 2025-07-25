# 📉 Customer Churn Analysis | Power BI

This project explores customer churn behavior through interactive Power BI dashboards using a structured Excel dataset. The goal is to identify trends, key churn drivers, and insights to improve customer retention.

---

## 📊 Project Overview

Customer churn is a critical KPI for any business. This project analyzes churn patterns among customers based on various dimensions such as credit card status, geography, age, gender, and credit scores. The dashboard provides powerful visualizations to help decision-makers quickly spot at-risk segments.

---

## 🛠️ Tools Used

- **Power BI** – for data modeling and dashboard development
👉 [Dashboard_1 Screenshot](./Dashboard_1.png)
👉 [Dashboard_2 Screenshot](./Dashboard_2.png)
- **Microsoft Excel** – for storing and preparing the dataset
👉 [Datasets File](./Datasets/)

---

## 📂 Dataset Description

The Excel dataset consists of multiple related tables structured in a star schema model:

| Table Name        | Columns                                           |
|------------------|----------------------------------------------------|
| `CustomerInfo`    | `CustomerID`, `Surname`                           |
| `ActiveCustomer`  | `ActiveID`, `ActiveCategory`                      |
| `ExitCustomer`    | `ExitID`, `ExitCategory`                          |
| `CreditCard`      | `CreditID`, `Category`                            |
| `Geography`       | `GeographyID`, `GeographyLocation`               |
| `Gender`          | `GenderID`, `GenderCategory`                      |
| `Date Master`     | `Date`, `Month`, `Month Order`, `Year`           |
| `Bank_Churn`      | `CustomerID`, `Age`, `Balance`, `CreditScore`, `Bank DOJ`, `Exited`, `EstimatedSalary`, `GenderID`, `CreditID`, `ExitID`, `GeographyID`, `ActiveID`

---

## 🗂️ Schema Diagram

Here is the schema used for data modeling in Power BI:

![image](https://github.com/user-attachments/assets/02336bf6-d2bf-4cfa-84dc-0357ed8ff0c3)

 
<sup>*ERD showing relationships among dimension and fact tables*</sup>

---

## ❓ Key Business Questions Answered

- What is the total churn rate and retention rate?
- What’s the trend of churn over different years and months?
- Which gender has a higher exit rate?
- Do credit card holders churn less than non-holders?
- Which credit score categories are more prone to churn?
- How does churn vary by geography (France, Germany, Spain)?
- What age group has the highest retention?

---

## 📊 Power BI Dashboard

### 1. **Customer Churn Analysis Overview Dashboard**

![image](https://github.com/user-attachments/assets/2fb36cde-c16f-4d2b-a03e-f8bf66609695)


### 2. **Customer Retention & Exit Trends Dashboard**

![image](https://github.com/user-attachments/assets/7737a2f2-7b51-4bd3-9e80-0c76470e9312)


---

## 🔍 Key Insights

- **Churn Rate**: ~20% of customers exited the service.
- **Retention**: 7,963 out of 10,000 customers retained.
- **Credit Card Impact**: Non-credit card holders account for a larger portion of churn.
- **Geography**:
  - France has the highest number of exited customers.
  - Germany and Spain have better customer retention.
- **Age Factor**: Most churn occurred between ages 30–45.
- **Gender**: Slightly more female customers exited compared to males.
- **Credit Score**: Customers with "Fair" and "Poor" scores churned the most.

---

## ✅ Conclusion

This dashboard enables business teams to:

- Understand customer churn behavior by multiple dimensions  
- Take targeted actions to retain at-risk segments  
- Optimize services and offers based on churn indicators  
- Support data-driven decisions with real-time visual insights

---

---

## 📬 Contact

**Author**: Mohan Kumar  
**Mail**: mohan122000kumar@gmail.com

---

⭐ *Feel free to fork or star this repo if you found it useful!*

