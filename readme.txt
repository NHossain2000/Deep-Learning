===================
Project description
===================

Twitter Sentimental Analysis Using NLP and Python
-------------------------------------------------

Scenario:
---------
By analyzing text data, we can find meaningful insights from non-numeric data that can help usachieve our objective.With the help ofNLP and its concepts,we can do it.Twitterisone of the biggest platformsthatpeopleuse to write their messages, express their feelingsabouta particular topic,and share knowledgein the form oftext. By analyzingtext data,we can make good decisionsfor different use cases likejudging the sentiment of the human tweets, and anyproduct review/comments can tell us the performance of a product in the market.NLP allowsus to study and understandthe colinearity of the data.Sowecanpredict our objective. 

Objective:
----------
 Use Python libraries such as Pandasfor data operations, Seabornand Matplotlibfor data visualization and EDA tasks,NLTKtoextract and analyze the information,Sklearnfor model building and performance visualization, to predict our different categories of people’s mindsets.

The following tasks are to be performed:

•Read the Data from the Given excel file.
•Change our dependent variable to categorical. (0 to “Neutral,”-1 to “Negative”, 1 to “Positive”)
•Do Missing value analysisand drop all null/missing values
•Do text cleaning. (remove every symbol except alphanumeric, transform all words to lower case, and remove punctuationand stopwords )
•Create a new column and find the length of each sentence (how many words they contain)
•Split data into dependent(X) and independent(y) dataframe
•Do operationson text data 
	o Do one-hot encoding for each sentence(use TensorFlow)
	o Add padding from the front side (use Tensorflow)
	o Build an LSTM model and compile it(describe features, input length, vocabulary size, information drop-out layer, activation function for output, )
	o Do dummy variable creation for the dependent variable
	o split the data into tests and train 
•Train new model
•Normalize the prediction as same as the originaldata(prediction might be in decimal, so whoever is nearest to 1 is predicted as yes and set other as 0)
•Measure performance metricsand accuracy
•print Classification report
