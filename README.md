# befeni-test
There will be two projects which written in C# and build as console application.  Please find below instruction on how to configure and run them.
Both projects will require visual studio to run the projects.

# Advanced Test
This project is desgined to read /write to multiple data sources which I simulate database as csv files.  

- The configuration for connection string can be founded under Config folder.  
- Data folder contains csv files which serve data and the output file is generated under Project folder -> bin -> Debug -> Data.
- The FileHelper class contains a method to connect to any database. If you want to test with your local database, please add your connection string to the config file.
- The console app will continue running with the following test
    - Get existing shirt order by id
    - Get non existing shirt order using id.
    - Get all shirt orders.
    - Update shirt orders to all data sources.
    - Delete shirt orders from all data sources.

# Basic Test
Please find Data folder which you can edit input data and run it.
