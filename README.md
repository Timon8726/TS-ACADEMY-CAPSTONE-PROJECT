# TS-ACADEMY-CAPSTONE-PROJECT
CAPSTONE-Project-- the dataset worked on is a medical dataset for determining the life expectancy of people suffering from different disease in different countries around the world from the period of the year 2000 to 2015at All neccesary libraries needed to work on the dataset was imported 
Pandas was imported to read in the data and also used for filtering the data
Simple imputer was used to handle missing values
Then an explorative data analysis (EDA) was carried out, using matplotlib and seaborn, an histogram was plotted with kernel density plot to show the distrubution of every column on the dataset
A corellation heatmap was also plotted to see how each disease and condition affects the life expectancy of the people in the different region on the dataset
On the project, two different machine learning models were built to predict the life expectancy of the people, these models are the linear regression model and random forest regression
The result from both models suggested that  socio-economic and health indicators are meaningful predictors of life expectancy. with a MEAN ABSOLUTE ERROR OF 4.2% and an R-squared value of 0.8
meanwhile, the random forest model identifies HIV/AIDS as the most predictive feature for life expectancy of the people
In summary, comparing both models,The Random Forest model significantly outperformed Linear Regression in predictive accuracy.

as such, it can be concluded that  life expectancy is strongly influenced by both health indicators and socioeconomic factors. Disease prevalence, particularly HIV/AIDS, plays a dominant role, while economic development and mortality rates are also critical drivers.

Below is the dictionary for the dataset
Columns Description
Country: Name of the country where the data was recorded.
Year: The year the data was collected.
Status: Classification of the country as Developed or Developing.
Life expectancy: Average number of years a newborn is expected to live.
Adult Mortality: Probability (per 1000 population) that a person aged 15–60 will die.
infant deaths: Number of infant deaths (under 1 year) per 1000 population.
Alcohol: Per capita alcohol consumption (litres of pure alcohol) among people aged 15+.
percentage expenditure: Health expenditure as a percentage of GDP per capita.
Hepatitis B: Percentage of 1-year-olds vaccinated against Hepatitis B.
Measles: Number of reported measles cases per 1000 population.
BMI: Average Body Mass Index of the population.
under-five deaths: Number of deaths of children under age 5 per 1000 population.
Polio: Percentage of 1-year-olds vaccinated against Polio (Pol3).
Total expenditure: Government health expenditure as a percentage of total government spending.
Diphtheria: Percentage of 1-year-olds vaccinated against DTP3 (Diphtheria, Tetanus, Pertussis).
HIV/AIDS: Deaths due to HIV/AIDS per 1000 live births (ages 0–4).
GDP: Gross Domestic Product per capita (in USD).
Population: Total population of the country.
thinness 1-19 years: Percentage of children and adolescents (ages 10–19) who are underweight.
thinness 5-9 years: Percentage of children (ages 5–9) who are underweight.
Income composition of resources: Human Development Index (HDI) income component (range 0 to 1).
Schooling: Average number of years of schooling completed.
