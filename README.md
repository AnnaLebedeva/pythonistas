# Задача классификации отзывов о банках по принципу этичности

Центральному банку и другим организациям необходимо оценивать качество работы коммерческих банков. Одним из критериев хорошей работы является параметр этичности, который включает в себя оценки добросовестности, ответственности и т.д., то есть то, насколько банк соблюдает нормы во взаимоотношениях с клиентами и партнерами. Датасет состоит из примерно 20 тыс. размеченных отзывов, в которых аннотаторы определяли этичность банка:
"+" - этично
"-" - неэтично
"?" - невозможно однозначно определить
Банки оценивались с точки зрения качества, коммуникации, работы с персональными данными.
Также отзывы были разделены разметчиками по категориям.
# Задачи хакатона:
+ обучить модель на задачу классификации по принципу этичности (multiclass)
+ обучить модель на задачу присваивания 1 или 2 категорий (multilabel)
# Классификация этичности:
Мы попробовали несколько моделей и сравнили их метрики.

[Random Forest]

[Catboost]

[RuBERT fine-tuning] Модель можно скачать по [ссылке](https://disk.yandex.ru/d/FuF3wHpkyTxcJg)

# Присваивание категорий:
Для этой задачи мы обучили [RandomForestClassifier] (TfIdf в качестве векторайзера).
Модель можно скачать по [ссылке](https://disk.yandex.ru/d/80Q9qc8c7efGyg).


[Random Forest]: <https://github.com/AnnaLebedeva/badass/blob/main/RF_classifier_sentiment.ipynb>
[Catboost]: <https://github.com/AnnaLebedeva/pythonistas/blob/master/eda%2Bcatboost.ipynb>
[RuBERT fine-tuning]: <https://github.com/AnnaLebedeva/pythonistas/blob/master/fine-tuning.ipynb>
[RandomForestClassifier]: <https://github.com/AnnaLebedeva/pythonistas/blob/master/categories_prediction.ipynb>
