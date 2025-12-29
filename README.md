# -Portfolio-Project-1---SQL-and-Power-BI---Adventure-Works

Welcome to my first portfolio project. In this data cleaning, analysis and visualisation project, I clean the AdventureWorks dataset with SQL, then visualise it as an interactive 3-page dashboard with PowerBI and also export a static version of the dashboard as a PDF.

Project Guide

The 4 CSV data tables are the output of the SQL queries, where I clean the tables by sorting and exporting only those columns which are needed for visualisation in PowerBI.

Once the cleaned data tables have been exported as CSVs, I import the 4 CSVs and the Excel worksheet into Power BI, where I link the tables together in the "Model" side tab:

portfolio_1-image-data_model

I then further process the data in Power Query ("Transform data" on the Home tab), renaming columns, changing columns' data type etc. and bring the columns into a format suitable for visualisation.

Finally, I visualise the data as an interactive 3-page dashboard in PowerBI. I also export a static version of the dashboard as a PDF.

Page 1 - AdventureWorks Sales Overview

portfolio_1-image-adventure_works_1

Page 2 - Sales by Customer

portfolio_1-image-adventure_works_2

Page 3 - Sales by Product

portfolio_1-image-adventure_works_3

Project Files

There are 3 project files (1 SQL, 1 PowerBI and 1 PDF) and 5 data table files (4 CSVs and 1 Excel Worksheet) in this repository.

I am unable to upload the full "AdventureWorks Data Warehouse version 2019" file (99 MB) here on my GitHub due to file size limit of 25 MB. Here is the download link to the original dataset on Microsoft's GitHub: .bak (Original Microsoft Learn link is available in my SQL script file.)

This file is in backup file format (.bak) so I went into Microsoft SQL Server Management Studio and restored the backup file, allowing access to the full dataset. I then ran this SQL script by TechTalkCorner to update some columns like dates in the dataset:
With that, I began my SQL querying and analysis.

Future Project Aim

In addition to SQL and R, I have now started learning Python. Once I improve my Python knowledge sufficiently, I aim to set up and automate this process as a system, where data is pulled from a database, cleaned and organised into a format suitable for visualisation, visualised in a dashboard, the dashboard is exported as a PDF and the PDF is emailed to concerned stakeholders automatically.

The entire process should be autonomous and require almost zero human attention, with the exception of regular checks to verify the proper functioning of the process and the accuracy of the results.

Statement to self - New Year's Resolution: As of January 2023, I intend to achieve this level of proficiency in Python (and if possible, complete this full project and upload here to GitHub) at most within the end of 2023, allowing for unforeseen constraints, though I hope to achieve it sooner.
