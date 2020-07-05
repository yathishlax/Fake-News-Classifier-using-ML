Fake News Classifier

The goal of this project is to analyse the various news articles and accurately detect if the news is genuine or not.
Fake news is a major concern in our society right now. It has gone hand-in-hand with the rise of the data-driven era – not a coincidence when you consider the sheer volume of data we are generating every second!
Fake news is such a widespread issue that even the world’s leading dictionaries are trying to combat it in their own way. Here are two leading lights in that space taking a stance in recent years:
•	Dictionary.com listed ‘misinformation’ as their Word of the Year in 2018
•	Oxford Dictionary picked ‘post-truth’ as their Word of the Year a few years ago
 
So what role has Machine Learning played in this? Machine learning Algorithms can be used to classify and predict if a news is fake after it has been trained or identified by using other techniques. Natural Language Processing (NLP) techniques are being used to analyse these fake articles and find a way to recognise the authenticity of the news being spread and broadcasted.
The dataset used is contains a set of news articles, they contain: the titles, author information, the textual content of the articles and finally a label that defines it as true or false.
The data was treated for missing values and explored before Natural Language Processing was used in cleaning the text of the articles and their titles. The Bag of Words model was applied using count vectorizer. Features with high frequency were considered and machine learning algorithms such as Multinomial Naïve Bayes, Passive Aggressive Classifier Algorithm and multinomial classifier with Hyperparameter were applied.

The best results were obtained using Passive Aggressive Classifier.
 
Results:
As can be seen from the image above:
•	3126 articles were correctly identified as Fake News, which means 92.24% of the Fake News Articles were correctly identified.
•	2419 articles were correctly identified as Real News, which means 91.42% of genuine articled were correctly identified.
•	The overall accuracy of prediction achieved in this model was 91.9%
Hence majority of the Fake News articled were correctly identified with a small margin for error. This can be utilized to successfully categorise and prevent the spread of misinformation in the form of fabricated Fake News.


