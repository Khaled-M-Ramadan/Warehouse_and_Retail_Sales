   ![Screenshot 2025-06-14 220400](https://github.com/user-attachments/assets/2a1fb071-ec8f-4951-a3ed-ee8286544448)
# Warehouse_and_Retail_Sales
data process
Data processing was performed using Python (pandas, numpy), and the following processing procedures were followed:
1. Check basic data details, such as the number of rows and columns and the data type for each column.
2. Check for duplicates.
3. Deal with null values ​​appropriately for each column. An example of this is the null value in the Suppliers column. The null value was dealt with by grouping the data based on the item type and considering the most common supplier for each item type to fill in the corresponding null values.
4. Check for outliers and their impact on the analysis process.
5. Deal with text columns to ensure uniform character formatting.
6. Create a date column for chronological comparisons.
7. Creating a column for the month, quarter, and total number of cases for subsequent analysis.



In the second phase, we conducted an exploratory analysis.
1 - When creating line charts to track sales over time (months), we observed a clear seasonal trend. We also noted an unexpected drop in sales in December, which is unusual given that it is a holiday month. This issue warrants further study. We also recommend paying attention to inventory management during peak periods to ensure that market demand is met during peak periods, as well as for the marketing and human resources departments.
It is also necessary to study how to increase sales in the first quarter of the year, which showed a significant decline. We also note the dominance of warehouse sales over the sales process, which deserves further attention.
2 - Analysis of categorical variables revealed the following: Beer dominates warehouse sales, while both wine and liquor surpass it in transfers and retail sales. However, beer's dominance remains constant as the best-selling product. Therefore, caution when dealing with the largest source of sales is essential. This section does not contain all the observations, but the graph provides details.
3 - When analyzing suppliers, we analyzed the largest suppliers of the most important types of items to investigate the risks of monopolization of a particular supplier and other supply chain problems. We found that there are approximately three major suppliers for the three largest categories of sales, which is beneficial when negotiating and avoids monopoly problems. There are also many smaller suppliers, which means a smooth supply chain.
4 - We studied the various relationships between warehouse sales, retail sales, and retail transfers. We found a positive relationship between retail sales and retail sales. TRANSFERS, as well as the absolute dominance of warehouse sales, and the stable ratio of retail sales to transfers, do not indicate bottlenecks in transfers. In conclusion, we can focus on studying the warehouse due to its absolute dominance over sales and examining seasonal causes.![Screenshot 2025-06-14 184611](https://github.com/user-attachments/assets/b3344e57-7de3-45ea-99d9-2c24b5c5e192)
![Screenshot 2025-06-14 181348](https://github.com/user-attachments/assets/3e5eb39a-7dd5-4a80-989c-e207d264b22f)






   
