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



# Dúvidas
Realizar normalização para todos os dados ou apenas os numéricos?

Referência sobre melhores indicações de cada método
 
Referências para escolher hyperparâmetros mais significativos que podem ser exercitados
 
Referências sobre métricas e, principalmente, se os valores estão aceitáveis
Qual a mais significativa para o estudo de caso?

Como fazer a análise de custo (basta realizar o produto escalar das matrizes)?




https://towardsdatascience.com/metrics-to-evaluate-your-machine-learning-algorithm-f10ba6e38234
https://neptune.ai/blog/performance-metrics-in-machine-learning-complete-guide
https://www.kdnuggets.com/2019/10/5-classification-evaluation-metrics-every-data-scientist-must-know.html
https://www.altexsoft.com/blog/machine-learning-metrics/
https://medium.com/analytics-vidhya/model-evaluation-metrics-in-machine-learning-928999fb79b2



