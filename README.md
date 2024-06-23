# Toy-Store-Analysis
 1)Create calculated columns in the sales table to pull in ‘cost’ and ‘price’ from the products table, then use those fields to calculate revenue and profit for each transaction
      hint(The RELATED function will be helpful here)
      
 2)Create measures to calculate the count of orders (‘total orders’), sum of revenue (‘total revenue’) and sum of profit (‘total profit’)
   hint(You can use DISTINCTCOUNT or COUNTROWS functions to calculate total orders, and a SUM function to calculate total revenue and profit)
3) BONUS: Define new measures to calculate total revenue and profit without referencing the calculated columns in the sales table 

hint(An iterator function like SUMX allows you to multiply the units sold by the RELATED product price for each transaction and sum the results)

KPI
1)Add KPI card visuals showing ‘total orders’, ‘total revenue’ and ‘total profit’ for the current month, along with monthly trends for each metric

2)Add a slicer to filter the report page by store location

3)Add a bar chart showing ‘total orders’ by product category, and a line chart showing ‘total revenue’ with the date hierarchy on the x-axis

4)Assemble the charts into a logical layout and adjust formatting, alignment and polish to finalize the report as you see fit

5) Add a pie chart showing sum of profit by store loaction. with slicer of store loaction.
   
6)Add a line and clustered column chart to show the count sale_id by product from product table

Summary 
*)We have been provided with sales & inventory data for a fictitious chain of toy stores in Mexico called Maven Toys, including information about products, stores, daily sales transactions, and current inventory levels at each location. 

*)The data spans from January 1st 2022 to September 1st 2023, containing over 820,000 transactions for all stores owned by Maven Toys.

*)The objective is to prepare the data, analyze and visualize it, and subsequently outline findings which allow the toy store chain to enhance its decision making capabilities and boost profits.

*)The data after marging the all tables we grt 145,987 transaction , and we have one-to-one for model view. We have used measure to add more column for the sloving kpi.
