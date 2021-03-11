# Launch Date and Funding Goals analysis for "Fever" (a play) by Louise

## Overview of Project
Following analysis of the outcomes of various Kickstarter campaigns based on their industry category (e.g., food, music, theater) as well as seasonal trends, Louise would like to look at additional data to determine whether and how outcomes are affected by campaign launch dates and fundraising goals.

### Purpose
The purpose of this analysis is to make recommendations regarding 1) the campaign launch dates/timeframes most conducive to the campaign's overall success, and 2) the funding goal ranges most closely correlated with successful campaigns.

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date

![Theater_Outcomes_vs_Launch.png](https://github.com/crkaide/kickstarter-analysis/blob/main/Theater_Outcomes_vs_Launch.png?raw=true)

### Analysis of Outcomes Based on Goals

![Outcomes_vs_Goals.png](https://github.com/crkaide/kickstarter-analysis/blob/main/Outcomes_vs_Goals.png?raw=true)

### Challenges and Difficulties Encountered

No significant challenges or difficulties were encountered in preparing this report.  There are no anomolies in the results to highlight.  While this is a robust data set, records span the years 2009-17.  Therefore, no COVID-19 impact is assessed.  For the most accurate analysis, data post-dating Dec. '19 is recommended.

## Results

### Theater Outcomes Based on Launch Date
1. The greatest number of successful campaigns are launched in May, and the count declines throughout the summer:  in June (which is the recommended launch time over all other months except May) and July (which is recommended over all other months except May and June).
2. The greatest number of failed campaigns are also launched in May.  However, the increase in "failed" in this month is not nearly as significant as the increase in "successful" in this Month, and more than offsets the risk indicated in this statistic.
3. Although there are marginally more canceled campaigns that launch in December than any other month, launch date does not appear to have a significant impact on whether a campaign is canceled.
4. Launch date has a greater impact on successful campaigns than on failed or canceled campaigns (ie, the count of successful campaigns is more volatile than the other counts).

### Outcomes Based on Goal
1. The greatest share of successful campaigns are either low-budget  (<$1,000) or relatively high-budget ($35,000-44,999).
2. Success declines and failure rises as the budget increases from $1,000 until there is a sharp increase in share of successful campaigns at $35,0000.
3. Percentage successful and failed are inversely proportionally related, while canceled is unaffected by the fundraising goal.

### Limitations
The greatest limitation is the age of this data, and particularly that all records pre-date Dec. '19.  Therefore, we cannot take into account the impact of COVID-19.  There is also significant disparity between the counts of available data points for each year (MIN=14 in 2009, MAX=1225 in 2015, most recent year is 2017 with 157 records).  Data from three years--2014, 2015, and 2016--could have a disproportionate impact on some results based on the volume of records contained in these three years (3151 records) against the volume contained in the six other years in the data set (963 records).

### Additional tables and graphs recommended
1. Count of records by year (to inform weighting of years or filtering out of records)
2. Success by length of campaign (number of days)
3. Average donation by launch date
4. Average donation by campaign length
5. Success by "Staff Pick" status
