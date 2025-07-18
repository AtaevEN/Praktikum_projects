# Прогноз температуры сплава для металлургического комбината «Стальная птица»

### [Вернуться обратно к проектам](https://github.com/AtaevEN/Praktikum_projects/tree/main)

## Описание проекта

Металлургический комбинат «Стальная птица» стремится оптимизировать производственные расходы, снизив потребление электроэнергии на этапе обработки стали. Для этого необходимо контролировать температуру сплава — ключевой параметр технологического процесса.

В рамках проекта требуется построить модель машинного обучения, которая будет предсказывать температуру сплава на основе технологических данных. Разработанная модель позволит имитировать процесс и оптимизировать производственные условия.

## Используемые технологии и библиотеки

- Python  
- pandas, numpy, matplotlib, seaborn, scipy, math  
- Модели машинного обучения:  
  - Линейная регрессия и Ridge-регрессия (sklearn.linear_model)  
  - Деревья решений и случайный лес (sklearn.tree, sklearn.ensemble)  
  - Градиентный бустинг: XGBoost (xgboost), LightGBM (lightgbm), CatBoost (catboost)  
- Предобработка и подготовка данных:  
  - sklearn.preprocessing (OneHotEncoder, OrdinalEncoder, StandardScaler и др.)  
  - sklearn.impute (SimpleImputer)  
  - sklearn.pipeline и ColumnTransformer  
- Модельная валидация и оптимизация:  
  - train_test_split, cross_val_score  
  - GridSearchCV, RandomizedSearchCV  
- Метрики качества: mean_absolute_error

## Этапы работы

1. Анализ и изучение данных  
2. Генерация новых признаков с учётом технологического процесса  
3. Обработка пропусков и кодирование категориальных признаков  
4. Масштабирование признаков  
5. Обучение и настройка моделей машинного обучения  
6. Оценка качества моделей и выбор лучшей для прогноза температуры  

## Результаты

- Разработана модель, позволяющая точно предсказывать температуру сплава  
- Модель готова к использованию для имитации технологического процесса и оптимизации энергозатрат
