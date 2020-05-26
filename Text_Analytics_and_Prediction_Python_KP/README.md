# Text Analytics and Prediction with Python
Usage of packages for simple tasks of text analytics and prediction

### Word Cloud (wordcloud package)
1. Read entire text file as one long string
2. Generate default stopword set from WordCloud function
3. Generate wordcloud data
4. Display wordcloud with matplotlib.pyplot
5. Update stopwords list, for better wordcloud

### Sentiment Analysis (textblob package)
1. Read text file in lines (list of strings)
2. Generate sentiment instance from fitting in TextBlob function
3. Call functions of polarity and subjectivity
4. Summarize sentiment in pie chart 

### Clustering Text (TfidfVectorizer, KMeans)
1. TF-IDF vectorization
2. Clustering data with KMeans
3. Elbow curve for detecting optimal cluster size

### Classification (NLTK preprocessing, TfidfVectorizer, LabelEncoder, MultinomialNB)
1. Read text file and split into lines
2. Preprocessing with NLTK stopwords and wordnet lemmatizer
3. TF-IDF with customized tokenizer
4. Transform labels to int classes with label encoder
5. 3-classes classification with Naive Bayes
6. Confusion metrics from sklearn.metrics