
# Applied Data Analytics

## Wedge Project


### Task 1

* Files for this task: 

wedge_proj_1.ipynb

Loads all data into GBQ data set.


### Task 2

* Files for this task: 

wedge_proj_2.ipynb

Runs a query from the database you just uploads to pull a query of owners. Then take a random sample of those owners!
	

### Task 3

* Files for this task: 

wedge_proj_3.ipynb

Using the GBQ Database, run 3 queries that...

1. Sales by date by hour: By calendar date (YYYY-MM-DD) and hour of the day, determine the total spend in the store, the number of transactions, and a count of the number of items .

2. Sales by owner by year by month: A file that has the following columns: card_no, year, month, sales, transactions, and items.

3. Sales by product description by year by month: A file that has the following columns: upc, description, department number, department name, year, month, sales, transactions, and items. You will submit your Python code that builds the database.



## Query Comparison Results

Fill in the following table with the results from the 
queries contained in `gbq_assessment_query.sql`. You only
need to fill in relative difference on the rows where it applies. 
When calculating relative difference, use the formula 
` (your_results - john_results)/john_results)`. 



|  Query  |  Your Results  |  John's Results | Difference | Rel. Diff | 
|---|---|---|---|---|
| Total Rows  |80867675|   |   |   |
| January 2012 Rows  |1070907   |   |   |   |
| October 2012 Rows  |1042287   |   |   |   |
| Month with Fewest  |September   |   | Yes/No  | NA  |
| Num Rows in Month with Fewest  | 5964994  |   |   |   |
| Month with Most  |May   |   | Yes/No  | NA  |
| Num Rows in Month with Most  |7578372   |   |   |   |
| Null_TS  |6306918   |   |   |   |
| Null_DT  |0   |   |   |   |
| Null_Local  |221434   |   |   |   |
| Null_CN  |0   |   |   |   |
| Num 5 on High Volume Cards  |14987   |   | Yes/No  | NA  |
|  Num Rows for Number 5 |431931  |   |   |   |
| Num Rows for 18736  |11651   |   |   |   |
| Product with Most Rows  |banana organic   |   | Yes/No  | NA  |
| Num Rows for that Product  |857274   |   |   |   |
| Product with Fourth-Most Rows  |avocado hass organic   |   | Yes/No  | NA  |
| Num Rows for that Product  |439828   |   |   |   |
| Num Single Record Products  |2798   |   |   |   |
| Year with Highest Portion of Owner Rows  |2014   |   | Yes/No  | NA |
| Fraction of Rows from Owners in that Year  |.759   |   |   |   |
| Year with Lowest Portion of Owner Rows  |2011   |   | Yes/No  | NA |
| Fraction of Rows from Owners in that Year  |.737   |   |   |   |

## Reflections

The wedge was an interesting process of uploading and manipulating large datasets. I thought the process as a whole definitely sets me up to be able to comfortably manage my own datasets (when I have one) and be able to run any tests to pull out data. I really enjoyed the relationship between python and GBQ, from testing queries in GBQ and then running them in python into a data frame was quite unique. Overall I enjoyed the process as a whole, even though it was tedious at times.
