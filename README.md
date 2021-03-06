### kickstarter-analysis (Including the Weekly Challenge)
* Performing analysis on Kickstarter data to uncover trends

### An Analysis of Kickstarter Campaigns
* Objective of this report is to present a data analysis on a Kickstarter data to uncover trends that will support decisions to initiate a crowdfunding campaign to a play called Fever and to validate if the funding estimation of $10,000 is a valid goal.

### Kickstarter findings:
#### Original dataset updates:
* The original dataset is available in the tab Kickstarter. In this tab, the Outcomes colors will facilitate a quick look to easily identify the success (green) and fail campaigns (red).  
* Since some goals amount was missed by a small margin, it was included a Percentage funded column to inform the deficit between Goal and Pledged. In this column a color scheme scale was added to highlight how close a campaign came to reach their funding goal, where blue is above goal and red below goal. To give more details on the pledged, an Average donation column was included to analyze the historical information of the average of how much people have pledged to campaigns in the past.
* A conversion of the original data in the deadline column and launched_at column (both columns are hidden in the document) are available in the new columns Date Created Conversion and Date Ended Conversion in a date format. To analyze whether the length of a campaign makes a difference in determining its success, an additional column with the amount of days that the campaign was active was included in the Active Period (days).
#### Additional tabs included: 
* Kickstarter_filter by play – Full kickstarter list filtered by play (Challenge)
* Outcomes Based on Goals – Summary play information per goal value and outcome (Challenge)
* Outcomes Based on Launch Date - outcome of each Kickstarter project based on the launch date (Challenge)
* Successful U.S. Kickstarters – Full list of all campaigns for plays in the U.S. that succeeded
*	Failed U.S. Kickstarters – Full list of all campaigns for plays in the U.S. that failed.
*	Descriptive Statistics – Summary that allows to compare the statistics for the goals and pledged for campaigns that succeed versus those that failed, for plays in the U.S.
*	Box and Whiskers – Graphic to easily compare the distribution of campaign goals and the distribution of total amounts pledged for plays in Great Britain.
*	Edinburgh Research – Summary of 5 plays from the Edinburgh Festival Fringe to understand the average donation and number of backers per each campaign.
*	Pivot Table_Category Statistics – Summary of the data to understand the performance by each Category. It is possible to filter the data and allow a more focused view of category of choice. At the moment it is filtered by Theater and Great Britain.
*	Pivot Table_SubCategory Stats - Summary of the data to understand the performance by each Subcategory so it is possible to filter by the most relevant subcategory: theatrical productions.
*	Pivottable_Launch Date outcomes – Summary of the data to understand the correlation between the length of a campaign with the success outcome and start dates.
*	Key Terms and Classification – a brief definition of key terms and colors classifications.
#### Overall Findings:
* From the total number of Kickstarter campaigns (4114), 74% (3038) of them are from U.S. and 15% are from Great Britain. 
*	There were 525 (58%) success theater campaigns in the U.S. against 349 (38%) that failed. In Great Britain there was 258 (72% ) successful and 89 (25%) failed. 
- ![alt text](https://github.com/DaniGio/kickstarter-analysis/blob/master/Theater%20Campaign%20outcome%20in%20the%20US.png)
- ![alt text](https://github.com/DaniGio/kickstarter-analysis/blob/master/Parent%20Category%20Outcomes.png)
*	While there are 604 campaigns in general in Great Britain, play campaigns are the most successful with 39% (238). The same for U.S with 412 successful play campaigns (14%).
*	Failed play campaigns in the U.S. have much higher goals than successful campaigns and at the same time their pledged are very low.
*	Since the pledged median for fail campaign is low, it shows that people are not pledging high for those campaigns
*	The mean campaign pledged is half of the suggested goal for US and Great Britain.
- US:
- ![alt text](https://github.com/DaniGio/kickstarter-analysis/blob/master/US%20Campains%20statistical%20info.png)

- GB:
- ![alt text](https://github.com/DaniGio/kickstarter-analysis/blob/master/Box%20and%20Whiskers_GB_musical.png)
#### Findings from the challenge:
*	May showed a high value for success campaigns while in December the number is almost 4 times less
![alt text](https://github.com/DaniGio/kickstarter-analysis/blob/master/Outcomes%20Based%20on%20Launch%20Date.png)
* When related to plays, the best oucomes are when the goal is less than $5000. 
* There are not enough information related, but evidence suggests that the chance of a successful campaign decrease when increasing the goal value 
![alt text](https://github.com/DaniGio/kickstarter-analysis/blob/master/Play%20Outcome%20based%20on%20goal.png)
#### Recommendation:
* Evidence suggests that play is a good subcategory to be fundreised and it is suggested that even for US or GB the goal should be decreased and the play should be produced for less than $10,000. It also suggests the campaign to be launched between May and June. 


