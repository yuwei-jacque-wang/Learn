# Baby Names with Pandas
A good exercise as introduction to Pandas, including essential data cleaning procedure and EDA (Exploritary Data Analysis).

### Import data into desirable data frame
Uncompress a zip archive, list contents of a directory, load CSV into Pandas, concatenate DataFrames

- zipfile.ZipFile().extractall()
  - Extract zip file directly 
  
- pandas.read_csv(filename, names=[])
  - Read csv file, assign column names
  
- dataframe1.append(dataframe2)
  - Append dataframe2 into dataframe1, output dataframe1 as one dataframe
  
- pandas.concat(list_of_df)
  - Concat a list of dataframes into one, with columns joined together

### Name popularity
Set and sort indexes, select rows by index value, make a stacked line plot in matplotlib

- dataframe.set_index([index1, index2])
  - Set each indexes in [] as index (row) for dataframe
  
- dataframe.loc[]
  - Look for certain observations (rows), could be more than one indexes in [] if dataframe is multi-indexed
  
- dataframe.loc[index].unstack(level=1/0)
  - Unstack certain index (in []), level=0 or 1 is just shifting row and column
  
- pyplot.stackplot()
  - Plot a stackplot, values might need to be transposed (add ".T") 
  - stackplot doesn't automatically give legend, need to set legend manually
  
### Yearly Top 10
Sort dataframe by column, drop column, join table by index, count values in a series

- dataframe.reset_index()
  - Reset index column, to make multi indexes "same level"
  
- dataframe.drop([column1, column2], axis=1)
  - Drop columns (may need to reset index first)
  
- dataframe.join(dataframe2, dataframe3)
  - Join dataframes together into one by same index

- def topten_comparison(gender, year0, year1)
  - Function for creating (joining) top 10 names of given gender from year0 to year1 
  
