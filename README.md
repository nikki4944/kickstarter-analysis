# Module 1 Challange: kickstarter-analysis
## Overview of Project

The client, as part of their successful kickstarter campaign, wants to know if there is a correlation between launch dates, funding goals, and fundraising success. Using the kickstarter data set, I have created visualizations of the data that is most similar to the client's project, i.e. a theatrical production.

## Analysis and Challanges

Using the kickstarter data set, I created a pivot table to determine how many successful, failed, or canceled theater campaigns were launched per month in the years in which the data was created. <img width="301" alt="Screen Shot 2021-04-25 at 9 26 00 PM" src="https://user-images.githubusercontent.com/82982901/116017184-eb27bb00-a60c-11eb-8af1-374ac683c3db.png"> This table was further filtered to include theater campaigns before creating a line graph visualization. ![Theater_Outcomes_VS_Launch](https://user-images.githubusercontent.com/82982901/116017318-4659ad80-a60d-11eb-986d-7e1b4f4b5c16.png) If a particular year is of interest to the client, the table and visualization can be furth filtered by specific year in the dataset, this was not done as part of my analysis.

The kickstarter data also allows us to determine how successful the campaigns were based on their fundraising goal. Using the COUNTIFS forumula in Excel, I was able to calculate the number of successful, failed, and canceled theater campaigns. <img width="802" alt="Screen Shot 2021-04-25 at 9 30 57 PM" src="https://user-images.githubusercontent.com/82982901/116017455-9df81900-a60d-11eb-8b51-1afc2669484b.png"> As the screenshot shows, once the nunber of campains was determined for each category (successful, failed, canceled), I was able to determine the percentage of campaings in each category for the budget ranges specified.

## Results

As illustrate in the attached graph, "Theater Outcome vs Launch", we are able to see that the best months to launch a new campaign are May, June, and July while the months of November, December, and January are the worst.![Theater_Outcomes_VS_Launch](https://user-images.githubusercontent.com/82982901/116016290-2d033200-a60a-11eb-9b1d-30300cb612ae.png)

As the attached graphic illustrates, the most successful campaigns had fundraising goals of less than $20,000. ![Outcomes_vs_Goals](https://user-images.githubusercontent.com/82982901/116016862-f201fe00-a60b-11eb-9509-0d40424cd71b.png)

The data visualized in the above graphics do not take into account any geographic considerations. If the client knows where they would like to stage this production, it would be helpful to reanalyze the data while filtering for country. I would recommend adding a filter for "country" to the "Theater Coutcomes vs Launch" pivot table in order to determine if geography has any impact on the results.
