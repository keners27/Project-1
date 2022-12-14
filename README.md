# Most Ideal State

This Project aims to identify which state is the best to live in based on a selection of factors
1 Crime
2 Schools
3 Unemployment
4 Housing

Contributors - Caroline Badocha, Daniel Kenworthy, Jose Sandoval & Balvinder Rajbans

# Project Structure

```
project
|__ .gitignore          # gitignore file
|__ Project 1 PPT - Group6.pdf    # slides for presentation
| 
|__ School Data/        # contains data and notebooks
|   |__ school_data_clean.ipynb         # cleaning notebook that takes in the raw data and outputs cleaned data for analysis
|   |__ school_data_analysis.ipynb     # analysis notebook that contains charts
|   |__ Output          # cleaned data & snippets from jupyter
|   |__ Resources     # raw data
|
|__ Employment_Underemployment/        # contains data and notebooks
|   |__Analysis_Underemployment_Unemployment.ipynb # analysis notebook that contains charts
|   |__ underemployment_data_cleaning.ipynb      # cleaning notebook that takes in the raw data and outputs cleaned data for analysis
|   |__ unemployment_data_cleaning.ipynb      # cleaning notebook that takes in the raw data and outputs cleaned data for analysis
|   |__ Figures          # cleaned data & snippets from jupyter
|   |__ Resources       # raw data
|
|__ Crime Data/        # contains data and notebooks
|   |__ Crime in state.ipynb      # cleaning notebook that takes in the raw data and outputs cleaned data for analysis, includes analysis and charts
|   |__ Output          # cleaned data & snippets from jupyter
|   |__ Resources       # raw data
|
|__ Housing Data Complete/        # contains data and notebooks
|   |__ Housing Data      # cleaning notebook that takes in the raw data and outputs cleaned data for analysis, includes analysis and charts
|   |__Images          # cleaned data & snippets from jupyter
|   |__ Resources       # raw data
```
# Questions
1. Which state is the safest?
2. Which state is the best of employment opportunities?
3. Which state would be the best for children to attend?
4. Which state is the most affordable for a family?
5. Based on these criteria which state is best to live in?

# Datasets
|No|Source|Link|
|-|-|-|
|1|Australian Bureau of Statistics - Housing|https://www.abs.gov.au/statistics/people/housing/housing-occupancy-and-costs/2019-20|
|2|Australian Curriculum, Assessment and Reporting Authority|https://www.acara.edu.au/contact-us/acara-data-access|
|3|Australian Bureau of Statistics - Crime and Justice|https://www.abs.gov.au/statistics/people/crime-and-justice/recorded-crime-offenders/2020-21#data-download|
|4|Australian Bureau of Statistics - Labour Force|https://www.abs.gov.au/statistics/labour/employment-and-unemployment/labour-force-australia/latest-release#key-statistics|

# Analysis

### Question 1 - Which state is the safest?
The ABS has public data on recorded crime offences available online and updated yearly.
Using this data, we are able to make an accurate assumption of which State would be the safest to live in. 

![chart](./Crime%20Data/images/Graph1.png)

The above shows the offender rate per 100,000 persons over the last 5 years. 
All states have gradually declined and made improvements on having less offenders. The 5 largest states are have similar averages.
Northern Territory has by far the highest amount of offender rates with one of the smallest populations.
ACT has the lowest offender rate while still declining showing it to be the safest State in Australia.

![chart](./Crime%20Data/images/Graph2.png)

The above bar graph shows the recorded offences in 2021 relating to either theft, illicit drug usage or violent acts.
SA & QLD have a higher illicit drug offences and correlates to more violent acts.
NT & NSW have significantly higher acts intended to cause injury compared to minor offences.
ACT has the lowest offender rates in all 3 categories.

### Question 2 - Which state is the best of employment opportunities?

For this question the information was sourced from the ABS:  "Underutilised persons by State and Territory and Sex - Trend, Seasonally adjusted and Original"  
For context, better understanding and according to the ABS:
-Underemployment is classified as persons who are not fully employed according to whether they are looking for and/or available to start work with more hours. 
-Unemployement is classified as persons who during a specified reference period, is not employed for one hour or more, is actively seeking work, and is currently available for work.

![chart](./Employment_Unemployment/Figures/Unemployment.png)

![chart](./Employment_Unemployment/Figures/Underemployment.png)

From the charts & analysis we can conclude the following:
Based on both Unemployment and Underemployment criteria, Northern Territory and Australian Capital Territory have the lowest rates.
In Addition, Western Australia and Australian Capital Territory had more resistance to change in the status in relation to the Covid-19 Pandemic
The relation between both criterias is evident. Although presenting different figures, when illustrated in the line chart their identical which denotes the close relation between them.  


### Question 3 - Which Australian state would be the best for children to attend?

The Index of Community Socio-educational Advantage (ICSEA) is a scale of socio-economic advantage that takes data collected about student family backgrounds and the variables that have statistically strong correlation to student performance and calculates the value on a scale with a median of 1000 and a standard deviation of 100.

![chart](./School%20Data/Output/ICSEA_Bar.png)

The above graph narrows the data to three years and also starts at an ICSEA of 700. Here it is clearly shown that most states have a positive trend to an increasing ICSEA. While the ACT currently displays a decreasing trend it's overall average is above the rest and so for this criteria the ACT is the best state to attend school depending on the average ICSEA.

![chart](./School%20Data/Output/Class%20Size.png)

Class size is a factor in a students learning. Using the Full Time Equivalent Enrollment and divided by the Full Time Teaching Equivalent I calculated the average class size per school. Then calculated the average size of a class per state. Based on the above graph the class sizes overall have been rapidly decreasing through the years. Tasmania however has the smallest class sizes in 2020 and therefore is the state that is the best in this category.

### Question 4 - Which state is the most affordable for a family?

The most affordable state using the mean housing costs. 
According to the ABS website the definition of housing costs is are defined as the sum of rent payments; rate payments (water and general); and mortgage or unsecured loan payments (if the initial purpose of the loan was primarily to buy, add, or alter the dwelling).

The charts below show the mean housing costs for couples with dependent children and one parent families with dependent children across the states over a 5 year period.

![chart](./Housing%20Data%20Complete/Images/Mean%20Housing%20Cost%20for%20couple%20family%20with%20dependent%20children.png)

The data shows that the most affordable state for a couple with dependent children in 2019-20 was Tasmania.
The mean housing cost remained comparable across the 5 years from 2015-20
The data shows that the least affordable state for a couple with dependent children in 2019-20 was NSW.

![chart](./Housing%20Data%20Complete/Images/Mean%20Housing%20Cost%20for%20single%20family%20with%20dependent%20children.png)

The data shows that the most affordable state for one parent with dependent children in 2019-20 was Tasmania.
The mean housing cost also remained comparable across the 5 years from 2015-20
The data shows that the least affordable state for a couple with dependent children in 2019-20 was NSW.

### Question 5 - Based on these criteria which state is best to live in?

From the analysis above the Australian Capital Territory is the best Australian states to live in according to the cirteria chosen by our research group.
