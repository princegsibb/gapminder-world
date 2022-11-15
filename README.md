# Project 1: Investigating GAPMINDER WORLD

## by Prince Sibanda

## Introduction

The selected data is from the Gapminder world and 5 different indicators were selected for the analysis, namely: population_total, income_per_person_gdppercapita_ppp_inflation_adjusted, life_expectancy_years, children_per_woman_total_fertility and child_mortality_0_5_year_olds_dying_per_1000_born. In this project I am going to use population as a primary dependent variable and life expectancy as a secondary dependent variable. There are 64113 observations and 7 features to start with and for further analysis, will be subset using 2 criterias:

Two dataset will be explored and compared, i.e. the country with the maximum recorded total population and the country with the lowest recorded population. The above selected dataset will also be filtered for data recorded from 1950 and onwards.

## Question(s) for Analysis

Q1. Besides the significant population difference between India and Brunei, what other trends in terms of fluctuations are observed over the given time period 1800 to 2050?

Q2. What are the notable differences and similarities between India and Brunei, with regards to life expectancy, children per woman, child mortality from 1950 going onwards?

Q3. Which factors significatly contribute to the increase in population for Brunei and India from 1950 going forward?

Q4. Which country has the highest average life expectancy and by how much does its life expectancy contribute to the total population?

Q5. Which notable trends are common to both countries?

Q6. Is there relationship between children_per_woman_total_fertility and child_mortality_0_5_year_olds_dying_per_1000_born and how do they both affect or contribute to the total population life expectancy years in Brunei?

## Conclusions

The following conclusions were reached:

Brunei has always had a higher life expectancy compared to India
There is a positive correlation between population, life expectancy and income for Brunei, where its strongest between population and life expectancy.
Income and life expectancy contribute highly to the increase in population in India
Child_mortality_0_5_year_olds_dying_per_1000_born and children_per_woman_total_fertility do not positively contribute to the increase in the average total population for Brunei
Child_mortality_0_5_year_olds_dying_per_1000_born and children_per_woman_total_fertility do not positively contribute to the increase in the average life expectancy years in Brunei.
Both countries have experienced a decline the number of children_per_woman_total_fertility since the 1950s
Looking at the graphs we learn that both countries experience a decrease in both child_mortality_0_5_year_olds_dying_per_1000_born and children_per_woman_total_fertility and showed stability around the same time as well in 2020.

## Limitations

The data doesn't give an insight or provide documentation on externall factors (e.g. political and socio-economic issues)that contributed to the various changes observed. This would assist in understanding the different trends observed over the years. For example 'what caused the rapid decline of income_per_person_gdppercapita_ppp_inflation_adjusted of Brunei in the late 1970s as shown in the graph above?'

The countries were not grouped by region/continent which would have made it easy to analyse the whole dataset then performing an analysis on particular region(s) incase there were common trends. Manually grouping them would have been time consuming.

## References

https://realpython.com/

https://www.statology.org/python-guides/

https://stackoverflow.com/

https://pandas.pydata.org/pandas-docs/stable/user_guide/index.html
