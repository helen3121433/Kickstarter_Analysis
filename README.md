# Kickstarting with Excel

## Overview of Project

### Purpose
- The purpose of this project is to help Louise to see how the outcomes of different campaigns funding related to launched dates and funding goals.

## Analysis and Challenges
- In this project, we're using the pivot table, COUNTIFS() formula to filter and organize the dataset we wanted as a table, then use the chart to visualize the data and make it easier to see.

### Analysis of Outcomes Based on Launch Date
- The chart and dataset for this are to see hows the different parent categories based on Launch Date related to outcomes. The pivot table contains data of Parent Category, Years, Data Created Conversion, and Outcomes from the Kickstarter dataset. We can filter by Parent Category, and years to see how each launched date might affect the outcomes of the funding. 

- The line chart(Theater_Outcomes_vs_Launch.png) shows how theater category outcomes are based on launched date. The chart clearly shows that May is the month that will receive the highest number of successful reaches to goal. October is the month that will receive the highest number of failed reaches to goal. When it comes to December, the number of successes and failures are nearly at the same point. The number of Successful is 37 and the number of failed is 35 in December. This could forecast that the outcome may be half/half if we launch the Theater campaigns in December. May is the month that we might want to consider launching theater campaigns.

- ![](https://github.com/helen3121433/Working_with_excel/blob/main/Theater_Outcomes_vs_Launch.png)

### Analysis of Outcomes Based on Goals
- We use COUNTIF() to see the relationship between funding goals and outcomes. In this tab, we're analyzing about subcategory "plays" in the theater category. 

- Take a rough look at the table, we could see that we have the highest number of projects on funding goal between 1000-4999, and we have the highest successful number on the same goal. Funding goal less than 1000, have the highest percentage of successful reached the funding goal. 

- From the line chart(Outcomes_vs_Goals.png), we can see that percentage of successful (blue) and percentage of failed (green) are nearly opposite on each point. Except, we get 50/50 percentage of successful and fail if the funding goal was between 15000 to 19999.

- Funding goal less than 1000, funding goal from 1000 to 4999, funding goal from 35000 to 39999, and funding goal 40000 to 44999 have higher chances of success as an outcome.

- Funding goals from 20000 to 24999, 30000 to 34999, 45000 to 49999, and greater than 50000 have higher chances of failing as outcome.

- ![](https://github.com/helen3121433/Working_with_excel/blob/main/Outcomes_vs_Goals.png)

### Challenges and Difficulties Encountered
- Challenge is that we must be carefully input the formula right, or it won't show that result as we want. This boot camp provides lessons for us to follow step by step. And it will show the screenshot of the result at the end for us to make sure we did it correctly. However, in the real world, it will be more difficult since we are the one who needs to find out the correct answer, we won't have template steps for us to follow. Therefore, we will need to be careful and always double-check which data we should use, how to input the formula, how to create a pivot table in a better look, and which chart we should use for a better look. 

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?
    - The first conclusion is if doing funding goal with theater category, setting the launched date in May, June and July will get higher chances of successful in reaching the funding goal. The second conclusion is that December is the month that has the least number of successful, and we have the nearly same number of failed.The third conclusion is that October has the highest number of failed, which October is not a good idea to launch funding by theater campaigns.

- What can you conclude about the Outcomes-based on Goals?
    - Conclude that if setting funding goal from less than 1000 to 5000, and funding goal from 35000 to 45000. It could get a higher rate of success. But this could also relate to how many projects there were, if we have a higher number of projects on higher funding goals, it may result in a higher percentage of failed.

- What are some limitations of this dataset?
    - The limitation of this dataset is that we're only compared with two results such as outcome vs launched date, outcome vs funding goal, which I think the comparison could be more detailed. 

- What are some other possible tables and/or graphs that we could create?
    - That are many possible tables and graphs we could make with this large set of data. We could create the outcome based on the deadline date, we could make a comparison of which year we received the better outcomes, We could see the relationship between outcomes and stuff pick, or we could see outcomes based on countries. 

