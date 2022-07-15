# Analysis of Play Kickstarter Campaigns
## Overview of Project
   - Using visualization tools (pivot tables and line graphs) to discern patterns in play-campaign data
### Purpose
   - To inform Louise of the number of and percentages of successful, failed, and canceled plays in each fundraising goal range.
## Analysis and Challenges
### Analysis
   - Using "=COUNTIFS()" function to calculate the number of successful, failed, and canceled play kickstarters in each goal range
   - Using "=SUMS(B2+C2+D2)" function to calculate the total amount of projects/plays in each goal range
   - Using "=B2/$E2" function to calculate the percentages of successful, failed, and canceled play campaigns in each goal range![Screenshot for Module 1 Assignment (#1)](https://user-images.githubusercontent.com/109160865/179293569-08312814-240d-484c-89bf-26bac1bb1904.png)
![Screenshot for Module 1 Assignment (#2)](https://user-images.githubusercontent.com/109160865/179293600-a2fd12eb-4f78-4e41-8ec1-9ab6d6a9e2ae.png)![Screenshot for Module 1 Assignment (#3)](https://user-images.githubusercontent.com/109160865/179293756-a241aa51-1cbf-4914-830b-dab92c58b56e.png)
![Screenshot for Module 1 Assignment (#4)](https://user-images.githubusercontent.com/109160865/179293824-c55e956f-f236-47e1-b3c9-6c627e1d7d85.png)
![Screenshot for Module 1 Assignment (#5)](https://user-images.githubusercontent.com/109160865/179293879-4f21abb6-104b-4211-8bba-6ad7819fe064.png)
### Challenges
   - One challenge was ensuring that all parameters were correctly applied to the function, "COUNTIFS()", when calculating the values in each individual cell from B2-D13.  In 
   order to circumvent this challenge, copying the function from cell B2 and pasting it into the above toolbar (in Excel) for each cell following B2 is required.  Next,
   careful attention to detail is necessary in order to eliminate the parameters from the function for B2 that do not apply to the other cells, and replacing the other cells'
   functions with applicable parameters.
## Results
### Two Conclusions for Theatre Outcomes by Launch Date
   - Kickstarter plays are most likely to succeed when launched in May or June, compared to all of the other ten months of the year
   - The chances of a theatre campaign succeeding and the chances of a theatre campaign failing (when launched in December of a given year) are virtually the same
### One Conclusion for Outcomes Based on Goals
   - It is statistically likely that a play campaign will succeed when it's fund goal does not exceed $14999.00.
### Limitations of Dataset
   - No data for the amount of theatre kickstarters that were canceled in October of a given year
   - The data only includes play/theatre campaigns that were launched between 2010 and 2017 (a range of 8 years)
   - The dataset may not have included each and every play campaign that was launched between 2010 and 2017, in any of the countries surveyed.
### Recommendation
   - It is recommended that additional pivot tables and line graphs be added to the dataset to illustrate the limitations of the dataset (if additional data is provided for
   the limitations of the dataset, first) before drawing any further conclusions about the number of and percentages of successful, failed, and canceled play kickstarter
   campaigns over given years and given countries.
   



