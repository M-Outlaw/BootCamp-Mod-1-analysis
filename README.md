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

- Since Louise is creating a campaign for a theater project, a graph was created of the outcomes for theater projects only to better visual the data.


<p align="center">
<img src="https://github.com/M-Outlaw/BootCamp-Mod-1-analysis/blob/main/Theater_Outcomes.png" width="572" height="418"/>
</p>

- Further narrowed down to the outcomes of all play projects.

<p align="center">
<img src="https://github.com/M-Outlaw/BootCamp-Mod-1-analysis/blob/main/Theater_Outcomes.png" width="572" height="418"/>
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
- Since Louise 

![GB Musical Boxplots](https://github.com/M-Outlaw/BootCamp-Mod-1-analysis/blob/main/GB_Musical_Stats.png)

### Analysis of Outcomes Based on Launch Date


![Outcomes Based on Launch Date](https://github.com/M-Outlaw/BootCamp-Mod-1-analysis/blob/main/Theater_Outcomes_vs_Launch.png)

### Analysis of Outcomes Based on Goals


![Outcome Percentage by Goal](https://github.com/M-Outlaw/BootCamp-Mod-1-analysis/blob/main/Outcomes_vs_Goals.png)

### Challenges and Difficulties Encountered

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?

- What can you conclude about the Outcomes based on Goals?

- What are some limitations of this dataset?

- What are some other possible tables and/or graphs that we could create?


