Grouping and aggregation: Analyse data by
grouping it based on specific features and
calculating aggregate statistics like sum, mean,
or count using methods like groupby()

# Group data by 'City' and calculate average
'Score' for each group
average_scores = df.groupby('City')
['Score'].mean()
print(average_scores)
