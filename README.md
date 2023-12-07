# World-Internet-Access-Data
![image](https://github.com/aashok30/World-Internet-Access-Data/assets/101622691/702b4e51-e8e8-4548-bf28-80a668082ee8)


This dataset contains information on internet access around the world.
The workspace is set up with two CSV files containing information on global internet access for years ranging from 1990 to 2020.

internet_users.csv
users - The number of people who have used the internet in the last three months
share - The share of the entity's population who have used the internet in the last three months
adoption.csv
fixed_telephone_subs - The number of people who have a telephone landline connection
fixed_telephone_subs_share - The share of the entity's population who have a telephone landline connection
fixed_broadband_subs - The number of people who have a broadband internet landline connection
fixed_broadband_subs_share - The share of the entity's population who have a broadband internet landline connection
mobile_cell_subs - The number of people who have a mobile subscription
mobile_cell_subs_share - The share of the entity's population who have a mobile subscription
Both data files are indexed on the following 3 attributes:

entity - The name of the country, region, or group.
code - Unique id for the country (null for other entities).
year - Year from 1990 to 2020.

## Problem Statement

This scenario helps you develop an end-to-end project for your portfolio.

Background: You work for a global internet provider on a mission to provide affordable Internet access to everybody around the world using satellites. You are tasked with identifying which markets (regions or countries) are most worthwhile to focus efforts on.

Objective: Construct a top 5 list of countries where there is a big opportunity to roll out our services. Try to consider the amount of people not having access to (good) wired or mobile internet and their spending power.

## Road Map Of The Project

### Performed Exploratory Data Analysis (EDA):
Conducted EDA to gain insights into the dataset.
Identified and analyzed the top 5 countries with the highest population share using the internet in 2020.

### Top 5 Countries with the Highest Internet Use in 2020:
Identified the countries with the highest internet usage based on population share.
Provided insights into the internet usage patterns in these top countries.

### Top 5 Internet Users Countries Overtime:
Analyzed the internet usage trends over time.
Visualized the top 5 countries with the highest internet users across different years.

### Correlation Heatmap:
Created a correlation heatmap to understand the relationships between variables, such as internet usage and other factors.

### Internet Usage Around the World in 2020:
Used a map to vividly illustrate internet usage globally in the year 2020.
Highlighted variations in internet usage across different regions.

![newplot](https://github.com/aashok30/World-Internet-Access-Data/assets/101622691/6144a62a-eee5-43c3-ac6d-4b3d42970e67)


### Conclusion about the Analysis:
Summarized key findings from the analyses conducted.
Provided insights into trends, patterns, and notable observations.

### Reasons for the Conclusion:
Justified the conclusions drawn based on the analysis conducted.
Explained the significance of identified trends and patterns.
Considered the implications of the analysis for stakeholders and decision-makers.

### What if there is no internet for the whole day?
![No_Internet_Day](https://github.com/aashok30/World-Internet-Access-Data/assets/101622691/495c5b15-8db9-426c-8ec2-c9873754b075)

Data_Source: Datacamp & https://ourworldindata.org/internet
