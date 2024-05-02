## COVID-19 Comprehensive Study

### Team Members

- Mohammed Alsailani
- Andrew Byrnes
- Collin Coakley
- Gilberto Zamarron


### Description
Our project focuses on analyzing data related to COVID-19, including the effect of vaccination on transmission and death. We also look at other local variables, such as temperature, humidity, and population density to track the spread of the virus. Our analysis also uses geospatial analysis to look for hot spots and infection surges and see how surrounding counties are impacted. We are relying on the COVID-19 Open Data by Google (https://health.google.com/covid-19/open-data/), which provides differing levels of granularity to allow us to focus on different analyses, providing data from 1/1/2020 to 9/17/2022 of various scopes, from world-wide aggregate data to data about individual counties in any given state in the US. This data was compiled by researchers who authored a paper called COVID-19 Open-Data, which is a global-scale spatially granular meta-dataset for coronavirus disease.


### Summary of Findings


##### How are COVID rates correlated with local variables:
- A moderate positive correlation exists between the new confirmed and deceased cases.
- Mobility data show weak negative correlations with new confirmed cases, with the highest in transit stations.
- Residential mobility shows a weak positive correlation with new confirmed cases.
- Temperature shows weak negative correlations with newly confirmed cases.

##### Did high vaccination rates help mitigate the deaths and spread of the virus?
The classification analysis shows that an increased vaccination rate in counties with higher older population rates decreases the mortality rate in the county. This shows a correlation between vaccines and lower mortality rates for older populations.


##### Understand the impact of detailed weather variables on COVID-19 rates
This analysis shows a decrease in the transmissibility of COVID-19 at temperatures exceeding 30°C, under 30°C, or under a 20% relative humidity.


##### Geospatial Analysis:
This analysis shows that COVID-19 spreads from county to county and the changes can be seen at different time aggregation periods and is more pronounced with appropriate binning.


### Application of this Knowledge

- The data confirm the relationship between increased COVID-19 cases and reduced mobility in workplaces and transit centers. However, the data also indicate increased residential mobility correlating with rising COVID-19 rates. When imposing future restrictions, care should be given to the fact that closures of outdoor venues may lead to increased indoor mobility.

- The analysis shows a relationship between increasing vaccination rates and decreasing death rates in populations over 50 years old. It supports the hypothesis that vaccination reduces mortality across the entire population. However, enforcing vaccinations remains a controversial topic.

- This study shows a decrease in the transmissibility of COVID-19 at temperatures exceeding 30 Deg C, below 30 Deg C, or under 20% relative humidity. The reason for this decrease is not identified within the scope of this study. It could be due to reduced virus transmissibility in extreme weather conditions or decreased mobility in such conditions. This information could be used to adjust pandemic restrictions during extreme weather.

- The Geospatial analysis informs that when a county, or counties in an area, are experiencing a significant increase in COVID-19 cases and deaths, the nearby and neighboring counties are likely to experience an increase in COVID-19 transmission and death, so those counties should plan accordingly. 


### Video Demonstration 
The project demonstration is in the following video:


### Final Paper
The final paper is the following link:


### Project Directory

| File | Description |
|---|---|
| All CSVs/     | Contains all counties data each in single CSV file |
| Geospatial/   | Contains all geospatial analysis code |
| Index and Ancilliary CSVs/   | ?? |
| Misc Functions/              | Contains code for importing data, classification, and clustering  |
|Test CSVs/            | Data for testing phase |
| frequent_patterns/              | Frequent pattern analysis code  |
