# Baby Names with Pandas
A good exercise as introduction to Pandas, including essential data cleaning procedure and EDA (Exploritary Data Analysis).

### Import data into desirable data frame
- zipfile.ZipFile().extractall()
  - Extract zip file directly 
  
- pandas.read_csv(filename, names=[])
  - Read csv file, assign column names
  
- dataframe1.append(dataframe2)
  - Append dataframe2 into dataframe1, output dataframe1 as one dataframe
  
- pandas.concat(list_of_df)
  - Concat a list of dataframes into one, with columns joined together
