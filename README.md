# Global-and-Crustacean-Fish-Export-and-Import
_Aquaculture and Fisheries_
# Introduction 

The Fisheries and Aquaculture industry is one of the industries with large data ranging over centuries which include seasonality, catch, culture, specie type, etc. all these data when analyzed can help generate insight to Improve this sector of any country's economy.
This current project focuses on the export and import of fish and crustaceans worldwide regarding value (dollar) and quantity for each country.



# Objective 
The objective is to enable users to interact with the dashboard to generate insight for the export and import of the fish and crustacean commodity guide towards data-driven decisions for stakeholders as well as anyone that might find this handy for their work. 
 
# Data Cleaning and Preprocessing 
<details><summary>More</summary>
The datasets for this project are gotten from [Kaggle.com] (https://www.kaggle.com/datasets/zhengtzer/global-fisheries-aquaculture-department?select=).
  ETL was carried out using PowerBI desktop. Headers were promoted, columns not needed were removed, appending of different tables. Column distribution and profiling was used to check for validity. In other to give further insight into this analysis another dataset titled Countries of the world is loaded into the query and the cleaning process was carried out on the dataset. Relationship between the four table was created in the data model. 
Before loading the data model, I made sure that only tables that were needed for visualization and analysis were loaded into the data model. 
  
  ![image](https://user-images.githubusercontent.com/108795960/198068727-842e0548-bd38-485b-8bf3-1124da235371.png)

</details>

 # Data Model
<details><summary>More</summary>
The data model Contains two tables which are Insight and Salary structure 
- The insight table contains: Employee ID, Gender, and Region 
- Salary structure contains Employee ID, Department, Basic salary, Bonus value, Total salary (Basic salary plus Bonus value).
- A one-to-one relationship was created between the two tables 

 ![image](https://user-images.githubusercontent.com/108795960/192601742-a1cf1b33-904a-4812-b24d-fe4c168fc66e.png)       
</details>

# Data Analysis and Visualization 

<details><summary>More</summary>
 
 - **Employee distribution by gender and region** 
 
There are 943 active employees on the company database, which shows that there are 24 male employees than female employees while the total number of the unspecified gender is 39. The region distribution also shows that Kaduna has more employees across the region with Lagos being the lowest. Consequently, total pay by region 
follows this same trend from Kaduna-Lagos.

![image](https://user-images.githubusercontent.com/108795960/192602811-fca82213-6923-4e85-b89e-0c1057025c19.png)
![image](https://user-images.githubusercontent.com/108795960/192603012-149bd7aa-8349-4f8e-a650-a5bb420f5c99.png)

- **Gender Distribution by Department** 
 
The result of the analysis indicates that there are more males in 7 of the 12 departments within the organization while the departments where female employees were more dominant are strategic departments within the organization.

![image](https://user-images.githubusercontent.com/108795960/192603146-194dc7e1-cafa-4aba-8904-3fc6de0f2ef3.png)

- **Gender Insight by Rating** 
 
There was more female in the top-rated categories than the other gender, it was also revealed from the analysis that more employee falls in the average category which is dominated by the male gender as well as the two least rated category. of the total 39 employees of the unspecific gender, 50% are rated average. 

![image](https://user-images.githubusercontent.com/108795960/192603236-cace9f1d-0920-49ad-94bf-26b4773b85f0.png)

- **Salary structure Gap by Gender**
 
Obvious gender gaps were observed in Accounting, Human Resources, and marketing with Unspecified earning more while the gap in Business Administration and Product Management department are more tended towards the male and female genders for the entire company. 

![image](https://user-images.githubusercontent.com/108795960/192603321-da9fe839-08cc-4dbc-9610-d5f514d5bc6f.png)

- **Regulatory Minimum Requirement**
 
A regulation that directs all manufacturing companies to pay a minimum of $90000 to its employee, the analysis shows that 69% of the company’s workforce are paid below the stipulated minimum amount 

![image](https://user-images.githubusercontent.com/108795960/192603392-4b6ce1f9-85f0-48aa-9738-bbf89f9f9e19.png)
</details>

# Recommendations 

• The analysis was able to determine that there were more male employees in the company in Lagos and Kaduna which is a tip to the regions where the alarm for patriarchy claims might be springing from that requires the immediate attention of the company in these regions 

• Rating insight and department distribution shows that more female gender occupy the top-rated category and more female employee are in top departments within the manufacturing company, something the company should also investigate before it escalates 

• Though the Unspecified gender constitutes a minute of the company’s employees, analysis of salary-shows they earn more in more than 50% of departments which is more pronounced in Kaduna.

[View Dashboard Here](https://app.powerbi.com/view?r=eyJrIjoiODcyMjA1MGMtMGJmNC00NTE1LWI2YzktNzZmMmQ5ZjliNjAwIiwidCI6IjA4MmY1ZjZjLWRmYmEtNGFiZS04M2Q1LTEzZmU1MWIzZTc2OSJ9&pageName=ReportSection2746c5225dfefd5b8c08) 


