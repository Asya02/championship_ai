# Решение задач, предложенных в рамках чемпионатов проекта Цифровой Прорыв 2022


## Описание проектов

| **Тема проекта** | **Задача** | **Используемые библиотеки и модули** | **Метрика** | **Результат на привате** |
|----:|:----:|:----:|:----:|:----:|
| Разработка модели для поиска музейных экспонатов | Задача - разработать модель, которая будет по текстовому описанию музейного экспоната определять, какая фотография из базы данных ему соответствует, что в дальнейшем позволит создавать выборки предметов по более гибким параметрам поиска. Условия: Для того, чтобы метрика отработала корректно, значения в присланных ответах должны: - Не повторяться- Не включать в себя индексы изображений из папки train| pandas, numpy, seaborn, os, re, string, nltk, stopwords, WordNetLemmatizer, ngrams, pymorphy2, train_test_split, sklearn, LGBMRegressor, TfidfVectorizer, Normalizer, hstack, LGBMRegressor, CatBoostRegressor, GridSearchCV | R2 |  |
| Прогнозирование статуса студента | Задача - предсказать будущий потенциальный статус студента на основе данных нескольких тысяч студентов. Такая прогнозная модель может стать хорошим инструментом при планировании учебной работы в вузах, взаимодействии с работодателями или реализации научных проектов. | pandas, seaborn, matplotlib, plotly, statistics, sklearn, train_test_split, cross_val_score, tree, numpy, f1_score, compute_class_weight, CatBoostClassifier | F1 |  |
