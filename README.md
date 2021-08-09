# Spam-Classifier
About
This NLP project reads a message and classifies them as Spam or Ham (Not Spam). This uses NLTK for text preprocessing and Machine learning algorithms for classifying text messages.

Text pre-processing done by applying **Regex**, **Stemming** and Removing **Stopwords**. 
The words are then converted into words using **Bag Of Words** Technique (Sklearn's **CountVecrtorizer**) and then a **Naive Bayes Classifier** is built for the use-case.
