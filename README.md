# Text-Classification
The full description, experiments and results are available in the [report](https://github.com/asavva3/Text-Classification/blob/main/Text_Mining_Assignment_1.pdf).
## Introduction
In this assignment, we were asked to follow the
[tutorial](https://scikit-learn.org/stable/tutorial/text_analytics/working_with_text_data.html) from scikit-learn about working with text
data. In the tutorial, a subset of the dataset [Twenty
Newsgroups](http://qwone.com/~jason/20Newsgroups/) is used and the procedure of extract-
ing features, training and optimizing a classifier is
explained. In our assignment, we used the entire
dataset to compare three classifiers with three types
of features: word counts, term frequencies and term-
frequency-inverse-document-frequency. We com-
pared the Naive Bayes classifier, SGDC and K-NN.
Furthermore, we had to test different parameters
affecting the vectorizer.

## Conclusion
We experimented with three different classifiers and
three different types of features and as expected TF-
IDF is the best of three. K-NN performs poorly
for this type of classification probably due to the
"curse of dimensionality". Naive Bayes has very
good results but SGDC gives the best results. Hy-
perparameter optimization makes a big difference
for the classifiers. Laslty, limiting the available fea-
tures gives worse results as expected.

## Collaborators
* [Ivan Horokhovskyi](https://github.com/doctorblinch)
* [Andreas Savva](https://github.com/asavva3)