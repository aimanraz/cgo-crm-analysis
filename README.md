# 2021 Chicago Crime Data Analysis

The main idea of the analysis is to help the City of Chicago makes sense of data collected in order to find important about how to improve law enforcement actions to prevent crime. 

## Code and Resources Used 
**Python Version:** 3.8++

**Packages:** pandas, numpy, matplotlib, and seaborn.

## About Dataset
The City of Chicago makes available through its [Data Portal](https://data.cityofchicago.org/Public-Safety/Crimes-2001-to-present/ijzp-q8t2/data) access to government data. The site hosts over 200 datasets presented in easy-to-use formats about City departments, services, facilities and performance.

Disclaimer: This dataset reflects reported incidents of crime (with the exception of murders where data exists for each victim) that occurred in the City of Chicago from 2001 to present, minus the most recent seven days. Data is extracted from the Chicago Police Department's CLEAR (Citizen Law Enforcement Analysis and Reporting) system. In order to protect the privacy of crime victims, addresses are shown at the block level only and specific locations are not identified.

![Dataset](https://github.com/aimanraz/cgo-crm-analysis/blob/main/img/top_row.JPG)

## Questions need to be answered

1. What are the top 12 most common crimes of the period?
2. What are the crime types that have median above 50 crimes/day?
3. For each crime type identified in the last question, use the latitude and longitude to analyse its spread.

## Exploratory Data Analysis (EDA)
Visualization that might answered the following question.

* Top 12 Crime and overall crime distribution.

![Top 12 crime](https://github.com/aimanraz/cgo-crm-analysis/blob/main/img/top12crime.JPG)
![Crime distribution](https://github.com/aimanraz/cgo-crm-analysis/blob/main/img/crime_dist.png)

* Observing which crime that have median above 50/day.

![Dashboard](https://github.com/aimanraz/cgo-crm-analysis/blob/main/img/boxplt.png)

* Top crime with its spread in chicago.

![Dashboard](https://github.com/aimanraz/cgo-crm-analysis/blob/main/img/analyze_spread.png)

## Conclusion
1. Based from the analysis top crime in chicago is battery with 32916 occurance(that was spotted). 
2. The top 12 crime are 
* Battery
* Theft
* Criminal damage
* Assault
* Deceptive practice
* Other offense
* Motor vehicle theft
* Weapon isolation
* Robbery
* Narcotics
* Criminal trespass
3. The average median of crime which more than 50 crime/day are:
* Battery
* Theft
* Criminal damage
* Assault

let the data drive you...and beyond.
