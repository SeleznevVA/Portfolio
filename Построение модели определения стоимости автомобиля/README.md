# Построение модели определения стоимости автомобиля
[ipynb](https://github.com/SeleznevVA/Portfolio/blob/2bcc0a4aaf070ff9f7f94e43d6a4e137de8bfd63/%D0%9F%D0%BE%D1%81%D1%82%D1%80%D0%BE%D0%B5%D0%BD%D0%B8%D0%B5%20%D0%BC%D0%BE%D0%B4%D0%B5%D0%BB%D0%B8%20%D0%BE%D0%BF%D1%80%D0%B5%D0%B4%D0%B5%D0%BB%D0%B5%D0%BD%D0%B8%D1%8F%20%D1%81%D1%82%D0%BE%D0%B8%D0%BC%D0%BE%D1%81%D1%82%D0%B8%20%D0%B0%D0%B2%D1%82%D0%BE%D0%BC%D0%BE%D0%B1%D0%B8%D0%BB%D1%8F/%D0%9F%D0%BE%D1%81%D1%82%D1%80%D0%BE%D0%B5%D0%BD%D0%B8%D0%B5%20%D0%BC%D0%BE%D0%B4%D0%B5%D0%BB%D0%B8%20%D0%BE%D0%BF%D1%80%D0%B5%D0%B4%D0%B5%D0%BB%D0%B5%D0%BD%D0%B8%D1%8F%20%D1%81%D1%82%D0%BE%D0%B8%D0%BC%D0%BE%D1%81%D1%82%D0%B8%20%D0%B0%D0%B2%D1%82%D0%BE%D0%BC%D0%BE%D0%B1%D0%B8%D0%BB%D1%8F.ipynb)
## Описание проекта

На основе исторических данных необходимо построить модель для определения стоимости автомобиля. Модель позволит узнать рыночную стоимость автомобиля по имеющимся данным. Модель оценивается по показателям RMSE и времени предсказания.

## Инструменты 
* pandas 
* numpy
* matplotlib
* seaborn
* sklearn.metrics (mean_squared_error, make_scorer)
* sklearn.linear_model (LinearRegression)
* sklearn.ensemble (RandomForestRegressor)
* sklearn.model_selection (train_test_split, cross_val_score, GridSearchCV)
* sklearn.preprocessing (StandardScaler, OneHotEncoder, OrdinalEncoder)
* sklearn.model_selection (RandomizedSearchCV)
* lightgbm (LGBMRegressor)
* catboost (CatBoostRegressor, Pool, cv)

## Общий вывод 
1. Данные подготолены, созданы новые признаки.
2. Построены и изучены модели на обучающей выборке.
3. Лучшая модель проверена на тестовой выборке и считается адекватной.
4. Модель отвечает поставленным требования по показателю RMSE, а так же имеет самое быстрое, среди остальных моделей, время предсказания.
