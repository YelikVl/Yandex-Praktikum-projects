# Предсказание спроса на услуги такси
## Цели проекта
Спрогнозировать количество заказов такси на следующий час.
Построить модель для такого предсказания.
Значение метрики RMSE на тестовой выборке должно быть не больше 48.
## Задачи проекта
Предобработка данных
Анализ данных. Определение тренда, сезонности, остатков
Обучение и тестирование моделей.
Признаками модели являются:
- среднее по скользящему окну
- отстающие значения
- календарные признаки: выходной - да/нет, день недели
## Используемые библиотеки
pandas
numpy
sklearn
statsmodels
matplotlib
seaborn
