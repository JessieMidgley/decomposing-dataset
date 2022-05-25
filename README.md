# decomposing-dataset

## Decompose dataset into 3NF
### Assignment Brief:
I am uploading a data set obtained from Kaggle (https://www.kaggle.com) in the "health data" portion of public data sets. 
The dataset is called Big City Health.  
It contains many fields that are compound fields (items munged together) when they are in fact separate (a violation of the Relational Model and Codd's Rules). 
Your assignment is to decompose the data into separate tables  that conform to 3NF and insert the data into SQLite tables in a schema that includes constraints (see: https://sqlite.org/foreignkeys.html). Decide on  the appropriate ON DELETE and ON UPDATE actions. 
You should create the entire schema and insert the data using R
Provide me with the Rmarkdown file that:

1. reads in the data
2. decomposes the compound keys
3. connects to a SQLite database (on file)
4. creates the appropriate schema and tables (DDL)
5. loads the data into the schema 
6. performs several joins such that each table is used at least once returning several lines from each join
7. 
I should be able to execute your R markdown file (.Rmd) by substituting in the location of the data file.
