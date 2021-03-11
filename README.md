# WorkingRemotely

Libraries Used:
numpy
pandas
matplotlib.pyplot
from sklearn.linear_model import LinearRegression
from sklearn.model_selection import train_test_split
from sklearn.metrics import r2_score, mean_squared_error
seaborn
%matplotlib inline

Motivation:
This is an exercise in basic data analysis using a single dataset. Specifically, this looks at working remotely and the effects of that on salary, job satisfaction, etc.

Files:
CPSurveyAnalysis.ipynb - This is the notebook for analysis

Results:
The only reliable information that can be drawn from the analysis is that the more experience that you have, the more likely it is that you will be able to work remotely.

Acknowledgements:
The dataset was downloaded from Kaggle and presented by StackOverflow

# Questions:
#  1. Does working remotely lead to higher salary?
#  2. Does working remotely lead to higher job satisfaction?
#  3. Does experience affect working remotely?
#  4. Does country/location affect working remotely?

# Business Understanding:
As the world flattens through easy data transfer and communication, jobs can now be executed from anywhere. From the employer's perspective, this could mean lower salaried employees by taking advantage of lower wage rates in certain countries. From the employee's perspective, this could mean flexibility to live wherever you want and still hold down the same salary. Hopefully the data will tell us which one (or both) are winning out.

# Data Understanding:
The 2017 survey from StackOverflow provides good data from job seekers and current programmers about where they live, how much they make, whether they work remotely and their job satisfaction. Because it is a survey, not all questions are answered for each respondent, so some data cleaning needs to be done.

# Prepare the Data:
Survey data was downloaded from Kaggle. Data was loaded into a dataform. From there, minimal cleansing needed to be done. Looked at the percentage of respondents that answered the salary question vs. the job satisfaction question. Data was further prepared by quantifying the remote work answers into numeric ratings.

# Data Modeling:
Several visualizations and data slicing models the data for us into charts and tables that are easier to analyze and understand.

# Evaluation:
The results are mostly inconclusive. The one main take-away is that the abillity to work remotely increases with the number of years of coding experience. This makes sense as working remotely can often be working in isolation and the more experienced the programmer is, the less guidance and help they will need.

More data from successive years would be helpful.
