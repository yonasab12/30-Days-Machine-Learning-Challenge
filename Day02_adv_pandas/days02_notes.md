In Pandas, .loc and .iloc are two of the primary methods for selecting and accessing data in a DataFrame or Series. They differ in how they index and retrieve data.

we are going to see grouping and aggregating using pandas. Grouping and aggregating will help to achieve data analysis easily using various functions. These methods will help us to the group and summarize our data and make complex analysis comparatively easy.  
 Aggregation in pandas provides various functions that perform a mathematical or logical operation on our dataset and returns a summary of that function. Aggregation can be used to get a summary of columns in our dataset like getting sum, minimum, maximum, etc. from a particular column of our dataset. The function used for aggregation is agg(), the parameter is the function we want to perform.
  Function Description:


sum()         :Compute sum of column values
min()          :Compute min of column values
max()         :Compute max of column values
mean()       :Compute mean of column
size()          :Compute column sizes
describe()  :Generates descriptive statistics
first()          :Compute first of group values
last()          :Compute last of group values
count()       :Compute count of column values
std()           :Standard deviation of column
var()           :Compute variance of column
sem()         :Standard error of the mean of column