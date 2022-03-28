# Kickstarter-analysis
Performing analysis on Kickstarter data to uncover trends
## Overview of Project
       Louise organized a fundraising to raise $295,956,469.81 for the play Fever The fundraising campaign took place from 2009 to 2017, around 4114 campaigns events. The fundraising was held in 21 countries, 73.9% of all the fundraising took place in the USA. The target of the campaigns was across 9 categories divided into 41 subcategories with a pledged amount $ 46,173,741.66. Based on the outcome, out of 4114 campaign events 2,185(53.1%) were successful, 1,530 (37.2%) campaign events failed, 349 (8.5%) campaign events were cancelled, and 50 (1.2%) campaigns events were live. The focus of this assignment is to analyze the category “theater” and the subcategory “plays”

### Purpose
       The purpose of this assignment is to help Louise insights on how the theater category in the “plays subcategory fared in relationship to launched dates and funding goals.

## Analysis and Challenges
       The initial step consisted of find how many rows and columns the data had, what types of data were present and if the data was readable. The initial data had 14 columns and 4,115. Theater was the category with the highest number of campaign events 1,393 events in total (33.9% of the overall fundraising).  Theater included 3 subcategories: “musicals” (3.4% of the overall campaign events), “Plays” (25.9% of the overall campaign events),” Spaces” (4.55% of the overall campaign events). The goal of the theater category was set at $65,236,770 (22 % of the overall goal’s amount) only $ 5,731,796 (12.4% of the overall pledged amount) was pledged. 

### Analysis of Outcomes Based on Launch Date
The launched date and deadline time was converted from Unix Timestamp to a readable human date using Epoch Converter - Unix Timestamp Converter. To split the text in the Category & Subcategory into parent and subcategory using How to Split Text in Cells with Flash Fill in Excel - Excel Campus.
The theater outcomes based on launched dates, there were 1,369 campaigns events,839 (61,3%) were successful, 493(36%) failed and 37 (2.7%) canceled. 33.4% of the campaign events took place in summer between May and July. No event was cancelled in October. Most of the cancelation happened in January.
![Theater_Outcomes_vs_Launch.png](path/to/Theater_Outcomes_vs_Launch.png)

### Analysis of Outcomes Based on Goals
The step to build the required deliverable was to use countifs formula COUNTIFS function (microsoft.com) and SUM formula.
The outcomes based on goals had the total of 1,064 projects with a goal assign into 12 range prices. The price range of 622 (89.6%) out of 694 successful projects was below 9999. The price range of 267(75.6) out of 353 failed projects was below 9999.

### Challenges and Difficulties Encountered
       One of the challenges is that the assignment focused only on one category out of nine categories, it is important to know on what criteria Louise set up the goal and how did she decided to choose the different categories. To have a better understanding an overall breakdown of the fundraising campaigns, to better understand the relationship between the variables.

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?
61.3% was successful, $65,236,770 (22 % of the overall goal’s amount) only $ 5,731,796 (12.4% of the overall pledged amount) was pledged.
Although theater had the highest number of campaign events, it did not materialize in term of $ amount pledge. For next time Louise need to shift the resources assigned to the theater category to a more lucrative category in term of $ amount pledged category
- What can you conclude about the Outcomes based on Goals?
The price range of 89.6% of successful total projects was below $9999.  
- What are some limitations of this dataset?
What was the cost of organizing each event?
What were the criteria to determine that an event was successful or failed?
- What are some other possible tables and/or graphs that we could create?
A pivot table showing the goal set for each category and the total amount pledge for each category and the percentage.
