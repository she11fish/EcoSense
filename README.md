# Can GDP cause the HDI to Increase?
Hypothesis
As Gross Domestic Product (GDP) increases, the Health Development Index (HDI) will increase as well. This should apply globally.
Secondary Data Collection and Analysis The following data was collected from Statistics Data sources from Human Development Reports (https://hdr.undp.org/data-center/documentation-and-downloads) and Kaggle (https://www.kaggle.com/datasets/yapwh1208/countries-gdp-2012-to-2021).

Disclaimer:  whenever 1990-2021 is mentioned for HDI and GDP, those years are actually 1990, 2000, 2010, 2015, 2018, 2019, 2020, and 2021.

The graph above shows a strong correlation (R2 = 0.777) from 1990-2021.
Interestingly, the higher the GDP, the higher the HDI the country experiences on average until it reaches an optimum. After that optimum, the HDI, according to the predicted line, is lowered. However, the actual HDI on the graph increases as the GDP increases.



Since both of GDP and HDI are increasing, then the GDP vs HDI graph should normally increase (especially when the HDI graph has R = 0.9915 and GDP graph has R = 0.9783)

Full GDP data graphed (1960 to 2020)
The graph has a very strong correlation of R2 = 0.977, which means that the GDP increases for every country on average per year
The GDP vs HDI graph residual
There seems to be 4 outliers (the last three dots on the right, and the highest point on the left of the graph). Correlation can be enhanced by removing Norway, Ireland, Luxembourg, and Sri Lanka from the graph.
After excluding the outliers, the graph has an even stronger correlation of R2 = 0.854. Removing the 4 points out of 71 (5.63% of data) seems like a reasonable amount of data to be removed from the graph.
Conclusion
Based on data from the GDP vs HDI graph from 1990 - 2021, the HDI increases as GDP increases until it reaches an optimum, then the GDP no longer affects the HDI as much as it did and it even is decreasing (according to the predicted graph). Removing the outliers re-emphasize that same pattern mentioned, which implies that this phenomenon is potentially true. One issue with that claim is that the actual HDI is not decreasing at all even after removing the outliers. If there was more time to analyze the data, a regression line would be graphed separately with the highest GDP countries. This would have helped clear up the discrepancy of the HDI not really decreasing but the regression curve implies the opposite 


the United Nations Development Programme (UNDP) methodology behind finding the HDI
UNDP carried out its research of HDI for each country by determining the 3 dimension indices:
Life Expectancy Index
Education Index
GNI Index ( “a measure of statistical dispersion intended to represent the income inequality, the wealth inequality, or the consumption inequality within a nation or a social group” Wikipedia) is measured by finding the GNI per capita (“the dollar value of a country's final income in a year divided by its population”)

The UNDP is very reliable therefore, the data is most likely unbiased and reliable. However, measuring HDI is difficult since the Life Expectancy Index can differ from person to person depending on the circumstances of the country, so one unexpected circumstance, such as a pandemic that killed thousands of people, can greatly impact the Life Expectancy Index, which affects the HDI. As for the Education Index, it is naturally a quantitative measure, which means the Education Index can not be as misleading as the Life Expectancy Index. One issue with the Education Index is the “Expected years of schooling” as it is an assumption made towards each individual person’s potential years of schooling, which could be inaccurate. Lastly, the GNI index is determined by finding the GNI per capita, which is also a good quantitative measure, but the GNI index itself, according to Wikipedia, is inequalities in wealth, consumption, income within a nation. However, measuring this GNI index is pretty difficult to acquire accurately. As a result, the HDI index of each country is not necessarily the most accurate form of data, but it came from a reliable source.
Finding the background of the GDP data’s extraction methods has not yet been found, so more time is needed to trace the original source to determine its accuracy, and potential sources of bias.
For the data presented to be more reliable, HDI should have started from the years 1960 to 2021 as GDP for a more accurate assessment with more countries to be conducted.
Overall, the data seems to be indicative of the hypothesis claimed that “Gross Domestic Product (GDP) increases, the Health Development Index (HDI) will increase as well. This should apply globally.”


References
Indicator Metadata Registry Details. (n.d.). https://www.who.int/data/gho/indicator-metadata-registry/imr-details/3355#:~:text=Gross%20National%20Income%20(GNI)%20per,its%20population%20using%20Atlas%20methodology.
Wikipedia contributors. (2023). Gross national income. Wikipedia. https://en.wikipedia.org/wiki/Gross_national_income
United Nations. (n.d.). Documentation and downloads. Human Development Reports. https://hdr.undp.org/data-center/documentation-and-downloads
Countries GDP 1960 to 2021. (2023, April 21). Kaggle. https://www.kaggle.com/datasets/yapwh1208/countries-gdp-2012-to-2021

‌

‌



Appendix:

Info
GDP
HDI
count
71
71
mean
15374.50576
0.6933028169
std
20770.27162
0.1654110645
min
217.8992038
0.34975
25%
1381.632694
0.548625
50%
5158.595751
0.709375
75%
30388.23257
0.894875
max
97355.25725
0.936
median
5158.595751
0.709375



