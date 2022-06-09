# Lifestyle Data Analysis - Gapminder

## Project Overview:
Gapminder has collected a lot of information about how people live their lives in di􀁷erent countries, tracked across the years, and on a number of different indicators.


## Data License and Attribution:
FREE DATA FROM WORLD BANK VIA GAPMINDER.ORG, CC-BY LICENSE


## Task:
The purpose of this project is to collect, explore and analyse data about three lifestyle indicators from [Gapminder](https://www.gapminder.org/data/).<br><br>
<b>Idicators analysed in this project:</b><br>
1. Children per woman (total fertility rate).
2. Child Mortality Rate.
3. Employment rate % (females aged 15+).


## Criteria:
1. Using Python, Numpy, Pandas, Matplotlib and Jupyter Notebook, collect, assess and clean the datasets.
2. Using Descriptive Statistics and Data Visualization, conduct your open ended Exploratory Data Analysis for each indicator individually and between the three indicators.
3. Draw your conclusions about your analysis.
4. Share your findings and communicate your results using Jupyter Notebook.


## Files:
1. Lifestyle_Data_Analysis_Gapminder.ipynb
- ipynb file (Jupyter Notebook File)
2. children_per_woman_total_fertility.csv
- CSV Database File.
3. child_mortality_0_5_year_olds_dying_per_1000_born.csv
- CSV Database File.
4. females_aged_15plus_employment_rate_percent.csv
- CSV Database File.


## Datasets Description:
<b>1. Children per woman (total fertility rate):</b>
- Description: Total fertility rate. The number of children that would be born to each woman with precailing age-specific fertility rates.
- Source url: https://www.gapminder.org/data/documentation/gd008/
- csv file downloaded from: gapminder.org/data/ .. Choose individual indicators .. Babies per woman
- file name: children_per_woman_total_fertility.csv
- Dataset alias: df_tfr
- Dataset shape: 202 rows (countries) 302 columns (years from 1800 to 2100)
- Columns:
    - Country (object - str)
    - 1800:2100 (float) <br><br>
 
 
<b>2. Child Mortality Rate:</b>
- Description: Death of children under five years of age per 1,000 live births.
- Source url: https://www.gapminder.org/data/documentation/gd005/
- csv file downloaded from: gapminder.org/data/ .. Choose individual indicators .. Child mortality.
- file name: child_mortality_0_5_year_olds_dying_per_1000_born.csv
- Dataset alias: df_cmr
- Dataset shape: 197 rows (countries) 302 columns (years from 1800 to 2100)
- Columns:
    - Country (object - str)
    - 1800:2100 (float) <br><br>


<b>3. Employment rate % (females aged 15+):</b>
- Description: Percentage of female population, age group 15+, that has been employed during the given year.
- Source url: https://ilostat.ilo.org/
- csv file downloaded from: gapminder.org/data/ .. Choose individual indicators .. Work .. Employment rate .. Female aged 15+
- file name: females_aged_15plus_employment_rate_percent.csv
- Dataset alias: df_erg
- Dataset shape: 189 rows (countries) 30 columns (years from 1991 to 2019)
- Columns:
    - Country (object - str)
    - 1800:2100 (float)


## Libraries used in the code:
- pandas
- numpy
- matplotlib.pyplot
- seaborn
