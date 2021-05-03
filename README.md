# Kickstarting with Excel

## Overview of Project
The purpose of of this project is to take a deep dive into Excel, it's functions and how we can use data to create a visual aid to display our findings about the data we have analyized
For this particular project, we are working with data pulled from previous Kickstarter projects. This projects


### Purpose
The purpose of of this project is to take a deep dive into Excel, it's functions and how we can use data to create a visual aid to display our findings about the data we have analyzed. For this particular project, we helping a client determine when the best time to launch a Kickstarter campaign for her play. We are using data from previous successful, failed and cancelled projects to help Louise determine the optimal time of year to launch a project, how likely her project is to be funded based on similar projects. We are working with data pulled from previous Kickstarter projects. 


## Analysis and Challenges

I faced a few challenges when working through this project. The first challenge I encountered was working with "Outcomes By Launch Date". Although I was able to filter the "Kickstarter" Worksheet correctly, I could not seem to get the Rows and column to accurately populate the information I needed to show the client. I was able to get the correct row "Count of Outcomes, but it would display years and/or quarters. I could not get it to display months, which is a lot more clear visual for what Lousie is looking for. It took some toying around with the PivotTable fields, but I was finally able to put the correct filters a and fields into the appropriate columns, rows, and values to achieve my desired outcomes. I think the biggest thing I learned from the PivotTables is that some field values contain other qualitative data points. For example, moving "Date Created" into the "Rows" I would see years, months and quarters as options to manipulate the table. I learned that if I removed the values or "Years" and "quarters" from rows, my table would then accurately reflect "Months". I encountered a few more issues with placing the correct values into the PivotTable field, and I was able to overcome them by trying to think through what it was I would want to see on a chart such as this and trying to think logically as to how I can accomplish that with the categories I have available. Again, with a little manipulation, I was able finally achieve my desired outcome.


Another difficulty I encounter was working with "Outcomes By Goals". It was my first time working with the "COUNTIF" formula in excel and I didn't quite grasp how to get the formula to accurate display data into the "Numbers Cancelled" and "numbers Failed" columns. I watched a few YouTube videos to see if there was another method I could utilize or if I was somehow missing something in my formula, to no avail. My chart had the same shape as the end goal but the percentage successful for a few data points was incredibly off. To work through it, I cleared all of my filters on the main "Kickstarter" worksheet and started over to see if I made a mistake somewhere. I did this over and over and I still could not see why it was off. Eventually I realized that I had filtered keywords in the wrong place. I had been filtering on the "Kickstarter" worksheet, when in fact, I should have filter out keywords "successful, failed, cancelled, and plays, into my COUNTIF formula. I realized filtering on the main worksheet was not going to change the data the the COUNTIF formula was searching for. Once I corrected that mistake, my line chart accurately reflected the results I was looking for.


### Analysis of Outcomes Based on Launch Date

https://github.com/roderickspells/kickstarter-analysis/blob/main/Resources/Theater_Outcomes_vs_Launch.png

### Analysis of Outcomes Based on Goals

https://github.com/roderickspells/kickstarter-analysis/blob/main/Resources/Outcomes_vs_Goals.png

### Challenges and Difficulties Encountered

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?


The first conclusion I can draw about the "Outcomes Based on Launch Date" is that the most successful Kickstarter campaigns are launched in the Summer time, May being the optimal month. This is likely to people having more free time (college students and/or teachers). Summer time is usually the time of year when people are more active in looking for things to participate in.

The second conclusion I can draw is that Kickstarters launching in the fall are the least successful in shear number of successfully launched as well as those that have failed.


- What can you conclude about the Outcomes based on Goals?

Given that there are not very many projects over the $25,000 range that were attempted, I can conclude that the most successful campaigns were those that less than $1000 up to the $10,000 range. The higher your campaign goal is, the more likely that it would not be successful.


- What are some limitations of this dataset?

I'm not sure how it directly affects the outcome, but one limitation could be that the currency used between the countries have not been standardizes. If we converted all values to one standard, would be able to better asses how successful they were to each other. Seeing as the British Pound outweighs the US dollar, this could lead to some unreliable results. 

- What are some other possible tables and/or graphs that we could create?





- What are some other possible tables and/or graphs that we could create?
