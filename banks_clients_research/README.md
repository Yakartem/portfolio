# Проект "Исследование оттока клиентов банка"

В данном проекте были даны данные о клиентах банка, а так же нас поставили перед фактом, что идет отток клиентов. Целью исследования было найти закономерность между оттоком клиентов и данными о них.

## Имеющиеся данные:

- RowNumber — индекс строки в данных
- CustomerId — уникальный идентификатор клиента
- Surname — фамилия
- CreditScore — кредитный рейтинг
- Geography — страна проживания
- Gender — пол
- Age — возраст
- Tenure — сколько лет человек является клиентом банка
- Balance — баланс на счёте
- NumOfProducts — количество продуктов банка, используемых клиентом
- HasCrCard — наличие кредитной карты
- IsActiveMember — активность клиента
- EstimatedSalary — предполагаемая зарплата

## Библиотеки, использовавшиеся в процессе выполнения проекта

- pandas
- sklearn (model_selection.train_test_split, linear_model.LogisticRegression, metrics.roc_auc_score, metrics.f1_score, metrics.confusion_matrix, preprocessing.StandardScaler, tree.DecisionTreeClassifier, ensemble.RandomForestClassifier, model_selection.GridSearchCV, metrics.roc_curve, metrics.f1_score, model_selection.StratifiedKFold, model_selection.RandomizedSearchCV)
- plotly
- matplotlib
- lightgbm
