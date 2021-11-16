# Netflix & Unemployment Correlation Analysis
- Author: Carmen Ruan
- Date Created: 05/12/2021
- Class: CIS 9440

Project Objective: Follow the Kimball Lifecycle to design and develop a public, cloud-based Data Warehouse with a functioning BI Applications

Project Tools:
The tools used to build this Data Warehouse were: 
1. For Data Integration - python (Spyder Anaconda3)
2. For Data Warehousing - Google BigQuery
3. For Business Intelligence - Tableau

## Kimball Lifecycle Project Stages

### Project Planning

Motivation for Project:
Since the pandemic started, the stock price for Netflix went up almost 50%. It is steadily moving in an upward trend while unemployment rate also rises. I want to use this project to find a correlation in how well Netflix does in parallel to the growth in unemployment rates.

Description of the issues or opportunities the project will address:
I hope that this project will give some good insights as to predicting for unemployment rates. It is safe to assume that when unemployment rate is high during the pandemic, people will have a whole lot more time spent at home. This leads to a higher usage of Netflix creating a possible correlation between the two. 

Project Business or Organization Value:
High-level Business Initiative:
The data warehouse will collect data from various sources such as the bureau of labor statistics for civilian unemployment rates, Yahoo finance for Netflix stock prices, and other credible, comprehensive, consistent sources. This information will be used to analyze and help predict unemployment rates in response to Netflix stock price movements. This is important because unemployment rate adversely affects the disposable income of families, erodes purchasing power, diminishes employee morale, and reduces the entire economy’s output.  

BI Sponsors and Stakeholders (who will own this project?)
The business partners of Netflix will own this project. Current stakeholders include shareholders of Netflix, CIO, CFO, as well as the IT department. Unemployment rates are released at 8:30AM on the first Friday of every month. Finding out the correlation of unemployment rates to Netflix stock prices will help investors make predictions for the market as well as giving Netflix an advantage on what to do with company shares.  

What is the Business Value?
To help Netflix make better insights as to where to bring their business. Examples include, spending more money for advertisements when the unemployment rates are high. Giving promotion deals during down times when unemployment rate is low.

How long will this take? How much will this cost?
The project will take an estimate of 18 months. It will be consisted with a team of software engineers, business intelligence analysts, data analysts, as well as a project manager. The allocated budget is approximately $500,000.

Data Sources:
1. https://finance.yahoo.com/quote/NFLX/history?period1=1300233600&period2=1615852800&interval=1mo&filter=history&frequency=1mo&includeAdjustedClose=true
2. https://data.oecd.org/unemp/unemployment-rate.htm

### Business Requirements Definition

List of Final Data Warehouse KPI's:
1. Overall Stock Price Change / Unemployment Change Over Time 
2. Total Market Cap / Unemployment Rate 
3. Max High Stock price by Month

### Dimensional Model

This project's Dimensional Model consists of (2) Facts and (2) Dimensions and will be attached.

Kimball Bus Matrix:
See attached

### Business Intelligence Design and Development

List of Visualizations for each KPI:
1. For the first KPI, I chose to use dual lines for the visualization because it makes sense to compare them together as they share the same timeline. It is a time-series analysis line chart with a legend to show the progression for stock price change as well as unemployment change.
2. For the second KPI, I chose to keep the two graphs separate for both the market cap volume and the unemployment rate. It is also a time-series analysis since time is involved and it would just make more sense rather than something like a bar graph since it clearly shows that the two graphs are actually pretty similar.
3. The third KPI, I chose to use a table to display the different high stock prices by month for each year between 2011 to 2020 since 2021 is not yet complete and the data will be skewed cause of that. I used a calculated field to determine the highest and lowest stock prices for each year comparing the data in each month. They are then color coded to show an easy visual.

BI Application Wireframe design:
See attached

Picture of final Dashboard:
See attached

### Deployment

The project was deployed on Tableau Public: (https://public.tableau.com/views/group_1_milestone_4_final_project_Carmen_Ruan/Dashboard?:language=en&:display_count=y&publish=yes&:origin=viz_share_link)