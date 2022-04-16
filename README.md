# Crowdfunding-Analysis
Analysis of Kickstarter data to uncover trends
## Overview of Project

### Purpose

In this module we are helping an upcoming Playwright Louise assess her chances of success in raising $10000 for her play *Fever* by analysing data of 4000+ kicstarter campaigns and advise her on probable impact of the size of goal and the launch month resulting in a success.

For the same we will conduct a deepdive and prepare a concise presentation for visual depiction of our analysis.



## Analysis and Challenges

As part of the review we studied outcomes data of 4114 kickstarter campaigns panning across 9 Parent categories and 10 countries for their goal value and pledged amount.

Highlevel analysis suggests that _Theater_ and _Music_ are most popular categories in terms of number of fundraiser campaigns initiated as well as their Success rates with majority campaigns launched in the US and Great Britain.  

While overall success rate for all campaign was merely 53%, for Theatre it was a modest 60% success. 

(![image](https://user-images.githubusercontent.com/102870991/163673442-63d4e86c-e784-434c-81fa-897b66de503e.png)

The sub-category analysis suggested that Plays dominated the funding landscape. 83% of Thetrical campaigns were also related to Plays.

![image](https://user-images.githubusercontent.com/102870991/163673463-9a97c091-0576-4589-a1fa-abdc21c2ccba.png)


So, Louise is ceratinly in the right spot as far as market and sub-category are involved. Further deepdive of Outcomes data by Launch date and Goal value is as shared below.


### Analysis of Outcomes Based on Launch Date

Based on the launch dates it was amply clear that the month that launched most successful Kickstarter campaigns was May followed by June and July. While the chances of failure do not spike significantly in any particualr time of the year. 

Accordingly Louise might want to consider launching her campaign during May/June.

![image](https://user-images.githubusercontent.com/102870991/163673469-c9920b86-a1e5-4119-ae9a-ab3633e0a7a8.png)



### Analysis of Outcomes Based on Goals


While studying the goals it is evident that the chances of success are inversely proportional with the size of the campign. However, few buckets (between 35000 to 45000 as shown in chart below) might be impacted by handful of large entries. For this reason we have done statistical analysis as well which suggests that in far and few cases there was success in raising funds for high value campaigns.

![image](https://user-images.githubusercontent.com/102870991/163673478-a3c731b6-dfac-4682-9d59-6580f2ef379d.png)


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
 
![image](https://user-images.githubusercontent.com/102870991/163673489-d1de1b5e-314d-48ea-9b27-48b88d15317c.png)

