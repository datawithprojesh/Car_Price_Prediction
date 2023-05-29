1. created a new environment (Env Name: carprediction)
To do this google manage anaconda environment and from the first link copy this following command: conda create -n myenv python=3.9. Here you need to change the env name (myenv).
I have used myenv = carprediction
2. changing directory
To do this open anaconda prompt and copy the folder path and paste it. Then activate your environment. In this case carprediction
3. create a python3 notebook
4. steps followed to create the model
a. importing libraries like pandas and numpy
b. load the data
c. find out various details about data like unique values and shape
d. check for null values
e. feature engineering. Here i have created a new column to find the age of the car
f. then drop the columns which are not needed
g. convert categorical columns by using one hot encoding. pd.get_dummies function is suitable here and use drop_first=True. dummy variable trap
jh.