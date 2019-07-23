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
