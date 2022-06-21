# Подбор тарифа исходя из активности пользователя (продолжение предыдущего проекта о тарифах)"

Требуется определить наиболее перспективный тариф из двух имеющихся.

## Имеющиеся данные:

- сalls — количество звонков,
- minutes — суммарная длительность звонков в минутах;
- messages — количество sms-сообщений;
- mb_used — израсходованный интернет-трафик в Мб;
- is_ultra — каким тарифом пользовался в течение месяца («Ультра» — 1, «Смарт» — 0).

## Библиотеки, использовавшиеся в процессе выполнения проекта

- pandas
- numpy
- sklearn (linear_model.LogisticRegression, model_selection.train_test_split, ensemble.RandomForestClassifier, tree.DecisionTreeClassifier, metrics.accuracy_score, model_selection.cross_validate, neighbors.KNeighborsClassifier, model_selection.cross_val_score, dummy.DummyClassifier) 
- plotly