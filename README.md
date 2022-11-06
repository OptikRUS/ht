# Real estate calculation
Приложение пасчёта эталона по аналогу, расчёт пула по эталону, отображение аналогов на карте, возможность корректировки стоимости 
в зависимости от параметром

[Техническое задание](https://github.com/OptikRUS/ht/blob/files/%D0%A2%D0%B5%D1%85%D0%BD%D0%B8%D1%87%D0%B5%D1%81%D0%BA%D0%BE%D0%B5%20%D0%B7%D0%B0%D0%B4%D0%B0%D0%BD%D0%B8%D0%B5.%20%D0%97%D0%B0%D0%B4%D0%B0%D1%87%D0%B0%2006.pdf)

## Техническая документация:
* Запуск проекта в docker: ```docker-compose up```
* Документация ендпоинтов(backend): ```http://0.0.0.0:8000/docs```
* Страница приложения(frontend): ```http://0.0.0.0:3000```

* ### Основные модули приложения:
  * CianParser - класс запроса выборки с сайта cian.ru
  * PoolEstimate - класс расчёта аналогов и эталонов
  * `/analog` и `/etalon` - ендпоинты для получения аналогов и эталонов

## Пользовательская документация:
