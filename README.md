# Customer Churn Analysis & Business Intelligence Dashboard


## 🧠Industry :Telecommunications (Subscription-Based Services)

## 📌Overview
This repository showcases my skills in Power BI, SQL, SSMS, and Excel, and demonstrates my ability to apply these tools effectively in conducting data analysis within the telecommunications sector, specifically for subscription‑based services.

## 📌 Business Problem

The company is steadily losing customers, which is causing revenue to drop and reducing how much value each customer brings over time. At the moment, the business doesn’t have a clear view of who is leaving or why they are leaving.Because of this lack of information, the company cannot create effective plans to keep customers or predict which customers might leave next.

## 🎯 Project Objective

The goal of this project is to analyze customer data and uncover patterns behind customer churn. By leveraging SQL, Excel, and Power BI, this project transforms raw data into actionable insights that support business decision-making.

## 🔄 Project Workflow (End-to-End)

![bar plot](https://github.com/Thoriso-Khutswane/Customer-Churn-Analysis/blob/main/images/Project%20Workflow%20(End-to-End)2.png)

## 🧹 Data Preparation (Excel)

The dataset was cleaned and prepared using Excel:

- Converted Text To Cloumns
- Checked and removed duplicates
- Handled missing values
- Standardized column formats
- Performed exploratory analysis using Pivot Tables
  
**Check walkthrough for details**

- Clean Dataset:

  ![bar plot](https://github.com/Thoriso-Khutswane/Customer-Churn-Analysis/blob/main/images/CleanTable.png)


## 🗄️ SQL Server Management Studio

A structured data model was developed using a star‑schema approach. Working from the raw dataset downloaded from Kaggle (WA_Fn‑UseC_-Telco‑Customer‑Churn), I transformed the data and created three analytical tables to support efficient reporting and analysis.

- Created a **DimCustomer** Table:
  
👉 This stores descriptive info about customer

 ```sql
  CREATE TABLE DimCustomer (
      CustomerID VARCHAR(50),
      Gender VARCHAR(10),
      SeniorCitizen INT,
      Partner VARCHAR(10),
      Dependents VARCHAR(10)
      );

```


✅ Inserted Data into Dimcustomer Table

 ```sql
   CREATE TABLE DimCustomer (
    CustomerID VARCHAR(50),
    Gender VARCHAR(10),
    SeniorCitizen INT,
    Partner VARCHAR(10),
    Dependents VARCHAR(10)
);

 ```

- Created a **DimContract** Table:
  
👉 This stores contract-related info 

 ```sql
  CREATE TABLE DimContract (
    CustomerID VARCHAR(50),
    Contract VARCHAR(50),
    PaymentMethod VARCHAR(50),
    InternetService VARCHAR(50)
);
  ```

✅ Inserted Data into DimContract Table

 ```sql
CREATE TABLE DimContract (
    CustomerID VARCHAR(50),
    Contract VARCHAR(50),
    PaymentMethod VARCHAR(50),
    InternetService VARCHAR(50)
);
 ```

- Created **FactCustomerActivity** Table:

👉 This table holds measurable data

```sql
  CREATE TABLE FactCustomerActivity (
    CustomerID VARCHAR(50),
    MonthlyCharges FLOAT,
    Tenure INT,
    Churn VARCHAR(10)
);
  
```

✅ Inserted Data into Fact Table

```sql
INSERT INTO FactCustomerActivity (CustomerID, MonthlyCharges, Tenure, Churn)
SELECT 
    CustomerID,
    MonthlyCharges,
    tenure,
    Churn
FROM Customers;

```


**This structure separates transactional data from descriptive attributes, improving analytical performance and scalability.**
  

## 📊 Power BI Dashboard

The SQL database was connected to Power BI to build an interactive dashboard.

Connected Power BI to SQL Server to extract vulnerability and asset inventory data for analysis. I followed a star-schema approach to model my data improving analytical performance and scalability.

- Star Schema Model:
  
  ![bar plot]()

- Dashboard Overview:

  ![bar plot]()
  

  
