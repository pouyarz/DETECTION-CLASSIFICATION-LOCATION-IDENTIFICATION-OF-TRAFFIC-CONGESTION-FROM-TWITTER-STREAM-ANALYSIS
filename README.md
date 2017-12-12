# DETECTION CLASSIFICATION AND LOCATION IDENTIFICATION Of TRAFFIC CONGESTION FROM TWITTER STREAM ANAlYSIS

Twitter’s Streaming API is used for collecting the data in real-time. There are two unique ways to fetch tweets. In the first method, a rectangular bounding box with south-west latitude-longitude coordinates and north-east latitude-longitude coordinates is given. A traffic keywords dictionary is created and given. Applications on Twitter were created for streaming the public tweets. The application requires authorization keys (OAuth Keys) and tokens which once allocated by Twitter, could be used for creating the application. There are some robust Python libraries for streaming Twitter data. Tweepy is used for streaming the data. Typically, the data from the web is provided in XML or JSON formats. The format of the data being retrieved is JSON.
Most of the data is textual. A collection of raw text is converted into a matrix of token counts. The execution delivers a sparse, which is the counts of words by using matrix. In fact, in the raw text, it could not be possible to represent a sequence of symbols into algorithms which are expected numerical feature vectors with a fixed size. Therefore, after tweets are collected, the first module is preprocessing and cleaning texts such as converting to lower case, removing emoji, removing punctuation, converting to UTF-8 format, etc. Then they are needed to convert to numerical features. Several different types of features are extracted from the data. 
In the proposed system, Redis is used as a database. Redis is really fast and a key-value in-memory data store typically used for caches and other such mechanisms. During fetching stream data, like Memcached, everything is held in memory. In Addition, Python is used for most tasks such as data streaming, data extraction, data cleaning, feature extraction, model generation, experimental and statistical analysis, etc.
For all tasks in feature extraction in this study, Python libraries are used. For extracting the features using natural language processing technique such as removing stop words (“an”, “are”, “the” etc.), tokenization, N-gram, etc.  Natural Language Toolkit (NLTK). Moreover, to get the term frequency inverse document frequency (Tf-Idf) vectorizer feature Natural Language Toolkit (NLTK) is used. For statistical analysis, Scipy is used. Moreover, one of the most prominent libraries, called Numpy for numerical linear algebra is used.
The Python libraries used for feature importance are obtained from Scikit-Learn. Scikit-Learn is a robust machine learning libraries used in this study. Scikit-learn libraries are used to implement classification. Various statistics primarily precision, recall, and accuracy are calculated for testing model performance.
