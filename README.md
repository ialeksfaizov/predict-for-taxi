# Прогноз заказов такси

## Описание проекта
Условная компания агрегатор такси собрала исторические данные о заказах в аэропортах. Чтобы привлекать больше водителей в период пиковой нагрузки, необходимо спрогнозировать количество заказов такси на следующий час.


## Stack
- Pandas
- Numpy
- Seaborn
- Statsmodels
- Scikit-learn 
- LGBMRegressor
- CatBoostRegressor
- XGBRegressor


## Вывод

Обучены модели:
- `RandomForestRegressor`;
- `DecisionTreeRegressor`;
- `LinearRegression`;
- `CatBoostRegressor`;
- `LGBMRegressor`;
- `XGBRegressor`.

Лучшая модель по результату скорости обучения и предсказания:
- `LinearRegression`.

Лучшая модель по результату среднеквадратичной ошибки `RMSE`:
- `LGBMRegressor`.
