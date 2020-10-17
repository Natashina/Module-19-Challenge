# Module-19-Challenge

## The purpose of this Challenge is to build your own machine learning model that will be able to predict the success of a venture paid by Alphabet soup and use different strategies on improving a model's performance.

1. Exploring the data types in our dataframe by org_df.dtypes, we find out that most of the columns are with categorical values and four columns with numerical values - EIN, STATUS, ASK_AMT, IS_SUCCESSFUL. Therefore we had to convert data with object data type to numeric. 

2. Looking at the unique value counts, there are variables that appear frequently in the dataset, however, many of them appear semi-frequently and even rarely appear in the dataset. According to the nunique method, some of the categorical variables have more than 10 unique values, such as APPLICATION_TYPE, CLASSIFICATION, etc.
The OneHotEncoder has been used to produce encoded DataFrames for APPLICATION_TYPE, CLASSIFICATION, AFFILIATION, etc. With Pandas’ merge and drop methods
the original columns were replaced with encoded features.

3. ASK_AMT column contains 8747 different amounts. To group them there were eight bins created as following:  ['<10K', '10K-24.9K', '25K-99.9K', '100K-999.9K', '1M-4.9M', '5M-9.9M', '10M-49.9M', '50M+']

4.
