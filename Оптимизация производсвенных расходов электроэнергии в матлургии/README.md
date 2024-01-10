# Оптимизация производсвенных расходов электроэнергии в матлургии
[ipynb](https://github.com/SeleznevVA/Portfolio/blob/718c7caf7c659ccceb1a6b81872fe34076c297be/%D0%9E%D0%BF%D1%82%D0%B8%D0%BC%D0%B8%D0%B7%D0%B0%D1%86%D0%B8%D1%8F%20%D0%BF%D1%80%D0%BE%D0%B8%D0%B7%D0%B2%D0%BE%D0%B4%D1%81%D0%B2%D0%B5%D0%BD%D0%BD%D1%8B%D1%85%20%D1%80%D0%B0%D1%81%D1%85%D0%BE%D0%B4%D0%BE%D0%B2%20%D1%8D%D0%BB%D0%B5%D0%BA%D1%82%D1%80%D0%BE%D1%8D%D0%BD%D0%B5%D1%80%D0%B3%D0%B8%D0%B8%20%D0%B2%20%D0%BC%D0%B0%D1%82%D0%BB%D1%83%D1%80%D0%B3%D0%B8%D0%B8/%D0%9E%D0%BF%D1%82%D0%B8%D0%BC%D0%B8%D0%B7%D0%B0%D1%86%D0%B8%D1%8F%20%D0%BF%D1%80%D0%BE%D0%B8%D0%B7%D0%B2%D0%BE%D0%B4%D1%81%D0%B2%D0%B5%D0%BD%D0%BD%D1%8B%D1%85%20%D1%80%D0%B0%D1%81%D1%85%D0%BE%D0%B4%D0%BE%D0%B2%20%D1%8D%D0%BB%D0%B5%D0%BA%D1%82%D1%80%D0%BE%D1%8D%D0%BD%D0%B5%D1%80%D0%B3%D0%B8%D0%B8%20%D0%B2%20%D0%BC%D0%B0%D1%82%D0%BB%D1%83%D1%80%D0%B3%D0%B8%D0%B8.ipynb)
## Описание проекта

Построить модель для предсказания финальной температуры сплава. Модель должна учитывать все этапы технологического процесса. Предсказанная температура позволит снизить расходы электроэнергии во время всего процесса.


## Инструменты 
* pandas
* numpy
* matplotlib
* seaborn
* scipy.stats
* sklearn.model_selection (train_test_split, GridSearchCV, cross_val_score)
* sklearn.preprocessing (StandardScaler)
* sklearn.linear_model (LinearRegression)
* sklearn.ensemble (RandomForestRegressor)
* catboost (CatBoostRegressor)
* sklearn.metrics (mean_absolute_error) 
* shap 

## Общий вывод 
1. Данные подготолены, созданы новые признаки.
2. Построены и изучены модели на обучающей выборке.
3. Лучшая модель проверена на тестовой выборке и считается адекватной. 
