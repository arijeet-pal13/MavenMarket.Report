# MavenMarket.Report

### Extract, Tranform & Load Data
To add a data source, go to the Get data option. Then, select the data source you want to connect and click the Connect button. Connect to following data from the Dataset file.

* MavenMarket_Calendar.csv
* MavenMarket_Customers.csv
* MavenMarket_Products.csv
* MavenMarket_Stores.csv
* MavenMarket_Transactions_1997.csv
* MavenMarket_Transactions_1998.csv

In Power Query Editor Transform all the data as needed. Load the data in Power BI

### Data Model
In the Relationship tab, you can see the relationship between data sources. When you add multiple data sources to Power BI visualization, the tool automatically tries to detect the relationship between the columns. When you navigate to the Relationship tab, you can view the relationship. You can also create a Relationship between the columns using Create Relationships option.

Here the relationship between tables is called 'Star Schema'. Star schema is a mature modeling approach widely adopted by relational data warehouses. It is classified into fact table & dimension tables. In this model Sales and Return table are fact tables. Others table are dimension table.

![image](https://github.com/arijeet-pal13/MavenMarket.Report/assets/84266230/aebc8825-9e99-4df6-9b99-166f94e39445)


### Creating Report

* From this page we can see Monthly Transaction,Profit,Return By Product_Brand and Location. Also see the Weekly Revenue Trend and Revenue Vs Target charts.
    
![image](https://github.com/arijeet-pal13/MavenMarket.Report/assets/84266230/b5092067-b677-4fb6-a2c6-d84713bdc324)

* This is a ToolTip Page. It is used to add some extra information in our visuals.

![image](https://github.com/arijeet-pal13/MavenMarket.Report/assets/84266230/61eea627-f873-4cc3-aa36-ab35d444ba33)
