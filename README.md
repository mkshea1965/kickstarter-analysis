
# An Analysis of Kickstarter Campaigns
Tutorial on performing analyses of Kickstarter data to uncover trends and uploading various types of documentation to github.
---
# Kickstarting with Excel

## Overview of Project
The scope of this project includes a robust analysis of the variables “launch date” and “goals” that may affect whether or not crowdfunding campaigns succeed, fail, or are canceled. The analysis consists of organizing and sorting the campaign data using filters in Excel to assist in creating data visualization models via pivot tables and charts. Doing this facilitates digesting tabular data and can help Louise mirror successful crowdfunding campaigns to improve her campaign’s chance of success. Additionally, we are looking to provide Louise with insight into the musicals market in Great Britain to prepare her for her future endeavors.
### Purpose
The purpose of this project is to help budding playwright, Louise, begin a crowdfunding campaign to help fund her play, Fever. Through an analysis of a crowdfunding campaign dataset using Excel, our goal is to find various trends throughout the campaign lifecycles in the provided dataset to help Louise optimize her campaign’s chance of success. 
## Analysis and Challenges
Louise estimates that the budget of her play to be greater than $10,000 and is aiming to launch her campaign in the United States using Kickstarter. Initially, the Kickstarter data for all parent categories in the United States were analyzed to gauge if her Kickstarter campaign has a relatively good chance of success: 
<p align="center"><img width="241" alt="2ParentCategoryOutcomesUS" src="https://user-images.githubusercontent.com/88520929/130296535-6f61ab4b-ca2a-4d87-8058-982c7a288fc5.png"></p>
<p align="center">Figure 1: Parent Category Outcomes – US<p/>

### Analysis of Outcomes Based on Launch Date
Out of all the parent categories, "theater" is the largest parent category. Additionally, it has the most successful number of campaigns; however, it does not have the highest success-to-failure ratio based on glance alone. 
Since Louise was specific with which theater category she would begin her campaign, further information can be used to her campaign’s advantage:
<p align="center"><img width="241" alt="3SubcategoryOutcomesUS" src="https://user-images.githubusercontent.com/88520929/130296600-7ba010e8-41e8-4f24-a1c4-41797c782098.png"></p>
<p align="center">Figure 2: Subcategory Outcomes – US</p>
As seen in Figure 2, plays - the subcategory of Louise’s campaign – again is the most popular and has over a 50% chance of succeeding. In all, these visuals allow us to make quick conclusions that Louise has a “decent” chance at succeeding; However, further factors should be explored to increase her campaign’s odds.
One of these factors is the launch date of the campaign. The fates of theater crowdfunding campaigns in the United States were analyzed according to the time of year the campaign began:
<p align="center"><img width="241" alt="Theater_Outcomes_vs_Launch" src="https://user-images.githubusercontent.com/88520929/130296630-550f8981-3937-4dad-9468-4a6e3cf63094.png"><p/>
<p align="center">Figure 3: Theater Outcomes Based on Launch Date</p>
According to Figure 3, successful campaign rates peak in May. Failing campaign rates peak in the summer around 50% between the months of May and August and in the month of October. Very little plays are canceled.
<p align="center"><img width="242" alt="1OutcomeLaunchDateTheaterUS" src="https://user-images.githubusercontent.com/88520929/130296697-05afce82-9249-4484-8197-472c77be4fda.png"></p>
<p align="center">Figure 4: Monthly Outcomes Based on Launch Date for Theater for Years 2007-2017 in US</p>
According to Figure 4, success counts of theater campaigns in the United States peaked in May and were generally continuously higher than failure counts throughout the year. June, July, August, February, and October all had roughly the same number of failed campaigns.  This can be determined based on the jaggedness of each line on the graph of Figure 3.
<p align="center"><img width="242" alt="1OutcomeLaunchDatePlaysUS" src="https://user-images.githubusercontent.com/88520929/130296716-fbc83ead-c47d-4a4f-ad2e-416e9f2ec86a.png"></p>
<p align="center">Figure 5: Monthly Outcomes Based on Launch Date for Plays for Years 2007-2017 in US.</p>
As seen in Figure 5, Theater’s subcategory, “plays,” follows roughly the same trend as its parent category. Plays, however, did not have any cancellations.
Utilizing the information from these trends can help Louise choose when to start her campaign. According to the visuals of Figures 3, 4, and 5, Louise can highly increase the likelihood of her campaign’s success if she begins her campaign in May.

### Analysis of Outcomes Based on Goals
Another factor that can be analyzed for Louise is the campaigns’ outcomes based on funding goals. She foresees her production to need more than $10,000 for the campaign to be successful. Initially, the measures of central tendency were calculated to see if Louise's expectations are realistic:
The initial analysis consisted of the campaigns’ fates based on funding goals of the “plays” category, as seen in Figure 6:
<p align="center"><img width="243" alt="Outcomes_vs_Goals" src="https://user-images.githubusercontent.com/88520929/130296755-4f6b6ea9-d760-4a6d-98d3-7685a0f5524a.png"></p>
<p align="center">Figure 6: Outcomes Based on Goals </p>

Figure 6 indicates that having a goal of greater than $10,000 lowers the percentage of success relative to having a goal that is less than $10,000 for the most part. The success rate valleys between $25,000 and $34,999, peaks between $35,000 and $39,999, and plummets above $40,000
Funding goal fate is similar when location is considered:
<p align="center"><img width="240" alt="Outcomes_vs_GoalsUS" src="https://user-images.githubusercontent.com/88520929/130296829-e3ffee72-6e32-423a-aeef-6ecfb6e2b83a.png"></p>
<p align="center">Figure 7: Outcomes Based on Goals – US Plays</p>
The peak success rate for plays in the United States is between $35,000 and $39,999 but quickly crashes above $45,000. Before $35,000, the percentage of success tends to be higher for lower goals.

Additionally, the measures of central tendency were calculated so Louise can gain insight into the theatre market and confidence in her campaign decisions:
<p align="center"Table 1: Measures of Central Tendency for Successful and Failed Funding Goals and Pledges (General)</P>
<p align="center"><img width="265" alt="7MeasuresofCTGeneral" src="https://user-images.githubusercontent.com/88520929/130298081-09cfca78-5b34-46af-bb22-ab830dabbe67.png"></p>

Table 1 shows that the mean goal of failed campaigns aligns with Louise's intended campaign goal. Additionally, the mean goal is higher than not only the median but also the upper quartile! This indicates a positive skew of the data. However, since the means for both successful and failed goals and pledges are around the upper quartile, the data follows a similar distribution in general (1.5.2 Measures of Spread - Findings). Since the standard deviation is greater than the mean, this indicates a widespread of data points and a right skew, so there may be some higher goals and pledges off-setting the data.

### Analysis of Musicals in Great Britain
For her future campaigns, Louise asked us to analyze the trends of musicals in Great Britain. For this analysis, a box and whisker plot was created for trends of musicals in Great Britain:
<p align="center"><img width="455" alt="5BoxWhiskerGBMusical" src="https://user-images.githubusercontent.com/88520929/130298245-a9fd7242-9d99-4768-b772-cf47c1bebc15.png"></p>
<p align="center">Figure 8: Box & Whisker for Goal vs Pledged Amounts in GB for Musical Subcategory.</p>

### Challenges and Difficulties Encountered
As shown in Figure 8, the mean goal amount is $4,000, while the mean pledged amount is around $1,300. The median goal amount is $2,000 while the median pledged amount is around $500. Louise should have her musical produced for no more than $4,000; however, even that goal is aggressive. Realistically, she should have it produced under the median and mean so that it has a high likelihood of getting funded. She should not plan for a big musical production to be crowdfunded in Great Britain. Perhaps a different means of funding would be better if she wants to produce a musical in Great Britain.
## Results
</p>- What are two conclusions you can draw about the Outcomes based on Launch Date?
</p>One conclusion we can make about the Outcomes based on Launch Date Louise is that Louise is more likely to succeed in starting her campaign in May than any other month. Another conclusion we can make about the Outcomes based on Launch Date Louise is that Success is more likely to occur than failure no matter what month the campaign begins, except for December based on success and failure counts. Louise should not start her campaign in December.
</p>- What can you conclude about the Outcomes based on Goals?
</p>We can conclude from the insights gained about the Outcomes based on goals is that Louise should not exceed a $30,000 goal if she aims to keep her “greater than $10,000” production closer to the $10,000 amount. However, for plays produced in the United States, the highest rate of success is between $35,000 and $39,999, with the range of $40,000 to $44,999 not far behind. However, the goal should not exceed $45,000 because the success rate plummets above $45,000.
</p>- What are some limitations of this dataset?
</p>Some limitations to this data set include the lack of play genre. It would be better if we had a mirror example that was successful or not without having to read the “blurb.”
</p>- What are some other possible tables and/or graphs that we could create?
</p>We can create histograms, pie charts and a probability table/matrix. Histograms can be used to visualize the measures of central tendency and spread of the data. Pie Charts can be used for individual category visualization, such as the Parent Category Outcomes (Figure 1) if we wanted to look at the theater category alone. I didn’t find the stacked bar chart as effective when it only represented counts for one category of data; however, I found them more effective at telling a story when there were multiple stacked bar charts to compare. Probability table/matrix with calculated probabilities of success based on various factors such as “Launch,” “goals,” “genre” can show specific probabilities of multi-factor events with ease.
