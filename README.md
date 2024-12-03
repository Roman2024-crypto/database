# Домашнее задание к занятию "`База данных`" - `Козырев Роман`


### Задание 1. Elasticsearch

Легенда
Заказчик передал вам https://github.com/netology-code/sdb-homeworks/blob/main/resources/hw-12-1.xlsx, в котором сформирован отчёт.

На основе этого отчёта нужно выполнить следующие задания.

Задание 1
Опишите не менее семи таблиц, из которых состоит база данных:

какие данные хранятся в этих таблицах;
какой тип данных у столбцов в этих таблицах, если данные хранятся в PostgreSQL.
Приведите решение к следующему виду:

Сотрудники (

идентификатор, первичный ключ, serial,
фамилия varchar(50),
...
идентификатор структурного подразделения, внешний ключ, integer).


### Решение 1.

![image](https://github.com/user-attachments/assets/334f13cb-89ce-4241-96d3-3aaa53dc63ef)



### Задание 2. Kibana

Установите и запустите Kibana.

Приведите скриншот интерфейса Kibana на странице http://<ip вашего сервера>:5601/app/dev_tools#/console, где будет выполнен запрос GET /_cluster/health?pretty.


### Решение 2

![image](https://github.com/user-attachments/assets/a67a4614-4105-40c2-bd65-2e44d6b50d58)



### Задание 3. Logstash

Установите и запустите Logstash и Nginx. С помощью Logstash отправьте access-лог Nginx в Elasticsearch.

Приведите скриншот интерфейса Kibana, на котором видны логи Nginx.

### Решение 3

![image](https://github.com/user-attachments/assets/404e3182-4e09-4971-ba3e-a0cd1f1c9b69)


### Задание 4. Filebeat

Установите и запустите Filebeat. Переключите поставку логов Nginx с Logstash на Filebeat.

Приведите скриншот интерфейса Kibana, на котором видны логи Nginx, которые были отправлены через Filebeat.


### Решение 4

![image](https://github.com/user-attachments/assets/4eaf7bbc-f505-4205-9432-63921e167847)

![image](https://github.com/user-attachments/assets/93cc88ec-29c6-4f19-b42f-c80703b8a899)
