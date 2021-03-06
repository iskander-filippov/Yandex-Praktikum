# Итоговый проект по теме "Анализ бизнес-показателей"
# Оптимизация маркетинговых затрат в Яндекс.Афише
# Статус проекта - выполнен ✅


## Задача

На основе данных о посещениях сайта Яндекс.Афиши изучить, как люди пользуются продуктом, когда они начинают покупать, сколько денег приносит каждый клиент, когда он окупается


## Данные

В наличии были следующие данные:

- Информация о пользователях:

  - уникальный идентификатор пользователя,
  - категория устройства пользователя,
  - дата и время начала сессии,
  - дата и время окончания сессии,
  - идентификатор источника перехода на сайт

- Информация о заказах:

  - уникальный идентификатор пользователя,
  - дата и время заказа,
  - сумма заказа

- Информация о расходах на маркетинг:

  - идентификатор рекламного источника,
  - дата проведения рекламной кампании,
  - расходы на эту кампанию.


## Краткий общий вывод

Основываясь на LTV, самой перспективной когортой является когорта сентября 2017 года. После исследования ROMI по когортам мы можем добавить ещё несколько:

* когорты июня, июля 2017 года, а также когорта марта 2018 года из источника №1;
* когорты сентября и декабря 2017 года, а также май 2018 из источника №2;
* когорта ноября 2017 из источника №4 - несмотря на общую бесперспективность данного источника, эта когорта окупилась с первого месяца жизни;
* когорта июня из источника №5;
* когорта августа 2017 из источника №9;
* мартовская и майская когорта из источника №10 - окупились с первого месяца, несмотря на общую неприбыльность источника.


## Используемые библиотеки
*pandas*, *matplotlib*, *seaborn*


## Компетенции
Визуализация данных, когортный анализ, юнит-экономика, продуктовые метрики


[Посмотреть проект в Jupyter NBViewer](https://nbviewer.jupyter.org/github/iskander-filippov/Yandex-Praktikum/blob/main/06_business_metrics_analysis/afisha_optimization.ipynb)
