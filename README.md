# A Hap-Py Analysis: Predicting Happiness using Python in Google Colab Notebook  
## Background & Rationale
This project explores factors that influence happiness around the world using both the World Happiness Report (scraped from this [site](https://data.worldhappiness.report/table)) and my own happiness dataset collected over 9 months. My background is in neuroscience and I have always loved learning about how individual people and cultures nurture happiness & what we can learn about what it means to live a meaningful life through our different approaches. I hope this analysis is as interesting to read as it was to conduct. *Hap-Py Reading!*

**Data Sources:** World Happiness Report, my own happiness dataset 

**Date Range:** World Happiness Report: 2015-2025 (score refresh = annual); My happiness dataset: July 2025-March 2026 (score refresh = daily)

## Project Objectives 
1. To analyze factors that influence happiness ranking of countries included in the WHR (global factors) 
2. To analyze the impact of different habits on my own happiness score (individual habits)

## Questions Explored
*World Happiness Report*
1. How highly does each category correlate with happiness ranking?
2. What are the top 10 happiest countries on average over the last 10 years?
3. What are the bottom 10 countries in terms of happiness on average over the last 10 years?
4. Which countries rank the highest on average for each category over the last 10 years?
5. How does one's expectancy of living a healthy life correlate to their satisfaction with life? Does this look different depending on where in the world you live?
6. How has the US changed in rankings for different factors over the last 10 years?
7. What factors best explain variation in how people feel their lives are going?
8. What is a person's life evaluation score likely to be based on the country they grew up in and how high that country ranks for each category in the last month?

*My dataset*
1. What are the most commonly practiced habits on days where my happiness rating is in the upper quartile?
2. How well does each habit correlate with my happiness rating?
3. What countries could you assume I might be living in based on my mean happiness rating according to the World Happiness Report?
4. Are my happiness rating and habits practiced related?

## Process
*WHR*
- Scrape rankings data from 2015-2025 from the World Happiness Report site
- Clean the data: identify nulls, outliers, and formatting issues and resolve; QCing with original site
- Add columns mapping countries to regions, subregions, and intermediate regions
- Conduct a 3 part analysis in GCN:
1. Descriptive statistics & exploratory data analysis
2. Hypothesis testing using multiple linear regression
3. Predictive modeling using multiple linear regression

*My dataset*
- Clean the data: identify nulls & outliers and QC with original paper trackers
- Conduct a 2 part analysis in GCN:
1. Descriptive statistics & exploratory data analysis
2. Hypothesis testing using a multi-way ANOVA

### ***BONUS:*** 
If you found this analysis interesting, I built an [interactive dashboard](https://datastudio.google.com/u/0/reporting/d5e423dc-24b2-422f-8fd0-6e90f5622991/page/G78tF) in Data Studio (Looker Studio) if you'd like to play around with the data yourself! I find this super fun myself - and I'd love to hear from you if you draw any hap-Py conclusions! :)
