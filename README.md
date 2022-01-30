# Kickstarter_Analysis

## Overview of Project:
In this project we are trying to help Louise and her fundraising goal in a short amount of time. She wants to know how different campaigns fared in relation to their launch dates and their funding goals. Bu using the Kickstarter dataset we have visualized campaign outcomes based on their launch dates and their funding goals. With this visualization, she will be able determine that  there are few components she needs to consider such as " Which month(s) of a year is best to launch a fundraising" , " The relation between Launch Date and fundraising Category/Goals." 

### Analysis  
The data we have received from her was not clear enough to analyze it so that we have to make some adjustments in order to provide with a better analysis and visualizations by following:

 * First, we created " Date Created Conversion " to make date readable by using formula : =(((J2/60)/60)/24)+DATE(1970,1,1)
 * Second, we extract the year from Date Created Conversion  by using formula : "Year()"

 #### Visualize campaign outcomes ("successful," "failed," and "canceled") based on launch date
 First target is the visualize the correlation between Campaign Outcome and Launch Date. To obtain the desired results we have followed below steps:

* Created new worksheet with pivot table which is names as "Theater Outcomes by Launch Date."
  * Filtered the table by "Parent Category" and "Years."  
  * Filtered the column labels to show only "successful," "failed," and "canceled."
  * Count of Outcomes category by months then create line chart to demonstrate the relation between date and outcomes. 
<br><br/>
 <p align="center"> <img src= "https://user-images.githubusercontent.com/60187022/151681917-3ea73ec0-5fac-4f97-8943-96ddbcbccbbc.PNG" alt="Image 1-Pivot Table" width="400" height="200" /> <img src="https://user-images.githubusercontent.com/60187022/151681546-cc603aa7-bca4-42e6-bb7d-fb83c4cc0ae0.PNG" alt="Image 2- Theater Outcomes Based on Launch Date" width="400" height="200"/> </p>


 #### Visualize the percentage of successful, failed, and canceled plays based on the funding goal amount.
 Second target is to  visualize the percentage of successful, failed, and canceled plays based on the funding goal amount such as :

 * Creating a new worksheet with following column :
  * Goal
  * Number Successful
  * Number Failed
  * Number Canceled
  * Total Projects
  * Percentage Successful
  * Percentage Failed
  * Percentage Canceled

 * In the “Goal” column, create the following dollar-amount ranges so projects can be grouped based on their goal amount.
<p align="center"> <img src="https://courses.bootcampspot.com/courses/1122/files/1257752/preview" alt="Image 3 - Goal Column "width="400" height="200" />

 * We  populate the "Number Successful," "Number Failed," and "Number Canceled" columns by filtering on the Kickstarter "outcome" column, on the "goal" amount column using the ranges created in , and on the "Subcategory" column using "plays" as the criteria by formula : COUNTIFS() .

 * After populating percentage columns and total projects by outcome category, finally created a Line Chart that demonstrate Percentage of each outcome category based on their fundraising Goal.

 p align="center"> <img src="https://courses.bootcampspot.com/courses/1122/files/1258221/preview" alt="Image 4 - Outcomes Based on Goal "width="400" height="200" />

#### Challenges:
Visualize campaign outcomes: The challenge for me in this part to how to filter the rows by month instead of year and remove sub dates but I figured out how to clean the pivot table by switching among tables.
Visualize the percentages:  I had skipped the filtering of Subcategory and obtain a graph that is way different than it supposed to be so that I realize that I needed to give more attention of the each details in order to create most accurate visuals. 

### Results 






    
 
