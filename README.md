# Kickstarting with Excel

## Overview of Project

 - Create a report based on different projects to check how the outcomes for the theater subcategory behaved throughout the months, considering the historical information and only those which were successful, canceled and failed. 
 - Also, generate and analyze the percentage of plays that belong in different goal ranges to explain how many succeeded, failed and were canceled in each range.
 
### Purpose

 - The purpose of this project is to analyze the outcomes for the Theater category based on the launch date. Drill down to the plays subcategory to check on the compliance percentage for three outcomes based on the goal of each Kickstarter and show the results obtained graphically to have a more objective, clean, and easy-to-understand analysis.

## Analysis and Challenges

 - Based on what Louise wants no know, we need to go through specific data, this includes the Theater category and the plays subcategory. I will need to look for possible trends and explanaitions that can justify the results that Louise obtained and get to a tangible conclusion.

### Analysis of Outcomes Based on Launch Date

 - After reviewing the database, I performed an analysis with different variables. The first thing I needed to know was how many projects in the theater category were successful, failed, or canceled since the record started. To do this, I made a pivot table to extract the number of plays that belonged in each category and arrange them by month. After this table, I created a new graph to display the results in a graphic and friendly way. The outcome is the next:

  - ![Theater_Outcomes_Vs_Launch](https://user-images.githubusercontent.com/113459001/193116688-95b4c427-8c93-4b9c-8972-f25e9b2efc1a.png)

 - As the graph shows, the most amount of projects are successful, being May, the highest record month. The canceled projects are the least and, in October, there were no projects with this outcome. We can also see that the failed projects are quiet constant, the variation month after month is not as big as in the successful outcomes. Finally, we see three peaks in the data located in February, May, and October, so we could conclude that those are the months with more volume throughout the year.

### Analysis of Outcomes Based on Goals

 - I needed to check the percentage of failed, successful, and canceled projects that belonged in the plays subcategory. I performed a count of the records arranging them in different goal categories to analyze how many projects were in each outcome category and calculate the compliance percentage of them. The graph presented the next results:

  - ![Outcomes_vs_Goals](https://user-images.githubusercontent.com/113459001/193118215-24ed1913-7df2-426c-9366-6b4fe8d5af0d.png)

 - As seen in the graph, the worst range for a successful outcome is "45,000 to 49,999" every single record failed in this category. The best range for a successful outcome is "Less than 1,000" meaning that the cheapest goal is the one that succeeds the most for the plays subcategory. Finally, we can conclude that on average for the plays subcategory, more than 50% of the outcomes will be failed, 43% successful and 0% canceled.

 
 *Every procedure made and graphs are in the excel sheet attached below*
  - [Kickstarter_Challenge.xlsx](https://github.com/smanon97/kickstarter-analysis/files/9679173/Kickstarter_Challenge.xlsx)


### Challenges and Difficulties Encountered

 - In terms of the challenges, I think the most difficult thing is finding an explanation that can link the results with the question, being able to know what you are doing, and the meaning of every column and variable. Also, I needed some assistance with the IFS(), not a tough one, but I had to look at the hint to check if my formula was misspelled.

## Results

- **What are two conclusions you can draw about the Outcomes based on Launch Date?**

 - The projects are more likely to succeed if they are launched between May and August. In this case 44.1% of the successful projects are launched in this period of time.
 - There is a very low possibility that a theater project is cancelled but you have to be careful with them, almost 40% are failed projects, the best month to launch one is May, out of 166 projects launched, 111 succeeded.

- **What can you conclude about the Outcomes based on Goals?**

 - Based on goals, more than 30% of the plays had a failed outcome, being the "25,000 to 29,999" and "45,000 to 49,000" the ones with more failure percentage. The category with more projects is the "15,000 to 19,999" with a succession percentage of 66%.
 - The category with the best succession percentage is "less than 1,000" with a 75% of success. 
 - You actually have a pretty good chance of success staying below 26,000 in case you go over, there is a greater chance of failure.

- **What are some limitations of this dataset?**

 - The dataset is a bit complex due to long names, such as the columns of "name" and "blurb". Some of the columns are not exactly clear, so you will nedd to have a brief explanation od them before starting to work. Also the fact that the information in the dataset is not homologate, there are spaces in some places and in others there are not, there are lots of upper and lowercase mixed, it is a pretty "dirty" dataset but you can get a lot of information from it.

- **What are some other possible tables and/or graphs that we could create?**

 - With the information we are given, we could have graphs of every category and subcategory by Country; which country has a better compliance percentage; the average time between launch and deadline; track the major influencers of every outcome; percentage of pleadged over goal; revenue by year ad country; total amount of projects by outcome; which category and subcategory is better in what range of goal; average donation by year and country; average percentage funded by year and country; sum of backers by project, year and country; number of projects with staff pick; among many others.

 The information that you can obtain from a dataset is everything you can imagine, there is almost no limit, and when you begin to transpose different databases is an even bigger universe of possible combinations, KPI´s, tables and graphs
