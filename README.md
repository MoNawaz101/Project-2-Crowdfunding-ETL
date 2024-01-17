# Project 2 - Crowdfunding ETL  
## Task
For the ETL mini project, as a group we practiced building an ETL pipeline using Python, Pandas, and either Python dictionary methods or regular expressions to extract and transform the data. After the data  
has been transformed we created four CSV files and used the CSV file data to create an ERD and a table schema. Finally, the CSV file data was uploaded into a Postgres database.

## Directory Structure

The root folder contains all the Jupyter Notebook and Database files

The root also contains to folder for the output CSV files;  
-[Resources](Resources)   
Contains the 2 original starting XLS files and the outputted CSV file from the Jupyter Notebook files
-[Crowdfunding Database output files](Crowdfunding%20Database%20Outputs)
Contains the 4 output results from the database query of each table


## Jupyter Notebook files
[ETL_Mini_Project_MNawaz_EAlton_KKhan_Starter_Code.ipynb](ETL_Mini_Project_MNawaz_EAlton_KKhan_Starter_Code.ipynb)  
- Completed file which does the following:
  - Loads the original excel files provided as starter code,  [crowdfunding.xlsx](Resources/crowdfunding.xlsx) and [contacts.xlsx](Resources/contacts.xlsx)
  - Create the category and subcategory dataframes and exports as two csv files, [category.csv](Resources/category.csv) and [subcategory.csv](Resources/subcategory.csv)
  - Create the campaign dataframe, and output as [campaign.csv](Resources/campaign.csv)
  - Create the contacts dataframe, and ouput a s [contacts.csv](Resources/contacts.csv)

[ETL_Mini_Project_MNawaz_Starter_Code.ipynb](ETL_Mini_Project_MNawaz_Starter_Code.ipynb)
- Working file for M. Nawaz to produce the category, subcategory and contacts dataframes and export them as CSV files,  [category.csv](Resources/category.csv), [subcategory.csv](Resources/subcategory.csv) and [contacts.csv](Resources/contacts.csv)

[ETL_Mini_Project_EAlton_Starter_Code.ipynb](ETL_Mini_Project_EAlton_Starter_Code.ipynb)
- Working for E. Alton in order produce the campaign dataframe and to export the data to [campaign.csv](Resources/campaign.csv)

[contacts_df.ipynb](contacts_df.ipynb)
- Working file for K. Khan for the purpose of producing the contacts dataframe.


## Database files  
[crowdfunding_db_ERD.png](crowdfunding_db_ERD.png)  
- ERD diagram to show the relationships between the four tables

[crowdfunding_db_schema.sql](crowdfunding_db_schema.sql)  
- Table schema for the database creates the four tables (category, subcategory, contacts and campaign)

[crowdfunding_queries.sql](crowdfunding_queries.sql)
- Simple queries which select the data from each of the tables. These output the csv files in the [Crowdfunding Database Outputs](Crowdfunding Database Outputs) folder


  

