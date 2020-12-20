# Kickstarting with Excel

## Overview of Project

### Purpose

The purpose of this analysis is to determine and visualize how different theater campaigns fared in relation to their launch dates and funding goals. Prior to this analysis, we discovered that theater campaigns account for the majority of Kickstarter campaigns, and appear to also be the most successful.

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date

![Theater Outcomes Based on Launch Date](/resources/Theater_Outcomes_vs_Launch.png)

Here we filtered our data to help us visualize which month showed the greatest success in theater campaign launches. We then calculated the number of successful, failed, and canceled campaigns for each month.

### Analysis of Outcomes Based on Goals

![Theater Outcomes Based on Goals](/resources/Outcomes_vs_Goals.png)

We wanted to discover where an ideal funding goal should be set in order to obtain success in a theater campaign launch. We calculated the number of successful, failed, and canceled campaigns within a set goal range. Our graph shows the success rate percentage of each goal range.

### Challenges and Difficulties Encountered

I personally ran into a difficulties analyzing the "goals" data - namely, with the COUNTIFS function. Incorrectly set criteria were causing the number of successful and failed outcomes to appear strangely high. Once I corrected the criteria, the visualization 
took shape to reflect accurate results.

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?

The most successful month to launch a theater campaign is May, with June a close second. The least successful months to launch a theater campaign are May and October. We can also see that there are almost twice as many successful theater campaigns than failures.

- What can you conclude about the Outcomes based on Goals?

The majority of projects set a funding goal of $1000-$4999, and the vast majority of these projects were successful (86%). Projects with a funding goal of less than $1000 also showed great success at 76%. 

- What are some limitations of this dataset?

We cannot determine other factors that influenced the failure of theater campaigns. Funding goal and launch date are clearly two pieces of a bigger picture that we can't fully see. Also, the dataset has outliers - there are very few theater campaigns with goals ranging from $25,000 to greater than $50,000.

- What are some other possible tables and/or graphs that we could create?

Looking at the Kickstarter dataset as a whole, we could compare success/failure rates across campaigns between different musical genres, for example, the success rate of jazz campaigns versus metal campaigns. Or, we could look at the outcome based on funding goals for documentary film campaigns versus animation film campaigns.
