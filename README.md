# Assignment:

It can be useful to be able to classify new "test" documents using already classified "training" documents.  A common example is using a corpus of labeled spam and ham (non-spam) e-mails to predict whether or not a new document is spam.  Here is one example of such data:  UCI Machine Learning Repository: Spambase Data Set

For this project, you can either use the above dataset to predict the class of new documents (either withheld from the training dataset or from another source such as your own spam folder).

For more adventurous students, you are welcome (encouraged!) to come up a different set of documents (including scraped web pages!?) that have already been classified (e.g. tagged), then analyze these documents to predict how new documents should be classified.

# Our Project:

We will be using the dataset at the following link: https://www.kaggle.com/datasets/shivamkushwaha/bbc-full-text-document-classification?resource=download

The dataset is titled BBC Full Text Document Classification, and it contains full documents with their text of five categories, which are business, entertainment, politics, sport, and tech. The goal of our text classification is to predict which category the documents in the test set fit in.

The models we will use include the Naive Bayes Classifier, Support Vector Machines, and Random Forests. The results will be compared for accuracy.
