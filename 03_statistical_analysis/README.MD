# Итоговый проект по теме "Статистический анализ данных"
# Определение перспективного тарифа для телеком компании
# Статус проекта - выполнен ✅


## Задача

На основе данных клиентов оператора сотовой связи проанализировать поведение клиентов и поиск оптимального тарифа


## Данные

В наличии были следующие данные об использовании услуг мобильной связи:

- Информация о пользователях

  - уникальный идентификатор пользователя
  - имя пользователя
  - фамилия пользователя
  - возраст пользователя
  - дата подключения тарифа
  - дата прекращения пользования тарифом
  - город проживания пользователя
  - название тарифного плана

- Информация о звонках:

  - уникальный номер звонка
  - дата звонка
  - длительность звонка в минутах
  - идентификатор пользователя, сделавшего звонок

- Информация о сообщениях:

  - уникальный номер сообщения
  - дата сообщения
  - идентификатор пользователя, отправившего сообщение

- Информация об интернет-сессиях:

  - уникальный номер сессии
  - объём потраченного за сессию интернет-трафика (в мегабайтах)
  - дата интернет-сессии
  - идентификатор пользователя

- Информация о тарифах:

  - название тарифа
  - ежемесячная абонентская плата в рублях
  - количество минут разговора в месяц, включённых в абонентскую плату
  - количество сообщений в месяц, включённых в абонентскую плату
  - объём интернет-трафика, включённого в абонентскую плату (в мегабайтах)
  - стоимость минуты разговора сверх тарифного пакета
  - стоимость отправки сообщения сверх тарифного пакета
  - стоимость дополнительного гигабайта интернет-трафика сверх тарифного пакета


## Краткий общий вывод

Для бизнеса предпочтительнее тариф №2, т.к. средняя выручка по данному тарифу на 68,1% выше, чем по тарифу №1


## Используемые библиотеки
*pandas*, *matplotlib*, *numpy*, *scipy*


## Компетенции
Предобработка данных, визуализация данных, исследовательский анализ данных, описательная статистика, проверка статистических гипотез


[Посмотреть проект в Jupyter NBViewer](https://nbviewer.jupyter.org/github/iskander-filippov/Yandex-Praktikum/blob/main/03_statistical_analysis/perspective_telecom_tariff.ipynb)
