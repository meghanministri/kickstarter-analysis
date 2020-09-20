# **Analysis of Kickstarter Campaign Data to Identify Trends**
---
## **Overview of Project:**

The purpose of this analysis is to provide Louise information about the success of other plays based on their fundraising goals and launch date so that she can make informed decisions about when to launch or how to fundraise for future campaigns. 

## **Analysis and Challenges:**

I used Excel tools and formulas to analyze the Kickstarter data in two ways – to determine the most successful campaigns based on launch dates and based on fundraising goals. We used the Kickstarter file as it contains data for thousands of programs, including goal and pledged amounts, backers, and dates. In this analysis, we focused on the data provided for the theater category. 

### Analysis of Theater Outcomes based on Launch Date
I used the “Year” function in excel to categorize the Date Created Conversion by year. I then created a pivot table to provide better insight into the total successful, failed and canceled theater programs based on the month in which they were launched. I used “Parent Category” and “Years” as the filters for the table and filtered Parent Category for “Theater.” I then added “Date Created Conversion” in the rows field to separate the data by month. I added “Outcomes” in both the columns field and the values field to categorize the data by each type of outcome with the total number of shows per month. Using this Pivot Table, I added a Pivot Chart to visualize the outcomes by launch date each month. 

![Theater_Outcomes_vs_Launch](Resources/Theater_Outcomes_vs_Launch.png)

### Analysis of Theater Outcomes Based on Goals
To analyze the outcomes by fundraising goal, I created a table based on the number of successful, failed or canceled plays within each fundraising goal range. I created the goal column to separate the fundraising amounts into $5,000 ranges, from less than $1,000 to greater than $50,000. I used the “COUNTIFS” function to determine the amount of successful, failed and canceled plays in each goal range. After finding the total in each range, I calculated the percentage successful, failed and canceled. I used this data to create a chart showing the ranges on the percentage of each outcome at each goal range. 

![Outcomes_vs_Goals](Resources/Outcomes_vs_Goals.png)

One of the challenges I faced during this analysis was during the “COUNTIFS” steps. I initially found it difficult to determine which data to use as the range or as the criteria. I watched the video in the example and compared the example to the data we were using, and what we wanted to show. I was able to write the formula using the necessary ranges (or columns) to show the number of outcomes in each fundraising range. Another challenge I encountered was the Outcomes_vs_Goals graph, where I was not sure how to show the specific data on each graph axis. I used “Select Data” in the Chart Design Toolbar and made the chart based on trial-and-error. Once I was able to get the correct data included on each axis, I changed the color of the lines.

## **Results:**

### Analysis Results
Based on the analysis and the Theater Outcomes Based on Launch Date, we can conclude that the most successful theater campaigns are launched in May. We can also determine that December is not the best time to launch a theater fundraising campaign as the number of successful launches decreases significantly and there are about as many failed campaigns as there are successful.

Based on the Outcomes Based on Goals analysis, we can determine that programs with a fundraising goal in the $45,000 to $49,999 range have the highest failure rate. Plays that have a fundraising goal that is either less than $1,000 or in the range of $1,000 to $4,999 are the most successful.

### Challenges and Limitations
One of the limitations of this dataset is that it only includes a select number of programs. This dataset likely does not include data from every theater program or play that was funded during this time, so It may not be the most complete information to make a decision about when to start a fundraiser or the goal to set. It might have also been useful to have information on how these programs were advertised for funding (online, at donation events, etc.) and the type of play, as that might have given more insight into why some plays were successful and some were not.

### Recommendations
We could have used the “Date Ended Conversion” to determine how the length of some fundraising campaigns may have affected the overall outcome. For example, if a campaign ended a month after being launched, that may have had an effect on the outcome. We could have created a graph that shows the ranges that the campaign is active and the outcomes in those ranges.


