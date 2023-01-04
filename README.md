# EmailSpamDetector
This project was focused on running predictions whether an entry is spam or non-spam(ham) given the provided test dataset of SMS entries.
Natural Language Processing was used to remove any stop or unnessesary words. Additionally, each SMS entry was vectorized or converted into a matrix of numbers for the machine learning algorithm to work on.
Finally, the Naive Bayes classifier algorithm was used from the sklean library and was fitted on the vectorized model and ran its predictions. 
A classification report displayed the accuracy results as well as the f1-score.
