# Telecom-churn
Оператор связи хочет научиться прогнозировать отток клиентов. Если выяснится, что пользователь планирует уйти, ему будут предложены промокоды и специальные условия. Команда оператора собрала персональные данные о некоторых клиентах, информацию об их тарифах и договорах. 

* Проведено иследование данных в результате которого выяснилось, что клиенты массово стали уходить с определенного месяца, что может свидетельствовать о появлении сильной конкуренции. Также показаны статистики ушедших людей в зависимости от подключеных услуг.
* Проведена кластеризация данных по сумме платежей. Выделены три категории.
* Данные были подготовлены: проведена очистка от выбросов, заполнены пропуски, использовано z-преобразование для количественных признаков.
* Были обучены следующие модели : линейная регрессия, классификатор на основе метода опорных векторов, градиентный бустинг
* Модели получившие лучшие значения целевой метрики, были объеденены в ансамбль

Стек: Pandas, Numpy, Sklearn, Lightgbm, Catboost, Matplotlib, Seaborn.
