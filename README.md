# Домашнее задание к занятию 11-2 «Кеширование Redis/memcached» - Ситкарёв Сергей

## Задание 1. Кеширование

### Приведите примеры проблем, которые может решить кеширование. Приведите ответ в свободной форме.

1) Повышение производительности
2) Увеличение скорости ответа
3) Экономия ресурсов БД
4) Сглаживание бустов траффика (резкое увеличение кол-ва запросов)

## Задание 2. Memcached

### Установите и запустите memcached. Приведите скриншот systemctl status memcached, где будет видно, что memcached запущен.

![Скриншот 2](https://github.com/SSitkarev/11-2/blob/main/img/2.jpg)

## Задание 3. Удаление по TTL в Memcached

### Запишите в memcached несколько ключей с любыми именами и значениями, для которых выставлен TTL 5. Приведите скриншот, на котором видно, что спустя 5 секунд ключи удалились из базы.

![Скриншот 3](https://github.com/SSitkarev/11-2/blob/main/img/3.jpg)

## Задание 4. Запись данных в Redis

### Запишите в Redis несколько ключей с любыми именами и значениями. Через redis-cli достаньте все записанные ключи и значения из базы, приведите скриншот этой операции.

![Скриншот 4](https://github.com/SSitkarev/11-2/blob/main/img/4.jpg)