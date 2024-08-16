
# Coffee Shop Sales Analysis using MS Excel 



**Problem Statement :**

The coffee shop industry is highly competitive, and understanding customer purchasing patterns is crucial for optimizing operations and maximizing revenue. This project aims to analyze retail sales data from multiple coffee shop locations to uncover key insights into sales trends, peak activity periods, and product performance. By examining variations in sales across different days, times, locations, and product categories, the analysis will provide actionable recommendations to improve sales strategies, enhance customer satisfaction, and drive overall business growth.

## Snapshot of Dashboard

![Screenshot 2024-08-16 164940](https://github.com/user-attachments/assets/9f9c26dd-6358-4dd1-92e2-10d73dbfb4e9)

#  Steps followed :- 
1. Transform the dataset using Power Query Editor.

2. Created a new categorical column for coffee size (e.g., Large, Regular, Small).

3. Transformed the 'Product_Details' column by extracting and removing the size information.

4. Applied the TRIM function to eliminate leading and trailing whitespace from the specified column.

5. Added a calculated column 'Total Bill' by multiplying 'Unit Price' and 'Transaction Quantity'  and also assingned currency to the column.

6. Refined the 'Time' column by removing the date component using the 'Text After Delimiter' function, with a space as the delimiter.

7. Extracted and added columns for 'Month' and 'Day of Week' from the 'Date' column.

8. Extracted the hour from the 'Time' column and populated it into a new column.

9. Added new columns categorizing data by 'Day of Week' and 'Month of Year'.
10. Sorted the 'Day of Week' and 'Month of Year' columns in chronological order.

11. Loaded the transformed data into the Excel workbook.

12. Inserted pivot tables for various analytical parameters and created different visualizations, including line , pie and bar charts along with slicers on basis of month name and day name . Inserted cards representing essential data.



# Specific Analysis:



1) How do sales vary by day of the week and hour of the day ?

     Sales do not vary significantly by day of the week but tend to decrease slightly on weekends. By hour of the day, sales peak between 10 and 11 AM and gradually decrease afterward.



2) Are there any peak times for sale activity ?  


     Yes, sales peak between 10 and 11 AM in the morning, as people prefer to have coffee before heading to work.

   

3) What is the total sales revenue for each month ?

    Total sales revenue for each month is visualized using a bar chart and slicer. Revenue has been increasing every month, indicating a healthy trend. Additionally, revenue is analyzed per store location.
   

4) How do sales vary across different store locations ?


    Sales variation by store location is displayed with a bar chart and slicer, allowing for monthly sales analysis by location. This helps to understand how different locations contribute to overall sales.
   

5) What is the average price/order per person ?
   
    The average order price per person is $1.44, while the average bill per person is $4.686, as shown using a card visualization.
  

6) Which products are the best selling in terms of quantity and revenue  ?
   

   The best-selling products, displayed using a pie chart, are coffee (38% of total sales), followed by tea (28%), and bakery products (12%).

   

7) How do sales vary by product category and type ? 
   
   
   The highest sales by product category were recorded for Barista Espresso, followed by Brewed Chai Tea and Hot Chocolate. In terms of size, sales distribution was 30% Large, 31% Regular, and 9% Small.
