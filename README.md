# Kickstarted-Analysis
Preforming analysis on Kickstarter data to uncover trends

## Overview & Purpose of Project

Using the data from the Kickstarter dataset my moal was to analyse and visualize campaign outcomes based on their launch dates and their funding goals.

## Analysis and Challenges

### Analysis of Outcomes Based on Goals

To form this analysis we first needed to compile data on the outcomes of the kickstarter campaigns based on their financial goals and start dates. This was done using both general data filters and COUNTIFS() formulas to calculate the number of successful, failed, and cancelled projects. The COUNTIFS() statements and parameters proved a little tedious as using the ><= operators had to be accompanied with "" so that Excel did not missinterpret them as formulas. After some trial and error I was able to make the data populate. After calculating the total nuber of successful, failed, and cancelled projects I made some simple percentage calculations that would then be used in the Outcomes Based on Goal line chart. 

### Analysis of Outcomes Based on Launch Date

For the Theater Outcomes based by launch date I created a pivot table from the Kickstarter dataset. I obtained data pm successful, failed, and canceled projects by filtering my pivot table by parent category "theater". Data found is listed in the Outcomes Based by Launch PNG file. This data was then made into a pivot chart labeled Theater Outcomes Versus Launch.

## Results

What are two conclusions you can draw about the Outcomes based on Launch Date?

Based on launch dates we can conclude that for Theater venues May-August seem to be the most successful months for campaigns. We can also conclude that relative to the time of year you are likely to see roughly the same amount ouf failed projects year round. This alludes that there may be more information needed to make an educated analysis on failed events. 

What can you conclude about the Outcomes based on Goals?

Gernerally, there is a lot more success with projects the smaller your goal is. It also happens that less projects are attempted at higher goals for this purpose. 

What are some limitations of this dataset?

The more data that you have the more accurate your results are going to be. Bacause less projects are attempted at higher goals, we do not have realy as much data to base these assumptions off of. For example, 85% of all projects attempted had goals under $10,000. The percentages we have available are much more accurate for these goal ranges. The data analysis is also filtered only to theaters and plays. Including the full data analysis may prove to show us different trends. 

What are some other possible tables and/or graphs that we could create?

There are a lot of other charts and tables that we can create to help visualize this data. We only focussed on outcomes filtered via Goals and Launch Dates. We did not include analysis on country, staff picks, backers, and length of campaigns.
