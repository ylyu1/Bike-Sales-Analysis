# Bike Sales Analysis

## Purpose
In this project, we want to build an excel dashboard to analyze the information of customers who are buying or not buying bikes from a company.

## Data source
The data source is a csv file that has information on gender, income, commute distance, education, occupation, etc.
<img src="https://user-images.githubusercontent.com/103335114/202567965-a50ac20e-978e-42c8-b5e8-064b9707a60d.png" width=100% height=100%>

## Data cleaning in Excel
- We want to create a new working sheet in the same workbook while keeping and referring to the original one.
- We want to first remove the duplicates rows in the working sheet by using the “removing duplicates” function. We have 26 duplicate found and removed. 
-  For the “Marital Status” and the “Gender” column, the S/M and F/M values are vague. We want to clarify them to Single/Married and Female/Male, respectively. So we select each of the two columns and apply the “find and replace” function.
- For the “Age” column, there are too many individual ages. For easier visualization, we want to add a “Age Brackets” column to categorize these individual ages. Using the if() function, we set ages older than 60 as “old”; ages younger than 60 but older than 40 as “middle age”; ages younger than 40 but older than 18 as “young adult”. <img src="https://user-images.githubusercontent.com/103335114/202569438-8e9450a1-9a38-4f37-8249-10319775cba8.png" width=100% height=100%>


## Data manipulation in Excel
We created pivot tables with charts based on different data combinations. These pivot tables will be added into the bike sales dashboard to browse the  customer information. <img src="https://user-images.githubusercontent.com/103335114/202571992-6c44796b-6204-4b5e-b05a-73650c4c4661.png" width=100% height=100%>

## Dashboard with slicers
By adding the slicers, we can check the customers information with more details. <img src="https://user-images.githubusercontent.com/103335114/202572220-90b225ed-5ef3-4b9b-95f7-5fc3cb0fa397.png" width=100% height=100%>
