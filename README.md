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
Rented Bike count: Count of bikes rented at each hour, the response variable <br>
Hour: Hour of the day <br>
Temperature: Temperature in Celsius <br>
Humidity: in % <br>
Windspeed: m/s <br>
Visibility: 10m <br>
Dew point temperature: Celsius <br>
Solar radiation: MJ/m2 <br>
Rainfall: mm <br>
Snowfall: cm <br>
Seasons: Winter, Spring, Summer, Autumn <br>
Holiday: Holiday/No holiday, indicating if the corresponding date is a public holiday or not <br>
Functional Day: NoFunc(Non Functional Hours), Fun(Functional hours), the variable indicates the days when the rental bike system does not operate. <br>

# Points could have been improved
1. As a data scientist, providing others (including publics) interesting insights of the data, rather than just telling them about statistical information.
2. Connecting the characteristics of data to model selection in more detail
3. Model comparison: 
1) Looking at other comparison metrics such as MAE (Mean Absolute Error) and CV (Coefficient of Variance) to compare different regression models 
2) Including more discussion and observation about R2 (R-squared) metric on the test data
3) Including more in-depth analysis and detailed comparison study such as model complexity
4) Drawing the calibration plot (actual vs. predicted values) to visually show the accuracy of the models
4. Removing redundant codes
