# kickstarter-analysis
performing analysis on kickstarting data to uncover trends
# Kickstarting with Excel
        Louise’s play Fever came close to its fundraising goal in a short amount of time. Now, she wants to know how different campaigns fared in relation to their launch dates and their funding goals. Using the Kickstarter dataset that you’ve already combed through, you’ll visualize campaign outcomes based on their launch dates and their funding goals.
## Overview of Project
       This project is related to fund raising campaign for categories like theatre, food, games, technology…etc. Most of the funding came from US for this campaign. Based on the dataset it is successful campaign and below are important details.
•	The Goal column tells us how much money each campaign will need to succeed.
•	The Pledged column tells us how much each campaign actually made.
•	The Outcomes column tells us if the campaign met its goal.
•	The Country column lists the country in which the campaign was started.

### Purpose
       The purpose of this analysis report to find the successful outcomes based on the launched date and percentage of the successful outcomes based on the range of amount.

## Analysis and Challenges
### Analysis of Outcomes Based on Launch Date
    ![Theater_Outcomes_vs_Launch png ](https://user-images.githubusercontent.com/108489186/178121639-1d71cf76-b824-449d-9d95-102c8b9ff487.png)
    resources/Theater_Outcomes_vs_Launch.png .png
   
Fund raising is successful as per expectation base on the above chart.
In this line graph we can show the Theater outcomes based on launch date. In this line graph x axis contains the months and y-axis contains the theater outcomes and it divided into three bases like successful ,failed and canceled .
Successful: In the may month theater outcomes shows more successful greater than 100 and outcomes in the month of December less than 40.
Failed: Most of these outcomes are in between 20 to 50 range.

### Analysis of Outcomes Based on Goals
      ![Theater_Outcomes_vs_Launch png ](https://user-images.githubusercontent.com/108489186/178121416-88eb6ee6-9fad-4f04-b2bc-1653e9ffa1e4.png)
       Most of the goals are successful and more funds raised as per the above chart.
 This line graph shows the outcomes based on goal.in this line graph x-axis contains the goals and y- axis contains the percentage. Blue line shows the percentage successful , orange line shows percentage failed and gray line show percentage of canceled. Percentage  successful funding more in the range less than 1000 and 35000 to 49999   in and it reached 80% in successful. Percentage successful shows less in the range of 45000 to 49999. Percentage failed shows highest at the range of 45000 to 49999 in goals less in the range of less then 1000 . percentage canceled shows 0% in the whole range of goals.

### Challenges and Difficulties Encountered
a)	Year from the date- usage of year function from unix date timestamp
b)	Date conversion -Unix date timestamp to human readble format.
c)	Showing of column labels for successful, failed and canceled in pivot chart
d)	Creating line chart from pivot table
e)	Using countif() function to get the count of outcomes based on the range
f)	Percentage calculation

## Results
- What are two conclusions you can draw about the Outcomes based on Launch Date?
	In the month of may launch dates theater outcome funding is collected more compared to other months.
	Canceled outcomes are very less in all the months.

- What can you conclude about the Outcomes based on Goals?
  Most of the successful funding outcomes are from less then 1000 and between 35000 to 49999
- What are some limitations of this dataset?
  a)Unix datastamp it should be in the human readable format of date
  b)Category and sub-category should be in different columns.

- What are some other possible tables and/or graphs that we could create?
  Graph:Based on the below graph we can say that most of the funding raised from US.
  ![successful outcomes based on country](https://user-images.githubusercontent.com/108489186/178121579-fc1f65ad-6b4b-469b-99d1-fdfd2a318eeb.png)
