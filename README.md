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

`LinearRegression`

![LinearRegression](https://user-images.githubusercontent.com/94479037/172681299-1b3ad76e-3dc0-421d-8a98-65216ef807e5.png)

Лучшая модель по результату среднеквадратичной ошибки `RMSE`:

`LGBMRegressor`

![LGBMRegressor](https://user-images.githubusercontent.com/94479037/172681410-b0ef7f0a-afa2-4186-b84b-603ac9b78bd8.png)

