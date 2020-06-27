# Kickstarting with Excel
Performing analysis on Kickstarter data to compare Outcomes VS Goals and Theater Outcomes VS Launch Date
## Overview of Project
Louise would like to know how different campaigns fared in relation to their launch dates and their fundraising goals.

### Purpose
Analyze the campaigns outcomes based on launch date and goals in order to achieve the optimal fundraising result in the future.

## Analysis and Challenges
Outcomes based on Launch Date: I performed the analysis by comparing the successful theatre outcomes and failed outcomes in different launch months. 
Outcomes based on Goals: I performed the analysis by comparing the percentage of sucessful rate and percentage failed rate according to different fundraising goals. 

### Analysis of Outcomes Based on Launch Date
The number of successful outcome for the category of theatre is the highest in th month of May. Same as the number of failed outcomes.
![Theater_Outcomes_vs_Launch](C:\Users\chiko\Desktop\Data Analytics\Crowdfunding Project\Resources/Theater_Outcomes_vs_Launch.png).

### Analysis of Outcomes Based on Goals
Sucess rate and failure rate has an inverse relationship. Sucess rate is the highest when the goal is less than $1000 and is the lowest when the goal is around $45,000 to $49,999.

### Challenges and Difficulties Encountered
Outcomes based on Launch Date: A possible challenge is to construct the pivot table by selecting the right data.
Outcomes based on Goals: A possible challenge is to correctly use the countifs function.

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?
Compare to other months, the period of May to August had the best outcome so it may be a good idea for Louise to start fundraising in this period; specifically, May is the best month to launch a fundraising project. 
In addition, the number of failed outcome is also the higest in this period which may due to the total number of outcomes.
The number of failed outcome is the highest in December. One possible reason is that people have lower budget because most money is spent on holidays including gifts, vacation, and dinners. As a result, its not recommeded to launch a campaign in December.

- What can you conclude about the Outcomes based on Goals?
Louise is most likely to reach her goal if her goal amount is less than $1000. On the other hand, she is least likely to reach her goal when her goal amount is between $45,000 to $49,999.

- What are some limitations of this dataset?
1. There are many other factors which might affect the outcomes including number of fundraiser, their budgets and etc which none of it was considered in our dataset.
2. Theatre Outcome Based on Launch Month: it is not fair to just compare the outcomes based on launch month since the total number of campaigns are different in each month.
- What are some other possible tables and/or graphs that we could create?
Theatre Outcome Based on Launch Month: it might be more accurate to use a dual axis chart to illustrate the outcome based on launch month VS percentage of success/failsure.
