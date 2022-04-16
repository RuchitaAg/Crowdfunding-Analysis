# Crowdfunding-Analysis
Analysis of Kickstarter data to uncover trends
## Overview of Project

### Purpose

In this module we are helping an upcoming Playwright Louise assess her chances of success in raising $10000 for her play *Fever* by analysing data of 4000+ kicstarter campaigns and advise her on probable impact of the size of goal and the launch month resulting in a success.

For the same we will conduct a deepdive and prepare a concise presentation for visual depiction of our analysis.



## Analysis and Challenges

As part of the review we studied outcomes data of 4114 kickstarter campaigns panning across 9 Parent categories and 10 countries for their goal value and pledged amount.

Highlevel analysis suggests that _Theater_ and _Music_ are most popular categories in terms of number of fundraiser campaigns initiated as well as their Success rates with majority campaigns launched in the US and Great Britain.  

While overall success rate for all campaign was merely 53%, for Theatre it was a modest 60% success. A sub-category analysis suggested that Plays dominated the Theater category with 83% of Thetrical campaigns related to Plays.

[Parent Category Analysis](Resources/Outcomes_vs_Parent Category.png)

[Sub-Category Analysis_US Market](Resources/Outcomes_vs_Parent Category.png)

So, Louise is ceratinly in the right spot as far as market and sub-category are involved. Further deepdive of Outcomes data by Launch date and Goal value is as shared below.


### Analysis of Outcomes Based on Launch Date

Based on the launch dates it was amply clear that the month that launched the most successful Kickstarter campaigns was May followed by June and July. While the chances of failure do not spike significantly in any particualr time of the year. 

Accordingly Louise might want to consider launching her campaign during May/June.

[Theater Outcomes Based on Launch Date](/Resources/Theater_Outcomes_vs_Launch.png)



### Analysis of Outcomes Based on Goals


While studying the goals it is evident that the chances of success are inversely proportional with the size of the campign. However, few categories might be impacted by handful of large entries. For this reason we have done statistical analysis as well which suggests that in far and few cases there was success in raising funds for high value campaigns.


[Outcomes Based on Goal](Resources/Outcomes_Vs_Goals.png)

We narrowed down the study to US Plays category which was not only relevant for Louise's campaign but also helped to limit goals in one currency. 

The finding of the Statistical study revealed that the average Mean value for the Successful Campaigns was $5000 half of what Louise plans to raise.  
The Mean Goal for Failed campaigns was $10000. 

Besides, there were several outliers where high value campaigns got success in getting pledges. Those scenarios were mainly of popular artists or production houses.


### Challenges and Difficulties Encountered

Challenges encountered while studying the outcomes by launch date involved unreadable format of the Unix Date Stamp and was overcome by converting the same into readable format using specific excel formula.

Another limitation of the dataset is that the goal and pledged values are in local currency which makes it difficult to compare size of the goal and related outcomes across countries. For this reason I tried to deuce inferences for US market theatre sub-category to compare like values.

The analysis was restricted to studying sab-categry for launch date and campaign values while there could be other reasons for failure of campaigns like genre of plays involved which hasn't been studied at length but could be attained based on blurb.



## Results


### What are two conclusions you can draw about the Outcomes based on Launch Date?

Based on the launch dates it can be concluded that: 

1) the month that launched the most successful Kickstarter campaigns was May followed by June and July. 

2) The chances of failure do not spike significantly in any particualr time of the year.


### What can you conclude about the Outcomes based on Goals?

Louise must reconsider the campaign value to see if she could manage with smaller budget or else create a buzz to garner interest at large scale having higher number of backers. 


### What are some limitations of this dataset?


*Challenges encountered while studying the outcomes by launch date involved unreadable format of the Unix Date Stamp and was overcome by converting the same into readable format using specific excel formula.

*Another limitation of the dataset is that the goal and pledged values are in local currency which makes it difficult to compare size of the goal and related outcomes across countries. For this reason I tried to deuce inferences for US market theatre sub-category to compare like values.

*The analysis was restricted to studying sab-categry for launch date and campaign values while there could be other reasons for failure of campaigns like genre of plays involved which hasn't been studied at length but could be attained based on blurb.


### What are some other possible tables and/or graphs that we could create?
 
[Box_&_Whiskers_US_Plays_Subcategory_Analysis](Resources/US_Plays_Box_&_Whiskers.png)
