# Исследование технологического процесса очистки золота
[ipynb](https://github.com/SeleznevVA/Portfolio/blob/33150094d2f98d6f8cf7689e337f3464942a7812/%D0%98%D1%81%D1%81%D0%BB%D0%B5%D0%B4%D0%BE%D0%B2%D0%B0%D0%BD%D0%B8%D0%B5%20%D1%82%D0%B5%D1%85%D0%BD%D0%BE%D0%BB%D0%BE%D0%B3%D0%B8%D1%87%D0%B5%D1%81%D0%BA%D0%BE%D0%B3%D0%BE%20%D0%BF%D1%80%D0%BE%D1%86%D0%B5%D1%81%D1%81%D0%B0%20%D0%BE%D1%87%D0%B8%D1%81%D1%82%D0%BA%D0%B8%20%D0%B7%D0%BE%D0%BB%D0%BE%D1%82%D0%B0/%D0%98%D1%81%D1%81%D0%BB%D0%B5%D0%B4%D0%BE%D0%B2%D0%B0%D0%BD%D0%B8%D0%B5%20%D1%82%D0%B5%D1%85%D0%BD%D0%BE%D0%BB%D0%BE%D0%B3%D0%B8%D1%87%D0%B5%D1%81%D0%BA%D0%BE%D0%B3%D0%BE%20%D0%BF%D1%80%D0%BE%D1%86%D0%B5%D1%81%D1%81%D0%B0%20%D0%BE%D1%87%D0%B8%D1%81%D1%82%D0%BA%D0%B8%20%D0%B7%D0%BE%D0%BB%D0%BE%D1%82%D0%B0.ipynb)
## Описание проекта

Построить модель машинного обучения для предсказания коэффициента восстановления золота из золотосодержащей руды на основе данных с параметрами добычи и очистки. Модель поможет оптимизировать производство, чтобы не запускать предприятие с убыточными характеристиками.

## Инструменты 
* pandas
* matplotlib
* numpy
* seaborn
* sklearn.linear_model (LinearRegression, Lasso)
* sklearn.tree (DecisionTreeRegressor)
* sklearn.ensemble (RandomForestRegressor)
* sklearn.dummy (DummyRegressor)
* sklearn.model_selection (train_test_split, cross_validate, cross_val_score, RandomizedSearchCV)
* sklearn.preprocessing (StandardScaler)
* sklearn.metrics (make_scorer)

## Общий вывод 
1. Проведено обучение моделей.
2. Обученные модели были проверены на тестовой выборке.
3. Выбрана одна модель для внедрения.
