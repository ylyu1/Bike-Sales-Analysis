# Excel-Projects

## **Purpose**
In this project, we want to build an excel dashboard to analyze the information of customers who are buying or not buying bikes from a company.

## **Data source**
The data source is a csv file that has information on customers' gender, income, commute distance, education, occupation, etc.
<img src="https://user-images.githubusercontent.com/103335114/202567965-a50ac20e-978e-42c8-b5e8-064b9707a60d.png" width=80% height=80%>

## **Data cleaning in excel**
- We want to create a new working sheet in the same workbook while keeping and referring to the original one.
- We want to first remove the duplicates rows in the working sheet by using the “removing duplicates” function. We have 26 duplicate found and removed. 
-  For the “Marital Status” and the “Gender” column, the S/M and F/M values are vague. We want to clarify them to Single/Married and Female/Male, respectively. So we select each of the two columns and apply the “find and replace” function.
- For the “Age” column, there are too many individual ages. For easier visualization, we want to add a “Age Brackets” column to categorize these individual ages. Using the if() function, we set ages older than 60 as “old”; ages younger than 60 but older than 40 as “middle age”; ages younger than 40 but older than 18 as “young adult”.
![cleaneddata](https://user-images.githubusercontent.com/103335114/202569438-8e9450a1-9a38-4f37-8249-10319775cba8.png)

