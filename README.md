# Codesoft-Spam-Ham-classification

In the spam email dataset, this Python code snippet is performing text classification using support VectorSVM. It starts by loading the dataset and performing basic data cleansing tasks, such as removing unnecessary columns and removing outliers based on the length of the text.

Remove stopwords, tokenizations andlemmatizing of words to prepress text data. After preprocessing, the text features are transformed into TF-IDF vectors using the TfidfVectorizer from scikit-learn. The target variable is encoded with the label encoding.

The dataset is split into training and testing sets, and a linear SVM model is trained on the training data. Classification metrics such as accuracy, precision, recall, F1 score and area under the ROC curveAUC are used to assess model accuracy in testing data.

In order to assess the SVM model's ability to classify reports of unspam email and emails, a classification table as well as ROC curve are shown. The model has an accuracy of about 98.29% for both classes, with a good precision and recall value.
