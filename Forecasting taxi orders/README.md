# Прогнозирование количества заказов такси

<a href = https://github.com/letoatreides2/Portfolio/blob/master/Forecasting%20taxi%20orders/Forecasting%20taxi%20orders.ipynb>ipynb</a>

## Описание проекта

Компания "Чётенькое такси" собрала исторические данные о заказах такси в аэропортах. Чтобы привлекать больше водителей в период пиковой нагрузки, нужно спрогнозировать количество заказов такси на следующий час.

## Навыки и инстурументы

* python
* pandas
* numpy
* statsmodels.tsa.seasonal.seasonal_decompose
* statsmodels.tsa.api.ExpotentialSmoothing
* sklearn.model_selection.TimeSeriesSplit
* sklearn.model_selection.train_test_split
* sklearn.preprocessing.StandardScaler
* sklearn.model_selection.GridSearchCV
* sklearn.linear_model.LinearRegression
* sklearn.ensemble.RandomForestRegressor
* sklearn.metrics.mean_squared_error
* catboost.CatBoostRegressor
* matplotlib
* seaborn

## Общий вывод

Были подготовлены и проведен исследовательский анализ исходных данных, представляющих собой временной ряд. Обучены четыре вида моделей: *линейная регрессия*, *случаный лес*, ансамбль *решающих дереьвев*, обученных методом *градиентного бустинга*, и *модель Хольта-Винтерса*. Выбрана и протестирована лучшая среди них.
