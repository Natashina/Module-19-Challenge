# Module-19-Challenge

## The purpose of this Challenge is to build your own machine learning model that will be able to predict the success of a venture paid by Alphabet soup and use different strategies on improving a model's performance.

### 1. Exploring the data types in our dataframe by org_df.dtypes, we find out that most of the columns are with categorical values and four columns with numerical values - EIN, STATUS, ASK_AMT, IS_SUCCESSFUL. Therefore we had to convert data with object data type to numeric. 

### 2. Looking at the unique value counts, there are a number of variables that appear frequently in the dataset, however, many of them appear semi-frequently and even rarely appear in the dataset. According to the nunique method, some of the categorical variables have more than 10 unique values, such as APPLICATION_TYPE, CLASSIFICATION, etc.
The OneHotEncoder has been used to produce encoded DataFrames for APPLICATION_TYPE, CLASSIFICATION, AFFILIATION, etc. the categorical variable list

### 3. 
