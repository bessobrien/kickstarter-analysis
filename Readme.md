# Kickstarting with Excel
---
## Overview of Project

### Purpose

Louise's play *Fever* has arrived close to its fundraising goal, and in a short amount of time. The purpose of this analysis is to review how different campaigns fared in relation to their launch dates and their funding goals. The result will provide a comparison.

## Analysis and Challenges

The analysis is in LINK. Within the main data in the tab *Kickstarter Analysis*, I added a *Years* column to the end that referenced the Date Launched.

Two new tables were created:
1. Theater Outcomes by Launch Date
2. Outcomes Based on Goals

### Analysis of Outcomes Based on Launch Date
Within the tab, *Outcomes Based on Launch Date*, I created a pivot table to filter down to:
1. Outcomes in the columns
2. Month in the rows
3. Count of outcomes in the values
4. Filtered down to theater

A visualization is provided here: LINK

### Analysis of Outcomes Based on Goals
Within the tab, *Outcomes Based on Goals*, I created a table:
1. Rows represent ranges of GOAL

The table represents the count of each outcome of all plays at each goal range. 

A visualization of the data is provided here: LINK

### Challenges and Difficulties Encountered

No challenges or difficulties were encountered during this analysis. A possible difficulty for some would be the IFS formulas used in the *Outcomes Based on Goals* tab. The formula is very manual, and some quick work could be done to create a quicker solution to reduce the amount of hand-key. This would reduce the risk of errors related to manual hand-key.

## Results

Based on *Outcomes based on Launch Date*, we can conclude:
1. The top number of successful outcomes occurred in May, June, and July.
2. There are much more successful outcomes in the theater campaign than failed or canceled outcomes.

Based on the *Outcomes based on Goals*, we can conclude:
1. The highest number of successful projects fall in the 1000 to 4999 goal range.
2. The goal range with the highest percentage of successful projects was Less than 1000.

One limitation of this dataset is that it contains different currencies. In order to properly represent consistent goal ranges, it would be important to establish and compare the same currency for each project.

Another option to explore with this dataset could include a table aggregating theater projects by year and outcome. This could provide a sense of relevance and context to the data.