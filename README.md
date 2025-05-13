<center>
    <img src="https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBMDeveloperSkillsNetwork-DB0201EN-SkillsNetwork/labs/FinalModule_Coursera_V5/images/SN_web_lightmode.png" width="300" alt="cognitiveclass.ai logo">
</center>

# Assignment: Notebook for Graded Assessment

## Introduction

This project involves working with three public datasets related to the city of Chicago. You will:

1. Understand three Chicago datasets
2. Load the datasets into a SQLite database
3. Execute SQL queries to answer data-driven questions

## Datasets Used

The datasets are sourced from the City of Chicago Data Portal:

1. [Socioeconomic Indicators in Chicago](https://data.cityofchicago.org/Health-Human-Services/Census-Data-Selected-socioeconomic-indicators-in-C/kn9c-c2s2)
2. [Chicago Public Schools Report Cards](https://data.cityofchicago.org/Education/Chicago-Public-Schools-Progress-Report-Cards-2011-/9xs2-f89t)
3. [Chicago Crime Data](https://data.cityofchicago.org/Public-Safety/Crimes-2001-to-present/ijzp-q8t2)

## Download Datasets

You can directly load the data into pandas dataframes using the URLs:

- [Chicago Census Data CSV](https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBMDeveloperSkillsNetwork-DB0201EN-SkillsNetwork/labs/FinalModule_Coursera_V5/data/ChicagoCensusData.csv)
- [Chicago Public Schools CSV](https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBMDeveloperSkillsNetwork-DB0201EN-SkillsNetwork/labs/FinalModule_Coursera_V5/data/ChicagoPublicSchools.csv)
- [Chicago Crime Data CSV](https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBMDeveloperSkillsNetwork-DB0201EN-SkillsNetwork/labs/FinalModule_Coursera_V5/data/ChicagoCrimeData.csv)

## Tools & Libraries

- Python
- Pandas
- SQLite
- ipython-sql
- prettytable

## Database Structure

The data is loaded into a SQLite database `FinalDB.db` with the following tables:

- `CENSUS_DATA`
- `CHICAGO_PUBLIC_SCHOOLS`
- `CHICAGO_CRIME_DATA`

## SQL Queries

The assignment involves writing SQL queries to solve problems such as:

1. Total number of crimes
2. Areas with income below a threshold
3. Crimes involving minors
4. Kidnappings involving children
5. Crimes recorded at schools
6. Average safety score by school type
7. Areas with highest poverty
8. Most crime-prone area
9. Area with highest hardship index
10. Community with most crimes

## Setup Instructions

1. Install dependencies:
   ```bash
   pip install pandas ipython-sql prettytable
