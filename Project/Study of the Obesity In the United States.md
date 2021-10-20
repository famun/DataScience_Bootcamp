Fahad Almunif
# Abstract
The goal of this project is to connect the education level and income to the obesity rates in the United States for a chosen year.
By doing so, we will be able to gain an insight on how they affect the obesity, therfore, finding means to reducce the obesity rate.
The ones benefitting from the study is the health industry and the citizens by taking into account the common factors or keys that 
indicate an increase in the obesity for certain individuals.
The scope of the project or the questions i hope to find an answers to from the study. 
How does the economy affect obesity?
which states suffer from obesity the most?
what is some approaches that might limit the obesity levels?
# Design
The project is centerd around the obesity in the United States and how the socieconomics levels affect it. 
The data was obtained from Kaggle and originally the data is from the Behavioral Risk Factor Surveillance System.
trying ot find a connection will give the opportunity to reduce the obesity rate by taking the measuremnets the study shows us.
# Data
The data contains 53392 entries which corrosponds to each state for different years and different people, it also contains 33 features
such as the year that the study was conducted, the location abbreviated and spelled out, the data value and some survey questions, it also has
information regarding the income levels, education levels, gender and Race/Ethnicity. we will not be using all the features because 
it contains more than what we need, our goal is to look into the education and income connection to the obesity only.
# Algorithms
Other than the tools used for data cleaning and analysis of the dataset. A linear regression model is developed to show how the regression coffecients chagnes depending on 
the different levels of the sociecononmics. the regression coffecient shows us which of the levels has the least amount of risk to obesity, for the year 2015 since it had 
the most data samples, the education levles regression coffecients were found to be:
- 4.3 for less than highschool education
- 3.6 for highschool education
- 3.1 for some college or technical school education
- R^2 to show how much of the linear model it corralate to yeilded: 48% which is considered good for a new study

which leads us to determine that as ones gain more education then their risk of obesity decreases. As for the income levels it was found:
- $15,000 − $24,999 : -1.8
- $25,000 − $34,999 : -3.8
- $35,000 − $49,999 : -4
- $50,000 − $74,999	: -4.2
- $75,000 or greater : -8.5
- R^2 to show how much of the linear model it corralate to yeilded: 29% which is considered acceptable for a new study

which leads us to determine that as ones gain more income then their risk of obesity decreases, however keeping in mind thaat the place of living might affect this as well.
# Tools
- numpy to manipulate numbers
- pandas to edit tables and merge
- matlap to plot alongside seaborn
- seaborn for visualization
- sklearn to train the model for the education and income cases
# Commmunication
Other than the PowerPoint presentation that could be find alongside this porject, multiple visualization attempted to make the project as easy as possible for interpretation,
the results were: 
- 1 graph that shows all 51 states from most obese to least obese for a chosen year 
- 4 graphs that shows the obesity rate depedning on the education level breakdown. 
- 1 graph that shows the obesity rate depending on the income level
- 2 graphs that shows the linear regression coeffecient for the education level and income level which helps us in understanding possible solutions.
