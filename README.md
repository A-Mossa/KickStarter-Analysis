# Kickstarter Campaigns Analysis

## **Overview of Project**
This is an analysis of data on kickstarter campaigns  that took in consideration the time of launch, outcome and different categories to determine what would be the best strategy to launch a new funding campaign in different industries.

### Purpose
This analysis would help Louise who wants to start a funding campaign for her new play, make data-informed decisions to increase the chances of success for the campaign.

## Analysis and Challenges
The data itself was mostly clean and valid, all be it mixed and not completely relevant to the specific industry our client was involved in. however,  a portion of the data was sufficient for the analysis we carried out, and an accurate analysis has been reached.

some challenges that I anticipated was encountering incomplete or unclean data, missing and unclean data, and the timeline of project completion. fortunately, none of the above issues were encountered and hiccups were minor.

### Analysis of Outcomes Based on Launch Date
Based on month analysis launch date of kickstarter theater campaigns, some interesting findings appeared.
from thourough analysis of data provided we concluded:
- The months with the most launched campaigns are May, June, and July. 
- The highest number of successful campaigns were launched in Q2, and the months are May, June, and July respecectively.
- The months with highest failed campaigns are May, October, and August.

![Chart displaying Outcomes vs Launch Date](https://github.com/A-Mossa/KickStarter-Analysis/blob/main/Theater_Outcomes_vs_Launch.png)

### Analysis of Outcomes Based on Goals
The campaign goal appeared to be a major factor in the success of a project. it had the following effect:
- Campaigns that saw the most success were the ones that had a goal of less than a 1000, from 1000 to 4999, and from 35000 to 49000.
- Campaigns with the least success were those with a goal of 45000 to 49999, 50000 or more, and 30000 to 34999.
![Outcomes vs Goals chart](https://github.com/A-Mossa/KickStarter-Analysis/blob/main/Outcomes_vs_Goals.png)
### Challenges and Difficulties Encountered
The dataset itself was relevantly small, easy to manipulate, clean and mostly complete. one challenge that was encountered was the converion of date from timestamps to DD/MM/YYYY format. Although it was comfortably overcame, it was an opportunity to learn about a new concept of timre registration and formula.

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?
Regarding Launch date, from the above findings we discovered that around mid year, is when most of the campaigns launch. May especially was the month that saw the most campaigns launched with a success rate of 66% followed by June then July.
May, June and July were recommended to the client to launch their campaign as it historically it shows the most success rate. August, October, and December are found to be the months with the highest failure rate.

- What can you conclude about the Outcomes based on Goals?
Looking at the successful rate of kickstarter projects that launched with a goal of less than 1000 to 5000 (72.5%) I can conclude that the optimal plan for the campaign goal would be somewhere in that range.
campaigns that launched with goals of 45000 or more tend to have significantly high fail rate. 100% of campaigns that asked 45000 to 49999 failed, and campaigns with goals of 50000 or more had a failure rate of 87.5% fail rate.
Therefore, my recommendation for the client would be to set their asking goals to be lower than 5000 to expect the best outcome

- What are some limitations of this dataset?
some limitations of this data set is that it does'nt specify the demographics of the backers, Their age group and gender could give hints on who the client's target audience would be.
Other than that the data seemed clean, consice, and gathered in a single format.
- What are some other possible tables and/or graphs that we could create?
If I had the opportunity I would have created a separate analysis on the relation between average donation and outcome. it would explain the relatioship between the contribution ammount and the end goal
