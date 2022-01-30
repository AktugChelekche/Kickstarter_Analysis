# Kickstarter_Analysis

## Overview of Project:
In this project we are trying to help Louise and her fundraising goal in a short amount of time. She wants to know how different campaigns fared in relation to their launch dates and their funding goals. Bu using the Kickstarter dataset we have visualized campaign outcomes based on their launch dates and their funding goals. With this visualization, she will be able determine that  there are few components she needs to condiser such as " Which month(s) of a year is best to launch a fundrasing" , " The relation between Lauch Date and fundraising Category/Golas." 

### Analysis  
The data we have received from her was not clear enough to analyze it so that we have to make some adjusments in order to provide with a better analysis and visulations by following:

 * First, we created " Date Created Conversion " to make date readable by using formula : =(((J2/60)/60)/24)+DATE(1970,1,1)
 * Second, we extract the year from Date Created Conversion  by using fourmula : "Year()"

 #### Visualize campaign outcomes ("successful," "failed," and "canceled") based on launch date
 First target is the visualize the correlation between Campaign Outcome and Launch Date. To obtain the desired results we have followed below steps:

* Created new worksheet with pivot table which is names as "Theater Outcomes by Launch Date."
  * Filtered the table by "Parent Category" and "Years."  
  * Filtered the column labels to show only "successful," "failed," and "canceled."
  * Count of Outcomes cotegory by months then create line chart to demostrate the relation between date and ourcomes. 
<br><br/>
 <p align="center"> <img src= "https://user-images.githubusercontent.com/60187022/151681917-3ea73ec0-5fac-4f97-8943-96ddbcbccbbc.PNG" width="400" height="200" /> <img src="https://user-images.githubusercontent.com/60187022/151681546-cc603aa7-bca4-42e6-bb7d-fb83c4cc0ae0.PNG" width="400" height="200"/> </p>

#### Challenges:
The challenge for me in this part to how to filter the rows by month instead of year and remove sub dates but I figured out how to clean the pivot table by swithing among tables.  
    
 
