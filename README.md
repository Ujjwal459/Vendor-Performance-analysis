# Vendor-Performance-analysis

step by step process to throughly understand this project-

step 1: Buisness problem
  Effective inventory and sales management are critical for optimizing profitability in the retail and wholesale industry. Companies need to ensure that they are not incurring losses due to inefficient pricing, poor inventory turnover, or vendor dependency. The goal of this analysis is to:
● Identify underperforming brands that require promotional or pricing adjustments.
● Determine top vendors contributing to sales and gross profit.
● Analyze the impact of bulk purchasing on unit costs.
● Assess inventory turnover to reduce holding costs and improve efficiency.
● Investigate the profitability variance between high-performing and low-performing vendors.

step2:  create a local database using SQLite.
        Explore Database Tables:
                begin_inventory.csv:-   Data Regarding inventory of brand at  the store in the starting of the year    
                end_inventory.csv:-     Data Regarding inventory of brand at  the store in the end of the year    
                purchases.csv:-         This table contains actual purchase_data,including the date of purchase ,products(brand) purchased by vendors ,the amount paid(in dollars) and the quantity purchased 
                purchase_prices.csv:-   This table provides Product-wise actual and Purchases prices, combination of vendors and brand is unique in this table  
                sales.csv:-             This table captures actual sales transaction,detailing the brands purchased by vendors ,the quantity sold ,the selling prices and revenue earned
                vendor_invoice.csv      This table aggregates data from the purchases table ,summarizing quantity and dollar amounts ,along with the additional column for freight.
        merge and clean the data 
        
step3: load aggregated table in jupyter notebook.
       1.Exploratory Data analysis
       2.Data cleaning
       3.Solving Research questions
       4.Analyze and interpret findings

step4 : Create Dashboard in powerBI
step5: Report Writing.
