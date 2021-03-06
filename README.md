# PortfolioProject11
IBM Data Science project in Python : Predicting House prices

Project Idea : This was one of the projects in the IBM Data Science certification course conducted by Coursera in collaboration with IBM. 
In this assignment, I am a Data Analyst working at a Real Estate Investment Trust. The Trust would like to start investing in Residential real estate. I am  tasked with determining the market price of a house given a set of features. We will analyze and predict housing prices using attributes or features such as square footage, number of bedrooms, number of floors, and so on. 
We will use Watson Studio to perform the analysis, and prepare a Jupyter notebook with a URL that can be shared. 

Resources used: Coursera certification course : https://www.coursera.org/professional-certificates/ibm-data-science

Data Source : In the form of a series of csv files was provided in the Coursera Case study. <br>
https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBMDeveloperSkillsNetwork-DA0101EN-SkillsNetwork/labs/FinalModule_Coursera/data/kc_house_data_NaN.csv
<br>This dataset contains house sale prices for King County, which includes Seattle. It includes homes sold between May 2014 and May 2015.

Tools used : Python, Jupyter Notebook and Watson Studio

ANALYSIS STEPS:

ASK - Problem description (provided in exercise)

PREPARE - Data collection and organization. Data was downloaded from Coursera. Reading in the csv files into the Python (Jupyter Notebook) environment that was created in Watson Studio.

PROCESS - Data wrangling involved dropping un-necessary columns, summarizing columns, identifying NaN (missing) values and replacing with 'mean' values.<br>
Exploratory Data Analysis included visualizing data with sns.boxplot() and sns.regplot() as well as investigating correlation factors for each feature.

ANALYZE - Created linear models with single feature and multiple features and compared R^2 values. Created a prediction model using Pipeline, utilizing multiple features with Normalization+Polynomial transformation+Linear regression and calculated its R^2 value. <br>
Split the data - created a training set and test set (15%) for further Ridge Regression analysis.<br>
Created Ridge regression models with 2nd degree Polynomial transformation on the training and test sets and calculate R^2 values

SHARE - Summarized findings, conclusions and recommendations in the same Jupyter Notebook

Note: The Jupyter notebook template was provided while I ha to write the code to the questions in the template.
