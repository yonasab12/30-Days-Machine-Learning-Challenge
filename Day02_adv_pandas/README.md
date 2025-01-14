<p>
  <img align="center" src="https://protoinfrastack-myfirstbucketb8884501-fnnzvxt2ee5v.s3.amazonaws.com/lAeXN1za8y45Vidyt7JGGcJgewRAXsrDjyRu.gif" alt="GIF Animation" ,hight="300",width="500"/>
</p>
In Pandas, .loc and .iloc are two of the primary methods for selecting and accessing data in a DataFrame or Series. They differ in how they index and retrieve data.

1. .loc (Label-Based Indexing)
What it Does: .loc is used to select data based on the labels (names) of rows and columns.

Key Features:

Uses explicit labels for indexing.
Includes the end of the range in slicing.
Supports boolean indexing and conditional filtering.


2.iloc (Integer-Based Indexing)
What it Does: .iloc is used to select data based on the integer position of rows and columns.

Key Features:

Uses integer-based positions for indexing.
Excludes the end of the range in slicing.
Does not rely on labels.
Grouping and aggregation: Analyse data by
grouping it based on specific features and
calculating aggregate statistics like sum, mean,
or count using methods like groupby()

# Group data by 'City' and calculate average
'Score' for each group
average_scores = df.groupby('City')
['Score'].mean()
print(average_scores)
