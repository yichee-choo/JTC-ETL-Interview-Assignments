Instructions

Candidates can choose 1 set of tools from the following to implement the task. Candidates can then choose to use a combination or only a single tool from that set.
Set A. Apache Kafka, Nifi, HDFS, Hive
Set B. Talend (Open Source), MongoDB
For verification purpose, we need the candidate to document the implemented steps in your github repository for us to set up the same environment as yours that will achive the same result as below.


Task

Implement a data flow orchestration to process raw data to generate pipe-delimited load files in the path (/dataextract/yy/MM/dd/factstore).
Then, load the processed data model into a nosql database (name it factstore) for querying the results to achieve the expected results (see sample DDL-DML.sql to create corresponding data structure in nosql database).

Pipe-delimited Data Schema
DateID: date (yyyy-MM-dd)
StoreID: Int
ProductID: Int
OnHandQty: Int
OnOrderQty: Int
DaysInStock: Int
MinDayInStock: Int
MaxDayInStock: Int

Expected Result #1: Query average number of stocks on hand by category.
Audio: 21
Cameras and camcords: 20
Cell phones: 62
Computers: 21
Games and Toys: 75
Home Appliances: 20
Music, Movies and Audio Books:
TV and Video: 20

Expected Result #2: Query average number of stocks on hand by store.
Catalog: 59
Online: 47
Reseller: 37
Store: 24
