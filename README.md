# Домашнее задание к занятию "`Кеширование Redis/memcached`" - `Латыпов Данияр`

   
### Дополнительные материалы, которые могут быть полезны для выполнения задания

1. [Руководство по оформлению Markdown файлов](https://gist.github.com/Jekins/2bf2d0638163f1294637#Code)

---

### Задание 1  Кеширование

Приведите примеры проблем, которые может решить кеширование.

Приведите ответ в свободной форме.

---

### Ответ 1

Проблемы, решаемые кешированием:

1) Повышение производительности достигается за счет складывания в кэш данных, к которым чаще всего происходит обращение;

2) Увеличение скорости ответа;

3) Экономия ресурсов базы данных, например, применяя кэширование тяжелых запросов;

4) Сглаживание бустов трафика.

---

### Задание 2 Memcached

Установите и запустите memcached.

Приведите скриншот systemctl status memcached, где будет видно, что memcached запущен.

---
### Решение 2


![Снимок экрана 2024-06-10 210419](https://github.com/ka3-14bara/11-02-sdb/assets/142439642/e398d481-f1bf-4be8-bd54-df66f68ba701)

---

### Задание 3 Удаление по TTL в Memcached

Запишите в memcached несколько ключей с любыми именами и значениями, для которых выставлен TTL 5.

Приведите скриншот, на котором видно, что спустя 5 секунд ключи удалились из базы.

---

### Решение 3

![Снимок экрана 2024-06-10 213643](https://github.com/ka3-14bara/11-02-sdb/assets/142439642/fc9b64c0-e1ec-44d0-9db4-aef388592f7f)

---

### Задание 4  Запись данных в Redis

Запишите в Redis несколько ключей с любыми именами и значениями.

Через redis-cli достаньте все записанные ключи и значения из базы, приведите скриншот этой операции.

---

### Решение 4

![Снимок экрана 2024-06-10 215557](https://github.com/ka3-14bara/11-02-sdb/assets/142439642/58a9542d-5a54-4673-a2fd-406ed99bffa4)

---

### Задание 5  Работа с числами

Запишите в Redis ключ key5 со значением типа "int" равным числу 5. Увеличьте его на 5, чтобы в итоге в значении лежало число 10.

Приведите скриншот, где будут проделаны все операции и будет видно, что значение key5 стало равно 10.

---

### Решение 5

![Снимок экрана 2024-06-10 215809](https://github.com/ka3-14bara/11-02-sdb/assets/142439642/34a097ce-ee41-44a8-a1cd-079c11244950)

---
