Meat Consumption Around the World: Trends and Differences Across Continents
📊 Project Overview

This project analyses meat consumption around the world, focusing on differences between continents, consumption patterns by meat type, and how these patterns have changed over time.

The project was developed as part of a Data Analytics course project and combines data collection, data cleaning, exploratory data analysis and visualisation using Python.

Main Research Question

How does meat consumption differ across continents, and how has it changed over time?

Key Questions
Which continents have the highest and lowest meat consumption per capita?
How does the composition of meat consumption differ between continents?
Which types of meat are most commonly consumed in each region?
How has meat consumption changed over time?
Which continents experienced the largest changes in consumption?
Is there a relationship between meat consumption and GDP per capita?
How do country-level patterns compare with continental trends?
🎯 Hypotheses

The analysis was guided by the following hypotheses:

H1: Meat consumption per capita differs between continents.
H2: North America has higher per-capita meat consumption than Africa and Asia.
H3: Meat consumption has increased over time in Asia.
H4: Poultry consumption has increased over time across most continents.
H5: Global meat consumption has increased over the period analysed.
🗂️ Project Structure
File	Description
Meat Consumption Around the World_Trends and Differences Across Continents (Plan).ipynb	Project planning, research questions, hypotheses, data collection and analysis preparation
Raquel_Dataset_APIs.ipynb	Data collection and analysis using datasets/APIs, including meat consumption and economic indicators
Effie_Dataset_3.ipynb	Additional dataset exploration and analysis
Effie_Scraping.ipynb	Web scraping and preparation of additional data
meat_countries_clean.csv	Cleaned country-level meat consumption dataset
meat_continents_clean.csv	Cleaned continental-level meat consumption dataset
FAOSTAT_data_en_9-30-2026 (1).csv	FAOSTAT dataset used for additional analysis
country_lookup.py	Dictionary mapping FAOSTAT country names to ISO3 codes and continents
Meat_Consumption_Around_the_World_v2.pptx	Final presentation of the project
🔎 Data Sources

The project uses data from multiple sources to combine different perspectives on meat consumption.

Our World in Data

Meat consumption data was collected from Our World in Data, including per-capita consumption by meat type and country/continent.

🔗 https://ourworldindata.org/

The analysis includes:

Poultry
Beef and buffalo
Sheep and goat
Pig
Other meats
Fish and seafood
Total meat consumption
FAOSTAT

Additional country-level data was obtained from FAOSTAT (Food and Agriculture Organization of the United Nations).

🔗 https://www.fao.org/faostat/

FAOSTAT data was used to complement the analysis and support country-level comparisons.

🧹 Data Preparation

The project includes several data preparation steps:

Importing data from external sources.
Cleaning and standardising column names.
Selecting relevant meat-consumption indicators.
Mapping countries to continents.
Removing or handling aggregate values where appropriate.
Creating a Total Meat Consumption variable.
Calculating percentage changes over time.
Preparing country- and continent-level datasets for visualisation.

The country_lookup.py file provides the country-to-continent mapping used when working with FAOSTAT data.

📈 Analysis

The project explores meat consumption from several perspectives.

🌍 Continental Comparison

The analysis compares six major geographic regions:

Africa
Asia
Europe
North America
South America
Oceania
🥩 Meat Type Composition

Consumption is broken down by meat type to identify the dominant categories in different regions.

This allows us to compare patterns such as poultry, pork, beef, sheep and goat, and fish and seafood consumption across continents.

📅 Trends Over Time

Time-series analysis is used to examine how total meat consumption has evolved across continents.

The analysis also calculates percentage changes between the beginning and end of the period studied.

🌎 Country-Level Analysis

Individual countries are compared to identify differences in consumption levels and changes over time.

This provides a more detailed perspective than looking only at continental averages.

💰 GDP and Meat Consumption

The project also examines the relationship between GDP per capita and meat supply per person.

This analysis investigates whether differences in economic development may help explain variations in meat consumption.

🛠️ Technologies Used
Python
Pandas – data manipulation and analysis
NumPy – numerical operations
Matplotlib – data visualisation
Jupyter Notebook – analysis and documentation
Requests – data collection from web sources
Web Scraping – collection of additional data
Microsoft PowerPoint – presentation of findings
📌 Main Outputs

The project produces visualisations and analysis covering:

Meat consumption by country
Meat consumption by continent
Per-capita meat consumption
Meat consumption by meat type
Changes in consumption over time
Percentage change by continent and country
Meat supply vs. GDP per capita
Comparative continental trends

The final results are presented in:

Meat_Consumption_Around_the_World_v2.pptx

🔄 Data Analytics Workflow

The project follows a complete data analytics workflow:

Data Collection
       ↓
Data Cleaning
       ↓
Data Transformation
       ↓
Exploratory Data Analysis
       ↓
Data Visualisation
       ↓
Insights
       ↓
Final Presentation
👥 Authors

Raquel Marques
Effie

Data Analytics Course Project — 2026

📚 Project Purpose

The purpose of this project is to explore global meat consumption patterns and understand how they vary geographically and over time.

Rather than focusing only on which regions consume more or less meat, the analysis combines country-level, continental, meat-type and economic data to provide a broader understanding of global consumption patterns.

The project demonstrates the practical application of data analytics techniques to a real-world topic, from collecting and cleaning data to analysing trends and communicating insights through visualisations.
