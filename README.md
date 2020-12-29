# Notebook Description

This notebook contains the process and results of the data analysis performed on a set of rental bike demand data. The aim of analysis is to bulid statistical learning models which can predict the bike sharing demands and identify the key features that are strongly associated with them.

The second section of the notebook explores the basic contents of a given dataset. It shows a structure of each attibute and brief statistical information of them.

The third section covers the exploratory data analysis to understand the characteristics and distribution of each attibute, and the correlation between them through visual aids.

The fourth section explains the methodology of the models which will be used in this experiment.

The fifth section is related to model development which is about how to derive the models used in the experiment, such as the method used to select model parameters.

The sixth secton discusses the results derived from the previous model development section.It will look at the pros and cons of each model and the important predictors extracted from those models.

Lastly, in the last section, the key findings of this experiment will be elaborated.


# Attribute information

Date : year-month-day <br>
Rented Bike count: Count of bikes rented at each hour, the response variable 
Hour: Hour of the day
Temperature: Temperature in Celsius
Humidity: in %
Windspeed: m/s
Visibility: 10m
Dew point temperature: Celsius
Solar radiation: MJ/m2
Rainfall: mm
Snowfall: cm
Seasons: Winter, Spring, Summer, Autumn
Holiday: Holiday/No holiday, indicating if the corresponding date is a public holiday or not
Functional Day: NoFunc(Non Functional Hours), Fun(Functional hours), the variable indicates the days when the rental bike system does not operate.
