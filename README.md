# AutomobileDataAnalysis
This project provides a simple step by step data analysis and model development for a simple automobile dataset.
The main goal is to get familiar with Numpy and Pandas tools in addition to Matplotlib and seaborn visualization packages to get initial insights of data and apply simple data cleaning approaches. The findings will help to decide which features are the most important features to predict a car price.
"Initial_Data_Wrangling.ipynb" and "EDA.ipynb" files show some initial data wrangling and EDA(Explorary Data Analysis) approaches along with visualization.
In "Model_Development.ipynb" file a Liniear Regression, a Multiple Linear Regression, and a Polynomial Linear Regression model is developed along with error analysis for each model. Finally, the model with the best error analysis result is chosen as the prediction model.

Notes : 
The main goal in this project is to apply EDA approach and utilize python tool to create a prediction model, therefore the data is not split to train and test subsets.

The data file "auto.csv" should be saved in a folder called "Data" in the same folder where the Python file is stored. The reason is that the data file path used in pd.read_csv() method is using the mentioned folder path.

The EDA Python file includes Exploratory Data Analysis (EDA) on "automobileEDA.csv" dataset which is almost the same as the first "auto.csv" dataset but with initial cleanup applied to it.
