# Resaurant Recommender system 
This project covers common strategies for building recommendation system. It contains several popular recommendation engines with different levels of complexities. Major contents are shown as follows:

### Popularity_Based_Recommender
  General, non-personalized recommendation engine using only most popular items to give general recommendation. Built by Python pandas functions.
- dataframe.groupby(group_name)[agg_column].count()
  - Aggregate counts of agg_column for each group_name (=SQL Group By)
  - Instead of .count() also works for other functions like .mean()
 
- dataframe.sort_values(column, ascending=True/False)
  - Sort values by ascending/descending order
 
- pandas.merge(dataframe1, dataframe2, on=column_name)
  - Merge two data frames on column_name (=SQL Join Table)
  
### Correlation_Based_Recommender
  Based on Pearson's r correlation to recommend an item similar to items a user has chosen (item-based similarity). Built by Python pandas functions.
- dataframe.pivot_table(data=,index=,values=,columns=)
  - Create pivot table for variable "index". data is dataframe used, index is one variable determining the rows, columns are variables chosen for each columns, values are what's presented as major contents.
