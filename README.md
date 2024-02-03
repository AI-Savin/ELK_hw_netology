# Домашнее задание к занятию «ELK» - `Савин Алексей`

### Задание 1. Elasticsearch
Установите и запустите Elasticsearch, после чего поменяйте параметр cluster_name на случайный.  
Приведите скриншот команды `curl -X GET 'localhost:9200/_cluster/health?pretty'`, сделанной на сервере с установленным Elasticsearch. Где будет виден нестандартный cluster_name.  

### Решение 1  
- Скриншот с командой и результатом ее выполнения
 
![Elasticsearch](https://github.com/AI-Savin/ELK_hw_netology/blob/main/img/elastic.png)  

---

### Задание 2. Kibana
Установите и запустите Kibana.  
Приведите скриншот интерфейса Kibana на странице http://<ip вашего сервера>:5601/app/dev_tools#/console, где будет выполнен запрос `GET /_cluster/health?pretty`.  

### Решение 2 

- Скриншот интерфейса Kibana  
   
![kibana](https://github.com/AI-Savin/ELK_hw_netology/blob/main/img/kibana.png) 

---

### Задание 3. Logstash
Установите и запустите Logstash и Nginx. С помощью Logstash отправьте access-лог Nginx в Elasticsearch.  
Приведите скриншот интерфейса Kibana, на котором видны логи Nginx.  

### Решение 3  

- Скриншот настройки Logstash
  
![Logstash_1](https://github.com/AI-Savin/ELK_hw_netology/blob/main/img/Logstash_1.png)  


- Скриншот интерфейса Kibana  

![Logstash](https://github.com/AI-Savin/ELK_hw_netology/blob/main/img/Logstash.png)  

---

### Задание 4. Filebeat.
Установите и запустите Filebeat. Переключите поставку логов Nginx с Logstash на Filebeat.  
Приведите скриншот интерфейса Kibana, на котором видны логи Nginx, которые были отправлены через Filebeat.  

### Решение 4

- Скриншот настройки Logstash

![Task_4_1](https://github.com/AI-Savin/ELK_hw_netology/blob/main/img/Task_4_1.png)  

- Скриншот интерфейса Kibana

  ![Task_4](https://github.com/AI-Savin/ELK_hw_netology/blob/main/img/Task_4.png)  
