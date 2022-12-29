# Kickstarting with Excel

## Overview of Project
The overview of this analysis was to find any trends in the Kickstarter dataset as far as the campaign outcomes based on their launch dates and funding goals. 

### Purpose
The purpose of this analysis is to help Louise understand how different campaigns fared in relation to her play's launch date as well as their funding goals.

## Analysis and Challenges
In the kickstarter tab, I used conditional formatting to differentiate between the different campaign outcomes based on color. 

Then, I created a new column to figure out how much each campaign made towards reaching their initial goal. I divided the pledged by the goal outcome.

Next, I figured out the average donation to see how much each backer paid on average. I divided pledge by backer count.

I created a Parent category column and a subcategory column in the Kickstarter tab I used a left and right search to fill them in. 

Next, I created a new sheet with a pivot table to see which campaigns are successful, failed, canceled or still live based on parent categories. I put the category in the row, outcome in the column and values, and country in the filter. I made a bar graph based on the those parameters.


[README.md](https://github.com/davis4a6/Kickstarter_Analysis/files/10317281/README.md)

Next, I created a new sheet with a pivot table to see which campaigns are successful, failed, canceled or still live based on subcategories. I put the subcategory in the row, outcome in the column and values, and country in the filter. I made a bar graph based on those parameters.


### Analysis of Outcomes Based on Launch Date
I created a new column for "Date Created Conversion" and "Date Ended Conversion". I converted the date timestamp dates to normal dates using the forumla from the Unix Time Converter. This used the launched at time, divided by minutes/the number of hours/the number of days.

Then, I created another column called years in the Kickstarter tab. In that column I did a formula with the years and the date created conversion column in parentheses. 

After this, I inserted and pivot table with outcome in values and columns, parent category in filters, years in filters, and date created conversion in rows. This gave me the outcomes based on launch date data for the graph. 

### Analysis of Outcomes Based on Goals
I performed this analysis by using the COUNTIFS formula to count how many successfula, failed, and canceled projects were created with goals range given.

### Challenges and Difficulties Encountered
I had a bit more difficulty with the Analysis of Outcomes Based on Goals. I was unsure how to use data from the Kickstarter tab while in the Outcomes Based on Goal tab after creating a pivot table, but I ended up figuring it out. While starting the formula, I clicked over to the Kickstarter tab and seleceted the column I wanted to use and it worked. I just had no clue you could do that. I am also having trouble adding links and images to the README. 

## Results


- What are two conclusions you can draw about the Outcomes based on Launch Date?
1. Campaigns that launched in May were significantly more successful than those that failed
2. n December, the number of campaigns that were successful were close to the number of campaigns that failed.

- What can you conclude about the Outcomes based on Goals?
The higher the goal of the campaign, the less successful they are in reaching that goal.

- What are some limitations of this dataset?
A limitation of this dataset is that we don't know how each campaign was marketing their goal. Not knowing the location could also be a limitation.

- What are some other possible tables and/or graphs that we could create?
Another graph that we could create is a bar graph based on goal and category. This would give us insight into what type of categories were more successful. It could show that some categories are more popular than others. 
