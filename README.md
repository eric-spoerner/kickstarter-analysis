# Kickstarting with Excel

## Overview of Project

### Purpose

This analysis was conducted in order to determine the optimal timing and funding goals for Kickstarter projects related to the theater in the US and Great Britain.  Analysis was compiled for a playwright considering launching a Kickstarter for their coming play.

Data set contains more than 4,000 Kickstarter campaigns launched between 2009 and 2017.  Analysis was conducted using Microsoft Excel.

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date

Data set was segmented by month (irrespective of year), as well as three of the four Kickstarter statuses: successful, failed, canceled.  Data set contains all Kickstarters in the parent category "theater".  Kickstarters that were currently live were ignored for this data.

![img text](Resources/Theater_Outcomes_vs_Launch.png)

### Analysis of Outcomes Based on Goals

For this analysis, the data set was further narrowed down to all theater Kickstarters with the child category of "plays" (this excludes fundraisers for musicals and venues).  Analysis again used the three outcomes (successful, failed, canceled), and segmented goals into numerical ranges in intervals of $5,000.

![img text](Resources/Outcomes_vs_Goals.png)

### Challenges and Difficulties Encountered

Data required cleanup in order to properly segment the subcategories within the theater category, as categories and subcategories were bundled in one data point.

## Results

### Conclusions on Seasonality

Based on the analysis, May is the most successful month for launching theatrical Kickstarters, with 111 successful Kickstarters, followed by June with 100.  Late spring and early summer is the most successful campaign season.  

December is the least successful month for Kickstarter campaigns, potentially due to either crowding out from holiday season spending, or seasonal trends in the theatrical industry causing limited interest in fundraisers immediately after the busy fall theater season.

Monthly failure counts only vary slightly throughout the year, so there is no timeframe for campaign launch that will eliminate risk of a failed campaign.

### Conclusions on Goal Size

Generally speaking, the smaller a campaign's goal amount is, the more likely it is to succeed.  Kickstarters with funding goals less than $20,000 all have at least a higher than 50% success rate, with campaigns less than $1,000 having a 75% success rate, and only decreasing narrowly to 73% for campaigns with goals between $1,000 and $5,000.

Small sample size for larger campaigns (>$20,000) limits what we can glean from the data; while Kickstarters between $35,000 and $45,000 have a 66% success rate, this is based on a total of 9 Kickstarters.

Cancellations appear to be highly unlikely and should not be expected; out of a total of 1,047 total Kickstarters in the "plays" subcategory, none have been cancelled.

### Data Limitations

For the purposes of this analysis, any data regarding the play's genre would presumably be helpful in further targeting as there may be a material difference in success rate or funding levels of comedies, dramas, etc.

Further data regarding the subsequent outcome of funded plays (revenue, attendance, etc) could help further determine the efficacy of the fundraisers.

### Other Possible Studies

Other unexplored avenues for analysis include:
* a study of success rates vs campaign duration
* year-over-year trends in success rates, both annually and monthly
* study of actual funding amounts for failed kickstarters 



