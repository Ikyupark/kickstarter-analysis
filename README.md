# Kickstarting with Excel
## Overview of Project 
### Purpose
The purpose of this analysis was to investigate how each campaigns in different categories resulted in relation to their outcomes based on launch dates and funding goals. Using the data of kickstarter, It was able to investigate the outcomes based on the launch dates and funding goals. 

---

## Analysis and Challenges
### Analysis of Outcomes Based on Launch Date 
There were two total analysis conducted, which are analysis of outcomes based on launch date and outcomes based on the goals. For analysis of outcomes based on launch date, pivot table and pivot chart were created in order to carefully look at the outcomes based on Launch date. First of all, pivot table was created from the data set where "parent cateogry" and "years" were filtered. Since the main goal was to analyze the outcome of theater from the parent category based on the launching date, "Date created conversion" went to the rows sections whereas "outcomes" was put into the columns section. Furthermore, parent category was filtered  so that the trend of theater could only be shown. Afterwards, pivot chart was created to visualize the the overall trend of the outcome based on the launching date, line graph was used since it shows the trend clearly. 
### Analysis of Outcomes Based on Goals
For the analysis of outcomes based on goals, the function CountIFS() was mostly used to gather each data of "number successful", "number failed", "number canceled" in order to visualize the overall trend of each three outcomes on the created "goal" ranges. The function of COUNTIFS was well used, it was used as =COUNTIFS(goal column,"range of goal",outcome column,"successful, failed or canceled"). Afterwards, the function =SUM() was used to gather the total projects on each goal range, then the percentage of each outcome on each goal range was created by dividing each number of "number successfull" by total projects on each goal range, and this was repeated for gathering the percentage of number failed and the percentage of number canceled. Lastly, line graph was created by selecting the goal range as x-axis and the percentage of each outcome as Y-axis. 
### Challenges and Difficulites Encountered
Throughout the analysis, the data looked little confused since there was another outcome called "live", and this was not included in this analysis. In order to check whether there was no problem in finding the number of each outcomes, I firstly found the number of total projects before using CountIFS.  It was found out that the total project was not equal to the each total project on each goal range, which I personally found out that it was challenged. Thanks to the filtering option, I was able to find out that there were four outcomes instead of three, which I overcame the challenge. Also, the function =CountIFS() was not familiar since it was used for the first time. I made several mistakes by forgetting the "" mark at the each value after inserting the "criteria range". However, through multiple practices, it got used to it and it was overcame quickly.

---
## Results
### What are two conclusions you can draw about the Outcomes based on Launch Date?
From the line graph that shows outcomes based on launch date, there were significantly more successful goals than failed or canceled goals, where successful goals almost double failed and canceled goals. (number of successful = 61.2% and number of failed and cancled goals 36%). Also, there were almost zero number of canceled goals where number of the canceled goals had only 2%. However, the trend also shows that number of successful goals signifcantly went down as the season gets to the winter and this is best explained at the December row, where the number of successful goals were equal to the number of failed goals. Possibly, it could be explained by the weather effect where people might not be interested in theater during winter season, which could affect the result of the goal.
### What can you conclude about the Outcomes based on Goals?
From the line graph of outcomes based on goal, it is well displayed that lower range of goal resulted in high successful goals, but it steeps down as the goal range become larger. Conversely, the lower range of goal resulted in low and very low failed and canceled goals respectively, but it goes up as the the range of the goal become larger. Therefore, it was concluded that number of successful goals go down as the goal range goes up, whereas number of failed and canceled goals go down as the goal range goes up.
### What are some limitations of this dataset?
In this data set, the outliers were shown where there were several goals that aimed at more than milions of dollars which resulted in failed or canceled, and I thought it could accidentally increase the percentage of failed and canceled goals on highest goal range. Furthermore, since the dataset includes different countries, this analysis did not investigate how each country differs in terms of outcomes based on goals or launching date. 
### What are some other possible tables and/or graphs that we could create?
For the analysis of outcomes based on the launch date, 100% stacked column could also be used since it clearly shows the percentage of each outcomes based on the launching date. For the analysis of outcomes based on goals, clusterd column could be used to easily compare the percentgae of each outcomes based on the goal ranges, which it also shows the trend of each outcomes. 

---


