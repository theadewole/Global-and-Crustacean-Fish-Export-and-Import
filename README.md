# Global-and-Crustacean-Fish-Export-and-Import
_Aquaculture and Fisheries_
# Introduction 

The Fisheries and Aquaculture industry is one of the industries with large data ranging over centuries which include seasonality, catch, culture, specie type, etc. all these data when analyzed can help generate insight to Improve this sector of any country's economy.
This current project focuses on the export and import of fish and crustaceans worldwide regarding value (dollar) and quantity for each country.



# Objective 
The objective is to enable users to interact with the dashboard to generate insight for the export and import of the fish and crustacean commodity guide towards data-driven decisions for stakeholders as well as anyone that might find this handy for their work. 
 
# Data Cleaning and Preprocessing 
The datasets for this project are gotten from [kaggle.com](https://www.kaggle.com/datasets/zhengtzer/global-fisheries-aquaculture-department?select=).
 ETL was carried out using PowerBI desktop. Headers were promoted, columns not needed were removed, appending of different tables. Column distribution and profiling was used to check for validity. In other to give further insight into this analysis another dataset titled [Countries of the world](https://www.kaggle.com/datasets/fernandol/countries-of-the-world) is loaded into the query and the cleaning process was carried out on the dataset. Relationship between the four table was created in the data model. 
Before loading the data model, I made sure that only tables that were needed for visualization and analysis were loaded into the data model. 
  
  ![image](https://user-images.githubusercontent.com/108795960/198068727-842e0548-bd38-485b-8bf3-1124da235371.png)

# Data Analysis and Visualization 

<details><summary>More</summary>
 
 - **Fish and Crustacean Trade Flow by value and Quantity** 
 
This visual represents the import and export of fish by value and quantity 

![image](https://user-images.githubusercontent.com/108795960/198079525-9c0025a7-1271-4ed0-8109-bc2bc141273e.png)
 ![image](https://user-images.githubusercontent.com/108795960/198079549-bfb5473a-3f83-4515-91dc-493c85b92ce7.png)
![image](https://user-images.githubusercontent.com/108795960/198079568-dfdb5398-13fa-4362-bb88-d7fe8641db72.png)
![image](https://user-images.githubusercontent.com/108795960/198079592-26f0ff99-c298-4c86-833c-066e0858a768.png)





- **Year analysis by Quantity and Value** 
 
Year analysis by Quantity and Value 
This visual represents the yearly analysis across the year covered in this analysis regarding value and quantity with respect to trade flow (import and export)
 
![image](https://user-images.githubusercontent.com/108795960/198080055-f84573af-6da3-4365-ac6c-3b1fb6185d52.png)
 ![image](https://user-images.githubusercontent.com/108795960/198080081-58d9f9a1-8e01-4614-9ed9-90c543d3be47.png)





- **Top countries by value and Quantity**
 
The visual gives insight on the top countries in this by value and quantity which can be further distilled by trade flow.
 
![image](https://user-images.githubusercontent.com/108795960/198080370-75995e01-9a6b-4ad0-b877-3cc69146dfee.png)
 ![image](https://user-images.githubusercontent.com/108795960/198080405-1ee4de4c-7017-4cb6-bdda-023c9e3f5276.png)


- **Global pool**
  
This visual gives insight in the similitude of the ocean of fish and crustacean and show individual country performance by how big the individual element of the visual represent
 
 ![image](https://user-images.githubusercontent.com/108795960/198080482-809c2729-4fef-4ccb-a7b7-603b3f1204d6.png)
 ![image](https://user-images.githubusercontent.com/108795960/198080509-f293222c-b3ce-43be-a1ab-db5e22513533.png)




[View Dashboard Here](https://app.powerbi.com/view?r=eyJrIjoiODcyMjA1MGMtMGJmNC00NTE1LWI2YzktNzZmMmQ5ZjliNjAwIiwidCI6IjA4MmY1ZjZjLWRmYmEtNGFiZS04M2Q1LTEzZmU1MWIzZTc2OSJ9&pageName=ReportSection2746c5225dfefd5b8c08](https://app.powerbi.com/view?r=eyJrIjoiNDIzZjcwODYtN2YxZC00OGE1LWFlNTktMDZiNzQwZDVmNDc0IiwidCI6IjA4MmY1ZjZjLWRmYmEtNGFiZS04M2Q1LTEzZmU1MWIzZTc2OSJ9&pageName=ReportSection65eee980b42e09ad8213)) 


