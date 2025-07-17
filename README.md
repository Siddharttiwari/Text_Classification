# Text_Classification
 Text Classification using Multinomial Naive Bayes (Built-in vs Manual)
This project demonstrates a Text Classification system implemented using two approaches:

Built-in MultinomialNB from scikit-learn

Manual implementation of the Naive Bayes algorithm

Both approaches were tested on the same dataset and preprocessing pipeline, achieving the same accuracy of 0.784. This validates the correctness of the manual model.

🔍 Objective
To classify text documents into categories using Naive Bayes, and compare:

The performance of built-in MultinomialNB from scikit-learn

A custom, manual implementation of Naive Bayes from scratch

📁 Dataset
Dataset: 20 Newsgroups (available via sklearn.datasets)

Task: Classify documents into one of several newsgroup topics

🧹 Preprocessing Steps
Lowercasing

Tokenization

Stopword removal

Filtering non-alphabetic tokens

Train-test split with stratification

⚙️ Feature Engineering
Created a vocabulary from training data

Represented documents using bag-of-words frequency vectors (manually)

Avoided using built-in vectorizers (like TfidfVectorizer or CountVectorizer)

📦 Models Implemented
✅ Built-in Approach
MultinomialNB from sklearn.naive_bayes

⚙️ Manual Naive Bayes
Computed:

Class priors

Likelihoods with Laplace smoothing

Used logarithmic probabilities for numerical stability

Predicted class with highest posterior probability

📈 Evaluation
Metric: Accuracy

Both models achieved the same accuracy of 0.784 on the test data

Confusion matrix and classification report used for further analysis

📌 Conclusion
Both built-in and manual Naive Bayes classifiers gave the same accuracy (0.784), validating the correctness of the manual implementation and the preprocessing pipeline.
