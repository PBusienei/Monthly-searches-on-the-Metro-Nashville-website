Excel Project 1 – Monthly searches on Metro Nashville website

Find the dataset of Top 500 Monthly Searches on https://data.nashville.gov and download the CSV for Excel version of the data. Open the file in Excel and examine it. Be sure to choose comma delimited when prompted. Do not worry about any datatypes for now.

How many rows and columns are in the dataset? Enter your answer as text in M2.

Enter the text “max queries:” in cell M3 and enter the maximum query count in N3 using a formula.

Sort the data by column C (Query Count).  
When did the maximum query count occur?
What was the Query Text?
What do you notice about the top 5 searches?

Enter the text “Year is number: “ in M4. Use a formula in N4 to check the first value in the Year column (B) to see if it is a number.

Enter the text “Query Count is number: “ in M5. Use a formula in N5 to check the first value in the Query Count column (C) to see if it is a number.

Enter the text “map searches:” in M7. 
Enter “Count” in cell N6. Below it in N7, use a COUNTIF() formula in N6 to find the number of months that “maps” appeared in the top 500 monthly searches.
Enter “Sum” in cell O6. Below it, use a SUMIF() formula to give a count of the total number of times that “maps” was searched.
Enter “Average” in cell P6. Below it, use AVERAGEIF() to find the average number of times that “maps” was searched (in the months that it appeared in our dataset).
Finally, enter “Max” in cell Q6, and below it use a formula to find the maximum number of times that “maps” was searched in any month.

Create a formula in E2 to rank the values in the query count column (C) in descending order. Be sure to use an absolute reference for the range of values over which you want to apply the ranking. 

To sort the data from newest to oldest, you’ll need Month as a number. Create a lookup table for Month in columns M and N starting in row 10 with the headers and ending in row 22:
Month Name
Month Num
January
1
February
2
March
3
April
4
May
5
June
6
July
7
August
8
September
9
October
10
November
11
December
12

Create a header at the top of column F called “Month Num”. Use a VLOOKUP to match the month name in the Month column (A) to the lookup table in M11:N22 in order to populate the “Month Num” in column K.

Select columns A through F and create a custom sort (Home 🡪 Sort & Filter 🡪 Custom Sort). Sort by the largest to smallest Year as your first level, Month Num largest to smallest as your second value, and Query Text A-Z as your third level. Scroll through to find how many times “fairgrounds” was searched in July 2018.

Find which month in 2016 had the most searches for “fire”. Try to use a Custom Sort to save yourself from too much scrolling up and down.

Enter text (“all query counts over 100:” in M7 and use COUNTIF() in N7 to count the number of times a query was run more than 100 times in a given month.

Enter text (“query for codes over 100 times:”) in M8 and use COUNTIFS() to find the number of times users searched for ‘codes’ more than 100 times in a given month.

Create a new column (G) with a header of “Volume”. Populate this column with one of 3 categories: ‘Low’, ‘Medium’, ‘High’. Low volume searches happened less than 50 times in a month, medium volume searches happened between 50 and 100 times in a month (inclusive), and high volume searches were conducted more than 100 times in a month.

