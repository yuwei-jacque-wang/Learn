# Resaurant Recommender system 
This project covers common strategies for building recommendation system. It contains several popular recommendation engines with different levels of complexities. Major contents are shown as follows:

### Popularity_Based_Recommender
General, non-personalized recommendation engine using only most popular items to give general recommendation. Built by Python pandas functions.
- dataframe.groupby(group_name)[agg_column].count()
 - Aggregate counts of agg_column for each group_name (=SQL Group By)
 
- dataframe.sort_values(column, ascending=True/False)
 - Sort values by ascending/descending order
 
- pandas.merge(dataframe1, dataframe2, on=column_name)
 - Merge two data frames on column_name (=SQL Join Table)
