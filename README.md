# Covid-19-and-its-effects-on-Life
This is an analysis of Covid-19 and its effects on our lives. The language used in Python and is created on a Jupyter Notebook where the data was visualised using Seaborn. Through this project I was able to analyse how the spread of Covid-19 has effected the lives of people in different countries.

The Covid Dataset has the total number of daily infections reported from Jan 22, 2020 to Dec 22, 2020 and it looks like:
![alt text](https://github.com/alizaazizlakho/Covid-19-and-its-effects-on-Life/blob/main/pictures/Covid%20dataset.png)

After removing the unnecesary columns (such as Longitude and Latitude) and Merging some rows together (since the covid rates for Australia were divided in 4 rows). This helped in the next step which was finidng a good measure for all countries which was chosen to be the maximum infection rate. Then the data looked something like:

![alt text](https://github.com/alizaazizlakho/Covid-19-and-its-effects-on-Life/blob/main/pictures/MaxInfectionRate.png)

Next step was getting the data from the World Happiness Report which initially looked like:

![alt text](https://github.com/alizaazizlakho/Covid-19-and-its-effects-on-Life/blob/main/pictures/World%20happiness%20report.png)

After dropping the columns we did not need, the dataframe looked like:

![alt text](https://github.com/alizaazizlakho/Covid-19-and-its-effects-on-Life/blob/main/pictures/cleaned%20whr.png)

Now it was time for some simple linear regression to find the correlation between the maximum infection rate in the countries and their standings in GDP per capita, Social Support, Healthy life expectency, and Freedom to make life choices.

## GDP per capita vs Max infection rate

![alt text](https://github.com/alizaazizlakho/Covid-19-and-its-effects-on-Life/blob/main/pictures/LR1.png)

## Social Support vs Max infection rate

![alt text](https://github.com/alizaazizlakho/Covid-19-and-its-effects-on-Life/blob/main/pictures/LR2.pngg)

## Healthy Life Expectancy vs Max infection rate

![alt text](https://github.com/alizaazizlakho/Covid-19-and-its-effects-on-Life/blob/main/pictures/LR3.png)

## Freedom to make life choices vs Max infection rate

![alt text](https://github.com/alizaazizlakho/Covid-19-and-its-effects-on-Life/blob/main/pictures/LR4.png)


