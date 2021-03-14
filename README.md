# Introduction
This is a system that automatically grades essays built using Machine Learning (ML), Deep Learning (DL), Natural Language Processing (NLP) techniques with the help of many libraries and tools e.g. scikit-learn, Keras, Seaborn, Gensim, NLTK, Ploty, Numpy, Pandas.

For more details refer to `unpublished-conference-paper.pdf`, please.

# Abstract
Abstract- The task of human-based grading essays has been big
trouble due to the long time it needs, subjectiveness in its nature,
difficulty it involves, and focus it requires to minimize the
possibility of errors as much as possible. As well as, the
requirement of numerous teachers as in most of the situations, a
single essay is being graded at least twice by distinct people.
These reasons push us toward investigating and exploring more
in this scope. We make use of the essays dataset obtained from
Kaggle.com. These essays are divided into 8 sets based on
context and grade of students arranging from 7 to 10. We first,
clean the data and preprocess it using NLP techniques then, we
convert the textual data into numeric by using the
word-embedding approach. After that, we feed those input
vectors into regression-based models to predict the grades. In the
training and testing phases, we use the KFold methodology.
Lastly, we evaluate the performance of the used models using
many measurement matrices depending on the model. In the case
of LSTM, we use Quadratic Weighted Kappa QWK to figure out
the agreement between predicted and original grade.
