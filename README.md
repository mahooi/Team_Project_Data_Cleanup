# Butter team project: COVID impact on energy consumprion in Spain

**Butter team** consists of Ibsy, Kosta, Maha, and Pepe
**GitHub repo**: https://github.com/Gleeful-Penguin/butter_team_project


## Introduction to the analysis
We combined two datasets hoping to find the change of energy demand and generation between the period of January and June 2019, and January and June 2020, when COVID had an impact on the energy behavior of people in Spain. We hoped to discover if there was a significant difference between those two years, how was energy created, and was there a significant shift in emissions as a result of it. We discovered an 8% decrease after the introduction of "stay at home" requirements.


## Data used

   ### 1. Stay at home (https://ourworldindata.org/policy-responses-covid)
The stay-at-home is a table with the daily government policies on stay-at-home requirements or household lockdowns per country. There are four categories: 0) No measures, 1) Recommended Stay-at-home, 2) Required to Stay-at-home with exception of essential trips, 3) Required to Stay-at-home with minimal exceptions. we used this dataset to determine the exact days on which requirements were introduced/changed. 

   ### 2. REData API (https://www.ree.es/es/datos/generacion)
The API dataset from the National Spanish Energy provider and gives detailed day-to-day insights into the current and daily historic variation of the demand for energy in Spain. Moreover, we used some of the information about the generation, and sources of energy (types) and estimated emissions. We extracted two-time perids from January to June for both 2019 and 2020 to benchmark and show the impact of the COVID restrictions minimizing the seasonal changes in energy demand and generation.


## Questions you want to answer
The main question we were aiming to answer was: **"What was the impact of the COVID restrictions on energy consumption in Spain?"** Initially, we discussed focusing on the energy of households, however finding that data proved to be a challenging task, as it is quite narrow. We also considered doing the same analysis for other countries, since this data was available for the majority of countries and it would further fortify the discoveries of our analysis. However, due to time constraints we decided to limit the analysis within Spain alone.


## Insights derived from your analysis
Spain has heavily invested in renewable energy generation, from which wind can contributes to up to 50% of the total daily energy generation and as low as 5%. As a result of that, the weather is a deciding factor on the number of emmisions released by the creation of energy. Thus having a lower energy demand does not necessarily result in lower emmissions created by day, since non-renewable energy generation is filling the gap of the lack of wind. Additionally, we discovered an 8% decrease in energy demand between the period Jan-jun 2019 and Jan-Jun 2020.


## Possible further questions and improvements
Is this cause and effect similar in other countries? 
Which countries experience the biggest and smallest difference? 
Which areas of energy demand were most impacted by the restrictions?
How can countries use those findings to control national emmissions?