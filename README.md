# Cryptocurrency-Database-Tool
Utilizing Binance's API to perform ETL into personal SQL database. 

Cryptocurrency Database Tool.ipynb:
Performs the ETL. Updates the database with the most recent data by deleting the last existing day of data then updating with fresh data ranging from the deleted day to the current day. 

Cryptocurrency Database Results.ipynb:
Loads the data processed from the database tool and graphs with the 8 day and 21 day exponential moving averages along with the volume. 

The data has been stored and is ready for use in machine learning algorithms algorithms. I have applied feature analysis, linear regression and XGBoost but have not been able to print free money yet. 

Below is the set up of the PostgreSQL server on my personal computer
<img width="1040" alt="PorstegeSQL Screenshot" src="https://user-images.githubusercontent.com/101516958/159086477-c1ba7bbc-4663-419f-9aa1-2fab9fcf8836.png">

Below is the output of Cryptocurrency Database Results.ipynb
<img width="1040" alt="Crypto Screenshot" src="https://user-images.githubusercontent.com/101516958/159090239-e28f3b02-4502-4948-b6bf-29daf3217463.png">


