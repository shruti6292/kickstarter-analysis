# kickstarter-analysis
Performing analysis on kickstarter data to uncover trends
Kickstarting with Excel


## Overview of Project
            Practice of Excel using Pivot Table and some great functions .      

### Analysis of Outcomes Based on Launch Date
•	Create new column "year".
•	Use function “=YEAR(T2)” based on column Data Created Conversion(T)
•	Create Pivot Table in new worksheet
•	Add Parent Category and Year in to the filter field
•	Outcomes in column and month in row
•	Finally add count of outcome in values
•	Using pivotable Analysis add “Clustered column”
•	Use some filters to make table more informative
•	Save the table in Paint with “TheaterOutcomesByLaunchDate.png”
         

### Analysis of Outcomes Based on Goals
•	Create new worksheet with the name “Outcome Based On Goals”
•	Add new 8 rows as below:
	Goal
	Number Successful
	Number Failed
	Number Canceled
	Total Projects
	Percentage Successful
	Percentage Failed
	Percentage Canceled
In Goal column created range as per requirement
•	Use COUNTIFS() function
        =COUNTIF(Kickstart!A2:A13,”<1000”,KickstartR2:R13,”Play”)
•	Use =SUM(B2:D2) to add values in Total Parojects
•	Finally Create Line Chart based on this information
•	Save that line chart named “Outcome Vs Goals”




### Challenges and Difficulties Encountered
           Major challenge I faced in Outcome Vs Goals for using COUNTIF() Function and Percentile Function to create values for columns.



## Results
•	Theater Outcomes By Launch Date
•	Outcomes Based on Goals
•	

- What are two conclusions you can draw about the Outcomes based on Launch Date?
1.	Count of Outcomes
2.	Outcomes by Date and months

- What can you conclude about the Outcomes based on Goals?
      Percentile Vs Range of the data

- What are some limitations of this dataset?
   We can only create dataset using different functions

- What are some other possible tables and/or graphs that we could create?
•	Bar chart
•	Line chart
•	Pie Chart

