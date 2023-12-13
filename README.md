# Impact of covid 19 on energy consumption in Baltic countries
### Authors: Carl-Christjan Bogoslovski, Artur Kreegipuu

## Goal of the project

The goal of the project is to find out how the COVID-19 measurements such as lockdown, shutdown of schools, universities, commercial places etc has impacted the energy consumption in the Baltic countries. The project also investigates the factors that influenced energy consumption changes during the pandemic. This could include variables like GDP, travel restrictions, temperature, and more.

## Provide a guide to the contents of the repository
This repository contains preprocessed dataframes for GDP("df_gdp_et.csv","df_gdp_lv.csv", "df_gdp_lt.csv"), daily mean temperature ("df_temp_et.csv", "df_temp_lv.csv", "df_temp_lt.csv"), cumulative COVID-19 deaths ("df_covid_deaths.csv"), confirmed new and cumulative COVID-19 infection cases reported World health  Organization (WHO) for the Baltics ("df_WHO_et.csv", "df_WHO_lv.csv", "df_WHO_lt.csv") and energy consumption (MWh) for all the Baltic States ("df_energy_consumption_et.csv", "df_energy_consumption_lv.csv" and "df_energy_consumption_lt.csv"). It also includes the documentation (workflow) of step-by-step proccessing of the original dataframes ("Data preprocessing.ipynb"). Correlations between different datasets are calculated and data is analysed in the "Data analysis.ipynb" file. Additionally, this repository provides visualizations ("Data_visualization.ipynb"), including plots and graphs, that illustrate the correlations between different datasets, offering a clear representation of the results."

## Explain how it is possible to take the code and replicate the same analysis that the authors have done
When processing the data into neat dataframes, we took into consideration the factors of readability and simplicity of the outcome. We also standardized the data types, so it is easier to implement. 

## Sources and datasets:

#### Energy consumption
* Estonian energy consumption ("estonia2018_2022.csv"): https://dashboard.elering.ee/en/system/with-plan/production-consumption?interval=minute&period=days&start=2023-11-08T22:00:00.000Z&end=2023-11-09T21:59:59.999Z
* Latvian energy consumption ("latvia2018_2022.csv"): https://www.ast.lv/lv/content/situacija-energosistema
* Lithuanian energy consumption ("Lithunia2018_2022.csv"): https://www.litgrid.eu/

#### Weather data
* Estonian weather data ("Tallinn-Harku weather.csv"): https://www.ilmateenistus.ee/kliima/ajaloolised-ilmaandmed/
* Latvian weather data ("Riga,Latvia 2018-01-01 to 2020-05-31.csv", "Riga,Latvia 2020-06-01 to 2022-12-31.csv"): https://www.visualcrossing.com/weather-history/Riga%2CLatvia
* Lithuanian weather data ("Vilnius,Lithuania 2018-01-01 to 2020-08-31.csv", "Vilnius,Lithuania 2020-09-01 to 2022-12-31.csv"): https://www.visualcrossing.com/weather-history/Vilnius

#### GDP
* Estonian GDP ("Real Gross Domestic Product for Estonia.csv"): https://fred.stlouisfed.org/
* Latvian GDP ("Real Gross Domestic Product for Latvia.csv"): https://fred.stlouisfed.org/
* Lithuanian GDP ("Real Gross Domestic Product for Lithuania"): https://fred.stlouisfed.org/

#### Cumulative COVID-19 deaths
* ("Cumulative Count of COVID-19 Deaths Baltics.csv"): https://datacommons.org/tools/timeline#statsVar=CumulativeCount_MedicalConditionIncident_COVID_19_PatientDeceased&place=country%2FEST%2Ccountry%2FLVA%2Ccountry%2FLTU

#### WHO data
* ("WHO-COVID-19-global-data.csv"): https://covid19.who.int/data

https://ourworldindata.org/covid-cases?country=IND~USA~GBR~CAN~DEU~FRA

