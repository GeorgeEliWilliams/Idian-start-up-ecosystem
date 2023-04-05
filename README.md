# Indian-start-up-ecosystem
Analysis of the Indian startup ecosystem from 2018 to 2021

INTRODUCTION
India is the 3rd largest startup hub in the world. The initiative of start-ups was launched by the Indian government in 2016. The objective was to boost startup culture and create an entrepreneurial environment in India. Startups contribute significantly to the nation’s economic growth by introducing innovation and diversity into the nation’s economic infrastructure.
This project aims to provide visualizations and information into the trends of the Indian start-up ecosystem from 2018 to 2021.

QUESTIONS
1.	Trend in investment rate over the years
2.	What sector received the highest investment?
3.	Which sectors thrived in the pandemic era
4.	Which stage had the highest number of startups
5.	What are the top 5 cities with the highest investment?
6.	The city with the highest number of startups and the total investment received by the city
7.	The average investment amount for a seed stage investment over the period in India
8.	Top 5 sectors in Mumbai per investment
9.	Top 5 sectors in Bangalore per number of startups

HYPOTHESIS

NULL HYPOTHESIS: Tech companies are more likely to access investment funds.

ALTERNATE HYPOTHESIS: Tech companies are less likely to access investment funds.

DATA UNDERSTANDING
Looking through the datasets, some observations were made
1.	The names of the columns vary between the 2018 dataset and the other datasets therefore there is a need to rename and match the columns
2.	The amount column was not in the appropriate data type. There are values with dollar and rupee symbols. For consistency, these values should be changed to one currency. Also, the cells with the symbols have to be converted to dollars using the 2018 conversion rate.
3.	There was the issue of missing values
