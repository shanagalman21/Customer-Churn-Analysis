# Customer Churn Analysis

## **Project Description**  
This project analyzes customer churn for a telecom company using a dataset of **6,418 records**. It involves data extraction, transformation, and loading (**ETL**) in SQL, followed by **data visualization and analysis** through dashboard creation in Power BI. A **machine learning model** in Python is also implemented to predict customer churn, helping identify at-risk customers.  

## **Project Workflow**  

### **1. ETL Process in SQL Server**  
- Handled **null values** and corrected **data types** for accuracy and consistency.  
- Stored the **cleaned dataset** into a new table.  
- Created **two additional views** for use in the dashboard and prediction model.  

### **2. Data Preparation and Visualization in Power BI**  
- Customer churn data was analyzed based on:  
- **Demographics:** Age and gender of customers
- **Geographic distribution:** Churn trends by location   
- **Payment & account details:** Contract type, payment method, and tenure  
- **Services:** Internet type and services availed
- Visualized the findings into a dashboard to highlight trends in customer churn.  

### **3. Churn Prediction Model**  
A **Random Forest Classifier** was implemented to predict customer churn. The dataset was preprocessed, split into training (80%) and testing (20%) sets. The model was trained on key customer attributes and evaluated using a confusion matrix and classification report to assess accuracy. Finally, the trained model was used to **predict customer churn**, with results visualized for further analysis.  

## **Key Findings**  
- 1,732 out of 6,418 customers have churned **(27% Churn Rate)** 
- **Jammu (57.2%) and Assam (38.1%)** have the highest churn rates by state.  
- Female customers **(64.15%)** are more likely to churn than male customers **(35.85%)**.  
- Customers aged 50+ **(31%)** have the highest churn rate among all age groups with.  
- Month-to-month contracts **(46.5%)** have the highest churn rate among contract types.  
- Fiber optics users **(41.1%)** churn the most.  
- **378 additional customers** are predicted to churn.  
