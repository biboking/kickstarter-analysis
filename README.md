# Crowdfunding Report for Louise

## Overview of Project

### Purpose
- We are helping a playwright Louise for her crowdfunding campaign to fund her play "Fever". Her estimate budget was over $10,000 and she wanted us to help her check if this is reasonable. We will be using excel to analysis ton of data on crowdfunding projects and see what are the key factors for a successful campaign, and our focus will be on similar categories, which are theaters and plays in the US.

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date

- This is a visualization of the successful, failed and canceled numbers of crowdfunding campaigns' of the "Theater" category based on their launch date. We want to look into the previous data and give Louise an idea of what months would be the best time to launch a campaign like this.

![launchdate!](Theater_Outcomes_vs_Launch.png)

### Analysis of Outcomes Based on Goals

- This chart shows the the successful, failed and canceled rate of crowdfunding campaigns' outcomes of the "plays" catergory based on their budget goal. From this, we want to check if goal setting will influence the outcome. Is a reasonable budget goal key to the success of such campaigns and how does it look like.

![Goals!](Outcomes_vs_Goals.png)


### Challenges and Difficulties Encountered
- The biggest and first challenge was that there was a huge amount of data to look at, clean and dig so as to find the related data that might provide Louise useful insights. We are using pivot table to compare different items and find correlations. But because of the outstanding outliers, we cannot use mean or median to give Louise a very straight forward answer of the most successful campaign budget range.

- Another difficulty I encountered was debugging. Some blank spaces/rows kept showing up in my pivot table and I couldn't delete it from the pivot table page. I searched on google and use youtube but no exact answer found. But from the videos and articles I read online, I figured that maybe the problem was the way I selected the data on the original sheet. I tried again selecting only cells with data, but not the whole sheet, the blanks gone! This was such an easy part in the class, but I spent an hour debugging, very time-consuming but the research process worth it.

## Results
### Two Conclusions about the Theater Outcomes by Launch Date
- For the blue successful line, we can see an upcliming trend from March and hit the highest end in May. This means that campaigns launched in May got the most successful outcomes. Although the successful outcomes trend started to fall since May, the succussful outcomes from April to August are higher than most of the rest months. It's a good option for Louise to launch her campaign in those months.

- The blue successful outcome line and the orange failed outcome line almost met in December, which means December is not a good month to launch a crowdfunding campaign, because the successful rate is the lowest of the year.

### One conclusion about the Outcomes based on Goals
- It has an obvious declining trend of successful rate when the budget is from the range of less than $1,000 to the range of $25,000 to $29,999. The charts shows that campaigns under the budget of $19,999 has the successful rate over 50%. So if Louise sticks to her budget at $10,000, she will still have over 50% successful rate for her play crowdfunding campaign, based on the previous similar campaigns data.

### limitations of this dataset
- This dataset is not detailed enough for Louise's campaign. It only provides an overall budget amount, but no detailed or break-down budget data of successful campaigns for Louise to take reference to. And if there are outstanding outliers, it could influence the overall analysis.

### Other tables/graphs recommendation
- We can also create histogram charts of the budget of successful campaigns in the category of the theaters and the plays in the US to see the distributions. A boxdot chart could also be created to see what the outliers of successful campaigns look like and how do their data influences the overall distribution. We can also see if there are successful campaigns' budget fell on 1.5 IQR and check if the dataset has its value for Louise to take a reference to.
