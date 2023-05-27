# Домашнее задание к занятию 12.2 "Работа с данными (DDL/DML) - Волков М.П."

Задание можно выполнить как в любом IDE, так и в командной строке.

# Задание 1.

1.1 Поднимите чистый инстанс MySQL версии 8.0+. Можно использовать локальный сервер или контейнер Docker.

1.2 Создайте учетную запись sys_temp.

1.3 Выполните запрос на получение списка пользователей в Базе Данных. (скриншот)

1.4 Дайте все права для пользователя sys_temp.

1.5 Выполните запрос на получение списка прав для пользователя sys_temp. (скриншот)

1.6 Переподключитесь к базе данных от имени sys_temp.

Для смены типа аутентификации с sha2 используйте запрос:

ALTER USER 'sys_test'@'localhost' IDENTIFIED WITH mysql_native_password BY 'password';

1.6 По ссылке https://downloads.mysql.com/docs/sakila-db.zip скачайте дамп базы данных.

1.7 Восстановите дамп в базу данных.

1.8 При работе в IDE сформируйте ER-диаграмму получившейся базы данных. При работе в командной строке используйте команду для получения всех таблиц базы данных. (скриншот)

Результатом работы должны быть скриншоты обозначенных заданий, а так же "простыня" со всеми запросами.
___
**Ответ:**

Установил чистый инстанс MySQL версии 8.0+ и создав учетную запись sys_temp выполняю запрос на получение списка пользователей в Базе Данных. 

![](https://github.com/VolkovMixail/12.2/blob/main/img/01.png)

Даю все права для пользователя sys_temp и запрос на получение списка прав для пользователя sys_temp.

![](https://github.com/VolkovMixail/12.2/blob/main/img/2.png)

ALTER USER 'sys_temp'@'localhost' IDENTIFIED WITH mysql_native_password BY 'password';

![](https://github.com/VolkovMixail/12.2/blob/main/img/3.png)

По ссылке https://downloads.mysql.com/docs/sakila-db.zip скачал дамп базы данных и Восстановил дамп в базу данных.Sakila

![](https://github.com/VolkovMixail/12.2/blob/main/img/4.png)

![](https://github.com/VolkovMixail/12.2/blob/main/img/5.png)

ER-диаграмма получившихся баз данных и спользую команду для получения всех таблиц базы данных.

![](https://github.com/VolkovMixail/12.2/blob/main/img/6.png)
![](https://github.com/VolkovMixail/12.2/blob/main/img/7.png)

# Задание 2.
Составьте таблицу, используя любой текстовый редактор или Excel, в которой должно быть два столбца, в первом должны быть названия таблиц восстановленной базы, во втором названия первичных ключей этих таблиц. Пример: (скриншот / текст)

Название таблицы | Название первичного ключа
customer         | customer_id
___

**Ответ:**

![](https://github.com/VolkovMixail/12.2/blob/main/img/8.png)
