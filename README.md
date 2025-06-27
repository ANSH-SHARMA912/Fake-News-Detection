This project focuses on detecting fake news articles using machine learning techniques. It utilizes a labeled dataset with the following features:
-  id : Unique identifier for each news article
-  title : The headline of the news article
-  author : The author of the news article
-  text : The main content of the article
-  label : Ground truth label — 0 for real news and 1 for fake news
Here we  preprocesses news article data by removing null values and combining relevant text fields. It applies NLP techniques like tokenization, cleaning, and vectorization using TfidfVectorizer. Machine learning models such as Logistic Regression and Naive Bayes are trained and evaluated using accuracy, confusion matrix, and classification report, with the dataset split into training and test sets.
It is capable of predicting the authenticity of news articles with high accuracy and generalization, making it potentially useful in combating the spread of misinformation.
main
