# Crowdfunding Report for Louise

## Overview of Project

### Purpose
- We are helping a playwright Louise for her crowdfunding campaign to fund her play "Fever". Her estimate budget was over $10,000 and she wanted us to help her check if this is reasonable. We will be using excel to analysis ton of previous data on crowdfunding and see what are the key factors for a successful campaign, and our focus will be on similar categories, which are theaters and plays in the US.

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date
![launchdate!](Theater_Outcomes_vs_Launch.png)

- This is a visualization of the successful, failed and canceled numbers of crowdfunding campaigns' outcomes of the "Theater" category based on their launch months. We want to look into the previous data and give Louise an idea what months would be the best time to launch a campaign like this.

### Analysis of Outcomes Based on Goals
![Goals!](Outcomes_vs_Goals.png)
- This chart shows the the successful, failed and canceled rate of crowdfunding campaigns' outcomes of the "plays" catergory based on their goal setting. From this, we want to check if goal setting will influence the outcome. Is a reasonable goal key to the success of this campaign and how does it look like.

### Challenges and Difficulties Encountered
- The biggest and first challenge was that there was huge amount of data to look at, clean and dig so as to find the related data that might provide Louise useful insight. We are using pivot table to compare different items and find correlations. But because of the outstanding outliers, we cannot use mean or median to give Louise a very straight forward answer of the most successful campaign budget range.

- Another difficulty I encountered was debugging. Some blank spaces/rows kept showing up in my pivot table and I couldn't delete it from the pivot table page. I searched on google and use youtube but no exact answer found. But from the videos and articles I read online, I figured that maybe the problem was the way I selected the data on the original sheet. I tried again selecting only cells with data, but not the whole sheet, the blanks gone! This was such an easy part in the class, but I spent an hour debugging, kinda time-taking but worth it.

## Results
### Two Conclusions about the Theater Outcomes by Launch Date
- Q2 seems to be the best time period of a year to do a crowdfunding campaign as it has an increasing trend of successful data and campaigns launched in the month of May got the highest successful numbers.

- December is not a good month to launch a crowdfunding campaign, as the successful rate is the lowest of the year.

### One conclusion about the Outcomes based on Goals
- It has an obvious declining trend of successful rate when the budget is from less than $1,000 to $30,000. The charts shows that campaigns under the budget of $19,999 has the successful rate over 50%. So if Louise sticks to her budget at $10,000, she will still have over 50% successful rate for her play crowdfunding campaign, based on the previous similar campaigns data.

### limitations of this dataset
- This dataset is not detailed enough for Louise to decide how much budget she should set as a goal for her campaigns. The mean and median goal of successful campaigns were at $5,000 and $3,000, meaning that there must be outstanding outliers. Also, this dataset only provide an overall budget amount, but no detailed or break-down budget data from the previous crowdfunding campaigns. So it is a bit ambiguous for Louise to decide the break down of the budget for a successful campaign. And 

### Other tables/graphs recommendation
- We can also create histogram charts of the budget of successful campaigns in the category of the theaters and the plays in the US to see the distributions. A boxdot chart could also be created to see what the outliers of successful campaigns look like and how do their data influences the overall distribution. We can also see if there are successful campaigns' budget fell on 1.5 IQR and see if the dataset has its value for Louise to take a reference to.
