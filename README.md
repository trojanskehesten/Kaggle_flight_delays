# Kaggle_flight_delays

[Kaggle competition](https://www.kaggle.com/c/flight-delays-2017) of flight delays prediction.

Удалось побить benchmark. Максимальное значение ROC AUC на тесте 0.73672 соответствует 19 месту из 211 (Top 9.0%).

В алгоритме используется комбинация XGBoost и CatBoost, которые настроенны на данных с OneHotEncoder и "Code Mean" соответственно. Исходные данные преобразованы, добавлены новые признаки. Логистическая регрессия не показала высокого результата.
