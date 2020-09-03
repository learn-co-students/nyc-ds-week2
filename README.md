# Phase 1 Review

For this review session, we will be accessing the `stocks.db` sqlite database. The database is located within the [data/](data/) folder in this repo. 

<u>This database contains three tables.</u>
1. open
2. date
3. company


| Table Name | Description                                         |
|:------------|:-----------------------------------------------------|
|`open`       | Contains the opening price for a stock.        |
|`date`       | Contains the date of a given stock price.   |
|`company`    | Contains the company name for a given stock. |

> This database was created using Kaggle's [S&P 500 Stock Dataset](https://www.kaggle.com/camnugent/sandp500). The code for creating this database can be reviewed [here](src/create_db.py)