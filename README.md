Instructions
As a hands on Assignment, you will be working on a real world dataset provided by the Chicago Data Portal. 
Imagine, you have been hired by a non-profit organization that strives 
to improve educational outcomes for children and youth in the City of Chicago. 
Your job is to analyze the census, crime, and school data for a given neighborhood or district. 
You will identify causes that impact the enrollment, safety, health, environment ratings of schools.

You will be asked questions that will help you understand the data just like a data analyst or data scientist would. 
You will be assessed both on the correctness of your SQL queries and results.

A Python based Jupyter notebook has been provided to help with completing this assignment. 
Follow the instructions to complete all the problems. Then share the Queries and Results with your peers for reviewing.


Step-By-Step Assignment Instructions
Assignment Topic:
In this assignment, you will download the datasets provided, load them into a database, write and execute SQL queries to answer the problems provided, and upload a screenshot showing the correct SQL query and result for review by your peers. A Jupyter notebook is provided in the preceding lesson to help you with the process.

This assignment involves 3 datasets for the city of Chicago obtained from the Chicago Data Portal:

1. Chicago Socioeconomic Indicators
This dataset contains a selection of six socioeconomic indicators of public health significance and a hardship index, by Chicago community area, for the years 2008 – 2012.

2. Chicago Public Schools
This dataset shows all school level performance data used to create CPS School Report Cards for the 2011-2012 school year.

3. Chicago Crime Data
This dataset reflects reported incidents of crime (with the exception of murders where data exists for each victim) that occurred in the City of Chicago from 2001 to present, minus the most recent seven days.

Instructions:
1. Review the datasets

Before you begin, you will need to become familiar with the datasets. Snapshots for the three datasets in .CSV format can be downloaded from the following links:

Chicago Socioeconomic Indicators: Click here

Chicago Public Schools: Click here

Chicago Crime Data: Click here

NOTE: Ensure you have downloaded the datasets using the links above instead of directly from the Chicago Data Portal. The versions linked here are subsets of the original datasets and have some of the column names modified to be more database friendly which will make it easier to complete this assignment. The CSV file provided above for the Chicago Crime Data is a very small subset of the full dataset available from the Chicago Data Portal. The original dataset is over 1.55GB in size and contains over 6.5 million rows. For the purposes of this assignment you will use a much smaller sample with only about 500 rows.

2. Load the datasets into a database

Perform this step using the LOAD tool in the Db2 console. You will need to create 3 tables in the database, one for each dataset, named as follows, and then load the respective .CSV file into the table:

CENSUS_DATA

CHICAGO_PUBLIC_SCHOOLS

CHICAGO_CRIME_DATA
