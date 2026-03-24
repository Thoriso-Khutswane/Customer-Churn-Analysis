# Project Walkthrough:

## 1. Cleaned and Prepared data utilizing Microsoft Excel <br/>

- Converted text to columns:
  
![bar plot](https://github.com/Thoriso-Khutswane/Customer-Churn-Analysis/blob/main/images/TextToColumn.png)

- Checked and removed duplicates:

![bar plot](https://github.com/Thoriso-Khutswane/Customer-Churn-Analysis/blob/main/images/RemoveDuplicates.png)

- Handled missing values

![bar plot](https://github.com/Thoriso-Khutswane/Customer-Churn-Analysis/blob/main/images/HandleMissingValuesProcess(2).png)


- Performed exploratory analysis using Pivot Tables:

The table gave insights on which gender churns more

  ![bar plot](https://github.com/Thoriso-Khutswane/Customer-Churn-Analysis/blob/main/images/PivotTableCalculateChurnByGender(2).png)

  - VLOOKUP

   ![bar plot](https://github.com/Thoriso-Khutswane/Customer-Churn-Analysis/blob/main/images/VLOOKUPPROCESS.png)   


   ## 2. SQL Server Management Studio

   - Created a database:

  ![bar plot](https://github.com/Thoriso-Khutswane/Customer-Churn-Analysis/blob/main/CreatedDatabase.png)  

  - Imported a flat file into the database:

    ![bar plot](https://github.com/Thoriso-Khutswane/Customer-Churn-Analysis/blob/main/ImportProcess(2).png)

- Created Tables & Imported data into the Tables:

     ![bar plot](https://github.com/Thoriso-Khutswane/Customer-Churn-Analysis/blob/main/images/FactTable.png)

  ![bar plot](https://github.com/Thoriso-Khutswane/Customer-Churn-Analysis/blob/main/images/DimTables.png)


    ## 3. Microsoft Power BI

  - Executive Overview:
 
    ![bar plot](https://github.com/Thoriso-Khutswane/Customer-Churn-Analysis/blob/main/images/ExecutiveOverview2.png)

 **Model:**
    ![bar plot](https://github.com/Thoriso-Khutswane/Customer-Churn-Analysis/blob/main/images/ModelView%26Relationships.png)

  - Imported data from sql server to Power BI:
 
      ![bar plot](https://github.com/Thoriso-Khutswane/Customer-Churn-Analysis/blob/main/images/LoadedDataFromsqlserverToPowerbi.png)

  - Transformed Data:
 
    Used first rows as headers

   ![bar plot](https://github.com/Thoriso-Khutswane/Customer-Churn-Analysis/blob/main/images/UsedFirstColumnsAsHeaders.png)
  

  - Created a measure to calculate Total Number Of Customers
 
     ![bar plot](https://github.com/Thoriso-Khutswane/Customer-Churn-Analysis/blob/main/images/TotalCustomers.png)


    - Created a measure to calculate Churn Rate:
   


       ![bar plot](https://github.com/Thoriso-Khutswane/Customer-Churn-Analysis/blob/main/images/ChurnRate.png)
      
      
  - Created a measure to calculate Churned Customers:

      ![bar plot](https://github.com/Thoriso-Khutswane/Customer-Churn-Analysis/blob/main/images/ChurnedCustomer.png)
 
    

 - Created a measure to calculate (ARP)Average Revenue PerUser:
       
![bar plot](https://github.com/Thoriso-Khutswane/Customer-Churn-Analysis/blob/main/images/AverageRevenuePerUser.png)


 - Created a calculated column TO specify tenure group:

![bar plot](https://github.com/Thoriso-Khutswane/Customer-Churn-Analysis/blob/main/images/TenureGroupCalculatedColumn.png)

 
    
