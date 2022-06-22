# Kickstarting with Excel

## Overview of Project

This analysis of kickstarter data was conducted to determine how campaigns performed. Excel was employed to analyze over 4000 campaigns based on start dates and success or failure in meeting stated goals. The main focus of the analysis was campaigns that fell within the theater category, specifically plays.

### Purpose

The purpose of the analysis was to assist a new campaign in launching successfully and setting attainable goals. The campaign creator, Louise, wanted to know what she could do the ensure that her campaign did not fail.

## Analysis and Challenges

Data was analyzed, filtered, and sorted in the main worksheet before being separated out into individual pivot charts and pivot charts. These tools were employed to find trends among successful campaigns.
<img width="1084" alt="Subcategory_Statistics" src="https://user-images.githubusercontent.com/106691255/174960458-7a57e695-08e8-4d86-a3e9-aa49d142b6be.png">

Using conditional formatting, the campaigns were sorted using color in order to quickly identify whether they succeeded, failed, or were cancelled. Since Louise planned to launch her campaign in the United States, the data was further filtered to only include those created in the US.
<img width="991" alt="Theater_Outcomes_US" src="https://user-images.githubusercontent.com/106691255/174960783-b69d8df1-cfd4-4c42-be7a-5b8febef2436.png">

### Analysis of Outcomes Based on Launch Date

It was determined that the month in which a campaign launches was indicative of its success. Those lunched in the late spring/early summer (May to July) had a much higher rate of success than those launched in any other month. Alternatively, it was more likely for a campaign to fail if it was launched in the late fall/winter (November, December, January, and March). In fact, campaigns launched in December were just as likely to fail as they were to succeed. It is thus recommended that Louise launch her campaign in May or June.
![Theater_Outcomes_vs_Launch](https://user-images.githubusercontent.com/106691255/174967731-3b715e6d-9f49-402d-b120-97ec8bc9ec6e.png)

### Analysis of Outcomes Based on Goals

By employing the COUNIFS function, the data was analyzed according to the campaign goal and whether or not that goal was reached. Based off of this analysis, it was ascertained that play campaigns with a goal of less than $5,000 were most likely to be successful. Louise would do best to keep her goal below the $5,000 mark.
![Outcomes_vs_Goals](https://user-images.githubusercontent.com/106691255/174967775-4906c323-35fa-46ad-8f11-bd784781a23c.png)

### Challenges and Difficulties Encountered

The only challenge I encountered was by being careless in the execution of functions. While using the COUNTIFS function, I employed the use of ‘copy/paste’ and did not pay close enough attention to what I had and had not updated in a couple of cells. It almost skewed my results, but I carefully double checked my work and noticed the mistake before submitting. 

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?
    * May/June/July is the best time to launch a theater kickstarter campaign. It is most likely to be successful when launch then.
    * Failure is more common in campaigns launched in November/December/January/March. It is not advisable to launch a campaign at that time.

- What can you conclude about the Outcomes based on Goals?
    * A goal of less than $5,000 for a play kickstarter was much more likely to be successful than those with higher goals. 76% of successful campaigns had a goal of $49,999 or less.

- What are some limitations of this dataset?
    * Something that would have been potentially important to know was the general of play. It is possible that dramas faired better than comedies or visa versa. 
    * The outliers in the data set of failed campaigns slightly skewed the analysis. Some of the goals were so high compared to the rest that it threw things off a bit.
    * None of the data is current (within the last four years). It would be important to get more data of current/recent campaigns to see how one would perform today in the current COVID and political climate.
    * It would be beneficial to know which state each campaign was launched in. Geographical location may have played a large part in whether or not a kickstater’s goal was reached.

- What are some other possible tables and/or graphs that we could create?
    * It would be a good idea to create a chart to determine whether the length a campaign was open lent itself to its success or failure.
    * Another possible analysis that could be performed (if we had the data) is to see whether the genre of play had anything to do with the outcome.
