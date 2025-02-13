# Greenhouse-Gas-Emissions-Analysis

## 1. Business Problem & Objectives

### Business Problem Statement

Climate change is one of the most pressing global challenges, driven by rising greenhouse gas (GHG) emissions. Understanding emissions trends and their relationship with economic growth (GDP) and population is crucial for developing sustainable policies. This project aims to analyze and visualize GHG emissions data alongside key economic and demographic indicators.

### Goals & Objectives

Data Cleaning & Integration: Collect, clean, and merge GHG emissions, GDP, and Population datasets for accurate analysis.

Trend & Impact Analysis: Identify global and country-level emissions trends, their relationship with GDP and Population, and highlight top polluters.

Define Key Performance Indicators (KPIs): Measure emissions efficiency using meaningful indicators.

Visualization & Reporting: Create interactive dashboards and generate insights using Power BI, Tableau, and StoryMaps.

## 2. Key Performance Indicators (KPIs)


* Total GHG Emissions: Sum of emissions per year - Measures overall trend of global emissions.

* Emissions per Capita: Total Emissions/Population - Evaluates how much CO₂ an average person contributes.

* Emissions Intensity of GDP: Total Emissions/GDP - Measures how much emissions are generated per unit of GDP.

* Top Polluting Countries: Ranking based on emissions - Identifies the biggest contributors to global emissions.

* Top Sectors by Emissions: Emissions grouped by sector - Highlights which industries are the largest polluters.

## 3. Data Collection & Cleaning

### Datasets Used

* GHG Emissions Dataset (1990-2021) from Climate Watch

* Population Dataset (1990-2021) from the World Bank

* GDP Dataset (1990-2021) from the World Bank

### Data Cleaning & Preprocessing Steps

1. Standardized Country Names: Applied reverse mapping to align country names across datasets.

2. Removed Missing & Incomplete Data:

* Excluded "Cook Islands" and "Niue" due to missing GDP and Population values.

* Forward-filled missing values for countries with gaps in the data.

3. Handled "World" Aggregation:

* Computed total World Population & GDP as the sum of all countries' values per year.

* Ensured "World" emissions data remained intact for global trend analysis.

4. Converted Wide Format to Long Format: Ensured consistency in data structure for analysis.

## 4. Data Integration & Merging

The final dataset includes:

* ISO: Country ISO Code

* Country: Country Name

* Data Source: Emissions Data Source

* Sector: Sector-wise Emissions

* Gas: Type of Greenhouse Gas (CO2, CH4, etc.)

* Unit: Measurement Unit (Million Metric Tons)

* Year: Year (1990-2021)

* Emissions: Total GHG Emissions

* Population: Total Country Population

* GDP: Total Country GDP

## 5. Initial Insights & Trends

1. Global Emissions Trends (1990-2021)

Total global emissions have increased over time, with significant spikes in industrial periods.

The top contributors to emissions remain China, USA, India, and Russia.

2. Relationship Between GDP & Emissions

Many developed nations show high GDP but lower emissions intensity (e.g., EU countries).

Developing economies exhibit rising emissions alongside economic growth (e.g., China & India).

3. Per Capita Emissions Trends

Some countries have high per capita emissions despite lower total emissions (e.g., Qatar, UAE).

Countries with large populations (e.g., India) have low per capita emissions despite high total emissions.

