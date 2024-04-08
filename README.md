# Advanced Data Management 

- A1

Based on the Data Analysis provided on the DVD rental database. I decided to create a business report for the total weekly sales. The sales will be ordered by earliest to latest date. The total amount per week and beginning week dates are added to the column
 
- A2

Four table from the database were incorporated. The 'store_id' utilized an integer type, since each store is identified by either '1' or '2'. The 'payment_date' is identified by TIMESTAMP, YYYY-MM-DD for when the payment was received. The 'amount' included only the last two decimal places, for the purchase of the rental. The 'rental' table includes 'rental_id' as an INT to show the unique identifier for each rental Also,  the 'rental_date' as a TIMESTAMP for the date movie was rented. 

- A3 

A detailed table was created named sales_report. The columns retrieved from the tables were store_id, payment_date, rental table, rental_id and amount. INSERT INTO and SELECT were used to pull the necessary data needed to complete the requirements outlined in A1. A summary table was created and two new columns were made called; total_sales_per_week and week_start_date. 

- A4 

The payment_date column in the detailed table was changed from TIMESTAMP to DATE. So only the year, month, day and not the time. Including the time movie was rented does not help with this particular data table. Since time is not relevant removing the time makes the table easier to follow. 

- A5  

Finding the total weekly sales could be beneficial to the stake holder in many different ways. Using the detail table shows you all the individual data (granular). Detailed tables could help you track all transaction for a period of time, which would be useful for finding sales performance at certain periods. The summary table provides more of an overview with less data. Using the summary tables can quickly show you if weekly sales are being met. Summary table could show how each stores individual weekly sales.. Seasonal sales trends could help you know when extra staff might be needed during certain time periods.

- A6 

The report should be updated weekly on a specific day of the week. To help keep track of any drastic changes in sales. 

- F

Linux Crontab could be used execute the files periodically. 
