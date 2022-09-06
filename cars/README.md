# Проект "Определение стоимости автомобилей"

Имеются данные о проданных на площадке автомобилях. Цель - построить модель градиентного бустинга для предсказания цены автомобиля, а также сравнить её с другими, более простыми моделями.

## Имеющиеся данные:

- DateCrawled — дата скачивания анкеты из базы
- VehicleType — тип автомобильного кузова
- RegistrationYear — год регистрации автомобиля
- Gearbox — тип коробки передач
- Power — мощность (л. с.)
- Model — модель автомобиля
- Kilometer — пробег (км)
- RegistrationMonth — месяц регистрации автомобиля
- FuelType — тип топлива
- Brand — марка автомобиля
- NotRepaired — была машина в ремонте или нет
- DateCreated — дата создания анкеты
- NumberOfPictures — количество фотографий автомобиля
- PostalCode — почтовый индекс владельца анкеты (пользователя)
- LastSeen — дата последней активности пользователя
- Price — цена (целевой признак)

## Библиотеки, использовавшиеся в процессе выполнения проекта

- pandas
- numpy
- sklearn (model_selection.train_test_split, preprocessing.StandardScaler, linear_model.LinearRegression, tree.DecisionTreeRegressor, ensemble.RandomForestRegressor, neighbors.KNeighborsRegressor, model_selection.GridSearchCV)
- seaborn
- matplotlib
- lightgbm
- catboost
- plotly
