# Employee-Attrition-jobathon--21nov21
Employee attrition is a major cost to an organization and predicting such attritions is the most important requirement of the Human Resources department in many organizations. In this problem, task is to predict the attrition rate of employees of an organization.

# Data cleaning – In this section, I have done following process
1. Checked for Missing values/Nan/na.
2. Throw down Duplicate values after extracting useful information.
3. Replace the Nan values with jan-2018 in ‘Last date of Working’
column.

# Feature engineering and Selection –
1. I have introduced 2 features in dataset

* Attrition = from last date of Working.

* Year = No. of year employees worked in company (first
day of working – Last day of Working).

# Data visualization – 
I have find out correlation between the
variable

* Drop independent variable and unnecessary variable

* Drop Emp_ID Variable.

# Splitting of Data –
1. Data splitting is done in 80% (train) and 20 %( test) manner.
# Model-
KNN –Classifier
Why – Since we have classification problem, where K-NN algorithm
stores all the available data and classifies a new data point based on
the similarity. This means when new data appears then it can be easily
classified into a well suite category by using K- NN algorithm.
Where, N = 7

#Evaluation using Macro f1_score –
Macro f1_score of KNNclassifier at n=7:- # 0.7378640776699029

# Conclusion/prediction –
From prediction model result, we can assume that out of 741
employees, we can expect that 160 employees will leave the company
in the upcoming two quarters (01 Jan 2018 - 01 July 2018) and 581
employees will be remain at their designation.
