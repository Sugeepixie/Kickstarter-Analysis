# Kickstarter-Analysis

## Overview of Project
Louise wants to start a crowdfunding campaign to raise fund for her play 'Fever' with a budget of $1000.00. She seeked help to analyze the crowdfunding data based on launch dates and Goals and its influence on campaign outcomes.The purpose of this project is to find factors that can help set Louise's crowdfunding campaign to success.

## Analysis and Challenges
* Created pivot tables and line charts to visualize and analyze the filtered data set
* Performed two sets of analysis
 - Outcomes Based on Launch Date
 - Outcomes Based on Goals


### Analysis of Outcomes Based on Launch Date

This analysis helped to understand campaign outcomes based on Launch date of the campaign. Since Louise's interest was towards Theater, the data was filtered by Parent Category. To create a time line added Years to the filter. Created a Pivot table with launch date in rows, Outcomes "sucessful", "failed", "canceled" in columns and count of outcomes in values. Using the pivot table, created a line chart with Theater as parent category. Refer to the chart below to analyze the dataset.

[Theater_Outcomes_vs_Launch](Resources/Theater_Outcomes_vs_Launch.png)

![Theater_Outcomes_vs_Launch](https://user-images.githubusercontent.com/76926148/184510866-6bc5dbc3-be61-4468-a642-1b9ea6e4bf84.png)

From the initial analysis based on launch date, month of May and June seems to be popular month with highest number of successful theater campaign
The the theater campaign seems to be be at the lowest in december where it is close to the highest failed number

### Analysis of Outcomes Based on Goals 

* This analysis helped to understand campaign outcomes based on goals. To achieve this, Goals were broken down to ranges in rows and number of successful, failed, canceled campaigns were calculated for each range in columns. Since Louise's interest was towards plays, the data was filtered by subcategory "Plays". The percentage of successful, failed, and canceled projects was calculated for each row.

* Created a line chart using Goals, Percantage Successful, failed and canceled columns. Refer to the chart below to anlayze the dataset 

[Outcomes_vs_Goals](Resources/Outcomes_vs_Goals.png)

![Outcomes_vs_Goals](https://user-images.githubusercontent.com/76926148/184510798-ca837e29-22dc-4146-a739-3f49edce7c07.png)

### Challenges and Difficulties Encountered

When creating line chart for Outcomes based on Goals, I first created a pivot table to generate the chart. The order of goal ranges in the table were difficult to put in order because of the way its written, ascending and decending didnt seem to work in my favor.The chart was not matching the expected outcome in the module. There was no way I could sort it in the table.  Then found that a chart can be created without a table by slecting the desired columns and selecting line chart under the recommended charts which solved my problem and things were in the given order and matching the expected picture. 

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?

* The highest amount of successful Theater campaigns were launched in May and second highest in June.
* Month of October did not have any cancellations.

   My recommendation would be to start Louise's campaign in May.


- What can you conclude about the Outcomes based on Goals?


* Higher the goal range, lower the number of campaigns with in that range and vice versa 
* 1000 to 4999 range has the highest number of Plays campaigns and 73% were successful

   My recommendation would be to set lower goal range (realistic goal) to achieve success. 

- What are some limitations of this dataset?

* Factors like Backers count, countires, and pledged amount are not included to see how these factors affect the outcome !


- What are some other possible tables and/or graphs that we could create?

 * Other possible dataset could be a pivot table including different catogeries/subcatogeries, backers count, pledged amount, and outcomes to see which campaign most people went to and its outcome ! A line chart simliar to Outcomes based on Goals can be created "Outcomes based on Backers count"
