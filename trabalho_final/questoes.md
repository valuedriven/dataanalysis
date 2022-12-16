# Questões diversas

Hyperparameters:

RandonForest: max_depth in Random Forest Algorithms, k in KNN Classifier.
MLP: number of nodes in layers, The learning rate, Dropout rate, Batch size, Epochs to train for


Analisar parâmetro cv do GridSearchCV

Métricas:
f1: 2 * (precision * recall) / (precision + recall)

precision: tp / (tp + fp)

recall: tp / (tp + fn)

https://scikit-learn.org/stable/modules/model_evaluation.html#classification-metrics

https://scikit-learn.org/stable/modules/model_evaluation.html

https://scikit-learn.org/stable/modules/generated/sklearn.metrics.classification_report.html

Subplots

Usar OrdinalEncoder e OneHotEncoder

Analisar: https://github.com/chongjason914/scikit-learn-tutorial/blob/main/feature-encoding.ipynb

Tunning de rede neural
https://scikit-learn.org/stable/modules/generated/sklearn.neural_network.MLPClassifier.html


8.  Cost Matrix
This dataset requires use of a cost matrix (see below)
      1        2
----------------------------
  1   0        1
-----------------------
  2   5        0
(1 = Good,  2 = Bad)

the rows represent the actual classification and the columns
the predicted classification.
It is worse to class a customer as good when they are bad (5), 
than it is to class a customer as bad when they are good (1).
