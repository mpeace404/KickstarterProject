# Kickstarting with Excel

## Overview of Project

### Purpose

The purpose of this project is to analyze outcomes of Kickstarter campaigns by Launch date and Goals. This project consists of 3 parts: a pivot table and chart showing the outcomes (failed, succcessful, or canceled) of Kickstarter campaigns in the Theatre category between the years of 2009 to 2017; a spreadsheet and chart showing the outcomes of Kickstarter campaigns in the Play subcategory based on the fundraising goals of the campaign; and an analysis of conclusions reached. This will assist the client with determining the best time of year to launch a Kickstarter for her new play, and what she should set the fundraising goal to for the best chances of success.

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date

To determine Theatre Outcomes by Launch Date, a pivot table and chart was created to show the number of successful, failed, and canceled campaigns based on the date that the campaign was started, and filtered for the Theatre category. 

![pivot screenshot](https://user-images.githubusercontent.com/82191831/123564861-fc19b780-d788-11eb-9bfe-1f6a08d477f9.jpg)


![pivot screenshot_2](https://user-images.githubusercontent.com/82191831/123564876-0b006a00-d789-11eb-9536-f51bd48d0aec.jpg)


### Analysis of Outcomes Based on Goals

To determine Outcomes Based on Goals, a spreadsheet was created to calculate the number of campaigns in the Play subcategory that succeeded, failed, or were canceled based on the dollar amount of the campaign fundraising goals. Then calculations were made to show what percentage of the total projects were successful, failed, or canceled. Then a line chart was created to visualized the data in the spreadsheet.

![goals screenshot 1](https://user-images.githubusercontent.com/82191831/123565486-0d63c380-d78b-11eb-9b6f-d96c9b0c107b.jpg)


![goals screenshot 2](https://user-images.githubusercontent.com/82191831/123565491-13f23b00-d78b-11eb-9676-0a688a2a4f47.jpg)


### Challenges and Difficulties Encountered

One difficulty I encountered was reconciling how the number of campaigns canceled was 0 in the Outcomes Based on Goals, but there were canceled campaigns in the Outcomes by Launch Date chart. I realized that the sheets were filtered on two different categories, the Theatre category for Outcomes by Launch Date and the Play subcategory for the Outcomes Based on Goals sheet. 

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?

1) The best time to launch a Kickstarter campaign in the Theatre category is early to mid-summer ( May, June, July), and the worst time would be late fall to winter (November, December, and January). 
2) Theatre Kickstarters are rarely canceled, 3% were canceled between 2009 and 2017. 

- What can you conclude about the Outcomes based on Goals?

1) Kickstarters campaigns with the Play subcategory rarely have a fundraising goal over $14,999, only 8% of campaigns have a goal of $15,000 or more.
2) The higher the goal, the more likely the campaign will fail.

- What are some limitations of this dataset?

The data is somewhat dated, the most recent information is from 5 years ago.

- What are some other possible tables and/or graphs that we could create?

1) Outcomes based on Years to determine which years were the most successful for plays, and if there are any patterns
2) Outcomes based on Country to determine which country is more likely to sponsor plays
3) Outcomes based on Staff Pick to determine if having the "Staff Pick" attribute actually contributes to the success of a campaign, and does it increase the number of backers 
