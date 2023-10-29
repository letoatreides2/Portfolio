# Предсказание температуры расплавленной стали

<a href="https://github.com/letoatreides2/Portfolio/blob/main/Prediction%20of%20molten%20steel%20temperature/Prediction%20of%20molten%20steel%20temperature.ipynb">ipynb</a>

## Описание проекта

Чтобы оптимизировать производственные расходы, металлургический комбинат ООО «Так закаляем сталь» решил уменьшить потребление электроэнергии на этапе обработки стали. Задача проекта заключается в построении модели, которая по исходным данным будет предсказывать конечную температуру расплавленной стали.

## Навыки и инстурменты

* python
* pandas
* numpy
* sklearn.model_selection.train_test_split
* sklearn.preprocessing.StandardScaler
* sklearn.model_selection.GridSearchCV
* sklearn.linear_model.Ridge
* sklearn.ensemble.RandomForestRegressor
* sklearn.metrics.mean_absolute_error
* catbooost.CatBoostRegressor
* matplotlib
* seaborn
* shap

## Общий вывод

Были подготовлены и проведен исследовательский анализ исходных данных. Проведена проверка признаков на коллинеарность. Обучены 3 вида моделей: *гребневая регрессия*, *случайный лес*, ансамбль *решающих деревьев*, обученных методом *градиентного бустинга*. Рассмотрены зависимости *целевой метрики* от различных *гиперпараметров*. Выбрана и протестирована лучшая модель. Выделены 10 наиболее значимых признаков.
