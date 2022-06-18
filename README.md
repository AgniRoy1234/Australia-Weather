# Australia-Weather
Predicting weather is an importamt aspect of daily life. Various meteorological organisations have been using the power of data to make their predictions more accurate. These predictions can influence many important decisions. For example, in areas of agriculture, fishing, travel prediction of weather becomes extremely crucial

#About the dataset
The dataset has been obtained from the website of Australian Government,Bureau of Meteorology.
Quoting from the website
"These observations have been taken from the Bureau of Meteorology's "real time" system. Most of the data are generated and handled automatically. Some quality checking has been performed, but it is still possible for erroneous values to appear.

From time to time, observations will not be available, for a variety of reasons. Sometimes when the daily maximum and minimum temperatures, rainfall or evaporation are missing, the next value given has been accumulated over several days rather than the normal one day. It is very difficult for an automatic system to detect this reliably, so caution is advised."
source-http://www.bom.gov.au/climate/dwo/IDCJDW0000.shtml

The includes 23 columns. The target variable is RainTomorrow.Features like Minimum Temperature,Rainfall,WindDirection etc have been used to make the prediction.

Models that have been used here 
Decision Tree,AdaBoostClassifier, Naive Bayes,KNN, StackingClassifier 
