# Kickstarting with Excel
## Overview of Project

### Purpose
* Project to analyze Kickstarter Campaign data for theater and play specific information to project best goal/pledge donations.

## Analysis and Challenges:

### Analysis of Outcomes Based on Launch Date
![Theater_Outcomes_vs_Launch.png](path/to/Theater_Outcomes_vs_Launch.png)
The Theater Outcomes vs Launch chart shows the outcomes based on date the campaign was launched, listed in months.  The line graph shows outcomes for Successful, Failed and Canceled Kickstarter Theater campaigns. There is an overall successful rate is higher than failed or canceled.  There is a low number of canceled campaigns overall, with the month of October showing 0 cases.  The months with highest success is in May (111) & June (100); the lowest is in December.

### Analysis of Outcomes Based on Goals
![Outcomes_vs_Goals.png](path/to/Outcomes_vs_Goals.png)
The Outcomes vs Goals chart shows the outcomes based on the projected donation goal amounts specifically for Plays in the Theater subcategory, ranging from less than $1,000 to greater than $50,000.  The line chart shows outcomes for Percentage Successful, Percentage Failed and Percentage Canceled and the donation goal amount ranges.  For the data analyzed, there are no canceled Play campaigns and only indicates Percentage of Successful and Failed cases.  Donation goal <$20,000 shows a higher successful percentage; as the goals increase >$20,000, the percentage of failed cases increase.  There are a few cases (4) in the $35,000 - $39,999 range that are successful and maybe exceptions.  The lowest success and highest failed percentage is found at $45,000 - $49,999 where all cases failed.

### Challenges and Difficulties Encountered
The challenges and difficulties I encountered were mainly related to being a novice at CountIFS and spent time on manual 'clean up' of the formula for each row.  I did spent a majority of time for this project ensuring each line is accurate and for ranges that are at the amount requires '=>' to include both the number at the range and above.  

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?  Based on the Kickstarter data, launch dates in May & June has the highest success rate.  The lowest success rate is in December.  From this information, May & June may be the better months to launch the Kickstarter campaigns. 

- What can you conclude about the Outcomes based on Goals?  Using the information derived from outcomes based on goals analysis, there is a 100% failure, 0% success rate when goals are set between $45,000 - $49,999.  At >$50,000, there's only a 16.67% success rate.  From this information, there's a higher chance of failure if the goal is greater than $45,000.  This goal may be too high and unrealistic.

- What are some limitations of this dataset?  This dataset captures Kickstarter campaigns from 2009 - 2017, not to current date and may not have the latest data to understand the current donation projections that may be affected by COVID-19 and theater/play restrictions.    

- What are some other possible tables and/or graphs that we could create?  The data set includes other subcategories for Theater and can create similar pivot tables to show outcomes based on launch dates.  Using similar analysis for outcomes based on goals, we can also create outcomes based on actual pledged amount.  Another analysis that may be helpful is to compare the goals vs pledged amount for the interested category/subcategories to understand if there is a relationship between the 2 variables and what goal amounts may yield closer to pledged amounts.
