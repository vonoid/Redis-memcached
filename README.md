

### Задание 1  Кеширование
Приведите примеры проблем, которые может решить кеширование.

Приведите ответ в свободной форме.

### Ответ 1
Кеширование с помощью Redis или Memcached помогает приложениям работать быстрее. Это уменьшает нагрузку на базу данных и сокращает время, которое требуется для ответа на запросы.

Пример:
Частые запросы к редко меняющимся данным (справочники, настройки системы) замедлят работу увеличивая время отклика на запрос.
Кеширование таких данных избавляет от лишних запросов к БД.

Формирование отчетов может значительно замедлить работу базы данных, при выполнении кеширования можно в кеше хранить готовые результаты.

---

### Задание 2 Установите и запустите memcached.


Скриншот запущенного memcached
![memcached](https://github.com/vonoid/Redis-memcached/blob/6b401244a20c2876e686765437828ea5bab59dc1/img/2.jpg)


---

### Задание 3 Удаление по TTL в Memcached

Запишите в memcached несколько ключей с любыми именами и значениями, для которых выставлен TTL 5.

Скриншот, на котором видно, что спустя 5 секунд ключи удалились из базы:

![Del_TTL](https://github.com/vonoid/Redis-memcached/blob/6b401244a20c2876e686765437828ea5bab59dc1/img/3.jpg)

---

### Задание 4 Запись данных в Redis

Запись и вывод данных Redis
![Redis](https://github.com/vonoid/Redis-memcached/blob/f79de27e97de8435d1db1870223c96af22d2c42e/img/4.jpg)
