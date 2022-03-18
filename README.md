# Cryptocurrency-Database-Tool
Utilizing Binance's API to perform ETL into personal SQL database. 

Cryptocurrency Database Tool.ipynb:
Performs the ETL. It is written to be able to update the database with the most recent data by deleting the last existing day of data and updating with data ranging from the deleted day to the current day. 

Cryptocurrency Database Results.ipynb:
Loads the data from the database and graphs with the 8 day and 21 day exponential moving averages along with the volume. 

The data has been stored and is ready for use in machine learning algorithms algorithms. I have applied feature analysis, linear regression and XGBoost but I have not been able to print free money yet. 

Below is the set up of the PostgreSQL server on my personal computer
<img width="1040" alt="PorstegeSQL Screenshot" src="https://user-images.githubusercontent.com/101516958/159086477-c1ba7bbc-4663-419f-9aa1-2fab9fcf8836.png">

Below is the data processed
![Crypto Graph Results](https://user-images.githubusercontent.com/101516958/159086830-3928f013-f01a-4de7-8f9d-fbde655391e4.png)

