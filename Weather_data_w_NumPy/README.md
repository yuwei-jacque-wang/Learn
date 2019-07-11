# Weather data with NumPy

A good exercise for loading data from txt file into NumPy array, including common data cleaning parts. The highlights for this project include: 

### Download data from URL link directly
  - urllib.request.urlretrieve()
    - grab data from given url
    
  - open('doc_name', 'r').readlines()[:n]
    - Read first n lines in file 'doc_name'
    
### Select observations with conditions
  - def findstation(s)
    - Search name of a station in datafile and return data
  
### Load data (and parse) from txt into NumPy array
  - def parsefile(filename) + np.genfromtxt()
    - Parse datafile from txt to load into NumPy array
    
  - def unroll()
    - Format NumPy array
    
  - def getobs() + np.concatenate()
    - concatenate values to generate a time series 

### Replace missing data with interpolation
  - def getobs()[improved] + np.nan
    - Replace missing data with "not a number"
    
  - def fillnans(data) + np.interp()
    - Replace nan value with interpolation value
    
### Smoothing data for local average 
  - def plot_smoothed() + np.correlate()
    - Smooth data by taking average of a certain window length
    
  - pyplot.subplot, title, axis, figure
    - Common plotting function in pyplot for visualization
