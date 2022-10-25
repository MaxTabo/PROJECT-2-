
##World Happiness Report Project.
Maximiliano Tabó


###Table of Contents:
**1-Intro.**
**2-Goal.**
**3-Data.**
**4-Steps.**
**5-Visualizations and Conclusions.**



###1-Intro.
The World Happiness Report is a publication that contains articles and rankings of national happiness, based on respondent ratings of their own lives, which the report also correlates with various life factors.

The report is a publication of the Sustainable Development Solutions Network, a global initiative of the United Nations. The report primarily uses data from the Gallup World Poll.

###Methods.
The rankings of national happiness are based on a Cantril ladder survey. Nationally representative samples of respondents are asked to think of a ladder, with the best possible life for them being a 10, and the worst possible life being a 0. They are then asked to rate their own current lives on that 0 to 10 scale. The report correlates the life evaluation results with various life factors.
Some of the key variables of the Happiness Index are:
*-GDP per capita*
*-Social support*
*-Healthy life expectancy*
*-Freedom to make life choices*
*-Generosity*
*-Perceptions of corruption*


###2-Goal.
For this project the goal is to contrast the different variables, intending to identify the prevalence of them whithin the 'Scores' given.




###3-Data.
In order to run the project the following libraries are needed to be installed:

*-requests*
*-BeautifulSoup*
*-pandas* 
*-re*
*-json_normalize*
*-json*
*-os*
*-seaborn* 
*-numpy*
*-matplotlib.pyplot*

###4-Steps.

Load the datasets into a DataFrame using Pandas, and explore them.
Set up the Data and do the cleaning, handle missing, incorrect or  not required information, and state Functions to make the work more compfortable.
After dropping the needless columns, proceed to create subsets to analize specific variables.
Eventually, assemble plots to start drawing conclusions.


###5-Visualizations and Conclusions.
####Heat map
<img src='Images\HEATMAP.png'>
As it is easily noticeable, the strongest correlation with the 'Happiness Score' are the variable s'GDP per capita'(0.82 coefficient) and 'Life Expectancy(0.75)'. So, at first sight, we can establish that incomes and health have much more weight than the other variables.
###Head and Tail
<img src='Images\HAPPINESS.png'>
Here we have a barplot showing the difference between the 'Top 5' and the ones that are on the bottom of the ranking. The countries with a higher 'Happinnes Score' are european countries and Canada. And on the other hand, we have countries in war, and from the 'deep third world'.
As we can see below, we have a scatterplot per Regions.
<img src='Images\HAPPY_SCATTER.png'>

###Happiness and Economy
<img src='Images\ECONOMY.png'>

This plot show as something remarkable. At the beggining of the conclusions we said that GDP was strongest variable.But just one country in the top 10 Ranking is one the 5 countries with the most GDP per capita. This probably is due to that the majority of the countries with highest GDP have a strong control of the Government, as Qatar, Kuwait and Singapore.
#####Scatter per Regions
<img src='Images\GDP_SCATTER.png'>
###Happiness and Freedom.
<img src='Images\FREEDOM.png'>
Here we can see the connection between them Happiness and Freedom. The light-colour ones have a higher freedom rates and are on top of the Ranking.
###Suicide rate and Happiness
<img src='Images\SUICIDE.png'>
I couldn't find any notorious relation between Happiness and suicide rate.


###Box plots of Happiness all over the World and per Regions.

<img src='Images\HAPPY_boxplot.png'>



<img src='Images\REGIONS_SCATTER.png'>










#####Links and Resources
https://www.kaggle.com/
https://www.shutterstock.com/
https://data.worldbank.org
https://en.wikipedia.org/
https://worldlifeexpectancy.com
https://www.gallup.com/