https://www.kaggle.com/competitions/llm-detect-ai-generated-text/overview
В этом соревновании нам нужно было решить задачу бинарной классификации, распознать текст, написанный с помощью LLM. Для решений этой задачи использовались DistilBertForSequenceClassification с Hugging Face (не успел обучить DeBERTa), а так же Voting Classifier (sgd, MultinomialNB, lgbm, catboost) из топовых публичных ноутбуков с поменянными весами.

Так же в этом соревновании не давали данные для обучения, поэтому я взял датасеты, которые составили другие участники: https://www.kaggle.com/datasets/thedrcat/daigt-v2-train-dataset и https://www.kaggle.com/datasets/thedrcat/daigt-proper-train-dataset.

Как итог, я не выбрал решение со скором 0.907 (серебро начиналось с 0.904) и не получил медальки вовсе :(
