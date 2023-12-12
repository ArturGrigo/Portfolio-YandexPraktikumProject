# Прогноз оттока клиентов в телекомунникационной компании
## Описание проекта: телекоммуникации
Оператор связи «Ниединогоразрыва.ком» предоставляет два основных типа услуг:

Стационарную телефонную связь. 

Интернет. 

Также доступны такие услуги:
## Цель:
Нужно научиться прогнозировать отток клиентов. Если выяснится, что пользователь планирует уйти, ему будут предложены промокоды и специальные условия. Команда оператора собрала персональные данные о некоторых клиентах, информацию об их тарифах и договорах.
Эффективность работы модели будет оцениваться метрикой ROC-AUC. Модель должна показать на тестовой выборке уровень метрики ROC-AUC не менее 0.85

## Навыки и инструменты:
python

pandas

numpy

matplotlib

seaborn

sklearn.metrics.accuracy_score

sklearn.metrics.roc_auc_score
sklearn.metrics.roc_curve
sklearn.metrics.confusion_matrix
sklearn.metrics.ConfusionMatrixDisplay
sklearn.preprocessing.OneHotEncoder
sklearn.preprocessing.RobustScaler
sklearn.l_selection.train_test_split
sklearn.model_selection.GridSearchCV
sklearn.pipeline.make_pipeline
sklearn.ensemble.RandomForestClassifier
sklearn.linear_model.LogisticRegression
sklearn.dummy.DummyClassifier

catboost.CatBoostClassifier

lightgbm.LGBMClassifier

phik.phik_matrix

## Общий вывод:
В результате выполнения проекта сотрудникам оператора связи предлагается использовать разработанную в данном проекте модель на основе градиентного бустинга CatBoostClassifier с подобранными гиперпараметрами для прогнозирования оттока клиентов и, соответственно, оптимального применения промокодов и специальных условий для удержания клиентов.
