This is my first Excel project. Data is taken from chandoo.org. The steps I went through in this projects are:
1. Data cleaning
   I cleaned my data by converting some rupees amount data to dollar amount in Amount column
2. Data processing
   I processed my data. I added column of another table by using XLOOKUP so I combined the data and added more calculated fields as these added fields will be 
   required later on.
3. Quick statistics
   I analysed my data and calculated sum, average, median, mode, min, max, range, quartiles, count by using formulas. I also used UNIQUE function to find the 
   distinct values.
4. Exploratory Data Analysis with conditional formatting
   I copied my data in new sheet and then using conditional formatting, I analysed my data. I sorted my Amount data in descending order and highlighted the top 10 
   and in Units column I highlighted the duplicate values to understand the nature of units being sold.
5. Data Analysis
   a)Sales by country(pivot table)
   I made a pivot table which is compairing sales and units country wise. I found India is the best selling country followed by Canada. Then I made pivot chart 
   showing sales and units in different countries. I inserted slicer having different sales person. On clicking a particular sales person, my table and chart 
   changed accordingly.
   b)Top 5 products by $ per unit
   Again with the help of pivot table I analysed my products and made a calculated field namely, sales per unit. I sorted sales per unit in descending order and 
   found Raspberry is most costly followed by peanut Butter Cubes and also made pivot chart analysing the same.
   c)Anamoly detection
   I compared my sales and units being sold using pivot chart and some anamolies. 510 units of a product were sold for $819 , only 39 units of another product were 
   sold for $16,184. These were some poits one can look up. 
   d)Best sales person by country
   Using pivot table I found the best sales persons in the different countries by sorting Amounts column in descending order and showing only the top one. I then 
   created pivot chart
   e)Top products by profit
   Using pivot table I compared my products and added a calculated field called as profit(Sales-cost) then sorted profit in descending order and selected top 5 
   products. Then I created a pivot chart and added a slicer showing different countries. Now I can compare my top 5 products( by profit) by countries.
   f)Dynamic country level sales report
   Here I used Data validation to have a advantage to select a country as it opened dropdown and we can select a country as per our choice. This report also 
   enables us to see the number of transactions by using COUNTIF function. Then I used SUMIFS and AVERAGEIFS to find total sales, cost, profit and units being 
   sold. Then using UNIQUE function I listed all salesperson and next column is giving a total sales and units being sold data done by that salesperson in that 
   country. Then I applied IF function which ticked the cell if sales is greater than $12,000 and marked cross if the salres is equal or less than $12,000. We can 
   analyse our data according to different countries.
   g)Which product to discontinue?
   Using pivot table I analysed my product and added a calculated field called as profit % and by sorting the profit% in ascending order the first data is showing 
  the least profit giving product and now by slicer we can analyse our data according to countries. We can discontinue the product giving the least profit.
   
![conclusion awesome chocolate](https://github.com/DivyanshiAgarwa1/Excel-Projects/assets/172874617/70367d37-272e-4d34-b6d4-7158bc30d006)
![image](https://github.com/DivyanshiAgarwa1/Excel-Projects/assets/172874617/0c2c1d06-e08a-4a4c-85f2-ce5a692864c4)
