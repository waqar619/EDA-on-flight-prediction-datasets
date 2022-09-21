# EDA-on-flight-prediction-datasets
EDA on flight prediction datasets

Following are the EDA done on it

Load both train dataset and train dataset in excel file.
Append both train and test dataset and stored in final_df variable.
There were two null value present in Route and Total_Stops and fill the null value with mode.
There were total 10 object and 1 float data types.
Split the data,month and year from Date_of_Journey feature and convert it to integer.
Also split hours and minutes from Arrival feature and convert tha data types from object to int.
Same process followed to Departure and duration.
And after spliting drop the feature from data Frame.
Used map function to change the variable.
we have done label encoding for categorical variable.
And now the datasets is ready for model training.
