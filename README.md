# Building-a-database-for-crime-reports
Building a database for crime reports

I've been learning about postgres recently and in this project, I just want to put everything together to build a database for storing data related to crimes that occurred in Boston. This dataset is available in the file boston.csv.

The goal of this project is to create a database named crimes_db with a table – boston_crimes – with appropriate datatypes for storing the data from the boston.csv file. I will be creating the table inside a schema named crimes. I will also create the readonly and readwrite groups with the appropriate privileges. Finally, I will also need to create one user for each of these groups.

The following diagram illustrates a high-level overview of what I want to achieve:

postgres%20db%20diag.png

I will start by creating a database for storing our crime data as well as a schema for containing the tables. Inside this database, I will create a schema to keep my data organized.
