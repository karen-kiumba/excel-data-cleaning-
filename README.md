 Project: Cleaning data using excel	
 ![image alt](https://github.com/karen-kiumba/excel-data-cleaning-/blob/6da512d54eeeaf4aaf6474167e4ec04976558d0a/before.png)
 ![image alt](https://github.com/karen-kiumba/excel-data-cleaning-/blob/6da512d54eeeaf4aaf6474167e4ec04976558d0a/after.png)
														
Project overview: The purpose of the project is to convert a raw, messy and unstructured dataset into a clean and consistent one suitable for analysis														
														


The workbook contains: 

   sheet 1: audit trail 													

   sheet 2: raw data

   sheet 3: cleaned data
														



Tools used: Microsoft Excel														
														
														


Steps followed:	

step 1: The original raw data is duplicated into a new sheet. This is done for the purpose of refering to the original data at a later date.														

step 2: The whole dataset in sheet 2 is selected and duplicates removed.														

step 3: The column names are re-named to ensure that they are clear and understandable. cust is renamed to Customer_ID, Name is renamed to Customer_Name, Age is renamed to Customer_Age,          Gender remains as Gender, marital stat is renamed to Marital Status, Pur Date is renamed to Purchase_Date, Amt is renamed to Amount, Location remains as Location.														

step 4: A new column is inserted next to the Customer_ID column. In the new column, the function TRIM() is used to clean the original Customer_ID column. The new Customer_ID column is            copied then pasted as values. The original messy Customer_ID column is then deleted.

step 5: For the Customer_Name column, the process in step 4 is repeated but this time, TRIM(PROPER()) is used to clean the column.														

step 6: The Customer_Age column has a mixture of number and text entries. The filter option is used and text entries identified. Find and replace option is then used to find and replace          the text entries with the corresponding numerical entry.

step 7: The Gender column has a mixture of Male, Female, M, F. This needs to be corrected. Find F and replace with Female. Find M and replace with Male. (click the match entire cell              contents option)

step 8: Marital Status column has three different unique entries. It has Marrd, Single, Sungle. Marrd and Sungle are typing errors. This needs to be fixed. Find Marrd and replace with            Married. Find Sungle and replace with Single.

step 9: The Purchase_Date column has a lot of inconsistencies. Text to column option in the data tab is used to fix this.

step 10: A new column is inserted next to the Location column. In the new column, the function PROPER() is used to clean the original Location column. The new Location column is copied            then pasted as values. The original Location column is deleted.

step 11: Missing values were dealt with by finding empty space and replacing with N/A. Alternatively, use COUNTBLANK() to find number of missing values in a row. If a row has too many             missing values, do away with the row completely.

step 12: The final dataset was made more presentable by adding gridlines, filling the header row and readjusting column width using (alt, h, o, i)														
														

Project Outcome:														
A clean and consistent dataset that is ready for analysis														
														
														
