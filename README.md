# Проект Мастерской Яндекс Практикума - Информационная безопасность

---
### Описание:
Компания онлайн-сервис с высоким уровнем входящего трафика имеет специализированный отдел безопасности, который занимается фильтрацией и анализом трафика. Сотрудники этого отдела обратились за помощью в автоматизации выявления аномального и злонамеренного трафика. Ваша задача - разработать модель, которая будет классифицировать трафик на нормальный и злонамеренный, включая следующие типы атак: DDoS, SQL-инъекции, брутфорс, вредоносные программы и т.д.

Задача\
🔸 Разработать модель, которая будет классифицировать трафик на нормальный и злонамеренный. При этом модель должна работать максимально качественно, так как цена ошибки может быть очень высока.\
🔸 Оценить качество модели по различным метрикам классификации: precision, recall, f1_score, accuracy.\
🔸 (*) Деплой: разработать REST API сервис, который будет принимать на вход данные трафика и возвращать класс этого трафика.\

Этапы работы:\
🔸 загрузка и ознакомление с данными,\
🔸 предварительная обработка,\
🔸 полноценный разведочный анализ,\
🔸 разработка новых синтетических признаков,\
🔸 проверка на мультиколлинеарность,\
🔸 отбор финального набора обучающих признаков,\
🔸 выбор и обучение моделей,\
🔸 итоговая оценка качества предсказания лучшей модели,\
🔸 анализ важности ее признаков.


### Технологии DS:

- :point_right: python, 
- :point_right: pandas, 
- :point_right: xgboost, 
