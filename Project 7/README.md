# Отток клиентов банка
## Цель проекта:
построить модель прогнозирования, позволяющую предсказывать уход клиентов из банка на основании имеющихся исторических данных о поведении клиентов и расторжении договоров с банком.
Для этого будет построена модель с предельно большим значением F1-меры.
Целевой показатель F1-меры - не менее 0.59.
F1-мера будет проверяться на тестовой выборке, подготовленной в рамках проекта.

## Навыки и инструменты:
python,
pandas,
sklearn.metrics.accuracy_score,
sklearn.metrics.f1_score,
sklearn.metrics.roc_auc_score,
sklearn.tree.DecisionTreeClassifier,
sklearn.ensemble.RandomForestClassifier,
sklearn.linear_model.LogisticRegression,
sklearn.dummy.DummyClassifier,
sklearn.utils.shuffle,
sklearn.preprocessing.StandardScaler,
sklearn.preprocessing.OneHotEncoder

## Общий вывод: 
Построенную в рамках данного проекта систему анализа поведения клиентов можно применять для выявления целевой группы клиентской базы с наибольшей вероятностью ухода, что может помочь выработке специального комплекса мер по их удержанию.
