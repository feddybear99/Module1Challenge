# Module1Challenge


**Analysis: Louise’s play Fever & financial impact on campaign performance by launch dates and funding goals**

The purpose of the analysis was to examine Louise’s play, Fever, and how each campaign performed (dollar amount) in relation to their launch dates and their funding goals




**Overview of Project**

•	The purpose of the analysis was to examine Louise’s play, Fever, and how each campaign performed (dollar amount) in relation to their launch dates and their funding goals. The analysis was performed in Excel using Louise’s data from her play, Fever. 

**Analysis and Challenges**
•	A few challenges came up during the analysis including: filtering issues within columns on the spreadsheet & pivot table data needing significant adjustments to find an easier way to display the information. For the filtering issue, I started using the data from my existing spreadsheet (done from homework a week prior), and I kept filters on the data, which ruined the entire graphing & analysis at the end of Deliverable #2. I then decided to re-download the spreadsheet and then go from there. Although I was re-doing all of the work I just completed, I found that it helped me understand the analysis and procedure better about finding the targeted data points (Outcomes Based on Launch Date Chart, Outcomes Based on Goals Chart).


**Results**
•	The chart, Theater Outcomes Based on Launch Date (see below) ![Theater_Outcomes_vs_Launch](https://user-images.githubusercontent.com/106992995/175875643-086b66e7-2242-4468-86dd-497c93bb030a.png), filtered data is aiming to measure Theater outcomes (failed, successful, canceled) occurring based on the (monthly) timeframe of its Launch Date. To isolate the information shown on the chart, columns from the original “Kickstarter” spreadsheet were used to create a pivot table. From the pivot table, the “Parent Category” was isolated to show only ‘Theater’ subcategories. We then needed to add in the different launch date schedules, and that was found by converting the “deadline” and “launched at” columns to read MM/DD/YYYY formatting. From these two variables, a line chart was used to create the visual because it’s continuous data that includes timing (months over the years). 

•	Based off of the data shown in the, “Outcomes Based on Launch Date” chart, it looks like there’s seasonality for the Parent Category, Theater, because in the month of May, the number of “successful” plays reached 111 outcomes, while only having 52 (failed) outcomes - leading to the largest disparity between “successful” and “failed” outcomes.

•	Another detail to note is that the number of “Failed” (35) outcomes and “Successful” (37) outcomes almost overlapped during the month of December, which could help explain ineffective launch dates, leading researchers to other variables like “Goals” and its impact on projected outcomes. 

•	The chart, Outcomes Based on Goals (see below) ![Outcomes_vs_Goals](https://user-images.githubusercontent.com/106992995/175875754-66689f60-1601-4c59-9490-85261f4ed3e8.png) aimed to examine the Goal (USD) against all three “plays” outcomes: failed, successful, and canceled. The “Percentage Successful” vs. the “Percentage Failed” ratios were created to find where the most successful and realistic Goal ($) targets could be based off of historical data. In the chart, the data shows where the most successful pricing tier for a successful outcome and lowest rate of both “failed” and “canceled” was found in the “Less than $1,000” bracket. The two intersecting points in the first intersection shows a “breakeven” point, which shows that there’s an equal number of “successful” plays as there are “failed” plays in pricing goal tier “15,000 to 19,999”. This could suggest that the type of customers buying these play tickets are more likely to buy ticket amounts within the lower pricing tier (less than $1,000) vs. buying in large volumes in more expensive pricing tiers. 


•	Potential limitations in the dataset include the variable “Years” because it’s not explicitly stated which timeframe of years are being considered for the analysis, and I think it’d be valuable to insert a timeline or have a general idea of when the data is being examined - especially when examining potential seasonality trends. 
