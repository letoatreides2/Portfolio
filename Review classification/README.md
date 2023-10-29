# Классификация отзывов пользователей по токсичности

<a href="https://github.com/letoatreides2/Portfolio/blob/main/Review%20classification/Review%20classification.ipynb">ipynb</a>

## Описание проекта

Интернет-магазин «Викишоп» запускает новый сервис. Теперь пользователи могут редактировать и дополнять описания товаров, как в вики-сообществах. Магазину нужен инструмент, который будет искать токсичные комментарии и отправлять их на модерацию.

## Навыки и инстурменты

* python
* pandas
* numpy
* spacy
* nltk
* sklearn.model_selection.train_test_split
* sklearn.pipeline.make_pipeline
* sklearn.feature_extraction.ext import TfidfVectorizer
* sklearn.model_selection.GridSearchCV
* sklearn.linear_model.LogisticRegression
* sklearn.svm.LinearSVC
* sklearn.metrics.f1_score
* sklearn.metrics.confusion_matrix
* catbooost.CatBoost.Classifier
* matplotlib
* seaborn

## Общий вывод

Были подготовлены и рассмотрены исходные данные, представляющие собой набор комментариев с оценкой об их токсичности. Проведена лемматизация и векторизация текстов комментариев с помощью величины *TF-IDF*. Обучены три вида моделей: *линейная регрессия*, *случайный лес*, ансамбль *решающих дереьвев*, обученных методом *градиентного бустинга*. Выбрана и протестирована лучшая среди них.
