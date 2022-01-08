**DESCRIPTION:**

Using NLP and machine learning, making a model to identify toxic comments from
the Talk edit pages on Wikipedia. Help identify the words that make a comment
toxic.

**Problem Statement:**

Wikipedia is the world’s largest and most popular reference work on the internet
with about 500 million unique visitors per month. It also has millions of
contributors who can make edits to pages. The Talk edit pages, the key community
interaction forum where the contributing community interacts or discusses or
debates about the changes pertaining to a particular topic.

Wikipedia continuously strives to help online discussion become more productive
and respectful. Building a predictive model that identifies toxic comments in
the discussion and marks them for cleanup by using NLP and machine learning.

**Analysis done:**

Built a text classification model using NLP and machine learning that detects
toxic comments.

**Content:**

\- id :Identifier number of the comment

\- comment_text:The text in the comment

\- toxic :0 (non-toxic) /1 (toxic)

**Tasks performed:**

1\. Get the comments into a list, for easy text cleanup and manipulation

2\. Cleanup:

\- Using regular expressions, remove IP addresses & URLs

\- Normalized the casing

\- Tokenized the comments using word_tokenize from NLTK

\- Removed stop words & punctuation marks

\- Defined a function to perform all these steps

3\. Used a counter to find the top terms in the data.

4\. Removed the contextual stop words like “Wikipedia”, “page”, “edit”.

5\. Separated data into train and test sets

6\. Used TF-IDF to get data into a vector space model

7\. Built the model using Support Vector Machine

8\. Model evaluation: Accuracy, recall, and f1_score

9\. Adjusted the appropriate parameter in the SVC module, as the model seems to
focus on the 0s because of class imbalance

10\. Evaluated the predictions on the test set: accuracy, recall, f1_score

11\. Hyperparameter tuning

\-Using GridSearch and StratifiedKFold (because of class imbalance)

\-Provided the parameter grid to choose for ‘C’

\-Finding the parameters with the best recall in cross validation

\-Choosing ‘recall’ as the metric for scoring

\-Choosing stratified 5 fold cross validation scheme

12\. Predicted and evaluated using the best estimator

13\. Reported the most prominent terms in the toxic comments & separated the
comments from the test set that the model identified as toxic to make one large
list of the terms to get the top 15 terms
