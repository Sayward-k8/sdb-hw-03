## Домашнее задание к занятию «`ELK`» - ` Игонин В.А.`

# Задание 1. Elasticsearch
Установите и запустите Elasticsearch, после чего поменяйте параметр cluster_name на случайный.

Приведите скриншот команды 'curl -X GET 'localhost:9200/_cluster/health?pretty', сделанной на сервере с установленным Elasticsearch. Где будет виден нестандартный cluster_name.

# Решение 1

<details>

![alt text](https://github.com/Sayward-k8/sdb-hw-03/blob/main/img/1.1.png)

</details> 

# Задание 2. Kibana
Установите и запустите Kibana.

Приведите скриншот интерфейса Kibana на странице http://<ip вашего сервера>:5601/app/dev_tools#/console, где будет выполнен запрос GET /_cluster/health?pretty.

# Решение 2

<details>

  ![alt text](https://github.com/Sayward-k8/sdb-hw-03/blob/main/img/2.png)

</details> 

# Задание 3. Logstash
Установите и запустите Logstash и Nginx. С помощью Logstash отправьте access-лог Nginx в Elasticsearch.

Приведите скриншот интерфейса Kibana, на котором видны логи Nginx.

# Решение 3

<details>

  ![alt text](https://github.com/Sayward-k8/sdb-hw-03/blob/main/img/3.1.png)

</details> 

# Задание 4. Filebeat.
Установите и запустите Filebeat. Переключите поставку логов Nginx с Logstash на Filebeat.

Приведите скриншот интерфейса Kibana, на котором видны логи Nginx, которые были отправлены через Filebeat.

# Решение 4

<details>

  ![alt text](https://github.com/Sayward-k8/sdb-hw-03/blob/main/img/4.png)
  
</details> 


# Решение 5

<details>

</details> 
