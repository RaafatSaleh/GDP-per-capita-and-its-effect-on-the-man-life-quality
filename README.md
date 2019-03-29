# GDP per capita and its effect on the man life quality: Gapminder datasaet Investigation

**Introduction**

My objective is to identify the impact of GDP growth on four metrics of human well-being: Income, Human Development Index (HDI) and Life Expectancy. In this investigation, I used four data sets from the Gapminder to identify trends of the change in GDP over time as well as other indicators according to different countries and regions of the world.

All data files are arranged by country and have not region file, for that I doanloaded the region file from github page.

**Step One: Posing Questions**

**Research Questions:**

**1-** What is the effect of GDP on Income, Human Development Index(HDI) and Life Expectancy?

**2-** Are there trends that can be observed between all selected metrics with each other? (correlation matrix)

**3-** What are the distributions of each one of the four metrics chosen according to the countries? and according to time (years)?

**4-** Have certain regions of the world been growing in the four metrics better than others?

**5-** Have certain sampled countries (for example Egypt, USA, etc ... ) of the world been growing in the four metrics better than others?

**Datasets Files:** 
For answering the quesitions above I download the folowing files from Gapminder page:

**1-** GDP file: gdppercapita\_us\_inflation\_adjusted.csv

**2-** Income file: income\_per\_person\_gdppercapita\_ppp\_inflation\_adjusted.csv

**3-** HDI file: human\_development\_index.csv

**4-** Life Expectancy file: life\_expectancy\_years.csv

and one file from github for Regions

**5-** World Regions file: world\_regions.csv


**2nd Step: Data Wrangling**

**2-1-** Gathering and reading data**

**2-2-** Assessing the data and Building Intuition**

**2-3-** Cleaning Data**


**3rd Step: Exploratory Data Analysis**

Research questions answers


**The Conclusion**

**1.** According to years for all countries there is a strong positive correlation between GDP and all the other metrics. But..

**2.** After calculating the correlation matrix according to countries for all years, I can conclude that GDP and Income are still positive strongly correlated and GDP does not affect the other metrics (no correlation) that appear clearly in GDP with Life Expectancy and GDP with HDI plots.

**3.** Distributions according to years show a righ skewed in GDP and Income that show the most countries are lower in GDP and income(which clearly appears in the GDP and Income boxplots as outliers). However, both HDI and Life Expectancy are almost left skewed in order to these metrics depend on health and education not economic indicators .

**4.** Europe region is growing in the four metrics over the years and Asia comes after Europe in GDP and Income but Americas come the second in HDI and Life Expectancy and Africa comes in the end of the list of regions in all metrics (as expected)

**5.** According to my selected countries, UAE comes the first in GDP and Income however Australia comes first in HDI and Life Expectancy, but Egypt occupy the last one of the list in GDP and Income as shown in previous bar and line charts.
