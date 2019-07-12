# Airbnb-Analysis-and-Simple-Modeling
This is a short  project provided by Springboard's free course Introduction to Business Analytics. 
The data from Airbnb features four markets (Amsterdam, Austin, New York, and Taipei).

**The following is a list of concepts explored and programs used:**
- Excel
  - PivotTables
  - SUMIFS()
  - IFERROR()
  - VLOOKUP()
- Statistics
  - Descriptive statistics, such as: average, counts, etc.
  - Inferential statistics, such as: correlation, simple linear regression, etc.
- Modeling

This short project also answers the following questions:
- 1. What is the average listing price per market?
- 2. What is the property type distribution per market?
- 3. Is there a correlation between average host response time and number of reviews?
- 4. Is there a correlation between average rating and cleaning fee?
- 5. Based on yearly profits, what is the most attractive market for new host listings?
- 5. How many listings per city are making more than the average profit per city?

I've also expanded the original scope of questions and included advice on the next phase of financial analysis. The biggest takeaway would be to collect data on more Asian markets. 

When I was analyzing the data, I saw that there was a strong, negative correlation between average listing price and average host response time __WHEN__ I took omitted data from the Taipei market. The reasons for omitting the data can be seen in comparisons between the Taipei market and the other markets. Moreover, Taiwan haschanged its economic status as developed in the WTO as recently as 2018. Links of the comparison are below:

- https://www.numbeo.com/cost-of-living/compare_cities.jsp?country1=Taiwan&country2=United+States&city1=Taipei&city2=New+York%2C+NY
- https://www.numbeo.com/cost-of-living/compare_cities.jsp?country1=Taiwan&country2=United+States&city1=Taipei&city2=Austin%2C+TX
- https://www.numbeo.com/cost-of-living/compare_cities.jsp?country1=Taiwan&country2=Netherlands&city1=Taipei&city2=Amsterdam

Analysis would be more congruent if similar markets in terms of purchasing power, geolocation, strength of currency, and other economic factors were investigated groupwise since the hotel/travel/tourism industry is based on said factors. It would be interesting to determine if the insights generated in this project would transition well when more data is included. 

Note to reader: 
This is an __extremely__ rudimentary introduction to business analysis and should be treated as such. There is space for further exploration of the nuances of the question prompts. I will update the files as I gain more knowledge. Seeing that the data set is limited and already preset as an introduction to financial analysis, the amount of analysis in this project will also be limited.

Another note:
I really like box and whisker plots to convey distributions. Unfortunately, my version of Excel (Mac 2011) doesn't have a proprietary ability to do so. BUT, I will follow the way Peltier describes on how to make a box and whisker plot (https://peltiertech.com/excel-box-and-whisker-diagrams-box-plots/).
