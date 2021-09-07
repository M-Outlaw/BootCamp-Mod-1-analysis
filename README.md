# An Analysis of Kickstarter Campaigns
Performing analysis on Kickstarter data given in Module 1 to uncover trends
## Overview of Project

### Purpose
The purpose of this analysis to use Kickstarter data to help determine the best funding goal and month to launch a successful campaign to fundraise for an upcoming event.

## Analysis and Challenges
### Data
The analysis started with examining the data obtained from Kickstarter. The first think to notice is that Kickstarter provided a very large data set. This is great, since more data allows for a more thorough analysis and the ability to see largescale trends. The first thing to notice about the data is that not only does it include the campaign’s goal, the amount pledged, and whether the campaign was successful or not, but it included the country in which the campaign took place, the launch date, the deadline, the number of backers the pledged, and the category of campaign.

### Initial Organization
- The data contained the category of the campaign, however it was hard to differentiate because there were an overarching category and subcategories within the same column. This was split into two different columns: Parent Category and Subcategory. 

- While the outcome is important, it is important to look at by how much each project succeeded or failed. This was made more visible by calculating the Percent funded and average donation each backer pledged for each campaign.

- The launch and deadline dates were converted to a more readable format. Also, a column was created, Campaign Days, to see how many days each campaign lasted.

- The year of each campaign was determined from the launch date to quickly be able to filter the data by the year in which the campaign took place.

### Initial Visualization
- To get an initial idea of trends in the data, a pivot table was created to see how the campaigns faired for each parent category. A graph of the data is shown below.


<p align="center">
<img src="https://github.com/M-Outlaw/BootCamp-Mod-1-analysis/blob/main/ParentCategoryOutcomesGraph.png" width="572" height="418" />
</p>

- Since Louise is creating a campaign for a theater project, a graph was created of the outcomes for theater projects only to better visual the data (left). Then, the data was further narrowed down to the outcomes of all play projects (right).


<p align="center">
<img src="https://github.com/M-Outlaw/BootCamp-Mod-1-analysis/blob/main/Theater_Outcomes.png" width="350" height="290"/>&nbsp;&nbsp;
<img src="https://github.com/M-Outlaw/BootCamp-Mod-1-analysis/blob/main/Play_Outcomes.png" width="380" height="290"/>
</p>

### Digging In
- While it is good information to see how many of the theater campaigns succeeded or failed, it does not help much in helping Louise determine when and for how much she should set her campaign. 

- The next step was to look at the launch dates in relationship to the outcome of the campaigns to see if certain months fared better than others, shown below. 
  * From this graph, it can be concluded that by far May had the most success of all of the campaigns.

<p align="center">
<img src="https://github.com/M-Outlaw/BootCamp-Mod-1-analysis/blob/main/DateOutcomesGraph.png" width="573.04" height="345.04"/>
</p>

### Statistics

- Statistics were performed to look for underlying trends.

- The mean, median, standard deviation, and IQR were determined for both the goal and pedged amounts for all US campaigns.
 * The mean goal for successful campaigns was about half that of failed campaigns.
 * The median goal for successful campaigns was $2,000 less than that of failed campaigns.
 * The statistics for successful amounts pledged were similar to those for the successful goals.
 * The statistics for failed amounts pledged were far below the goal, showing that when a campaign failed, it received minimal pledges and not many campaigns came close to their goal.

<p align="center">
<img src="https://github.com/M-Outlaw/BootCamp-Mod-1-analysis/blob/main/US_Goal_Stats.png" width="382.5" height="159"/>&nbsp;&nbsp;&nbsp;&nbsp;
<img src="https://github.com/M-Outlaw/BootCamp-Mod-1-analysis/blob/main/US_Pledged_Stats.png" width="382.5" height="159"/>
</p>

- Since Louise is interested in musicals in Great Britian, the mean, median, standard deviation, and IQR were determined for both the goal and pledged amounts for Great Britian musicals.
 * This further shows that campaigns with lower goals were more successful.

<p align="center">
<img src="https://github.com/M-Outlaw/BootCamp-Mod-1-analysis/blob/main/GB_Musical_Stats.png" width="515" height="400"/>
</p>

### Analysis of Outcomes Based on Launch Date
- By looking at the graph of the outcomes for all of the campaigns, it can be seen that May was the most successful. But we want to confirm that this is also true for the theater campaigns. To confirm, a graph of the outcomes of only the theater campaigns for each month was created. 
 * From this graph, it can be concluded that May had the most success for theater campaigns.

<p align="center">
<img src="https://github.com/M-Outlaw/BootCamp-Mod-1-analysis/blob/main/Theater_Outcomes_vs_Launch.png" width="543.2" height="256"/>
</p>

### Analysis of Outcomes Based on Goals
- Now that we know when the best time would be to launch a campaign, we need to determine the goal amount that would provide the most success. The data for all of the play campaigns was sorted by goal value in increments of $500 and then converted to percentages. The percentages of the play outcomes are displayed in the graph.
 * From this graph, it can be concluded that campaigns with a goal of less than $1,000 were the most successful, but closely followed by campains with a goals of $1,0000 to $4,999, $3,500 to $3,999, and $4,000 to $4,499.

![Outcome Percentage by Goal](https://github.com/M-Outlaw/BootCamp-Mod-1-analysis/blob/main/Outcomes_vs_Goals.png)

### Challenges and Difficulties Encountered
- A challenge I had was understanding which country Louise prefered to hold her campaign. It was confusing to determine if she preferred the US or Great Britian. If I were able to communicate with her, I would discuss this in more detail, because while the trends are similar amoung the countries, knowing this specific detail would allow for a more specific analysis.

## Results

- For a successful campaign, I would suggest Louise launch her campaign in May since May contained the most successful number of campaigns. If May is not possible, I would suggest Louise not launch her campaign in December or January because in December the number of successful campaigns was approximately the same as the number of failed campaigns and in January, while the number of successful campaigns are higher than failed campaigns, the most number of shows cancels also occured this month.

- For a successful campaign, I would suggest setting a campaign goal of $4,999 or less. This is because while campaigns with a goal of less than $1,000 had the largest percent of success, it is only slightly higher than campaigns with a goal of between $1,000 and $4,999. While campaigns of $35,000 to $49,999 had a success percentage of slightly less than those with a goal of $4,999 or less, as seen from the other statistics, lower goal values proved to be more successful.

- A limitation to the dataset is that all of the goals and pledges are given in dollar amount. I wonder if this is an approximation of the converstion of what the goals were in other currencies to dollars. Having the goal and pledged amount in each countries corresponding currencies would provide a more accurate analysis.

- Based on where Louise prefered to hold her campaign, graphs of Outcomes based on Launch Date and Outcomes based on Goals limited to just the target country could provide further helpful information.


