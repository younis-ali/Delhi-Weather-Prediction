# Delhi-Weather-Prediction
This notebook performs the time series weather prediction of temperature in delhi using Deep learning. The other methods available are Regression Models. The reason to choose the Deep learning are:
1. Deep Learing models are good in feature engineering.
2. Deep learning models show good accuracy than regression models.
3. We have Keras framework available that provide most of the deep learing APIs.

We use Pandas,Numpy and other libraires to perform Descriptve Analysis and then Predective Analysis
# 1.Data Acquisition
It is the process of loading the historic data. In pandas the data is loaded into the Dataframe and we can load most of the tabular data formats into Data frames. Data frames automatically extracts the attributes from data and also assigns the required types to the  attributes.
Data Wrangling: Data wrangling is the process of cleaning and unifying messy and complex data for easy access and analysis. The main tasks of this step are: Data Exploration, Dealing with missing values, Reshaping the data. If required we can perform the data wrangling step on the data frame according to our needs. Pandas provide a variety of methods to achieve data wrangling. For example, replace() method is used to fill the missing values in data, map() method is used to reshape the data, groupby() method groups the data on a specific attribute. 
The most important task of data wrangling in our case (temperature feild) is Data slicing. In this process we extract only those attributes that are to be manipulated.
# 2.Descriptive Analysis
After performing the above steps we can write the following programmes to achieve descriptive statistics on the temperature data. We can also visualise the results graphically by using the matplotlib library.
# 3. Predictive Analysis
To perform the predictive analysis we first need to train the machine learning model that will later on do predictions with a particular confidence score.
